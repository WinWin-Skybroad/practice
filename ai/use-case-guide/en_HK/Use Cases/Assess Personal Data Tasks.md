---
title: Assess Personal Data Tasks
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC22
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Assess Personal Data Tasks

## 1. What This Use Case Is

Use this page when you want AI to help with: **Assess whether a task involves personal data / PDPO pre-check**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Approved as a thinking aid**.
- Human review needed: **Yes — not a legal conclusion**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A personal-data task may appear acceptable when the prompt says that consent exists, while the actual collection purpose, notice, consent record, intended new use, tool, recipients, retention, or transfer arrangements tell a different story. A false AI clearance can lead the organisation to use or disclose data on the wrong basis and expose people to privacy, dignity, relationship, or reputational harm.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Identify the actual data, the original collection purpose, the notices or consent records provided to the people concerned, and the proposed AI-supported use.
2. Compare the proposed use with the original purpose and any directly related purpose. If the use may be new, unclear, or outside the recorded expectations, do not rely on the AI assessment.
3. Review the planned tool, account, access, storage, retention, disclosure, processor, and transfer arrangements against current approved policy and official guidance.
4. Treat the AI assessment as issue-spotting only. Escalate when the purpose, notice, consent, legal basis, exemption, data boundary, or required control is unclear.

---

### 3.2 Before You Approve — One Check

> **Has the accountable data owner compared this proposed use with the actual collection purpose, notices or consent records, tool and processing arrangements, and current official guidance — with qualified review where any point remains unclear?**

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

- **Privacy / data-boundary review:** Identify the actual data fields, people, purpose, AI tool, account, recipients, storage, access, retention, and any transfer outside Hong Kong before deciding whether the task may proceed.
  - Look for: Generic “low-risk” conclusions that ignore identifiers, combined data, vulnerable people, confidential context, or downstream recipients.
  - Timing: Before any data is entered and again before the output is used.
  - Reviewer: Privacy/data owner or person accountable for the dataset and task.

- **Tool / process governance review:** Confirm that the tool, account type, settings, vendor terms, workflow, and approval route are allowed for the identified data and purpose.
  - Look for: Use of personal accounts, training-enabled settings, unapproved integrations, unclear storage, or no named reviewer.
  - Timing: Before prompting.
  - Reviewer: Tool owner, privacy lead, governance owner, or authorised manager.

- **Qualified legal / compliance review:** Treat the AI assessment as a preliminary checklist, not a PDPO conclusion. Obtain qualified review where the data use, transfer, consent, notice, retention, or legal basis is unclear.
  - Look for: AI presenting a definitive compliance clearance without current legal or privacy review.
  - Timing: Before proceeding with an uncertain or higher-impact personal-data task.
  - Reviewer: Qualified privacy, legal, compliance, HR, or relevant professional reviewer.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Approved as a thinking aid**.
- Confirm that the planned reviewer can complete the required human review: **Yes — not a legal conclusion**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Privacy Harm and Consequence Blindness

**Prompt focus:** Give only the minimum non-sensitive task context needed to identify the data issue. State the original collection purpose, proposed use, audience, data categories, planned tool, intended output, and whether any personal or confidential data must remain outside the prompt. Ask the AI to mark purpose, notice or consent, sensitivity, processing, transfer, retention, and confirmation points as {VERIFY}.

**Human review focus:** The reviewer should check whether the task creates real privacy, confidentiality, consent, expectation, or data-boundary issues that AI cannot own. Escalate when personal data, confidential information, beneficiary data, pastoral/theological information, or sensitive organisational data is involved.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the data use may depend on people’s expectations, sensitivity, vulnerability, consent context, or the real-world harm of disclosure.

**Do not rely only on:** a neat classification. Privacy risk depends on real people, purpose, expectations, tool settings, and approval authority.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter

---

## 8. Main Risks

- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: False Privacy Clearance (High)** — Whether a personal-data task may proceed depends on the actual data, original collection purpose, proposed use, notices or consent records, people affected, tool and processing arrangements, current policy, and applicable official guidance. AI knows only what the prompt states and may fill missing context with assumptions. A confident clearance can therefore create a false sense that the task has been approved when important purpose, data-boundary, security, retention, disclosure, processor, or transfer questions remain unresolved.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: No Felt Weight of Real Harm (High)** — AI can classify data and purpose, but it does not feel the personal, relational, reputational, or dignity harm that misuse of someone’s data may cause. A human must judge the real impact before the task proceeds.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: PDPO Misinterpretation (High)** — AI may apply an incomplete or outdated privacy framework, overlook the actual collection and use context, or present issue-spotting as legal clearance. Check the current official position and obtain qualified review where the answer affects rights, obligations, sensitive data, or consequential use.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: External Processing and Transfer Blind Spot (High)** — A cloud or AI service may involve processing, storage, support access, subprocessors, or transfers outside the organisation or Hong Kong. AI may not identify the actual vendor, location, contract, security, retention, or accountability arrangements. Review the real service and current official guidance rather than relying on a general statement about cross-border processing.

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
| False Privacy Clearance | **Task** | Produce a preliminary personal-data risk checklist for the proposed AI task. Do not give final legal or compliance clearance. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| False Privacy Clearance | **Instruction** | List the data fields, people affected, purpose, tool/account, recipients, storage/access, retention, cross-border transfer, and unknowns that must be confirmed. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |
| False Privacy Clearance | **Rule** | Mark any missing fact or legal conclusion as `{VERIFY}` and do not label the task compliant, safe, anonymous, or low-risk without human confirmation. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| No Felt Weight of Real Harm | **Instruction** | Identify who could be affected if the data is exposed, misused, combined, misunderstood, or sent to the wrong person, and describe the practical consequence for review. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]]; [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| No Felt Weight of Real Harm | **Rule** | Use only the minimum personal or confidential information needed for the assessment. Do not reproduce unnecessary identifying detail. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]]; [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| PDPO Misinterpretation | **Rule** | Treat PDPO and privacy statements as issue-spotting only. Identify the official source or qualified reviewer needed. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |
| External Processing and Transfer Blind Spot | **Instruction** | State whether hosting, support access, processing, storage, or recipients may be outside Hong Kong. Mark unknown locations or access routes as `{VERIFY}`. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- If sensitive data was already entered into an unapproved tool, output review cannot undo exposure. Escalate according to privacy / incident process.
- A content review cannot fix the wrong tool, account, or data process. Fix the process before using the output.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before using AI for a personal-data task, check the real person-impact: consent, purpose, expectation, sensitivity, tool approval, and who could be harmed if the data or output is exposed or reused.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
