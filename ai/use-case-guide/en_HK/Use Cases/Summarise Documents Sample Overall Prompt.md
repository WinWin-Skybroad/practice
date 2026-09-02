---
title: Summarise Documents Sample Overall Prompt
created: 2026-07-01
updated: 2026-07-29
use_case_id: UC04
version: "1.0"
status: active
type: sample-prompt
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Summarise Documents Sample Overall Prompt

This sample shows how the Summarise Documents use-case prompt enhancements can be added to the base prompt patterns from `HK Safe AI Use Pack and Prompt Pattern Library.md`.

Legend:

- **Bold text** = base prompt content from `HK Safe AI Use Pack and Prompt Pattern Library.md`.
- *Italic text* = prompt enhancement from the Summarise Documents use-case page.
- Plain text = scenario-specific content supplied by the user.

This sample uses only the prompt add-ons relevant to the scenario. It is not an instruction to copy every risk control into every prompt.

The scenario assumes that the document summary has the main risk and all other risks to watch: Compression Error, Deliberate Ambiguity Loss, Selective Emphasis, Confidential Content Widened, Loss of Nuance, Compounding AI Error, and **Reliability Illusion**.

---

## 1. Sample Scenario

An SME director wants a short summary of a draft supplier service agreement before a management meeting.

The source contains:

- payment terms.
- deadlines.
- caveats and exceptions.
- a conditional approval phrase.
- restricted financial information.
- one appendix drafted by AI and not yet checked.
- ambiguous wording that should not be simplified away.
- a risk that previous accurate AI summaries may cause the reviewer to relax today’s source comparison.

The AI summary is only for internal review. It is not legal advice and must not be used as the basis for signing.

---

## 2. Overall Prompt

### 2.1 Background

- **You are a faithful assistant for a Hong Kong SME or nonprofit.**
- **Your role is to summarise a document for human review while preserving caveats, conditions, deadlines, limitations, and uncertainty.**

Organisation: Harbour Services Limited, Hong Kong.

Task owner: Operations director.

Reviewer: Document owner and management reviewer.

Important boundary: This is not legal advice. If the summary affects signing, payment obligations, rights, penalties, liability, or compliance, it must be escalated to qualified review.

---

### 2.2 Task

**Task: Summarise a document into a decision-support summary for human review.**

Please summarise the supplied document extract for an internal management meeting.

The summary should help the reviewer identify issues, not replace review of the source document.

---

### 2.3 Audience / Tone / Language

- **Tone: neutral, cautious, precise, and source-grounded.**
- **Language: English.**

Audience:

- Operations director and management reviewers considering the draft agreement.

Purpose:

- Support an internal management discussion.
- Do not replace reading the agreement or qualified advice.

---

### 2.4 Instruction

- *Preserve the source’s key conclusions, caveats, exceptions, uncertainty, decision status, unresolved issues, and important supporting reasons.*
- *Use the stated purpose and audience to identify what is important, while listing material points that were excluded or shortened.*

Prepare the output in this order:

- Key points.
- Caveats and exceptions.
- Unresolved or disputed items.
- Items omitted because of scope or sensitivity.
- Items requiring human verification.
- Escalation warning.

---

### 2.5 Rule

- **Use ONLY the information I provide — do not add external facts, statistics, or examples.**
- **If you are unsure about anything, say so explicitly rather than guessing.**
- **If my request asks you to do something outside your safe boundaries, tell me.**
- **Do not provide legal, financial, pastoral, theological, medical, HR, or professional advice.**
- *Do not resolve ambiguity, remove a condition, merge different positions, or make the source more certain than it is.*
- *Do not include restricted details in a version intended for a wider audience. Mark where an authorised owner must decide what may be shared.*
- *Summarise the original approved source, not an earlier AI summary, paraphrase, or memory of the document.*

Additional scenario-specific rules:

- Mark anything not clearly supported by the original source `{VERIFY}`.
- Do not advise whether to sign, accept, reject, or negotiate the agreement.
- Do not treat the AI-drafted appendix as verified source material.
- Do not circulate the confidential appendix outside the management team.

---

### 2.6 Output Format

- **Output Format: Plain text with clearly labelled sections.**
- *Include `Key points`, `Caveats and exceptions`, `Unresolved or disputed items`, and `Items omitted because of scope or sensitivity`.*

Please provide:

- `Key points`
- `Caveats and exceptions`
- `Unresolved or disputed items`
- `Items omitted because of scope or sensitivity`
- `Items requiring human verification`
- `Escalation warning`

---

### 2.7 Reminder / Review Note

- *Compare every new summary with its own source. Do not reduce the review because previous summaries were accurate.*

Human reviewer must check:

- all payment terms, dates, deadlines, notice periods, conditions, exceptions, ambiguity, and decision status against the original agreement.
- whether important supporting reasons or material points were shortened or omitted.
- whether restricted financial or confidential content was widened.
- whether any AI-generated appendix was treated as verified source material.
- whether the matter needs legal, financial, regulatory, or authorised management review before use.

---

### 2.8 Content

**Content (use only what I provide — do not add information I have not given):**

#### Document context

- Document: Draft Supplier Service Agreement extract
- Version: Draft v0.8
- Date of extract: 7 July 2026
- Intended use: internal management discussion only
- Not for signing or external circulation

#### Source extract

1. Service period

The service period is proposed to run from 1 September 2026 to 31 August 2027, subject to final confirmation by both parties.

2. Monthly fee

The draft monthly service fee is HK$18,000. This figure is marked “subject to supplier confirmation” in the pricing table.

3. Payment timing

Invoices are to be issued monthly. Payment is due within 21 calendar days after receipt of a valid invoice.

4. Service-level wording

The supplier will use reasonable efforts to provide support within two working days. The phrase “reasonable efforts” has not yet been defined.

5. Termination

Either party may terminate the agreement with 30 days’ written notice. Early termination fees are “to be discussed” and are not yet confirmed.

6. Confidential appendix

Appendix B contains internal cost estimates and should not be circulated outside the management team.

7. AI-generated appendix warning

Appendix C was drafted using AI based on earlier project notes. It has not been checked against the original project records.

8. Open issue

The operations director asked whether the 21-day payment term is acceptable. No decision has been made.
