---
title: Human Review Patterns
created: 2026-07-01
updated: 2026-08-14
version: "1.0"
status: active
type: reference
locale: en_HK
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Human Review Patterns

## 1. Purpose and Scope

Use this file when a use-case page points to a review method, when you are training reviewers, or when a reviewer needs a deeper explanation of the task-specific checks.

Use-case pages belong to the Practical Layer and are the normal starting point for real AI tasks. They contain the prompt, review, mitigation, escalation, and related-reference guidance needed for that specific task.

This file is different. It explains the reusable human review patterns that sit behind several use-case pages.

For example, a use-case page may tell the reviewer to check decisions, action owners, dates, meaning drift, source accuracy, or approval authority. This file explains the broader review pattern behind those checks so reviewers can understand why the check matters and how to apply the same pattern across different tasks.

Use this file when:

- a use-case page links to a review pattern and the reviewer needs more explanation.
- you are training reviewers across several use cases.
- you are adapting this guide into a local workflow.
- you need to compare review methods across different AI tasks.
- the reviewer is unsure what kind of human review is needed.

Do not treat this file as mandatory reading before every use-case page. Start with the relevant use-case page. Open this file only when deeper review guidance, reviewer training, or reusable review method explanation is needed.

Human review is not a backup step. It is part of responsible AI use. A proper review is not a quick skim; it is a task-specific check against source, authority, risk, context, and intended use.

---

## 2. How To Use This Reference

### 2.1 How the Review Patterns Fit Together

A review pattern is a reusable way of checking AI-supported work. It is not a complete review workflow by itself.

Start with the relevant use-case page. The use-case page identifies the task-specific risks and tells the reviewer what must be checked. Use the patterns in this file when the reviewer needs a deeper method, when several review methods must be combined, or when an organisation is designing reviewer training or a local workflow.

Different patterns answer different review questions:

| Review question | Pattern to use |
|---|---|
| Is the whole output fit for the task, audience, approved scope, and intended use? | **General output review** |
| Does it fit the real people, local context, authority, and consequences? | **Human-grounded review** |
| Did it preserve the meaning of the supplied source? | **Source comparison review** |
| Are its claims true, supported, current, and correctly attributed? | **Source and fact verification** |
| Were fields, figures, identifiers, and calculations transferred correctly? | **Extracted data verification** |
| Can an externally provided document itself be trusted? | **Document fraud / authenticity check** |
| Does the wording preserve meaning, language variety, tone, and language register? | **Bilingual / localisation review** |
| Does the task stay within privacy and approved data boundaries? | **Privacy / data-boundary review** |
| Does the output stay within approved scope, authority, and operational capacity? | **Scope, authority, and feasibility review** |
| Does it require qualified legal, regulatory, or professional judgement? | **Qualified legal / compliance review** |
| Is the tool, account, data setting, and workflow approved? | **Tool / process governance review** |

These patterns are not mutually exclusive. One task may require several of them.

#### Remember the Evidence Checks

When the review depends on documents, sources, claims, or figures, remember four separate questions:

1. **Meaning — Source comparison review**  
   Did the AI preserve what the source meant, including caveats, exceptions, decisions, and unresolved points?

2. **Truth — Source and fact verification**  
   Are the output’s claims true, supported, current, and correctly attributed?

3. **Transfer — Extracted data verification**  
   Were names, dates, figures, totals, identifiers, and other fields transferred correctly from the source?

4. **Trust — Document fraud / authenticity check**  
   Is the source document genuine and consistent with independent organisational records?

Passing one check does not mean the output has passed the others.

A figure may be copied correctly from a fraudulent invoice. A genuine source may be summarised inaccurately. A summary may preserve the source faithfully even though the source itself is outdated. A factual claim may be correct while the final output still exceeds the reviewer’s authority.

Use every pattern materially required by the task. Do not treat one successful check as proof that the whole output is safe to approve.

---

### 2.2 How To Adapt a Review Pattern for a Use-Case Page

The patterns in this file explain reusable review methods. A use-case page should apply the relevant method to the actual task rather than copy the whole general pattern unchanged.

Use this sequence:

1. **Select** the review pattern required by the task and risk.
2. **Remove** checks that are unrelated to the task.
3. **Specify** what the reviewer must compare or verify, which source or real-world reference is needed, and what decision the review supports.
4. **Add** the task-specific warning signs, reviewer role, timing, and escalation boundary.
5. **Check** that the adapted instruction still preserves the purpose and limits of the review pattern.

