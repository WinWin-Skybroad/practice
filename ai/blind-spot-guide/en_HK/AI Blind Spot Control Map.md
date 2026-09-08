---
title: AI Blind Spot Control Map
created: 2026-07-06
updated: 2026-09-07
version: "1.0"
status: active
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
locale: en_HK
type: guide
tags:
  - control-map
  - risk-map
---

# AI Blind Spot Control Map

## 1. Purpose and Scope

Use this page to identify the **currently recognised Controls, Methods, and Accountable Routes** that may be relevant to an AI Blind Spot risk.

This page has two jobs:
- it is the canonical registry for the individual Controls, Methods, and Accountable Routes recognised by the **Win.Win AI Blind Spot Guide**; and
- it explains how canonical AI Blind Spot risks relate to those recognised elements, including why an item may help and which Controls are most direct or conditional.

[[Glossary]] defines what the architectural terms **Control**, **Method**, and **Accountable Route** mean across this guide. This page defines the individual canonical instances.

The relationships are many-to-many:
- one risk may relate to several Controls;
- one Control may address several risks;
- one Method may support several Controls; and
- one Accountable Route may be relevant to several Controls or risks.

Controls, Methods, and Accountable Routes remain distinct registry types. A Method is not automatically a Control. A role, reviewer, sign-off action, forwarding step, or specialist topic is not automatically an Accountable Route.

An item is canonical only if it is defined in the corresponding registry below.

