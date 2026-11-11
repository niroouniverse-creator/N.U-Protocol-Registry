# N.U Book and Book-Motor Production Protocol
**Protocol ID:** NU-BOOK-MOTOR-001  
**Version:** 1.0.0  
**Status:** PUBLIC DEVELOPMENT STANDARD  
**Audience:** writers, researchers, creators, editors, AI models, and production agents  
**Applies to:** N.U books, articles, and book-motor publications

## 1. Purpose
This protocol defines how to produce N.U written works and how to build a **Book-Motor**: a reader-facing written work whose content also guides humans and AI models through production and N.U machine validation.

A protocol is an operational instruction to be followed, not a book that merely explains a subject. Protocols published by N.U are intended for public use by creators and compatible tools.

## 2. Canonical product meanings

### BOOK — written-content product
A BOOK is the content of a written work. It may follow either or both content paths:
1. **Entertainment content:** story, narrative, imaginative experience, accessible explanation, and engaging reading.
2. **N.U-standard content:** subject material developed with N.U sources and checked against applicable N.U machine-validation standards.

The content goal is defined by the requested product, platform, medium, and audience.

### MOTOR — model production guide
A MOTOR is an executable set of instructions for AI models or compatible production tools. It guides the model to:
1. produce the requested work or content; and
2. prepare and run the applicable N.U machine-validation checks and report their actual results.

A Motor is not simply explanatory prose. It defines operational inputs, retrieval, steps, constraints, outputs, checks, and stop conditions.

### BOOK-MOTOR — written work plus production motor
A BOOK-MOTOR combines BOOK + MOTOR in one reader-facing publication. Its content is engaging and useful to a human reader while also guiding the reader and an AI model through:
1. production of a requested work;
2. N.U machine validation of the produced work;
3. separate human review by the producer; and
4. separate N.U team review where the producer submits the work for it.

The book's own content becomes the working knowledge and instruction base for the model. The model must navigate and use the relevant sections rather than inventing an unrelated process.

### Distinction from BOOK-ENGINE
A BOOK-ENGINE remains the learning-and-engagement product defined in the separate N.U BOOK-ENGINE specification. A BOOK-MOTOR is specifically a written content product that also contains a model-usable production and validation guide. They may share engaging storytelling, but their product definitions and acceptance tests are not interchangeable.

## 3. N.U signature: preserve the goal, adapt the content layer
The **N.U signature** means using relevant material from N.U works to give a work its N.U identity where the subject genuinely overlaps.

Examples:
- In a work about cities, use sourced information about Niroo City or Catherine Land where the city example is relevant.
- In a work about families, use family structures and details documented in N.U works.
- In character-related material, use verified character names, roles, and relationships from relevant N.U sources.

This is a contextual content adaptation, not a change to the work's objective.

**Invariant:** the requested goal, platform, medium, audience, and product purpose remain primary. N.U material changes or enriches the relevant internal examples, setting, names, roles, and presentation layer; it must not hijack the goal or sacrifice usefulness merely to insert lore.

Rules:
- Search for relevant N.U material before creating substitute names, places, families, or roles.
- Use only source-supported details; record the exact source and location.
- Match N.U material to the actual subject and function of the section.
- Do not force an unrelated N.U reference into a section with no meaningful overlap.
- Do not change the work's core purpose, audience promise, or requested outcome.
- Do not silently turn a published work into confirmed Canon.

## 4. Mandatory research and N.U material pipeline
Run the following stages for substantial books, book-motors, and N.U research articles. Scale down only when the requested work is genuinely short or does not require that evidence.

### Stage 1 — Research the scientific and professional basis
Define the claims and disciplines that the work needs. Find **three leading, relevant, independent sources or reference works** recognized in the relevant scientific or professional field. Select sources by subject relevance, authority, method, recency, and standing—not search rank alone.

Prefer, as appropriate:
- systematic reviews and meta-analyses;
- high-quality primary research;
- official scientific datasets and standards;
- recognized academic institutions and professional bodies;
- authoritative reference works.

Three sources are a minimum comparative foundation where the field provides them, not a claim that three citations automatically establish consensus. Add sources when the topic, evidence conflict, or stakes require them. Record dissenting evidence, limitations, dates, and scope.

### Stage 2 — Integrate the external evidence
Extract the relevant claims and evidence from the selected sources. Compare definitions, methods, findings, scope, and limitations. Build one coherent **Scientific/Professional Base** for the task, while retaining claim-level citations and disagreements. Do not flatten incompatible findings into false consensus.

