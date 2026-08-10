# Material Dimensions Reference — Exact Numbers for a 3×3×3m Pavilion

Companion to `02_Material_Catalogue.md`. That document's "Dimensions" column mostly said "variable" or "non-standard" — accurate for reclaimed material's actual condition, but not useful for early computational/structural planning. This document gives **real, numeric standard dimensions** for every material where an industry standard genuinely exists (AS/NZS or common Australian trade sizes, since sourcing is Melbourne-based), and is honest about the entries where no standard exists because the material is fundamentally salvage/found-condition — those are marked "No fixed standard" rather than a fabricated number.

Every dimension is read against the 3×3×3m envelope: **3000mm is the largest single usable dimension in any direction** — anything longer needs cutting/joining; anything the right order of magnitude below 3000mm can potentially be used near-whole.

---

## METAL

| ID | Material | Exact Standard Dimension | Fits 3m Module? |
|---|---|---|---|
| MET-01 | Steel I-beams/H-beams (AU Universal Beam) | Common sections: 150UB14, 200UB18, 250UB25 (depth×mass/m); stock lengths 6m/9m/12m | Cut to ≤3000mm lengths |
| MET-02 | Angle iron (AU Equal Angle) | 40×40×5mm, 50×50×6mm, 65×65×6mm, 75×75×6mm, 100×100×10mm; stock length 6m | Cut to ≤3000mm |
| MET-03 | Steel tube — SHS (Square Hollow Section) | 25×25×1.6mm, 40×40×2.5mm, 50×50×3mm, 75×75×4mm, 100×100×5mm; stock length 6–8m | Cut to ≤3000mm |
| MET-03b | Steel tube — CHS (Circular Hollow Section) | 33.7mm, 48.3mm, 60.3mm, 88.9mm, 114.3mm outer diameter; 6–8m stock lengths | Cut to ≤3000mm |
| MET-04 | Steel plate offcuts | Standard sheet 2400×1200mm or 3000×1500mm; thickness 3/5/6/8/10/12mm | 2400×1200mm sheet fits within one 3m face directly |
| MET-05 | Rebar (AU deformed bar, N-series) | N12 (12mm), N16 (16mm), N20 (20mm), N24 (24mm) diameter; stock length 6m/12m | Cut to ≤3000mm |
| MET-06 | Beverage cans | 330mL: ~66mm dia × 115mm h; 500mL: ~68mm dia × 168mm h | Small-unit aggregation only |
| MET-07 | AU number plates | 372×134mm (standard passenger plate) | Small-unit cladding tile |
| MET-08 | Appliance panels | No fixed standard — varies by appliance model | Sort/measure on collection |
| MET-09 | Bicycle frame tube | 25.4mm / 28.6mm / 31.8mm dia (standard seatpost/tube sizes); frame ~500–600mm main triangle | Small-scale node prototyping |
| MET-10 | Corrugated roofing sheet (AU Colorbond-style) | 762mm cover width; custom length to 12m; 0.42–0.48mm BMT | Cut to ≤3000mm length, tile the 762mm width across a face |
| MET-11 | ACP (aluminium composite panel) | Standard sheet 1220×2440mm or 1250×3200mm; 3–4mm thick | 1220×2440mm fits directly within a 3m face |
| MET-12 | Stainless steel sheet | Standard sheet 1200×2400mm; 0.8–1.5mm gauge (kitchen-grade) | Fits directly within a 3m face |
| MET-13 | Appliance sheet panels | No fixed standard | Sort/measure on collection |
| MET-14 | 44-gallon drum (flattened) | 572mm dia × 851mm height before flattening; ~1.2mm steel | Flattens to roughly 1.8×0.85m sheet — fits within face |
| MET-15 | Aluminium extrusion (window mullion) | Profile width typically 50–100mm; stock length 6m | Cut to ≤3000mm |
| MET-16 | Aluminium sheet | Standard sheet 1200×2400mm; 0.9–3mm | Fits directly within a 3m face |
| MET-17 | Crushed cans | No fixed standard once crushed | Small-unit aggregation only |

---

## GFRC

| ID | Material | Exact Standard Dimension | Fits 3m Module? |
|---|---|---|---|
| GFR-01/02 | GFRC panel offcuts/rejects | No fixed standard — fabricator/project-dependent; typical architectural panel run 1200×1200mm to 1500×3000mm | Sort on collection; largest standard panels approach the 3m limit directly |
| GFR-03 | Ground GFRC/GFRP aggregate | N/A — processed to fine granular, no piece dimension | Mixed into new cast, not a discrete unit |
| GFR-04 | New GFRC mix (basalt fibre) | Cast to design — sprayed wall thickness typically 10–13mm per the main precedent (`GFRC_PRECEDENT.md`) | Panel size set by growth-algorithm segmentation, capped at ≤1.2×1.2m per panel to match the flexible-mould precedent |

---

## CIRCULAR WOOD

