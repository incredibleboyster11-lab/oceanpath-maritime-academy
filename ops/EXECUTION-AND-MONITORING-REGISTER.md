# EXECUTION AND MONITORING REGISTER



## 15 November 2026 — author permission and uploaded corpus milestone

- The author explicitly confirmed that all nine uploaded Chief Mate PDFs are their own work/data and authorised OceanPath to use them. Permission for the author's original authored material is recorded in `ops/CHIEF-MATE-SOURCE-RIGHTS-REGISTER.md`.
- Opened all nine PDFs: 3,265 pages total. Source-declared coverage includes written answers, worked numericals, past-paper indexes, three oral-function question banks and surveyor-profile sections. Detailed page counts and declared metrics are recorded in `docs/CHIEF-MATE-CONTENT-INVENTORY-AUDIT.md`.
- OP-03 advances from artifact-body access blocked to uploaded-book corpus received and structurally reviewable. Component-level third-party rights and privacy checks remain open.
- OP-04 can proceed with internal source-to-platform mapping and migration manifest design. No public content migration until third-party rights, privacy and qualified review gates pass.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Author permission confirmed for original authored work; 9 PDFs / 3,265 pages received and opened; detailed audit in progress | Full topic/index extraction, count reconciliation, component-level third-party rights and privacy review | No public release of uncleared third-party or personal material |
| OP-04 | Internal migration design authorised to proceed | Source-to-OceanPath manifest with page refs, stable IDs, content types and review states | Separate derivatives only; originals remain read-only |


## 15 November 2026 — nine-book topic-index extraction

- Read index/topic pages from all nine uploaded PDFs and created `docs/CHIEF-MATE-TOPIC-LEVEL-SOURCE-MAP.md` with source page references, written/oral subject structure, answer/numerical groups and candidate cross-book integration links.
- The map deliberately distinguishes topic-name overlap from verified duplicate questions. No question-level deduplication is claimed yet.
- Confirmed the oral books' Part A / Part B structure and surveyor-profile ranges. Surveyor/oral-report-derived material remains excluded from public migration pending privacy review.
- Next: row-level question inventory and count reconciliation, starting with written books; preserve page-level provenance and source terminology.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Nine-book topic-level index extraction completed; question-level inventory pending | `docs/CHIEF-MATE-TOPIC-LEVEL-SOURCE-MAP.md` | No claims of unique question counts until reconciled |
| OP-04 | Topic-level migration architecture documented | Row-level source-to-unit map, then controlled pilot derivative | Originals remain read-only; review gates before publication |


## 15 November 2026 — NAV question-level inventory extraction, batches 1–2

- Read the uploaded NAV PDF directly and extracted answer-card IDs and titles from Topics 1–6. Source pages and source-declared frequency metadata are preserved in two internal inventory files:
  - `data/nav-content-question-inventory-batch-01.md` — 32 rows covering Magnetic Compass, Gyro Compass, Autopilot/Steering/Turns (including T1 and T2).
  - `data/nav-content-question-inventory-batch-02.md` — 31 additional rows covering Echo Sounder/Logs/SDME, Performance Standards/Carriage and GPS/GNSS/ECDIS; confirms T2's page location.
- Cumulative extracted NAV theory-card IDs: 63. This is a partial extraction, not the full book total. The book declares 74 theory answers; later topics remain to be extracted and reconciled. The 51 declared numericals remain a separate inventory task.
- Source-declared paper frequencies have not been independently checked against original past-paper PDFs. Do not present them as verified exam statistics.
- No answer content was migrated to public learning pages. Source PDF remains read-only.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NAV source inventory reconciled: 74 theory cards + 51 numerical/plot cards | Three theory inventory batches plus `data/nav-numerical-bank-inventory-and-reconciliation.md`; next: question-level cross-book overlap analysis and source answer QA | Source frequencies remain unverified; technical/regulatory/rights/privacy review before public release |
| OP-04 | Row-level NAV inventory complete for theory and numerical groups | Cross-book question-level matching; then select a controlled pilot derivative | Original PDFs read-only; derivatives remain internal drafts |


## 15 November 2026 — NAV numerical-bank reconciliation

