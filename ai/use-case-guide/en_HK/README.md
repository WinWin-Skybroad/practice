---
title: Win.Win AI Use Case Guide
created: 2026-07-01
updated: 2026-08-10
version: "1.0"
tags:
  - WinWin-Skybroad
  - use-case-guide
  - bundle
  - index
  - reviewer-centred
status: active
type: bundle-index
source-role: master
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Win.Win AI Use Case Guide

**Author:** Win.Win@Skybroad  
**Contact:** winwin.skybroad@gmail.com  
**Release:** 1.0 | September 2026  
**Licence:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) — Free to share and adapt with attribution

> [!note] Master Source:  
> This is the `en_HK` folder — the master source for the **Win.Win AI Use Case Guide**. All other language folders (`tc_HK/`, `sc_HK/`) are translations of this document. Content updates are made here first, then carried across to other language folders.

---

## What This Is

**Win.Win AI Use Case Guide** is a practical guide for using AI in everyday organisational work without giving AI the final say.

This guide is organised by task. You do not need to read everything before you begin. Start with the task you are doing now, open the matching use-case page, and use the review checks before the AI output is sent, shared, approved, published, or acted on.

This guide helps individuals, churches, nonprofits, and SMEs choose sensible AI tasks, prepare better prompts, understand the risks, apply safeguards, escalate sensitive matters, and decide whether an AI output should be approved, corrected, or stopped.

It is a companion to **Win.Win AI Essentials**. The Essentials materials explain the foundation. This guide shows how to apply that foundation to real tasks.

**Using these materials does not guarantee that an AI task will be safe, compliant, or successful. The reader and the organisation remain responsible for their own decisions.**

These materials are shared for general information and independent use. They are not consulting services, legal advice, compliance certification, technical implementation guidance, financial advice, medical advice, counselling advice, theological advice, or pastoral counsel.

---

## New Here? Start With These

Not sure where to begin? Open the page that matches your situation.

| Entry point | Open this |
|---|---|
| Individual or new reader — quick orientation and first entry point | [[Start Here]] |
| Need to understand how this guide works after choosing an entry point | [[How To Use This Guide]] |
| Church or ministry | [[Church Quick Start]] |
| SME or business | [[SME Quick Start]] |
| Nonprofit | [[Nonprofit Quick Start]] |
| Need a quick approve/correct/escalate tool | [[Reviewer Decision Card]] |
| Want to understand human review risks and AI blind spots | [[Human Review Risk Library]] |
| Need to choose a safe first AI task | [[Choosing Your First Use Case]] |
| Ready to turn a use-case page into a workflow | [[Use Case Workflow Template]] |
| Running a first pilot | [[Pilot And Stop Rule Card]] |
| Want to customise, translate, extend, or maintain this guide | [[Author and Editor Guide]] |

The quick-start pages help you enter this guide without opening every file first. They do not remove the need for review, safeguards, or escalation.

---

> [!note] AI Blind Spot  
> This guide uses one important idea for both prompting and review: **AI Blind Spot**. AI can make an answer look careful, complete, and well judged, while still missing the real-world context behind the task. It may not know the relationship history, local practice, professional instinct, authority limits, verification needs, or consequences that matter. A better prompt can reduce this risk, but a responsible person still needs to check whether the output fits the real organisation, real people, real authority, and real consequences before it is used or approved.

> [!note] AI Blind Spot Guide companion  
> The **Win.Win AI Blind Spot Guide** is the companion guide for examining AI Blind Spot risks in more depth. These risks may involve relevant context missing from or inadequately represented in the task basis, lived or local understanding, professional instinct, authority, accountability, independent verification, recipient impact, operational memory, or consequences that AI cannot reliably hold.
>
> The current detailed focus of the **Win.Win AI Blind Spot Guide** is identifying and eliciting unstated context. Unstated context is relevant context that is absent from, incomplete in, or not adequately represented in the task basis. It may be known by people, available in current approved records, held in both, or of unclear source.
>
> Related guidance covers approved-source retrieval and extraction, representability, safe conversion, human-only handling, verification, accountable or specialist review, stopping, and escalation after context is identified or surfaced. **Organisational Context Handling** gives concise wider current-task orientation for locating and handling context, but it is not a complete knowledge-management, records-management, enterprise-retrieval, preservation, or RAG framework. Surfaced context is not automatically entered into AI or recorded; preservation is a separate governed decision.
>
> Use the **AI Blind Spot Control Map** to choose the relevant control family. Use **Organisational Context Handling** for the wider current-task source and handling questions, and **Unstated Context Control** where relevant context is absent from, incomplete in, or not adequately represented in the task basis.

