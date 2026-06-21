# A D&D Player's Guide to PSIOPS

*Moving from a d20 to 2d6.*

## TL;DR

The [*PSIOPS* role‑playing game](https://joemoose.github.io/PSIOPS/) comes from a different design lineage than Dungeons & Dragons and draws inspiration from *[Powered by the Apocalypse](https://www.lumpley.games/2023/11/22/what-is-pbta/)* and *[Blades in the Dark](https://www.bladesinthedark.com)*.

That means:

- **2d6** dice rolls instead of **d20**
- Tiered outcomes rather than pass/fail
- No classes, levels, or experience points
- Lethal in a way modern D&D typically isn't

Details follow.

## How to Use This Primer

You already know how to play tabletop role-playing games. Perhaps you've run a game (I hope so; it's a blast). That experience is an asset, but some assumptions about how these games work may not apply in *PSIOPS*, especially if you come from a modern Dungeons & Dragons background.

This primer isn’t a complete rules reference; the *[PSIOPS Field Manual](https://joemoose.github.io/PSIOPS/)* provides that. Instead, it offers an overview of how *PSIOPS* differs from D&D and helps you remap your assumptions. Read this primer to orient yourself and become familiar with the key elements before reading the rule manual and playing your first game session.

## Part 1: Habits to Leave Behind

Many Dungeons & Dragons conventions don’t apply to *PSIOPS*. Details on each difference appear in the following sections. 

| D&D | PSIOPS |
| --- | --- |
| What’s the **DC**? What do I need to roll? | There are **no Difficulty Class (DC)** modifiers to the target number for die rolls. The likelihood of success is adjusted by applying advantage or disadvantage to the roll, not by changing the target number. |
| Advantage means roll two d20. | *Advantage* means roll 3d6 and drop the **lowest** die. *Disadvantage* means roll 3d6 and drop the **highest** die. |
| I rolled a 14. Do I hit? | Outcomes come in **four tiers**: *failure*, *partial success*, *success*, and *critical success*, rather than **two tiers** of *hit* or *miss*. |
| I missed, so nothing happens. | A **failure always makes things worse** by introducing an unwanted consequence. |
| Better armor means I'm harder to hit. | Armor **reduces damage after you're hit**. It doesn’t make you harder to hit. |
| The DM rolls the monster's attack against my AC. | When you're attacked, **you roll to defend**. The GM rarely rolls dice at all; players roll **both** attack and defense. |
| Roll initiative — we go in order. | Initiative is rolled **once**. It only determines whether you can take a turn in the first round of combat. After that, you and your team members always go first. |
| I move 30 feet — count the squares. | No grid, no feet. You **move between tactical zones** during combat. |
| I’ll cast a spell — which slot? | No spell slots, spell levels, or daily preparation. You start with **two fixed powers**. |
| We all pile damage onto the boss. | Against a single target, **only the highest single hit counts.** |
| Let's take a long rest to heal up. | Healing is limited to falling back to a *rally point* **once** per mission. |
| My character will level up to 5th soon. | **No levels, no XP.** Advancement is an upgrade to one ability in your build, earned between missions at base. It's earned through roleplay, not XP. |

## Part 2: 2d6 and the *Partial Success*

The core task-resolution system in *PSIOPS* uses **2d6** and *tiered outcomes*, whereas Dungeons & Dragons uses a **d20** and *pass*/*fail*. This is the most significant change from D&D.

### The Dice Roll

 `2d6 + an attribute score`.

 That's the entire task-resolution mechanic.

### The Tiered Outcomes

Four outcomes of a **2d6 + Attribute** roll underlie nearly every rule in *PSIOPS*:

- **6 or lower**: *Failure*. You don't get what you wanted, and **something else** goes wrong.
- **7–9**: *Partial Success*. You get what you wanted, **but with a complication**.
- **10–12**: *Success*. You get what you wanted.
- **13+**: *Critical Success*. You get **better** than expected.

### Probability Feels Different

**2d6** rolls produce a bell-shaped curve centered on **7**, unlike the flat **d20**. As a result, rolls cluster around the middle (*partial success*), and your **attribute scores matter tremendously**.

### Here Are the Probabilities

For fellow dice-math geeks, here's a **2d6** vs. **d20** probability comparison. If you're not one, skip this diagram.

![2d6 vs. d20 Probabilities](img/2d6-vs-d20.svg "2d6 vs. d20 Probabilities")

To keep the comparison fair, both systems start with the same base success rate (~40%), so the chart shows only how much each +1 shifts the probability:

- **2d6**: needing 8+ (41.7%)
- **d20**: needing 13+ (40%)

On the d20, every +1 is worth a flat 5 percentage points. On 2d6, the same +1 is worth far more in the middle of the curve: +16.7, then +13.9, then +11.1 points. At +3, 2d6 succeeds 83% of the time, compared to the d20's 55%, even though both start at nearly the same percentage.

**Takeaway**: In a 2d6 system, modifiers swing outcomes dramatically.

### Advantage and Disadvantage

The terms *advantage* and *disadvantage* are borrowed from Dungeons & Dragons, but their implementation differs.

- **Advantage**: Roll **3d6**, drop the lowest.
- **Disadvantage**: Roll **3d6**, drop the highest.

They don't stack. Multiple advantages may simply mean “you succeed without rolling.”

### 7–9 *Partial Success* Is the Core of Task Resolution

Dungeons & Dragons does not build partial successes directly into its core resolution mechanic. D&D rolls are *success* or *failure*. In *PSIOPS*, the most common result is “you succeed, but…”, a *partial success*. Expect partial successes and lean into the complications (the “but…”); they drive the story.

### There Are No Target Numbers

In Dungeons & Dragons, difficult tasks are often assigned a *difficulty class* (DC). *PSIOPS* has no DC and instead determines difficulty through *fictional positioning*, which means the descriptions of the challenge you're facing and the approach you describe to overcome it.

These circumstances may grant an *advantage* or impose a *disadvantage* on your roll, shifting the odds toward higher or lower results, but the number ranges for *failure* (6–), *partial success* (7–9), *success* (10–12), and *critical success* (13+) remain unchanged.

## Part 3: Building an Operator (vs. Building a PC)

You'll use almost none of the Dungeons & Dragons character-creation approach.

### Four Attributes, Not Six

*PSIOPS* characters have four attributes: STRENGTH, REFLEXES, TACTICS, and WILLPOWER.

- There's no CON attribute (durability is covered by STRENGTH and HP).
- INT and WIS collapse into TACTICS (training, situational awareness).
- WILLPOWER covers presence (CHA) and resolve. It's the “casting stat” for your powers.

### A Limited, Assigned Array of Attribute Scores

Distribute **2**, **1**, **0**, and **-1** among the four attributes. No 4d6-drop-lowest rolls, no point buy, no 3–18 range.

- **The score *is* the modifier.** An attribute score of **2** means you add **+2** to the roll. Negative modifiers are normal and acceptable. The ceiling, reachable only through advancement, is **3**.
- **The “applicable attribute” for a roll** depends on how you narrate your action. This is genuinely different. The same task can be resolved with different attributes. Consider an attack: STRENGTH for kicking the door and blasting, REFLEXES for sliding into cover and firing, TACTICS for flanking through a window, or WILLPOWER for baiting an enemy. You describe it; the GM then agrees or redirects.
	- **Exception**: Some rolls have a **fixed** attribute by rule and a special name (for example, *initiative rolls* are always TACTICS, and *wound rolls* are always STRENGTH). Most of these fixed-attribute rolls are combat-related and are described in the rules manual.

### No Class. No Level. No XP.

Your starting character build includes your four *attributes*, 1 *core drive*, 2 *advanced specializations*, and 2 *neural weapons (powers)*. You assign your attribute scores, but you randomly select your core drive, advanced specializations, and powers.

#### Core Drive

Your *core drive* is a little like the Dungeons & Dragons Bond/Ideal/Flaw, fused with a character advancement threshold. It's a one-line motivation and the trigger for improving your character's abilities. You advance by playing to your drive — easing a conflict, getting revenge, or protecting someone — **not** by accumulating kills or XP.

### Advanced Specializations

Your *advanced specializations* are essentially your skills. They’re binary; you have them, or you don’t. They aren’t scored like skills in Dungeons & Dragons. There are no ranks or scaling proficiency bonuses. If one applies to your action, you add a flat **+1** bonus to the roll. The baseline assumption is that a trained operator can attempt almost anything. Advanced specializations improve your odds of success.

### Powers

In *PSIOPS*, your innate powers or “spells” are called *neural weapons*. We'll discuss these later, in [Part 8](#part-8-magic-without-spell-slots-powers).

### Character Advancement Is One Ability at a Time

After a mission where you satisfied your *core drive*, you'll choose one character improvement: increase an attribute score, increase your maximum HP, randomly gain a new power, or learn a new advanced specialization applicable to things you did on the mission. There's no leveling table or class features you unlock.

## Part 4: Inventory is Abstract and Intentionally Limited

Tracking a character's inventory is another major difference between *PSIOPS* and Dungeons & Dragons.

D&D tracks inventory **by weight in pounds**. Every item has a listed weight, and your carrying capacity is your STRENGTH score × 15. Manually adding up individual weights is fiddly. Bookkeeping for large inventories is no fun, so it's often hand-waved (at least I do). Some groups might require a fighter with 15 STRENGTH to carry no more than 210 pounds of gear, probably using a spreadsheet. Regardless, it's a **ledger** listing equipment and treasure. You can keep adding items until the GM says the total is unreasonable or you reach your maximum weight by STRENGTH.

*PSIOPS* uses **12** abstract inventory slots. Most equipment takes **1** slot. Larger items or two-handed equipment, such as a rifle, take **2** slots. Body armor occupies **1–3** slots, depending on its level of damage reduction. Small items, such as grenades, can be **bundled** into **1** slot.

The inventory system intentionally constrains what you can carry on a mission, forcing trade-offs, decisions, and coordination among you and your fellow players. The abstracted integer values of **1** or **2** slots, to a max of **12**, streamline management. You're **choosing** what to carry rather than measuring whether you **can** carry it.

## Part 5: Combat Is a Different Beast

*PSIOPS* combat runs differently from Dungeons & Dragons.

### There Is No Armor Class; It Reduces Damage

Armor does not reduce your chance of being hit. Instead, when you’re hit, you **subtract** your armor rating from the damage. The total damage reduction from armor is capped at **3**. 

### The Attack Roll Is *Also* the Damage Roll

There is no separate damage roll or weapon damage die. The *attack roll* itself determines the resulting damage based on which outcome tier you roll:

- **6 or lower** (failure): no damage.
- **7–9** (partial success): The **lower** die + weapon modifier.
- **10–12** (success): The **higher** die + weapon modifier.
- **13+** (critical): The **sum** of both dice + weapon modifier.

Weapons have a flat **damage modifier** (-1, +0, +1, +2, +3, or +4), not a damage die. There is no *1d8 longsword*; instead, there is a *sidearm, +1 damage*.

### Defense Rolls

When an enemy attacks, *you* make a **defense roll**, **2d6 + an applicable attribute** to determine whether you take damage and how much. This inverts the Dungeons & Dragons table dynamic. In *PSIOPS*, the GM rolls no attack dice, and players roll their own defense.

### Initiative Is a One-Time Go/No-Go Result

Like Dungeons & Dragons, when combat breaks out, you roll for *initiative*: **2d6 + TACTICS**. But that's where the similarity ends. The initiative roll determines **whether you can act** in the first round. If you fail, you must wait until the **second round** to act. You're skipped in the first round.

Starting in the second round of combat, you and your team members **always** take the first turn. No further initiative rolls are made. This approach eliminates the need to re‑roll initiative each round while keeping initiative important and the first round tense.

### Your Squad Acts Simultaneously

There’s no initiative order that has all combatants take turns in sequence, one by one, during a round. Your squad’s actions and moves happen **all at once** on your turn. The opposing side’s actions and moves happen all at once on their turn.

You and the other players declare all actions and moves for the round **up front**, before any outcomes are known. You then resolve all declared actions and moves as a group. You can also **hold an action** with a trigger (“when the guard rounds the corner…”) to interrupt the enemy’s turn.

### Tactical Zones, Not a Grid

The battlefield consists of a handful of named *tactical zones* — your position, the opponent's position, the space between them, and other tactical positions and locations with distinct features. Think of zones as chunks of tactical spaces — rooms, hallways, rooftops, hilltops — not 5‑foot squares.

You take one move to enter an **adjacent zone**, regardless of its real-world size; difficult terrain costs two moves. Distance is measured in **hops** across zones: Close (0) / Nearby (1) / Far (2) / Distant (3) / Extreme (4+). Zones can be altered during combat: flip a table to split a zone or throw tear gas to make one hazardous.

### Weapon Ranges Result in Advantage, Disadvantage, or Impossible

Each weapon has an *optimal range* based on zone distance, granting *advantage* on attack rolls. Attacks outside that range may be made normally, with *disadvantage*, or may be *impossible*. An assault rifle suffers *disadvantage* at long range (3 zones), a sniper rifle is *impossible* at close range (same zone), and an SMG gains *advantage* at nearby range (1 zone).

If you’re accustomed to games that measure combat in grids, feet, or meters, this may feel strange at first. “A sniper rifle can shoot someone standing ten feet away in real life. Why not in *PSIOPS*?”

The question isn’t whether the rifle can fire, but whether it’s suited to that engagement range within *PSIOPS’* tactical model. In-game zones and ranges aren’t about real-world physics; they’re about giving each of your available weapons an in-game tactical niche that approximates how the weapon is used.

*PSIOPS* prioritizes tactical decisions and gameplay over combat simulation. Weapon ranges, zones, cover, and positioning are designed to create meaningful trade-offs rather than model real-world ballistics. The game favors fast-paced, cinematic action, grounded in abstractions that keep combat moving quickly at the game table.

### Ammo Is an Abstract Rating That Depletes on Failure

Small arms start with a **6** ammo rating. You lose **1** ammo on a *failed* attack. Successful attacks, regardless of outcome tier, don’t reduce ammo. No bullet counting required.

### New Combat Options to Learn

- **Cover**: Grants advantage on your *defense roll*. *Hard* cover adds damage reduction, and when you're behind *total* cover, you can't be targeted. Of course, you can't target enemies either. It's a tactical choice based on what's in a zone and on your declared actions and movement, not a static bonus for the position.
- **Interrupts**: A free attack available against pinned or retreating enemies who expose themselves to fire.
- **Suppressing fire**: No roll required and no damage. Instead, you pin everyone in a zone (friend and foe) and set up interrupt attacks.

### Damage From Multiple Attackers *Doesn't* Stack

If several team members attack the *same target*, only the **highest** damage result applies.

- **…except against a mob.** A crowd of weak enemies is run as **one stat block**, meaning a single target rather than many, with its armor and number of attacks scaling with its size. Damage removes members one-for-one, so multiple attackers all contribute their damage.

## Part 6: The “Action Movie” Systems: Momentum and Mission Clocks

These subsystems have no direct Dungeons & Dragons equivalent. Momentum buffs your combat actions and keeps the action flowing. Mission clocks track progress toward overcoming complex obstacles and serve as a countdown to impending threats.

### Momentum

Momentum is the game’s action‑movie currency, earned by succeeding on risky actions and spent to do something cool. You start each mission with **2** points and gain more on *success* or *critical success* rolls. You can then spend your accumulated momentum for immediate combat benefits on your turn, such as *advantage* on rolls or an extra *action*. The closest D&D equivalent to momentum is *inspiration*, but momentum offers more options and is always in play.

### Mission Clocks (aka Segmented Progress Trackers)

**Complex tasks** don’t resolve on a single roll. Instead, they fill a mission clock with 4, 6, or 8 segments across multiple actions. *Partial success* fills 1 segment, *success* fills 2, *critical success* fills 3, and *failure* removes 1 filled segment. When all segments on the mission clock are filled, the task is complete. 

**Threats** have their own mission clocks that count down on any *failed* roll. Once all segments are filled, the threat manifests. The closest Dungeons & Dragons equivalent is the 4e skill *challenge*.

## Part 7: A Side‑by‑Side Example Turn

Picture how your turn in combat can feel a little different.

---

**Dungeons & Dragons**

You wait for your initiative number to come up on the initiative track. The DM tells you the enemy's AC is 15; you have a +5 bonus and roll 12, so you hit. Then you roll a separate longsword d8 for damage. If the enemy falls, the next player on the initiative track can change their plan and attack another target. Otherwise, they pile on the same enemy. Further along the track, an enemy attacks you. The DM rolls to hit against your AC and a damage die while you sit still. When the round ends, everyone rolls initiative again, and the order resets.

---

***PSIOPS***

In *PSIOPS*, at the start of the round, your whole squad decides together what you're all doing this turn. You describe flanking through the office window and firing, so this is a TACTICS attack at one zone's distance, giving your SMG its optimal range and an advantage because you're firing into an adjacent zone. Another player describes blasting through the front door with a STRENGTH attack. Another provides overwatch and holds their REFLEXES attack in case an opponent survives the initial assault. You all then resolve your declared actions.

You roll 2d6 + TACTICS and land within the 7–9 *partial success* outcome tier, dealing the *lower* die plus your weapon modifier. Your team member makes their STRENGTH attack roll. Because both attacks target the same enemy in the office, only the higher damage result applies. However, you have a team member holding their action to interrupt any enemy’s turn if the enemy exposes themselves to attack during their turn.

After your squad’s actions and moves are resolved, your turn ends. It’s now the enemy’s turn. But you’ve got momentum saved; you spend it immediately to take another action, move into the office zone, and take cover.

When an enemy returns fire, *you* roll to defend from behind cover, gaining *advantage* from cover, and subtract your armor rating from any damage you take on a hit.

Welcome to the unit, operator.

---

Different rhythm, different rules, but both share tension, crossed fingers for a good roll, and the fun of tabletop role-playing.

## Part 8: Magic Without Spell Slots: Powers

Magic in *PSIOPS* works nothing like Vancian spellcasting.

You start with **two powers** (called *neural weapons* in *PSIOPS*), and those are your only “spells” unless you advance and choose to gain another. There's no spell list to choose from each morning, and no spell levels. You **can't choose** specific neural weapons when creating your character or when advancing your ability; they're chosen randomly.

### Activation Is a Roll, Not a Slot

Roll **2d6 + WILLPOWER** to activate (cast) your *neural weapon*:

- **6–**: It fails. You take **1** fatigue, and that power is locked out for the rest of the mission (until a *rally point*). Harsher than a failed Dungeons & Dragons check.
- **7–9**: It works, but you take **1** fatigue.
- **10–12**: It works.
- **13+**: It works, with an enhanced effect.

### Concentration Resembles Dungeons & Dragons, but Costs More

Many *neural weapons* persist only if you **spend an action each round** to maintain them, and taking damage breaks the effect. You can move freely without breaking concentration. Unlike D&D, the upkeep consumes your entire *action*, not a saving throw.

Neural weapons produce *tactical effects* (movement, control, damage that often bypasses armor, healing, buffs) rather than the breadth and utility of a Dungeons & Dragons spell list.

## Part 9: Damage, Wounds, Stress, and Recovery

Damage is grittier and can be more lethal than in modern Dungeons & Dragons.

### HP Is Limited

You start with a maximum of **6** HP, and it doesn’t automatically increase as you advance, unlike D&D’s HP pools. When you advance, you must specifically choose a **1d6** increase to your max HP rather than another type of improvement. Combat is dangerous for everyone, veterans and rookies alike.

### 0 HP Doesn't Mean Death; It Means a Wound Roll

When you drop to **0** HP or lower, you make a *wound roll*, **2d6 + STRENGTH**, then subtract the amount you are below zero.

- **6–**: Immediate death.
- **7–9**: Incapacitated.
- **10-12**: Knocked down and unconscious if not wearing a helmet.
- **13+**: Still on your feet, and you revive, recovering HP.

There are no “three-death-saves” as in Dungeons & Dragons.

### Wounds Are Lasting Injuries

Each wound **permanently reduces your max HP** until you’re treated at base after the mission. If multiple wounds reduce your max HP to **0**, you die. You can’t heal wounds in the field.

### Fatigue Is Stored as an Inventory Item

As you grow fatigued, you can carry less equipment. Each point of fatigue **occupies an inventory slot**, crowding out your gear. **12** fatigue (an inventory filled with fatigue) means death. This is unlike anything in Dungeons & Dragons.

### Stress Is a Sanity-Style Meter

Witnessing death, taking wounds, and especially encountering the paranormal add *stress*. Once your stress is maxed out, you make a *stress roll*, **2d6 + WILLPOWER**:

- **6–**: *Panicked*. A random debilitating condition strikes.
- **7–9**: You keep it together — for now.
- **10–12**: You keep it together and shake off **1** stress.
- **13+**: *Lock-in*. You clear all stress and gain a *combat buff*.

Maxing out your stress can be a **good** thing, creating tactical advantages. It’s a gamble. That’s the opposite of what a Dungeons & Dragons player might expect from an *overwhelmed* sanity track.

### Recovery Occurs Only at the Rally Point, Once Per Mission

Falling back to a *rally point* resets your momentum to its starting value of **2**, clears panicked and locked-in effects, and re-enables spent powers. You then choose **one** benefit (gain intel, recover HP, remove stress/fatigue, or resupply). Note the trade-off: clearing panicked conditions also removes any locked-in combat buffs. There is no per-day rest cycle or “adventuring day.”

## Part 10: Cheat Sheet

Here are some reminders.

### Universal Outcomes

Nearly every roll uses the same four **tiered outcomes**:

| Roll | Result |
| :-: | --- |
| 6– | Failure |
| 7–9 | Partial success |
| 10–12 | Success |
| 13+ | Critical success |

The number ranges are fixed, regardless of whether your task is made easier or more difficult by current circumstances.

### Common Gotchas

These rules are some of the most different between the two games:

- **7+** on **2d6** is the target for at least *partial success*, and there is no DC.
- *Advantage*: roll **3d6** and drop the **lowest** die.
- *Disadvantage*: roll **3d6** and drop the **highest** die.
- Armor **reduces** damage; it doesn't affect whether you're hit.
- **You roll** to defend yourself on the enemy's turn.
- The attack dice **are also** the damage dice.
- Roll *initiative* **once** to determine whether you can act in the first round. Afterward, you act first every round.
- Move to an adjacent *zone*; there are no movement rates or grids.
- A failed neural weapon roll can lock it out for the entire mission.
- You have **12** inventory slots, and each item typically occupies **1** or **2** slots.
- *Fatigue* occupies an inventory slot.
- Multiple attacks on one enemy are **not** cumulative (except against mobs).

## Final Thoughts

*PSIOPS* vs. Dungeons & Dragons. Both are distinct. Both are fun. Lean into the differences; you might just enjoy the change of style during your mission. Now move out, soldier!

## Postscript

If you’d like to delve deeper into minimalist indie RPG design, *[Principia Apocrypha](https://www.osr.camp/principia-apocrypha)* is a definitive resource. It’s an enjoyable read.
