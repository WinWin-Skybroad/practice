---
title: Use Case Page Template
created: 2026-07-01
updated: 2026-08-14
version: "1.0"
status: active
type: template
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Use Case Page Template

## 1. How To Use This Template

Use this template when your organisation wants to create or adapt a use-case page. The main audience is the **human reviewer**, not only the person using AI.

---

## 2. Plain-Language Writing Rule

Write each use-case page for a busy general reader. Keep the message clear and direct. Explain what the AI can help with, what a person must still check, and when the task should stop or escalate. Use short connected sentences and avoid technical language unless the term is needed by this guide.

---

## 3. What This Use Case Is

Describe the task in plain language. Say who usually uses it, the approval level, and whether human review is required.

---

## 4. What This Could Cost You

Write one concrete general consequence narrative. Show what rubber-stamp review could miss and what the mistake may cost in real organisational work.

Write it as a plain narrative paragraph. Do **not** label it as illustrative, hypothetical, or a failure scenario. Prefer a description of what may happen rather than a detailed past-tense incident. Do not imply that a regulator, insurer, funder, auditor, professional, or named organisation actually reached a stated outcome unless the incident is documented and the provenance has been checked.

Avoid examples that depend on a current legal conclusion or professional outcome. Keep the practical consequence, then direct the reader to current official sources or qualified review where needed. If a documented incident is used, anonymise it unless you have permission and a clear reason to identify it.

---

## 5. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 5.1 Review Setup

1. [Name the actual source, record, person, standard, or real-world reference that must be available.]
2. [Name the task-specific items that must be checked.]
3. [Name the reviewer competence, experience, or authority needed.]

---

### 5.2 Before You Approve — One Check

> **[Write one task-specific question that would expose the most important failure.]**

---

### 5.3 Risk-Specific Review Checks

For every risk that lists this page under **Affected use cases** in [[Human Review Risk Library]], adapt its **What review must check** into a visible task-specific review instruction.

Preserve the canonical review obligation, but remove unrelated examples and name:

- the actual item being checked;
- the source, record, person, standard, or real-world reference used;
- the task-specific warning signs;
- the reviewer competence, experience, qualification, or authority needed;
- when the check happens; and
- what must happen if the issue cannot be resolved.

Where wording is approved for exact reuse, keep it unchanged and add a separate **For this use case** line.

