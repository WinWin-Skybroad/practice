---
title: Draft WhatsApp Broadcasts Sample Overall Prompt
created: 2026-07-01
updated: 2026-07-29
use_case_id: UC02
version: "1.0"
status: active
type: sample-prompt
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft WhatsApp Broadcasts Sample Overall Prompt

This sample shows how the Draft WhatsApp Broadcasts use-case prompt enhancements can be added to the base prompt patterns from `HK Safe AI Use Pack and Prompt Pattern Library.md`.

Legend:

- **Bold text** = base prompt content from `HK Safe AI Use Pack and Prompt Pattern Library.md`.
- *Italic text* = prompt enhancement from the Draft WhatsApp Broadcasts use-case page.
- Plain text = scenario-specific content supplied by the user.

This sample uses only the prompt add-ons relevant to the scenario. It is not an instruction to copy every risk control into every prompt.

The scenario assumes that the broadcast has the main risk and all other risks to watch: Rapid Delivery — Limited Reversal, Real-Time Social Context Gap, Recipient List and Personal Data, Informal Channel Tone Mismatch, Error Propagation at Scale, and **Volume Overwhelm**.

---

## 1. Sample Scenario

A community service team needs to send a WhatsApp broadcast to volunteers about a food-packing session. The message must be short, clear, and reviewed before sending.

The source notes include:

- confirmed event details.
- one unconfirmed rumour about why the venue changed.
- a private recipient list that must not be entered into the AI prompt.
- a capacity limit.
- a request not to imply that attendance is compulsory.
- a need to avoid personal or beneficiary details.
- a risk that several AI-assisted reminders may be drafted quickly, causing review to become a skim.

---

## 2. Overall Prompt

### 2.1 Background

- **You are a faithful assistant for a Hong Kong nonprofit.**
- **Your role is to help draft a WhatsApp / Telegram broadcast for human review before sending.**

Organisation: Harbour Neighbourhood Support Association, Hong Kong.

Task owner: Volunteer coordinator.

Reviewer: Programme manager who has authority to approve the broadcast.

Tool/account: Approved organisation AI account only. Do not paste phone numbers, contact lists, group membership, or the actual recipient list into this prompt.

---

### 2.2 Task

**Task: Draft a short WhatsApp / Telegram broadcast message.**

Please draft one WhatsApp broadcast and one shorter backup version.

The message is about the food-packing session venue change and volunteer arrival time.

---

### 2.3 Audience / Tone / Language

- **Tone: friendly, brief, clear, and practical.**
- **Language: English.**
- *Use concise, respectful wording suitable for the actual group. Do not become overfamiliar, abrupt, or more authoritative than the sender’s role.*

Audience:

- Existing adult volunteers in the Food Support Team WhatsApp group.

Tone rules:

- Warm but not emotional.
- Practical but not corporate.
- Do not sound like attendance is compulsory.
- Do not imply blame for the venue change.

---

### 2.4 Instruction

- *Before producing the send-ready version, list the audience, date, time, venue, deadline, link, contact, capacity, action required, and approval status for human confirmation.*
- *Use the supplied current timing, recent events, group relationship, and audience sensitivities. Flag any missing context that may make the message inappropriate now.*

Draft:

- `Send-critical facts to verify`.
- Primary WhatsApp message.
- Short backup version.
- Tone and social-context concerns.
- Privacy and recipient-list concerns.

---

### 2.5 Rule

- **Use ONLY the information I provide — do not add external facts, statistics, or examples.**
- **If you are unsure about anything, say so explicitly rather than guessing.**
- **If my request asks you to do something outside your safe boundaries, tell me.**
- **Do not provide legal, financial, pastoral, theological, medical, HR, or professional advice.**
- *Do not fill a missing send-critical detail. Mark it `{VERIFY}` and do not label the message ready to send.*
- *Do not place phone numbers, contact lists, group membership, or other recipient data in the prompt. Use an audience description instead.*
- *Produce only the requested message variants. Do not generate a large batch that cannot each be reviewed before sending.*

Additional scenario-specific rules:

- Do not mention beneficiary names, individual family situations, or other restricted details.
- Do not say the venue changed because of a complaint; that is unconfirmed.
- Do not promise transport, meal reimbursement, or special arrangements unless stated below.
- Do not make the broadcast sound compulsory unless the source explicitly says attendance is mandatory.
- Keep the primary message under 120 words.
- Keep the backup message under 70 words.

---

### 2.6 Output Format

- **Output Format: Plain text, ready to review and copy only after approval.**
- *Include a final `Send-critical facts to verify` line before the message.*

Please provide:

- `Send-critical facts to verify`
- `Primary WhatsApp broadcast`
- `Short backup version`
- `Tone and social-context concerns`
- `Privacy and recipient-list concerns`

---

### 2.7 Reminder / Review Note

- *The authorised sender must review the final message immediately before sending because deletion or unsending may not reverse exposure after recipients have seen, copied, forwarded, downloaded, or captured the message.*
- *Name the reviewer for each requested variant and check each message separately before sending; approval of one variant does not approve the others.*

Human reviewer must check:

- the actual recipient group, date, time, venue, arrival instruction, contact, capacity, action required, and approval status.
- whether the message implies compulsory attendance.
- whether the wording fits the group’s current mood, relationship, and recent concerns about too many reminders.
- whether any phone number, contact-list, group-membership, beneficiary, family, or other restricted detail appears.
- whether each variant has been checked separately.
- whether approval has been given immediately before sending.

---

### 2.8 Content

**Content (use only what I provide — do not add information I have not given):**

#### Approved source facts

- Activity: Food Support Packing Session.
- Date: Saturday 25 July 2026.
- Volunteer arrival time: 9:15 am.
- Packing time: 9:30 am to 12:00 noon.
- Original venue: Room 2A.
- New venue: Community Hall, G/F.
- Public reason to state: Room 2A is unavailable.
- Action required: Volunteers should go directly to Community Hall, G/F.
- Contact person: Volunteer Coordinator, volunteers@harbourhelp.hk.
- Approved closing line: “Thank you for helping us prepare the packs.”.

#### Information not approved for the message

- Unconfirmed note: someone said the venue change may relate to a complaint. Do not mention this.
- No beneficiary or individual follow-up information is approved for this prompt or message.
- Recipient list: not included in this prompt and must not be inferred.

#### Group context

- The group is friendly but busy.
- Volunteers prefer short messages.
- Some volunteers have recently said there are too many reminders, so avoid over-explaining.
