---
title: Verify HK Regulatory Questions
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC11
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Verify HK Regulatory Questions

## 1. What This Use Case Is

Use this page when you want AI to help with: **Verify Hong Kong legal, regulatory, or compliance questions**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Escalate before relying on output**.
- Human review needed: **Yes — verify with official sources or qualified professionals**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A regulatory answer may explain the general framework correctly while missing a current official requirement, a fact-specific condition, or the regulator’s position on the proposed arrangement. If the organisation acts on the AI answer as clearance, it may submit inaccurate information, miss an applicable requirement, delay the activity, or face rectification and regulatory exposure.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Identify the specific regulatory body and ordinance relevant to the question.
2. Go directly to the regulator’s official website and search for current guidance on this topic.
3. Treat the AI answer as a list of issues to verify, not as the answer itself.
4. For any regulatory conclusion with financial or operational consequence, escalate to a qualified professional before acting.

---

### 3.2 Before You Approve — One Check

> **Has a qualified legal or compliance professional with current knowledge of the relevant regulator’s position confirmed this conclusion — not by reading the AI answer and agreeing with it, but by independently checking the current official guidance?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.13 AI Blind Spot|AI Blind Spot]]:** Whether the output fits the real people, real situation, real authority, and real consequences behind the task, including tacit context the AI was not told and lived or professional judgement that cannot be fully reduced to a prompt.
  - **For this use case:** Check the answer against the actual entity, activity, date, Hong Kong jurisdiction, professional responsibility, decision authority, and consequences of acting on the regulatory interpretation.
- **[[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]]:** Verify every material position against current Hong Kong legislation, regulator guidance, official sources, and appropriately qualified local expertise. Check that Mainland China, overseas, or generic regulatory assumptions have not been substituted or combined.

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

- **Qualified legal / compliance review:** Treat the AI output as issue-spotting only. Independently check the specific question against current official Hong Kong law, regulator guidance, and qualified professional judgement.
  - Look for: Unsupported legal conclusions, outdated regulator positions, omitted requirements, or an answer that sounds authoritative without professional confirmation.
  - Timing: Before relying on, sharing, or acting on the answer.
  - Reviewer: Qualified Hong Kong legal, compliance, privacy, HR, tax, regulatory, or relevant professional reviewer.

- **Source and fact verification:** Verify every ordinance, section, regulator name, guidance document, effective date, threshold, deadline, and factual statement against the current official source.
  - Look for: Wrong citation, superseded guidance, mixed versions, or a claim that cannot be found in the named official source.
  - Timing: Before professional sign-off or decision use.
  - Reviewer: Source-checking reviewer or qualified professional with current official access.

- **Scope, authority, and feasibility review:** Confirm the exact jurisdiction, organisation, activity, decision, and authority boundary, and ensure the output does not give final clearance or approval.
  - Look for: Stacking rules from different jurisdictions, applying a general rule to the wrong entity, or bypassing the responsible decision owner.
  - Timing: Before action is taken.
  - Reviewer: Compliance owner, decision owner, or authorised manager.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights/obligation issues unless the reviewer is explicitly authorised and competent to confirm the matter under the approved process.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Escalate before relying on output**.
- Confirm that the planned reviewer can complete the required human review: **Yes — verify with official sources or qualified professionals**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Accountability Gap

**Prompt focus:** Before prompting, give the AI the exact HK regulatory question, date, organisation type, intended use, and required official sources. Ask it to identify assumptions, official sources to check, uncertainty, and items requiring review by the right qualified or responsible person.

**Human review focus:** Verify against current official HK sources and escalate when the answer affects compliance, money, rights, obligations, personal data, public statements, pastoral/theological matters, or organisational responsibility.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the question depends on unstated local practice, why the regulatory answer is needed, professional responsibility, or a decision the reviewer is not authorised to make. Use current Hong Kong official sources and qualified review as the primary controls for regulatory accuracy.

**Do not rely only on:** AI confidence or source-looking wording. Regulatory responsibility remains with responsible people and qualified reviewers, not the model.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — Calibrated Research (HK)

---

## 8. Main Risks

- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: AI Legal or Regulatory Advice Substitution (High)** — A regulatory answer may depend on current legislation, official guidance, FAQs, licensing or registration conditions, dates, entity type, and the exact facts of the proposed activity. AI may describe the general framework correctly and still be wrong about the current or fact-specific position. Treat the output as issue-spotting only; independently check current official sources and obtain qualified advice before relying on it for a consequential decision.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Accountability Gap (High)** — AI may summarise regulatory material confidently, but it has no professional licence, duty, reputation, or liability attached to the advice. Confidence is not accountability.
- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Jurisdiction and Scope Error — related review risk: [[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]] (High)** — AI may combine rules from different jurisdictions, apply a general rule to the wrong entity or activity, or overlook a fact-specific exception, approval route, or regulator position.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Regulatory Currency Gap (High)** — Official requirements, guidance, forms, thresholds, and administrative positions may change. AI may not reflect the version in force or currently applied. Record the official source and date checked before relying on the answer.
- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Qualified Reviewer Bypass (High)** — Users treat AI output on legal and compliance questions as sufficient for decision-making without professional review. This is the failure mode the use case was designed to prevent — and it is most likely to occur when the AI answer sounds authoritative.

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
| AI Legal or Regulatory Advice Substitution | **Background** | State the exact Hong Kong regulatory question, organisation type, activity, date, and intended use. Treat the output as issue-spotting only. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| AI Legal or Regulatory Advice Substitution | **Instruction** | Identify the current official Hong Kong sources and the claims that require qualified professional confirmation. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| AI Legal or Regulatory Advice Substitution | **Rule** | Do not give legal advice, compliance clearance, or a final conclusion. Mark unresolved points `{QUALIFIED REVIEW REQUIRED}`. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| AI Blind Spot | **Instruction** | Identify assumptions, missing information, uncertainty, jurisdiction boundaries, authority limits, and items requiring confirmation by an official source, responsible owner, or appropriately qualified Hong Kong professional. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Output Format** | Add `Items requiring official or qualified confirmation` with `Issue`, `Current source`, `Source or reviewer needed`, and `Status`. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Reminder / Review Note** | This list is a review aid only. Current official Hong Kong sources and appropriately qualified reviewers must still confirm the answer before reliance or action. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Accountability Gap | **Output Format** | For each issue, show the official source, source date, responsible owner, qualified reviewer, unresolved assumption, and required next step. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| Jurisdiction and Scope Error | **Rule** | Keep Hong Kong requirements separate from any other jurisdiction. Do not combine them into one rule or assume that one satisfies another. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |
| Regulatory Currency Gap | **Instruction** | State the date checked and identify whether the ordinance, code, regulator guidance, threshold, office, or process may have changed. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |
| Qualified Reviewer Bypass | **Reminder / Review Note** | Do not use the AI answer as a substitute for the qualified or authorised reviewer required by the issue. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Ordinary human review is not enough. Final reliance requires qualified professional judgement and current authoritative sources.
- If sensitive data was already entered into an unapproved tool, output review cannot undo exposure. Escalate according to privacy / incident process.

---

## 12. Related Win.Win AI Essentials Items

- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before acting on a regulatory answer, verify it against current official HK sources and qualified review. Do not treat AI confidence as authority, compliance clearance, or professional accountability.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
