# Damage

Your job is inherently dangerous. It might be a question of when, not if, you’re wounded. This section explains how to take damage and recover from it.

## Hit Points

*Hit points* (HP) represent your physical health. When you take damage, subtract the damage from your current HP. Keep track of your HP. Your character sheet includes spaces to record your maximum and current HP.

- If you have at least **1 HP** remaining after taking damage, you’re still in the fight.
- If your HP drops to **0 or below**, you’re *wounded*, possibly grievously. See the next section.

## Wounded

Once *wounded*, with **0** or fewer HP, immediately make a *wound roll*. Roll **2d6 + STRENGTH**, then **subtract** the number of HP you’ve fallen below zero. If your HP is exactly zero, subtract nothing. Apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | - |
| **6–** | You're **dead**. Roll up a new operator. |
| **7–9** | You're *incapacitated* at **0 HP**. Take **2** *wounds*, **2** *fatigue*, and **2** *stress*. You'll die unless *stabilized*. See [Stabilize Team Members](#stabilize-team-members). |
| **10–12** | You’re *knocked down*, unconscious but stable at **1 HP**. Take **1** *wound*, **1** *fatigue*, and **1** *stress*. A team member can revive you by spending **1** *action*.<br/>**Note**: If you’re wearing a helmet, you’re knocked down but remain conscious. Spend **1** *action* to climb to your feet. |
| **13+** | You take **1** *wound* but stay on your feet. Set your current HP to **1d6**, up to your maximum after reducing it from the wound. See [Wounds](#wounds).<br/>You're one tough SOB. |

</div>

See [Wounds](#wounds), [Fatigue](#fatigue), and [Stress](stress.md) for details on these conditions.

!!! note

	If knocked *unconscious* and pushed to *maximum stress*, you still make a *stress roll*. Any resulting *panicked* or *locked-in* conditions take effect once you revive. See [Maximum Stress](stress.md#maximum-stress).

!!! example

	You have 2 STRENGTH and 2 current HP, and take 3 points of damage. You now have -1 HP and must make a *wound roll*.

	You roll **2d6 + 2** (STRENGTH) and subtract **1** (the number of current HP points below zero). You roll a 4 and a 5. The sum is 4 + 5 + 2 - 1 = 10. You're *knocked down*, but not *unconscious* because you're wearing a *helmet*. You would have been knocked out otherwise  You add **1** wound, **1** fatigue, **1** stress, and increase current HP to **1**.

	You spend **1** action to get back on your feet. You’re wounded, growing tired, and a little more stressed, but not yet out of the fight.

### Wounds

Each *wound* you sustain reduces your *maximum HP* by **1**. Your current HP remains unchanged unless it exceeds the new maximum. If it does, reduce your current HP to the new maximum. Wounds **can’t be healed** in the field and require medical treatment at the base after the mission.

!!! important

	Wounds cause permanent HP loss until treated at base. If multiple wounds reduce your maximum HP to **0**, you **die**. Roll up a new operator.

### Fatigue

All *fatigue* you sustain must be stored in your **inventory** as an abstract item. Each unit of fatigue takes up **1** slot. If your inventory is full, drop equipment to free a slot for fatigue.

!!! important

	Accumulated fatigue is debilitating. If your inventory reaches **12** units of fatigue, you **die**. Roll up a new operator.

## Restore HP and Fatigue

Lost *hit points* can be restored, and *fatigue* can be removed, by regrouping at a *rally point*. See [Rally Point](#rally-point).

Some *neural weapons* also restore lost HP and remove fatigue. See [Neural Weapons](character.md#neural-weapons).

!!! tip

	Experimental or anomalous medical restoratives are rumored to exist.

## Stabilize Team Members

Stabilizing an *incapacitated* team member requires medical supplies, such as the individual aid kit in your basic kit. Once medical supplies are available, you can stabilize a team member after combat or during the battle, as described in the following sections.

### After Combat

If you have medical supplies, you **automatically** stabilize an *incapacitated* team member **after** combat ends. After stabilizing your team member, remove the medical supplies from your inventory.

### During Combat

If you need to stabilize an *incapacitated* team member **during** combat, the action is complex and risky, and it uses a *mission clock* to track progress. The clock typically has 4 segments. See [Mission Clocks](playing.md#mission-clocks).

To **stabilize a team member in combat**, first acquire medical supplies, then make a *stabilization roll*. Roll **2d6 + TACTICS**. Apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | - |
| **6–** | You do **not** mark off a segment on the mission clock and **use up** your medical supplies. Remove them from your inventory.<br/>You’ll need to acquire additional medical supplies to continue making *stabilization rolls*. |
| **7–9** | Mark off **1** segment on the mission clock. |
| **10–12** | Mark off **2** segments on the mission clock. |
| **13+** | Mark off **3** segments on the mission clock. |

</div>

Once all segments are marked off the clock, the incapacitated team member is stabilized. Remove the medical supply you used from your inventory.

### Stabilized

Once you're *stabilized*, you're back on your feet and combat-effective, though at **0** HP. Until you're *patched up* at a *rally point* and recover lost HP, any damage you take immediately reduces your HP below zero, triggering a *wound roll*. See the next section.

## Rally Point

Once per mission, your squad can fall back to a designated *rally point*. The rally point is a location where you and your team members can rest and regroup. A rally point is typically a concealed, defensible position. The GM will tell you where it is if your squad decides to rest and regroup during the mission.

!!! warning

	There are only enough supplies at the rally point for your squad to rest and regroup **once** during the mission.

### Rest and Regroup

Reaching the *rally point* automatically resets the following effects:

- You lose your current *momentum*, which resets to its starting value of **2** points. If you have fewer than 2 momentum, it increases to 2.
- Any *neural weapons* that are no longer usable reactivate.
- Remove all *panicked* and *locked-in* effects.

Additionally, you may choose **one** benefit from the following options:

| Benefit | Description |
| - | - |
| INTEL | Ask a single question about the mission, and the GM will reply with a “yes” or “no.” |
| PATCH UP | If you have medical supplies, such as the individual aid kit in your basic kit, recover **1d6 HP** up to your *maximum HP*.<br/>You can patch up yourself or a team member. After patching up, remove the medical supply from your inventory.<br/>Note that *wounds* reduce your maximum HP. Wounds can’t be healed at the *rally point*. See [Wounds](#wounds). |
| RECUPERATE | Remove **1d3** *stress* and **1d3** *fatigue* from yourself. |
| RESUPPLY | Add **1** *tactical supply* to your or a team member’s inventory. |

## Backfill

If your character dies, create a new one while the game continues. When you’re ready to rejoin your squad, make a *backfill roll*. Roll **2d6 + TACTICS** and apply the result as follows:

<div class="roll-table" markdown="1">

| Roll | Result |
| :-: | - |
| **6–** | You join the squad, possibly taking damage while deploying. Make a *defense roll* with *advantage*. See [Defending](combat.md#defending). Armor reduces damage. |
| **7–9** | You join the squad, but deployment comes with a *complication*. |
| **10–12** | You join the squad. |
| **13+** | You join the squad and may optionally add **1** *tactical supply* to your inventory. |

</div>