- Read the numerical/plot section directly (PDF pages 91–206) and reconciled all source-declared numerical groups:
  - Radar plotting Q1: 19 cards, RP01–RP19 (pages 91–162).
  - Gyro compass Q2: 24 cards, GN01–GN24 (pages 163–191).
  - Radius of turn / ROTI Q4: 8 cards, TN01 and TN03–TN09 (pages 192–206).
- Total: 51 numerical/plot cards, matching the book's declared 51. The source has no TN02 card; preserve the source's numbering gap and do not invent or renumber it.
- Created `data/nav-numerical-bank-inventory-and-reconciliation.md`. Old-paper appearances are cross-references to grouped cards, not additional unique numerical cards.
- Reconciled combined NAV inventory: 74 theory answer cards + 51 numerical/plot cards. The separate old-paper section declares 38 papers; this is a distinct index, not part of the learning-card total.
- This is count reconciliation only; individual solution accuracy and regulatory references remain to be reviewed. Source frequencies have not been independently audited against original paper PDFs. No public content migration; source remains read-only.


## 15 November 2026 — NAV theory inventory reconciliation

- Completed direct extraction of the NAV PDF's Topics 7–8: AIS/LRIT (7 cards) and VDR/BNWAS (4 cards).
- Reconciled all eight topic index counts to 74 theory answer-card IDs: 18 + 6 + 8 + 13 + 8 + 10 + 7 + 4 = 74, matching the book's declared 74 answers.
- Added `data/nav-content-question-inventory-batch-03.md`; the three batches together provide titles, source page references and source-declared frequency labels for all 74 theory cards.
- The separate numerical section begins at PDF page 91. The book declares 51 solved numerical cards; those IDs and page spans remain to be extracted and reconciled. Radar plotting Q1 begins with a guide and 19 different questions, so its internal card count needs careful reconciliation with the book-wide 51.
- No answer text was migrated to public learning pages; source remains read-only.


## 15 November 2026 — BWK question-level inventory started

- Opened the BWK PDF directly. The index declares 103 answer cards across 12 topics and 35 old papers.
- Extracted Topic 1 (Search and rescue, man overboard): R1–R15, 15 cards, with source page references in `data/bwk-content-question-inventory-batch-01.md`.
- Topic 1's 15-card count reconciles to its index. The remaining 11 topics contain 88 further declared answer cards.
- Source-declared paper-pattern statistics remain unverified against the underlying paper set. The PDF is read-only; no answer content migrated publicly.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NAV fully inventoried: 74 theory + 51 numerical cards; BWK inventory started with 15/103 cards | `data/nav-content-question-inventory-batch-01.md` through `batch-03.md`; `data/nav-numerical-bank-inventory-and-reconciliation.md`; `data/bwk-content-question-inventory-batch-01.md` | Continue BWK topics; no public release without review |
| OP-04 | NAV row-level inventory complete; BWK row-level inventory in progress | Complete BWK 103-card inventory, then question-level cross-book overlap analysis | Original PDFs read-only; derivatives remain internal drafts |


## 15 November 2026 — BWK answer-card inventory reconciled

- Extracted the BWK topic index and IDs for Topics 2–12, adding 88 cards to the 15-card SAR inventory from batch 1.
- Combined BWK total: 103 answer-card IDs across 12 topics, matching the source-declared 103 answers.
- Evidence:
  - `data/bwk-content-question-inventory-batch-01.md` — Topic 1, R1–R15.
  - `data/bwk-content-question-inventory-batch-02.md` — Topics 2–12, 88 cards.
- Topic-level counts reconcile: 15 + 4 + 4 + 15 + 9 + 7 + 20 + 3 + 13 + 6 + 5 + 2 = 103.
- This is index-level extraction of IDs and headings; individual answer bodies have not all been audited. Exact per-card page spans and technical accuracy review remain open.
- Next: inspect BWK answer bodies and begin actual NAV↔BWK question wording overlap analysis. Shared topic labels alone are not sufficient to call duplicates. Original PDFs remain read-only; no public content migration.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NAV fully inventoried (74 theory + 51 numerical); BWK index inventory reconciled (103/103) | NAV inventory files; `data/bwk-content-question-inventory-batch-01.md`; `data/bwk-content-question-inventory-batch-02.md` | BWK answer-body QA and technical/regulatory/privacy review before release |
| OP-04 | NAV row-level map complete; BWK topic-index map complete | Answer-body QA and cross-book question-level overlap report | Original sources remain read-only; derivatives internal until cleared |


