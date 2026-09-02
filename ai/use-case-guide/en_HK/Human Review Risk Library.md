---
title: Human Review Risk Library
created: 2026-07-01
updated: 2026-08-14
version: "1.0"
status: active
type: reference
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Human Review Risk Library

## 1. Purpose and Scope

This library explains common AI review risks, failure patterns, and AI blind spots that can affect AI-supported work.

Use it with the use-case pages and [[Risk Taxonomy]]. The taxonomy classifies risks by family and provides the package-wide named-risk and failure-mode index; this library defines reusable human-review risks and explains what prompt, review, or escalation action counters them.

The aim is not to memorise every entry. The aim is to ask: **which review risk or AI blind spot is most likely in this workflow, and what action counters it?**

Each entry includes a definition, what review must check, and where the risk is explicitly or conceptually linked. Some entries also include a prompt-side control, its limits, or other explanation needed to apply the risk safely.

**Cross-reference rule:**

- **Affected use cases** means the linked use-case page explicitly names this risk. This is a strict traceability field.
- **Also relevant to** means the risk is conceptually relevant to the use case, workflow, or reference file, but the current use-case page does not explicitly name this risk. Treat this as implementation guidance, not proof of explicit coverage.
- A use-case page may keep a more specific risk label while linking to a broader library entry. The page label names how the risk appears in that workflow; the linked library entry explains the underlying review pattern.

If a use-case page is later updated to name the risk directly, move it from **Also relevant to** into **Affected use cases**.

---

## 2. How To Use This Reference

### 2.1 How To Adapt What Review Must Check for a Use-Case Page

