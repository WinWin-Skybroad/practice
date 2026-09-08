---
title: Translation Notes for en_HK, tc_HK, and sc_HK
created: 2026-07-06
updated: 2026-09-07
version: "1.0"
status: active
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
type: translation-notes
tags:
  - translation
  - multilingual
  - ai-blind-spot
---
# Translation Notes for en_HK, tc_HK, and sc_HK

## 1. Purpose and Scope

Use this file as **translation implementation guidance specific to the Win.Win AI Blind Spot Guide** for authorised Traditional Chinese or Simplified Chinese editions.

It covers:
- source pairing;
- structural alignment;
- control strength;
- Hong Kong localisation;
- safe-context and authority boundaries; and
- bilingual-review expectations.

This file does not create or override controlled terminology, canonical definitions, page responsibilities, or the architecture of the Win.Win AI Blind Spot Guide. If there is a conflict, follow the latest owner-designated external terminology authority and owner-approved guide architecture. Canonical English meanings remain governed by their authoritative registries and pages in the Win.Win AI Blind Spot Guide. Qualified bilingual review is still required.

The current public package contains complete `en_HK/`, `tc_HK/`, and `sc_HK/` language folders. `en_HK/` remains the master source. The `tc_HK/` and `sc_HK/` editions are translations and still require independent or qualified bilingual review before publication acceptance.

---

## 2. Version and publication note

Document version remains **1.0**. Release version is **1.0 | September 2026**.

---

## 3. Translation principles

Translate for clear public understanding by individuals, churches, nonprofits, and SMEs. The target reader is a general adult who uses GenAI, may not know AI-governance terminology, and may over-trust polished or confident AI output.

The translation should help that reader understand:
- the core AI Blind Spot idea;
- why the risk matters; and
- what to do next.

Use clear public language. Preserve necessary controlled governance terminology and distinctions. Do not make the translation more academic, bureaucratic, or compliance-heavy than the English source. Translation must not weaken Controls, authority boundaries, reviewer-standing requirements, data-boundary warnings, or escalation conditions.

Keep the core message strong:

- AI can produce a polished answer and still miss something important.
- A good-looking AI output is not the same as accountable human judgement.
- Some blind spots can be reduced by surfacing unstated context.
- Some blind spots need other recognised Controls, Methods, or Accountable Routes, such as Verification Control or an appropriate owner or escalation Route.

If translations are authorised, record the exact English source file and document version, identify the intended target file, and confirm the pairing before translation. Stop and resolve any uncertain pair rather than translating from a guessed source.

Keep corresponding headings, paragraphs, callouts, list items, examples, and blank-line boundaries in the same source order where natural language permits.

As a default:
- use one source paragraph per target paragraph;
- use one source list item per target list item;
- translate meaning rather than word-by-word phrasing; and
- avoid idioms that do not carry well across editions.

Structural alignment helps detect omissions. It does not prove translation quality or replace qualified bilingual review.

Do not use TC or SC translation to silently repair unclear English. If a faithful translation requires the translator to guess the actor, recipient, condition, source, route, referent, sequence, or scope of a qualifier, return the English source to Stage 1 for clarification before translating it.

Compare source and target side by side, then read the target independently for natural language, intended reader action, authority strength, escalation strength, Hong Kong scope, and cultural register.

---

## 4. Core scope distinction

Preserve this distinction everywhere:

```text
Win.Win AI Blind Spot Guide
= broad umbrella guide for AI Blind Spot risks.

Current detailed Control
= Unstated Context Control.

Deepest practical treatment
= identifying and safely eliciting unstated context.

Related current-task guidance within Unstated Context Control
= source location, retrieval and extraction, representability, safe conversion, human-only handling, verification, accountable review, stopping, and escalation.

Recognised control architecture
= Controls, Methods, and Accountable Routes defined in the Control Map, including recognised items whose full methods are not currently provided.
```

Do not translate this guide as if it only covers unstated context. Do not imply that Unstated Context Control is the universal first Control or solves every AI Blind Spot risk. Do not turn the related current-task guidance into co-equal detailed modules merely because it is named in the scope description.

---

## 5. Controlled terminology authority and gap handling

