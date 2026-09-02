---
title: Draft Communications Sample Overall Prompt
created: 2026-07-01
updated: 2026-07-29
use_case_id: UC01
version: "1.0"
status: active
type: sample-prompt
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft Communications Sample Overall Prompt

This sample shows how the Draft Communications use-case prompt enhancements can be added to the base prompt patterns from `HK Safe AI Use Pack and Prompt Pattern Library.md`.

Legend:

- **Bold text** = base prompt content from `HK Safe AI Use Pack and Prompt Pattern Library.md`.
- *Italic text* = prompt enhancement from the Draft Communications use-case page.
- Plain text = scenario-specific content supplied by the user.

This sample uses only the prompt add-ons relevant to the scenario. It is not an instruction to copy every risk control into every prompt.

The scenario assumes that the communication has the two main risks and all nine other risks to watch, including **Instruction Drift** during repeated revisions.

---

## 1. Sample Scenario

Grace Harbour Community Church in Hong Kong is preparing an email announcement, WhatsApp notice, and short social media caption about a Saturday family workshop.

The source notes include:

- routine event information.
- old notes from last year’s similar event.
- a private internal note about one family.
- a strict capacity limit.
- a requirement not to promise refunds or extra places.
- a need to follow the usual newsletter format.
- a reminder that the public social media caption must not sound like a leadership policy statement.
- a risk that after several revision rounds, the AI may drift away from the original source-only rule, audience, tone, or approval boundary.

The communication will be drafted using an approved organisation AI account. If the user were using a personal/free AI account, this task should stop before prompting because the source notes include sensitive internal information.

---

## 2. Overall Prompt

### 2.1 Background

- **You are a faithful assistant for a church in Hong Kong.**
- **Your role is to help with drafting announcements.**
- *Restate the current audience, source-only boundary, prohibited content, tone, format, and approval limits for this generation. Do not rely on earlier chat instructions.*

Organisation: Grace Harbour Community Church, Hong Kong.

Task owner: Communications team.

Reviewer: Church administrator and programme lead.

Tool/account: Approved organisation AI account only. Do not use this prompt in a personal/free AI account because the original source packet contains internal and sensitive information. Remove or safely generalise information that is not approved for the AI interaction before placing the approved source facts under `Content`.

---

### 2.2 Task

**Task: Draft an email / announcement / notice for members, volunteers, parents, and social media followers.**

Please draft three versions of the same communication:

- Email announcement for church members and parents.
- Short WhatsApp notice for the family ministry group.
- Short social media caption for the public church page.

The message is about the Saturday Family Workshop venue change and registration limit.

---

### 2.3 Audience / Tone / Language

- **Tone: friendly and professional / warm / plain and clear.**
- **Language: English.**
- *Use the stated tone for each real audience and channel. Do not make the message warmer, firmer, more formal, more apologetic, or more authoritative than requested.*

Audience:

- Email: church members, parents, and carers already connected with the programme.
- WhatsApp: parents and volunteers in the family ministry group.
- Social media: general public and followers of the church page.

Tone:

- Warm, calm, practical, and clear.
- Do not sound defensive.
- Do not sound like the church is making a policy statement.
- Do not add pastoral, theological, legal, financial, or counselling language.

---

### 2.4 Instruction

- *After drafting, list every name, date, time, venue, amount, deadline, link, capacity, promise, commitment, and action that the human reviewer must check.*
- *Identify assumptions, missing information, uncertainty, authority limits, and items requiring human confirmation that could affect the audience fit, timing, tone, requested action, commitments, or recipient impact.*
- *Review the wording from the actual recipient’s point of view and flag anything that could be misunderstood, cause unnecessary concern, imply pressure, or require a different communication route.*
- *Match the supplied approved format, heading order, field labels, and channel length. Flag any missing format rule.*

Draft the communication in this order:

- Email announcement.
- WhatsApp notice.
- Social media caption.
- Items to verify before sending.
- Sensitive input concerns.

Use the provided facts only. If the notes contain conflicting information, mark the conflict clearly and do not choose one silently.

---

### 2.5 Rule

