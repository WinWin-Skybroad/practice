---
title: Summarise Meeting Notes
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC05
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Summarise Meeting Notes

## 1. What This Use Case Is

Use this page when you want AI to help with: **Summarise meeting notes or minutes into structured summaries**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Generally approved if non-confidential**.
- Human review needed: **Yes — check accuracy, attribution, and action owners**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A meeting summary may record a discussed or deferred item as approved, assign the wrong owner, omit a condition, or turn an open question into a decision. If teams act on the summary without comparing it with the original notes and the meeting’s actual authority, the organisation may make an unauthorised commitment or need to reverse work already started.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open the original meeting notes and the AI summary side by side.
2. For every decision, action item, and action owner in the summary, find the matching entry in the original notes and confirm the status, owner, and scope match exactly.
3. Pay particular attention to deferred items, conditional approvals, and any item where the meeting produced discussion but not a formal decision.
4. Do not review the summary from memory. The person who attended the meeting is the most likely to miss the errors, not the least.

---

### 3.2 Before You Approve — One Check

> **Has someone who attended this meeting compared every decision, action item, and action owner in this summary against the original notes — with the original document open, not from memory?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.2 Insider’s Blind Spot|Insider’s Blind Spot]]:** Compare every decision, caveat, action owner, due date, status, unresolved issue, and distribution boundary with the original notes or recording. Use the outsider test: the summary must make sense to a reader who was not in the meeting.
- **[[Human Review Risk Library#4.4 Automation Complacency|Automation Complacency]]:** Confirm that the same full source-comparison and approval standard is being applied even if earlier summaries were accurate. Assign a named reviewer and do not reduce checking because the workflow is routine.
- **[[Human Review Risk Library#4.8 Missing Context It Cannot Feel|Missing Context It Cannot Feel]]:** Check whether prior decisions, local constraints, relationship context, stakeholder sensitivities, data-quality concerns, or other missing facts could change the summary’s meaning, distribution, or required action. Decide whether to add safe context, keep reviewer-only notes, check with an owner, or escalate.
- **[[Human Review Risk Library#4.9 Earlier Context Silently Lost|Earlier Context Silently Lost]]:** Confirm that the immediate instructions and source packet still contain the meeting purpose, relevant prior decisions, terminology, exclusions, source limits, distribution rules, and approval boundaries. Compare the final summary with those requirements rather than relying on earlier chat context.
- **[[Human Review Risk Library#4.12 Approval Without Authority|Approval Without Authority]]:** Check every stated decision, approval, promise, commitment, obligation, deadline, refund, policy position, or public statement against the original notes and the actual decision owner. Reword recommendations or proposals that have been presented as approved decisions.

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

- **Source comparison review:** Compare every decision, proposal, objection, deferral, action owner, deadline, and approval status with the original notes and any approved prior-decision extract.
  - Look for: Discussion turned into agreement, wrong attribution, missing caveat, unclear owner resolved by guessing, or prior context imported without a source.
  - Timing: Before circulation or use as minutes.
  - Reviewer: Meeting chair, note-taker, or person accountable for the official record.

- **Human-grounded review:** Check whether the summary fits what the actual participants understood, including tacit agreements, relationship context, current sensitivities, and matters that were intentionally not finalised or circulated.
  - Look for: A textually plausible summary that insiders know is misleading, incomplete, insensitive, or inconsistent with how the meeting actually operated.
  - Timing: Before circulation.
  - Reviewer: Meeting owner or participant with sufficient context and standing.

- **Privacy / data-boundary review:** Decide what sensitive, HR, pastoral, beneficiary, financial, or confidential content may appear in each version and audience.
  - Look for: Restricted detail carried into a board, staff, volunteer, or public summary without an authorised reason.
  - Timing: Before prompting and before each version is circulated.
  - Reviewer: Information owner, meeting chair, HR/privacy-aware reviewer, or authorised manager.

- **Scope, authority, and feasibility review:** Confirm that the summary does not turn a recommendation or discussion into an authorised decision or commitment.
  - Look for: Approval without authority, implied budget approval, or action assigned beyond the named owner’s role.
  - Timing: Before the summary is treated as an official record or instruction.
  - Reviewer: Decision owner, meeting chair, or authorised approver.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when a summary will influence decisions, approvals, funding, HR, legal, or governance action and the reviewer is not authorised or properly informed to confirm it.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Generally approved if non-confidential**.
- Confirm that the planned reviewer can complete the required human review: **Yes — check accuracy, attribution, and action owners**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Tacit Agreement Gap

**Prompt focus:** Before prompting, give the AI the meeting purpose, audience for the summary, decision rules, action-owner format, approval process, and whether unresolved items must stay unresolved. Ask it to mark assumptions about decisions, approvals, objections, deferrals, and action ownership.

**Human review focus:** The reviewer should check every decision, action owner, deadline, objection, deferral, and approval status against the notes. Do not let AI turn discussion into agreement or silence into approval.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the summary depends on whether discussion, agreement, objection, deferral, or formal approval was actually reached.

**Do not rely only on:** meeting-summary neatness. A clean action list can hide unresolved disagreement or unapproved decisions.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Meeting Notes Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter

---

## 8. Main Risks

- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: [[Human Review Risk Library#4.2 Insider’s Blind Spot|Insider’s Blind Spot]] (High)** — The person reviewing an AI-generated meeting summary was in the room. They know what was meant, what was agreed, and what the context was. When the AI drops a caveat or overstates a conclusion, the reviewer unconsciously corrects it from memory — because they know what should be there. The summary passes their review. The error remains for every other reader who was not in the meeting and has no memory to fill the gaps. This is not a failure of attention. It is a predictable failure of position: the person best placed to review the summary is the person least able to see its errors.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: Tacit Agreement Gap — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (High)** — AI may not distinguish discussion, support, objection, deferral, and formal approval unless the notes are explicit. People in the room may remember the difference, but the summary must be checked against the record.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Confused Attribution (High)** — AI may swap names or attach an action item to the wrong person, especially if names are similar or the discussion was fast-paced. A reviewer who recognises the names may skim past the error.
- **Pastoral / Theological / Scripture: Data Boundary Crossing (High)** — A single meeting often contains public updates, internal operational matters, and sensitive pastoral/theological or HR items in the same notes. AI may not classify these safely or consistently according to the intended audience and access boundary. A summary intended for wide distribution may include items that should only go to specific people.
- **Pastoral / Theological / Scripture: Sensitive Detail Without Anchor (High)** — If personal, pastoral/theological, or confidential details were withheld from the AI prompt, a named person must add them back manually into the correct version for the appropriate audience. Without a prior record of what was withheld and who owns that step, this responsibility disappears.
- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: Context Gap from Prior Meetings — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (Medium)** — AI only knows what was in the current prompt. It has no awareness of decisions made in previous meetings. A summary may be technically accurate for this meeting but misleading without prior context.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: [[Human Review Risk Library#4.12 Approval Without Authority|Approval Without Authority]] (High)** — A reviewer may be able to check whether the summary matches the notes, but still lack authority to approve the decision, commitment, governance action, or public communication implied by the summary.
- **[[Risk Taxonomy#3.12 Operational Feasibility / Workflow|Operational Feasibility / Workflow]]: [[Human Review Risk Library#4.4 Automation Complacency|Automation Complacency]] (Medium)** — When meeting summaries are generated repeatedly, reviewers may gradually stop checking every decision, action owner, and deferred item against the original notes because previous AI summaries seemed reliable.
- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: [[Human Review Risk Library#4.8 Missing Context It Cannot Feel|Missing Context It Cannot Feel]] (High)** — Important context such as prior decisions, informal constraints, stakeholder sensitivities, or other facts may be absent from the notes, prompt, or review basis. The reviewer must determine whether that missing context changes the summary’s suitability, meaning, risk, or required handling, and whether it should be added safely, kept in reviewer-only notes, checked with the appropriate owner, or escalated.
- **[[Risk Taxonomy#3.3 Context / Nuance / Compression|Context / Nuance / Compression]]: [[Human Review Risk Library#4.9 Earlier Context Silently Lost|Earlier Context Silently Lost]] (High)** — In a long chat used for multiple meeting summaries, users may rely on a decision, constraint, approval boundary, or source limit stated much earlier. If it is not still present in the immediate instructions or source material used for the summary, the later output may omit or contradict it.

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
| Insider’s Blind Spot | **Instruction** | Separate `Confirmed decisions`, `Proposals or discussion`, `Deferred or unresolved items`, and `Actions`. Include caveats and source-note references so an outsider can understand the status. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| Insider’s Blind Spot | **Rule** | Do not rely on shared memory or assume that silence meant agreement. Mark unclear status, owner, deadline, or meaning `{VERIFY}`. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Tacit Agreement Gap | **Instruction** | Flag items that may depend on an unwritten shared understanding and require participant or meeting-owner confirmation. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]] |
| Confused Attribution | **Output Format** | For every action or statement that matters, show the named speaker or owner, source-note reference, deadline, and verification status. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]] |
| Data Boundary Crossing | **Rule** | Do not include sensitive HR, pastoral, beneficiary, financial, or confidential details in a wider-circulation version. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]] |
| Context Gap from Prior Meetings | **Rule** | Do not import a prior decision, constraint, or action unless the approved prior source is included under Content. | [[Prompt Enhancement Patterns#5.12 Earlier Context Continuity Control\|Earlier Context Continuity Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Automation Complacency | **Reminder / Review Note** | Check every new summary against its own notes even when previous AI summaries were correct. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Missing Context It Cannot Feel | **Instruction** | List relevant local realities, hidden assumptions, missing constraints, stakeholder sensitivities, or other facts that may be absent and could change how the summary should be handled. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| Earlier Context Silently Lost | **Background** | Restate current source limits, excluded content, distribution boundaries, decision status rules, and approval limits in the immediate prompt used for this summary. | [[Prompt Enhancement Patterns#5.12 Earlier Context Continuity Control\|Earlier Context Continuity Control]] |
| Approval Without Authority | **Rule** | Do not label a proposal, recommendation, discussion, or pending item as approved unless the notes and authorised decision record support it. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Sample Prompt

For a full use-case-specific worked example, open [[Summarise Meeting Notes Sample Overall Prompt]]. It is listed next to this use case in the Full Use-Case Library.

The sample shows how the **Meeting Notes Summary** base prompt pattern from `HK Safe AI Use Pack and Prompt Pattern Library.md` can be combined with the default add-ons and risk add-ons above.

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
- AI Usage Policy - Church.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Document Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — Meeting Notes Summary
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Red Lines Quick Reference.md

---

## 14. Final Reminder

Before approving meeting-note summaries, check decisions, action owners, deadlines, deferred items, objections, unresolved questions, distribution boundaries, and whether any assumed agreement was actually approved.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
