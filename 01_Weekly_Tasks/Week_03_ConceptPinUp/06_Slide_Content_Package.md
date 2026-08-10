# Slide Content Package (FULL, v2) — Week 3 Concept Pin-Up

Complete rebuild incorporating everything researched to date — every list, table, stat, narrative, and comparison from all material/precedent/fabrication/systemic documents, including the additions since the last version: reclaimed fibre as a fourth material family, the exact-dimensions reference, the categorized timber joint standards, and the narrative case for reclaimed metal. Paste this whole file into Claude Design as your prompt, or work through it slide-by-slide. ~71 slides total — the ★-marked slides (~24) are the suggested tighter path for the actual 10–15 minute talk; everything else is backup/appendix depth for handling questions.

---

## PART 1 — FRAMING & COMPUTATIONAL LEAD

### ★ SLIDE 1 — Title + Project Context
**Title:** Circular Tectonics — Concept Pin-Up
**Subtitle:** Biomorphic Computation × Metal, GFRC, Circular Wood & Reclaimed Fibre
**Content (credits):** Name / RMIT Circular Tectonics HK Travelling Studio / 5 Aug 2026 / Dr Nic Bao, Harlan Guo

**Content (why this matters — global context):**
- The world generates roughly **2.24 billion tonnes of solid waste** — rising every day
- Construction waste: **~1.3 billion tons/year** globally, **projected to double to 2.2 billion tonnes by 2025**
- The 3Rs — Reduce, Reuse, Recycle — the established primary strategy
- Ten construction materials/components with proven recycling pathways: brick, concrete, timber, plastic, metal, tiles, rammed earth, cardboard, doors/window frames, shipping containers
- Real precedent in this studio's own city: **Brickface House (Austin Maynard Architects, Melbourne, 2017)** — recycled red brick
**Source:** Arpitha S., ParametricArchitecture, 25 Feb 2023. https://parametric-architecture.com/building-with-a-conscience-how-recycled-materials-are-changing-the-face-of-architecture/

### ★ SLIDE 2 — Framing
**Title:** The Lead: Growth Over Assembly
**Content:**
- A differential-growth algorithm generates a variable, non-standard structural/skin network
- Reclaimed material is already variable — the network's irregularity and the material's irregularity are a match, not a conflict
- Four material families tested against this: Metal, GFRC, Circular Wood, Reclaimed Fibre

### SLIDE 3 — Differential Growth, Explained
**Title:** What "Growth Algorithm" Means Here
**Content:** Three simple local rules run over many small agents, repeated until form emerges:
- **Repulsion** — agents push away from neighbours that get too close
- **Cohesion** — agents stay connected to/within range of neighbours
- **Insertion** — new agents inserted when connected agents stretch too far apart
- Tooling: Grasshopper + Kangaroo2, run on a mesh surface or along a curve network

### SLIDE 4 — Related Growth-Family Algorithms
**Title:** Alternatives Considered
**Content:**
- **Cellular Automata / DLA** — discrete, grid-based, harder to control geometrically
- **L-Systems** — rule-based string-rewriting, branching plant-like structures
- **Agent-based growth on a mesh** — differential growth constrained across an existing surface

### SLIDE 5 — Natural Mimicry as Behaviour
**Title:** Mimicry Means Behaviour, Not Just Shape
**Content:**
- Two biomimicry approaches: simulate a biological process computationally, or co-opt a living/biological material directly
- Example: bioMASON grows brick using bacteria altering aggregate pH — modelled on coral reef formation
- The growth algorithm's rule-set is chosen because it reproduces a real structural behaviour — not because the output "looks organic"

---

## PART 2 — MATERIAL RESEARCH: METAL

### ★ SLIDE 6 — Why Reclaimed Metal (narrative opener)
**Title:** Reclaimed Metal — The Primary Material
**Content (one-line thesis, largest text on slide):** A growth algorithm produces an irregular network. Reclaimed metal is already irregular. The two problems cancel each other out.
**Content (supporting):**
- 1,085 million tonnes of steel recycled worldwide every year — 99% of structural steel eventually reused
- The scarcity was never volume — it's geometry, and that's exactly the irregularity a growth network needs
- Thin enough (2–3mm), curvature alone becomes the structure — no separate frame required
- Proven at real scale: Thin-Shell Nest Pavilion was disassembled and rebuilt at a new site; Fornes' method scaled from a campus pavilion to a 10m shell with 200,000+ rivets

### SLIDE 7 — Metal, List A: Structural/Sectional
**Title:** Reclaimed Metal — Structural Sections
**Content (table):**
| Type | Source | Dimensions | Fit |
|---|---|---|---|
| Steel I-beams/H-beams | Demolished commercial/industrial buildings | Sections: 150UB14–250UB25, 6–12m stock | Primary "trunk" members |
| Angle iron/flat stock | Demolition, fabricator offcuts | 40×40×5mm to 100×100×10mm, 6m stock | Secondary bracing |
| Steel tubing (SHS/CHS) | Scrapyards, fencing/railing | 25×25mm to 100×100mm SHS; 33.7–114.3mm CHS | Node/connector design |
| Steel plate offcuts | Fabricator waste, shipyard offcuts | 2400×1200mm or 3000×1500mm sheet, 3–12mm | Skin fragments, gusset plates |
| Rebar | Demolished concrete elements | N12/N16/N20/N24 (12–24mm dia), 6–12m stock | Linear/branching elements |

