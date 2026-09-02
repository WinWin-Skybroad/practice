---
title: How To Use This Guide
created: 2026-07-01
updated: 2026-08-14
version: "1.0"
status: active
type: guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# How To Use This Guide

## 1. Purpose and Scope

Use [[Start Here]] when you only need a quick entry point.

Use this page when you need to understand how the files in this guide work together: use-case pages, source preparation, prompt safeguards, reviewer decisions, escalation, recordkeeping, workflow templates, and learning after mistakes.

Win.Win AI Essentials explains why responsible AI use requires Purpose, Permission, and Proof. This guide answers the next question: **then, how do I apply those responsibilities to the administrative task in front of me?**

It turns the principles into task-specific preparation, prompting, review, mitigation, escalation, approval, recordkeeping, and learning. It gives particular depth to the practical work required for P3 · Proof, while continuing to support Purpose and Permission throughout the workflow.

You do not need to read this page before every use-case page. A use-case page should be usable on its own for ordinary task-level review. Read this page when you are training reviewers, adapting this guide for an organisation, setting up a local workflow, or deciding which Practical Layer tool or Reference Layer file to open.

---

## 2. Operating Principle

Start with the use-case page in the Practical Layer, then open another Practical Layer tool or a Reference Layer file only when the task raises a source, prompt, review, escalation, recordkeeping, workflow, or improvement question.

The use-case page is the primary Practical Layer page for the task. Other Practical Layer tools help readers prepare source material, decide whether to approve or escalate, record the result, and improve the workflow. Reference Layer files explain the reusable risks, methods, controls, and authoring rules behind that practical guidance.

AI output should be treated as a draft, helper, or review aid. The reviewer and organisation remain responsible for what is sent, approved, published, relied on, or acted on.

---

## 3. How the Files Work Together

Use [[Author and Editor Guide]] when authoring, editing, customising, localising, validating, or maintaining this guide for an organisation.

| File or file group | Role in this guide | Open it when |
|---|---|---|
| [[Use Case Register]] | Finds the closest use-case page | You know the task area but not the exact page |
| Use-case pages | Give task-specific prompt, review, risk, mitigation, and escalation guidance | You are reviewing a real AI output for a defined task |
| [[Source Packet Before Prompting]] | Checks whether the input material is ready before prompting | The task depends on documents, notes, policies, emails, webpages, or other source material |
| [[Prompt Enhancement Patterns]] | Explains how targeted prompt safeguards fit into the prompt structure | The use-case page calls for a risk-specific prompt add-on |
| Sample Overall Prompt files | Show worked examples for selected starter use cases | You want to see how the base prompt and add-ons can be assembled |
| [[Human Review Patterns]] | Explains common ways to check AI output | You are training reviewers or choosing a review method |
| [[Human Review Risk Library]] | Defines named human-review risks used in the use-case pages | A use-case page names a risk and you need the meaning or cross-reference |
| [[Risk Taxonomy]] | Explains broader risk categories | You need the larger risk category behind task-specific guidance |
| [[Mitigation Library]] | Lists controls beyond prompting | The task needs source checks, reviewer roles, approval records, or workflow safeguards |
| [[Reviewer Decision Card]] | Supports the approve, correct, or escalate decision | The reviewer needs to decide what can happen to a specific output |
| [[Escalation Guide]] | Explains escalation routes and stop rules | Ordinary review may not be enough for the output |
| [[AI Output Record Template]] | Records review and approval evidence | The output needs a review trail, approval record, or later audit reference |
| [[Use Case Workflow Template]] | Turns a use-case page into a local process | An organisation wants to define who prepares, prompts, reviews, approves, records, and escalates |
| [[Pilot And Stop Rule Card]] | Controls a first pilot | An organisation is testing a use case before wider rollout |
| [[First Mistake Review]] | Supports learning after a mistake or near miss | A mistake, complaint, reviewer concern, or near miss shows that the workflow needs improvement |

This page gives the operating map. The detailed instructions belong in the individual files listed above.

---

## 4. Typical Flow

Use the relevant use-case page as the primary Practical Layer page for the task. The use-case page should normally give enough task-specific prompt, review, mitigation, and escalation guidance to begin.

