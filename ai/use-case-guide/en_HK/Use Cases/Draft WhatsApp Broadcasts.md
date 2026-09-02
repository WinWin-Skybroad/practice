---
title: Draft WhatsApp Broadcasts
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC02
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft WhatsApp Broadcasts

## 1. What This Use Case Is

Use this page when you want AI to help with: **Draft WhatsApp / Telegram broadcasts**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Generally approved**.
- Human review needed: **Yes — before sending**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A fast broadcast can expose personal, pastoral, health, donor, staff, or other confidential information that appeared only in the source notes. Once sent to a group, the message may be copied or forwarded beyond the intended audience, causing loss of trust, distress, relationship harm, or an incident the organisation cannot fully reverse.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Read the draft as if you are a recipient seeing it for the first time — not as the person who wrote the source notes.
2. Check every name, date, venue, and instruction against the approved source.
3. Check whether any personal information, pastoral/theological content, or confidential detail has been included from notes pasted into the prompt.
4. Confirm that every specific claim, event detail, and implied commitment has been explicitly approved by the responsible person.

---

### 3.2 Before You Approve — One Check

> **Does this message contain any personal information, implied commitment, wrong date, or statement that the person responsible for sending it has explicitly verified and approved — reading it as a recipient, not as the author?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.6 Volume Overwhelm|Volume Overwhelm]]:** Check whether the number of messages, variants, recipient groups, and delivery batches exceeds the named reviewers’ real capacity. Prioritise high-impact variants and ensure each version has a responsible reviewer before it is sent.

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

- **General output review:** Check the final broadcast—not an earlier draft—for the correct audience, purpose, action, date, time, place, link, contact, tone, and length.
  - Look for: A send-ready message with one wrong fact, unclear action, stale link, or wording that no longer matches the approved version.
  - Timing: Immediately before sending.
  - Reviewer: Authorised sender or communication owner.

- **Human-grounded review:** Check whether the message suits the actual group, timing, recent events, relationship, and likely reaction in a fast informal channel.
  - Look for: A message that is technically clear but badly timed, too forceful, too casual, or insensitive to the group’s current situation.
  - Timing: Immediately before sending.
  - Reviewer: Group owner, programme lead, or person who knows the recipients and current context.

- **Privacy / data-boundary review:** Confirm that recipient lists, group details, personal information, replies, attachments, and copied content are handled only through approved channels.
  - Look for: Pasting recipient data into AI, exposing group membership, or including private details in a broadcast.
  - Timing: Before prompting and before sending.
  - Reviewer: Group administrator, privacy-aware reviewer, or authorised sender.

- **Source and fact verification:** Verify every operational fact against the approved source because deletion or unsending may not reverse exposure after recipients have seen, copied, forwarded, downloaded, or captured the message.
  - Look for: Wrong date, venue, deadline, link, capacity, contact, or action multiplied across a large group.
  - Timing: Immediately before sending.
  - Reviewer: Source owner or responsible sender.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the plan affects public events, logistics, safety, finance, external parties, or many recipients and ordinary review cannot confirm safe use.
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

- Confirm that this task fits the approval level: **Generally approved**.
- Confirm that the planned reviewer can complete the required human review: **Yes — before sending**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Real-Time Social Context Gap

**Prompt focus:** Before prompting, give the AI the recipient group, purpose, sender authority, timing, approved facts, sensitivity level, privacy boundary, and what must not be broadcast. Ask it to flag wording that could cause confusion, overstate urgency, reveal sensitive information, or create social ripple effects.

**Human review focus:** The reviewer should check the actual group, timing, tone, names, personal data, and social ripple before sending. A message that is technically clear may still be wrong for this audience at this moment.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the broadcast depends on this week’s events, group mood, relationship sensitivity, timing, or how recipients may react on a fast-moving channel.

**Do not rely only on:** speed or brevity. Broadcast messages travel fast, and the human sender remains accountable for timing, audience, and impact.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — WhatsApp / Telegram Broadcast
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter
- HK Safe AI Use Pack and Prompt Pattern Library.md — Persona Guardrail

---

## 8. Main Risks

