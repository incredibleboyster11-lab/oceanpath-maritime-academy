# OceanPath Nine-Book Integration — Batch 23
## Naval Architecture I ↔ Naval Architecture II initial cross-book source map

**Date:** 15 November 2026  
**Sources:** User-authored *Chief Mate Naval Architecture I – Chief Mate Phase I (latest)* (428 pp; updated 14 Nov 2026) and *Chief Mate Naval Architecture II* (299 pp; updated 27 Oct 2026).  
**Purpose:** First structural cross-book pass to identify duplicate, complementary and separate learning units. Source PDFs remain read-only. This is not technical approval or a complete question-level audit.

## 1. Source inventory reconciliation

| Book | Source-declared answers | Source-declared numericals | Past papers | Main architecture |
|---|---:|---:|---:|---|
| Naval Architecture I | 62 | 81 | 42 | 8 theory topics; 8 numerical groups |
| Naval Architecture II | 70 | 73 | 39 | 14 theory topics; 3 numerical groups |
| Combined | 132 | 154 | 81 paper records (not unique) | Phase I + Phase II |

Counts are transcribed from the book covers / indexes and are not deduplicated learning-unit counts.

### NA I theory topics
1. Simpson's rules & hydrostatics — 1 answer.
2. Dry-docking & grounding — 3.
3. Trim, density & list — 1.
4. GZ curves, intact & grain stability — 10.
5. Bulkheads, doors & Ro-Ro openings — 17.
6. Surveys & certification — 15.
7. Welding — 8.
8. Corrosion & painting — 7.

### NA I numerical groups
- Simpson's rules — waterplanes / sections: 13.
- Dry-docking: 5.
- Simpson's rules — bulkhead / deck areas and centroids: 16.
- Grounding: 13.
- Change of density — draft and trim: 8.
- Trim, list and loading for required drafts: 15.
- GZ curves from KN, list and IMO criteria: 9.
- Grain stability: 2.

### NA II theory topics
1. Basic stability ideas — 3.
2. Inclining experiment — 1.
3. Rolling of ships — 4.
4. IMO Intact Stability Code criteria — 4.
5. Heel while turning — 1.
6. Hull stresses — 2.
7. Midship section sketches — 11.
8. Ship plans and shipyard practice — 8.
9. Shipbuilding steel and testing — 6.
10. Aluminium in shipbuilding — 3.
11. Passenger ship subdivision and damage stability — 6.
12. Fire integrity (SOLAS II-2) — 8.
13. Load Line Convention — 9.
14. Tonnage Convention — 4.

### NA II numerical groups
- Bilging (box-shaped vessel): 20.
- Shear force & bending moment: 20.
- Thrust & centre of pressure: 7.

## 2. Cross-book concept map — first pass

| Integration ID | NA I source | NA II source | Relationship | Match confidence | Keep separate because |
|---|---|---|---|---|---|
| XNA-001 | Topic 5 B15 — midship section of a bulk carrier, p. 96 | Topic 7 G9 — bulk carrier midship, Topic 7 pp. 38 onward | Strong same-vessel sketch candidate | High | Verify exact framing / labels and source drawing before merging; NA I B15 is one answer within watertight-bulkhead topic, NA II G9 is a dedicated ship-type sketch card. |
| XNA-002 | Topic 5 B01–B14 — collision / WT bulkheads, WT doors, Ro-Ro doors / ramps, pp. 53–95 | Topic 11 K1–K6 — passenger ship subdivision / damage stability; Topic 12 L1–L9 — fire integrity | Complementary structural integrity | High | Watertight subdivision, damage stability and fire division are different regulatory / physical functions. Link, do not merge. |
| XNA-003 | Topic 4 G1–G10 — GZ curves, intact and grain stability, pp. 25–52 | Topics 1–5 — basic stability, inclining, rolling, IS Code criteria, heel while turning, pp. 8–33 | Broad stability family overlap | High | NA I focuses on GZ / intact / grain and exam sketches; NA II adds inclining, rolling, weather criterion and turning heel. Split by learning objective and cross-link. |
| XNA-004 | Topic 3 T1 — trim, density and list, p. 21; numerical groups change of density and loading / trim | NA II Topic 6 — hull stresses; numerical SF/BM | Related hydrostatic / structural loading | Low–medium | Trim and loading condition can affect longitudinal strength, but no direct duplicate answer established. |
| XNA-005 | Topic 2 dry-docking / grounding, pp. 12–20; numerical dry-docking / grounding | NA II Topic 8 — ship plans / shipyard practice | Complementary shipyard context | Medium | Dry-docking calculations and shipyard planning / drawings are not the same answer. |
| XNA-006 | Topic 5 B06/B07/B14 — Ro-Ro bow door, stern ramp, monitoring; Topic 5 B15 bulk carrier sketch | NA II Topic 7 G1 Ro-Ro, G9 bulk carrier midship; Topic 12 fire integrity L8 special category spaces | Ship-type integration | High | Sketch, access closure, stability and fire integrity remain separate but connected units. |
| XNA-007 | Topic 6 surveys & certification, including ESP / surveys | NA II Topic 8 shipyard practice and Topic 9 steel / testing | Complementary lifecycle / construction QA | Medium | Survey regime, material testing and yard processes have distinct purposes and source codes. |
| XNA-008 | Topic 5 WT bulkhead / door answers | NA II Topic 12 L2 A/B/C divisions and L4 standard fire test | Same physical boundary, different integrity performance | High | Watertight integrity is not fire integrity; one structure may have both requirements, but tests and criteria differ. |
| XNA-009 | Topic 4 intact / grain stability and grain numerical group | NA II Topics 1, 3, 4, 5 and 9 stability / rolling / weather / turning | Complementary stability system | Medium–high | Grain stability is cargo-specific; rolling and weather criteria are separate dynamic / regulatory topics. |
| XNA-010 | Topic 5 B02/B08/B09/B12 and B13 — WT bulkhead location, compartment testing, tightness, openings and door testing | NA II Topic 11 K1–K6 — passenger subdivision and damage stability | Complementary subdivision framework | High | NA I has construction / closure details; NA II explains floodable / permissible length and passenger damage criteria. |
| XNA-011 | NA I has no dedicated bilging numerical bank identified in its index | NA II numerical group 1 — 20 box-shaped-vessel bilging problems | NA II-specific numerical family | High | Keep as a separate Phase II numerical bank; link conceptually to damage stability / compartment flooding. |
| XNA-012 | NA I hydrostatics / Simpson's rules numerical groups | NA II numerical group 2 — 20 SF/BM problems | Different numerical families | High | Hydrostatic integration and longitudinal strength calculations should not be merged. |
| XNA-013 | NA I hydrostatics / GZ / trim calculations | NA II numerical group 3 — 7 thrust / centre-of-pressure problems | Related fluid mechanics / ship design | Medium | Similar pressure / hydrostatic foundations, but distinct problem-solving methods and exam objectives. |