## 15 November 2026 — BWK answer-body QA / NAV cross-match batch 01
- Inspected BWK Topic 1 answer pages 10–26 and verified index-to-answer presence for all 15 R-cards (R1–R15). This is structural presence QA, not technical/regulatory validation.
- Compared BWK SAR/MOB and sampled BWK ship-handling material with NAV autopilot/controlled-radius turn material. No exact duplicate identified in the inspected scope.
- Classified NAV controlled-radius turns (ROTI, WOP, WOL, VRM) versus BWK turning-circle / ship-handling cards as complementary or distinct learning units, not duplicates.
- Full BWK answer-body QA remains incomplete; Topic 7 was sampled, and Topics 2–6 and 8–12 remain for later batches.
- Detailed findings and limitations: [BWK-NAV batch 01](../data/bwk-nav-answer-body-qa-crossmatch-batch-01.md).


## 15 November 2026 — BWK Topic 7 and VTS/SAR cross-match batch 02
- Inspected BWK Topic 7 answer pages 71–93. H1–H5 and H8–H20 were visible; H6–H7 exact answer spans remain to be confirmed. This is presence/mapping QA, not technical verification.
- Compared BWK ship-handling cards with NAV autopilot, wheel-over, ROTI and controlled-radius turn material: no exact duplicate established; units are complementary and should remain separate.
- Compared BWK VTS / ship reporting / routeing cards (V1–V4) and SAR cards with NAV AIS/LRIT/ECDIS. These are complementary shipboard-equipment versus shore-service / SAR-response perspectives, not duplicates.
- Details and source-page limitations: [BWK-NAV batch 02](../data/bwk-nav-answer-body-qa-crossmatch-batch-02.md).


## 15 November 2026 — BWK Topics 3–6 answer-body mapping batch 03
- Inspected BWK Topic 3 Pilotage P1–P4 (printed pp.33–36); 4/4 topic cards located in answer section.
- Inspected BWK Topic 4 emergency-plan material (E1/E2 and partial E3/E8/abandon-ship extracts); full E1–E15 mapping remains incomplete.
- Inspected BWK Topic 5 T7–T9 (printed pp.59–62); earlier cards T1–T6 remain to be mapped.
- Inspected BWK Topic 6 A1–A4 and start of A5 (printed pp.63–67); A5 completion and A6–A7 remain.
- No exact NAV duplicates established in these inspected topics. Cross-links remain complementary or separate; report includes limitations: [BWK-NAV batch 03](../data/bwk-nav-answer-body-qa-crossmatch-batch-03.md).


## 15 November 2026 — BWK Topics 8–12 source pass, batch 04
- Topic 8 Mooring: all 3 answer cards M1–M3 located in printed pp.94–97.
- Topic 9 index declares 13 cards; W1–W5 and W10–W12 were inspected/partly mapped; W6–W9 and W13 remain to be mapped. Do not mark topic complete.
- Topic 10 STS/dry-dock: partial page review pp.111–114; S3 and side-shell repair specification content visible; complete card/page mapping pending.
- Topic 11 index declares I1–I5; I1–I4 visible/partly inspected pp.115–117; I5 remains unmapped. Source old-paper index flags a Polar navigation-system requirements question as not yet covered by an answer in the book.
- Topic 12: Z2 and partial Z1 material visible on p.121; full index and card mapping pending.
- No exact NAV duplicates established. Full limits and next actions: [BWK Topics 8–12 batch 04](../data/bwk-answer-body-qa-topics-08-to-12-batch-04.md).


## 15 November 2026 — BWK answer-body completion pass 05
- Completed Topic 4 E1–E15 mapping; explicit source gaps include chemical-tanker cargo-space fire contingency plan.
- Completed Topic 5 T1–T9 mapping, with exact T3/T4 page boundary flagged for final confirmation.
- Completed Topic 6 A1–A7 mapping.
- Completed Topic 8 M1–M3, Topic 9 W1–W13, Topic 10 S1–S6, Topic 11 I1–I5, and Topic 12 Z1–Z2 answer-body mapping.
- Topic 9 source gap: Safety Committee role/duties/meeting agenda. Topic 11 source gap: Polar Code navigation-system requirements/exemptions for existing ships.
- No exact BWK↔NAV duplicate established in inspected scope; F1/F3 comparison remains pending. Mapping is presence QA only, not technical correctness or regulatory approval.
- Detailed evidence and boundaries: [BWK completion batch 05](../data/bwk-answer-body-qa-completion-batch-05.md).


