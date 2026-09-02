---
title: Answer Policy Questions
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC08
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Answer Policy Questions

## 1. What This Use Case Is

Use this page when you want AI to help with: **Answer policy questions from existing policy documents**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — no legal interpretation without qualified review**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A policy answer may rely on a broad clause while overlooking a more specific requirement, exception, or approval condition elsewhere in the same document. If the answer is treated as authoritative without reading the applicable section directly, the organisation may skip a required step, give inconsistent guidance, or act outside the approved policy.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open the policy document to the section the AI answer references.
2. Read that section directly. Do not rely on the AI’s summary of it.
3. Check whether the specific situation — age group, activity type, duration, location — has a different rule from the general case.
4. If the policy is silent or ambiguous on the specific situation, treat it as unanswered and escalate.

---

### 3.2 Before You Approve — One Check

> **Has the specific policy section that applies to this exact situation been read directly — not summarised by AI — and confirmed to require or not require this step?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]]:** Check whether local practice, approved exceptions, prior owner decisions, relationship context, current sensitivities, or other unwritten information could change the answer or its handling. Confirm that safe context was included and that sensitive or difficult-to-write context was considered by the policy owner outside the AI interaction.
- **[[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]]:** If the user pushed for a different answer, check the disputed point against the current approved policy, authoritative record, or policy owner. Do not accept the AI’s revised answer merely because it became more agreeable or definite.
- **[[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]]:** Confirm the exact organisation, sector, jurisdiction, current policy version, and authority owner. Check whether the answer changes under Hong Kong law, local organisational practice, or a specific exception route.

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

- **Source comparison review:** Read the exact current policy section and compare the answer with its wording, definitions, exceptions, and stated authority.
  - Look for: A general rule applied to the wrong situation, omitted exceptions, or a silent policy gap presented as an answer.
  - Timing: Before the answer is relied on or shared.
  - Reviewer: Policy owner or person authorised to interpret the internal policy.

- **Qualified legal / compliance review:** Where the answer affects legal rights, obligations, employment, privacy, safety, or compliance, verify the issue against current official sources and obtain qualified review.
  - Look for: The policy answer being presented as legal advice, a compliance conclusion, or a statement of law.
  - Timing: Before action is taken on a legal or compliance-sensitive answer.
  - Reviewer: Qualified legal, compliance, privacy, HR, or relevant professional reviewer.

- **Scope, authority, and feasibility review:** Confirm who has authority to decide when the policy is silent, ambiguous, or requires an exception.
  - Look for: AI filling a policy gap, inventing an approval route, or presenting an interpretation as an authorised decision.
  - Timing: Before communicating a binding or individual outcome.
  - Reviewer: Policy owner, decision owner, or authorised manager.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights/obligation issues unless the reviewer is explicitly authorised and competent to confirm the matter under the approved process.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — no legal interpretation without qualified review**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Unwritten Context Gap and User-Pressure Drift

**Prompt focus:** Before prompting, give the AI the current policy text, exact situation, relevant audience, known authority limits, and any local practice or prior decision that may affect the answer. Instruct it not to accept user pushback unless the challenge is supported by the source material, an authoritative record, or a named responsible owner.

**Human review focus:** The reviewer should check whether the written policy is complete for the real situation. Look for exceptions, grandfathered arrangements, past decisions, current practice, or approval authority that the AI was not told. If the AI changed its answer after a challenge, re-check the source before trusting the revision.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the answer may depend on relevant context that is absent from, incomplete in, or not adequately represented in the task basis, including exceptions, prior decisions, grandfathered arrangements, local practice, current approved records, or a policy owner’s knowledge.

**Do not rely only on:** AI agreement with the user. A revised answer is not safer merely because it became more convenient or confident.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Answer a Policy Question
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A

---

## 8. Main Risks

- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: AI Legal Interpretation Risk (High)** — AI interprets policy text as it reads, not as it was intended. A general clause may be read as covering a specific scenario that the policy author intended to require a separate step for. In church and nonprofit contexts, policy questions frequently concern safeguarding, consent, and duty of care — areas where a wrong answer has direct consequence for vulnerable individuals, particularly children. An AI interpretation that substitutes for a direct policy reading is not a policy reading.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]] (Medium)** — If a user confidently challenges a cautious answer, AI may soften or reverse the answer without new reliable evidence. Agreement with the user is not verification.
- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (High)** — Important context may exist outside the written policy, such as established exceptions, grandfathered arrangements, past incidents, current practice, relationship context, or other knowledge held by people. Some of that context may be safe to add to the source or prompt; sensitive, confidential, or difficult-to-write context must instead be accounted for during human review.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Policy Gap Assumption (High)** — AI may fill gaps between policy provisions with plausible but unauthorised interpretations. Where the policy is silent, AI provides an answer rather than flagging that the policy does not address the question.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Currency of Policy (High)** — An AI answer must not be relied on to confirm whether the policy being queried is the current version in force. An answer based on a superseded policy may be technically accurate for the document provided but wrong for the current situation.
- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Jurisdiction Default Error — related review risk: [[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]] (High)** — For HK-specific policies, AI may default to non-HK precedent, UK common law, or Mainland Chinese regulatory interpretation when the policy is silent or ambiguous. HK operates under its own legal framework.

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
| AI Legal Interpretation Risk | **Instruction** | Answer the internal policy question from the supplied current policy text and identify the exact clause or section used. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| AI Legal Interpretation Risk | **Rule** | Do not present the policy answer as legal advice or a statement of law. Mark legal or compliance questions as `{QUALIFIED REVIEW REQUIRED}`. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| AI Legal Interpretation Risk | **Output Format** | Separate `Policy text`, `Application to the stated situation`, `Policy gaps or ambiguity`, and `Required owner or professional review`. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| User-Pressure Drift | **Rule** | Do not change the answer after user pushback unless new approved policy text, an authoritative record, or the policy owner supports the change. Mark an unsupported challenge `{VERIFY}` and identify the source or owner needed to resolve it. | [[Prompt Enhancement Patterns#5.15 User-Pressure Drift Control\|User-Pressure Drift Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Unwritten Context Gap | **Instruction** | Apply only relevant local practice, approved exceptions, and prior owner decisions that are accurate, necessary, permitted, current, and safe to include under Content. Flag context that may change the answer but has not been confirmed. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| Unwritten Context Gap | **Rule** | Do not treat missing local-practice or exception information as confirmation that no exception applies. Flag it for policy-owner confirmation. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| Policy Gap Assumption | **Rule** | If the policy is silent or ambiguous, say so. Do not invent a rule, exception, approval, or enforcement position. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |
| Currency of Policy | **Rule** | Use only the named current policy version and date. Flag any uncertainty about whether it has been superseded. | [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Jurisdiction Default Error | **Rule** | Do not import legal or policy assumptions from another jurisdiction. Use Hong Kong or the specified jurisdiction only when supported by the supplied source. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |
| Unwritten Context Gap | **Content** | Provide the current non-sensitive local practice, approved exceptions, prior policy-owner decisions, and safe general constraints relevant to the question. Keep confidential, personal, uncertain, or restricted context outside the AI interaction. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| Unwritten Context Gap | **Reminder / Review Note** | The policy owner must still account for sensitive, confidential, or difficult-to-write context outside the AI interaction before the answer is approved or shared. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Ordinary human review is not enough. Final reliance requires qualified professional judgement and current authoritative sources.
- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.
- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Use Case Triage Scorecard.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before relying on a policy answer, check whether the policy text is complete for this real situation. Ask whether there is any exception, past decision, local practice, or authority issue that the AI was not told.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