Keep the published pattern name so readers can follow the link back to this file. Do not change the meaning of the pattern on individual use-case pages.

A task-specific review instruction should normally answer:

- What exactly is being checked?
- What is it checked against?
- What task-specific failure should the reviewer look for?
- Who is sufficiently informed, experienced, qualified, or authorised to review it?
- When must the check happen?
- When must the reviewer stop and escalate?

Do not use a long generic checklist when only two or three items are relevant. Do not omit an important task-specific item merely because it is not listed in the general pattern.

---

## 3. Entry Structure Standard

Each reusable review pattern follows a common structure so readers can understand what the review is for, who should perform it, how to perform it, what must be checked, and when ordinary review is not enough.

---

### 3.1 Mandatory Sections

Every review pattern must contain the following sections.

#### When to use this

Describe the task conditions, output type, or risk signals that make the review pattern relevant.

#### Who should review

Identify the role, competence, experience, context, source access, qualification, or authority required for the review.

#### How to perform the review

Explain the review method. Name what the reviewer should compare, verify, test, inspect, or confirm. Where a pattern needs distinct steps, use bold key-value labels inside this section.

#### What review must check

State the minimum review obligation and the task failures or warning signs the reviewer must look for.

#### When review is not enough

State when the reviewer must stop, obtain another source, involve a more qualified or authorised person, use another control, or escalate.

---

### 3.2 Optional Sections

Use an optional section only where it adds information not already covered by the mandatory sections.

#### Relationship to other review patterns

Explain which other patterns may be required and why one successful check does not prove the whole output is safe to approve.

#### Evidence to retain

State what source, comparison, decision, correction, approval, or review record should be retained.

#### Worked example

Use a short example only where the review method would otherwise remain difficult to apply.

---

## 4. Patterns

### 4.1 General Output Review

#### When to use this

- Before any AI output is used, shared, sent, published, recorded, or relied on

#### Who should review

- The responsible person reviewing the work

#### How to perform the review

- Read the AI output in full.
- Check it against the task brief, intended audience, approved scope, required content, red lines, and intended use.
- Check whether the output generally reflects the supplied source material, without assuming that this high-level check proves detailed source fidelity or factual accuracy.
- Correct issues that the reviewer is competent and authorised to correct.
- Approve only the final human-owned version.

#### What review must check

- Failure to answer the requested task
- Missing required content
- Content outside the approved scope
- Unsupported or overconfident wording
- Wrong names, dates, figures, or audience
- Missing caveats
- Tone or format mismatch
- Unauthorised promises, commitments, decisions, or instructions
- Content that should be checked using a more specific review pattern

#### Relationship to other review patterns

- General output review is the starting review applied to the whole output. It asks whether the output is fit for the task.
- It does not establish detailed source fidelity, factual truth, data-transfer accuracy, document authenticity, specialist correctness, or authority to approve.
- Also use the relevant specialist pattern whenever the task depends on one of those questions.

#### When review is not enough

- General review reduces ordinary errors but does not prove that all specialist checks have passed. Use the additional review patterns and escalation route required by the task.

---

### 4.2 Human-Grounded Review

#### When to use this

- When the task depends on organisational context, people, authority, local practice, audience reaction, or consequences that may not be fully written into the prompt.

#### Who should review

- A responsible person who knows the real context and has authority, or access to someone with authority, to decide whether the output can be used.

#### How to perform the review

**Pre-review context check:**

- Confirm what audience, purpose, source material, authority limits, known constraints, and local context were given to the AI.
- If important context was missing from the brief, do not treat the output as ready for approval; revise the prompt, obtain the missing information, or route the task to the right owner.
- Treat any AI-generated assumption list as a review aid only. Do not rely on the AI to identify every missing local or tacit detail.

**Human-review controls:**

- Check whether the brief was enough and whether the output fits the real organisation, people, authority, and consequences.
- Ask whether a smart human reviewer would have needed more information before answering.
- Escalate when the reviewer does not have the context, authority, or domain competence to approve the output.

#### What review must check

- Missing organisational history, informal practice, prior decisions, sensitive relationships, hidden constraints, audience expectations, unrealistic commitments, false balance, and wording that sounds approved when no authorised person has approved it.

#### When review is not enough

- If the reviewer cannot judge the real context, authority, or consequence, escalate to someone who can. AI fluency, structure, or confidence cannot replace responsible person judgement.

---

### 4.3 Source Comparison Review

#### When to use this

- When the output must preserve the meaning, caveats, decisions, exceptions, status, or unresolved points in supplied material

