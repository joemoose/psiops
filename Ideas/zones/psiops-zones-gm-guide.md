# Running Tactical Zones
### PSIOPS GM Reference — Combat Scene Design

---

## The Two Distance Scales

PSIOPS operates at two distinct spatial scales that flow into and out of each other as the pace of play shifts.

**Operational distance** governs narrative movement — traveling between locations, approaching a target, maneuvering through terrain. These distances are deliberately imprecise. *The safehouse is three blocks north. The bunker is close, but you'll be exposed crossing the field.* You add precision only when a player's question demands it, and only as much as the fiction requires. No one needs to know the field is 90 meters unless they're calculating whether a specific weapon can suppress it.

**Tactical zones** engage when the situation requires structured positioning — typically when a firefight, breach, or other high-stakes physical confrontation makes spatial relationships matter. Zones remain active until the situation resolves, then the scene returns to operational distance language.

The transition is fluid. A team that spends two turns of narrative play stacking on a door and moving one operator to cover the alley has already established position. When Combat Mode opens, those positions carry over. The zones formalize what the fiction already implied.

---

## When to Open Combat Mode

Combat Mode isn't just for gunfights. Open it whenever the spatial stakes get high enough that position and movement should have mechanical weight:

- An ambush is triggered
- A player takes a violent action and initiative is called
- A hostile threat requires structured tracking (active pursuit, a countdown while hostiles converge)
- A player asks a positioning question that demands a real answer: *"Can I get to the generator room before they do?"*

When in doubt, ask yourself: *does it matter who is where right now?* If yes, name the zones.

---

## Building a Scene in Zones

### Step 1: Identify Tactical Significance

Before naming anything, ask: *what parts of this location create meaningful choices?* You're not mapping the building — you're identifying the positions that matter.

Four questions to guide you:

1. Where can people take cover or gain elevation?
2. Where are the choke points and approach routes?
3. Where is the open ground — the killing field?
4. Where are the objectives, hazards, or things worth fighting over?

Anything that doesn't answer at least one of those questions probably doesn't need to be its own zone.

### Step 2: Name Zones Functionally

Names are load-bearing. Players navigate by them. A name should tell the player what the zone *is* tactically, not just where it is geographically.

| Weak | Strong |
|---|---|
| North corner | Sniper Nest |
| Middle of the road | Kill Zone |
| Top floor | Overwatch |
| Room 3 | Hostage Room |
| Behind the cars | Hard Cover |

When a player hears *Killzone*, they know not to run across it without suppression. The name does tactical work before any rules are consulted.

### Step 3: Define Adjacency

Adjacency is your map. Two zones are adjacent if you can cross the boundary between them in a few seconds at a sprint. Sketch it as a node graph — a handful of circles connected by lines. It does not need to be to scale. It only needs to answer: *what borders what?*

```
          [Overwatch]
               |
[Alley] — [Courtyard] — [Main Entrance]
                              |
                        [Lobby / Choke]
                              |
                        [Objective Room]
```

This sketch establishes everything: range relationships, movement paths, chokepoints, and the sniper's vantage. The whole tactical scene in under ten seconds.

Declare adjacency clearly when opening Combat Mode. Players can't make good decisions about movement if they don't know what connects to what.

### Step 4: Assign Traits

Traits define each zone's tactical character. Assign them when building the scene. Most zones should have at least one.

---

## Zone Traits Reference

### Cover
Hard barriers — vehicles, concrete walls, sandbag emplacements, heavy machinery. Ranged attacks *into* this zone from 2+ hops suffer Disadvantage. At Engaged range, Cover is irrelevant — the attacker is past it.

*Examples: vehicle wreckage, cargo containers, reinforced doorframe, rubble pile*

### Partial Cover
Soft concealment — furniture, foliage, chain-link, shadows. Attacks into this zone from 2+ hops suffer Disadvantage. Adjacent attackers are unaffected — they can angle around it.

*Examples: office furniture, dense shrubs, parked motorcycles, low wall*

