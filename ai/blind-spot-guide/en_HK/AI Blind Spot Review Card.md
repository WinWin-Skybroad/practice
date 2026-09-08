---
title: AI Blind Spot Review Card
created: 2026-07-06
updated: 2026-09-07
version: "1.0"
status: active
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
locale: en_HK
type: guide
tags:
  - review-card
  - controls
---

# AI Blind Spot Review Card

## 1. Purpose and Scope

Use this page as a **short current-task review card** when an AI-supported output may look usable but still needs a human Blind Spot check before it is used, sent, approved, published, relied on, or acted on.

The card follows the Win.Win AI Blind Spot Guide operating sequence: identify the risk, consult the Control Map, select the relevant Control or Controls, use applicable Methods or detailed guidance, involve an Accountable Route where required, and make a review decision.

Use [[AI Blind Spot Risk Library]] for fuller risk explanations and [[AI Blind Spot Control Map]] for canonical Controls, Methods, and Accountable Routes. Use the detailed unstated-context sequence in this card only when **Unstated Context Control** is relevant.

---

## 2. Name the task

```text
Use case or task:
Output type:
Audience:
Intended use:
Who may be affected:
Owner:
Reviewer:
Approval owner if different:
Task basis, including source packet, prompt, approved material actually used, review basis and current decision record:
```

This keeps the review grounded in a real situation, not a general discussion about AI.

---

## 3. Name the likely AI Blind Spot risk

Choose the risk that sounds most like the problem you are seeing. More than one may apply.

If you can tell that something important may be missing or unresolved but cannot yet identify the specific risk, start with **AI Blind Spot** and use [[AI Blind Spot Risk Library]] to narrow it.

- **AI Blind Spot** — Something important may be missing or unresolved, but the more specific risk is not yet clear.
- **Unwritten Context Gap** — Relevant context may be missing from, incomplete in, or not adequately represented in the task basis.
- **Reader Interpretation Gap** — Intended readers may understand the wording differently from what the sender means.
- **Recipient Impact Blindness** — Even if the wording is understood correctly, the output may affect a person or group differently in ways that matter, such as dignity, trust, relationships, reputation, or practical interests.
- **Authority Boundary Blindness** — The output may appear to approve, promise, decide, or authorise beyond the actual authority available.
- **Materiality Judgement Gap** — The output may give the wrong weight to something that could change a decision or consequence. **Use this question: Material relative to what decision or consequence?**
- **Local or jurisdiction-specific blind spot** — The output may not fit the actual place, sector, authority, or local source.
- **AI Self-Validation Illusion** — AI output, including another AI response, may be mistaken for independent verification.
- **User-Pressure Drift** — Caution may be weakened after pushback without reliable new evidence or an authoritative basis.
- **Anomaly Instinct Gap** — Unusual figures, dates, sequences, wording, formats, or omissions may be missed.
- **Bicultural Register Gap** — Literal wording may carry the wrong tone, social signal, or authority in the real context.
- **Local Operational Memory Gap** — Setup, timing, access, dependencies, workarounds, or lessons from past problems may be missing.

**Other:** ________________________________________

**Quick distinction — meaning and impact**

- **Reader Interpretation Gap:** Could reasonable intended readers understand what this wording says differently because of their role, relationship, timing, history, or context?
- **Recipient Impact Blindness:** Even if readers understand it the same way, could receiving, acting on, or being identified through the output affect a particular person or group materially differently?

Both risks may apply to the same output. Use these questions to distinguish the mechanisms being checked; do not treat the risks as mutually exclusive.

---

## 4. Select the relevant Control or Controls

Use [[AI Blind Spot Control Map]]. Record all Controls that are materially relevant to this risk in this task.

```text
Relevant Control(s):
```

Do not assume a one-risk-to-one-Control relationship. Do not treat Unstated Context Control as the universal first Control merely because it is the most developed Control in this guide.

---

## 5. Use relevant Methods and guidance

For each selected Control, identify any canonical Method or detailed guidance that is useful for this task.

```text
Relevant Method(s) or detailed guidance:
```

A canonical Method is a reusable way of carrying out or supporting a Control. Do not turn an ordinary action, reviewer role, or sign-off step into a Method merely to fill this field.

---

## 6. If Unstated Context Control applies, use the detailed unstated-context sequence

Skip this section when Unstated Context Control is not relevant. Here, **unstated context** means relevant context that is absent from, incomplete in, or not adequately represented in the task basis.

Use these review questions:

```text
Could relevant context be absent, incomplete, or not adequately represented in the task basis?
```

```text
If suitable people may hold relevant context, what may they know or use implicitly that is missing from the source packet, prompt, or review basis?
```

Then check the source location:

- [ ] people;
- [ ] approved records;
- [ ] both;
- [ ] unclear.

If a current approved record exists, retrieve the source and extract the task-relevant approved material before asking people to recreate it.

Check **representability** — how well the relevant context can be expressed clearly and safely enough for this task:

- [ ] clear;
- [ ] partial;
- [ ] difficult;
- [ ] unsafe or inappropriate;
- [ ] not fully expressible for AI use.

Use [[Elicitation Techniques]] only if a suitable person may carry context implicitly and a specific, focused question is safe and permitted.

Then choose the minimum current-task handling route:

- add the approved minimum to the task basis, only if it is accurate, necessary, permitted, current, and safe;
- use safe conversion: give AI only the necessary safe effect. This may be a fact or source, a constraint or wording rule, an omission or review instruction, an approval boundary or human-drafting requirement, or an escalation trigger;
- keep the underlying context human-only and use an authorised person to guide drafting, review, approval, timing, or escalation;
- verify it against a sufficiently independent approved source, tool, record, or suitably accountable reviewer;
- route it to an accountable or specialist reviewer;
- stop and escalate;
- do not use or record it.

The seven routes are protected handling choices within Unstated Context Control. Completing them does not prove that every other relevant Control has been satisfied.

---

## 7. Use Accountable Routes and check standing

Use the canonical Accountable Routes in [[AI Blind Spot Control Map]] if responsibility, authority, expertise, independence, approval, or escalation must move elsewhere.

```text
Relevant Accountable Route(s):
```

Before choosing **Approve** or **Correct then approve**, confirm:
- **reviewer standing** — whether the reviewer is suitably placed to perform the required review; and
- **approval standing** — whether the person or body has the authority and accountability to approve the output for its intended use.

Use [[Templates/Reviewer Standing Check]] if either is unclear.

---

## 8. Decide

Choose one:

```text
Approve
Correct then approve
Stop and escalate
```

A good review does not always end in approval. Sometimes the safest and most responsible answer is to stop and route the task to someone with the right authority, expertise, independence, or standing.

---

## 9. Preserve only what should not be lost

If review surfaced a safe, reusable exception, warning, operational lesson, local practice, prior decision, relationship-sensitive warning, or other context, decide separately whether it should be preserved through the approved process. Here, **preservation** means deciding whether useful context or a lesson should be kept through an approved process for later reuse.

Do not make preservation automatic. Use [[Templates/Exception Note Template]] only if the context is:
- accurate;
- necessary;
- permitted;
- current;
- safe;
- sufficiently reliable;
- reusable;
- appropriate to preserve; and
- assigned to an accountable owner and approved location.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Blind Spot Guide Feedback Form](https://forms.gle/se5ruqaZeytDoFENA)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
