# Week 4 — Computational Strategy: Form-Finding, Tectonic Joint, Aggregation

**Responds to:** `01_Design_Direction.md`
**Status:** Direction/technique selection — not yet implemented in Grasshopper. Tutor has confirmed computational methods are optional at this stage; this document is preparatory so we're ready to move fast once modelling starts.

---

## 1. Form-Finding Technique

Two natural-mimic methods, used in sequence rather than as alternatives:

### Step A — Physics-based shell relaxation (Kangaroo2)
Catenary/minimal-surface relaxation. The shell shape emerges from force distribution (soap-film / hanging-chain logic), the same principle behind naturally efficient shell forms. Necessary because thin reclaimed sheet metal is strong in pure compression/tension but weak in bending — the form has to be found, not sculpted, or it won't behave structurally.

### Step B — Field-driven cellular subdivision (Voronoi/Delaunay on the relaxed surface)
Once the shell surface is relaxed, generate panel cells from a point field on that surface. This mimics biological tissue patterning (turtle shell, dragonfly wing) and — critically — the field driving point density/cell size should be a real value (sun exposure, distance from ground, local structural stress from Step A), not arbitrary, per Oxman's "material follows performance" principle already noted in `07_Computational_Design/BIOMORPHIC_GROWTH_ALGORITHMS.md`.

*(Differential growth, the doc's other primary candidate, remains an option for the shell's edge/silhouette if an organic perimeter is wanted — treated as secondary here since panel subdivision is the more pressing problem for reclaimed sheet material.)*

## 2. Tectonic Joint Type — Answering "How Do Irregular Geometries Connect"

Every reclaimed sheet is a different size, shape, and condition — this constrains which joint types are viable.

| Joint type | Tolerance to size/shape irregularity | Notes |
|---|---|---|
| **Overlapping / shingle (lapped)** | High — overlap absorbs variation | Recommended primary joint. Same logic as fish scales, pinecone bracts, and our own Kuma Folk Art Museum precedent (variable tile size, still reads as ordered). Weather-tolerant, fits pavilion enclosure function. |
| Twist connection | Low–Medium | Needs fairly consistent geometry to leverage against neighbours. Use only as an accent condition at specific nodes/transitions, not the whole system. |
| Multi-directional (reciprocal/nexorade-style) | Low | Interesting for self-supporting spans without extra framing, but reciprocal frames generally need consistent member geometry — poor match for irregular reclaimed stock as a primary system. |

**Recommendation:** overlapping/shingle as the primary connection logic across the shell, with twist/multi-directional reserved for specific structural nodes if the hybrid-shell option needs a stiffer local frame.

## 3. Aggregation on the Field — Matching to Real Stock

The point-cloud/field-emergence approach (already the instinct going in) is correct, with one addition specific to reclaimed material:

1. Field (sun exposure / height / stress) → point density → Voronoi/Delaunay cells → **target panel size per cell**.
2. **Best-fit matching pass**: match each target cell size against the actual dimensions already logged in Week 3's 46-entry material catalogue (`01_Weekly_Tasks/Week_03_ConceptPinUp/02_Material_Catalogue.md`), nearest-neighbour by size.

Without step 2, the algorithm designs an idealised shell that doesn't correspond to material we can actually source — undermining the circular-material premise of the whole project. This matching step is the direct computational answer to "how does this algorithm allow irregular geometries to connect": cells aren't cut to fit a predetermined pattern, the *available* irregular stock is matched to the nearest generated cell.

## 4. Tying the Gradient Requirement Into the System

One field drives two outputs simultaneously:
- **Overlap amount** (denser/more overlap in one zone → lighter/more perforated in another)
- **Finish selection** (rust-left-weathered vs. treated/cleaned, assigned per the same gradient)

This directly answers the tutor's four Group 3 directives (rust vs. treated; organise colour/weathering; develop a clear gradient) as one coherent generative rule rather than four separate manual decisions.

## 5. Fabric Role — Still Open

Two candidate roles, not yet decided (see open question in `01_Design_Direction.md`):
- **Structural**: tensioned between sheet-metal panel edges, bracing the shell in shear — would sit in the aggregation logic as a second layer between adjacent Voronoi cells.
- **Environmental**: filling gaps/perforations left by the overlap gradient — shading, rain-screening, or acoustic softening where panel density is low.

Both are compatible with the field-driven system above; likely resolved once pavilion function (gallery vs. open/threshold) is decided.

## 6. Suggested Tooling

- **Kangaroo2** — shell relaxation (Step A)
- **Grasshopper native / Delaunay-Voronoi plugins** — field-driven cell generation (Step B)
- **Human / Human UI or a custom nearest-neighbour script** — best-fit matching against the material catalogue (Section 3)
- **Weaverbird** — mesh subdivision/cleanup if needed between steps

## 7. Next Action

Prototype a rough Grasshopper definition outline (component sequence) for: relax → field → Voronoi → best-fit match, once pavilion function/spatial intent is confirmed per `01_Design_Direction.md`.
