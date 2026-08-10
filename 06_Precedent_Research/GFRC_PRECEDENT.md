# GFRC Precedent — Structural Thin-Shell GFRC

This fills the gap flagged in Chain 4 of `09_Systemic_Design_Framework/MATERIAL_FABRICATION_PRECEDENT_SYSTEM_MAP.md`, which previously cited generic industry installation practice rather than a named project. Two real precedents here — one historical origin point, one detailed modern case study with full structural data — written in the same slide-ready block format as `06_Precedent_Research/MAIN_PRECEDENT_THIN_SHELL_METAL.md`.

---

## PRECEDENT 1 (Origin) — Stuttgart Garden Pavilion, Jörg Schlaich (1977)

**Designer:** Jörg Schlaich
**Location:** Stuttgart, Germany
**Year:** 1977
**Significance:** <cite index="149-1">The first proposed structural use of GFRC for complex-geometry buildings.</cite>

### Key Facts (slide-ready)
| Metric | Value |
|---|---|
| Number of shells | 7 identical shells |
| Casting method | Cast in-situ on a wooden formwork |
| Shell geometry | Monolithic, hyperbolic form per shell |
| Assembly | Individual shells connected together after casting |

### Why It Matters
This is the founding precedent for everything downstream in GFRC shell design — <cite index="149-1">it sits in a lineage alongside the first monolithic concrete shell structures by Torroja, Candela, Isler, and Nervi</cite>, but Schlaich's pavilion specifically was the first to prove GFRC itself (not just conventional reinforced concrete) could carry a complex hyperbolic shell geometry structurally, not just as cladding. Every GFRC precedent since — including Precedent 2 below — builds directly on this project's basic proof of concept.

---

## PRECEDENT 2 (Main detailed case study) — "Thinking Space / Testing Space," Arup HQ Artwork Competition (Henriksen, Allan, Knaack, Lo — 2014–2016)

**Designer/Architect:** Ben Allan (concept), T. Henriksen (Delft Technical University, with Waagner Biro), supervised by Ulrich Knaack (TU Delft) and Stephen Lo (University of Bath)
**Client/Context:** Design competition for an artwork at Arup HQ, London, 2015
**Intended completion:** 2016 (pending connection detail testing at time of publication)

### Key Facts (slide-ready)
| Metric | Value |
|---|---|
| Number of elements | 96 free-form thin-walled GFRC panels |
| Element size | ~1.2m × 1.2m each |
| Proposed height | 12 metres |
| Wall thickness (monolithic model) | 10mm |
| Fabrication method | Sprayed GFRC on a digitally-driven flexible mould table |

### Design Concept
<cite index="149-1">The geometry is a hyperbolic form based directly on the catenary systems of Antoni Gaudí and Heinz Isler — a shape that, by definition, sits in pure compression under its own weight</cite>, generated using <cite index="149-1">a Grasshopper script for Rhino, which allowed the height, number, and size of elements to be adjusted and let the artwork be scaled to different sizes.</cite> <cite index="149-1">The parametric model divided the form into equal-sized elements everywhere except around the entrance openings at the base, where curvature changed too sharply to keep elements uniform.</cite>

### Structural Strategy — Monolithic vs. Discretised (the genuinely useful comparison for this project)
The project ran a full structural comparison between two build strategies:

| | Monolithic model | Discretised model |
|---|---|---|
| Description | <cite index="149-1">Cast as one continuous shell</cite> | <cite index="149-1">Comprised of small elements joined by structural connections</cite> |
| Max stress | 6 MPa (26 MPa at opening singularities) | 10 MPa (43 MPa at opening singularities) |
| Max deflection | 12.7mm (span/950) | 32.3mm (span/370) |
| Feasibility | Structurally cleaner, but impossible to fabricate/transport at 12m scale as one piece | <cite index="149-1">Feasible, but success depends entirely on how well the connections between elements are engineered</cite> |

<cite index="149-1">The discretised model's stresses came close to the maximum tensile strength limit of the sprayed GFRC, meaning thicker elements needed to be considered specifically at the base of the artwork where loads concentrate.</cite>

