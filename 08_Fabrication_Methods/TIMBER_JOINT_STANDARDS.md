# Timber Joint Standards — Categorized Reference

Four categories, as requested, covering the standard joinery vocabulary this project can draw on for reclaimed timber assembly. Each entry notes its fit for genuinely irregular reclaimed stock, since that's the recurring constraint across all this semester's research (see `09_Systemic_Design_Framework/MATERIAL_FABRICATION_PRECEDENT_SYSTEM_MAP.md`, Chains 5, 7, 9).

---

## 1. Interlocking Joints

Joints that lock two pieces together through cut geometry alone, with or without glue/fasteners as secondary reinforcement.

| Joint | How It Works | Strength Notes | Fit for Reclaimed Stock |
|---|---|---|---|
| **Mortise & Tenon** | A protruding tenon on one member fits into a cut mortise (hole/slot) in the other | <cite index="25-1">Resists forces in all directions — the benchmark for structural furniture and framing; independent testing shows ~500 lbs capacity in oak</cite> | Good — this is the joint family behind Chain 9's discrete mortise-tenon research (Xu et al. 2025), directly tested for tolerance to irregular block sizes |
| **Dovetail** | Wedge-shaped "pins" and "tails" cut to interlock, wider at the base than the neck | <cite index="25-1">Superior tensile strength — mechanical interlock outlasts the timber itself; wedge shape physically prevents pulling apart</cite> | Moderate — requires precise cutting, harder to achieve by hand on irregular reclaimed sections without a jig |
| **Finger Joint / Box Joint** | Interlocking rectangular "fingers" cut into both mating ends, like interlaced fingers | <cite index="25-1">Highest end-grain strength (540 PSI) — ideal for end-grain-to-end-grain connections</cite>; <cite index="26-1">stronger than a butt or lap joint</cite> | Good — this is the exact joint geometry behind the ICD/ITKE biomimetic pavilion's ~100,000-joint timber shell (already documented in `06_Precedent_Research/BIOMORPHIC_COMPUTATIONAL_REFERENCES.md`), proven to scale to reclaimed/variable-length short pieces |
| **Half-Lap** | Both members notched to half their thickness at the overlap, sitting flush | <cite index="32-1">Weaker than mortise & tenon, but maintains uniform thickness across the structure — aesthetically cleaner</cite> | Good — simplest of the interlocking joints to cut on irregular sections, forgiving of dimensional variation |
| **Sliding Dovetail** | A dovetail tail slides into a tapered socket, tightening as it seats | <cite index="26-1">Tapered socket makes assembly easy but the joint self-tightens as it reaches final position</cite> | Good — the taper itself absorbs minor dimensional mismatch, useful for reclaimed stock with slightly inconsistent sections |

**Relevance to this project:** interlocking joints are the closest physical realisation of the "standardise the joint, tolerate the material" strategy from Chain 9 — finger joints and half-laps in particular don't demand perfectly uniform stock the way a tight dovetail does.

---

## 2. Groove & Tongue

| Joint | How It Works | Strength Notes | Fit for Reclaimed Stock |
|---|---|---|---|
| **Tongue & Groove** | A protruding "tongue" on one board's edge fits into a matching "groove" cut into the neighbouring board's edge | <cite index="29-1">Commonly seen ready-made on flooring stock — locks adjacent boards edge-to-edge, resists lateral separation while allowing the panel to expand as one continuous surface</cite> | Good — well suited to reclaimed sheet/board stock (formply, plywood offcuts, pallet deck boards) being joined edge-to-edge into larger skin panels |
| **Spline Joint** | A separate thin strip ("spline") inserted into matching grooves cut into both mating edges, rather than a tongue integral to one piece | Functionally similar to tongue & groove, but the spline can be a *different* material (e.g. plywood spline between two solid timber edges) | Excellent for reclaimed stock — the spline being a separate piece means it doesn't need to match the two host pieces' species or condition, only their groove dimension |
| **Rabbet (Rebate)** | A step-shaped recess cut into the edge of one board, into which a second board's edge or a panel infill sits flush | <cite index="33-1">Simple joint, much stronger than a butt joint — allows a flat piece like a cabinet back to sit flush with both sides for a seamless finish</cite> | Good — simple to cut on irregular board thickness, forgiving |
| **Dado** | A groove cut *across* the grain (not at the edge) into which a perpendicular panel slots | Used for shelving/partition joints — <cite index="31-1">offers excellent strength and resistance to pulling forces but requires precision to execute properly</cite> | Moderate — precision-dependent, better suited to consistent-thickness stock (e.g. sorted formply/plywood batches) than raw reclaimed sections |