## 3. Important source distinctions and risk flags

1. **NA I bulk carrier midship vs NA II bulk carrier midship:** likely a duplicate vessel-type sketch objective. Do not merge drawings until both answer bodies / diagrams are compared at image level.
2. **Watertight vs fire divisions:** NA I B-series concerns watertight integrity and closure; NA II L-series concerns SOLAS II-2 fire divisions and standard fire tests. A shared “bulkhead” word does not make them duplicates.
3. **Passenger subdivision:** NA II K1–K6 uses floodable / permissible length, factor of subdivision, permeability, margin line, subdivision load lines and passenger damage stability. Link to NA I WT bulkhead / door construction but preserve as its own regulatory theory set.
4. **2026 SOLAS changes:** the IMO January 2026 supplement lists amendments effective 1 Jan 2026 affecting SOLAS II-1, II-2 and V, among others. NA I / NA II answers citing these chapters require current-edition / applicability checks before public release. <https://wwwcdn.imo.org/localresources/en/publications/Documents/Supplements/English/QH110E_supplement_January2026.pdf>
5. **New inclinometer carriage:** IMO reports SOLAS V/19 amendments requiring electronic inclinometers or equivalent on containerships and bulk carriers of 3,000 GT and above constructed on/after 1 Jan 2026, with stated scope exceptions. This may be a future update hook for bulk-carrier material; do not retrofit into historical exam answers without a separate dated update. <https://www.imo.org/en/mediacentre/pressbriefings/pages/raft-of-shipping-rules-in-force-from-1-january-2026.aspx>
6. **Load Line / Tonnage:** NA II topics 13 and 14 are not directly duplicated by the NA I index's core theory topic list, though NA I survey/certificate answers may reference certificates. More detailed answer-body search is required before declaring them unique.

## 4. Integration model proposed

Create one canonical concept record per learning objective with:
- canonical concept ID;
- phase / exam paper;
- primary source book, answer code and printed page;
- secondary source links;
- relationship type: duplicate / near-duplicate / complementary / prerequisite / distinct;
- source comparison status (index-only / answer text inspected / diagram inspected / numerical independently checked);
- regulatory version and effective date where relevant;
- rights / privacy / reviewer / publication fields already defined in the OceanPath schema.

For the bulk-carrier midship sketch, retain one canonical concept with two source variants until the diagrams are visually compared. For watertight and fire integrity, create linked sibling concepts rather than one combined answer.

## 5. Next batch

- Inspect NA I B15 and NA II G9 answer bodies / diagrams for exact sketch equivalence.
- Compare NA I B01–B14 with NA II K1–K6 and L1–L9 at answer-code level.
- Build a full NA I numerical taxonomy against NA II bilging / SF-BM / thrust banks; avoid assuming similar formulas mean same numerical type.
- Continue NA II Topics 8–14 against NA I surveys, welding, corrosion and certification.
- Only then publish a stable nine-book crosswalk.

## 6. Limitations

- This is a first-pass map based on indexes, selected answer bodies and paper-pattern pages.
- “No direct duplicate” is not claimed for uninspected answer bodies.
- Source-declared answer / numerical counts are not independently deduplicated.
- No source PDF or study repository was modified.
- Technical correctness, regulatory currency and publication clearance are separate gates.
