---
title: Glossary
created: 2026-07-06
updated: 2026-09-07
version: "1.0"
status: active
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
locale: en_HK
type: guide
tags:
 - glossary
 - terms
---
# Glossary

## 1. Purpose and Scope

Use this page as the **canonical plain-English terminology reference** for the Win.Win AI Blind Spot Guide. It defines the controlled meaning of core model terms, roles and standing, decision labels, and the architectural distinctions used across this guide.

Use it when checking whether a term is being used consistently or when a non-intuitive term in this guide needs a stable definition. Canonical AI Blind Spot risks are defined in [[AI Blind Spot Risk Library]]. Individual Controls, Methods, and Accountable Routes are defined in [[AI Blind Spot Control Map]]; the Glossary defines what those architectural categories mean across this guide.

Each controlled term or canonical item has one authoritative definition in one place. Other files may provide procedures, examples, navigation, relationships, or application guidance, but they must not create a second competing definition. The Glossary explains the terms assigned to it; it does not reproduce canonical risk or registry definitions owned elsewhere.

---

## 2. How To Use This Reference

Use this file to check whether a term is being used consistently. Link or briefly explain a non-intuitive term when it first appears in newcomer-facing content. Do not use near-synonyms merely for stylistic variety where they would blur a control boundary.

The Glossary defines the architectural concepts **Control**, **Method**, and **Accountable Route**. It does not independently define individual canonical Controls, Methods, or Routes; use [[AI Blind Spot Control Map]] for those canonical entries and their definitions. It also does not define canonical AI Blind Spot risks; use [[AI Blind Spot Risk Library]] for the authoritative risk definitions and practical risk guidance.

`Related terms` is a navigation aid. It points to nearby concepts that may help the reader explore the Glossary; it is not a formal relationship map and does not imply that every listed term is equally relevant in every situation. Formal risk-to-Control/Method/Route relationships belong in [[AI Blind Spot Control Map]].

---

### 2.1 Entry Structure Standard

Each repeated Glossary entry follows the structure for its category:

- Category A core model terms use `Definition`, `In plain English`, `Why it matters`, `Includes`, `Does not mean`, `Example`, and `Related terms`. Add `Not the same as` where a plausible reader confusion needs an explicit contrast.
- Category B roles and standing use `Definition`, `When this term is used`, and `Example`. Add `Not the same as` where a plausible reader confusion needs an explicit contrast.
- Category C decision labels use `Definition`, `Who may use it`, and `Does not mean`.

Canonical risks are not a Glossary category. Their authoritative definitions and risk-specific guidance belong in [[AI Blind Spot Risk Library]].

The standard fields are mandatory for entries in the corresponding category unless the field is explicitly described as conditional. Add no empty subsection for visual symmetry, and do not replace a field with a near-synonym that weakens comparison or traceability.

`Not the same as` is a diagnostic contrast, not a list of nearby terms. When it names another term, state the circumstance in which a reader could plausibly confuse the terms and the material boundary that separates them. Do not imply that two terms are mutually exclusive when one can include the other, when the same person may hold both roles, or when the relationship is otherwise overlapping; state that relationship explicitly. Use `Not the same as` only where confusing the concepts would blur a meaningful responsibility, authority, review, standing, or handling boundary.

---

## 3. How the Core Terms Fit Together

```text
Organisational context
→ all relevant context around the organisation and task

Task basis
→ the information and boundaries actually available for the current task

Unstated context
→ relevant organisational context absent from, incomplete in,
 or not adequately represented in the task basis

Source location
→ where the unstated context may exist:
 people, approved records, both, or unclear

Representability
→ how clearly, faithfully, and safely the context can be expressed

Unstated Context Control
→ the bounded current-task Control

Organisational context handling
→ the wider context lifecycle, which is outside the current detailed scope
```

Unstated context is defined by the task-basis gap, not storage location. Recorded information can still be unstated for the task. Context can exist in people and records at the same time. Implicit context is one possible source of unstated context, not a synonym. Elicitation is one method, not the whole Control. Not all surfaced context should enter AI. Not all useful context can be expressed fully or safely.

The wider control architecture uses a separate relationship:

```text
AI Blind Spot risk
→ may relate to one or more Controls

Control
→ may use one or more Methods

Risk or Control
→ may require an Accountable Route
```

These relationships are not one-to-one. A Control is named for the safeguard it provides rather than for one particular risk.

---

## 4. Common Confusions

Most pairwise distinctions are recorded under the relevant entry’s `Not the same as` field, where the reader encounters the term itself. This section retains cross-cutting comparisons that are clearer when several concepts are viewed together.

| Distinction | Plain-English boundary |
|---|---|
| Unstated context versus source location versus representability | Unstated context identifies the task-basis gap. Source location identifies where the missing context may exist. Representability describes how clearly, faithfully, and safely that context can be expressed. |
| Retrieve versus extract versus handle | Retrieve locates and brings the approved source into the task process; extract selects the relevant approved material; handling decides how that material may be used for the task. |
| Review versus verification versus approval | Review assesses whether the task or output is suitable for its intended use. Verification checks support or correctness through a sufficiently independent approved basis. Approval is a decision made by someone with suitable approval standing. |
| Risk versus Control versus Method versus Accountable Route | A risk identifies the problem; a Control defines the safeguard; a Method is a reusable way of carrying out or supporting one or more Controls; an Accountable Route identifies where responsibility, authority, expertise, review, approval, verification, or escalation goes. These relationships may be many-to-many. |