> [!note] About the file format:  
> These files are designed to work best in the free note-taking app [Obsidian](https://obsidian.md/). However, you do not need Obsidian to use them. You can open any file in a plain-text editor, copy the content into Microsoft Word, or read it directly on screen. Outside Obsidian, formatting may look slightly different, but all content will be preserved.

---

## How This Guide Is Organised

This guide has two layers. The layer names describe how readers use the material, not whether one layer is more important than the other.

| Layer | Purpose | What it contains | When to use it |
|---|---|---|---|
| **Practical Layer** | Helps readers apply this guide to a real AI-supported task. | [[Start Here]], quick-start pages, [[Use Case Register]], use-case pages, [[Source Packet Before Prompting]], [[Reviewer Decision Card]], [[Escalation Guide]], workflow templates, record templates, and pilot or learning cards. | Start here when choosing a use case, preparing source material or a prompt, reviewing an output, recording a decision, or deciding whether to stop or escalate. |
| **Reference Layer** | Explains the risks, methods, controls, and authoring rules that support consistent use of the Practical Layer. | [[How To Use This Guide]], [[Author and Editor Guide]], [[Risk Taxonomy]], [[Human Review Patterns]], [[Human Review Risk Library]], [[Prompt Enhancement Patterns]], and [[Mitigation Library]]. | Consult this layer when a risk, review method, prompt control, mitigation, terminology, adaptation, or maintenance question needs more explanation. |

A use-case page should be usable on its own for ordinary task-level review. New readers do not need to read every Reference Layer file before using this guide. Start with the Practical Layer, then use the Reference Layer when the task or review needs deeper explanation. Organisations should still use the Reference Layer over time when training reviewers or adapting and maintaining this guide.

---

## Use Case Approval Level Legend

This section explains the approval level used for each type of AI use case in this guide.

The approval level does **not** mean that a specific AI output is automatically approved. It only describes whether this kind of task is generally suitable for AI-supported work, and what conditions or safeguards are needed before the output can be used.

For example, a use case may be marked as **Generally approved** because AI can usually help draft or structure that type of work. However, the actual AI output still needs human review before it is sent, shared, approved, published, or acted on.

In short:

- **Approval level** tells you whether this type of AI task is suitable to try.
- **Reviewer decision** tells you whether a specific AI output should be approved, corrected, or escalated.

A use case being listed as approved does not remove the need for review, source checking, privacy checking, authority checking, or escalation where required.

| Approval level | Practical meaning |
|---|---|
| **Generally approved** | AI may be used for this task under the normal use-case workflow, provided the assigned reviewer checks the output before it is used. |
| **Generally approved if non-confidential** | Use this only when the input does not include confidential, sensitive, or personal data that the tool or workflow is not approved to handle. |
| **Use with caution** | AI may help with drafting or spotting issues, but the output needs stronger review and may need escalation before use. |
| **Approved as a thinking aid** | AI may help with brainstorming, framing, comparison, or checking questions. The output should not be used directly as the final message, decision, policy, advice, approval, or record without a separate human-authored or human-approved result. |
| **Escalate before relying on output** | Ordinary review is not enough. Do not approve, send, publish, act on, or rely on the output until the right qualified or authorised person has reviewed it under the approved process. |

---

## Choose Your Path

Use this section to decide how to enter this guide. You do not need to read every file before using it. Start with the path that matches your current need.

---

### Path 0 — New to This Guide

Use this path if you are opening this guide for the first time and are not sure where to begin.

- Open [[Start Here]] for quick orientation.
- Open [[How To Use This Guide]] if you want to understand how Practical Layer and Reference Layer files, escalation guidance, and recordkeeping templates work together.
- Then open the quick-start page that best matches your organisation:
  - [[Church Quick Start]]
  - [[Nonprofit Quick Start]]
  - [[SME Quick Start]]
- Pick one ordinary task that your organisation already performs with AI.
- Open the matching use-case page.
- Read **What This Could Cost You** and **How To Review This Output** before using the AI output.
- Review the output before it is sent, published, relied on, or used.

---

### Path A — I already know the use case

Use this path when you already know what AI task you want to review, such as drafting a communication, summarising meeting notes, translating a notice, or preparing a bilingual version.

- Open the relevant use-case page.
- Read **What This Could Cost You** to understand the practical risk.
- Use **How To Review This Output** to guide the task-specific review before approving, correcting, or escalating the AI output.
- Check **When To Escalate Instead of Approve** if the output may exceed the reviewer’s authority, expertise, evidence, approved process, or responsibility.
- Open [[How To Use This Guide]] only if you need help understanding approval levels, Reference Layer files, reviewer tools, recordkeeping, or how the use-case page fits into this guide.
- Use the related reference files only when deeper guidance is needed.

---

### Path B — Improve a Prompt

Use this path when the AI task is allowed, but the prompt needs better structure, clearer source material, or stronger safeguards before the output is generated.

- Start with the relevant use-case page so the prompt improvement stays connected to a real task.
- Use [[Source Packet Before Prompting]] if the task depends on documents, meeting notes, policies, emails, webpages, or other source material.
- Open [[Prompt Enhancement Patterns]].
- Choose only the prompt enhancement that matches the actual risk.
- Add the prompt enhancement to the right part of the Win.Win AI Essentials prompt structure, usually **Instruction**, **Rule**, **Output Format**, or **Reminder / Review Note**.
- Keep source material under **Content** at the end of the prompt.
- Open [[How To Use This Guide]] if you are unsure how source preparation, prompt enhancement, human review, and escalation fit together.
- Do not rely on better prompting alone. Still perform human review after the AI output is generated.

---

### Path C — Train Reviewers

Use this path when you are training reviewers, setting up an internal AI review process, or deciding how your organisation should review AI outputs across several use cases.

- Read [[How To Use This Guide]] to understand the operating method behind this guide.
- Start with the relevant use-case page so the review stays connected to a real task.
- Read [[Human Review Patterns]] to understand the common ways AI output should be checked.
- Read [[Human Review Risk Library]] to understand the named human-review risks used in the use-case pages.
- Use [[Risk Taxonomy]] when you need broader risk categories behind the use-case risks or the meaning and definition route of a named risk or failure mode.
- Use [[Prompt Enhancement Patterns]] and [[Source Packet Before Prompting]] when the issue starts before the AI output is created.
- Use [[Mitigation Library]] when you need controls beyond prompting, such as source checks, reviewer roles, approval records, or workflow safeguards.
- Use [[Reviewer Decision Card]] to decide whether the reviewer can approve, should correct, or must stop and escalate.
- Use [[Escalation Guide]] when the output may exceed the reviewer’s authority, expertise, evidence, approved process, or responsibility.
- Use the use-case pages to practise task-specific review with real or realistic examples.

You do not need to open every reference file for every AI task. Use the relevant use-case page first, then open the deeper reference files only when the review question requires them.

---

### Path D — Adapt This Guide for Your Organisation

Use this path when your organisation wants to turn this guide into a local guide, internal workflow, or training resource.

- Read [[How To Use This Guide]] to understand this guide structure before adapting it.
- Read [[Author and Editor Guide]] before changing this guide structure, wording, language, controls, links, or publication files.
- Read [[Use Case Page Template]].
- Copy the template structure.
- Keep the approval level, review method, escalation boundary, and related reference files clear.
- Add your organisation’s own risks, reviewers, escalation routes, source checks, and approval process.
- Use [[Reviewer Decision Card]] to define who may approve, who must correct, and when escalation is required.
- Use [[AI Output Record Template]] when the local workflow needs a review trail, approval record, or later audit reference.

---

### Path E — Implement One Use Case

Use this path when you are ready to pilot or implement one AI use case in a real workflow.

- Read [[How To Use This Guide]] if this is the first time your organisation is turning a use-case page into a real workflow.
- Read [[Choosing Your First Use Case]] before selecting a pilot task.
- Choose one manageable task that the organisation already performs.
- Gather the [[Source Packet Before Prompting]] before prompting AI.
- Turn the selected use-case page into a local workflow using [[Use Case Workflow Template]].
- Assign a named reviewer and clarify who has approval authority.
- Use [[Reviewer Decision Card]] during review to decide whether to approve, correct, or escalate.
- If piloting, use [[Pilot And Stop Rule Card]] to decide when the pilot should continue, pause, change, or stop.
- Keep a simple [[AI Output Record Template]] for outputs that leave the organisation, affect people, or support real decisions.
- Use [[First Mistake Review]] when something goes wrong or when the workflow needs improvement.

---

## Full Asset Index

### Start and Audience Entry Pages

| File | What it covers |
|---|---|
| [[Start Here]] | Orientation to this guide, five starter tasks, and how to choose and read a use-case page |
| [[Church Quick Start]] | Five tasks most useful for churches and ministry organisations |
| [[SME Quick Start]] | Five tasks most useful for small and medium businesses |
| [[Nonprofit Quick Start]] | Five tasks most useful for nonprofits |

---

### Implementation and Rollout Cards

| File | What it covers |
|---|---|
| [[Choosing Your First Use Case]] | How to start with a boring, reviewable, reversible AI task rather than the most impressive one |
| [[Source Packet Before Prompting]] | What source material, audience, exclusions, authority limits, and review basis to gather before prompting |
| [[Use Case Workflow Template]] | How to turn one use-case page into a local workflow |
| [[Pilot And Stop Rule Card]] | How to run a pilot small enough to pause or stop safely |
| [[AI Output Record Template]] | A simple record for source version, prompt/task brief, reviewer, corrections, approval, and final output |
| [[First Mistake Review]] | How to treat the first AI mistake as a workflow design signal, not only a personal error |

---

### Five Starter Use Cases

These are the best first use-case pages because they are common, practical, and reviewable.

| Use Case | What it covers |
|---|---|
| [[Use Cases/Draft Communications]] | Draft emails, newsletters, announcements, notices, bulletins, event communications, and social media posts |
| [[Use Cases/Summarise Meeting Notes]] | Summarise meeting notes or minutes into structured summaries |
| [[Use Cases/Draft WhatsApp Broadcasts]] | Draft WhatsApp / Telegram broadcasts |
| [[Use Cases/Produce Bilingual Versions]] | Produce bilingual English and Traditional Chinese versions |
| [[Use Cases/Summarise Documents]] | Summarise documents, reports, board papers, or committee papers |

---

### Full Use-Case Library

#### Communications and Drafting

| Use Case | What it covers |
|---|---|
| [[Use Cases/Draft Communications]] | Draft emails, newsletters, announcements, notices, bulletins, event communications, and social media posts |
| [[Use Cases/Draft Communications Sample Overall Prompt]] | Worked example showing how the Draft Communications base prompt and use-case prompt enhancements fit together in one complete prompt |
| [[Use Cases/Draft WhatsApp Broadcasts]] | Draft WhatsApp / Telegram broadcasts |
| [[Use Cases/Draft WhatsApp Broadcasts Sample Overall Prompt]] | Worked example showing how the Draft WhatsApp Broadcasts base prompt and use-case prompt enhancements fit together in one complete prompt |
| [[Use Cases/Draft Internal Memos]] | Draft internal memos, internal communications, and administrative notices |
| [[Use Cases/Draft Admin Templates]] | Draft internal administrative documents, templates, or standard letters |
| [[Use Cases/Draft Reports And Presentations]] | Draft reports, proposals, or presentations |
| [[Use Cases/Draft Event Planning Checklists]] | Draft event planning checklists and schedules |

#### Meetings, Documents, and Knowledge

| Use Case | What it covers |
|---|---|
| [[Use Cases/Summarise Meeting Notes]] | Summarise meeting notes or minutes into structured summaries |
| [[Use Cases/Summarise Meeting Notes Sample Overall Prompt]] | Worked example showing how the Summarise Meeting Notes base prompt and use-case prompt enhancements fit together in one complete prompt |
| [[Use Cases/Summarise Documents]] | Summarise documents, reports, board papers, or committee papers |
| [[Use Cases/Summarise Documents Sample Overall Prompt]] | Worked example showing how the Summarise Documents base prompt and use-case prompt enhancements fit together in one complete prompt |
| [[Use Cases/Answer Internal FAQs]] | Answer internal FAQs from approved documents |
| [[Use Cases/Answer Policy Questions]] | Answer policy questions from existing policy documents |

#### Bilingual and Hong Kong Context

| Use Case | What it covers |
|---|---|
| [[Use Cases/Produce Bilingual Versions]] | Produce bilingual English and Traditional Chinese versions |
| [[Use Cases/Produce Bilingual Versions Sample Overall Prompt]] | Worked example showing how the Produce Bilingual Versions base prompt and use-case prompt enhancements fit together in one complete prompt |
| [[Use Cases/Translate General Communications]] | Translate general communications |
| [[Use Cases/Research HK Topics]] | Research Hong Kong-specific topics |
| [[Use Cases/Verify HK Regulatory Questions]] | Verify Hong Kong legal, regulatory, or compliance questions |

#### Research and Reliability

| Use Case | What it covers |
|---|---|
| [[Use Cases/Research General Topics]] | Research and fact-find on general topics |
| [[Use Cases/Check Confidence Before Research]] | Check confidence and uncertainty before a research task |
| [[Use Cases/Check AI Output Reliability]] | Check AI output reliability / hallucination risk |

#### Governance, Policy, and Personal Data

| Use Case | What it covers |
|---|---|
| [[Use Cases/Assess Personal Data Tasks]] | Assess whether a task involves personal data / PDPO pre-check |
| [[Use Cases/Draft Organisational Policies]] | Draft organisational policies |
| [[Use Cases/Extract Invoice Or Document Data]] | Extract invoice or document data from standardised digital documents |

#### Nonprofit and People-Facing Operations

| Use Case | What it covers |
|---|---|
| [[Use Cases/Draft Grant Applications]] | Draft grant applications or funding report sections |
| [[Use Cases/Draft Volunteer Roles]] | Draft volunteer onboarding materials and role descriptions |

---

### Guide and Reference Files

| File | What it covers |
|---|---|
| [[How To Use This Guide]] | Operating method for how use-case pages, source preparation, prompt safeguards, reviewer decisions, escalation, recordkeeping, and Practical Layer and Reference Layer files work together |
| [[Author and Editor Guide]] | How to author, edit, customise, translate, validate, publish, and maintain this guide without weakening its governance boundaries |
| [[Use Case Register]] | Index of all use cases with review focus and reliability distinction |
| [[Human Review Patterns]] | Review methods behind the use-case pages, including source comparison, authority, privacy, bilingual, human-grounded, and qualified review patterns |
| [[Risk Taxonomy]] | Classification map for risk families, including AI Blind Spot / Context Risks, plus the named risk and failure-mode index |
| [[Human Review Risk Library]] | Practical explanations of review risks, failure patterns, and AI blind spots, including what action counters them |
| [[Prompt Enhancement Patterns]] | Complete copyable prompt enhancements and worked examples; prompt enhancements reduce risk before output and do not replace human review after output |
| [[Mitigation Library]] | Controls beyond prompt wording, including approved tools, source checks, reviewer assignment, output limits, and escalation |
| [[Escalation Guide]] | When to stop and ask a responsible, qualified, or authorised reviewer |
| [[Reviewer Decision Card]] | One-page approve / correct / stop-and-escalate decision aid |
| [[Use Case Page Template]] | Public-facing reviewer-centred template for creating new use-case pages |

---

## Release History

> A **release** is the published snapshot of the entire Win.Win AI Use Case Guide, while a document **version** is the revision number of an individual document.
>
> *These materials will be updated as feedback is received and AI governance practice in Hong Kong develops. Check the release history for changes.*

| Release | Date | Notes |
|---|---|---|
| 1.0 | September 2026 | Initial release |

---

## Contact and Feedback

Feedback on **clarity, practicality, reviewer usefulness, and accuracy** of these materials is welcome.  
Please use the feedback form as the primary feedback channel:  
[Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)

To report a specific error or publicly suggest a document change:  
[GitHub Issues](https://github.com/WinWin-Skybroad/practice/issues)

For private enquiries or to start a conversation about your organisation’s specific situation:  
winwin.skybroad@gmail.com

---

**Win.Win@Skybroad**  
https://github.com/WinWin-Skybroad/practice/tree/main/ai/use-case-guide/en_HK

*Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
