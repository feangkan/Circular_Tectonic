# Systemic Map: Material → Fabrication → Precedent → Strategy

**Purpose of this document.** Task 1 of the weekly brief asks for material research that leads to fabrication — not two disconnected lists. This document restructures the research done so far (`05_Material_Research/`, `07_Computational_Design/`, `08_Fabrication_Methods/`) into a single chain per material: **what the material is → how it actually gets fabricated → who has actually built something this way (precedent, any scale, pavilion where possible) → what design/structural strategy the fabrication method served.** The point is that a fabrication method is never neutral — every precedent below chose it to solve a specific problem, and that problem-and-solution pairing is the real transferable lesson, not just "this material can be joined this way."

This is also the template going forward: every future material this project considers should be run through this same four-step chain before it's added to the catalogue, so material research stays connected to buildability from the start rather than being reconciled with fabrication later.

---

## Chain 1 — Reclaimed Structural Steel Sections → Welding / Bolted Aggregation → Precedent: Temp'L Pavilion (Shinslab, Seoul, 2016)

**Material:** Reclaimed steel sections from a decommissioned ship hull, cut into structural fragments (List A, `RECLAIMED_METAL_SCRAP.md`).

**Fabrication method:** The ship's steel was cut (torch/plasma cutting) into an inverted hull-section form, then minimally reinforced — <cite index="61-1">the hollowed-out volume is stabilised by connected spherical elements that provide the minimum structural reinforcement needed to hold the overall shape</cite>. This is welding/fabrication used sparingly, as *reinforcement of an already-strong found form* rather than building a structure from scratch.

**Strategy:** <cite index="61-1">The architects deliberately left the material's origin visible — rusty, rough surface texture retained — using a "utilitarian process" that reassigns new meaning and value to the material rather than disguising it.</cite> The fabrication decision (minimal intervention, exposed surface) was in service of a communication strategy: the object had to still *read* as "old ship" to make its point about reuse.

**Lesson for this project:** When the reclaimed material already has a strong found geometry (a curved ship hull section, a large single structural fragment), the fabrication strategy can be "reinforce and preserve" rather than "cut down and rebuild." This is a genuinely different mode from most of the other precedents below, worth keeping in mind if any large single metal-scrap fragment gets sourced.

---

## Chain 2 — Reclaimed Steel Sections (Inventory-Constrained) → Bolted/Dry-Joint Frame Assembly → Precedent: Antepavilion 2026 Shortlist Entries (London)

**Material:** Mixed reclaimed steel sections plus reclaimed timber, explicitly drawn from a fixed available inventory rather than sourced to spec. <cite index="58-1">Entries were required to reuse existing construction materials including scrap steel from a set inventory at Hoxton Docks.</cite>

**Fabrication method:** <cite index="58-1">One shortlisted entry's metal armature is fabricated from available reclaimed steel sections in the inventory and assembled as a series of straightforward, repeatable components</cite> — i.e. bolted/dry-jointed assembly designed around whatever sections the inventory actually contained, rather than a pre-fixed design that inventory is later matched to. <cite index="58-1">The design brief itself is described as "inspired by medieval construction methods" — a structure deliberately frozen in a scaffolding-like stage, where the scaffolding itself becomes the ornament.</cite>

**Strategy:** This is the clearest working example of **inventory-first design** — the exact "reversed design process" also described in the EPFL reuse literature below (Chain 5): the stock of available reclaimed elements is fixed first, and the structure's form follows from what's actually on hand, rather than a form being decided first and materials sourced to match.

**Lesson for this project:** Directly validates the Week 3 "Graded Frame" pavilion concept and the growth-algorithm's own logic (agents responding to local constraints rather than a fixed global form) — this is architecturally the same idea, applied at the level of *sourcing strategy* rather than computation.

---

## Chain 3 — Reclaimed Metal Sheet → Fold/Bend + Bolted Dry-Joint (Welding-Free) → Precedent: Thin-Shell Metal Woven Pavilion (XISUI Design, China, 2020–2023)

