---
title: Author and Editor Guide
created: 2026-07-17
updated: 2026-09-08
version: "1.0"
tags:
  - WinWin-Skybroad
  - ai-blind-spot
  - authoring
  - editing
  - maintenance
status: active
type: reference
source-role: master
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Author and Editor Guide

## 1. Purpose and Scope

Use this page when **authoring, editing, customising, localising, reviewing, validating, publishing, or maintaining** the Win.Win AI Blind Spot Guide. It is the package-level authoring authority for structure, terminology, control strength, file roles, cross-references, localisation, validation, maintenance, and change reporting.

In this Author and Editor Guide, the **Win.Win AI Blind Spot Guide (BSG)** and **Win.Win AI Use Case Guide (UCG)** may be abbreviated as **BSG** and **UCG** after these definitions. BSG and UCG are used only for authoring, maintenance, review, validation, and evidence work. Do not assume that a reader-facing file has defined or should use either abbreviation.

This guide is for Win.Win maintainers, organisations adapting BSG, authors and editors, reviewers and specialists, translators and bilingual reviewers, and AI assistants supporting controlled work.

Its scope is the governance and maintenance of this guide’s content. It does not replace the reader-facing operating guidance in [[How To Use This Guide]], the scope statement in [[Guide Scope And Positioning]], the canonical terminology in [[Glossary]], or the task-level specialist processes that this guide may require readers to use.

The named audience for BSG is individuals, churches, nonprofits, and small and medium-sized enterprises (SMEs). Other readers may adapt it to their context without weakening mandatory controls.

---

### 1.1 Purpose Fidelity and Reader Outcomes

Win.Win AI Blind Spot Guide helps readers recognise where AI-supported output may look clear, complete, balanced, or confident while AI cannot reliably see, retain, judge, verify, authorise, or be accountable for something a responsible person must address.

AI Blind Spot is broader than unstated context. This guide’s broad model includes task-basis gaps and wider boundaries involving lived or local understanding, judgement, authority, accountability, independent verification, recipient impact, professional instinct, operational memory, consequence awareness, or another matter AI cannot reliably hold.

The current detailed focus of the Win.Win AI Blind Spot Guide is identifying and eliciting unstated context.

Supporting guidance on retrieving and extracting approved sources, representability, safe conversion, human-only handling, verification, accountable or specialist review, stopping, and escalation helps readers act after context is identified or surfaced. Do not describe that supporting guidance as a co-equal detailed module.

This guide treats elicitation, retrieval, extraction, safe handling, review, verification, routing, stopping, escalation, and optional preservation as related but **architecturally distinct functions**. Depending on context, an item may be a canonical Control, a canonical Method, an action within a Control, a handling decision, a review activity, an Accountable Route, an escalation action, or a preservation decision. Do not call every risk-reduction activity a Control. One broad question, a complete source packet, or a detailed prompt cannot replace authority, independent verification, qualified judgement, accountable review, escalation, or stop rules.

When reviewing whether BSG fulfils its purpose, check whether readers can:
- recognise the relevant blind spot;
- identify the problem a responsible person must solve;
- locate or elicit suitable context when appropriate;
- choose a safe current-task route;
- involve a reviewer with suitable standing; and
- stop or escalate when the issue cannot be resolved safely.

> [!important] Owner purpose and intended reader outcome
> Reader-facing BSG content is designed for general adults across roughly ages 20–80 who are familiar with using generative AI (GenAI) but may not know AI-governance terminology and may tend to trust fluent, polished, or confident AI output.
>
> Design this guide so that, after using it, a reader is more likely to remember the core **AI Blind Spot** idea, recognise important AI Blind Spot risk patterns, and remember at least one relevant mitigation route such as a Control, Method, Accountable Route, or detailed guidance. If the reader later cannot remember the exact risk name or solution, the minimum intended outcome is that they recognise **“this may be an AI Blind Spot”** and know that the **Win.Win AI Blind Spot Guide** is a place to return for more information and practical mitigation guidance.

Use these owner-purpose acceptance criteria when authoring or reviewing reader-facing content:

1. **Terminology consistency** — use one stable controlled name for the same concept so readers can recognise it again. Plain-language orientation may explain a controlled term, but must not create a competing name.
2. **General-adult comprehension** — a general GenAI user should be able to understand the key message and next action without first studying the Glossary. Introduce unfamiliar controlled terminology with a short point-of-use cue where needed.
3. **Awareness plus mitigation** — every canonical AI Blind Spot risk must help the reader understand what may go wrong, why it matters, and what to do next. If detailed mitigation guidance is not provided, name at least a relevant Control, Method, Accountable Route, or other approved route to continue.

Treat reader recognition and recall as design goals, not guarantees. Do not claim that this guide can ensure what a reader will remember.

#### Fresh-reader clarity and translation robustness

For every non-README reader-facing page, preserve the original substantive intent but present it so a fresh reader can understand the action without decoding complex English sentence structure.

Use these defaults:
- name the actor when it may be unclear who should act;
- use **if** or **when** for conditions; reserve **where** mainly for location or an explicit place/source question;
- do not use bare `Ask:`, `ask what`, `ask whether`, or similar wording unless the person or system being asked is explicit;
- start action instructions with a clear verb such as **identify, check, consult, retrieve, verify, route, decide, stop,** or **record**;
- separate people-held context, record-held context, AI handling, and human-only handling when they use different routes;
- use bullets for parallel options, criteria, routes, or consequences when bullets reduce cognitive load;
- use numbered steps when order matters;
- keep prose when the relationship between ideas is clearer as prose;
- do not use an unexplained name-only list when the grouping represents a meaningful relationship, selection decision, or implementation choice; briefly state **why each item is related, when it applies, or what role it plays**;
- bare lists remain acceptable for inventories, indexes, navigation aids, or other cases where the relationship itself does not need explanation;
- prefer one main action or judgement per sentence where practical; and
- avoid vague pronouns such as **this, it, they,** or **that** when the referent could be read in more than one way.

**Actor–Action–Recipient–Condition–Route discipline**

For every instruction, decision rule, review cue, or routing statement, make the operative logic recoverable from the text itself. When relevant, a fresh reader should be able to identify:

- **Actor** — who acts;
- **Action** — what they do;
- **Object or recipient** — what or whom they act on, check, consult, ask, verify, route, or review;
- **Condition** — when or if the action applies; and
- **Route** — whether the matter goes through AI, a person, an approved record, human-only handling, verification, accountable review, or escalation.

Do not rely on the author’s remembered intent to supply one of these elements. The published wording does not need to use these labels, but the logic must be recoverable without guessing.

Do not personify a concept, Control, Method, or Accountable Route as though it were the person performing a review action. Avoid wording such as `Reviewer standing asks whether...`, `Materiality asks what...`, or `Source location asks where...`. Prefer one of these forms:

- state the concept directly — for example, `Reviewer standing concerns whether...`;
- state the reviewer action — for example, `Check whether...`; or
- label a diagnostic question explicitly — for example, `Use this question: ...`.

When using **ask**, make both sides clear whenever context does not already make them unmistakable: **who asks + whom or what they ask + what information is sought**. `Ask what...` or `ask whether...` is not sufficiently clear merely because the author knows who the intended asker is.

As a review diagnostic, reduce each substantive instruction to a simple logic trace where useful:

> **If X applies → Y does Z → through route R.**

The published prose does not need to use this mechanical form. Use it to detect hidden actors, conditions, recipients, or routes before finalising the wording.

For a passage that is materially restructured — for example, prose split into bullets, conditions separated, routes reordered, or a dense sentence decomposed — record a short **logic trace** in the review evidence. The trace should show that the revised presentation preserves the original conditions, exceptions, boundaries, and required actions.

Meaning preservation is the hard boundary. Do not remove a governance distinction, condition, exception, safety boundary, authority requirement, or escalation requirement merely to shorten the text.

As a translation stress test, render changed reader-facing passages into Traditional Chinese before finalising the English. If the TC version forces the translator to guess the actor, condition, source, route, referent, or sequence, revise the English first. This TC check is a review aid; it does not replace authorised Stage 2 translation or qualified bilingual review.

As a second diagnostic, consider whether **two competent TC translators could reasonably infer different actors, recipients, conditions, route relationships, or scopes from the same English sentence**. If so, treat the English as REVIEW_REQUIRED even if both possible translations are grammatically natural. Clarify the English source rather than resolving the ambiguity silently in translation.

For a final whole-package clarity claim, review **every in-scope non-README public page**. Sampling may support an interim review, but sampling is not enough to claim whole-package fresh-reader or translation-robustness PASS. Record one page-level disposition for every in-scope page.

If the author or reviewer wrote or recently edited the page, perform a separate **clean-room fresh-reader pass**. Judge only what a reader can recover from the words, structure, links, and point-of-use cues actually present on the page. Do not fill in missing meaning from remembered author intent. Use this diagnostic question:

> **Could a fresh reader know what to notice and do from this page, or am I supplying missing meaning because I already know what the author intended?**

A page may rely on an explicitly linked authoritative definition or detailed method, but the dependency must be signposted. Do not assume that a reader has memorised another page.

As a fresh-reader test, read the page without relying on prior BSG knowledge. A general GenAI user should be able to tell:
1. what to notice;
2. what to decide;
3. what to do next; and
4. where to go if the page does not provide the full solution.

Do not judge this guide only by word count, equal section length, or the number of risks, questions, routes, templates, or supporting files.

> [!important] Customisation does not authorise weaker governance
> Do not remove or weaken required human accountability, authority boundaries, source and evidence requirements, privacy controls, professional-review requirements, escalation conditions, or stop rules merely to make a workflow easier.

---

### 1.2 Finding the Rules You Need

Most readers do not need every section for every task. Start with Sections 1–3, then use the route that matches the work.

| Your task | Main sections |
|---|---|
| Make a small wording or formatting correction | 3.2, 5, 9–11, 14, and 16–18 |
| Reorganise existing content | 3.1, 7–9, 11, and 16–18 |
| Add, remove, rename, or repurpose a file | 6–10 and 15–18 |
| Adapt BSG for an organisation | 4–5, 11, and 16–18 |
| Translate or localise content | 12–14 and 16–18 |
| Use an AI assistant | 15 and the sections relevant to the task |
| Review a package before publication | 16–18 |

Package maintainers should use the complete Author and Editor Guide. Other readers should still check Section 5 before making a change.

---

### 1.3 Terms Used in This Guide

| Term | Meaning in this guide |
|---|---|
| **Approved source version** | The exact file or package accepted as the source for the current task. |
| **Canonical** | The approved name, meaning, structure, or rule that other files should follow. |
| **Control strength** | How strict a requirement, prohibition, review, approval, stop, or escalation rule is. |
| **Control** | A canonical defined safeguard used to address one or more AI Blind Spot risks; canonical names end with `Control`. |
| **Method** | A canonical reusable way of carrying out or supporting one or more Controls; canonical names end with `Method`. |
| **Accountable Route** | A canonical path to a person, role, reviewer, owner, approved process, or escalation point with responsibility or authority to act; canonical names end with `Route`. |
| **Independent verification** | Checking a point against a sufficiently independent approved source, tool, record, or suitably accountable reviewer rather than relying only on the same output or an automatically non-independent confirmation. |
| **Material** | Important enough to affect meaning, risk, control, authority, approval, reader action, or publication. |
| **Standing** | The role, competence, authority, permission, and independence needed to perform a task or review. |
| **Substantive change** | A change to meaning, scope, risk, control, authority, approval, or reader action—not only wording or layout. |
| **Traceability** | Being able to follow a term, risk, route, control, or change from its approved source to the files that use it. |
| **Document version** | The version of one public file. |
| **Package release** | The published snapshot of the complete artefact. |

These definitions support the rules below. They do not replace the Glossary or file-specific definitions.

---

### 1.4 Current Detailed Scope and Control Architecture

The primary BSG operating sequence is:

```text
identify the Blind Spot concern
→ identify the canonical risk
→ consult the Control Map
→ select the relevant recognised Control or Controls
→ use applicable detailed guidance and Methods
→ use an Accountable Route where responsibility, authority, expertise, independence, approval, or escalation is required
```

Do not make **Unstated Context Control** the mandatory first Control for every risk. Enter its detailed sequence only if relevant context may be absent from, incomplete in, or not adequately represented in the task basis.

**Unstated Context Control** is the current detailed Control. Its most developed practical guidance concerns **identifying and safely eliciting unstated context**.

Related current-task guidance within that Control covers locating approved records, retrieving and extracting task-relevant approved material, representability, safe conversion, human-only handling, verification, accountable or specialist review, stopping, and escalation. Do not describe every part of that supporting guidance, or every other recognised Control that may use similar actions, as a co-equal detailed module.

Use this controlled definition: **unstated context** is any relevant context that is absent from, incomplete in, or not adequately represented in the task basis. The task basis includes the source packet, prompt, approved material actually used, review basis, and current decision record available for the task.

Do not define unstated context by source location. Do not use `context known by people` as a canonical category. Source location and representability must remain separate checks:

- source location: people, approved records, both, or unclear;
- representability: clearly expressible, partly expressible, difficult to articulate, unsafe or inappropriate to state, or not fully expressible for AI use.

Do not imply that all context can or should be expressed to AI. Do not imply that all reusable context belongs in a record or retrieval-augmented generation (RAG) system.

Use exactly seven minimum current-task routes where the full route list is reproduced:

1. add the approved minimum to the task basis, only where accurate, necessary, permitted, current, and safe;
2. convert only the necessary effect into a safe form: a fact or source, a constraint or wording rule, an omission or review instruction, an approval boundary or human-drafting requirement, or an escalation trigger;
3. keep the underlying context human-only and use an authorised person to guide drafting, review, approval, timing, or escalation;
4. verify it against a sufficiently independent approved source, tool, record, or suitably accountable reviewer;
5. route it to an accountable or specialist reviewer;
6. stop and escalate;
7. do not use or record it.

Preservation is a separate optional decision, not an eighth route.

