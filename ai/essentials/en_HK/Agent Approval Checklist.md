---
title: Agent Approval Checklist
created: 2026-04-04
version: "1.0"
tags:
  - WinWin-Skybroad
  - agentic-AI
  - governance
status: active
type: checklist
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Agent Approval Checklist

**Before AI can act on its own**

> [!note] **Who this is for:**  
> Technology leads, operations managers, and IT-capable staff considering AI tools that take automated actions. Most churches and small organisations starting with AI do not need this document yet. If you are only using AI to draft text for human review, start with the [[3P Framework Poster]] and [[AI Safety Checklist - Work]] instead.

> [!quote] The key difference:  
> A standard AI tool responds. An AI agent acts.  
> Before you give AI the ability to send messages, update records, book meetings, submit forms, or make purchases — you need different controls. This checklist is those controls.

**What this checklist is:** A structured approval gate for any AI system that can take actions — not just generate text.

**What this checklist is not:** A guarantee that a passing score means the agent is safe or will perform correctly. Agentic AI introduces genuine risks that standard text generation does not. This checklist reduces those risks — it does not eliminate them.

---

## 1. What Makes an Agent Different from Standard AI Use?

Standard AI use: you provide input → AI generates text → human reads and decides what to do.

An AI agent: the AI can take actions — sending emails, updating records, booking meetings, submitting forms, or posting to social media — often with limited or no human approval for each step.

**Examples of agentic AI in organisation settings:**
- **Auto-reply emails** — reads and sends replies automatically
- **Auto-booking** — books meeting rooms or appointments on your behalf
- **Record updates** — updates contact management system, spreadsheets, or databases based on conversations
- **Auto-broadcast** — posts to social media or sends WhatsApp broadcasts automatically
- **Form submission** — submits forms, applications, or orders without human confirmation
- **Multi-step workflows** — research → draft → send → follow up

**Why agents require different controls:** With a standard AI tool, you see the output before anything happens. With an agent, actions may already be taken before you notice. Errors can propagate across multiple steps. Reversing them may be difficult or impossible.

> [!important] Ask this first:  
> Could this workflow be achieved with a well-designed prompt and a human clicking send — rather than a fully autonomous agent?  
> Many workflows that seem to need an agent work just as well with a good prompt and a human in the loop.  
> If yes — use the simpler approach. Agents amplify both value and risk.

---

## 2. The Four Agent Risk Dimensions

| Dimension | Question | Why it matters |
|---|---|---|
| **Reversibility** | If the agent makes a mistake, can it be undone? | Sent emails cannot be unsent. Deleted records may not be recoverable. |
| **Scale of impact** | How many people or systems are affected if it goes wrong? | An agent emailing one person vs. one emailing your whole congregation. |
| **Visibility** | Can you see what the agent did, when, and why? | Without an audit trail (a record of what the AI did, when, and why — so errors can be investigated later), errors are invisible until consequences appear. |
| **Authorization** | Has someone explicitly approved each action type? | Agents should not take actions their operator has not consciously permitted. |

---

## 3. Define the Agent (Complete Before Scoring)

| Field | Your Answer |
|---|---|
| **Agent name / identifier** | |
| **Problem it solves** | |
| **Actions it can take** (List all) | |
| **Systems and data access** | |
| **What triggers it?** | |
| **Named human owner** | |
| **Scope of autonomy** | |
| **Simpler alternative?** | Yes / No / Unsure |

---

## 4. Critical Gates (All Must Be "Yes" to Proceed)

| # | Question | Yes | Partial | No | Notes |
|---|---|---|---|---|---|
| C1 | **Named owner** — accountable human for the agent's outputs? | ☐ | ☐ | ☐ | |
| C2 | **Bounded permissions** — explicit, no open-ended access? | ☐ | ☐ | ☐ | |
| C3 | **Human review gate** — for high-impact decisions or external communications? | ☐ | ☐ | ☐ | |
| C4 | **Tested** — with edge cases and failure scenarios before deployment? | ☐ | ☐ | ☐ | |
| C5 | **Emergency stop** — a way to pause or roll back immediately? | ☐ | ☐ | ☐ | |