### SLIDE 8 — Metal, List B: Found/Consumer-Object Scrap
**Title:** Reclaimed Metal — Found Objects
**Content (table):**
| Type | Dimensions | Design Fit |
|---|---|---|
| Cans | 330mL: 66×115mm; 500mL: 68×168mm | Decorative/skin infill |
| License plates (AU) | 372×134mm | Textured cladding unit |
| Appliance panels | No fixed standard | Fold-and-bend skin candidate |
| Bicycle/vehicle frame offcuts | 25.4/28.6/31.8mm tube dia. | Small-scale node stock — sort alloys before welding |

### ★ SLIDE 9 — Metal, List C: Metal Sheet
**Title:** Reclaimed Metal Sheet
**Content (table):**
| Type | Dimensions | Fabrication Fit |
|---|---|---|
| Roofing/cladding steel | 762mm cover width, to 12m length, 0.42–0.48mm | Fold & bend skin — near-usable as-is |
| ACP offcuts | 1220×2440mm or 1250×3200mm, 3–4mm | Dry-joint cladding |
| Stainless steel sheet | 1200×2400mm, 0.8–1.5mm | Best-condition option — doesn't rust |
| Appliance sheet panels | No fixed standard | Fold/bend candidate |
| Drum steel (flattened) | 572mm dia × 851mm h → ~1.8×0.85m flat | Pre-curved "grown" curvature |
- Sheet is the easiest metal sub-category to source in volume

### SLIDE 10 — Metal, List D: Aluminium-Specific
**Title:** Aluminium-Specific Scrap
**Content:**
- Aluminium extrusion offcuts — 50–100mm profile width, 6m stock — cleanest, most consistent reclaimed sections available
- Aluminium sheet offcuts — 1200×2400mm, 0.9–3mm — light, easy hand-fold
- Crushed cans/found aluminium — no fixed standard once crushed — decorative use only, not structural

### SLIDE 11 — Metal Sourcing & Safety Notes
**Title:** Sourcing & Condition Assessment
**Content:**
- Melbourne leads: scrap yards, demolition contractors, RMIT workshop bins, local fabricators/welders
- Before use: wire-brush rust, magnet-test ferrous/non-ferrous, log dimensions/weight
- Safety: pre-1978 painted steel may carry lead paint
- Structural sections = load-bearing; found-object scrap = cladding/texture — don't mix roles

---

## PART 3 — MATERIAL RESEARCH: GFRC

### SLIDE 12 — GFRC, List A: Fabricator Waste
**Title:** Reclaimed GFRC — Realistic Sourcing
**Content:**
- No public salvage stream exists (unlike timber/metal) — GFRC is young (1970s–80s), mostly still in service
- Panel offcuts/trim waste — fabricators increasingly zero-waste, volume may be shrinking
- Rejected/failed casts — structurally sound, rejected for cosmetic reasons — potentially the best find
- Sourcing dimension note: typical architectural panel run 1200×1200mm to 1500×3000mm

### SLIDE 13 — GFRC, List B & C: Processed Waste / Alternatives
**Title:** GFRC — Ground Waste & Alternatives
**Content:**
- Ground GFRC/GFRP aggregate: feasible up to ~20% of sand volume in new mixes (non-structural)
- Mechanical recycling: lowest-impact route (0.27–3.03 MJ/kg)
- Fallback: reclaimed precast concrete panel offcuts (non-fibre, established demolition stream)

### SLIDE 14 — GFRC Material Properties
**Title:** GFRC Physical/Performance Data
**Content (table):**
| Property | Value |
|---|---|
| Density | 19–21 kN/m³ |
| Compression strength | 50–80 MPa |
| Elasticity modulus | 10–20 GPa |
| Tensile strength | 8–11 MPa |
| Sprayed wall thickness | ~10–13mm |
| Weight vs. solid concrete | ~75% lighter |
| Fire rating | Class A1 |

### ★ SLIDE 15 — Circular Fibre for GFRC: Three Families
**Title:** Rethinking the "GF" in GFRC
**Content:**
- CO₂/tonne: glass fibre 1,700–2,500kg vs. flax 350kg, hemp 410kg, jute 550kg
- Glass fibre costs 1–8× more, 3–5× the carbon footprint of natural fibre
- **Natural (flax/hemp/jute):** low carbon, but alkaline-degradation risk in concrete
- **Mineral (basalt):** same manufacturing as glass, less energy, tensile strength slightly higher than E-glass
- **Recycled (steel from tyres, carbon, glass):** genuinely circular; recycled glass fibre shows +88% tensile strength vs. natural-fibre-only composites