The seven **minimum current-task handling routes** are handling choices within Unstated Context Control. They are not the same concept as a canonical **Accountable Route** in [[AI Blind Spot Control Map]]. A current-task handling choice may use an Accountable Route when responsibility, authority, expertise, review, approval, or escalation must move to another person or process.

Practical recognition angles for unstated context must retain their definitions, not only their labels. Source location and representability remain separate checks.

**Retrieve** means locate and bring a current approved source into the task process. **Extract** means select the task-relevant approved material from the retrieved source. **Verify** means check a claim, source, output, or decision basis against a sufficiently independent approved source, tool, record, or suitably accountable reviewer. These are distinct operations: retrieval does not mean extraction, and extraction does not mean verification.

**Elicit** means use a suitable specific, focused question or technique to help a person surface relevant context. **Classify** means assess source location, representability, reliability, sensitivity, authority, materiality, and handling implications. **Route** means send the matter through the appropriate approved path. **Review** means human examination against the task basis, intended use, risks, and controls.

An owner confirmation may support verification only where that owner has suitable knowledge, authority, accountability, and sufficient independence for the matter. A responsible owner is not automatically an independent verifier.

Organisational context handling is wider than the current detailed scope. Other recognised Controls may be defined in [[AI Blind Spot Control Map]] without being explained in detail. Do not invent an unapproved detailed framework for a Control outside this guide’s current detailed scope.

Preserve a problem-first structure for risk and control content: state the problem, how it appears, what a responsible person must solve, and which recognised Controls, Methods, or Accountable Routes may be relevant. Do not imply that one risk has only one Control.

A problem-first architecture does not authorise deletion of a risk-specific prompt-side control, limit, context-outside-AI boundary, safe-conversion instruction, or escalation trigger.

---

### 1.5 Glossary Authority

The Glossary is the controlled terminology reference for the Win.Win AI Blind Spot Guide. It defines what the architectural terms **Control**, **Method**, and **Accountable Route** mean across BSG.

The individual canonical Controls, Methods, and Accountable Routes are defined only in the corresponding registries of [[AI Blind Spot Control Map]]. Do not duplicate full individual-registry definitions in the Glossary or another file. Other files may cross-reference the canonical name and describe task-specific application without redefining it.

If the Glossary needs to mention an underlying concept that also appears inside a canonical Control, Method, or Accountable Route name, keep the distinction explicit. Use a short orientation cue plus a link to the canonical registry when a fuller Glossary entry could reasonably look like a second definition of the canonical item.

Use the exact canonical name whenever referring to a recognised Control, Method, or Accountable Route. Do not demote a canonical Control into an ordinary method or recreate a removed canonical item by descriptive relabelling. Preservation remains a separate optional governed decision under the organisation’s approved process; it is not a canonical Control, Method, Accountable Route, or eighth current-task handling route unless the owner later establishes a new canonical preservation concept.

Controlled terms must retain their Glossary meaning. Do not invent near-synonyms for stylistic variety where that would weaken or blur meaning. In newcomer-facing content, briefly explain or link a non-intuitive term on first use.

Use **AI Blind Spot risk** as the sole live controlled name for the risk category. Do not use `Blind Spot risk` as a shortened controlled alias; it is retired because two fixed names for the same architectural concept can make readers and translators infer a distinction that does not exist. Ordinary references to an AI Blind Spot or to a named canonical risk remain valid where they are not being used as the category label.

Keep these distinctions intact:

- AI Blind Spot is broader than unstated context;
- do not reduce authority, accountability, verification, impact, professional instinct, or user-pressure boundaries to missing task-basis information;
- responsible person is a general responsibility description;
- responsible owner ensures an approved route and does not absorb specialist owner roles;
- accountable reviewer is responsible for the review outcome within their standing;
- elicitation, retrieval, extraction, classification, routing, handling, review, and verification are separate actions;
- approved-record status and verification independence must remain explicit;
- source location and representability are separate;
- unstated context and implicit context are not synonyms;
- representability and reliability are not synonyms;
- review and verification are not synonyms;
- a risk and a Control are not the same thing; their relationship may be many-to-many;
- a Control and a Method are not the same thing;
- a Control and an Accountable Route are not the same thing;
- preservation, organisational memory, and RAG are not synonyms;
- role and standing terms are not interchangeable;
- canonical risk names and decision labels remain exact.

---

### 1.6 Permanent Presentation Rule

Write substantive definitions, principles, controls, examples, boundaries, roles, risks, and decision labels as durable guidance.

Do not present them as temporary release content.

The approved substantive scope-dependent statement is:

> The current detailed focus of the Win.Win AI Blind Spot Guide is identifying and eliciting unstated context.

A file may also say that a wider topic is **outside the current detailed scope** or that its full method **is not provided here**.

Do not say that separate guidance exists unless an approved public artefact exists and is linked.

Use **Win.Win AI Blind Spot Guide** where the formal artefact title is needed. The word `the` is not part of the formal title.

In running English prose, add **the** immediately before the formal title where normal grammar requires the definite article. Do not add **the** inside the formal title, filename, path, link label, table entry, source-version field, or other exact controlled name.

In ordinary reader-facing prose, use **This guide** at the beginning of a sentence and **this guide** within a sentence. Keep `guide` lower-case in ordinary prose. Do not use `The Guide`, `the Guide`, `This Guide`, `The guide`, or `the guide` as ordinary self-reference.
Apply the same self-reference rule in permanent BSG review guides, validator documentation, authoring prompts, and evidence summaries whenever they refer to Win.Win AI Blind Spot Guide itself. Retain a prohibited form only inside a protected owner-controlled baseline, an exact quotation, code, a test fixture, or an instructional example that clearly identifies the form as incorrect.

Title case remains correct in formal artefact titles and Markdown headings.

Preserve the owner-protected repository-README presentation unless the owner expressly authorises a necessary change. If an authorised correction changes protected wording, preserve the established shell, navigation function, hard-break intent, and unaffected presentation blocks, and record the exact owner-authorised reason.

Do not mechanically remove a grammatical article before a full artefact title where English grammar genuinely requires it. Proper artefact names, feedback-form names, attribution, release metadata, and version metadata remain unchanged.

During package review, scan all public English Markdown for ordinary-prose self-reference drift. Classify title and heading uses, protected repository-README wording, code or exact quotations, and ordinary prose separately. No prohibited ordinary-prose occurrence may remain.

Release and version language remains valid in frontmatter, publication and release history, translation identity, source-package control, validation, change control, and packaging guidance.

---

## 2. Who This Guide Is For

### 2.1 Win.Win Maintainers

Use this guide to preserve canonical content, maintain cross-file relationships, prepare releases, and keep approved language versions aligned.

---

### 2.2 Organisations Customising This Guide

Use this guide to adapt roles, systems, policies, terminology, review routes, blind-spot tasks, control areas, and escalation paths to the organisation’s real operating context.

---

### 2.3 Authors and Editors

Use this guide when creating new files, restructuring existing files, revising wording, adding examples, correcting Markdown and links, or preparing a release.

---

### 2.4 Reviewers and Specialists

Use this guide to understand which changes require bilingual, legal, privacy, employment, finance, cybersecurity, safeguarding, medical, psychological, counselling, pastoral, theological, technical, cultural, or other qualified review.

---

### 2.5 Translators and Bilingual Reviewers

Use this guide to preserve approved meaning, control strength, terminology, titles, structure, authority language, escalation language, and Hong Kong context when BSG translations are authorised.

During pre-publication work, the working package may temporarily be English-only. This role description does not imply that `tc_HK` or `sc_HK` editions are complete before their approved translation and review are finished. The published release must contain all three complete editions.

---

### 2.6 AI Assistants

Use this guide as operational context when supporting authoring, editing, comparison, localisation, validation, evidence preparation, or packaging. AI assistance does not replace owner or qualified-human approval.

---

## 3. Types of Change

### 3.1 Structural Change

A structural change moves, groups, splits, combines, renames, relevels, or renumbers headings and content without intending to change meaning.

Even a structural change may affect heading anchors, links, navigation, interpretation, and maintenance traceability.

---

### 3.2 Editorial Change

An editorial change improves clarity, grammar, consistency, plain language, or formatting without intending to change the control, obligation, scope, authority, risk, or decision.

---

### 3.3 Substantive Governance Change

A substantive change alters a risk meaning, control strength, approval condition, authority boundary, review obligation, escalation threshold, disclaimer, professional boundary, or organisational responsibility.

Substantive changes require explicit owner approval and any qualified review appropriate to the subject.

---

### 3.4 Organisational Customisation

Organisational customisation replaces or supplements generic content with approved local roles, systems, tools, policies, sources, terminology, controls, and escalation routes.

---

### 3.5 Localisation and Translation

Localisation and translation adapt approved content for another language folder while preserving meaning, control strength, structure, Hong Kong context, and intended reader action.

**Example:** Adapt approved English wording into natural Hong Kong Traditional Chinese while preserving the same action and control.

---

### 3.6 Packaging and Publication Change

Packaging and publication changes affect included files, folder paths, filenames, frontmatter, document versions, footer versions, release labels, indexes, release history, encoding, line endings, or archive contents.

They can break navigation or publication even where prose is unchanged.

**Example:** Add, remove, rename, version, or publish a file.

---

## 4. Customising This Guide for an Organisation

### 4.1 Define the Organisational Context

Record the organisation, intended users, sector, jurisdictions, operating environment, data types, approved AI tools, and purpose of the customised guide.

---

### 4.2 Identify Applicable Blind-Spot Tasks or Control Areas

Select blind-spot tasks, control areas, templates, and review routes that match real organisational use. Do not adopt a blind-spot control merely because it appears useful or low-risk.

---

### 4.3 Assign Roles and Authority

Replace generic roles with real organisational roles. Identify who may propose, prepare, review, correct, approve, escalate, and publish or act.

Do not use a role title as proof that the person has the necessary competence, context, source access, authority, or approved process.

---

### 4.4 Adapt Review and Approval Requirements

Specify the source or real-world reference, reviewer, timing, warning signs, decision supported, and escalation boundary for each material review check.

---

### 4.5 Adapt Risks and Controls

Retain applicable canonical risk meanings. Remove inapplicable examples, specify real task objects, add missing local risks, and preserve the minimum control obligation.

---

### 4.6 Adapt Prompt Content

Use the applicable base prompt pattern and only the prompt enhancements relevant to the task. Replace generic placeholders with approved sources, audiences, terminology, limits, authority boundaries, uncertainty markers, and output requirements.

---

### 4.7 Adapt Escalation Routes

Name the actual accountable person, role, committee, professional adviser, or stop route. Do not invent a specialist role that does not exist.

---

### 4.8 Add Organisation-Specific References

Link only approved policies, procedures, source repositories, forms, systems, and contacts. Check that each link and source version remains current.

---

### 4.9 Record Organisational Deviations

Keep the published Win.Win content distinguishable from the organisation’s approved adaptation.

Record at least:

**Source version:** Win.Win AI Blind Spot Guide [release]

**Organisation:** [name]

**Customisation owner:** [role]

**Approved by:** [role or authority]

**Approved date:** [date]

**Sections changed:** [list]

**Reason for change:** [explanation]

**Local policies or sources:** [list]

**Next review date:** [date]

**Win.Win approval:** Do not imply that organisational adaptation has been approved, endorsed, validated, or adopted by Win.Win unless the owner expressly confirms that status.

---

## 5. What Must Not Be Customised Away

### 5.1 Human Accountability

A human or accountable organisational body remains responsible for what is sent, published, approved, relied on, or acted on.

---

### 5.2 Authority Boundaries

Drafting, reviewing, correcting, approving, publishing, and acting are different authorities. Do not merge them merely because one person performs several roles.

---

### 5.3 Required Review

Do not remove a review because the task appears routine, the prompt is detailed, the AI has worked before, or the output sounds polished.

---

### 5.4 Privacy and Confidentiality

Do not weaken data minimisation, approved-tool, access, confidentiality, pastoral, HR, donor, client, beneficiary, or personal-data boundaries.

---

### 5.5 Source and Evidence Requirements

Do not replace source comparison, source checking, independent verification, or real-world confirmation with AI self-review.

A semantic report must quote or locate the content it checks. A heading, keyword, or `yes` value alone is not proof that the controlled meaning or baseline message was preserved.

---

### 5.6 Escalation and Stop Conditions

Preserve stop and escalation conditions where the reviewer lacks evidence, authority, competence, context, source access, or an approved process.

---

### 5.7 Professional and Specialist Boundaries

Do not turn AI-generated or generally reviewed content into legal, regulatory, financial, HR, medical, psychological, safeguarding, theological, technical, or other specialist approval.

---

### 5.8 Semantic Evidence and Reviewer Standing

Do not replace source-to-final semantic evidence with a heading match, keyword match, automated `yes` value, or AI summary. Quote or locate the source obligation and its final destination.

Do not treat a role title, owner confirmation, language fluency, familiarity, or AI-assisted review as proof of suitable standing. Confirm the role, competence, authority, permission, context, source access, accountability, and independence required for the task.

---

## 6. File Types and Their Roles

### 6.1 README Files

A `README` (“read me”) file introduces a package or folder and helps readers navigate it.

#### Protected README authoring boundary

The repository-level `public/README.md` is owner-controlled and permanently outside ordinary BSG author scope. A BSG author, editor, translator, AI assistant, or package-alignment task must not edit, reformat, retitle, reorder, relink, localise, or update its metadata. If a possible discrepancy or dependency is found, report it as an owner-decision item and leave the file byte-identical.

The `public/en_HK/README.md` file remains a public navigation file, but its Master Source callout is protected shared Win.Win presentation. Preserve the following two lines exactly:

```text
> [!note] Master Source:  
> This is the `en_HK` folder — the master source for the **Win.Win AI Blind Spot Guide**. All other language folders (`tc_HK/`, `sc_HK/`) are translations of this document. Content updates are made here first, then carried across to other language folders.
```

