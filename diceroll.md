# The Script Warnings

*When You First Click the Dice Roll Button*

## TL;DR

Google Sheets shows warnings when my script is first used to confirm trust. In our case, my script records the dice log. I am trustworthy. Please enable the diceRoll script once by following and accepting each prompt.


## Details

The first time you click the Roll button, Google displays one or more prompts asking you to confirm whether you want to proceed and allow an unknown, unverified script to run in your Google Sheet. The warnings are written as though the sky is falling, which is entirely intentional and justified when loading 3rd-party scripts from unknown sources. Most spreadsheets aren't automated and don't attempt to load scripts. 

What you’re encountering is Google’s OAuth app verification consent screen. The warnings you’re seeing (“This app isn’t verified,” “Google hasn’t reviewed this app”) appear because any Apps Script project that requests permissions (such as reading or writing your Sheet) is technically an unverified OAuth app (requesting authentication). Once a script is verified, an untrustworthy actor could abuse this privileged access to fully control and read your Sheet. 

## Authorizing

For a personal group-use script like this, where you know who wrote it (me — Zachary) and why (to generate random numbers, change the dice glyphs, and write a result log to the Sheet), you don't need real verification — you just need to get past the warning once. 

Here's how:

1. When you click the "Roll" button for the first time and the "Google hasn't verified this app" screen appears, click Advanced (small text, easy to miss, usually at the bottom-left of the dialog).
2. Click Go to [Your Project Name] (unsafe).
3. Grant the requested permissions (edit access to the spreadsheet, etc.). 

Soldier on! The warnings sound very grim to scare you into making sure you know what you're doing. 

That's it — this only needs to happen once per Google account, the first time that script is authorized. After that, it runs silently in the background without re-prompting because the authorization is now cached.

## What’s Going On

Why it's not actually "unsafe" in our case: the warning exists because the code could do anything with the permissions you grant (read your files, send data elsewhere), so Google flags anything outside their reviewed app directory. Since you wrote the script yourself and it only touches this one spreadsheet, this is the exact scenario the warning doesn't apply to — you're the author, not an untrusted third party.

Each of you will see this warning the first time you run the script under your own Google account — I can't "pre-clear" it on your behalf. It's a one-time click-through per person, not per session.

## What About Using the RANDBETWEEN() Function?

Sure, a Sheet has a built-in random number generator—it can easily approximate a die roll. But you need more to do any whiz-bang stuff. A Sheet formula won’t suffice. These randomly generated numbers from functions are volatile—the function recalculates anywhere in the sheet and has no “memory.” And you couldn’t then just create a personal set of rollers for each individual character sheet. You can’t get a consistent “last 10 rolls” log that appends the newest and deletes the oldest when it hits that limit. 

If you try to store the results in history, they will be cleared every time a new roll is requested. That is our exact design goal — a shared dice roller — so multiple hits on one set of dice controls and a log are required. A Google Sheets script can do all this: compute the roll once, write it to a cell, and shift the log range, all while another roll is requested.

## Google Verification?

Formal verification is possible via Google Cloud Console (by creating a proper OAuth consent screen and submitting it for Google’s code review), but that’s intended for public-facing apps distributed to strangers. Until (or if) I publish this, Google Sheet-based dice rollers aren’t common in our RPG space. I found only one comprehensive example on a now-defunct website, and it appeared to have bugs.

Regardless, the Google verification process for bypassing the multiple draconian authorization prompts is cumbersome. It requires publishing a privacy policy URL, a scope justification, and sometimes a security review. For a private script that six friends run once, it'd be considerably more setup than it's worth.