Use the latest **owner-designated external cross-guide terminology authority** for controlled EN→TC and EN→SC mappings. Identify that authority in the Stage 2 handoff or provenance evidence by owner designation together with retained content identity, version/date evidence, and SHA-256 where available rather than relying on an outer upload filename alone. Do not copy the master terminology table into this file.

Canonical English meaning remains governed by the authoritative Win.Win AI Blind Spot Guide location for the item:

- [[AI Blind Spot Risk Library]] is the authoritative canonical risk-definition registry;
- [[AI Blind Spot Control Map]] is the authoritative registry for individual Controls, Methods, Accountable Routes, and their relationships;
- [[Glossary]] defines owner-approved architectural concepts, roles and standing, decision labels, and other Glossary terms without duplicating canonical registry definitions; and
- reader-facing pages and templates may use exact controlled names and concise application guidance without becoming competing definition registries.

Before Stage 2 begins, audit the complete governed-English-term set against the owner-designated external terminology authority. If a genuinely controlled English term is missing, place it in a supplemental terminology proposal or gap register for owner decision. Do not silently invent or normalise a TC/SC mapping.

After owner acceptance, consolidate approved new mappings into a successor single master terminology authority. Do not maintain a permanent guide-local parallel terminology authority.

---

### 5.1 Unstated-context recognition angles

Any authorised translation must preserve the formal task-basis definition and the overlapping practical recognition angles below. These are not mutually exclusive permanent types.

#### How context became absent, incomplete, or thin in the task basis

- **unwritten** — not recorded anywhere;
- **unprompted** — recorded or known somewhere but not supplied to, retrieved for, or adequately represented in the task basis;
- **partly recorded** — some relevant parts are recorded, but important limits, reasons, exceptions, or consequences are missing;
- **distributed** — spread across people, records, prior decisions, or related tasks rather than available in one complete source;
- **current** — known or obvious in the present situation but not yet reflected in the task basis.

#### How people may carry or express it

- **tacit** — known through experience but hard to list or explain on demand;
- **accumulated or experiential** — built through repeated tasks, related work, prior decisions, workarounds, mistakes, near-misses, and lived experience;
- **difficult to articulate** — recognised or acted on by people but not easily expressed as a clear fact, rule, or instruction;
- **relational** — tied to trust, history, role, audience reaction, or reputation;
- **operational** — tied to how a task, venue, supplier, process, or team actually works;
- **bicultural/register-based** — tied to tone, formality, language, culture, or social meaning.

#### Why it may require controlled handling

- **sensitive** — inappropriate to disclose broadly or to place in ordinary documents or AI interactions;
- **authority-based** — tied to who may approve, decide, promise, refuse, commit, or send;
- **material** — tied to what would change a decision, priority, threshold, approval, or consequence;
- **unsafe or inappropriate** — unsuitable to place in AI or ordinary records without a permitted and accountable route;
- **not fully expressible for AI use** — cannot be fully expressed for AI use without losing important judgement, nuance, or responsibility.

The same context may fit several angles at once. Source location is a separate check. Representability is a separate check. The canonical risk name **Unwritten Context Gap** is not limited to literally unwritten information.

---

## 6. Tone guidance

Use clear public language appropriate to the target audience. Preserve necessary controlled governance terminology and distinctions, but do not make the translation more academic, bureaucratic, or compliance-heavy than the English source. Prefer short, direct sentences and connect ideas so readers understand why each step matters. Avoid making this guide sound like it gives legal, HR, counselling, pastoral, safeguarding, financial, regulatory, or other specialist advice.

Plain language does not permit removing or blurring controlled concepts such as Control, Method, Accountable Route, reviewer standing, approval standing, task basis, Verify, Retrieve, Extract, or other owner-approved terminology. Reader-facing translations should preserve short point-of-use explanations of unfamiliar controlled terms so a reader does not need to study the Glossary before using the guide; the authoritative definitions remain in their canonical locations.

---

## 7. Disclaimer boundary

Keep the disclaimer meaning stable across every authorised language edition:

Win.Win AI materials are general information and insight sharing. They do not provide legal advice, compliance certification, technical implementation guidance, financial advice, medical advice, counselling advice, theological advice, pastoral counsel, or other specialist advice. Matters requiring specialist judgement should be escalated to an accountable human authority.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Blind Spot Guide Feedback Form](https://forms.gle/se5ruqaZeytDoFENA)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
