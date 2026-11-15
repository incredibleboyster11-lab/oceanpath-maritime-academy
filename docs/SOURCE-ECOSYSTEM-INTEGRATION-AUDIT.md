# OceanPath — Source Ecosystem Integration Audit

Audit date: 15 November 2026  
Scope: Read-only inspection of the chiefmate-reels repository main branch. No source files were changed.

## 1. Confirmed source files inspected

- README.md
- plan/strategy/growth-plan.html
- plan/hub/hub.json
- plan/tracker.csv
- plan/videos/ individual JSON records

## 2. Existing rank/book catalogue

The Study Hub JSON currently defines one rank group, Chief Mate, with nine book entries:

| Code | Book | Existing grouping |
|---|---|---|
| MEK | Engineering Knowledge (MEK) | Phase II written |
| LAW | Maritime Law | Phase II written |
| NAV | Navigational Aids | Phase II written |
| NA | Naval Architecture | Phase II written |
| BWK | Bridge Watchkeeping, SAR & Ship Handling | Phase II written |
| F1 | Function 1 Orals | Orals |
| F2 | Function 2 Orals | Orals |
| F3 | Function 3 Orals | Orals |
| NA1 | Naval Architecture I | Phase I written |

The Hub records resource counts and external artifact URLs. Those URLs currently point to hosted interactive artifacts. The OceanPath migration must preserve the interactive learning experience; do not flatten these books into static text summaries.

## 3. Social distribution links confirmed in hub.json

- YouTube channel and playlist page.
- Instagram account.
- WhatsApp group.
- WhatsApp Channel.

The Hub also contains individual video records with YouTube Shorts URLs, Instagram Reel URLs, a canonical subject/lane, episode metadata, titles, dates, and reading links back to the relevant question/book location.

## 4. Tracker fields confirmed

The tracker CSV contains:
- lane and sequence,
- planned date/day,
- subject and season/episode,
- chapter and chapter part,
- format and tier,
- unit/source identifier,
- title,
- asked-frequency notes,
- production status and completion date,
- notes.

Example stable source identifiers include F1:1_3 and F1:1_69. Some episodes combine multiple question identifiers. The integration must preserve these IDs and parse combined IDs carefully; never replace them with titles alone.

## 5. Existing video-record structure

The plan/videos folder contains individual JSON records for oral lanes and written-subject content, including F1/F2/F3, MEK, LAW, NA, NAV, BWK and TCN. The Hub's aggregate video records expose:
- lane/subject,
- series and episode,
- chapter,
- title,
- frequency/asked note,
- format,
- publish date,
- YouTube URL,
- Instagram URL,
- reading deep-link.

This is a strong basis for a central OceanPath media index. The source repository remains the content-production system of record.

## 6. Integration design decisions

1. Keep source question IDs as canonical identifiers wherever possible.
2. Create a public-safe derivative index in OceanPath; do not expose internal tracker notes, private planning, personal contact data, or unpublished oral reports.
3. Preserve book interaction and navigation. Each book gets a stable OceanPath landing page and a reviewed embed/hosted version after publication rights and technical checks.
4. Link videos to question IDs and the exact book anchor when the destination is public and stable.
5. Keep YouTube/Instagram/WhatsApp as distribution endpoints, not the only canonical record.
6. Add status and review metadata to every public content record.
7. Keep future Second Mate, Master and Engineering tracks as separate rank/discipline entities, not hard-coded Chief Mate-only pages.

## 7. Gaps and checks before public content migration

- Confirm publication rights for every book, diagram, image, source extract and third-party asset.
- Review the existing surveyor-profile fields before any public migration. Do not publish identifiable surveyor information or imply official endorsement.
- Confirm which tracker records are public-safe; internal production statuses and frequency notes may need editorial review.
- Audit every external artifact link for access, portability, mobile behaviour and ownership.
- Validate each answer against authoritative current references and obtain human review where needed.
- Build a mapping report for broken, duplicate, missing or ambiguous question IDs.
- Confirm that public video links and reading anchors resolve correctly.

## 8. Immediate next technical work

1. Define a versioned public content schema.
2. Generate a public-safe inventory from approved Hub/tracker fields only.
3. Map each current book to an OceanPath canonical route.
4. Create media-to-question cross-links.
5. Add automated validation for IDs, URLs, status and required provenance.
6. Do not publish full book content until the rights and review gates are complete.

## 9. Repository safety statement

This audit is read-only. The chiefmate-reels source repository and its files were not modified. The OceanPath repository is the destination for reviewed public derivatives only.
