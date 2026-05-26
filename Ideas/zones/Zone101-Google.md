# Zone 101 - Google

It makes total sense that you're hitting a wall with *Shadow of the Demon Lord* (which leans more toward loose grid/theater of the mind) and the *Fate SRD* (which treats zones as narrative buckets rather than tactical friction).

If you want a modern, OSR-adjacent, tactical-but-gridless framework for your military/PSIOPS game, you need zones that act as **tactical terrain containers** rather than just abstract spots on a map.

Here is a practical 101 on how zones work when you strip away the narrative fluff and inject gritty OSR functionality, followed by a direct re-work of your weapon range mechanics.

---

## Zones 101: The OSR Military Framework

In a gritty, tactical game, a **Zone** is defined by its boundaries, its tactical traits, and its capacity. Instead of tracking *where* a character is down to the foot, you track *what environmental reality they are currently bound by*.

### 1. Anatomy of a Tactical Zone

Every zone you map out in a scene should have three explicit properties:

* **Capacity:** How many people can reasonably fit here before they become a crowded, easy target for area-of-effect (AoE) attacks (like grenades or PSIOPS blasts)?
* **Traits:** Environmental modifiers built right into the space. A zone isn't just "The Lobby"; it's "The Lobby [Open, Exposed]" or "The Server Room [Choke Point, Heavy Cover]."
* **Connections:** Which adjacent zones can you move to with a standard move action?

### 2. Movement and Positioning

* **Intra-Zone (Inside a Zone):** Moving *within* your current zone (e.g., diving from a desk to a filing cabinet) is usually part of a standard action or a minor move. You are altering your positioning relative to the zone's traits (moving from *No Cover* to *Heavy Cover*).
* **Inter-Zone (Between Zones):** Moving from your current zone to an adjacent, connected zone requires a dedicated Move Action. If an enemy is in that zone and monitoring the crossing, it triggers overwatch or opportunity attacks.

---

## Re-Working Your Weapon Ranges for Zones

Your original range-band system relied on a linear grid ($A \rightarrow B \rightarrow C$). Zones are non-linear; they form a web or a node-map.

To keep your **Advantage / Normal / Disadvantage / Impossible** matrix without a linear track, we translate "Range" into **"Zone Distance" (the number of zone borders a shot must cross).**

### The Zone-Distance Metric

* **Point-Blank:** Shared Zone (You and the target are in the exact same zone).
* **Close Range:** 1 Zone Border away (An adjacent zone).
* **Medium Range:** 2 Zone Borders away.
* **Long Range:** 3+ Zone Borders away.

Here is how you map your weapons to this new gridless spatial reality:

| Weapon Type | Point-Blank (Same Zone) | Close (1 Border Away) | Medium (2 Borders Away) | Long (3+ Borders Away) |
| --- | --- | --- | --- | --- |
| **Sidearms / Shotguns** | **Advantage** | Normal | Disadvantage | *Impossible* |
| **Carbines / SMGs** | Normal | **Advantage** | Normal | Disadvantage |
| **Assault Rifles** | Disadvantage | Normal | **Advantage** | Normal |
| **Sniper / Heavy** | *Impossible* | Disadvantage | Normal | **Advantage** |

### Tactical Nuance for a Military/PSIOPS Game

Because you are building a gritty, OSR-style game, the traits of the zones interacting with these ranges create instant tactical choices:

* **Line of Sight (LoS):** A rifle might have a "Normal" roll at 3 zones away, but if an intervening zone has the **[Dense Smoke]** or **[Concrete Walls]** trait, the shot becomes *Impossible* or suffers Disadvantage regardless of the weapon's ideal range.
* **Clearing a Zone:** If a PSIOPS agent fires a pistol inside the same zone (Point-Blank), they get Advantage. However, if that zone has the **[Choke Point]** trait, enemies might be tightly packed, allowing a shotgun or an AoE power to hit multiple targets without splitting damage.

---

## Step-by-Step Scene Setup (No Maps, No Minis)

When a structured combat scene breaks out, you can sketch a quick "node map" on a index card or simply declare it out loud.

1. **Identify the Anchors:** The tactical anchors.
Name the 3 to 5 distinct areas where the action will happen. E.g., *Zone A: The Security Checkpoint, Zone B: The Main Lobby, Zone C: The Mezzanine Balcony.*


2. **Assign Traits and Cover:** Environmental realities.
Give each zone its teeth. Security Checkpoint gets **[Heavy Cover, Choke Point]**. Main Lobby gets **[Open, No Cover]**. Mezzanine gets **[Elevated, Light Cover]**.


3. **Map the Connections:** Defining movement paths.
Determine who can go where. Security Checkpoint connects *only* to the Main Lobby. The Mezzanine Balcony connects to the Main Lobby (via stairs), but physically sits *above* it.


4. **Drop in the Combatants:** Initial positioning.
Place the PCs and enemies into the containers. *"The strike team is in the Security Checkpoint. The corporate muscle is patrolling the Main Lobby."*