### Elevated
High ground — rooftops, balconies, catwalks, raised platforms. Ranged attacks *from* this zone to lower zones gain Advantage. Attacks *into* this zone from lower zones suffer Disadvantage (bad angle, awkward exposure). Melee entry into an Elevated zone costs an extra move — you have to climb.

*Examples: rooftop, fire escape landing, catwalk, watchtower, second-floor window*

### Exposed
No cover, clear sightlines in all directions. Crossing this zone (entering or leaving) triggers a reaction-fire opportunity from any enemy with line of sight. Being stationary here: anyone targeting you gains Advantage on ranged attacks.

A combatant already in an Exposed zone who hasn't moved can attempt to go to ground as a full action — declaring they're prone and using whatever minimal terrain exists. This is desperation, not cover.

*Examples: open field, rooftop approach, wide street crossing, cleared landing zone*

### Chokepoint
A bottleneck — doorway, narrow bridge, stairwell, breach point. Only one character per side may enter this zone per round (or two, if they accept Disadvantage on defense). Defenders in an adjacent zone gain Advantage on attacks against anyone passing through.

The Chokepoint is the defender's greatest gift. An operator stacked on the near side of a Chokepoint zone can hold against multiples.

*Examples: doorway, hallway mouth, stairwell, bridge span, security gate*

