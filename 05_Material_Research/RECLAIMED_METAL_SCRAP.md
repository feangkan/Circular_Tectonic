# Reclaimed Metal Scrap — Material List

Compiled to feed both the material catalogue and the growth-algorithm structural network (see `07_Computational_Design/BIOMORPHIC_GROWTH_ALGORITHMS.md`). <cite index="15-1">Steel is the most recycled material in active use today, with over 1,085 million tons recycled worldwide annually</cite>, and <cite index="15-1">99% of structural steel is recycled</cite> — so availability at any scrap yard or demolition site is close to guaranteed; the question is condition and geometry, not existence.

## List A — Structural/Sectional Scrap (primary candidates for a growth-network frame)

| Type | Typical Source | Typical Dimensions/Form | Condition Notes | Fit for Growth-Network Structure |
|---|---|---|---|---|
| Steel I-beams / H-beams | Demolished commercial/industrial buildings | Non-standard, source-dependent depth/flange width | Surface rust, occasional weld/bolt scars from original use | Good as primary "trunk" members at high-load network nodes |
| Angle iron / flat stock | Demolition, fabricator offcuts | Short-to-medium lengths, variable | Often better condition than large sections (less structural fatigue) | Good as secondary bracing members |
| Steel tubing (square/rectangular/round) | Scrapyards, fencing/railing removal | Variable diameter/section, cut lengths | Usually clean-cuttable to size | Well suited to node/connector design — round section works naturally with a 3D-printed or welded socket joint |
| Steel plate offcuts | Fabricator waste, shipyard/industrial offcuts | Irregular polygon shapes, variable thickness | Cut edges may be rough/oxidised | Good as flat "skin" panel fragments (see List C) or node gusset plates |
| Rebar (reinforcement bar) | Demolished concrete structural elements | 6–40mm diameter, straight or bent | Surface rust, may be embedded with concrete residue needing removal | Interesting fit for a growth-network aesthetic — naturally linear, bendable, reads as "branching" |

## List B — Found/Consumer-Object Scrap (lower structural value, high character)

| Type | Typical Source | Typical Dimensions | Condition Notes | Design Fit |
|---|---|---|---|---|
| Beverage/food cans (aluminium/steel) | Recycling stream, municipal collection | Standard can geometry, thin gauge | Clean if sourced pre-crush; crushed if from general recycling | <cite index="11-1">A recurring precedent in scrap-metal architecture — smaller structures have been made almost entirely from items like discarded license plates and cans</cite>; best as a decorative/skin infill rather than structure |
| License plates / signage offcuts | Scrap metal recyclers, vehicle recycling | Standard flat plate, roughly A5–A4 size | Painted/printed surface, generally sound flat sheet | <cite index="11-1">Directly precedented — small scrap-metal sheds have been built primarily from old license plates</cite>; good textured cladding unit |
| Appliance/whitegoods panels | E-waste/appliance recyclers | Flat or curved sheet panels, variable gauge | Painted steel, generally sound | Candidate for fold-and-bend skin panels (see fabrication doc) |
| Bicycle/vehicle frame offcuts | Bike shops, scrapyards | Tube sections, various diameters | Variable alloy (steel or aluminium — needs sorting) | Small-scale node/connector stock; aluminium pieces need separating from steel before any welding |

## List C — Reclaimed Metal Sheet (dedicated category — flat stock for skin/cladding)

Separated out explicitly because sheet is a distinct structural role from sectional/tube stock (List A) — it's the material that actually gets fold/bend/rivet fabrication applied to it (see `08_Fabrication_Methods/FABRICATION_METHODS.md`), so it deserves its own entry rather than being buried inside "found objects."

| Type | Typical Source | Typical Dimensions | Condition Notes | Fabrication Fit |
|---|---|---|---|---|
| Roofing/cladding steel sheet (corrugated or flat) | Demolition/renovation roof strip-outs, shed/warehouse teardown | Large flat/corrugated sheets, standard gauge (~0.4–0.6mm) | Often galvanised (good corrosion resistance already built in); may have old fixing holes | Prime candidate for fold & bend skin panels — already sheet-scale, minimal recutting needed |
| Aluminium composite panel (ACP) offcuts | Shopfitters, signage fabricators, facade contractors | Flat panel offcuts, various sizes | Two thin aluminium skins bonded to a plastic core — check core condition, not just surface | <cite index="50-1">The same dry-joint cladding-attachment logic used for new ACM/ACP facade panels applies directly to reclaimed offcuts — proven demountable, repairable panel system</cite> |
| Stainless steel sheet offcuts | Commercial kitchen fitout waste, fabricator offcuts | Small-to-medium flat pieces, consistent gauge | Usually very good condition (stainless doesn't rust) | Best-condition sheet option available; good for small feature panels or connector covers |
| Appliance/whitegoods sheet panels | E-waste/appliance recyclers | Flat or pre-curved panels, thin gauge | Painted steel, generally sound | Fold/bend candidate; painted finish can be kept as found colour/texture |
| Drum/barrel steel (flattened) | Industrial waste streams, oil/chemical drum recyclers | Curved sheet, becomes flat once cut and unrolled | Needs thorough cleaning/degreasing before any use — safety-critical if drum previously held chemicals | Distinctive pre-curved memory in the metal — interesting for a growth-network skin that wants to reference a "grown" curvature rather than starting flat |

**Sourcing note:** sheet is generally the easiest reclaimed metal sub-category to source in useful quantity, since roofing/cladding strip-outs happen constantly on renovation sites — worth prioritising a relationship with a roofing/demolition contractor specifically for this category.

## List D — Aluminium-Specific Scrap (lighter-weight structural option)

<cite index="13-1">Aluminium scrap ranges from very early manufacturing waste (scalping chips, off-cuts from ingot surface preparation) to post-consumer scrap like crushed beverage cans</cite> — useful to know because these two streams behave very differently when sourcing:

| Type | Source | Notes |
|---|---|---|
| Aluminium extrusion offcuts | Window/curtain-wall fabricators, shopfitters | Clean, consistent sections — closest thing to "standardised" reclaimed stock available; worth prioritising a fabricator relationship here |
| Aluminium sheet offcuts | Signage/fabrication shops | Flat, light, easy to fold/bend by hand at pavilion scale | Strong candidate for skin panels — much lighter than steel equivalent |
| Crushed cans / found aluminium objects | General recycling | <cite index="13-1">Non-uniform shapes, jagged edges from processing — genuinely difficult to use structurally without reprocessing</cite> | Decorative/textural use only, not structural |

## Sourcing & Condition-Assessment Notes

- **Melbourne sourcing leads to chase:** metal recyclers/scrap yards (will generally sell small quantities of sorted offcuts cheaply), demolition contractors (ask about small-quantity salvage before a job goes to bulk scrap), RMIT workshop metal offcut bins, local fabricators/welders (offcuts from custom jobs).
- **Before use, every piece needs:** wire-brush to remove loose rust, magnet test to separate ferrous/non-ferrous (critical before welding — mixing alloys at a joint is a real failure risk), rough dimension/weight logging for the catalogue.
- **Safety flag:** older painted steel (pre-1978 in many countries) may carry lead paint — worth a quick check before any grinding/cutting that would aerosolise dust, and definitely before any welding that would burn the coating.
- **Honesty check for the catalogue:** structural sections (List A) are the genuinely load-bearing option; found-object scrap (List B) is best treated as cladding/texture, not structure — mixing the two roles up is the most common mistake in scrap-metal pavilion projects.
