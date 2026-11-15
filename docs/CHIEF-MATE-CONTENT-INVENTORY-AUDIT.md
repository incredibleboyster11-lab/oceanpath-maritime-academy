# Chief Mate Content Inventory — Baseline Audit

**Date:** 15 November 2026  
**Status:** All 64 video metadata files individually inspected; learning-artifact body review and rights clearance remain open.  
**Source repository:** `incredibleboyster11-lab/chiefmate-reels` — read-only.  
**Destination:** OceanPath repository.

## Executive result

The Hub catalogue identifies **9 Chief Mate learning groups** spanning Phase I written, Phase II written and oral preparation. The source production tracker contains **1289 data rows**. The video metadata directory contains **64 JSON files** at the time of this snapshot.

The Hub reports the group-level answer, numerical, MCQ and past-paper figures recorded in `data/chiefmate-content-inventory.json`. These are explicitly labelled **source-reported metrics**, not independently verified counts of unique, complete or publication-ready learning units.

**No learning content is cleared for republication at this stage.** Rights remain unknown, external artifact bodies have not been inspected, and specialist content review has not been recorded.

## Inventory by learning group

| Code | Learning group | Stage | Hub pointer |
|---|---|---|---|
| MEK | Engineering Knowledge (MEK) | Phase II written | Hub catalogue entry |
| LAW | Maritime Law | Phase II written | Hub catalogue entry |
| NAV | Navigational Aids | Phase II written | Hub catalogue entry |
| NA | Naval Architecture | Phase II written | Hub catalogue entry |
| BWK | Bridge Watchkeeping, SAR & Ship Handling | Phase II written | Hub catalogue entry |
| F1 | Function 1 Orals | Orals | Hub catalogue entry |
| F2 | Function 2 Orals | Orals | Hub catalogue entry |
| F3 | Function 3 Orals | Orals | Hub catalogue entry |
| NA1 | Naval Architecture I | Phase I written | Hub catalogue entry |

## Source snapshot and coverage

- Hub catalogue: `plan/hub/hub.json`, blob `f3e40a10e6a6ec678212004b27412eadecaf911a`.
- Production tracker: `plan/tracker.csv`, blob `89cb94339d10311cc32bfab9833edb0536fe8cb0`.
- Video metadata: `plan/videos/`, 64 files listed with blob SHA and byte size in the JSON inventory.
- Tracker subject row totals: F1 295; F2 313; F3 239; MEK 116; NAV 68; BWK 63; LAW 121; NA 74.
- The tracker contains operational fields such as episode status and production notes. They are not copied row by row into the public-safe inventory.
- Surveyor identifiers, oral-report details, personal data and question-frequency claims are intentionally excluded from this derivative.

## Video metadata review findings\n\nAll 64 JSON metadata files were individually fetched and parsed. They contain recurring production/distribution fields such as content slug, subject/lane, series or episode, topic/title, captions, YouTube descriptions, playlist references, media IDs/URLs and publication/privacy status. Several distinct metadata shapes exist (written/oral short-form, navigation lesson/shorts, promotional records and TCN chapter/question records); a single rigid source-field mapping would lose information.\n\nSome records contain source question identifiers or internal frequency/recency fields. Keep these internal until provenance and permitted use are established; do not present them publicly as verified exam likelihoods or official examination statistics. Some series records contain a `made_by` field, but this alone is not a contributor release, copyright assignment or licence. No dependable rights evidence or complete third-party attribution/licence record was established from the inspected metadata.\n\nThe nine Claude-hosted learning artifact bodies could not be fetched through the connected GitHub retrieval route, which rejected non-GitHub URLs. Their answer bodies, stable IDs and content quality remain unaudited.\n\n## Governance classification

1. **Catalogue metadata:** suitable for internal inventory, subject to source attribution and brand review.
2. **Answer/question content:** rights unknown; blocked from publication.
3. **Past papers and third-party extracts:** require separate permissions/terms review.
4. **Oral reports and surveyor-related data:** heightened privacy/confidentiality review; no personal identifiers in public derivatives.
5. **Video scripts/media:** rights unknown until contributor, voice, music, image and stock licences are checked.

## Next actions

1. Individually inspect video JSON metadata and identify creator/contributor/source fields without copying sensitive data.
2. Open each of the nine external learning artifacts where access permits; record structure and stable content IDs only, not answer bodies.
3. Obtain written rights evidence and contributor permissions.
4. Map stable source IDs to the OceanPath public-learning schema only after rights clearance.
5. Select one low-risk written topic for a human-reviewed pilot after rights are established.

## Audit boundary

This report is a **baseline**, not a complete content audit. It does not certify answer accuracy, uniqueness, syllabus currency, copyright ownership, privacy compliance or regulatory alignment. Source repositories remain unchanged.
