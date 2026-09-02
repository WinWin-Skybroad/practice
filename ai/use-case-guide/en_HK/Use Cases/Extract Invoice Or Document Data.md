---
title: Extract Invoice Or Document Data
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC23
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Extract Invoice Or Document Data

## 1. What This Use Case Is

Use this page when you want AI to help with: **Extract invoice or document data from standardised digital documents**.

- Common users: **SME, nonprofit**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — finance or responsible staff verification before recording**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

AI may accurately extract what appears on a document even when the document is altered, duplicated, incomplete, or inconsistent with trusted records. If payment details or other material fields are accepted without cross-checking the original and an independent approved source, the organisation may make a wrong payment, record incorrect data, or face a difficult recovery or insurance dispute.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open the organisation’s approved supplier register alongside the extracted data.
2. For every payment: verify the payee name, bank account number, and payment amount against the supplier’s registered details. Do not rely on the document alone.
3. Flag any discrepancy between extracted data and registered details for human investigation before processing.
4. For high-value payments, require a second reviewer to verify account details independently before authorising.

---

### 3.2 Before You Approve — One Check

> **Has every bank account number, payee name, and payment amount in this extraction been compared against the supplier’s registered details in the organisation’s own records — not just against the document?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.19 Anomaly Instinct Gap|Anomaly Instinct Gap]]:** Check whether any figure, supplier name, bank detail, date, sequence, format, field, process step, or omission is unusual compared with the source document, supplier register, purchase record, and normal organisational practice. Use an experienced finance or procurement reviewer where the first reviewer may not recognise warning signs.

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

- **Extracted data verification:** Compare every extracted field with the exact location in the source document and recalculate totals, tax, currency, and dates where applicable.
  - Look for: OCR substitutions, transposed digits, wrong field mapping, missing pages, duplicate records, and totals that do not reconcile.
  - Timing: Before data is recorded, imported, approved, or paid.
  - Reviewer: Finance staff, data owner, or responsible person familiar with the document.

- **Document fraud / authenticity check:** Verify supplier identity, invoice number, payment details, purchase order, delivery record, and changes against independent organisational records.
  - Look for: Changed bank details, duplicate invoice, mismatched supplier, altered document, or a document that is internally consistent but not genuine.
  - Timing: Before payment or operational reliance.
  - Reviewer: Finance owner, procurement owner, or person authorised to verify the external record.

- **Human-grounded review:** Consider whether the reviewer has enough experience to notice unusual patterns or missing expected information. Seek an experienced or qualified reviewer when they may not.
  - Look for: Plausible data that falls outside normal ranges, an expected field or document missing, or a process step that an experienced person would question.
  - Timing: Before approval, payment, or recording.
  - Reviewer: Experienced finance, procurement, operations, or domain reviewer.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when output may affect employment, pay, invoices, benefits, safeguarding, medical, pastoral/theological, finance, or professional obligations and the reviewer is not authorised or competent to confirm the matter.
- Escalate before tool use when confidential data, third-party systems, financial processing, or automation is involved and the tool, account, reviewer, or process has not been approved for that use.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — finance or responsible staff verification before recording**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Anomaly Instinct Gap

**Prompt focus:** Before prompting, give the AI the document type, fields to extract, required format, expected ranges or known vendors when appropriate, and instructions to mark unreadable or ambiguous fields instead of guessing. Ask it to flag unusual amounts, dates, names, account details, or formatting anomalies for manual confirmation.

**Human review focus:** The reviewer should check every extracted field against the original document. Ask whether any amount, vendor, account detail, date, or document feature looks unusual even if the extraction appears tidy.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the document may depend on local vendor history, expected figure ranges, usual bank details, recurring formats, or anomaly signals that experienced staff know but the AI was not given.

**Do not rely only on:** tidy extraction. A clean table can still carry a wrong amount, altered account detail, or suspicious anomaly.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter
- HK Safe AI Use Pack and Prompt Pattern Library.md — Document Summary

---

## 8. Main Risks

- **[[Risk Taxonomy#3.10 Professional / HR / Finance Boundary|Professional / HR / Finance Boundary]]: Parsing and OCR Error (High)** — AI may misread visible text, numbers, dates, totals, invoice numbers, account details, or field labels. It may also map a value to the wrong field while preserving a format that looks correct. These errors are easy to miss when the reviewer checks only whether the extracted data resembles the document. For finance or records use, every extracted field must be checked against the original document before it is entered, paid, filed, or relied on.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.19 Anomaly Instinct Gap|Anomaly Instinct Gap]] (High)** — AI may fail to notice an unusual vendor, amount, account detail, date, sequence, format, or other warning sign, and may also miss expected information that is absent. The reviewer may lack the experience needed to recognise the anomaly or omission and may need an appropriate professional, domain expert, source owner, or experienced responsible person to review it.
- **[[Risk Taxonomy#3.10 Professional / HR / Finance Boundary|Professional / HR / Finance Boundary]]: Field Mapping Error (High)** — AI may assign extracted data to the wrong category — for example, attributing a subtotal to a different line item, or mapping a supplier code to a product code field. These errors are invisible without item-by-item verification against the source.
- **[[Risk Taxonomy#3.5 Tool / Security / Process Governance|Tool / Security / Process Governance]]: Fraud Detection Bypass (High)** — AI extraction should not be relied on to establish whether an invoice or document is authentic. Altered figures, forged stamps, manipulated dates, or other changes may still be extracted without warning.

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
| Parsing and OCR Error | **Instruction** | Extract only the named fields and show the source page, section, or label for each value. Preserve characters exactly and state when text is unclear. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Parsing and OCR Error | **Rule** | Do not infer, autocorrect, or complete an unreadable value. Mark it `{UNREADABLE}` or `{VERIFY}`. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Parsing and OCR Error | **Output Format** | Use a table with `Field`, `Extracted value`, `Source location`, `Confidence`, and `Verification status`. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Anomaly Instinct Gap | **Instruction** | Flag unusual or missing fields, figures, dates, supplier details, sequences, formats, totals, or process documents for an experienced reviewer. Do not decide that an anomaly is harmless. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]] |
| Field Mapping Error | **Rule** | Map each value only to the named target field. Do not move an amount, identifier, date, tax value, or address into a different field because it appears plausible. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Fraud Detection Bypass | **Rule** | Do not state that the document is genuine, safe to pay, or fraud-free. Identify the independent records and authorised checks required. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| Fraud Detection Bypass | **Instruction** | List the supplier name, bank details, invoice number, purchase order, amount, tax, dates, payment instructions, and any changed details that require comparison with the approved supplier record, purchase record, and authorised payment checks. Flag mismatches or unavailable records. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Human review must include fraud/authenticity checks; AI extraction alone must not be relied on to determine whether a document has been altered.

---

## 12. Related Win.Win AI Essentials Items

- Agent Approval Checklist.md — if extraction is automated or agentic
- AI Use Case Triage Scorecard.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Document Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Minimum Security Baseline for Agentic AI.md — if extraction is automated or agentic
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before recording, paying, or reporting extracted data, compare every field against the source document and ask whether anything looks unusual: vendor, amount, bank details, invoice number, date, duplicate, or document authenticity.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