This file is the canonical source for the meaning of each reusable named risk contained in this library and its minimum review obligation. A use-case page may use a narrower task-specific risk name when that name is defined on the page and indexed in [[Risk Taxonomy#4. Named Risk and Failure-Mode Index|Named Risk and Failure-Mode Index]]. Where a use-case page links to a library risk, it should convert **What review must check** into a task-specific review instruction without changing or weakening that obligation.

For every risk listed under **Affected use cases**, the linked use-case page should show visible review coverage. Do not leave the relationship implicit merely because the page already contains a general review section.

Use this sequence:

1. **Select** the named risk and its canonical **What review must check**.
2. **Preserve** the central review obligation, including any source, authority, competence, judgement, or escalation requirement.
3. **Remove** examples or objects that cannot occur in the task.
4. **Specify** the actual items, source or real-world reference, warning signs, reviewer, timing, and decision supported by the check.
5. **Add** task-specific items that this general library cannot know.
6. **Check** that the adapted wording still addresses the same risk and has not become a weaker generic reminder.

Place the task-specific review obligation under **How To Review This Output**, either as a named risk-specific check or clearly within the selected review methods.

A task-specific review instruction should normally answer:

- What exactly must be checked for this task?
- What source, record, person, standard, or real-world reference must it be checked against?
- What failure or warning sign should the reviewer look for?
- Who has enough context, competence, experience, qualification, or authority to perform the check?
- When must the check happen?
- What must happen if the issue cannot be resolved?

Do not write only “review carefully”, “check important information”, or “confirm with a human”. Name the actual information, source, reviewer, authority, and decision boundary.

Where wording has been approved for exact reuse, keep the canonical sentence unchanged and add a separate task-specific line, for example:

> **For this use case:** Check whether the proposed role fits the actual volunteers, supervision capacity, safeguarding arrangements, decision authority, and consequences of assigning responsibilities incorrectly.

The canonical review obligation does not need to be copied into the prompt table. A **Reminder / Review Note** may remind the user of the human check, but it does not replace the operational review instruction under **How To Review This Output**.

---

### 2.2 How To Adapt a Prompt-Side Control for a Use-Case Page

A **Prompt-side control** in this file is canonical control logic. It should not normally be copied into every affected use-case page as one long paragraph.

For every risk that has a **Prompt-side control** and lists a page under **Affected use cases**, assess whether prompt wording can materially reduce that risk in the specific task.

Where it can, convert the control into one or more task-specific rows under **Prompt Enhancements To Add**:

- use **Default Add-Ons** when the safeguard is normally required whenever the use case is performed;
- use **Conditional Risk Add-Ons** when it is needed only when a stated risk, source type, audience, jurisdiction, authority issue, or operating condition is present; and
- use the actual risk name in the `Risk` column, not a category label such as `Main risk` or `Additional risk`.

Whether the risk appears under **Main Risks** or **Other Risks To Watch** does not determine whether its prompt add-on is default or conditional.

Use this sequence:

1. **Select** the canonical prompt-side control.
2. **Separate** its distinct prompt functions.
3. **Remove** examples, fields, limits, and checks unrelated to the task.
4. **Specify** the actual source, audience, output, jurisdiction, authority boundary, material information, operational dependency, verification source, or uncertainty marker.
5. **Map** each remaining function to the correct Win.Win AI Essentials prompt section.
6. **Add** task-specific fields, thresholds, prohibited commitments, source versions, warning markers, or review aids that the general control cannot know.
7. **Check** that the adapted wording preserves the control and does not imply that prompting replaces human review.

Use the following mapping:

| Control function | Essentials prompt section |
|---|---|
| Context or setting AI needs | **Background** |
| More precise task scope | **Task** |
| Audience, tone, language, register, or cultural requirement | **Audience / Tone / Language** |
| Method AI should follow | **Instruction** |
| Hard boundary, prohibition, or required uncertainty handling | **Rule** |
| Visible assumptions, gaps, verification items, or reviewer aid | **Output Format** |
| Human responsibility or limitation of the prompt control | **Reminder / Review Note** |
| Source material, approved wording, facts, exclusions, or operational notes | **Content** |

One risk may require one row or several rows. Keep every row that performs a distinct task-specific function. Do not force all risks into the same number or combination of prompt sections.

Do not add a prompt row where prompting cannot materially control the risk. In that case, state where the risk is handled instead, such as task-specific human review, an approved tool, independent verification, professional or authority review, other mitigation, or escalation. Do not let the prompt-side control disappear silently from an **Affected use case**.

A prompt-side control is not automatically the whole control for a risk. Do not move elicitation, source verification, authority sign-off, professional judgement, operational-owner review, or escalation into the prompt table unless the relevant reference guidance defines a prompt action for it.

A **Reminder / Review Note** may preserve the control limitation or name the required reviewer, but it does not replace the fuller task-specific review instruction under **How To Review This Output**.

---

## 3. Entry Structure Standard

Each risk entry uses the same core structure so readers can distinguish the risk meaning, the minimum human-review obligation, the affected use cases, and any prompt-side or contextual control.

---

### 3.1 Mandatory Sections

#### Definition

Explain the named risk in plain language and distinguish it from nearby risks.

#### What review must check

State the minimum human-review obligation. This is canonical risk-library content and must not be weakened when adapted for a use-case page.

#### Traceability

Show where the risk is expected to be applied. Keep compact relationship fields as bold key-value pairs:

- **Affected use cases:** pages that require visible coverage of the risk.
- **Also relevant to:** other pages, workflows, or circumstances where the risk may apply.

---

### 3.2 Optional Sections

#### How it appears

Describe common observable forms of the risk.

#### Prompt-side control

State canonical prompt control logic where prompting can materially reduce the risk. Do not imply that the prompt proves the output is safe or correct.

#### What “real” means

Clarify the people, context, authority, consequences, or lived judgement that must be checked outside the AI output.

#### How it can affect the output

Explain the practical ways the risk can change, omit, distort, or misdirect the result.

#### Context boundaries

Use this where some context should remain outside the AI interaction or cannot be fully written down. Keep those distinctions as bold labels inside the section.

#### Limits of prompt-side control

State what prompting cannot resolve and which review, source, authority, professional, workflow, or escalation control remains necessary.

---

### 3.3 Key-Value Fields

Use bold labels for compact fields inside an H4 section. Do not promote each short relationship field into a separate heading. For example:

**Affected use cases:** [linked pages]

**Also relevant to:** [other pages or workflows]

---

## 4. Risks

### 4.1 Low-Risk Assumption Trap

#### Definition

A familiar task feels low-risk, so reviewers check quickly and miss the specific facts or commitments that can cause harm.

#### What review must check

Every date, name, figure, venue, deadline, audience, and implied commitment against the source, not memory.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Communications]].