---

## 5. Category A — Core model terms

Canonical risk names, including **AI Blind Spot**, are defined in [[AI Blind Spot Risk Library]] rather than duplicated in this category.

---

### 5.1 AI-supported task

#### Definition

A task in which AI is used to draft, summarise, classify, translate, analyse, prepare, check, or support work that a person or organisation may use.

#### In plain English

AI helps with the work, but a human or organisation remains responsible for the use.

#### Why it matters

It defines the task boundary for review, approval, and escalation.

#### Includes

Prompts, outputs, source materials, review notes, intended use, and the human decision that follows.

#### Does not mean

It does not mean AI owns the task or that every AI output is ready to use.

#### Example

A team uses AI to draft a donor update that will be reviewed before sending.

#### Related terms

Task basis; review; approval standing

---

### 5.2 Organisational context

#### Definition

Relevant context around the organisation and task, including people, audience, authority, history, timing, operating practice, consequences, language, and local setting.

#### In plain English

It is the wider real-world setting around the task.

#### Why it matters

It helps reviewers see what may be missing from the narrow material given to AI.

#### Includes

Formal records, informal practice, local constraints, decision history, audience expectations, and approval boundaries.

#### Does not mean

It does not mean every piece of organisational knowledge should be put into AI.

#### Not the same as

**Unstated context** — organisational context is the wider setting around the organisation and task; unstated context is the relevant part of that wider context that is absent from, incomplete in, or not adequately represented in the task basis.

#### Example

A venue rule, a funder preference, and a recent complaint may all affect how a message should be drafted.

#### Related terms

Task basis; unstated context; organisational context handling

---

### 5.3 Task basis

#### Definition

The information and boundaries actually available for the current AI-supported task.

#### In plain English

It is what the task is really based on at the moment of prompting or review.

#### Why it matters

It shows what AI and the reviewer can safely rely on for the current task.

#### Includes

The source packet, prompt, approved material actually used, review basis, and current decision record.

#### Does not mean

It does not include every fact the organisation knows unless that fact is available and permitted for the task.

#### Example

A policy PDF, a prompt, and a review note form the task basis for a policy Q&A draft.

#### Related terms

Source packet; approved record; unstated context

---

### 5.4 Unstated context

#### Definition

Any relevant information or context that is absent from, incomplete in, or not adequately represented in the task basis.

#### In plain English

It is context that matters for this task but is not properly available in the task basis.

#### Why it matters

It explains why AI may produce a plausible output that still misses something a responsible person or approved record would have changed.

#### Includes

Unstated context may come from people, approved records, both, or an unclear source. It may be explicit or implicit, easy or difficult to express, and safe or unsafe for AI use.

Use [[Unstated Context Control]] for the detailed recognition angles, source-location check, representability check, and handling guidance.

#### Does not mean

It does not mean only unwritten information, only implicit knowledge, or only information held in people’s memories.

#### Not the same as

**Unwritten information** — unstated context can be written or recorded; the defining issue is the task-basis gap, not whether the information exists in writing.

**Implicit context** — implicit context is context a person uses without stating it directly and is one possible source of unstated context. Recorded or otherwise explicit context can also be unstated when it was not retrieved, supplied, or adequately represented in the task basis.

#### Example

A rule exists in an approved procedure, but it was not retrieved for the current task, so it is unstated for this task.

#### Related terms

Task basis; source location; representability; Unwritten Context Gap

---

### 5.5 Implicit context

#### Definition

Context that a person may use without stating it directly.

#### In plain English

It is what someone may assume, sense, or apply automatically.

#### Why it matters

It is one common reason relevant context is absent from the task basis.

#### Includes

Tacit assumptions, relationship cues, routine workarounds, informal thresholds, and practical judgement.

#### Does not mean

It is not a synonym for all unstated context because some unstated context may be recorded but not retrieved.

#### Not the same as

**Unstated context** — implicit context describes context a person uses without stating it directly; unstated context describes relevant context that is absent from, incomplete in, or not adequately represented in the task basis. Recorded context can therefore be unstated without being implicit.

#### Example

An event lead knows a supplier is usually late but does not mention it in the prompt.

#### Related terms

Unstated context; tacit knowledge; professional instinct

---

### 5.6 Source location

#### Definition

Possible source locations for relevant unstated context: people, approved records, both, or unclear.

#### In plain English

Source location identifies where to look before deciding how to handle the gap.

#### Why it matters

It prevents reviewers from treating all missing context as something to ask people or all context as something records already solve.

#### Includes

People, approved records, both people and records, or unclear source.

#### Does not mean

It does not describe how safe, clear, reliable, or complete the context is.

#### Not the same as

**Context type** — source location identifies where relevant context may exist; context type describes what kind of context it is.

**Representability** — source location identifies where to look; representability describes how clearly, faithfully, and safely the context can be expressed once found or surfaced.

#### Example

A venue access rule may be in an operations note, known by the event lead, or both.

#### Related terms

Representability; approved record; elicitation; retrieve

---

### 5.7 Representability

#### Definition

How clearly, faithfully, and safely context can be expressed for the task or AI interaction.

