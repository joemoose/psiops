EDITS - zone source

Here's a full developmental edit of `zones.md`, issue by issue.

---

## Developmental Edit: Tactical Zones

### Preliminary Observation: Two Drafts, Not One Chapter

The document contains a primary draft followed by a section labeled `ALTERNATE DRAFT` that partially overlaps with, partially contradicts, and partially extends the primary draft. The alternate draft's weapon engagement table is the most complete version of range rules in the entire file and doesn't appear anywhere in the primary draft. Before this chapter can be edited into shape, you need to decide which draft is canonical and salvage the unique content from the other. The notes below treat the primary draft as the base and flag where alternate draft content should be promoted.

---

### Issue 1 — Missing Section Title
**Section:** The unnamed `### SECTION_TITLE` heading under *Tactical Zones*

**Problem:** Placeholder text. The section covers zone construction — how a GM defines and lays out zones before or during play. This is foundational procedural content and needs a real heading.

**Recommendation:** Title it something like `### Defining Zones` or `### How Zones Are Built`. More importantly, note that this section is written *to the GM* ("the GM sketches the scene") while the surrounding text addresses players. If this chapter is player-facing, the construction procedure should be reframed — or split into a GM sidebar/admonition block. If the chapter serves both audiences, that should be declared at the top.

---

### Issue 2 — Section Order: Range Introduced Before Movement
**Section:** `## Zone Distances` appears before `### Zone Movement`

**Problem:** A new player reading linearly encounters the range table (hop counts, range bands) before they know how movement between zones works. They don't yet know what "crossing into an adjacent zone" means or costs, so the range table lacks context. Suppressed zones and difficult terrain in the movement section also affect tactical range decisions, but the player hasn't read that yet when they hit the range table.

**Recommendation:** Swap the order. Present `Zone Movement` first — how you get between zones, what it costs, what stops you — then introduce `Zone Distances` as a consequence of adjacency. Range becomes legible once movement is understood.

---

### Issue 3 — `### Zone Ranges` is an Empty Stub
**Section:** `### Zone Ranges` (the two-word section reading only "Advantage, disadvantage")

**Problem:** This is a placeholder note to yourself, not a section. It signals that weapon range rules exist but provides nothing usable. A player who reaches this heading gets nothing actionable.

**Recommendation:** This is exactly where the weapon engagement table from the Alternate Draft belongs. Promote that table here, rename the section `### Weapon Ranges by Zone`, and cut the stub. If the full range rules live in a separate weapons chapter, this section should at minimum explain the *principle* (weapons have optimal engagement distances, not hard max ranges) and cross-reference that chapter explicitly: *"See [Weapons, p. XX] for full engagement tables."*

---

### Issue 4 — Zone Trait Table is Incomplete Relative to the Trait List
**Section:** The Zone Traits table under `### SECTION_TITLE`

**Problem:** The traits table lists five traits (Burning, Darkness, Elevated, Dense Cover, Contaminated), but the adjacency/property prose above it mentions additional traits by name — Cover, Elevated, Open Ground, Chokepoint, Obscured, Hazardous — that don't all appear in the table. "Open Ground," "Chokepoint," and "Obscured" have no defined mechanical effects anywhere in the document. A player (or GM) trying to apply these traits has no rules to stand on.

**Recommendation:** Audit the full trait list against the table and reconcile them. Either add the missing traits with their mechanical effects, or remove the names from the prose and list only what the table actually defines. This is also a content completeness flag — if these traits are fully defined in another chapter, add a cross-reference here.

---

### Issue 5 — The Zone Example Table is Disconnected from the Diagram
**Section:** The four-zone example table (Loading Dock / Catwalks / Office Block / Main Floor) and the `### Example` ASCII diagram

**Problem:** These two examples use completely different scenarios. The table describes an industrial interior (catwalks, office block, loading dock), while the diagram depicts an outdoor military scene (forest edge, kill zone, research facility, garage). Neither example is developed enough to show a player how zone adjacency actually *plays* — they're both structural sketches. The tactical choices listed after the diagram ("Suppress the kill zone / Flank through the garage") are the most useful part, but they're orphaned from any explanation of how the system produces them.

**Recommendation:** Commit to one example and develop it fully: show the zone sketch, the adjacency list, one or two trait assignments, and then a brief example-of-play paragraph — two or three exchanges where the zones visibly shape decisions. Cut or relocate the other sketch. The diagram note ("should be a stylized diagram, perhaps with a hand-drawn feel") is a production note that doesn't belong in the manuscript body; move it to a design/layout sidebar or a separate notes document.