#### Who should review

- Meeting owner, document owner, or person who understands the source context

#### How to perform the review

- Compare the AI output line by line or point by point against the exact source version.
- Check that decisions, caveats, minority views, action owners, dates, exceptions, uncertainty, and version status are preserved.
- Mark anything that cannot be confirmed from the source.

#### What review must check

- Dropped caveats, over-compressed conclusions, wrong action owners, wrong version, missing exceptions, invented links between points, and summaries that reflect memory rather than the source.

#### Relationship to other review patterns

- This is a **meaning and fidelity check**. It asks whether the output preserved what the source said and meant.
- It does not prove that the source itself is true, current, complete, or authentic.
- Use **Source and fact verification** when claims need independent checking.
- Use **Document fraud / authenticity check** when the source document itself may not be trustworthy.

#### When review is not enough

- Human reviewers may fill gaps from memory. Keep the exact source visible and mark uncertain items explicitly. If the source is incomplete, outdated, conflicting, or untrustworthy, use the additional pattern or escalation route required by the task.

---

### 4.4 Source and Fact Verification

#### When to use this

- Before using or sharing output that makes factual, evidential, current, or jurisdiction-specific claims

#### Who should review

- Subject owner or source-checking reviewer

#### How to perform the review

- Identify each material claim, statistic, citation, date, name, and Hong Kong-specific statement.
- Check it against the original source and, where needed, an independent official or authoritative source.
- Confirm that the source is current, relevant, and correctly attributed.
- Replace unsupported claims with checked text, or mark them as unverified.

#### What review must check

- Invented sources, plausible but unsupported facts, outdated information, missing uncertainty, non-HK defaults, wrong source attribution, and claims not present in the supplied material.

#### Relationship to other review patterns

- This is a **truth and evidence check**. It asks whether claims are true, supported, current, and correctly attributed.
- Use **Extracted data verification** as well when names, figures, identifiers, or structured fields have been copied from a document.
- Use **Document fraud / authenticity check** when the trustworthiness of the source document itself is uncertain.
- Use **Source comparison review** when the question is whether the AI preserved the meaning of a supplied source.

#### When review is not enough

- A review is only as strong as the sources checked. For legal, medical, financial, or regulatory claims, escalate to qualified review.

---

### 4.5 Extracted Data Verification

#### When to use this

- Before recording, payment, filing, or relying on extracted data

#### Who should review

- Finance, operations, or records owner

#### How to perform the review

- Compare every extracted field with the original document before recording or action.
- Validate names, dates, identifiers, invoice numbers, payee details, bank or payment details, subtotals, totals, and calculations.
- Mark unreadable, ambiguous, or missing fields instead of guessing.

#### What review must check

- OCR misreads, wrong field mapping, subtotal or total confusion, transposed digits, missing fields, duplicate invoices, missing pages, and calculations that do not reconcile.

#### Relationship to other review patterns

- This is a **transfer check**. It confirms whether data was copied, mapped, and calculated correctly from the source document.
- It does not prove that the source document is genuine or that narrative claims and conclusions based on the data are correct.
- Use **Document fraud / authenticity check** when the trustworthiness of the source document is uncertain.
- Use **Source and fact verification** when the output makes claims, interpretations, or conclusions based on the extracted data.

#### When review is not enough

- Correct extraction from an altered or fraudulent document still produces unsafe data. Use independent authenticity controls before payment, reliance, or high-impact action.

---

### 4.6 Document Fraud / Authenticity Check

#### When to use this

- Whenever externally provided documents, including invoices, contracts, identity documents, applications, or financial statements, may be relied on for recording, payment, approval, access, or another material action

#### Who should review

- Finance owner, operations owner, records owner, or designated verification reviewer

#### How to perform the review

- Compare the document and extracted details against independent organisational records, not only against the document itself.
- Confirm supplier, counterparty, payee, account, order, contract, or identity details through an approved record or established verification channel.
- Escalate unexpected changes before payment or material action.

#### What review must check

- Bank account numbers that differ from registered supplier details; payee names that differ from approved records; duplicate document or invoice numbers; unexpected changes in contact or payment details; formatting inconsistencies; missing pages; amounts that differ from purchase, contract, or order records; and other signs that the document may have been altered or fabricated.

#### Relationship to other review patterns

- This is a **trust check**. It asks whether the source document itself can be relied on.
- **Extracted data verification** can confirm that the AI copied the document accurately, but accurate copying does not prove that the document is genuine.
- **Source and fact verification** may still be needed for claims or conclusions based on the document.

