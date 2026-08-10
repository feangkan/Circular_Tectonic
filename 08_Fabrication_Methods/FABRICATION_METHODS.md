# Fabrication Methods — Fold & Bend, Cold Casting, Weld, Rivet, Aggregation, Dry Joint

Six methods requested, assessed specifically against this direction's two real-world constraints: (1) the reclaimed metal scrap and GFRC catalogued above is dimensionally irregular, and (2) a growth-algorithm structural network produces many small variable-angle connections rather than a few large standard ones. Each method is scored on how well it copes with those two constraints, not just described generically.

---

## 1. Fold & Bend (sheet metal forming)

**What it is:** <cite index="40-1">Sheet metal folding uses a folding machine where the sheet is clamped and a folding beam pivots to create bends, while bending typically uses a press brake with a punch and die.</cite> <cite index="35-1">Common architectural techniques include air bending (punch applies pressure without fully seating in the die, leaving flexibility in the final angle), bottoming (sheet fully pressed into the die for a precise repeatable angle), and coining (extreme force locking the bend permanently through the material thickness).</cite>

**Applied to this project:** Best suited to reclaimed flat sheet stock (steel plate offcuts, aluminium sheet, appliance panels — List B/C in the metal scrap document) being turned into skin/cladding panels or structural gusset/node plates. <cite index="36-1">Folded sheet metal is a well-established facade cladding technique specifically because the folding process itself creates the visual and structural texture — no separate finishing step needed.</cite>

**Fit for irregular reclaimed stock:** Good — folding tolerates variable sheet size well (you fold what you have), though thickness must be reasonably consistent within a single folded piece for the bend to behave predictably. Hand tools (manual folders, box-and-pan brakes) can achieve simple folds at pavilion scale without needing CNC access — a genuine advantage before Hong Kong fabrication access opens.

**Growth-network fit:** Moderate — folding produces flat-derived, faceted curvature (a series of straight folds approximating a curve) which pairs naturally with a *discretized* growth output (see computational design doc's note on discretized vs. free-form growth) rather than a fully smooth double-curved surface.

---

## 2. Cold Casting

**What it is:** <cite index="31-1">Mixing metal powder (aluminium, brass, nickel-silver, copper) into a resin until thick and creamy, then pouring or brushing into a mould; the cured part has the weight and surface appearance of solid metal without melting any actual metal.</cite> <cite index="34-1">Popular for sculptural, decorative, and restoration work — reproducing a missing or damaged metal detail without the cost and equipment of true foundry casting.</cite> After curing, <cite index="30-1">the surface is burnished with steel wool and can be given an aged/patinated finish.</cite>

**Applied to this project:** This is the connector between the metal-scrap and GFRC-adjacent research — cold casting is essentially "casting a metal-look object using resin + metal powder," and ground GFRC waste (List B in the GFRC document) could similarly be blended into a resin matrix for small connector nodes, following the same logic.

**Honest limitation:** <cite index="27-1">Cold-cast parts don't have true structural metal strength — they're a surface/appearance technique, not a load-bearing casting method</cite>, so this is realistically a finishing/detailing technique (decorative nodes, small non-structural connector caps, texture/patina matching between old and new metal elements) rather than a primary structural fabrication method. Worth stating this clearly in the presentation rather than overselling it as a structural casting technique.

**Growth-network fit:** Useful specifically for casting small custom node covers over irregular welded/riveted joints — giving visually consistent "grown" node geometry even when the underlying joint (welded scrap of variable section) is inevitably irregular underneath.

---

## 3. Weld

**What it is:** Fusing two metal pieces by melting the joint interface (with or without filler material) so they become continuous once cooled.

**Applied to this project:** <cite index="53-1">Compared to riveting and bolting, welding provides a strong and continuous joint, though it can introduce a heat-affected zone and residual stress in the surrounding material.</cite> For reclaimed steel scrap specifically, this matters because a previously-stressed or fatigued piece may behave unpredictably under welding heat — visual inspection and a test weld on a scrap sample from the same source batch is worth doing before committing to a structural joint.

**Fit for irregular reclaimed stock:** Good — unlike bolting, welding doesn't require matched pre-drilled holes, so it copes well with genuinely non-standard scrap geometry (exactly the Bamboo 3D-printed-joint problem from Week 3's precedent research, but solved by melting rather than by a custom-printed socket).

**Trade-off (directly relevant to circular design principles):** Welding is <cite index="53-1">permanent and cannot be easily disassembled or modified</cite> — which cuts directly against the studio's design-for-disassembly principle established across nearly every precedent studied so far. **Recommendation:** use welding only at primary structural nodes where permanence is acceptable, and reserve bolted/riveted/dry-joint connections (below) for anything that should remain demountable — this is the same "hybrid" strategy already flagged in `05_Material_Research/MATERIAL_RESEARCH_GUIDE.md`'s reclaimed steel section.

**Growth-network fit:** High — welding is the only method here that can join genuinely arbitrary, non-standard angles without a pre-designed connector, which matches a growth-algorithm's tendency to generate non-repeating node geometry.

