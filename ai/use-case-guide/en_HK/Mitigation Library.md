---
title: Mitigation Library
created: 2026-07-01
updated: 2026-08-14
version: "1.0"
status: active
type: reference
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Mitigation Library

## 1. Purpose and Scope

Use this file when a use-case page points to a mitigation control, when prompt wording and ordinary review are not enough, or when you are designing a local workflow.

Use-case pages give the task-specific mitigation guidance needed to begin. This file explains reusable controls that can support several use cases. It does not need to be read before every use-case page.

Mitigation means reducing risk through something beyond prompt wording.

Prompt enhancement can guide the AI. Human review can catch many errors. Some risks also need process controls, approval rules, source controls, or escalation.

---

## 2. How To Use This Reference

Use the mitigation entries after identifying the relevant risk family. Select only the controls that apply to the real task, organisation, data, authority, and consequences. Do not treat a generic mitigation list as automatic approval for a local workflow.

---

## 3. Entry Structure Standard

Each mitigation entry describes controls outside ordinary prompt wording, including process, source, approval, workflow, or escalation controls.

---

### 3.1 Mandatory Sections

#### Default other mitigation

State the normal non-prompt control for the risk family.

#### Useful controls

List practical organisational controls, records, approval gates, source controls, or workflow safeguards that may support the mitigation.

#### Escalation trigger

State when ordinary review is insufficient because the reviewer lacks the required evidence, source access, context, competence or qualification, authority, approved process, or ability to resolve material uncertainty, or when the approved process itself requires escalation.

---

### 3.2 Optional Sections

#### Prompt-side mitigation

Use where a prompt action is part of the wider mitigation but is not sufficient by itself.

#### Human-review mitigation

State the specific human judgement or real-world check needed beyond prompting.

#### Other controls

Use for additional operational, technical, governance, or recordkeeping controls that do not fit the standard fields.

---

## 4. Mitigations

### 4.1 Accuracy / Hallucination

#### Default other mitigation

- Keep source material available; verify all factual claims; mark unsupported claims as placeholders.

#### Useful controls

- Approved source pack, citation log, fact-check step, version control.

#### Escalation trigger

- Escalate when a material factual claim, figure, source, attribution, or conclusion cannot be adequately verified and the reviewer does not have the evidence, source access, context, competence, authority, or approved process needed to resolve the uncertainty or confirm the claim. This includes legal, financial, pastoral, theological, public, or other specialist claims where the reviewer lacks the required standing to confirm them.

---

### 4.2 Source Grounding / Evidence

#### Default other mitigation

- Use approved source documents only; record source version/date; do not answer from memory.

#### Useful controls

- Approved document repository, source version naming, source comparison review.

#### Escalation trigger

- Escalate when the source is unclear, outdated, missing, or conflicts with another approved source and the reviewer cannot resolve the issue through the available approved sources, source access, competence, authority, or approved source-checking process.

---

### 4.3 Context / Nuance / Compression

#### Default other mitigation

- Keep original document/minutes attached; require source-owner or meeting-attendee review.

#### Useful controls

- Keep original materials available; require attendee/source-owner review for complex summaries.

#### Escalation trigger

- Escalate when a summary may influence decisions, approvals, funding, HR, legal, or governance action and the reviewer does not have the source access, context, competence, authority, or approved process needed to confirm that material facts, conditions, caveats, and nuance have been preserved.

---

### 4.4 Privacy / Confidentiality / Data Boundary

#### Default other mitigation

- Remove or anonymise personal data before prompting; use approved tools/settings; apply PDPO pre-check.

#### Useful controls

- PDPO pre-check, approved AI tool, training opt-out, data classification, redaction workflow.

#### Escalation trigger

- Escalate when personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.

---

### 4.5 Tool / Security / Process Governance

#### Default other mitigation

- Use only approved tools/accounts; check training/data-retention settings; document workflow approval.

#### Useful controls

- Approved tool list, minimum security baseline, access control, vendor review, workflow approval.

#### Escalation trigger

- Escalate before tool use when confidential data, third-party systems, financial processing, or automation is involved and the reviewer or process does not have the authority, technical competence, context, source access, or approved tool and workflow controls needed to confirm safe use.

---

### 4.6 Authority / Scope / Commitment

#### Default other mitigation

- Route draft to authorised owner before use; keep approval record; prohibit AI-generated commitments.

#### Useful controls

- Approval route, authorised sender review, sign-off record, scope statement.

#### Escalation trigger

- Escalate when the output could bind the organisation, affect rights or obligations, or appear as official approval and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm and approve that use.

---

### 4.7 Tone / Representation / Cultural Sensitivity

#### Default other mitigation

