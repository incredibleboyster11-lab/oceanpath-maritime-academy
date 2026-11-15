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


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 15

- Reopened BWK Topic 2 pp. 27–32 and compared V1–V4 with inspected F1 reporting / VTS / routeing answers.
- Added `data/bwk-f1-f3-crossbook-match-batch-15-vts-reporting-routeing.md` and concept register Draft 11 with XBK-091 to XBK-094.
- Strong direct overlap: VTS service structure and ship reporting systems; strong complementary overlap: practical VTS communication and ship routeing.
- Preserved separation of SOLAS V/10 routeing, V/11 ship reporting and V/12 VTS; recorded Indian reporting thresholds as requiring current official verification.
- No direct F3 answer established in targeted search; absence is limited to inspected search scope.
- Candidate register now contains 94 IDs; partial BWK↔F1↔F3 inspected-scope audit only.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through BWK Topic 2 VTS/reporting/routeing batch 15; Draft 11 contains XBK-001–094 | `data/bwk-f1-f3-crossbook-match-batch-15-vts-reporting-routeing.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-11.md` | Inspected-scope audit only; not complete nine-book deduplication |
| OP-04 | BWK Topic 2 VTS/reporting/routeing concepts mapped and classified | Batch 15 report | Qualified regulatory review, rights and privacy screening remain mandatory |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 16

- Reopened BWK Topic 3 pp. 33–36 and compared P1–P4 with inspected F1/F3 passage-planning, pilot-ladder and BRM material.
- Added `data/bwk-f1-f3-crossbook-match-batch-16-pilotage.md` and concept register Draft 12 with XBK-095 to XBK-098.
- MPX and pilot duties have partial / complementary support only; pilot boarding manoeuvre has ladder and passage-plan support; no complete F1/F3 equivalent established for pilot engagement/duties.
- Preserved the distinction between MPX and passage planning, and between pilot's conduct of navigation and Master's command.
- Candidate register now contains 98 IDs; partial BWK↔F1↔F3 inspected-scope audit only.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through BWK Topic 3 Pilotage batch 16; Draft 12 contains XBK-001–098 | `data/bwk-f1-f3-crossbook-match-batch-16-pilotage.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-12.md` | Inspected-scope audit only; not complete nine-book deduplication |
| OP-04 | BWK Topic 3 pilotage concepts mapped and classified | Batch 16 report | Qualified regulatory review, rights and privacy screening remain mandatory |


## 15 November 2026 — BWK↔F1↔F3 cross-book audit batch 17

- Reopened BWK Topic 12 pp. 120–121 and compared Z1–Z2 with F1 regional reporting and F3 ISPS / piracy material.
- Added `data/bwk-f1-f3-crossbook-match-batch-17-piracy-bmp.md` and concept register Draft 13 with XBK-099 to XBK-100.
- Strong overlap: BWK BMP5 prevention / response ↔ F1 reporting contacts and F3 attack response / SPM / SSAS / SSA.
- Material version conflict recorded: F3 says BMP Maritime Security (2025) replaces BMP5. BWK BMP5 retained as historical source content pending current-version review.
- Flagged AIS treatment and HRA geographic definitions for current official security guidance check; security-sensitive ship-specific details excluded from public migration.
- Candidate register now contains 100 IDs; partial BWK↔F1↔F3 inspected-scope audit only.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Cross-book audit extended through BWK Topic 12 piracy/BMP batch 17; Draft 13 contains XBK-001–100 | `data/bwk-f1-f3-crossbook-match-batch-17-piracy-bmp.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-13.md` | Partial inspected-scope register; not complete nine-book deduplication |
| OP-04 | BWK Topic 12 piracy/BMP concepts mapped and classified | Batch 17 report | Current security guidance, confidentiality, rights and qualified review remain mandatory |


## 15 November 2026 — BWK↔F1↔F3 open-gap audit batch 18

