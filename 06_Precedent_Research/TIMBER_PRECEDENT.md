# Timber Precedent — Circular/Reclaimed Timber + Jose Sanchez's Discrete Design

Two parts: (A) consolidates the reclaimed/upcycling timber precedents already scattered across this semester's research into one place, and (B) adds Jose Sanchez / Plethora Project's discrete design work as requested, including the direct academic bridge between his theory and current discrete-timber joinery research — which turns out to be a much closer connection than expected.

---

## PART A — Circular / Upcycling / Reclaimed Timber Precedents (consolidated)

Already documented individually across this semester's research; gathered here as one reference list.

| Precedent | Material/Method | Strategy | Where Documented |
|---|---|---|---|
| Re-Emerge Pavilion (AA EmTech + Hassell, London 2022) | Reclaimed pallet wood, scored/kerfed into volumetric diamond modules, lap-jointed | Turns weak thin reclaimed board into a self-stiffening module via cutting pattern alone | `06_Precedent_Research/EXPANDED_PRECEDENTS_GUIDE.md`; Chain analysis in Week 3 `03_Precedent_Critical_Analysis.md` |
| Circular Pavilion (Encore Heureux, Paris 2015) | 180 reclaimed timber doors + salvaged furniture | Found-object modularity; provenance kept visible and legible | `06_Precedent_Research/EXPANDED_PRECEDENTS_GUIDE.md` |
| Re-SPLAM Pavilion (SOM, Chicago 2025) | Reclaimed 2×4 timber, computationally optimised | Grade material first, then place each piece where its actual measured capacity is needed | Week 3 `03_Precedent_Critical_Analysis.md` |
| EPFL Ski Pavilion (Structural Xploration Lab, 2017) | 210 reclaimed skis, elastic gridshell | Grade by measured mechanical property, assign to structural role, use elastic form-finding | Chain 5, `09_Systemic_Design_Framework/MATERIAL_FABRICATION_PRECEDENT_SYSTEM_MAP.md` |
| DTC Timbershell | CLT production door/window cut-offs shaped into polygonal shell elements | Offcut's actual boundary shape becomes the design input | Chain 6, systemic map; `05_Material_Research/RECLAIMED_WOOD.md` |
| Wood ReFramed | Reclaimed timber trusses, parametric structural distribution | Computational optimisation counters unknown reclaimed-material properties | Chain 7, systemic map |
| Reclaimed Design (ITECH M.Sc., ITKE Stuttgart, 2024) | Reclaimed lumber + ML-predicted compressive strength | Machine-learning-graded material feeds a 7m demonstration truss | `06_Precedent_Research/MAIN_PRECEDENT_THIN_SHELL_METAL.md` addendum |
| UCL/UK CLT Secondary Timber (CLST/glulamST) prototype | Reclaimed structural timber remanufactured into new CLT/glulam | <cite index="128-1">Non-destructive full-scale bending tests demonstrate secondary timber's feasibility as CLT feedstock, aiming to make specifying reused timber as simple and certifiable as specifying new stock</cite> | `05_Material_Research/RECLAIMED_WOOD.md`, List B |

**Cross-precedent theme, confirmed again:** every genuinely built or tested reclaimed-timber precedent uses some version of *grade the material first, then let a computational/parametric process assign it to a structural role* — this is now the single most repeated lesson across the entire semester's research (metal, wood, and GFRC connections all converge on the same principle).

---

## PART B — Jose Sanchez / Plethora Project — Discrete Design

**Studio:** Plethora Project, directed by Jose Sanchez (Architect, Game Designer; currently Associate Professor, Cornell Tech; previously USC, Bartlett/UCL, AA)
**Core theoretical contribution:** <cite index="187-1">"Combinatorial Design" (2016) — a term Sanchez coined for non-parametric design strategies focused on the permutation, combination, and patterning of discrete units, fundamentally different from parametric design because it operates on finite discrete sets rather than continuous numerical ranges.</cite>

### Why This Is a Genuinely Different Computational Paradigm From This Project's Growth-Algorithm Lead