> [!warning] Hard stop:  
> If any Critical Gate is "No" — do not proceed until it is resolved.  
> These are not optional.

---

## 5. Risk Controls (Should Be "Yes" or "Partial with Mitigation")

| # | Question | Yes | Partial | No | Mitigation if Partial/No |
|---|---|---|---|---|---|
| R1 | **Purpose documented** — aligned with organisational goals? | ☐ | ☐ | ☐ | |
| R2 | **PDPO-compliant** — data inputs minimised and anonymised? | ☐ | ☐ | ☐ | |
| R3 | **Audit logging** (a record of what the AI did, when, and why — so errors can be investigated later) — prompts, actions, and outputs logged? | ☐ | ☐ | ☐ | |
| R4 | **Success metrics** — defined monitoring thresholds? | ☐ | ☐ | ☐ | |
| R5 | **Fallback plan** — if the agent fails or behaves unexpectedly? | ☐ | ☐ | ☐ | |
| R6 | **Re-certification** — defined process every 3 months to prevent goal creep? | ☐ | ☐ | ☐ | |

> [!note] Caution:  
> If any Risk Control is "No" — document an explicit mitigation before proceeding.

---

## 6. Mandatory Human Approval Triggers

The following action types must always require explicit human approval before execution, regardless of the agent's confidence level:

- [ ] **External communications** — email, message, notification, or social media
- [ ] **Financial records** — modification to transactions, invoices, or payments
- [ ] **People records** — update to personnel, HR, or member records
- [ ] **Access or benefits** — any action affecting a person's eligibility, care, or access
- [ ] **Irreversible actions** — sent email, deleted record, or submitted form
- [ ] **High-cost mistakes** — reputational, financial, legal, or relational risk

---

## 7. Failure Mode Analysis

Before deploying, identify the most likely failure modes for this specific agent.

| Failure Mode | Description | Risk Level | Mitigation |
|---|---|---|---|
| **Prompt injection** | Malicious content in a document instructs the agent to take unintended actions | Medium–High | Sanitise inputs; restrict what the agent reads; validate outputs before action |
| **Goal misinterpretation** | Agent interprets a vague instruction in an unintended way | Medium | Write precise, bounded instructions; test edge cases before deployment |
| **Cascading errors** | An early error in a multi-step workflow propagates downstream | High | Add human checkpoints between steps |
| **Scope creep** | Agent accesses data or systems beyond its intended scope | High | Apply least-privilege: give access only to what is specifically needed |
| **Hallucinated actions** | Agent fabricates a decision it believes was authorised | Medium | Log all actions; implement rollback (reversing what the AI did); require human review of logs |
| **Over-confidence** | Agent proceeds with low-quality output with no uncertainty mechanism | Medium | Build in uncertainty thresholds; require human review below threshold |

**For your specific agent — identify the top 3 most likely failure modes:**

| Failure Mode | How likely? | How bad if it happens? | Mitigation planned |
|---|---|---|---|
| | High / Medium / Low | High / Medium / Low | |
| | High / Medium / Low | High / Medium / Low | |
| | High / Medium / Low | High / Medium / Low | |

---

## 8. Good Practices (Nice to Have)

| # | Question | Yes | No | Notes |
|---|---|---|---|---|
| G1 | **Explainable logic** — decision logic explainable to non-technical stakeholders? | ☐ | ☐ | |
| G2 | **End users trained** — on the agent's capabilities and limits? | ☐ | ☐ | |
| G3 | **Feedback loop** — users can report issues or suggest improvements? | ☐ | ☐ | |
| G4 | **Bias considered** — fairness and accessibility in the agent's design? | ☐ | ☐ | |
| G5 | **Actions distinguishable** — agent's actions separate from human actions in shared systems? | ☐ | ☐ | |
| G6 | **Quarterly review** — regular cycle (at least every 3 months) to check for goal creep? | ☐ | ☐ | |

> [!note] Agents must be reviewed at least every 3 months to ensure no goal creep — the gradual expansion of scope beyond what was originally intended.

---

## 9. Pilot Design

Agentic AI should always start with a constrained pilot before broader deployment.