Do not rewrite this callout to describe an interim English-only working package, staged translation progress, missing folders, future approval, or another temporary condition. Record temporary package state in internal review evidence or change reporting, not in the protected public callout.

Package-wide alignment, navigation maintenance, translation work, validation findings, metadata updates, or another README rule do not create permission to change either protected README area. A proposed change must be reported to the owner rather than executed by the BSG author.

#### What README files are exempt from

Repository-level and language-folder `README.md` files do not need:

- numbered H2 or H3 headings;
- `---` section breaks before H2 or H3 headings.

Do not report either difference as a formatting or structural failure.

#### What still must be checked

README files must still be checked for:

- artefact identity, purpose, audience, working-language status, and intended trilingual publication position;
- heading hierarchy and required sections;
- protected presentation and authorised exceptions;
- navigation, indexes, and reader routes;
- duplicate headings and broken anchors;
- links, release information, licence meaning, and rendering;
- cross-language purpose parity where multilingual root descriptions are retained.

---

### 6.2 Language Folders and Source Roles

Use these controlled source roles:

- `en_HK/` — the English master source for Hong Kong;
- `tc_HK/` — the complete approved Traditional Chinese translation for Hong Kong at publication;
- `sc_HK/` — the complete approved Simplified Chinese translation for Hong Kong at publication.

A pre-publication working package may temporarily contain only `en_HK/` or partially completed translation folders. That temporary state does not authorise changing the protected Master Source callout in `en_HK/README.md`.

Do not publish BSG until all three approved language editions are complete. A language folder is complete only when every approved public file for that edition has been translated, reviewed, indexed, linked, and validated.

During staged translation work, describe incompleteness only in internal evidence, review reports, or translation tracking. Do not present an incomplete folder as a complete public edition and do not convert temporary production status into durable public README wording.

When a language edition is complete, it must be independently usable. Do not make it depend on another language folder for a public file, instruction, or link.

Author substantive changes in `en_HK` first unless the owner explicitly authorises another source.

After an English source and translation scope are approved:

- translate the approved source into the authorised target language;
- review each translation against the exact approved English source;
- preserve the same control strength and intended reader action;
- keep local filenames, links, indexes, and navigation complete;
- obtain qualified bilingual review before approval.

---

### 6.3 Reference Files

Reference files define reusable terminology, risks, control mappings, reviewer decisions, scope boundaries, or authoring rules. Repeated-entry references must define an Entry Structure Standard.

Current BSG reference files include [[How To Use This Guide]], [[Guide Scope And Positioning]], [[Glossary]], [[AI Blind Spot Risk Library]], [[AI Blind Spot Control Map]], and [[Author and Editor Guide]].

[[How To Use This Guide]] is the operating map of this guide’s files. [[Guide Scope And Positioning]] defines this guide’s scope, current detailed focus, boundaries, and positioning. [[AI Blind Spot Risk Library]] owns the authoritative canonical risk definitions. [[AI Blind Spot Control Map]] owns the canonical Controls, Methods, and Accountable Routes and the authoritative explanation of how those items relate to each canonical risk.

Within [[Glossary]], `Related terms` is a compact navigation aid rather than a formal relationship map. It may remain a name-only list when its sole purpose is to help readers find nearby concepts. Do not use it to imply formal risk-to-Control/Method/Route relationships.

---

### 6.4 Guide and Control Files

Guide and control files explain AI Blind Spot risks, Unstated Context Control, approved-source preparation, reviewer standing, elicitation techniques, context handling, preservation boundaries, and practical review decisions. They adapt canonical meanings into reusable guidance rather than replacing them.

---

### 6.5 Templates and Cards

Templates and cards provide reusable working structures for elicitation, exception recording, reviewer-standing checks, and review decisions. Keep instructional text distinguishable from content intended to be copied or completed.

A short route, card, or template must not create authority, weaken a control, bypass reviewer standing, remove a human-only boundary, or replace the full source guidance.

For [[AI Blind Spot Review Card]], keep risk recognition **scan-first**. Present the canonical risks as short, visually separated recognition cues rather than one dense prose or code block. The card may contrast easily confused risks, but it must not become a second canonical definition registry.

---

### 6.6 Translation and Localisation Notes

Translation notes preserve controlled terminology, source-language authority, target-script requirements, disclaimer boundaries, Hong Kong context, and bilingual-localisation review rules.

During an English-only pre-publication stage, translation notes describe controlled work in progress. They must not imply that translated editions are complete before approval, but the publication package must ultimately include complete `tc_HK` and `sc_HK` editions.

---

### 6.7 Author and Editor Guides

Author and Editor Guides define reusable authoring, editing, translation, adaptation, review, validation, versioning, packaging, and publication rules. Keep common rules here rather than repeating them throughout every file.

The package-extracted `public/en_HK/Author and Editor Guide.md` is the BSG authoring authority for the current package.

Do not substitute a detached copy where it differs from the package-extracted file.

For BSG work, this guide must be self-contained for applicable authoring, editing, translation, localisation, review, validation, packaging, and publication rules. When a same-topic, same-function rule from the current Win.Win AI Use Case Guide Author and Editor Guide is useful to BSG, copy or adapt that rule into this guide; do not make BSG compliance depend on consulting the Use Case Guide Author and Editor Guide.

When the underlying English rule is identical across the two guides, keep the English wording aligned and use the same approved `tc_HK` and `sc_HK` translation unless the current owner-approved terminology or localisation authority requires a different controlled form. Retain BSG-specific differences only where BSG terminology, architecture, filenames or localised folders, README mappings, reader actions, or stricter controls require them.

The approved translated Author and Editor Guides must preserve the same rule meaning, control strength, intended reader action, and approved structural alignment, subject to recorded language-specific differences and qualified bilingual review.

---

## 7. Heading Structure

### 7.1 Heading Levels and Numbering

Use one unnumbered H1 for the file title.

For non-README BSG pages, use numbered H2 and H3 headings.

Except for both README files, place `## 1. Purpose and Scope` as the first H2 immediately after the H1 when no opening body content is required. The section must first explain the **purpose, scope, and correct use of that specific file**. It may then explain relevant whole-guide concepts where needed, but it must not substitute a general explanation of BSG for the file’s own purpose.

Do not insert a thematic break between the H1 and its immediate first H2 where no body content intervenes.

Number every H2 as `1.`, `2.`, `3.` within a non-README file.

Number every H3 as `1.1`, `1.2`, `2.1` under its parent H2.

Do not number H4.

Use H4 as the normal maximum heading depth. Avoid H5.

Do not skip directly from H2 to H4. Use a numbered H3 where the content is a true subsection. Use bold labels for compact local fields that do not need navigation.

Repository-level and language-folder README files are exempt from H2 and H3 numbering.

---

### 7.2 Canonical Section Names

Use the approved heading where two sections perform the same function. Use a different heading only where the function is genuinely different.

When sections in different files serve the same purpose, use the same published heading name. Do not introduce synonyms merely for stylistic variety.

A `Purpose and Scope` section must answer what **this file** is for, when to use it, and what it does not attempt to replace. Whole-guide purpose or AI-limitation background may follow where relevant but must not be the only content of the section.

Common names include:

- `Purpose and Scope`;
- `How To Use This Reference`;
- `Entry Structure Standard`;
- `Mandatory Sections`;
- `Optional Sections`;
- `Related References`;
- `Maintenance and Change Control`;
- `How the Core Terms Fit Together`;
- `Common Confusions`;
- `Tier A — Core model terms`;
- `Tier B — Roles and standing`;
- `Tier C — Canonical risks`;
- `Tier D — Decision labels`;
- `What This Is`;
- `Risk Relationship Entry Structure Standard`;
- `Controls`;
- `Methods`;
- `Accountable Routes`;
- `Control Map`;
- `How to use this card`;
- `What unstated context means`;
- `Why direct questions often fail`;
- `What to do with surfaced context`;
- `What not to put into AI`;
- `Practical rule`;
- `What it is`;
- `How it appears`;
- `How unstated context may matter`;
- `Prompt-side control`;
- `Reviewer action`;
- `Unstated Context Control guidance`;
- `Controls to consider first`;
- `Additional Controls when relevant`;
- `Methods that may support those Controls`;
- `Accountable Routes that may be needed`;
- `Risk Relationships`;
- `Additional implementation notes`;
- `Escalate when`;
- `What to record`;
- `What not to record in ordinary notes`;
- `Signals that routing is needed`;
- `What to do instead`.

Use a different name only when the content function is materially different. Do not rename blind-spot risks, canonical Control names, canonical Method names, canonical Accountable Route names, reviewer-decision labels, or template field labels merely for style.

**Layer names**

If a Win.Win AI guide separates directly usable material from deeper explanation, use:

- **Practical Layer** — files used directly during a real task or review;
- **Reference Layer** — files used for deeper explanation, consistent methods, training, adaptation, or maintenance.

Use these names across guides where the functions are equivalent.

For Author and Editor Guides, use these shared H2 names where the purposes are equivalent:

- `Purpose and Scope`;
- `Who This Guide Is For`;
- `Types of Change`;
- `What Must Not Be Customised Away`;
- `File Types and Their Roles`;
- `Heading Structure`;
- `Entry Structure Standards`;
- `Cross-References and Traceability`;
- `Headings, Bold Labels, and Callouts`;
- `Writing and Plain-Language Rules`;
- `Translation and Localisation Rules`;
- `Chinese Markdown Rules`;
- `Markdown and GitHub Formatting Rules`;
- `Using AI Assistants for Authoring and Editing`;
- `Pre-Publication Review and Validation`;
- `Maintenance and Change Control`;
- `Change Reporting`.

---

### 7.3 Headings Versus Bold Labels

Use a heading where the content forms a genuine section or subsection.

Under an H3, use an unnumbered H4 where readers may need to:

- find the content through navigation or a table of contents;
- link directly to it;
- review or maintain it separately;
- distinguish it from parallel rules or process stages;
- read several paragraphs, a substantial list or table, or a distinct procedure beneath it.

Use a bold label where the content is a compact local part of the current section, such as:

- a short field or category;
- an example;
- a `Use` or `Avoid` label;
- a checklist group;
- a report group;
- a brief label introducing one paragraph or list;
- an author action, review check, or evidence label that does not need separate navigation.

Use this practical test:

```text
Could a reader reasonably ask to go directly to this part?
→ use a heading

Does it only introduce a short part of the current section?
→ use a bold label
```

A heading normally introduces content with its own purpose. A bold label normally introduces content that remains part of the purpose of the current heading.

Length alone does not decide the structure. A bold-labelled block containing several paragraphs, a substantial list or table, a distinct rule or process stage, or independently maintained guidance should normally become an H4.

Do not use a bold label merely to avoid an H4 where the content functions as a genuine subsection.

Do not use an H4 only for visual emphasis where a short bold label is enough.

Items that perform the same function at the same structural level should use the same treatment. Do not mix headings and bold labels among parallel items unless their functions are genuinely different.

---

### 7.4 Repeated-Entry Collections

Group repeated entries under one numbered collection heading such as `Risks`, `Controls`, `Methods`, `Accountable Routes`, `Reviewer Decisions`, `Checklist Items`, `Questions`, `Templates`, or `Risk Families`.

Use numbered H3 for each named entry and unnumbered H4 for the entry’s standard sections.

Use a stable structure for equivalent entries. Do not allow equivalent entries to drift into different structures without a reason.

---

## 8. Entry Structure Standards

### 8.1 Purpose

An Entry Structure Standard tells readers and editors what each repeated entry should contain, what is mandatory, what is optional, and which short fields remain bold key-value pairs.

---

### 8.2 Mandatory Sections

Include every mandatory section in each new entry. Do not leave mandatory headings empty.

---

### 8.3 Optional Sections

Include an optional section only when it contains useful content. Do not add empty headings merely to make entries visually identical.

If an Entry Structure Standard teaches what optional subsections mean, define each subsection through an H4 heading and explanatory prose. A bullet list may summarise available subsection names, but it must not replace the definitions.

---

### 8.4 File-Specific Standards

#### Existing collections

Follow the Entry Structure Standard in the relevant file. A risk entry, Control Map risk-relationship entry, review-card item, glossary entry, elicitation question, template field, reviewer-standing check, and decision label do not have identical functions and may require different mandatory sections.

Preserve an existing repeated-entry pattern unless the owner approves a structural change.

For [[AI Blind Spot Control Map]]:

- keep one `Registry Entry Structure Standard` governing the repeated entries in `Controls`, `Methods`, and `Accountable Routes`;
- define every canonical Control in the `Controls` registry; canonical names end with `Control`;
- require each Control entry to state its definition, control objective, boundary, guidance availability, and relevant canonical Methods where meaningful; for each relevant Method, explain briefly **how it helps carry out or support that Control** rather than using a bare name list;
- define every canonical Method in the `Methods` registry; canonical names end with `Method`;
- require each Method entry to state its definition, purpose, supported Controls, use condition where needed, boundary, and detailed-guidance location or availability; for each supported Control or clearly related group of Controls, explain briefly **what the Method contributes** rather than using a bare name list;
- define every canonical Accountable Route in the `Accountable Routes` registry; canonical names end with `Route`;
- require each Accountable Route entry to state its definition, use condition, accountability destination, responsibility/authority/expertise function, and boundary;
- do not mechanically add empty registry fields for visual symmetry; a genuine exception requires an owner-approved reason;
- use the separate `Risk Relationship Entry Structure Standard` to govern the risk-relationship entries;
- use one risk-relationship entry for each canonical risk and preserve the exact Risk Library risk name;
- explain **why** each named Control, Method, or Accountable Route is relevant to that risk instead of presenting an unexplained flat list;
- make the risk-relationship section directly reachable from the Control Map Purpose and Scope so readers do not have to read the canonical registries before using the map;
- distinguish the Control or Controls that address the risk most directly from additional Controls that apply only under stated conditions;
- present Methods as ways to carry out or support relevant Controls, not as equal alternatives to Control selection;
- present Accountable Routes as routes used when responsibility, authority, expertise, review, approval, or escalation must move elsewhere;
- keep the Risk Library focused on risk meaning and reviewer action; do not duplicate the full risk-to-Control/Method/Route relationship list in each Risk Library entry;
- include Unstated Context Control where relevant rather than treating it as an invisible default;
- do not invent a Control, Method, or Accountable Route merely to complete a relationship entry;
- do not imply that a listed element is absent, not already applied, or always additionally required;
- do not make the current detailed scope determine the long-term control architecture;
- keep risk → Control selection before any Control-specific Method in reader-facing operating flows.