If you already know the risk, go directly to [[#7. Risk Relationships|Risk Relationships]]. You do not need to read every registry entry first. Use Sections 3–5 when you need the authoritative definition of a particular Control, Method, or Accountable Route.

**How this guide currently helps** describes the practical guidance available in this guide for that risk. It does not imply that this guide provides detailed implementation guidance for every related Control, Method, or Accountable Route.

Use:
- [[AI Blind Spot Risk Library]] for fuller risk explanations;
- the relevant Control, Method, template, or guide page when detailed working guidance exists; and
- [[Guide Scope And Positioning]] to check what this guide covers in detail and where its boundaries sit.

This registry is not a claim that the recognised set is permanently complete. Do not invent a canonical Control, Method, or Accountable Route merely to complete a relationship entry; add one only through owner-approved development when its meaning and boundary are sufficiently established.

---

## 2. Registry Entry Structure Standard

The **Controls**, **Methods**, and **Accountable Routes** sections are governed canonical registries. Their entries tell readers what each recognised item means and constrain authors from changing its function through free-form wording elsewhere.

Each canonical entry uses a common heading structure so substantive fields can contain the paragraphs, lists, notes, or cross-references they need without being forced into a single colon-style paragraph.

Use the exact canonical item name as the H3 heading. Use H4 headings for substantive entry fields. Bold key-value labels may be used only for genuinely compact metadata where needed; do not use them as substitutes for substantive entry sections.

Canonical Controls end with `Control`, canonical Methods end with `Method`, and canonical Accountable Routes end with `Route`.

---

### 2.1 Control entries

Every Control entry must contain the following sections.

#### Definition

State what the safeguard is.

#### Control objective

State what the safeguard is intended to achieve.

#### Boundary

State what the Control does not establish, replace, authorise, or prove.

#### Guidance in this guide

State whether and where detailed or supporting guidance currently exists.

#### Relevant Methods

Identify canonical Methods that may support the Control when they are meaningfully relevant. For each Method, state briefly **how it helps carry out or support this Control**. Do not use an unexplained name-only list for a relationship field.

Do not name a Control after a risk merely to create one-to-one symmetry. A Control may address several risks and a risk may relate to several Controls.

---

### 2.2 Method entries

Every Method entry must contain the following sections.

#### Definition

State what the reusable way of working is.

#### Purpose

State what implementation function it serves.

#### Supports

Identify the canonical Control or Controls the Method may support. For each Control or clearly related group of Controls, state briefly **what the Method contributes**. Do not use an unexplained name-only list for a relationship field.

#### Use when

State the conditions that make the Method relevant when those conditions need to be explicit.

#### Boundary

State what the Method does not establish, replace, authorise, or prove.

#### Detailed guidance

Identify where fuller instructions exist, or state that no fuller method is currently provided.

A procedural step, prompt, question, tool, reviewer action, or technique is not automatically a canonical Method.

---

### 2.3 Accountable Route entries

Every Accountable Route entry must contain the following sections.

#### Definition

State what path the Route creates.

#### Use when

State the condition that makes the Route relevant.

#### Accountability destination

Identify the person, role, reviewer, owner, or approved process receiving the matter.

#### Function

State the responsibility, authority, expertise, independence, approval, or escalation function supplied by the destination.

#### Boundary

State what the Route does not establish, replace, authorise, or guarantee.

Do not create a Route merely by adding `Route` to a role, sign-off action, forwarding step, or specialist topic.

Do not add empty fields for visual symmetry. If a future entry genuinely does not need a normally expected field, record the reason in owner-approved development rather than adding filler.

---

## 3. Controls

The entries below are the Controls currently recognised by this guide. A recognised Control may be defined here even when detailed application guidance is not currently provided elsewhere in this guide.

---

### 3.1 Unstated Context Control

#### Definition

Identifies, locates, assesses, uses elicitation when suitable, and safely handles relevant context that is absent from, incomplete in, or not adequately represented in the task basis.

#### Control objective

Reduce material task-basis gaps without assuming that all relevant context is recorded, safely expressible, suitable for AI, or can be fully expressed as instructions.

#### Boundary

This Control does not replace verification, authority, impact, local, specialist, operational, or other Controls that may also be relevant to the risk.

#### Guidance in this guide

This is the current detailed Control. Its most developed guidance concerns identifying and safely eliciting unstated context. Related current-task guidance also covers approved-source retrieval and extraction, representability, safe conversion, human-only handling, verification, accountable review, stopping, and escalation; those supporting areas are not all co-equal detailed modules.

#### Relevant Methods

- **Source Packet Check Method** — checks whether the approved task basis already contains the needed context before further collection.
- **Approved Record Retrieval and Extraction Method** — retrieves current approved records and extracts task-relevant material when the missing context is recorded.
- **Representability Assessment Method** — checks whether identified context can be expressed clearly, faithfully, and safely enough for AI-supported use.
- **Safe Elicitation Method** — helps surface relevant context held implicitly by suitable people when asking is safe and permitted.
- **Safe Conversion Method** — carries only the necessary safe effect into the AI task when the underlying context should remain outside AI.
- **Human-Only Handling Method** — keeps unsuitable or restricted context outside AI while allowing an authorised person or process to account for it.
- **Approved Basis Comparison Method** — compares a material claim, assumption, or decision basis with a sufficiently independent approved basis when checking is needed.
- **Reviewer Standing Check Method** — checks whether the person handling, reviewing, or eliciting the context has suitable standing for that function.

---

### 3.2 Communication Review Control

#### Definition

Reviews wording from the perspective of the actual reader or audience to identify material differences in interpretation, certainty, commitment, tone, timing, relationship meaning, or required action.

#### Control objective

Reduce the risk that wording which appears clear to the drafter is reasonably understood differently by the intended reader.

#### Boundary

This Control does not by itself establish recipient impact, authority, materiality, verification, or specialist acceptability.

#### Guidance in this guide

Defined in this registry and supported by risk and review guidance; a complete communication-review method is not currently provided.

#### Relevant Methods

- **Safe Elicitation Method** — helps surface audience, relationship, timing, or other context held by suitable people that may affect interpretation.
- **Bilingual Back-Check Method** — checks whether intended meaning, tone, conditions, and authority signals remain aligned across languages or registers.
- **Reviewer Standing Check Method** — checks whether the reviewer has suitable competence, context, permission, and standing to judge how the audience may interpret the wording.

---

### 3.3 Recipient Impact Review Control

#### Definition

Assesses material emotional, relational, practical, reputational, dignity, pressure, exclusion, or social effects that an AI-supported output may have on a real person or group.

#### Control objective

Ensure that recipient impact is considered before an output is used when its wording, timing, distribution, or action may affect people materially.

#### Boundary

This Control does not replace safeguarding, professional, legal, HR, counselling, pastoral, or other specialist processes when those processes are required.

#### Guidance in this guide

Defined in this registry and supported by risk and review guidance; a complete recipient-impact method is not currently provided.

#### Relevant Methods

- **Safe Elicitation Method** — helps surface relevant recipient or relationship context held by suitable people when asking is safe and appropriate.
- **Human-Only Handling Method** — allows sensitive recipient context to inform human judgement without exposing that context to AI.
- **Bilingual Back-Check Method** — checks whether language or register changes meaning, tone, pressure, dignity, or other recipient-facing effects.
- **Reviewer Standing Check Method** — checks whether the reviewer is suitably placed to judge material impact on the affected person or group.

---

### 3.4 Authority Review Control

#### Definition

Checks the authority boundary for an output, including who may approve, promise, decide, refuse, authorise, commit, or speak for the organisation, and prevents wording from exceeding that authority.

#### Control objective

Keep AI-supported drafting separate from human or organisational authority to make or communicate a decision or commitment.

#### Boundary

This Control identifies and protects authority boundaries; it does not grant authority to the drafter, reviewer, or AI system.

#### Guidance in this guide

Defined in this registry and supported by risk and reviewer-standing guidance; a complete authority-governance method is not currently provided.

#### Relevant Methods

- **Source Packet Check Method** — checks whether the task basis already contains the relevant authority boundaries, approvals, instructions, or exclusions.
- **Approved Record Retrieval and Extraction Method** — retrieves current approved records that may establish delegated authority, approval status, or decision boundaries.
- **Approved Basis Comparison Method** — compares a proposed commitment, decision, or authority claim with an approved basis rather than relying on AI or assumption.
- **Reviewer Standing Check Method** — checks whether the reviewer or approver has the role, authority, permission, competence, and accountability required for the function.

---

### 3.5 Materiality Review Control

#### Definition

Assesses whether a fact, condition, uncertainty, omission, dependency, or consequence is important enough to change a decision, approval, funding, trust, timing, rights, access, cost, or next action.

#### Control objective

Prevent material matters from being omitted, softened, misweighted, or treated as minor without accountable human judgement.

#### Boundary

This Control does not supply the organisation’s decision threshold when that threshold must come from an authorised owner, policy, source, or specialist judgement.

#### Guidance in this guide

Defined in this registry and supported by risk and review guidance; a complete materiality-assessment method is not currently provided.

#### Relevant Methods

- **Source Packet Check Method** — checks whether the task basis contains the thresholds, conditions, dependencies, consequences, or decision basis needed to judge materiality.
- **Approved Basis Comparison Method** — compares the matter with the relevant approved threshold, condition, account, right, obligation, or other decision-relevant basis.
- **Reviewer Standing Check Method** — checks whether the person making the materiality judgement has suitable role, competence, context, authority, and accountability.

---

### 3.6 Local Source Checking Control

#### Definition

Checks whether an output is grounded in current sources, policies, authorities, requirements, or practices applicable to the actual jurisdiction, sector, organisation, and local setting.

#### Control objective

Reduce reliance on general, overseas, stale, or locally inapplicable information.

#### Boundary

This Control does not make a general source locally authoritative and does not replace qualified local or sector interpretation when that interpretation is required.

#### Guidance in this guide

Defined in this registry and supported by source and verification guidance; a complete local-source methodology is not currently provided.

#### Relevant Methods

- **Source Packet Check Method** — checks whether the task basis includes current sources that apply to the actual jurisdiction, organisation, sector, or local setting.
- **Approved Record Retrieval and Extraction Method** — retrieves current locally applicable approved records and extracts the material needed for the task.
- **Approved Basis Comparison Method** — compares the output or assumption with an approved local basis rather than a generic, stale, or overseas source.
- **Reviewer Standing Check Method** — checks whether the reviewer has suitable competence, access, context, and standing to judge local applicability.

---

### 3.7 Verification Control

#### Definition

Checks a claim, source, output, or decision basis against a sufficiently independent approved source, tool, record, or suitably accountable reviewer.

#### Control objective

Prevent AI self-validation and unsupported reliance by requiring an adequate independent basis for the matter being checked.

#### Boundary

Verification is distinct from general review. The same AI repeating or agreeing with its own output is not independent verification, and an owner is not automatically sufficiently independent.

#### Guidance in this guide

Defined in this registry with supporting guidance relevant to current-task handling; a complete verification framework is not currently provided.

#### Relevant Methods

- **Approved Record Retrieval and Extraction Method** — retrieves an approved record that may provide part of the verification basis; retrieval itself is not verification.
- **Approved Basis Comparison Method** — performs the comparison against a sufficiently independent approved basis that the Control requires.
- **Reviewer Standing Check Method** — checks whether a reviewer used in the verification basis has suitable competence, access, standing, and independence for that function.

---

### 3.8 Challenge Handling Control

#### Definition

Preserves appropriate caution when a user challenges or pressures an AI-supported conclusion, and requires reliable new evidence, an authoritative record, or a suitably authorised owner before a material safeguard or uncertainty is reduced.

#### Control objective

Prevent unsupported user pressure from weakening a justified control, warning, uncertainty, or escalation requirement.

#### Boundary

This Control does not require a reviewer to defend an earlier conclusion when reliable new evidence shows that it should change.

#### Guidance in this guide

Defined in this registry and supported by the challenge rule in the Risk Library; a complete challenge-management framework is not currently provided.

#### Relevant Methods

- **Approved Basis Comparison Method** — checks whether reliable new evidence or an authoritative basis actually supports reducing a warning, uncertainty, safeguard, or escalation requirement.
- **Reviewer Standing Check Method** — checks whether the person judging or authorising the change has suitable standing rather than relying on pressure or preference alone.

---

### 3.9 Anomaly Review Control

#### Definition

Requires deliberate review of unusual figures, names, dates, sequences, formats, assumptions, process steps, omissions, expected information, or local warning signs that may indicate a material problem.

#### Control objective

Create a pause-and-check safeguard for signals that an experienced person, source owner, or specialist may recognise as abnormal or consequential.

#### Boundary

An anomaly is a trigger to investigate, not proof that the output is wrong or that a particular cause exists.

#### Guidance in this guide

Defined in this registry and supported by risk and review guidance; a complete anomaly-detection method is not currently provided.

#### Relevant Methods

- **Approved Basis Comparison Method** — checks an unusual signal against the relevant approved source, record, calculation, or other comparison basis.
- **Safe Elicitation Method** — helps surface experience-based context from suitable people when the anomaly depends on patterns not fully recorded elsewhere.
- **Reviewer Standing Check Method** — checks whether the reviewer has the relevant experience, competence, context, and standing to recognise and judge the anomaly.

---

### 3.10 Bicultural and Register Review Control

#### Definition

Checks whether intended meaning, tone, politeness, formality, authority, commitment, social signal, and recipient impact remain appropriate across language and cultural registers.

#### Control objective

Prevent literal or fluent wording from creating a material meaning or relationship shift for the intended audience.

#### Boundary

This Control does not treat one bilingual reviewer or back-check as proof of cultural appropriateness for every audience or use.

#### Guidance in this guide

Defined in this registry and supported by risk, elicitation, and bilingual-review guidance; a complete bicultural/register-review method is not currently provided.

#### Relevant Methods

- **Safe Elicitation Method** — helps surface relevant language, cultural, relationship, or register context held by suitable people.
- **Bilingual Back-Check Method** — checks whether intended meaning, tone, politeness, formality, authority signals, and material qualifications remain aligned across languages or registers.
- **Reviewer Standing Check Method** — checks whether the reviewer has suitable language, cultural, contextual, and professional standing for the review.

---

### 3.11 Operational Review Control

#### Definition

Checks an output against how the relevant task, venue, supplier, event, workflow, system, or team actually operates, including constraints, sequence, dependencies, timing, access, role expectations, workarounds, near misses, and changed assumptions.

#### Control objective

Prevent apparently reasonable output from failing because it does not fit current operational reality.

#### Boundary

This Control does not make informal operational memory automatically current, approved, or safe to preserve; source status and accountable ownership still matter.

#### Guidance in this guide

Defined in this registry and supported by unstated-context and organisational-memory guidance; a complete operational-control framework is not currently provided.

#### Relevant Methods

- **Source Packet Check Method** — checks whether current operational constraints, dependencies, sequence, timing, access, and assumptions are already represented in the task basis.
- **Approved Record Retrieval and Extraction Method** — retrieves current approved operational records and extracts the task-relevant material.
- **Safe Elicitation Method** — helps surface tacit or experience-based operating context from suitable people when it is not adequately recorded.
- **Reviewer Standing Check Method** — checks whether the reviewer has suitable operational knowledge, context, access, competence, and standing.

---

## 4. Methods

The entries below are the reusable Methods currently recognised by this guide.

---

### 4.1 Source Packet Check Method

#### Definition

Checks whether the current task basis contains the approved sources, intended use, audience, exclusions, authority boundaries, review basis, and other task-relevant context needed before prompting or review.

#### Purpose

Improve the quality and boundedness of the task basis before AI generation or human review.

#### Supports

- **Unstated Context Control** — helps reveal whether relevant context is already present or missing from the approved task basis.
- **Authority Review Control** — checks whether authority boundaries, approvals, instructions, or exclusions are present before the authority judgement is made.
- **Materiality Review Control** — checks whether the task basis contains the thresholds, conditions, dependencies, or consequences needed for the materiality judgement.
- **Local Source Checking Control** — checks whether current locally applicable sources are present in the task basis.
- **Verification Control** — helps establish whether the approved sources or records needed for later verification are available; it does not itself verify the claim.

#### Use when

Use when the task depends on documents, records, instructions, policies, prior decisions, or other source material and the completeness or authority of the task basis matters.

#### Boundary

This Method does not establish that every included source is correct, current, locally applicable, or independently verified.

#### Detailed guidance

See [[Source Packet Add-On]].

---

### 4.2 Approved Record Retrieval and Extraction Method

#### Definition

Uses two distinct stages: first **retrieve** a current approved record into the task process; then **extract** only the task-relevant approved material needed for the current task.

#### Purpose

Use existing approved records before asking people to recreate recorded information from memory, while keeping retrieval and extraction conceptually distinct.

#### Supports

- **Unstated Context Control** — fills a task-basis gap when the needed context is already recorded in an approved source.
- **Local Source Checking Control** — obtains current approved records that apply to the actual local setting.
- **Verification Control** — retrieves an approved record that may form part of a sufficiently independent verification basis; retrieval itself is not verification.
- **Authority Review Control** — obtains approved records that may establish authority, delegation, approval status, or decision boundaries.
- **Materiality Review Control** — obtains approved records containing thresholds, conditions, dependencies, or consequences relevant to materiality.
- **Operational Review Control** — obtains current approved operational records that show how the task, process, venue, system, or team actually operates.

#### Use when

Use when a relevant current approved record may already contain part or all of the information needed for the task.

#### Boundary

Retrieval does not mean extraction, and extraction does not mean verification. This Method does not prove that the retrieved material is sufficient, correctly interpreted, current for the intended use, or independently verified.

#### Detailed guidance

See [[Source Packet Add-On]] and [[Unstated Context Control]].

---

### 4.3 Representability Assessment Method

#### Definition

Assesses how clearly, faithfully, and safely relevant context can be expressed for the current task, including whether it is clear, partial, difficult to articulate, unsafe or inappropriate to state, or not fully expressible for AI use.

#### Purpose

Decide whether context can enter the task basis directly, needs safe conversion, should remain human-only, or needs another route.

#### Supports

- **Unstated Context Control** — decides how identified context can enter the task: directly, through safe conversion, through human-only handling, or through another route.

#### Use when

Use when relevant context has been identified or surfaced and the reviewer must decide how it can be represented safely and faithfully.

#### Boundary

Representability is not reliability. A context item may be easy to express but unreliable, or reliable but unsafe or difficult to express.

#### Detailed guidance

See [[Unstated Context Control]] and [[Organisational Context Handling]].

---

### 4.4 Safe Elicitation Method

#### Definition

Uses specific, focused, neutral, task-relevant questions with suitable people to help surface relevant context that is carried implicitly and can be asked about safely and appropriately.

#### Purpose

Surface relevant implicit context without treating questioning as unrestricted information collection.

#### Supports

- **Unstated Context Control** — surfaces relevant context held implicitly by suitable people.
- **Communication Review Control** — surfaces audience, relationship, timing, or other context that may change how wording is understood.
- **Recipient Impact Review Control** — surfaces context about people or relationships that may change the material effect of the output.
- **Authority Review Control** — may surface relevant authority context held by suitable people, but does not itself establish authority.
- **Materiality Review Control** — may surface decision context, thresholds, dependencies, or consequences held by suitable people, but does not itself decide materiality.
- **Bicultural and Register Review Control** — surfaces language, cultural, politeness, formality, relationship, or register context held by suitable people.
- **Anomaly Review Control** — surfaces experience-based knowledge that may explain why something looks unusual or consequential.
- **Operational Review Control** — surfaces tacit or experience-based operating context that is not adequately represented in records.

#### Use when

Use only if a suitable person may carry relevant context implicitly and asking is safe, permitted, proportionate, and within the questioner’s standing.

#### Boundary

Do not use elicitation when the answer should come from an approved source, restricted process, responsible owner, specialist reviewer, or escalation path.

#### Detailed guidance

See [[Elicitation Techniques]] and [[When Questions Are Not Enough]].

---

### 4.5 Safe Conversion Method

#### Definition

Converts only the necessary effect of context into a safe form without exposing underlying context that should not enter AI. The safe form may be a fact or source, a constraint or wording rule, an omission or review instruction, an approval boundary or human-drafting requirement, or an escalation trigger.

#### Purpose

Allow sensitive or unsuitable context to influence the task without unnecessarily disclosing the underlying information to AI.

#### Supports

- **Unstated Context Control** — allows the necessary effect of sensitive or unsuitable context to influence the task without exposing the underlying context to AI.

#### Use when

Use when the underlying context should not be placed into AI but a bounded effect can be represented accurately, safely, and with permission.

#### Boundary

Safe conversion must not distort meaning, hide a material issue, or bypass a required owner, specialist, verification, or escalation process.

#### Detailed guidance

See [[Unstated Context Control]] and [[Organisational Context Handling]].

---

### 4.6 Human-Only Handling Method

#### Definition

Keeps underlying context outside AI and has an appropriate person or approved process use that context to guide drafting, review, approval, timing, or escalation.

#### Purpose

Protect context that should influence the task but should not be exposed to AI or ordinary records.

#### Supports

- **Unstated Context Control** — allows relevant context that should remain outside AI to influence authorised human drafting, review, approval, timing, or escalation.
- **Recipient Impact Review Control** — allows sensitive recipient or relationship context to inform human impact judgement without exposing it to AI.

#### Use when

Use when the context is sensitive, restricted, unsafe for AI, not adequately expressible for AI use, or dependent on human authority or judgement.

#### Boundary

Human-only handling is not concealment and does not remove verification, approval, specialist, or escalation requirements that still apply.

#### Detailed guidance

See [[Unstated Context Control]], [[Organisational Context Handling]], and [[When Questions Are Not Enough]].

---

### 4.7 Approved Basis Comparison Method

#### Definition

Compares a claim, assumption, output, or decision basis with a sufficiently independent approved source, tool, record, or qualified accountable basis appropriate to the issue.

#### Purpose

Provide a concrete comparison step when a Control requires support beyond AI self-review or unsupported judgement.

#### Supports

- **Verification Control** — provides the sufficiently independent comparison step required to verify a material claim, assumption, output, or decision basis.
- **Local Source Checking Control** — compares the matter with an approved local basis rather than a generic, stale, or overseas source.
- **Challenge Handling Control** — tests whether reliable new evidence or an authoritative basis supports changing a justified safeguard or uncertainty.
- **Anomaly Review Control** — compares an unusual signal with the relevant approved source, record, calculation, or other basis.
- **Authority Review Control** — compares a proposed decision, commitment, or authority claim with an approved authority basis.
- **Materiality Review Control** — compares a fact, condition, or consequence with the decision-relevant threshold, account, right, obligation, or other approved basis.

#### Use when

Use when a claim, source, assumption, output, or decision basis needs to be checked against an approved basis with sufficient independence for the matter.

#### Boundary

This Method does not make every approved source independent or authoritative for every question. Independence and suitability must be judged for the matter being checked.

#### Detailed guidance

See [[Unstated Context Control]] and the relevant risk guidance in [[AI Blind Spot Risk Library]].

---

### 4.8 Reviewer Standing Check Method

#### Definition

Checks whether the proposed reviewer has enough role, competence, authority, permission, independence, context, and accountability to perform the required review, approval, elicitation, or escalation safely.

#### Purpose

Prevent a review or approval decision from being assigned to a person who lacks the standing needed for that function.

#### Supports

- **Unstated Context Control** — checks whether the person handling, eliciting, or judging context has suitable role, permission, competence, context, and accountability.
- **Communication Review Control** — checks whether the reviewer is suitably placed to judge how the intended audience may interpret the wording.
- **Recipient Impact Review Control** — checks whether the reviewer is suitably placed to judge material effects on the affected person or group.
- **Authority Review Control** — checks whether the reviewer or approver has the authority and standing required for the authority function.
- **Materiality Review Control** — checks whether the person making the materiality judgement has suitable role, competence, context, authority, and accountability.
- **Local Source Checking Control** — checks whether the reviewer has suitable local competence, access, context, and standing.
- **Verification Control** — checks whether a reviewer used in verification has suitable competence, access, standing, and enough independence for that verification function.
- **Challenge Handling Control** — checks whether the person judging or authorising a reduction in caution has suitable standing to do so.
- **Anomaly Review Control** — checks whether the reviewer has the relevant experience, competence, context, and standing to recognise and judge the anomaly.
- **Bicultural and Register Review Control** — checks whether the reviewer has suitable language, cultural, contextual, and professional standing for the review.
- **Operational Review Control** — checks whether the reviewer has suitable operational knowledge, context, access, competence, and standing.

#### Use when

Use when reviewer, approval, elicitation, verification, or escalation standing is not already clear from the approved workflow.

#### Boundary

Standing for one function does not automatically confer standing for another; reviewer standing does not automatically mean approval standing or specialist competence.

#### Detailed guidance

See [[Templates/Reviewer Standing Check]].

---

### 4.9 Bilingual Back-Check Method

#### Definition

Compares a bilingual or translated output with its source to confirm that intended meaning, conditions, commitments, authority signals, terminology, tone, and material qualifications remain aligned for the intended audience.

#### Purpose

Detect material meaning or register drift across language versions.

#### Supports

- **Bicultural and Register Review Control** — checks whether intended meaning, tone, politeness, formality, authority signals, and social meaning remain aligned across languages or registers.
- **Communication Review Control** — checks whether translation or register shift changes what the intended reader may understand.
- **Recipient Impact Review Control** — checks whether translated or bilingual wording changes pressure, dignity, relationship meaning, or other recipient-facing effects.
- **Authority Review Control** — checks whether commitments, permissions, refusals, approvals, or other authority signals remain aligned across languages.
- **Materiality Review Control** — checks whether material conditions, thresholds, qualifications, or consequences remain present and correctly weighted in translation.

#### Use when

Use when bilingual or translated content carries material meaning, commitments, conditions, authority signals, or audience-sensitive register.

#### Boundary

A back-check does not by itself prove bicultural appropriateness, specialist accuracy, or approval for the intended use.

#### Detailed guidance

See [[Author and Editor Guide]] and the bilingual-review requirements relevant to the task.

---

## 5. Accountable Routes

The entries below are the reusable Accountable Routes currently recognised by this guide.

---

### 5.1 Responsible Owner Route

#### Definition

Routes an issue to the responsible owner who is accountable for ensuring that the matter has an approved handling path and is not left unmanaged.

#### Use when

Use when an issue needs ownership but no more specific owner route clearly resolves the accountability question.

#### Accountability destination

The responsible owner for the task, process, or organisational matter.

#### Function

Ensure that the issue receives an approved handling path and that responsibility is not left ambiguous.

#### Boundary

This Route does not absorb the distinct authority, decision, source, operational, specialist, or approval responsibilities of other owners.

---

### 5.2 Source Owner Route

#### Definition

Routes a source, record, provenance, currency, interpretation, or source-status question to the person or function responsible for the relevant approved source.

#### Use when

Use when the status, provenance, currency, permitted use, or authoritative interpretation of a source needs accountable resolution.

#### Accountability destination

The person or function responsible for the relevant approved source or record.

#### Function

Resolve source-status and source-governance questions within that owner’s standing.

#### Boundary

A Source Owner Route does not automatically provide independent verification or authority to make the underlying business decision.

---

### 5.3 Decision Owner Route

#### Definition

Routes a material decision, threshold, consequence, approval basis, or next-action question to the person or body authorised and accountable for that decision.

#### Use when

Use when the task depends on a decision or threshold that the current reviewer is not authorised to make.

#### Accountability destination

The person or body authorised and accountable for the relevant decision.

#### Function

Make or confirm the decision within the destination’s authority and accountability.

#### Boundary

This Route does not replace source verification, specialist review, or separate authority-owner involvement if those remain necessary.

---

### 5.4 Authority Owner Route

#### Definition

Routes a question about approval, promise, commitment, refusal, delegation, organisational position, or authority boundary to the person or body that holds the relevant authority.

#### Use when

Use when the output may communicate or imply authority that the current drafter or reviewer does not clearly hold.

#### Accountability destination

The person or body that holds or governs the relevant authority.

#### Function

Confirm, limit, delegate, or refuse the relevant authority action within the destination’s standing.

#### Boundary

This Route does not make an AI-generated statement authoritative. It also does not replace a separate decision owner if the decision itself belongs elsewhere.

---

### 5.5 Operational Owner Route

#### Definition

Routes an operational constraint, sequence, dependency, timing, access, setup, workflow, supplier, venue, staffing, or current-practice question to the person or function accountable for how the work actually operates.

#### Use when

Use when practical operating reality is material and the current task basis may not reflect current practice.

#### Accountability destination

The person or function accountable for the relevant operation, workflow, venue, supplier relationship, system, or team process.

#### Function

Confirm current operational reality and the constraints that must shape the task.

#### Boundary

Operational ownership does not automatically make an informal practice approved, safe, current for every use, or suitable for preservation.

---

### 5.6 Accountable Reviewer Route

#### Definition

Routes the output or issue to a reviewer who has sufficient standing and is accountable for the review outcome within that standing.

#### Use when

Use when the current reviewer lacks the standing needed for the required review but the issue does not necessarily require specialist expertise or higher authority.

#### Accountability destination

A reviewer with sufficient standing for the required review function.

#### Function

Provide accountable review within the reviewer’s role, competence, authority, permission, independence, context, and accountability.

#### Boundary

This Route does not confer approval authority or specialist competence beyond the reviewer’s actual standing.

---

### 5.7 Specialist Review Route

#### Definition

Routes a matter to a suitably qualified specialist or approved specialist process when the issue requires knowledge, judgement, permission, independence, or professional responsibility beyond ordinary review.

#### Use when

Use when ordinary review is insufficient because the matter requires specialist competence, professional judgement, restricted handling, or another qualified process.

#### Accountability destination

The suitably qualified specialist or approved specialist process relevant to the matter.

#### Function

Provide the specialist judgement, review, or process required within the specialist’s standing.

#### Boundary

This Route does not guarantee approval or replace the decision or authority owner if a separate organisational decision remains required.

---

### 5.8 Qualified Bilingual and Register Review Route

#### Definition

Routes a bilingual, translation, cultural-register, or meaning-alignment issue to a suitably qualified bilingual or register reviewer with the competence and standing needed for the intended audience and use.

#### Use when

Use when language or register may materially change meaning, tone, commitment, authority, or recipient impact and ordinary language checking is insufficient.

#### Accountability destination

A suitably qualified bilingual or register reviewer for the relevant language, audience, and use.

#### Function

Review meaning and register alignment with the competence and standing required for the intended audience.

#### Boundary

This Route does not automatically provide legal, specialist-domain, authority, or final approval standing.

---

### 5.9 Local or Sector Review Route

#### Definition

Routes a local-applicability question to a suitably qualified local, sector, policy, regulatory, or organisational reviewer when general guidance is insufficient for the actual setting.

#### Use when

Use when local or sector applicability requires judgement beyond current general sources or ordinary review.

#### Accountability destination

A suitably qualified local, sector, policy, regulatory, or organisational reviewer or approved process.

#### Function

Resolve local-applicability or sector-specific interpretation within the destination’s competence and standing.

#### Boundary

This Route does not make a general source current or authoritative and does not replace any separately required decision or authority owner.

---

### 5.10 Escalation Route

#### Definition

Routes the task, context, or issue to the appropriate higher-authority, more qualified, more independent, restricted, or otherwise approved process when the current reviewer cannot safely resolve it within their standing.

#### Use when

Use when the current reviewer cannot responsibly continue, decide, approve, verify, or handle the matter within the available authority, competence, independence, access, safety, or process boundary.

#### Accountability destination

The higher-authority, more qualified, more independent, restricted, or otherwise approved destination appropriate to the issue.

#### Function

Move unresolved responsibility to a destination that can lawfully and responsibly decide or direct the next action.

#### Boundary

Escalation is not evidence that the issue is severe or that a particular outcome is required; it is a routing decision based on the current boundary.

---

## 6. Risk Relationship Entry Structure Standard

The risk relationship map explains **why** a canonical Control, Method, or Accountable Route may be relevant to a risk. It is not a second definition registry: the authoritative definitions remain in Sections 3–5.

Use one numbered H3 relationship entry for each canonical AI Blind Spot risk. Keep the exact risk name from [[AI Blind Spot Risk Library]].

Each relationship entry should help a fresh reader answer:

1. What needs to be controlled?
2. Which Control or Controls address the risk most directly?
3. Which additional Controls matter only in particular conditions?
4. Which Methods may help carry out or support those Controls?
5. Which Accountable Routes may be needed when responsibility, authority, expertise, review, approval, or escalation must move elsewhere?
6. What practical help does this guide currently provide?

Use short risk-specific reasons beside each named item. Explain the **relationship to this risk**, not the canonical definition of the item.

Do not use a flat relationship list that makes every item look equally important. Do not repeat the same relationship list in the Risk Library.

---

### 6.1 Control need

State what must be addressed for the risk to be responsibly controlled.

Describe the need in terms such as context, evidence, verification, judgement, authority, recipient impact, local applicability, professional or operational knowledge, accountability, or another material requirement.

Do not prescribe one universal Control merely to make the map symmetrical.

---

### 6.2 Controls to consider first

Identify the Control or Controls that most directly address the risk mechanism.

For each Control, give a short risk-specific reason. `Consider first` means **most directly relevant**, not automatically required in every task.

If a general risk such as **AI Blind Spot** cannot sensibly have one primary Control before the issue is narrowed, say so explicitly rather than inventing a default.

---

### 6.3 Additional Controls when relevant

List only Controls whose relevance depends on a recognisable condition, and state that condition.

Omit this local field if there is no additional Control beyond the directly related Control or Controls.

---

### 6.4 Methods that may support those Controls

List canonical Methods that may provide a practical way to carry out or support a relevant Control for this risk.

For each Method, state why it may help in this risk context. A Method is not a Control and should not be presented as an equal alternative to Control selection.

---

### 6.5 Accountable Routes that may be needed

List canonical Accountable Routes that may be relevant when the issue needs responsibility, authority, expertise, review, approval, or escalation beyond the current reviewer.

For each Route, state the condition that makes the route useful. Do not imply that every route is required in every case.

---

### 6.6 How this guide currently helps

State what the current version of the **Win.Win AI Blind Spot Guide** actually provides for this risk.

This field describes only the practical guidance currently available in this guide. Do not describe future guidance as though it already exists, and do not imply that this guide itself performs verification, approval, judgement, or accountability.

---

## 7. Risk Relationships

The entries below are the authoritative risk-to-Control/Method/Route relationship map for this guide. They explain **why** each listed item may be relevant. The canonical meaning of each item remains in Sections 3–5.

---

### 7.1 AI Blind Spot

**Control need**

Identify the material human or organisational requirement that AI cannot reliably see, hold, judge, verify, authorise, or be accountable for, then apply safeguards and accountable human involvement that match that requirement.

**Controls to consider first**

No single Control is automatically primary while the concern remains at the general **AI Blind Spot** level. First narrow the unresolved requirement, then use the Control or Controls that match it:

- **Unstated Context Control** — when relevant context may be missing from or inadequately represented in the task basis.
- **Communication Review Control**, **Recipient Impact Review Control**, or **Bicultural and Register Review Control** — when the concern is meaning, recipient impact, language, culture, or register.
- **Authority Review Control**, **Materiality Review Control**, **Local Source Checking Control**, or **Verification Control** — when the concern is authority, what matters, local applicability, or independent checking.
- **Challenge Handling Control**, **Anomaly Review Control**, or **Operational Review Control** — when the concern is unsupported pressure, an unusual signal, or operational reality.

**Methods that may support those Controls**

- **Reviewer Standing Check Method** — helps check whether the current reviewer is suitably placed to judge or route the unresolved issue.

**Accountable Routes that may be needed**

- **Accountable Reviewer Route** — when the issue needs a reviewer with suitable responsibility and standing.
- **Specialist Review Route** — when the unresolved issue depends on specialist expertise.
- **Escalation Route** — when the issue cannot be safely resolved within the current task or reviewer boundary.

**How this guide currently helps**

Helps the reviewer name the Blind Spot, check whether unstated context contributes, assess reviewer standing, and identify any remaining verification, authority, impact, local, specialist, operational, or escalation needs.

---

### 7.2 Unwritten Context Gap

**Control need**

Find and responsibly handle relevant context that is absent from, incomplete in, or not adequately represented in the task basis.

**Controls to consider first**

- **Unstated Context Control** — directly addresses the missing or inadequately represented task-basis context.

**Methods that may support those Controls**

- **Source Packet Check Method** — checks whether the task basis already contains the needed context before further collection.
- **Approved Record Retrieval and Extraction Method** — retrieves current approved records and extracts the task-relevant material when the context is recorded.
- **Representability Assessment Method** — checks whether the relevant context can be expressed clearly and safely enough for AI-supported use.
- **Safe Elicitation Method** — helps surface relevant context held implicitly by suitable people when asking is safe and permitted.
- **Safe Conversion Method** — carries only the necessary safe effect into the AI task when the underlying context should remain outside AI.
- **Human-Only Handling Method** — keeps unsuitable or restricted context within authorised human handling.
- **Reviewer Standing Check Method** — checks whether the person handling or judging the context has suitable standing.

**Accountable Routes that may be needed**

- **Responsible Owner Route** — when the context needs an accountable handling path rather than remaining unmanaged.
- **Source Owner Route** — when source status, provenance, currency, or permitted use needs resolution.
- **Accountable Reviewer Route** — when a suitably placed reviewer must judge how the context affects the output.
- **Specialist Review Route** — when the context requires specialist interpretation.
- **Escalation Route** — when the gap cannot be resolved safely within the current task.

**How this guide currently helps**

Provides the deepest practical guidance in this guide: identifying the gap, locating possible sources, assessing representability, using safe elicitation when suitable, and choosing minimum current-task handling.

---

### 7.3 Reader Interpretation Gap

**Control need**

Check how the intended reader may reasonably interpret meaning, certainty, commitment, tone, timing, relationship signals, and required action.

**Controls to consider first**

- **Communication Review Control** — directly checks whether the intended audience may understand the wording differently from what was intended.

**Additional Controls when relevant**

- **Recipient Impact Review Control** — when a possible interpretation could materially affect a person or group.
- **Bicultural and Register Review Control** — when language, culture, politeness, formality, or register may change meaning or social signal.
- **Unstated Context Control** — when missing audience, relationship, timing, history, or situational context may be causing the interpretation problem.

**Methods that may support those Controls**

- **Safe Elicitation Method** — helps surface relevant audience or relationship context held by suitable people.
- **Bilingual Back-Check Method** — checks whether intended meaning survives across languages or registers.
- **Reviewer Standing Check Method** — checks whether the reviewer is suitably placed to judge the interpretation risk.

**Accountable Routes that may be needed**

- **Responsible Owner Route** — when intended meaning or communication choices need accountable owner judgement.
- **Qualified Bilingual and Register Review Route** — when material language, cultural, or register judgement is needed.
- **Specialist Review Route** — when interpretation depends on specialist subject knowledge.
- **Escalation Route** — when a material interpretation issue cannot be resolved safely at the current level.

**How this guide currently helps**

When unstated context contributes, helps surface audience history, relationship cues, timing sensitivity, preferences, and local meaning that may be absent from the task basis.

---

### 7.4 Recipient Impact Blindness

**Control need**

Assess material effects on real recipients or groups, including dignity, trust, pressure, exclusion, relationships, reputation, practical interests, and timing.

**Controls to consider first**

- **Recipient Impact Review Control** — directly checks how the output may affect real recipients or groups beyond whether they understand the wording correctly.

**Additional Controls when relevant**

- **Communication Review Control** — when the impact depends partly on how the recipient may interpret the wording.
- **Unstated Context Control** — when missing lived, relationship, vulnerability, timing, or situational context may change the impact.

**Methods that may support those Controls**

- **Safe Elicitation Method** — helps surface relevant recipient or situational context from suitable people when safe and permitted.
- **Human-Only Handling Method** — keeps sensitive recipient context outside AI while allowing authorised human judgement to account for it.
- **Reviewer Standing Check Method** — checks whether the reviewer is suitably placed to assess recipient impact.

**Accountable Routes that may be needed**

- **Responsible Owner Route** — when the impact needs accountable owner handling.
- **Accountable Reviewer Route** — when the task needs a reviewer with suitable responsibility and standing.
- **Specialist Review Route** — when the potential impact depends on specialist expertise.
- **Escalation Route** — when a material recipient-impact concern cannot be resolved safely at the current level.

**How this guide currently helps**

When unstated context contributes, helps surface recent events, lived experience, vulnerable points, likely reactions, affected people, and timing concerns that may not be represented in the task basis.

---

### 7.5 Authority Boundary Blindness

**Control need**

Confirm who can approve, promise, decide, refuse, authorise, commit, or speak for the organisation and keep wording within that boundary.

**Controls to consider first**

- **Authority Review Control** — directly checks whether the output stays within the actual authority available.

**Additional Controls when relevant**

- **Materiality Review Control** — when the importance of the commitment, decision, or consequence affects the required authority or review level.
- **Unstated Context Control** — when informal approval practice, delegation, or other authority context may be missing from the task basis.

**Methods that may support those Controls**

- **Approved Record Retrieval and Extraction Method** — retrieves current approved authority, delegation, policy, or decision records when available.
- **Approved Basis Comparison Method** — compares the proposed output or decision with the approved authority basis.
- **Reviewer Standing Check Method** — checks whether the reviewer has the role, competence, access, and authority needed for the review.

**Accountable Routes that may be needed**

- **Authority Owner Route** — when the actual authority boundary or delegation needs accountable resolution.
- **Decision Owner Route** — when the issue depends on a decision reserved to an authorised person or body.
- **Accountable Reviewer Route** — when a suitably placed reviewer must judge the authority issue.
- **Escalation Route** — when the authority boundary cannot be resolved at the current level.

**How this guide currently helps**

Helps surface informal authority practice or missing approval context. It also provides reviewer-standing and escalation support when the current reviewer cannot resolve the issue.

---

### 7.6 Materiality Judgement Gap

**Control need**

Determine which facts, uncertainties, conditions, omissions, dependencies, or consequences are important enough to change a decision or outcome.

**Controls to consider first**

- **Materiality Review Control** — directly checks what matters enough to change the decision, approval, consequence, or next action.

**Additional Controls when relevant**

- **Verification Control** — when materiality depends on whether a fact, assumption, or claim is actually supported.
- **Authority Review Control** — when the material issue changes who is authorised to decide or approve.
- **Unstated Context Control** — when thresholds, dependencies, local priorities, or other decision context may be missing.

**Methods that may support those Controls**

- **Source Packet Check Method** — checks whether the decision basis contains the information needed to judge materiality.
- **Approved Basis Comparison Method** — compares the issue against the explicit threshold, rule, source, or other approved basis that determines what matters.
- **Reviewer Standing Check Method** — checks whether the reviewer is suitably placed to make or route the materiality judgement.

**Accountable Routes that may be needed**

- **Decision Owner Route** — when the relevant threshold, consequence, or decision needs an authorised decision owner.
- **Source Owner Route** — when materiality depends on the status or interpretation of an authoritative source.
- **Specialist Review Route** — when the materiality judgement needs specialist expertise.
- **Escalation Route** — when materiality cannot be safely resolved at the current level.

**How this guide currently helps**

When unstated context contributes, helps surface thresholds, conditions, dependencies, caveats, consequences, and local priorities that may be absent or misweighted in the task basis.

---

### 7.7 Local or jurisdiction-specific blind spot

**Control need**

Establish whether the output is current and applicable to the actual jurisdiction, sector, organisation, authority, policy environment, and local setting.

**Controls to consider first**

- **Local Source Checking Control** — directly checks whether the output is grounded in the current local or sector-specific basis that applies.

**Additional Controls when relevant**

- **Verification Control** — when a local claim or conclusion needs an adequately independent check.
- **Unstated Context Control** — when relevant local practice, authority, source, or situational context is missing from the task basis.

**Methods that may support those Controls**

- **Approved Record Retrieval and Extraction Method** — retrieves current approved local or sector records and extracts the material relevant to the task.
- **Approved Basis Comparison Method** — compares the output against the applicable local or sector basis.
- **Reviewer Standing Check Method** — checks whether the reviewer has the competence, access, and standing needed for local judgement.

**Accountable Routes that may be needed**

- **Source Owner Route** — when the currency, authority, provenance, or interpretation of a local source needs resolution.
- **Local or Sector Review Route** — when the issue needs someone with accountable local or sector knowledge.
- **Specialist Review Route** — when local applicability depends on specialist interpretation.
- **Escalation Route** — when the local applicability question cannot be resolved safely at the current level.

**How this guide currently helps**

Helps identify when local sources or local expertise are missing from the task basis and supports retrieval and extraction of current approved material; it does not replace local verification or qualified interpretation.

---

### 7.8 AI Self-Validation Illusion

**Control need**

Establish an adequately independent basis for checking a claim, source, output, or decision rather than relying on AI confirming itself.

**Controls to consider first**

- **Verification Control** — directly requires checking against a sufficiently independent approved basis rather than treating AI agreement as verification.

**Methods that may support those Controls**

- **Approved Record Retrieval and Extraction Method** — brings the relevant approved source or record into the checking process when appropriate.
- **Approved Basis Comparison Method** — performs the actual comparison against the sufficiently independent approved basis.
- **Reviewer Standing Check Method** — checks whether a reviewer used as part of the verification basis has suitable competence, access, standing, and independence.

**Accountable Routes that may be needed**

- **Source Owner Route** — when the authoritative status or interpretation of the verification source needs resolution.
- **Accountable Reviewer Route** — when verification needs a suitably accountable reviewer with sufficient independence for the function.
- **Specialist Review Route** — when the verification basis requires specialist expertise.
- **Escalation Route** — when an adequately independent verification basis cannot be established at the current level.

**How this guide currently helps**

Reinforces that AI self-review is not independent verification and helps identify which approved source, record, owner, tool, or accountable reviewer may provide a suitable verification basis.

---

### 7.9 User-Pressure Drift

**Control need**

Preserve justified caution until a material challenge is supported by reliable evidence, an authoritative record, or a suitably authorised decision.

**Controls to consider first**

- **Challenge Handling Control** — directly protects justified warnings, uncertainty, or safeguards from being weakened merely because a user pushes back.

**Additional Controls when relevant**

- **Verification Control** — when the challenge depends on whether new evidence actually changes the factual basis.
- **Authority Review Control** — when the challenge depends on whether someone has authority to change the decision or boundary.
- **Materiality Review Control** — when the challenge concerns whether the new information matters enough to change the outcome.

**Methods that may support those Controls**

- **Approved Basis Comparison Method** — compares the challenge against reliable evidence, an authoritative record, or another approved basis.
- **Reviewer Standing Check Method** — checks whether the person resolving the challenge is suitably placed to do so.

**Accountable Routes that may be needed**

- **Source Owner Route** — when the challenge concerns source status or interpretation.
- **Decision Owner Route** — when the challenge needs an authorised decision.
- **Authority Owner Route** — when the issue is whether someone may change the boundary or commitment.
- **Escalation Route** — when pressure continues but the issue cannot be safely resolved within the current boundary.

**How this guide currently helps**

Preserves the existing `{VERIFY}` challenge rule and helps identify who or what should resolve the dispute. Use unstated-context work only when missing context materially contributes.

---

### 7.10 Anomaly Instinct Gap

**Control need**

Detect and investigate unusual or missing information that may signal a material error, mismatch, operational problem, or need for experienced judgement.

**Controls to consider first**

- **Anomaly Review Control** — directly requires unusual or missing signals to be noticed and investigated rather than normalised away.

**Additional Controls when relevant**

- **Verification Control** — when the anomaly may indicate that a claim, figure, source, or output is wrong.
- **Operational Review Control** — when recognising the anomaly depends on how the operation normally works.
- **Unstated Context Control** — when missing context may explain why the pattern looks unusual.

**Methods that may support those Controls**

- **Approved Basis Comparison Method** — compares the unusual item against the relevant approved or expected basis.
- **Safe Elicitation Method** — helps obtain experience-based context from suitable people when the anomaly depends on practical knowledge.
- **Reviewer Standing Check Method** — checks whether the reviewer has the relevant experience and standing to recognise or route the signal.

**Accountable Routes that may be needed**

- **Source Owner Route** — when the anomaly concerns a source, record, or data basis.
- **Operational Owner Route** — when the anomaly concerns actual operational practice or history.
- **Specialist Review Route** — when the anomaly requires specialist interpretation.
- **Escalation Route** — when the anomaly may be material and cannot be resolved safely at the current level.

**How this guide currently helps**

Helps surface expected patterns, previous near misses, local warnings, and source or context gaps that may explain why something looks unusual.

---

### 7.11 Bicultural Register Gap

**Control need**

Preserve intended meaning, tone, politeness, formality, authority, commitment, and recipient impact across language and cultural registers.

**Controls to consider first**

- **Bicultural and Register Review Control** — directly checks whether meaning and social signals survive the language and cultural register actually used.

**Additional Controls when relevant**

- **Communication Review Control** — when the issue is how the audience may understand the wording.
- **Recipient Impact Review Control** — when the language or register may affect dignity, trust, pressure, relationships, or practical interests.
- **Authority Review Control** — when translation or register may accidentally strengthen or weaken an authority, promise, commitment, or refusal signal.
- **Unstated Context Control** — when audience expectations, relationship cues, local norms, or other cultural context are missing from the task basis.

**Methods that may support those Controls**

- **Safe Elicitation Method** — helps surface audience or cultural context held by suitable people when safe and permitted.
- **Bilingual Back-Check Method** — checks whether intended meaning, tone, and authority signals survive across languages or registers.
- **Reviewer Standing Check Method** — checks whether the reviewer has suitable language, cultural, role, and task standing.

**Accountable Routes that may be needed**

- **Qualified Bilingual and Register Review Route** — when the issue needs a reviewer with suitable bilingual and register competence.
- **Specialist Review Route** — when terminology or meaning also depends on specialist expertise.
- **Escalation Route** — when a material language or cultural issue cannot be resolved safely at the current level.

**How this guide currently helps**

When unstated context contributes, helps surface audience expectations, terms to avoid, tone sensitivity, local communication norms, and contextual meaning that literal translation may miss.

---

### 7.12 Local Operational Memory Gap

**Control need**

Check the output against current operational reality, including constraints, sequence, dependencies, timing, access, roles, workarounds, near misses, and changed assumptions.

**Controls to consider first**

- **Operational Review Control** — directly checks whether the output fits how the work currently operates in practice.

**Additional Controls when relevant**

- **Unstated Context Control** — when important operating context is absent from or inadequately represented in the task basis.
- **Anomaly Review Control** — when unusual patterns, exceptions, or past near misses may reveal a hidden operational problem.

**Methods that may support those Controls**

- **Source Packet Check Method** — checks whether current operational material is already present in the task basis.
- **Approved Record Retrieval and Extraction Method** — retrieves current approved operational records and extracts the relevant material.
- **Safe Elicitation Method** — helps surface practical operating context held implicitly by suitable experienced people.
- **Reviewer Standing Check Method** — checks whether the reviewer has the relevant experience and standing to judge operational reality.

**Accountable Routes that may be needed**

- **Operational Owner Route** — when current constraints, sequence, access, setup, workflow, or actual practice needs accountable resolution.
- **Source Owner Route** — when the operational source or record needs provenance, currency, or interpretation resolved.
- **Escalation Route** — when an operational issue cannot be safely resolved within the current task boundary.

**How this guide currently helps**

Helps surface practical memory about how work actually happens, retrieve and extract approved operational material, and preserve safe reusable lessons when appropriate.

---

## 8. Practical Rule

Use the risk relationship entries to identify:

1. **what needs to be controlled**;
2. **which Control or Controls address the risk most directly**;
3. **which additional Controls matter only in particular conditions**;
4. **which Methods may support those Controls**; and
5. **where accountable action may need to go**.

Do not treat every listed item as equally important or automatically required. Select the minimum set justified by the actual risk, task basis, consequence, authority, and reviewer standing.

The Risk Library explains the risk itself. The relationship map on this page explains why recognised safeguards and routes may be relevant. The canonical registry entries in Sections 3–5 remain the authoritative definitions of those Controls, Methods, and Accountable Routes.

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Blind Spot Guide Feedback Form](https://forms.gle/se5ruqaZeytDoFENA)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