#### In plain English

Representability concerns whether context can be turned into usable wording without distortion or harm.

#### Why it matters

Some useful context should be converted, limited, kept human-only, or escalated instead of being copied into AI.

#### Includes

Clearly expressible, partly expressible, difficult to articulate, unsafe or inappropriate to state, or not fully expressible for AI use.

#### Does not mean

It is not the same as reliability; context can be reliable but unsafe or difficult to express.

#### Not the same as

**Source location** — source location identifies where context may exist; representability describes how safely and faithfully it can be expressed.

**Reliability** — representability concerns expression; reliability concerns trustworthiness. Context can be reliable but difficult or unsafe to express.

#### Example

A reviewer may know the relationship history matters but decide only a neutral wording constraint should enter the prompt.

#### Related terms

Source location; reliability; human-only handling

---

### 5.8 Reliability

#### Definition

How trustworthy the context is for the current task, given its source, age, accuracy, approval status, and dispute level.

#### In plain English

Reliability concerns whether the context can be trusted.

#### Why it matters

Reliable context can support action; unreliable context may need verification or escalation.

#### Includes

Current approved records, dated decision records, corroborated facts, and owner confirmation only where the owner has suitable knowledge, authority, and accountability.

#### Does not mean

It is not the same as representability; trustworthy context may still be unsafe to put into AI.

#### Not the same as

**Representability** — reliability concerns whether context can be trusted; representability concerns whether it can be expressed clearly, faithfully, and safely. Trustworthy context may still be unsuitable to place into AI.

#### Example

A signed board decision is reliable, but the reason behind it may still be sensitive.

#### Related terms

Verification; approved record; representability

---

### 5.9 Accumulated context

#### Definition

Context built from repeated exposure to tasks, decisions, people, patterns, exceptions, and outcomes over time.

#### In plain English

It is what experience has built up across work.

#### Why it matters

It explains why experienced people may notice missing pieces that a prompt does not show.

#### Includes

Repeated-task learning, prior decisions, exceptions, practical patterns, and observed consequences.

#### Does not mean

It is not the same as tacit knowledge, although it may produce tacit knowledge.

#### Not the same as

**Tacit knowledge** — accumulated context is built over time through repeated exposure and may be explicit or recorded; tacit knowledge is know-how a person uses but may find hard to state fully. Accumulated context can produce tacit knowledge, but the terms are not interchangeable.

#### Example

A coordinator remembers which venue arrangements usually fail because they have managed similar events many times.

#### Related terms

Tacit knowledge; organisational memory; professional instinct

---

### 5.10 Tacit knowledge

#### Definition

Knowledge a person uses in practice but may find hard to state fully or systematically.

#### In plain English

It is know-how that may sit below the surface.

#### Why it matters

It may need careful elicitation because direct questions often miss it.

#### Includes

Practical know-how, judgement cues, informal thresholds, and experience-based distinctions.

#### Does not mean

It is not the same as all accumulated context, and it is not automatically reliable or appropriate to record.

#### Not the same as

**Accumulated context** — tacit knowledge is defined by the difficulty of fully stating practical know-how; accumulated context is defined by how context builds through repeated experience over time. Accumulated context may remain explicit and may also produce tacit knowledge.

#### Example

A senior reviewer senses that a proposed deadline is unrealistic before they can list every reason.

#### Related terms

Implicit context; accumulated context; professional instinct

---

### 5.11 Lived context

#### Definition

Context shaped by being inside a real situation, relationship, community, role, vulnerability, or moment.

#### In plain English

It is first-hand understanding that may not be fully captured in a description, source packet, or AI interaction.

#### Why it matters

It protects against assuming that written summaries carry the full human impact of a task.

#### Includes

Relationship history, vulnerability, local experience, timing sensitivity, cultural meaning, and recipient impact.

#### Does not mean

It does not mean a person is automatically correct or that AI should receive private details.

#### Not the same as

**Professional instinct** — lived context is first-hand understanding shaped by being inside a real situation, relationship, community, role, vulnerability, or moment; professional instinct is an experience-based signal that something may be unusual, incomplete, risky, or not ready.

#### Example

A support worker understands why a technically accurate message may still feel harsh to a particular group.

#### Related terms

Recipient Impact Blindness; human-only handling; representability

---

### 5.12 Professional instinct

#### Definition

An experienced person’s practical sense that something may be unusual, risky, incomplete, or not ready.

#### In plain English

It is an experience-based signal that something may need more checking.

#### Why it matters

It helps identify anomalies and escalation needs that may not be visible in the task basis.

#### Includes

Anomaly recognition, practical red flags, risk thresholds, and readiness judgement.

#### Does not mean

It is not proof by itself and should not replace verification where verification is needed.

#### Not the same as

**Lived context** — professional instinct is an experience-based signal that further checking may be needed; lived context is first-hand understanding of a real situation or relationship. Either may inform review, but neither is automatically proof.

#### Example

An accountant notices a number looks plausible but unusual for this organisation’s normal pattern.

#### Related terms

Anomaly Instinct Gap; Verification Control; reviewer standing

---

### 5.13 Elicitation

#### Definition

Helping a suitable person notice and surface relevant context they know, remember, sense, or normally act on but may not state on direct request.

#### In plain English

Elicitation uses better, safer questions to surface missing context.