For [[AI Blind Spot Risk Library]]:

- keep the page as the sole canonical risk-definition registry;
- keep each risk focused on what the risk is, how it appears, how unstated context may matter, what a responsible person must solve, and reviewer action;
- do **not** repeat an exhaustive `Related controls, methods and accountable routes` field inside every risk entry;
- rely on the page-level Purpose and Scope to direct readers to the Control Map rather than adding the same navigation sentence after every risk; and
- keep `Additional implementation notes` optional rather than routine: retain it only when it adds a distinct risk-specific practical lesson that would otherwise be lost;
- do not use `Additional implementation notes` as a miscellaneous list of related Controls, Methods, Accountable Routes, reviewers, owners, documents, or processes; the Control Map owns relationship mapping;
- if an implementation note is retained, explain **why it matters** and **what the reader should do**, using bullets where they improve scanning; and
- remove the section entirely when the core risk sections or another authoritative page already carry the same meaning.

For first-use and unstated-context pages:

- keep [[Start Here]] focused on teaching the short first-use route and the few ideas a new reader should remember; do not reproduce the full protected seven-route handling list there when the operational detail is already available in [[AI Blind Spot Review Card]] and [[Unstated Context Control]];
- keep [[AI Blind Spot Review Card]] as the compact current-task working aid; operational checklists may be repeated there when the reader needs them at the point of action;
- keep [[Unstated Context Control]] as the detailed owner of the unstated-context recognition and handling sequence; do not duplicate the canonical risk-to-Control relationship map there;
- keep [[Organisational Context Handling]] as a short orientation and worked-example bridge; do not reproduce the full seven-route handling sequence, full preservation criteria, or another detailed Control procedure there; and
- keep [[Glossary]] entries focused on term meaning and distinctions. Do not reproduce a detailed recognition taxonomy or operating procedure when a guidance page already owns that material; and
- keep Glossary examples conceptual. An example may name a canonical item to illustrate the concept, but it must not enumerate risk-to-Control, Control-to-Method, Method-to-Control, or other canonical relationship sets owned by [[AI Blind Spot Control Map]].

#### New collections

For a new repeated-entry collection, define:

- the entry name and purpose;
- mandatory fields or sections;
- optional fields or sections;
- links or dependencies;
- review requirements;
- maintenance requirements.

#### Short routes and quick versions

A quick-start route, summary, triage, shortened checklist, or thin companion route may simplify navigation. It must not create approval authority, extend standing, weaken a control, remove a source, review, escalation, or stop requirement, or allow a specialist, uncertain, restricted, human-only, or multi-person process to be skipped.

A thin route points to the full guidance. It does not replace the full guidance or the task-specific controls in the originating file.

Do not add a separate shortened public file merely because the full guidance appears dense. First require:

- evidence from representative readers or real use that a shorter route is needed;
- owner approval;
- assessment of package, translation, navigation, validation, and maintenance effects;
- evidence that the shorter route preserves every required boundary.

#### Reorganising content

Changing the structure—such as grouping, shortening, or reorganising content—must not remove an important control.

Keep every instruction that tells the reader:

- which source to use;
- what not to do;
- what must stay outside AI;
- who must review or approve;
- when to stop or escalate;
- what may or must not be recorded or preserved.

When reproducing a framework, decision path, route list, checklist, or approved set of items, keep its approved labels and meanings. Preserve the number and order where these are part of the model. Make clear whether the items are steps, alternatives, criteria, or separate controls.

---

## 9. Cross-References and Traceability

This section explains how to keep approved names, links, source meanings, and dependent files aligned when something changes.

---

### 9.1 Canonical Titles and Stable Names

Published risk, control, decision, role, source-location, representability, route, file, and artefact names may be linked from other files. Do not rename them casually.

Preserve formal published titles exactly unless the owner approves a title change.

Use the current package, Glossary, Risk Library, Control Map, and canonical reference files as title and terminology authorities rather than maintaining a duplicate fixed inventory here.

In reader-facing content, use the complete formal artefact name at first mention in each standalone file, adding `the` where normal English grammar requires it. After that first mention, use `this guide` for Win.Win AI Blind Spot Guide self-reference and `the Use Case Guide` for the named companion where the reference remains unambiguous.

Do not use `BSG`, `UCG`, or another internal abbreviation in reader-facing content. Within the public guide, `BSG` and `UCG` may appear only in this Author and Editor Guide. Outside the public guide, they may be used for authoring, maintenance, review, validation, and evidence work. Companion-guide headings, labels, and navigation routes must identify the specific formal artefact.

Use the current approved terminology source for the publication. Keep approved terms and meanings consistent. Do not replace an approved term with a similar word where that could change, weaken, broaden, narrow, or blur the meaning.

A term that readers or maintainers are expected to recognise repeatedly as the same concept, canonical risk, Control, Method, Accountable Route, elicitation technique, named principle, decision, or recurring structural/navigation label must use one fixed English form and one owner-approved fixed translation in each target language. A plain-language explanation may sit beside the controlled term, but it must not become a second controlled name.

Before Stage 2 translation, compare the complete governed-term inventory with the owner-designated external terminology authority. Surface uncovered fixed-translation terms for owner decision; do not invent or normalise target-language mappings silently and do not create a competing BSG-local master table.

The governed-term inventory must include stable repeated structural labels, not only concept names. For the current Control Map risk-relationship structure, include at least `Risk Relationship Entry Structure Standard`, `Risk Relationships`, `Control need`, `Controls to consider first`, `Additional Controls when relevant`, `Methods that may support those Controls`, `Accountable Routes that may be needed`, and `How this guide currently helps`, together with the registry structural fields.

Keep important distinctions clear in definitions, examples, translations, validation, and review evidence. For example:

- AI Blind Spot is broader than unstated context;
- review is not verification;
- elicitation is not retrieval or extraction;
- a responsible person is not necessarily the responsible owner;
- a responsible owner is not automatically an independent verifier;
- source location is not representability or reliability;
- current-task handling is not preservation;
- organisational memory is not RAG;
- recording something is not approval.

---

### 9.2 Filenames, Wikilinks, Heading Links, and Aliases

Preserve approved filenames exactly.

When a numbered H2 or H3 changes, update every Obsidian or Markdown link that targets the heading. Preserve a readable alias so readers see the entry name rather than the number where appropriate.

Outside Markdown tables, use this source form:

```md
[[Target|Display text]]
```

Inside Markdown tables, escape the Obsidian alias separator so the alias does not create another Markdown table column:

```md
[[Target\|Display text]]
```

A local wikilink must point to a file in the same language folder unless the link is intentionally external.

When a file is added, removed, renamed, or materially repurposed:

- update the applicable local README index or navigation route;
- update every affected wikilink and heading link;
- update approved translated equivalents where they exist;
- validate the complete package.

Use the exact local filename in each wikilink.

---

### 9.3 Canonical and Adapted Content

Keep reusable canonical meaning in the approved reference or source file and task-specific or organisational implementation in the relevant control, card, template, or adaptation.

Keep the published Win.Win source distinguishable from organisational adaptation.

If local material supplements canonical content, state what is local, who approved it, and which source release and document version it adapts.

---

### 9.4 Source-to-Final Traceability

For a structural or substantive rewrite, record the exact source heading, paragraph, list item, table row, callout, example, field, or control and its exact final destination.

A heading match, keyword match, noun phrase, broad summary, or automated `yes` value is not proof that the source meaning survived.

Use both directions:

- **source to final** — every source obligation, prohibition, exception, distinction, example, evidence requirement, control, and reader action has a recorded disposition and destination;
- **final to source** — every final heading, rule, example, field, list item, control, and instruction traces to the current BSG source, an identified shared-guide authority, a retained BSG-specific control, or an explicit owner-authorised addition.

---

### 9.5 Cross-File Change Impact

Before completing a change, check whether it affects the Risk Library, Control Map, Review Card, Glossary, scope guidance, elicitation guidance, source-packet guidance, Unstated Context Control, context-handling guidance, reviewer-standing guidance, organisational-memory guidance, templates, READMEs, navigation, translation notes, or future language sources.

When a canonical term, risk name, route, decision, control statement, consequence explanation, authority boundary, specialist qualification, title, filename, heading, anchor, or public-language statement changes, search the complete package for the previous wording.

Do not treat the change as complete until:

- every intended dependency uses the current wording;
- no unintended stale occurrence remains;
- working cards and templates teach the same current risk and control model as their source guidance;
- any renamed risk, Control, Method, or Accountable Route remains traceable to its canonical meaning and current control architecture;
- README navigation and purpose descriptions remain accurate;
- temporary working-language status and final trilingual publication requirements remain distinct and accurate.

---

### 9.6 BSG–UCG Reference Dependency

This subsection explains when a material BSG change may require notification and review of Win.Win AI Use Case Guide (UCG). Section 16.10 explains how to perform the impact review.

#### When notification or review is required

Assess possible UCG impact where a BSG change affects:

- BSG’s broad purpose, scope, or current detailed focus;
- a canonical term, definition, risk name, decision label, role distinction, route, or control used by UCG;
- the meaning of AI Blind Spot, unstated context, task basis, source location, representability, elicitation, retrieval, extraction, review, verification, preservation, organisational memory, or RAG;
- where relevant context may exist or how it may be represented, handled, verified, recorded, or preserved;
- a public title, filename, heading, purpose, route, function, availability statement, or approved destination;
- routing among the Control Map, Organisational Context Handling, Unstated Context Control, Elicitation Techniques, Source Packet Add-On, When Questions Are Not Enough, or other supporting guidance;
- a boundary involving safe conversion, human-only handling, independent verification, accountable or specialist review, reviewer standing, stopping, escalation, do-not-record, or do-not-use controls;
- the relationship between UCG and BSG, including independent usability, publication status, availability, or whether the companion is optional, recommended, or required;
- an approved English, Traditional Chinese, or Simplified Chinese title or term used by UCG;
- wording that remains literally true but has become incomplete, misleading, or insufficient for the reader’s task.

If impact is uncertain, notify the owner and review the current UCG reference rather than assuming no impact.

#### Changes unlikely to affect UCG

A BSG change does not normally require UCG correction where it affects only:

- punctuation or typography;
- internal formatting;
- evidence packaging;
- an internal example that does not change approved meaning;
- translation naturalness without changing a title, term, scope, route, boundary, or reader action;
- package metadata that does not affect publication status, availability, filename, path, or destination.

#### Work boundaries

A BSG-only task may assess and notify possible UCG impact. It does not authorise editing UCG unless the owner explicitly includes UCG in scope.

Do not maintain a permanent dependency occurrence register as a second master source. Rescan the current packages for each impact review.

---

## 10. Headings, Bold Labels, and Callouts

### 10.1 Callout Types

Use callouts selectively for information that deserves to interrupt normal reading.

Use these technical identifiers:

- `[!note]` for supporting context or interpretation guidance;
- `[!tip]` for optional practical help;
- `[!important]` for a requirement the reader must not overlook;
- `[!warning]` for a stop condition, prohibited action, or escalation trigger;
- `[!caution]` only for a serious and potentially irreversible consequence.

---

### 10.2 Callout Rules

A file or section may contain more than one callout where each callout has a clear and distinct purpose. Do not impose a fixed maximum number of callouts.

Avoid unnecessary repetition, fragmented guidance, contradictory callouts, or multiple callouts that compete for attention.

Review callouts for valid Markdown and Obsidian syntax, lower-case identifiers, clear purpose, appropriate placement, readable GitHub rendering, correct links and hard breaks, and proportional use.

Do not use callouts as substitutes for structural headings or mandatory entry sections.

Do not repeat the same generic warning throughout many files. Put common guidance in this guide and retain file-specific warnings where they materially help the reader.

Do not place callout syntax inside copyable prompts, questions, or template response fields unless it is intentionally part of the copyable content.

Keep the technical callout identifier in English. Localise the visible title and content where appropriate.

**Use**

```md
> [!warning] Stop before relying on the output
> Do not rely on the output until the named accountable or specialist reviewer has completed the required review.
```

**Avoid**

```md
> [!NOTE]
> Important information.
```

The second example uses an upper-case identifier and does not explain the required action.

---

## 11. Writing and Plain-Language Rules

### 11.1 Preserve Meaning and Control Strength

Do not silently remove, merge, weaken, or invent definitions, distinctions, risks, controls, routes, caveats, review requirements, approval conditions, escalation boundaries, examples, template fields, or reusable habits.

**When shortening or restructuring a list.** When shortening, paraphrasing, reordering, or converting to bullets a list of obligations, conditions, exceptions, routes, safeguards, or controlled options, account for every substantive item in the source. Do not replace several distinct items with a broad umbrella phrase unless the revised wording clearly preserves every distinction that matters. For a materially restructured list, the review evidence should show where each substantive source item is preserved.

**When reusing a canonical list.** When an authoritative registry provides a complete option set or canonical list, decide whether a dependent page needs the full set or only a short orientation cue. If the full set is reproduced, preserve the complete set and its distinctions. If only orientation is needed, give a clearly non-canonical plain-language cue and link to the authoritative registry. Do not create a partial canonical-looking list or a second authoritative-looking definition.

---

### 11.2 Plain Language

Prefer concrete verbs, named roles, named sources, clear conditions, and direct consequences. Avoid vague instructions such as “review carefully” where the actual check can be named.

Write for readers who may be new to AI governance. Reader-facing pages should work for general adult readers across roughly ages 20–80 who are familiar with using GenAI but may over-trust a polished or confident AI output.

