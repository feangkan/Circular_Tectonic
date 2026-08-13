# Week 4 — Presentation Script (Extended)

**Total time target: ~9–10 minutes.** This supersedes the earlier 5-minute cut — extended so each precedent has enough depth to actually justify our decisions rather than just being named.

---

### Slide 1 (~15 sec)
"Hi, I'm [name] from Group 3. Quick update on how we're responding to last week's feedback — we've narrowed our materials to metal sheet and fabric, and locked in a shell structure direction."

### Slide 2 (~45 sec)
"We're building a shell or hybrid-shell structure, because thin sheet metal is strong in tension and compression but weak in bending — so the form has to be found through force, not sculpted by hand. For the method, we're following Neri Oxman's principle that material distribution should follow a real performance gradient, not decoration. Looking back at our three Week 3 concepts — Gyroid, Plexus, and Stigmergic Piping — none of them actually center metal sheet plus fabric. The closest is Gyroid's bent-sheet skin layer, so that's our seed — we're rebuilding its shell logic without the oyster-cage frame, and properly introducing fabric this time."

### Slide 3 — Frei Otto & Heinz Isler (~65 sec)
"Our form-finding logic actually goes back to the 1960s and 70s. Frei Otto, at the Institute for Lightweight Structures in Stuttgart, built soap-film models to find minimal surfaces, and hanging-chain models to find compression arches and shells — his tensile fabric roof for the 1972 Munich Olympic Stadium is the best-known result. Heinz Isler, a Swiss engineer, described three physical form-finding methods — the freely shaped hill, the membrane under pressure, and what he called the hanging cloth reversed — and used them to build around a thousand thin concrete shells across Europe with almost no reinforcement. Here's why this matters directly to us: the digital relaxation we're planning to run in Kangaroo or RhinoVAULT is literally that same 'hanging cloth reversed' method, just computed instead of physically draped. We could even test this by hand first — hang a piece of our own reclaimed fabric or wire mesh and photograph the shape it settles into — before we touch Grasshopper at all."

### Slide 4 — Block Research Group / RhinoVAULT (~70 sec)
"The more contemporary version of this is the Block Research Group at ETH Zurich, led by Professor Philippe Block. They built RhinoVAULT, released in 2014, which uses something called Thrust Network Analysis — basically a 3D version of 19th-century graphic statics — to form-find compression-only shells directly inside Rhino and Grasshopper. It's been downloaded over 30,000 times, so it's a proven, accessible tool, not experimental software. Their clearest demonstration is the Armadillo Vault, shown at the 2016 Venice Biennale: 399 individually cut limestone blocks, no mortar, no reinforcement, held together purely by geometry and compression. That's essentially our exact problem — irregular, individually-shaped units, assembled without glue or welds — just solved in stone instead of metal. This is our leading candidate tool for the actual shell relaxation step."

### Slide 5 — XISUI Design, Thin-Shell Metal Woven Pavilion (~60 sec)
"For a much closer material match, there's XISUI Design's Thin-Shell Metal Woven Pavilion, completed in 2023, spanning eleven meters over water. It's a keel-free, doubly-curved shell built from just two layers of two-point-five millimeter steel plate — a span-to-thickness ratio of 4,400 to 1, which is remarkable for something this thin. The form is inspired by bird-nest weaving and the way eggshells transmit force through their curvature, which is the same structural-biomimicry logic we're working with. Critically, it's assembled with bolts, not welds, and it was actually disassembled and rebuilt at a completely different site. That's direct proof that a lapped, bolted connection works structurally at real scale in thin sheet metal — which is exactly the joint type we're planning to use."

### Slide 6 — Wang Shu (~50 sec)
"On the material-ordering side, our tutor pointed us directly to Wang Shu, the 2012 Pritzker Prize winner, and specifically the Ningbo History Museum from 2008. That building's facade is made from millions of reclaimed roof tiles and bricks, salvaged from demolished traditional houses across Zhejiang province, laid using a traditional technique called Wa Pan, scaled up to a large contemporary building. The result reads as a deliberate banded, gradient texture — the irregularity is visible and organised, not hidden and not random. This is essentially the hand-craft version of exactly what we're trying to do computationally: take irregular reclaimed units and order them into something legible."

### Slide 7 — Superuse Studios / Villa Welpeloo (~50 sec)
"On the sourcing side, there's Superuse Studios in Rotterdam, led by Jan Jongert. Their Villa Welpeloo project from 2009 used roughly sixty percent locally salvaged material — including cable reels and timber from a decommissioned textile-machine factory nearby. What's most useful to us is their process: they built a tool called the Harvest Map, which catalogues whatever reclaimed material is actually available locally before design even starts. We already have a 46-entry material catalogue from Week 3 — this precedent confirms we should be designing from that real catalogue, not designing an ideal shape first and hoping matching material turns up afterward."

### Slide 8 — Matching Algorithms / Wave Function Collapse (~55 sec)
"Last precedent thread is more academic than built: there's active research on matching algorithms that assign irregular reclaimed elements to a target design using best-fit or minimum-cost assignment methods — some versions actually use the Hungarian algorithm to minimise leftover waste. A related technique, Wave Function Collapse, has been used inside Grasshopper to aggregate heterogeneous reclaimed modules using adjacency rules rather than a fixed pattern — one published study resolved 2,820 modules across 729 observations this way. This isn't just inspiration for us — this is the literal computational method we're planning to adapt for matching our generated panel sizes against our real catalogue stock."

### Slide 9 — Our Computational Strategy (~65 sec)
"So here's how all of that comes together. Step one: relax the shell surface using force-based simulation — Kangaroo or RhinoVAULT — drawing directly on the Otto, Isler, and Block Research Group logic. Step two: generate panel cells on that surface using a real field, like sun exposure or structural stress, so cell size varies for a reason — that's Wang Shu's ordering principle, just computed. Step three: match each target cell size against our real catalogue dimensions, using a best-fit matching approach — that's Superuse's harvest-first thinking combined with the matching-algorithm research. For the joint itself, we're using an overlapping, shingle-style lap, proven at scale by XISUI, because it tolerates size variation far better than a twist or interlocking joint would. And critically, that same field also drives whether a panel stays rusty or gets treated — so one system answers the tutor's whole gradient request, instead of four separate decisions."

### Slide 10 (~20 sec)
"Next steps: confirm the pavilion's function and spatial intent, prototype the actual Grasshopper definition — relax, field, Voronoi, match — test a physical hanging-fabric model by hand using our own reclaimed fabric, and decide whether fabric works structurally or environmentally alongside the metal. Thanks."

---

**Running total: ~15 + 45 + 65 + 70 + 60 + 50 + 50 + 55 + 65 + 20 sec ≈ 8:15–8:35** depending on pacing — within the extended target, with some room to breathe or take a question.
