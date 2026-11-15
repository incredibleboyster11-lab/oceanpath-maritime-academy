# OceanPath Maritime Academy — Master Platform Blueprint

Version: 1.0  
Status: Strategic baseline; implementation is phased and subject to review.  
Working brand: OceanPath Maritime Academy (name/domain/trademark clearance is not yet complete).

## 1. North-star ambition

Build the most trusted, useful and widely recommended independent maritime examination-learning ecosystem for Indian seafarers, beginning with Deck Officers. Aim for category leadership through learning outcomes, content quality, community trust and institutional usefulness—not artificial exclusivity or anti-competitive conduct.

## 2. Non-negotiable principles

1. Essential learning resources remain free for learners.
2. No sale of candidate lists or personal data.
3. Candidate profiles are never shared with employers or recruiters without a separate, explicit, revocable candidate action.
4. No claim of DG Shipping, MMD, IMU or government affiliation, approval, endorsement, or authority to issue a Certificate of Competency.
5. No live-exam leaks, surveyor names, or unauthorised copyrighted material.
6. Public answers require source, technical and editorial review; corrections are visible and traceable.
7. Existing chiefmate-reels and Merchant-Navy-Education study repositories remain protected source systems. This public repository receives only reviewed, publication-cleared copies and metadata. Never edit, move, rename, delete, or refactor source material as part of website work.
8. No learner personal-data collection until privacy notice, purpose-specific consent, secure storage, role-based access, retention/deletion and incident response are implemented.
9. Do not collect data from under-18 learners until appropriate age assurance and parental-consent safeguards are implemented.
10. No paid AI API dependency in the first release.

## 3. Platform experience: Hybrid Academy + Open Library

### Public, no-login experience
- Academy homepage and rank-wise pathways.
- Open searchable library of approved books, question pages, revision material and diagrams.
- Links to related YouTube lessons, Instagram explainers and WhatsApp community/channel.
- Public exam guidance, corrections log, privacy information and editorial standards.
- No login wall for essential learning.

### Optional learner account (later phase)
- Saved bookmarks and personal notes.
- Learning progress and revision lists.
- Mock-test attempts and score history.
- Candidate-controlled profile and data export/deletion.
- Account is optional; public learning remains accessible without it.

### Rank and subject expansion order
- Initial focus: Chief Mate Phase II written, F1/F2/F3 orals and TCN, following source-project priorities.
- Next: Chief Mate Phase I and Master.
- Then: Second Mate FG.
- Marine Engineering/MEO only with a qualified engineering content partner.
- Later: overseas CoC examinations where there is verified demand and qualified reviewers.

## 4. Connected content model

Use stable canonical IDs as the join key. Never use display titles or social URLs as the only identifier.

Core entities:
- rank — e.g. Chief Mate, Second Mate, Master.
- subject — e.g. Maritime Law, Naval Architecture, TCN.
- book — an interactive revision book or structured learning resource.
- question — stable question ID, source reference, topic, marks/type where verified.
- answer_version — reviewed answer copy, version, reviewer, review date, citations and publication status.
- media_item — YouTube lesson, Instagram post/reel, or other media URL.
- revision_asset — diagram, memory hook, summary sheet or practice item.
- exam_report — consented and moderated candidate-submitted oral/exam report.
- assessment — mock test, question set, attempt and scoring rules.
- correction — issue, severity, status, resolution and affected answer version.

Relationship example:
Question ID → Book answer → YouTube lesson → Instagram short → Revision asset → Practice question → Corrections.

Every content item must have a publication state:
draft → source_checked → technical_review → editorial_review → approved → published → superseded/withdrawn.

A draft or unreviewed answer must never appear as approved.

## 5. Social and community integration

The website is the canonical owned hub. Social platforms are discovery and distribution channels.

- YouTube: full lessons, playlists and topic explainers.
- Instagram: short-form discovery and traffic to the relevant question/lesson.
- WhatsApp Channel: announcements, new lessons and updates.
- WhatsApp Group: peer discussion and doubt support, subject to moderation.
- Website: canonical library, stable question pages, learning paths, corrections and future assessments.

Each media record should include canonical question IDs, platform, URL, format, publish status, language, date and campaign/source tags. Keep copies/backups of owned media and maintain a platform-independent content index.

## 6. Data strategy and learner trust

Collect only data with a defined use. Separate the following purposes and consents:

A. Account/service data — only what is required to provide requested account features.  
B. Learning analytics — preferably aggregate or pseudonymous where practical.  
C. Marketing/newsletter — separate opt-in, not bundled with account creation.  
D. Oral/exam reports — explicit submission notice; moderation; no public surveyor names or identifying details.  
E. Results and testimonials — separate optional submission and separate permission for public use.  
F. Employer/recruiter sharing — default off; share only after the candidate selects the recipient and confirms the specific profile/data to share.

Initial data products:
- Learner interest and target-exam trends.
- Oral question frequency and topic trends from moderated, consented reports.
- Mock-test topic-level performance.
- Learning-resource usage in aggregate.
- Candidate-reported outcomes, with clear limitations and no unsupported pass-rate claims.

Never infer or publish pass rates from incomplete or self-selected submissions as if they represent all candidates.

Before forms/accounts launch, complete:
- Plain-language privacy notice and purpose-specific consent wording.
- Data inventory and lawful-purpose assessment.
- Secure database/storage, encryption in transit and at rest where supported.
- Least-privilege access, admin MFA and audit logs.
- Retention schedule and deletion/export workflow.
- Vendor/processor review and breach/incident response.
- Consent withdrawal and contact process.
- Age safeguards; exclude under-18 registrations until safeguards exist.
- Legal review for applicable Indian data-protection requirements, including the DPDP Act and Rules in force at launch.

