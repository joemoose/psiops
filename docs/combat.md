# Combat

Combat is like any risky action: attacking requires an *action roll* to deal damage, and defending against an attack requires an *action roll* to avoid taking damage. Details follow.

## Combat Sequence

Once *combat mode* begins, the game proceeds through a fixed sequence of steps as follows:

<figure class="diagram" style="--diagram-max-width: 640px">
--8<-- "img/combat.svg"
<figcaption>Combat Sequence</figcaption>
</figure>

## Rounds

A *combat round* is about 6 seconds, enough time to **move once** and take **1 action**, such as firing at a target or moving again. You can move or act in any order, or choose to forgo either.

!!! note

	If you use your action to move again, you make two moves, crossing into a second zone, which count as a sprint.

Complex actions that take more than 6 seconds may require multiple combat rounds to complete. See [Mission Clocks](playing.md#mission-clocks). Minor actions, such as shouting, moving through a doorway, or dropping an item, are free and don’t count against your 1 action.

In each combat round, both your squad and the opposing force take turns moving and acting as units. The following section explains how to determine which side takes the first turn.

### First Round and Initiative Roll

Whether you act before the enemy in the **first** round of combat is determined by an *initiative roll*. Roll **2d6 + TACTICS** and apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | - |
| **2–6** | You **do not** act in the first round of combat. You’ll wait until the **second round** to move or take any action. |
| **7–9** | You get the drop on the enemy and act **first**, but you have a *disadvantage* on your next *action roll*. |
| **10–12** | You get the drop on the enemy and act **first**. |
| **13+** | You get the drop on the enemy, act **first**, and you gain an *advantage* on your next *action roll*. |

</div>

!!! note

	Like any other *action roll*, initiative rolls can have *advantage* or *disadvantage* depending on tactical circumstances.

#### Completing the First Combat Round

After the *initiative roll*, all squad members who act first in the combat round take their turn and resolve their movement and actions. Other team members who failed their initiative roll must sit out the first round and wait until the second round before they.

Afterward, the opposing force takes its turn. The first round of combat ends.

### Subsequent Rounds

In the second and subsequent rounds of combat, you **do not** make an *initiative roll*. You and your squad **always** take the first turn, followed by the enemy, until one side is eliminated or withdraws.

### Ambushes

Who takes the first turn can be determined by circumstances or careful planning rather than by *initiative rolls*.

#### Ambushing the Opponents

If you *ambush* the enemy, you don't make an *initiative roll*. Instead, you and your team each take a turn in the combat round and gain *advantage* on *action rolls*. The enemy takes no turn in the first combat round.

Afterward, in the second and subsequent rounds, combat proceeds as usual: your squad takes the first turn, followed by the opposing force.

!!! tip

	Because your squad always acts first in the second round, an ambush gives you two consecutive turns before the enemy can respond. This is a commanding tactical advantage. Exploit it.

#### Being Ambushed

If the enemy *ambushes* you, your squad doesn’t take a turn in the first round of combat. You can take no actions or move until the second round, and the enemy goes first. In the second and subsequent rounds, combat proceeds as usual.

## Simultaneous Actions

During your turn, all actions and moves for your entire squad occur **at the same time**. Everyone declares their actions and moves for the current turn upfront, before any results are determined. Actions and moves are not declared individually by each player and then resolved one at a time.

!!! note

	Ask questions. The GM can give you a general sense of what the enemy is doing to help you plan your actions.

### Interrupting Turns

You may hold your action and specify a trigger, for example, “I wait until the enemy rounds the corner.” If the trigger occurs, you act immediately with your declared action to interrupt the enemy’s turn.

## Determining the Results

As described in [Actions](playing.md#actions), the outcome of any *risky* or *uncertain* action you attempt is determined by an *action roll*. Since nearly every action you take in combat is risky, you’ll make an *action roll* whenever you declare an action during your turn.

## Attacking

When you **attack** a target, make an *attack roll*. Roll **2d6 + Applicable Attribute** and apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | - |
| **2–6** | The attack misses. You deal **no damage**. |
| **7–9** | You deal damage equal to the **lower** of the two d6 rolls, plus your weapon's **damage modifier**. |
| **10–12** | You deal damage equal to the **higher** of the two d6 rolls, plus your weapon's **damage modifier**. |
| **13+** | You deal damage equal to the **sum** of both dice, plus your weapon's **damage modifier**. |

</div>

### Applicable Attack Roll Attributes

The *applicable attribute* for your *attack roll* depends on how you describe the attack. Examples follow:

| Attribute | Example Attack |
| - | - |
| STRENGTH | I kick down the door and fire my shotgun at anything I see. |
| REFLEXES | I run through the house, slide into cover, and fire from there. |
| TACTICS | I go around the side of the house, flank them, and fire through the window. |
| WILLPOWER | I lure someone to the doorway, then fire when they respond. |

!!! note

	*Advantage* or *disadvantage* may also apply to your attack roll based on the distance to your target or other tactical circumstances. See [Attack Roll Modifiers](#attack-roll-modifiers).

### Weapon Damage Modifiers

The *damage modifier* applied to a successful attack is determined by the type of weapon you’re using. Modifiers for each weapon type are listed in the [Equipment](equipment.md) section. See [Combat Weapons](equipment.md#combat-weapons).

For weapons or other attacks not listed on the Combat Weapons list, use the following guidelines to gauge damage modifiers:

| Level of Effect | Examples | Modifier |
| - | - | :-: |
| **Unarmed** | — | -1 |
| **Improvised** | club, shiv | +0 |
| **Light** | combat knives, sidearms | +1 |
| **Medium** | rifles, shotguns | +2 |
| **Heavy** | antiarmor missiles, sniper rifles | +3 |
| **Anomalous** | \[*REDACTED*\] | +4 |

### Blast Damage

Attacks with the *blast* quality, such as explosives or frag grenades, can affect multiple targets in the target *zone*. To determine how many targets are affected, roll **1d6 + the weapon's damage modifier**. The result is the number of targets affected in the zone. See [Zones](zones.md).

All targets caught in the blast then suffer the same *attack roll* results. If there are more targets in a zone than the target count, select the targets randomly.

!!! note

	Against a *mob*, a blast attack removes a number of members equal to the blast’s target count. See [Mobs](#mobs).

### Multiple Attackers

If you and other team members attack the same target, make all *attack rolls* separately, but apply only the **highest amount of damage**. Damage from multiple attackers is not cumulative.

!!! note

	When attacking *mobs*, damage from multiple attackers is cumulative. Damage to a mob is the exception to this rule. See [Mobs](#mobs).


## Attack Roll Modifiers

The odds for success on your *attack roll* is modified by weapon type, engagement distance, and tactical circumstances. See the following tables for the modifiers.

### Distance Modifiers

Each weapon type has a distinct *optimal engagement distance*. Depending on your weapon and the distance to your target, your *attack roll* may have *advantage*, *disadvantage*, or be *impossible*. Measure distance to your target by the number of intervening *zones*. See [Zone Distances](zones.md#distances).

Weapon distance modifiers are as follows:

| Weapon | Same Zone (Close) | 1 Zone (Nearby) | 2 Zones (Far) | 3 Zones (Distant) | 4+ Zones (Extreme) |
| - | :-: | :-: | :-: | :-: | :-: |
| **Antiarmor** | impossible | disadvantage | normal | normal | disadvantage |
| **Assault rifle** | disadvantage | normal | normal | disadvantage | impossible |
| **Combat knife** | normal | impossible | impossible | impossible | impossible |
| **Combat shotgun** | normal | normal | disadvantage | impossible | impossible |
| **Command-detonated mine** | advantage | normal | impossible | impossible | impossible |
| **Frag grenade** | normal | normal | impossible | impossible | impossible |
| **Grenade launcher** | impossible | normal | normal | disadvantage | impossible |
| **LMG** | impossible | normal | advantage | normal | impossible |
| **Sidearm** | normal | advantage | disadvantage | impossible | impossible |
| **SMG** | normal | advantage | disadvantage | impossible | impossible |
| **Sniper rifle** | impossible | disadvantage | advantage | normal | normal |

### Tactical Modifiers

Tactical decisions apply attack modifiers as follows:

- **Aiming**: When you take an *action* to aim at a target, your next *attack roll* has *advantage* unless you move or take an action other than continuing to attack that target.
- **Prone**: When attacking from a prone position, you have *advantage*. Attacks against a prone target have *disadvantage*.

## Expending Ammunition

At the start of a mission, all your small arms have an *ammo rating* of **5**.

Each time you attack, your weapon’s *ammo rating* may decrease as follows:

- If your *attack roll* **fails**, reduce your weapon's *ammo rating* by **1**.
- If your *attack roll* is any type of **success** (*partial*, or better), do **not** reduce your *ammo rating*.

When a weapon's *ammo rating* reaches **0**, it becomes unusable until you resupply it with ammunition.

!!! note

	Some weapons are marked *single-use*, such as antiarmor missiles. These weapons have no *ammo rating* and are removed from your inventory after use.

### Resupply

You can resupply ammunition in several ways: carrying extra ammunition in your inventory, using your *tactical supplies*, or restocking at a *rally point*. See [Rally Point](damage.md#rally-point).

If you recover enemy ammunition during the mission, increase the *ammo rating* of one weapon by **1**.


## Defending

When you **defend** against an enemy attack, make a *defense roll*. Roll **2d6 + Applicable Attribute** and apply the result.

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | - |
| **2–6** | You take **damage** equal to the **highest d6 result** plus your enemy’s *damage modifier*. |
| **7–9** | You take **damage** equal to the **lowest d6 result** plus your enemy’s *damage modifier*. |
| **10–12** | You take **no** damage. |
| **13+** | You take **no** damage, and your next *action roll* has *advantage*. |

</div>

### Applicable Defense Roll Attributes

The *applicable attribute* for your *defense roll* depends on the type of attack you’re trying to avoid. Examples follow:

| Attribute | Attack Type |
| - | - |
| STRENGTH | An attack that can’t be dodged, such as poisoning or electrocution |
| REFLEXES | An attack that can be dodged, such as gunfire |
| TACTICS | An attack that can be avoided through instinctive training and observation, such as an ambush |
| WILLPOWER | Resisting a mental attack, such as one from a neural weapon |

## Cover

When you move behind cover to avoid an enemy attack, your *defense roll* has *advantage*, regardless of the type of cover. Hard cover also reduces the *damage* you might take.

Cover is rated as follows:

| Cover | Bonus | Example |
| :-: | - | - |
| **No cover** | None | Fully exposed |
| **Soft** | *Advantage* on *defense rolls* | Foliage, smoke, lying prone, or thin barriers |
| **Hard** | *Advantage* on *defense rolls* and +1 DAMAGE REDUCTION | Concrete barriers, vehicles, sandbags, or 200-liter barrels |
| **Total** | The attacker cannot directly target you unless they flank, use indirect fire, or breach the cover. | Wall, AFV hull, wide tree |

### Hard Cover Damage Reduction

The *damage reduction* from hard cover is in **addition** to your personal protective system’s *armor rating*. The maximum damage reduction from your personal protective system is capped at **3** points. When behind hard cover, your total damage reduction includes **both** your armor rating and the **+1** cover bonus.

Hard cover protects against certain types of damage that bypass ballistic body armor, such as intense flames. See [Personal Protective System](equipment.md#personal-protective-system).

### Damage Reduction Summary

You can reduce the damage you take by using a personal protective system and by fighting from behind cover as follows:

| Protection Source | Damage Reduction | Stacks |
| - | :-: | - |
| Base armor | 1–3 | Yes, with secondary |
| Secondary armor | +1 | Capped at 3 total |
| Hard Cover | +1 | Yes, independent of armor |

Some *neural weapons* can also provide damage reduction. See [Neural Weapons](character.md#neural-weapons).

!!! example

	You take cover behind a concrete barrier. The cover is rated hard, granting *advantage* on defense rolls and reducing damage by **1** point. You're wearing heavy ballistic body armor (**3** armor) and a helmet (**+1** armor), which results in a damage reduction of *3* rather than **4** because the helmet’s **+1** bonus to the armor rating exceeds the 3-point damage-reduction cap. If hit by hostile fire, the total damage reduction would be **3** (armor) + **1** (hard cover) = **4** points.

	Continuing the example, assume you're attacked with a flamethrower. Ballistic body armor and helmets don't reduce this type of damage, but hard cover still does. The total damage reduction would be **1** point from the cover.

## Suppressing Fire

Instead of making an attack, you can lay down *suppressing fire* on a *zone*.

Suppressing fire saturates a zone with automatic fire, forcing all targets in the area to keep their heads down and take cover. It automatically affects **all** targets in the zone, friend or foe. See [Zones](zones.md).

### Suppression Requirements

Only automatic weapons, including assault rifles, SMGs, machine guns, and similar weapons, can provide suppressing fire.

- Suppressing fire requires **no** *attack roll*.
- Suppressing fire deals **no** damage.
- Suppressing fire consumes **1** ammo.
- You can’t suppress a *zone* you occupy.

### Free Attacks

All targets in a suppressed zone are pinned down for their combat round. Pinned targets generally remain behind cover and avoid exposing themselves to attack unless they have no other choice or are fanatical or mindless.

If a pinned target becomes visible to you, for example, by attacking or moving out of cover, you may immediately interrupt their turn to make a **free attack** with *advantage* against them.

!!! example

	Your squad is assaulting a bunker patrolled by automated guard drones. A zone with no cover lies between you and the bunker.

	You lay down suppressing fire with your LMG on the bunker’s zone, and the rest of the squad moves forward into the open zone, then uses their actions to move again and continue sprinting into the bunker’s zone. Your squad’s turn is now complete.

	The drones go next. Following only their programming and lacking any instinct for self-preservation, they stop and swivel to fire on the team members now occupying their zone. However, this exposes the drones to your suppressing fire. You immediately interrupt their turn and make a free attack with advantage against each drone. Send it!

## Neural Weapons

*Neural weapons* are among your squad’s most lethal assets. When a neural weapon is brought to bear, it produces a tactical effect: precise, controlled, and potentially decisive.

### Activating Neural Weapons

To activate your *neural weapon*, make a *neural attack roll*. Roll **2d6 + WILLPOWER** and apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | - |
| **2–6** | Your neural weapon **doesn't activate**. You take **1** *fatigue* and **cannot activate** this neural weapon again during the mission unless you regroup at a *rally point*. See [Fatigue](damage.md#fatigue) and [Rally Point](damage.md#rally-point). |
| **7–9** | The power **activates**, but you take **1** *fatigue*. |
| **10–12** | The power **activates**. |
| **13+** | The power **activates**, and the effect is greater than expected. |

</div>

### Ongoing Neural Effects and Concentration

Many *neural weapons* can continue their effect across multiple combat rounds. Doing so requires that you maintain *concentration* to sustain the effect. As long as you maintain concentration on each of your turns in the combat round, the effect persists.

- To keep an ongoing neural weapon's effect active, you must spend an *action* each combat round to maintain concentration.
- If you take any action other than concentrating at the start of your combat round, the effect ends immediately.
- If you take damage while concentrating, your focus is disrupted, and the effect ends immediately.

!!! note

	- You're still free to **move** into another zone during your round; only your action is required to maintain concentration. Any movement you initiate does not break your concentration.

## Disengage

Moving out of a *zone* that contains an enemy leaves the *disengaging* force vulnerable to an additional attack.

### Enemy Disengages

If your **enemy** disengages, you can immediately make a free attack against them, interrupting their turn either **before** they move out of your zone or **after** they do so, your choice. 

### You Disengage

If **you** *disengage*, make a *disengage roll*. Roll **2d6 + TACTICS** and apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | :- |
| **2–6** | Your opponent immediately makes a **free attack** against you as you disengage. |
| **7–9** | You disengage but suffer a *complication*. |
| **10–12** | You disengage without mishap. |
| **13+** | You disengage without mishap and can optionally take an **extra** move this turn without spending an action. |

</div>

## Mobs

When facing a large number of relatively weak, identical opponents, such as a rabble of untrained militants, they may merge into a *mob*. A mob is treated as a **single** opponent in combat rather than as many individuals. This abstraction speeds up gameplay and allows for large swarms of nonhuman opponents.

### Mob Stats

The mob's *armor rating* and *attacks per round* depend on the number of members in the group, as follows:

| Number | Armor | Attacks |
| :-: | :-: | :-: |
| 1–4 | 2 | 1 |
| 5–8 | 1 | 2 |
| 9–12 | 1 | 3 |
| 13–16 | 0 | 4 |
| 17–20 | 0 | 5 |
| 21+ | 0 | 6 |

The number of attacks per round determines how many individual opponents the mob can attack during its turn in a single combat round. If there are fewer opponents than the mob's number of attacks, the remaining attacks are wasted.

!!! note

	You’ll notice that armor increases as the number of opponents decreases. The mob isn’t equipping more body armor. Rather, larger mobs are less spread out, increasing their target density.

Regardless of a mob’s size, its *damage modifier* is fixed, typically **+1**.

!!! example

	You face **10** street thugs. The GM merges them into a mob. The resulting mob, composed of the 10 thugs, has **1** armor and can attack up to **3** times. The GM sets its damage modifier to **+1**.

### Attacking a Mob

For each point of damage a mob takes, its member count decreases by **1**. The member count can be considered the mob’s HP.

!!! note

	When you and other team members attack the same mob, all damage is cumulative.<br/>Mobs are an exception to the general rule that cumulative damage doesn’t apply when attacking a target. See [Multiple Attackers](#multiple-attackers).

As a mob’s member count decreases, its stats change when it crosses the threshold for the next size down. When a mob reaches **0** members, it’s eliminated.

!!! example

	You face a mob of **14** members with **0** armor and **4** attacks. You attack and deal **4** points of damage, reducing the mob to **10** members. Because the mob is smaller, its stats change to **1** armor and **3** attacks.
