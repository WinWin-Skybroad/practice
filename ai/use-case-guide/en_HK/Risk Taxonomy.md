---
title: Risk Taxonomy
created: 2026-07-01
updated: 2026-09-02
version: "1.0"
status: active
type: reference
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Risk Taxonomy

## 1. Purpose and Scope

Use this file when you need the broader risk categories behind a use-case page, when you are training reviewers, or when you are designing controls across several use cases.

Use-case pages belong to the Practical Layer and are the normal starting point for real AI tasks. This taxonomy belongs to the Reference Layer and explains the risk families behind the task-specific guidance. It does not need to be read before every use-case page.

The concrete scenarios in each use-case page are practical examples of how a risk can appear in everyday organisational work, unless separately documented as real incidents.

This file is the classification map for risks used in the **Win.Win AI Use Case Guide**.

Risk families help reviewers name what kind of risk is present, which category it belongs to, and which mitigation family should be applied before AI output is used.

For practical explanations of reusable human-review risks, use [[Human Review Risk Library]]. For the meaning and definition route of a specific named risk or failure mode used anywhere in this guide, use Section 4, **Named Risk and Failure-Mode Index**.

---

## 2. Entry Structure Standard

Each risk-family entry uses the same structure so readers can compare risk types and select the right prompt, review, mitigation, and escalation controls.

---

### 2.1 Mandatory Sections

#### Definition

Describe the risk family and the kind of failure it covers.

#### Common forms

List exact named risks or failure modes from Section 4 that are typical of this family. Each listed name’s **Typical family** entry in Section 4 must include this risk family.

#### Prompt enhancement usually helps by

Describe the prompt-side controls that may reduce the risk before generation.

#### Human review should focus on

State the real-world checks, sources, competence, context, or authority the reviewer should apply.

#### Other controls may include

List non-prompt controls such as approved tools, source controls, workflow gates, records, professional review, or organisational policy.

#### Escalate when

State when ordinary review is insufficient and the task must pause or move to another accountable person.

---

## 3. Risk Families

### 3.1 Accuracy / Hallucination

#### Definition

The AI output may invent, distort, omit, or overstate facts, figures, dates, names, citations, or conclusions.

#### Common forms

- Unsupported or Misread Statistics.
- Source Hallucination.
- Confidence Without Calibration.
- Invented Examples.
- Unsupported Conclusions.

#### Prompt enhancement usually helps by

- Force source-only drafting, uncertainty flags, verification lists, and placeholders instead of invented details.

#### Human review should focus on

- Compare factual claims against approved sources; verify names, dates, figures, citations, and claims.

#### Other controls may include

- Approved source pack, citation log, fact-check step, version control.

#### Escalate when

- Escalate when a material factual claim, figure, source, attribution, or conclusion cannot be adequately verified and the reviewer does not have the evidence, source access, context, competence, authority, or approved process needed to resolve the uncertainty or confirm the claim. This includes legal, financial, pastoral, theological, public, or other specialist claims where the reviewer lacks the required standing to confirm them.

---

### 3.2 Source Grounding / Evidence

#### Definition

The AI may answer beyond the provided material, use outdated material, mix document versions, or hide unsupported assumptions.

#### Common forms

- Hallucination Beyond Source.
- Document Version Confusion.
- Policy Gap Assumption.
- Circular Validation.

#### Prompt enhancement usually helps by

- Require use of only named source documents, section references, and explicit “not found in source” answers.

#### Human review should focus on

- Check every important answer against the exact source version, section, page, or paragraph.

#### Other controls may include

- Approved document repository, source version naming, source comparison review.

#### Escalate when

- Escalate when the source is unclear, outdated, missing, or conflicts with another approved source and the reviewer cannot resolve the issue through the available approved sources, source access, competence, authority, or approved source-checking process.

---

### 3.3 Context / Nuance / Compression

#### Definition

The AI may compress, simplify, reorder, or frame information in a way that loses nuance, caveats, minority views, or unresolved issues.

#### Common forms

- Compression Error.
- Selective Emphasis.
- Loss of Nuance.
- Context Gap from Prior Meetings.

#### Prompt enhancement usually helps by

- Ask for caveats, unresolved items, minority views, missing context, and assumptions to be listed separately.

#### Human review should focus on

- Check whether key qualifications, exceptions, limitations, and unresolved issues survived the summary.

#### Other controls may include

- Keep original materials available; require attendee/source-owner review for complex summaries.

#### Escalate when

- Escalate when a summary may influence decisions, approvals, funding, HR, legal, or governance action and the reviewer does not have the source access, context, competence, authority, or approved process needed to confirm that material facts, conditions, caveats, and nuance have been preserved.

---

### 3.4 Privacy / Confidentiality / Data Boundary

#### Definition

The task may expose personal, sensitive, confidential, pastoral, theological, HR, financial, or organisational data to an AI tool or to the wrong audience.

#### Common forms

- Sensitive Data in Prompt.
- Confidential Content Exposure.
- Recipient List and Personal Data.
- Data Boundary Crossing.

#### Prompt enhancement usually helps by

- Require data minimisation, anonymisation, no personal data input, and a privacy pre-check before the task proceeds.

#### Human review should focus on

- Check prompt inputs and output recipients before use; remove personal and confidential details.

#### Other controls may include

- PDPO pre-check, approved AI tool, training opt-out, data classification, redaction workflow.

#### Escalate when

- Escalate when personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.

---

### 3.5 Tool / Security / Process Governance

#### Definition

Risk arises from using the wrong AI tool, personal accounts, insecure settings, unapproved workflows, or prompt injection / malicious content.

#### Common forms

- Shadow AI Risk.
- Prompt Injection.
- Tool Misuse.
- Training Enabled.
- Unapproved Workflow.
- Fraud Detection Bypass.

#### Prompt enhancement usually helps by

- Require the user to identify the approved tool, allowed data, source of truth, and tool limits before proceeding.

#### Human review should focus on

- Check account type, settings, workflow approval, source of truth, and whether the tool is allowed for the data.

#### Other controls may include

- Approved tool list, minimum security baseline, access control, vendor review, workflow approval.

#### Escalate when

- Escalate before tool use when confidential data, third-party systems, financial processing, or automation is involved and the reviewer or process does not have the authority, technical competence, context, source access, or approved tool and workflow controls needed to confirm safe use.

---

### 3.6 Authority / Scope / Commitment

#### Definition

The AI may imply authority, make commitments, change boundaries, or present a draft as an approved organisational decision.

#### Common forms

- Authority Boundary Blindness.
- Boundary Softening.
- Undeliverable Commitments.
- Scope Creep.
- Template Scope Creep.

#### Prompt enhancement usually helps by

- State the AI is drafting only; prohibit new commitments, promises, policy decisions, or authoritative language.