Support recognition and recall rather than requiring terminology study. A reader should be able to encounter an unfamiliar controlled term, understand the practical idea from nearby plain-language guidance, and recognise the same controlled term when it appears again. When practical, reinforce the route **AI Blind Spot risk → relevant Control(s) → applicable Method(s) or guidance → Accountable Route where required → decision** without turning every page into a duplicate workflow.

Use **purposeful repetition**. Repeat short, stable memory cues, controlled names, decision labels, and point-of-action checks when repetition helps recognition or safe use. Do not repeatedly teach the same long procedure, taxonomy, relationship map, preservation criteria, or detailed explanation across several reader-facing pages.

Use this editorial rule:

> **Repeat what the reader should remember. Reference what the reader should look up. Do not repeatedly teach what the reader only needs to look up.**

When two pages cover similar material, confirm that each has a distinct reader job, such as teaching, recognition, detailed guidance, working checklist, template use, or canonical reference. If the second page adds no distinct reader value, shorten it, cross-reference the owning page, or remove the duplicated material.

Do not require readers to study the Glossary before they can use a first-use or practical page. When an unfamiliar controlled term is necessary, give a short plain-language orientation cue at the point of use and link or route the reader to the authoritative definition when precision is needed. The cue must not become a competing canonical definition.

For **Level 2 controlled terms** that readers do not need to learn at the beginning but must understand when first used — for example **reviewer standing, approval standing, materiality, verification, representability, preservation, and unstated context** — give a brief point-of-use recognition cue at the first meaningful reader-facing encounter. Do not preload all Level 2 terms into Start Here, and do not repeat their full canonical definitions across pages. Preserve the exact controlled term, explain only enough for the reader to understand the practical distinction or next action, and route to the Glossary or other authoritative page where precision is needed.

For each AI Blind Spot risk, a general reader should be able to understand what may go wrong, why it matters, and what to do next. If this guide does not provide a detailed mitigation method, name at least the relevant recognised Control, Method, Accountable Route, or other approved next step so the reader knows where to continue.

Prefer:

- short, complete sentences;
- active voice where responsibility matters;
- specific author and review actions;
- defined technical terms;
- durable wording that does not depend on an unstable file, risk, route, question, template, or asset count.

Avoid:

- unexplained jargon;
- inflated claims;
- fear-based language;
- unnecessary legal or technical detail;
- stylistic variety that changes a canonical term.

Use UK English spelling consistently throughout `en_HK` ordinary prose, headings, tables, callouts, examples, templates, and guidance. Use forms such as `organisation`, `customise`, `localise`, `authorise`, `recognise`, `behaviour`, `licence` as a noun, `license` as a verb, `practice` as a noun, `practise` as a verb, `centre`, `programme` for a non-computing plan or activity, and `program` for computing.

Retain another spelling only where it is part of an exact official title, product or platform label, filename, path, URL, code value, command, technical literal, approved controlled term, validation string, or exact quotation. Do not mix UK and US spelling merely because a comparison source or earlier draft uses different spelling.

The formal names **Win.Win AI Essentials**, **Win.Win AI Use Case Guide**, and **Win.Win AI Blind Spot Guide** do not include the article **the**. In running English prose, add **the** immediately before any of these formal names where normal grammar requires the definite article. Apply the same grammatical rule consistently across all three artefacts. Do not add **the** inside a formal title, filename, path, link label, table entry, source-version field, or other exact controlled name unless it is genuinely part of that controlled text.

When referring to Win.Win AI Blind Spot Guide itself, write **this guide** in body text and **This guide** at the beginning of a sentence. In Markdown headings, write **This Guide**. Do not write **the guide**, **The guide**, **the Guide**, or **The Guide** for this self-reference.

Before delivery, search every in-scope English public file for these prohibited self-reference forms. Review each occurrence in context. Correct ordinary self-reference, but preserve the protected repository-level README, formal titles, exact quotations, filenames, paths, links, code, and instructional examples that explicitly identify a prohibited form. A package-wide replacement without contextual review is not permitted.

Preserve the formal title **Win.Win AI Blind Spot Guide**, file titles, wikilink targets, and the names of other guides. Apply this rule only to self-reference, not as a global replacement of the word **the**.

When a review or validation term is necessary, explain it in everyday words the first time. State what the author or reviewer must do before naming the formal term. Keep machine-readable evidence labels in reports, registers, and validation outputs rather than ordinary guidance unless the reader must enter that exact value.

Define a non-common abbreviation at its first ordinary-prose use in each independently usable public file. Write the full approved term first, followed by the abbreviation in parentheses. After that, the abbreviation may be used alone where it remains clear. Do not rely on a definition in another file.

An abbreviation inside frontmatter, a filename, path, URL, package name, command, code, inline code, locale value, exact status label, or another controlled technical identifier does not need to be rewritten merely to create a prose definition. If the same term appears in ordinary prose, explain it at its first ordinary-prose use.

Preserve an owner-approved standard footer exactly. The approved English footer may use the controlled identifier `CC BY 4.0` because the corresponding README gives the full licence name. These controlled footer patterns do not permit unexplained abbreviations elsewhere.

If a controlled short label has no approved full form, explain its function instead of inventing an expansion.

---

### 11.3 Lists

Use numbered lists only where order, sequence, dependency, priority, ranking, completion order, or a fixed decision process is meaningful.

Use bullet lists for alternatives, options, patterns, criteria, examples, inventories, roles, risks, controls, and non-sequential choices.

Use one list style consistently within each list.

For standalone or self-contained bullets:

- write each item as a complete point;
- use consistent ending punctuation;
- normally end full-sentence items with a full stop;
- do not add `and` or `or` before the final item.

Use `and` before the final item only where all listed actions, conditions, or requirements apply together and the bullets intentionally form one grammatical sentence.

Use `or` before the final item only where the listed items are alternatives and one or more may apply.

If a bulleted list intentionally forms one grammatical sentence:

- punctuate the earlier items consistently, normally with semicolons;
- place `and` or `or` at the end of the penultimate item;
- end the final item with a full stop.

Do not mix standalone-list style with sentence-list style within one list.

Do not use `and/or`. State clearly whether all items apply, any one item may apply, or one or more items may apply.

---

### 11.4 One Function at a Time

Keep one risk, control, route, decision, review function, authority condition, escalation trigger, preservation decision, or recording requirement per row or item where practical.

Do not combine unrelated functions merely to shorten a table, card, checklist, or template.

---

### 11.5 Examples and Placeholders

Use examples only when they help readers understand a blind spot, task, control, route, decision, or consequence.

Do not present invented or composite examples as documented real incidents or evidence.

For a consequence section, prefer a general consequence narrative that describes what may happen without asserting that a regulator, insurer, funder, auditor, platform provider, or professional reached a particular outcome.

Do not require labels such as “hypothetical” or “illustrative” when this general consequence style is used.

If a documented incident is used, confirm its provenance and anonymise it unless permission and a clear reason support identification.

Use placeholders that make required local information clear.

Do not present an example as an approved organisational decision.

---

### 11.6 Specialist and Time-Sensitive Claims

Do not use a concrete example that depends on a current legal conclusion, regulator outcome, insurer decision, funder decision, platform function, or asserted professional conclusion.

State the general consequence instead, and require current official-source checking or appropriately qualified review where the task needs it.

Do not remove useful legal, regulatory, privacy, employment, financial, safeguarding, cybersecurity, medical, psychological, counselling, pastoral, theological, technical, or professional controls merely to avoid time-sensitive claims. Preserve issue-spotting, current-source, authority, reviewer-standing, and escalation requirements while removing unsupported or unstable conclusions.

---

### 11.7 Legal, Regulatory, Privacy, and Specialist Tone

#### Start with the facts

Use an **issue-spotting, conditional, source-led, and authority-aware tone**.

This guide may help readers identify a possible legal, regulatory, privacy, financial, employment, safeguarding, medical, psychological, counselling, pastoral, theological, technical, platform, or other specialist issue. It must not sound as though this guide, an AI system, or an ordinary reviewer has made a final specialist determination.

State the relevant facts or conditions before describing the possible requirement or risk.

#### Use conditional wording

Prefer conditional wording such as `may`, `can`, `could`, `where`, `if`, `depending on`, and `in some circumstances`.

Avoid universal or absolute wording such as `every`, `always`, `never`, `cannot`, `only`, `automatically`, `constitutes`, `is required by law`, `is compliant`, or `is illegal`, unless the statement is a stable conceptual or mandatory governance boundary, or is directly supported by a current authoritative source and any required qualified review.

#### Separate facts, risks, and conclusions

Distinguish clearly between:

1. an observable fact or circumstance;
2. a possible risk, consequence, or control need;
3. a legal, regulatory, privacy, or specialist conclusion.

Do not turn a possible issue into a definite conclusion merely because the wording sounds plausible.

Do not imply that a regulator, court, insurer, funder, auditor, platform provider, or qualified professional will reach a particular outcome.

#### Current features and external outcomes

For current platform functions, product behaviour, model capability, or technical limits, use platform-neutral or model-neutral wording where possible. If a current feature matters, check the current official source and record the date checked.

Describe consequences as possibilities unless documented evidence supports stronger wording.

Preserve current-source checking, authority boundaries, escalation, and qualified-review controls.

A disclaimer does not correct an unsupported definite claim elsewhere in the content.

#### When accurate wording is not possible

Use this preferred sentence pattern:

> When **[relevant facts or conditions]** apply, **[the information, action, or arrangement]** may **[create the risk or consequence]**. Check **[the current official source, approved record, policy, or process]**. Seek qualified review if **[interpretation, authority, or material consequence]** remains unclear.

If the content cannot be made accurate through conditional, source-led wording, remove the conclusion and retain only:

- the issue to check;
- the current authoritative source requirement;
- the responsible role;
- the qualified-review or escalation requirement.

---

### 11.8 Keeping Important Meaning During Rewrites

Keeping important meaning during a rewrite is sometimes called semantic preservation.

A rewrite may improve wording or structure, but it must not remove an important question, recognition example, risk-specific prompt instruction, reviewer action, source requirement, limit, human-only boundary, safe-conversion instruction, approval boundary, escalation trigger, template field, recording restriction, preservation condition, or reusable habit unless the owner approves the removal.

For a major rewrite, list each important point from the approved source and record whether it was:

- kept exactly;
- kept in equivalent or stronger wording;
- restored;
- replaced by an approved newer point;
- removed with explicit owner approval.

A surviving heading, keyword, or summary is not proof that the meaning survived. Check the examples, reasons, conditions, consequences, boundaries, and instructions themselves.

A broad risk explanation must not replace the specific way the risk appears or the distinct safeguards and reviewer actions for that risk.

---

### 11.9 Separate Actions, Checks, and Evidence

If a passage could confuse the reader’s role, separate:

- **Author action** — what the author or editor must do;
- **Review check** — what a reviewer must confirm;
- **Required evidence** — what must be quoted, located, recorded, or reported.

Use these labels only where they improve clarity. Do not add all three mechanically when one short instruction is enough.

---

### 11.10 BSG Semantic Preservation Rule

A terminology, scope, architecture, risk, route, or control rewrite may clarify or broaden this guide, but it must not delete a memorable question, concrete recognition example, risk-specific reviewer action, safety example, escalation trigger, practical template field, human-only boundary, do-not-record instruction, preservation condition, or reusable habit unless the owner explicitly approves its removal.

For substantial rewrites, classify baseline messages as:

- retained verbatim;
- retained in equivalent or stronger wording;
- restored;
- properly superseded;
- removed with explicit owner approval.

Risk Library rewrites must not let generic repeated content replace risk-specific content. Every risk needs recognisable examples and a distinct reviewer action. Optional sections such as prompt-side control, limits, context outside AI, and escalation should remain where they carry unique control meaning. Do not restore exhaustive relationship lists to the Risk Library merely for traceability; the Control Map owns the complete explained relationship mapping.

A surviving heading, label, noun phrase, or broad summary does not by itself prove semantic preservation. Distinct examples, reasons, contrasts, conditions, consequences, boundaries, and operational instructions must remain separately identifiable unless the owner explicitly approves their removal.

Protected examples, questions, triggers, template fields, route order, decision labels, and reusable habits must remain traceable in source-to-final evidence.

---

### 11.11 Typographic Apostrophes

Use the typographic apostrophe `’` for possessives and contractions in ordinary reader-facing English Markdown prose, headings, tables, callouts, captions, and sample content. For paired single quotation marks, use `‘…’`.

Retain U+0027 only where machine syntax, code, commands, paths, identifiers, regular expressions, literal search terms, URLs, YAML, JavaScript Object Notation (JSON), or exact source quotation requires it. Review each occurrence in context; do not apply an unrestricted replacement to machine-oriented content.

---

## 12. Translation and Localisation Rules

During pre-publication work, the working package may be English-only until translation work is authorised and completed. Do not imply that `tc_HK` or `sc_HK` editions are complete merely because translation rules exist. Before publication, both translated editions must be completed, reviewed, indexed, linked, and validated.

This section contains the BSG translation and localisation rules needed for BSG work. Do not make BSG authoring, translation, review, or validation depend on consulting another guide’s Author and Editor Guide. Where a shared Win.Win rule is useful, copy or adapt it into this guide and then apply the BSG-specific terminology, architecture, filenames or localised folders, README mappings, and stricter BSG controls stated here.

---

### 12.1 Source and Terminology Authority

Treat the designated current `en_HK` source as authoritative for translation where the package identifies it as the master source. Do not silently correct, clarify, shorten, or otherwise edit English through `tc_HK` or `sc_HK`. An English source correction requires its own authorised source-change process before translated editions are updated.

Use the current external owner-approved terminology authority as the single controlled terminology authority for the publication cycle. Apply controlled mappings to the intended concept, not by blind substring or character replacement. When mappings overlap, the more-specific complete controlled concept takes precedence over a generic component mapping.