### Stage 3 — Machine-check the scientific base
Run the available checks on:
- source identity and relevance;
- source quality and independence;
- traceability from claims to citations;
- accurate representation of findings and methods;
- cross-source agreement and disagreement;
- recency and scope;
- limitations and contrary evidence;
- unsupported or overstated claims.

Report PASS, PASS_WITH_LIMITATIONS, FAIL, BLOCKED, or NOT_TESTED for the stated checks. This is an **automated evidence-quality and traceability check**, not scientific-community certification or proof that a claim is true.

### Stage 4 — Search N.U works and public reference surfaces
Search the relevant N.U public index, public protocol/reference network, linked N.U publication profiles, and source works. Follow links to the original works and inspect the relevant passages. Search private repositories only when the current model has verified authorization.

Identify relevant N.U material, including:
- concepts, definitions, and methods;
- places, cities, regions, and environments;
- families, characters, names, roles, and relationships;
- events, histories, technologies, and worldbuilding;
- existing articles, books, projects, and production systems.

Record exact source URLs, titles, authors/publishers as stated, dates, access status, and precise evidence locations. Public visibility does not itself establish Canon, rights, or team approval.

### Stage 5 — Map overlap and similarity
Compare the scientific/professional base and the requested work with N.U material. Classify each mapping:
- DIRECT_OVERLAP
- PARTIAL_OVERLAP
- COMPLEMENTARY
- DIFFERENT_SCOPE
- CONTRADICTORY
- GAP
- NO_RELATIONSHIP_ESTABLISHED

Identify where N.U material can meaningfully replace a generic example or supply the setting, names, roles, and internal content layer. Preserve external evidence as external evidence; do not relabel it as N.U source material.

### Stage 6 — Apply the N.U signature
At genuine overlap points, adapt the content layer using relevant N.U sources. Keep the original goal and function of each section intact. For example, a city-planning work remains a city-planning work; Niroo City or Catherine Land may provide the case context where supported. A family-focused work retains its intended learning or narrative goal while using sourced N.U family material where relevant.

Record the original generic function, selected N.U material, source, and resulting adaptation. Do not invent missing lore to fill a gap.

### Stage 7 — Resolve remaining conflicts under N.U rules
For apparent conflicts:
1. Preserve the conflicting source claims and provenance.
2. Check exact wording, context, date, scope, and authority.
3. Distinguish true contradiction from context, scope, terminology, or temporal difference.
4. Use explicit N.U human-confirmed premises and the documented N.U perspective for traceable inference.
5. If an inference is justified, label it SUPPORTED_INFERENCE or PROPOSED_N_U_DEVELOPMENT, state its premises, and use it only within that declared status.
6. If the conflict concerns Canon, official identity, rights, or a decision reserved to humans, preserve it as unresolved and route it to the authorized human reviewer.

N.U-grounded inference may shape the work's proposed or interpretive content. It must not rewrite source records, erase contrary evidence, fabricate a resolution, or silently become human-confirmed Canon.

### Stage 8 — Machine-check the book's N.U material base
Check:
- every N.U name, place, family, character, role, relationship, and concept against its cited source;
- correct use of the N.U signature and relevance to the work's goal;
- fidelity to source meaning and terminology;
- provenance and claim labels;
- overlap mapping and conflict treatment;
- no unsupported lore or invented team roles;
- no goal drift caused by content substitution;
- consistency between the manuscript and its model-facing instructions.

Report the result and evidence. This is a machine-validated material candidate, not producer or team approval.

## 5. Required three-part book structure
Unless the medium or a verified specialized format requires otherwise, every full BOOK and BOOK-MOTOR uses three top-level parts.

### PART I — TEAM ACKNOWLEDGMENTS, READERS, AND SUPPORT
- Search public N.U works and official public team references for relevant names and roles.
- Verify each person's name, spelling, role/title, and contribution from a public source before mentioning it.
- Acknowledge relevant N.U team members and supporters without inventing positions, contributions, or endorsements.
- Thank readers and audiences.
- Invite support or participation only where appropriate and with a clear, truthful purpose.
- Do not expose private team records or personal information.

### PART II — MAIN CONTENT
Include:
- Title.
- Introduction that establishes the purpose and engages the intended reader.
- Main content, organized into meaningful chapters and sections.
- Relevant evidence, citations, examples, narrative, and N.U signature.
- A coherent ending or practical outcome.