**Relevance to this project:** groove & tongue methods are the natural choice for joining reclaimed *sheet* stock (formply, plywood, pallet deck boards) into larger continuous skin panels — directly usable for Concept A's "Grown Skin" direction if realised in timber rather than metal.

---

## 3. Timber & Metal Joints

Connections where a metal fastener or connector plate does the load transfer, rather than the wood-to-wood cut geometry itself.

| Connector Type | How It Works | Strength/Use Notes | Fit for Reclaimed Stock |
|---|---|---|---|
| **Plate & Bolt** | A steel plate (flat, angle, or T-shaped) bolted to the faces of two timber members, transferring load through the bolts in shear | <cite index="41-1">Steel plate connectors between mass timber panels can be engineered with a defined stiffness threshold — moving as one body under normal loads, but allowing controlled, ductile deformation under extreme events (earthquake, high wind)</cite> — the same "engineered give" logic used in structural steel connection design | Excellent — this is the most tolerant connector type for irregular reclaimed sections, since bolt holes can be oversized/slotted to absorb dimensional mismatch between mating pieces |
| **Toothed/Spike Plate Connector** | A metal plate with pre-punched teeth, pressed (via hydraulic press or high-strength bolt) directly into the timber face on both sides of a joint, teeth embedding into the wood grain | <cite index="36-1">Only for small connector diameters up to 65mm can a mild steel bolt press the teeth in — larger connectors need a hydraulic press; large washers are required to prevent crushing the wood</cite>; <cite index="42-1">toothed-plate connectors measurably reduce timber destruction in the bearing zone, though they don't fully protect against splitting, and reinforcement can increase joint stiffness by up to 2.9× while slightly reducing peak strength</cite> | Moderate — effective but the pressing/teeth-embedding step needs relatively sound, non-degraded timber to work; less suited to weathered or split reclaimed sections |
| **Split Ring Connector** | A circular steel ring set half-embedded into a matching groove cut into each of two mating wood faces, bolted through the centre | <cite index="38-1">Used for wood-to-wood joints; the load transmits across the joint through the ring, not the bolt alone — historically effective but now less common due to the precision required in fabricating the matching grooves</cite> | Poor-moderate — the precision-groove requirement makes this a bad match for genuinely irregular reclaimed sections; better suited to new, consistently-milled timber |
| **Shear Plate Connector** | A round steel plate embedded flush into a precut recess ("dap") in the timber face, used for wood-to-steel or demountable wood-to-wood connections | <cite index="38-1">Manufactured in 2⅝" and 4" diameters; particularly useful in demountable structures since plates can be pre-installed and held with nails, then bolted together on site</cite>; <cite index="35-1">primarily used in glulam, heavy sawn timber, and structural composite lumber — not typically used in CLT panel assembly</cite> | Good — the demountability feature aligns directly with this project's disassembly principle; works well for the structural-section timber (glulam, reclaimed beams) in the catalogue rather than sheet stock |
| **3D-Printed Connector** | A custom-designed node printed to match the exact measured geometry of the specific timber pieces it joins | Already documented in this project's own precedent research — <cite index="0-0">the Bamboo Pavilion (Academy Bezalel) uses 3D-printed nylon/resin connectors custom-fitted to each individual pole's measured diameter and angle, solving natural dimensional variability directly at the connector stage</cite> | Excellent — the single best-matched connector type for genuinely irregular reclaimed stock, since the connector geometry adapts to the material rather than requiring the material to be sorted/matched to a standard connector; directly dependent on CUHK's Hong Kong-phase fabrication access |

**Relevance to this project:** this category is where the project's two competing computational strategies (grade-then-place vs. standardise-the-joint) become concrete hardware choices. Plate & bolt and shear plate connectors both tolerate irregular material well and are achievable before Hong Kong fabrication access opens; 3D-printed connectors are the most precise but wait on that access.

---

## 4. Mass Timber Connections

Connection systems specific to engineered mass timber panels (CLT, glulam) — directly relevant given the project's catalogue includes CLT production offcuts (WD-04) as a leading material candidate.