For example, `Row → 列 / 行` applies to the table-row concept. It must not cause character replacement inside unrelated ordinary words such as `列出`, `列舉`, or `圍欄`.

If a genuinely controlled term is missing from the current authority, record it for supplemental terminology handling and owner decision rather than inventing a permanent mapping. Translation Notes may explain implementation and provenance, but must not become a competing terminology registry.

During translation review, record the source file and version used for each translation, how the source and translation were paired, and how certain that pairing is.

In Traditional Chinese and Simplified Chinese content, use the approved localised names for reader-facing titles, headings, labels, links, platforms, and publication channels. Do not keep the English name merely because it appears in inline code in the English source.

Keep English only for literal technical text, such as a filename, path, URL, package name, command, code value, validation string, or controlled English-master source identifier.

Current terminology authority includes approved forms such as:

| English source | Traditional Chinese (`tc_HK`) | Simplified Chinese (`sc_HK`) |
|---|---|---|
| `Win.Win AI Blind Spot Guide` | `Win.Win 人工智能盲點指南` | `Win.Win 人工智能盲点指南` |
| `LinkedIn` | `領英` | `领英` |

Use the current owner-approved terminology authority for all other terms. Do not maintain a competing translation table inside this guide.

Do not report an uncertain pair as a confirmed match or confirmed missing file.

---

### 12.2 Meaning Fidelity

Compare source and target side by side. Check for omission, unsupported addition, strengthening, softening, narrowing, broadening, reframing, changed governance meaning, and changed reader action.

For every meaning-bearing passage, preserve the actor, recipient, condition, negation, modality, scope, authority, reviewer standing, verification requirement, escalation trigger, human-only boundary, preservation condition, and the identity of each Risk, Control, Method, or Accountable Route.

Preserve obligations, prohibitions, warnings, uncertainty, approval boundaries, specialist boundaries, source requirements, reviewer-standing requirements, human-only boundaries, recording restrictions, preservation conditions, and stop or escalation conditions. Prefer natural Chinese sentence structure over English word order, but do not improve naturalness by weakening, strengthening, deleting, or adding meaning.

---

### 12.3 Hong Kong Context

All three language folders are Hong Kong editions.

Preserve Hong Kong jurisdiction, terminology, privacy concepts, language register, character set, institutional practice, and audience context.

Do not substitute Mainland, Taiwan, US, or UK defaults where Hong Kong-specific content is required.

Simplified Chinese wording must not introduce People’s Republic of China (PRC) legal, regulatory, institutional, or cultural assumptions merely because the language is Simplified Chinese.

Use current Hong Kong sources for Hong Kong-specific claims.

---

### 12.4 Source Grounding and Source Checking

Preserve the distinction between:

- **source grounding** — the basis supporting content;
- **source checking** — the act of comparing or verifying content against a source.

Do not translate these as though they were the same control.

---

### 12.5 Script and Structure

Preserve the source structure where it supports navigation, comparison, maintenance, or review.

Check Traditional and Simplified Chinese script consistency, unintended untranslated text, headings, tables, lists, callouts, disclaimers, links, examples, and section order.

Prefer line-aligned Markdown source across `en_HK`, `tc_HK`, and `sc_HK` wherever natural language permits.

Keep each corresponding heading, paragraph, callout, list item, example, code fence, thematic break, and blank-line boundary on the corresponding source line or block and in the same order.

Statement length may differ. Do not split, merge, move, omit, duplicate, or reflow corresponding content merely to improve the appearance of one language.

Exact rendered wrapping and cross-language hard-break parity are not required.

If natural language or an approved localisation difference requires a split, merge, move, omission, or different structure, record the source and target locations, reason, and semantic-preservation decision in the translation-alignment evidence.

Structural source alignment is an omission-detection aid. It does not prove translation quality or qualified bilingual review.

---

### 12.6 Qualified Bilingual Review

Use both bilingual comparison and target-language reading.

Use this review sequence:

1. translate and review `en_HK → tc_HK` directly against the current English source;
2. independently translate and review `en_HK → sc_HK` directly against the current English source;
3. after both direct reviews, compare `tc_HK ↔ sc_HK` for substantive parity.

Do not treat `sc_HK` as a simple character-converted derivative of `tc_HK`. TC may be used as a comparison aid, but SC must still be independently checked against the English source.

Check terminology, meaning, naturalness, filenames, links, headings, tables, lists, callouts, disclaimers, examples, authority language, approval language, reviewer-standing language, escalation language, and Hong Kong context.

TC and SC do not need character-level identity. Preserve differences explained by Traditional/Simplified script conversion, exact controlled mappings, owner-approved localisation variants, approved TC/SC quotation punctuation, approved locale-specific CC BY 4.0 naming, or natural locale wording that preserves the same substantive meaning.

AI-assisted comparison supports but does not replace qualified bilingual sign-off.

Escalate ambiguity, specialist terminology, material meaning change, or changed authority, risk, review, disclaimer, human-only, recording, preservation, or escalation meaning.

---

### 12.7 Reader-Facing Filenames and Template Folder Localisation

Use these exact reader-facing language-folder paths:

| Locale | Template folder |
|---|---|
| `en_HK` | `Templates/` |
| `tc_HK` | `範本/` |
| `sc_HK` | `模板/` |

Internal links, README entries, and source/target pairing records must use the locale-appropriate physical path. Do not create `Templates/` under `tc_HK` or `sc_HK`.

---

### 12.8 Chinese README Filename/Path Mapping

The complete asset index in each Chinese language-folder README must cover every public asset in that language folder, including template-subfolder assets. Use the localised Chinese filename or path as the actual navigation link, followed immediately by the exact corresponding English source filename or path in parentheses.

Traditional Chinese pattern:

```md
[[localised TC filename/path]] (exact English source filename/path)
```

Simplified Chinese pattern:

```md
[[localised SC filename/path]] (exact English source filename/path)
```

The parenthesised English source path is mapping text only. Do not make it a link back to `en_HK`. Use the exact current English filename/path, including `Templates/...` for template-source mappings.

---

### 12.9 Unicode ZIP Filename and Path Handling

Public or consolidated BSG ZIP packages containing Chinese filenames or folder names must store those entry names with standards-compliant Unicode/UTF-8 ZIP filename metadata. Correct display in one graphical ZIP application is not sufficient evidence.

Verify the packaged ZIP with a standards-oriented ZIP reader, then extract it to a clean directory and confirm that physical Unicode paths match Markdown link destinations. In particular, confirm that `public/tc_HK/範本/` and `public/sc_HK/模板/` exist exactly with those Unicode names and that local links resolve after extraction.

---

## 13. Chinese Markdown Rules

### 13.1 Emphasis Spacing

In `tc_HK` and `sc_HK`, insert one ASCII space where an opening or closing `*` or `**` would otherwise touch adjacent Chinese or Latin text.

Correct:

```md
這是一個 **重要提醒**。
这是一个 **重要提醒**。
```

Do not insert artificial spaces between emphasis and Chinese punctuation.

Correct:

```md
**指令**、**規則**
（**重要**）
```

---

### 13.2 Chinese Colons and Bold Labels

Use the full-width Chinese colon `：` in Chinese publication prose and labels.

For a bold key-value label, use:

```md
**標籤：** 內容
**标签：** 内容
```

Keep the colon inside the bold markers and add one ASCII space after the closing `**` when content follows.

---

### 13.3 Technical Exclusions

Do not apply Chinese emphasis-spacing or colon conversion rules inside YAML, URLs, times, ratios, drive paths, namespaces, JSON, code, inline code, identifiers, Markdown link destinations, escaped asterisks, or exact English technical strings.

---

## 14. Markdown and GitHub Formatting Rules

### 14.1 Raw Markdown Review

Check raw file content rather than relying only on rendered preview.

Review trailing spaces, hard breaks, line endings, indentation, structural markers, code blocks, frontmatter, links, tables, and technical literals.

---

### 14.2 Section Breaks and Blank Lines

This convention applies only to non-README Markdown files. Repository-level and language-folder `README.md` files are explicitly exempt.

Apply the immediate-child exception at both hierarchy levels:

- do not place a thematic break between the H1 and its immediate first H2 when no body content appears between them;
- do not place a thematic break between an H2 and its immediate first H3 when no body content appears between them.

If body content appears between a parent heading and its child heading, place exactly one thematic break before the child heading.

Every later H2 requires exactly one preceding thematic break, including when it follows an H2, H3, H4, paragraph, list, table, callout, code block, or other body content.

Every later H3 requires exactly one preceding thematic break when it begins after body content or follows another H3 or H4.

Body content includes paragraphs, lists, tables, callouts, blockquotes, fenced code, images, content links, and other reader-facing material. Blank lines, the thematic break itself, and complete HTML comments do not count as body content.

Use exactly one blank line before and one blank line after every thematic break. Apply this to **every live thematic break**, including end-of-page/footer breaks and breaks immediately after fenced code, not only breaks before headings. Do not use consecutive thematic breaks or multiple blank lines around a thematic break.

Use one blank line between a heading and the content that follows. Do not place thematic breaks before H4 headings.

**Use**

```md
# Document Title

## 1. Immediate First Main Section
```

```md
## 2. Main Section

### 2.1 Immediate First Subsection
```

```md
## 3. Main Section

Introductory text.

---

### 3.1 New Subsection
```

**Avoid**

```md
# Document Title

---

## 1. Immediate First Main Section
```

```md
## 2. Main Section

---

### 2.1 Immediate First Subsection
```

---

### 14.3 GitHub Hard Breaks

GitHub normally joins consecutive physical lines inside one paragraph. Use two trailing ASCII spaces only where separate visual lines are intentionally required.

Common cases include contact details, signature lines, feedback labels and links, short paired guidance lines, and footer attribution.

Do not require hard-break parity across languages. Judge the intended rendering of each file.

**Use a hard break where two visual lines must remain separate**

```md
Win.Win@Skybroad | winwin.skybroad@gmail.com  
Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
```

Do not use trailing spaces where normal paragraph wrapping is intended.

---

### 14.4 Tables

Keep table headings short and descriptive.

Preserve the meaning of each row when reformatting. Check that pipes, emphasis, links, and line breaks render correctly.

Do not force every idea into a table where prose or a checklist is clearer.

---

### 14.5 Encoding and Line Endings

Use 8-bit Unicode Transformation Format (UTF-8) without a byte order mark (BOM), use line feed (LF) line endings, and include exactly one final newline. Report mixed or unintended line-ending styles.

Do not change line endings, whitespace, wrapping, or table spacing in an unchanged file.

---

## 15. Using AI Assistants for Authoring and Editing

### 15.1 Role and Authority

An AI assistant may support authoring, editing, comparison, localisation, validation, evidence preparation, and packaging. It must not assume authority to approve, publish, adopt, or make an unrequested substantive governance change.

An AI assistant must not claim owner acceptance, qualified bilingual approval, specialist approval, Pure Human Review completion, publication approval, or final acceptance unless those steps actually occurred.

---

### 15.2 Current-Task Source of Truth

Use only the files supplied for the current task. Confirm the exact package filename, direct inventory, package-extracted Author and Editor Guide, current terminology authority, applicable review toolkit, and validator before work begins.

For README protection, use the exact BSG README files from the current owner-designated BSG baseline package. For the present control baseline, use `bsg 20260730(3).zip`: `public/README.md` is the protected repository-level README, and its `public/en_HK/README.md` supplies the exact protected Master Source callout. UCG and AI Essentials README files may confirm a shared Win.Win presentation pattern, but they are supporting comparisons and are not the direct BSG README baseline.

Ignore old uploads, cached copies, earlier extracted folders, previous reports, and remembered wording unless the owner explicitly authorises them as references.

Do not substitute a detached BSG guide or README where it differs from the package-extracted or owner-designated BSG baseline file.

---

### 15.3 Before Starting Work

The AI assistant should:

1. identify the exact source package and version;
2. derive the direct source inventory;
3. list files in scope and files excluded;
4. classify file types and source roles;
5. inspect headings, links, terminology, formatting, repeated-entry structures, and protected presentation;
6. identify canonical sources and dependent files;
7. distinguish structural, editorial, substantive, organisational, translation, and packaging changes;
8. identify required version, footer, release, index, navigation, cross-artefact, and translation effects;
9. identify deterministic, semantic, bilingual, specialist, owner, representative-reader, and publication review gates;
10. state material assumptions in the change report;
11. mark `public/README.md` as owner-controlled and excluded;
12. mark the `public/en_HK/README.md` Master Source callout as protected exact wording;
13. separate temporary translation-production state from durable public README wording.

---

### 15.4 Editing Existing Content

Preserve original meaning unless a substantive change is requested. Do not silently remove sections, controls, approval conditions, escalation rules, caveats, examples, questions, template fields, human-only boundaries, recording restrictions, preservation conditions, or other safeguards.

Record whether content was retained, renamed, moved, split, combined, replaced, or newly added. Check every affected internal link after changing a title or heading.

For a major rewrite, complete source-to-final and final-to-source semantic comparisons before treating the work as complete.

Do not edit `public/README.md`. Preserve it byte-for-byte against the exact owner-designated BSG README baseline. Do not change the protected Master Source callout in `public/en_HK/README.md`; compare it with the exact BSG callout, not with a reconstructed UCG or AI Essentials version. If either appears to require a change, stop that part of the task, preserve the current file or callout, and report the matter for owner decision.

---

### 15.5 Authoring New Content

Identify the correct file type and canonical structure. Use the applicable Entry Structure Standard, include mandatory sections, use optional sections only when useful, and state what prompting, elicitation, review, or AI-assisted validation cannot prove.

Add the file to every applicable local index or navigation route and create translations only where the owner expressly authorises them.

Do not add, delete, or rename a public file without explicit owner approval.

---

### 15.6 Fresh-Chat Instruction

