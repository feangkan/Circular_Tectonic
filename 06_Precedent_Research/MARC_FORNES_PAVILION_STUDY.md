---
tags: [precedent]
architect: Marc Fornes / THEVERYMANY
year: 2015-2025
material: 3-6mm aluminium sheet (alloy 5052)
fabrication: CNC/laser-cut flat stripes, riveted, hand-curved on assembly
---

# Precedent — Marc Fornes / THEVERYMANY: Technique, Materials, Structure Type

**Architect / studio:** Marc Fornes (founder), THEVERYMANY, New York
**Years covered:** Vaulted Willow (2015) → Zephyr Pavilion (2019) → The Orb (2025) → PILOTI (2025)
**Location:** Built work across North America (Edmonton, Lubbock TX, Bellevue WA, Mountain View CA)
**Material:** Perforated/solid aluminium sheet, alloy 5052, 3–10mm depending on part role
**Fabrication method:** Flat-pattern CNC/laser-cut "stripes," hand- or jig-curved, riveted into a self-supporting doubly-curved shell — no welding, no separate structural frame
**Source / link:** see Sources section below

This note pulls together the Marc Fornes material already scattered across `MAIN_PRECEDENT_THIN_SHELL_METAL.md` (Zephyr, The Orb) with two projects flagged there as a "next research step" but not yet written up — **Vaulted Willow** and **PILOTI** — into one focused study of *his* technique specifically, separated from the XISUI Nest Pavilion comparison. Where the two documents overlap, this one goes deeper on the numbers.

---

## 1. What They Did

Marc Fornes founded THEVERYMANY around a single, decade-long research question: how thin can a self-supporting architectural shell be made, using only flat sheet stock and no separate skeleton, if the *geometry itself* is engineered to carry the load? Every built project is a variation on the same building system, refined project to project rather than reinvented.

### 1.1 The technique — "Structural Stripes" / "Crawling Assemblies"

- The studio's whole body of work is grouped under the name **"Crawling Assemblies"** — a family of self-similar, curvilinear, doubly-curved shell structures.
- The building system used to realise them is called **"Structural Stripes."** A target double-curved surface is computationally unrolled/segmented into a network of narrow, flat, custom-shaped aluminium strips ("stripes"). Each stripe is individually unique — no two parts are identical — because each carries a slightly different curvature and connection geometry dictated by its position on the target surface.
- Each stripe does two jobs at once: it **carries load** along its length, and its overlapping tab **is the connection point** for the next stripe. Controlled folds of roughly 6–15° per stripe accumulate into tangential continuity of curvature, which is what reads as an organic, flowing surface even though every individual part is flat, angular stock before assembly.
- **Digital chain:** Rhino 3D is the core modelling environment; the studio writes custom scripts (Python via RhinoCommon, plus in-house C++ tooling built up over the years) rather than relying only on off-the-shelf Grasshopper definitions, because the problem — describing one continuous curved surface as thousands of non-repeating flat parts with tolerant, buildable seams — is bespoke enough to need custom software at every project.
- **Assembly logic — "walking assembly":** the structure is built from the inside out, one stripe at a time, in a strict, pre-computed sequence, without scaffolding. A part forced into place out of sequence will not fit — sequence is a primary structural design constraint, not just a construction-schedule convenience. This is only possible because the geometry is self-stabilising as it grows: each new ring of stripes braces the ring before it, so the partially-built structure is never dependent on temporary shoring.
- Fabrication equipment is CNC or laser cutting for the flat stripe blanks, with curvature introduced by hand or simple jigs during assembly (not pre-formed/pressed) — keeping the fabrication step itself low-tech and repeatable even though the design computation behind it is highly bespoke.

### 1.2 Materials research

