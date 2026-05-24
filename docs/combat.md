# Combat

Combat is like any risky action: attacking requires an action check to deal damage, and defending requires an action check to avoid damage. Details follow.

## Combat Rounds

A *combat round* is 6 seconds of game time during which you can **move** and take **one action**, such as engaging a target or moving again. 

Complex actions lasting more than 6 seconds may require multiple rounds to determine their results. Minor actions, such as shouting, opening a door, or dropping an item, are free actions.

## Starting Combat

### Initiative Check

Whether you can take action in the first round of combat before the opposing force is decided by an *initiative check*. You and each member of your unit roll **2D6 + TACTICS** and apply the result. 

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | You **do not** act in the first round of combat. The hostiles get the drop on you. |
| **7–9** | You get the drop on the hostiles and act first, but you have a *disadvantage* on your next *action check*. |
| **10–12** | You get the drop on the hostiles and act first. |
| **13+** | You get the drop on the hostiles and act first. You also gain *advantage* on your next *action check*. |

</div>

After completing the initiative check, all members of your unit who are able will take their actions. Afterward, the opposing force takes its actions. The first round of combat is now complete.  

## Resolving Actions

In a round of combat, all your unit's actions occur **at the same time**. You and your team members declare **all** actions for the current round upfront, before any results are determined. Actions are not declared and then resolved one at a time. 

!!! note

	The GM will give you a general sense of what the hostiles are doing to help with planning your actions. 

### Subsequent Rounds

After the first round of combat, no further initiative checks are made. The engagement proceeds with your unit acting first, then the opposing force, and so on, round by round, until one side is eliminated or withdraws.

### Ambushes

Operational circumstances or careful planning can also determine which side acts first in combat. If you *ambush* the opposing force, your unit does not roll initiative and instead acts first, gaining *advantage* on all action checks. 

Afterward, combat proceeds as usual: your unit takes actions, then the opposing force takes actions. An ambush lets you take two consecutive rounds of combat before your opponent can respond. 

However, if the opposing force ambushes you, you will not make an initiative check; you simply cannot act in the first round of combat. In subsequent rounds, combat proceeds as usual.

### Interrupting Actions

You may hold an action and specify a trigger, for example, “I wait until the enemy rounds the corner.” When the trigger occurs, you act immediately, interrupting the target’s turn.

## Combat Modifiers

The effectiveness of your attacks is modified by weapon type, range, and tactical situations. See the following tables for situational modifiers. 

### Weapon Ranges

Depending on your weapon type and the range to your target, the resulting *action check* for your attack may be at an *advantage*, *disadvantage*, or *impossible*.

| Weapon | Close | Near | Far | Distant |
| - | :-: | :-: | :-: | :-: |
| **Assault rifle** | disadvantage | – | – |  impossible |
| **Close-quarters combat** | – | impossible |  impossible | impossible |
| **Heavy weapon** | impossible | disadvantage | – | – |
| **LMG** | impossible | – | disadvantage |  disadvantage |
| **Shotgun** | – | – | disadvantage |  impossible |
| **Sidearm** | – | – | disadvantage | impossible |
| **SMG** | – | advantage | disadvantage | impossible |
| **Sniper rifle** | impossible | disadvantage | advantage | – |
| **Thrown** | – | – |  impossible  |  impossible  |

### Tactical Decisions

The following tactical decisions also apply modifiers to your attacks.

- **Aiming**: When you take an *action* to aim at a target, attacks gain *advantage* until you take a different action that is not attacking that target.
- **Prone**: When attacking from a prone position, you have *advantage*. Attacks against a prone target have *disadvantage*.

## Attacking