- Use approved tone examples; have target-audience or communications owner review.

#### Useful controls

- Tone examples, approved voice guide, reviewer from target audience or ministry context.

#### Escalation trigger

- Escalate when wording concerns vulnerable groups, culture, crisis, complaints, or public reputation and the reviewer does not have the context, competence, authority, source access, or approved process needed to judge the wording, likely impact, and appropriate response.

---

### 4.8 Bilingual / Localisation / HK Context

#### Default other mitigation

- Maintain HK/TC terminology glossary; require TC-proficient reviewer; verify official HK terms.

#### Useful controls

- Terminology glossary, TC reviewer, official HK source verification, bilingual review.

#### Escalation trigger

- Escalate legal, medical, financial, technical, or public translation when the reviewer does not have the language and subject-matter competence, authority, context, source access, or approved process needed to confirm the specialist meaning.

---

### 4.9 Legal / Regulatory / Compliance

#### Default other mitigation

- Check official HK source and obtain qualified legal/compliance review before adoption or advice.

#### Useful controls

- Solicitor/compliance review, official source check, policy owner sign-off.

#### Escalation trigger

- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights or obligation issues when the reviewer does not have the authority, competence, current official-source access, context, or approved process needed to confirm the matter.

---

### 4.10 Professional / HR / Finance Boundary

#### Default other mitigation

- Require HR/finance/professional owner review; use approved templates; avoid advice or compliance assurance.

#### Useful controls

- HR/finance/professional reviewer, approved templates, dual control, policy owner sign-off.

#### Escalation trigger

- Escalate when output may affect employment, pay, invoices, benefits, safeguarding, medical, pastoral or theological matters, finance, or professional obligations and the reviewer does not have the authority, competence or qualification, context, source access, or approved process needed to confirm the matter.

---

### 4.11 AI Blind Spot / Unwritten Context

AI Blind Spot risks are managed in two different moments: prompting reduces the blind spot before output is created, and human review checks the remaining blind spot before output is used.

#### Prompt-side mitigation

- Provide the real-world context that a human professional would normally know or ask for: audience, purpose, constraints, source documents, local practice, authority limits, known exceptions, intended use, and decision context.
- Ask the AI to surface likely assumptions, task-type missing-information categories, decision dependencies, authority limits, uncertainty, and items that may require human confirmation.
- Treat the AI’s assumption list as a review aid, not proof that every missing context item has been found.
- Ask the AI to preserve uncertainty instead of resolving unclear points into confident wording.

#### Human-review mitigation

- Check whether the AI’s assumptions match the real organisation, people, sources, authority, and consequences.
- Ask whether a smart human reviewer would have requested more information before answering.
- Do not rely on the AI to know every local gap. The reviewer must still check organisational history, informal practice, relationship context, current sensitivities, local constraints, and approval authority.

#### Other controls

- Named responsible reviewer.
- Source owner check.
- Authority owner sign-off.
- Assumption checklist.
- Independent source, record, or policy check where the output affects a decision.
- Written approval record for high-impact outputs.

#### Escalation trigger

- Escalate when the reviewer lacks the evidence, source access, context, authority, domain competence, or approved process needed to confirm the output or safely resolve an identified blind spot.
- Where the output touches legal, financial, HR, privacy, regulatory, pastoral, theological, safeguarding, or other specialist matters, escalate when those reviewer requirements are not met or when the approved process requires accountable or specialist review.

---

### 4.12 Operational Feasibility / Workflow

#### Default other mitigation

- Confirm owners, dates, dependencies, venue or capacity, correction channel, operational feasibility, expected output volume, and real review capacity before generation.
- Set the requested output or batch size within what named reviewers can check before use.

#### Useful controls

- Complete source packet, well-scoped prompt, output or batch limits, named-reviewer assignment, risk-based triage, review queue limits, owner sign-off, pilot use, correction channel, operational checklist, and version control.

#### Escalation trigger

- Escalate when the plan affects public events, logistics, safety, finance, external parties, or many recipients and the responsible reviewer or owner does not have the operational evidence, context, competence, authority, or approved process needed to confirm feasibility and consequences.
- Pause or reduce the output scope when volume exceeds real review capacity or no named reviewer can complete the required review before use. Escalate if adequate review capacity or a suitable named reviewer cannot be established within the approved process.

---

## 5. Maintenance and Change Control

Keep mitigation-family names aligned with the corresponding families in [[Risk Taxonomy]]. When a mitigation changes, check the use-case pages that rely on that family under **Other Mitigation** and preserve valid task-specific controls.

Use [[Author and Editor Guide]] for common editorial, heading, localisation, validation, and packaging rules.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
