---
title: AI Use Case Triage Scorecard
created: 2026-04-04
version: "1.0.1"
tags:
  - WinWin-Skybroad
  - triage
  - use-case
  - 3P
  - 3R
status: active
type: scorecard
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# AI Use-Case Triage Scorecard

> [!quote] Purpose:  
> Before committing time and resources to any AI project, spend 20 minutes answering these questions.  
> The score tells you whether to start now, fix something first, or stop entirely.

**What this scorecard is:** A structured tool for deciding whether an AI use case should start now, start as a small pilot, wait, or stop.

**What this scorecard is not:** A guarantee that a high-scoring use case will succeed, or that a low-scoring use case will fail. This is a thinking tool, not a certification. The final decision remains with the people and organisation involved.

---

## 1. Basic Use Case Description

Complete this section first. If you cannot answer all fields clearly, the use case is not ready to score yet.

| Field | Your Answer |
|---|---|
| **Use case name** | |
| **Organisation** | SME / Church / Nonprofit / Other: |
| **Owner / champion** | |
| **What task is AI helping with?** | |
| **Who will use it?** | |
| **Current pain or problem** | |
| **Current manual process** | |
| **Desired improvement** | Time / Quality / Consistency / Cost / Other: |
| **Could this be a simple workflow instead of AI?** | Yes / No / Unsure |

---

### How to Score

Answer each question honestly. Use the scoring guide below. Add up each section total at the end.

| Score | Meaning |
|---|---|
| **2** | Yes, clearly addressed — no concerns |
| **1** | Partially addressed or uncertain |
| **0** | Not addressed, unknown, or a red flag applies |

**Final score interpretation:**

| Total | Decision                                                             |
| ----- | -------------------------------------------------------------------- |
| 14–17 | ✅ **Green: Start a small pilot** — conditions are good               |
| 10–13 | ⚠️ **Amber: Fix first** — address the gaps, then re-score            |
| 6–9   | 🔴 **Danger: Not ready** — significant gaps; do not start yet        |
| 0–5   | ⛔ **Red: Stop** — fundamental problems; AI is not the right path now |

---

## 2. 3P: Safe-Use Assessment (0–6 points)

### P1 · Purpose (0–2 points)
**How clearly defined is the purpose of this AI use case?**

| Score | Situation |
|---|---|
| **2** | The task is clearly bounded: we know exactly what AI will do, who reviews the output, and what success looks like |
| **1** | The task is partly defined but some roles, boundaries, or success criteria are still unclear |
| **0** | The purpose is vague ("use AI to improve operations"), or AI is being considered because others are using it |

**P1 Red Flags — if any apply, score 0:**
- [ ] **Vague task** — described only as "use AI to improve our work"
- [ ] **No reviewer named** — no human reviewer has been identified
- [ ] **Unmeasurable success** — cannot describe success in one measurable sentence
- [ ] **People decisions** — task involves eligibility, access, or welfare of a person

*My P1 score:* ___

---

### P2 · Permission (0–2 points)
**How well do we understand what data we are allowed to use with AI?**

| Score | Situation |
|---|---|
| **2** | We have checked PDPO compliance; data is anonymised or clearly permitted; no sensitive personal data involved |
| **1** | We have thought about data permissions but have not formally checked PDPO; some sensitive data may be involved |
| **0** | We have not considered data permissions; OR sensitive personal, pastoral, HR, or regulated data is involved |

**P2 Red Flags — if any apply, score 0:**
- [ ] **No PDPO check** — sensitive personal data will be involved without PDPO assessment
- [ ] **Tool not approved** — data terms have not been checked
- [ ] **People decisions** — task involves eligibility, access, or welfare of a person

**HK gate — Traditional Chinese readability:**
- [ ] **TC documents?** — are they in typed digital format (not scanned images)?  *(Scanned TC — especially handwritten — without testing = automatic Red. Do not proceed until tested and issues are resolved.)*

> [!warning] Using images introduces a "hidden" risk that native text does not:  
> - **Silent Hallucination:** AI tools may "fix" messy handwriting or blurry Traditional Chinese characters without telling the user, potentially changing the meaning of a document.  
> - **Verification Burden:** When the source is an image, the human reviewer must work harder to cross-reference the output against the visual source.

*My P2 score:* ___

---

### P3 · Proof (0–2 points)
**Can we verify AI outputs and be accountable for them?**