#### Human review should focus on

- Check whether the output changes commitments, responsibilities, approvals, tone, or organisational position.

#### Other controls may include

- Approval route, authorised sender review, sign-off record, scope statement.

#### Escalate when

- Escalate when the output could bind the organisation, affect rights or obligations, or appear as official approval and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm and approve that use.

---

### 3.7 Tone / Representation / Cultural Sensitivity

#### Definition

The AI may produce wording that is too formal, casual, insensitive, culturally inappropriate, or misaligned with the organisation’s voice.

#### Common forms

- Tone Drift.
- Informal Channel Tone Mismatch.
- Register Mismatch.
- Cultural Insensitivity.

#### Prompt enhancement usually helps by

- Specify audience, tone, language, red lines, and ask AI to flag wording that may be too strong, weak, or culturally sensitive.

#### Human review should focus on

- Read as the real audience; check tone, inclusiveness, warmth, clarity, and alignment with organisational values.

#### Other controls may include

- Tone examples, approved voice guide, reviewer from target audience or ministry context.

#### Escalate when

- Escalate when wording concerns vulnerable groups, culture, crisis, complaints, or public reputation and the reviewer does not have the context, competence, authority, source access, or approved process needed to judge the wording, likely impact, and appropriate response.

---

### 3.8 Bilingual / Localisation / HK Context

#### Definition

The AI may use the wrong language variety, character set, terminology, register, legal/cultural frame, or HK-specific context.

#### Common forms

- Character Set Mixing.
- Mainland China Default.
- English-Chinese Terminology Mismatch.
- Translation Variant Confusion.

#### Prompt enhancement usually helps by

- Require Hong Kong context, Traditional Chinese, terminology flags, no Simplified Chinese, and ambiguous-term review notes.

#### Human review should focus on

- Check TC/EN accuracy, HK terminology, Cantonese/HK context, names, proper nouns, and register.

#### Other controls may include

- Terminology glossary, TC reviewer, official HK source verification, bilingual review.

#### Escalate when

- Escalate legal, medical, financial, technical, or public translation when the reviewer does not have the language and subject-matter competence, authority, context, source access, or approved process needed to confirm the specialist meaning.

---

### 3.9 Legal / Regulatory / Compliance

#### Definition

The AI may give legal or compliance-sounding output without authority, current law, HK jurisdiction grounding, or professional review.

#### Common forms

- AI Legal or Regulatory Advice Substitution.
- Jurisdiction and Scope Error.
- Regulatory Currency Gap.
- Compliance Gap.

#### Prompt enhancement usually helps by

- Prohibit legal advice and compliance assurance; require official HK source names, uncertainty flags, and professional review notes.

#### Human review should focus on

- Verify against official HK sources and qualified professionals; check jurisdiction, currency, and legal effect.

#### Other controls may include

- Solicitor/compliance review, official source check, policy owner sign-off.

#### Escalate when

- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights or obligation issues when the reviewer does not have the authority, competence, current official-source access, context, or approved process needed to confirm the matter.

---

### 3.10 Professional / HR / Finance Boundary

#### Definition

The AI may produce content that crosses into HR, finance, professional, employment, medical, or duty-of-care judgement.

#### Common forms

- Implied Employment or Contractual Terms.
- Discriminatory Language.
- Salary Benchmark Fabrication.
- Parsing and OCR Error.

#### Prompt enhancement usually helps by

- Require the AI to avoid professional advice, use placeholders for uncertain figures, and flag content for qualified review.

#### Human review should focus on

- Check HR, finance, employment, safeguarding, duty-of-care, and professional judgement areas.

#### Other controls may include

- HR/finance/professional reviewer, approved templates, dual control, policy owner sign-off.

#### Escalate when

- Escalate when output may affect employment, pay, invoices, benefits, safeguarding, medical, pastoral or theological matters, finance, or professional obligations and the reviewer does not have the authority, competence or qualification, context, source access, or approved process needed to confirm the matter.

---

### 3.11 AI Blind Spot / Context Risks

#### Definition

This category covers risks where AI may produce fluent, structured, and plausible output without the human grounding needed to know whether the output fits the real situation. These risks are cross-cutting: they can affect prompting before generation and human review before use.

AI Blind Spot risks are broader than unstated information. Some blind spots arise because context was not stated. Others remain even when context has been described, because described context is not the same as lived context, and described professional instinct is not the same as actual professional judgement.

For deeper Blind Spot recognition and control selection, use **Win.Win AI Blind Spot Guide**. The current detailed focus of the **Win.Win AI Blind Spot Guide** is identifying and eliciting unstated context; related guidance covers current-task source location, safe handling, verification, review, stopping, and escalation.

Its detailed unstated-context focus is especially important for **Unwritten Context Gap** and may also support **Reader Interpretation Gap**, **Recipient Impact Blindness**, **Authority Boundary Blindness**, **Materiality Judgement Gap**, **Anomaly Instinct Gap**, **Bicultural Register Gap**, and **Local Operational Memory Gap**. Other Blind Spot risks may still require independent verification, authority-owner sign-off, decision-owner review, source-owner checking, local source checking, escalation, or challenge-handling discipline.

#### Common forms

- **AI Blind Spot:** AI produces the outward form of good judgement — clear structure, balanced language, plausible reasoning, and confident wording — while being blind to lived context, tacit knowledge, relationship memory, accountability, professional instinct, authority, verification limits, or consequences that a human reviewer may need to judge safely.
- **Unwritten Context Gap:** The real constraint lives in local practice, organisational history, relationship context, current sensitivity, or informal precedent that the AI was not told.
- **Local Exception Blindness:** AI applies the written general rule while missing an exception or handling practice known locally.
- **Reader Interpretation Gap:** AI does not reliably know how a real reader may interpret wording, tone, implied authority, implied commitment, or action required.
- **Recipient Impact Blindness:** AI writes what sounds clear or polite without knowing how the actual recipient group may be affected emotionally, relationally, reputationally, or practically.
- **Authority Boundary Blindness:** AI phrases a draft as if approval, commitment, policy, or responsibility already exists.
- **Materiality Judgement Gap:** AI includes or omits details without knowing which caveat, figure, exception, or condition changes the decision.
- **User-Pressure Drift:** AI changes a correct or cautious answer after a user confidently challenges it, without new reliable evidence.
- **AI Self-Validation Illusion:** AI appears to verify AI output, but no independent source, record, tool, or responsible person has confirmed it.

#### Prompt enhancement usually helps by

- Providing the context a human professional would normally know or ask for: audience, purpose, constraints, source documents, local practice, authority limits, known exceptions, intended use, and decision context.
- Asking the AI to surface likely assumptions, task-type missing-information categories, decision dependencies, authority limits, uncertainty, and items that may require human confirmation. This is a gap-surfacing aid, not proof that the AI has found everything it does not know.

