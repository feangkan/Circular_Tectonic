# Circular Fibre for GFRC — Alternatives to Virgin Glass Fibre

This document answers a specific question left open in `RECLAIMED_GFRC.md`: that document was honest that a true *reclaimed panel* stream barely exists for GFRC — but it didn't examine whether the **fibre component itself** (the "GF" in GFRC) could be swapped for something more circular while keeping the concrete matrix. This turns out to be a genuinely active research area with real built precedent, organised here into three families: natural plant fibres, mineral fibres, and genuinely recycled/waste fibres.

---

## Why This Matters — The Baseline Problem With Virgin Glass Fibre

<cite index="153-1">Producing one tonne of glass fibre releases roughly 1,700–2,500 kg of CO₂, and one tonne of carbon fibre releases roughly 29,500 kg — compared to natural fibres like hemp (410 kg), flax (350 kg), jute (550 kg), and kenaf (420 kg) per tonne.</cite> <cite index="150-1">Glass fibre also costs 1–8 times more than natural fibre, and its carbon footprint is 3–5 times larger; manufacturing one tonne of glass fibre produces 1.35 times more carbon than flax fibre production.</cite> This is the core case for exploring alternatives — the fibre component, not just the concrete matrix, is a real embodied-carbon and cost lever.

---

## Family 1 — Natural Plant Fibres (Flax, Hemp, Jute, Sisal, Coir)

| Fibre | Notes |
|---|---|
| Flax | <cite index="156-1">Widely available in Ireland/UK/Europe; surface treatment (e.g. 1% stearic acid in ethanol) has been shown to increase tensile strength by 101% in lab testing</cite> |
| Hemp | <cite index="152-1">Portland cement-bonded lime composites reinforced with hemp/flax shives (hurds) are a well-established application already in use for insulating/lightweight construction</cite>; <cite index="156-1">NaOH surface treatment reduces degradability in the alkaline concrete environment</cite> |
| Jute, kenaf | <cite index="153-1">Among the most-used natural fibres in bio-based FRP composites generally, though epoxy rather than cementitious matrices dominate current research</cite> |
| Sisal, coir | <cite index="152-1">Shown to significantly enhance concrete's mechanical properties, reducing reliance on synthetic reinforcement</cite> |

**Known limitation (must be stated honestly):** <cite index="156-1">plant-based fibres have long-documented issues with property variability and biodegradability risk in concrete's high-alkaline pore environment</cite> — this is the natural-fibre equivalent of the alkali-degradation problem that AR (alkali-resistant) glass fibre was specifically engineered to solve in standard GFRC. Surface treatment (alkaline pre-treatment, stearic acid) measurably helps but doesn't fully eliminate the concern — any natural-fibre GFRC application in this project should budget for this as an open engineering question, not a solved one.

### Built Precedent — livMatS Pavilion & Hybrid Flax Pavilion (Universities of Freiburg & Stuttgart, ICD/IntCDC)

Two real, built projects, though worth being precise about what they actually demonstrate: **neither uses flax fibre mixed into a concrete matrix** (i.e., neither is literally "flax-GFRC"). Instead:

- <cite index="163-1">livMatS Pavilion (2021) is the first-ever building with a load-bearing structure made entirely of robotically wound flax fibre — 15 coreless components, no concrete at all, weighing about 1.5 tonnes total, wound using a robotic arm around a reusable winding frame.</cite>
- <cite index="161-1">Hybrid Flax Pavilion pairs thin cross-laminated timber with robotically wound flax fibre bodies for the roof structure, sitting on a geothermally-activated floor slab made from recycled concrete and CO₂-reduced cement.</cite> <cite index="164-1">The load-bearing structure was assembled in just eight days using minimally invasive construction methods and pre-assembled hybrid components.</cite>