### SLIDE 16 — Basalt Fibre: The Recommended Path
**Title:** Basalt Fibre — Strongest Candidate
**Content:**
- Compressive strength improvement: +7–14% at various dosages
- Direct precedent: basalt fibre cast into precast wall panels, tested for frost resistance
- Drop-in substitute: same casting method as standard GFRC, no change to panel format or connections

### SLIDE 17 — Fibre-for-Concrete Ranking
**Title:** Recommendation, Ranked
**Content:**
1. **Basalt fibre** — best overall, drop-in, real precedent
2. **Recycled waste glass fibre** — genuinely circular, sourcing consistency is the open question
3. **Flax/hemp** — best narrative, but requires novel testing (alkalinity)
4. **Recycled carbon fibre** — least realistic for student timeline (fibre cost can exceed concrete cost)

---

## PART 4 — MATERIAL RESEARCH: CIRCULAR WOOD

### ★ SLIDE 18 — Why Reclaimed Timber (narrative opener)
**Title:** Reclaimed Timber — Where Structure Started
**Content (one-line thesis, largest text on slide):** Every joint researched this semester — from Sanchez's discrete design back to a mortise and tenon — was worked out in timber first. Reclaimed timber lets this pavilion build with that inheritance instead of starting over.
**Content (supporting):**
- Timber is the one material family with a category no other has: engineered offcuts. CLT production waste is new-condition factory waste — a structural stream metal and GFRC simply don't offer.
- It's the most forgiving material to work by hand this week, before Hong Kong fabrication access opens — no welding, no casting, just a joint proven for centuries.
- It's also where both of the project's computational strategies were already tested at real scale: EPFL's ski pavilion graded material by hand; the 2025 mortise-tenon research standardised the joint and let a robot absorb the variability instead. Timber shows both approaches working.

### SLIDE 19 — Wood, List A: Structural/Sectional
**Title:** Circular Wood — Structural Timber
**Content (table):**
| Type | Dimensions | Fit |
|---|---|---|
| Reclaimed structural beams | No fixed standard — orig. sections 90×45mm to 300mm+ deep | Primary frame |
| Reclaimed glulam beams | Widths 65/85/135/185mm, depths 200–900mm, to 24m | High-value if sourceable |
| Railway sleepers | 2400×230×115mm | Base/plinth — built-in weatherproofing |

### ★ SLIDE 20 — Wood, List B: Engineered Mass Timber Offcuts (unique find)
**Title:** The Standout Category — CLT/Glulam Offcuts
**Content:**
- CLT production offcuts: ~1000×1000mm and ~2000×1000mm door/window cut-offs — genuine factory waste, new condition
- Standard CLT: thickness 60–360mm (3/5/7/9-ply), width 1.2–3.0m, length 5–18m
- Directly precedented: DTC Timbershell reuses exactly these cut-offs, shaped into polygonal shell elements
- CLST (CLT from reclaimed feedstock): no significant strength difference vs. new CLT in testing
- **No metal or GFRC equivalent exists at this structural scale**

### SLIDE 21 — Wood, List C: Sheet/Panel
**Title:** Circular Wood — Sheet Stock
**Content (table):**
| Type | Dimensions | Fit |
|---|---|---|
| Formply | 2400×1200mm, 17–19mm | Best-condition, highest-volume — thrown out after one pour |
| General construction offcuts | 2400×1200mm sheet, 6–18mm | CNC-cut node components |
| Set/backdrop plywood | No fixed standard, pre-cut shapes | Check for pre-curved plywood |
| Furniture-grade offcuts | No fixed standard | Visible interior surfaces |
| OSB/particleboard/MDF | 2400×1200mm, 3–25mm | Backing/blocking |

### SLIDE 22 — Wood, List D: Found-Object
**Title:** Circular Wood — Found Objects
**Content (table):**
| Type | Dimensions | Notes |
|---|---|---|
| Pallet deck boards | 22×95–145mm section, 1000–1165mm | Kerf/score for curved skin |
| Pallet stringers/blocks | ~38×90mm, ~1000–1165mm | Structural blocking |
| CHEP pallets (whole) | 1165×1165mm | Heat-treated, dimensionally consistent |
| Wine barrel staves | ~950mm × 100–120mm × 25–27mm | Genuinely pre-curved found geometry |
| Scaffold boards | 225×38mm, 2400/3000/3900mm | Unusually standardised for reclaimed stock |

### ★ SLIDE 23 — Wood Cross-Category Synthesis
**Title:** How Wood Compares to Metal & GFRC
**Content (table):**
| | Structural | Engineered Offcuts | Sheet | Found-Object |
|---|---|---|---|---|
| Metal equivalent | I-beams, angle | *(none)* | Sheet, ACP | Cans, panels |
| GFRC equivalent | Concrete offcuts | *(none)* | Fabricator rejects | *(none)* |
| Wood advantage | Sourced whole | **Unique — no equivalent** | Highest-volume (formply) | Most characterful (barrel curvature) |