**Also relevant to:** [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Draft Event Planning Checklists]], [[Use Cases/Draft Internal Memos]].

---

### 4.2 Insider’s Blind Spot

#### Definition

The person reviewing an AI summary was in the meeting or situation, so their memory fills in what AI omitted or overstated.

#### What review must check

Decisions, caveats, action owners, status, and distribution boundaries against the original notes, using the outsider test.

#### Traceability

**Affected use cases:** [[Use Cases/Summarise Meeting Notes]].

**Also relevant to:** [[Use Cases/Summarise Documents]], [[Use Cases/Draft Reports And Presentations]].

---

### 4.3 Reliability Illusion

#### Definition

AI worked well many times, so users start assuming it will continue performing consistently like traditional software.

#### What review must check

Today’s output against today’s source, audience, authority, and risk — not yesterday’s trust.

#### Traceability

**Affected use cases:** [[Use Cases/Summarise Documents]].

**Also relevant to:** [[Use Cases/Check AI Output Reliability]], [[Use Cases/Draft Communications]], [[Use Cases/Research General Topics]], repeated drafting workflows.

---

### 4.4 Automation Complacency

#### Definition

Human review effort reduces over time because the AI appears reliable.

#### What review must check

Whether the same review standard is still being applied after repeated successful outputs.

#### Traceability

**Affected use cases:** [[Use Cases/Summarise Meeting Notes]].

**Also relevant to:** weekly or monthly workflows, [[Use Cases/Draft Communications]], [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Translate General Communications]].

---

### 4.5 Knowledge Gap

#### Definition

The reviewer is careful but lacks the domain knowledge needed to see the error.

#### What review must check

Whether the reviewer is competent for the risk, not merely careful or trusted.

#### Traceability

**Affected use cases:** [[Use Cases/Produce Bilingual Versions]].

**Also relevant to:** [[Use Cases/Assess Personal Data Tasks]], [[Use Cases/Verify HK Regulatory Questions]], [[Use Cases/Translate General Communications]].

---

### 4.6 Volume Overwhelm

#### Definition

AI increases output volume faster than humans can responsibly review it, so review becomes nominal.

#### Prompt-side control

Limit the requested output to the number and form that named reviewers can check before use. Use a complete source packet and a well-scoped prompt to reduce avoidable errors, unsupported assumptions, unnecessary variants, and rework.

Do not imply that better prompting lowers the required review standard.

#### What review must check

Whether output volume exceeds real review capacity; whether source preparation, prompt scope, and output limits reduce avoidable review work; whether high-risk outputs are prioritised and assigned to named reviewers; and whether the workflow pauses when the required review cannot be completed.

#### Limits of prompt-side control

A prompt cannot prove that the organisation has enough review capacity, prevent users from generating additional outputs elsewhere, or decide which consequence is material. Named-reviewer assignment, queue or batch limits, risk-based triage, escalation, and stop rules remain necessary.

#### Traceability

**Affected use cases:** [[Use Cases/Draft WhatsApp Broadcasts]].

**Also relevant to:** multi-platform communications, batch translations, donor/client updates, social media schedules, [[Use Cases/Draft Reports And Presentations]].

---

### 4.7 Prompt Over-Trust

#### Definition

Users or reviewers treat a well-designed, tested or approved prompt—and the AI’s apparent compliance with it—as evidence that the output is safe, accurate or ready to use. A prompt can reduce risk, but it cannot replace the review patterns, verification, authority checks or escalation required by the task.

