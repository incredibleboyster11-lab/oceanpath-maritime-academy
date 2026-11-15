# OceanPath Nine-Book Integration — Batch 29
## Naval Architecture I / II numerical-bank taxonomy and count reconciliation

**Date:** 15 November 2026  
**Sources:** NA I numerical index, printed p. 3 and numerical pages pp. 180–368; NA II numerical index, printed p. 3 and numerical pages pp. 110–201.  
**Method:** Source index reconciliation and question-family comparison. This is not an independent recalculation of every worked solution.

## 1. Source-declared numerical taxonomy

### NA I — 81 questions with worked solutions

| Numerical family | Source-declared count | Printed start page |
|---|---:|---:|
| Simpson's rules — waterplanes and sections (displacement, KB, LCB, COF) | 13 | 180 |
| Dry-docking | 5 | 213 |
| Simpson's rules — bulkhead and deck areas, centroids | 16 | 226 |
| Grounding | 13 | 260 |
| Change of density — draft and trim | 8 | 289 |
| Trim, list and loading for required drafts | 15 | 306 |
| GZ curves from KN, list and IMO criteria | 9 | 337 |
| Grain stability | 2 | 361 |
| **Total** | **81** | |

**Important index anomaly:** The NA I source index says “Dry-docking” has 5 questions, but the detailed numerical type page calls Dry-docking “16 different questions · came 24 times” and lists D01, D06–D10, D15 etc. The 5 appears to be a count for one separate index item or a source-layout mismatch; the printed index ordering also appears to place the 5-question dry-docking label before the 16-question bulkhead/deck family. Do not silently decide which count is correct. The eight displayed family counts sum to 81 only if Dry-docking = 5 and bulkhead/deck = 16. Record a source reconciliation query for a full card-ID audit.

### NA II — declared 73 questions with worked solutions

| Numerical family | Source-declared count | Printed start page |
|---|---:|---:|
| Bilging (box-shaped vessel) | 20 | 110 |
| Shear force & bending moment | 20 | 155 |
| Thrust & centre of pressure | 7 | 195 |
| **Displayed family total** | **47** | |
| **Cover/index total** | **73** | |

**Unresolved count gap: 26 questions.** The visible numerical index lists 20 + 20 + 7 = 47, while the cover/index declares 73. This is a 26-question discrepancy. Do not fabricate missing numerical groups or report 73 as reconciled. The likely next task is to inspect the full numerical contents / page ranges and exact IDs for hidden or unindexed questions, or verify whether the cover total is stale.

## 2. Numerical integration map — different methods, linked foundations

| ID | NA I family | NA II family | Relationship | Boundary |
|---|---|---|---|---|
| XNA-064 | Simpson's waterplane / sections | Bilging | Shared hydrostatic / geometry foundations | Simpson integration and bilging stability are different calculations. |
| XNA-065 | Simpson's bulkhead / deck area and centroid | Thrust / centre of pressure | Strong mathematical / geometry bridge | Geometric centroid is not the centre of pressure; pressure varies with depth and shifts the resultant. |
| XNA-066 | Simpson's bulkhead areas / centroids | Thrust / centre of pressure | Shared ordinates / Simpson's-rule techniques | The pressure distribution requires first and second moments; do not substitute plain area centroid. |
| XNA-067 | Grounding | Bilging | Related loss-of-buoyancy / damage-stability context | Grounding is seabed reaction / tide / refloating; bilging is compartment flooding. |
| XNA-068 | Dry-docking | SF/BM | Structural loading context only | Dock-block reactions and critical instant are not longitudinal shear-force / bending-moment calculations. |
| XNA-069 | Trim / list / loading | Bilging | Related equilibrium and stability context | Intact loading / trim is not a damaged-compartment calculation. |
| XNA-070 | GZ / KN / IMO criteria | Bilging | Stability bridge | Intact GZ assessment and damaged stability / bilging are separate. |
| XNA-071 | Grain stability | Bilging | Cargo / flooding risk context | Grain heeling moment and bilging are not the same stability criterion. |
| XNA-072 | No direct NA I SF/BM numerical family in index | SF/BM | NA II-specific numerical family | Keep as separate longitudinal strength calculation bank. |
| XNA-073 | No direct NA I thrust / COP bank identified | Thrust / COP | NA II-specific numerical family | Keep as separate hydrostatic pressure-resultant calculation bank. |

## 3. Numerical learning architecture

1. **Integration / geometric methods:** Simpson's rules for waterplanes, sections, bulkheads and decks.
2. **Hydrostatic equilibrium:** displacement, KB, LCB, COF, draft changes, density, trim and list.
3. **Grounding and docking:** seabed reaction, refloating, dry-dock critical instant, virtual GM and block reaction.
4. **Intact stability:** KN/GZ curves, list, IMO criteria and grain stability.
5. **Flooding / damage stability:** box-shaped-vessel bilging and compartment flooding.
6. **Longitudinal strength:** shear force and bending moment.
7. **Hydrostatic pressure:** thrust and centre of pressure.

The pathway is a learning architecture inferred from the source question families; it is not a replacement for the books' own ordering.

## 4. High-priority source QA actions

- NA I: audit all 81 numerical IDs and verify the dry-docking 5 vs 16 mismatch in the index / detailed topic page.
- NA II: audit every numerical ID from p. 110 onward and locate the 26-question gap between declared 73 and visible groups 47.
- Verify each solution independently: formula selection, units, signs, rounding, hydrostatic assumptions, diagrams and final answer.
- Mark repeated exam questions separately from unique worked numerical templates. “Came 24 times” is not the same as “24 different questions.”
- Preserve source IDs; do not renumber or invent a missing group until the full source pages are inspected.

## 5. Limitations

This is a numerical-family map and index reconciliation, not a complete question-by-question audit or recalculation. Counts are source-declared except the arithmetic totals shown. No source PDF or numerical solution was modified.
