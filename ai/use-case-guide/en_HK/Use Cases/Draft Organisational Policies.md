---
title: Draft Organisational Policies
created: 2026-07-01
updated: 2026-09-02
use_case_id: UC21
version: "1.0"
status: active
type: use-case-guide
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Draft Organisational Policies

## 1. What This Use Case Is

Use this page when you want AI to help with: **Draft organisational policies**.

- Common users: **Church, nonprofit, SME**.
- Approval level: **Use with caution**.
- Human review needed: **Yes — professional review where legal, HR, or compliance impact exists**.
- Use the AI output to help you draft or check the work. Do not treat it as the final decision.

---

## 2. What This Could Cost You

An AI-drafted policy may include an unsupported legal statement, retention period, mandatory step, authority assignment, or standard copied from another context. Once adopted, people may treat it as binding even though it conflicts with current authoritative requirements, existing policy, or real operating practice, creating correction work and governance exposure when the policy is applied.

---

## 3. How To Review This Output

Use the checks below before approving the AI output. Do not approve it just because it reads well.

---

### 3.1 Review Setup

1. List every legal or regulatory reference in the policy.
2. Verify each reference against the current official HK source: the ordinance text, PCPD guidance, or the relevant regulator’s website.
3. Remove or mark as unverified any requirement that cannot be traced to a specific HK source.
4. Do not submit to the board for adoption without qualified legal review of all regulatory content.

---

### 3.2 Before You Approve — One Check

> **Has a qualified reviewer confirmed that every legal reference, regulatory standard, and compliance requirement in this policy is accurate under current HK law — not verified by reading the AI’s explanation of the law, but by checking the official source directly?**

---

### 3.3 Risk-Specific Review Checks

These checks adapt the minimum review obligations in [[Human Review Risk Library]] to this task.

