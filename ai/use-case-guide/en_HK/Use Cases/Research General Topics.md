---
title: Research General Topics
created: 2026-07-01
updated: 2026-08-14
use_case_id: UC09
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Research General Topics

## 1. What This Use Case Is

Use this page when you want AI to help with: **Research and fact-find on general topics**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — verify all facts and sources**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

AI research may include a citation that does not exist, attribute a claim to the wrong source, reverse a study’s conclusion, or present an uncertain position as settled. If the output is used before each material claim is verified, inaccurate content may enter a briefing, training session, report, or public statement.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. List every named study, statistic, researcher, and publication in the output.
2. Search each one using a search engine, library database, or official source — not using AI.
3. For any claim that cannot be verified, remove it or mark it clearly as unverified before use.
4. Do not treat a plausible-sounding citation as a real citation. Verify it exists before using it.

---

### 3.2 Before You Approve — One Check

> **Has at least one human-verified source been found for every factual claim, research finding, and citation in this output before it is used in any document, presentation, or public statement?**

---

### 3.3 Reviewer Decision

After completing the task-specific review checks above, choose one outcome using [[Reviewer Decision Card]]:

- **Approve as is**
- **Correct then approve**
- **Stop and escalate**

Do not approve the output if the reviewer lacks the role, evidence, authority, competence, source access, context, or approved process needed for this task.

---

### 3.4 Review Methods for This Task

The review instructions below are customised for this task. They apply the reusable methods in [[Human Review Patterns]] to the actual sources, decisions, people, and consequences involved here.

- **Source and fact verification:** Verify each material claim, citation, statistic, date, quotation, and named source against the original current source.
  - Look for: Fabricated citations, inaccessible sources, outdated evidence, unsupported conclusions, and claims that do not match the cited material.
  - Timing: Before the research is used, shared, or relied on.
  - Reviewer: Researcher, subject owner, or source-checking reviewer.

- **General output review:** Check whether the research answers the stated question, defines its scope, distinguishes evidence from interpretation, and makes limitations and missing viewpoints visible.
  - Look for: A polished answer that appears complete despite narrow sources, hidden assumptions, or unresolved disagreement.
  - Timing: Before circulation or decision use.
  - Reviewer: Research owner or person responsible for the intended use.

- **Privacy / data-boundary review:** Check search queries, uploaded sources, notes, excerpts, and outputs for personal, confidential, proprietary, or restricted information.
  - Look for: Sensitive information entered into an unapproved tool or reproduced unnecessarily in the research output.
  - Timing: Before prompting and before sharing.
  - Reviewer: Information owner or privacy-aware reviewer.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate when the source itself is unclear, outdated, missing, or conflicts with another approved source.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.
- Escalate when wording concerns vulnerable groups, culture, crisis, complaints, or public reputation and the reviewer lacks the context, authority, or approved process to confirm safe use.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — verify all facts and sources**.

---

## 6. AI Blind Spot Focus

**Risk focus:** False Completeness

**Prompt focus:** Before prompting, give the AI the research purpose, audience, date sensitivity, jurisdiction, accepted source types, and required level of certainty. Ask it to state assumptions, likely missing perspectives, source limits, and what evidence could change the answer.

**Human review focus:** The reviewer should check source quality, recency, missing perspectives, and whether the overview sounds complete while omitting decisive evidence or limits.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the overview may omit the reason the question is being asked, the local decision context, known minority views, recent changes, or decisive sources that matter to this organisation.

**Do not rely only on:** a rounded overview. Balanced-looking research can still miss the source or caveat that matters.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Calibrated Research (HK)
- HK Safe AI Use Pack and Prompt Pattern Library.md — Hallucination Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Pre-Task Calibration

---

## 8. Main Risks

- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: Source Hallucination (High)** — AI can produce plausible-looking citations that do not exist or do not support the stated claim. A false citation may be hard to distinguish by reading alone. Verify that the source exists and that it supports the claim through a trusted database, publisher, original document, or other authoritative source. In church and nonprofit contexts, unverified citations in public communications, grant applications, or policy submissions can damage credibility and lead readers to rely on unsupported claims.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: False Completeness (High)** — AI may produce a well-rounded overview that feels complete while missing decisive sources, recent evidence, minority positions, or the one assumption that changes the conclusion.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Knowledge Cutoff Blindness (High)** — AI may present older information as if it were current, especially when current sources are not supplied, retrieved, or checked. For fast-moving topics — regulations, market conditions, organisational structures — the information may be significantly outdated.
- **[[Risk Taxonomy#3.2 Source Grounding / Evidence|Source Grounding / Evidence]]: False Consensus (Medium)** — AI may present one perspective or interpretation as if it were universally agreed, when the topic is in fact genuinely contested. Research output appears settled when it is not.
- **[[Risk Taxonomy#3.7 Tone / Representation / Cultural Sensitivity|Tone / Representation / Cultural Sensitivity]]: Confidence Without Calibration (High)** — AI expresses certainty about genuinely contested or uncertain factual claims. Users interpret confident tone as a signal of accuracy. There is no visible marker distinguishing well-established fact from AI speculation.

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
| Source Hallucination | **Instruction** | For each material claim, provide the source title, publisher or owner, publication date, and a quotation or precise location that supports it. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Source Hallucination | **Rule** | Do not invent a source, citation, author, date, quotation, URL, or study. Mark unsupported claims `{VERIFY}`. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Source Hallucination | **Output Format** | Use a claim-to-source table and a separate list of claims that still need verification. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| False Completeness | **Instruction** | State the search scope, source types used, important exclusions, missing viewpoints, and questions the research does not answer. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| False Completeness | **Rule** | Do not present the overview as complete or comprehensive merely because it covers several sources or viewpoints. State the limits of the search and unresolved gaps. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Knowledge Cutoff Blindness | **Rule** | State the date boundary of the available evidence and identify claims requiring a current source check. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| False Consensus | **Instruction** | Distinguish established agreement, majority view, credible disagreement, limited evidence, and unresolved questions. | [[Prompt Enhancement Patterns#5.3 Context and Caveat Preservation Control\|Context and Caveat Preservation Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| Confidence Without Calibration | **Audience / Tone / Language** | Match certainty to the strength and consistency of the evidence. Do not use confident wording for weak, indirect, or disputed support. | [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.
- If sensitive data was already entered into an unapproved tool, output review cannot undo exposure. Escalate according to privacy / incident process.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Safety Checklist - Work.md — Human review reminders
- Hallucination Defence Guide.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Source-Grounded Q&A
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before using research output, ask what may be missing. Verify sources, dates, disputed points, current evidence, and whether the overview is complete enough for the decision it will support.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