## 15 November 2026 — BWK↔F1/F3 cross-book candidate matrix, batch 01
- Reopened F1/F3 source PDFs and mapped exact overlapping question objectives for running/standing moor, girting, collision response, grounding, beaching, anchor dragging, wheelhouse poster, emergency towing and blackout-in-TSS.
- Recorded complementary matches for pilotage/pilot ladder, anchor maintenance, ship–tug interaction, dry dock, emergency drills, abandon ship, CO2 and enclosed-space topics.
- Preserved source differences in beaching tide guidance, stranding definitions and ETA/ETP regulatory scope; no silent harmonisation.
- Regulatory watch: IMO MSC 110 approved MSC.1/Circ.1691, MSC.1/Circ.1175/Rev.2 and MSC.1/Circ.1255/Rev.1. Actual circular texts and applicability must be checked before revising learning content. IMO safe-mooring page records SOLAS II-1/3-8 amendments effective 1 Jan 2024 and associated guidelines.
- Detailed matrix and next steps: [BWK–F1–F3 candidate cross-match batch 01](../data/bwk-f1-f3-crossbook-match-candidates-batch-01.md).


## 15 November 2026 — BWK↔F1/F3 cross-book candidate matrix, batch 02
- Completed exact Polar & Ice mapping: BWK I1–I5 cross-referenced to F1 Topic 6 Q1–Q11. I1/I2/I3 have strong direct overlap; I4 is related coverage; I5 spans multiple F1 questions. The BWK Polar navigation-system regulatory/exemption gap is only partially addressed by F1 equipment questions.
- Compared BWK emergency cards E10–E15 with inspected F3 Topic 8 answer bodies. Strong overlap established for BWK E15 collision ↔ F3 T8 Q16. E10 abandon ship, E12 CO2 and E13 enclosed-space entry are complementary rather than duplicates; E14 chemical tanker contingency and E15 flooding/blackout remain unmatched in inspected F3 pages.
- Preserved distinctions between BWK's operational procedures and F3's drill/system answers. No source material was modified and no public learning unit was created.
- Regulatory currency lead: IMO MSC.538(107) Polar Code amendments entered into force 1 Jan 2026. Applicability depends on ship category, tonnage, voyage and construction date; verify the current official text before any answer is updated.
- Detailed source map and limitations: [BWK–F1–F3 candidate cross-match batch 02](../data/bwk-f1-f3-crossbook-match-candidates-batch-02.md).
- Next: exact F1 Topic 1 Watchkeeping/COLREG mapping against BWK W1–W13; inspect F3 Topic 6 dry-dock answer bodies against BWK S4–S6; extend F3 Topic 8 search for any further matches before declaring gaps.


## 15 November 2026 — BWK↔F1 Watchkeeping/COLREG cross-match, batch 03
- Inspected BWK Topic 9 W1–W13 (printed pp. 98–108) and cross-referenced F1 Topic 1 COLREG, Topic 9 STCW/SOLAS and relevant Topic 4 weather material.
- Strong/direct matches: W3↔F1 T9 Q23/Q24; W4↔T9 Q2/Q17/Q29; W5↔T9 Q3; W6↔T1 Q2; W7↔T1 Q3; W8↔T1 Q103/Q8/Q29; W9↔T1 Q6 and rule-specific questions; W11↔T1 Q1/Q4/Q7/Q9 plus T9 Q3; W12↔T9 Q18; W13↔T1 Q30/T9 Q9.
- W1/W2 have complementary rather than exact matches in F1 T9 Q1/Q23; W10 has only partial weather/equipment cross-references in the inspected F1 material and remains a distinct operational learning unit.
- Corrected the mapping scope: F1 watchkeeping questions are primarily in Topic 9, COLREG in Topic 1 and heavy-weather context partly in Topic 4. Do not treat all as Topic 1 duplicates.
- Detailed map: [BWK–F1 Watchkeeping/COLREG cross-match batch 03](../data/bwk-f1-watchkeeping-colreg-crossmatch-batch-03.md).
- Next: inspect F3 Topic 6 dry-dock answers against BWK S4–S6; then consolidate cross-book candidate batches into a provenance-preserving concept register. No source PDFs modified and no public learning units created.