---

## PART 5 — MATERIAL RESEARCH: RECLAIMED FIBRE (NEW FAMILY)

### ★ SLIDE 24 — Fibre as a Fourth Material Family
**Title:** Reclaimed Fibre — Rope, Net, Textile
**Content:**
- Distinct from fibre-as-concrete-additive (Slide 15) — this is fibre as skin/tension material in its own right
- Three streams: reclaimed rope, reclaimed fishing net, reclaimed textile waste
- Best structural role: tension elements, woven skin, compression-reversed modules — complements metal's frame and GFRC's shell

### SLIDE 25 — Reclaimed Rope
**Title:** Reclaimed Rope & Cordage
**Content:**
- Source: marine/shipping industry, dockyard/rigging offcuts
- Scale: 640,000 tonnes lost or discarded at sea annually — 3.3% of all rope market production
- Nautical rope diameter typically 12–24mm; coil lengths 100–220m as sourced
- Naturally a tension material — the interesting design move is reversing that into compression

### SLIDE 26 — Reclaimed Fishing Net
**Title:** Reclaimed Fishing Net
**Content:**
- Scale: derelict fishing gear causes ~380,000 marine animal deaths/year; 5.7% of nets, 8.6% of traps, 29% of lines lost globally in a single year (2017)
- Mesh opening 40–200mm; roll/panel width 1–4m
- **Genuine advantage over every other material researched this semester:** established commercial recycling infrastructure already exists — REFINVERSE (Japan) and MARINYLON (Taiwan) already convert ghost nets into consistent, quality-controlled textile yarn

### SLIDE 27 — Reclaimed Textile Waste
**Title:** Reclaimed Textile/Denim
**Content:**
- Scale: EPA estimates only 13% of clothing textile waste recycled; 11.3 million tons landfilled/year (7.7% of all municipal solid waste)
- Waste wool fibre composite panels: thermal conductivity 0.049–0.060 W/(m·K) — comparable to conventional insulation
- Denim/PP-PE composite panels: sound transmission loss up to 8dB, thermal resistance up to 0.11 m²·°C/W
- Honest limitation: higher embodied carbon per unit mass than some alternatives; 10–50% pricier than fiberglass

---

## PART 6 — ALTERNATIVE MATERIALS

### SLIDE 28 — Six Suggested Alternatives
**Title:** Filling the Gaps — Alternative Materials
**Content:**
1. **Wire mesh/chain-link** (50mm diamond mesh, 900–1800mm roll height) — already the right topology for a growth network
2. **Steel cable/wire rope** (6–20mm dia.) — tension counterpart to compression members
3. **Mycelium composite** (300×300×50mm to 600×600×100mm block scale) — literal "growth" concept
4. **Reclaimed glass** (2440×1220mm to 3210×2250mm sheet, 4–12mm) — translucency, ties to GFRC's glass link
5. **Reclaimed rubber** (450–2000mm belt width, 3–15mm) — flexible node gasket
6. **Bicycle components** (25.4–31.8mm tube, 622/559mm wheel) — small tension elements, prototyping

---

## PART 7 — FABRICATION METHODS

### SLIDE 29 — Fold & Bend
**Title:** Fabrication 1 — Fold & Bend
**Content:** Air bending, bottoming, coining. Applied here: flat sheet stock into skin/cladding. Fit: good, tolerates variable sheet size. Hand tools achievable now.

### SLIDE 30 — Cold Casting
**Title:** Fabrication 2 — Cold Casting
**Content:** Metal powder + resin, weight/appearance of solid metal without melting. **Honest limitation:** not true structural strength — finishing/detailing only. Best use: connector covers over irregular joints.

### SLIDE 31 — Weld
**Title:** Fabrication 3 — Weld
**Content:** Strong, continuous, copes with non-standard geometry — no matched holes needed. **Trade-off:** permanent, cuts against disassembly. Recommendation: use only at primary nodes.

### SLIDE 32 — Rivet, Aggregation, Dry Joint
**Title:** Fabrication 4–6 — Rivet / Aggregation / Dry Joint
**Content:**
- **Rivet:** no heat distortion, needs both-sides access, largely permanent
- **Aggregation:** many small discrete units — physical equivalent of the growth algorithm itself; ICD/ITKE's ~100,000 finger-joint pavilion proves it at scale
- **Dry Joint:** friction/gravity/clamping — fully reversible by design, most circular-aligned method

### ★ SLIDE 33 — Fabrication Method-per-Role Summary
**Title:** Recommended Method by Structural Role
**Content (table):**
| Role | Method | Reasoning |
|---|---|---|
| Primary structural nodes | Weld or bolted dry joint | Handles arbitrary angles; per-node disassembly choice |
| Skin/cladding panels | Fold & bend + rivet | Hand-achievable, low heat distortion |
| Aggregated infill | Aggregation of dry-jointed/riveted units | Mirrors the growth algorithm's own logic |
| Decorative/connector detail | Cold casting | Visual consistency, not structural |

