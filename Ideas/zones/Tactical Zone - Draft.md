# Tactical Zones - Draft

---

Zones are **discrete chunks of space** that matter tactically. They are not distances; they are **areas of influence**.

A zone is defined by:
- **What it contains** (cover, vantage, hazards)
- **How it connects** to other zones
- **How hard it is to move into/out of**

Think of zones as the answer to:  
**"What parts of this scene matter tactically?"**  
not  
**"Where exactly is everyone standing?"**

---

## A Zone Is:

> A tactically coherent position.

A zone is defined by:

* exposure,
* cover,
* elevation,
* visibility,
* access,
* movement difficulty,
* and tactical purpose.

Not size

## Modern Military Zone Design

Good combat zones in a military game tend to represent:

| Type               | Example                      |
| ------------------ | ---------------------------- |
| Cover position     | Sandbags, vehicle wreckage   |
| Exposure area      | Street crossing, open lot    |
| Interior space     | Office floor, stairwell      |
| Elevation          | Rooftop, balcony             |
| Chokepoint         | Doorway, breach point        |
| Concealed area     | Treeline, drainage ditch     |
| Tactical objective | Generator room, hostage room |

## Range

You still need weapon ranges to matter.

But range should emerge from:

* zone adjacency,
* not linear strips.

This becomes:

| Distance      | Meaning        |
| ------------- | -------------- |
| Same Zone     | Close quarters |
| Adjacent Zone | Short          |
| 2 Zones Away  | Medium         |
| 3+ Zones Away | Long           |
Instead of:

* "weapon has max range"

use:

> weapons have *optimal engagement distances*.

| Weapon       | Same Zone  | Adjacent   | 2 Away     | 3+ Away    |
| ------------ | ---------- | ---------- | ---------- | ---------- |
| Knife        | Adv        | Impossible | Impossible | Impossible |
| Pistol       | Adv        | Normal     | Disadv     | Impossible |
| SMG          | Adv        | Normal     | Disadv     | Impossible |
| Carbine      | Disadv     | Normal     | Adv        | Normal     |
| Battle Rifle | Disadv     | Normal     | Adv        | Adv        |
| Shotgun      | Adv        | Normal     | Disadv     | Impossible |
| Sniper Rifle | Impossible | Disadv     | Normal     | Adv        |

---

## What Zones Are (and Aren't)

A **zone** is a named area of tactical significance. It answers: *What kind of position is this, and what does it mean to be here?* Not *exactly where is everyone standing?*

Zones replace the grid, ruler, range band, and miniature. They are the GM's tool for transmitting "here is the battlefield" in a sentence or two. Players orient around questions of *position and choice*, not measurement.

A zone is **not** a room, not a fixed size, not a square on a grid. It is the smallest unit of space that creates a meaningful tactical decision.

> **Design heuristic:** If being *here* vs. *there* doesn't change what you can do, it's not a zone — it's just scenery.

## Range: Zone-Hop Distance

Range is the **minimum number of zone boundaries** between you and your target, following adjacency connections.

| Hops | Range Band Label | Flavor |
|---|---|---|
| 0 | **Contact** | Same zone — in each other's faces |
| 1 | **Close** | Adjacent zone — across the room, over a barrier |
| 2 | **Medium** | One zone removed — across a street, through a window |
| 3+ | **Long** | Far enough to need optics or real marksmanship |

Count the *shortest path* through the adjacency graph. If Zone A borders B, B borders C, then A→C is 2 hops (Medium).

## Weapon Modifiers by Zone Distance

This directly replaces the range-band advantage/disadvantage system. The logic is identical; the measurement tool is different.

| Weapon | Contact (0) | Close (1) | Medium (2) | Long (3+) |
|---|---|---|---|---|
| Knife / Baton | Advantage | Disadvantage | Impossible | Impossible |
| Pistol | Advantage | Normal | Disadvantage | Impossible |
| SMG / Shotgun | Normal | Advantage | Normal | Disadvantage |
| Carbine / AR | Disadvantage | Normal | Advantage | Normal |
| Sniper Rifle | Impossible | Disadvantage | Normal | Advantage |
| Thrown (grenade, etc.) | Normal | Normal | Disadvantage | Impossible |

---

## Weapon Modifiers by Zone Distance

This directly replaces the range-band advantage/disadvantage system. The logic is identical; the measurement tool is different.

| Weapon | Contact (0) | Close (1) | Medium (2) | Long (3+) |
|---|---|---|---|---|
| Knife / Baton | Advantage | Disadvantage | Impossible | Impossible |
| Pistol | Advantage | Normal | Disadvantage | Impossible |
| SMG / Shotgun | Normal | Advantage | Normal | Disadvantage |
| Carbine / AR | Disadvantage | Normal | Advantage | Normal |
| Sniper Rifle | Impossible | Disadvantage | Normal | Advantage |
| Thrown (grenade, etc.) | Normal | Normal | Disadvantage | Impossible |

### How it Plays Out in Practice

An assault rifle user in the *Security Checkpoint* wants to shoot an enemy in the *Main Lobby*. That is 1 Zone Border away (**Close Range** for an Assault Rifle = **Normal Roll**).

If that enemy runs up the stairs to the *Mezzanine Balcony*, they are now 2 Zone Borders away (Checkpoint $\rightarrow$ Lobby $\rightarrow$ Mezzanine). That is **Medium Range** for the Assault Rifle, granting them **Advantage**.

Furthermore, because the Mezzanine has the **[Elevated]** trait, the enemy might get a bonus to shoot down into the *Lobby*, but the rifleman on the ground has successfully found the weapon's sweet spot.

---

Zones answer a different question than range bands. Range bands ask, "How far apart are these two things on a line?" while zones ask, "What parts of the scene matter, and how do they connect?" In practice, that lets you model doors, rooftops, alleys, vehicles, cover positions, stairwells, and control points as meaningful tactical spaces rather than distances. [reddit](https://www.reddit.com/r/rpg/comments/90lzw5/combat_zones_in_grid_centric_rpgs/)

A useful mental model is: a zone is a space where movement is mostly free, but moving **between** zones is what costs actions, attention, or risk. Fate's zone rules treat the environment this way, and movement is typically one zone per exchange unless obstacles or opposition make it harder. Shadow of the Demon Lord also uses zones in a similarly abstract way, with zones divided by meaningful terrain and adjacency. [fate-srd](https://fate-srd.com/fate-system-toolkit/means-war-mass-combat)



