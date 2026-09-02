---
title: Draft Reports And Presentations
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC06
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft Reports And Presentations

## 1. What This Use Case Is

Use this page when you want AI to help with: **Draft reports, proposals, or presentations**.

- Common users: **SME, nonprofit**.
- Approval level: **Generally approved if non-confidential**.
- Human review needed: **Yes — author reviews before finalising**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A report or presentation may transpose figures, introduce unsupported statistics, omit caveats, or make a recommendation sound more certain than the evidence. Because the structure and totals look plausible, the error may influence a board, client, funder, or management decision before anyone traces each material claim back to its source.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open the source data and the report side by side.
2. Check every figure in every table against the source — cell by cell. Do not read for overall sense.
3. Check that figures in the narrative text match figures in tables. AI sometimes produces inconsistencies between body and table.
4. For any figure that cannot be traced to a specific source, mark it as unverified before circulation.

---

### 3.2 Before You Approve — One Check

> **Has every figure in this report been compared cell by cell against the source data — not read for overall plausibility, but checked field by field?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.13 AI Blind Spot|AI Blind Spot]]:** Whether the output fits the real people, real situation, real authority, and real consequences behind the task, including tacit context the AI was not told and lived or professional judgement that cannot be fully reduced to a prompt.
  - **For this use case:** Check the report against the actual stakeholders, decision purpose, organisational context, approval authority, political or relationship sensitivities, and consequences of decision-makers relying on the presentation.