## 15 November 2026 — BWK↔F3 dry-dock cross-match, batch 04
- Inspected BWK S4–S6 (printed pp. 112–114) and F3 Topic 6 dry-docking / ship-construction questions (printed pp. 133–153 and relevant Part B references).
- S4 flooding checklist has strong coverage across F3 T6 Q1/Q3/Q7/Q10/Q63/Q66: preparation, critical period, pre-flooding checks, stability and post-undocking checks.
- S5 dry-dock emergencies is only partially matched by F3 T6 Q46/Q49/Q92: critical-period hazards, toppling prevention and listing during flooding. F3's inspected answers do not cover the full BWK fire / personal-injury / enclosed-space / yard-safety scope.
- S6 side-shell repair specification has related supporting material in F3 T6 Q5/Q51/Q61/Q62 (shell expansion plan, deck crack, thickness criteria and UTM), but no exact side-shell plate repair-specification answer was established. Deck-crack Q51 is not a substitute.
- Differences and review gates are recorded in [BWK–F3 Dry-Dock cross-match batch 04](../data/bwk-f3-drydock-crossmatch-batch-04.md).
- Next: search the remaining F3 Topic 6 Part B material for direct steel-renewal matches; then consolidate cross-match batches 01–04 into a provenance-preserving concept register. Original PDFs remain read-only; no public learning units created.


## 15 November 2026 — BWK↔F3 dry-dock search extension and cross-book concept register draft 01
- Extended F3 Topic 6 search through Part B and added supporting cross-references: T6 Q30 (docking/shell-expansion plans) and Q72 (docking a vessel with bow damage). These support repair planning but do not supply an exact side-shell plate replacement specification for BWK S6.
- Confirmed F3 T6 Q7 as a strong BWK S4 match for pre-flooding checks; Q1/Q3/Q10/Q63/Q66 cover critical period, preparation, upthrust and post-undocking lifecycle.
- Created `data/bwk-f1-f3-deduplicated-concept-register-draft-01.md` consolidating cross-match batches 01–04 into 26 concept records plus complementary candidates, source differences, confidence and review gates.
- Register is a draft, not full nine-book deduplication, technical approval or publication clearance. It records inspected-scope absences only and preserves all source PDFs as read-only.
- Next: complete remaining F3↔BWK topic mappings (including broader F3 Topic 8 and BWK E14/E15, S5/S6 edge cases), then extend the concept register to all nine books with rights/privacy/reviewer metadata before any public migration.


## 15 November 2026 — BWK↔F3 emergency / dry-dock safety cross-match, batch 05
- Extended F3 Topic 8 and related Topic 3/6 review against BWK E10–E15 and S5.
- E12 fixed CO2 release has a strong operational match in F3 T8 Q38 (engine-room fire / CO2 release precautions); Q9/Q12/Q21 are supporting test, system and PMS references only.
- E10 abandon ship is related to F3 T8 Q34 foundering and Q30/Q11 drills, but operational abandonment and drill requirements remain separate objectives.
- E11 fire-wallet / port-fire content is complementary to F3 T8 Q84 fire control plan, Q85 fire drill and Q38 engine-room fire; no full port-fire handover equivalent was established.
- E14 chemical-tanker cargo-space fire / NLS spill has no direct match in inspected F3 scope. E15 engine-room flooding partially relates to F3 T8 Q29; blackout in TSS remains unmatched as an operational sequence. T3 Q6 lists blackout generally; T8 Q110 is steering failure in TSS, not blackout.
- S5 gains additional complementary links to F3 T6 Q94 (worker death in dry dock), Q46/Q49/Q92 (critical-period and flooding hazards), without replacing BWK's broad yard-safety coverage.
- Detailed map: [BWK–F3 emergency / dry-dock safety cross-match batch 05](../data/bwk-f3-emergency-drydock-crossmatch-batch-05.md).
- Next: update the concept register and continue BWK/F3 cross-topic mapping where emergency and ship-handling objectives overlap. Original PDFs remain read-only; no public content migration.


