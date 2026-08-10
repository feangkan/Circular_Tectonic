# Week 3 (v2) — Precedent Research: Critical Analysis

Five precedents selected from the full body of research this semester, chosen to cover metal, GFRC, and wood, plus the computational-design lineage (Sanchez) — matching the three material families and growth-algorithm lead now driving the project. Full detail for each lives in the dedicated precedent documents; this is the critical-analysis synthesis the brief asks for.

---

## 1. Thin-Shell Nest Pavilion (XISUI Design) — MAIN PRECEDENT
*(Full case study: `06_Precedent_Research/MAIN_PRECEDENT_THIN_SHELL_METAL.md`)*

**Why was this construction method selected?** A keel-free, bird-nest-inspired double-curved geometry was chosen specifically so a thin metal surface alone could carry the load — avoiding a separate structural skeleton entirely. Bolts were used instead of welding *specifically* so the computationally-precise geometry could be trusted to assemble accurately, without the form-finding errors manual welding introduces.

**How do the materials influence the architectural form?** Completely — the 4,400:1 span-to-thickness ratio is only achievable because the double curvature itself carries the load; the material's thinness and the form's curvature are the same design decision, not two separate ones.

**How are structure, fabrication, and assembly integrated?** Total integration — bolted point-to-point seams are the structure, the fabrication method, and the disassembly mechanism simultaneously. This was proven, not just claimed: the whole pavilion was actually disassembled and rebuilt at a new site.

**Lessons for my pavilion:** This is the single closest precedent to the project's actual direction — thin reclaimed metal sheet, panelised via a growth-algorithm-generated segmentation, riveted/bolted rather than welded specifically to preserve disassembly.

---

## 2. "Thinking Space / Testing Space" GFRC Artwork (Henriksen, Allan, Knaack, Lo, 2015)
*(Full case study: `06_Precedent_Research/GFRC_PRECEDENT.md`)*

**Why was this construction method selected?** A monolithic cast shell was structurally cleaner (12.7mm deflection) but physically impossible to fabricate/transport at 12m scale — the discretised panel-and-connection approach was chosen because it's buildable, even though it triples the deflection (32.3mm) and makes success entirely dependent on connection engineering.

**How do the materials influence the architectural form?** The hyperbolic, catenary-derived form (following Gaudí/Isler) exists specifically because it puts the thin GFRC shell into pure compression — the material's brittleness in tension directly dictated the geometry chosen.

**How are structure, fabrication, and assembly integrated?** A digitally-driven flexible mould table was reshaped between casts using the same parametric model that generated the overall geometry — meaning fabrication tooling and design geometry were never separated into different processes.

**Lessons for my pavilion:** Directly answers how to cast many unique, non-repeating GFRC panels (a growth-algorithm output) affordably — one reconfigurable mould, not 96 fixed ones. Also demonstrated three real connection types (bolted, cast-in, embedded) worth referencing directly for node design.

---

## 3. EPFL Ski Pavilion (Structural Xploration Lab, 2017)
*(Full detail: Chain 5, `09_Systemic_Design_Framework/MATERIAL_FABRICATION_PRECEDENT_SYSTEM_MAP.md`)*

**Why was this construction method selected?** An elastic gridshell was chosen specifically because it suits a material (skis) that's flexible but can't be significantly reshaped or cut to length — the structural typology was picked to match what the reclaimed material could actually do, not the reverse.

**How do the materials influence the architectural form?** Different ski types (downhill, slalom, cross-country) were measured and deliberately placed at strategic points according to their individual mechanical properties — the final asymmetric form is a direct readout of that grading process.

**How are structure, fabrication, and assembly integrated?** The grid is built flat, then pulled into shape — fabrication (arranging graded pieces) and structural form-finding (the shell curvature) happen in the same physical act.

**Lessons for my pavilion:** The clearest built (not just simulated) proof that "grade material by measured property, then assign to structural role" is a real, working strategy — 85% lower embodied energy than an equivalent new-timber gridshell, genuinely disassembled and reassembled across four cities.

---

## 4. Combinatorial Nest / Combo-Nest (Jose Sanchez / Plethora Project, Tallinn Architecture Biennale 2019)
*(Full detail: `06_Precedent_Research/TIMBER_PRECEDENT.md`)*

**Why was this construction method selected?** A discrete, open-ended combinatorial system was chosen specifically to avoid two failure modes at once — bespoke bad (too expensive, one-off fabrication of everything) and standardised-boring (homogenous serial repetition) — by using permutation of a small standardised part library instead.

**How do the materials influence the architectural form?** The reverse of most precedents here — the *joint rules*, not individual material pieces, generate the form; a reconfigured A-frame unit produces an "open-whole" that can grow, be pruned, or reconfigured after initial design.

**How are structure, fabrication, and assembly integrated?** Physically prototyped at 1:1 scale specifically to test assembly *sequence*, not just final geometry — assembly order is treated as a design variable, the same lesson already seen in the Zephyr Pavilion's stripe-by-stripe sequencing.

**Lessons for my pavilion:** A genuinely different computational strategy worth holding alongside the growth-algorithm lead — instead of measuring and uniquely placing every reclaimed piece, define standardised connection rules that *tolerate* dimensional variation in the material itself. Directly relevant given how irregular reclaimed timber stock actually is.

---

## 5. Discrete Mortise-Tenon Timber Assemblies (Xu, Teixeira & Shafiei, 2025 — building on Sanchez)
*(Full detail: `06_Precedent_Research/TIMBER_PRECEDENT.md`, Part C)*

**Why was this construction method selected?** Traditional Chinese Dougong mortise-tenon joinery was computationally reinterpreted specifically because it joins timber with zero fasteners while remaining structurally provable — the researchers wanted joinery to be "a central driver of architectural formation," not a secondary detail bolted onto a pre-decided form.

**How do the materials influence the architectural form?** Voxel-based discretisation and shape-grammar rules generate three distinct outcomes (stacked Dougong-derived, integrated column-wall, curved hyperbolic wall) from the *same* underlying rule system — proving one joinery logic can produce genuinely different architectural expressions.

**How are structure, fabrication, and assembly integrated?** Fully closed-loop — structural optimisation (Karamba3D/Wallacei, reducing displacement 26.3% over 200 iterations) fed directly into robotic milling toolpaths, with assembly-direction tolerances deliberately built in to absorb real material variability.

**Lessons for my pavilion:** The most technically rigorous evidence in this whole research set that a discrete, standardised-joint strategy is structurally real (not just conceptual) — and the "tolerances built in to compensate for material variability" detail is a direct, tested answer to working with genuinely irregular reclaimed timber.

---

## Cross-Precedent Synthesis

| Precedent | Material | Core Strategy |
|---|---|---|
| Thin-Shell Nest Pavilion | Metal | Double curvature carries load; bolt/rivet preserves disassembly |
| Thinking Space/Testing Space | GFRC | Flexible mould matches non-repeating panels; connection engineered from casting stage |
| EPFL Ski Pavilion | Wood (found-object) | Grade material by property, assign to structural role, elastic form-finding |
| Combo-Nest (Sanchez) | Timber/discrete | Standardise the joint rules, not the material — system absorbs irregularity |
| Discrete MTJ Assemblies | Timber | Joinery as generative driver, structurally optimised, fabrication-tolerant |

**The recurring theme, now proven across five independent precedents spanning three materials:** either grade the material and computationally place it where its measured capacity is needed, *or* standardise the joint so the system tolerates whatever variability the material already has. My pavilion needs to pick, consciously, which of these two strategies (or what mix) it's actually using per material family — this is the central design decision the presentation should surface for discussion.
