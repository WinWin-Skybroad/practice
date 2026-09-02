---
title: Summarise Documents
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC04
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Summarise Documents

## 1. What This Use Case Is

Use this page when you want AI to help with: **Summarise documents, reports, board papers, or committee papers**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Generally approved if non-confidential**.
- Human review needed: **Yes — verify against original**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A summary may omit a deadline, exception, escalation clause, financial condition, minority view, or unresolved issue while still sounding balanced and complete. If decision-makers rely on the summary instead of checking the original, the organisation may miss a response window, accept an unintended obligation, or overlook a material limitation.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open the source document and the summary side by side. Keep the source visible throughout review.
2. For every conclusion, decision, or obligation in the summary, find the corresponding passage in the source and confirm the summary preserves the same conditions and scope.
3. Check specifically for: dropped deadlines, softened conditions, merged exceptions, and provisional decisions stated as final.
4. Do not review the summary without the source document open. Memory-based review will not catch compression errors.

---

### 3.2 Before You Approve — One Check

> **Has someone checked this summary against the original document to confirm that no condition, deadline, exception, qualification, or limitation has been dropped, softened, or merged into a general statement?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.3 Reliability Illusion|Reliability Illusion]]:** Compare this summary with the current source version, current audience, intended use, source limits, and present risk each time it is produced. Do not reduce review because earlier summaries from the same prompt or tool were accurate.

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

- **Source comparison review:** Compare the summary with the exact source version and preserve the source’s meaning, caveats, exceptions, uncertainty, status, minority views, and unresolved issues.
  - Look for: A shorter but materially different account, deliberate ambiguity resolved by AI, or conclusions stronger than the source.
  - Timing: Before circulation or decision use.
  - Reviewer: Document owner, subject owner, or reviewer who understands the source context.

- **General output review:** Check whether the summary serves the stated audience and purpose without overemphasising selected points or omitting information important to the intended use.
  - Look for: A summary that is faithful sentence by sentence but gives the wrong overall emphasis for the decision or audience.
  - Timing: Before approval.
  - Reviewer: Summary owner or decision owner.

- **Privacy / data-boundary review:** Check whether confidential or restricted material from the source is reproduced, widened to a new audience, or included beyond what the summary needs.
  - Look for: Sensitive details, appendices, personal information, or confidential caveats included in a broader-circulation version.
  - Timing: Before prompting and before circulation.
  - Reviewer: Information owner or authorised document owner.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when a summary will influence decisions, approvals, funding, HR, legal, or governance action and the reviewer is not authorised or properly informed to confirm it.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Generally approved if non-confidential**.
- Confirm that the planned reviewer can complete the required human review: **Yes — verify against original**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Deliberate Ambiguity Loss

**Prompt focus:** Before prompting, give the AI the document purpose, audience for the summary, what must be preserved, and instructions to retain caveats, conditions, deadlines, minority views, unresolved items, and deliberately vague language. Ask it to mark uncertain or ambiguous points instead of resolving them.

**Human review focus:** Compare the summary with the source. Check whether compression removed important caveats, conditions, exceptions, deadlines, uncertainty, minority views, or deliberately vague language.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the source contains deliberate ambiguity, caveats, conditions, exceptions, minority views, or limits that may be compressed away.

**Do not rely only on:** clarity alone. A clearer summary can be worse if it removes ambiguity that was intentional or important.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Document Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A

---

## 8. Main Risks

- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: Compression Error (High)** — Summarisation removes detail by design. It may omit qualifications, conditions, hedging language, deadlines, or minority positions that materially affect meaning. A shorter summary can therefore hide the conditions that made a decision provisional, the caveats that limited an approval, or the deadlines that made inaction costly. Omitted conditions can cause an organisation to miss a deadline, accept an unintended obligation, or act without understanding a material limitation.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: Deliberate Ambiguity Loss (High)** — AI may turn intentionally cautious, provisional, or politically negotiated wording into a cleaner summary that loses the ambiguity the source deliberately preserved.
- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: Selective Emphasis (Medium)** — AI may emphasise points that appear statistically or linguistically prominent rather than those that are organisationally most important. Summary readers may prioritise the wrong information.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Confidential Content Widened (High)** — Board papers and committee papers are typically restricted distribution. A summary may be circulated more widely than the source. Sensitive financial, personnel, or strategic content may reach unintended audiences.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Loss of Nuance (High)** — Hedging language, conditional approvals, and provisional decisions in source documents are smoothed out in AI summaries. The summary may present a provisional decision as final or a conditional approval as unconditional.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Compounding AI Error (High)** — If the document being summarised was itself AI-generated and contains hallucinations or errors, AI summarisation inherits and may amplify those errors. The human reviewer sees two layers of AI output as if they were primary source material.
- **[[Risk Taxonomy#3.1 Accuracy / Hallucination|Accuracy / Hallucination]]: [[Human Review Risk Library#4.3 Reliability Illusion|Reliability Illusion]] (Medium)** — A document-summary prompt may work well many times, but that history does not prove the next summary has preserved today’s caveats, deadlines, source limits, or obligations. Each summary still needs source comparison.

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
| Compression Error | **Instruction** | Preserve the source’s key conclusions, caveats, exceptions, uncertainty, decision status, unresolved issues, and important supporting reasons. | [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]] |
| Compression Error | **Rule** | Do not resolve ambiguity, remove a condition, merge different positions, or make the source more certain than it is. | [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]] |
| Compression Error | **Output Format** | Include `Key points`, `Caveats and exceptions`, `Unresolved or disputed items`, and `Items omitted because of scope or sensitivity`. | [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Selective Emphasis | **Instruction** | Use the stated purpose and audience to identify what is important, while listing material points that were excluded or shortened. | [[Prompt Enhancement Patterns#5.13 Materiality Control\|Materiality Control]]; [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]] |
| Confidential Content Widened | **Rule** | Do not include restricted details in a version intended for a wider audience. Mark where an authorised owner must decide what may be shared. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]] |
| Compounding AI Error | **Rule** | Summarise the original approved source, not an earlier AI summary, paraphrase, or memory of the document. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Reliability Illusion | **Reminder / Review Note** | Compare every new summary with its own source. Do not reduce the review because previous summaries were accurate. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Sample Prompt

For a full use-case-specific worked example, open [[Summarise Documents Sample Overall Prompt]]. It is listed next to this use case in the Full Use-Case Library.

The sample shows how the **Document Summary, Boundary Setter, and Source-Grounded Q&A** base prompt patterns from `HK Safe AI Use Pack and Prompt Pattern Library.md` can be combined with the default add-ons and risk add-ons above.

In the sample:

- **bold text** is the base prompt content from `HK Safe AI Use Pack and Prompt Pattern Library.md`.
- *italic text* is the use-case prompt enhancement from this page.
- plain text is scenario-specific content supplied by the user.

---

## 12. Other Mitigation

- Human reviewers may fill gaps from memory; keep the source document visible and mark uncertain items explicitly.

---

## 13. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Use Case Triage Scorecard.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Document Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — Meeting Notes Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Red Lines Quick Reference.md

---

## 14. Final Reminder

Before circulating a summary, compare it with the source for caveats, exceptions, provisional language, minority views, deadlines, figures, unresolved questions, and any ambiguity that must not be smoothed away.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