### How it Plays Out in Practice

An assault rifle user in the *Security Checkpoint* wants to shoot an enemy in the *Main Lobby*. That is 1 Zone Border away (**Close Range** for an Assault Rifle = **Normal Roll**).

If that enemy runs up the stairs to the *Mezzanine Balcony*, they are now 2 Zone Borders away (Checkpoint $\rightarrow$ Lobby $\rightarrow$ Mezzanine). That is **Medium Range** for the Assault Rifle, granting them **Advantage**.

Furthermore, because the Mezzanine has the **[Elevated]** trait, the enemy might get a bonus to shoot down into the *Lobby*, but the rifleman on the ground has successfully found the weapon's sweet spot.

—

To keep that gritty, minimalist OSR flavor, we want to avoid complex mathematical tracking or sub-grids inside the zones. In an OSR-style game, the environment should feel lethal, and tactical decisions should be binary or highly impactful rather than minor incremental bonuses ($+1$ or $+2$).

Here is a streamlined, minimalist way to handle **Cover, Flanking, and Suppression** using the Zone framework.

---

## 1. Dynamic Cover: State Over Statistics

Instead of tracking precise positions, treat cover as a **state** a character actively chooses to occupy within a zone.

When you enter a zone, you don't automatically get its cover benefits. You must spend a minor action (or part of your movement) to **"Take Cover"** behind a specific asset.

* **No Cover:** The default state if caught in the open.
* **Light Cover:** (Debris, wooden desks, drywall). Enemies attacking you suffer **Disadvantage** on their attack rolls.
* **Heavy Cover:** (Concrete pillars, armored bulkheads, sandbags). Enemies attacking you suffer **Disadvantage**, and you gain **Advantage on saving throws/damage reduction** against incoming ballistic fire.

> **OSR Lethality Rule:** Cover is destructible. If an attacker rolls an attack with *Advantage* (due to weapon range) against a target in *Light Cover*, the cover is obliterated after the shot resolves.

---

## 2. Flanking: The "Crossfire" Condition

In a gridless zone, flanking isn't about being on opposite sides of a miniature; it's about forcing a target to defend against two conflicting angles. We call this **Crossfire**.

Because a character can only anchor themselves against cover in *one direction* at a time, Crossfire completely bypasses cover.

### How to Achieve Crossfire:

* **Intra-Zone Flanking:** Two attackers are in the *same zone* as the target, but they are anchored to different environmental pieces. The target's cover is negated against the second attacker.
* **Inter-Zone Flanking:** Attackers occupy *two different zones* that both have clear lines of sight into the target's zone.

```
[Zone A: PC 1] ───↘
                    [Zone B: Target in Cover] 
[Zone C: PC 2] ───↗

```

> **The Rule:** If a target is taking cover from Zone A, an attack originating from Zone C completely **ignores that cover**. If attackers in both Zone A and Zone C attack the target in the same round, all attacks gain **Advantage**.

---

## 3. Suppression: Locking Down the Zone

In a modern/military OSR game, automatic fire shouldn't just be about rolling more damage dice; it should be a tool for battlefield control. Suppression targets an **entire zone** or a **specific piece of cover**, not an individual person.

### The Mechanic: Laying Down Fire

As a main action, a character with an automatic weapon can declare they are suppressing a zone (or a specific piece of cover within it). They expend a significant amount of ammo.

Until the start of the suppressor's next turn, the targeted area becomes a **Hazard Zone**.

### The Effect on Enemies:

Any character currently in the suppressed area, or attempting to move *into* or *through* it, faces a brutal choice:

1. **Keep Your Head Down:** Stay pinned behind your current cover. You cannot move out of the zone or make ranged attacks. You are safe from damage, but tactically paralyzed.
2. **Break Cover / Move:** If you choose to act or move through the suppressed zone, you must immediately make a saving throw (or attribute check). Failure means you take automatic weapon damage as you run into the stream of lead. Success means you scramble through, but your action or movement suffers **Disadvantage**.

---

## Putting It Together: A Tactical Turn

Imagine a PSIOPS squad pinned down in a hallway zone:

1. **The Enemy Suppresses:** Enemy Turn.
A corporate merc with a heavy machine gun suppresses **Zone A (The Hallway)**. The PSIOPS squad is currently in Light Cover behind flipped cafeteria tables.


2. **The Pointman Stays Pinned:** PC 1 Turn.
The squad's Pointman decides to **Keep Their Head Down**. They don't take damage, but they lose their action this turn, completely pinned by the gunfire.


3. **The Telekinetic Flanks:** PC 2 Turn.
The PSIOPS Adept uses a power to teleport or slip into **Zone B (The Side Ventilation Lab)**, which connects to the Merc's zone. They are now attacking from a different angle.


4. **Crossfire Established:** Resolution.
Because the Adept is attacking from Zone B while the Pointman threatens from Zone A, the Merc is caught in a **Crossfire**. The Merc's heavy cover is negated, and the Adept fires their pistol with **Advantage**.