#### Why it matters

It helps reduce gaps where relevant context is carried by people or is hard to express.

#### Includes

Specific, focused questions, suitable concrete reference points, safety and standing checks, context surfacing, and neutral permission for nothing relevant.

#### Does not mean

It is not the whole control and does not replace handling, records, verification, specialist review, or escalation. Handling follows after elicitation under the wider Unstated Context Control.

#### Not the same as

**Unstated Context Control** — elicitation is one way of surfacing relevant context from a suitable person; Unstated Context Control is the wider Control that also covers locating, retrieving, assessing, converting, verifying, keeping human-only, and escalating where appropriate.

**Handling** — elicitation surfaces context; handling decides what may be added, converted, kept human-only, verified, referred, escalated, or not used or recorded.

#### Example

Instead of asking “Anything else?”, a reviewer asks, “What would an experienced person check before using this?”

#### Related terms

Unstated Context Control; source location; representability

---

### 5.14 Retrieve

#### Definition

Locate and bring a current approved source into the task process.

#### In plain English

It is locating and bringing the right approved record into the task process before asking people to recreate it.

#### Why it matters

It prevents avoidable re-elicitation and supports a stronger task basis.

#### Includes

Approved policies, decision records, source documents, forms, and current operational notes.

#### Does not mean

It is not the same as extracting material, applying it to the task, or using unapproved material.

#### Not the same as

**Extract** — retrieve locates and brings the approved source into the task process; extract selects the task-relevant material from that source.

**Handling** — retrieval makes the source available; handling decides how relevant material may be used for the task.

#### Example

A reviewer retrieves the latest approved venue checklist before drafting event instructions.

#### Related terms

Approved record; extract; source packet

---

### 5.15 Extract

#### Definition

Select the task-relevant part of a retrieved approved source.

#### In plain English

It is selecting the part of a source that the task needs.

retrieve
→ locate and bring the source

extract
→ select the relevant approved material

handle
→ decide how the material may be used for the task

#### Why it matters

It limits overload, privacy exposure, and irrelevant context.

#### Includes

Relevant clauses, constraints, dates, approval limits, and source references.

#### Does not mean

It does not mean copying the whole record into AI, changing the approved meaning, or deciding how the material may be used.

#### Not the same as

**Retrieve** — retrieve locates and brings the approved source into the task process; extract selects the relevant approved material after retrieval.

**Handling** — extraction selects relevant material; handling decides its permitted use for the task.

#### Example

From a full policy, the reviewer extracts only the paragraph that governs refund wording.

#### Related terms

Retrieve; source packet

---

### 5.16 Approved record

#### Definition

A record that the organisation permits for the intended use and whose owner, status, currentness, applicability, permission, and access are sufficiently established for the task.

#### In plain English

It is a source that has standing for the intended use in the current task.

#### Why it matters

It supports review, retrieval, verification, and accountable reuse.

#### Includes

Approved policies, procedures, decision records, templates, source registers, and controlled notes.

#### Does not mean

It does not mean every document in a drive, every old email, or every AI-generated note is approved. Approval for one purpose does not automatically approve every other use or AI disclosure.

#### Example

A board-approved policy is an approved record for answering a policy question.

#### Related terms

Source owner; retrieve; verification

---

### 5.17 Source packet

#### Definition

The bounded set of task-relevant approved sources, context, instructions, exclusions, authority information, intended use, review requirements, and current decision information assembled for the current task.

#### In plain English

It is the package of information the task relies on.

#### Why it matters

A clear source packet reduces blind spots and makes review traceable.

#### Includes

Current approved sources, audience, purpose, exclusions, authority boundary, intended use, review basis, escalation route, prompt context, and current decision information.

#### Does not mean

It does not mean every available document or all organisational memory.

#### Example

A translator receives the original notice, audience, tone limits, and terms to preserve.

#### Related terms

Task basis; approved record; Source Packet Add-On

---

### 5.18 Human-only handling

#### Definition

Keeping underlying context outside AI and handling the affected judgement through a suitable person or approved process.

#### In plain English

It means the human handles what AI should not receive or decide.

#### Why it matters

It helps protect privacy, safety, relationships, authority boundaries, and context that cannot be represented safely.

#### Includes

Sensitive context, relational nuance, safeguarding matters, restricted records, and specialist judgement.

#### Does not mean

It is not concealment, avoidance, or a way to skip review.

#### Not the same as

**Concealment** — human-only handling keeps context that is unsafe or unsuitable for AI within an appropriate human or approved process while still routing the issue responsibly; concealment would hide or avoid the issue instead of handling it.

#### Example

A reviewer keeps a vulnerable person’s details out of AI and asks the accountable owner to draft the sensitive sentence.

#### Related terms

Representability; escalation

---

### 5.19 Organisational context handling

#### Definition

The wider lifecycle for identifying, sourcing, assessing, using, converting, preserving, maintaining, retrieving, or escalating organisational context.

#### In plain English

It is the broader context-management problem around the task.

#### Why it matters

It shows why some issues must be routed beyond this guide’s current detailed scope.

#### Includes

Classification, routing, preservation, repository design, lifecycle governance, access control, retrieval, and RAG implementation.

#### Does not mean

It is not fully provided here and should not be treated as the same as Unstated Context Control.

#### Example