When you **attack** a target to **deal damage**, roll **2D6 + Applicable Attribute** and apply the result. See [Choose an Applicable Attribute](playing.md#choose-an-applicable-attribute) to determine which attribute score to select.

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | The attack misses. You deal **no damage**. |
| **7–9** | You deal damage equal to the **lowest D6 roll** plus the weapon's **damage modifier**. |
| **10–12** | You deal damage equal to the **highest D6 roll** plus the weapon's **damage modifier**. |
| **13+** | You deal damage equal to the **sum of both dice** plus the weapon's **damage modifier**. |

</div>

### Multiple Attackers

If you and other team members attack the same opponent, determine the damage for each attack separately, but apply only the **highest value**. The damage from multiple attackers is not cumulative.

### Weapon Damage Modifiers

Apply the damage modifiers to your attacks as listed below.

| Weapon | Examples | Modifier |
| :- | :- | :-: |
| **Unarmed** | — | -1 |
| **Concealable** | boot knives, brass knuckles | +0 |
| **Light** | combat knives, sidearms | +1 |
| **Medium** | rifles, shotguns | +2 |
| **Heavy** | antiarmor missiles, sniper rifles | +3 |
| **Anomalous** | \[REDACTED\] | +4 |

#### Blast Damage

Attacks with the *blast* quality, such as explosives, can affect multiple targets in a close area. To determine the number of targets, roll **1D6 + the weapon’s damage modifier**. The result is the number of targets affected.

## Expending Ammunition

At the start of a mission, all your small arms are fully stocked with an *ammo rating* of **6**. 

Each time you attack, if your attack fails with an *action check* of **6 or lower**, mark off **1** point from the weapon's ammo rating. When your weapon's ammo rating reaches **0**, the weapon becomes unusable until you restock it with ammunition.

You can restock a weapon in several ways: carrying extra ammunition in your equipment, using *tactical supplies*, or restocking at a *rendezvous point*. Ammunition recovered during the mission will increase the *ammo rating* of one of your weapons by **1** point. See [Rest and Recovery](combat.md#rest-and-recovery).

## Defending

When you must **defend** against an attack and risk **taking damage**, roll **2D6 + Applicable Attribute** and apply the result. See [Choose an Applicable Attribute](playing.md#choose-an-applicable-attribute) to determine which attribute score to select.

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | You take **damage** equal to the **highest D6 result** plus the hostile's damage modifier. |
| **7–9** | You take **damage** equal to the **lowest D6 result** plus the hostile's damage modifier. |
| **10–12** | You take **no** damage. |
| **13+** | You take **no** damage, and your next *action roll* has *advantage*. |

</div>

## Damage, Wounds, and Dying

All damage you take is deducted from your current *hit points* total. After deducting the damage, if you have at least **1 HP** left, you’re still in the fight.

### Wounds

If your HP drops to **0 or lower**, you’re wounded, potentially grievously. Roll **2D6 + STRENGTH** and **subtract** the number of points you’ve gone below 0. Then consult the following Wounds table and apply the result.

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | You're **dead**. Roll up a new operator. |
| **7–9** | You're *incapacitated* at **0 HP**. Take **2** *injuries*, **2** points of *stress*, and **2** units of *fatigue*. You'll die unless stabilized. See the following section. |
| **10–12** | You’re down, stable at **1 HP**, but unconscious. Take **1** *injury*, **1** point of *stress*, and **1** unit of *fatigue*. Buddy aid can revive you with 1 action.<br/><br/>**Note**: If you have a helmet equipped, you’ve been knocked down and must take 1 action to climb to your feet, but you aren’t unconscious. |
| **13+** | You take **1** *injury* but **no** *stress* or *fatigue*. You’re still on your feet and **rally** with **1D6 HP**, up to your current maximum. You're one tough SOB. |

</div>

See [Injuries](#injuries), [Fatigue](#fatigue), and [Stress](stress.md#reaching-maximum-stress).

!!! example

	An operator with 2 STRENGTH and 2 HP is in a knife fight and is struck for 4 points of damage after their armor reduces the attack’s damage. The operator now has –2 HP. They need to make an action check for a *wound*.
	
	The operator has the *Close Quarters Combat* specialization, so the GM agrees with the player that the operator knows how to take a hit and grants a +1 to the action check. They roll a 9. The total is 9 + 2 + 1 - 2 = 10. The operator is *down* at 1 HP and falls to the ground.
	
	But they aren’t *knocked out* since they’re wearing a *helmet*. The player suggests that, because of the Close Quarters Combat specialization, the operator could leap to their feet without taking an action. The GM agrees. The operator flips to their feet and attacks.

### Stabilizing Incapacitated Team Members

Buddy aid can automatically stabilize an incapacitated team member after combat. If required **during** combat, the action is complex and risky, so it uses a *mission clock* to track the task.

Stabilizing first requires medical supplies, such as your IFAK in the basic kit. The following outcomes apply in addition to the standard mechanics for action checks that mark off segments. See [Mission Clocks](playing.md#mission-clocks).

- A *partial success* may consume a unit of medical supply.
- A *failed* check moves the mission clock **back** 1 segment, up to a maximum of starting over. 

Once stabilized, the operator is back in the fight, but carrying injuries and fatigue, and at ***0 HP***. See the following sections. 

### Injuries

Each *injury* reduces your ***maximum* HP** by **1** and **cannot** be healed in the field. Your current HP is not affected unless it exceeds the reduced maximum HP. If so, the current HP points are lowered to the reduced maximum. Injuries require medical treatment at base between missions. 

!!! warning 

	Injuries are permanent HP loss until treated at base. If multiple injuries reduce maximum HP to **0**, the operator **dies**.

### Fatigue

*Fatigue* must be stored in your **inventory**. Each unit takes 1 slot. All fatigue units must be carried in your inventory. If your inventory is full, drop enough equipment to free up space for fatigue.

!!! warning

	Accumulated fatigue is debilitating. If it reaches **12** units in inventory, the operator **dies**.

### Recovering Hit Points and Fatigue

Fatigue can be removed, and lost hit points restored, by recovering at a *rendezvous point*. See [Rest and Recovery](#rest-and-recovery).  

If you sleep uninterrupted in a secure location during an extended mission and aren't otherwise deprived of an essential need, such as food and water, all fatigue is removed from your inventory, and **1D6 + STRENGTH** HP points are restored, to your current maximum.

!!! note

	Recall that injuries and the associated permanent reduction in maximum HP cannot be treated in the field. Treatment is available only after the mission, back at base.

## Cover

Hiding behind an object provides *cover* and reduces the damage you take from attacks. Cover blocks **all** damage types, including those that would bypass ballistic body armor. 

The damage blocked by your cover is in **addition** to your personal protective system *armor rating*. The maximum damage reduction from armor is capped at **3**, but when defending behind cover, damage reduction includes **both** your armor rating and the cover bonus.

See [Personal Protective Systems](equipment.md#personal-protective-system) for details on armor ratings.

### Cover Ratings

Cover is divided into three ratings: *low*, *medium*, and *high*. A description of each rating and the damage it blocks follows.

| Cover | Description | Examples | Block Rating |
| - | - | - | :-: |
| Low | Minimal protection and might require lying prone. | Thick foliage, another person | 1 |
| Medium | Protects at least half the body and might require crouching. | Car hood, highway divider | 2 |
| High | Protects the whole body. | Concrete wall, AFV hull | 3 |

### Damage Reduction Summary

You can reduce the amount of damage you take when hit using both body armor and cover as follows:

| Protection Source | Reduction | Stacks |
| - | - | - |
| Base armor | 1–3 | Yes, with secondary |
| Secondary armor| +1 | Capped at 3 total |
| Cover | 1–3 | Yes, independent of armor |

!!! example

	An operator crouches behind a 55-gallon drum. The cover is rated medium, blocking 2 points of damage. The operator wears tier-3 ballistic body armor (3 armor rating) and a helmet (+1 armor), resulting in a damage reduction of 3 rather than 4 because the helmet’s +1 bonus to the armor rating exceeds the maximum 3-point damage reduction allowed for a personal protective system. If hit by hostile fire, the total damage reduction would be 2 (cover) + 3 (armor) = 5 points.
	
	Continuing the example, assume the operator is attacked with a flamethrower. Ballistic body armor and helmets do not reduce this type of damage, but cover still does. The total damage reduction would be 2 points. 

## Suppressing Fire

When you attack an enemy with a ranged weapon, you can instead lay down *suppressing fire*. This consumes **1 ammo**, deals no damage, and forces the target to dive for cover and remain pinned down during their next combat round.

If a suppressed enemy takes any action that makes them visible to you, you can make an immediate **free attack** with *advantage* that interrupts their turn. This free attack's damage isn't reduced by cover. Unless opponents are fanatical or mindless, suppressed targets generally remain pinned down, hiding behind cover.

## Deploying Neural Weapons

Neural weapons are among your unit's most lethal assets. When a neural weapon is brought to bear, it is a tactical effect: precise, controlled, and potentially decisive.

When you invoke your neural weapon, roll **2D6+WILLPOWER** and consult the list below to determine the result.

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | Your neural power **doesn’t manifest**, and you take **1** point of *stress*. You can’t use this neural weapon again during the mission unless you recover at a *rendezvous point*. See [Rest and Recovery](combat.md#rest-and-recovery). |
| **7–9** | The power **manifests**, and you take **1** point of *stress*. |
| **10–12** | The power **manifests**, and you do not feel any stress.  |
| **13+** | The power **manifests**, and you feel no stress. The neural weapon’s effect is **greater** than expected. Work with the GM to specify what else happens.   |

</div>

Neural weapons described as *ongoing* require concentration to keep the power active after it’s manifested.

- You must spend an action each round of combat to maintain concentration and keep the power active.
- If you take damage while concentrating, your focus is disrupted, and the neural weapon’s effect ends.
- Otherwise, you can voluntarily stop concentrating to end the effect. 

## Retreating

Withdrawing from a fight while engaged in combat may expose the retreating force to additional attack.

- If your **opponents** retreat, you can immediately make a free attack against them before they move.
- If **you** retreat, roll **2D6 + REFLEXES** and apply the result.

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | Your opponent makes a **free attack** immediately against you. |
| **7–9** | You disengage, but you suffer a *complication*. |
| **10–12** | You disengage without mishap. |
| **13+** | You make a **free attack** against your opponent, then disengage without mishap. |

</div>

## Mobs

When facing many weak, similar opponents, such as untrained guards or street thugs, the GM can merge them into a *mob* that’s treated as a single opponent in combat.

The **number of opponents** in a mob determines its *hit points*, *armor*, and *attacks per round*, as shown in the table below. A mob’s attacks have a **+1 damage** rating.  

| Number | Armor | Attacks |
| :- | :-: | :-: |
| 1–4 | 0 | 1 |
| 5–8 | 0 | 2 |
| 9–12 | 1 | 3 |
| 13–16 | 2 | 4 |
| 17–20+ | 3 | 5 |

Each point of damage reduces the **number** of hostiles in the mob by **1**, which in turn lowers its related stats.

!!! example

	An operator is facing a mob of 14 enemies. The mob’s stats are 14 HP and 2 ARMOR. Each round, the mob can attack up to 4 opponents. After taking 5 damage, the mob’s size drops to 9, and its stats become 9 HP and 1 ARMOR. Consequently, the mob can now attack up to 3 targets each round.

## Emergency Deployment

If your character dies, create a new one while the game continues. When you’re ready to rejoin, the GM will ask you to roll **2D6 + TACTICS** and consult the list below. 

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | Your deployment encounters a **complication**. The GM will let you know. |
| **7–9** | You deploy normally. |
| **10–12** | You deploy normally and gain **one extra** tactical supply. |
| **13+** | You deploy normally, gain **one extra** tactical supply, and your next *action roll* has *advantage*. |

</div>

## Rest and Recovery

Once per mission, your unit can send a *rendezvous signal*. The GM then designates a nearby *rendezvous point* and describes any obstacles to reaching it. Arriving at a rendezvous point lets your unit rest and recover. 

Reaching the rendezvous point has the following effects:

- Remove all *panicked and locked-in* effects. See [Reaching Maximum Stress](stress.md#reaching-maximum-stress).
- *Momentum* points reset to their starting value of 2. 

You also choose **one** benefit from the following list:

- **INTEL**: Ask a single question about the mission. The GM will reply “yes” or “no.”
- **PATCH UP**: Recover **1D6 HP**.
- **RECUPERATE**: Remove **1D6** *stress points* and **1D3** *fatigue*.
- **RESUPPLY**: Receive **one** unit of tactical supplies.

!!! note

	You cannot recover hit points at a rendezvous point if you lack medical supplies, such as an IFAK in your basic kit.