| Score | Situation |
|---|---|
| **2** | Human review is built into the workflow before any output reaches anyone; we can explain and audit what AI did |
| **1** | Human review is planned but not yet designed into the process; accountability is unclear |
| **0** | No human review step planned; OR the output goes directly to external parties without review |

**P3 Red Flags — if any apply, score 0:**
- [ ] **No review step** — human review has not been planned
- [ ] **No source documents** — AI will generate freely from memory
- [ ] **Direct to external** — output goes to external parties without any review gate

*My P3 score:* ___

**3P Subtotal:** ___ / 6

---

## 3. 3R: Project Success Assessment (0–6 points)

### R1 · Right Problem (0–2 points)
**Is AI genuinely the right solution for this problem?**

| Score | Situation |
|---|---|
| **2** | AI solves a real, specific, recurring pain point; alternatives were considered and AI is clearly better for this task |
| **1** | AI is probably useful here but the case has not been tested; we are not sure if simpler tools would work |
| **0** | AI is proposed without clear analysis of the problem; OR the real problem is a process or people issue, not a tool issue |

**Diagnostic questions to help score R1:**
- **One sentence?** — what exact problem does this solve?
- **Current workaround?** — how is this problem currently handled? What breaks?
- **Simpler solution?** — would a better spreadsheet, template, or SOP solve this without AI?
- **Resistors involved?** — who in the organisation will resist this, and have you included them?

**R1 Red Flags — if any apply, score 0:**
- [ ] **Vague problem** — "use AI to improve our work" is not a use case

*My R1 score:* ___

---

### R2 · Ready (0–2 points)
**Are we ready to proceed — across data, organisation, process, and governance?**

> [!note] Why "Ready" covers more than data:  
> Most AI projects fail not because of bad technology, but because something else was not ready: the data was messy, the team was not prepared for change, the existing process had no place for AI output to land, or nobody thought through who is accountable. This question checks all four readiness dimensions before you commit.

| Score | Situation |
|---|---|
| **2** | All four dimensions addressed: data is clean and permitted; people are prepared for the change; the process is designed to receive AI output; accountability and governance are in place |
| **1** | Most dimensions are addressed but one or two have gaps that need attention during the pilot |
| **0** | Significant gaps in one or more dimensions — data unusable, people unprepared, process undefined, or governance absent |

**R2 Red Flags — if any apply, score 0:**
- [ ] **Unusable data** — source documents are messy, outdated, incomplete, or not machine-readable
- [ ] **No named owner** — no owner or sponsor for this project

#### R2a — Data Readiness

| Check | Status |
|---|---|
| **Native Digital Text** — searchable, not just a picture of text | Pass / Fail |
| **TC Image Reliability** — if scanned/handwritten, has been tested for accuracy | Pass / Fail |
| **Consistent format** — naming and structure across sources | Pass / Fail |
| **PDPO passed** — no sensitive personal data; Principle 3 check done | Pass / Fail |
| **Complete enough** — for the intended task | Pass / Fail |
| **Right to use** — this data for AI processing | Pass / Fail |

*If 2 or more rows Fail: data is not ready. This alone may score R2 = 0.*

#### R2b — Organisational Readiness

| Check | Status |
|---|---|
| **Leadership approved** — this use case formally | Pass / Fail |
| **Named accountable** — person responsible for AI workflow and outputs | Pass / Fail |
| **End users prepared** — staff involved and ready for change | Pass / Fail |
| **Resistors engaged** — identified and included, not bypassed | Pass / Fail |
| **Training planned** — orientation for end users | Pass / Fail |

*Organisational readiness is frequently the real bottleneck. Technology rarely is.*

#### R2c — Process Readiness

| Check | Status |
|---|---|
| **Workflow mapped** — we know where AI output will land | Pass / Fail |
| **Process redesigned** — includes AI as drafting step with human review | Pass / Fail |
| **Error path defined** — we know what happens when AI produces something wrong | Pass / Fail |
| **Roles assigned** — drafter, reviewer, and approver named | Pass / Fail |

#### R2d — Governance Readiness

| Check | Status |
|---|---|
| **Policy in place** — AI usage policy exists or being adopted before go-live | Pass / Fail |
| **Escalation path** — clear path if AI produces something harmful or wrong | Pass / Fail |
| **Quality standard** — responsible person can judge what a good output looks like | Pass / Fail |
| **Review plan** — plan to review and improve the workflow after the pilot | Pass / Fail |