| Parameter | Detail |
|---|---|
| Base alloy | Aluminium 5052 (marine/structural grade sheet aluminium — good formability and corrosion resistance) |
| Skin gauge | 3mm is the standard "stripe" thickness across the recent large-scale work (Zephyr, The Orb, PILOTI); Vaulted Willow used 1/8" (~3mm) for its 721 stripes |
| Heavier gauges at load transfer points | Vaulted Willow steps up to 1/4" (6mm) at the feet and 1/2" (10mm) for its 24 base plates — the only places the design departs from constant-thickness skin, exactly where loads concentrate into the foundation |
| Surface treatment | Perforation is used on several projects (e.g. The Orb) both to filter daylight/create a lit-sculpture night effect and to shed self-weight without losing the stripe's structural depth |
| Fasteners | Aluminium rivets exclusively — no welding anywhere in the system. Rivet counts scale directly with part count: Vaulted Willow (721 stripes / 14,043 rivets), Zephyr (2,343 parts / 59,216 rivets), The Orb (6,441 parts / 217,847 rivets), PILOTI (6,665 parts / 180,900 rivets) |
| Foundation interface | Vaulted Willow anchors to 60 epoxy-concrete anchor points — the one place the aluminium system hands off to a conventional wet-trade foundation |

The material logic is the same one already identified in `MAIN_PRECEDENT_THIN_SHELL_METAL.md`: **structure and skin are not separated.** There is no secondary frame hiding behind the aluminium; the sheet itself, once curved and stripe-jointed, is the entire structural system. This is why gauge only ever changes at genuine load-transfer points (bases, feet) rather than varying freely — the material research question for this technique isn't "which material" so much as "how little of a single material, arranged how, is structurally sufficient."

### 1.3 Structure type

All four projects are the same underlying structural typology, expressed at different plan geometries:

- **Self-supporting monocoque shell** — double curvature substitutes for material thickness. There is no post-and-beam frame, no separate cladding layer; the "wall" and the "structure" are the same 3mm of aluminium.
- **Branching, columnar variant** (Zephyr, PILOTI): the shell logic is applied to tree-like forms — loop columns that branch upward into funnelled bridges/umbrella canopies, landing loads at a small number of discrete ground points ("PILOTI" is literally named for this — stilts/pillars lifting a canopy).
- **Enclosed, orb-like variant** (The Orb): the same stripe logic wraps into a punctured sphere rather than a canopy-on-columns, showing the system generalises past canopy/vault forms into fully enclosed volumes.
- **Vaulted, tunnel-like variant** (Vaulted Willow): a folly-scale barrel/vault form, the smallest and earliest of the four, useful as the clearest small-scale reference for a student-scale pavilion.

---

## 2. Why It Matters Here