### Obscured
Smoke, darkness, heavy rain, blinding flashbang aftermath, supernatural murk. Ranged attacks *through* this zone are at Disadvantage. Ranged attacks from 2+ hops *into* this zone are Impossible — no line of sight. Engaged and Nearby combat is unaffected (you're close enough to find them anyway).

Obscured is temporary unless the fiction says otherwise — smoke clears, dawn comes. Track it.

*Examples: smoke grenade cloud, power-out interior, heavy fog, supernatural interference*

### Hazardous
Active danger — burning wreckage, chemical spill, electrified water, structural collapse in progress, paranormal emanation zone. Anyone entering or remaining takes HP damage or makes a save each round. The GM sets the severity and type at scene creation.

A Hazardous zone can be tactically useful: enemies won't push into it willingly, and it creates natural barriers. A zone can become Hazardous mid-scene.

*Examples: burning vehicle, ruptured gas main, contaminated laboratory, psi-active anomaly zone*

### Difficult
Movement into this zone costs 2 actions instead of 1. Does not affect attacks or defense on its own — it just slows everything down, which creates its own tactical pressure.

*Examples: standing water, thick mud, rubble field, dense crowd, debris-strewn floor*

---

## Movement Rules

Movement is counted in zone crossings, not meters or feet.

**Standard Move:** Cross 1 zone boundary. The operator can still act this turn — shoot, interact, go to ground — unless something in your system restricts it.

**Sprint:** Cross 2 zone boundaries in a single turn. No other action. The operator is committed to movement.

**Tactical Advance (Covered Move):** Cross 1 zone boundary without triggering reaction fire. Uses the entire turn — no attack, no secondary action. Used specifically when crossing Exposed zones under observation.

**Entering a Suppressed Zone:** Entering a zone designated as suppressed requires a test. On a failure, the operator stops short or goes to ground in their current zone.

**Difficult Terrain:** Costs 2 moves to enter that zone. An operator with only 1 move can't enter — they stop at the boundary.

**Free Transitions:** Some movement is too small or uncontested to cost an action: slipping through an already-open interior door, repositioning within a large zone while not under fire, ducking from one piece of cover to another within the same zone. The GM narrates these rather than tracking them as movement actions.

---

## Range: Counting Zone Hops

Range is the minimum number of zone boundaries between the attacker and the target, following the adjacency graph.

| Hops | Range Label | Tactical Feel |
|---|---|---|
| 0 | **Engaged** | Same zone — in each other's space |
| 1 | **Nearby** | Adjacent zone — across the room, over a low wall |
| 2 | **Far** | One zone removed — across a street, through a window |
| 3 | **Distant** | Real marksmanship territory |
| 4+ | **Extreme** | Sniper work, or desperation |

Count the *shortest path* through the adjacency graph. If Zone A borders B, and B borders C, then A→C is 2 hops (Far range). There is no shortcut through non-adjacent zones.

---

## Weapon Engagement Ranges

Range and zone distance drive the Advantage/Disadvantage/Impossible modifiers on attacks. The table below uses your weapon categories; adjust column labels to match your range names.

| Weapon | Engaged | Nearby | Far | Distant | Extreme |
|---|---|---|---|---|---|
| **Close-quarters combat** | — | Impossible | Impossible | Impossible | Impossible |
| **Sidearm** | — | Advantage | Disadvantage | Impossible | Impossible |
| **SMG** | — | Advantage | Disadvantage | Impossible | Impossible |
| **Shotgun** | — | — | Disadvantage | Impossible | Impossible |
| **Assault Rifle** | Disadvantage | — | — | — | Impossible |
| **LMG** | Impossible | — | Disadvantage | Disadvantage | Impossible |
| **Heavy Weapon** | Impossible | Disadvantage | — | — | — |
| **Sniper Rifle** | Impossible | Disadvantage | Advantage | — | — |
| **Thrown** | — | — | Impossible | Impossible | Impossible |

**Reading the table:** Advantage means roll with bonus. Disadvantage means roll with penalty. Impossible means the action cannot succeed at that range — no roll. Blank means unmodified.

**Design note on Assault Rifle at Engaged:** The Disadvantage at Engaged for long weapons is intentional and realistic — rifles are awkward in a grapple. It creates genuine incentive to draw a sidearm when an enemy closes, which is a satisfying tactical decision that mirrors real close-quarters doctrine.

---

## Line of Sight

LOS is declared, not calculated. When building the scene, note which non-adjacent zones have line of sight to each other.

- **Adjacent zones** have LOS by default unless a trait blocks it (Obscured, a solid wall)
- **Non-adjacent zones** may or may not have LOS — declare this explicitly at scene setup
- A sniper on Overwatch may have LOS to every zone on the map; a team in the basement may not see the courtyard even though it's technically adjacent

Write it on your zone sketch: *"Overwatch has LOS to Courtyard and Main Entrance, not Alley or Lobby."*

LOS can change mid-scene. Smoke fills a zone — LOS through it is blocked. A wall gets blown out — LOS opens up.

---

## The Transition: Narrative to Combat Mode

**Opening Combat Mode (30 seconds at the table):**

1. Name all zones in the scene and their traits
2. Declare adjacency — which zones border which, and any non-adjacent LOS
3. Place every combatant into a zone
4. Call initiative

The fiction that preceded the fight is preserved. If operators spent turns during narrative play moving to flank the target building, they're already in the Alley zone when Combat Mode opens. Honor what the fiction established.

**Running the transition aloud:**

> *"Okay, the ambush is triggered — here's what you've got. The Street is wide open, Exposed — you don't want to be there when the shooting starts. The Alley runs along the east side, it's tight, Chokepoint. The target building's Lobby is through the main doors — Cover inside. The Overwatch position is on the roof across the street; it has LOS to everything except the Alley. Everyone tell me where you are."*

Give players one clear sentence per zone. That's enough to orient and start making decisions.

**Returning to Narrative Mode:**

When the fight resolves, breaks off, or transitions to a chase or investigation, drop zones and return to operational language. Zone tracking stops. There's no ceremony — just shift the language.

---

## Dynamic Zones: Changing the Battlefield

Zones are not static. The GM should actively evolve them as the scene develops. Dynamic zone states create memorable moments and reward players who pay attention to the environment.

**Trait escalation examples:**

| Trigger | Zone Change |
|---|---|
| Operator throws smoke | Zone becomes Obscured |
| Operator flips a vehicle | Zone gains Cover |
| Explosive hits | Cover zone may become Exposed; adjacent zones may become Hazardous |
| Fire spreads | Hazardous zone expands to adjacent zone |
| Lights shot out | Zone becomes Obscured |
| Hostile takes a prone position behind debris | Personal Cover (one character; doesn't change zone trait) |

**Improvised traits mid-scene:** Players can spend an action to create a zone trait under the right conditions. Throw smoke (Obscured). Drag a dumpster into position (Cover for one person). Barricade the stairwell door (upgrade Chokepoint). This rewards tactical creativity and gives players meaningful environmental interaction beyond just shooting.

---

## GM Design Principles

**Fewer zones, richer traits.** Three zones with strong tactical identities beat six zones that are just empty space. If two zones feel the same, collapse them.

**Every zone should create at least one question.** *Do I want to be here? Can I take that zone? What happens if they push me into the open?* A zone that doesn't generate decisions isn't earning its place.

**Name for function.** The name is the first thing players encounter. *Killzone* does more work than *Center of the Road*. *Breach Point* does more than *Doorway*. Front-load the tactical implication in the name.

**Don't over-engineer adjacency.** If a character could sprint from one place to another in a few seconds, they're probably adjacent. Resist the urge to make fine distinctions the players won't be able to track.

**Reward spatial thinking.** When a player asks *"Can I use the fire escape to flank the Overwatch zone?"* — say yes, probably, with a move. The zone system exists to enable creative positioning decisions, not to constrain them.

---

## Example Zone Scene: Compound Extraction

**Mission brief:** Extract asset from a rural research facility. Intel suggests a security team has already arrived.

**Zones:**

```
         [Guard Tower]
              |
[Forest Edge] — [Approach Road] — [Compound Gate]
                                        |
                              [Courtyard — Exposed]
                               /               \
                     [Admin Block]         [Laboratory]
                                               |
                                         [Basement Lab]
```

**Zone traits:**

- **Forest Edge** — Cover, Obscured (night canopy)
- **Approach Road** — Exposed (no cover, open ground both directions)
- **Compound Gate** — Chokepoint (one through at a time; gate mechanism)
- **Guard Tower** — Elevated (LOS to Approach Road and Courtyard; not Forest Edge or interior zones)
- **Courtyard** — Exposed (open ground; crossing triggers reaction from Gate or Tower)
- **Admin Block** — Cover (desks, filing cabinets, hard interior walls)
- **Laboratory** — Cover, Hazardous (chemical storage; if ignited, spreads)
- **Basement Lab** — Difficult (equipment crowding the floor), Obscured (no windows)

**Tactical questions this layout forces:**

- Do we take out the Guard Tower before crossing the Approach Road, or risk the sprint?
- Can we breach the Admin Block to reach the Courtyard without exposing ourselves at the Gate?
- The asset is in the Basement Lab. Getting out means crossing the Courtyard again — or finding another route.
- If the Lab ignites, the Hazardous trait could spread to the Courtyard mid-extraction.

That's a complete scene with meaningful decisions, evolving terrain, and real pressure — built from eight zone names and a handful of trait assignments.

---

## Quick Reference

```
RANGE
  Engaged   — same zone
  Nearby    — 1 hop
  Far       — 2 hops
  Distant   — 3 hops
  Extreme   — 4+ hops

MOVEMENT
  Standard Move:      1 zone, still act
  Sprint:             2 zones, no action
  Tactical Advance:   1 zone, no action, no reaction fire triggered
  Difficult Terrain:  costs 2 actions to enter
  Suppressed Zone:    requires test to enter

ZONE TRAITS
  Cover          — attacks in from 2+ hops: Disadvantage
  Partial Cover  — attacks in from 2+ hops: Disadvantage; adjacent unaffected
  Elevated       — attacks from here: Advantage; attacks in from below: Disadvantage
  Exposed        — crossing triggers reaction fire; attacks in: Advantage
  Chokepoint     — 1 combatant through per round; defenders: Advantage
  Obscured       — ranged through: Disadvantage; 2+ hops in: Impossible
  Hazardous      — damage/save per round in zone
  Difficult      — costs 2 actions to enter

LINE OF SIGHT
  Adjacent zones: LOS by default unless blocked
  Non-adjacent: GM declares at scene setup
  LOS can change mid-scene (smoke, destruction)

COMBAT MODE TRIGGER
  When position and movement need mechanical weight, name the zones.
  When the situation resolves, return to operational distance language.
```

---

*PSIOPS GM Reference — Tactical Zones v0.1*