*My R2 score:* ___

---

### R3 · Realistic Expectations (0–2 points)
**Are time, cost, effort, and expected results honestly assessed?**

| Score | Situation |
|---|---|
| **2** | Clear, measurable success criteria defined; time and resource estimates are grounded; we accept AI outputs need review |
| **1** | Rough success criteria but no firm resource estimate; review burden expected but not modelled |
| **0** | Success is vague; OR AI expected to work without human review; OR transformational results promised without evidence |

**Warning signs that R3 = 0:**
- **"50% time saved"** — with no baseline evidence
- **"Just plug it in"** — assuming it will work without process design
- **"Vendor said easy"** — without independent validation
- **Tool installed = success** — not measuring actual outcomes
- **No baseline** — no current metric to compare improvement against

**R3 Red Flags — if any apply, score 0:**
- [ ] **No baseline (quantitative cases)** — no current measure to compare time, cost, or performance improvement
- [ ] **Undefined value (qualitative cases)** — no clear way to judge whether outputs are better (e.g. clarity, consistency, risk)
- [ ] **No named owner** — no owner or sponsor for this project
- [ ] **Fully automated** — human review has not been planned

*My R3 score:* ___

**3R Subtotal:** ___ / 6

---

## 4. Practical Fit Assessment (0–5 points)

**Note:** Section 4 has a maximum of 5 points, giving a total possible score of 17.

### F1 · Risk Level (0–2 points)
**How serious would it be if AI produced an error in this use case?**

| Score | Situation |
|---|---|
| **2** | Low stakes: errors are easy to catch and correct; no external parties affected; no sensitive content |
| **1** | Medium stakes: errors could embarrass the organisation or require correction effort; some external visibility |
| **0** | High stakes: errors could harm a person, create legal exposure, damage a pastoral relationship, or violate regulations |

**F1 Red Flags — if any apply, score 0:**
- [ ] **Pastoral content** — use case involves pastoral counselling or spiritual direction
- [ ] **Eligibility decisions** — use case involves beneficiary eligibility
- [ ] **Large-scale personal data** — sensitive personal data at scale
- [ ] **No review gate** — output goes externally without human review
- [ ] **Professional qualification** — task requires legal, medical, or financial expertise

*My F1 score:* ___

---

### F2 · Resource Fit (0–2 points)
**Do we have the time, skills, and capacity to run this properly?**

| Score | Situation |
|---|---|
| **2** | We can run a small, bounded pilot in 2–4 weeks without sacrificing other priorities; someone has time to review outputs; the team has enough AI literacy to use the tool responsibly |
| **1** | Time or skills are constrained but workable — the pilot would require some adjustment to current workload |
| **0** | No one has time to run a proper pilot or review outputs; OR the team lacks the basic AI literacy needed; OR the pilot requires significant custom development |

*My F2 score:* ___

---

### F3 · Sustainability (0–1 points)
**If the pilot succeeds, can we sustain this beyond the trial?**

| Score | Situation |
|---|---|
| **1** | We have thought through ongoing time, cost, maintenance, and skills needed — and the organisation can absorb them |
| **0** | We have not thought beyond the pilot; OR the ongoing costs or skills needed are beyond what the organisation can sustain |

*My F3 score:* ___

**Section 4 total (0–5):** ___

---

## 5. Recommended First Mode

Which starting mode is most appropriate? Check one.

- [ ] **Drafting assistant** — AI produces a first draft; human edits and sends
- [ ] **Summarisation assistant** — AI condenses a document; human verifies
- [ ] **Internal Q&A assistant** — AI answers questions from approved documents; human available for exceptions
- [ ] **Translation / rewriting** — AI produces a version; qualified human reviews
- [ ] **Structured extraction** — AI extracts fields from documents; human verifies before recording
- [ ] **Meeting recap** — AI produces a draft summary; attendee verifies
- [ ] **Not suitable yet** — use case needs more preparation first

---

## 6. Decision

### Total Score

| Section | Score |
|---|---|
| 3P (Safe-Use Assessment) | ___ / 6 |
| 3R (Project Success Assessment) | ___ / 6 |
| Practical Fit | ___ / 5 |
| **Total** | **___ / 17** |

### Decision Rule