- Start with the use-case page that matches the AI task.
- Use the prompt guidance on that page to prepare or improve the prompt.
- Review the AI output using the task-specific review guidance on that page.
- Check the escalation guidance on that page before approving, correcting, or using the output.
- Open another Practical Layer tool or a Reference Layer file only when deeper guidance is needed, such as:
  - [[Human Review Patterns]]: understanding the review pattern behind the task.
  - [[Human Review Risk Library]]: understanding named human-review risks mentioned in the use-case page.
  - [[Risk Taxonomy]]: understanding broader risk categories behind the task.
  - [[Prompt Enhancement Patterns]]: choosing or adapting a prompt enhancement.
  - [[Source Packet Before Prompting]]: preparing source material before prompting.
  - [[Mitigation Library]]: choosing controls beyond prompting and ordinary review.
  - [[Reviewer Decision Card]]: deciding whether the reviewer may approve, should correct, or must stop and escalate.
  - [[Escalation Guide]]: checking when the issue requires a more authorised, qualified, or responsible person.
  - [[Use Case Workflow Template]]: setting up a local workflow for one use case.
  - [[Pilot And Stop Rule Card]]: deciding whether a pilot should continue, pause, change, or stop.
  - [[AI Output Record Template]]: keeping a review or approval record when needed.
  - [[First Mistake Review]]: learning from a mistake, near miss, complaint, or reviewer concern.

Use the flow lightly. Do not turn it into a burden for every small task. Start with the use-case page, then open another Practical Layer tool or a Reference Layer file only when the task, risk, reviewer decision, escalation question, or local workflow needs deeper support.

---

## 5. Prompting, Review, Escalation, and Records

These parts are related, but they do different jobs.

| Part | What it controls | Key point |
|---|---|---|
| Source preparation | What material AI is allowed or expected to use | Good prompting cannot fix missing, outdated, or unauthorised source material |
| Prompt enhancement | What the AI is asked to do or avoid before generating output | Add only the safeguards that match the task and risk |
| Human review | Whether the output is accurate, appropriate, authorised, and usable | Review is still needed even after a strong prompt |
| Escalation | Whether ordinary review is enough | Escalate when the reviewer cannot safely approve within their role, evidence, authority, competence, or approved process |
| Recordkeeping | Whether the review and approval trail needs to be explainable later | Keep records when the output leaves the organisation, affects people, supports decisions, or may be questioned later |

Human review often needs more scaffolding than prompting because it depends on judgement about the real source, audience, authority, context, materiality, competence, and consequences. This is why this guide supports review through several different references and decision tools rather than one checklist alone.

Source preparation and prompt safeguards still matter. A complete source packet, a well-scoped prompt, and a request limited to what can realistically be reviewed can reduce avoidable errors, unsupported assumptions, unnecessary output, and rework before review begins. This can reduce review workload as AI increases output volume, but it does not lower the review standard for any output that will be used, sent, approved, published, or relied on.

Use the individual files for detailed instructions. This page is only the map of how those files fit together.

Use-case pages contain task-specific versions of prompt add-ons and review instructions. The Reference Layer pattern files explain the reusable method behind them. When adapting this guide, start with the relevant pattern, remove unrelated items, and add the sources, checks, limits, reviewer roles, and escalation conditions that matter to the particular task. Do not rewrite a risk or review pattern into a different meaning merely to make it sound specific.

---

## 6. Companion Guides

Use-case pages may point to a companion guide when deeper recognition or control selection is useful. Each use-case page retains only its task-specific trigger. This section is the canonical explanation in this guide of the companion guide’s purpose, current focus, scope boundaries, and internal routes.

---

### 6.1 Win.Win AI Blind Spot Guide

Use the **Win.Win AI Blind Spot Guide** when a task-level review points to an AI Blind Spot or when a polished AI-supported output still appears unsafe, incomplete, overconfident, unauthorised, or poorly grounded in the real situation.

The current detailed focus of the **Win.Win AI Blind Spot Guide** is identifying and eliciting unstated context. Related guidance also helps locate current approved records, extract task-relevant approved material, assess representability, choose safe conversion or human-only handling, verify sufficiently independently, involve accountable or specialist reviewers, and stop or escalate.

Use the Blind Spot Guide’s **AI Blind Spot Control Map** for deeper control selection. Use **Organisational Context Handling** for the wider current-task source-location and handling questions, and **Unstated Context Control** when relevant context is absent from, incomplete in, or not adequately represented in the task basis.

A use-case page remains the primary task-level working page. The Blind Spot Guide is not a prerequisite for ordinary review.

---

## 7. Practical Rule

Use the use-case page for the task. Use this page to decide which Practical Layer tool or Reference Layer file to open next.

Do not rely on AI output because it sounds complete. Rely on it only after the right review, correction, escalation, and recordkeeping decisions have been made.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