**Material:** Thin steel/metal plate, 2.5mm gauge, used as sheet stock rather than sectional stock — directly comparable to `List C` in `RECLAIMED_METAL_SCRAP.md` (this precedent uses new sheet, but the fabrication chain transfers directly to reclaimed sheet of similar gauge).

**Fabrication method:** <cite index="69-1">Only two layers of 2.5mm-thick metal plate span 4,400 times their own thickness, and — critically — this is a welding-free construction: bolts are used for point-to-point seams from foundation to main volume instead.</cite> <cite index="69-1">Each bolt position is digitally designed and verified in advance, specifically to avoid the form-finding errors that come with a conventional manual welding process.</cite>

**Strategy — this is the standout lesson of the whole systemic map:** <cite index="69-1">Its structural logic is explicitly biomimetic — modelled on the mechanics of vaulted historic buildings and bird eggshells in nature</cite>, i.e. this precedent is simultaneously biomorphic/growth-informed (the "natural mimicry" behaviour this project's Week 4 direction is built around) AND uses sheet metal AND uses dry-joint bolted assembly instead of welding. <cite index="69-1">The stated reason for choosing bolts over welding was explicitly circularity-related: bolted parts, or even the entire structure, can be replaced or relocated, which is exactly what allowed this pavilion to be dismantled and rebuilt at a new site two years after first assembly.</cite>

**Lesson for this project:** This single precedent connects every strand of this week's research — biomorphic structural logic, metal sheet as the primary material, and dry-joint fabrication chosen specifically to preserve disassembly. It should be treated as the closest match to this project's overall direction found so far and studied in more depth (full case study write-up recommended as a follow-up task).

---

## Chain 4 — GFRC / Cast Concrete Panels → Casting + Discretised Bolted/Cast-In Connections → Precedent: "Thinking Space / Testing Space" (Henriksen, Allan, Knaack, Lo — Arup HQ Artwork Competition, 2015), building on Jörg Schlaich's Stuttgart Garden Pavilion (1977)

**Material:** GFRC panels — in this project's case, ideally sourced from fabricator offcuts/rejects (`RECLAIMED_GFRC.md`, List A) rather than new production.

**Fabrication method:** <cite index="149-1">96 free-form thin-walled GFRC panels, ~1.2m×1.2m each, sprayed on a digitally-driven flexible mould table whose shape was generated directly from the same parametric model that defined the overall hyperbolic form — allowing 48 unique moulds to be produced cost-effectively rather than requiring fixed moulds per panel.</cite> Three connection types were engineered and compared: bolted latch plates, a cast-in stainless steel angle, and an embedded anchor system.

**Strategy:** The project explicitly compared a monolithic shell (cast as one piece — structurally cleaner, 12.7mm max deflection) against a discretised, panel-and-connection shell (buildable and disassemblable, but 32.3mm max deflection and entirely dependent on connection engineering) — <cite index="149-1">concluding the discretised approach was structurally feasible provided the connection detail was properly developed and tested.</cite> This traces back to <cite index="149-1">Jörg Schlaich's 1977 Stuttgart Garden Pavilion, the first project to propose GFRC as a genuinely structural (not just cladding) material for complex-geometry shells, built from 7 identical shells cast in-situ and then connected.</cite>

**Lesson for this project:** Full case study in `06_Precedent_Research/GFRC_PRECEDENT.md`. The core transferable lesson: connection points and casting geometry must be co-designed from the start using the same parametric model, and a flexible/reconfigurable mould is the direct answer to GFRC's biggest obstacle for a growth-algorithm output — many unique, non-repeating panel shapes that a fixed-mould production process couldn't handle economically.

---

## Chain 5 — Reclaimed Sports Equipment (Skis) → Elastic Bending / Constrained Grid-Shell → Precedent: Ski Pavilion (EPFL Structural Xploration Lab, Switzerland, 2017)

**Material:** 210 reclaimed skis — not metal, but included here because the fabrication *logic* is the most directly transferable precedent to a growth-algorithm-driven, dimensionally-variable reclaimed-material structure found in this entire research pass.

**Fabrication method:** <cite index="91-1">The individual reclaimed components are arranged in two directions to form a flexible grid of rectangles, built flat on the ground first; when the grid's edges are pulled inward, the flexible modules cause the whole grid to arch upward into its final shell shape, which is then locked in place.</cite> <cite index="91-1">Crucially, different ski types (downhill, slalom, cross-country, freeride) were tested and deliberately placed at strategic points in the structure according to their individual mechanical properties</cite> — i.e. the design process explicitly graded and assigned individual variable pieces to specific structural roles, exactly the Re-SPLAM/"Graded Frame" logic already established in Week 3's research, but here fully built and measured.

**Strategy:** <cite index="90-1">The structure's typology (an elastic gridshell) was set as a design constraint from the start, on the basis that reclaimed sporting equipment suited to bending should also be plausibly locally sourced</cite> — sourcing feasibility directly shaped the choice of structural typology, not the other way around. <cite index="92-1">The measured result: the reclaimed-ski gridshell has an 85% lower cumulative embodied energy demand than an equivalent gridshell built from new timber.</cite> <cite index="89-1">The whole system is also designed to be disassembled and reassembled multiple times without scaffolding, using only traditional hand tools — it has since toured to at least four different cities.</cite>

**Lesson for this project:** This is the strongest available proof-of-concept that (a) grading reclaimed material by individual mechanical property and assigning pieces accordingly is a buildable, measurable strategy, not just a computational abstraction, and (b) an elastic/tensioned form-finding approach (pulling a flat grid into a 3D shell) is itself a legitimate "growth-adjacent" fabrication technique worth comparing against the Kangaroo2 differential-growth approach in `07_Computational_Design/`. Also directly informs the project's own catalogue's "grading before design" principle already stated in `01_Weekly_Tasks/Week_03_ConceptPinUp/02_Material_Catalogue.md`.

---

## Chain 6 — CLT Production Offcuts → Polygonal Shell Shaping → Precedent: DTC Timbershell

**Material:** CLT (cross-laminated timber) door and window cut-offs, roughly 1m×1m and 2m×1m rectangular offcuts — genuine factory production waste, not damaged material (`RECLAIMED_WOOD.md`, List B).

**Fabrication method:** <cite index="125-1">Rectangular CLT cut-offs from door and window openings are shaped into polygonal elements that form a wood-only shell structure</cite> — the offcut's actual available boundary is treated as the starting geometry, rather than trimming it down to fit a pre-decided panel shape.

**Strategy:** This solves the exact problem flagged in the general reclaimed-wood literature — <cite index="115-1">irregularly shaped off-cut wood is widely considered hard to reuse specifically because of its complicated geometry and the lack of established design methods for working with it</cite> — by inverting the usual design order: geometry follows the offcut, not the other way around.

**Lesson for this project:** Directly extends the stripe-segmentation lesson from the main precedent (`06_Precedent_Research/MAIN_PRECEDENT_THIN_SHELL_METAL.md`) to wood — a growth-algorithm-generated surface pattern could be matched against actual available CLT offcut shapes the same way THEVERYMANY's stripes are cut to a computed pattern, but here the offcut boundary is a starting constraint rather than a design choice.

---

## Chain 7 — Reclaimed Timber (Mixed Grades) → Parametric Structural Distribution → Precedent: Wood ReFramed

**Material:** Reclaimed timber of unknown/variable structural properties (`RECLAIMED_WOOD.md`, List A).

**Fabrication method:** <cite index="125-1">A parametric design approach distributes material according to its structural requirements rather than producing complex geometry for its own sake — computational optimisation is used specifically to counter the unknown material properties that come with reclaimed stock.</cite>

**Strategy:** The same "grade then assign" logic as Chain 5 (EPFL Ski Pavilion), now confirmed as a repeated pattern across three separate academic/research projects (EPFL, ITKE's Reclaimed Design, and this one) — strong evidence this is the field-standard response to reclaimed-material variability, not a one-off technique.

**Lesson for this project:** Reinforces that this project's own catalogue-first, grade-before-design approach (established since Week 3) is aligned with current academic practice across multiple institutions and material types, not just a convenient assumption.

---

## Cross-Chain Synthesis Table

| Chain | Material | Fabrication | Precedent | Core Strategy Transferred |
|---|---|---|---|---|
| 1 | Reclaimed steel (large found fragment) | Minimal-intervention welding/reinforcement | Temp'L Pavilion | Preserve found form; fabricate only enough to stabilise it |
| 2 | Reclaimed steel sections (fixed inventory) | Bolted/dry-joint modular frame | Antepavilion 2026 | Design follows available stock, not the reverse |
| 3 | Reclaimed/thin metal sheet | Fold-informed biomimetic form + bolted dry joint | Thin-Shell Metal Woven Pavilion | Biomorphic structural logic + disassembly-first fabrication choice |
| 4 | GFRC / cast panels | Discretised shell casting on a flexible mould table + engineered (bolted/cast-in/embedded) connections | "Thinking Space / Testing Space" (2015), building on Schlaich's Stuttgart Garden Pavilion (1977) | Co-design casting geometry and connections in the same parametric model; use a flexible mould for non-repeating panel shapes |
| 5 | Reclaimed sports equipment (skis) | Graded assignment + elastic bending into gridshell | EPFL Ski Pavilion | Grade material by measured property, assign to structural role, use elastic form-finding |
| 6 | CLT production offcuts (door/window cutouts) | Cutting/shaping into polygonal shell elements | DTC Timbershell | Treat each offcut's actual boundary shape as a design input, not a defect to fit into a pre-set grid |
| 7 | Reclaimed timber (mixed grades) | Parametric structural distribution | Wood ReFramed | Computational optimisation counters unknown material properties by placing capacity where it's actually needed |
| 8 | Glass fibre (in GFRC) | Basalt fibre substitution, same casting process | Basalt Fibre Reinforced Precast Concrete Panels | Drop-in fibre swap for lower carbon/cost without changing the established casting or connection method |
| 9 | Reclaimed/irregular timber | Discrete mortise-tenon joinery, standardised connection rules | Xu, Teixeira & Shafiei (2025), building on Sanchez's Combinatorial Design (2016) & Combo-Nest (2019) | Standardise the joint rules, not the material — let the connection system absorb dimensional variability instead of requiring uniquely-graded pieces |
| 10 | Reclaimed rope | Biomimetic tension-to-compression reversal, bundled/coiled brick modules | Recycled Rope Pavilion (Leinemann \| Ortiz) | Study behaviour under a different loading condition than the material is naturally suited to, design a module shape to make the reversal work |
| 11 | Reclaimed fishing net | Existing commercial fibre-recycling infrastructure → woven/knitted skin | ¡Qué Faena(r)! (+cruz.atelier) | Leverage an already-established recycling supply chain rather than inventing a new processing method |

## What This Means for Next Steps (not yet done — flagging for follow-up)

1. **Chain 3 (Thin-Shell Metal Woven Pavilion) deserves a full standalone case study** — it's the single best-matched precedent to this project's stated direction and hasn't been researched beyond what's captured here.
2. **Chain 5's grading methodology should be tested at small scale** — once real metal scrap is sourced (per `RECLAIMED_METAL_SCRAP.md`), a simple property test (visual grading, or basic bend test) on a handful of pieces would validate whether the "graded assignment" strategy is realistic for this project's timeline, before committing to it as the primary structural logic.
3. **This four-step chain format should be applied to any new material added to the catalogue going forward** — per your note that the actual outcome needs to follow the weekly task structure as a system, not disconnected research documents.