| Connection Type | How It Works | Technical Notes | Fit for This Project |
|---|---|---|---|
| **Self-Tapping Screws (STS)** | Fully-threaded structural screws driven directly into the mass timber panel, transferring load through thread engagement rather than shear on the screw shaft | <cite index="37-1">Mostly used to connect mass timber panels in floor-to-floor, wall-to-wall, and floor-to-wall joints, with or without additional steel hardware; fully-threaded screws made from higher-strength steel change the failure mechanism, allowing the connection to resist perpendicular-to-grain crushing and shear-along-grain splitting — both brittle failure modes that otherwise limit timber connection capacity</cite> | Good — the current industry-standard connection method for CLT, directly applicable to WD-04/WD-05/WD-06 (CLT offcuts, CLST, deconstructed panels) |
| **Glued-In Rods (GiRods)** | Threaded steel rods bonded into pre-drilled holes in the timber with structural epoxy, transferring load through the adhesive bond along the rod's embedded length | <cite index="37-1">One of the two most common modern mass timber fastening systems alongside self-tapping screws — neither is directly addressed by current US (NDS) or Canadian (CSA O86) timber design standards, meaning engineering judgement/testing is still required rather than simple code lookup</cite> | Moderate — high load capacity but requires careful epoxy work and isn't yet fully standardised; more appropriate for a later-phase structural connection than an early prototyping one |
| **Concealed/Exposed Steel Plate Connectors** | Standard steel angle brackets or plates, exposed or routed into a concealed pocket, fixed to CLT panel faces with screws or bolts | <cite index="35-1">Acoustic membrane can be inserted between wall/floor panels and the metal bracket to improve airtightness and sound insulation in exterior applications; special installation devices are used to ensure a tight fit between individual panels during assembly</cite> | Good — straightforward, uses hardware already covered in Category 3 above, easiest mass-timber connection to prototype without specialist tooling |
| **Timber-Concrete Composite (TCC) Connectors** | A steel base plate with an integral top bar (welded, pressed, or bent from a single sheet), fixed into the timber substrate with inclined self-tapping screws, then embedded in a concrete topping | <cite index="40-1">The connector's inclined screw holes are specifically angled — not perpendicular to the base plate — to improve the mechanical interlock between the steel connector and the timber substrate</cite> | Relevant only if a hybrid timber+GFRC connection is pursued (per Concept D, Layered Hierarchy) — otherwise not a priority for this project |
| **Bolted Panel-to-Panel Plate (shear wall type)** | Rectangular steel plates bolted to the faces of two adjoining CLT shear-wall panels, engineered with a defined stiffness/ductility threshold | <cite index="41-1">Maintains initial stiffness (panels move as one body) under normal loads, but deforms in a controlled, ductile way once loads exceed a defined threshold — allowing the panels to move independently rather than fail catastrophically</cite> | Good precedent-level detail if the project wants to reference genuinely engineered, code-adjacent mass timber connection design in the presentation |

**Relevance to this project:** self-tapping screws are the practical, achievable starting point for connecting WD-04 (CLT offcuts) — no specialist adhesive or welding needed, directly compatible with hand tools. Glued-in rods and TCC connectors are worth knowing about but are lower priority given the project's current fabrication access constraints.

---

## Cross-Category Summary

| Category | Best Match for Reclaimed/Irregular Stock | Best Match for This Project's Current Fabrication Access |
|---|---|---|
| Interlocking | Finger joint, half-lap (both proven at scale — ICD/ITKE pavilion, Xu et al. 2025) | Half-lap — simplest to cut by hand |
| Groove & Tongue | Spline joint (separate spline absorbs mismatch between host pieces) | Tongue & groove — standard tooling |
| Timber & Metal | Plate & bolt, shear plate (oversized holes absorb dimensional variation) | Plate & bolt — no specialist equipment |
| Mass Timber | Self-tapping screws (standard industry method, forgiving of panel variation) | Self-tapping screws — directly buys into WD-04's CLT offcut catalogue entry |

**The recurring principle, again:** every category has at least one joint type that tolerates reclaimed material's irregularity well (finger joints, splines, oversized-hole bolted plates, STS) and at least one that demands precision better suited to new, consistently-milled stock (dovetails, split rings, dado joints). This mirrors the project's established Chain 9 lesson — choose joints that standardise the *connection*, not ones that require the *material* to already be standard.

## Sources
- Interlocking joint mechanics/strength data: https://www.carbitool.com.au/2026/02/the-complete-guide-to-wood-joints-how-to-pick-the-right-one-every-time/ ; https://toolstoday.com/learn/18-woodworking-joints
- Groove & tongue, dado, rabbet: https://factorydirectsupply.com/blogs/news/the-10-different-types-of-wood-joints-explained ; https://www.finepowertools.com/woodworking/wood-joint-types/
- Timber-metal connector mechanics: https://www.buildersmetalwork.com/timber_connectors_and_metal_plate_fasteners.html ; https://civilengineeringx.com/bdac/split-ring-and-shear-plate-connectors/ ; https://materialsmarket.com/building-materials/builders-metalwork/timber-connectors
- Toothed plate reinforcement testing: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9370061/
- Mass timber connections (STS, GiRods): https://www.structuremag.org/article/modern-wood-fasteners/
- CLT connection detailing: https://www.fpl.fs.usda.gov/documnts/pdf2013/fpl_2013_mohammad001.pdf
- Bolted panel-to-panel shear wall connector: US Patent 10,533,338
- Timber-concrete composite connector: US Patent 12,509,882
