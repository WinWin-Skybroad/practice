---
title: Unstated Context Control
created: 2026-07-06
updated: 2026-09-07
version: "1.0"
status: active
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
locale: en_HK
type: guide
tags:
  - unstated-context
  - controls
---

# Unstated Context Control

## 1. Purpose and Scope

Use this page when relevant context may be **absent from, incomplete in, or not adequately represented in the task basis**.

**Unstated Context Control** is the current detailed Control in the Win.Win AI Blind Spot Guide. Its most developed practical guidance concerns identifying and safely eliciting unstated context. Related current-task guidance also covers source location, retrieval and extraction, representability, safe conversion, human-only handling, verification, accountable review, stopping, and escalation.

This page explains how to:
- recognise unstated context;
- identify likely sources;
- assess representability;
- use Safe Elicitation Method when suitable; and
- select the minimum current-task handling, such as approved retrieval, safe conversion, human-only handling, verification, accountable review, stopping, or escalation.

Unstated Context Control can support several AI Blind Spot risks but does not solve every risk. Use [[AI Blind Spot Control Map]] to identify other relevant Controls, Methods, or Accountable Routes.

It does not provide a complete organisational-context, knowledge-management, records-management, or RAG framework.

---

## 2. What unstated context means

**Unstated context** is any relevant context that is absent from, incomplete in, or not adequately represented in the task basis.

The **task basis** includes the source packet, prompt, approved material actually used, review basis, and current decision record available for the task.

AI can work with the information made available to it, but it does not live inside the organisation. It does not know what people quietly remember. It does not feel the timing of a message. It does not hold authority. It does not carry the consequences if the output is used wrongly.

A draft can look clear, balanced and complete while still missing something a human reviewer needs before safe use.

This includes what people know, remember, sense or normally do but have not put into the source material, prompt or review basis.

---

## 3. Recognition angles

### 3.1 How Context Became Absent, Incomplete, or Thin in the Task Basis

- **unwritten** — not recorded anywhere;
- **unprompted** — recorded or known somewhere but not supplied to, retrieved for, or adequately represented in the task basis;
- **partly recorded** — some relevant parts are recorded, but important limits, reasons, exceptions, or consequences are missing;
- **distributed** — spread across people, records, prior decisions, or related tasks rather than available in one complete source;
- **current** — known or obvious in the present situation but not yet reflected in the task basis.

---

### 3.2 How People May Carry or Express It

- **tacit** — known through experience but hard to list or explain on demand;
- **accumulated or experiential** — built through repeated tasks, related work, prior decisions, workarounds, mistakes, near-misses, and lived experience;
- **difficult to articulate** — recognised or acted on by people but not easily expressed as a clear fact, rule, or instruction;
- **relational** — tied to trust, history, role, audience reaction, or reputation;
- **operational** — tied to how a task, venue, supplier, process, or team actually works;
- **bicultural/register-based** — tied to tone, formality, language, culture, or social meaning.

---

### 3.3 Why It May Require Controlled Handling

- **sensitive** — inappropriate to disclose broadly or to place in ordinary documents or AI interactions;
- **authority-based** — tied to who may approve, decide, promise, refuse, commit, or send;
- **material** — tied to what would change a decision, priority, threshold, approval, or consequence;
- **unsafe or inappropriate** — unsuitable to place in AI or ordinary records without a permitted and accountable route;
- **not fully expressible for AI use** — cannot be fully expressed for AI use without losing important judgement, nuance, or responsibility.

The same context may fit several angles at once. Source location is a separate check. Representability is a separate check. The canonical risk name **Unwritten Context Gap** is not limited to literally unwritten information.

---

## 4. Why experienced humans and AI differ

A human may also receive incomplete instructions. An experienced human is not automatically complete or correct.

The distinctive concern addressed here is that an experienced person often carries more than the explicit task information, while AI usually receives only the task basis and other information actually made available.

