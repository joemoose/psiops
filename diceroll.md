# The Script Warnings

*When You First Click the Dice Roll Button*

## TL;DR

Google Sheets shows warnings when my script is first used to confirm trust. In our case, my script records the dice log. I am trustworthy. Please enable the diceRoll script once by following and accepting each prompt.


## Details

The first time you click the Roll button, Google displays one or more prompts asking you to confirm whether you want to proceed and allow an unknown, unverified script to run in your Google Sheet. The warnings are written as though the sky is falling, which is entirely intentional and justified when loading 3rd-party scripts from unknown sources. Most spreadsheets aren't automated and don't attempt to load scripts. 

What you’re encountering is Google’s OAuth app verification consent screen. The warnings you’re seeing (“This app isn’t verified,” “Google hasn’t reviewed this app”) appear because any Apps Script project that requests permissions (such as reading or writing your Sheet) is technically an unverified OAuth app (requesting authentication). Once a script is verified, an untrustworthy actor could abuse this privileged access to fully control and read your Sheet. 

## Authorizing

For a personal group-use script like this, when you know who wrote it (me — Zachary) and why (to generate random numbers, change the dice glyphs, and write a result log to the Sheet), you don't need real verification — you just need to get past the warning once. 

Here's how:

1. When you click the "Roll" button for the first time and the "Google hasn't verified this app" screen appears, click Advanced (small text, easy to miss, usually at the bottom-left of the dialog).
2. Click Go to [Your Project Name] (unsafe).
3. Grant the requested permissions (edit access to the spreadsheet, etc.). 

Soldier on! The warnings sound very grim to scare you into making sure you know what you're doing. 

That's it — this only needs to happen once per Google account, the first time that script is authorized. After that, it runs silently in the background without re-prompting because the authorization is now cached.

## What’s Going On

Why it's not actually "unsafe" in our case: the warning exists because the code could do anything with the permissions you grant (read your Sheet, send data elsewhere), so Google flags anything outside their reviewed app directory. Since I wrote the script myself and it only touches this one spreadsheet, this is the exact scenario the warning doesn't apply to — I'm the author, not an untrusted third party. Not a bad actor. 

Each of you will see this warning the first time you run the script under your own Google account — I can't "pre-clear" it on your behalf. It's a one-time click-through per person, not per session.

## What About Using the RANDBETWEEN() Function?

Sure, a Sheet has a built-in random number generator—it can easily approximate a die roll. But you need more to do any whiz-bang stuff. A Sheet formula won't suffice. These randomly generated numbers from functions are volatile—the function recalculates anywhere in the sheet and has no "memory." You can't get a consistent "last 10 rolls" log that appends the newest and deletes the oldest when it hits that limit.

If you try to store the results in history, they will be cleared every time a new roll is requested. That is the opposite of our goal — a shared dice roller with one set of dice where everyone can see each other's results. You couldn't get around this by, say, creating a personal set of dice embedded on each individual character sheet with some roll formulas. Dice rolls created only with formulas, even if located in several places in the Sheet, would change every time, everywhere, whenever anyone clicked a roll. A Google Sheets script can get around all these limitations: compute a roll that isn't volatile and could immediately change in memory; write it to a cell; and shift the log range, all while another roll is requested.

## Google Verification?

Formal verification is possible via Google Cloud Console (by creating a proper OAuth consent screen and submitting it for Google’s code review), but that’s intended for public-facing apps distributed to strangers. Until (or if) I publish this, Google Sheet-based dice rollers aren’t common in our RPG space. I found only one comprehensive example on a now-defunct website, and it appeared to have bugs.

Regardless, the Google verification process for bypassing the multiple draconian authorization prompts is cumbersome. It requires publishing a privacy policy URL, a scope justification, and sometimes a security review. For a private script that five friends run once, it'd be considerably more setup than it's worth.

## Let’s See This Script