### Fabrication Strategy — Three Connection Types Tested
This is the most directly transferable part of the whole precedent for this project's own connector/node design work:

1. **Bolted connection with latch plates** — <cite index="149-1">close-fit predrilled bolt holes transferring force directly from one element to the next, connecting four elements together at each corner.</cite>
2. **Cast-in stainless steel angle** — <cite index="149-1">a stainless steel angle cast directly into the GFRC element during spraying, able to transfer small moments (unlike the bolted option) and only visible from inside the element — but more labour-intensive and protrudes into the interior space.</cite>
3. **Embedded anchor** — <cite index="149-1">an anchor bolt embedded in the concrete plate itself, invisible from the front face, but limited to automated premixed concrete panel production; tested to a design shear load of 1.7kN.</cite>

<cite index="149-1">Load calculations for the discretised shell found a maximum bending moment of 108kNm from a simple cantilever assumption, with a maximum tensile force of 36kN across the connections — only four of the middle panels were capable of transferring load given the geometry, and each would need roughly six undercut-anchor fixings if that connection type were used.</cite>

### Material Properties Used (useful reference data for slides)
| Property | Value |
|---|---|
| Density | 19–21 kN/m³ |
| Compression strength | 50–80 MPa |
| Elasticity modulus | 10–20 GPa |
| Tensile strength | 8–11 MPa |
| Moment of rupture | 21–31 MPa |

### Fabrication Method — Flexible Mould Table
<cite index="149-1">Elements were fabricated using the spraying method specifically because it produces an acceptable surface quality with fewer rejections compared to other GFRC casting methods, and because it allows a connection detail to be embedded directly into the element during spraying.</cite> <cite index="149-1">The doubly-curved geometry of each unique element was formed using a digitally-driven flexible mould table — the table's shape was generated directly from the parametric model, allowing 48 individual moulds to be produced in a timely, cost-effective way rather than requiring 48 separate fixed moulds.</cite>

---

## Why This Precedent Matters for This Project

1. **Directly validates the "design connections into the mould" principle already stated in Chain 4** of the systemic map — this precedent's entire connection-detail R&D effort (three tested options) exists specifically because that principle is hard in practice, not just a nice idea.
2. **The monolithic-vs-discretised comparison is a genuinely useful structural argument for the growth-algorithm paneling approach** — it gives real numbers showing the trade-off (discretised = buildable but nearly 3x the deflection and connection-dependent) rather than just asserting panelisation is "the circular/disassemblable choice."
3. **The flexible mould table solves GFRC's biggest fabrication problem for a growth-algorithm output** — a differential-growth-generated surface produces many unique, non-repeating panel shapes; a fixed mould per panel would be prohibitively expensive, but a digitally-reconfigurable flexible table (reshaped between casts, driven by the same parametric model that generated the geometry) is a direct, provable solution to exactly that problem.
4. **Historical grounding** — Schlaich's 1977 pavilion gives this material palette a 45+ year structural pedigree, useful for answering any studio-discussion pushback on whether GFRC can really be structural rather than just decorative cladding.

## Sources
- Origin precedent (Schlaich, 1977): cited within Henriksen et al. 2015, referencing J Schlaich & W Menz, "The application of glass fibre reinforced concrete for shell structures," IASS, Oulu, 1980.
- Main case study: T. Henriksen, U. Knaack (TU Delft) & S. Lo (University of Bath), "Advancing the architectural application of complex geometry GFRC," GRCA Congress 2015. Full paper: https://grca.org.uk/pdf/congress-2015/21%20Advancing%20the%20architectural%20application%20of%20complex%20geometry%20GFRC.pdf

## Recommended Update to Systemic Map
Chain 4 in `09_Systemic_Design_Framework/MATERIAL_FABRICATION_PRECEDENT_SYSTEM_MAP.md` should be updated to reference this precedent directly instead of generic rainscreen installation practice — flagging as a follow-up edit rather than doing it silently here, since it changes an existing chain's evidentiary basis.
