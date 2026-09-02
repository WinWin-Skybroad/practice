---
title: Author and Editor Guide
created: 2026-07-17
updated: 2026-08-14
version: "1.0"
tags:
  - WinWin-Skybroad
  - use-case-guide
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

This guide explains how to author, edit, customise, localise, review, validate, publish, and maintain the Win.Win AI Use Case Guide (UCG).

This guide is for Win.Win maintainers, organisations adapting UCG, authors and editors, reviewers and specialists, translators and bilingual reviewers, and AI assistants supporting controlled work.

The named audience for UCG is individuals, churches, nonprofits, and small and medium-sized enterprises (SMEs). Other readers may adapt it to their context without weakening mandatory controls.

This guide helps preserve the structure, meaning, governance boundaries, and usability of the published material while allowing appropriate organisational adaptation.

---

### 1.1 Purpose Fidelity

The Win.Win AI Use Case Guide is the practical **“then, how?”** layer above the Win.Win AI Essentials.

In this Author and Editor Guide, the **Win.Win AI Blind Spot Guide (BSG)** may be abbreviated as **BSG** after this definition. UCG and BSG are used only for authoring, maintenance, review, validation, and evidence work. Do not assume that a reader-facing file has defined or should use either abbreviation.

The Win.Win AI Essentials explains why responsible AI use requires Purpose, Permission, and Proof. This guide operationalises those responsibilities for real administrative tasks:

- task selection, scope, intended use, and expected consequence support **Purpose**.
- source, data, tool, authority, access, and process boundaries support **Permission**.
- task-specific review, verification, evidence, records, explanation, correction, approval, and escalation support **Proof**.

These responsibilities overlap across the workflow. Do not describe prompting as only Purpose and Permission, human review as the whole of Proof, or the Use Case Guide as a human-review-only guide.

This guide treats source preparation, prompting, human review, mitigation, escalation, recordkeeping, workflow design, and learning after mistakes as one control system.

Human review receives more guidance because it may require judgement about context, importance, audience, authority, competence, and consequences. One prompt checklist cannot replace that judgement.

A complete source packet and a well-scoped prompt can reduce preventable errors, unsupported assumptions, unnecessary output, and rework.

They do not lower the review standard. They also do not replace review, independent verification, authority, qualified judgement, escalation, or stop rules.

When reviewing whether UCG fulfils its purpose, check whether readers can move from a real task to preparation, prompting, review, mitigation, approval, correction, recording, or escalation.

Do not judge this guide only by word count, equal section length, or the number of prompt and review patterns.

> [!important] Customisation does not authorise weaker governance
> Do not remove or weaken required human accountability, authority boundaries, source and evidence requirements, privacy controls, professional-review requirements, escalation conditions, or stop rules merely to make a workflow easier.

---

### 1.2 Finding the Rules You Need

Most readers do not need every section for every task. Start with Sections 1–3, then use the route that matches your work.

| Your task | Main sections |
|---|---|
| Make a small wording or formatting correction | 3.2, 5, 9–11, 14, and 16–18 |
| Reorganise existing content | 3.1, 7–9, 11, and 16–18 |
| Add, remove, rename, or repurpose a file | 6–10 and 15–18 |
| Adapt UCG for an organisation | 4–5, 11, and 16–18 |
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
| **Independent verification** | Checking a point against a suitably separate approved source, tool, record, or reviewer rather than relying only on the same output or owner confirmation. |
| **Material** | Important enough to affect meaning, risk, control, authority, approval, reader action, or publication. |
| **Standing** | The role, competence, authority, permission, and independence needed to perform a task or review. |
| **Substantive change** | A change to meaning, scope, risk, control, authority, approval, or reader action—not only wording or layout. |
| **Traceability** | Being able to follow a term, risk, control, or change from its approved source to the files that use it. |
| **Document version** | The version of one public file. |
| **Package release** | The published snapshot of the complete artefact. |

These definitions support the rules below. They do not replace file-specific definitions or the Risk Taxonomy.

---

## 2. Who This Guide Is For

### 2.1 Win.Win Maintainers

Use this guide to preserve canonical content, maintain cross-file relationships, prepare releases, and keep the language versions aligned.

---

### 2.2 Organisations Customising This Guide

Use this guide to adapt roles, systems, policies, terminology, review routes, use cases, and escalation paths to the organisation’s real operating context.

---

### 2.3 Authors and Editors

Use this guide when creating new files, restructuring existing files, revising wording, adding examples, correcting Markdown and links, or preparing a release.

---

### 2.4 Reviewers and Specialists

Use this guide to understand which changes require bilingual, legal, privacy, employment, finance, cybersecurity, safeguarding, medical, psychological, pastoral, theological, technical, or other qualified review.

---

### 2.5 Translators and Bilingual Reviewers

Use this guide to preserve approved meaning, control strength, terminology, titles, structure, and Hong Kong context across `en_HK` (Hong Kong English), `tc_HK` (Hong Kong Traditional Chinese), and `sc_HK` (Hong Kong Simplified Chinese).

---

### 2.6 AI Assistants

Use this guide as operational context when supporting authoring, editing, comparison, localisation, validation, evidence preparation, or packaging. AI assistance does not replace owner or qualified-human approval.

---

## 3. Types of Change

### 3.1 Structural Change

A structural change moves, groups, splits, combines, renames, relevels, or renumbers headings and content without intending to change meaning.

Even a structural change may affect heading anchors, links, navigation, interpretation, emphasis, translation alignment, and maintenance traceability.

**Example:** Move a subsection to a clearer location without changing its meaning.

---

### 3.2 Editorial Change

An editorial change improves clarity, grammar, consistency, plain language, typography, punctuation, or formatting without intending to change the control, obligation, scope, authority, risk, or reader action.

**Example:** Shorten a sentence without changing the requirement or reader action.

---

### 3.3 Substantive Governance Change

A substantive change alters a framework, obligation, prohibition, risk, control strength, approval condition, authority boundary, review requirement, escalation threshold, disclaimer, specialist boundary, source requirement, audience, or organisational responsibility.

Substantive changes require explicit owner approval and any qualified review appropriate to the subject.

**Example:** Change who must approve an output or when a task must stop.

---

### 3.4 Organisational Customisation

Organisational customisation replaces or supplements generic content with approved local roles, systems, tools, policies, sources, terminology, controls, decision rights, and escalation routes.

**Example:** Replace a generic role with the organisation’s actual approved role.

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

Use this section as a working sequence:

```text
understand the organisation
→ select the relevant use cases
→ assign real roles and authority
→ adapt review, controls, and prompts
→ define escalation
→ link approved sources
→ record what changed
```

---

### 4.1 Define the Organisational Context

Record the organisation, sector, intended users, jurisdictions, operating environment, data types, approved AI tools, source systems, policies, and purpose of the adaptation.

---

### 4.2 Identify Applicable Use Cases

Select use cases that match real organisational tasks. Do not adopt a use-case page merely because it appears useful or low-risk.

---

### 4.3 Assign Roles and Authority

Replace generic roles with real organisational roles. Identify who may propose, prepare, review, correct, approve, publish, escalate, stop, or act.

Do not use a role title as proof that the person has the required competence, context, source access, authority, independence, or approved process.

---

### 4.4 Adapt Review and Approval Requirements

Specify the source or real-world reference, reviewer, timing, warning signs, decision supported, approval route, and escalation boundary for each important check.

---

### 4.5 Adapt Risks and Controls

Retain applicable canonical risk meanings. Remove inapplicable examples, specify real task objects, add missing local risks, and preserve the minimum control obligation.

---

### 4.6 Adapt Prompt Content

Use the applicable base prompt pattern and only the prompt enhancements relevant to the task. Replace generic placeholders with approved sources, audiences, terminology, limits, authority boundaries, uncertainty markers, and output requirements.