- Rechecked the three explicit BWK source gaps against targeted F1/F3 searches.
- Added `data/bwk-f1-f3-gap-audit-batch-18-emergency-polar-chemical-fire.md` and concept register Draft 14 with XBK-101 to XBK-103.
- Safety Committee: F3 T4 Q85 / T3 Q21 give partial safety-officer / monthly-meeting support, but no full committee agenda.
- Polar Code: F1 T6 navigation equipment supports part of the question; existing-ship exemptions remain unlocated in inspected passages.
- Chemical tanker Type 1/2 cargo-space fire: F3 fixed systems and tanker deck explosion answers are related only; no complete contingency plan found.
- All three remain open. No generic operational answer stitched together from incomplete material.
- Candidate register now contains 103 IDs; partial BWK↔F1↔F3 register and gap record only.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Three explicit BWK gaps rechecked against F1/F3 in batch 18; Draft 14 contains XBK-001–103 | `data/bwk-f1-f3-gap-audit-batch-18-emergency-polar-chemical-fire.md`; `data/bwk-f1-f3-deduplicated-concept-register-draft-14.md` | All three gaps remain open |
| OP-04 | Safety Committee, Polar Code exemptions and chemical tanker fire-plan gaps classified | Batch 18 report | Official source verification and qualified review required before drafting / publication |


## 15 November 2026 — Regulatory gap research batch 19

- Added `docs/REGULATORY-GAP-RESEARCH-BATCH-19-SAFETY-POLAR-CHEMICAL-FIRE.md` and concept register Draft 15.
- XBK-101 Safety Committee: ILO MLC OSH Chapter 5 and MCA COSWP committee agenda/minutes guidance located. Ready for source-led educational drafting after checking current COSWP 2026 and flag/company applicability. Agenda to be labelled a synthesis, not universal mandatory list.
- XBK-102 Polar Code: verified original MSC.385(94) Chapter 9.3 construction-date provisions and MSC.538(107) new Chapter 9-1 effective 1 Jan 2026. Clarified that specific equipment provisions have build-date thresholds; no blanket existing-ship exemption. UK legislation provides a jurisdiction-specific transition to 1 Jan 2027 for specified additional categories built before 1 Jan 2026.
- XBK-103 Chemical tanker fire: IMO IBC framework and Type 1/2 definitions verified. Current detailed IBC/FSS/SOLAS provisions and cargo-/ship-specific fire plan still required; no generic operational checklist drafted.
- Candidate register remains 103 IDs; Draft 15 refines research status without adding new concepts.
- No source PDFs, study repositories or website files modified; no public migration or technical approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-04 | Regulatory gap research batch 19 completed; Safety Committee and Polar topics ready for source-led draft; chemical tanker fire remains open | `docs/REGULATORY-GAP-RESEARCH-BATCH-19-SAFETY-POLAR-CHEMICAL-FIRE.md`; concept register Draft 15 | Current flag/company / COSWP verification; qualified Polar Code and chemical-tanker review |


## 15 November 2026 — Internal answer drafting batch 20

- Created `drafts/BWK-GAP-ANSWERS-BATCH-20-SAFETY-COMMITTEE-POLAR-NAVIGATION.md`.
- Drafted source-led exam answers for XBK-101 Safety Committee and XBK-102 Polar Code navigation requirements / existing-ship provisions.
- Safety Committee agenda labelled a synthesis based on ILO / MCA guidance, not a universal statutory agenda.
- Polar answer separates original Chapter 9 construction-date thresholds from MSC.538(107) Chapter 9-1 effective 1 Jan 2026; Administration-specific implementation check remains required.
- XBK-103 chemical-tanker Type 1/2 cargo-space fire intentionally remains undrafted as a generic operational checklist pending current consolidated IBC/FSS/SOLAS text, cargo-specific approved procedures and specialist review.
- Drafts are internal and not approved for public release.
- No source PDFs, study repositories or website files modified.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-04 | Safety Committee and Polar navigation gap answers drafted internally in batch 20 | `drafts/BWK-GAP-ANSWERS-BATCH-20-SAFETY-COMMITTEE-POLAR-NAVIGATION.md`; concept register Draft 16 | Qualified technical / regulatory review before publication |
| OP-03 | Candidate register remains 103 concepts; Draft 16 records gap-draft statuses | `data/bwk-f1-f3-deduplicated-concept-register-draft-16.md` | Partial BWK↔F1↔F3 register only |


