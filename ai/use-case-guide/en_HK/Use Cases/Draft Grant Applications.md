---
title: Draft Grant Applications
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC16
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft Grant Applications

## 1. What This Use Case Is

Use this page when you want AI to help with: **Draft grant applications or funding report sections**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — verify funder rules, statistics, and impact claims**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A grant draft may use unsupported metrics, general grant-writing assumptions, or outdated funder requirements instead of the current application materials and the organisation’s own evidence. The application may then contain inaccurate claims, miss a required element, or commit to delivery that the organisation cannot support, leading to delay, rejection, rework, or damaged credibility.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open the funder’s current application guidelines alongside the draft.
2. Check every required section, word limit, eligibility criterion, and submission format against the guidelines.
3. Verify every metric and statistic against the organisation’s own records or publicly available HK data — not AI output.
4. Remove any figure or claim that cannot be traced to a specific verifiable source.

---

### 3.2 Before You Approve — One Check

> **Has every metric, eligibility claim, funder rule, and required section in this application been verified against the funder’s current published guidelines and the organisation’s own programme data — not drawn from AI’s general knowledge?**

---

### 3.3 Reviewer Decision

After completing the task-specific review checks above, choose one outcome using [[Reviewer Decision Card]]:

- **Approve as is**
- **Correct then approve**
- **Stop and escalate**

Do not approve the output if the reviewer lacks the role, evidence, authority, competence, source access, context, or approved process needed for this task.

---

### 3.4 Review Methods for This Task

The review instructions below are customised for this task. They apply the reusable methods in [[Human Review Patterns]] to the actual sources, decisions, people, and consequences involved here.

- **Source and fact verification:** Check every eligibility statement, funder rule, deadline, outcome claim, statistic, quotation, and organisational fact against the current funder documents and approved records.
  - Look for: Invented funder preferences, unsupported impact claims, old deadlines, and claims stronger than the evidence.
  - Timing: Before submission.
  - Reviewer: Grant owner, source-checking reviewer, or person accountable for the application.

- **Extracted data verification:** Reconcile every budget figure, total, date, beneficiary number, target, and reported result with the approved spreadsheet or record.
  - Look for: Transposed figures, wrong periods, double counting, totals that do not reconcile, or projected figures presented as actual.
  - Timing: Before submission and before any financial report is signed.
  - Reviewer: Finance reviewer, grant administrator, or responsible data owner.

- **General output review:** Check that the application answers the funder’s actual questions, fits the word limits, distinguishes evidence from aspiration, and does not overstate organisational capacity or relationship.
  - Look for: Polished but generic answers, unsupported certainty, unrealistic promises, or omission of a required criterion.
  - Timing: Before final sign-off.
  - Reviewer: Proposal owner and programme lead.

- **Qualified legal / compliance review:** Confirm declarations, eligibility, restricted funding conditions, data/privacy statements, and contractual or regulatory commitments where needed.
  - Look for: A declaration or compliance statement that the organisation is not authorised or qualified to make.
  - Timing: Before submission where legal, regulatory, contractual, or compliance consequences exist.
  - Reviewer: Qualified legal/compliance reviewer or authorised organisational owner.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.
- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights/obligation issues unless the reviewer is explicitly authorised and competent to confirm the matter under the approved process.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — verify funder rules, statistics, and impact claims**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Funder Relationship and Unrealistic Ask Gap

**Prompt focus:** Before prompting, give the AI the funder guidance, project facts, budget source, timeline status, evidence, confirmed commitments, and any known funder relationship or prior feedback. Ask it to mark assumptions, provisional claims, and items needing source or owner confirmation.

**Human review focus:** The reviewer should check whether the application reflects real capacity, funder expectations, confirmed figures, and current commitments. Do not let persuasive language turn provisional plans into confirmed claims.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the draft depends on funder relationship history, past feedback, informal expectations, local assessment culture, or realistic delivery constraints.

**Do not rely only on:** persuasive writing. A grant draft can sound fundable while overstating capacity, evidence, or commitment.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Grant or Funding Report Section
- HK Safe AI Use Pack and Prompt Pattern Library.md — Hallucination Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check

---

## 8. Main Risks

- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Funder Rule Fabrication (High)** — A grant application must follow the specific current funder materials supplied for that opportunity, not general grant-writing conventions. AI may invent or import eligibility rules, priorities, required sections, assessment criteria, or metrics from another programme or context. A polished application built on unsupported requirements may be delayed, rejected, or require substantial rework.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: Funder Relationship and Unrealistic Ask Gap (High)** — AI may write persuasive content while missing funder history, informal feedback, current priorities, or whether the proposed timeline and budget feel realistic to people who must deliver the project.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Impact Claim Inflation (High)** — AI may generate stronger impact claims than the evidence supports by extrapolating from limited data, rounding figures, or presenting planned outcomes as achieved results. This may misrepresent the organisation’s evidence, capacity, or track record to the funder.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Statistics Fabrication (High)** — AI may invent supporting statistics — beneficiary numbers, outcome percentages, comparison figures — to support funding arguments. These appear credible in a professional document and are hard to detect without source verification.
- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Compliance Gap (High)** — Grant compliance requirements are funder-specific and change with each funding cycle. AI should not be assumed to know the current requirements unless they are supplied or retrieved from approved, current sources. A missing mandatory element may disqualify the application.

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
| Funder Rule Fabrication | **Instruction** | Use only the current funder guidance, application form, eligibility rules, and approved organisational records supplied under Content. Cite the relevant requirement for each material answer. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Funder Rule Fabrication | **Rule** | If a funder rule, deadline, eligibility condition, required attachment, or assessment criterion is not found, mark `{NOT FOUND IN FUNDER MATERIAL}` and do not invent it. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Funder Relationship and Unrealistic Ask Gap | **Rule** | Do not imply an existing funder relationship, likely success, special access, or delivery capacity that is not supported by approved evidence. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Funder Relationship and Unrealistic Ask Gap | **Instruction** | Identify assumptions requiring owner confirmation about the funder relationship, eligibility, budget, timeline, evidence, delivery capacity, previous applications, and prior feedback. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Impact Claim Inflation | **Instruction** | Distinguish actual results, approved estimates, forecasts, and aspirations. Keep caveats and measurement limits visible. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]] |
| Statistics Fabrication | **Rule** | Use only supplied statistics with their source and period. Use `{VERIFY}` or a placeholder for any missing figure. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Compliance Gap | **Reminder / Review Note** | Identify declarations, eligibility claims, restrictions, or obligations requiring authorised owner or qualified review before submission. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| Compliance Gap | **Rule** | Do not present legal, regulatory, tax, employment, privacy, contractual, or funder-compliance content as clearance. Mark it `{QUALIFIED REVIEW REQUIRED}`. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.
- Human review reduces risk, but it does not guarantee accuracy. Keep records and use approved tools.
- Human review must include fraud/authenticity checks; AI extraction alone must not be relied on to determine whether a document has been altered.
- Ordinary human review is not enough. Final reliance requires qualified professional judgement and current authoritative sources.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before submitting grant content, check the AI draft against funder guidance, past funder feedback, real delivery capacity, evidence for impact claims, budget support, and any relationship context the AI was not told.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