#### When review is not enough

- If a document has been tampered with, AI extraction and document-only review may both reproduce the same false information. Independent record comparison and the organisation’s fraud, finance, or incident process are required.

---

### 4.7 Bilingual / Localisation Review

#### When to use this

- Before publication or external sharing

#### Who should review

- Qualified bilingual reviewer familiar with HK terminology

#### How to perform the review

- Review the translation against the source text, approved terminology table, target audience, and required script. Fix meaning drift, language-register mismatch, terminology inconsistency, and formatting loss.

#### What review must check

- Simplified/Traditional mixing, untranslated English, wrong HK legal or technical terms, tone changes, over-literal idioms, formatting breakage, and source meaning that has been strengthened or softened.

#### Relationship to other review patterns

- Use **Source comparison review** to confirm that the translation preserves the source meaning.
- Use **Source and fact verification** as well when translated claims, legal terms, dates, names, or jurisdiction-specific statements must be independently checked.

#### When review is not enough

- Fluent text can hide meaning drift. Bilingual review must compare source and target, not just read the target.

---

### 4.8 Privacy / Data-Boundary Review

#### When to use this

- Before prompting and again before output use

#### Who should review

- Data/privacy owner, task owner, or person accountable for the dataset

#### How to perform the review

- Check the prompt, attachments, source documents, output, recipient list, and tool choice before use. Remove or anonymise personal, confidential, HR, financial, pastoral/theological, or restricted information unless approved for that exact purpose and tool.

#### What review must check

- Names, HKID/passport numbers, contact details, health/financial/HR/pastoral/theological information, confidential business details, recipient lists, metadata, copied source text, and use of unapproved consumer AI tools.

#### When review is not enough

- If sensitive data was already entered into an unapproved tool, output review cannot undo exposure. Escalate according to privacy / incident process.

---

### 4.9 Scope, Authority, and Feasibility Review

#### When to use this

- Before approval, sending, publishing, or adoption

#### Who should review

- Owner of the communication, project, policy, or operation

#### How to perform the review

- Check that the output stays within the approved brief, the right authority, the audience, the organisation’s capacity, and the organisation’s actual position. Remove promises, commitments, or official statements that have not been clearly approved.

#### What review must check

- Implied promises, softened boundaries, unauthorised positions, unrealistic timelines, wrong audience, missing escalation route, or language that exceeds the organisation’s actual capacity.

#### When review is not enough

- Human review should be done by someone who can approve the scope and commitments, not only someone checking spelling or grammar.

---

### 4.10 Qualified Legal / Compliance Review

#### When to use this

- Before relying on output or sharing externally

#### Who should review

- Qualified legal, compliance, privacy, HR, or relevant professional reviewer

#### How to perform the review

- Treat the AI output only as a draft or a way to spot issues. Check every legal, regulatory, PDPO, employment, or compliance statement against current official Hong Kong sources, a qualified professional, or both, as appropriate.

#### What review must check

- Wrong jurisdiction, missing HK-specific requirements, outdated laws or regulator names, unsupported legal conclusions, false compliance clearance, and wording that sounds like legal advice.

#### When review is not enough

- Ordinary human review is not enough. Final reliance requires qualified professional judgement and current authoritative sources.

---

### 4.11 Tool / Process Governance Review

#### When to use this

- Before using the tool or workflow

#### Who should review

- Tool owner, manager, privacy lead, or governance owner

#### How to perform the review

- Before entering content or relying on output, check that the AI tool, account type, data settings, approval route, and review workflow are allowed.

#### What review must check

- Personal/free accounts, training enabled, wrong model/tool used, no source-of-truth document, no reviewer assigned, missing escalation route, and undocumented tool terms.

#### When review is not enough

- A content review cannot fix the wrong tool, account, or data process. Fix the process before using the output.

---

## 5. Maintenance and Change Control

Keep the reusable method in this file and the task-specific application in the use-case page. When a review pattern changes, update only the use-case pages that use that pattern, preserving valid task-specific content.

Published pattern names and their meaning are reused across use-case pages. When a review pattern changes, identify only the affected pages, preserve valid task-specific checks, and confirm that reviewer competence, authority, evidence, and escalation boundaries have not been weakened.

Use [[Author and Editor Guide]] for common editorial, heading, localisation, validation, and packaging rules.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Use Case Guide Feedback Form](https://forms.gle/Cq2zCwvsMvKyXPSx6)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