> [!note] Instruction for a fresh AI-assisted editing chat
> **Before editing**
> - Read the package-extracted current Author and Editor Guide.
> - Use only the current files supplied in the chat.
> - Confirm the exact source package, direct inventory, terminology authority, current review toolkit, and validator.
> - Record files in scope and excluded.
> - Treat `public/README.md` as owner-controlled and excluded. Do not modify it.
> - Preserve the exact Master Source callout in `public/en_HK/README.md`; do not rewrite it for an interim English-only or staged-translation state.
> - Apply the README numbering and section-break exceptions in Section 6.1.
>
> **While editing**
> - Follow the approved headings, structure, terminology, localisation, version, evidence, and validation rules.
> - Use UK English spelling and apply the list-punctuation and `and` or `or` rules in Section 11.3.
> - Preserve the BSG model, current detailed focus, Glossary distinctions, seven-route order, preservation boundary, reviewer-standing controls, protected examples, and risk-specific controls.
> - Do not silently remove, merge, weaken, rename, or invent governance content.
> - For a major rewrite, list the important points in the approved source and show what happened to each one in both directions.
> - A surviving heading, keyword, or summary is not proof that important meaning survived.
> - Assess whether a material BSG change may require UCG notification. Do not edit UCG unless it is expressly in scope.
>
> **After editing**
> - Validate every affected file and compare the final package directly with the exact source baseline.
> - For a whole-package clarity claim, complete a clean-room fresh-reader and TC translation-stress disposition for every in-scope non-README public page; do not substitute sampling for final coverage.
> - Report changed, unchanged, added, removed, and renamed files; source and final locations; semantic effects; stale wording searched; validator findings and dispositions; unresolved review gates; and what AI-assisted work cannot approve or prove.
> - For a full successor-pack generation, also produce the standard GitHub commit-message Markdown file, reviewer-neutral independent-AI review brief, and consolidated deliverables ZIP defined in Section 18.3.

---

## 16. Pre-Publication Review and Validation

Use this review order:

```text
confirm inputs
→ extract and derive inventory
→ pair source and translations where applicable
→ review content, README files, versions, and formatting
→ review specialist tone, BSG model integrity, and cross-artefact effects
→ check important meaning in both directions
→ classify findings and report status
```

Complete only the steps that apply to the authorised scope, but do not present a partial review as complete.

---

### 16.1 Required Input Preflight

Confirm the current public ZIP archive, package-extracted BSG Author and Editor Guide, current terminology authority, applicable review instructions, current accepted or owner-designated BSG Review Toolkit and Stage 1 Validator, document-version and release rules, and any source-to-translation pairings required by the authorised scope.

For a guide-alignment task, also confirm the latest owner-designated AI Essentials and UCG Author and Editor Guides required for same-topic, same-function comparison.

If a mandatory review input is missing or cannot be opened reliably, stop the affected comparison, list exactly what is missing, and do not present a partial comparison as complete.

---

### 16.2 Extraction and Inventory

Check that:

- the ZIP extracts successfully;
- Markdown files decode as UTF-8;
- the direct package inventory is complete;
- unexpected files, duplicate paths, case collisions, and non-public content are identified;
- displayed paths match actual package paths;
- each language folder matches its approved translation stage under Section 6.2;
- the public package contains no evidence, tool, report, prompt, or temporary file.

Require a language folder to be complete and independently usable only where that language edition has been designated complete under Section 6.2.

Do not require or create an external `file_list.txt`, checksum manifest, or equivalent package-control file unless the owner expressly changes this BSG rule for a later task.

---

### 16.3 File Pairing

Do not pair translations by filename similarity alone. Use explicit README, index, or register mapping, English names shown beside localised links, approved mappings, canonical paths, frontmatter, document function, and owner confirmation in that order.

Record how each source and translation were paired and how certain the pairing is. Do not report an uncertain pairing as a confirmed missing file.

If a pre-publication working package is English-only, record translation pairing and trilingual structure review as not yet applicable to that interim package. Do not create translations merely to suppress a validation finding. Before publication, complete the authorised translations and rerun the full trilingual review.

---

### 16.4 Translation and Localisation Review

If translations are in scope, check meaning fidelity, approved terminology, Hong Kong context, script contamination, untranslated text, links, headings, tables, lists, callouts, disclaimers, examples, approval language, reviewer-standing language, escalation language, accountability, human-only boundaries, recording restrictions, preservation conditions, and professional boundaries.

Structural source alignment is evidence for omission detection only. It does not prove naturalness, meaning accuracy, or qualified bilingual approval.

---

### 16.5 README Review

Check README files in four groups. Use the exact owner-designated BSG README baseline as the direct comparison source. For the present baseline, use `public/README.md` and the protected Master Source callout from `public/en_HK/README.md` in `bsg 20260730(3).zip`. Do not reconstruct the BSG baseline from UCG or AI Essentials wording.

**Identity and purpose**

- artefact identity;
- purpose and audience;
- broad model and current detailed focus;
- intended publication-language position;
- licence meaning;
- exact protected Master Source callout wording;
- confirmation that temporary translation-production status has not replaced durable public wording;
- approved terminology.

**Structure and navigation**

- protected presentation and authorised exceptions;
- heading hierarchy and required sections;
- folder navigation and asset index;
- durable reader routes;
- duplicate headings and broken anchors.

**Publication control**

- release information;
- shared boilerplate and approved substitutions;
- contact and feedback routes;
- repository paths;
- complete `en_HK`, `tc_HK`, and `sc_HK` editions before publication;
- no incomplete language edition represented as publication-ready;
- no author modification of the owner-controlled repository-level README.

**Links and rendering**

- links;
- intended hard breaks;
- final rendering.

Do not require different artefact families to share the same release number or artefact-specific purpose.

---

### 16.6 Document Version and Release Review

Check that:

- before first publication, every existing public file retains document version `1.0` unless the owner explicitly starts a new published document version;
- after publication, only changed documents receive an owner-approved version change;
- new public documents start at the owner-approved initial version;
- footer versions match frontmatter versions;
- every modified file uses the owner-approved correction date;
- unchanged files retain their existing versions, metadata, whitespace, and exact bytes;
- no file changes only to update its date;
- the pre-publication package release remains `1.0` unless the owner explicitly changes it;
- release labels are consistent across applicable README files;
- release history records material reader-facing changes.

Omit minor typography, punctuation, self-reference, evidence, or packaging corrections from release history unless the owner asks for them.

A package release may contain documents with different document versions after publication.

---

### 16.7 GitHub Hard-Break Review

Review hard breaks separately from translation. Classify cases as:

- `valid_github_hard_break`;
- `missing_github_hard_break`;
- `unnecessary_hard_break_review_only`;
- `strict_raw_difference_only`;
- `no_fix_needed`.

Use two trailing spaces as the project convention where GitHub would otherwise join two intended visual lines.

---

### 16.8 Legal, Regulatory, Privacy, and Specialist Tone Review

Perform a targeted tone review of legal, regulatory, privacy, financial, employment, safeguarding, medical, psychological, counselling, pastoral, theological, technical, platform, and other specialist content.

#### What to search

Search for certainty markers including:

`always`, `every`, `never`, `cannot`, `only`, `automatically`, `constitutes`, `required by law`, `compliant`, `illegal`, `defaults to`, `will reject`, `will require`, and `no recall`.

A match is a **review candidate**, not an automatic failure.

Also search for every canonical term, risk name, legal or privacy framing, control statement, consequence explanation, authority boundary, or specialist qualification changed during the review cycle.

#### How to assess each result

For each match, determine whether the statement:

- is a stable conceptual or mandatory governance boundary;
- is conditional on facts not stated in the sentence;
- depends on current law, regulatory guidance, platform functionality, model behaviour, or organisational arrangements;
- implies a final specialist conclusion;
- implies a definite external decision or consequence;
- should instead use conditional, source-led wording;
- requires a current authoritative source, date checked, or qualified review.

#### After wording changes

Confirm that:

- no stale wording remains in the Risk Library, Control Map, Review Card, Glossary, guidance, templates, READMEs, navigation, or translation notes;
- working cards and templates teach the same risk and control model as their source guidance;
- any renamed risk, Control, Method, or Accountable Route remains traceable to its canonical meaning and current control architecture.

---

### 16.9 Semantic Preservation Review

Use this review when a rewrite changes terminology, scope, structure, architecture, route wording, or how content is grouped.

1. identify the exact approved source version;
2. list the important points that must remain;
3. quote each point or record its exact source location;
4. record what happened to each point using Sections 11.8 and 11.10;
5. compare source to final section by section and list-item set by list-item set;
6. compare final to source and shared-guide authority;
7. confirm that the final wording keeps the same or stronger meaning;
8. record every approved replacement or removal;
9. check that examples, reasons, distinctions, conditions, boundaries, routes, and instructions remain clear;
10. detect unsupported additions, duplicates, stale content, changed heading functions, and weakened conditions or exceptions.

This evidence is for the current review only. It is not a new master source. Create a fresh register for each new review.

---

### 16.10 UCG Reference Impact Notification Review

Section 9.6 explains which BSG changes may affect UCG. This subsection explains how to perform the review.

#### Before reviewing

1. confirm the exact current BSG and UCG packages;
2. use the revised BSG package as the source for current BSG meaning and the current UCG package as the reference target;
3. read BSG orientation, scope, terminology, routing, control boundaries, unstated-context, context-handling, preservation, reviewer-standing, and maintenance guidance.

#### Review current references

1. identify BSG changes that match a trigger in Section 9.6;
2. scan current UCG public files for formal titles, companion descriptions, routes, definitions, use conditions, template fields, risk-library references, translated equivalents, availability statements, and related scope wording;
3. assess whether each reference remains accurate, complete enough for its function, and consistent with UCG’s independent usability.

#### Decide and record

1. record whether UCG correction appears required, not required, or uncertain;
2. identify exact UCG files and references affected;
3. notify the owner of any material impact;
4. do not edit UCG during a BSG-only task unless the owner explicitly includes it in scope;
5. preserve UCG task-level controls and independent usability;
6. create fresh evidence for each package review rather than reusing an old occurrence register.

---

### 16.11 BSG Model, Risk, Route, and Standing Review

Confirm package-wide that:

- the owner-purpose reader outcome remains visible: general GenAI users can recognise the AI Blind Spot concept, understand what the relevant risk means, and find at least one mitigation route without first studying the Glossary;
- terminology that readers are expected to recognise repeatedly uses one stable controlled English form, with fixed target-language mapping coverage identified before Stage 2;
- every canonical risk supports the three owner-purpose questions: what may go wrong, why it matters, and what to do next;
- where detailed mitigation is not provided, the risk names at least a relevant Control, Method, Accountable Route, or other approved next step;
- the first-use journey supports the fallback recognition **this may be an AI Blind Spot** and a route back to Win.Win AI Blind Spot Guide for further guidance;
- AI Blind Spot remains broader than unstated context;
- the approved current-detailed-focus sentence remains accurate;
- task-basis meaning is preserved;
- source location, representability, and reliability remain distinct;
- people, approved records, both, or unclear remain the source-location options;
- the controlled representability categories remain intact;
- the seven minimum current-task routes remain in the approved order where reproduced;
- preservation remains a separate governed decision;
- retrieve, extract, elicit, classify, route, review, and verify remain distinct;
- owner confirmation is not automatically independent verification;
- role, standing, competence, permission, independence, and authority remain distinct;
- canonical risk names and decision labels remain exact;
- problem-first risk architecture retains risk-specific prompt-side, reviewer, human-only, safe-conversion, and escalation controls;
- protected examples, questions, triggers, fields, and reusable habits remain separately identifiable;
- risk identification leads to Control selection before Control-specific methods;
- Unstated Context Control is not presented as the universal first Control;
- Control, Method, and Accountable Route remain distinct and every canonical name resolves to exactly one Control Map registry;
- the Glossary defines the architectural concepts without duplicating full individual canonical registry definitions;
- the Control Map contains both a Registry Entry Structure Standard and a separate Risk Relationship Entry Structure Standard;
- every canonical risk has one Control Map relationship entry that explains why listed Controls, Methods, and Accountable Routes may be relevant;
- the Control Map distinguishes the most directly related Controls from additional conditional Controls, and does not present Controls, Methods, and Accountable Routes as one undifferentiated list;
- Risk Library risk entries do not duplicate the exhaustive relationship map;
- Unstated Context Control does not reproduce the canonical risk-to-Control relationship map owned by the Control Map;
- Start Here teaches the short first-use route without reproducing the full detailed seven-route handling sequence;
- the Review Card presents risk-recognition cues in a scan-first format and may retain point-of-action checklists needed during review;
- Organisational Context Handling remains a short orientation rather than a second detailed unstated-context procedure;
- Glossary entries define and distinguish terms without reproducing long detailed recognition taxonomies or operating procedures owned elsewhere;
- package-wide repetition reinforces short memory cues or point-of-action safety rather than repeatedly teaching long lookup material;
- the current detailed-scope wording identifies Unstated Context Control as the current detailed Control while keeping identifying and safely eliciting unstated context as the deepest practical treatment;
- retrieval, extraction, and verification remain distinct, including within any combined retrieval-and-extraction Method;
- no speculative higher-level control grouping is introduced without owner-approved architecture.

---

### 16.12 Finding Severity

`P1` and `P2` are controlled finding-severity labels. They are not abbreviations for Purpose, Permission, or Proof.

Use **P1** for a confirmed issue affecting meaning, authority, approval, accountability, privacy, legal or professional boundaries, publication identity, required links, Markdown rendering, or risk treatment.

Use **P2** for a confirmed terminology, structural, UK English spelling, list-punctuation, conjunction, publication-formatting, shared-boilerplate, required-hard-break, heading, table, navigation, release, version, frontmatter, or Chinese publication-convention issue that does not change central governance meaning.

Use **Review only** where evidence, pairing, source authority, specialist terminology, translation meaning, reviewer standing, owner intent, or intended presentation remains uncertain.

---

### 16.13 Overall Status

Use **PASS** only when no actionable finding remains and every required deterministic and semantic check within the authorised execution boundary has been completed.

Use **REVIEW REQUIRED** when no confirmed correction blocker remains but an owner, bilingual, specialist, organisational, representative-reader, pairing, terminology, release, or publication decision remains unresolved.