## 15 November 2026 — Cross-book concept register draft 02
- Extended draft 01 with eight additional concepts from emergency and dry-dock safety cross-match batch 05: abandon ship/foundering, fire-wallet, fixed CO2 release, enclosed-space entry/rescue, chemical-tanker fire/NLS spill, flooding/foundering, blackout-in-TSS, and dry-dock fatality/yard safety.
- New register: `data/bwk-f1-f3-deduplicated-concept-register-draft-02.md`; draft 01 retained as historical version.
- The register remains an internal BWK↔F1↔F3 candidate map, not a nine-book full deduplication or public-content approval. Unmatched findings are limited to inspected source scope.


## 15 November 2026 — BWK↔F3 SAR/MOB cross-match, batch 06
- Inspected BWK R1–R15 (printed pp. 10–26) and relevant F3 Topic 7/8/3 answers.
- Strong overlap: BWK R12 MOB turns ↔ F3 T7 Q48 (Williamson, Anderson and Scharnow). BWK's Lorén and double-turn coverage remains additional.
- Partial/strong scenario overlap: BWK R11 MOB immediate actions/recovery ↔ F3 T8 Q104 (person fallen in water in port) and T7 Q48. F3 Q104 is port-specific; BWK R11 is broader at-sea response.
- Partial: BWK R10 missing crew ↔ F3 T7 Q48 only for the manoeuvre options; F3 does not cover the wider Master's reporting/search duties in that answer.
- F3 T8 Q78 assistance to a vessel on fire is related to distress assistance but is not a general SOLAS V/33 distress-message answer. BWK R1–R7, R13–R15 remain unmatched in inspected F3 scope.
- Detailed map: [BWK–F3 SAR/MOB cross-match batch 06](../data/bwk-f3-sar-mob-crossmatch-batch-06.md).
- Next: search F1 Topics 7/9 for SAR, MOB, distress-message and IAMSAR-related question IDs, then update the concept register. Original PDFs remain read-only.


## 15 November 2026 — BWK↔F1 SAR/MOB cross-match, batch 07
- Inspected F1 Topic 7, Topic 9 and Topic 3 for exact SAR/MOB links to BWK R1–R15.
- Strong/direct matches: R6/R7 search patterns ↔ F1 T7 Q16; R8 distress obligations ↔ T9 Q37; R13 MOB in TSS ↔ T7 Q19; R15 Indian MRCC organisation ↔ T3 Q51.
- Partial coverage: R1/R3/R4 OSC/IAMSAR structure, R5 datum/track spacing, R9 first-on-scene preparation, R10 missing crew, R11 general MOB, R12 turns (F1 Q27 only Williamson). R2 SMC duties and R14 heavy-weather recovery remain unmatched in inspected F1 scope.
- Detailed mapping: [BWK–F1 SAR/MOB cross-match batch 07](../data/bwk-f1-sar-mob-crossmatch-batch-07.md).
- Next: add confirmed F1/F3 SAR links to the concept register and continue remaining BWK topic comparisons. Original PDFs remain read-only.


## 15 November 2026 — Cross-book concept register draft 03
- Extended draft 02 with ten SAR/MOB concepts from cross-match batches 06–07: IAMSAR search patterns, SAR coordination, datum/track spacing, SOLAS V/33 distress obligations, MOB actions, MOB turns, TSS/fog MOB, heavy-weather recovery, Indian MRCC/MRSC and missing crew.
- New register: `data/bwk-f1-f3-deduplicated-concept-register-draft-03.md`; drafts 01 and 02 retained as historical versions.
- SAR/MOB mapping shows F1 has useful direct matches for search patterns, distress obligations, TSS MOB and Indian MRCCs; F3 has direct/partial matches for rescue turns and port MOB. SMC duties and heavy-weather recovery remain gaps in inspected F1/F3 scope.
- This remains an internal BWK↔F1↔F3 candidate map, not a complete nine-book deduplication or publication approval.


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 08