---

## PART 8 — TIMBER JOINT STANDARDS (NEW)

### ★ SLIDE 34 — Interlocking Joints
**Title:** Timber Joints 1 — Interlocking
**Content (table):**
| Joint | Strength | Reclaimed-Stock Fit |
|---|---|---|
| Mortise & Tenon | Resists forces in all directions, ~500lbs oak | Good — basis of Chain 9's discrete mortise-tenon research |
| Dovetail | Superior tensile strength | Moderate — needs precise cutting |
| Finger/Box Joint | Highest end-grain strength (540 PSI) | Good — same geometry as ICD/ITKE's ~100,000-joint pavilion |
| Half-Lap | Weaker but uniform thickness | Good — simplest to cut on irregular sections |
| Sliding Dovetail | Self-tightening on assembly | Good — taper absorbs minor mismatch |

### ★ SLIDE 35 — Groove & Tongue
**Title:** Timber Joints 2 — Groove & Tongue
**Content (table):**
| Joint | How It Works | Reclaimed-Stock Fit |
|---|---|---|
| Tongue & Groove | Locks adjacent boards edge-to-edge | Good — suits reclaimed sheet/board stock |
| Spline Joint | Separate strip joins two grooved edges | Excellent — spline doesn't need to match host pieces |
| Rabbet | Step-cut recess, flush fit | Good — forgiving of irregular thickness |
| Dado | Cross-grain groove for perpendicular panel | Moderate — precision-dependent |

### ★ SLIDE 36 — Timber & Metal Joints
**Title:** Timber Joints 3 — Timber & Metal
**Content (table):**
| Connector | How It Works | Reclaimed-Stock Fit |
|---|---|---|
| Plate & Bolt | Steel plate bolted to both faces, shear transfer | Excellent — oversized/slotted holes absorb mismatch |
| Toothed/Spike Plate | Pressed teeth embed into timber face | Moderate — needs sound, non-degraded timber |
| Split Ring | Ring in matched grooves, bolted centre | Poor — precision-groove requirement |
| Shear Plate | Embedded flush plate, demountable | Good — demountability aligns with project principle |
| 3D-Printed Connector | Custom node matched to measured geometry | **Excellent** — best match for irregular stock, gated on HK fabrication access |

### ★ SLIDE 37 — Mass Timber Connections
**Title:** Timber Joints 4 — Mass Timber
**Content (table):**
| Connection | How It Works | Notes |
|---|---|---|
| Self-Tapping Screws (STS) | Fully-threaded, load transfer through thread engagement | Current industry standard for CLT — directly buys into CLT offcut catalogue entry |
| Glued-In Rods (GiRods) | Threaded rod bonded with epoxy | High capacity, not yet fully code-standardised |
| Steel Plate Connectors | Angle brackets, screwed/bolted to CLT face | Straightforward, easiest to prototype |
| Timber-Concrete Composite | Steel base plate + inclined screws, embedded in concrete | Relevant only if hybrid GFRC+timber pursued |
| Bolted Shear-Wall Plate | Engineered stiffness/ductility threshold | Code-adjacent reference detail |

### SLIDE 38 — Joint Standards Cross-Category Summary
**Title:** Best Joint per Category
**Content (table):**
| Category | Best for Irregular Stock | Best for Current Access |
|---|---|---|
| Interlocking | Finger joint, half-lap | Half-lap — simplest by hand |
| Groove & Tongue | Spline joint | Tongue & groove — standard tooling |
| Timber & Metal | Plate & bolt, shear plate | Plate & bolt — no specialist equipment |
| Mass Timber | Self-tapping screws | Self-tapping screws |
- Recurring principle: standardise the connection, not the material

---

## PART 9 — MAIN PRECEDENT: THIN-SHELL METAL CLUSTER

### ★ SLIDE 39 — Thin-Shell Nest Pavilion (MAIN)
**Title:** Main Precedent — Thin-Shell Nest Pavilion (XISUI Design)
**Content:**
- Location: sited over a pool, China | 2020 → relocated/rebuilt 2022 → completed 2023 | Span: 11×8m
- 2 layers × 2.5mm metal plate, span-to-thickness ratio 4,400:1, bolts only
- Keel-free, bird-nest-inspired — mechanics compared to vaulted historic buildings AND bird eggshells
- **Actually disassembled and rebuilt at a new site** — proof, not just claim

### SLIDE 40 — Nest Pavilion — Spatial Experience
**Title:** Nest Pavilion — Experiential Detail
**Content:** Sunken passage below the pool; exterior white, interior matt brown-gold (low reflection, contemplative); openings let dynamic light patterns move across the interior

### ★ SLIDE 41 — Zephyr Pavilion (Texas Tech, THEVERYMANY)
**Title:** Zephyr Pavilion — Marc Fornes / THEVERYMANY
**Content:**
- 18'H × 48'W × 13'D | 2 layers of 3mm aluminium
- **7,400m total linear cut, 2,343 parts, 59,216 rivets**
- "Structural Stripes": each stripe rotated 45° — carries load AND connects simultaneously
- Controlled 6–15° folds per stripe give curvature from flat stock; assembled one stripe at a time, in precise sequence