- **[[Risk Taxonomy#3.12 Operational Feasibility / Workflow|Operational Feasibility / Workflow]]: Rapid Delivery — Limited Reversal (High)** — Some platforms provide deletion or unsend features, but these may not reverse exposure after recipients have seen, copied, forwarded, downloaded, or captured the message. Review before sending is the primary control. Prompt correction, deletion where available, notification, and containment are secondary controls. In HK church and nonprofit contexts, broadcasts may reach many members, donors, or beneficiaries simultaneously. A factual error, personal disclosure, or unauthorised commitment can therefore spread quickly and affect many recipients before corrective action is possible.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: Real-Time Social Context Gap — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (High)** — AI should not be assumed to understand the group’s current emotional temperature, recent events, or how a fast broadcast may affect recipients unless relevant current context is provided. Timing and audience fit require human judgement.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Recipient List and Personal Data (High)** — A broadcast recipient list may contain personal data where names, telephone numbers, account identifiers, or other information identify living individuals. Entering or uploading the list to an AI tool may disclose, transfer, or otherwise process that data beyond the approved purpose or process. Check the actual fields, purpose, tool, account, recipients, access, and processing arrangements before use.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Informal Channel Tone Mismatch (Medium)** — Messaging platforms carry informal expectations. AI-drafted content formatted for email may read as cold or corporate in a WhatsApp context. The reverse risk — AI producing inappropriately casual content for a serious message — also applies.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Error Propagation at Scale (High)** — Broadcast channels can reach many recipients quickly. A factual error, wrong date, or incorrect instruction may spread before correction or containment is possible, even where deletion or unsend features exist.
- **[[Risk Taxonomy#3.12 Operational Feasibility / Workflow|Operational Feasibility / Workflow]]: [[Human Review Risk Library#4.6 Volume Overwhelm|Volume Overwhelm]] (Medium)** — When AI helps produce many broadcasts, reminders, or updates quickly, review may become a quick skim. The risk is not one message only; it is review capacity being outpaced by message volume.

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
| Rapid Delivery — Limited Reversal | **Instruction** | Before producing the send-ready version, list the audience, date, time, venue, deadline, link, contact, capacity, action required, and approval status for human confirmation. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Rapid Delivery — Limited Reversal | **Rule** | Do not fill a missing send-critical detail. Mark it `{VERIFY}` and do not label the message ready to send. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Rapid Delivery — Limited Reversal | **Reminder / Review Note** | The authorised sender must review the final message immediately before sending because deletion or unsending may not reverse exposure after recipients have seen, copied, forwarded, downloaded, or captured the message. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Real-Time Social Context Gap | **Instruction** | Use the supplied current timing, recent events, group relationship, and audience sensitivities. Flag any missing context that may make the message inappropriate now. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |
| Recipient List and Personal Data | **Rule** | Do not place phone numbers, contact lists, group membership, or other recipient data in the prompt. Use an audience description instead. | [[Prompt Enhancement Patterns#5.4 Privacy and Confidentiality Control\|Privacy and Confidentiality Control]] |
| Informal Channel Tone Mismatch | **Audience / Tone / Language** | Use concise, respectful wording suitable for the actual group. Do not become overfamiliar, abrupt, or more authoritative than the sender’s role. | [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |
| Error Propagation at Scale | **Output Format** | Include a final `Send-critical facts to verify` line before the message. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Volume Overwhelm | **Rule** | Produce only the requested message variants. Do not generate a large batch that cannot each be reviewed before sending. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Volume Overwhelm | **Reminder / Review Note** | Name the reviewer for each requested variant and check each message separately before sending; approval of one variant does not approve the others. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Sample Prompt

For a full use-case-specific worked example, open [[Draft WhatsApp Broadcasts Sample Overall Prompt]]. It is listed next to this use case in the Full Use-Case Library.

The sample shows how the **WhatsApp / Telegram Broadcast** base prompt pattern from `HK Safe AI Use Pack and Prompt Pattern Library.md` can be combined with the default add-ons and risk add-ons above.

In the sample:

- **bold text** is the base prompt content from `HK Safe AI Use Pack and Prompt Pattern Library.md`.
- *italic text* is the use-case prompt enhancement from this page.
- plain text is scenario-specific content supplied by the user.

---

## 12. Other Mitigation

- Human review reduces risk, but it does not guarantee accuracy. Keep records and use approved tools.
- A content review cannot fix the wrong tool, account, or data process. Fix the process before using the output.
- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.
- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.

---

## 13. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- Agent Approval Checklist.md — if broadcast drafting or sending is automated or agentic
- AI Safety Checklist - Work.md — Human review reminders
- AI Use Case Triage Scorecard.md
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Red Lines Quick Reference.md

---

## 14. Final Reminder

Before sending a broadcast, check the live social context: recipient list, timing, sensitivity, personal data, names, dates, tone, and whether this message should be broadcast at all.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