- Reopened the user-authored BWK, F1 and F3 PDFs and inspected BWK Topic 2 (VTS/SRS/routeing) and Topic 12 (piracy/BMP5), with corresponding F1 routeing/reporting/piracy questions and F3 security questions.
- Added internal audit report `data/bwk-f1-f3-crossbook-match-batch-08-vts-routeing-piracy.md`.
- Added concept register Draft 04 with XBK-045 to XBK-049. The candidate register now contains 49 IDs; it remains a partial BWK↔F1↔F3 register, not a complete nine-book deduplication.
- Key source divergence: BWK uses BMP5; F3 T3 Q61 explicitly refers to BMP Maritime Security (2025) replacing BMP5. Preserve both source versions pending dated regulatory/industry verification; no silent update.
- Confirmed the need to keep SOLAS V/10 ship routeing, V/11 ship reporting and V/12 VTS as separate learning concepts, while linking related questions.
- No original PDF, source repository, study answer, website branch or public learning unit was modified. No public migration or technical approval is claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | BWK↔F1↔F3 cross-book matching extended through batch 08; concept register Draft 04 now has XBK-001–049 | `data/bwk-f1-f3-crossbook-match-batch-08-vts-routeing-piracy.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-04.md` | Partial inspected-scope audit only; no accuracy or publication clearance |
| OP-04 | Source-to-platform mapping extended for VTS, SRS, routeing and piracy concepts | Batch 08 report and stable XBK IDs | Keep BMP5/BMP 2025 divergence visible; rights, privacy and qualified technical review remain mandatory |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 09

- Reopened the user-authored BWK, F1 and F3 PDFs and inspected BWK Topic 3 Pilotage against F1 bridge-support / pilot-ladder questions and F3 pilot-ladder material.
- Added `data/bwk-f1-f3-crossbook-match-batch-09-pilotage.md` and concept register Draft 05 with XBK-050 to XBK-052.
- Separated three linked but distinct learning objectives: Master–pilot information exchange; Master's/bridge team's duties with pilot onboard; pilot boarding manoeuvre and transfer-equipment requirements.
- Flagged F3's cited pilot-ladder amendments MSC.572(110) / MSC.576(110) and future applicability dates for official-text verification before public use.
- Candidate concept register now contains 52 IDs; still a partial BWK↔F1↔F3 inspected-scope register, not a nine-book complete deduplication.
- No source PDFs, study repositories or website files were modified; no public migration or technical approval is claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through pilotage batch 09; Draft 05 contains XBK-001–052 | `data/bwk-f1-f3-crossbook-match-batch-09-pilotage.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-05.md` | Inspected-scope match audit only; no technical or publication clearance |
| OP-04 | Pilotage concepts mapped to source questions and stable IDs | Batch 09 report | Official pilot-transfer requirements, rights, privacy and qualified review remain open |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 10

- Reopened BWK Topic 5 pp. 53–62 and compared T1–T9 with inspected F1/F3 ETA, tug and girting material.
- Added `data/bwk-f1-f3-crossbook-match-batch-10-towing-tugs.md` and concept register Draft 06 with XBK-053 to XBK-061.
- Strong overlaps: tanker ETA (BWK T1 ↔ F1 T7 ETA questions ↔ F3 T8 Q8), tug types (BWK T7 ↔ F3 T7 Q40), girting (BWK T8 ↔ F3 T7 Q8).
- BWK's full non-tanker procedure, ETB decision matrix, connecting/passage/casting-off sequence, ocean towing/bollard-pull material and ship–tug interaction remain distinct or unmatched in the inspected F1/F3 scope.
- Flagged gob/gog terminology and current applicability of SOLAS II-1/3-4 / towing guidance for qualified review.
- Candidate register now contains 61 IDs; still a partial BWK↔F1↔F3 inspected-scope register, not a complete nine-book deduplication.
- No source PDF, study repository or website file modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through towing/tugs batch 10; Draft 06 contains XBK-001–061 | `data/bwk-f1-f3-crossbook-match-batch-10-towing-tugs.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-06.md` | Inspected-scope audit only; no technical or publication clearance |
| OP-04 | Towing / tug / ETA source concepts mapped and classified | Batch 10 report | Official regulatory currency, rights, privacy and qualified technical review remain open |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 11