#### Human review should focus on

- Checking what the AI was not told: organisational history, informal practice, past incidents, current sensitivities, audience expectations, local constraints, authority to approve, and consequences if the output is wrong.
- Checking what the AI cannot truly hold even when it has been described: lived context, professional instinct, accountability, hesitation, and consequence-awareness.
- Checking whether the AI turned a decision, approval, or risk issue into a simple drafting task, or presented a draft as an authorised decision.

#### Other controls may include

- Named responsible reviewer, source owner review, decision owner sign-off, assumption checklist, escalation triggers, and reviewer decision record.

#### Escalate when

- Escalate when the reviewer lacks the evidence, source access, context, authority, domain competence, or approved process needed to confirm the output or safely resolve an identified blind spot. Where the output touches legal, financial, HR, privacy, regulatory, pastoral, theological, safeguarding, or other specialist matters, escalate when those reviewer requirements are not met or when the approved process requires accountable or specialist review.

---

### 3.12 Operational Feasibility / Workflow

#### Definition

The AI may produce a plan, checklist, schedule, or process that is plausible on paper but infeasible or unsafe in the real organisation.

#### Common forms

- Logistically Impossible Timelines.
- Generic Checklist Without Organisational Context.
- Error Propagation at Scale.
- No Correction Trail.

#### Prompt enhancement usually helps by

- Require constraints, assumptions, dependencies, feasibility checks, and a list of decisions still requiring owner confirmation.

#### Human review should focus on

- Check against real capacity, dates, owners, venues, dependencies, correction route, and implementation risk.

#### Other controls may include

- Owner sign-off, pilot use, correction channel, operational checklist, version control.

#### Escalate when

- Escalate when the plan affects public events, logistics, safety, finance, external parties, or many recipients and the responsible reviewer or owner does not have the operational evidence, context, competence, authority, or approved process needed to confirm feasibility and consequences. Pause or reduce the output scope when volume exceeds real review capacity or no named reviewer can complete the required review before use. Escalate if adequate review capacity or a suitable named reviewer cannot be established within the approved process.

---

## 4. Named Risk and Failure-Mode Index

Use this index when a risk or failure-mode name appears under **Common forms**, on a use-case page, in a prompt-enhancement `Risk` cell, or under **What this helps with** in [[Prompt Enhancement Patterns]]. It gives readers one place to find the meaning and the detailed definition route.

The three naming levels are:

- **Risk family** — the broad category in Section 3 of this taxonomy.
- **Reusable human-review risk** — a canonical risk defined in [[Human Review Risk Library]].
- **Task-specific risk or failure mode** — a narrower manifestation defined on a use-case page, or another materially distinct named failure mode defined in this index where no separate use-case definition is needed.

The short meaning below is an orientation definition, not a second competing master definition. Where the **Detailed definition / route** links to the Human Review Risk Library or a use-case page, that linked definition controls if more detail or task-specific wording is needed. A task-specific use-case page may classify the same underlying risk under the family most relevant to that task.

Every name used under **Common forms** must match an exact name in this index, and the entry’s **Typical family** must include the Section 3 family where that common form appears. The same defined risk may list more than one typical family when it genuinely spans those families. Do not merge, confuse, or substitute a materially different risk merely to force alignment.

Do not introduce a new risk or failure-mode label in **Common forms**, a prompt table, or **What this helps with** merely for stylistic variety or shorthand. Reuse an existing defined name when the meaning is the same. Add a new name only when it represents a materially distinct failure mode and give it an approved definition and traceability route here.

