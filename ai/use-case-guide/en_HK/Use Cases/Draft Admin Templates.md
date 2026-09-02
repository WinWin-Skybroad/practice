---
title: Draft Admin Templates
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC20
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft Admin Templates

## 1. What This Use Case Is

Use this page when you want AI to help with: **Draft internal administrative documents, templates, or standard letters**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — review before sharing**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A reusable template can spread one unsupported retention period, authority statement, approval step, or contractual clause across many future records. Because the document looks complete and professional, the error may survive routine review and become embedded in the organisation’s normal process before it is compared with the approved policy or source.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. List every clause that creates an obligation, right, commitment, or data handling requirement.
2. For each clause, identify whether it must align with an internal policy, an HK ordinance, or an external requirement.
3. Check each clause against the relevant source document directly — not from memory.
4. Confirm the template will not be used across different contexts without a review step for each new context.

---

### 3.2 Before You Approve — One Check

> **Has every clause, requirement, and commitment in this template been checked against the organisation’s current internal policies and HK legal requirements — not just read for completeness and professional tone?**

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

- **Scope, authority, and feasibility review:** Confirm that the template supports the intended administrative task without creating new obligations, approvals, entitlements, deadlines, or organisational positions.
  - Look for: A reusable template that silently expands scope or becomes treated as an approved policy or contract.
  - Timing: Before the template is issued or reused.
  - Reviewer: Template owner, process owner, or authorised manager.

- **Qualified legal / compliance review:** Review any legal, employment, privacy, contractual, regulatory, or rights-related clause against current approved wording and qualified advice.
  - Look for: Invented clauses, outdated legal references, or generic wording that is unsuitable for Hong Kong or the organisation.
  - Timing: Before adopting a template with legal or compliance effect.
  - Reviewer: Qualified legal, HR, compliance, privacy, or relevant professional reviewer.

- **Privacy / data-boundary review:** Check that examples and placeholders do not contain real personal, confidential, HR, financial, pastoral, or restricted information.
  - Look for: A template preserving real data from the source example or encouraging unnecessary collection.
  - Timing: Before prompting and before publication.
  - Reviewer: Data owner, template owner, or privacy-aware reviewer.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.
- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights/obligation issues unless the reviewer is explicitly authorised and competent to confirm the matter under the approved process.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — review before sharing**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Long-Tail Template Propagation Risk

**Prompt focus:** Before prompting, give the AI the template purpose, user group, fields required, approval process, reuse context, and any data that must never be collected. Ask it to flag wording that could be reused outside the intended scope or require owner approval.

**Human review focus:** The reviewer should check whether the template could be reused in the wrong context, collect unnecessary data, imply approval, or create a flawed clause that repeats across future work.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the template may be reused across situations where authority, local exceptions, or future consequences differ.

**Do not rely only on:** one successful draft. A template error can propagate silently across many future uses.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Email / Announcement Draft
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter

---

## 8. Main Risks

- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Template Scope Creep (Medium)** — A reusable template can propagate one unsupported clause, field, or instruction across many later records. The error may become embedded in routine practice and remain unnoticed until a later review, complaint, or incident. Check that each reusable clause, consent statement, data field, instruction, and approval boundary reflects the organisation’s actual process and current requirements before the template is adopted.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.12 Operational Feasibility / Workflow|Operational Feasibility / Workflow]]: Long-Tail Template Propagation Risk (High)** — AI can produce a reusable template quickly, but it does not feel the future consequence of one flawed clause, missing field, or wrong instruction being reused for months. Test the template against realistic cases before adoption.
- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Legal Clause Error (High)** — Standard letters touching on contractual, liability, or regulatory matters may contain errors that create legal exposure. AI generates legally-formatted language without legal competence.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Outdated Legislative Reference (High)** — AI may reference superseded legislation, renamed regulatory bodies, or outdated policy versions. In HK, regulatory body names and ordinance titles change; AI training data may not reflect recent changes.

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
| Template Scope Creep | **Background** | State the exact administrative purpose, intended users, approved process, and matters the template must not decide or change. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Template Scope Creep | **Rule** | Use placeholders for approvals, dates, amounts, legal terms, and responsible roles unless approved wording is supplied. Do not create new obligations or policy positions. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Template Scope Creep | **Output Format** | Include a `Fields requiring owner approval` note and a visible template version/date field. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Template Scope Creep | **Instruction** | Follow the supplied approved template structure, heading order, field labels, and mandatory sections exactly. Flag any requested structural change for template-owner approval. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Long-Tail Template Propagation Risk | **Instruction** | Include template owner, version, approval date, review date, and a warning not to reuse superseded copies. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Long-Tail Template Propagation Risk | **Rule** | Do not present the template as permanently approved or suitable for new uses. Require re-review when the process, law, owner, audience, system, or intended use changes. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Legal Clause Error | **Rule** | Do not invent legal, employment, privacy, contractual, or compliance clauses. Mark missing approved wording as `{QUALIFIED REVIEW REQUIRED}`. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Legal Clause Error | **Instruction** | Identify any existing clause or statement that may create legal, employment, privacy, contractual, or compliance effect, and mark it for official-source or qualified review. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Outdated Legislative Reference | **Rule** | Use a legal or regulatory reference only when its current official wording and date are supplied or independently verified. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.
- Ordinary human review is not enough. Final reliance requires qualified professional judgement and current authoritative sources.
- If sensitive data was already entered into an unapproved tool, output review cannot undo exposure. Escalate according to privacy / incident process.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Use Case Triage Scorecard.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before approving a template, test it against realistic examples and edge cases. A fast draft may become long-term practice, so check fields, authority, wording, privacy, and exceptions before reuse.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
