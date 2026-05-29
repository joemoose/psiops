## Tactical Zones

Once the game enters *combat mode*, your battle space is represented by **tactical zones**. Tactical zones offer an abstract way to organize space in combat without exact measurements, grids, or miniatures. Instead of tracking whether someone is "27 feet away," the game divides the environment into meaningful, interconnected areas. 

### SECTION_TITLE

Before or during combat, the GM sketches the scene as 3–6 zones. The zones will use tactical layers, networked areas, or linear connections, without resorting to detailed maps.

A zone is **not** necessarily a room, a fixed size, or a square on a grid. It is the smallest unit of space that creates a meaningful tactical decision.

Each zone gets three things:

1. **A name** — *Loading Dock / Street / Overpass / Alley Mouth*
2. **Adjacency** — which other zones it borders (determines engagement and range)
3. **Traits (optional)** — Cover, Elevated, Open Ground, Chokepoint, Obscured, Hazardous

Adjacency is the map. You can sketch it as a node graph on scratch paper in 30 seconds, or just declare it verbally. It does not need to be to scale or spatially accurate. It only needs to answer: *what borders what?*

A zone may have properties, obstacles, or challenges of its own. The environment becomes easier to describe.

| Trait | Effect |
| - | - |
| Burning | Damage over time |
| Darkness | Visibility penalties |
| Elevated | Attack *advantage*|
| Dense Cover | Defense *advantage*|
| Contaminated | Requires protection or take damage | 

A zone is less a precise location and more a **tactically relevant space**.

Examples:

* ~~"The rusted-out catwalk."~~
* ~~"Behind the parked trucks."~~
* ~~"The ritual circle."~~
* ~~"The north trench."~~
* ~~"The burning hallway."~~

| Zone | Description |
| - | - |
| Loading dock | Crates, forklifts, open exterior |
| Rusted-out catwalks | Precarious walkways above the Main Floor |
| Office block | Windows and hard cover |
| Main Floor | Open, exposed space |

Zones simplify positioning while preserving:

* movement,
* range,
* cover,
* tactical choices,
* and spatial relationships.

## Zone Distances

Range is measured in zone hops — the number of zone boundaries between you and a target, following connections.

| Hops | Range |
|---|---|
| 0 | **Engaged** — same zone, sharing air |
| 1 | **Nearby** — across the room, over a barrier |
| 2 | **Far** — across a street, through a window |
| 3 | **Distant** — requires real marksmanship |
| 4+ | **Extreme** — sniper country |

Count the shortest path through connected zones — not a straight line on a map.

### Zone Movement

Characters move *between zones* rather than counting squares or meters.

Crossing into an adjacent zone consumes one movement action. You can still act afterward — fire, interact, or go to ground.

Some boundaries between zones complicate things:

- **Difficult terrain** (rubble, standing water, thick smoke): costs 2 actions to push through.
- **Suppressed zone**: entering a zone under active fire requires a test — fail, and you stop short or go to ground.
- **Free transitions**: slipping through an open interior door or moving within the same building floor. No action required; the GM narrates it.

### Zone Ranges 

Advantage, disadvantage

### Example

(the following should be a stylized diagram, perhaps with a hand-drawn feel)

```
[Forest Edge]
      |
[Kill Zone]
      |
[Research Facility]
   /          \
[Garage] — [Generator Room]
```

Now tactical choices emerge naturally:

* Suppress the kill zone
* Flank through the garage
* Destroy generator
* Breach facility

### Philosophical Difference from Grids

Zones are abstractions of battlefield spatial relationships, not accurate battlemaps with precise positioning. They provide a faster pace and enough structure for your actions, tactical decision-making, and interaction with the environment.

Grid combat asks:

> "Where is everyone standing?"

Zone combat asks:

> "Which part of the tactical landscape are you leveraging?"

That distinction is at the heart of PsiOps combat gameplay.

#### Tactical Depth Without Precise Geometry

A common misconception is that zones eliminate tactics.

Instead, they shift tactics away from:

* exact positioning
* geometry optimization
* movement counting

toward:

* controlling chokepoints,
* managing exposure,
* securing advantageous terrain,
* narrative positioning,
* timing,
* and pressure.


---

ALTERNATE DRAFT

*Tactical zones* treat the battlefield as a handful of meaningful areas—each with its own tactical properties—rather than a grid or a linear strip. Characters move between zones, not along gridlines. Ranges become **relationships between zones**, not measurements, to preserve tactical clarity

Zones are **discrete chunks of space** that matter tactically. They are not distances; they are **areas of influence**.

| Type               | Example                      |
| ------------------ | ---------------------------- |
| Cover position     | Sandbags, vehicle wreckage   |
| Exposure area      | Street crossing, open lot    |
| Interior space     | Office floor, stairwell      |
| Elevation          | Rooftop, balcony             |
| Chokepoint         | Doorway, breach point        |
| Concealed area     | Treeline, drainage ditch     |
| Tactical objective | Generator room, hostage room |

A zone is defined by:

- **What it contains** (cover, vantage, hazards)
- **How it connects** to other zones
- **How hard it is to move into/out of**

Think of zones as the answer to:  

**"What parts of this scene matter tactically?"**  

not  

**"Where is everyone standing?"**


### Range

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