---

### 4.7 Adapt Escalation Routes

Name the actual accountable person, role, committee, professional adviser, incident route, or stop route.

Do not invent a specialist role or review process that does not exist.

---

### 4.8 Add Organisation-Specific References

Link only approved policies, procedures, source repositories, forms, systems, official guidance, and contacts.

Check that each source and link remains current and accessible to the intended reviewer.

---

### 4.9 Record Organisational Deviations

Keep the published Win.Win content distinguishable from the organisation’s approved adaptation.

Record at least:

**Source version:** Win.Win AI Use Case Guide [release]

**Organisation:** [name]

**Customisation owner:** [role]

**Approved by:** [role or authority]

**Approved date:** [date]

**Sections changed:** [list]

**Reason for change:** [explanation]

**Local policies or sources:** [list]

**Next review date:** [date]

Do not imply that Win.Win@Skybroad approved an organisation’s adaptation unless that approval was explicitly given.

---

## 5. What Must Not Be Customised Away

### 5.1 Human Accountability

A human or accountable organisational body remains responsible for what is sent, published, approved, relied on, or acted on.

Do not imply that AI output, AI self-review, a detailed prompt, or a completed checklist transfers accountability to the tool.

---

### 5.2 Authority Boundaries

Drafting, reviewing, correcting, approving, publishing, and acting are different authorities. Do not merge them merely because one person performs several roles.

---

### 5.3 Required Review

Do not remove a review because the task appears routine, the prompt is detailed, the AI has worked before, or the output sounds polished.

---

### 5.4 Privacy and Confidentiality

Do not weaken data minimisation, approved-tool, access, confidentiality, personal-data, pastoral, human resources (HR), client, beneficiary, donor, employee, volunteer, congregation, or commercially sensitive boundaries.

---

### 5.5 Source and Evidence Requirements

Do not replace source comparison, source checking, independent verification, authenticity checks, or real-world confirmation with AI self-review.

When a review says that important meaning was preserved, it must show where that meaning appears in the final file. A heading, keyword, search count, yes/no result, or pass label is not enough.

Information from an owner may help verify a point where that person has the right knowledge, authority, responsibility, and source access. However, being the owner does not make the person independent. Where independent verification is required, use another suitable source, tool, record, or reviewer.

---

### 5.6 Escalation and Stop Conditions

Preserve stop and escalation conditions where the reviewer lacks evidence, authority, competence, context, independence, source access, or an approved process.

---

### 5.7 Professional and Specialist Boundaries

Do not turn AI-generated or generally reviewed content into legal, regulatory, financial, employment, medical, psychological, safeguarding, cybersecurity, pastoral, theological, technical, or other specialist approval.

---

## 6. File Types and Their Roles

### 6.1 README Files

A `README` (“read me”) file introduces a package or folder and helps readers navigate it. The root `README.md` is owner-controlled and must not be changed unless the owner explicitly includes it in scope.

In this guide, `H1` to `H5` mean Markdown heading levels 1 to 5.

#### What README files are exempt from

Repository-level and language-folder `README.md` files do not need:

- numbered H2 or H3 headings.
- `---` section breaks before H2 or H3 headings.

Do not report either difference as a formatting or structural failure.

#### What still must be checked

README files must still be checked for:

- heading hierarchy and required sections.
- navigation, indexes, and registers where applicable.
- duplicate headings and broken anchors.
- links, release information, and rendering.

---

### 6.2 Language Folders and Source Roles

The package is organised into:

- `en_HK/` — English master source for Hong Kong.
- `tc_HK/` — Traditional Chinese translation for Hong Kong.
- `sc_HK/` — Simplified Chinese translation for Hong Kong.

A language folder represents a complete public language edition only when all approved public files for that edition have been translated, reviewed, indexed, and linked.

During a staged translation process, a language folder may contain only the approved files completed so far. Do not describe that folder as a complete published edition.

When a language edition is complete, it must be independently usable. Do not make it depend on another language folder for a public file, instruction, or link.

Author substantive changes in `en_HK` first unless the owner explicitly authorises another source.

After the English source is approved:

- translate the approved source into `tc_HK` and `sc_HK`.
- review each translation against the approved English source.
- preserve the same control strength and intended reader action.
- keep local filenames, links, indexes, registers where applicable, and navigation complete.

---

### 6.3 Reference Files

Reference files define reusable patterns, risks, mitigations, decisions, taxonomies, escalation guidance, or authoring rules. Repeated-entry references must define an Entry Structure Standard.

---

### 6.4 Use-Case Pages

#### What use-case pages contain

Use-case pages contain task-specific prompting, review, risk, mitigation, escalation, and related-reference guidance. They apply approved reference material to a real task rather than replacing the reference material.

#### Where companion guidance belongs

Use-case pages should contain:

- a clear route to the relevant companion guidance.
- the task-specific reason for using that guidance.

Keep the companion’s full purpose, current detailed focus, definitions, internal routes, handling model, and scope boundaries in its named subsection under `Companion Guides` in `How To Use This Guide`.

For the Win.Win AI Blind Spot Guide, use the approved local route to its named subsection. Do not repeat the complete Blind Spot Guide explanation on every use-case page.

#### When a later Blind Spot Guide is supplied

Section 9.5 explains which BSG changes may affect UCG. Section 16.9 explains how to perform the review.

Review the canonical subsection first. Then change a use-case page only where its route or task-specific trigger has become stale, incomplete, inaccurate, misleading, broken, or insufficient for the task.

Give every future companion artefact its own named subsection and clearly named page-level route.

---

### 6.5 Templates and Cards

Templates and cards provide reusable working structures. Keep instructional text distinguishable from content intended to be copied or completed.

---

### 6.6 Sample Overall Prompts

Sample prompts demonstrate how base prompt patterns and selected task-specific add-ons can be assembled. They are examples, not mandatory master prompts.

---

### 6.7 Author and Editor Guides

Author and Editor Guides define reusable authoring, editing, translation, adaptation, review, validation, versioning, packaging, and publication rules. Keep common rules here rather than repeating them throughout every file.

---

## 7. Heading Structure

### 7.1 Heading Levels and Numbering

Use one unnumbered H1 for the file title.

Number every H2 as `1.`, `2.`, `3.` within a non-README file.

Number every H3 as `1.1`, `1.2`, `2.1` under its parent H2.

Do not number H4.

Use H4 as the normal maximum heading depth. Avoid H5.

Repository-level and language-folder README files are exempt from H2 and H3 numbering.

---

### 7.2 Canonical Section Names

Use the approved heading where two sections perform the same function. Use a different heading only where the function is genuinely different.

When sections in different files serve the same purpose, use the same published heading name. Do not introduce synonyms merely for stylistic variety.

Common names include:

- `Purpose and Scope`.
- `How To Use This Reference`.
- `Entry Structure Standard`.
- `Mandatory Sections`.
- `Optional Sections`.
- `Related References`.
- `Maintenance and Change Control`.
- `When to use this`.
- `What review must check`.
- `What it cannot do`.

Use a different name only when the content function is materially different.

**Layer names**

Where a Win.Win AI guide separates directly usable material from deeper explanation, use:

- **Practical Layer** — files used directly during a real task or review.
- **Reference Layer** — files used for deeper explanation, consistent methods, training, adaptation, or maintenance.

Use these names across guides where the functions are equivalent.

For Author and Editor Guides, use these shared H2 names where the purposes are equivalent:

- `Purpose and Scope`.
- `Who This Guide Is For`.
- `Types of Change`.
- `What Must Not Be Customised Away`.
- `File Types and Their Roles`.
- `Heading Structure`.
- `Entry Structure Standards`.
- `Cross-References and Traceability`.
- `Headings, Bold Labels, and Callouts`.
- `Writing and Plain-Language Rules`.
- `Translation and Localisation Rules`.
- `Chinese Markdown Rules`.
- `Markdown and GitHub Formatting Rules`.
- `Using AI Assistants for Authoring and Editing`.
- `Pre-Publication Review and Validation`.
- `Maintenance and Change Control`.
- `Change Reporting`.