| Field | Your Answer |
|---|---|
| **Pilot scope** | Which specific action subset will be tested? |
| **Pilot environment** | Real data / real systems, or test environment? |
| **Pilot duration** | |
| **Human oversight** | How will a human monitor what the agent does? |
| **Success criteria** | What does a successful pilot look like? |
| **Stop criteria** | Under what conditions will the pilot be halted? |
| **Sign-off before rollout** | Who must approve the move from pilot to broader use? |

---

## 10. Prohibited Agent Uses — Always Out of Scope

- [ ] **Pastoral communications** — faith, crisis, or counselling messages: human pastor or leader only
- [ ] **HR decisions** — employment, discipline, pay, or performance: never by agent
- [ ] **Financial commitments** — committing funds, approving expenditure, or initiating payments: human approval required
- [ ] **Legal submissions** — filing, submitting, or responding to legal or regulatory documents: never by agent
- [ ] **Beneficiary decisions** — eligibility, access, or priority for any service or benefit: never by agent
- [ ] **Health communications** — providing, recommending, or acting on health-related information: never by agent
- [ ] **Bulk personal data** — exporting, deleting, or transferring bulk personal data: explicit human authorisation required

---

## 11. Guarded Workflow Pattern

A guarded workflow has human checkpoints built in at the right places:

```
GUARDED WORKFLOW PATTERN

Step 1: Agent gathers information / researches / drafts
        |
Step 2: [HUMAN CHECKPOINT] — Human reviews agent plan or draft
        | Approved
Step 3: Agent executes low-risk steps (e.g. creates internal draft)
        |
Step 4: [HUMAN CHECKPOINT] — Human reviews before any external action
        | Approved
Step 5: Agent executes OR human executes the external action
        |
Step 6: Agent logs the action and confirms to human
```

**Minimum checkpoints required:**
- **Before external send** — any external communication
- **Before data change** — any data modified in a production system
- **Before financial action** — any financial action initiated
- **Unexpected situation** — when the agent encounters something outside scope

---

## 12. Approval Record

**Agent name:** ___________________________  
**Purpose:** ___________________________  
**Proposed by:** Name: _______________ Role: _______________  
**Assessment date:** ___________________________  
**Approved actions:** ___________________________  
**Prohibited actions:** ___________________________  
**Responsible human:** ___________________________  
**Kill switch location:** ___________________________  
**Log review schedule:** ___________________________  
**Review date:** ___________________________  

**Critical Gates:** All C1–C5 marked Yes ☐

**Risk Controls:** R1–R6 reviewed, mitigations documented ☐

**Overall decision:**
- [ ] Approved for constrained pilot — all critical gates passed
- [ ] Not approved — gates failed: ___________________________
- [ ] Requires further review by: ___________________________

**Approved by:** ___________________________ **Date:** _______________   

**Next re-certification review:** ___________________________ (recommended: 3 months from approval)  

> [!note] This approval covers the defined scope only. Any change to the agent's purpose, action types, data access, or target systems requires a new assessment.

---

## 13. HK-Specific Considerations

- [ ] **PDPO Principle 3** — compliance assessed if agent handles personal data
- [ ] **External communications** — no personal data of third parties included without consent
- [ ] **Church context** — pastoral content, prayer requests, and counselling records explicitly excluded
- [ ] **Third-party platforms** — data residency and privacy terms reviewed
- [ ] **Regulated entity** — additional regulatory review required if operating for SFC or HKMA entities

---

## 14. A Note on Agents for organisations

For most organisations, the AI agent use cases that make sense in the near term are:
- **Meeting transcription** — summarisation with human review of output
- **Email draft generation** — triggered by an enquiry; human approves before sending
- **Document Q&A** — human available for escalation

Fully autonomous agents — ones that send communications, update records, or make decisions without per-action human approval — carry significantly higher risk and are generally not appropriate as a starting point for organisations without dedicated IT governance capability.

**The principle:** Start with the simplest solution that solves the real problem. Many workflows that seem to need an agent actually work well with a well-designed prompt and a human clicking send.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Essentials Feedback Form](https://forms.gle/52JirD3TMQqSwJbm7)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