- **[[Human Review Risk Library#4.18 Materiality Judgement Gap|Materiality Judgement Gap]]:** Identify the figures, conditions, caveats, differences, uncertainties, thresholds, and omissions that could change the decision. Check that important information remains visible and appropriately weighted, and that minor information is not treated as decisive.

---

### 3.4 Reviewer Decision

After completing the task-specific review checks above, choose one outcome using [[Reviewer Decision Card]]:

- **Approve as is**
- **Correct then approve**
- **Stop and escalate**

Do not approve the output if the reviewer lacks the role, evidence, authority, competence, source access, context, or approved process needed for this task.

---

### 3.5 Review Methods for This Task

The review instructions below are customised for this task. They apply the reusable methods in [[Human Review Patterns]] to the actual sources, decisions, people, and consequences involved here.

- **Source and fact verification:** Verify every factual claim, statistic, date, quotation, comparison, and cited source against the approved evidence.
  - Look for: Fabricated or outdated statistics, unsupported causal claims, and conclusions stronger than the source.
  - Timing: Before circulation, presentation, or decision use.
  - Reviewer: Author, subject owner, or source-checking reviewer.

- **Extracted data verification:** Reconcile figures, totals, percentages, labels, periods, and chart inputs with the approved spreadsheet or source record.
  - Look for: Wrong denominator, mixed periods, transposed fields, inconsistent totals, or chart labels that do not match the data.
  - Timing: Before charts or figures are finalised.
  - Reviewer: Data owner, finance reviewer, analyst, or responsible author.

- **General output review:** Check whether the report or presentation answers the intended question, suits the audience, separates fact from interpretation, and keeps important limitations visible.
  - Look for: A polished narrative that hides uncertainty, overstates confidence, or gives minor points more weight than material ones.
  - Timing: Before approval or presentation.
  - Reviewer: Report owner, decision owner, or responsible presenter.

- **Privacy / data-boundary review:** Check source files, extracts, charts, quotations, images, and distribution for personal, confidential, restricted, or third-party content.
  - Look for: Identifiable data, confidential details, copied material without permission, or wider circulation than approved.
  - Timing: Before prompting and before circulation.
  - Reviewer: Information owner, privacy-aware reviewer, or authorised publisher.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when output may affect employment, pay, invoices, benefits, safeguarding, medical, pastoral/theological, finance, or professional obligations and the reviewer is not authorised or competent to confirm the matter.
- Escalate when wording concerns vulnerable groups, culture, crisis, complaints, or public reputation and the reviewer lacks the context, authority, or approved process to confirm safe use.
- Escalate when a claim affects legal, financial, pastoral, theological, public, or external decision-making and the reviewer is not authorised or competent to confirm it.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Generally approved if non-confidential**.
- Confirm that the planned reviewer can complete the required human review: **Yes — author reviews before finalising**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Materiality Judgement Gap

**Prompt focus:** Before prompting, give the AI the audience, decision purpose, source data, date range, caveats, approval status, and what must not be overstated. Ask it to identify assumptions, missing evidence, and decision-critical figures, caveats, or limitations requiring confirmation.

**Human review focus:** The reviewer should check figures, caveats, limitations, source dates, material omissions, and whether the draft changes what decision-makers will believe or approve.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the report supports a decision and may depend on caveats, missing figures, audience politics, or material details that only a domain reviewer can judge.

**Do not rely only on:** polish or structure. A report can look complete while omitting the detail that changes the decision.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Grant or Funding Report Section
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter
- HK Safe AI Use Pack and Prompt Pattern Library.md — Hallucination Check

---

## 8. Main Risks

- **[[Risk Taxonomy#3.10 Professional / HR / Finance Boundary|Professional / HR / Finance Boundary]]: Unsupported or Misread Statistics (High)** — In reports and presentations, AI may generate a plausible statistic from general model knowledge even though it is not in the supplied sources, or transpose, misread, or inconsistently repeat a figure from the source material. A reviewer who checks only the argument and formatting may miss the error. Every material figure must be traced to an approved source.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.18 Materiality Judgement Gap|Materiality Judgement Gap]] (High)** — AI may misjudge the importance of figures, conditions, caveats, differences, uncertainties, or stakeholder concerns. It may omit or soften an important point, give too much weight to a minor point, or treat uncertain information as decisive, making the report’s emphasis, conclusion, recommendation, tone, approval route, or next action inappropriate.
- **[[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity|Tone / Representation / Cultural Sensitivity]]: False Confidence Tone (High)** — Reports and proposals drafted by AI tend to present uncertain information with confident language. Uncertainty, risk caveats, and qualifications are under-represented in AI-generated professional documents.
- **[[Risk Taxonomy#3.1 Accuracy / Hallucination|Accuracy / Hallucination]]: Missing Organisational Context — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (Medium)** — AI should not be assumed to know internal priorities, budget constraints, political dynamics, or relationship history unless that context is supplied through approved sources. A proposal may be logically sound but wrong for the specific organisational situation it addresses.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Undeliverable Commitments (High)** — AI may draft proposals that include commitments — timelines, resources, outputs — that the organisation cannot deliver. Reviewers focus on content quality rather than feasibility.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Intellectual Property and Attribution Risk (Medium)** — AI may produce wording, structure, images, or ideas that closely resemble source material without reliable attribution or permission information. Published or client-facing content may therefore create attribution, licence, contractual, reputational, or legal concerns that require source checking and qualified review where material.

---

## 10. Prompt Enhancements To Add

Start with the base prompt pattern from the Win.Win AI Essentials. The add-ons below are already customised for this task.

Use only the rows that match the actual situation. Do not add unrelated controls merely because they appear in [[Prompt Enhancement Patterns]]. Do not create a prompt add-on for a risk that must be handled mainly through human review, an approved tool, specialist checking, other mitigation, or escalation.

Keep source material, notes, policy extracts, figures, and documents under **Content** at the end of the base prompt.

---

### 10.1 Default Add-Ons

Use these for this use case unless there is a clear reason not to.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Unsupported or Misread Statistics | **Rule** | Use only figures supplied in approved sources. Show the source, period, unit, and calculation basis, and mark missing figures `{VERIFY}`. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Unsupported or Misread Statistics | **Output Format** | Provide a `Data and claim verification` table linking each material figure or claim to its source. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| AI Blind Spot | **Instruction** | Identify assumptions, missing evidence, uncertainty, authority limits, and items requiring human confirmation that could change the report’s suitability, interpretation, recommendation, or decision consequence. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Output Format** | Add `Assumptions and human confirmation needed` with `Item`, `Why it matters`, `Evidence or owner needed`, and `Status`. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Reminder / Review Note** | This list is a review aid only. The decision owner and relevant domain reviewer must still check the report against the actual stakeholders, authority, and consequences. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Materiality Judgement Gap | **Instruction** | Where importance is known, state which information, caveats, thresholds, differences, or uncertainties must remain visible and must not be treated as minor or decisive without justification. | [[Prompt Enhancement Patterns#5.13 Materiality Control\|Materiality Control]] |
| Materiality Judgement Gap | **Reminder / Review Note** | A human reviewer must identify what is important to this report and check whether the output recognised and handled it appropriately. | [[Prompt Enhancement Patterns#5.13 Materiality Control\|Materiality Control]] |
| Materiality Judgement Gap | **Rule** | If the importance of an item is uncertain, mark it `{MATERIALITY REVIEW}`. Do not omit, soften, elevate, or treat it as decisive without reviewer confirmation. | [[Prompt Enhancement Patterns#5.13 Materiality Control\|Materiality Control]] |
| False Confidence Tone | **Audience / Tone / Language** | Use wording that distinguishes confirmed fact, interpretation, estimate, uncertainty, and recommendation. Do not make the conclusion sound more certain than the evidence. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |
| Missing Organisational Context | **Instruction** | Apply relevant non-sensitive organisational aims, constraints, prior decisions, and audience sensitivities supplied under Content. Flag missing context that may change the report. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| Undeliverable Commitments | **Rule** | Distinguish proposals and targets from approved commitments. Do not promise resources, dates, outcomes, or capacity not confirmed by the responsible owner. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Intellectual Property and Attribution Risk | **Rule** | Do not reproduce substantial third-party text, images, charts, or confidential material without permission. Identify material requiring attribution or rights review. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Human review must include fraud/authenticity checks; AI extraction alone must not be relied on to determine whether a document has been altered.
- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.
- Human review reduces risk, but it does not guarantee accuracy. Keep records and use approved tools.
- If sensitive data was already entered into an unapproved tool, output review cannot undo exposure. Escalate according to privacy / incident process.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Safety Checklist - Work.md — Human review reminders
- AI Use Case Triage Scorecard.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Grant or Funding Report Section
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before finalising a report or presentation, check what is material: figures, caveats, assumptions, omitted limits, audience reaction, decision implications, and what the organisation can responsibly stand behind.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
