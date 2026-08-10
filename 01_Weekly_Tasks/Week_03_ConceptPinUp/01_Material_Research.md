# Week 3 (v2) — Circular Material Research

Three material families, each assessed against the brief's seven required categories. Full detail in the dedicated documents referenced under each heading — this is the synthesis.

---

## Family 1 — Reclaimed Metal

*(Full detail: `05_Material_Research/RECLAIMED_METAL_SCRAP.md`)*

- **Source:** Demolition sites (structural sections, sheet), scrap yards, fabricator offcuts, roofing/cladding strip-outs, scrapped bicycles/appliances.
- **Physical characteristics:** Zero material degradation from prior structural use (unlike concrete); surface rust/patina; visible prior fixing holes and weld scars.
- **Typical dimensions:** Highly variable by source — non-standard sections from structural scrap; roofing sheet arrives close to usable panel scale already.
- **Structural behaviour:** Full retained steel/aluminium performance; smaller sections needed than timber for equivalent load; proven in-service performance.
- **Advantages/limitations:** Long slender spans, legible connections, infinitely recyclable at true end-of-life — against surface prep needs, non-standard sizing complicating connectors, welding vs. bolting trade-off between speed and disassembly.
- **Environmental implications:** Steel production is highly energy-intensive, so *reuse* (not just remelting) captures the most embodied-energy saving.
- **Existing applications:** Temp'L Pavilion (ship steel), Zephyr Pavilion/The Orb (new aluminium, riveted thin-shell method directly transferable to reclaimed sheet), Antepavilion 2026 (inventory-constrained steel armature).

## Family 2 — GFRC (+ Circular Fibre Alternatives)

*(Full detail: `05_Material_Research/RECLAIMED_GFRC.md` and `CIRCULAR_FIBRE_FOR_GFRC.md`)*

- **Source:** No true public salvage stream exists (unlike timber/metal) — realistic sourcing is fabricator offcuts/rejects, or ground waste as new aggregate.
- **Physical characteristics:** Thin-cast, ~10mm wall achievable when sprayed; can be shaped into complex/compound curves; matte or fine finish depending on mix.
- **Typical dimensions:** Panel-scale, typically ~1.2×1.2m in documented precedent (Thinking Space/Testing Space).
- **Structural behaviour:** Compression strength 50–80MPa, tensile 8–11MPa (sprayed GFRC); genuinely self-supporting at thin-shell scale when panelised and connected properly (see GFRC precedent).
- **Advantages/limitations:** ~75% lighter than solid concrete, fire-rated (Class A1), moulds to any curve — against brittleness (can't drill/modify on site), and a genuinely thin reclaimed-material stream.
- **Environmental implications:** Avoids new concrete's high embodied carbon; **fibre component itself can be swapped** — basalt fibre is a drop-in substitute for virgin glass fibre with equal-or-better tensile strength, less energy, lower cost, no chemical additives.
- **Existing applications:** Schlaich's Stuttgart Garden Pavilion (1977, origin of structural GFRC), Thinking Space/Testing Space (2015, full structural/connection data), Basalt Fibre Reinforced Precast Panels (direct fibre-substitution precedent).

## Family 3 — Circular Wood

*(Full detail: `05_Material_Research/RECLAIMED_WOOD.md`)*

- **Source:** Structural — demolition beams, glulam, railway sleepers. Engineered offcuts — CLT/glulam production waste (a genuinely unique category, no metal/GFRC equivalent). Sheet — formply, construction offcuts. Found-object — pallets, barrel staves, scaffold boards.
- **Physical characteristics:** Visible grain/patina; CLT offcuts are new-condition factory waste, not damaged material.
- **Typical dimensions:** Structural sections highly variable; CLT offcuts ~1×1m and 2×1m (door/window cut-outs); formply 2400×1200mm standard.
- **Structural behaviour:** Reclaimed softwood 10–15MPa bending, hardwood 40–80+MPa; CLST (CLT from reclaimed feedstock) shows no significant strength difference from new CLT in published testing.
- **Advantages/limitations:** Near-zero cost, warm/legible material, simple tooling — against inconsistent quality requiring piece-by-piece grading, and (for engineered panels specifically) adhesive content limiting true recyclability even though reuse works well.
- **Environmental implications:** Diverts directly from landfill/demolition waste; low reprocessing energy.
- **Existing applications:** Re-Emerge (kerfed pallet wood), EPFL Ski Pavilion (graded reclaimed sports equipment, elastic gridshell), DTC Timbershell (CLT offcuts into polygonal shells), Combo-Nest/Sanchez (discrete standardised joinery tolerant of irregular reclaimed stock).

---

## Cross-Family Synthesis — Why These Three Together

| | Metal | GFRC | Wood |
|---|---|---|---|
| Best structural role | Primary frame/tension | Thin-shell skin panels | Structural sections + found-object infill |
| Fabrication method (from `08_Fabrication_Methods/`) | Fold & bend, rivet, weld, dry joint | Cold casting, dry joint (embedded fittings) | Aggregation, dry joint (mortise-tenon) |
| Biggest sourcing win | Metal roofing sheet (abundant, near-usable as-is) | Basalt-fibre-swapped mix (avoids weak reclaimed-panel stream entirely) | CLT production offcuts (genuinely unique, high-value stream) |
| Computational fit | Growth-algorithm stripe/panel segmentation (Thin-Shell precedent) | Flexible mould table matches non-repeating growth output | Discrete combinatorial joinery absorbs dimensional variability (Sanchez) |

Every family independently converges on the same principle established across the whole semester: **grade the material (or, per Sanchez, standardise the joint instead) and let a computational process respond to real, measured variability** — this is now the throughline for the presentation.
