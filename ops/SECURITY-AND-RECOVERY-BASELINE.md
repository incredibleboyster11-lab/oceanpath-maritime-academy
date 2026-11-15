# OceanPath — Minimum Security & Recovery Baseline

**Created:** 15 November 2026  
**Status:** Implementation checklist; controls are not complete until evidence is recorded.

## 1. Identity and access

- [ ] Enable MFA on GitHub, primary email, domain registrar, hosting and any production vendor.
- [ ] Use unique passwords stored in a reputable password manager.
- [ ] Remove unused collaborators, tokens and app permissions.
- [ ] Use least-privilege access; do not share personal access tokens in chat, source files or screenshots.
- [ ] Prefer short-lived credentials where supported; rotate credentials after suspected exposure.
- [ ] Keep recovery codes offline in a secure location.
- [ ] Define who can publish, deploy, administer and approve content.

**Evidence:** date, account/service, control enabled, verifier (never record passwords, tokens or recovery codes).

## 2. Repository protection

- [ ] Keep source repositories read-only for OceanPath migration work.
- [ ] Use a dedicated OceanPath working branch for changes that need review.
- [ ] Protect the default branch and require reviewed changes before production.
- [ ] Review changed-file lists before every merge.
- [ ] Never commit learner personal data, credentials, API keys or private oral reports.
- [ ] Keep public derivatives and source provenance separate.
- [ ] Enable dependency/security alerts where available.

## 3. Backup policy

Back up:
- website source and configuration;
- approved public content and metadata;
- rights/provenance records;
- operational documentation and incident logs (without personal secrets).

Minimum initial policy:
- daily automated backup when production data exists;
- weekly independent copy in a separate account/provider;
- retain at least 30 daily and 12 monthly recovery points where storage and vendor policy permit;
- encrypt backups and restrict restore permissions;
- never treat GitHub as the only backup.

## 4. Restore testing

- [ ] Select a non-production test environment.
- [ ] Restore website code and public content from an independent backup.
- [ ] Verify key pages, canonical routes, assets and search.
- [ ] Record restore duration and data loss window.
- [ ] Fix failures and repeat the test.
- [ ] Target initial RPO 24 hours / RTO 24 hours, then revise based on actual service commitments.

**Restore evidence record**

| Test date | Backup source | Components restored | RPO achieved | RTO achieved | Result | Issues / corrective action |
|---|---|---|---|---|---|---|
| Not yet tested | — | — | — | — | Pending | Schedule after production storage and hosting are selected |

## 5. Incident response

1. Identify and classify the event: account compromise, malware, data exposure, outage, deletion or content tampering.
2. Contain: revoke compromised credentials, isolate affected systems and pause risky deployments.
3. Preserve evidence: logs, timestamps, affected paths and actions taken.
4. Assess affected systems and data; involve qualified security/legal support when needed.
5. Restore only from a verified clean backup.
6. Verify integrity, access controls and core user journeys.
7. Communicate accurately and make legally required notifications.
8. Record root cause, corrective actions, owner and closure date.

## 6. Privacy launch gate

Do not introduce learner accounts, payment, personal-data forms, analytics identifiers or sensitive learner profiles until:
- [ ] Data inventory and purpose are documented.
- [ ] Privacy notice and consent/legal basis are reviewed.
- [ ] Retention and deletion process is tested.
- [ ] Role-based access and audit trail are implemented.
- [ ] Vendor and processor terms are reviewed.
- [ ] Incident response and breach escalation are defined.
- [ ] Legal review confirms applicable Indian privacy and consumer obligations.

## 7. Security review log

| Date | Area checked | Finding | Severity | Owner | Action due | Closure evidence |
|---|---|---|---|---|---|---|
| 15 Nov 2026 | Initial baseline | Checklist created; implementation not yet verified | Open | Unassigned | Next operations review | Evidence to be attached |
