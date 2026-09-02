---
title: Draft Internal Memos
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC03
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft Internal Memos

## 1. What This Use Case Is

Use this page when you want AI to help with: **Draft internal memos, internal communications, and administrative notices**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Generally approved**.
- Human review needed: **Yes — sender responsible for accuracy**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

An internal memo may turn discussion, a provisional proposal, or an unresolved issue into an apparently approved decision. If staff act on that wording, the organisation may create commitments, disputes, or implementation work before the responsible authority has actually decided the matter.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Identify every decision or position stated as agreed, approved, or concluded in the memo.
2. For each, confirm: who has authority to make this decision, and did they formally make it?
3. Remove or qualify any statement that implies agreement where only discussion has occurred.
4. Confirm the distribution list is appropriate for the content — not wider than the decision warrants.

---

### 3.2 Before You Approve — One Check

> **Has the person authorising this memo confirmed that every decision, policy change, and organisational position stated in it has been formally approved — not merely discussed?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.13 AI Blind Spot|AI Blind Spot]]:** Whether the output fits the real people, real situation, real authority, and real consequences behind the task, including tacit context the AI was not told and lived or professional judgement that cannot be fully reduced to a prompt.
  - **For this use case:** Check the memo against the actual internal audience, hierarchy, relationship history, recent decisions, distribution boundary, sender authority, and consequences of staff treating the wording as an official decision or instruction.
- **[[Human Review Risk Library#4.17 Authority Boundary Blindness|Authority Boundary Blindness]]:** Identify every statement that appears to decide, approve, refuse, promise, warn, commit, or state an official position. Confirm the actual decision owner and remove, qualify, or escalate wording that exceeds the sender’s authority.
- **[[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]]:** Where the user challenged a cautious or source-grounded answer, verify the disputed point against the current approved record or responsible owner. Do not treat the revised AI wording as safer merely because it agreed with the user.

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

- **Scope, authority, and feasibility review:** Check whether the memo accurately distinguishes information, proposal, recommendation, decision, approval, and required action, and whether the sender has authority for each.
  - Look for: A recommendation presented as a decision, an unauthorised commitment, or wording that makes optional action sound mandatory.
  - Timing: Before distribution.
  - Reviewer: Memo owner, decision owner, or authorised manager.

- **Privacy / data-boundary review:** Check the source, memo content, attachments, and distribution list for confidential, HR, personal, financial, pastoral, or restricted information.
  - Look for: Sensitive detail included without need, wrong distribution group, or a wider audience than the source permits.
  - Timing: Before prompting and before distribution.
  - Reviewer: Information owner, HR/privacy-aware reviewer, or authorised sender.

- **Source comparison review:** Compare decisions, status, owners, dates, conditions, and caveats with the approved record, meeting note, or source document.
  - Look for: Incorrect action owner, lost caveat, old decision status, or context filled in from memory.
  - Timing: Before distribution.
  - Reviewer: Source owner or person who knows the underlying decision.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.
- Escalate when a summary will influence decisions, approvals, funding, HR, legal, or governance action and the reviewer is not authorised or properly informed to confirm it.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Generally approved**.
- Confirm that the planned reviewer can complete the required human review: **Yes — sender responsible for accuracy**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Authority Signal Misread and User-Pressure Drift

**Prompt focus:** Before prompting, give the AI the memo purpose, audience, sender authority, approved decision status, confidential boundaries, distribution limits, and what has not yet been decided. Instruct it not to accept user pressure toward firmer wording unless supported by an approved decision or responsible owner.

**Human review focus:** The reviewer should check whether the memo sounds like a decision, promise, warning, or official position beyond what has been approved. Confirm distribution scope, internal sensitivities, and any AI revision made after a user challenge.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the memo touches recent decisions, internal tension, hierarchy, personnel history, or matters requiring a reviewer with organisational standing.

**Do not rely only on:** professional tone. A memo can sound clear and official while implying authority or approval that does not exist.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Email / Announcement Draft
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter

---

## 8. Main Risks

- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: [[Human Review Risk Library#4.17 Authority Boundary Blindness|Authority Boundary Blindness]] (High)** — Internal memos are read as organisational decisions by staff who receive them. AI drafts memos in authoritative declarative style because that is the format. The authority implied by the style is independent of whether authority actually exists. A discussion becomes a decision, an option becomes a commitment, a proposal becomes a policy — not because anyone intended it, but because the memo format implies finality. A reviewer who checks for professionalism rather than for accuracy of stated authority will not catch this.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]] (Medium)** — If a user confidently challenges a cautious answer, AI may soften or reverse the answer without new reliable evidence. Agreement with the user is not verification.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Authority Signal Misread (High)** — AI may not understand how staff interpret hierarchy, tone, timing, and implied instruction. A memo can sound like a decision, promise, warning, or management position that was not actually authorised.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Confidential Content Exposure (High)** — Internal does not mean low-sensitivity. Memos may contain HR matters, financial information, or policy-sensitive content. AI processing of this content may expose it beyond its intended boundary.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Distribution Scope Error (Medium)** — AI should not be assumed to know the appropriate recipients unless current organisational roles, distribution rules, or relevant context are supplied. It may generate a document whose scope, language, or content is appropriate for one audience but distributed to a wider group through a routine process.
- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: Context Gap — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (Medium)** — AI has no knowledge of internal organisational history, prior decisions, or interpersonal dynamics. A memo that appears logically correct may be contextually wrong for the specific situation.

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
| Authority Boundary Blindness | **Instruction** | Label each material item as `Information`, `Proposal`, `Recommendation`, `Decision`, `Approved action`, or `Requires approval`, using only the supplied source. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]] |
| Authority Boundary Blindness | **Rule** | Do not write as if a proposal, recommendation, refusal, commitment, deadline, or organisational position has been authorised when it has not. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]] |
| AI Blind Spot | **Instruction** | Identify assumptions, missing information, uncertainty, authority limits, and items requiring human confirmation about decision status, hierarchy, confidential context, distribution, and likely staff interpretation. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Output Format** | Add `Items requiring owner confirmation` with `Issue`, `Current evidence`, `Decision or authority owner`, and `Status`. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Reminder / Review Note** | This list is a review aid only. A responsible internal reviewer must still check the memo against the actual organisation, people, authority, and consequences before circulation. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| User-Pressure Drift | **Rule** | Do not change decision status or source-grounded wording merely because the user challenges it without new approved evidence. Mark the disputed point `{VERIFY}` and identify the approved record or responsible owner needed to resolve it. | [[Prompt Enhancement Patterns#5.15 User-Pressure Drift Control\|User-Pressure Drift Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Authority Signal Misread | **Audience / Tone / Language** | Use wording that clearly reflects the actual status and sender authority. Avoid headings or commands that imply a stronger decision than exists. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |
| Confidential Content Exposure | **Rule** | Exclude or generalise personal, HR, pastoral, financial, legal, and other restricted details not necessary for the authorised audience. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]] |
| Distribution Scope Error | **Output Format** | Include a visible `Distribution` line and any circulation restriction supplied by the owner. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]]; [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]] |
| Context Gap | **Instruction** | List missing decisions, prior agreements, role boundaries, or current sensitivities that may change the memo and require owner confirmation. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.
- If sensitive data was already entered into an unapproved tool, output review cannot undo exposure. Escalate according to privacy / incident process.
- Human reviewers may fill gaps from memory; keep the source document visible and mark uncertain items explicitly.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Use Case Triage Scorecard.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Document Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — Meeting Notes Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before circulating an internal memo, check what the wording signals inside the organisation: authority, implied decisions, audience scope, current tensions, and whether the sender can stand behind it.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