#### What review must check

Whether the reviewer independently checked the output using the review patterns required by the task, rather than relying on the quality of the prompt or the AI’s apparent compliance with it.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Communications]].

**Also relevant to:** shared prompt templates, [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Draft Internal Memos]], [[Prompt Enhancement Patterns]].

---

### 4.8 Missing Context It Cannot Feel

#### Definition

AI gives a complete-looking answer without knowing that important organisational or local context is missing.

#### What review must check

Whether important context such as relevant local realities, hidden assumptions, missing constraints, data-quality issues, stakeholder sensitivities, or other facts were absent from the source material, prompt, or review basis—and whether that missing context changes the suitability, meaning, risk, or required handling of the output. Decide whether the context should be added safely, kept in reviewer-only notes, checked with the appropriate source or decision owner, or escalated.

#### Traceability

**Affected use cases:** [[Use Cases/Summarise Meeting Notes]].

**Also relevant to:** [[Use Cases/Check Confidence Before Research]], [[Use Cases/Research General Topics]], [[Use Cases/Research HK Topics]], [[Use Cases/Draft Event Planning Checklists]], [[Use Cases/Answer Policy Questions]].

---

### 4.9 Earlier Context Silently Lost

#### Definition

A user gave important context earlier in a long AI conversation, but it is no longer reliably active in later output.

#### What review must check

Whether critical constraints, red lines, source limits, excluded content, jurisdiction, terminology, and approval boundaries were still present in the immediate instructions or source material used to produce the output, rather than relying on information given much earlier in the conversation. Check the final output against those requirements and restore or restate any context that may have been lost.

#### Traceability

**Affected use cases:** [[Use Cases/Summarise Meeting Notes]].

**Also relevant to:** [[Use Cases/Draft Grant Applications]], [[Use Cases/Draft Organisational Policies]], [[Use Cases/Draft Reports And Presentations]], [[Use Cases/Translate General Communications]], long drafting sessions.

---

### 4.10 Instruction Drift

#### Definition

AI acknowledges an instruction but later output gradually moves away from it during revisions.

#### What review must check

Whether the final version still follows the original boundary after refinements, tone changes, or repeated edits.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Communications]].

**Also relevant to:** [[Use Cases/Draft Organisational Policies]], source-only tasks.

---

### 4.11 Fluency Illusion

#### Definition

AI output reads clearly, naturally, confidently, or professionally, causing users or reviewers to assume that its content is accurate, complete, supported, suitable, or ready to use. Fluency is a presentation quality; it is not evidence that the output has preserved the source, stated true facts, applied the correct context, stayed within authority, or satisfied the review requirements of the task.

#### What review must check

Whether the output was independently checked using the review patterns required by the task, rather than being treated as correct, complete, or ready to use because it reads fluently, naturally, confidently, or professionally.

#### Traceability

**Affected use cases:** [[Use Cases/Produce Bilingual Versions]], [[Use Cases/Translate General Communications]].

**Also relevant to:** [[Use Cases/Draft Communications]], [[Use Cases/Summarise Documents]], [[Use Cases/Summarise Meeting Notes]], [[Use Cases/Draft Internal Memos]], [[Use Cases/Draft Organisational Policies]], [[Use Cases/Draft Reports And Presentations]], [[Use Cases/Research General Topics]], [[Use Cases/Research HK Topics]], [[Use Cases/Verify HK Regulatory Questions]], and other workflows where polished wording may conceal errors, omissions, unsupported claims, lost context, or authority problems.

---

### 4.12 Approval Without Authority

#### Definition

A reviewer reads the output carefully but lacks authority to approve what the output says, implies, or commits.

#### What review must check

Promises, approvals, commitments, obligations, deadlines, refunds, policy positions, public statements, and whether the reviewer can authorise them.

#### Traceability

**Affected use cases:** [[Use Cases/Summarise Meeting Notes]].