**Honest positioning for this project:** these are precedents for *flax fibre as a genuinely circular structural material alongside circular concrete*, not for flax fibre *inside* a GFRC mix. They're the closest built, real-world evidence that flax fibre performs at genuine structural scale (not just lab specimens) — directly useful for arguing plant fibre is viable in principle — but the actual fibre-in-concrete-matrix application (true "flax-GFRC") remains mostly at the research-paper stage, not yet built at pavilion scale.

---

## Family 2 — Mineral Fibre (Basalt) — the Closest Direct GFRC Substitute

<cite index="168-1">Basalt fibre has gained popularity specifically as a potential competitor to glass fibre in concrete reinforcement, due to its excellent mechanical properties and more environmentally friendly manufacturing process — basalt fibres typically have tensile strength slightly higher than E-glass fibres, and far greater than steel fibres.</cite> <cite index="170-1">Manufacturing is essentially identical to glass fibre production, but with no chemical additives and less energy used, making it cheaper than carbon or standard glass fibre.</cite> Basalt is <cite index="170-1">a volcanic rock, historically used as a building and paving stone since Roman times</cite>, now processed into continuous fibre the same way glass is.

**Performance data:** <cite index="170-1">studies report compressive strength improvements ranging from roughly 7–14% when basalt fibre is added to concrete at various dosages</cite> — comparable to, and in some studies better than, equivalent glass fibre additions.

### Direct Architecture Precedent — Basalt Fibre Reinforced Precast Concrete Panels

<cite index="171-1">A precast wall panel study cast basalt fibre matting directly into the middle of the concrete cross-section (between two concrete layers), vibrated for bonding, and tested for frost resistance and durability — explored specifically as an alternative concept for exterior wall panels, the most heavily weather-exposed part of any building.</cite> <cite index="171-1">The same research proposed basalt fibre panels for refugee shelter modules in Jordan, evaluated for thermal comfort performance via building simulation.</cite> This is a genuinely direct GFRC-format precedent — the same panel geometry and casting method as standard GFRC, with basalt fibre substituted for glass.

**Computational fabrication precedent:** <cite index="167-1">research into parametrically-defined sculptural concrete façade elements has specifically tested basalt fibre (in both bundle-dispersion and "minibar" forms) for flexural and impact performance, finding that minibars specifically improved post-cracking behaviour</cite> — directly relevant if this project pursues a digitally-fabricated, non-repeating GFRC panel system (per the growth-algorithm computational lead).

**Why basalt is the strongest single candidate for this project:** it's a drop-in geometric/process substitute (same casting method as standard GFRC, same panel format as the main GFRC precedent already documented in `06_Precedent_Research/GFRC_PRECEDENT.md`), avoids virgin glass fibre's higher cost and carbon footprint, and unlike plant fibres doesn't carry the alkaline-degradation question mark.

---

## Family 3 — Genuinely Recycled/Waste Fibre (closest to "circular" in the strictest sense)

Three real waste-fibre streams researchers have successfully tested as concrete reinforcement — none yet at pavilion-built scale, all at lab/research-paper stage, but worth documenting since this is the most literally "circular" of the three families:

| Fibre Source | Waste Stream | Key Finding |
|---|---|---|
| Recycled steel fibre from waste tyres (RSF) | End-of-life vehicle tyres | <cite index="175-1">High-strength concrete with 1.2% RSF by volume showed the best strength improvement across all tested dosages, with damping ratio and dynamic modulus results confirming genuine valorisation potential for this waste stream, backed by full lifecycle analysis</cite> |
| Recycled carbon fibre (rCF) | Aerospace/automotive composite waste | <cite index="180-1">rCF production is still energy-intensive, but offers significant energy and raw material savings over virgin carbon fibre and can lower global warming impact; carbon's non-corrosive properties also allow slimmer concrete components than steel reinforcement would need</cite> |
| Recycled glass fibre (from GFRP/GFRC waste) | GFRP/GFRC manufacturing and end-of-life waste (directly connects to `RECLAIMED_GFRC.md` List B) | <cite index="154-1">A hybrid composite study found waste glass fibres enhanced tensile strength by 88% compared to natural-fibre-only composites, while also showing lower water uptake than flax or hemp fibre composites — recycled waste glass fibre offered comparable mechanical performance to virgin glass fibre while drastically lowering raw material consumption</cite> |