### ★ SLIDE 42 — The Orb (Google, THEVERYMANY)
**Title:** The Orb — Google Charleston East Campus
**Content:**
- 10m/33' tall | 3mm aluminium
- **26,820m total linear cut, 6,441 parts, 217,847 rivets**
- Extreme curvature enables full self-support at 3mm; proves the method scales, not small-object-only

### SLIDE 43 — Cluster Comparison Table
**Title:** Why These Three Belong Together
**Content (table):**
| | Nest Pavilion | Zephyr | The Orb |
|---|---|---|---|
| Material | 2×2.5mm plate | 2×3mm aluminium | 3mm aluminium |
| Connection | Bolts | Rivets | Rivets |
| Disassembly demonstrated | Yes — actually rebuilt | Not stated | Not stated |
| Scale | 11×8m | 18'×48'×13' | 10m tall, 26.8km cut edge |
- Core lesson: none treat structure and skin as separate systems

### SLIDE 44 — Direct Implications for This Pavilion
**Title:** What This Cluster Means for Us
**Content:** Reclaimed sheet stock is directly viable; rivet/bolt is the preferred skin connection; growth algorithm output should be a stripe/panel segmentation problem; disassembly is provable, not just claimed

### SLIDE 45 — ICD/ITKE Cross-Check (honest finding)
**Title:** Checked Against ICD/ITKE — No Direct Match
**Content:**
- None of ITKE's numbered pavilions use metal or true GFRC — their programme is fibre-composite/timber
- Elytra Filament Pavilion: 40 robotically-wound glass/carbon-fibre cells, <9kg/m², modelled on beetle elytra
- Concrete-Filled FRP Nodes: braided FRP hull + concrete core, proposed as steel-node alternative
- Reclaimed Design (ITECH thesis): same "grade then assign" methodology, ML-backed
- Conclusion: Nest/Zephyr/Orb cluster remains the strongest material match

---

## PART 10 — GFRC PRECEDENT

### ★ SLIDE 46 — Stuttgart Garden Pavilion (Origin)
**Title:** GFRC Origin — Jörg Schlaich, 1977
**Content:** First proposed structural use of GFRC for complex-geometry buildings. 7 identical hyperbolic shells, cast in-situ, connected after casting.

### ★ SLIDE 47 — Thinking Space / Testing Space (2015)
**Title:** GFRC Main Case Study
**Content:**
- 96 free-form thin-walled GFRC panels, ~1.2×1.2m each, 12m proposed height, 10mm wall
- Hyperbolic form based on Gaudí/Isler catenary systems — pure compression under self-weight

### SLIDE 48 — Monolithic vs. Discretised Comparison
**Title:** The Key Structural Trade-Off
**Content (table):**
| | Monolithic | Discretised |
|---|---|---|
| Max deflection | 12.7mm (span/950) | 32.3mm (span/370) |
| Feasibility | Unbuildable at 12m as one piece | Buildable, connection-dependent |

### ★ SLIDE 49 — Three Connection Types Tested
**Title:** GFRC Connection Engineering
**Content:** Bolted latch plates (4 elements/corner) | Cast-in stainless steel angle (transfers small moments) | Embedded anchor (tested to 1.7kN shear); max bending moment 108kNm, max tensile force 36kN across connections

### SLIDE 50 — GFRC Fabrication — Flexible Mould Table
**Title:** Solving 96 Unique Panels
**Content:** Digitally-driven flexible mould table, shape generated from the same parametric model — 48 individual moulds produced cost-effectively rather than 48 fixed ones. Direct answer to a growth-algorithm output's non-repeating panels.

---

## PART 11 — TIMBER PRECEDENT

### ★ SLIDE 51 — Consolidated Reclaimed Timber Precedents
**Title:** Circular Timber — Precedent Table
**Content (table):**
| Precedent | Method | Strategy |
|---|---|---|
| Re-Emerge Pavilion | Kerfed pallet wood | Weak board → self-stiffening module |
| Circular Pavilion | 180 reclaimed doors | Found-object modularity |
| Re-SPLAM Pavilion | Optimised reclaimed 2×4s | Grade first, place by capacity |
| EPFL Ski Pavilion | 210 skis, elastic gridshell | Grade, assign role, elastic form-finding |
| DTC Timbershell | CLT cut-offs → shell | Offcut boundary as design input |
| Wood ReFramed | Parametric distribution | Optimisation counters unknown properties |

### ★ SLIDE 52 — Jose Sanchez / Plethora Project — Combinatorial Design
**Title:** A Second Computational Paradigm
**Content (table):**
| | Growth Algorithm (our lead) | Combinatorial/Discrete (Sanchez) |
|---|---|---|
| Units | Continuous, emergent | Finite, discrete, standardised |
| Variation | Every element potentially unique | Permutation of a limited part catalogue |
| Fabrication need | Tolerant of non-repeating geometry | Standardised joints absorb material variability |
- Key insight: combinatorial design may suit reclaimed material better — the system absorbs variation

