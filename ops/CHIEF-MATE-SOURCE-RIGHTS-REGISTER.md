# Chief Mate Source Rights & Provenance Register

**Review date:** 15 November 2026  
**Source repository:** `incredibleboyster11-lab/chiefmate-reels` (read-only)  
**OceanPath rule:** No source learning content is approved for republication until rights evidence and qualified content review are recorded.

## Current finding

The source repository contains a Hub catalogue, a production tracker and a video metadata directory. The catalogue points to nine Chief Mate learning groups. The tracker contains 1289 data rows across F1: 295, F2: 313, F3: 239, MEK: 116, NAV: 68, BWK: 63, LAW: 121, NA: 74. The video directory currently lists 64 JSON metadata files. These are inventory facts only; they do not establish ownership or permission.

**Overall rights status: UNKNOWN — NOT CLEARED FOR PUBLICATION.**

## Asset-class register

| Asset class | Identified scope | Rights status | Evidence required | Publication decision |
|---|---|---|---|---|
| Written-answer books | 9 Hub groups: MEK, LAW, NAV, NA, BWK, F1, F2, F3, NA1 | Unknown | Author/rightsholder identity, written licence/assignment, third-party source permissions, diagrams/images rights | Blocked |
| Oral-question banks | F1, F2, F3 groups; exact question content not copied into this register | Unknown | Rights to question wording, submitted reports, recordings/transcriptions and any third-party contributions | Blocked |
| Past examination papers | Referenced in source group metrics and learning assets | Unknown | Issuing authority terms, reproduction permission, copyright status and permitted excerpts | Blocked |
| Numerical solutions, sketches and diagrams | Embedded in subject learning assets | Unknown | Creator identity and rights; licences for any source diagrams, tables or illustrations | Blocked |
| Video scripts and metadata | 64 JSON files listed under `plan/videos/` | Unknown | Script/voice/visual ownership, contributor releases, music/font/stock licences, platform reuse scope | Blocked |
| Published short-form videos | YouTube/Instagram pointers appear in Hub metadata | Unknown | Account ownership, underlying script and media rights, cross-platform embedding/reuse permissions | Blocked |
| Oral reports and surveyor-related material | Referenced in oral-learning source groups; details intentionally excluded here | Unknown / heightened privacy review | Consent, anonymisation, lawful basis, confidentiality assessment, right to withdraw, no identifying personal data | Blocked |
| Social/community material | WhatsApp, YouTube and Instagram distribution pointers | Unknown | Account ownership, user-generated content terms, consent and moderation/privacy controls | Blocked |
| Brand assets | Names, logos, covers, thumbnails and visual templates | Unknown | Trademark clearance, designer assignment/licence, third-party logo permissions | Blocked |

## Source snapshots

| Source | Observed identifier | Use in this audit |
|---|---|---|
| `plan/hub/hub.json` | Blob `f3e40a10e6a6ec678212004b27412eadecaf911a` | Nine-group catalogue and asset pointers |
| `plan/tracker.csv` | Blob `89cb94339d10311cc32bfab9833edb0536fe8cb0` | Aggregate inventory only; row-level details not republished |
| `plan/videos/` | 64 listed JSON files | File paths, blob SHAs and sizes retained in the machine-readable inventory |

## Required clearance workflow

1. Identify each author, contributor and relevant rightsholder for each asset group.
2. Obtain written permission or confirm an applicable licence; record the exact evidence location and scope.
3. Audit third-party material separately: statutory text, exam papers, textbooks, diagrams, photographs, charts, fonts, music and stock media.
4. Treat oral reports, surveyor-related material and learner submissions as a separate privacy/confidentiality review; remove identifying details unless there is a documented lawful basis and consent/permission.
5. Record reviewer, review date, rights evidence, allowed uses, attribution, expiry/termination and takedown contact.
6. Only then create a separate derivative for OceanPath with provenance and human review. Never edit or move the original source.

## Explicit limitations

- The external Claude artifact contents have not been inspected in this pass.
- The 64 video JSON files have been listed by filename, SHA and size; their individual contents have not yet been audited.
- No author agreement, copyright assignment, licence, contributor release or third-party permissions were present in the inspected Hub/tracker metadata.
- Therefore this is a **baseline rights register**, not a legal opinion and not a completed rights clearance.