- **[[Human Review Risk Library#4.x Risk name|Risk name]]:** [Task-specific version of **What review must check**.]
  - **For this use case:** [Use this additional line only where the canonical sentence must remain unchanged.]

Do not rely on a general review method to imply that the named risk is covered. Keep the risk-specific obligation visible, then use the review methods below to explain how the check is performed.

---

### 5.4 Reviewer Decision

After completing the task-specific review checks above, choose one outcome using [[Reviewer Decision Card]]:

- **Approve as is**
- **Correct then approve**
- **Stop and escalate**

Do not approve the output if the reviewer lacks the role, evidence, authority, competence, source access, context, or approved process needed for this task.

---

### 5.5 Review Methods for This Task

Select only the review patterns that materially apply. Keep the published pattern name, but adapt the instruction to the task.

For each selected pattern, state:

- what is being checked;
- what it is checked against;
- the task-specific warning signs;
- when the check happens; and
- who should perform it.

Remove unrelated items from the general pattern. Add task-specific checks that the general pattern could not know. Do not copy the full generic pattern mechanically.

- **[Review pattern name]:** [Task-specific application of the pattern.]
  - Look for: [Task-specific warning signs.]
  - Timing: [Task-specific timing.]
  - Reviewer: [Task-specific reviewer role, competence, or authority.]

---

## 6. When To Escalate Instead of Approve

List the conditions that require a more senior, qualified, or authorised reviewer.

---

## 7. Before You Prompt

Give the minimum checks before using AI: purpose, source material, privacy/confidentiality, reviewability, and authority.

---

## 8. AI Blind Spot Focus

**Risk focus:** Name the specific AI Blind Spot risk for this use case, such as Unwritten Context Gap, Reader Interpretation Gap, Authority Boundary Blindness, Materiality Judgement Gap, User-Pressure Drift, AI Self-Validation Illusion, or another task-specific risk.

**Prompt focus:** State what task-specific context the user should give AI before generation. Do not use a generic missing-context prompt if the real risk is reader interpretation, authority, materiality, verification, anomaly, translation register, or operational memory.

**Human review focus:** State what the human reviewer must check before use, including the real organisation, people, source documents, approval authority, consequences, and the specific risk focus above.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when: State only the task-specific condition that makes deeper Blind Spot review useful. Do not restate the companion guide’s complete purpose, current focus, definitions, internal routing, handling model, or scope boundaries here. If another control is primary, identify that control clearly instead of implying that Blind Spot Guide work is sufficient.

**Do not rely only on:** State the false comfort to avoid, such as clear wording, AI confidence, AI agreement with the user, AI self-checking, fluent translation, tidy extraction, or a plausible checklist.

---

## 9. Base Prompt Pattern

List the relevant base prompt pattern from **Win.Win AI Essentials**. Make clear that the pattern is in `HK Safe AI Use Pack and Prompt Pattern Library.md`, not repeated here.

---

## 10. Main Risks

List every main risk in this format:

- **[[Risk Taxonomy#3.x Risk family|Risk family]]: [[Human Review Risk Library#4.x Risk name|Risk name]] (Severity)** — Explain how the risk appears in this use case.

Use the exact risk-family title from [[Risk Taxonomy]]. Link the risk name to [[Human Review Risk Library]] when that reusable risk has an entry there. If the risk is a narrower task-specific manifestation, define it clearly in this use-case page and ensure the exact published name is indexed in [[Risk Taxonomy#4. Named Risk and Failure-Mode Index|Named Risk and Failure-Mode Index]]. If a family does not yet have a taxonomy section, leave the family name as plain text rather than creating a broken link. Do not introduce a shorthand risk name when an existing defined name has the same meaning.

Use **Main Risks** as the heading even when only one main risk is listed.

---

## 11. Other Risks To Watch

List additional risks in the same **Risk family: Risk name (Severity)** format. Explain why each risk matters in this use case.

---

## 12. Prompt Enhancements To Add

Start with the base prompt pattern from `HK Safe AI Use Pack and Prompt Pattern Library.md` of the Win.Win AI Essentials. Then add only safeguards that can materially reduce the risks in this task.

The rows below must already be customised for the use case. Do not leave generic placeholders for the reader to interpret.

For every risk that lists this page under **Affected use cases** in [[Human Review Risk Library]] and has a **Prompt-side control**, assess that control for this task. Where prompt wording can materially reduce the risk, convert the control into task-specific Default or Conditional Risk Add-On rows. Where prompting is not the main control, state where the risk is handled instead through review, an approved tool, independent verification, specialist or authority review, other mitigation, or escalation. Do not let the prompt-side control disappear silently.

The `Risk` column must contain exactly one actual, already-defined risk name. It must match the published name used under **Main Risks** or **Other Risks To Watch**, or an applicable reusable risk defined in [[Human Review Risk Library]] and indexed in [[Risk Taxonomy#4. Named Risk and Failure-Mode Index|Named Risk and Failure-Mode Index]]. Do not use a shortened alias, near-synonym, or new label merely for the prompt table. Do not replace the name with a category label such as `Main risk`, `Additional risk`, `Default risk`, or `Conditional risk`, and do not merge several risks into one row. Whether the risk appears under **Main Risks** or **Other Risks To Watch** does not determine which Essentials prompt sections it uses or how many rows it receives.

Use the final `Patterns` column for traceability to [[Prompt Enhancement Patterns]]. Link the exact published pattern heading. If several patterns materially contribute to one add-on, list the linked pattern names in the same cell separated by semicolons. Do not use commas, ditto marks, blank cells, or a merged pattern label. List only patterns whose control logic is present in that row.

Choose each row according to the distinct job it performs in this task. A risk may need one row or several rows, and it may use any relevant Essentials prompt section. Where prompt functions differ, use separate rows even if they use the same risk and pattern.

Use this method:

1. Select the relevant canonical prompt-side control.
2. Remove examples, fields, checks, and prompt sections that are unrelated to this task.
3. Name the actual task-specific element the instruction applies to, such as the source document, audience, output, jurisdiction, authority owner, material condition, operational dependency, verification source, or warning marker.
4. Adjust the selected control to the concrete use case by adding only the fields, limits, thresholds, prohibited commitments, review markers, or source requirements that materially apply.
5. Confirm that each row performs one clear prompt function, preserves the original control, and does not imply that prompting replaces human review.

Task-specific wording must tell the user what to provide, what AI should do, what AI must not do, or what the reviewer must check for this particular use case. Avoid generic wording such as “check the source”, “consider the audience”, “review carefully”, or “verify important information” unless the actual source, audience, reviewer, information, or verification method is also named.

Do not add a prompt row for a risk that is handled mainly through human review, approved tools, specialist checking, other mitigation, or escalation.

Keep source material, notes, policy extracts, figures, and documents under **Content** at the end of the base prompt.

Each add-on must already show where it belongs in the Win.Win AI Essentials prompt structure. Do not ask the reader to decide where the sentence should go. Do not duplicate the same sentence across multiple sections.

The difference between **Default Add-Ons** and **Conditional Risk Add-Ons** is when they are used:

- **Default Add-Ons** are normally used for this use case because the safeguard is ordinarily needed whenever the task is performed.
- **Conditional Risk Add-Ons** are used only when the stated risk, condition, source type, audience, jurisdiction, authority issue, or operating circumstance is present.

This distinction is not the same as **Main Risks** versus **Other Risks To Watch**. A main risk may have no prompt add-on if it is controlled mainly through human review, specialist checking, approved tools, other mitigation, or escalation. A risk listed under **Other Risks To Watch** may still justify a default add-on if the safeguard is normally needed for this use case.

This difference is **not** a restriction on prompt sections. Both Default Add-Ons and Conditional Risk Add-Ons may use any Essentials prompt section: **Background**, **Task**, **Audience / Tone / Language**, **Instruction**, **Rule**, **Output Format**, **Reminder / Review Note**, or **Content**.

Use only the rows needed for the use case. Do not include every section mechanically. Use the actual risk name in every populated row.

---

### 12.1 Default Add-Ons

Use these for this use case unless there is a clear reason not to.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| [Risk name] | **Background** | [Name the default organisation context, jurisdiction, setting, user role, authority boundary, or task boundary that normally applies to this specific use case.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Task** | [State the precise action AI should perform on the named source or content for this specific use case.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Audience / Tone / Language** | [Name the actual audience or reader group and specify the channel, tone, register, language, bilingual, or cultural requirement that normally applies.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Instruction** | [State the task-specific method AI should use, including what it should compare, organise, analyse, flag, or separate.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Rule** | [State the concrete task-specific limit AI must not cross, including the relevant source boundary, authority limit, prohibited commitment, or uncertainty marker.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Output Format** | [Specify the exact task-specific review aid required, including its fields, labels, source references, exception markers, or decision points.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Reminder / Review Note** | [Name what the human reviewer must check, what it must be checked against, and the role or authority needed before this output is used.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Content** | [Name the source material, approved text, facts, exclusions, operational notes, or other task-specific content to place under Content at the end of the prompt.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |

---

### 12.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| [Risk name] | **Background** | [Name the specific context, jurisdiction, setting, source condition, memory or session boundary, audience circumstance, or authority boundary that triggers this add-on.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Task** | [State the additional task instruction required when this risk or condition is present.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Audience / Tone / Language** | [Name the affected audience or reader group and specify the additional channel, tone, register, language, bilingual, or cultural requirement triggered by this risk.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Instruction** | [State the concrete method, comparison, analysis, flagging step, or uncertainty check AI should perform when this risk is present.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Rule** | [State the concrete limit, source boundary, authority boundary, prohibited action, or uncertainty rule required for this risk.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Output Format** | [Specify the exact table, checklist, verification list, source-gap list, exception marker, or reviewer aid required for this risk.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Reminder / Review Note** | [Name what the human reviewer must check for this risk, what it must be checked against, and who has the competence or authority to decide.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |
| [Risk name] | **Content** | [Name the additional source material, exclusions, examples, operational notes, or approved wording to place under Content when this risk is present.] | [Link the applicable pattern heading or headings. Separate multiple linked patterns with semicolons.] |

Risks not represented in these tables must still be handled through the task-specific review, mitigation, or escalation sections where relevant.

Keep source material, notes, documents, policy extracts, figures, and examples under **Content** at the end of the base prompt.

If a prompt enhancement has several jobs, write several rows. For example, put the checking step in **Instruction**, the hard limit in **Rule**, the review aid in **Output Format**, and the human responsibility in **Reminder / Review Note**.

Do not use a combined Instruction-and-Rule location. Split the content so each row has one clear place.

---

## 13. Sample Prompt

If the use case needs a worked example, add a short sample prompt or link to a sample prompt file. In that sample:

- **bold text** may show base prompt content from the Win.Win AI Essentials.
- *italic text* may show use-case prompt enhancements.
- plain text should show scenario-specific user content.

---

## 14. Other Mitigation

List controls beyond prompt wording, such as approved tools, source retention, review records, or escalation.

---

## 15. Related Win.Win AI Essentials Items

List related Essentials materials.

---

## 16. Final Reminder

Remind the reader that AI is a drafting/review aid, not the final approver.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
