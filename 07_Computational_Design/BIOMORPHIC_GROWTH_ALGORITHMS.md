# Biomorphic Computational Design — Growth Algorithms & Natural Mimicry

**Lead design driver for the pavilion.** This document sets out the computational approach first, since the brief for this direction treats growth-algorithm logic as generative — material and fabrication choices below are meant to respond to what this approach produces, not the other way around.

---

## 1. What "Growth Algorithm" Means Here

A growth algorithm doesn't draw a final form directly — it simulates a simple local behaviour repeated many times over many small elements ("agents"), and the overall form emerges from that repetition. This is different from sculpting a shape by hand in Rhino; the designer sets the *rules*, not the *outcome*, and then steers the outcome by tuning the rules and constraints.

### Differential Growth (primary candidate)

The core technique: a set of points/agents distributed along a curve or mesh, each following three simple rules simultaneously —
- **Repulsion** — agents push away from neighbours that get too close, preventing overlap/crowding
- **Cohesion** — agents stay connected to or within range of their neighbours, keeping the growing form continuous
- **Insertion** — when two connected agents stretch too far apart, a new agent is inserted between them, allowing the form to lengthen and complexify over time

<cite index="9-1">This mimics natural growth processes where different parts of a structure expand at different rates, producing complex emergent forms from repeated simple local rules.</cite> This is the same underlying logic that produces coral growth patterns, intestinal folding, and leaf-margin wrinkling in nature — which is exactly the "natural mimicry" behaviour named in the brief.

**Tooling:** Grasshopper + Kangaroo2 physics plugin is the standard implementation route (matches the software your studio brief already references). Differential growth can be run directly on a mesh surface (surface-constrained growth, useful for cladding/skin patterns) or along a curve network (useful for branching/frame-like structural patterns).

### Related growth-family algorithms worth knowing (for comparison, not necessarily to use)

- **Cellular Automata / Diffusion-Limited Aggregation** — discrete, grid-based growth; <cite index="2-1">tends to be harder to control geometrically and to translate into buildable architecture compared to free-form growth methods like differential growth.</cite> Noted here mainly to explain *why* differential growth is the better starting point for a buildable pavilion rather than a purely generative art piece.
- **L-Systems (Lindenmayer Systems)** — rule-based string-rewriting used to generate branching plant-like structures (trees, root systems, vascular patterns). Useful if the pavilion direction leans toward branching/columnar structure rather than a continuous skin.
- **Agent-based growth on a mesh** — differential growth constrained to grow *across* an existing surface rather than freely in space; useful for a skin/cladding pattern applied over a simpler primary structure (relevant if paired with the "Kerfed Skin"-style envelope concepts from Week 3).

## 2. Precedent: Growth-Logic Already Documented in This Repo

`06_Precedent_Research/BIOMORPHIC_COMPUTATIONAL_REFERENCES.md` already covers the two most directly relevant precedent groups in depth — worth re-reading through this week's growth-algorithm lens specifically:

- **Neri Oxman / Mediated Matter Group** — "growth over assembly" as a design philosophy; Silk Pavilion (silkworm co-fabrication) and Aguahoja (generative bio-composite toolpaths) are the clearest "natural mimicry drives fabrication" precedents in the whole reference set.
- **ICD/ITKE Research Pavilions (Stuttgart)** — <cite index="45-1">their design methodology is explicitly biomimetic, translating structural principles observed in nature (arthropod cuticle, segmented shell structures) into digitally fabricated architecture</cite>, and one pavilion in the series used timber finger-joints modelled directly on a biological joining principle, assembled from roughly <cite index="45-1">100,000 individual finger joints</cite> — a striking demonstration that a growth/biomimetic *logic* can still resolve into an entirely conventional, buildable material (plywood) and joint type.

## 3. Natural Mimicry as "Behaviour," Not Just Form

The brief's phrase "natural mimicry" is worth being precise about, because it's easy to slip into copying a shape (a leaf, a shell) rather than a *behaviour*. <cite index="46-1">Biomimicry in architecture and engineering broadly falls into two approaches: simulating a biological process computationally, or directly co-opting a living/biological material or organism (bio-utilization)</cite> — for example <cite index="46-1">bioMASON grows brick using bacteria that alters aggregate pH so calcium carbonate binds the material together, a process modelled on how microorganisms build coral reefs</cite>.

For this pavilion, "mimicry" should mean: **the growth algorithm's rule-set is chosen because it reproduces a real structural/material behaviour** (how load-bearing natural structures grow toward strength, e.g. bone remodelling toward stress lines, coral toward available surface, root systems toward resource gradients) — not because the output "looks organic." This distinction matters directly for the assessment framework's "material as active generator, not decoration" criterion.

## 4. How This Should Drive Material + Fabrication Choices (see following documents)

The growth algorithm's output is inherently a network of **variable, non-standard members and nodes** — exactly the same problem reclaimed material already presents (no two pieces the same). This is a genuine strategic alignment worth stating explicitly in the presentation: a growth-generated structural network *needs* a material and connection strategy that tolerates dimensional variation anyway, so working with reclaimed metal scrap (naturally irregular offcuts) is arguably a *better* match for a growth-algorithm structure than it would be for a rigid modular grid design.

This is the throughline connecting all three parts of this week's research:
1. **Computational lead (this doc):** growth algorithm generates a variable structural/skin network
2. **Materials (`05_Material_Research/`):** reclaimed metal scrap and GFRC offcuts are inherently variable — matched to the network's own variability rather than fighting it
3. **Fabrication (`08_Fabrication_Methods/`):** connection methods (dry joint, rivet, weld, cold casting) chosen specifically for their ability to join non-standard, variable-geometry members — see fabrication doc for how each method performs against that requirement

## 5. Open Questions to Bring to Studio

- Should growth simulation run in 3D directly at pavilion scale, or generate a 2D/surface pattern first that's then extruded/thickened into structure? (Affects whether Kangaroo2 differential growth or a mesh-relaxation approach is more appropriate.)
- What's the actual structural constraint set the growth algorithm should respond to — self-weight only, or wind/typhoon loading data relevant to eventual HK exhibition? Needs input from Dr Nic Bao / Harlan Guo on how rigorous the structural simulation needs to be at this stage.
- Does "grow algorithm lead" mean the growth output directly IS the final geometry, or is it a diagram/study that a more resolved design is then developed from? Worth clarifying before committing significant computational time.