- Reopened BWK Topic 7 source pages for H1–H10 and compared inspected F1/F3 ship-handling passages.
- Added `data/bwk-f1-f3-crossbook-match-batch-11-shiphandling-h1-h10.md` and concept register Draft 07 with XBK-062 to XBK-071.
- Strong overlaps include squat, bank effect, ship-to-ship interaction, shallow-water effects and transverse thrust; pivot point and turning-circle material are complementary; passing moored ships, large-freeboard wind effects and restricted-water current effects remain unmatched in the inspected scope.
- Kept formal turning-circle definitions separate from practical factors, and fixed-pitch propeller behaviour separate from CPP behaviour.
- Candidate register now contains 71 IDs; still partial BWK↔F1↔F3 inspected-scope matching, not complete nine-book deduplication.
- No source PDF, study repository or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through ship-handling H1–H10 batch 11; Draft 07 contains XBK-001–071 | `data/bwk-f1-f3-crossbook-match-batch-11-shiphandling-h1-h10.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-07.md` | Inspected-scope audit only; technical / publication clearance remains open |
| OP-04 | Ship-handling H1–H10 source concepts mapped and classified | Batch 11 report | Qualified technical review, rights and privacy screening remain mandatory |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 12

- Reopened BWK Topic 7 pp. 84–92 and compared H11–H20 with inspected F1/F3 source passages.
- Added `data/bwk-f1-f3-crossbook-match-batch-12-shiphandling-h11-h20.md` and concept register Draft 08 with XBK-072 to XBK-081.
- Strong overlaps: BWK H14 short-round turn ↔ F1 fixed-pitch short-turn questions; BWK H16 pooping/broaching ↔ F3 T5 Q28.
- Complementary coverage: CPP ↔ F3 transverse-thrust material; rolling ↔ F3 rolling-period material; following-sea capsize ↔ F3 pooping/broaching and rolling-period material; heavy-weather manoeuvring ↔ F3 preparation/ballast; stopping distance ↔ F1 wheelhouse poster.
- Kept CPP separate from fixed-pitch, short-turn examples for RH separate from BWK's LH procedure, and stopping distance separate from rudder cycling.
- Candidate register now contains 81 IDs; partial BWK↔F1↔F3 inspected-scope audit only.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through ship-handling H11–H20 batch 12; Draft 08 contains XBK-001–081 | `data/bwk-f1-f3-crossbook-match-batch-12-shiphandling-h11-h20.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-08.md` | Inspected-scope audit only; not complete nine-book deduplication |
| OP-04 | Ship-handling H11–H20 concepts mapped and classified | Batch 12 report | Qualified technical/regulatory review, rights and privacy screening remain mandatory |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 13

- Reopened BWK Topic 8 pp. 94–97 and compared M1–M3 with inspected F1/F3 mooring material.
- Added `data/bwk-f1-f3-crossbook-match-batch-13-mooring.md` and concept register Draft 09 with XBK-082 to XBK-084.
- Running moor and standing moor have strong direct overlap with F1/F3; mooring between two buoys remains unmatched in inspected F1/F3 passages.
- Preserved running vs standing sequence distinction, source-specific anchor labels and cable-length caveats.
- Candidate register now contains 84 IDs; partial BWK↔F1↔F3 inspected-scope register only.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through BWK Topic 8 Mooring batch 13; Draft 09 contains XBK-001–084 | `data/bwk-f1-f3-crossbook-match-batch-13-mooring.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-09.md` | Inspected-scope audit only; not complete nine-book deduplication |
| OP-04 | BWK Topic 8 mooring concepts mapped and classified | Batch 13 report | Qualified technical review, rights and privacy screening remain mandatory |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 14

- Reopened BWK Topic 10 pp. 109–114 and compared S1–S6 with inspected F1/F3 STS and dry-dock passages.
- Added `data/bwk-f1-f3-crossbook-match-batch-14-sts-drydock-repairs.md` and concept register Draft 10 with XBK-085 to XBK-090.
- No full STS area-selection / service-ship approach answer was established in the inspected F1/F3 passages. BWK's parallel and angled approaches remain separate.
- Strong overlap: pre-flooding dry-dock checklist ↔ F3 T6 Q7; complementary F1 docking sequence; dry-dock emergencies ↔ F3 critical-period hazards / fatality response; side-shell repair specification ↔ F3 shell expansion plan, UTM and scantling material.
- Candidate register now contains 90 IDs; partial BWK↔F1↔F3 inspected-scope audit only.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through BWK Topic 10 STS/dry-dock/repairs batch 14; Draft 10 contains XBK-001–090 | `data/bwk-f1-f3-crossbook-match-batch-14-sts-drydock-repairs.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-10.md` | Inspected-scope audit only; not complete nine-book deduplication |
| OP-04 | BWK Topic 10 concepts mapped and classified | Batch 14 report | Qualified technical/class/regulatory review, rights and privacy screening remain mandatory |