**Also relevant to:** [[Use Cases/Draft Grant Applications]], [[Use Cases/Draft Organisational Policies]], [[Use Cases/Draft Communications]], [[Use Cases/Answer Policy Questions]].

---

### 4.13 AI Blind Spot

#### Definition

AI can produce the outward form of good judgement — fluent language, balanced options, structured reasoning, and confident conclusions — while being blind to lived context, tacit knowledge, relationship memory, accountability, professional instinct, authority, verification limits, or consequences that a human reviewer may need to judge safely.

#### How it appears

Some AI Blind Spots arise because context was not stated. Others remain even when context has been described, because described context is not the same as lived context, and described professional instinct is not the same as actual professional judgement. A description of Hong Kong, an organisation, or a profession is only an input; it is not the same as living inside that setting or carrying responsibility for the outcome.

#### Prompt-side control

Provide the context a human professional would normally know or ask for, and ask the AI to surface likely assumptions, missing-information categories, uncertainty, authority limits, and items requiring human confirmation. This is a review aid only; it is not proof that all gaps have been found.

#### What review must check

Whether the output fits the real people, real situation, real authority, and real consequences behind the task, including tacit context the AI was not told and lived or professional judgement that cannot be fully reduced to a prompt.

#### What “real” means

“Real” refers to the parts of the actual people, setting, authority, and possible consequences that could change whether the output is suitable. It does not mean that every aspect of a person, place, organisation, profession, or community can be listed or checked. The relevant aspects will differ from task to task.

For example, checking whether an output suits a real group of people may require considering characteristics, expectations, experiences, relationships, rights, sensitivities, or circumstances that matter to that particular task. Checking whether it meets a real professional standard may require judgement from someone who actually understands and carries responsibility for that professional practice, rather than relying only on a description of the practice in the prompt.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Communications]], [[Use Cases/Draft Internal Memos]], [[Use Cases/Draft Organisational Policies]], [[Use Cases/Draft Reports And Presentations]], [[Use Cases/Verify HK Regulatory Questions]].

**Also relevant to:** people-impact and decision-influencing workflows.

---

### 4.14 Unwritten Context Gap

#### Definition

Relevant context is absent from, incomplete in, or not adequately represented in the task basis. It may be known by people, available in current approved records, held in both, or of unclear source. Examples include organisational history, informal practice, past incidents, relationship context, individual preferences, local expectations, current sensitivities, or other context that the task basis does not represent adequately.

#### How it can affect the output

The missing context may change what the output should say, omit, emphasise, recommend, promise, or avoid. It may also change who should review or approve the output, how it should be delivered, or whether the task should proceed at all.

#### Prompt-side control

First identify which unwritten context could materially affect the output. Add only the context that is necessary, accurate, permitted, and safe to include in the source material or prompt. Do not include sensitive, confidential, personal, or otherwise restricted information merely to give AI more context. Where possible, use a safe general constraint instead of exposing the underlying sensitive detail.

#### What review must check

Whether relevant unwritten context could change the suitability, meaning, risk, or required handling of the output; whether appropriate and safe context was included in the source material or prompt; and whether context that was sensitive, confidential, unsuitable, or difficult to put into words was properly considered during human review. Decide whether the output should be corrected, checked with the appropriate source or decision owner, kept subject to reviewer-only context, or escalated.

#### Context boundaries

**Context that should remain outside the AI interaction:** Some relevant context should not be placed into the prompt or source material. This may include confidential information, personal details, safeguarding information, private relationship history, unverified allegations, sensitive organisational matters, or other information outside the approved data boundary. The responsible reviewer must account for that context without exposing it to the AI tool.

**Context that cannot be fully written down:** Some context is difficult to describe completely, such as an individual’s preferences, the history of a relationship, local working habits, professional instinct, or a sense that wording may be unsuitable in the actual situation. In these cases, the reviewer should check whether the output fits the real people and circumstances involved, rather than assuming that a written description has fully captured what matters.

