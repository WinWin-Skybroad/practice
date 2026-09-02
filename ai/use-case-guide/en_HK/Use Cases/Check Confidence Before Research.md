---
title: Check Confidence Before Research
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC13
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Check Confidence Before Research

## 1. What This Use Case Is

Use this page when you want AI to help with: **Check confidence and uncertainty before a research task**.

- Common users: **Individuals, churches, nonprofits, SMEs**.
- Approval level: **Approved as a thinking aid**.
- Human review needed: **Yes — especially before research or high-risk use**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A detailed research answer may list schemes, policies, deadlines, or official positions that are incomplete, outdated, or no longer applicable. If the organisation treats detail and confidence as evidence of currency, it may spend time or money preparing work on the wrong basis before checking the current official source.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. List every named scheme, policy, eligibility criterion, and official body in the output.
2. Go directly to the official government or regulatory website for each one. Do not use the AI output as the reference.
3. Check the effective date of any policy or scheme information.
4. Treat AI research as a list of things to verify, not a verified list of facts.

---

### 3.2 Before You Approve — One Check

> **Has each named scheme, policy, or official position in this output been verified directly against the official government or regulatory website before any planning, preparation, or expenditure is committed?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]]:** Check whether the confidence assessment has correctly identified the relevant Hong Kong or other jurisdiction, sector, organisation, population, language, and current source requirements. Seek local or specialist input where the reviewer cannot judge the boundary.

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

- **General output review:** Check whether the proposed research question, scope, audience, and intended decision match the real need before research begins.
  - Look for: A confident plan for the wrong question, an undefined audience, or a scope too broad to answer responsibly.
  - Timing: Before research starts.
  - Reviewer: Research owner or person responsible for the decision the research will support.

- **Source and fact verification:** Verify any preliminary facts, definitions, dates, jurisdiction assumptions, or baseline claims used to set the research direction.
  - Look for: An early unsupported assumption becoming the foundation of the whole research task.
  - Timing: Before the research plan or search terms are approved.
  - Reviewer: Researcher, subject owner, or source-checking reviewer.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.
- Escalate legal, medical, financial, technical, or public translation when the reviewer is not qualified or authorised to confirm the specialist meaning.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Approved as a thinking aid**.
- Confirm that the planned reviewer can complete the required human review: **Yes — especially before research or high-risk use**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Wrong Question Confidence

**Prompt focus:** Before prompting, give the AI the research question, jurisdiction, audience, intended use, date sensitivity, and what source types count as acceptable. Ask it to state assumptions, possible reframings, and what information would change the research direction.

**Human review focus:** The reviewer should check whether the research question itself is complete and correctly framed. Do not rely on confident wording; verify uncertainty, source quality, currentness, and whether a qualified person should review the answer.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the research question may be incomplete, wrongly framed, jurisdiction-specific, or dependent on context the prompt did not state.

**Do not rely only on:** confidence. A confident answer to the wrong or incomplete question is still unsafe.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Pre-Task Calibration
- HK Safe AI Use Pack and Prompt Pattern Library.md — Hallucination Check

---

## 8. Main Risks

- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Metacognitive Overconfidence (High)** — AI may not reliably indicate when its Hong Kong-specific coverage is incomplete or outdated. A detailed, confident answer does not establish that the underlying information is current or complete. Checking confidence before research does not resolve the gap; it helps identify what needs external verification. Check current official or authoritative sources before acting on HK-specific claims.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: Wrong Question Confidence (High)** — AI may confidently answer the question asked while a careful human would first notice that the question is incomplete, wrongly framed, or missing a decisive local constraint.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Scope Misjudgement — related review risk: [[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]] (High)** — AI may rate a task as straightforward when the HK-specific, cultural, or domain-specific complexity puts it beyond the model’s actual knowledge. The user proceeds with false confidence that the task is within AI capability.

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
| Metacognitive Overconfidence | **Instruction** | Rate confidence separately for the question, scope, available evidence, terminology, and expected answer. Explain the evidence and assumptions behind each rating. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Metacognitive Overconfidence | **Output Format** | List `Known`, `Assumed`, `Unknown`, `Needs current source`, and `Could change the research direction`. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Metacognitive Overconfidence | **Rule** | Treat the confidence assessment as a review aid only. Do not present the categories or unknowns list as proof that every relevant gap, assumption, or missing factor has been found. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Wrong Question Confidence | **Instruction** | Restate the decision or purpose behind the research, identify alternative interpretations of the question, and ask which one should be confirmed before research begins. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Scope Misjudgement | **Instruction** | Define the relevant geography, time period, population, sector, jurisdiction, language, and intended use. Mark any unresolved boundary as `{VERIFY}`. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.
- Fluent text can hide meaning drift; bilingual review must compare source and target, not just read the target.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Bilingual Draft (English + Traditional Chinese)
- HK Safe AI Use Pack and Prompt Pattern Library.md — Calibrated Research (HK)
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A

---

## 13. Final Reminder

Before starting research, check whether the question itself is good enough. Ask what the AI was not told, what local or current context could change the answer, and whether a human expert would ask for clarification first.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