**Key honest caveat on rCF specifically:** <cite index="177-1">virgin carbon fibre dosed at just 1% of cement mass in 1m³ of concrete would cost roughly 1,155 CNY in fibre alone — already exceeding the cost of the concrete itself — which is exactly the economic problem recycled carbon fibre is trying to solve, though recycled fibre still carries reduced/inconsistent length and surface-bonding challenges from the recycling process itself.</cite>

---

## Recommendation for This Project

Ranked by realistic fit given this project's timeline and fabrication access:

1. **Basalt fibre** — strongest overall candidate. Direct drop-in substitute for the glass fibre in the main GFRC precedent already researched (`06_Precedent_Research/GFRC_PRECEDENT.md`), genuine architectural precedent at panel scale, avoids the alkaline-degradation question mark that both plant fibre and to a lesser extent standard glass fibre carry, and is commercially available (not a lab-only material).
2. **Recycled waste glass fibre** — genuinely circular (literally closes the loop on GFRC/GFRP waste already flagged in `RECLAIMED_GFRC.md`) and shown to perform comparably to virgin glass fibre, but sourcing a consistent recycled glass fibre supply at student-project scale is the open practical question — same sourcing-difficulty honesty flag already given to reclaimed GFRC panels generally.
3. **Flax/hemp** — strongest *narrative* fit (natural, low-carbon, real built pavilion precedent exists) but the built precedent is fibre-as-primary-structure, not fibre-in-a-GFRC-mix — would require this project to do genuinely novel testing work (surface treatment, alkalinity trials) rather than following an established recipe.
4. **Recycled carbon fibre** — technically the most exciting given carbon fibre's strength, but its recycling process and cost profile make it the least realistic for a student-project timeline; flag as "known but not pursued" in the presentation rather than a real option.

## Fits Into the Existing System

**Chain 8 — Virgin/recycled glass fibre → basalt fibre substitution → panel casting → Precedent: Basalt Fibre Reinforced Precast Concrete Panels.** Strategy: swap the fibre component of an established GFRC panel-casting process for a lower-carbon, lower-cost mineral fibre with equivalent or better tensile performance, without changing the casting method, connection strategy, or panel geometry already established via the main GFRC precedent (Chain 4). This is the most "drop-in" chain of the whole systemic map — everything else about Chain 4's fabrication logic (flexible mould table, engineered connections) transfers directly.

## Sources
- CO₂/cost comparison data: multiple ScienceDirect reviews on natural fibre reinforced concrete (search results 150, 153)
- livMatS / Hybrid Flax Pavilion: https://www.azuremagazine.com/article/a-recyclable-university-pavilion-high-in-flax-fibre/ ; https://www.icd.uni-stuttgart.de/projects/hybrid-flax-pavilion/
- Basalt fibre concrete mechanics: https://www.sciencedirect.com/science/article/abs/pii/S0950061816312727
- Basalt fibre precast panels (refugee shelter application): https://www.researchgate.net/publication/319490688_Basalt_fiber_reinforced_precast_concrete_panels-an_alternative_concept
- Parametric sculptural FRC facade research (basalt fibre types): https://www.researchgate.net/publication/325682579_PARAMETRIC_DESIGN_OF_SCULPTURAL_FIBRE_REINFORCED_CONCRETE_FACADE_COMPONENTS
- Recycled steel fibre from tyres: https://www.sciencedirect.com/science/article/pii/S2666165924000851
- Recycled carbon fibre in concrete: https://www.mdpi.com/2071-1050/17/6/2779
- Recycled glass fibre hybrid composites: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12030246/
