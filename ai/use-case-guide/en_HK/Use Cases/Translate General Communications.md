---
title: Translate General Communications
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC14
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Translate General Communications

## 1. What This Use Case Is

Use this page when you want AI to help with: **Translate general communications**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — qualified bilingual reviewer required**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A translation may replace a legal, technical, safeguarding, or organisational term with a broader everyday expression, changing what the reader must provide, do, or understand. If no qualified bilingual reviewer compares the source and target versions, the process may need to be repeated and the organisation may give inconsistent or misleading instructions.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Read both the source and the translation side by side.
2. Identify every term with legal, regulatory, or technical significance — do not rely on overall fluency to catch these.
3. For each such term, confirm the TC equivalent carries the correct legal or technical meaning in HK context. Fluent is not the same as correct.
4. If the document has legal consequence for the recipient, escalate to a reviewer with subject-matter qualification, not only language competence.

---

### 3.2 Before You Approve — One Check

> **Has a bilingual reviewer with knowledge of the subject area — not just language fluency — confirmed that every legal term, technical term, and phrase with formal consequence carries the same legal weight and meaning in TC as in the English source?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.11 Fluency Illusion|Fluency Illusion]]:** Compare the translation line by line with the source for meaning, facts, caveats, tone, authority, terminology, formatting, and omissions. Do not approve it because it reads naturally or professionally.
- **[[Human Review Risk Library#4.15 Reader Interpretation Gap|Reader Interpretation Gap]]:** Check how each named reader group may interpret the translated tone, certainty, authority, commitment, refusal, approval, and required action. Correct wording that may be understood differently from the source intent.
- **[[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]]:** Check whether the translation depends on Hong Kong or another named jurisdiction, sector, organisation, or local setting. Verify official terminology, local rules, and institutional meaning against current authoritative sources or an appropriate local reviewer.

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

- **Bilingual / localisation review:** Compare the translation with the source line by line for meaning, omissions, additions, terminology, names, script, formatting, and Hong Kong usage.
  - Look for: Fluent wording that changes meaning, untranslated text, script mixing, inconsistent terminology, or formatting that changes the message.
  - Timing: Before sending or publishing.
  - Reviewer: Qualified bilingual reviewer familiar with the audience and Hong Kong usage.

- **Human-grounded review:** Read the translation as the actual recipient and check tone, formality, politeness, implied authority, action required, and likely interpretation.
  - Look for: A literal translation that sounds too strong, cold, casual, official, insensitive, or ambiguous for the real relationship and channel.
  - Timing: Before sending or publishing.
  - Reviewer: Bilingual, cultural, or audience-aware reviewer.

- **Qualified legal / compliance review:** Where the source contains legal, regulatory, HR, medical, financial, pastoral, technical, or other specialist meaning, obtain relevant professional review as well as bilingual review.
  - Look for: Correct general language with incorrect specialist meaning or jurisdictional effect.
  - Timing: Before specialist content is relied on or published.
  - Reviewer: Relevant qualified professional and bilingual reviewer.

- **Tool / process governance review:** Confirm the approved model/tool, version, source file, terminology table, and comparison workflow when more than one model or translation step is used.
  - Look for: Model substitution, source drift, different terminology bases, or no record of which output was reviewed.
  - Timing: Before and during the translation workflow.
  - Reviewer: Translation owner, tool owner, or governance reviewer.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights/obligation issues unless the reviewer is explicitly authorised and competent to confirm the matter under the approved process.
- Escalate legal, medical, financial, technical, or public translation when the reviewer is not qualified or authorised to confirm the specialist meaning.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — qualified bilingual reviewer required**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Reader Interpretation Gap

**Prompt focus:** Before prompting, give the AI the intended audience, channel, purpose, relationship, locale, tone, terminology preferences, and action required. Ask it to identify wording that could be misunderstood, sound stronger than intended, imply authority or commitment, change formality, appear insensitive, or confuse the reader.

**Human review focus:** Compare source and translation side by side, then read from the target reader’s point of view. Check meaning, register, cultural fit, names, dates, obligations, and whether the translation changes what the organisation is saying.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the translation depends on reader interpretation, local register, institutional meaning, formality, or terminology that a fluent but outside translation may miss.

**Do not rely only on:** literal accuracy or fluent wording. The real reader may understand tone, obligation, or authority differently from what the sender intended.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Bilingual Draft (English + Traditional Chinese)
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter

---

## 8. Main Risks

- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: [[Human Review Risk Library#4.11 Fluency Illusion|Fluency Illusion]] (High)** — Natural-sounding translation can be treated as correct even when it uses a general Chinese expression where a specific Hong Kong legal or regulatory term is required. The smooth wording can hide a change in legal weight, obligation, or entitlement unless the output is independently checked using the bilingual, localisation, legal, and other review patterns required by the task.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.15 Reader Interpretation Gap|Reader Interpretation Gap]] (Medium)** — AI may choose natural wording that is technically correct but changes how the reader understands tone, obligation, formality, or institutional meaning.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Character Set Mixing (Medium)** — AI may insert Simplified Chinese characters into a Traditional Chinese document and vice versa. This is invisible to a reviewer who cannot distinguish the two scripts fluently.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Formatting Loss During Translation (Low)** — Translation models prioritise semantic accuracy over structural preservation. Headers, bullets, bold text, and table formatting may be lost or altered. A formatting check against the original is required separately from a content check.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Untranslated English Words (Low)** — AI may leave English words embedded in Chinese text without translating them. These are easy to miss on a fast read because the surrounding Chinese text looks correct and the eye skips familiar English words.
- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: Jurisdiction Mismatch — related review risk: [[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]] (High)** — Simplified Chinese output may introduce Mainland Chinese terminology, legal assumptions, or institutional references, especially when Hong Kong jurisdiction is not explicit. Even SC content for HK use should specify Hong Kong jurisdiction and be checked against official Hong Kong terminology and current sources where legal or regulatory meaning matters.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Terminology Inconsistency (Medium)** — Providing a terminology translation table reduces inconsistency but does not eliminate it. Models interpret instructions — they do not execute them mechanically. Targeted term-by-term verification is required after translation.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Model Substitution During Multi-Model Review (Medium)** — When multiple source documents are given to a reviewing model simultaneously, the model may choose its own authoritative source rather than the one specified, producing correct formatting but incorrect terminology.

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
| Fluency Illusion | **Reminder / Review Note** | Independently check the translation using the bilingual, cultural, specialist, and other review methods required by the task. Do not treat fluent wording as proof that it is correct. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |
| Fluency Illusion | **Output Format** | Include a list of terminology, wording, jurisdiction, or formatting items requiring human confirmation. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Reader Interpretation Gap | **Audience / Tone / Language** | State the actual recipient, relationship, channel, purpose, tone, formality, and action required. Flag wording that may be interpreted differently from the source intention. | [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]]; [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]] |
| Character Set Mixing | **Rule** | Use the required script consistently and flag any character whose correct form is uncertain. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Formatting Loss During Translation | **Instruction** | Preserve headings, bullets, tables, emphasis, labels, placeholders, links, and line breaks required by the source. | [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Formatting Loss During Translation | **Rule** | Do not invent or normalise missing, broken, or unclear source formatting. Preserve it where possible and mark the affected part `{VERIFY}` when the intended layout is uncertain. | [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Untranslated English Words | **Rule** | Translate or deliberately retain each English term according to the approved terminology. Flag unexplained English that remains. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Jurisdiction Mismatch | **Rule** | Preserve the stated jurisdiction and do not substitute terminology, law, institutions, or practices from another jurisdiction. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |
| Terminology Inconsistency | **Instruction** | Use the approved term consistently and list any source term that has more than one possible translation. | [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Model Substitution During Multi-Model Review | **Reminder / Review Note** | Record which model and source version produced each draft. Compare the final output with the approved source and terminology, not only with another model’s translation. | [[Prompt Enhancement Patterns#5.5 Prompt Injection and Tool Safety Control\|Prompt Injection and Tool Safety Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Fluent text can hide meaning drift; bilingual review must compare source and target, not just read the target.
- A content review cannot fix the wrong tool, account, or data process. Fix the process before using the output.

---

## 12. Related Win.Win AI Essentials Items

- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Bilingual Draft (English + Traditional Chinese)
- HK Safe AI Use Pack and Prompt Pattern Library.md — Calibrated Research (HK)
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before using a translation, do not read the target text alone. Compare it with the source for meaning, register, obligations, names, dates, HK terminology, formatting, and likely reader interpretation.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