## 15 November 2026 — Chemical tanker fire / NLS research batch 21

- Added `docs/REGULATORY-GAP-RESEARCH-BATCH-21-CHEMICAL-TANKER-FIRE-NLS.md`.
- Retrieved the exact BWK source question (Nov 2022 Q2) and confirmed E14's NLS spill answer exists while the cargo-space fire answer is explicitly marked not yet covered.
- Key interpretation: IMO Type 1 / Type 2 are chemical-tanker design categories based on cargo hazards, not fire classes. Fire medium cannot be selected from ship type alone.
- Located IBC Code Chapter 11 provisions: 11.3 fixed deck foam (cargo compatibility and coverage); 11.4 fixed dry chemical powder for deck cargo area / connections when flammable products are carried; 11.5 fixed systems for enclosed cargo-handling machinery spaces. These systems must not be misrepresented as a universal tank-interior extinguishing method.
- Located IBC 16.2.3 cargo information requirements (including fire-fighting procedures / media) and 16.3.3 officer training for leakage, spillage and fire. SOLAS II-2 Reg.16 requires fire-safety operational booklet with IBC references.
- Kept NLS spill plan separate and flagged that oil-spill techniques / absorbents / dispersants cannot be assumed chemically compatible with every NLS.
- Added a role-based educational response architecture, not a vessel-approved operational checklist.
- XBK-103 is now research-supported but remains open for specialist technical approval and controlled current-code review.
- No source PDFs, study repositories or website files modified; no public migration or approval claimed.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-04 | Chemical tanker fire / NLS source research batch 21 completed; XBK-103 research-supported, not approved | `docs/REGULATORY-GAP-RESEARCH-BATCH-21-CHEMICAL-TANKER-FIRE-NLS.md` | Current IBC/FSS/SOLAS controlled texts, cargo-specific media, specialist review |
| OP-03 | Candidate register remains 103 concepts; XBK-103 research status refined | Draft 16 + Batch 21 memo | Nine-book deduplication still incomplete |


## 15 November 2026 — Chemical tanker fire / NLS answer framework batch 22

- Added `drafts/BWK-GAP-ANSWER-BATCH-22-CHEMICAL-TANKER-FIRE-NLS.md`.
- XBK-103 now has an internal exam-answer framework combining cargo-space fire response architecture and the existing NLS spill response, with distinct sections.
- The answer correctly distinguishes Type 1 / Type 2 ship design categories from fire classes and makes cargo-specific media selection mandatory.
- IBC 11.3 / 11.4 / 11.5 are described separately; no claim that deck foam or deck dry powder is a universal cargo-tank interior extinguishing method.
- NLS response has compatibility cautions: do not assume generic oil-spill absorbents, dispersants, water or neutralisers are suitable.
- Draft remains internal and requires current-code and qualified specialist review before public release or operational use.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-04 | XBK-103 internal exam framework drafted in batch 22 | `drafts/BWK-GAP-ANSWER-BATCH-22-CHEMICAL-TANKER-FIRE-NLS.md`; research Batch 21 | Qualified chemical-tanker / fire-safety review and controlled current-code verification |
| OP-03 | Candidate concept register remains 103 IDs; Draft 17 records all three former gaps' draft/research status | `data/bwk-f1-f3-deduplicated-concept-register-draft-17.md` | Broader nine-book deduplication remains incomplete |


