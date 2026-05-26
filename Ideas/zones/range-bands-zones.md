# Range Bands and Zone

This is a rich design space, and the tension you're navigating is a real one in TTRPG theory: **relational distance** (range bands, which are dyadic — A is Close to B) versus **positional space** (zones, which are topographic — A is *in* the Courtyard). The two approaches solve slightly different problems, and how you combine them determines almost everything downstream.

---

## The Core Design Decision

**Range bands** are fundamentally about *pairs of combatants*. They answer: how far apart are these two people? The classic implementation (Traveller, WEG Star Wars, Cortex+) puts each combatant-pair on a linear track: Engaged → Close → Medium → Far → Extreme. It's clean for one-on-one, but gets combinatorially messy with larger groups — you'd need to track a band for every pair, which collapses the abstraction.

**Zones** solve the group problem by making position a property of the *scene*, not of pairs of combatants. Everyone in The Doorway has the same relationship to everyone in The Courtyard. FATE Core's zone system is the most fully worked-out modern implementation, and it's worth knowing: zones are named, freeform, connected by adjacency, and can carry tags (Dim Lighting, Rubble, etc.). Range becomes a function of zone-hop distance rather than a separate track.

If you want to preserve all five of your priorities — movement, range, cover, tactical choices, spatial relationships — **zones are your primary layer** and range bands can be derived from zone adjacency rather than tracked separately.

---

## A Framework Sketch

**Scene geography:** Before the fight, sketch 3–6 zones. Name them evocatively. Define which zones border which. That adjacency graph *is* your tactical map.

> The Nave / The Chancel / The Side Chapel / The Bell Tower Stairs

**Range derived from adjacency:**
- Same zone → Engaged (melee, grapple)
- Adjacent zone → Close (pistols, thrown weapons, short bows)
- One zone removed → Medium (rifles, longbows)
- Two or more zones removed → Far/Extreme (sniping, artillery)

Movement costs one action to cross one zone boundary, modified by zone traits.

**Zone traits carry the tactical texture:** This is where cover, elevation, chokepoints, and hazards live — attached to the zone itself, not to individual combatant pairs. A zone can be:
- *Cover* — ranged attacks into this zone suffer a penalty
- *Elevated* — ranged attacks *from* this zone gain a bonus; melee entry costs extra movement
- *Difficult* — movement into this zone costs double
- *Exposed* — no cover, perhaps even a penalty to defense
- *Hazardous* — lingering here costs something each round

**Tactical choices emerge from zone geometry:** Who controls the chokepoint (the one zone adjacent to everything else)? Does your archer get to the elevated zone before the enemy closes? Do you split the party to attack from two non-adjacent zones, preventing the enemy from being in cover against both simultaneously? Flanking becomes "attacking from zones that aren't adjacent to each other," which the zone graph makes visible.

---

## Where Range Bands Still Earn Their Place

Range bands as a *secondary* concept are still useful for one thing: **within-zone differentiation**. If a zone is large (a marketplace, a throne room), you might want to distinguish between being Engaged with a specific opponent versus merely sharing their zone. A simple binary — *Engaged* (locked in melee) versus *Free* (in the same zone but not actively grappling) — handles this without reinstating a full band track.

You could also use bands as a **quick-and-dirty system for simpler scenes** with few combatants, and switch to full zone maps for set-piece fights. Having both in the toolkit, with zones as the richer tool, gives you flexibility.

---

## A Few Design Tensions to Resolve

**Is cover personal or positional?** Zone-as-cover means everyone in a zone benefits equally, which simplifies bookkeeping. But it removes the choice of *taking* cover — which is a satisfying tactical decision. One solution: zones have a cover *capacity* (this zone can protect up to 2 people), and taking cover costs an action. Beyond capacity, the benefit is denied.

**How do you handle distance between non-adjacent zones?** You need a rule for "how many zone-hops is Far vs. Extreme." Either count hops explicitly, or set a scene-wide rule: in this encounter, Far = 2 hops, Extreme = 3+. The second option lets you scale the system to scene size.

**Movement economy:** The risk with zone systems is that movement becomes trivially cheap, and the map collapses into meaninglessness. Charging across zones should feel costly — either a dedicated move action (no attack that turn), a reduced action economy (move and attack but at penalty), or zone traits that make some crossings dangerous.

---

## Existing Systems Worth Pillaging

- **FATE Core** — The zone system is the gold standard for this design philosophy. Even if you're not building a FATE game, the chapter on zones is essential reading.
- **Blades in the Dark** — Uses position (Controlled/Risky/Desperate) as a quasi-spatial abstraction layered over fiction; not zones per se, but the design philosophy of "what's the situation?" over "where exactly are you?" is instructive.
- **Cortex Prime** — Has range bands as a modular option; shows how they interact with dice pools rather than hit points.
- **Shadow of the Demon Lord** — Zone-adjacent approach with a simple Close/Near/Far/Farther track; low overhead, worth examining for economy of design.

The core insight threading all of them: **the map is a set of meaningful decisions, not a measurement tool**. If a zone or band doesn't create a tactical choice, it shouldn't exist.

What direction are you pulling the system — more narrative-light (FATE-flavored), more crunchy-tactical, or something in between? That would shape which tradeoffs to lean into.