| Total Score | Decision | What to do next |
|---|---|---|
| **14–17** | ✅ Green: Start a small pilot | Define scope, assign human reviewer, set a 4-week review date |
| **10–13** | ⚠️ Amber: Fix first, then re-score | Identify lowest-scoring questions; address gaps before piloting |
| **6–9** | 🔴 Danger: Not ready | Significant preparation needed; reconsider whether AI is right for this now |
| **0–5** | ⛔ Red: Stop | Fundamental problems; address root issues first; revisit in 3–6 months |

These thresholds apply before starting. If a pilot is already running and conditions deteriorate, use the exit condition defined in Section 7.

### Final Recommendation

- [ ] Start pilot now
- [ ] Small pilot — after fixing: ___________________________
- [ ] Fix first, then reassess — key issues: ___________________________
- [ ] Do not start — reason: ___________________________

---

## 7. Pilot Design (Complete Only If Proceeding)

Complete this section alongside the Decision Log. Keep a copy with the project record.

A well-designed pilot has all of these:

- [ ] **Scope** — one specific, bounded task (not "all our communications")
- [ ] **Duration** — 2–4 weeks maximum
- [ ] **Volume** — 5–10 real outputs before scaling
- [ ] **Named reviewer** — reads every AI output before use
- [ ] **Review points** — named checkpoints that require human review before proceeding
- [ ] **Success metric** — defined before starting
- [ ] **Stop condition** — what would make us stop the pilot?
- [ ] **Sign-off person** — who approves before wider rollout?
- [ ] **Exit condition** — e.g. "if error rate > 20%, we stop"
- [ ] **Record kept** — log of what AI produced and what was changed

---

## 8. Use Cases to Avoid Starting With

For churches and nonprofits in particular — do not start with these:

- **Pastoral AI** — counselling, prayer ministry, or spiritual guidance via AI
- **Theological bots** — Q&A bots presented as authoritative
- **Automated member responses** — without per-message human review
- **People decisions** — care referrals, financial assistance, volunteer suitability, or staff matters
- **Member personal data** — entry into any public AI tool
- **Pastoral records** — confidential files in any AI tool

---

## 9. HK-Specific Reminders

- [ ] **TC readability tested** — before any AI processing
- [ ] **PDPO Principle 3 assessed** — for any personal data
- [ ] **Funder AI policy checked** — if use case involves grant applications
- [ ] **HK regulations verified** — on official sources, not assumed from AI output
- [ ] **Pastoral scope confirmed** — theological content confirmed out of scope

---

## 10. Best Early Use Cases (Reference)

These consistently score high and are low-risk starting points:

| Use Case | Why It Works Well |
|---|---|
| **Newsletter drafting** | Text-heavy, repetitive, human reviews before sending |
| **Meeting recap** | Clear source (the meeting), structured output, human verifies |
| **Document summarisation** | Source is right there — cannot hallucinate what is in the document |
| **Policy / SOP Q&A** | Bounded source, known questions, clear human fallback |
| **Onboarding packs** | Generative from structured input — no knowledge base needed |

---

## 11. Decision Log (complete before starting)

```
Use Case Name: _______________
Date completed: _______________
Completed by: _______________

Scores:
  P1 (Purpose): __ / 2
  P2 (Permission): __ / 2
  P3 (Proof): __ / 2
  R1 (Right problem): __ / 2
  R2 (Ready — data, org, process, governance): __ / 2
  R3 (Realistic expectations): __ / 2
  F1 (Risk level): __ / 2
  F2 (Resource fit): __ / 2
  F3 (Sustainability): __ / 1
  TOTAL: __ / 17 → [Green / Amber / Red]

R2 readiness gaps identified:
  Data: [Pass / Fail]  notes: _______________
  Organisation: [Pass / Fail]  notes: _______________
  Process: [Pass / Fail]  notes: _______________
  Governance: [Pass / Fail]  notes: _______________

Decision:
  [ ] Proceed with pilot (14–17)
  [ ] Fix first (10–13) — gaps to address: _______________
  [ ] Do not start (6–9) — reasons: _______________
  [ ] Stop (0–5)

Pilot success criteria: _______________
Human review gate: [Named person]
Review date: [Date]

Approved by: _______________  Date: _______________
```

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Essentials Feedback Form](https://forms.gle/52JirD3TMQqSwJbm7)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0.1 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