### SLIDE 53 — Combo-Nest (Tallinn Biennale 2019)
**Title:** Sanchez's Built Precedent — Combo-Nest
**Content:** 3rd Prize, Tallinn. Discrete, open-ended "open-whole" system. 1:1 prototyped, standardised joints. Participatory tools: toy model, instruction cards, video game co-design.

### ★ SLIDE 54 — Discrete Mortise-Tenon Timber (2025 academic bridge)
**Title:** Sanchez's Theory, Applied to Timber Joinery
**Content:**
- Xu, Teixeira & Shafiei, eCAADe 2025 — directly cites Sanchez's combinatorial systems
- Timber blocks: 90×35mm cross-section, orthotropic properties
- **Displacement reduced 26.3% (2.36cm → 1.74cm), stress reduced 14.7%, over 200 iterations/20 generations**
- UR10 robot, 9.5mm bit, 10mm/s — assembly-direction tolerances built in for material variability

### SLIDE 55 — Three Design Cases (MTJ paper)
**Title:** One Rule System, Three Forms
**Content:** Traditional Dougong-derived stacked configuration | Integrated column-wall (Kengo Kuma-inspired) | Curved hyperbolic wall from base-curve input

---

## PART 12 — FIBRE PRECEDENTS (NEW)

### ★ SLIDE 56 — Recycled Rope Pavilion
**Title:** Recycled Rope Pavilion (Leinemann | Ortiz, 2019)
**Content:**
- Unbuilt proposal, Roosevelt Island, New York
- Biomimetic reversal: rope (naturally tension) formed into brick-like modules optimised for compression
- Two structural layers of rope modules anchor a nautical-fabric canopy + secondary mesh
- 3D-printed modules and 1:1 mock-ups used to study geometry before final design
- Directly ties to this project's biomimicry-as-behaviour principle (Slide 5)

### SLIDE 57 — ¡Qué Faena(r)! (+cruz.atelier)
**Title:** ¡Qué Faena(r)! — Built Circular Pavilion, Galicia
**Content:**
- Inspired by Galicia's mussel-platform structures
- **82% of the pavilion's form built from end-of-life materials** — fishing nets, rusty drums, reclaimed platform wood, granite
- Genuine multi-material validation — net + wood + metal, not a single-stream system

---

## PART 13 — SYSTEMIC MAP (ALL 11 CHAINS)

### ★ SLIDE 58 — The Eleven-Chain Synthesis
**Title:** Material → Fabrication → Precedent → Strategy (All 11 Chains)
**Content (table):**
| # | Material | Strategy |
|---|---|---|
| 1 | Steel (found fragment) | Preserve found form |
| 2 | Steel (fixed inventory) | Design follows available stock |
| 3 | Metal sheet | Biomorphic logic + disassembly-first choice |
| 4 | GFRC/cast panels | Co-design casting geometry and connections |
| 5 | Reclaimed skis | Grade by property, assign role, elastic form-finding |
| 6 | CLT offcuts | Offcut boundary as design input |
| 7 | Reclaimed timber (mixed) | Optimisation counters unknown properties |
| 8 | Glass fibre (GFRC) | Drop-in fibre swap for lower carbon/cost |
| 9 | Irregular timber | Standardise the joint, not the material |
| 10 | Reclaimed rope | Biomimetic tension-to-compression reversal |
| 11 | Reclaimed fishing net | Leverage existing recycling infrastructure |

### SLIDE 59 — What the Eleven Chains Prove
**Title:** The Methodology, Not Just the Materials
**Content:** Two repeated strategies: **grade-then-place** (1,5,6,7) vs. **standardise-the-joint** (2,3,9). GFRC chains (4,8) sit apart — casting-specific logic. The research method itself has scaled properly across four material families.

---

## PART 14 — MATERIAL CATALOGUE (46 ENTRIES) + EXACT DIMENSIONS

### ★ SLIDE 60 — Catalogue Overview
**Title:** Digital Material Catalogue — 46 Entries, 5 Families
**Content (table):**
| Family | Entries | Best Sourcing Bet |
|---|---|---|
| Metal | 17 | Roofing sheet |
| GFRC | 4 | Basalt-fibre new mix |
| Circular Wood | 16 | Formply, CLT offcuts |
| Reclaimed Fibre | 3 | Fishing net |
| Alternatives | 6 | Wire mesh, bicycle components |
- Every entry is a computational parameter set — dimension, quantity, fabrication, connection — feeding the growth-algorithm workflow directly

### SLIDE 61 — Metal Catalogue Detail (17 entries)
**Title:** Metal — Full Catalogue
**Content:** [Insert MET-01 through MET-17 table from `02_Material_Catalogue.md`]