Where a shared heading contains a self-reference, use the correct artefact term. For example:

- UCG: `Customising This Guide for an Organisation`.
- AI Essentials: `Customising This Kit for an Organisation`.

---

### 7.3 Headings Versus Bold Labels

Use a heading where the content forms a genuine section or subsection.

Under an H3, use an unnumbered H4 where readers may need to:

- find the content through navigation or a table of contents.
- link directly to it.
- review or maintain it separately.
- distinguish it from parallel rules or process stages.
- read several paragraphs, a substantial list or table, or a distinct procedure beneath it.

Use a bold label where the content is a compact local part of the current section, such as:

- a short field or category.
- an example.
- a `Use` or `Avoid` label.
- a checklist group.
- a report group.
- a brief label introducing one paragraph or list.
- an author action, review check, or evidence label that does not need separate navigation.

Use this practical test:

```text
Could a reader reasonably ask to go directly to this part?
→ use a heading

Does it only introduce a short part of the current section?
→ use a bold label
```

A heading normally introduces content with its own purpose. A bold label normally introduces content that remains part of the purpose of the current heading.

Length alone does not decide the structure. However, a bold-labelled block containing several paragraphs, a substantial list or table, a distinct rule or process stage, or independently maintained guidance should normally become an H4.

Do not use a bold label merely to avoid an H4 where the content functions as a genuine subsection.

Do not use an H4 only for visual emphasis where a short bold label is enough.

Items that perform the same function at the same structural level should use the same treatment. Do not mix headings and bold labels among parallel items unless their functions are genuinely different.

Examples:

```md
#### Where companion guidance belongs

Use a heading because this is a distinct rule that readers may need to find, link to, review, or maintain separately.

**Affected files:** [list]

Use a bold label because this is a compact local field within the current subsection.
```

---

### 7.4 Repeated-Entry Collections

Group repeated entries under one numbered collection heading such as `Patterns`, `Risks`, `Controls`, `Mitigations`, `Reviewer Decisions`, `Checklist Items`, `Policy Rules`, or `Risk Families`.

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

---

### 8.4 File-Specific Standards

#### Existing collections

Follow the Entry Structure Standard in the relevant file. Different entry types have different functions and may need different mandatory sections. Preserve an existing repeated-entry pattern unless the owner approves a structural change.

#### New collections

For a new repeated-entry collection, define:

- the entry name and purpose.
- mandatory fields or sections.
- optional fields or sections.
- links or dependencies.
- review and maintenance requirements.

#### Short routes and quick versions

A quick-start route, summary, triage, shortened checklist, or thin companion route may simplify navigation. It must not create approval authority, extend standing, weaken a control, remove a source, review, escalation, or stop requirement, or allow a high-risk, specialist, uncertain, restricted, human-only, or multi-person process to be skipped.

A thin route points to the full guidance. It does not replace the full guidance or the task-specific controls in the originating file.

Do not add a separate shortened public file merely because the full guidance appears dense. First require:

- evidence from representative readers or real use that a shorter route is needed.
- owner approval.
- assessment of package, translation, navigation, validation, and maintenance effects.
- evidence that the shorter route preserves every required boundary.

#### Reorganising content

Changing the structure—such as grouping, shortening, or reorganising content—must not remove an important control.

Keep every task-specific instruction that tells the reader:

- which source to use.
- what not to do.
- what must stay outside AI.
- who must review or approve.
- when to stop or escalate.
- what must be recorded.

When reproducing a framework, decision path, checklist, or approved set of items, keep its approved labels and meanings. Preserve the number and order where these are part of the model. Make clear whether the items are steps, alternatives, criteria, or separate controls.

---

## 9. Cross-References and Traceability

This section explains how to keep approved names, links, and dependent files aligned when something changes.

---

### 9.1 Canonical Titles and Stable Names

Published risk, prompt-pattern, review-pattern, mitigation-family, reviewer-decision, taxonomy, and use-case names may be linked from other files. Do not rename them casually.

Preserve formal published titles exactly unless the owner approves a title change.

Preserve the exact prompt-pattern title `Answer a Policy Question`.

Use the current package, Use Case Register, and canonical reference files as title authorities rather than maintaining a duplicate fixed title inventory here.

In reader-facing content, use the complete formal artefact name at first mention in each standalone file, adding `the` where normal English grammar requires it. After that first mention, use `this guide` for Win.Win AI Use Case Guide self-reference and `the Blind Spot Guide` for the named companion where the reference remains unambiguous.

Do not use `UCG`, `BSG`, or another internal abbreviation in reader-facing content unless it is defined at first use and provides a clear reader benefit. Companion-guide headings, labels, and navigation routes must identify the specific formal artefact.

Use the current approved terminology source for the publication. Keep approved terms and meanings consistent. Do not replace an approved term with a similar word where that could change, weaken, broaden, narrow, or blur the meaning.

In content for new readers, briefly explain or link an unfamiliar approved term the first time it appears.

Use three risk-name levels consistently:

- **Risk family** — the broad category in [[Risk Taxonomy]].
- **Reusable named risk** — a canonical human-review risk defined in [[Human Review Risk Library]].
- **Task-specific risk or failure mode** — a narrower manifestation defined on a use-case page and indexed in [[Risk Taxonomy#4. Named Risk and Failure-Mode Index|Named Risk and Failure-Mode Index]].

Every risk or failure-mode name used in **Main Risks**, **Other Risks To Watch**, a prompt-enhancement `Risk` cell, or **What this helps with** must have an approved definition and traceability route. Reuse an existing defined name when the meaning is the same. Do not introduce a new label merely for stylistic variety, shorthand, or a prompt-table convenience.

Where a task-specific risk or failure mode has an approved relationship to a reusable named review risk, keep both names visible and distinct. Where the reusable risk’s `Affected use cases` field includes the page, use the pattern `Task-specific risk name — related review risk: [[Human Review Risk Library#target|Reusable named risk]]` in the applicable task-specific risk entry.

The task-specific name identifies the narrower manifestation in that use case. The explicitly named reusable risk links the reader to the canonical review guidance in [[Human Review Risk Library]]. Do not use the task-specific name as the visible alias of a differently named reusable risk. Do not omit the task-specific name by replacing it with only the reusable risk name.

An `Affected use cases` relationship means that the use-case page explicitly names the reusable named risk. The explicit `related review risk` pattern satisfies that traceability requirement while preserving the distinct task-specific name.

Every name used under **Common forms** in [[Risk Taxonomy]] must use the exact name in the [[Risk Taxonomy#4. Named Risk and Failure-Mode Index|Named Risk and Failure-Mode Index]], and that index entry’s **Typical family** must include the risk family where the common form appears. Where the same defined risk genuinely spans more than one family, list each applicable family in the index. Do not merge, confuse, or substitute a materially different risk merely to force alignment.

Keep important distinctions clear in definitions, examples, translations, validation, and review evidence. For example:

- review is not the same as verification.
- drafting is not approval.
- a responsible person is not necessarily the responsible owner.
- a source owner is not necessarily the decision owner.
- the way a risk appears in one task is not the same as its broader category in the Risk Taxonomy.
- recording something is not approval.

---

### 9.2 Filenames, Wikilinks, Heading Links, and Aliases

Preserve approved filenames exactly.

When a numbered H2 or H3 changes, update every Obsidian or Markdown link that targets the heading. Preserve a readable alias so readers see the entry name rather than the number where appropriate.

A local wikilink must point to a file in the same language folder unless the link is intentionally external.

When a file is added, removed, renamed, or materially repurposed:

- update the applicable local README index or register.
- update every affected wikilink and heading link.
- update translated equivalents.
- validate the complete package.

Use the exact local filename in each wikilink.

Where a translated README shows the English title in parentheses, preserve that established pattern.

---

### 9.3 Canonical and Adapted Content

Keep reusable canonical meaning in the approved reference or source file and task-specific or organisational implementation in the relevant adapted file.

Keep the published Win.Win source distinguishable from organisational adaptation.

Where local material supplements canonical content, state what is local, who approved it, and which source release and document version it adapts.

---

### 9.4 Cross-File Change Impact

Before completing a change, check whether it affects use-case pages, templates, cards, Sample Overall Prompts, risk links, prompt-pattern links, mitigation families, review methods, escalation guidance, the Risk Taxonomy, the Use Case Register, language versions, indexes, or navigation files.

When a risk name, legal or privacy framing, control statement, consequence explanation, authority boundary, specialist qualification, prompt pattern, or use-case title changes, search the complete package for the previous wording.

Do not treat the change as complete until:

- every intended dependency uses the current wording.
- no unintended stale occurrence remains.
- Sample Overall Prompts teach the same risk and control model as their source use-case page.
- renamed descriptions of how a risk appears in a task remain traceable to the broader category in the Risk Taxonomy and the applicable control objective.
- translated files, indexes, registers, and links remain aligned.

---

### 9.5 UCG–BSG Reference Dependency

This subsection explains **when** a BSG change may require UCG review. Section 16.9 explains **how** to perform that review.

#### When review is required

When the owner supplies a later Win.Win AI Blind Spot Guide package, use it as the current source for checking UCG references to the Blind Spot Guide.

Review possible UCG impact where the later BSG changes:

- its broad purpose, scope, or current detailed focus.
- a canonical term, definition, risk name, decision label, or important distinction used by UCG.
- the meaning of AI Blind Spot, unstated context, organisational context, representability, elicitation, retrieval, verification, preservation, or another UCG reference.
- where relevant context may exist or how it may be represented and handled.
- a public title, filename, purpose, route, function, or approved public destination.
- routing among the AI Blind Spot Control Map, Organisational Context Handling, Unstated Context Control, Elicitation Techniques, or other supporting guidance.
- what BSG explains in detail, introduces as supporting guidance, routes elsewhere, or places outside its detailed scope.
- a boundary involving safe conversion, human-only handling, independent verification, accountable or specialist review, stopping, escalation, recording, organisational memory, or preservation.
- whether surfaced context may enter AI, remain outside AI, be recorded, or be preserved.
- the relationship between UCG and BSG, including independent usability, publication status, availability, or whether the companion is optional, recommended, or required.
- an approved English, Traditional Chinese, or Simplified Chinese title or term used by UCG.
- wording that remains literally true but has become incomplete, misleading, or insufficient for the reader’s task.

Where impact is uncertain, review the UCG reference rather than assuming that no change is needed.

#### Changes unlikely to affect UCG

A BSG change does not normally require UCG correction where it affects only:

- punctuation or typography.
- internal formatting.
- evidence packaging.
- an internal example that does not change approved meaning.
- translation naturalness without changing a title, term, scope, route, boundary, or reader action.
- package metadata that does not affect publication status, availability, filename, path, or destination.

#### Where detailed guidance belongs

Keep BSG purpose, current-focus, scope-boundary, and internal-routing detail in the named Blind Spot Guide subsection of `How To Use This Guide`.

Use-case pages should contain only:

- the approved route.
- the task-specific trigger.

A material BSG change does not automatically require every use-case page to change.

#### Evidence and work boundaries

Review the current UCG package against the supplied BSG package. A change notice, earlier report, remembered wording, or old occurrence list may help, but it does not replace a fresh review.

Do not maintain a permanent dependency map or standing occurrence register as a second master source. Create the occurrence register or comparison evidence again for each package review.

Do not edit the Win.Win AI Blind Spot Guide during a UCG-only task unless the owner explicitly includes it in scope.

---

## 10. Headings, Bold Labels, and Callouts

### 10.1 Callout Types

Use callouts selectively for information that deserves to interrupt normal reading.

Use these technical identifiers:

- `[!note]` for supporting context or interpretation guidance.
- `[!tip]` for optional practical help.
- `[!important]` for a requirement the reader must not overlook.
- `[!warning]` for a stop condition, prohibited action, or escalation trigger.
- `[!caution]` only for a serious and potentially irreversible consequence.

---

### 10.2 Callout Rules

A file or section may contain more than one callout where each callout has a clear and distinct purpose. Do not impose a fixed maximum number of callouts.

Avoid unnecessary repetition, fragmented guidance, contradictory callouts, or multiple callouts that compete for attention.

Review callouts for valid Markdown and Obsidian syntax, lower-case identifiers, clear purpose, appropriate placement, readable GitHub rendering, correct links and hard breaks, and proportional use.

Do not use callouts as substitutes for structural headings or mandatory entry sections.

Do not repeat the same generic warning throughout many files. Put common guidance in this guide and retain file-specific warnings where they materially help the reader.

Do not place callout syntax inside copyable prompts unless it is intentionally part of the prompt.

Keep the technical callout identifier in English. Localise the visible title and content where appropriate.

**Use**

```md
> [!warning] Stop before publishing
> Do not publish until the named approver has reviewed the final output.
```

**Avoid**

```md
> [!NOTE]
> Important information.
```

The second example uses an upper-case identifier and does not explain the action.

---

## 11. Writing and Plain-Language Rules

### 11.1 Preserve Meaning and Control Strength

Do not silently remove, merge, weaken, or invent frameworks, risks, controls, caveats, review requirements, approval conditions, escalation boundaries, examples, or mitigation.

---

### 11.2 Plain Language

Prefer concrete verbs, named roles, named sources, clear conditions, and direct consequences. Avoid vague instructions such as “review carefully” where the actual check can be named.

Write for readers who may be new to AI governance.

Prefer:

- short, complete sentences.
- active voice where responsibility matters.
- specific review actions.
- defined technical terms.
- durable wording that does not depend on an unstable file, asset, pattern, or use-case count.

Avoid:

- unexplained jargon.
- inflated claims.
- fear-based language.
- unnecessary legal or technical detail.
- stylistic variety that changes a canonical term.

Use UK English spelling consistently throughout `en_HK` ordinary prose, headings, tables, callouts, examples, templates, and guidance. Use forms such as `organisation`, `customise`, `localise`, `authorise`, `recognise`, `behaviour`, `licence` as a noun, `license` as a verb, `practice` as a noun, `practise` as a verb, `centre`, `programme` for a non-computing plan or activity, and `program` for computing.

Retain another spelling only where it is part of an exact official title, product or platform label, filename, path, URL, code value, command, technical literal, approved controlled term, validation string, or exact quotation. Do not mix UK and US spelling merely because a comparison source or earlier draft uses different spelling.

The formal names **Win.Win AI Essentials**, **Win.Win AI Use Case Guide**, and **Win.Win AI Blind Spot Guide** do not include the article **the**. In running English prose, add **the** immediately before any of these formal names where normal grammar requires the definite article. Apply the same grammatical rule consistently across all three artefacts. Do not add **the** inside a formal title, filename, path, link label, table entry, source-version field, or other exact controlled name unless it is genuinely part of that controlled text.

When referring to the Win.Win AI Use Case Guide itself, write **this guide** in body text and **This guide** at the beginning of a sentence. In Markdown headings, write **This Guide**. Do not write **the guide**, **The guide**, **the Guide**, or **The Guide** for this self-reference.

Preserve the formal title **Win.Win AI Use Case Guide**, file titles, wikilink targets, and the names of other guides. Apply this rule only to self-reference, not as a global replacement of the word **the**.

In reader-facing English Markdown prose, headings, tables, callouts, captions, and sample content, use the typographic apostrophe **’** for contractions and possessives. For paired single quotation marks, use **‘…’**.

Retain U+0027, the straight apostrophe in the American Standard Code for Information Interchange (ASCII) character set, only where machine syntax, code, commands, paths, identifiers, regular expressions, literal search terms, or exact source quotation requires it. Review the context before changing punctuation; do not apply an unrestricted replacement to machine-oriented content.

When a review or validation term is necessary, explain it in everyday words the first time. State what the author or reviewer must do before naming the formal term. Keep machine-readable evidence labels in reports, registers, and validation outputs rather than ordinary guidance unless the reader must enter that exact value.

Define a non-common abbreviation at its first ordinary-prose use in each independently usable public file. Write the full approved term first, followed by the abbreviation in parentheses. After that, the abbreviation may be used alone where it remains clear. Do not rely on a definition in another file. If readers may not know the abbreviation, define it.

An abbreviation inside frontmatter, a filename, path, URL, package name, command, code, inline code, checksum, locale value, exact status label, or another controlled technical identifier does not need to be rewritten merely to create a prose definition. If the same term appears in ordinary prose, explain it at its first ordinary-prose use.

Preserve an owner-approved standard footer exactly. The approved English footer may use the controlled identifier `CC BY 4.0` because the corresponding README gives the full licence name. The approved Traditional Chinese and Simplified Chinese footers include the full localised licence name followed by `CC BY 4.0`. These are controlled footer patterns and do not permit unexplained abbreviations elsewhere.

Where a controlled short label has no approved full form, explain its function instead of inventing an expansion.

---

### 11.3 Lists

Use numbered lists only where order, sequence, ranking, or a fixed decision process is meaningful.

Use bullet lists for alternatives, examples, criteria, roles, risks, controls, and non-sequential options.

Use one list style consistently within each list.

For standalone or self-contained bullets:

- write each item as a complete point.
- use consistent ending punctuation.
- normally end full-sentence items with a full stop.
- do not add `and` or `or` before the final item.

Use `and` before the final item only where all listed actions, conditions, or requirements apply together and the bullets intentionally form one grammatical sentence.

Use `or` before the final item only where the listed items are alternatives and one or more may apply.

Where a bulleted list intentionally forms one grammatical sentence:

- punctuate the earlier items consistently, normally with semicolons.
- place `and` or `or` at the end of the penultimate item.
- end the final item with a full stop.

Do not mix standalone-list style with sentence-list style within one list.

Do not use `and/or`. State clearly whether all items apply, any one item may apply, or one or more items may apply.

---

### 11.4 One Function at a Time

Keep one risk, control, decision, prompt function, review function, approval condition, escalation route, or recording requirement per row or item where practical.

Do not combine unrelated functions merely to shorten a table or checklist.

---

### 11.5 Examples and Placeholders

Use examples only when they help readers understand a task, control, decision, or consequence.

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

Do not remove useful legal, regulatory, privacy, employment, financial, safeguarding, cybersecurity, pastoral, theological, technical, or professional controls merely to avoid time-sensitive claims. Preserve issue-spotting, current-source, authority, and escalation requirements while removing unsupported or unstable conclusions.

---

### 11.7 Legal, Regulatory, Privacy, and Specialist Tone

#### Start with the facts

Use an **issue-spotting, conditional, source-led, and authority-aware tone**.

This guide may help readers identify a possible legal, regulatory, privacy, financial, employment, safeguarding, medical, psychological, pastoral, theological, technical, platform, or other specialist issue. It must not sound as though this guide, an AI system, or an ordinary reviewer has made a final specialist determination.

- State the relevant facts or conditions before describing the possible requirement or risk.

#### Use conditional wording

- Prefer conditional wording such as `may`, `can`, `could`, `where`, `if`, `depending on`, and `in some circumstances`.
- Avoid universal or absolute wording such as `every`, `always`, `never`, `cannot`, `only`, `automatically`, `constitutes`, `is required by law`, `is compliant`, or `is illegal`, unless the statement is a stable conceptual or mandatory governance boundary, or is directly supported by a current authoritative source and any required qualified review.

#### Separate facts, risks, and conclusions

- Distinguish clearly between:
  1. an observable fact or circumstance.
  2. a possible risk, consequence, or control need.
  3. a legal, regulatory, privacy, or specialist conclusion.
- Do not turn a possible issue into a definite conclusion merely because the wording sounds plausible.
- Do not imply that a regulator, court, insurer, funder, auditor, platform provider, or qualified professional will reach a particular outcome.

#### Current features and external outcomes

- For current platform functions, product behaviour, model capability, or technical limits, use platform-neutral or model-neutral wording where possible. Where a current feature matters, check the current official source and record the date checked.
- Describe consequences as possibilities unless documented evidence supports stronger wording.
- Preserve current-source checking, authority boundaries, escalation, and qualified-review controls.
- A disclaimer does not correct an unsupported definite claim elsewhere in the content.

#### When accurate wording is not possible

Use this preferred sentence pattern:

> Where **[relevant facts or conditions]** apply, **[the information, action, or arrangement]** may **[create the risk or consequence]**. Check **[the current official source, approved record, policy, or process]**. Seek qualified review where **[interpretation, authority, or material consequence]** remains unclear.

Examples:

| Avoid | Prefer |
|---|---|
| Every recipient list is personal data. | A recipient list may contain personal data where names, telephone numbers, account identifiers, or other information identify living individuals. |
| Broadcast messages cannot be recalled. | Deletion or unsending may not reverse exposure after recipients have seen, copied, forwarded, downloaded, or captured the message. |
| Searching is the only way to detect a false citation. | A plausible-looking false citation may be difficult to identify by reading alone. Verify the source through a trusted database, publisher, original document, or other authoritative source. |
| Simplified Chinese defaults to Mainland Chinese law. | Simplified Chinese output may introduce Mainland Chinese terminology, legal assumptions, or institutional references, especially where Hong Kong jurisdiction is not explicit. |
| The regulator will reject the submission. | The omission may cause delay, rejection, further questions, or another adverse outcome, depending on the applicable requirements and decision-maker. |

Where the content cannot be made accurate through conditional, source-led wording, remove the conclusion and retain only:

- the issue to check.
- the current authoritative source requirement.
- the responsible role.
- the qualified-review or escalation requirement.

---

### 11.8 Keeping Important Meaning During Rewrites

Keeping important meaning during a rewrite is sometimes called semantic preservation.

A rewrite may improve wording or structure, but it must not remove an important question, example, task-specific risk, prompt instruction, review action, source requirement, limit, approval boundary, escalation trigger, template field, recordkeeping requirement, or reusable habit unless the owner approves the removal.

For a major rewrite, list each important point from the approved source and record whether it was:

- kept exactly.
- kept in equivalent or stronger wording.
- restored.
- replaced by an approved newer point.
- removed with explicit owner approval.

A surviving heading, keyword, or summary is not proof that the meaning survived. Check the examples, reasons, conditions, consequences, boundaries, and instructions themselves.

A broad risk explanation must not replace the way the risk appears in a particular task or the specific controls for that task.

---

### 11.9 Separate Actions, Checks, and Evidence

Where a passage could confuse the reader’s role, separate:

- **Author action** — what the author or editor must do.
- **Review check** — what a reviewer must confirm.
- **Required evidence** — what must be quoted, located, recorded, or reported.

Use these labels only where they improve clarity. Do not add all three mechanically when one short instruction is enough.

---

## 12. Translation and Localisation Rules

### 12.1 Source and Terminology Authority

Treat `en_HK` as the source where the package identifies it as the master source. Use the current owner-approved terminology table for the publication cycle.

During translation review, record the source file and version used for each translation, how the source and translation were paired, and how certain that pairing is.

In Traditional Chinese and Simplified Chinese content, use the approved localised names for reader-facing titles, headings, labels, links, platforms, and publication channels. Do not keep the English name merely because it appears in inline code in the English source.

Keep English only for literal technical text, such as a filename, path, URL, package name, command, code value, validation string, or controlled English-master source identifier.

The table below is maintained only in the English master to show the approved localised names. Do not copy or translate it into the Traditional Chinese or Simplified Chinese Author and Editor Guides. Those guides use the approved localised names directly. This intentional difference is not missing translation.

Current canonical localised forms include:

| English source | Traditional Chinese (`tc_HK`) | Simplified Chinese (`sc_HK`) |
|---|---|---|
| `How To Use This Guide` | `如何使用本指南` | `如何使用本指南` |
| `Companion Guides` | `配套指南` | `配套指南` |
| `Win.Win AI Blind Spot Guide` | `Win.Win 人工智能盲點指南` | `Win.Win 人工智能盲点指南` |
| `LinkedIn` | `領英` | `领英` |

The table defines the approved localised names. It does not permit the English names to remain in ordinary Chinese prose.

Do not report an uncertain pair as a confirmed match or confirmed missing file.

---

### 12.2 Meaning Fidelity

Compare source and target side by side. Check for omission, unsupported addition, strengthening, softening, narrowing, broadening, reframing, changed governance meaning, and changed reader action.

Preserve obligations, prohibitions, warnings, uncertainty, approval boundaries, specialist boundaries, source requirements, and stop or escalation conditions.

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

- **source grounding** — the basis supporting content.
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

Where natural language or an approved localisation difference requires a split, merge, move, omission, or different structure, record the source and target locations, reason, and semantic-preservation decision in the translation-alignment evidence.

---

### 12.6 Qualified Bilingual Review

Use both bilingual comparison and target-language reading.

Check terminology, meaning, naturalness, filenames, links, headings, tables, lists, callouts, disclaimers, examples, authority language, approval language, escalation language, and Hong Kong context.

AI-assisted comparison supports but does not replace qualified bilingual sign-off.

Escalate ambiguity, specialist terminology, material meaning change, or changed authority, risk, review, disclaimer, or escalation meaning.

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

Do not apply Chinese emphasis-spacing or colon conversion rules inside YAML (a structured text format commonly used for configuration data), URLs, times, ratios, drive paths, namespaces, JavaScript Object Notation (JSON), code, inline code, identifiers, Markdown link destinations, escaped asterisks, or exact English technical strings.

---

## 14. Markdown and GitHub Formatting Rules

### 14.1 Raw Markdown Review

Check raw file content rather than relying only on rendered preview.

Review trailing spaces, hard breaks, line endings, indentation, structural markers, code blocks, frontmatter, links, and tables.

---

### 14.2 Section Breaks and Blank Lines

This section-break convention applies only to non-README Markdown files. Repository-level and language-folder `README.md` files are explicitly exempt.

Apply the immediate-child exception at both hierarchy levels:

- do not place a section break between the H1 and its immediate first H2 when no body content appears between them.
- do not place a section break between an H2 and its immediate first H3 when no body content appears between them.

If body content appears between a parent heading and its child heading, place exactly one section break before the child heading.

Every later H2 still requires exactly one preceding section break, including when it follows an H2, H3, H4, paragraph, list, table, callout, code block, or other body content.

Every later H3 requires exactly one preceding section break when it begins after body content or follows another H3 or H4.

Body content includes paragraphs, lists, tables, callouts, code blocks, images, links presented as content, and other reader-facing material. Blank lines are not body content.

Use exactly one blank line before and one blank line after every section break. Do not use consecutive section breaks or multiple blank lines around a section break.

Use one blank line between a heading and the content that follows. Do not place section breaks before H4 headings.

**Use**

```md
## 2. Main Section

Introductory text.

---

### 2.1 New Subsection
```

```md
## 3. Main Section

### 3.1 Immediate First Subsection
```

**Avoid**

```md
## 3. Main Section

---

### 3.1 Immediate First Subsection
```

The final example adds an unnecessary break between an H2 and its immediate first H3.

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

**Do not use trailing spaces where normal paragraph wrapping is intended.**

---

### 14.4 Tables

Keep table headings short and descriptive.

Preserve the meaning of each row when reformatting. Check that pipes, emphasis, links, and line breaks render correctly.

Do not force every idea into a table where prose or a checklist is clearer.

---

### 14.5 Encoding and Line Endings

Use 8-bit Unicode Transformation Format (UTF-8) without a byte order mark (BOM), use line feed (LF) line endings, and include one final newline. Report mixed or unintended line-ending styles.

Do not change line endings, whitespace, or table spacing in an unchanged file.

---

## 15. Using AI Assistants for Authoring and Editing

### 15.1 Role and Authority

An AI assistant may support authoring, editing, comparison, localisation, validation, evidence preparation, and packaging. It must not assume authority to approve, publish, adopt, or make an unrequested substantive governance change.

---

### 15.2 Current-Task Source of Truth

Use only the files supplied for the current task. Confirm the exact package filename and checksum before work begins. Ignore old uploads, cached copies, earlier extracted folders, previous reports, and remembered wording unless the owner explicitly authorises them as references.

---

### 15.3 Before Starting Work

The AI assistant should:

1. identify the exact source package and version.
2. list files in scope and files excluded.
3. classify file types.
4. inspect headings, links, terminology, formatting, and repeated-entry structures.
5. identify canonical sources and dependent files.
6. distinguish structural, editorial, substantive, translation, and packaging changes.
7. identify required version, footer, release, index, register, and translation effects.
8. state material assumptions in the change report.

---

### 15.4 Editing Existing Content

Preserve original meaning unless a substantive change is requested. Do not silently remove sections, controls, approval conditions, escalation rules, caveats, examples, or other safeguards.

Record whether content was retained, renamed, moved, split, combined, or newly added. Check every affected internal link after changing a title or heading.

---

### 15.5 Authoring New Content

Identify the correct file type and canonical structure. Use the applicable Entry Structure Standard, include mandatory sections, use optional sections only when useful, and state what prompting or review cannot prove.

Add the file to every applicable local index or register and create approved translations where required.

---

### 15.6 Fresh-Chat Instruction

> [!note] Instruction for a fresh AI-assisted editing chat
> **Before editing**
> - Read the current Author and Editor Guide.
> - Use only the current files supplied in the chat.
> - Confirm the exact source package, checksum, and approved file list.
> - Do not modify README files unless they are explicitly in scope.
> - Apply the README numbering and section-break exceptions in Section 6.1.
>
> **While editing**
> - Follow the approved headings, structure, terminology, localisation, version, and validation rules.
> - Use UK English spelling and apply the list-punctuation and `and` or `or` rules in Section 11.3.
> - Do not silently remove, merge, weaken, or invent governance content.
> - For a major rewrite, list the important points in the approved source and show what happened to each one.
> - A surviving heading or keyword is not proof that the important meaning survived.
>
> **After editing**
> - Validate every affected file.
> - Report what changed, where moved or reorganised content came from, where the important final meaning appears, and what still requires human approval.

---

## 16. Pre-Publication Review and Validation

Use this review order:

```text
confirm inputs
→ extract and check inventory
→ pair source and translations
→ review content, README, versions, and formatting
→ review specialist tone and cross-artefact effects
→ check important meaning
→ classify findings and report status
```

Complete only the steps that apply to the authorised scope, but do not present a partial review as complete.

---

### 16.1 Required Input Preflight

For a full multilingual pre-publication review, confirm the current public ZIP archive, approved file list or approved inventory where used, approved terminology table, applicable review instructions, this guide, current source and translation pairings, and release and document-version rules.

If a mandatory review input is missing, stop the affected comparison, list exactly what is missing, and do not present a partial comparison as complete.

---

### 16.2 Extraction and Inventory

Check that:

- the ZIP extracts successfully.
- Markdown files decode as UTF-8.
- expected files are present and unexpected files are identified.
- displayed paths match the approved inventory where one is used.
- each language folder matches its approved translation stage under Section 6.2.
- the public package contains no evidence or temporary files.

Require a language folder to be complete and independently usable only where that language edition has been designated complete under Section 6.2.

A manifest is not required inside the publication package unless the owner explicitly requests one.

---

### 16.3 File Pairing

Do not pair translations by filename similarity alone. Use explicit README, index, or register mapping, English names shown beside localised links, approved mappings, canonical paths, frontmatter, document function, and owner confirmation in that order.

Record how each source and translation were paired and how certain the pairing is. Do not report an uncertain pairing as a confirmed missing file.

---

### 16.4 Translation and Localisation Review

Check meaning fidelity, approved terminology, Hong Kong context, script contamination, untranslated text, links, headings, tables, lists, callouts, disclaimers, examples, approval language, escalation language, accountability, and professional boundaries.

---

### 16.5 README Review

Check README files in four groups.

**Identity and purpose**

- artefact identity.
- purpose and audience.
- licence meaning.
- master-source statements.
- approved terminology.

**Structure and navigation**

- heading hierarchy and required sections.
- folder navigation.
- use-case indexes and the Use Case Register where linked.
- duplicate headings and broken anchors.

**Publication control**

- release information.
- shared boilerplate and approved substitutions.
- contact and feedback routes.
- repository paths.

**Links and rendering**

- links.
- intended hard breaks.
- final rendering.

Do not require different artefact families to share the same release number or artefact-specific purpose.

---

### 16.6 Document Version and Release Review

Check that:

- before first publication, every public file retains document version `1.0` unless the owner explicitly starts a new published document version.
- after publication, only changed documents receive an owner-approved version change.
- new public documents start at the owner-approved initial version.
- footer versions match frontmatter versions.
- unchanged files retain their existing versions.
- the pre-publication package release remains `1.0` unless the owner explicitly changes it.
- release labels are consistent across applicable README files.
- release history records material reader-facing changes.

Omit minor typography, punctuation, self-reference, evidence, or packaging corrections from release history unless the owner asks for them.

A package release may contain documents with different document versions after publication.

---

### 16.7 GitHub Hard-Break Review

Review hard breaks separately from translation. Classify cases as:

- `valid_github_hard_break`.
- `missing_github_hard_break`.
- `unnecessary_hard_break_review_only`.
- `strict_raw_difference_only`.
- `no_fix_needed`.

Use two trailing spaces as the project convention where GitHub would otherwise join two intended visual lines.

---

### 16.8 Legal, Regulatory, Privacy, and Specialist Tone Review

Perform a targeted tone review of legal, regulatory, privacy, financial, employment, safeguarding, medical, psychological, pastoral, theological, technical, platform, and other specialist content.

#### What to search

Search for certainty markers including:

`always`, `every`, `never`, `cannot`, `only`, `automatically`, `constitutes`, `required by law`, `compliant`, `illegal`, `defaults to`, `will reject`, `will require`, and `no recall`.

A match is a **review candidate**, not an automatic failure.

Also search for every task-specific risk name, legal or privacy framing, control statement, consequence explanation, authority boundary, or specialist qualification changed during the review cycle.

#### How to assess each result

For each match, determine whether the statement:

- is a stable conceptual or mandatory governance boundary.
- is conditional on facts not stated in the sentence.
- depends on current law, regulatory guidance, platform functionality, model behaviour, or organisational arrangements.
- implies a final specialist conclusion.
- implies a definite external decision or consequence.
- should instead use conditional, source-led wording.
- requires a current authoritative source, date checked, or qualified review.

#### After wording changes

Confirm that:

- no stale wording remains in prompt rows, Sample Overall Prompts, Prompt Enhancement Patterns, taxonomies, libraries, registers, templates, indexes, navigation files, or translation sources.
- Sample Overall Prompts teach the same risk and control model as their source use-case pages.
- renamed descriptions of how a risk appears in a task remain traceable to the broader category in the Risk Taxonomy and the applicable control objective.

---

### 16.9 BSG Reference Impact Review

Section 9.5 explains which BSG changes may affect UCG. This subsection explains how to perform the review.

#### Before reviewing

1. confirm the exact UCG and BSG package filenames and 256-bit Secure Hash Algorithm (SHA-256) checksum values.
2. use the current UCG package as the reference target and the latest supplied BSG package as the source for BSG meaning.
3. read the BSG orientation, scope, terminology, routing, control boundaries, organisational-context, unstated-context, preservation, and maintenance guidance.

#### Review current references

1. identify BSG changes that match a trigger in Section 9.5.
2. scan current UCG public files for formal titles, companion descriptions, routes, definitions, use conditions, template fields, risk-library references, translated equivalents, and related scope wording.
3. assess whether each reference remains accurate, complete enough for its function, and consistent with UCG’s independent usability.

Review the named Blind Spot Guide subsection in `How To Use This Guide` first. Then review each use-case page’s route and task-specific trigger.

#### Decide and apply corrections

1. correct only references that are stale, incomplete, inaccurate, misleading, broken, or insufficient for the task.
2. change a use-case page only where its destination or task-specific trigger needs correction.
3. preserve every unaffected file byte-for-byte.
4. apply each material correction to every affected language version, index, template, navigation file, use-case page, and authoring rule.
5. preserve the root `README.md` byte-for-byte unless the owner explicitly includes it in scope.
6. confirm that BSG has not become a prerequisite for ordinary UCG task-level review.
7. confirm that UCG task-level controls have not been displaced by or unnecessarily copied from BSG.

#### Record evidence

For the current review, record:

- file and physical line.
- language.
- current UCG wording.
- BSG dependency involved.
- current BSG meaning.
- status of the UCG reference.
- required action and final wording.
- rationale.
- owner, bilingual, or specialist review required.

Create this evidence again for each package review. Do not reuse an old occurrence register without rescanning the current packages.

#### Work boundaries

Do not use unrestricted search-and-replace.

Do not describe the review as complete where a material BSG change has not been assessed against all current UCG occurrences.

Do not edit BSG during a UCG-only task unless the owner explicitly includes it in scope.

---

### 16.10 Checking Important Meaning After a Major Rewrite

Use this review when a major rewrite changes terminology, scope, structure, or how content is grouped.

1. identify the approved source version.
2. list the important points that must remain.
3. quote each point or record its exact source location.
4. record what happened to each point using the categories in Section 11.8.
5. confirm that the final wording keeps the same or stronger meaning.
6. record every approved replacement or removal.
7. check that the examples, reasons, conditions, boundaries, and instructions remain clear.

This checklist is evidence for the current review only. It is not a new master source. Create a fresh checklist for each new review.

---

### 16.11 Finding Severity

`P1` and `P2` are the controlled finding-severity labels used in this guide. They are not abbreviations for Purpose, Permission, or Proof.

Use **P1** for a confirmed issue affecting meaning, authority, approval, accountability, privacy, legal or professional boundaries, publication identity, required links, Markdown rendering, or risk treatment.

Use **P2** for a confirmed terminology, structural, UK English spelling, list-punctuation, conjunction, publication-formatting, shared-boilerplate, required-hard-break, heading, table, index, register, release, version-parity, or Chinese publication-convention issue that does not change central governance meaning.

Use **Review only** where evidence, pairing, source authority, specialist terminology, translation meaning, or intended presentation remains uncertain.

---

### 16.12 Overall Status

Use **PASS** only when no actionable finding remains and every required check has been completed.

Use **REVIEW REQUIRED** when no confirmed material failure remains but an owner, bilingual, specialist, pairing, terminology, release, or presentation decision is unresolved.

Use **FAIL** when a confirmed actionable issue remains or a required input, extraction, decoding, structure, terminology, script, link, identity, release, version, or P1 rendering problem prevents reliable publication.

---

### 16.13 Review Reporting

A full review should provide a summary, file-pairing map, prioritised fix list, H3- or H4-to-H2 section-break findings, UK English spelling findings, list-punctuation and conjunction findings, hard-break findings, Chinese emphasis and colon findings, README findings, index and register findings, version and release findings, expected differences ignored, false positives avoided, owner-decision items, limitations, and downloadable reports where requested.

Only actionable issues belong in the prioritised fix list. Do not include harmless raw differences or speculative findings without supporting evidence.

---

## 17. Maintenance and Change Control

### 17.1 Common Rules

Keep common editorial, structural, localisation, validation, versioning, packaging, and publication rules in this file rather than repeating them across every file.

---

### 17.2 File-Specific Rules

Keep a `Maintenance and Change Control` section in an individual file only where that file has a specific dependency, such as stable linked entry names, canonical wording adapted elsewhere, mitigation-family alignment, Sample Overall Prompt synchronisation, use-case page and register alignment, or template and card synchronisation.

---

### 17.3 Related References

Add `Related References` only where the original or approved content has real and useful cross-file relationships. Do not add an empty or speculative section merely for symmetry.

Do not make a LinkedIn series, article, training session, unpublished explanation, presentation, or other external commentary a prerequisite for understanding or safely using this guide. External material may introduce, illustrate, explain, or promote this guide, but every mandatory instruction, control, boundary, route, and stop condition must remain available within the approved public package.

Write important definitions, frameworks, controls, examples, boundaries, roles, risks, decisions, and instructions so that they remain useful after the current release.

Do not present lasting guidance as a temporary release note, future promise, or unpublished plan.

Do not say that another guide, quick version, training resource, or supporting document exists unless it has been approved, published, and linked. Where the owner approves a reference to future work, state clearly that it is not yet available and is not required to understand or safely use this guide.

---

### 17.4 Review Cycle

Review organisational adaptations and published artefact maintenance on a defined schedule and after material changes to tools, policy, law, organisational roles, source systems, workflows, security controls, risk exposure, language, or terminology authority.

---

### 17.5 Frontmatter

Preserve established frontmatter fields and ordering unless a controlled migration is authorised.

Common fields include:

- `title`.
- `created`.
- `updated`.
- `version`.
- `tags`.
- `status`.
- `type`.
- `source-role`.
- `locale`.
- `licence`.

Keep `created` stable.

Every modified public file must contain an `updated` field set to the owner-approved correction date. Add the field if it is absent.

Do not change `updated` in a file that is otherwise unchanged. Unchanged files must remain byte-identical.

Frontmatter tag values are short labels. Do not add a full stop merely for visual consistency.

---

### 17.6 Document Versions

A document version belongs to one public file.

Before first publication:

- keep each existing public file at version `1.0`.
- do not increment the version for pre-publication editorial, structural, translation, typography, evidence, or packaging corrections.
- change the version only if the owner explicitly starts a new published document version.

After publication:

- change only documents included in the owner-approved version update.
- keep unchanged files at their existing versions.
- keep each footer version identical to the frontmatter version.

Use the owner-approved standard footer for the artefact and language.

- In `en_HK`, use the approved short English licence wording with `CC BY 4.0`.
- In `tc_HK`, use the full approved Traditional Chinese licence name followed by `（CC BY 4.0）`.
- In `sc_HK`, use the full approved Simplified Chinese licence name followed by `（CC BY 4.0）`.

The licence wording follows the corresponding approved Win.Win AI Essentials language pattern, but the version number must always match the current UCG file’s own frontmatter version. Do not copy a version number from another artefact, language file, package, or example.

Treat the approved footer wording as controlled shared boilerplate. Do not shorten, expand, retranslate, or otherwise alter it unless the owner expressly approves a new footer pattern.

New public documents start at the owner-approved initial version.

A document version is separate from the package release.

---

### 17.7 Package Releases and Release History

A package release is the published snapshot of the complete artefact.

Before first publication, keep the package release at `1.0` unless the owner explicitly changes it.

The release number appears in applicable README files.

A release may contain documents with different document versions.

Record material reader-facing release changes, such as:

- a new public file.
- a significant framework, risk, control, or approval change.
- a new language folder.
- a material package restructuring.
- an important scope or audience change.
- a substantial new maintenance or adaptation capability.

Minor typography, punctuation, self-reference, evidence, or packaging corrections do not need a release-history note unless the owner asks for one.

---

### 17.8 Index and Navigation Maintenance

When a public file is added, renamed, removed, or materially repurposed:

- update the applicable language-folder README indexes.
- update the Use Case Register where the change affects a registered use case.
- update related navigation files.
- use the exact local filename in each wikilink.
- preserve the English title in parentheses where that is the established translation-folder pattern.
- describe what the file helps the reader do, not merely its file type.
- verify every new local link.

Do not modify the root `README.md` unless the owner explicitly includes it in scope.

---

### 17.9 Public Package and Evidence Separation

The public archive must contain only intended public files under the `public/` wrapper.

Do not place inside the public archive:

- external `file_list.txt`.
- review reports.
- validation outputs.
- change registers.
- evidence files.
- temporary files.

Maintain an external canonical file list with relative paths, forward slashes, no leading slash or backslash, no duplicate entries, and one final newline.

Record final archive checksums externally. Do not embed an archive’s own final checksum inside that archive.

---

## 18. Change Reporting

### 18.1 Minimum Change Report

Report the following.

**Source and scope**

- source package and checksum.
- files in scope and excluded.
- files added, removed, renamed, changed, and deliberately unchanged.
- terminology authority used.

**Content and structure**

- headings added, renamed, moved, split, or combined.
- newly written content.
- source of reorganised content.
- cross-file references updated.
- previous wording searched, dependent files checked, and stale occurrences corrected or retained with a recorded reason.
- approved source version used for any major rewrite.
- important source points checked and what happened to each one.
- content restored, replaced, or removed with owner approval.
- exact final locations used as evidence.

**Translation and publication**

- how each source and translation was paired, and how certain the pairing is.
- index, register, and navigation changes.
- release-label and release-history changes.
- document-version and footer changes.
- confirmation that lasting guidance remains in the public package.
- confirmation that every referenced public resource exists and has an approved public link or path.

**Legal, regulatory, privacy, platform, and specialist review**

- tone review performed.
- current sources and dates checked where applicable.
- unresolved specialist or authority decisions.

**UCG–BSG reference review**

- BSG source package and SHA-256.
- BSG changes assessed against the Section 9.5 triggers.
- current UCG references to BSG reviewed and the outcome for each reference.
- UCG files corrected because of BSG changes.
- BSG changes assessed as having no UCG impact and the reasons.
- UCG independence and companion-boundary checks performed.
- unresolved owner, bilingual, specialist, publication, or destination decisions.

**Validation and status**

- validation performed.
- unresolved judgement calls.
- qualified-human review required.
- final review status.

Do not remove a reporting requirement merely because it does not apply to the current task. Mark it `not applicable` with a reason where necessary.

---

### 18.2 Provenance Rule

Do not describe a change as simple formatting when it alters meaning, control strength, scope, authority, escalation, translation alignment, release information, or downstream dependencies.

Where content is combined or split, identify the original headings, labels, or source paragraphs used.

Where a translated file is created or updated, record the approved source file and version.

---

### 18.3 Final Boundary

This guide supports consistent authoring and review. It does not replace owner judgement, qualified specialist review, bilingual human review, organisational approval, or evidence from real readers and real use.

Final publication decisions remain with the Win.Win artefacts owner.

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