This project's own biomorphic growth-algorithm lead (`07_Computational_Design/BIOMORPHIC_GROWTH_ALGORITHMS.md`) generates a network of small, non-repeating, variably-curved elements rather than a single global form — which is exactly the kind of output Fornes' stripe system was built to construct. The overlap is not just material (aluminium, already in this project's reclaimed-metal catalogue) but structural-logic: both approaches treat the built form as an aggregation of many small unique parts whose geometry alone provides stiffness, rather than a big shape cut down to size.

## 3. Comparative Table — All Four Fornes Projects

| | Vaulted Willow (2015) | Zephyr (2019) | The Orb (2025) | PILOTI (2025) |
|---|---|---|---|---|
| Location | Edmonton, Canada | Lubbock, TX | Mountain View, CA | Bellevue, WA |
| Typology | Vault/tunnel folly | Branching loop columns + canopy | Enclosed punctured sphere | Umbrella-cluster canopy on piloti |
| Material | Aluminium 5052, 3/6/10mm (stripe/feet/base) | 2 layers, 3mm aluminium | 3mm aluminium | 3mm aluminium |
| Stripes / parts | 721 | 2,343 | 6,441 | 6,665 |
| Rivets | 14,043 | 59,216 | 217,847 | 180,900 |
| Linear cut distance | not published | 7,400 m | 26,820 m | 23,378 m |
| Foundation | 60 epoxy-concrete anchors | — | — | — |
| Build crew/time | 4-person crew, 4 days | — | — | walking assembly, no scaffolding |

**Trend worth flagging for this project's own scale planning:** part count and rivet count scale roughly with surface area and enclosure complexity, not simply with height — Vaulted Willow (the smallest, a folly) needed under 15,000 rivets, while the two most recent, most topologically complex projects (The Orb, PILOTI) need well over 180,000. A first pavilion attempt at this project's scale should expect to sit much closer to the Vaulted Willow end of that range.

## 4. Lesson for This Project

1. **Fastener choice is now triple-confirmed across the whole precedent set** (this study, plus XISUI's bolt-only Nest Pavilion in `MAIN_PRECEDENT_THIN_SHELL_METAL.md`): mechanical fastening (rivet or bolt), never welding, is the consistent choice whenever the structural logic depends on computationally pre-verified part geometry — welding's heat distortion is incompatible with a system this dimensionally tight. This directly supports the rivet/bolt recommendation already standing in `08_Fabrication_Methods/FABRICATION_METHODS.md`.
2. **Gauge should follow load path, not be held constant everywhere.** Vaulted Willow's step from 3mm (skin) → 6mm (feet) → 10mm (base plate) is a usable rule of thumb for this project's own reclaimed-sheet material list (`05_Material_Research/RECLAIMED_METAL_SCRAP.md`, List C/D): reserve the thickest, best-condition reclaimed offcuts for foundation/load-transfer points, and let thinner, more available reclaimed sheet do the bulk skin area.
3. **"Walking assembly" (build from the inside out, no scaffolding, strict sequence)** is a fabrication-method idea this project hasn't yet captured in `08_Fabrication_Methods/FABRICATION_METHODS.md` — worth adding explicitly, since a growth-algorithm-generated structure would naturally produce the same kind of self-bracing build sequence (each new grown element stiffens the ones already placed).
4. **The stripe/panel segmentation approach should be the concrete deliverable of the growth algorithm**, not just a branching line network — this echoes and reinforces point 3 of the "Direct Implications" section already in `MAIN_PRECEDENT_THIN_SHELL_METAL.md`, now with four real projects' part/rivet counts as a sanity check for what "buildable at this scale" actually looks like in practice.
5. **Vaulted Willow is the most directly transferable single project for a student-scale pavilion** — smallest part count, only precedent here with a fully published build crew/time (4 people, 4 days), and the only one that documents its foundation detail (epoxy-concrete anchors) end-to-end.

## References

- Zephyr Pavilion: https://theverymany.com/texas-tech-lubbock-tx and https://www.archpaper.com/2019/09/marc-fornes-theverymany-uses-computational-design-for-texas-pavilion/
- The Orb: https://theverymany.com/google and https://www.thisiscolossal.com/2025/04/marc-fornes-theverymany-the-orb/
- Vaulted Willow: https://www.archdaily.com/596033/marc-fornes-theverymany-constructs-self-supported-vaulted-willow-with-ultra-thin-aluminum-shells, https://architizer.com/projects/vaulted-willow/, https://parametrichouse.com/vaulted-willow/, https://www.edmontonarts.ca/public-art/vaulted-willow
- PILOTI: https://theverymany.com/piloti, https://www.designboom.com/architecture/marc-fornes-theverymany-6665-aluminum-parts-umbrella-canopy-washington-09-04-2025/, https://parametric-architecture.com/piloti-pavilion-by-marc-fornes/
- Studio methodology ("Structural Stripes" / "Crawling Assemblies"): https://theverymany.com/studio, https://designwanted.com/theverymany-installations-spatial-experience/

## Images

Not yet collected — see `04_Pictures/` once diagrams/photos of these four projects are added for slide use.

---
Related: [[06_Precedent_Research/README|Precedent Research]] · [[06_Precedent_Research/MAIN_PRECEDENT_THIN_SHELL_METAL|Main Thin-Shell Metal Precedent Cluster]] · [[07_Computational_Design/BIOMORPHIC_GROWTH_ALGORITHMS|Biomorphic Growth Algorithms]] · [[09_Systemic_Design_Framework/MATERIAL_FABRICATION_PRECEDENT_SYSTEM_MAP|Systemic Map]]