#### Traceability

**Affected use cases:** [[Use Cases/Answer Policy Questions]], [[Use Cases/Answer Internal FAQs]], [[Use Cases/Draft Event Planning Checklists]], [[Use Cases/Draft Internal Memos]], [[Use Cases/Draft Organisational Policies]], [[Use Cases/Draft Reports And Presentations]], [[Use Cases/Draft Volunteer Roles]], [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Summarise Meeting Notes]].

**Also relevant to:** [[Use Cases/Draft Communications]], [[Use Cases/Draft Grant Applications]].

---

### 4.15 Reader Interpretation Gap

#### Definition

AI may produce wording that seems clear to the sender but may be understood differently by the real reader.

#### What review must check

How a named reader or reader group may interpret the tone, certainty, authority, commitment, refusal, approval, or action required.

#### Traceability

**Affected use cases:** [[Use Cases/Translate General Communications]].

**Also relevant to:** [[Use Cases/Draft Communications]], [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Draft Internal Memos]], [[Use Cases/Produce Bilingual Versions]].

---

### 4.16 Recipient Impact Blindness

#### Definition

AI may miss how an output could affect a real person emotionally, relationally, practically, socially, or reputationally.

#### What review must check

Who may be affected, what they may feel or infer, what action or pressure the output may create, and whether timing or relationship context changes the impact.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Communications]].

**Also relevant to:** [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Draft Volunteer Roles]], [[Use Cases/Draft Internal Memos]], [[Use Cases/Draft Grant Applications]].

---

### 4.17 Authority Boundary Blindness

#### Definition

AI may write as if a decision, approval, promise, refusal, commitment, or official interpretation has already been authorised.

#### What review must check

What the output appears to decide or commit to, who actually has authority, and whether unauthorised wording must be removed or escalated.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Internal Memos]].

**Also relevant to:** [[Use Cases/Answer Policy Questions]], [[Use Cases/Draft Organisational Policies]], [[Use Cases/Draft Grant Applications]], [[Use Cases/Summarise Meeting Notes]], [[Use Cases/Draft Communications]].

---

### 4.18 Materiality Judgement Gap

#### Definition

AI may misjudge the importance of particular information, conditions, caveats, differences, or uncertainties. It may give too much weight to a minor point, too little weight to an important point, or fail to recognise that certain information should change the emphasis, conclusion, recommendation, tone, approval route, or next action.

#### How it appears

AI may omit or soften an important caveat, overemphasise a minor issue, treat an uncertain figure as decisive, present a material exception as background detail, or produce a conclusion that is inappropriate because it misunderstood the significance of the information provided.

#### Prompt-side control

Where the importance of particular information is already known, explain that importance in the prompt or source material. Identify information that must not be omitted, softened, grouped with minor details, or treated as decisive. State any known thresholds, conditions, dependencies, or consequences that should affect the output. Ask AI to flag uncertainty about the importance of information rather than deciding materiality confidently on its own.

#### What review must check

What information, conditions, caveats, differences, uncertainties, or thresholds are important to the task, and whether the output has recognised and handled them appropriately. Check whether important information was omitted, softened, given too little weight, or treated as minor, and whether less important information was overemphasised or treated as decisive in a way that made the output inappropriate.

#### Limits of prompt-side control

A prompt can explain materiality that people have already identified, but it cannot guarantee that AI will apply that importance correctly or recognise every material factor. Human judgement is still required where importance depends on context, consequences, professional judgement, organisational priorities, or decision responsibility.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Reports And Presentations]].

**Also relevant to:** [[Use Cases/Draft Grant Applications]], [[Use Cases/Summarise Documents]], [[Use Cases/Summarise Meeting Notes]], [[Use Cases/Extract Invoice Or Document Data]].

---

### 4.19 Anomaly Instinct Gap

#### Definition

AI may fail to notice unusual information, inconsistent patterns, practical warning signs, or important information that is missing. An experienced person may recognise that a figure, name, date, sequence, format, assumption, or omission does not fit normal practice and requires checking or clarification before the task continues.