| Named risk or failure mode | Type | Short meaning | Typical family | Detailed definition / route |
|---|---|---|---|---|
| Accountability Gap | Task-specific risk or manifestation | AI may summarise regulatory material confidently, but it has no professional licence, duty, reputation, or liability attached to the advice. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Verify HK Regulatory Questions#9. Other Risks To Watch\|Verify HK Regulatory Questions]] |
| AI Blind Spot | Reusable human-review risk | AI can produce the outward form of good judgement — fluent language, balanced options, structured reasoning, and confident conclusions — while being blind to lived context, tacit knowledge, relationship memory, accountability, professional instinct, authority, verification limits, or consequences that a human reviewer may need to judge safely. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.13 AI Blind Spot\|Human Review Risk Library]] |
| AI Legal Interpretation Risk | Task-specific risk or manifestation | AI interprets policy text as it reads, not as it was intended. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Answer Policy Questions#8. Main Risks\|Answer Policy Questions]] |
| AI Legal or Regulatory Advice Substitution | Task-specific risk or manifestation | A regulatory answer may depend on current legislation, official guidance, FAQs, licensing or registration conditions, dates, entity type, and the exact facts of the proposed activity. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Verify HK Regulatory Questions#8. Main Risks\|Verify HK Regulatory Questions]] |
| AI Self-Validation Illusion | Reusable human-review risk | An AI-generated answer appears verified because AI reviewed it again, even though no independent source, record, tool, or responsible person reviewer confirmed it. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.24 AI Self-Validation Illusion\|Human Review Risk Library]] |
| Anomaly Instinct Gap | Reusable human-review risk | AI may fail to notice unusual information, inconsistent patterns, practical warning signs, or important information that is missing. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.19 Anomaly Instinct Gap\|Human Review Risk Library]] |
| Approval Without Authority | Reusable human-review risk | A reviewer reads the output carefully but lacks authority to approve what the output says, implies, or commits. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Human Review Risk Library#4.12 Approval Without Authority\|Human Review Risk Library]] |
| Authority Boundary Blindness | Reusable human-review risk | AI may write as if a decision, approval, promise, refusal, commitment, or official interpretation has already been authorised. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]]; [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.17 Authority Boundary Blindness\|Human Review Risk Library]] |
| Authority Signal Misread | Task-specific risk or manifestation | AI may not understand how staff interpret hierarchy, tone, timing, and implied instruction. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Draft Internal Memos#9. Other Risks To Watch\|Draft Internal Memos]] |
| Automation Complacency | Reusable human-review risk | Human review effort reduces over time because the AI appears reliable. | [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | [[Human Review Risk Library#4.4 Automation Complacency\|Human Review Risk Library]] |
| Bicultural Register Gap | Reusable human-review risk | AI may produce bilingual or cross-cultural wording that is accurate in literal meaning but inappropriate in tone, language register, formality, politeness, implication, level of authority, or social signal for the actual audience and setting. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.20 Bicultural Register Gap\|Human Review Risk Library]] |
| Boundary Softening | Task-specific risk or manifestation | AI may imply a commitment or soften a stated boundary that was not explicitly intended in the original notes. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Draft Communications#9. Other Risks To Watch\|Draft Communications]] |
| Character Set Mixing | Task-specific risk or manifestation | AI may insert Simplified Chinese characters into a Traditional Chinese document. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Produce Bilingual Versions#9. Other Risks To Watch\|Produce Bilingual Versions]]; [[Use Cases/Translate General Communications#9. Other Risks To Watch\|Translate General Communications]] |
| Circular Validation | Task-specific risk or manifestation | Using AI to check AI output can create a closed loop when both outputs rely on the same unsupported basis. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]]; [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Check AI Output Reliability#8. Main Risks\|Check AI Output Reliability]] |
| Compliance Gap | Task-specific risk or manifestation | Grant compliance requirements are funder-specific and change with each funding cycle. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Draft Grant Applications#9. Other Risks To Watch\|Draft Grant Applications]] |
| Compounding AI Error | Task-specific risk or manifestation | If the document being summarised was itself AI-generated and contains hallucinations or errors, AI summarisation inherits and may amplify those errors. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Summarise Documents#9. Other Risks To Watch\|Summarise Documents]] |
| Compression Error | Task-specific risk or manifestation | Summarisation removes detail by design. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Use Cases/Summarise Documents#8. Main Risks\|Summarise Documents]] |
| Confidence Without Calibration | Task-specific risk or manifestation | AI expresses certainty about genuinely contested or uncertain factual claims. | [[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity\|Tone / Representation / Cultural Sensitivity]]; [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Use Cases/Research General Topics#9. Other Risks To Watch\|Research General Topics]] |
| Confidential Content Exposure | Task-specific risk or manifestation | Internal does not mean low-sensitivity. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft Internal Memos#9. Other Risks To Watch\|Draft Internal Memos]] |
| Confidential Content Widened | Task-specific risk or manifestation | Board papers and committee papers are typically restricted distribution. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Summarise Documents#9. Other Risks To Watch\|Summarise Documents]] |
| Confused Attribution | Task-specific risk or manifestation | AI may swap names or attach an action item to the wrong person, especially if names are similar or the discussion was fast-paced. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Summarise Meeting Notes#9. Other Risks To Watch\|Summarise Meeting Notes]] |
| Context Gap | Task-specific risk or manifestation | AI has no knowledge of internal organisational history, prior decisions, or interpersonal dynamics. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Use Cases/Draft Internal Memos#9. Other Risks To Watch\|Draft Internal Memos]] |
| Context Gap from Prior Meetings | Task-specific risk or manifestation | AI only knows what was in the current prompt. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Use Cases/Summarise Meeting Notes#9. Other Risks To Watch\|Summarise Meeting Notes]] |
| Cultural Framing Loss | Task-specific risk or manifestation | Idiomatic English expressions, metaphors, or cultural references require cultural adaptation in Chinese, not literal translation. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Produce Bilingual Versions#9. Other Risks To Watch\|Produce Bilingual Versions]] |
| Cultural Insensitivity | Named failure mode | AI wording may ignore cultural norms, identities, sensitivities, or audience expectations and cause avoidable offence, exclusion, or relational harm. | [[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity\|Tone / Representation / Cultural Sensitivity]] | Defined in this index; see the linked risk family. |
| Currency of Policy | Task-specific risk or manifestation | An AI answer must not be relied on to confirm whether the policy being queried is the current version in force. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Answer Policy Questions#9. Other Risks To Watch\|Answer Policy Questions]] |
| Data Boundary Crossing | Task-specific risk or manifestation | A single meeting often contains public updates, internal operational matters, and sensitive pastoral/theological or HR items in the same notes. | Pastoral / Theological / Scripture; [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Summarise Meeting Notes#9. Other Risks To Watch\|Summarise Meeting Notes]] |
| Deliberate Ambiguity Loss | Task-specific risk or manifestation | AI may turn intentionally cautious, provisional, or politically negotiated wording into a cleaner summary that loses the ambiguity the source deliberately preserved. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Use Cases/Summarise Documents#9. Other Risks To Watch\|Summarise Documents]] |
| Discriminatory Language | Named failure mode | AI wording may introduce or reproduce biased, discriminatory, exclusionary, or inappropriate language in employment, professional, service, or organisational contexts. | [[Risk Taxonomy#3.10 Professional / HR / Finance Boundary\|Professional / HR / Finance Boundary]] | Defined in this index; see the linked risk family. |
| Distribution Scope Error | Task-specific risk or manifestation | AI should not be assumed to know the appropriate recipients unless current organisational roles, distribution rules, or relevant context are supplied. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft Internal Memos#9. Other Risks To Watch\|Draft Internal Memos]] |
| Document Version Confusion | Task-specific risk or manifestation | An AI system must not be relied on to distinguish current from outdated policy documents unless it is explicitly constrained to approved current sources. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Answer Internal FAQs#9. Other Risks To Watch\|Answer Internal FAQs]] |
| Earlier Context Silently Lost | Reusable human-review risk | A user gave important context earlier in a long AI conversation, but it is no longer reliably active in later output. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Human Review Risk Library#4.9 Earlier Context Silently Lost\|Human Review Risk Library]] |
| Enforcement Ambiguity | Task-specific risk or manifestation | AI-drafted disciplinary, grievance, or escalation clauses may use ambiguous language that creates disputes about meaning when applied. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Draft Organisational Policies#9. Other Risks To Watch\|Draft Organisational Policies]] |
| English-Chinese Terminology Mismatch | Task-specific risk or manifestation | Official HK terminology in English and Traditional Chinese differs from both UK English equivalents and Mainland Chinese equivalents. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Research HK Topics#9. Other Risks To Watch\|Research HK Topics]] |
| Error Propagation at Scale | Task-specific risk or manifestation | Broadcast channels can reach many recipients quickly. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]]; [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | [[Use Cases/Draft WhatsApp Broadcasts#9. Other Risks To Watch\|Draft WhatsApp Broadcasts]] |
| External Processing and Transfer Blind Spot | Task-specific risk or manifestation | A cloud or AI service may involve processing, storage, support access, subprocessors, or transfers outside the organisation or Hong Kong. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Assess Personal Data Tasks#9. Other Risks To Watch\|Assess Personal Data Tasks]] |
| False Completeness | Task-specific risk or manifestation | AI may produce a well-rounded overview that feels complete while missing decisive sources, recent evidence, minority positions, or the one assumption that changes the conclusion. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Research General Topics#9. Other Risks To Watch\|Research General Topics]] |
| False Confidence Tone | Task-specific risk or manifestation | Reports and proposals drafted by AI tend to present uncertain information with confident language. | [[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity\|Tone / Representation / Cultural Sensitivity]] | [[Use Cases/Draft Reports And Presentations#9. Other Risks To Watch\|Draft Reports And Presentations]] |
| False Consensus | Task-specific risk or manifestation | AI may present one perspective or interpretation as if it were universally agreed, when the topic is in fact genuinely contested. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Research General Topics#9. Other Risks To Watch\|Research General Topics]] |
| False Legal Authority | Task-specific risk or manifestation | Organisational policies carry institutional authority once adopted. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Draft Organisational Policies#8. Main Risks\|Draft Organisational Policies]] |
| False Privacy Clearance | Task-specific risk or manifestation | Whether a personal-data task may proceed depends on the actual data, original collection purpose, proposed use, notices or consent records, people affected, tool and processing arrangements, current policy, and applicable official guidance. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Assess Personal Data Tasks#8. Main Risks\|Assess Personal Data Tasks]] |
| False Reassurance | Task-specific risk or manifestation | AI may rate its own output — or another model’s output — as reliable when it is not. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Check AI Output Reliability#9. Other Risks To Watch\|Check AI Output Reliability]] |
| Field Mapping Error | Task-specific risk or manifestation | AI may assign extracted data to the wrong category — for example, attributing a subtotal to a different line item, or mapping a supplier code to a product code field. | [[Risk Taxonomy#3.10 Professional / HR / Finance Boundary\|Professional / HR / Finance Boundary]] | [[Use Cases/Extract Invoice Or Document Data#9. Other Risks To Watch\|Extract Invoice Or Document Data]] |
| Fluency Illusion | Reusable human-review risk | AI output reads clearly, naturally, confidently, or professionally, causing users or reviewers to assume that its content is accurate, complete, supported, suitable, or ready to use. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]]; [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Human Review Risk Library#4.11 Fluency Illusion\|Human Review Risk Library]] |
| Format Inconsistency | Task-specific risk or manifestation | AI does not reliably replicate the exact format of previous newsletters. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Use Cases/Draft Communications#9. Other Risks To Watch\|Draft Communications]] |
| Formatting Loss During Translation | Task-specific risk or manifestation | Translation models prioritise semantic accuracy over structural preservation. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Translate General Communications#9. Other Risks To Watch\|Translate General Communications]] |
| Fraud Detection Bypass | Task-specific risk or manifestation | AI extraction should not be relied on to establish whether an invoice or document is authentic. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]] | [[Use Cases/Extract Invoice Or Document Data#9. Other Risks To Watch\|Extract Invoice Or Document Data]] |
| Funder Relationship and Unrealistic Ask Gap | Task-specific risk or manifestation | AI may write persuasive content while missing funder history, informal feedback, current priorities, or whether the proposed timeline and budget feel realistic to people who must deliver the project. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Use Cases/Draft Grant Applications#9. Other Risks To Watch\|Draft Grant Applications]] |
| Funder Rule Fabrication | Task-specific risk or manifestation | A grant application must follow the specific current funder materials supplied for that opportunity, not general grant-writing conventions. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Draft Grant Applications#8. Main Risks\|Draft Grant Applications]] |
| Generic Checklist Without Organisational Context | Task-specific risk or manifestation | AI generates checklists from general event management knowledge. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]]; [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | [[Use Cases/Draft Event Planning Checklists#8. Main Risks\|Draft Event Planning Checklists]] |
| Hallucination Beyond Source | Task-specific risk or manifestation | AI may answer confidently from general model knowledge when the approved source does not contain a direct answer for the specific situation. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Answer Internal FAQs#8. Main Risks\|Answer Internal FAQs]] |
| HK Coverage and Currency Gap | Task-specific risk or manifestation | HK-specific policy, institutional, legal, and regulatory material may be documented across English and Chinese official sources and may change over time. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Research HK Topics#8. Main Risks\|Research HK Topics]] |
| Impact Claim Inflation | Task-specific risk or manifestation | AI may generate stronger impact claims than the evidence supports by extrapolating from limited data, rounding figures, or presenting planned outcomes as achieved results. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Draft Grant Applications#9. Other Risks To Watch\|Draft Grant Applications]] |
| Implied Employment or Contractual Terms | Task-specific risk or manifestation | A detailed volunteer role may create ambiguity about status, minimum commitments, supervision, payment, benefits, authority, performance expectations, or exit rights. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]]; [[Risk Taxonomy#3.10 Professional / HR / Finance Boundary\|Professional / HR / Finance Boundary]] | [[Use Cases/Draft Volunteer Roles#8. Main Risks\|Draft Volunteer Roles]] |
| Informal Channel Tone Mismatch | Task-specific risk or manifestation | Messaging platforms carry informal expectations. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]]; [[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity\|Tone / Representation / Cultural Sensitivity]] | [[Use Cases/Draft WhatsApp Broadcasts#9. Other Risks To Watch\|Draft WhatsApp Broadcasts]] |
| Informal Practice Collision | Task-specific risk or manifestation | AI may draft a clean policy that conflicts with how the organisation actually works, including unwritten exceptions, resource limits, past incidents, or informal practices that were never included in the prompt. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Draft Organisational Policies#9. Other Risks To Watch\|Draft Organisational Policies]] |
| Insider’s Blind Spot | Reusable human-review risk | The person reviewing an AI summary was in the meeting or situation, so their memory fills in what AI omitted or overstated. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Human Review Risk Library#4.2 Insider’s Blind Spot\|Human Review Risk Library]] |
| Instruction Drift | Reusable human-review risk | AI acknowledges an instruction but later output gradually moves away from it during revisions. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Human Review Risk Library#4.10 Instruction Drift\|Human Review Risk Library]] |
| Intellectual Property and Attribution Risk | Task-specific risk or manifestation | AI may produce wording, structure, images, or ideas that closely resemble source material without reliable attribution or permission information. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft Reports And Presentations#9. Other Risks To Watch\|Draft Reports And Presentations]] |
| Invented Examples | Named failure mode | AI presents fabricated people, events, cases, scenarios, or examples as if they were factual or source-supported. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | Defined in this index; see the linked risk family. |
| Jurisdiction and Scope Error | Task-specific risk or manifestation | AI may combine rules from different jurisdictions, apply a general rule to the wrong entity or activity, or overlook a fact-specific exception, approval route, or regulator position. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Verify HK Regulatory Questions#9. Other Risks To Watch\|Verify HK Regulatory Questions]] |
| Jurisdiction Default Error | Task-specific risk or manifestation | For HK-specific policies, AI may default to non-HK precedent, UK common law, or Mainland Chinese regulatory interpretation when the policy is silent or ambiguous. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Answer Policy Questions#9. Other Risks To Watch\|Answer Policy Questions]] |
| Jurisdiction Mismatch | Task-specific risk or manifestation | Simplified Chinese output may introduce Mainland Chinese terminology, legal assumptions, or institutional references, especially when Hong Kong jurisdiction is not explicit. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Translate General Communications#9. Other Risks To Watch\|Translate General Communications]] |
| Knowledge Cutoff Blindness | Task-specific risk or manifestation | AI may present older information as if it were current, especially when current sources are not supplied, retrieved, or checked. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Research General Topics#9. Other Risks To Watch\|Research General Topics]] |
| Knowledge Gap | Reusable human-review risk | The reviewer is careful but lacks the domain knowledge needed to see the error. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Human Review Risk Library#4.5 Knowledge Gap\|Human Review Risk Library]] |
| Legal Clause Error | Task-specific risk or manifestation | Standard letters touching on contractual, liability, or regulatory matters may contain errors that create legal exposure. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Draft Admin Templates#9. Other Risks To Watch\|Draft Admin Templates]] |
| Local Exception Blindness | Task-specific risk or manifestation | AI may answer from the approved FAQ while missing an unwritten exception, informal practice, or local handling rule that staff know but the document does not state. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Answer Internal FAQs#9. Other Risks To Watch\|Answer Internal FAQs]] |
| Local Institutional Context Gap | Task-specific risk or manifestation | AI may know general concepts but miss HK-specific institutional practice, bilingual official terminology, current government guidance, or sector-specific interpretation. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Research HK Topics#9. Other Risks To Watch\|Research HK Topics]] |
| Local Operational Memory Gap | Reusable human-review risk | AI may miss practical knowledge about how a task, process, venue, supplier, event, system, or team normally operates because that knowledge is held in people’s experience rather than fully recorded. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.21 Local Operational Memory Gap\|Human Review Risk Library]] |
| Local or jurisdiction-specific blind spot | Reusable human-review risk | AI may give a confident general answer that is wrong for Hong Kong, the sector, the organisation, or the local setting. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot\|Human Review Risk Library]] |
| Logistically Impossible Timelines | Task-specific risk or manifestation | AI may generate schedules that appear reasonable in structure but are logistically impossible — insufficient setup time, back-to-back sessions with no transition, or incorrect assumptions about venue access hours. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]]; [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | [[Use Cases/Draft Event Planning Checklists#9. Other Risks To Watch\|Draft Event Planning Checklists]] |
| Long-Tail Template Propagation Risk | Task-specific risk or manifestation | AI can produce a reusable template quickly, but it does not feel the future consequence of one flawed clause, missing field, or wrong instruction being reused for months. | [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | [[Use Cases/Draft Admin Templates#9. Other Risks To Watch\|Draft Admin Templates]] |
| Loss of Nuance | Task-specific risk or manifestation | Hedging language, conditional approvals, and provisional decisions in source documents are smoothed out in AI summaries. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]]; [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Use Cases/Summarise Documents#9. Other Risks To Watch\|Summarise Documents]] |
| Low-Risk Assumption Trap | Reusable human-review risk | A familiar task feels low-risk, so reviewers check quickly and miss the specific facts or commitments that can cause harm. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Human Review Risk Library#4.1 Low-Risk Assumption Trap\|Human Review Risk Library]] |
| Mainland China Default | Task-specific risk or manifestation | Regulatory, legal, and cultural content may introduce PRC terminology, assumptions, or institutional references, especially when the query is in Simplified Chinese or when Hong Kong context is not explicit. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]]; [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Research HK Topics#9. Other Risks To Watch\|Research HK Topics]] |
| Materiality Judgement Gap | Reusable human-review risk | AI may misjudge the importance of particular information, conditions, caveats, differences, or uncertainties. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.18 Materiality Judgement Gap\|Human Review Risk Library]] |
| Metacognitive Overconfidence | Task-specific risk or manifestation | AI may not reliably indicate when its Hong Kong-specific coverage is incomplete or outdated. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Check Confidence Before Research#8. Main Risks\|Check Confidence Before Research]] |
| Missing Context It Cannot Feel | Reusable human-review risk | AI gives a complete-looking answer without knowing that important organisational or local context is missing. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Human Review Risk Library#4.8 Missing Context It Cannot Feel\|Human Review Risk Library]] |
| Missing Organisational Context | Task-specific risk or manifestation | AI should not be assumed to know internal priorities, budget constraints, political dynamics, or relationship history unless that context is supplied through approved sources. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Use Cases/Draft Reports And Presentations#9. Other Risks To Watch\|Draft Reports And Presentations]] |
| Missing Protection and Duty Elements | Task-specific risk or manifestation | AI may omit safeguarding, health and safety, supervision, confidentiality, insurance, complaints, or other protections required by the organisation’s actual role, current policy, contracts, or applicable requirements. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Draft Volunteer Roles#9. Other Risks To Watch\|Draft Volunteer Roles]] |
| Missing Required Provisions | Task-specific risk or manifestation | A policy may omit provisions required by current applicable law, regulation, contracts, funder or insurer conditions, sector guidance, or the organisation’s own approved controls. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft Organisational Policies#9. Other Risks To Watch\|Draft Organisational Policies]] |
| Model Substitution During Multi-Model Review | Task-specific risk or manifestation | When multiple source documents are given to a reviewing model simultaneously, the model may choose its own authoritative source rather than the one specified, producing correct formatting but incorrect terminology. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Translate General Communications#9. Other Risks To Watch\|Translate General Communications]] |
| No Correction Trail | Named failure mode | The workflow provides no reliable way to identify, communicate, propagate, or record a correction after an error is found. | [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | Defined in this index; see the linked risk family. |
| No Felt Weight of Real Harm | Task-specific risk or manifestation | AI can classify data and purpose, but it does not feel the personal, relational, reputational, or dignity harm that misuse of someone’s data may cause. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Assess Personal Data Tasks#9. Other Risks To Watch\|Assess Personal Data Tasks]] |
| Omission of Current HK Requirements | Task-specific risk or manifestation | AI may omit current Hong Kong requirements that depend on the venue, event type, food, safety, accessibility, insurance, permissions, or other local conditions. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Draft Event Planning Checklists#9. Other Risks To Watch\|Draft Event Planning Checklists]] |
| Outdated HK Policy and Legislation | Task-specific risk or manifestation | HK ordinances and policies change with some frequency. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Research HK Topics#9. Other Risks To Watch\|Research HK Topics]] |
| Outdated Legislative Reference | Task-specific risk or manifestation | AI may reference superseded legislation, renamed regulatory bodies, or outdated policy versions. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft Admin Templates#9. Other Risks To Watch\|Draft Admin Templates]] |
| Overconfident Answer to Uncertain Question | Task-specific risk or manifestation | AI may give a definitive answer to a question the policy document does not actually settle. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Answer Internal FAQs#9. Other Risks To Watch\|Answer Internal FAQs]] |
| Parsing and OCR Error | Task-specific risk or manifestation | AI may misread visible text, numbers, dates, totals, invoice numbers, account details, or field labels. | [[Risk Taxonomy#3.10 Professional / HR / Finance Boundary\|Professional / HR / Finance Boundary]] | [[Use Cases/Extract Invoice Or Document Data#8. Main Risks\|Extract Invoice Or Document Data]] |
| PDPO Misinterpretation | Task-specific risk or manifestation | AI may apply an incomplete or outdated privacy framework, overlook the actual collection and use context, or present issue-spotting as legal clearance. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Assess Personal Data Tasks#9. Other Risks To Watch\|Assess Personal Data Tasks]] |
| Policy Gap Assumption | Task-specific risk or manifestation | AI may fill gaps between policy provisions with plausible but unauthorised interpretations. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]]; [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Answer Policy Questions#9. Other Risks To Watch\|Answer Policy Questions]] |
| Policy-Practice Gap | Task-specific risk or manifestation | AI may draft aspirational policies that the organisation cannot implement — insufficient staff, systems, or processes to meet the stated standards. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Draft Organisational Policies#9. Other Risks To Watch\|Draft Organisational Policies]] |
| Prompt Injection | Prompt-side failure mode | Untrusted or malicious instructions in user input, retrieved content, documents, webpages, or tool results attempt to override the task, source, data, or authority boundaries. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]] | Defined in this index; see the linked risk family. |
| Prompt Over-Trust | Reusable human-review risk | Users or reviewers treat a well-designed, tested or approved prompt—and the AI’s apparent compliance with it—as evidence that the output is safe, accurate or ready to use. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Human Review Risk Library#4.7 Prompt Over-Trust\|Human Review Risk Library]] |
| Qualified Reviewer Bypass | Task-specific risk or manifestation | Users treat AI output on legal and compliance questions as sufficient for decision-making without professional review. | [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Verify HK Regulatory Questions#9. Other Risks To Watch\|Verify HK Regulatory Questions]] |
| Rapid Delivery — Limited Reversal | Task-specific risk or manifestation | Some platforms provide deletion or unsend features, but these may not reverse exposure after recipients have seen, copied, forwarded, downloaded, or captured the message. | [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | [[Use Cases/Draft WhatsApp Broadcasts#8. Main Risks\|Draft WhatsApp Broadcasts]] |
| Reader Interpretation Gap | Reusable human-review risk | AI may produce wording that seems clear to the sender but may be understood differently by the real reader. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.15 Reader Interpretation Gap\|Human Review Risk Library]] |
| Real-Time Social Context Gap | Task-specific risk or manifestation | AI should not be assumed to understand the group’s current emotional temperature, recent events, or how a fast broadcast may affect recipients unless relevant current context is provided. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Draft WhatsApp Broadcasts#9. Other Risks To Watch\|Draft WhatsApp Broadcasts]] |
| Recipient Impact Blindness | Reusable human-review risk | AI may miss how an output could affect a real person emotionally, relationally, practically, socially, or reputationally. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.16 Recipient Impact Blindness\|Human Review Risk Library]] |
| Recipient List and Personal Data | Task-specific risk or manifestation | A broadcast recipient list may contain personal data where names, telephone numbers, account identifiers, or other information identify living individuals. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft WhatsApp Broadcasts#9. Other Risks To Watch\|Draft WhatsApp Broadcasts]] |
| Register Mismatch | Task-specific risk or manifestation | Formal English may be translated into inappropriately casual Chinese, or vice versa. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]]; [[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity\|Tone / Representation / Cultural Sensitivity]] | [[Use Cases/Produce Bilingual Versions#9. Other Risks To Watch\|Produce Bilingual Versions]] |
| Regulatory Currency Gap | Task-specific risk or manifestation | Official requirements, guidance, forms, thresholds, and administrative positions may change. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]]; [[Risk Taxonomy#3.9 Legal / Regulatory / Compliance\|Legal / Regulatory / Compliance]] | [[Use Cases/Verify HK Regulatory Questions#9. Other Risks To Watch\|Verify HK Regulatory Questions]] |
| Relationship and Trust Context Gap | Task-specific risk or manifestation | AI may draft a neutral-looking volunteer role without knowing trust level, past conduct, safeguarding concerns, informal boundaries, or community history that should shape the role. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Draft Volunteer Roles#9. Other Risks To Watch\|Draft Volunteer Roles]] |
| Reliability Illusion | Reusable human-review risk | AI worked well many times, so users start assuming it will continue performing consistently like traditional software. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Human Review Risk Library#4.3 Reliability Illusion\|Human Review Risk Library]] |
| Salary Benchmark Fabrication | Named failure mode | AI invents or presents unsupported salary, pay, market, or benchmark figures as factual. | [[Risk Taxonomy#3.10 Professional / HR / Finance Boundary\|Professional / HR / Finance Boundary]] | Defined in this index; see the linked risk family. |
| Scope Creep | Task-specific risk or manifestation | A user asks a question that extends beyond the approved document scope and the AI answers anyway, drawing on general knowledge. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Answer Internal FAQs#9. Other Risks To Watch\|Answer Internal FAQs]] |
| Scope Misjudgement | Task-specific risk or manifestation | AI may rate a task as straightforward when the HK-specific, cultural, or domain-specific complexity puts it beyond the model’s actual knowledge. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Check Confidence Before Research#9. Other Risks To Watch\|Check Confidence Before Research]] |
| Selective Emphasis | Task-specific risk or manifestation | AI may emphasise points that appear statistically or linguistically prominent rather than those that are organisationally most important. | [[Risk Taxonomy#3.3 Context / Nuance / Compression\|Context / Nuance / Compression]] | [[Use Cases/Summarise Documents#9. Other Risks To Watch\|Summarise Documents]] |
| Sensitive Data in Prompt | Task-specific risk or manifestation | User may paste sensitive member information, confidential details, or pastoral content into the prompt. | Pastoral / Theological / Scripture; [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft Communications#9. Other Risks To Watch\|Draft Communications]] |
| Sensitive Detail Without Anchor | Task-specific risk or manifestation | If personal, pastoral/theological, or confidential details were withheld from the AI prompt, a named person must add them back manually into the correct version for the appropriate audience. | Pastoral / Theological / Scripture | [[Use Cases/Summarise Meeting Notes#9. Other Risks To Watch\|Summarise Meeting Notes]] |
| Session Memory Gap | Task-specific risk or manifestation | AI has no memory of previous newsletters or communications. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Use Cases/Draft Communications#9. Other Risks To Watch\|Draft Communications]] |
| Shadow AI Risk | Task-specific risk or manifestation | The tool used may be a personal consumer account rather than an approved organisation account. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]] | [[Use Cases/Draft Communications#9. Other Risks To Watch\|Draft Communications]] |
| Source Hallucination | Task-specific risk or manifestation | AI can produce plausible-looking citations that do not exist or do not support the stated claim. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]]; [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Use Cases/Research General Topics#8. Main Risks\|Research General Topics]] |
| Statistics Fabrication | Task-specific risk or manifestation | AI may invent supporting statistics — beneficiary numbers, outcome percentages, comparison figures — to support funding arguments. | [[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary\|Privacy / Confidentiality / Data Boundary]] | [[Use Cases/Draft Grant Applications#9. Other Risks To Watch\|Draft Grant Applications]] |
| Tacit Agreement Gap | Task-specific risk or manifestation | AI may not distinguish discussion, support, objection, deferral, and formal approval unless the notes are explicit. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Summarise Meeting Notes#9. Other Risks To Watch\|Summarise Meeting Notes]] |
| Template Scope Creep | Task-specific risk or manifestation | A reusable template can propagate one unsupported clause, field, or instruction across many later records. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Draft Admin Templates#8. Main Risks\|Draft Admin Templates]] |
| Terminology Inconsistency | Task-specific risk or manifestation | Providing a terminology translation table reduces inconsistency but does not eliminate it. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Translate General Communications#9. Other Risks To Watch\|Translate General Communications]] |
| Tone Drift | Task-specific risk or manifestation | AI may gradually shift tone beyond what was requested. | [[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity\|Tone / Representation / Cultural Sensitivity]] | [[Use Cases/Draft Communications#9. Other Risks To Watch\|Draft Communications]] |
| Tool Misuse | Named failure mode | An AI tool is used outside its permitted purpose, data boundary, account, settings, or approved operating conditions. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]] | Defined in this index; see the linked risk family. |
| Training Enabled | Named failure mode | AI input or uploaded data may be retained or used for service or model improvement because training or data-use settings are enabled. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]] | Defined in this index; see the linked risk family. |
| Translation Variant Confusion | Named failure mode | AI uses the wrong Chinese variant, regional language convention, or locale-specific form for the intended audience. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | Defined in this index; see the linked risk family. |
| Unapproved Workflow | Named failure mode | AI is used in a workflow or process that has not been approved for the task, data, action, or level of automation. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]] | Defined in this index; see the linked risk family. |
| Unauthorised External Action | Prompt-side failure mode | AI or an automated workflow attempts or performs an external action, such as sending, publishing, changing a record, or triggering a transaction, without the required human authority or approval. | [[Risk Taxonomy#3.5 Tool / Security / Process Governance\|Tool / Security / Process Governance]] | Defined in this index; see the linked risk family. |
| Unauthorised Organisational Voice | Task-specific risk or manifestation | For public posts, official notices, or social media, AI may generate content that sounds authoritative and represents the organisation’s position on matters not approved by leadership. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Draft Communications#9. Other Risks To Watch\|Draft Communications]] |
| Undeliverable Commitments | Task-specific risk or manifestation | AI may draft proposals that include commitments — timelines, resources, outputs — that the organisation cannot deliver. | [[Risk Taxonomy#3.6 Authority / Scope / Commitment\|Authority / Scope / Commitment]] | [[Use Cases/Draft Reports And Presentations#9. Other Risks To Watch\|Draft Reports And Presentations]] |
| Unknown Unknown | Task-specific risk or manifestation | AI cannot flag errors it does not know it has made. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Check AI Output Reliability#9. Other Risks To Watch\|Check AI Output Reliability]] |
| Unrealistic Role Expectations | Task-specific risk or manifestation | AI may draft aspirational role descriptions that do not match the organisation’s actual capacity, supervision resources, or volunteer time. | [[Risk Taxonomy#3.2 Source Grounding / Evidence\|Source Grounding / Evidence]] | [[Use Cases/Draft Volunteer Roles#9. Other Risks To Watch\|Draft Volunteer Roles]] |
| Unsupported Conclusions | Named failure mode | AI reaches or states a conclusion that is not adequately supported by the available evidence, sources, or stated reasoning. | [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | Defined in this index; see the linked risk family. |
| Unsupported or Misread Statistics | Task-specific risk or manifestation | In reports and presentations, AI may generate a plausible statistic from general model knowledge even though it is not in the supplied sources, or transpose, misread, or inconsistently repeat a figure from the source material. | [[Risk Taxonomy#3.10 Professional / HR / Finance Boundary\|Professional / HR / Finance Boundary]]; [[Risk Taxonomy#3.1 Accuracy / Hallucination\|Accuracy / Hallucination]] | [[Use Cases/Draft Reports And Presentations#8. Main Risks\|Draft Reports And Presentations]] |
| Untranslated English Words | Task-specific risk or manifestation | AI may leave English words embedded in Chinese text without translating them. | [[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context\|Bilingual / Localisation / HK Context]] | [[Use Cases/Translate General Communications#9. Other Risks To Watch\|Translate General Communications]] |
| Unwritten Context Gap | Reusable human-review risk | Relevant context is absent from, incomplete in, or not adequately represented in the task basis. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.14 Unwritten Context Gap\|Human Review Risk Library]] |
| User-Pressure Drift | Reusable human-review risk | AI changes a correct or cautious answer after a user confidently challenges it, even when no new reliable source has been provided. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Human Review Risk Library#4.22 User-Pressure Drift\|Human Review Risk Library]] |
| Volume Overwhelm | Reusable human-review risk | AI increases output volume faster than humans can responsibly review it, so review becomes nominal. | [[Risk Taxonomy#3.12 Operational Feasibility / Workflow\|Operational Feasibility / Workflow]] | [[Human Review Risk Library#4.6 Volume Overwhelm\|Human Review Risk Library]] |
| Wrong Question Confidence | Task-specific risk or manifestation | AI may confidently answer the question asked while a careful human would first notice that the question is incomplete, wrongly framed, or missing a decisive local constraint. | [[Risk Taxonomy#3.11 AI Blind Spot / Context Risks\|AI Blind Spot / Context Risks]] | [[Use Cases/Check Confidence Before Research#9. Other Risks To Watch\|Check Confidence Before Research]] |

---

## 5. Maintenance and Change Control

Keep risk-family names aligned with [[Mitigation Library]] and with any family links used on use-case pages. Keep the named-risk and failure-mode index aligned with Section 3 **Common forms**, [[Human Review Risk Library]], use-case risk sections, and [[Prompt Enhancement Patterns]]. Moving, renaming, splitting, or combining a family requires checking the taxonomy links, mitigation headings, affected **Common forms**, and affected use-case risk tables. Adding, renaming, or changing the family mapping of a named risk or failure mode requires checking its definition route, every **Common forms** occurrence, every prompt-table `Risk` cell, every **What this helps with** occurrence, and any affected use-case or review links.

Use [[Author and Editor Guide]] for common editorial, heading, localisation, validation, and packaging rules.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
