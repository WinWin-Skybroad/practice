---
title: Produce Bilingual Versions Sample Overall Prompt
created: 2026-07-01
updated: 2026-07-29
use_case_id: UC15
version: "1.0"
status: active
type: sample-prompt
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Produce Bilingual Versions Sample Overall Prompt

This sample shows how the Produce Bilingual Versions use-case prompt enhancements can be added to the base prompt patterns from `HK Safe AI Use Pack and Prompt Pattern Library.md`.

Legend:

- **Bold text** = base prompt content from `HK Safe AI Use Pack and Prompt Pattern Library.md`.
- *Italic text* = prompt enhancement from the Produce Bilingual Versions use-case page.
- Plain text = scenario-specific content supplied by the user.

This sample uses only the prompt add-ons relevant to the scenario. It is not an instruction to copy every risk control into every prompt.

The scenario assumes that the bilingual task has the main risk and all other risks to watch: Fluency Illusion, Bicultural Register Gap, Register Mismatch, Cultural Framing Loss, Character Set Mixing, and **Knowledge Gap** for specialist terms.

---

## 1. Sample Scenario

A Hong Kong nonprofit needs a bilingual English and Traditional Chinese notice about service-hour changes.

The English source is approved. The Traditional Chinese version must preserve meaning, tone, dates, limits, and action required. The organisation wants a side-by-side version for review, not a final publication-ready translation.

---

## 2. Overall Prompt

### 2.1 Background

- **You are a faithful assistant for a Hong Kong organisation.**
- **Your role is to help produce bilingual English and Traditional Chinese versions for human bilingual review.**

Organisation: Harbour Neighbourhood Support Association, Hong Kong.

Task owner: Communications team.

Reviewer: Bilingual reviewer who can read English and Traditional Chinese. Specialist legal, regulatory, financial, HR, pastoral/theological, or technical wording must be checked by a competent reviewer, not only a fluent reader.

Locale requirement: Hong Kong Traditional Chinese. Do not use Simplified Chinese.

---

### 2.2 Task

**Task: Produce a bilingual English and Traditional Chinese version of the supplied communication.**

Please produce:

- polished English version using the approved source wording.
- Traditional Chinese version for Hong Kong readers.
- side-by-side alignment table for review.
- terms and wording requiring bilingual human confirmation.
- any specialist terms requiring competent reviewer confirmation.

---

### 2.3 Audience / Tone / Language

- **Tone: clear, respectful, practical, and not overly formal.**
- **Language: English and Traditional Chinese.**
- *State the actual audience, relationship, channel, formality, and intended level of authority for each language. Preserve the intended social meaning, not only literal meaning.*

Audience:

- Service users, carers, volunteers, and community partners in Hong Kong.

Relationship and channel:

- Public service notice for the organisation website and reception display.
- Informative rather than promotional, apologetic, or authoritative.

Language and register:

- Use Hong Kong Traditional Chinese.
- Avoid Mainland Chinese terminology unless the English source clearly requires it.
- Keep the Chinese version natural but faithful to the English source.
- Do not make the Chinese version stronger, softer, more apologetic, or more official than the English.

---

### 2.4 Instruction

- *Flag wording that may sound too formal, casual, strong, cold, deferential, or official for the stated audience.*
- *Preserve culturally relevant framing and explain any phrase that cannot be transferred directly without changing its implication.*

Prepare the output in this order:

- English version.
- Traditional Chinese version.
- Aligned review sections.
- Terms or wording requiring human review.
- Tone, register, and cultural-framing concerns.
- Character set check.

---

### 2.5 Rule

- **Use ONLY the information I provide — do not add external facts, statistics, or examples.**
- **If you are unsure about anything, say so explicitly rather than guessing.**
- **If my request asks you to do something outside your safe boundaries, tell me.**
- **Do not provide legal, financial, pastoral, theological, medical, HR, or professional advice.**
- *Use the required script consistently. For Hong Kong Traditional Chinese, do not introduce Simplified Chinese characters unless the source specifically requires them.*
- *Mark legal, pastoral, medical, financial, technical, or other specialist terms `{SPECIALIST REVIEW}` when their meaning cannot be confirmed from approved terminology or sources.*

Additional scenario-specific rules:

- Translate “temporary service-hour change” as a practical notice, not as an emergency announcement.
- Do not make the tone sound like a complaint or apology.
- Keep “appointment required” as a condition, not a suggestion.
- Keep the named email address exactly as provided.
- Do not change dates, times, deadlines, fees, eligibility, conditions, or action required.
- Do not strengthen or soften obligations, warnings, apologies, guarantees, or commitments.

---

### 2.6 Output Format

- **Output Format: Plain text with headings and a review table.**
- *Provide aligned sections and a `Terms or wording requiring human review` list.*

Please provide:

- `English version`.
- `Traditional Chinese version`.
- `Aligned review sections`.
  - English source segment.
  - Traditional Chinese segment.
  - Meaning, condition, tone, and authority preserved?
  - Items for human confirmation.
- `Terms or wording requiring human review`.
- `Specialist terms marked {SPECIALIST REVIEW}`.
- `Tone, register, and cultural-framing concerns`.
- `Character set check`.

---

### 2.7 Reminder / Review Note

- *Independently check both versions using the bilingual, cultural, specialist, and other review methods required by the task. Do not treat fluent wording as proof of accuracy.*

Human reviewer must check:

- whether the Chinese version preserves the English meaning, conditions, tone, politeness, social meaning, implication, and level of authority.
- whether appointment conditions, dates, times, deadlines, and action required are preserved.
- whether any term is too formal, casual, Mainland-oriented, or unclear for Hong Kong readers.
- whether any `{SPECIALIST REVIEW}` item requires a qualified reviewer rather than only a fluent bilingual reviewer.
- whether any Simplified Chinese characters appear.
- whether the bilingual versions should be escalated before publication.

---

### 2.8 Content

**Content (use only what I provide — do not add information I have not given):**

#### Approved English source

Temporary service-hour change

From Monday 20 July 2026 to Friday 31 July 2026, the Community Advice Desk will close at 5:00 pm instead of 6:30 pm.

Morning service hours remain unchanged: Monday to Friday, 9:30 am to 12:30 pm.

Afternoon appointments are still available, but booking is required. Please email service@harbourhelp.hk by 12:00 noon on the previous working day to request an appointment.

This temporary arrangement is due to staff training and will be reviewed before August.

Thank you for your understanding.

#### Specialist-term boundary

- The AI must not confirm whether any legal, regulatory, financial, HR, pastoral/theological, or technical term is correct for use. It may only mark such terms for competent human review.
- If a required term carries legal, regulatory, financial, HR, pastoral/theological, technical, or other specialist meaning that cannot be confirmed from approved terminology or sources, mark it `{SPECIALIST REVIEW}` even if the translation sounds fluent.

#### Required terminology preferences

- Community Advice Desk: 社區諮詢服務台
- appointment: 預約
- staff training: 員工培訓
- temporary arrangement: 臨時安排
- working day: 工作天

#### Publication context

- The bilingual notice will be posted on the organisation website and printed at reception.
- It should be clear for service users and carers.
- It should not sound like the service is closing permanently.