| ID | Material | Exact Standard Dimension | Fits 3m Module? |
|---|---|---|---|
| WD-01 | Reclaimed structural beams | No fixed standard (demolition-sourced) — but original AU structural sections commonly 90×45mm to 240×45mm sawn, or 300mm+ deep for larger spans | Cut to ≤3000mm |
| WD-02 | Glulam beams | Standard AU glulam widths 65/85/135/185mm; depths 200–900mm in ~90mm increments; stock length to 24m | Cut to ≤3000mm |
| WD-03 | Railway sleepers (AU standard timber) | 2400×230×115mm (concrete AU sleepers: 2400×250×200mm) | Fits directly — just under the 3m limit |
| WD-04 | CLT production offcuts (door/window cutouts) | ~1000×1000mm and ~2000×1000mm per precedent (DTC Timbershell) | Fits directly within 3m module |
| WD-05 | CLST (reclaimed-feedstock CLT) | Matches standard CLT: thickness 60–360mm (3/5/7/9-ply), width 1.2–3.0m, length 5–18m | Width fits directly; length must be cut to ≤3000mm |
| WD-06 | Deconstructed CLT/glulam panels | As above — standard CLT panel thickness 60–360mm | Cut/select panels ≤3000mm |
| WD-07 | Formply | 2400×1200mm, 17mm or 19mm thick (AU standard) | Fits directly within a 3m face |
| WD-08 | General plywood offcuts | Standard AU plywood sheet 2400×1200mm; thickness 6/9/12/15/18mm | Fits directly within a 3m face |
| WD-09 | Set/backdrop plywood | No fixed standard — pre-cut to production-specific shapes | Sort/measure on collection |
| WD-10 | Furniture-grade veneer offcuts | No fixed standard — typically smaller format, 600–1200mm | Small-panel use |
| WD-11 | OSB/particleboard/MDF | Standard AU sheet 2400×1200mm; thickness 3–25mm (MDF), 6–25mm (particleboard) | Fits directly within a 3m face |
| WD-12 | Pallet deck boards | 22×95mm to 22×145mm section; 1000mm or 1165mm length (standard AU/CHEP pallet width) | Fits directly, multiple pieces per face |
| WD-13 | Pallet stringers/blocks | ~38×90mm section; ~1000–1165mm length | Fits directly |
| WD-14 | CHEP pallet (whole, for reference) | 1165×1165mm (AU standard) or 1200×1000mm (Euro pallet) | Deck boards/stringers fit directly once disassembled |
| WD-15 | Wine barrel stave (225L Bordeaux barrel) | ~950mm length × 100–120mm width (tapered) × 25–27mm thick | Fits directly, multiple staves per face |
| WD-16 | Scaffold board (AU/UK standard) | 225×38mm section; standard lengths 2400mm, 3000mm, 3900mm | 2400mm and 3000mm lengths fit directly |

---

## RECLAIMED FIBRE

| ID | Material | Exact Standard Dimension | Fits 3m Module? |
|---|---|---|---|
| FIB-01 | Reclaimed rope | Nautical rope diameter typically 12–24mm; coil lengths 100–220m as sourced | Cut to any length ≤3000mm per module, coiled/bundled into modules |
| FIB-02 | Reclaimed fishing net | Mesh opening 40–200mm depending on net type; roll/panel width 1–4m as sourced | Cut/panel to size, fits directly |
| FIB-03 | Reclaimed textile waste | N/A — shredded/carded to loose fibre before panel-pressing; pressed panel size set by production (e.g. sandwich panels ~600×600mm to 1200×1200mm in research precedent) | Panel size flexible, fits directly |

---

## ALTERNATIVE MATERIALS

| ID | Material | Exact Standard Dimension | Fits 3m Module? |
|---|---|---|---|
| ALT-01 | Chain-link mesh | Standard 50mm diamond mesh; roll height 900/1200/1500/1800mm; wire gauge 2.5mm | Cut to size, fits directly |
| ALT-02 | Steel cable/wire rope | Standard diameter 6/8/10/12/16/20mm | Cut to ≤3000mm |
| ALT-03 | Mycelium composite | Grown to mould — commonly tested at 300×300×50mm to 600×600×100mm block scale in current research/industry practice | Aggregate multiple blocks per face |
| ALT-04 | Reclaimed glass | Standard glazing sheet 2440×1220mm to 3210×2250mm; thickness 4–12mm | Fits directly within a 3m face |
| ALT-05 | Reclaimed rubber (conveyor belt) | Standard conveyor belt width 450–2000mm; thickness 3–15mm, as sourced in rolls | Cut to size, fits directly |
| ALT-06 | Bicycle components | Tube diameter 25.4/28.6/31.8mm; wheel diameter 622mm (700c) or 559mm (26") | Small-scale, aggregate multiple units |

---

## Reading This Table for Pavilion Design

- **Genuinely modular at 3m scale without cutting:** most sheet goods (ACP, stainless sheet, aluminium sheet, formply, plywood, OSB, reclaimed glass) — all standard sheet sizes sit comfortably within a 3×3m face.
- **Needs cutting to length:** all linear/sectional stock (I-beams, angle, tube, rebar, glulam, cable) — stock lengths (6–24m) exceed the pavilion envelope and must be cut down; this is normal and expected, not a sourcing problem.
- **Genuinely no fixed standard (honest flag):** demolition-sourced structural beams, appliance panels, set/backdrop plywood, crushed cans — these need to be measured individually on collection, which is exactly why the catalogue's field-documentation step (per `MATERIAL_RESEARCH_GUIDE.md`) matters before design can rely on them.
- **Found geometry smaller than 3m, used as a repeating unit:** cans, number plates, pallet boards, barrel staves, scaffold boards, bicycle components — these were never going to span the full 3m on their own; they're aggregation-strategy materials (Fabrication Method: Aggregation, per `08_Fabrication_Methods/FABRICATION_METHODS.md`) by nature of their size, not by design choice.
