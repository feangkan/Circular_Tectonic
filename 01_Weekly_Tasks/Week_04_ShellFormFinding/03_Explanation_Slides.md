# Week 4 — Explanation Slides (Extended, ~9–10 min)

**Note:** This supersedes the earlier 5-minute version — extended per direction to give each precedent enough depth to actually justify our design decisions, not just name-drop them. 10 slides.

---

## Slide 1: Group 3 — Responding to Feedback
- Materials narrowed: **reclaimed metal sheet + fabric**
- Structure type locked in: **shell / hybrid-shell**
- Method: **biomorphic form-finding**
**Visual:** Title card — metal sheet + fabric texture photo/swatch

## Slide 2: Design Direction
- Shell/hybrid-shell — sheet metal is strong in tension/compression, weak in bending, so form must be *found*, not sculpted
- Method follows Neri Oxman's principle: material distribution follows a real performance gradient, not decoration
- Gap check: none of our 3 Week 3 concepts (Gyroid, Plexus, Stigmergic) center metal sheet + fabric — **Gyroid's bent-sheet skin is our seed**, rebuilt without the oyster-cage frame, fabric properly introduced
**Visual:** Side-by-side of the 3 Week 3 concept sketches, Gyroid skin detail circled

## Slide 3: Precedent — Frei Otto & Heinz Isler (Form-Finding Origins)
- Otto (Institute for Lightweight Structures, Stuttgart): soap-film models for minimal surfaces, hanging-chain models for compression arches/shells; Munich Olympic Stadium (1972) tensile fabric roof
- Isler (Swiss engineer): three physical form-finding methods — "the freely shaped hill, the membrane under pressure, and the hanging cloth reversed"; built ~1,000 thin concrete shells across Europe this way, almost no reinforcement (e.g. Sicli SA Geneva, Naturtheater Grötzingen)
- **Direct link to us:** our Kangaroo/RhinoVAULT digital relaxation *is* the "hanging cloth reversed" method, just computed instead of physically draped — we could even physically test a hanging fabric/wire model using our own reclaimed fabric stock before digitising, closing the loop between our two material families
**Visual:** Isler hanging-membrane model photo + Munich Olympic Stadium roof photo

## Slide 4: Precedent — Block Research Group, ETH Zurich (RhinoVAULT)
- Led by Prof. Philippe Block, part of ETH's NCCR Digital Fabrication programme
- **RhinoVAULT** (2014, Dr. Matthias Rippmann): Thrust Network Analysis — a 3D extension of 19th-century graphic statics — for compression-only, funicular shell form-finding, built directly for Rhino/Grasshopper; 30,000+ downloads
- **Armadillo Vault** (Venice Biennale 2016): 399 individually cut limestone blocks, no mortar, no reinforcement — held together by geometry and compression alone
- Also: ETH Pavilion at Ideas City NYC (2015) built from recycled waste material; Droneport project using soil-pressed tiles
- **Direct link to us:** this is our leading candidate tool for Step 1 (shell relaxation) — more targeted to a discrete, compression-shell logic than generic physics relaxation. Armadillo Vault also proves the exact conceptual problem we have (irregular individually-cut units, held by geometry not fasteners) at building scale
**Visual:** Armadillo Vault construction photo + RhinoVAULT thrust-network diagram

## Slide 5: Precedent — XISUI Design, Thin-Shell Metal Woven Pavilion
- Completed 2023 (assembly began 2020), spans 11m over water
- Keel-free, doubly-curved shell using **only 2 layers of 2.5mm steel plate** — span-to-thickness ratio of 4,400:1
- Form inspired by bird-nest weaving and eggshell arched force transmission (structural biomimicry, same family as our own biomorphic direction)
- Assembled with **bolts, not welds** — meaning it was later fully disassembled and rebuilt at a new site
- **Direct link to us:** closest material type-match to our own project (thin sheet metal shell) and hard proof that bolted/lapped connections work structurally at real scale and thin gauge — directly supports our overlap/shingle joint choice and disassembly ambition
**Visual:** XISUI pavilion exterior photo + detail shot of plate-to-plate bolted seams

## Slide 6: Precedent — Wang Shu / Amateur Architecture Studio
- 2012 Pritzker Prize laureate (with Lu Wenyu); Ningbo History Museum (2008)
- Millions of reclaimed roof tiles and bricks salvaged from demolished traditional houses across Zhejiang province, laid using the traditional **"Wa Pan"** wall-building technique scaled up to a large contemporary building
- Facade reads as deliberately **banded/gradient texture** — irregularity is visible and organised, not hidden or randomised
- Given to us directly by the tutor as our own precedent
- **Direct link to us:** this is the hand-craft version of exactly what we're trying to do computationally — order irregular reclaimed units into a legible gradient, rather than making them uniform or leaving them random
**Visual:** Ningbo History Museum facade photo, close-up of tile/brick banding

## Slide 7: Precedent — Superuse Studios (Jan Jongert), Villa Welpeloo
- Rotterdam-based practice (originally 2012Architecten); Villa Welpeloo (2009, Enschede) — roughly **60% locally salvaged material**, including cable reels and timber from a decommissioned textile-machine factory
- Developed the **"Harvest Map" / Oogstkaart** tool: catalogues available local waste/reclaimed stock *before* design begins
- **Direct link to us:** methodological precedent for our own approach — we already have a 46-entry material catalogue from Week 3; Superuse's model confirms designing *from* that catalogue's real stock is the right order of operations, not designing an ideal form first and hoping the material fits after
**Visual:** Villa Welpeloo exterior (cable-reel cladding) + a Harvest Map screenshot/diagram

## Slide 8: Precedent — Matching Algorithms for Reclaimed Material
- Academic research area, not just built precedent: matching algorithms that assign irregular reclaimed elements to a target design using **best-fit / minimum-cost assignment** (some formulations use the Hungarian algorithm, minimising leftover waste)
- Related technique: **Wave Function Collapse (WFC)**, used in Grasshopper to aggregate heterogeneous reclaimed modules via adjacency/constraint rules rather than a fixed pattern — one published study resolved 2,820 modules across 729 observations
- **Direct link to us:** this is the literal computational technique for our Step 3 (matching generated Voronoi cell sizes against our real catalogue) — not inspiration, an actual method we intend to adapt directly
**Visual:** Diagram of a matching/assignment algorithm (grid of target cells vs. available stock, matched by nearest size)

## Slide 9: Our Computational Strategy — Putting It Together
- **Step 1:** Relax the shell (Kangaroo2 / RhinoVAULT) — force-found, not arbitrary [Otto/Isler/Block Research Group]
- **Step 2:** Field-driven panel cells (Voronoi) — a real field (sun exposure / structural stress) sets cell size [Wang Shu's ordering logic, computed]
- **Step 3:** Best-fit match each cell to our real catalogue dimensions [Superuse's harvest-first logic + matching-algorithm research]
- **Joint:** overlapping/shingle lap — tolerates size variation far better than twist or interlocking joints [XISUI's bolted lap precedent]
- **Same field also sets rust vs. treated finish** — one system, answers the tutor's whole gradient request at once
**Visual:** Flow diagram — Field → Voronoi cells → Best-fit match → Overlap joint → Finish gradient, each step tagged with its precedent

## Slide 10: Next Steps
- Confirm pavilion function + spatial intent
- Prototype the Grasshopper definition: relax → field → Voronoi → match
- Test a physical hanging-fabric/wire form-finding model using our own reclaimed fabric stock (Otto/Isler method, hands-on)
- Decide fabric's role: structural brace vs. environmental skin
**Visual:** Simple 4-item checklist