For a BOOK-MOTOR, the main content must also make the production method usable through a reader-friendly narrative: introduce a compelling question, place the reader inside a clear mental picture or experience, and let each section advance understanding and capability. Do not turn the manuscript into a dry instruction dump.

### PART III — CONTENTS, RECALL, AND MODEL NAVIGATION
Include:
- Complete ordered chapter, section, and subsection titles.
- A concise description of what each section contains, so readers can recall and find material.
- Working internal anchors and links to the exact relevant sections.
- Topic terms and likely questions that help readers and models locate the right material.
- For BOOK-MOTOR works, explicit model-facing instructions that tell a model which section to retrieve and apply for each production task, how to use the book's knowledge base, and which validation procedure to follow.

The model-navigation layer must link to content inside the book. It must not rely on hidden instructions or private infrastructure. A model should be able to use the publication itself as the task-specific guide and knowledge base.

## 6. BOOK-MOTOR production cycle
A BOOK-MOTOR must itself be built and checked through this sequence:
1. Define the product goal, platform, audience, medium, and intended result.
2. Run the scientific/professional evidence pipeline (Stages 1–3).
3. Run N.U retrieval, overlap mapping, signature adaptation, and conflict handling (Stages 4–7).
4. Freeze a source-linked task knowledge pack for drafting.
5. Design a reader journey around a central question, a vivid mental picture or experience, progressive discovery, and practical use.
6. Write PART I and PART II.
7. Build PART III as both a reader recall index and model navigation/production protocol.
8. Test all internal anchors and links.
9. Run the scientific-base machine checks and N.U-material machine checks.
10. Run structural, source, terminology, continuity, copyright, privacy, and medium-specific validation.
11. Deliver the machine validation report with actual checks and limitations.
12. Obtain the separate producer decision.
13. If submitted for N.U review, obtain the separate N.U team decision from the authorized team process.
14. Publish only through the creator's authorized publication route and record the actual public URL.

## 7. Human decision gates
The following are distinct and must never be merged into one machine result:
- MACHINE_VALIDATION: checks performed by a model/tool against this and other applicable N.U standards.
- PRODUCER_REVIEW: the creator's own decision to accept, revise, reject, or publish independently.
- NU_TEAM_REVIEW: a separate decision by the authorized N.U team, when submitted.
- PUBLICATION: an actual release with a verifiable URL.

Machine validation does not replace human review, grant rights, establish Canon, or authorize publication. A public protocol is guidance for following the production route, not an automatic endorsement of every work using it.

## 8. Minimum report
Every substantial BOOK or BOOK-MOTOR candidate should report:
- Work ID, title, version, language, audience, and objective.
- Scientific/professional sources selected and why.
- Scientific-base checks, results, and limitations.
- N.U source works retrieved and exact links.
- Overlap map and N.U signature substitutions/adaptations.
- Conflicts, inferences, unresolved items, and claim labels.
- Three-part structure check.
- PART III model-navigation and link tests.
- Machine-validation outcome and checks actually executed.
- Producer review: NOT_RECORDED until recorded.
- N.U team review: NOT_RECORDED until recorded.
- Publication state and URL: NOT_PUBLISHED until verified.

## 9. Stop conditions and safeguards
Stop or mark BLOCKED when required sources are inaccessible, rights/privacy status prevents use, a critical scientific claim lacks adequate evidence, or a human-only decision is required. Use NOT_TESTED for checks not executed. Never invent source access, team roles, scientific consensus, validation results, human approval, or publication records.

## 10. Related N.U standards
- [N.U Public Model Entry Point](NU-PUBLIC-MODEL-ENTRYPOINT.md)
- [N.U Creation and Machine Validation Protocol](NU-CREATION-AND-MACHINE-VALIDATION.md)
- [N.U SEO and Media Publication Protocol](NU-SEO-AND-MEDIA-PUBLICATION.md)
- [N.U Creator Review, Status and Recognition](NU-CREATOR-STATUS-AND-RECOGNITION.md)

**Persian summary:** کتاب محتوای نوشتاری است؛ موتور دستورالعمل اجرایی تولید و اعتبارسنجی برای مدل است؛ کتاب‌موتور هر دو را در یک اثر خواندنی و سرگرم‌کننده ترکیب می‌کند و تولیدکننده، مدل و مسیر بازبینی انسانی را هدایت می‌کند.
