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
