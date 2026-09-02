---
title: Answer Internal FAQs
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC07
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Answer Internal FAQs

## 1. What This Use Case Is

Use this page when you want AI to help with: **Answer internal FAQs from approved documents**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Generally approved**.
- Human review needed: **Yes — responsible person reviews before sharing**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

An internal FAQ answer may accurately summarise the general rule while missing an exception that applies to a particular person, contract, grade, location, or circumstance. If staff rely on that general answer, they may make requests or decisions on the wrong basis, and the organisation may need to correct records, expectations, or earlier communications.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open the approved policy or FAQ source document alongside the AI answer.
2. Identify which section of the source the answer draws from.
3. Check whether the person’s specific situation — contract type, tenure, grade, location — changes the answer from the general case.
4. Confirm the source document is the current approved version.

---

### 3.2 Before You Approve — One Check

> **Does this answer apply specifically to this person’s situation, contract type, and current policy — not just to the general case described in the source document?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]]:** Where the user challenges the answer, verify the disputed point against the current approved FAQ, policy, handbook, authoritative record, or responsible owner. Do not treat an AI concession as evidence that the revised answer is correct.

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

- **Source comparison review:** Compare the answer with the exact current FAQ, policy, handbook, or approved document section that governs the question. Preserve eligibility conditions, exceptions, qualifiers, and version status.
  - Look for: An answer that is generally consistent but misses a contract type, location, grade, tenure, exception, or wording that changes the result.
  - Timing: Before the answer is shared.
  - Reviewer: Document owner, policy owner, or person who knows the approved source.

- **Source and fact verification:** Verify names, dates, amounts, contacts, links, and other factual details against the current approved record.
  - Look for: Outdated contacts, wrong dates or amounts, invented details, and claims not supported by the named source.
  - Timing: Before the answer is shared.
  - Reviewer: Source-checking reviewer or responsible internal owner.

- **Scope, authority, and feasibility review:** Confirm that the response explains the approved general rule without making an individual decision, granting an exception, or creating a commitment.
  - Look for: Wording that sounds like approval, entitlement, refusal, promise, or a new policy interpretation.
  - Timing: Before the answer is sent to the person asking.
  - Reviewer: Policy owner, HR/operations owner, or authorised responsible person.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Generally approved**.
- Confirm that the planned reviewer can complete the required human review: **Yes — responsible person reviews before sharing**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Local Exception Blindness

**Prompt focus:** Before prompting, give the AI the exact approved FAQ or source document, the intended audience, the current document version, and any known limits on what the FAQ is allowed to answer. Ask it to identify likely local exceptions, source gaps, version issues, and items that need confirmation by the responsible owner.

**Human review focus:** The reviewer should check whether the answer matches current practice, not only the written FAQ. Confirm informal handling rules, exceptions, document-version issues, and unanswered policy gaps with the responsible owner before sharing.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the answer may depend on relevant context that is absent from, incomplete in, or not adequately represented in the task basis, including informal practice, local exceptions, current approved records, or handling knowledge held by staff.

**Do not rely only on:** the written FAQ alone. A technically correct answer can still be wrong if current practice, local exception, or owner approval says otherwise.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- HK Safe AI Use Pack and Prompt Pattern Library.md — Answer a Policy Question
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter

---

## 8. Main Risks

- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Hallucination Beyond Source (High)** — AI may answer confidently from general model knowledge when the approved source does not contain a direct answer for the specific situation. Because source-grounded and unsupported wording can look equally fluent, the reader may not notice the difference. A general answer may therefore give the wrong entitlement, process, exception, or next step for the actual case and create inconsistent treatment or correction work.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]] (Medium)** — If a user confidently challenges a cautious answer, AI may soften or reverse the answer without new reliable evidence. Agreement with the user is not verification.
- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: Local Exception Blindness — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (High)** — AI may answer from the approved FAQ while missing an unwritten exception, informal practice, or local handling rule that staff know but the document does not state. A responsible owner must confirm whether the answer matches actual current practice before sharing.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Document Version Confusion (High)** — An AI system must not be relied on to distinguish current from outdated policy documents unless it is explicitly constrained to approved current sources. If an older document version is in the prompt alongside a newer one, AI may draw on both without flagging the conflict.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Overconfident Answer to Uncertain Question (High)** — AI may give a definitive answer to a question the policy document does not actually settle. Users receive a confident response and do not seek clarification from a qualified person.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Scope Creep (Medium)** — A user asks a question that extends beyond the approved document scope and the AI answers anyway, drawing on general knowledge. The boundary between ‘from approved documents’ and ‘general AI knowledge’ is invisible to the user.

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
| Hallucination Beyond Source | **Instruction** | Answer from the current approved FAQ, policy, handbook, or source document supplied under Content. Identify the exact section supporting each material part of the answer. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Hallucination Beyond Source | **Rule** | If the source does not answer the person’s specific situation, state `{NOT FOUND IN SOURCE}` and do not infer an answer from general knowledge. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Hallucination Beyond Source | **Output Format** | Separate the response into `Answer supported by source`, `Source section`, and `Items requiring owner confirmation`. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| User-Pressure Drift | **Rule** | Do not change the answer merely because the user insists. Revise it only when a supplied source, authoritative record, or responsible owner supports the correction. Mark an unsupported challenge `{VERIFY}` and identify the source or owner needed to resolve it. | [[Prompt Enhancement Patterns#5.15 User-Pressure Drift Control\|User-Pressure Drift Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Local Exception Blindness | **Instruction** | Apply only exceptions supplied for the relevant role, location, contract type, tenure, grade, or situation. Flag any possible local exception that is not confirmed. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Local Exception Blindness | **Reminder / Review Note** | Confirm with the current policy or process owner whether an unwritten local practice, exception, or recent change affects the answer before it is used. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Document Version Confusion | **Rule** | Use only the named current version. Do not combine wording from earlier drafts, superseded policies, or remembered answers. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Overconfident Answer to Uncertain Question | **Output Format** | Show what is answered, what is not answered, and what must be checked with the responsible owner. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Scope Creep | **Rule** | Provide a source-grounded FAQ response only. Do not make an individual decision, grant an exception, or promise an outcome. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.
- Human reviewers may fill gaps from memory; keep the source document visible and mark uncertain items explicitly.
- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Use Case Triage Scorecard.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A

---

## 13. Final Reminder

Before sharing an FAQ answer, check not only whether it quotes the approved source, but whether any local exception, informal practice, or current handling rule changes the answer. If the AI was not told that context, the responsible owner must add it or stop the answer.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
