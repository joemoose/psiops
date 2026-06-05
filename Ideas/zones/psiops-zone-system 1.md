# Zone System: Design Reference
### PSIOPS — Tactical Positioning Without Grids or Range Bands

---

## What Zones Are (and Aren't)

A **zone** is a named area of tactical significance. It answers: *What kind of position is this, and what does it mean to be here?* Not *exactly where is everyone standing?*

Zones replace the grid, the ruler, the range band, and the miniature. They are the GM's tool for transmitting "here is the battlefield" in a sentence or two. Players orient around questions of *position and choice*, not measurement.

A zone is **not** a room, not a fixed size, not a square on a grid. It is the smallest unit of space that creates a meaningful tactical decision.

> **Design heuristic:** If being *here* vs. *there* doesn't change what you can do, it's not a zone — it's just scenery.

---

## Building a Scene in Zones

Before or during combat, the GM sketches the scene as 3–6 zones. Name them evocatively — names are load-bearing, because players navigate by them.

Each zone gets three things:

1. **A name** — *Loading Dock / Street / Overpass / Alley Mouth*
2. **Adjacency** — which other zones it borders (determines engagement and range)
3. **Traits (optional)** — Cover, Elevated, Open Ground, Chokepoint, Obscured, Hazardous

Adjacency is the map. You can sketch it as a node graph on scratch paper in 30 seconds, or just declare it verbally. It does not need to be to scale or spatially accurate. It only needs to answer: *what borders what?*

**Zone count by scene type:**

| Scene Type | Zones |
|---|---|
| Tight interior (hallway, small room) | 2–3 |
| Building / compound | 3–5 |
| Urban street fight | 4–6 |
| Open terrain (field, rooftop complex) | 3–5 |

Fewer zones = faster, less granular. More zones = slower, more tactical texture. For PSIOPS, lean toward 3–5 as a default.

---

## Range: Zone-Hop Distance

Range is the **minimum number of zone boundaries** between you and your target, following adjacency connections.

| Hops | Range Band Label | Flavor |
|---|---|---|
| 0 | **Contact** | Same zone — in each other's faces |
| 1 | **Close** | Adjacent zone — across the room, over a barrier |
| 2 | **Medium** | One zone removed — across a street, through a window |
| 3+ | **Long** | Far enough to need optics or real marksmanship |

Count the *shortest path* through the adjacency graph. If Zone A borders B, B borders C, then A→C is 2 hops (Medium).

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

**Reading the table:** Advantage = roll with advantage (or bonus die, or +modifier, per your resolution system). Disadvantage = roll with disadvantage. Impossible = no roll; the action simply cannot succeed at that range. Normal = unmodified roll.

**Design note on Contact disadvantage for rifles:** The Disadvantage at Contact for long guns reflects real doctrine — rifles are awkward in a grapple. This creates a meaningful pull toward drawing a sidearm when an enemy closes, which is a satisfying tactical decision.

### Optional: Zone Trait Modifiers Stack with Range

Zone traits (below) modify *defense*, not attack range. So a target behind Cover in an adjacent zone forces: attack at **Close** range with the **Cover** penalty. These are independent axes.

---

## Zone Traits

Zone traits are properties of a zone that apply to everyone in it (or attacking into/out of it). The GM assigns traits when building the scene. Players can sometimes *create* traits mid-combat (lay smoke, flip a table).

### Standard Traits

**Cover**
The zone has hard concealment — barriers, vehicles, walls. Attacks *into* this zone from non-adjacent zones suffer Disadvantage. At Contact range, Cover doesn't apply (you're past it).

**Partial Cover**
Soft concealment — bushes, light furniture, shadows. Attacks into this zone from 2+ hops suffer Disadvantage. Adjacent attackers are unaffected.

**Elevated**
High ground — overpass, rooftop, balcony. Ranged attacks *from* this zone to lower zones gain Advantage. Attacks *into* this zone from lower zones suffer Disadvantage (bad angle). Melee entry into this zone costs an extra move.

**Open Ground**
No cover, exposed sight lines. Crossing this zone (entering or leaving) triggers reaction fire from any enemy with line of sight to this zone. Being stationary in Open Ground: anyone targeting you gains Advantage on ranged attacks.

**Chokepoint**
A bottleneck — doorway, narrow bridge, stairwell. Only one character per side may enter per round (or two, if willing to accept Disadvantage on defense). Defenders in an adjacent zone gain Advantage against attackers passing through.

**Obscured**
Smoke, darkness, heavy rain, blinding light. Ranged attacks *through* this zone are at Disadvantage. Ranged attacks at 2+ hops *into* this zone are Impossible. Contact and Close attacks unaffected. Lasts until cleared.

**Hazardous**
Fire, chemical spill, electrified water, collapsing structure. Entering or remaining in this zone costs HP (or a save) per round. Amount and type set by GM at scene creation or as the scene evolves.

### Creating Traits Mid-Scene

Players and NPCs can generate traits as actions:
- *Throw smoke grenade → Obscured*
- *Flip a car / pull a shelf → Cover*
- *Kick out the lights → Obscured*
- *Take up a defensive position → Partial Cover (personal only)*