An organisation may need a formal system for deciding which recurring context belongs in controlled records.

#### Related terms

Unstated Context Control; organisational memory; RAG

---

### 5.20 Preservation

#### Definition

Keeping a safe, reliable, necessary, permitted, and reusable context note or record for later use through an approved owner and location.

#### In plain English

It is saving only what should be safely kept.

#### Why it matters

It prevents repeated rediscovery while avoiding unsafe or excessive recording.

#### Includes

Small exception notes, checklist updates, approved records, restricted owner notes, and review triggers.

#### Does not mean

It does not mean automatic recording, unlimited retention, or making context AI-ready.

#### Not the same as

**Automatic recording** — preservation is a separate, optional governed decision based on safety, permission, reliability, usefulness, an owner, and an approved location; it is not an automatic consequence of surfacing useful context.

#### Example

After repeated event reviews, a team records a safe note that the rear entrance needs owner approval.

#### Related terms

Organisational memory; approved record; human-only handling

---

### 5.21 Organisational memory

#### Definition

The organisation’s ability to carry useful context from past work into later work through people, records, habits, systems, and approved processes.

#### In plain English

It is how an organisation remembers safely and usefully.

#### Why it matters

It helps reduce repeated mistakes and unnecessary re-elicitation.

#### Includes

People’s experience, approved records, templates, checklists, exception notes, and retrieval habits.

#### Does not mean

It is not the same as RAG, a database, or automatic preservation.

#### Not the same as

**Retrieval-augmented generation (RAG)** — organisational memory is the broader human and organisational capability for carrying useful context forward through people, records, habits, systems, and approved processes; RAG is one technical implementation route that may support part of that capability.

#### Example

A team checklist reminds future reviewers to verify venue access before drafting instructions.

#### Related terms

Preservation; accumulated context; approved record

---

### 5.22 Retrieval-augmented generation (RAG)

#### Definition

A technical approach that retrieves relevant material from an approved knowledge source and supplies it to an AI system for a task.

#### In plain English

It is one possible technical way to bring records into AI-supported work.

#### Why it matters

It may support source use, but it also needs governance, access, accuracy, and review controls.

#### Includes

Retrieval pipelines, source indexes, chunking, permissions, citations, and model prompts.

#### Does not mean

It is not organisational memory itself and not verification by itself. This guide does not provide a full RAG implementation method. Full RAG implementation is outside the current detailed scope. RAG does not automatically make information current, reliable, authorised, complete, or safe.

#### Not the same as

**Organisational memory** — RAG is a technical approach for retrieving material into AI-supported work; organisational memory is the broader organisational capability that may use people, records, habits, processes, or systems with or without RAG.

#### Example

A system retrieves approved policy passages before AI drafts a policy answer, but a reviewer still checks the result.

#### Related terms

Retrieve; approved record; organisational context handling

---

### 5.23 Review

#### Definition

Human examination of an AI-supported task or output against the task basis, intended use, risks, and required controls.

#### In plain English

It is checking whether the output is ready, needs correction, or must be escalated.

#### Why it matters

It keeps responsibility with a suitable person rather than the AI system.

#### Includes

Source comparison, context checks, authority checks, risk review, impact review, and reviewer-standing checks.

#### Does not mean

It is not the same as Verification Control; review may identify that verification is needed.

#### Not the same as

**Verification Control** — review assesses whether an AI-supported task or output is suitable for its intended use; Verification Control checks support or correctness through a sufficiently independent approved basis. Review may identify that verification is required, but review alone does not establish independent verification.

#### Example

A reviewer checks whether a draft notice fits the audience, source, authority, and timing.

#### Related terms

Verification Control; reviewer standing; decision labels

---

### 5.24 Control

#### Definition

A defined safeguard used to address one or more AI Blind Spot risks.

#### In plain English

A Control says what safeguard is being applied, not merely what risk exists or who is asked to act.

#### Why it matters

It separates the safeguard from the risk, the Method used to carry it out, and the Accountable Route used when responsibility or authority must move elsewhere.

#### Includes

The current canonical Controls are listed and defined only in [[AI Blind Spot Control Map]].

#### Does not mean

It is not the same as a risk name, Method, Accountable Route, role, sign-off action, tool, prompt, or complete procedure. A Control may address several risks and a risk may require several Controls.

#### Not the same as

**Risk** — a risk identifies the problem; a Control defines a safeguard that may address one or more risks.

**Method** — a Control states the safeguard and its objective; a Method is a reusable way of carrying out or supporting one or more Controls.

**Accountable Route** — a Control defines the safeguard; an Accountable Route identifies where responsibility, authority, expertise, review, approval, verification, or escalation goes.

#### Example

For a material factual claim, Verification Control requires a sufficiently independent check before the claim is relied on. The Control is the safeguard being applied; the canonical relationship map remains in [[AI Blind Spot Control Map]].

#### Related terms

Method; Accountable Route; AI Blind Spot

---

### 5.25 Method

#### Definition

A defined and reusable way of carrying out or supporting one or more Controls.

#### In plain English

A Method explains how part of a safeguard can be performed.

#### Why it matters

It allows a reusable way of working to support several Controls without incorrectly treating the technique itself as a separate Control.

#### Includes

The current canonical Methods are listed and defined only in [[AI Blind Spot Control Map]].