Use **FAIL** when a confirmed actionable issue remains or a required input, extraction, decoding, structure, terminology, script, link, identity, release, version, or P1 rendering problem prevents reliable completion.

#### Translation-readiness gate

Do not treat a clean validator run, an author self-review, or an owner skim by itself as proof that the English package is ready for Stage 2 translation. Before the owner declares an English package **TRANSLATION READY**, require all of the following for that exact package:

1. no unresolved P1 or P2 finding;
2. a complete page-by-page fresh-reader and TC translation-stress review for every in-scope non-README public page;
3. one independent reviewer-neutral review of whether the package fulfils the owner-purpose acceptance criteria, with any sampling limitation stated explicitly;
4. all actionable semantic findings corrected, or explicitly accepted by the owner as no-change decisions;
5. governed-term coverage checked against the owner-designated external terminology authority, with no unresolved controlled-term gap;
6. the Author and Editor Guide, Review Toolkit, Validator, Translation Notes, and cross-file navigation reassessed against the final English content;
7. final package, authority, tool, and evidence identities recorded by content hash/version rather than relying only on uploaded outer filenames; and
8. an explicit owner declaration that this exact English package is **TRANSLATION READY** and is the frozen Stage 2 source baseline.

Any English source change after that declaration reopens Stage 1 and requires a superseding Stage 2 baseline rather than a silent translation-stage correction.

---

### 16.14 Review Reporting

A full review should provide:

- source and final direct inventories;
- changed, unchanged, added, removed, and renamed file report;
- source-to-final diffs for changed files;
- file-pairing map or pre-publication English-only not-yet-applicable result;
- package-wide rule-to-file coverage;
- prioritised actionable findings;
- immediate-child section-break findings;
- UK English, list-punctuation, conjunction, typography, and hard-break findings;
- README protection, protected-callout, and publication-language findings;
- version, release, frontmatter, and unchanged-file findings;
- semantic-preservation and BSG-model evidence;
- an owner-purpose reader-outcome review covering terminology consistency, general-adult comprehension, awareness and mitigation, and the first-use/return path;
- a reader-memory and purposeful-duplication review confirming that repeated material either reinforces a short memory cue, supports point-of-action use, or has another distinct reader function;
- a page-by-page fresh-reader and TC translation-stress coverage register for every in-scope non-README public page, including PASS / REVIEW REQUIRED, whether wording changed, whether material restructuring occurred, whether meaning preservation was confirmed, and a logic-trace reference where material restructuring occurred;
- a 12-risk purpose matrix recording whether each canonical risk explains what may go wrong, why it matters, the mitigation route, and any detailed-guidance boundary;
- a governed-term and fixed-translation coverage report against the owner-designated external terminology authority;
- UCG impact notification outcome;
- expected differences and controlled exceptions;
- false positives and acceptable wording dispositions;
- owner, bilingual, specialist, organisational, representative-reader, and publication decisions;
- limitations and final status.

Only actionable issues belong in the prioritised fix list. Do not include harmless raw differences or speculative findings without supporting evidence.

---

## 17. Maintenance and Change Control

### 17.1 Common Rules

Keep common editorial, structural, localisation, validation, versioning, packaging, publication, evidence, and reporting rules in this file rather than repeating them across every public file.

For every discrepancy confirmed by the owner, assess why the existing controls allowed it. Add or strengthen a preventive authoring rule, review rule, validator check, test, or combination of controls where practical. Do not close a recurring-class discrepancy only by correcting the current file.

For **every correction or full-pack change**, explicitly reassess whether this Author and Editor Guide, the current Review Toolkit, and the current Validator need a corresponding update. Record `no change required` when the existing control already covers the issue; do not update a component merely to create version churn.

---

### 17.2 File-Specific Rules

Keep a `Maintenance and Change Control` section in an individual file only where that file has a specific dependency, such as stable linked entry names, canonical wording adapted elsewhere, Risk Library and Control Map alignment, Review Card synchronisation, template-field alignment, protected examples, or reviewer-standing controls.

---

### 17.3 Related References

Add `Related References` only where the original or approved content has real and useful cross-file relationships. Do not add an empty or speculative section merely for symmetry.

Do not make a LinkedIn series, article, training session, unpublished explanation, presentation, or other external commentary a prerequisite for understanding or safely using this guide. External material may introduce, illustrate, explain, or promote this guide, but every mandatory instruction, control, boundary, route, and stop condition must remain available within the approved public package.

Write important definitions, controls, examples, boundaries, roles, risks, routes, decisions, and instructions so that they remain useful after the current release.

Do not present lasting guidance as a temporary release note, future promise, or unpublished plan.

Do not say that another guide, language edition, quick version, training resource, or supporting document exists unless it has been approved, published, and linked. If the owner approves a reference to future work, state clearly that it is not yet available and is not required to understand or safely use this guide.

---

### 17.4 Review Cycle

Review organisational adaptations and published guide maintenance on a defined schedule and after material changes to tools, policy, law, organisational roles, source systems, workflows, security controls, risk exposure, language, terminology authority, reviewer-standing arrangements, or BSG–UCG dependencies.

---

### 17.5 Frontmatter

Preserve established frontmatter fields and ordering unless a controlled migration is authorised.

Common fields include:

- `title`;
- `created`;
- `updated`;
- `version`;
- `tags`;
- `status`;
- `type`;
- `source-role`;
- `locale`;
- `licence`.

Keep `created` stable.

Every modified public file must contain an `updated` field set to the owner-approved correction date. Add the field if it is absent.

Do not change `updated` in a file that is otherwise unchanged. Unchanged files must remain byte-identical.

A file changed only to update `updated` is a defect.

Frontmatter tags and short label-style metadata values do not require terminal full stops. Do not add punctuation merely for visual consistency.

---

### 17.6 Document Versions

A document version belongs to one public file.

Before first publication:

- keep each existing public file at version `1.0`;
- do not increment the version for pre-publication editorial, structural, translation, typography, evidence, validation, or packaging corrections;
- change the version only if the owner explicitly starts a new published document version.

After publication:

- change only documents included in the owner-approved version update;
- keep unchanged files at their existing versions;
- keep each footer version identical to the frontmatter version.

Use the owner-approved standard footer for the artefact and language.

For the current BSG package, every non-README public Markdown file must use the approved short standard footer. `README.md` files are the documented file-role exception because they use their own approved navigation, contact, repository-path, and licence footer structure. Do not add the short standard footer to a README merely for visual symmetry.

In `en_HK`, use the approved short English licence wording with `CC BY 4.0`.

In the published `tc_HK` and `sc_HK` editions, use the full approved Traditional Chinese or Simplified Chinese licence name followed by `（CC BY 4.0）` in the corresponding footer.

The licence wording may follow an approved shared Win.Win pattern, but the version number must always match the current BSG file’s own frontmatter version. Do not copy a version number from another artefact, language file, package, or example.

Treat approved footer wording as controlled shared boilerplate. Do not shorten, expand, retranslate, or otherwise alter it unless the owner expressly approves a new footer pattern.

A document version is separate from the package release.

---

### 17.7 Package Releases and Release History

A package release is the published snapshot of the complete artefact.

Before first publication, keep the package release at `1.0` unless the owner explicitly changes it.

The release number appears in applicable README files.

A release may contain documents with different document versions after publication.

Record material reader-facing release changes, such as:

- a new public file;
- a significant risk, control, route, decision, authority, or approval change;
- a new language folder;
- a material package restructuring;
- an important scope, audience, or public-language change;
- a substantial new maintenance or adaptation capability.

Minor typography, punctuation, self-reference, evidence, validation, or packaging corrections do not need a release-history note unless the owner asks for one.

---

### 17.8 Index and Navigation Maintenance

When a public file is added, renamed, removed, or materially repurposed:

- update the applicable language-folder README index;
- update related navigation files and reader routes;
- use the exact local filename in each wikilink;
- preserve established localised naming patterns where translations exist;
- describe what the file helps the reader understand or do, not merely its file type;
- verify every new local link.

Review the root `README.md` for dependency impact and report any issue to the owner. The BSG author must not modify it.

When `en_HK/README.md` is otherwise in scope, preserve its protected Master Source callout exactly. Navigation, language-folder, metadata, or publication changes must not alter that callout.

---

### 17.9 Public Package and Evidence Separation

The public archive must contain only intended public files under the `public/` wrapper.

Do not place inside the public archive:

- external `file_list.txt` or equivalent file lists;
- checksum or hash manifests;
- review reports;
- validation outputs;
- change registers;
- comparison matrices;
- correction prompts;
- tool source code or tests;
- evidence files;
- temporary files.

Use direct ZIP inventory and direct source-to-final path and byte comparison for BSG package and change control.

Keep all evidence outside the public package.

---

## 18. Change Reporting

### 18.1 Minimum Change Report

Report the following.

**Source and scope**

- exact source package used;
- direct source and final inventories;
- files in scope and excluded;
- files added, removed, renamed, changed, unchanged, and deliberately unchanged;
- terminology authority used;
- owner-approved correction date.

**Content and structure**

- headings added, renamed, moved, split, or combined;
- newly written content;
- source of reorganised content;
- exact source and final locations;
- content retained, moved, split, combined, replaced, restored, or added;
- semantic meaning changed, if any;
- affected canonical terms, risks, routes, controls, roles, decisions, or boundaries;
- previous wording searched, dependent files checked, and stale occurrences corrected or retained with a recorded reason;
- approved source version used for any major rewrite;
- source-to-final and final-to-source semantic comparison results;
- protected examples, questions, triggers, fields, and habits checked;
- ordinary BSG self-reference checked so `This guide` or `this guide` is used instead of `The Guide`, `the Guide`, `The guide`, or `the guide`, except in protected or literal contexts;
- cross-file references, links, and anchors updated.

**Translation and publication**

- current working-language position and intended trilingual publication position;
- confirmation that the protected `en_HK/README.md` Master Source callout is unchanged;
- confirmation that the repository-level `public/README.md` is unchanged;
- source and translation pairing and certainty where translations are in scope;
- translation-structure review status or pre-publication English-only not-yet-applicable result;
- index and navigation changes;
- release-label and release-history changes;
- document-version, footer, frontmatter, and modified-date changes;
- confirmation that lasting guidance remains in the public package;
- confirmation that every referenced public resource exists and has an approved public path or link.

**Legal, regulatory, privacy, platform, and specialist review**

- tone review performed;
- current sources and dates checked where applicable;
- unresolved specialist, authority, standing, or safe-context decisions.

**BSG–UCG impact review**

- material BSG changes assessed against Section 9.6;
- current UCG references reviewed where a trigger applied;
- UCG impact assessed as correction required, not required, or uncertain;
- exact owner notification status;
- confirmation that UCG was not edited unless expressly in scope;
- unresolved owner, bilingual, specialist, publication, or destination decisions.

**Validation and status**

- validator and review toolkit used;
- source, Phase A, package-wide, and final validation performed;
- deterministic findings and dispositions;
- semantic and owner-review candidates and dispositions;
- unresolved judgement calls;
- qualified-human, bilingual, organisational, representative-reader, owner, or publication review required;
- final status.

Do not remove a reporting requirement merely because it does not apply to the current task. Mark it `not applicable` with a reason where necessary.

Do not include checksums, hash manifests, or an external file list where the BSG direct-inventory rule applies.

---

### 18.2 Provenance Rule

Do not describe a change as simple formatting when it alters meaning, control strength, scope, authority, escalation, translation alignment, release information, public-language position, or downstream dependencies.

If content is combined or split, identify the original headings, labels, paragraphs, list items, table rows, examples, or template fields used.

If a translated file is created or updated, record the exact approved source file and version.

---

### 18.3 Standard Outputs for a Full Pack Generation

When a ChatGPT-assisted author generates a complete successor BSG pack, provide the following as standard outputs unless the owner explicitly narrows the deliverables:

1. the revised public BSG package ZIP;
2. the current standalone **Author and Editor Guide**;
3. the current **Review Toolkit**;
4. the current **Stage 1 Validator**;
5. validation evidence, including the final validator summary and regression-test result;
6. the page-by-page fresh-reader and TC translation-stress review evidence for the clarity scope;
7. a changed-file register or equivalent exact change report, including a **tooling-control reassessment** that records whether the Author and Editor Guide, Review Toolkit, and Validator were revised or why no change was required;
8. a **GitHub commit-message Markdown file** based on the final exact diff, stating what changed and why;
9. an **independent-AI review brief Markdown file** that another AI reviewer can use without relying on the author’s remembered intent; and
10. one consolidated ZIP containing the current downloadable deliverables.

If an owner-designated terminology authority is a governing input for the pack, identify it in the evidence and consolidated deliverables without silently modifying it.

The GitHub commit message must describe the actual final change scope, not an earlier draft or intended change list. Include the main reason for the changes and note important preserved boundaries when they are material to understanding the diff.

The independent-AI review brief must be reviewer-neutral. Do not assume a particular reviewer name. It should identify the exact pack and baseline, summarise what changed and why, state the owner-purpose acceptance criteria, focus the review on concrete defects or worthwhile comprehension improvements, require meaning-preservation and TC translation-stress checks where relevant, and discourage broad stylistic rewriting without a demonstrated reader or governance benefit.

These two Markdown files are standard deliverables for a full pack generation even when the owner has not separately requested them in that turn.

---

### 18.4 Final Boundary

This guide supports consistent authoring, editing, review, validation, and evidence preparation. It does not replace owner judgement, qualified specialist review, bilingual human review, organisational approval, representative-reader evidence, or evidence from real use.

AI-assisted work and a zero validator exit code do not prove semantic equivalence, control sufficiency, safe disclosure or recording, real reviewer standing, qualified review, owner acceptance, translation readiness, publication readiness, or practical usefulness.

Final publication and acceptance decisions remain with the Win.Win artefacts owner.

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Blind Spot Guide Feedback Form](https://forms.gle/se5ruqaZeytDoFENA)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
