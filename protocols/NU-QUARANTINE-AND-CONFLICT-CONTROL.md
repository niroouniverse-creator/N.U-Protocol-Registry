# N.U Quarantine, Archive Identity and Conflict-Control Protocol
**Protocol ID:** NU-QUARANTINE-001  
**Version:** 1.0.0  
**Status:** PUBLIC DEVELOPMENT STANDARD  
**Audience:** AI models, creators, archive operators, researchers, and reviewers.

## 1. Purpose
Protect source integrity, prevent accidental approval or Canon promotion, preserve useful ideas, and make every archived item identifiable and retrievable with a clear reason for its status.

Quarantine is a controlled holding state, not a rejection label. A small or unfinished idea may be worth preserving even when it is not ready for execution.

## 2. Default rule
Unclassified, uncertain, conflicting, rights-unclear, privacy-sensitive, security-sensitive, or provenance-deficient material must not be treated as verified knowledge or published N.U reference material.

If the model or creator does not have authorized access to the private N.U archive, it must not claim to have quarantined or registered the item there. Preserve a local note or handoff description and mark the private archive action as BLOCKED_PENDING_AUTHORIZED_INTAKE.

## 3. Required intake sequence
`RECEIVED → PRESERVED_OR_LINKED → IDENTITY_CHECK → RIGHTS_PRIVACY_SECURITY_CHECK → DEDUPLICATION → CONFLICT_CHECK → SOURCE_REVIEW → CLASSIFICATION → HUMAN_REVIEW_IF_REQUIRED → ROUTING → DESTINATION_VERIFICATION → CLOSEOUT`

Exception states include:
- `QUARANTINED`
- `NEEDS_HUMAN_REVIEW`
- `CONFLICT_PENDING`
- `BLOCKED_DESTINATION`
- `RESTRICTED`
- `REJECTED`

Never advance an item merely because a model generated a confident summary.

## 4. Stable identity and archive reason
Every official archived item must have a permanent, non-recycled identifier assigned by the authorized archive process. Common N.U identifiers include:
- `ARC-YYYY-NNNN`: received source or distinct version.
- `DUP-YYYY-NNNN`: duplicate or similarity case.
- `CON-YYYY-NNNN`: contradiction case.
- `FUTURE-YYYY-NNN`: deferred idea or future-project record.
- `TOPIC-<slug>`: normalized topic group.

Do not invent an official ID when you cannot write to the authoritative archive. Use a clearly labelled temporary reference until the archive assigns one.

Each archived file must state **why it is being kept and why it is not currently operational**, when applicable. Required record information:
1. Stable ID and project.
2. Original source, locator, and date received.
3. Exact title and content type.
4. Classification and current status.
5. **Archive reason / retention rationale.**
6. **Why parked, quarantined, or awaiting review.**
7. Original wording or a faithful permitted extract.
8. Context, scope, version, and source authority.
9. Related records, duplicate links, and conflict links.
10. Missing information, risks, dependencies, and next action.
11. Destination and retrieval links.
12. Append-only status history, actor, date, reason, and evidence.

The index is for discovery; the individual record explains the item. Do not use an unexplained filename as the only reason for retention.

## 5. Duplicate and similarity handling
Check exact source identity, version, canonical URL, aliases, and content hash where available before semantic comparison.

- **Exact duplicate:** link to the existing record; do not create a redundant raw copy.
- **Compatible overlap:** create one normalized topic view, but preserve every original source record and provenance.
- **Uncertain similarity:** keep records separate and request human review.
- **Different scope, time, version, project, or proposition:** do not merge merely because the keywords match.

A normalized summary never replaces the original records.

## 6. Contradiction handling
A contradiction exists only when two claims are materially incompatible about the same subject, property, scope, conditions, and time/version context.

When a material conflict is found:
1. Preserve both original claims and their source locators.
2. Assign or request a stable CON case ID through the authorized archive.
3. Link both source/archive records to the conflict case.
4. State the exact disputed proposition and why the claims cannot both be true in the stated scope.
5. Mark the case `CONFLICT_PENDING`.
6. Keep both claims visible and unmerged.
7. Route the case to an authorized reviewer.
8. Record a resolution only after a documented decision with authority, evidence, counter-evidence, scope, rationale, and date.

Do not resolve by recency, repetition, popularity, majority vote, AI confidence, or silence. A later statement may be a correction or a time-based change; compare versions and context before calling it a contradiction.

## 7. Deferred ideas and future projects
A deferred idea is not a failed idea. Keep it under a stable FUTURE ID with:
- Original idea and source.
- Reason for preserving it.
- Why it is parked rather than active.
- Feasibility label and evidence.
- Dependencies, permissions, risks, and missing decisions.
- Next decision required.
- Status history.

Suggested statuses: `PARKED`, `REVIEW_REQUESTED`, `FEASIBILITY_CHECKED`, `READY_FOR_DECISION`, `APPROVED_FOR_EXECUTION`, `IN_PROGRESS`, `BLOCKED`, `COMPLETED`, `REJECTED`, `SUPERSEDED`.

Feasibility is not authorization. Execution begins only after the required human approval for the defined scope.

## 8. Privacy, rights and public boundaries
Keep raw intake, private drafts, credentials, personal/sensitive data, confidential lore, restricted source captures, and unresolved sensitive material in authorized private storage only.

Public boards may contain safe metadata and original public links after the relevant checks. Do not publish private review notes or full copyrighted works without permission.

## 9. Automation and human authority
This protocol describes required behavior; it does not claim that a crawler, classifier, malware scanner, synchronization service, scheduled review, or approval workflow is deployed.

Models may identify risks, compare records, draft summaries, and recommend routes. Models cannot grant rights, confirm identity or consent, approve Canon, authorize official publication, or override human decisions.

## 10. Related public protocols and status boards
- [Public Model Entry Point](NU-PUBLIC-MODEL-ENTRYPOINT.md)
- [Creation and Machine Validation](NU-CREATION-AND-MACHINE-VALIDATION.md)
- [Creator Review and Recognition](NU-CREATOR-STATUS-AND-RECOGNITION.md)
- [Public Announcement and Routing](NU-PUBLIC-ANNOUNCEMENT-ROUTING.md)
- [N.U Public Announcements](https://github.com/niroouniverse-creator/NU-PUBLIC-BULLETINS/blob/main/boards/announcements.md)

**Persian:** هر مورد آرشیوی باید شناسه ثابت، دلیل نگهداری، علت توقف یا قرنطینه، منبع، وضعیت و مسیر بازیابی داشته باشد. تناقض‌ها حذف یا حدس‌زده حل نمی‌شوند؛ با شناسه مستقل به صف بررسی برمی‌گردند.