```
const DIE_FACES = ['⚀', '⚁', '⚂', '⚃', '⚄', '⚅'];

function faceFor(n) {
  return DIE_FACES[n - 1];
}

function rollDice() {
  const sheet = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('Dice');
  const character = sheet.getRange('C4').getValue();
  const dieType = sheet.getRange('C5').getValue();
  const modifier = Number(sheet.getRange('C6').getValue()) || 0;
  const advMode = sheet.getRange('C7').getValue();

  if (!character || !dieType) {
    SpreadsheetApp.getUi().alert('Select a character and die type first.');
    return;
  }

  let dieLabel = dieType;
  let detailText = '';
  let strikeRange = null; // [startIndex, endIndex] within detailText to gray out
  let total = 0;

  if (dieType === 'd3' || dieType === 'd6') {
    const sides = dieType === 'd3' ? 3 : 6;
    const result = roll(sides);
    total = result;
    detailText = faceFor(result);

  } else if (dieType === '2d6') {
    let dice, dropped = null;

    if (advMode === 'Advantage' || advMode === 'Disadvantage') {
      dice = [roll(6), roll(6), roll(6)].sort((a, b) => a - b);
      if (advMode === 'Advantage') {
        dropped = dice[0];
        total = dice + dice + modifier;
        dieLabel = '2d6 ADV';
      } else {
        dropped = dice[2];
        total = dice + dice + modifier;
        dieLabel = '2d6 DIS';
      }
    } else {
      dice = [roll(6), roll(6)];
      total = dice + dice + modifier;
      dieLabel = '2d6';
    }

    if (modifier !== 0) {
      dieLabel += (modifier > 0 ? ' +' : ' ') + modifier;
    }

    const faces = dice.map(faceFor);
    detailText = faces.join(' ');

    if (dropped !== null) {
      // each face is 1 character, separator is a single space (1 char)
      const droppedIndex = dice.indexOf(dropped);
      const offset = droppedIndex * 2; // (face + ' ') * index
      strikeRange = [offset, offset + 1];
    }

  } else if (dieType === 'd66') {
    const tens = roll(6), ones = roll(6);
    total = tens * 10 + ones;
    detailText = faceFor(tens) + ' ' + faceFor(ones);
    dieLabel = 'd66';
  }

  logRoll(sheet, character, dieLabel, detailText, total, strikeRange);
}

function roll(sides) {
  return Math.floor(Math.random() * sides) + 1;
}

function logRoll(sheet, character, dieLabel, detailText, total, strikeRange) {
  const startRow = 11;
  const numRows = 10;

  // Time, Character, Die — plain values (keeps Time sortable as a real timestamp)
  const mainRange = sheet.getRange(startRow, 2, numRows, 3);
  const mainValues = mainRange.getValues();
  for (let i = numRows - 1; i > 0; i--) mainValues[i] = mainValues[i - 1];
  mainValues[0] = [new Date(), character, dieLabel];
  mainRange.setValues(mainValues);

  // Detail — rich text, so the dropped die can be grayed out
  const detailRange = sheet.getRange(startRow, 5, numRows, 1);
  const detailRich = detailRange.getRichTextValues();
  for (let i = numRows - 1; i > 0; i--) detailRich[i] = detailRich[i - 1];
  let builder = SpreadsheetApp.newRichTextValue().setText(detailText);
  if (strikeRange) {
    builder = builder.setTextStyle(
      strikeRange[0], strikeRange[1],
      SpreadsheetApp.newTextStyle().setForegroundColor('#b7b7b7').build()
    );
  }
  detailRich[0] = [builder.build()];
  detailRange.setRichTextValues(detailRich);

  // Total — plain numeric value (stays sortable/summable)
  const totalRange = sheet.getRange(startRow, 6, numRows, 1);
  const totalValues = totalRange.getValues();
  for (let i = numRows - 1; i > 0; i--) totalValues[i] = totalValues[i - 1];
  totalValues[0] = [total];
  totalRange.setValues(totalValues);

  SpreadsheetApp.flush();
}
```