#### How it appears

A figure looks plausible but falls outside the usual range; a supplier name, date, format, sequence, or process step looks slightly wrong; expected information is absent; or the output proceeds confidently even though an experienced person would pause, question the pattern, or ask for missing information.

#### What review must check

Whether any information, pattern, figure, name, date, sequence, format, assumption, process step, or omission appears unusual or inconsistent with normal practice, and whether important expected information is missing. The reviewer must also consider whether they have enough experience or knowledge to recognise such warning signs. Where they may not, the output should be checked by an appropriate professional, domain expert, source owner, or experienced responsible person before the task continues or the output is approved.

#### Traceability

**Affected use cases:** [[Use Cases/Extract Invoice Or Document Data]].

**Also relevant to:** [[Use Cases/Check AI Output Reliability]], [[Use Cases/Research HK Topics]], [[Use Cases/Verify HK Regulatory Questions]], [[Use Cases/Draft Reports And Presentations]].

---

### 4.20 Bicultural Register Gap

#### Definition

AI may produce bilingual or cross-cultural wording that is accurate in literal meaning but inappropriate in tone, language register, formality, politeness, implication, level of authority, or social signal for the actual audience and setting.

#### What review must check

Whether the bilingual or cross-cultural wording preserves the intended tone, formality, politeness, social meaning, implication, and level of authority for the actual audience and setting. The reviewer must consider whether they have sufficient language and cultural understanding to make that judgement. Where they may not, seek an appropriate bilingual, cultural, or audience-aware reviewer. Seek relevant professional review separately where specialist meaning or professional practice is also involved.

#### Traceability

**Affected use cases:** [[Use Cases/Produce Bilingual Versions]].

**Also relevant to:** [[Use Cases/Translate General Communications]], [[Use Cases/Draft Communications]], [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Research HK Topics]].

---

### 4.21 Local Operational Memory Gap

#### Definition

AI may miss practical knowledge about how a task, process, venue, supplier, event, system, or team normally operates because that knowledge is held in people’s experience rather than fully recorded. This may include routine steps, usual sequences, dependencies, timing realities, role expectations, local practices, recurring constraints, workarounds, exceptions, and lessons from previous experience.

#### Prompt-side control

Identify relevant non-sensitive operational knowledge that may not be recorded in the formal source material, such as normal steps, usual sequences, dependencies, timing realities, role expectations, local practices, recurring constraints, known workarounds, and lessons from previous experience. Add accurate, necessary, permitted, and current information to the source material or prompt where it can help AI produce a more suitable output. Do not include confidential, personal, sensitive, uncertain, or otherwise restricted information merely to provide more context.

#### What review must check

Whether the task may depend on practical operational knowledge that is not recorded in the source material, including both how the work normally operates and what people have learned from past problems, exceptions, or near misses. Check with an appropriate experienced person and confirm whether the output has missed or misunderstood any normal step, sequence, dependency, timing requirement, role, constraint, local practice, warning, workaround, or exception before approving or using it.

#### Limits of prompt-side control

Operational knowledge may be incomplete, outdated, difficult to put into words, or held by people who were not consulted. Providing some operational context does not prove that all relevant knowledge has been captured or applied correctly. An appropriate experienced person should still check the output against how the work actually operates.

#### Traceability

**Affected use cases:** [[Use Cases/Draft Event Planning Checklists]].

**Also relevant to:** [[Use Cases/Draft Admin Templates]], [[Use Cases/Draft Volunteer Roles]], [[Use Cases/Draft WhatsApp Broadcasts]], [[Use Cases/Draft Internal Memos]].

---

### 4.22 User-Pressure Drift

#### Definition

AI changes a correct or cautious answer after a user confidently challenges it, even when no new reliable source has been provided.

#### Prompt-side control

Tell the AI not to accept user corrections or challenges unless they are supported by supplied source material, an authoritative record, or a named responsible owner. Ask it to mark unsupported challenges as `{VERIFY}`.

