---
title: Check AI Output Reliability
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC12
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Check AI Output Reliability

## 1. What This Use Case Is

Use this page when you want AI to help with: **Check AI output reliability / hallucination risk**.

- Common users: **Individuals, churches, nonprofits, SMEs**.
- Approval level: **Approved as a thinking aid**.
- Human review needed: **Yes — use as a review aid, not final proof**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

An AI reliability check can repeat or reinforce the same unsupported claim found in the original AI output. If both outputs are treated as independent confirmation, a plausible but unverified statistic, citation, date, or conclusion may enter a report, policy, presentation, or decision before anyone checks a primary non-AI source.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Identify the specific claims being assessed for reliability.
2. For each claim, check it against a non-AI source: official HK government data, academic publication, or primary document.
3. Do not use one AI output to verify another AI output from the same model or model family.
4. Treat a positive AI reliability assessment as a starting point for human verification, not as verification itself.

---

### 3.2 Before You Approve — One Check

> **Has at least one specific claim in this output been verified against a non-AI source — an official document, government database, or primary reference — before the original output is treated as reliable?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.24 AI Self-Validation Illusion|AI Self-Validation Illusion]]:** Verify each material claim against an independent official source, original document, calculation, source record, approved tool, responsible owner, regulator, professional adviser, or other accountable reviewer outside the AI conversation. A second AI response is not independent verification.

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

- **Source and fact verification:** Break the output into material claims and verify each one against an independent source, original record, calculation, or responsible person outside the AI conversation.
  - Look for: Claims marked “verified” only because AI reviewed its own answer, repeated the same source, or expressed confidence.
  - Timing: Before relying on the reliability assessment.
  - Reviewer: Subject owner, source-checking reviewer, or person able to access independent evidence.

- **Tool / process governance review:** Confirm that the verification method is genuinely independent and that evidence, source versions, calculations, and reviewer decisions are recorded where needed.
  - Look for: A second prompt, second model, or AI critique being treated as independent proof when it uses the same unsupported basis.
  - Timing: Before the reliability check is accepted.
  - Reviewer: Review owner, governance owner, or person accountable for the verification process.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate before tool use when confidential data, third-party systems, financial processing, or automation is involved and the tool, account, reviewer, or process has not been approved for that use.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Approved as a thinking aid**.
- Confirm that the planned reviewer can complete the required human review: **Yes — use as a review aid, not final proof**.

---

## 6. AI Blind Spot Focus

**Risk focus:** AI Self-Validation Illusion

**Prompt focus:** Provide the output, source material, intended use, and required reliability check. Ask the AI to identify which claims, figures, dates, sources, calculations, or assumptions need independent verification, and what non-AI source or responsible reviewer should be used.

**Human review focus:** Do not treat AI self-checking as independent verification. Confirm the result against external sources, source documents, records, tools, or a responsible human reviewer before relying on it.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the reliability check depends on unstated assumptions, local source expectations, missing source context, or a reason the available record may not be complete. Use independent verification as the primary control for source-dependent claims.

**Do not rely only on:** another AI answer as proof. Trust increases only when the output is checked against an independent source, record, tool, or accountable person.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Hallucination Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A

---

## 8. Main Risks

- **[[Risk Taxonomy#3.5 Tool / Security / Process Governance|Tool / Security / Process Governance]]: Circular Validation (High)** — Using AI to check AI output can create a closed loop when both outputs rely on the same unsupported basis. A second AI response may repeat, reinforce, or reframe the original error rather than independently verify it. Break the evidential loop with source records, authoritative external evidence, independent calculations, approved non-AI tools, or other verification outside the unsupported AI basis. AI may help identify questions, but a responsible reviewer decides whether the independent evidence is sufficient before the output is relied on.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.24 AI Self-Validation Illusion|AI Self-Validation Illusion]] (High)** — Asking AI to judge whether AI is reliable can create false reassurance. A fluent self-check is not independent verification; source records, external evidence, or responsible person judgement must break the circle.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: False Reassurance (High)** — AI may rate its own output — or another model’s output — as reliable when it is not. The checking step gives the user confidence that is not warranted, making the overall output more dangerous, not less.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Unknown Unknown (High)** — AI cannot flag errors it does not know it has made. Hallucinations about topics outside the model’s training data, or in highly specialised domains, are the least likely to be self-detected and the most likely to be presented confidently.

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
| AI Self-Validation Illusion | **Instruction** | List each material claim and the independent source, record, calculation, approved tool, or responsible person needed to verify it outside this AI conversation. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Circular Validation | **Rule** | Do not label the output verified merely because you re-read it, criticised it, regenerated it, or compared it with another AI answer. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Circular Validation | **Output Format** | Use a table with `Claim`, `Evidence currently available`, `Independent verification needed`, and `Status`. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| AI Self-Validation Illusion | **Reminder / Review Note** | AI may help identify what to check, but a human must complete the independent verification. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| False Reassurance | **Rule** | Do not convert confidence, fluency, internal consistency, or absence of obvious errors into a reliability conclusion. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Unknown Unknown | **Instruction** | State assumptions, missing-information categories, scope limits, and plausible failure areas, while making clear that the list may not be complete. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- A content review cannot fix the wrong tool, account, or data process. Fix the process before using the output.
- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- Agent Approval Checklist.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Minimum Security Baseline for Agentic AI.md
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Do not let an AI reliability check become AI self-certification. Treat it as an issue-spotting aid only, then verify important claims against sources, records, or a reviewer with real accountability.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
