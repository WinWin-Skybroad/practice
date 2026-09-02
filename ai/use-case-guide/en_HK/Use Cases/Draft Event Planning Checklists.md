---
title: Draft Event Planning Checklists
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC19
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft Event Planning Checklists

## 1. What This Use Case Is

Use this page when you want AI to help with: **Draft event planning checklists and schedules**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Generally approved**.
- Human review needed: **Yes — before finalising**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A polished event checklist may omit a local dependency that was never included in the prompt, such as venue confirmation, access arrangements, a supplier hand-off, safeguarding coverage, accessibility, or a contingency owner. If announcements or commitments are made before someone with operational knowledge checks those dependencies, the event may require late changes, extra cost, or cancellation.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Compare the AI checklist against a previous checklist or event record for the same type of event.
2. Identify every step that depends on organisational knowledge not included in the approved source packet, such as venue systems, booking processes, specific contacts, budget approvals, or regulatory permissions.
3. Add missing steps manually before the checklist is used for planning.
4. Confirm that deadlines on the checklist match the actual lead times required by this organisation and its suppliers.

---

### 3.2 Before You Approve — One Check

> **Has someone with operational knowledge of this organisation — not just the checklist — confirmed that every site-specific, team-specific, booking, and approval step is present before this checklist is used for planning?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.21 Local Operational Memory Gap|Local Operational Memory Gap]]:** Check with an experienced organiser whether the checklist reflects how the venue, suppliers, staff, volunteers, approvals, setup, handovers, access, delivery, and closing normally operate, as well as past problems, workarounds, exceptions, and near misses.
- **[[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]]:** Check the checklist against current Hong Kong and venue-specific safety, licensing, insurance, accessibility, safeguarding, employment, food, privacy, and other applicable requirements. Obtain qualified or responsible-owner confirmation where needed.

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

- **Scope, authority, and feasibility review:** Check the checklist against the actual event, venue, date, audience, capacity, owners, budget, lead times, dependencies, access needs, and available staff or volunteers.
  - Look for: Generic steps, impossible timing, missing owner, unconfirmed venue assumptions, or a plan that exceeds capacity or authority.
  - Timing: Before the checklist becomes the working event plan.
  - Reviewer: Event owner, venue/operations lead, or responsible organiser.

- **Qualified legal / compliance review:** Identify safety, licensing, insurance, accessibility, safeguarding, employment, food, privacy, or other requirements that need current Hong Kong or specialist confirmation.
  - Look for: A checklist presented as complete or compliant without the relevant qualified check.
  - Timing: Before commitments are made or the event proceeds.
  - Reviewer: Relevant qualified professional, compliance owner, safeguarding lead, or authorised organiser.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.
- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights/obligation issues unless the reviewer is explicitly authorised and competent to confirm the matter under the approved process.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Generally approved**.
- Confirm that the planned reviewer can complete the required human review: **Yes — before finalising**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Local Operational Memory Gap

**Prompt focus:** Before prompting, give the AI the event type, venue, audience, date constraints, staffing, budget, approval limits, known supplier or venue issues, and past event problems. Ask it to flag assumptions about capacity, dependencies, local practice, and operational feasibility.

**Human review focus:** The reviewer should check the checklist against real operational memory: venue issues, volunteer capacity, supplier reliability, timing constraints, past event problems, and what will fail if an assumption is wrong.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the plan depends on local operational memory, venue constraints, volunteer habits, supplier history, or past event problems.

**Do not rely only on:** a plausible checklist. A standard checklist may miss the local reason this plan often fails.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

No direct base prompt pattern is mapped. Use the general safety patterns in `HK Safe AI Use Pack and Prompt Pattern Library.md` and ask the responsible person or task owner to review the prompt before use.

---

## 8. Main Risks

- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Generic Checklist Without Organisational Context — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (Medium)** — AI generates checklists from general event management knowledge. It should not be assumed to know local operational constraints unless they are supplied through approved sources—for example, that this church uses an external venue requiring advance booking, that the sound system needs a specialist operator who must be booked three weeks ahead, or that catering must be ordered through a specific approved supplier. Every organisation has operational constraints that may not be represented in the task basis. A checklist that looks thorough but omits these constraints is more dangerous than a partial checklist, because the organisation assumes the AI has covered everything and stops looking for gaps.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.21 Local Operational Memory Gap|Local Operational Memory Gap]] (Medium)** — AI may generate a standard checklist while missing practical knowledge about how the event, venue, suppliers, volunteers, and team normally operate, as well as workarounds, exceptions, recurring constraints, and lessons from previous events.
- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Omission of Current HK Requirements — related review risk: [[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]] (High)** — AI may omit current Hong Kong requirements that depend on the venue, event type, food, safety, accessibility, insurance, permissions, or other local conditions. Identify and check the relevant current official sources and involve qualified reviewers where interpretation or approval is required.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Logistically Impossible Timelines (Medium)** — AI may generate schedules that appear reasonable in structure but are logistically impossible — insufficient setup time, back-to-back sessions with no transition, or incorrect assumptions about venue access hours.

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
| Generic Checklist Without Organisational Context | **Background** | State the event type, date, venue, audience, expected numbers, budget, responsible roles, fixed constraints, and decisions already made. | [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]]; [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]] |
| Generic Checklist Without Organisational Context | **Instruction** | Create the checklist around the supplied event stages, dependencies, owners, lead times, and local operating conditions. Flag missing inputs rather than filling them generically. | [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]]; [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Local Operational Memory Gap | **Instruction** | Use the supplied non-sensitive knowledge about normal setup, venue access, supplier arrangements, volunteer routines, known constraints, workarounds, and previous lessons. List any operational information that still needs an experienced organiser. | [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Local Operational Memory Gap | **Reminder / Review Note** | An apparently complete checklist is not proof that it fits the actual venue, suppliers, staffing, timing, or local practice. An experienced organiser must confirm feasibility before approval. | [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Omission of Current HK Requirements | **Instruction** | List possible Hong Kong-specific checks that may apply to this event and identify the responsible owner or professional needed to confirm them. Do not claim compliance. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |
| Logistically Impossible Timelines | **Output Format** | Include owner, dependency, earliest start, deadline, lead time, and confirmation status for each material task. | [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]]; [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]] |
| Logistically Impossible Timelines | **Rule** | Do not invent lead times, dependencies, setup durations, travel times, approval windows, or supplier availability. Use supplied or owner-confirmed values and mark unknown timing `{VERIFY}`. | [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]]; [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]] |
| Local Operational Memory Gap | **Content** | Provide current non-sensitive notes on normal setup and closing sequences, venue access, supplier handovers, staff and volunteer roles, approval lead times, dependencies, recurring constraints, known workarounds, and lessons from previous events. | [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.
- Ordinary human review is not enough. Final reliance requires qualified professional judgement and current authoritative sources.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Use Case Triage Scorecard.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before finalising an event checklist, compare it with real operational memory: past event problems, venue constraints, volunteer capacity, supplier issues, setup time, and local approvals.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