---

## 4. Rivet (Metal Sheet)

**What it is:** <cite index="53-1">A rivet — a metal pin with a head — is inserted through pre-drilled holes in two parts and deformed on the far side to lock them together permanently.</cite>

**Applied to this project:** The natural joining method for the fold-and-bend sheet panels above — connecting adjacent skin panels to each other or to the primary metal-scrap frame.

**Comparison to welding/bolting:** <cite index="56-1">Riveting doesn't generate heat, so it avoids the contour distortion that welding can cause in thin sheet metal</cite> — genuinely useful for thinner reclaimed sheet stock that would warp under weld heat. <cite index="56-1">However, riveting requires access to both sides of the joint, which can be a real constraint depending on the panel/node geometry</cite>, and <cite index="53-1">like welding, it's a largely permanent connection that's not easily disassembled once installed.</cite>

**Fit for irregular reclaimed stock:** Good for sheet-to-sheet and sheet-to-frame connections specifically; less suited to the thick structural sections in the metal scrap list's List A (rivets are a thin-sheet joining method, not a substitute for structural bolting on I-beams/tubing).

**Growth-network fit:** Best suited to the skin/cladding layer of a growth-network design (where panels meet each other), rather than the primary structural nodes.

---

## 5. Aggregation

**What it is:** In this context, aggregation means assembling many small, discrete, often non-identical units into a larger coherent structure — the units stay individually distinguishable rather than fusing into a continuous material (contrast with welding). This is a structural *strategy*, not a single joining technique — it can be achieved with any of the other five methods.

**Applied to this project:** This is the direct structural expression of the growth-algorithm computational lead — <cite index="45-1">the ICD/ITKE biomimetic pavilion precedent already researched demonstrates aggregation at extreme scale, with an entire pavilion built from roughly 100,000 individual finger-joint connections</cite>, proving that a large number of small, simply-joined discrete units can resolve into a coherent large-scale structure. This is functionally identical to how differential growth itself works computationally (many small agents, simple local rules, complex emergent whole) — aggregation is the *physical* fabrication equivalent of the *computational* growth logic.

**Fit for irregular reclaimed stock:** Excellent — this is arguably the best-matched fabrication strategy of all six for genuinely irregular material, because aggregation doesn't require uniform units at all; irregular scrap pieces can simply become irregular aggregate units, with the overall system's coherence coming from the assembly logic (spacing, connection pattern) rather than from individual-piece precision.

**Growth-network fit:** Direct — this is the physical realisation of the computational approach, not just a compatible technique.

---

## 6. Dry Joint

**What it is:** A connection that relies on friction, gravity, interlocking geometry, or mechanical clamping rather than an adhesive, weld, or permanent fastener — fully reversible by design. <cite index="50-1">Dry-joint cladding attachment systems are an established facade technique specifically because they allow convenient installation, repair, or individual panel replacement without disturbing the rest of the system.</cite>

**Applied to this project:** The connection type most aligned with circular design principles of all six methods here — every precedent studied in Week 3 that explicitly discussed disassembly (Re-Emerge's lap joints, Blue Ocean Dome's no-concrete-piles approach, reclaimed concrete panels' post-installed anchor system) ultimately relies on some form of dry, reversible joint.

**Fit for irregular reclaimed stock:** Moderate — pure friction/gravity dry joints usually need reasonably consistent contact geometry to work reliably, which is harder to guarantee with irregular scrap than with, say, milled timber. Bolted connections (a mechanical, still-reversible dry-joint variant) are more forgiving of irregular stock, since <cite index="MATERIAL_RESEARCH_GUIDE" index="0">oversized bolt holes can accommodate misalignment between mismatched pieces.</cite>

**Growth-network fit:** Good for the primary "can this be taken apart and re-grown/reconfigured" narrative — worth pairing with aggregation (many small dry-jointed units) as the two techniques that most directly embody circular tectonics principles for this direction.

---

## Recommended Method-per-Role Summary

| Structural Role | Recommended Method(s) | Reasoning |
|---|---|---|
| Primary structural nodes (irregular scrap sections) | Weld (where permanence acceptable) or bolted dry joint (where disassembly needed) | Handles arbitrary angles; choose per node based on whether that specific joint needs to come apart later |
| Skin/cladding panels | Fold & bend + rivet | Established, hand-achievable, low heat distortion |
| Aggregated infill/texture zones | Aggregation of small dry-jointed or riveted units | Directly mirrors the growth algorithm's own logic |
| Decorative/connector detailing | Cold casting (metal powder + resin, or ground GFRC + resin) | Visual consistency over irregular underlying joints; not for structural loads |

**Core takeaway for the presentation:** no single method here should be used exclusively — the growth-algorithm computational lead already implies a *system* of different member/node types doing different jobs (exactly the Blue Ocean Dome material-hierarchy principle from Week 3), and this fabrication method list should be read the same way: weld where permanence is fine, dry-joint/bolt where disassembly matters, aggregation as the overarching assembly logic tying the small irregular pieces into a coherent whole.