This framework keeps your math flat, relies entirely on player choices ("Do I risk running through the fire?"), and makes the spatial layout of your zones feel incredibly tactical without ever needing to know exactly how many feet apart anyone is standing.

—

To keep things fast and lethal in your OSR-style military game, PSIOPS powers shouldn't require measuring radii or templates. Instead, powers should interact directly with the **structural geometry of the zones** themselves—turning the environment from static theater-of-the-mind backdrops into something players can actively weaponize.

Here is how you can cleanly map psychic mechanics to your zone framework.

---

## 1. Area of Effect (AoE): Saturated vs. Structural

Without a grid, "AoE" is redefined by boundaries. Psychic blasts, psychic storms, or exploding telekinetic bursts affect spaces in one of two binary ways:

* **Zone-Wide (Saturated):** The power fills the entire target zone. Everyone inside—regardless of cover—must make a saving throw or take damage/effects.
> *Tactical Use:* This is the ultimate tool to flush enemies out of Heavy Cover or break a **Suppression** lock without needing an angle of attack.


* **Asset-Targeted (Structural):** The power targets a specific structural trait or piece of cover within a zone (e.g., exploding a concrete pillar or collapsing a ceiling). It hits only the targets anchored to that specific asset.

---

## 2. Line of Sight (LoS): Mind over Matter

In a military game, physical line of sight usually dictates where you can shoot. But PSIOPS introduces a terrifying tactical shift: **Cognitive Line of Sight**.

Because you are tracking encounters via zones, you can create three distinct visibility rules for psychic powers:

| Visibility State | Rule | Tactical Reality |
| --- | --- | --- |
| **Physical LoS** | You can see into the target zone via a connected border. | Standard ballistic rules apply. |
| **Cognitive LoS** | You cannot see the zone, but you *know* minds are there (via telepathic ping, sensors, or biometric links). | You can target the zone with mental/saving throw attacks, completely bypassing physical **Heavy Cover**. |
| **Blind / Blocked** | The zone is physically shielded (e.g., a lead-lined PSI-shield or a subterranean bunker zone). | No psychic powers can cross this zone border. |

---

## 3. Telekinetic Mechanics: Weaponizing Zone Traits

Telekinesis shouldn't just be about lifting heavy objects; it should be about shifting the tactical state of the scene. You can boil telekinetic actions down to three minimalist, high-impact maneuvers:

### A. The "Yank" (Altering Cover States)

Instead of dealing damage, a telekinetic can target an enemy anchored to cover within their current zone or an adjacent zone.

* **The Effect:** The player makes an attribute check against the target. On a success, the target is violently ripped from their asset into **No Cover**, or their Light Cover is physically torn away. This instantly sets them up for a lethal **Advantage** shot from a teammate.

### B. The "Shove" (Inter-Zone Displacement)

Telekinesis can force a target across a zone border.

* **The Effect:** A successful telekinetic strike blasts an enemy out of their current zone into an adjacent one.
* **The OSR Synergy:** If an enemy is blasted into a zone currently under **Suppression**, they instantly trigger the hazard penalty and take automatic weapon damage. If blasted into a zone with a hazardous trait (like **[Blazing Fire]** or **[Exposed Chasm]**), they face immediate environmental consequences.

### C. The "Bulwark" (Creating Dynamic Traits)

A psychic can assemble debris, desks, or even a localized gravity warp to physically alter a zone's properties on the fly.

* **The Effect:** As an action, the psychic adds the **[Light Cover]** or **[Choke Point]** trait to their current zone, or blocks a connection border entirely, preventing enemies from moving between two zones without spending a turn clearing the psychic debris.

---

## Putting it Together: The PSIOPS Combo

Here is a quick tactical sequence showing how ballistic suppression and psychic powers create a terrifying synergy using zero minis or grids:

1. **Lay Down Suppression:** Ballistic setup.
The squad's Gunner uses an LMG to suppress **Zone B (The Loading Dock)**. The corporate guards inside stay pinned behind their heavy metal crates, safe but trapped.


2. **Scan with Cognitive LoS:** Bypassing cover.
The squad's PSIOPS Adept stands in **Zone A (The Corridor)**. They can't physically see the guards behind the crates, but they lock onto their brainwaves (**Cognitive LoS**).


3. **Execute a Telekinetic Shove:** Manipulating the space.
The Adept unleashes a kinetic wave. They don't roll to damage; they roll to **Shove** the lead guard backwards out of their crate-cover asset.


4. **Trigger the Trap:** Lethal resolution.
The guard is physically thrown into the open space of the Loading Dock. Because that zone is currently a **Suppression Hazard**, the guard immediately takes automatic, lethal ballistic damage from the Gunner's active stream of fire.


By binding psychic powers to **Zone Borders, Zone Traits,** and **Cover States**, your rules stay entirely lightweight while giving players a massive mechanical sandbox to play with.

