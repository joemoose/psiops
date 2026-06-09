# Combat

Combat is like any risky action: attacking requires an *action roll* to deal damage, and defending against an attack requires an *action roll* to avoid damage. Details follow.

## Combat Sequence

Once combat begins, the game follows a set framework for each combat round:

1. Roll initiative to determine whether you can act in the first round of combat.
2. If you can act in the first round:
	- Declare actions
	- Make required action rolls
	- Apply the results
3. Start the next round of combat:
	- Declare actions
	- Make required action rolls
	- Apply the results
4. Repeat Step 3 until combat ends. 

Details on these steps follow.

## Combat Rounds

A *combat round* is about 6 seconds, enough time for you to **move once** and take **1 action**, such as firing at a target or moving again. 

Complex actions taking more than 6 seconds may require multiple combat rounds to complete. See [Mission Clocks](playing.md#mission-clocks). Minor actions, such as shouting, moving through a door, or dropping an item, are free and don't count as your 1 action.

### The First Round and Initiative Roll

Whether you act before the enemy in the **first** round of combat is decided by an *initiative roll*. Roll **2D6 + TACTICS** and apply the following result:

<div class="roll-table" markdown="1">

| Roll | Result |
|:----:|--------|
| **6–** | You **do not** act in the first round of combat. The enemy gets the drop on you, and you’ll have to wait until the **second round** to move or take any action.  |
| **7–9** | You get the drop on the enemy and act **first**, but you have a *disadvantage* on your next *action roll*. |
| **10–12** | You get the drop on the enemy and act **first**. |
| **13+** | You get the drop on the enemy and act **first**. You gain an *advantage* on your next *action roll*. |

</div>

Following the initiative roll, all members of your squad who can act in the first round declare their moves and actions. The results of those actions are then determined. See the following sections for details. 

Afterward, the opposing force takes its actions. The first round of combat is now complete. 

### The Second and Subsequent Rounds

In the second and subsequent rounds of combat, you **no longer** roll initiative. You and your squad always act first in each subsequent round, followed by the enemy, until one side is eliminated or withdraws.

### Ambushes

Circumstances or careful planning can sometimes determine which side acts first. If you *ambush* the enemy, your squad doesn’t make an initiative roll and instead acts first, gaining *advantage* on all action rolls during the first combat round.

Afterward, combat proceeds as usual: your squad takes actions, then the opposing force takes actions. An ambush lets you take two consecutive rounds of combat before your opponent can respond. 

If the enemy ambushes you, your squad doesn’t act during the first round of combat. In subsequent rounds, combat proceeds as usual.

## Declaring Actions

In a combat round, your actions and your team members’ actions occur **at the same time**. Everyone declares their actions for the current combat round upfront, before any results are determined. Actions are not declared individually and then resolved one by one. 

!!! note

	The GM will give you a general sense of what the enemy is doing to help with planning your actions. 

### Interrupting Actions

You may hold an action and specify a trigger, for example, “I wait until the enemy rounds the corner.” When the trigger occurs, you act immediately, interrupting the enemy’s turn.

## Determining the Results

As described in [Actions](playing.md#actions), the outcome of any *risky* or *uncertain* action you attempt is determined by an *action roll*. Because nearly every decision and action you make in combat is perilous, you’ll make an *action roll* whenever you declare an action during a combat round.

The following sections provide details on specific combat-related *action rolls*, such as *attacking* and *defending*. Regardless of what you attempt in combat, all actions are resolved using the PsiOps core mechanic: **2D6 + Attribute** to determine the result.  

## Attacking

When you **attack** a target, make an *attack roll*. Roll **2D6 + Applicable Attribute** and apply the following result:

<div class="roll-table" markdown="1">

| Roll | Result |
|:----:|:-------|
| **6–** | The attack misses. You deal **no damage**. |
| **7–9** | You deal damage equal to the **lowest D6 roll** plus your weapon's **damage modifier**. |
| **10–12** | You deal damage equal to the **highest D6 roll** plus your weapon's **damage modifier**. |
| **13+** | You deal damage equal to the **sum of both dice** plus your weapon's **damage modifier**. |

</div>

!!! note Notes

- For help choosing the attack roll attribute, see [Choosing an Applicable Attribute](playing.md#choose-an-applicable-attribute). 
- *Advantage* or *disadvantage* may apply to your attack roll based on the range to your target. See the following [Attack Roll Modifiers](#attack-roll-modifiers).

### Weapon Damage Modifiers

The damage modifer for your attack is dtetrmine by your weapons. Specific damage modifiers for ecah class of weapon is  listed in the Equipment sections. See [Combat Weapons](equipment.md#combat-weapons).

For weapons or other types of attacks not specifically listed on the Combat Weapons list, the GM uses the following general guidelines to determine a damage modifier:

| Level of Effect | Examples | Modifier |
| :- | :- | :-: |
| **Unarmed** | — | -1 |
| **Minimal** | boot knives, brass knuckles | +0 |
| **Light** | combat knives, sidearms | +1 |
| **Medium** | rifles, shotguns | +2 |
| **Devastating** | antiarmor missiles, sniper rifles | +3 |
| **Anomalous** | \[REDACTED\] | +4 |

### Blast Damage

Attacks with the *blast* quality, such as explosives, can affect multiple targets in a confined area. To determine the number of targets, roll **1D6 + the weapon's damage modifier**. The result is the number of targets affected.

### Multiple Attackers

If you and other team members attack the same opponent, determine the damage for each attack separately, but apply only the **highest value**. The damage from multiple attackers is not cumulative.

## Attack Roll Modifiers

The effectiveness of your attacks is modified by weapon type, optimal engagement distance, and tactical situations. See the following tables for attack modifiers. 

### Range Modifiers

Each weapon class has a distinct optimal engagement distance. Depending on your weapon type and the range to your target, your *attack roll* may be at *advantage*, *disadvantage*, or *impossible*. The range to your target is determined by the number of intervening zones. See [Tactical Zones](zones.md).

| Weapon | Same Zone (Close) | 1 Zone (Nearby)  | 2 Zones (Far) | 3 Zones (Distant) | 4+ Zones (Extreme) |
| - | :-: | :-: | :-: | :-: |
| **Assault rifle** | disadvantage | normal | normal | impossible | impossible |
| **Close-quarters combat** | normal | impossible |  impossible | impossible | impossible |
| **Heavy weapon** | impossible | disadvantage | normal | normal | disadvantge |
| **LMG** | impossible | normal | normal |  disadvantage | disdvantage |
| **Shotgun** | normal | normal | disadvantage |  impossible | impossible |
| **Sidearm** | normal | advantage | disadvantage | impossible | impossible |
| **SMG** | normal | advantage | disadvantage | impossible | impossible |
| **Sniper rifle** | impossible | disadvantage | advantage | normal | normal |
| **Thrown** | normal | normal |  impossible  |  impossible  | impossible |

### Tactical Modifiers

The following tactical decisions apply modifiers to your attacks.

- **Aiming**: When you take an *action* to aim at a target, your subsequent *attack rolls* gain *advantage* unless you move or take an action other than continuing to attack the target.
- **Prone**: When attacking from a prone position, you have *advantage*. Attacks against a prone target have *disadvantage*.

## Expending Ammunition

At the start of a mission, all your small arms are stocked with an *ammo rating* of **6**. 

Each time you attack, your weapon’s ammo rating may decrease as follows:

- If your *attack roll* **fails**, reduce your weapon's *ammo rating* by **1**.
- If your attack roll is either a **partial** or a **complete** success, you do **not** reduce your *ammo rating*. 

When a weapon's *ammo rating* reaches **0**, it becomes unusable until you resupply it with ammunition.

### Resupply

You can resupply expended ammunition in several ways: carrying extra ammunition in your inventory, using up your *tactical supplies*, or restocking at a *laying-up point*. See [Rest and Recovery](combat.md#rest-and-recovery).

If you recover enemy ammunition during the mission, it increases the *ammo rating* of **one** of your weapons by **1** point.

!!! note

	Some weapons are listed as *single-use*, such as antiarmor missiles. These weapons have no ammo rating and are removed from your inventory after use.

## Defending

When you **defend** against an enemy attack, make a *defense roll*. Roll **2D6 + Applicable Attribute** and apply the result.

<div class="roll-table" markdown="1">

| Roll | Result |
|:----:|:-------|
| **6–** | You take **damage** equal to the **highest D6 result** plus your enemy weapon’s damage modifier. |
| **7–9** | You take **damage** equal to the **lowest D6 result** plus your enemy weapon's damage modifier. |
| **10–12** | You take **no** damage. |
| **13+** | You take **no** damage, and your next *action roll* has *advantage*. |

</div>

!!! note

- For help choosing the defense roll attribute, see [Choosing an Applicable Attribute](playing.md#choose-an-applicable-attribute).

## Damage, Wounds, and Dying

### Damage

Deduct all *damage* directly from your *hit points (HP)*. Keep track of your current HP. Your character sheet has a place to record it. If you have at least **1 HP** remaining after taking damage, you’re still combat-ready and in the fight.

### Wounds

If your current HP drops to **0** or **below**, into negative values, you’re *wounded*, possibly grievously. 

Immediately after being *wounded*, make a *wound roll*. Roll **2D6 + STRENGTH** and **subtract** the number of hit points you’ve dropped below zero. Then apply the following result:

<div class="roll-table" markdown="1">

| Roll | Result |
|:----:|:-------|
| **6–** | You're **dead**. Roll up a new operator. |
| **7–9** | You're *incapacitated* at **0 HP**. Take **2** *injuries*, **2** *fatigue*, and **2** *stress*. You'll die unless *stabilized*. See the following section. |
| **10–12** | You’re *knocked down*, unconscious but stable at **1 HP**. Take **1** *injury*, **1** *fatigue*, and **1** *stress*. A team member can revive you by spending 1 action.<br/><br/>**Note**: If you’re wearing a helmet, you’re still knocked down but not unconscious. Spend 1 action to climb to your feet. |
| **13+** | You take **1** *injury*, but you’re **relentless** with **1D6 current HP**, up to your maximum. You are one tough SOB. |

</div>

See [Injuries](#injuries), [Fatigue](#fatigue), and [Stress](stress.md#reaching-maximum-stress) for details on the additional wound effects.

!!! example

	An operator with 2 STRENGTH and 2 current HP is in a firefight. They are attacked for 3 points of damage. The operator now has –1 HP. They must make a *wound roll* because their current HP is zero or below.
	
	They roll *2D6* + *2* (STRENGTH) and subtract *1* (the number of current HP points below zero), getting 4 and 5. The total is 4 + 5 + 2 - 1 = 10. The operator is *knocked down*. They add 1 *injury*, 1 *fatigue*, 1 *stress*, and increase current HP to 1. 
	
	But they aren’t *unconscious* because they’re wearing a *helmet*. The operator spends their action to return to a firing position. They’re injured, growing tired, and a little more stressed, but not yet out of the fight. 

### Stabilizing Incapacitated Team Members

Stabilizing an *incapacitated* team member requires a unit of medical supplies, such as the IFAK in your basic kit. If you have medical supplies, you automatically stabilize an incapacitated team member **after** combat ends.

If need to stabilize an incapacitated team member **during** combat, the action is complex and risky. The GM then uses a *mission clock* to track your progress. See [Mission Clocks](playing.md#mission-clocks).

To **stabilize a team member in combat**, move a unit of medical supplies into your hand, then make a *stabilization roll*. Roll **2D6 + TACTICS**. Apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
|------|--------|
| **6–** | You do **not** mark off a segment on the mission clock, and you **use up** your unit of medical supplies. Remove it from your inventory.<br/>You’ll need to find more medical supplies to continue making *stabilization rolls*. |
| **7–9** | Mark off **1** segment on the mission clock. |
| **10–12** | Mark off **2** segments on the mission clock. |
| **13+** | Mark off **3** segments on the mission clock. |

</div>

Once all segments are marked off the clock, the incapacitated team member is stabilized. Stabilized operators are conscious and back on their feet, though at **0 HP**. Any damage immediately reduces their HP below zero, triggering another *wound roll*.

### Injuries

Each *injury* you sustain reduces your ***maximum HP** by **1** and **cannot** be healed in the field. Your current HP is not affected unless it exceeds the reduced maximum HP. If it does, your current HP is lowered to the new maximum. Injuries require medical treatment at base between missions. 

!!! warning 

	Injuries cause permanent HP loss until treated at base. If multiple injuries reduce maximum HP to **0**, the operator **dies**.

### Fatigue

All *fatigue* you sustain must be stored in your **inventory** as an abstract item. Each unit of fatigue takes up 1 slot. If your inventory is full, drop enough equipment to free up slots for the fatigue.

!!! warning

	Accumulated fatigue is debilitating. If inventory reaches **12** units of fatigue, the operator **dies**.

### Recovering Hit Points and Fatigue

Lost *hit points* can be restored, and *fatigue* removed by resting at a *laying-up point*. See [Rest and Recovery](#rest-and-recovery).

!!! note 

	Experimental or anomalous medical restoratives are rumored to exist. 

## Cover

When you duck behind an object to take *cover* from an attack, your *defense roll* has *advantage* to avoid damage. Cover is rated as *low*, *medium*, or *high*. All three types of cover grant *advantage* on your defense roll, but *medium* and *hard* cover also **reduce** damage by **1** point.

*Medium* and *hard* cover differ in that *hard* cover protects your whole body. If you stay behind *high* cover and avoid exposing yourself to the enemy, you can't be targeted. However, if you lean out from or over *high* cover to attack, you expose yourself to enemy fire. Attacking from behind *high* cover essentially places you in the *medium* category.  

The damage blocked by cover is in **addition** to your personal protective system’s *armor rating*. The maximum damage reduction from armor is capped at **3**. When defending from behind cover, damage reduction includes **both** your armor rating and the **+1** cover bonus.

Cover protects against certain types of damage that would bypass ballistic body armor, such as intense flames. The GM will let you know. See [Personal Protective Systems](equipment.md#personal-protective-system).

### Cover Ratings Summary

Each cover rating’s description and defensive bonus are as follows:

| Cover | Description | Examples | Defensive Bonus |
| :- | :- | :- | :-: |
| Soft | Provides minimal protection and may require lying prone. | Thick foliage, another person | *advantage* |
| Medium | Protects at least half the body and may require crouching. | Car hood, highway divider | *advantage*, +1 ARMOR |
| High | Protects the whole body. | Concrete wall, AFV hull | Either can’t be targeted, or, if you lean out and attack, *advantage*, +1 ARMOR. |

### Damage Reduction Summary

You can reduce the damage you take by using a personal protective system and by fighting from behind cover as follows:

| Protection Source | Reduction | Stacks |
| - | :-: | - |
| Base armor | 1–3 | Yes, with secondary |
| Secondary armor | +1 | Capped at 3 total |
| Hard Cover | +1 | Yes, independent of armor |

!!! example

	An operator crouches behind a 55-gallon drum. The cover is rated medium, granting *advantage* on defense rolls and blocking 1 point of damage. The operator wears tier-3 ballistic body armor (3 armor rating) and a helmet (+1 armor), resulting in a damage reduction of *3* rather than 4 because the helmet’s +1 bonus to the armor rating exceeds the maximum 3-point damage reduction. If hit by hostile fire, the total damage reduction would be 3 (armor) + 1 (medium cover) = 4 points.
	
	Continuing the example, assume the operator is attacked with a flamethrower. Ballistic body armor and helmets do not reduce this type of damage, but cover still does. The total damage reduction would be 1 point. 

## Suppressing Fire

When you attack an enemy with a ranged weapon, you can instead lay down *suppressing fire*. This consumes **1 ammo**, deals no damage, and forces the target to dive for cover and remain pinned down until their next combat round.

If a suppressed enemy takes any action that makes them visible to you, you can make an immediate **free attack** with *advantage* that interrupts their turn. This free attack’s damage isn’t reduced by cover. Unless opponents are fanatical or mindless, suppressed targets will generally stay pinned down behind cover.

## Neural Weapons

*Neural weapons* are among your squad’s most lethal assets. When a neural weapon is brought to bear, it produces a tactical effect: precise, controlled, and potentially decisive.

### Activating Neural Weapons

To activate your neural weapon, make a *neural attack roll*. Roll **2D6 + WILLPOWER** and apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
|:----:|:-------|
| **6–** | Your neural weapon **doesn’t activate**, and you take **1** *fatigue*. See [Fatigue](#fatigue).<br/>You can also **no longer** activate this neural weapon during the mission unless you rest at a *laying-up point*. See [Rest and Recovery](#rest-and-recovery). |
| **7–9** | The power **manifests**, but you take **1** *fatigue*. |
| **10–12** | The power **manifests**.  |
| **13+** | The power **manifests**. The effect is greater than expected. Work with the GM to specify what else happens. |

</div>

### Ongoing

Neural weapons described as *ongoing* require concentration to keep the power active after it’s manifested.

- You must spend an *action* each combat round to maintain concentration and keep the power active.
- If you take damage while concentrating, your focus is disrupted, and the neural weapon’s effect ends.

## Retreating

Retreating from a fight while engaged in combat may leave the retreating force vulnerable to further attack.

- If your **opponents** retreat, you can immediately make a free attack against them before they move.
- If **you** retreat, make a *retreat roll*. Roll **2D6 + REFLEXES** and apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
|:----:|:-------|
| **6–** | Your opponent makes a **free attack** immediately against you. |
| **7–9** | You disengage, but you suffer a *complication*. |
| **10–12** | You disengage without mishap. |
| **13+** | You make a **free attack** against your opponent, then disengage without mishap. |

</div>

## Mobs

When facing many weak, similar opponents, such as untrained guards or street thugs, the GM can merge them into a *mob* treated as a single opponent in combat.

The **number of opponents** in a mob determines its *hit points*, *armor*, and *attacks per round*, as shown in the table below. A mob’s attacks deal **+1 damage**.  

| Number | Armor | Attacks |
| :-: | :-: | :-: |
| 1–4 | 0 | 1 |
| 5–8 | 0 | 2 |
| 9–12 | 1 | 3 |
| 13–16 | 2 | 4 |
| 17–20+ | 3 | 5 |

Each point of damage reduces the **number** of hostiles in the mob by **1**, which in turn lowers the mob’s related stats.

!!! example

	An operator faces a mob of 14 enemies. The mob’s stats are 14 HP and 2 ARMOR. Each round, the mob can attack up to 4 opponents. After taking 5 damage, the mob’s size drops to 9, and its stats become 9 HP and 1 ARMOR. Consequently, the mob can now attack up to 3 targets each round.

## Emergency Deployment

If your character dies, create a new one while the game continues. When you’re ready to rejoin, the GM will ask you to make a *deployment roll*. Roll **2D6 + TACTICS** and apply the result as follows: 

<div class="roll-table" markdown="1">

| Roll | Result |
|:----:|:-------|
| **6–** | Your deployment encounters a **complication**. The GM will let you know. |
| **7–9** | You deploy normally. |
| **10–12** | You deploy normally and gain **one extra** tactical supply. |
| **13+** | You deploy normally, gain **one extra** tactical supply, and your next *action roll* has *advantage*. |

</div>

## Rest and Recovery

Once per mission, your squad can *rally*. The GM then designates a nearby *laying-up position (LUP)* and describes any obstacles to reaching it. Arriving at the LUP lets your squad rest and reorganize. Your LUP is always concealed and defensible. You can rally once per mission. 

Reaching the LUP has the following effects:

- Your *momentum* resets to its initial value of **2** points.
- Reactivate any *neural weapons* that are no longer usable.
- Remove all *panicked* and *locked-in* effects.

Additionally, choose **one** benefit from the following list:

- **INTEL**: Ask a single question about the mission, and the GM will reply with a “yes” or “no.”
- **PATCH UP**: Recover **1D6 HP**.
- **RECUPERATE**: Remove **1D6** *stress points* and **1D3** *fatigue*.
- **RESUPPLY**: Add **one** unit of tactical supplies to your inventory.

!!! note

	You **cannot** patch up and recover hit points without medical supplies, such as an IFAK in your basic kit.