Do not store personal data, credentials, tokens, or private contact lists in this Git repository.

## 7. Assessment and future products

### All India Mock Test
- Monthly, free learner-facing test as the target model.
- Published syllabus, format, marking scheme and review process.
- Topic-level feedback and transparent scoring.
- Rankings only where data quality, anti-cheating controls and consent support them.
- No claim that mock scores are official examination results or CoC certification.

### AI Oral Examiner
- Later-stage product, not a first-release dependency.
- Ground questions in approved content and moderated reports.
- Clearly identify AI practice; never impersonate an actual examiner or guarantee passing.
- Provide feedback with evidence and uncertainty; route disputed answers to human review.
- Design for low-bandwidth and intermittent connectivity.

### Readiness Score
- Candidate-facing, explainable and subject-specific.
- Based on disclosed assessment inputs and adequate sample size.
- Not a certificate, hiring guarantee or official competency judgment.
- Employer sharing only by specific candidate opt-in.

## 8. Sustainable revenue model

Keep essential learner education free. Prioritise organisation-funded services:
1. Clearly labelled relevant sponsorships.
2. Sponsored learner seats for premium practice tools while core content remains free.
3. MTI licences for assessment and learning dashboards.
4. Ship-manager officer development and promotion-readiness programmes.
5. SIRE 2.0/inspection interview practice for operators, with qualified subject reviewers.
6. Events, reports, webinars, corporate learning and grants/CSR.
7. Talent access only through an appropriately licensed RPSL partner and explicit candidate consent; do not independently undertake regulated recruitment.

Do not forecast revenue as guaranteed. Validate willingness to pay through pilots and measured outcomes before pricing.

## 9. Technical evolution

### Stage 1 — static public site
- Current GitHub Pages deployment.
- Mobile-first accessible HTML/CSS/JS.
- No login, no personal-data forms, no paid AI APIs.
- Static content index and stable canonical URLs.
- Basic privacy, corrections and editorial pages.

### Stage 2 — structured content and publishing pipeline
- Content metadata schema and validation.
- Build-time generation of subject/question pages.
- Broken-link, missing-source and publication-state checks.
- Versioned public content releases.
- Search index generated from approved content only.

### Stage 3 — domain and application backend
- Purchase/verify a suitable custom domain after trademark and availability checks.
- Move DNS without changing canonical content IDs.
- Select hosting and backend based on security, portability, cost and support needs.
- Database, authentication, consent records, backups and access controls.
- Keep content portable and exportable; avoid vendor lock-in.

### Stage 4 — assessments and dashboards
- Mock-test engine, scoring, anti-cheating safeguards and learner progress.
- Human-reviewed analytics and candidate-controlled data export/deletion.
- Institution dashboards with strict tenant separation.

### Stage 5 — AI and institutional platform
- AI oral practice, readiness insights and company/MTI tools.
- Use retrieval from approved content, evaluation sets, human review and monitoring.
- Do not introduce paid AI API costs until a validated budget and sustainable funding model exist.

## 10. Security and repository boundaries

- This public repository contains only publication-cleared website material and public code.
- Never copy private learner data, unpublished oral reports, internal tracker sheets, source PDFs or draft answers into the public repository.
- Never modify chiefmate-reels or Merchant-Navy-Education as a side effect of website work.
- Use separate branches and reviewable commits for site development.
- Protect main; use pull requests for substantial changes.
- Keep deployment permissions minimal and pin/review third-party actions as the workflow matures.
- Run link checks, HTML validation, accessibility checks, dependency review and backup checks.
- No secrets in source control.

## 11. Quality and trust system

Every published answer should have:
- Stable question ID and source provenance.
- Technical reviewer and editorial reviewer where appropriate.
- Last-reviewed date and version.
- References checked against authoritative current sources where applicable.
- Report-a-correction link and public correction status.
- Clear note where exam pattern or regulations may change.

Track quality indicators: corrections per 100 answers, time to resolve critical corrections, reviewed-content coverage, broken-link rate and learner-reported usefulness.

## 12. Growth scorecard

Measure outcomes, not vanity metrics:
- Monthly active learners and returning learners.
- Search-to-learning engagement and completion.
- Book/question/video cross-navigation.
- Newsletter opt-in and unsubscribe rates.
- Oral reports received, moderated and usable.
- Mock-test participation and repeat attempts.
- Reviewer coverage and correction resolution.
- Learner-reported exam outcomes with sample-size disclosure.
- Institutional pilots, renewals and measured learning outcomes.
- Website uptime, page speed, accessibility and security incidents.

Set numeric targets only after establishing a baseline.

## 13. Immediate execution backlog

1. Audit the existing public website and its links.
2. Inventory the source repositories read-only; map content IDs to books and media.
3. Define and validate the content metadata schema.
4. Create the public information architecture and mobile navigation.
5. Build the Open Library and rank-wise pathways using approved content only.
6. Connect YouTube, Instagram and WhatsApp records to canonical question IDs.
7. Publish editorial standards, corrections policy and privacy information.
8. Design data forms on paper first; do not activate collection until safeguards are ready.
9. Establish a reviewer workflow and content publication gate.
10. Baseline analytics and define measurable 90-day goals.

## 14. Decision rule

For every proposed feature, ask:
- Does it improve learner outcomes?
- Does it strengthen trust and content quality?
- Does it create useful, consented data?
- Does it improve discoverability or retention?
- Does it support a sustainable organisation-funded model?
- Can it be delivered without exposing or damaging protected source work?

If a feature fails these tests, defer or reject it.