---

### Issue 6 — Scope: GM-Only Construction Detail in a Player-Facing Section
**Section:** `### SECTION_TITLE` (zone construction procedure)

**Problem:** The instruction "the GM sketches the scene as 3–6 zones" and the adjacency-as-node-graph guidance is GM prep content. A player doesn't need to know how many zones the GM draws or that adjacency "doesn't need to be to scale." What a player needs from this section is: *what is a zone, how do I know which one I'm in, and what does being in one mean for my actions?*

**Recommendation:** Split this section. Keep the player-facing content (what a zone is, what traits mean, how adjacency governs range) in the main text. Move the construction guidance ("3–6 zones," "node graph on scratch paper," "declare it verbally") to a GM admonition block or a dedicated GM chapter. This is the single biggest scope problem in the document.

---

### Issue 7 — "Philosophical Difference from Grids" and "Tactical Depth" Are Misplaced
**Section:** `### Philosophical Difference from Grids` and `#### Tactical Depth Without Precise Geometry`

**Problem:** These sections argue *for* the zone system — they're selling the design to a skeptical reader. That's introduction or preface material, not mid-chapter content. Placing them after the mechanical rules means a reader who's already confused by the zone/movement/range sections hits a philosophical argument when they want clarification.

The `#### Tactical Depth` subsection is also over-leveled — a fourth-level heading (`####`) for content that is substantively parallel to the third-level heading above it creates a false hierarchy.

**Recommendation:** Move both sections to the opening of the chapter, before any mechanical content, as a brief orientation ("Why zones instead of grids?"). If you want them available as reference for skeptical mid-read players, a single pull-quote or sidebar version works better than inline prose at this position. Collapse the `####` into the `###` above it or make them parallel headings.

---

### Issue 8 — "Advantage/Disadvantage" Referenced Without Definition
**Section:** Throughout — Zone Traits table, `### Zone Ranges` stub, weapon engagement table in Alternate Draft

**Problem:** The terms *advantage* and *disadvantage* are used as mechanical shorthand throughout, but this chapter never defines what they mean in PsiOps. A new player reading this chapter doesn't know if advantage means bonus dice, a flat modifier, a reroll, or something else. This is a forward reference without a pointer.

**Recommendation:** Add a one-sentence inline definition on first use ("*Advantage* means [X]; see [Core Mechanics, p. XX] for the full rule"), or add a cross-reference callout box near the first instance in the traits table.

---

### Issue 9 — Alternate Draft Range Table Should Not Be Buried
**Section:** `ALTERNATE DRAFT` → weapon engagement table

**Problem:** This is the most mechanically complete content in the entire file. It defines how every weapon category performs across zone distances and is directly necessary for players to make combat decisions. It is currently inaccessible because it's labeled as an alternate draft and sits after a section break.

**Recommendation:** This table belongs in the main text under `### Weapon Ranges by Zone` (see Issue 3). The prose framing from the alternate draft — "weapons have optimal engagement distances" rather than hard max ranges — is also a cleaner framing than anything in the primary draft and should replace the stub entirely.

---

### Issue 10 — Suppressed Zones: Mechanic Referenced, Never Defined
**Section:** `### Zone Movement` — "Suppressed zone: entering a zone under active fire requires a test"

**Problem:** "Suppressed zone" is introduced as a movement modifier, but *suppression* as a game state is never defined here. What creates suppression? How long does it last? Who can suppress? What does "a test" mean — which skill, against what difficulty? This single bullet point opens three separate rules questions it doesn't answer.

**Recommendation:** Either expand this into a proper rule (even two or three sentences covering how suppression is established and resolved), or move it to a Suppression section elsewhere and replace the bullet here with a cross-reference: *"See [Suppression, p. XX]."* Do not leave it as-is — it's a dangling mechanic.

---

### Summary: Recommended Chapter Structure

Given all of the above, here's a suggested reorganization:

1. **Introduction / Why Zones** (content from "Philosophical Difference" sections, moved up)
2. **What Is a Zone** (definition, traits table — reconciled and complete)
3. **Zone Movement** (movement actions, terrain costs, free transitions)
4. **Zone Distances** (hop count table — follows naturally from movement)
5. **Weapon Ranges by Zone** (the engagement table from the Alternate Draft, promoted here)
6. **One Developed Example** (single scenario, sketch → adjacency → example of play)
7. **GM Sidebar: Sketching Zones** (the construction guidance, scoped to GM use)