- **[[Human Review Risk Library#4.13 AI Blind Spot|AI Blind Spot]]:** Whether the output fits the real people, real situation, real authority, and real consequences behind the task, including tacit context the AI was not told and lived or professional judgement that cannot be fully reduced to a prompt.
  - **For this use case:** Check the draft against the organisation’s actual people, operations, authority structure, resources, past incidents, implementation capacity, and consequences of enforcing or relying on the policy.
- **[[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]]:** Check whether warnings, source limits, required reviews, or unresolved policy questions were removed after user pressure. Restore them unless a current approved source or authorised decision owner supports the change.
- **[[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]]:** Confirm the applicable Hong Kong law, regulator guidance, sector requirement, organisational authority, and local operating practice using current official sources and qualified review. Do not import Mainland China, overseas, or generic rules.

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

- **Qualified legal / compliance review:** Check legal, employment, privacy, safeguarding, regulatory, rights, and compliance content against current official sources and qualified advice.
  - Look for: A draft presented as legally complete, compliant, or enforceable without the required specialist review.
  - Timing: Before approval or adoption.
  - Reviewer: Qualified legal, compliance, HR, privacy, safeguarding, or relevant professional reviewer.

- **Scope, authority, and feasibility review:** Check that the policy reflects actual organisational authority, roles, resources, enforcement process, exceptions, and operational capacity.
  - Look for: A policy that cannot be implemented, conflicts with current practice, leaves enforcement unclear, or assigns authority to the wrong role.
  - Timing: Before consultation, approval, and adoption.
  - Reviewer: Policy owner, operational owner, decision owner, and authorised governing body.

---

## 4. When To Escalate Instead of Approve

- Escalate before use if the output affects legal, HR, financial, safeguarding, medical, regulatory, public-facing, or high-impact decisions and the reviewer does not have the authority, competence, context, source access, or approved process needed to confirm safe use.
- Escalate legal, regulatory, employment, PDPO, contract, compliance, or rights/obligation issues unless the reviewer is explicitly authorised and competent to confirm the matter under the approved process.
- Escalate whenever personal data, HR, pastoral, theological, medical, financial, HKID, beneficiary, or confidential information is involved and the reviewer does not have the authority, context, source access, or approved process needed to confirm safe use.
- Escalate when the output could bind the organisation, affect rights/obligations, or appear as official approval and the reviewer is not authorised to confirm that effect.

---

## 5. Before You Prompt

Before using AI for this task, check these basics:
- The purpose is clear.
- The input does not contain personal or confidential data that should not be entered into the tool.
- A responsible person can check the AI output before it is used.
- The task does not ask AI to make the decision, provide professional advice, or act as the final authority.

- Confirm that this task fits the approval level: **Use with caution**.
- Confirm that the planned reviewer can complete the required human review: **Yes — professional review where legal, HR, or compliance impact exists**.

---

## 6. AI Blind Spot Focus

**Risk focus:** Informal Practice Collision and User-Pressure Drift

**Prompt focus:** Before prompting, give the AI the policy purpose, current practice, authority owner, applicable jurisdiction, implementation capacity, known exceptions, source materials, and any unresolved decisions. Instruct it to mark gaps and not to resolve policy disputes merely because the user pushes for a preferred wording.

**Human review focus:** The reviewer should check whether the draft policy can actually be implemented and whether it conflicts with current practice, legal/regulatory requirements, board authority, past incidents, resource limits, or unresolved decisions.

**Deeper Blind Spot review:** Follow the [[How To Use This Guide#6.1 Win.Win AI Blind Spot Guide|Win.Win AI Blind Spot Guide route]] when the policy may collide with relevant context that is absent from, incomplete in, or not adequately represented in the task basis, including informal practice, past incidents, approved records, exceptions, or operational reality.

**Do not rely only on:** balanced policy language. A well-written policy can still be unauthorised, infeasible, or inconsistent with real practice.

---

## 7. Base Prompt Pattern

> **Essentials dependency:** These base prompt patterns are in `HK Safe AI Use Pack and Prompt Pattern Library.md`, part of **Win.Win AI Essentials**. They are not repeated in this guide.

- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- HK Safe AI Use Pack and Prompt Pattern Library.md — Boundary Setter
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification

---

## 8. Main Risks

- **[[Risk Taxonomy#3.9 Legal / Regulatory / Compliance|Legal / Regulatory / Compliance]]: False Legal Authority (High)** — Organisational policies carry institutional authority once adopted. AI may state a general legal or regulatory concept correctly while inventing, misapplying, or using an outdated provision, requirement, threshold, or retention period for the specific policy. If the draft is approved without comparison to current authoritative sources and qualified advice where needed, unsupported wording may become an internal rule that staff, volunteers, reviewers, or external parties rely on.

---

## 9. Other Risks To Watch

- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: [[Human Review Risk Library#4.22 User-Pressure Drift|User-Pressure Drift]] (Medium)** — If a user confidently challenges a cautious answer, AI may soften or reverse the answer without new reliable evidence. Agreement with the user is not verification.
- **[[Risk Taxonomy#3.11 AI Blind Spot / Context Risks|AI Blind Spot / Context Risks]]: Informal Practice Collision — related review risk: [[Human Review Risk Library#4.14 Unwritten Context Gap|Unwritten Context Gap]] (High)** — AI may draft a clean policy that conflicts with how the organisation actually works, including unwritten exceptions, resource limits, past incidents, or informal practices that were never included in the prompt.
- **[[Risk Taxonomy#3.4 Privacy / Confidentiality / Data Boundary|Privacy / Confidentiality / Data Boundary]]: Missing Required Provisions — related review risk: [[Human Review Risk Library#4.23 Local or jurisdiction-specific blind spot|Local or jurisdiction-specific blind spot]] (High)** — A policy may omit provisions required by current applicable law, regulation, contracts, funder or insurer conditions, sector guidance, or the organisation’s own approved controls. A generic request does not provide enough basis to establish the complete mandatory content of a policy. Use current authoritative sources and qualified review where the policy affects rights, obligations, employment, privacy, safety, or compliance.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Policy-Practice Gap (High)** — AI may draft aspirational policies that the organisation cannot implement — insufficient staff, systems, or processes to meet the stated standards. When the policy is tested against an actual incident, the gap becomes a liability.
- **[[Risk Taxonomy#3.6 Authority / Scope / Commitment|Authority / Scope / Commitment]]: Enforcement Ambiguity (High)** — AI-drafted disciplinary, grievance, or escalation clauses may use ambiguous language that creates disputes about meaning when applied. Ambiguity that appears harmless in a draft becomes significant when the policy is invoked.

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
| False Legal Authority | **Background** | State that the output is a policy draft for organisational review, not legal advice, compliance certification, or an approved policy. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]] |
| False Legal Authority | **Rule** | Do not claim that the draft satisfies law, regulation, employment, privacy, safeguarding, or professional requirements. Mark those parts `{QUALIFIED REVIEW REQUIRED}.` | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]] |
| AI Blind Spot | **Instruction** | Identify assumptions, missing information, uncertainty, authority limits, and items requiring human confirmation about current practice, exceptions, implementation capacity, legal or regulatory requirements, and enforcement consequences. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Output Format** | Add `Policy assumptions and owner decisions` with `Issue`, `Evidence or context needed`, `Responsible owner`, and `Status`. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |
| AI Blind Spot | **Reminder / Review Note** | This list is a review aid only. Policy, operational, authority, and qualified reviewers must still check the draft against the organisation’s real practice and consequences. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.1 Accuracy and Uncertainty Control\|Accuracy and Uncertainty Control]] |

---

### 10.2 Conditional Risk Add-Ons

Use these only when the stated risk or task-specific condition applies.

| Risk | Essentials prompt section | Add this text | Patterns |
|---|---|---|---|
| User-Pressure Drift | **Rule** | Do not remove a caution, required review, or source limitation merely because the user asks for a more definitive policy without new approved evidence. Mark the disputed point `{VERIFY}` and identify the approved source or authorised decision owner needed to resolve it. | [[Prompt Enhancement Patterns#5.15 User-Pressure Drift Control\|User-Pressure Drift Control]]; [[Prompt Enhancement Patterns#5.2 Source Grounding and Citation Control\|Source Grounding and Citation Control]] |
| Informal Practice Collision | **Instruction** | Compare the proposed rule with supplied current practice, approved exceptions, past implementation issues, and role responsibilities. Flag conflicts for owner decision. | [[Prompt Enhancement Patterns#5.11 AI Blind Spot and Unwritten Context Control\|AI Blind Spot and Unwritten Context Control]]; [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]] |
| Missing Required Provisions | **Instruction** | Use the supplied approved checklist or authoritative source to identify required sections. Mark missing or uncertain provisions for qualified review rather than inventing them. | [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]]; [[Prompt Enhancement Patterns#5.8 Hong Kong Localisation Control\|Hong Kong Localisation Control]] |
| Policy-Practice Gap | **Output Format** | Include `Owner`, `Required process`, `Resources`, `Training`, `Record`, `Exception route`, and `Implementation dependency` for each material rule. | [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Policy-Practice Gap | **Rule** | Do not invent implementation owners, resources, training, records, exception routes, or dependencies. Use placeholders and require policy-owner confirmation where these are not supplied. | [[Prompt Enhancement Patterns#5.14 Local Operational Memory Control\|Local Operational Memory Control]]; [[Prompt Enhancement Patterns#5.16 Operational Process Control\|Operational Process Control]] |
| Enforcement Ambiguity | **Rule** | Do not invent sanctions, appeal routes, decision rights, or enforcement powers. Use placeholders where approved arrangements are not supplied. | [[Prompt Enhancement Patterns#5.6 Authority and Commitment Control\|Authority and Commitment Control]]; [[Prompt Enhancement Patterns#5.9 Legal and Compliance Boundary Control\|Legal and Compliance Boundary Control]] |

Risks not listed in these tables are still covered by the task-specific review, mitigation, and escalation sections. Their omission from the prompt table does not mean they are unimportant; it means extra prompt wording is not the main control.

---

## 11. Other Mitigation

- Ordinary human review is not enough. Final reliance requires qualified professional judgement and current authoritative sources.
- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.

---

## 12. Related Win.Win AI Essentials Items

- 3P Framework Poster.md
- AI Use Case Triage Scorecard.md
- HK Safe AI Use Pack and Prompt Pattern Library.md
- HK Safe AI Use Pack and Prompt Pattern Library.md — HK Regulatory Verification
- HK Safe AI Use Pack and Prompt Pattern Library.md — PDPO Pre-Check
- HK Safe AI Use Pack and Prompt Pattern Library.md — Policy Draft
- Red Lines Quick Reference.md

---

## 13. Final Reminder

Before approving a policy draft, check whether it fits real practice and capacity. Ask what unwritten exceptions, past incidents, legal/compliance boundaries, and authority decisions must be resolved before adoption.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