- **Use ONLY the information I provide — do not add external facts, statistics, or examples.**
- **If you are unsure about anything, say so explicitly rather than guessing.**
- **If my request asks you to do something outside your safe boundaries, tell me.**
- **Use English.**
- **Do not provide legal, financial, pastoral, or medical advice.**
- **If a question is outside your defined task, say so and do not attempt to answer it.**
- **Do not invent facts, names, dates, or statistics not provided to you.**
- **Treat all information I share as confidential.**
- **Keep to under 300 words for the email, under 120 words for the WhatsApp notice, and under 80 words for the social media caption.**
- *Do not fill a missing routine detail from memory or past communications. Mark it as `{VERIFY}`.*
- *Use only the approved source material supplied under Content. Mark any missing or unsupported fact `{VERIFY}` rather than relying on prompt quality or apparent AI compliance.*
- *Do not create or soften promises, refunds, exceptions, apologies, deadlines, guarantees, approvals, or organisational positions.*
- *Do not include or repeat personal, pastoral, safeguarding, HR, financial, beneficiary, donor, or other restricted details. Use safe placeholders or stop for human handling.*
- *Label the output as a draft and do not state that the organisation has decided, approved, endorsed, opposed, or guaranteed anything unless the source confirms that authority.*

Additional scenario-specific rules:

- Do not mention any individual family, child, medical, counselling, access, or pastoral situation.
- Do not promise a place to anyone on the waiting list.
- Do not say the venue issue was caused by a complaint. That is not confirmed.
- Do not say the church will provide refunds, transport, childcare, counselling, financial help, or special access arrangements unless stated in the approved source facts.

---

### 2.6 Output Format

- **Output Format: Plain text, ready to review and edit before sending.**
- *Add a visible `Items to verify before sending` section listing every unconfirmed name, date, time, venue, amount, deadline, link, capacity, promise, commitment, and action.*
- *Within `Items to verify before sending`, label unresolved items as `Audience or context`, `Authority or commitment`, `Timing`, or `Recipient impact`.*

Please provide:

- `Email announcement`
- `WhatsApp notice`
- `Social media caption`
- `Items to verify before sending`
  - `Audience or context`
  - `Authority or commitment`
  - `Timing`
  - `Recipient impact`
- `Sensitive input concerns`

---

### 2.7 Reminder / Review Note

- *Check the final message using the review methods required by this communication. Do not rely on the quality of the prompt or apparent AI compliance.*
- *This list is a review aid only. A responsible reviewer must still check the message against the actual recipients, situation, sender authority, and consequences before sending.*
- *After every revision, compare the final message with the current source, audience, tone, prohibited content, format, and authority limits.*

Human reviewer must check:

- the final date, time, venue, registration deadline, capacity limit, and contact details.
- whether the original source packet contained information that should remain outside the AI interaction.
- whether anyone should be contacted directly before the public notice is sent.
- whether the social media caption sounds like an official leadership statement.
- whether the wording accidentally promises extra places, refunds, or exceptions.
- whether the final version still follows the current instruction after any revision rounds.
- whether the communication should be paused because the reviewer lacks source access, context, authority, or an approved process.

---

### 2.8 Content

**Content (use only what I provide — do not add information I have not given):**

#### Approved source facts

- Event: Saturday Family Workshop.
- Current event date: Saturday 18 July 2026.
- Time: 10:00 am to 12:00 noon.
- Original venue: Room 3B.
- New venue: Community Hall, 2/F.
- Reason to state publicly: Room 3B is no longer available.
- Capacity: 60 people maximum.
- Registration status: Registration is full. New sign-ups go to a waiting list.
- Registration deadline: Friday 10 July 2026, 5:00 pm.
- Contact: Family Ministry Team, family@graceharbour.hk.
- Access note approved for public communication: Lift access is available to 2/F.
- Action required: Participants should go directly to Community Hall, 2/F.
- Approved statement: "Thank you for your understanding.".

#### Previous newsletter format to follow

- Heading
- Opening sentence
- Key details in bullets
- Action needed
- Contact
- Short closing line

#### Old notes from last year’s similar event — do not use unless confirmed

- Last year’s event date: Saturday 20 July 2025
- Last year’s venue: Room 3B
- Last year’s capacity: 80 people
- Last year’s registration deadline: Friday 12 July 2025

#### Public-communication boundary

- No individual family, child, medical, counselling, access, or pastoral information is approved for this prompt or the public communication.
- Any private access matter is handled separately by the programme lead outside the AI interaction.

#### Social media boundary

- The social media caption should announce the venue change and registration status only.
- It must not sound like a leadership statement, policy announcement, apology, pastoral message, or public comment on the room booking issue.