#### Does not mean

A procedural step, technique, prompt, question, tool, or review action is not automatically a canonical Method. Canonical Methods are explicitly defined and use the `Method` suffix.

#### Not the same as

**Control** — a Method describes a reusable way of carrying out or supporting a safeguard; the Control defines the safeguard itself and its objective.

**Accountable Route** — a Method describes how work may be carried out; an Accountable Route identifies where accountable action must go.

#### Example

Approved Basis Comparison Method is a reusable way to compare a material point with an approved basis. The Method describes how the check is carried out; the canonical supported-Control relationships remain in [[AI Blind Spot Control Map]].

#### Related terms

Control; Accountable Route; elicitation; review

---

### 5.26 Accountable Route

#### Definition

A defined path to a person, role, reviewer, owner, approved process, or escalation point with the responsibility, authority, competence, independence, access, or accountability needed to act.

#### In plain English

It says where accountable action must go when the current person or process cannot responsibly resolve the issue alone.

#### Why it matters

It keeps responsibility, authority, specialist judgement, approval, and escalation with an appropriate person or process rather than treating them as properties of AI.

#### Includes

The current canonical Accountable Routes are listed and defined only in [[AI Blind Spot Control Map]].

#### Does not mean

A role name, reviewer action, sign-off, forwarding step, or specialist topic is not automatically a canonical Accountable Route. Canonical routes are explicitly defined and use the `Route` suffix.

#### Not the same as

**Control** — an Accountable Route identifies where accountable action goes; a Control defines the safeguard being applied.

**Method** — an Accountable Route identifies the accountable destination or path; a Method describes a reusable way of carrying out or supporting one or more Controls.

**Current-task handling route** — an Accountable Route is a canonical path to accountable action; a current-task handling route is one of the seven handling choices in Unstated Context Control, and only some of those choices involve an Accountable Route.

#### Example

An output that appears to make an unauthorised commitment may move through the Authority Owner Route rather than being approved by the drafter.

#### Related terms

Control; Method; reviewer standing; escalation

---

## 6. Category B — Roles and standing

The terms in this category describe different kinds of responsibility, ownership, review, standing, and escalation. They do not necessarily identify different people. One person may hold more than one role in a particular task, but holding one role does not automatically confer the accountability, authority, competence, or standing of another.

---

### 6.1 How the Roles and Standing Fit Together

| Term | Main question it answers |
|---|---|
| **Responsible person** | Who has a responsibility to notice, act, route, or escalate appropriately here? |
| **Responsible owner** | Who ensures that the matter has an appropriate approved route and is not left unmanaged? |
| **Source owner** | Who is accountable for the source’s status, meaning, access, currentness, and maintenance? |
| **Decision owner** | Who is accountable for the decision affected by the AI-supported work? |
| **Authority owner** | Who has the organisational authority to approve, promise, decide, refuse, authorise, or speak for the organisation? |
| **Operational owner** | Who is accountable for how the relevant process, venue, supplier, event, team, or workflow actually operates? |
| **Accountable reviewer** | Who is assigned responsibility for the review outcome within their standing? |
| **Specialist reviewer** | Who supplies the specialist competence required for the review? |
| **Reviewer standing** | Is the reviewer sufficiently suitable and equipped to perform the required review or ask the required questions? |
| **Approval standing** | Is the person or body authorised and accountable to approve the output for the intended use? |
| **Escalation** | Where should an unresolved issue go when the current person cannot safely resolve it within their standing? |

The owner roles remain distinct accountabilities rather than sub-types of `Responsible owner`. A responsible owner may need to identify or coordinate the relevant source owner, decision owner, authority owner, operational owner, accountable reviewer, specialist reviewer, or another approved route. The same person may hold more than one of these roles where appropriately assigned, but that overlap should not be assumed.

---

### 6.2 Responsible person

#### Definition

A person who must act appropriately in relation to the current task or issue. It is a broad responsibility description that may apply to a formally assigned task performer, owner, reviewer, or approver, or to another person who has a responsibility to notice, act, route, or escalate.

#### When this term is used

Use this term when this guide refers to what a person must notice, solve, check, route, or escalate.

#### Not the same as

**Responsible owner** — both terms describe responsibility, so a reader may assume that anyone who must act on an issue is also the owner responsible for its overall routing. A responsible person has a responsibility to act appropriately within the situation; a responsible owner has the narrower accountability for ensuring that the matter has an appropriate approved route and is not left unmanaged. A task performer, reviewer, approver, or other person may therefore be a responsible person without being the responsible owner.

#### Example

A staff member who notices that a draft may affect an earlier commitment is a responsible person for routing that issue appropriately, even if they are not the owner or approver.

---

### 6.3 Responsible owner

#### Definition

The person accountable for ensuring that the task, output, or issue has an appropriate approved route and is not left unmanaged.

#### When this term is used

Use this term when someone must ensure that the task, output, or issue reaches the right source owner, decision owner, authority owner, operational owner, accountable reviewer, specialist reviewer, or other approved route and is not left unmanaged.

Routing a matter to a specialist reviewer does not by itself transfer responsible-owner accountability. The specialist reviewer may provide the specialist judgement needed for the matter, while the responsible owner remains accountable for ensuring that any required review, decision, approval, routing, escalation, or follow-up is appropriately addressed.