### SLIDE 62 — GFRC Catalogue Detail (4 entries)
**Title:** GFRC — Full Catalogue
**Content:** [Insert GFR-01 through GFR-04 table]

### SLIDE 63 — Wood Catalogue Detail (16 entries)
**Title:** Circular Wood — Full Catalogue
**Content:** [Insert WD-01 through WD-16 table]

### SLIDE 64 — Fibre + Alternatives Catalogue Detail (9 entries)
**Title:** Reclaimed Fibre & Alternatives — Full Catalogue
**Content:** [Insert FIB-01 through FIB-03 and ALT-01 through ALT-06 tables]

### ★ SLIDE 65 — Exact Dimensions, Scoped to 3×3×3m
**Title:** Reading Material Against the Pavilion Envelope
**Content:**
- Genuinely modular without cutting: sheet goods (ACP, stainless, aluminium, formply, plywood, OSB, glass) — all standard sheets fit within a 3×3m face
- Needs cutting to length: linear/sectional stock (I-beams, angle, tube, rebar, glulam, cable) — stock lengths 6–24m exceed the envelope
- No fixed standard (honest flag): demolition beams, appliance panels, set plywood, crushed cans — measure individually on collection
- Found geometry smaller than 3m, used as repeating unit: cans, plates, pallet boards, barrel staves, scaffold boards, bicycle parts — aggregation-strategy materials by nature

---

## PART 15 — PAVILION CONCEPTS

### ★ SLIDE 66 — Concept A: Grown Skin
**Title:** Concept A — Grown Skin (Metal)
**Content:** Differential-growth segmentation → reclaimed roofing sheet, fold/bend per panel, riveted, no separate frame. Strength: closest match to strongest precedent. Weakness: reclaimed sheet's variable gauge may not tolerate tight folding tolerances.

### ★ SLIDE 67 — Concept B: Cast Growth
**Title:** Concept B — Cast Growth (GFRC)
**Content:** Basalt-fibre GFRC panels, flexible mould table, connections cast in from the start. Strength: most rigorous structural precedent. Weakness: no confirmed flexible-mould-table access.

### ★ SLIDE 68 — Concept C: Graded Frame, Standardised Joint
**Title:** Concept C — Hybrid Timber Strategy
**Content:** Graded reclaimed timber/CLT at high-load nodes + discrete mortise-tenon joinery for bulk stock — tests both computational paradigms at once. Strength: directly tests growth vs. combinatorial. Weakness: most conceptually complex.

### ★ SLIDE 69 — Concept D: Layered Hierarchy
**Title:** Concept D — Layered Hierarchy (All Four Materials)
**Content:** Metal for frame/tension, GFRC for base/accent, wood for bulk infill, fibre for skin/tension layer — each material doing only what it's good at. Strength: most realistic against sourcing constraints, spreads risk across four streams. Weakness: cross-material connection detailing unresearched.

### SLIDE 70 — Concept Comparison
**Title:** Four Concepts, Compared
**Content (table):**
| | A: Grown Skin | B: Cast Growth | C: Graded Frame | D: Layered Hierarchy |
|---|---|---|---|---|
| Primary material | Metal sheet | GFRC (basalt) | Timber (mixed) | All four, function-split |
| Fabrication dependency | Low | High (mould access) | Medium | Medium-high |
| Sourcing risk | Low | Medium | Low | Spread across 4 |

---

## PART 16 — CLOSE

### ★ SLIDE 71 — Discussion Questions
**Title:** Questions for Discussion
**Content:**
- Growth algorithm and Sanchez's combinatorial design are genuinely different computational paradigms — commit to one, or hybrid (Concept C)?
- Is flexible-mould-table access realistic for GFRC, or should it stay secondary/accent?
- With sourcing unconfirmed across four families, how much should feedback push toward narrowing vs. keeping options open?
- Does the studio favour grade-then-place or standardise-the-joint for demonstrating "reclaimed material as active generator of form"?
- Should reclaimed fibre (rope/net) be elevated from Concept D's secondary role given its strong biomimetic precedent (Recycled Rope Pavilion)?

---

## Notes for Building This in Claude Design

- **~71 slides of source material.** The ★-marked slides (~24) are the suggested tighter path for the 10–15 minute talk; everything else is backup/appendix for handling questions in depth.
- **Catalogue detail slides (60–63):** these are large tables — copy directly from `02_Material_Catalogue.md`, they're already formatted. Consider whether Claude Design should render them as dense reference slides (fine for appendix) or whether to summarise further for the live talk.
- **Images:** precedent photos aren't yours to reuse in a submitted document without checking licensing — screenshot-with-citation for in-class-only use, or ask Claude Design for simple diagrammatic stand-ins.
- **Sketches (Concepts A–D, slides 65–68):** still yours to hand-draw per the brief's own requirement.
- **Practical suggestion, unchanged from before:** build the full deck in Claude Design as your complete reference/appendix, then pull a second, separate ~24-slide deck from just the ★ slides for the actual timed talk.