## 15 November 2026 — Nine-book integration begins: Naval Architecture I ↔ II batch 23

- Reopened both user-authored Naval Architecture source books and reviewed their indexes, paper-pattern pages and selected answer bodies.
- Added `docs/NAVAL-ARCHITECTURE-I-II-CROSS-BOOK-MAP-BATCH-23.md` and register Draft 18.
- NA I: 62 source-declared theory answers, 81 worked numericals, 42 past papers; eight theory topics and eight numerical groups.
- NA II: 70 source-declared theory answers, 73 worked numericals, 39 past papers; fourteen theory topics and three numerical groups.
- Created first 13 integration records XNA-001 to XNA-013.
- Key findings: bulk-carrier midship sketch B15 ↔ G9 likely duplicate pending diagram comparison; WT integrity vs fire integrity are related but distinct; passenger subdivision and damage stability complement WT bulkhead construction; NA II bilging / SF-BM / thrust numerical banks remain separate from NA I numerical types.
- Flagged January 2026 SOLAS amendments to II-1 / II-2 / V and new electronic inclinometer carriage requirements for qualifying new bulk carriers / containerships. These are dated update hooks, not retroactive edits to exam-source answers.
- No source PDFs, original study repos or website files modified.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | Nine-book integration started with NA I ↔ NA II batch 23; 13 XNA cross-book relationships created | `docs/NAVAL-ARCHITECTURE-I-II-CROSS-BOOK-MAP-BATCH-23.md`; Draft 18 | First-pass only; diagram and answer-body comparisons pending |
| OP-04 | NA I / NA II regulatory currency watch flagged for 2026 SOLAS changes | IMO January 2026 SOLAS supplement and IMO 2026 rules summary | Qualified technical / regulatory review before publication |


## 15 November 2026 — NA I / NA II diagram comparison batch 24

- Reopened exact answer bodies and diagram descriptions for NA I B15 (printed pp. 96–97) and NA II G9 (printed p. 51).
- Corrected the first-pass XNA-001 classification: not a confirmed duplicate. NA I B15 is explicitly a single-skin bulk carrier; NA II G9 is a bulk carrier / double-skin variant and adds high-density-cargo strengthening.
- Preserved two source variants under a recommended parent concept; prohibited silent mixing of double-skin features into the single-skin sketch.
- Added `docs/NAVAL-ARCHITECTURE-BULK-CARRIER-SKETCH-COMPARISON-BATCH-24.md` and register Draft 19.
- Full-resolution visual QA of original figures remains a final gate before public redraw.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | XNA-001 diagram-level source comparison completed; reclassified as related variants, not duplicate | Batch 24 comparison memo; Draft 19 | Full-resolution figure inspection before public visual redraw |


## 15 November 2026 — NA stability cross-book map batch 25

- Compared NA I Topic 4 G01–G15 selected cards with NA II Topics 1–5.
- Added `docs/NAVAL-ARCHITECTURE-STABILITY-CROSS-BOOK-MAP-BATCH-25.md` and concept register Draft 20.
- Added XNA-014 to XNA-025: beam / GZ, angle of loll, grain criteria / VHM, intact / weather criteria, dynamical stability, GM estimation, cargo shift, KN curves, booklet contents and numerical-theory bridges.
- Identified two high-value near-duplicates: NA I G02 ↔ NA II A3 (beam effect) and NA I G03 ↔ NA II A4 (angle of loll), but preserved the extra scope in NA I cards.
- Kept Grain Code criteria distinct from grain heeling-arm curve, and general intact criteria distinct from weather criterion.
- No source PDFs or study repositories modified.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NA stability cross-book map extended to XNA-025 | Batch 25 report; Draft 20 | Full answer-body review and regulatory currency checks remain |


## 15 November 2026 — NA subdivision / fire integrity batch 26

