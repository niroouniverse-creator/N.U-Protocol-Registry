# N.U Creation and Machine Validation Protocol
**Protocol ID:** NU-CREATE-MACHINE-001  
**Version:** 1.0.0  
**Status:** PUBLIC DEVELOPMENT STANDARD

## 1. Purpose
Define a repeatable, tool-independent route from a creative seed to an N.U-standard candidate work. The seed may be a word, question, feeling, image, sketch, scene, observation, research lead, or practical problem.

## 2. Production path
`SEED → BRIEF → SOURCE CHECK → CREATION → SELF-CHECK → MACHINE VALIDATION → RESULT RECORD`

Human review and public release are separate decisions. They do not become part of a machine score.

## 3. Creator brief
Record, where relevant:
- Seed ID and original seed wording or media.
- Working title and intended work type.
- Intended audience, purpose, language, and medium.
- Creator's intended effect or practical use.
- N.U public sources consulted.
- External evidence needed and retrieved.
- Assumptions, unknowns, rights/privacy concerns, and conflicts.
- Version and current status.

A small creative work may use a short brief. Do not create unnecessary paperwork for a simple sketch, note, or short text.

## 4. Create for the actual medium
The model or creator should apply the relevant quality criteria:
- Text/article/story: clear purpose, coherent structure, readable language, accurate claims, sources, continuity, and meaningful links.
- Illustration/design: legible composition, correct text, visual consistency, source and asset provenance, and suitable output dimensions.
- Comic/film/animation: scene and character continuity, timing, readability, sound/subtitle needs, and asset rights.
- Product/stationery: real use case, dimensions/material assumptions, functional requirements, prototype and safety checks where relevant.
- Software/interactive work: input/output definition, dependencies, security/privacy, error handling, accessibility, and tests actually run.
- Research/educational work: source quality, method, limitations, evidence, and separation of fact from interpretation.

## 5. Machine validation
The machine checks only criteria it can actually inspect:
1. Required sections and deliverable files exist.
2. The declared manifest and stable identifiers are present where required.
3. Public source links and internal references resolve when tested.
4. Claims are labelled and important factual claims have traceable evidence.
5. N.U terminology and known boundaries are followed or flagged.
6. Contradictions, duplicates, and uncertainty are visible rather than silently erased.
7. Rights, privacy, safety, and attribution questions are surfaced.
8. Medium-specific requirements and declared technical tests are checked where tools permit.
9. The result states what was tested, what failed, and what remains untested.
10. The output has an appropriate destination category.

## 6. Validation result
- `PASS`: all applicable declared machine-checkable requirements passed.
- `PASS_WITH_LIMITATIONS`: checks passed but meaningful limitations remain.
- `FAIL`: at least one required machine-checkable requirement failed.
- `BLOCKED`: required input, source, permission, or tool is unavailable.
- `NOT_TESTED`: no evidence that the check was run.

Every result must include the version checked, date, checks performed, evidence, limitations, and validator/tool identity where available.

## 7. What machine validation does not mean
A machine result does not establish:
- Final quality or artistic merit.
- Authorship, ownership, copyright permission, or licensing.
- Scientific truth or professional certification.
- Canon status or a change to N.U foundations.
- Producer approval or consent to publish.
- Final N.U team approval, endorsement, or official publication.

A creator may use a machine-validated result as a quality-checked candidate. They remain responsible for deciding whether to publish independently or seek the separate human review route.

## 8. Minimum validation record
```yaml
standard_id: NU-CREATE-MACHINE-001
deliverable_id: NU-WORK-YYYY-NNNN
title: "Working title"
version: "0.1.0"
work_type: ARTICLE | STORY | IMAGE | COMIC | PRODUCT | SOFTWARE | OTHER
language: "en"
status: MACHINE_VALIDATION_PENDING
sources: []
claim_labels: []
validation:
  overall: NOT_TESTED
  checked_at: null
  checks: []
  limitations: []
human_decisions:
  producer: NOT_RECORDED
  nu_team: NOT_RECORDED
publication:
  state: NOT_PUBLISHED
  public_url: null
destination_basket: NOT_ASSIGNED
```

## 9. Next destination
After machine validation:
- SEO/article candidate → creator's own review; after publication, the [Media Publications Board](https://github.com/niroouniverse-creator/NU-PUBLIC-BULLETINS/blob/main/boards/media-publications.md).
- Independent story or artwork → creator's own publication choice; if publicly released and the creator wants discovery, the [Independent Stories Board](https://github.com/niroouniverse-creator/NU-PUBLIC-BULLETINS/blob/main/boards/independent-stories.md).
- Public N.U reference or standard → [N.U Public References](https://github.com/niroouniverse-creator/NU-PUBLIC-BULLETINS/blob/main/boards/nu-public-references.md), only after its public status and source are verified.
- General decision or process notice → [N.U Public Announcements](https://github.com/niroouniverse-creator/NU-PUBLIC-BULLETINS/blob/main/boards/announcements.md).

## 10. Related protocol
See [N.U Public Model Entry Point](NU-PUBLIC-MODEL-ENTRYPOINT.md), [SEO and Media Publication Protocol](NU-SEO-AND-MEDIA-PUBLICATION.md), and [Creator Review and Recognition](NU-CREATOR-STATUS-AND-RECOGNITION.md).