#### What review must check

Do not treat a revised AI answer as safer just because it agreed with the user. Check the source policy, record, law, decision owner, or responsible person.

#### Traceability

**Affected use cases:** [[Use Cases/Answer Policy Questions]], [[Use Cases/Answer Internal FAQs]], [[Use Cases/Draft Internal Memos]], [[Use Cases/Draft Organisational Policies]].

**Also relevant to:** other workflows where the user may push the AI toward a convenient answer.

---

### 4.23 Local or jurisdiction-specific blind spot

#### Definition

AI may give a confident general answer that is wrong for Hong Kong, the sector, the organisation, or the local setting.

#### What review must check

Whether the answer could differ in Hong Kong, in this sector, or in this organisation, and whether a local source, policy owner, regulator, professional adviser, or accountable reviewer must confirm it.

#### Traceability

**Affected use cases:** [[Use Cases/Answer Policy Questions]], [[Use Cases/Check Confidence Before Research]], [[Use Cases/Draft Event Planning Checklists]], [[Use Cases/Draft Organisational Policies]], [[Use Cases/Research HK Topics]], [[Use Cases/Translate General Communications]], [[Use Cases/Verify HK Regulatory Questions]].

**Also relevant to:** [[Use Cases/Assess Personal Data Tasks]], [[Use Cases/Produce Bilingual Versions]], and other workflows where law, policy, terminology, institutional practice, or operating requirements vary by jurisdiction, sector, or organisation.

---

### 4.24 AI Self-Validation Illusion

#### Definition

An AI-generated answer appears verified because AI reviewed it again, even though no independent source, record, tool, or responsible person reviewer confirmed it.

#### Prompt-side control

Ask AI to identify what independent sources, records, calculations, or responsible reviewers should be used to verify the answer.

#### What review must check

Verify against an independent source such as an official source, original document, spreadsheet, source record, policy owner, regulator, professional adviser, or responsible reviewer.

#### Traceability

**Affected use cases:** [[Use Cases/Check AI Output Reliability]].

**Also relevant to:** [[Use Cases/Check Confidence Before Research]], [[Use Cases/Research HK Topics]], [[Use Cases/Verify HK Regulatory Questions]], and source-dependent workflows.

---

## 5. Related References

- [[Risk Taxonomy]] classifies the broader risk families and provides the package-wide index for reusable risks, task-specific risks, and named failure modes.
- [[Prompt Enhancement Patterns]] explains reusable prompt-side controls referred to by some risk entries.
- [[Use Case Register]] links to the task-specific pages where the risks are adapted.

---

## 6. Maintenance and Change Control

Keep each reusable human-review risk name, definition, and minimum review obligation canonical in this file. Keep narrower task-specific risk or failure-mode definitions on the relevant use-case page and keep every published name traceable through [[Risk Taxonomy#4. Named Risk and Failure-Mode Index|Named Risk and Failure-Mode Index]]. Do not create a second name for the same meaning merely for shorthand or stylistic variety.

When **What review must check** changes:

- identify every page under **Affected use cases**;
- update only the review instructions that use that obligation;
- preserve valid task-specific sources, warning signs, reviewer roles, timing, and escalation boundaries; and
- confirm that the revised use-case wording still covers the full review obligation.

Keep the canonical prompt-side control in this file and the task-specific implementation in the use-case page.

When a **Prompt-side control** changes:

- identify every page under **Affected use cases**;
- reassess whether the control belongs in **Default Add-Ons**, **Conditional Risk Add-Ons**, or outside the prompt table;
- update only the affected prompt rows;
- preserve valid task-specific details;
- remove newly irrelevant wording;
- preserve one risk per row and the `Patterns` traceability column; and
- confirm that any Sample Overall Prompt still matches the revised use-case page.

Use [[Author and Editor Guide]] for common editorial, heading, localisation, validation, and packaging rules.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