#### Not the same as

**Responsible person** — both terms concern responsibility, so a reader may assume they identify the same role. `Responsible person` is the broader description of anyone who must act appropriately in relation to the matter; `Responsible owner` identifies the narrower accountability for ensuring that the matter has an appropriate approved route and is not left unmanaged.

**Source owner, decision owner, authority owner, or operational owner** — the shared word `owner` can make these roles look interchangeable. They are separate owner roles with particular source, decision, authority, or operational accountabilities. The responsible owner ensures that the appropriate route exists rather than automatically holding those specific accountabilities. The same person may hold more than one owner role where appropriately assigned.

**Specialist reviewer** — the roles can appear similar after a responsible owner routes an issue to a specialist and the specialist becomes the person visibly handling it. A specialist reviewer contributes the specialist competence needed for the review; receiving or reviewing the issue does not by itself make that reviewer the responsible owner for ensuring that the wider matter remains appropriately routed and managed.

#### Example

A programme lead remains the responsible owner for a privacy-sensitive member communication after routing the privacy question to a specialist reviewer. The specialist provides the privacy judgement; the programme lead still ensures that any required decision, approval, escalation, and follow-up are appropriately addressed.

---

### 6.4 Source owner

#### Definition

The person or function accountable for a source’s status, meaning, access, currentness, and maintenance.

#### When this term is used

Use this term when a source needs confirmation, interpretation, update, or correction.

#### Not the same as

**Decision owner** — both may be asked to resolve a question arising from the same task, especially when a decision depends on a particular source. The source owner is accountable for the source’s status, meaning, access, currentness, and maintenance; the decision owner is accountable for the decision affected by the work. Confirming a source does not by itself make the source owner accountable for the resulting decision.

**Authority owner** — a reader may assume that the person who controls or confirms an authoritative source also has authority to approve organisational action. The source owner is accountable for the source; the authority owner holds the organisational authority to approve, promise, decide, refuse, authorise, or speak for the organisation. The roles may overlap, but one does not automatically confer the other.

#### Example

The HR policy owner confirms which leave-policy version is current.

---

### 6.5 Decision owner

#### Definition

The person or body accountable for the decision that the AI-supported work may affect.

#### When this term is used

Use this term when the output influences a real decision.

#### Not the same as

**Source owner** — both may be involved because a decision depends on a source, which can make the source-confirmation role look like decision ownership. The decision owner is accountable for the real decision affected by the work; the source owner is accountable for the status and meaning of a source used in that work.

**Authority owner** — the same person may often hold both roles, so decision accountability can be mistaken for authority to approve or commit the organisation. The decision owner is accountable for the underlying decision; the authority owner holds the organisational authority to approve, promise, decide, refuse, authorise, or speak for the organisation. The roles may overlap but should not be assumed to be identical.

#### Example

A grant committee is the decision owner for approving a submission.

---

### 6.6 Authority owner

#### Definition

The person or body with authority to approve, promise, decide, refuse, authorise, or speak for the organisation.

#### When this term is used

Use this term when authority boundary is the issue.

#### Not the same as

**Decision owner** — the same person may often hold both roles, so accountability for a decision can be mistaken for organisational authority. The authority owner holds authority to approve, promise, decide, refuse, authorise, or speak for the organisation; the decision owner is accountable for the underlying decision the work may affect. The roles may overlap but should not be assumed to be identical.

**Responsible person** — a person who notices or must act on an authority issue may appear to be the person entitled to resolve it. A responsible person has a duty to act appropriately and route the issue, but that duty does not by itself confer organisational authority.

#### Example

Only the board chair may approve a public statement on behalf of the organisation.

---

### 6.7 Operational owner

#### Definition

The person or role accountable for how a process, venue, supplier, event, team, or workflow actually operates.

#### When this term is used

Use this term when practical execution details need confirmation.

#### Not the same as

**Source owner** — operational facts are often recorded in schedules, procedures, supplier records, or other sources, so the person who knows how something operates can be mistaken for the owner of those records. The operational owner is accountable for how the process, venue, supplier, event, team, or workflow actually operates; the source owner is accountable for the status and maintenance of the source that records or describes it.

**Decision owner** — an operational owner may provide the practical facts on which a decision depends and may sometimes also make the decision. Operational ownership concerns how the matter actually works in practice; decision ownership concerns accountability for the decision the AI-supported work may affect. The roles may overlap but should not be assumed to be identical.

#### Example

The event lead is the operational owner for room setup and access timing.

---

### 6.8 Accountable reviewer

#### Definition

A reviewer assigned responsibility for the review outcome and for deciding whether to approve, correct, refer, or escalate within their standing.

#### When this term is used

Use this term when review must produce a responsible review outcome within the reviewer’s standing.

#### Not the same as

**Reviewer standing** — because an accountable reviewer has been assigned the review, a reader may assume that assignment itself proves the reviewer is suitable to perform every required part of it. `Accountable reviewer` identifies responsibility for the review outcome; `reviewer standing` concerns whether that reviewer has sufficient role, trust, context, authority, competence, independence, access, safety, permission, and accountability to perform the required review.

**Approval standing** — an accountable reviewer may be the person who gives the final review outcome, which can look like authority to approve the output for use. Responsibility for the review outcome does not automatically confer approval standing.