- Compared NA I B01–B14 and B16–B17 with NA II K1–K6 and L1–L9.
- Added XNA-026 to XNA-037 and report `docs/NAVAL-ARCHITECTURE-SUBDIVISION-FIRE-INTEGRATION-BATCH-26.md`.
- Confirmed integration is complementary, not answer duplication: WT boundaries / doors / tests preserve subdivision; K-series addresses passenger subdivision and damage condition; L-series addresses fire objectives, divisions and testing.
- Preserved source corrections: P1/P2/P3 subdivision load lines are current source terminology; factor-of-subdivision A/B is not Load Line Convention Type A/B; no L7 answer is listed.
- Flagged January 2026 SOLAS II-2 amendments for current fire-safety review.
- No source PDFs or original study repos modified.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NA subdivision / fire integration extended to XNA-037 | Batch 26 report; Draft 21 | Current SOLAS / flag review required |


## 15 November 2026 — NA surveys / Load Line / Tonnage batch 27

- Compared NA I V01–V15 with NA II M1–M9 and N1–N5.
- Added XNA-038 to XNA-046 and report `docs/NAVAL-ARCHITECTURE-SURVEYS-LOADLINE-TONNAGE-BATCH-27.md`.
- Direct practical overlap: V11 Load Line survey preparation ↔ M9 Load Line survey.
- HSSC, ESP, CAP and CAS remain connected but distinct; tonnage measurement remains a separate NA II family.
- Added 2026 ESP Code amendment as a dated update hook: Administration oversight / audits of thickness-measurement firms. Do not silently rewrite historical source answers.
- No source PDFs or original study repos modified.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NA surveys / Load Line / Tonnage integration extended to XNA-046 | Batch 27 report; Draft 22 | Current convention / flag review and qualified surveyor review |


## 15 November 2026 — NA welding / corrosion / materials batch 28

- Compared NA I W01–W08 and C01–C07 with NA II I1/I2/I3/I5/I6/I7 and J1–J3.
- Added XNA-047 to XNA-063 and report `docs/NAVAL-ARCHITECTURE-WELDING-CORROSION-MATERIALS-BATCH-28.md`.
- Strong integrations: weld NDT ↔ steel testing; corrosion cell / galvanic series / cathodic protection ↔ aluminium-steel joint protection; steel and aluminium material selection ↔ fabrication.
- Preserved differences: general hull cathodic protection vs local dissimilar-metal electrical isolation; welding processes vs transition-joint design; steel tests vs weld NDT.
- Source index omissions preserved: no I4 card in NA II; no invented card or renumbering.
- No source PDFs or original study repos modified.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NA welding / corrosion / materials integration extended to XNA-063 | Batch 28 report; Draft 23 | Qualified welding / NDT / naval architecture review before public release |


## 15 November 2026 — NA numerical taxonomy / reconciliation batch 29

- Reopened NA I and NA II numerical indexes and selected detailed numerical pages.
- Added XNA-064 to XNA-073 and `docs/NAVAL-ARCHITECTURE-NUMERICAL-BANK-RECONCILIATION-BATCH-29.md`.
- NA I source index displays 8 families totalling 81 if dry-docking is counted as 5; detailed dry-docking page states 16 different questions. Marked unresolved pending exact numerical ID audit.
- NA II declares 73 worked numericals, but its visible index groups are 20 bilging + 20 SF/BM + 7 thrust/COP = 47. Flagged 26-question gap; no missing groups invented.
- Mapped shared mathematical foundations while preserving differences between centroid / centre of pressure, grounding / bilging, docking / SF-BM, intact / damage stability.
- No source PDFs or original study repositories modified.

| ID | Updated status | Evidence / next deliverable | Gate |
|---|---|---|---|
| OP-03 | NA numerical taxonomy mapped; two source count discrepancies opened | Batch 29 report; Draft 24 | Exact numerical ID reconciliation and independent solution verification |