Improvised Cover (one character, one action) applies only to that character until they move. Full zone traits affect everyone.

---

## Movement

Movement is measured in zone crossings, not meters.

**Standard Move:** Cross 1 zone boundary. Can still act (shoot, interact) in the same turn unless your system restricts it.

**Sprint:** Cross 2 zone boundaries. No other action that turn.

**Covered Move (Tactical Advance):** Cross 1 boundary in a way that avoids triggering reaction fire. Costs the full turn — no attack. Used when crossing Open Ground without eating a reaction shot.

**Crossing Open Ground:** Triggers a reaction-fire opportunity from any enemy with line of sight to that zone. The moving character is considered undefended (Disadvantage on defense, or GM calls it a free shot) unless they use Covered Move.

**Difficult Terrain (zone trait):** Costs 2 moves to enter. Can be added to any zone (rubble, water, dense crowd).

---

## Narrative Mode vs. Combat Mode

PSIOPS runs in two modes, and the zone system behaves differently in each.

### Narrative Mode

Zones exist loosely. The GM describes the environment in terms that imply zones — *"You're inside the warehouse; the guards are outside covering the loading bay and the road"* — but nothing is formalized. Range, cover, and position are adjudicated by common sense and GM ruling.

When a player asks *"Can I get a clear shot?"* the GM answers by feel, based on the implied fiction.

### Combat Mode

**Trigger:** A player takes a violent action that enters a declared initiative sequence, or the GM decides the scene requires structured tracking.

**Transition (30 seconds):**
1. GM names the zones present and their traits
2. GM declares adjacency ("the street borders the alley and the lot; the rooftop only borders itself but has line of sight to the street")
3. Everyone is placed into a zone
4. Initiative runs

The zones established narratively carry over. If the players spent three turns of narrative play positioning themselves behind the dumpsters, that's still Cover in Combat Mode.

**Return to Narrative:** When the fight ends, dies down, or transitions into a chase or investigation, drop back to Narrative Mode. Zone tracking stops.

---

## Line of Sight

Zones use **declared line of sight**, not measured traces. When building the scene, the GM notes:

- **Adjacent zones** have LOS by default unless a trait blocks it (Obscured, or a wall)
- **Non-adjacent zones** may or may not have LOS — GM declares this at scene setup
- A sniper on a rooftop may have LOS to a zone two hops away; a combatant in a basement may not have LOS to the street even if it's adjacent

Write it on the zone sketch: *"Rooftop has LOS to Street and Lot, not Alley."*

---

## Running Zones at the Table: GM Guidance

**Keep zone count low.** Three zones with meaningful traits beat six zones that are all just empty space. Each zone should do something.

**Name zones for their function, not their geography.** *Killzone* instead of *Middle of the Road*. *Sniper Nest* instead of *Rooftop Corner*. Names carry tactical implication.

**Front-load the scene description.** When you declare Combat Mode, give one clear sentence per zone: *"The Street is Open Ground — crossing it will get you shot. The Alley is narrow, Chokepoint, and it connects to the Back Lot. The Back Lot has a dumpster — Cover. The Rooftop overlooks all of it."* Players should be able to visualize and plan from that.

**Let players use zones cleverly.** When a player asks *"Can I use the fire escape to get to the Elevated zone?"* — yes, probably, with a move. Reward spatial thinking.

**Zones can change mid-scene.** A wall gets blown out (Cover becomes Open Ground). Smoke fills a zone (add Obscured). A car catches fire (add Hazardous). Dynamic zone states create memorable moments.

**Don't over-engineer adjacency.** When in doubt: if you can run to it in a few seconds, it's probably adjacent.

---

## Quick Reference

```
RANGE = zone hops (0 = Contact, 1 = Close, 2 = Medium, 3+ = Long)

WEAPON MODIFIERS
  Knife/Baton:    Contact ADV | Close DIS | Med IMP | Long IMP
  Pistol:         Contact ADV | Close NRM | Med DIS | Long IMP
  SMG/Shotgun:    Contact NRM | Close ADV | Med NRM | Long DIS
  Carbine/AR:     Contact DIS | Close NRM | Med ADV | Long NRM
  Sniper:         Contact IMP | Close DIS | Med NRM | Long ADV

ZONE TRAITS
  Cover         — ranged attacks in from 2+ hops: Disadvantage
  Partial Cover — ranged attacks in from 2+ hops: Disadvantage; adjacent unaffected
  Elevated      — attacks from here: Advantage; attacks in from below: Disadvantage
  Open Ground   — crossing triggers reaction fire; attacks in: Advantage
  Chokepoint    — 1 combatant through per round; defenders: Advantage
  Obscured      — ranged through: Disadvantage; 2+ hops in: Impossible
  Hazardous     — damage/save per round

MOVEMENT
  Move:          1 zone, still act
  Sprint:        2 zones, no action
  Covered Move:  1 zone, no action, no reaction fire triggered
  Open Ground:   triggers reaction fire unless Covered Move
```

---

*PSIOPS Zone System — Design Reference v0.1*