**Specialist reviewer** — both are reviewer roles and the same person may hold both, so they can easily appear interchangeable. A specialist reviewer is identified by the specialist competence needed for the review; an accountable reviewer is assigned responsibility for the review outcome. A specialist may advise without owning that outcome, and an accountable reviewer may need specialist input before reaching it.

**Responsible person** — a person who notices or routes a review issue may be actively involved without being the assigned reviewer. `Responsible person` is a broader duty to act appropriately; `accountable reviewer` identifies responsibility for the review outcome.

#### Example

A communications lead reviews a donor email because they know the audience and have approval responsibility.

---

### 6.9 Specialist reviewer

#### Definition

A reviewer with relevant professional, technical, legal, regulatory, safeguarding, linguistic, cultural, financial, pastoral, theological, or other specialist competence.

#### When this term is used

Use this term when the task touches legal, financial, HR, safeguarding, medical, theological, technical, or other specialist matters.

#### Not the same as

**Accountable reviewer** — both are reviewer roles and the same person may hold both, so specialist expertise can be mistaken for responsibility for the whole review outcome. A specialist reviewer is identified by relevant specialist competence; an accountable reviewer is assigned responsibility for the review outcome. A specialist may advise without owning that outcome, and an accountable reviewer may need specialist input.

**Responsible owner** — after a matter is routed for specialist input, the specialist reviewer may become the person visibly handling the issue and can therefore appear to have taken ownership of the whole matter. Specialist competence does not by itself create responsible-owner accountability for ensuring that the wider matter has an appropriate approved route and is not left unmanaged.

**General reviewer** — both perform review, but the specialist label is used because the matter requires particular professional, technical, legal, regulatory, safeguarding, linguistic, cultural, financial, pastoral, theological, or other specialist competence. A general reviewer may conduct ordinary review without that specialist role.

#### Example

A privacy specialist reviews a draft that involves personal data handling.

---

### 6.10 Reviewer standing

#### Definition

Whether a reviewer has enough role, trust, context, authority, competence, independence, access, safety, permission, and accountability to perform the required review or ask the required questions.

#### When this term is used

Use this term before relying on a reviewer’s judgement.

#### Not the same as

**Approval standing** — both concern whether a person is suitably positioned to act, and the same person may sometimes have both, so being able to review can be mistaken for being able to approve. Reviewer standing concerns whether a person is suitable and sufficiently equipped to perform the required review or ask the required questions; approval standing concerns whether the person or body has authority and accountability to approve the output for the intended use. A person may have reviewer standing without approval standing.

#### Example

A volunteer may notice a problem but may not have standing to approve the final external message.

---

### 6.11 Approval standing

#### Definition

Whether the person or body has authority and accountability to approve the output for the intended use.

#### When this term is used

Use this term before choosing Approve or Correct then approve.

#### Not the same as

**Reviewer standing** — both concern whether a person is suitably positioned to act, and the same person may sometimes have both, so successful or responsible review can be mistaken for authority to approve. Approval standing is authority and accountability to approve the output for the intended use; reviewer standing is suitability to perform the required review or ask the required questions. Being able to review responsibly does not automatically mean being authorised to approve.

#### Example

A team member can review a draft, but only the authorised sender has approval standing to send it.

---

### 6.12 Escalation

#### Definition

Moving the task, context, or issue to a person or process with the necessary authority, competence, independence, access, or accountability.

#### When this term is used

Use this term when the reviewer cannot safely resolve the issue within their standing.

#### Not the same as

**Delay or avoidance** — both can result in the current person not resolving the issue immediately, which can make inaction look like escalation. Escalation actively moves the unresolved issue to a suitable person or approved process; delay or avoidance leaves it unresolved without an accountable route.

**Approval** — an escalated matter may eventually return with an approval decision, so escalation can be mistaken for approval itself. Escalation only moves the unresolved issue to a route with the necessary standing; it does not approve the output.

**Merely forwarding an AI output** — both involve sending material to someone else, but forwarding alone does not establish why the matter needs attention or who is accountable for resolving it. An accountable escalation identifies the issue, required decision or action, and the reason the receiving route is appropriate.

#### Example

A reviewer escalates a draft when it makes a commitment only the board can approve.

---

## 7. Category C — Decision labels

### 7.1 Approve

#### Definition

A decision to use the output because no unresolved context, control, authority, or reviewer-standing issue remains for the intended use.

#### Who may use it

Only a reviewer with suitable reviewer standing and approval standing may use this label.

#### Does not mean

It does not mean the output is universally safe or approved for other uses.

---

### 7.2 Correct then approve

#### Definition

A decision to correct, safely convert, verify, or record the minimum necessary item before use, then approve only if the reviewer has suitable standing.

#### Who may use it

Only a reviewer with suitable reviewer standing and approval standing after correction may use this label.

#### Does not mean

It does not mean unresolved risks can be ignored.

---

### 7.3 Stop and escalate

#### Definition

A decision to stop use and route the issue to an approved owner, reviewer, specialist, or process.

#### Who may use it

Any reviewer should use this label when the issue exceeds their standing or safe task boundary.

#### Does not mean

It does not mean the work has failed; it means the issue needs a suitable route.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Blind Spot Guide Feedback Form](https://forms.gle/se5ruqaZeytDoFENA)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
