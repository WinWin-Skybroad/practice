---
title: Produce Bilingual Versions
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC15
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Produce Bilingual Versions

## 1. What This Use Case Is

Use this page when you want AI to help with: **Produce bilingual English and Traditional Chinese versions**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — bilingual reviewer required**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

A small shift in modality, restriction, amount, date, responsibility, or tone can make two language versions communicate different obligations. If each version is read only on its own, the mismatch may reach donors, staff, clients, members, or the public and require correction, explanation, or a decision about which version governs.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. Open both versions side by side with the English as the source.
2. Read sentence 1 in English, then sentence 1 in TC. Confirm they carry the same meaning and the same conditions before moving to sentence 2.
3. Pay particular attention to: conditional terms, limitations, commitments, legal references, and any phrase that creates an obligation or restriction.
4. Flag any sentence where the TC reads fluently but carries a different scope, strength, or condition from the English.

---

### 3.2 Before You Approve — One Check

> **Has a qualified bilingual reviewer read the TC output alongside the English source, sentence by sentence — not just checking that the Chinese reads well, but confirming that the meaning, conditions, and commitments are identical in both versions?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.5 Knowledge Gap|Knowledge Gap]]:** Confirm that the reviewer has sufficient competence in both languages and in the document’s subject matter to detect meaning, terminology, authority, and cultural errors. Obtain separate professional review where specialist content exceeds the bilingual reviewer’s expertise.
- **[[Human Review Risk Library#4.11 Fluency Illusion|Fluency Illusion]]:** Independently compare the bilingual output with the source for meaning, facts, caveats, authority, terminology, formatting, and omissions. Do not treat natural or polished wording as evidence that the translation is complete or correct.
- **[[Human Review Risk Library#4.20 Bicultural Register Gap|Bicultural Register Gap]]:** Check whether the wording preserves the intended tone, formality, politeness, social meaning, implication, and level of authority for the actual audience and setting. Use an appropriate bilingual, cultural, or audience-aware reviewer, and seek specialist review separately where professional meaning is involved.

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

- **Bilingual / localisation review:** Compare each language version with the approved source and terminology, checking meaning, omissions, additions, script, names, formatting, and Hong Kong usage.
  - Look for: A fluent translation that changes meaning, mixes scripts, alters authority, loses formatting, or uses inconsistent terms.
  - Timing: Before publication or external use.
  - Reviewer: Qualified bilingual reviewer familiar with the target audience and Hong Kong usage.

- **Human-grounded review:** Check whether tone, formality, politeness, social meaning, implication, and level of authority suit the actual audience and relationship in both languages.
  - Look for: Literal accuracy with an inappropriate cultural or social signal, or wording that feels colder, stronger, more official, or less respectful than intended.
  - Timing: Before publication or sending.
  - Reviewer: Bilingual, cultural, or audience-aware reviewer.

- **Qualified legal / compliance review:** Where specialist meaning or professional practice is involved, obtain review from a qualified professional as well as a bilingual reviewer.
  - Look for: Technically fluent wording that changes legal, pastoral, medical, financial, technical, or other specialist meaning.
  - Timing: Before specialist content is relied on or published.
  - Reviewer: Relevant qualified professional and bilingual reviewer.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate legal, medical, financial, technical, or public translation when the reviewer is not qualified or authorised to confirm the specialist meaning.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — bilingual reviewer required**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Bicultural Register Gap

**Prompt focus:** Before prompting, give the AI the source text, target audience, locale, register, terminology preferences, channel, and whether legal, official, or public-facing wording is involved. Ask it to mark terms, idioms, formal expressions, and audience-sensitive phrases that require bilingual human confirmation.

**Human review focus:** Compare meaning side by side. Check register, audience fit, HK terminology, names, dates, official terms, and whether fluent wording changes the intended meaning.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the bilingual output depends on local terminology, formality, cultural meaning, audience expectation, or institutional register.

**Do not rely only on:** natural fluency. A bilingual version can read well while shifting tone, obligation, formality, or institutional meaning.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Bilingual Draft (English + Traditional Chinese)
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter

---

## 8. Main Risks

- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: [[Human Review Risk Library#4.11 Fluency Illusion|Fluency Illusion]] (High)** — AI-generated Traditional Chinese may read clearly, naturally, and professionally, causing reviewers to assume it is accurate and ready to use. Meaning drift, softened conditions, strengthened commitments, character-set errors, and register mismatches can remain hidden unless the output is independently checked using the bilingual, localisation, specialist, and other review patterns required by the task. Fluent text is not evidence of accurate text.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.20 Bicultural Register Gap|Bicultural Register Gap]] (Medium)** — AI may produce bilingual or cross-cultural wording that is accurate in literal meaning but inappropriate in tone, language register, formality, politeness, implication, level of authority, or social signal for the actual audience and setting.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Register Mismatch (Medium)** — Formal English may be translated into inappropriately casual Chinese, or vice versa. Register errors are particularly consequential in HK church and nonprofit communications where formal address carries relational meaning.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Cultural Framing Loss (Medium)** — Idiomatic English expressions, metaphors, or cultural references require cultural adaptation in Chinese, not literal translation. AI tends toward literal rendering. The Chinese output may be linguistically correct but culturally confusing or inappropriate.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: Character Set Mixing (Medium)** — AI may insert Simplified Chinese characters into a Traditional Chinese document. In a bilingual document, this is especially hard to detect because the reviewer may be focused on the English-Chinese alignment rather than character-level accuracy.
- **[[Risk Taxonomy#3.8 Bilingual / Localisation / HK Context|Bilingual / Localisation / HK Context]]: [[Human Review Risk Library#4.5 Knowledge Gap|Knowledge Gap]] (High)** — A reviewer may be careful and bilingual, but still not qualified to confirm whether legal, regulatory, financial, HR, pastoral/theological, or specialist terms have been translated correctly. Specialist terms need a competent reviewer, not only a fluent reader.

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
| Fluency Illusion | **Reminder / Review Note** | Independently check both versions using the bilingual, cultural, specialist, and other review methods required by the task. Do not treat fluent wording as proof of accuracy. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |
| Fluency Illusion | **Output Format** | Provide aligned sections and a `Terms or wording requiring human review` list. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| Bicultural Register Gap | **Audience / Tone / Language** | State the actual audience, relationship, channel, formality, and intended level of authority for each language. Preserve the intended social meaning, not only literal meaning. | [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Register Mismatch | **Instruction** | Flag wording that may sound too formal, casual, strong, cold, deferential, or official for the stated audience. | [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Cultural Framing Loss | **Instruction** | Preserve culturally relevant framing and explain any phrase that cannot be transferred directly without changing its implication. | [[Prompt Enhancement Patterns#5.7 Tone and Representation Control\|Tone and Representation Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Character Set Mixing | **Rule** | Use the required script consistently. For Hong Kong Traditional Chinese, do not introduce Simplified Chinese characters unless the source specifically requires them. | [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Knowledge Gap | **Rule** | Mark legal, pastoral, medical, financial, technical, or other specialist terms `{SPECIALIST REVIEW}` when their meaning cannot be confirmed from approved terminology or sources. | [[Prompt Enhancement Patterns#5.10 Professional Boundary Control\|Professional Boundary Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Sample Prompt

For a full use-case-specific worked example, open [[Produce Bilingual Versions Sample Overall Prompt]]. It is listed next to this use case in the Full Use-Case Library.

The sample shows how the **Bilingual Draft (English + Traditional Chinese)** base prompt pattern from `HK Safe AI Use Pack and Prompt Pattern Library.md` can be combined with the default add-ons and risk add-ons above.

In the sample:

- **bold text** is the base prompt content from `HK Safe AI Use Pack and Prompt Pattern Library.md`.
- *italic text* is the use-case prompt enhancement from this page.
- plain text is scenario-specific content supplied by the user.

---

## 12. Other Mitigation

- Fluent text can hide meaning drift; bilingual review must compare source and target, not just read the target.

---

## 13. Related Win.Win AI Essentials Items

- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — Bilingual Draft (English + Traditional Chinese)
- HK Safe AI Use Pack and Prompt Pattern Library.md — Calibrated Research (HK)

---

## 14. Final Reminder

Before using bilingual output, compare source and target sentence by sentence and check meaning, register, HK terminology, names, dates, commitments, and how the wording lands for the real audience.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