```text
Experienced human
= explicit task information
+ accumulated experience
+ tacit judgement
+ organisational memory
+ local and relational awareness

AI
= the task basis and other information actually made available
```

The missing context may come from repeated tasks, related tasks, prior decisions, workarounds, relationships, habits, lived experience, local practice, preferences, risk appetite, timing sensitivity, informal thresholds, or what the organisation would actually approve.

---

## 5. Identify the likely source

Check the likely source location:

- people;
- approved records;
- both;
- unclear.

If a current approved record exists, retrieve the source and extract the task-relevant approved material before asking people to recreate it.

If the context remains implicit, partial, difficult to express, unsafe to state, or unclear, use a suitable route rather than forcing it into AI.

---

## 6. Assess representability

Assess representability using the closest option:

- clearly expressible;
- partly expressible;
- difficult to articulate;
- unsafe or inappropriate to state;
- not fully expressible for AI use.

Representability informs the route. It does not by itself decide whether the context matters, is reliable, is authorised, may be used, or should be preserved.

---

## 7. Why direct questions often fail

A broad question such as:

```text
Is there anything else I should know?
```

may honestly receive:

```text
No.
```

People do not always store experience as a neat list. Specific, concrete questions give memory something to attach to.

For example, instead of asking:

```text
Are there any exceptions?
```

use this question:

```text
When did we last bend, bypass, adapt, or quietly make an exception to this rule, and for whom or why?
```

The second question gives memory a concrete event to attach to.

Use [[Elicitation Techniques]] for **Safe Elicitation Method** only if a suitable person may carry context implicitly and the question is safe and permitted.

---

## 8. Minimum current-task handling

Choose one route:

- add the approved minimum to the task basis, only if it is accurate, necessary, permitted, current, and safe;
- use safe conversion: give AI only the necessary safe effect. This may be a fact or source, a constraint or wording rule, an omission or review instruction, an approval boundary or human-drafting requirement, or an escalation trigger;
- keep the underlying context human-only and use an authorised person to guide drafting, review, approval, timing, or escalation;
- verify it against a sufficiently independent approved source, tool, record, or suitably accountable reviewer;
- route it to an accountable or specialist reviewer;
- stop and escalate;
- do not use or record it.

| Context condition | Minimum route |
|---|---|
| Accurate, necessary, permitted, current, and safe for AI-supported use | Add only the approved minimum to the task basis. |
| The underlying detail should not enter AI, but its effect can be represented safely | Use safe conversion. |
| The underlying context should remain outside AI but must guide human judgement | Use human-only handling. |
| Truth, currentness, applicability, or support is uncertain | Use a sufficiently independent verification route. |
| Authority, competence, standing, or specialist judgement is needed | Route to the accountable or specialist reviewer. |
| The matter cannot be handled safely or within authority | Stop and escalate. |
| The context is irrelevant, unreliable, unnecessary, non-permitted, or unsafe to use or retain | Do not use or record it. |

Do not place sensitive, restricted, private, disputed, stale, unverified, or non-permitted context into AI.

If the underlying context should remain outside the AI tool:
- keep it reviewer-only or human-only; and
- supply only the safe minimum effect, if any.

Preservation is a separate optional decision, not an eighth current-task route.

Consider preservation only if the context or safe representation is:
- sufficiently reliable;
- necessary;
- reusable;
- permitted;
- appropriate to retain;
- assigned to an accountable owner and approved location; and
- subject to suitable access and review controls.

---

## 9. Boundary

This Control does not replace other relevant Controls, Methods, Accountable Routes, specialist judgement, or accountable human decision-making. Use [[AI Blind Spot Control Map]] for the authoritative relationships and selection rationale.

---

## 10. Practical rule

```text
Use four checks:
1. What may be missing from the task basis?
2. Where may that context exist?
3. Can it be represented safely for AI use?
4. What is the minimum handling route needed for this task?
```

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Blind Spot Guide Feedback Form](https://forms.gle/se5ruqaZeytDoFENA)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