Worth stating honestly upfront: Sanchez's discrete/combinatorial approach and this project's differential-growth computational lead (`07_Computational_Design/BIOMORPHIC_GROWTH_ALGORITHMS.md`) are **two different families of computational design logic**, not the same thing with different names:

| | Growth Algorithm (this project's lead) | Combinatorial/Discrete Design (Sanchez) |
|---|---|---|
| Units | Continuous, emergent, no fixed catalogue of part-types | <cite index="187-1">Finite, discrete, standardised units</cite> |
| Variation | Every element potentially unique (differential growth insertion rule) | <cite index="185-1">Variation comes from permutation and combination of a limited part catalogue, not from unique-per-element geometry</cite> |
| Fabrication implication | Needs a fabrication method tolerant of non-repeating geometry (bolt/rivet, flexible mould — see main precedent) | Needs standardised, repeatable joints between a small number of part types — ideal for reclaimed material that's already irregular, since the *system* absorbs variation rather than each *part* needing to be custom |

This distinction matters directly for this project: **combinatorial/discrete design may actually be a better computational match for reclaimed material than free-form growth simulation**, because it doesn't require every reclaimed piece to be measured and uniquely fabricated — instead it defines a small number of connection *rules* that a wide range of imperfect, variably-sized reclaimed pieces can still satisfy. This is worth raising as a genuine alternative or complementary strategy to the growth-algorithm lead, not just an additional precedent to cite.

### Built/Prototyped Precedent — Combinatorial Nest ("Combo-Nest"), Tallinn Architecture Biennale 2019

**Result:** 3rd Prize, Tallinn Pavilion Program competition
**Team:** Jose Sanchez (Director), Brendan Ho (Principal Designer), with design development, fabrication/analysis, and video game simulation collaborators

<cite index="196-1">Combo-Nest is described as a discrete, open-ended tectonic system relying on the patterning of material units to grow volumetrically with different motifs — unlike a closed system such as a geodesic dome that behaves like a fixed jigsaw puzzle, Combo-Nest's units define an "open-whole" that remains susceptible to alteration, growth, or pruning after the fact.</cite>

**Fabrication/prototyping:** <cite index="196-1">The system was physically prototyped at 1:1 scale specifically to understand assembly-sequence challenges, using standardised pieces and joints; the project situates itself explicitly within "Discrete Architecture" — a paradigm aiming to increase the affordability of complexity through combinatorial patterning of standardised units, deliberately avoiding non-standard (i.e. bespoke, one-off) fabrication of the whole project.</cite> <cite index="196-1">The base unit reconsiders a traditional A-frame structure, exploring the interior/exterior ambiguity found in sloped surfaces.</cite>

**Participatory strategy:** <cite index="196-1">a physical disassembled toy model, printed instruction cards, and a video game simulation (built on the Common'hood engine) were all developed as parallel tools so the Tallinn community could co-design the final built pavilion before fabrication — reflecting Sanchez's broader "Architecture for the Commons" agenda of treating design combinatorics as a participatory, not just technical, tool.</cite>

**Why this matters for this project:** Combo-Nest is a genuine built/prototyped pavilion precedent (not just theory) demonstrating that a small library of standardised, reclaimed-material-tolerant joints can generate a complex, non-repetitive spatial outcome — directly relevant to a 3×3×3m pavilion built from irregular reclaimed stock rather than uniform new material.

---

## PART C — The Direct Bridge: Sanchez's Theory Applied to Discrete Timber Joinery (2024–2025 research)

This is the strongest possible connection between Sanchez's work and this project's timber research, and it's very recent (2025): current academic research on **discrete mortise-tenon timber assemblies explicitly builds on Sanchez's combinatorial design theory**, applying it to real, structurally-tested, robotically-fabricated timber.

**Source:** Xu, Teixeira & Shafiei, "Rule-Based Generative Design Principles for Discrete Mortise-Tenon Timber Assemblies," eCAADe 2025.

<cite index="197-1">This paper directly cites Sanchez's combinatorial architectural systems work as one of three foundational methodologies its own discrete timber grammar builds upon</cite> (alongside Tessmann & Rossi's computational interlocking assemblies and Stiny's shape grammars). <cite index="197-1">The research reinterprets traditional Chinese Dougong mortise-tenon joinery — an interlocking technique that joins wood elements with zero fasteners — through voxel-based discretization and parametric shape grammars, generating reconfigurable timber block assemblies.</cite>

### Real Structural and Fabrication Data (directly useful for this project's own timber connector design)

- <cite index="197-1">Timber blocks measured 90×35mm cross-section, modelled with orthotropic (anisotropic) material properties matching real pine behaviour.</cite>
- <cite index="197-1">Joint stiffness was explicitly modelled — 100 kNm/rad rotational stiffness on X/Y axes vs. 1000 kNm/rad on Z, and 100 kN/m vs. 1000 kN/m translational stiffness — replicating how real mortise-tenon joints allow limited rotation while resisting translation.</cite>
- <cite index="197-1">Initial structural analysis showed 2.36cm maximum displacement and 0.156 kN/cm² peak stress; after 200 optimisation iterations across 20 generations (genetic algorithm via Wallacei), displacement was reduced by 26.3% to 1.74cm and peak stress by 14.7% to 0.133 kN/cm².</cite>
- <cite index="197-1">Physical fabrication used a UR10 robotic arm with a 9.5mm straight router bit at 10mm/s, with an adjustable fixation system built specifically to handle blocks of varying sizes — directly relevant given this project's own reclaimed timber stock is inherently non-standard.</cite> <cite index="197-1">Assembly-direction tolerances were deliberately introduced into the toolpath to compensate for material variability.</cite>

**Three design cases tested**, each a different application of the same rule-based grammar: <cite index="197-1">(1) traditional Dougong-derived layered/stacked configurations, (2) integrated column-wall elements blurring structural/spatial boundaries following Kengo Kuma's small-timber-block architecture as an (non-computational) inspiration, and (3) parametric curved assemblies generating double-curved hyperbolic wall forms from a base-curve input.</cite>

### Why This Matters for This Project

1. **This is the clearest available evidence that combinatorial/discrete timber design is structurally provable, not just conceptual** — real stiffness values, real displacement/stress numbers, real robotic fabrication tolerances.
2. **The "assembly-direction tolerances... to compensate for material variability" detail is a direct, practical answer** to this project's core reclaimed-material problem — a documented, tested method for absorbing dimensional inconsistency in reclaimed timber stock at the joint-design stage rather than requiring perfectly uniform material.
3. **It closes the loop from Sanchez's 2016 theory → Sanchez's own built pavilion (Combo-Nest, 2019) → third-party academic validation with real reclaimed-timber-relevant engineering data (2025)** — a nine-year lineage worth presenting as a coherent narrative arc in slides, showing the idea maturing from concept to genuinely testable structural system.

## Fits Into the Existing System

**Chain 9 — Reclaimed/irregular timber → discrete mortise-tenon joinery (standardised connection rules, variable pieces) → Precedent: Xu, Teixeira & Shafiei (2025), building on Sanchez's Combinatorial Design (2016) and Combo-Nest (2019).** Strategy: rather than measuring and custom-fabricating every unique reclaimed piece (the Re-SPLAM/EPFL Ski Pavilion approach), define a small library of standardised joint *rules* that tolerate dimensional variation in the pieces themselves — shifting the burden of "handling irregularity" from the material-grading stage to the joint-design stage. This is a genuine alternative strategy to Chains 5 and 7, worth comparing directly against them when this project moves from research into design development.

## Sources
- Sanchez, J. (2016) "Combinatorial design: Non-parametric computational design strategies," ACADIA 2016. https://www.researchgate.net/publication/367699329
- Plethora Project / Jose Sanchez: https://www.plethora-project.com/
- Combinatorial Nest (Combo-Nest), Tallinn Architecture Biennale 2019: https://www.plethora-project.com/combinatorial-nest
- Xu, Q., Teixeira, F.F. & Shafiei, M. (2025) "Rule-Based Generative Design Principles for Discrete Mortise-Tenon Timber Assemblies," eCAADe 43, Volume 2. https://papers.cumincad.org/data/works/att/ecaade2025_194.pdf
