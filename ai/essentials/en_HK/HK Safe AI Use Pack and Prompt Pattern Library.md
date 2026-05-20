---
title: HK Safe AI Use Pack and Prompt Pattern Library
created: 2026-04-04
version: "1.1"
tags:
  - WinWin-Skybroad
  - HK-safe-AI-use
  - PDPO
  - prompt-patterns
  - Traditional-Chinese
  - 3P
status: active
type: pack
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# HK Safe AI Use Pack and Prompt Pattern Library

> [!quote] One sentence:  
> Safe AI use in Hong Kong means applying the right habits, knowing the local rules, and reviewing every output before it reaches anyone.

**What this pack is:** A Hong Kong-specific reference and a library of copy-paste prompt templates for the most common admin tasks.

**What this pack is not:** Legal advice, PDPO compliance certification, or a guarantee of safe outcomes. For specific legal questions, consult a Hong Kong solicitor or the PCPD directly.

---

## 1. HK Safe AI Use Pack

### 1.1 Why Hong Kong Is Different

Most AI guidance is written for a US or UK audience. Hong Kong has its own legal framework, language realities, and cultural context that change how safe AI use works in practice.

| HK-specific factor | What it means for AI use |
|---|---|
| **PDPO (Cap. 486)** | Personal data collected for one purpose cannot be used for AI without assessment. Six Data Protection Principles apply — especially DPP 3 (use limitation). |
| **Traditional Chinese (繁體字)** | Scanned TC documents may not be machine-readable. AI may read images as blank or hallucinate content. Always test. |
| **Cantonese code-switching** | Meeting transcripts with mixed Cantonese/English/TC are high-risk for AI summarisation. Errors compound and are hard to spot. |
| **HK legal specificity** | AI is trained predominantly on US/UK law. HK-specific ordinances, SFC rules, and HKMA guidance are frequently wrong in AI output. Always verify on elegislation.gov.hk. |
| **Church and pastoral** | AI must never substitute for pastoral care, theological authority, or confidential spiritual counsel. |
| **Grant and government forms** | Some HK funders restrict AI-generated content in applications. Check directly with the funder before using AI. |
| **Data residency** | Enterprise AI tools may store data outside HK. Verify data residency terms before using any tool with confidential organisational data. |
| **Training opt-out** | Many public AI tools use inputs for model training by default. If using a personal or free account for work tasks, verify the "chat history and training" setting is off. |

---

### 1.2 The Three Non-Negotiable HK Rules

These apply to every AI use, every time, in every HK context:

> [!warning] Rule 1 — PDPO Before You Prompt:  
> Before putting any data into an AI tool, ask:
> - Was this data collected for a purpose that includes AI processing?
> - Do the people whose data this is know it may be processed by AI?
> - Is this data sensitive (medical, financial, HR, pastoral, HKID)?
> If you cannot answer yes to the first two, or if the answer to the third is yes — stop.

> [!warning] Rule 2 — Check Traditional Chinese Readability:  
> Before using AI on any Traditional Chinese document:
> - Is it a digital text file (Word, typed PDF)? → Likely readable
> - Is it a scanned image or photo of a document? → Readability is uncertain — AI may misread, omit, or “correct” characters without warning (especially handwritten Traditional Chinese).
> **Mandatory:** Perform a spot check by comparing at least one full paragraph of the AI output against the original image.

> [!warning] Rule 3 — Human Review Before It Reaches Anyone:  
> - No AI output goes to a client, congregation member, staff member, or the public without a human reading it first.
> - This is not optional. It is the minimum responsible standard.

---

### 1.3 HK Safe AI Use — Task-by-Task Guide

#### Communications drafting (newsletters, announcements, WhatsApp)
- ✅ **First draft** — safe to use AI
- ✅ **Bilingual drafting** — EN/TC with AI assistance
- ⚠️ **Human approves** — tone, accuracy, and theological content before sending
- ❌ **No member data** — names, addresses, or personal details
- ❌ **No pastoral messages** — these require genuine human care

#### Meeting notes and action summaries
- ✅ **Internal meetings** — safe for staff or committee use
- ✅ **Approved transcripts** — AI can summarise from approved tools
- ⚠️ **Verify attribution** — speaker names and action owners must be correct
- ⚠️ **Cantonese/English risk** — mixed-language transcripts: review very carefully
- ❌ **No HR or pastoral** — do not use AI on sensitive meeting content

#### Document summarisation
- ✅ **Digital documents** — typed/digital files with no personal data
- ⚠️ **Test TC readability** — scanned Chinese documents: test before use
- ⚠️ **Check key sections** — long complex documents: compare summary against original
- ❌ **No contracts** — do not summarise without solicitor review of the original
- ❌ **No pastoral records** — beneficiary files or counselling records: never use AI

#### Policy and handbook drafting
- ✅ **First draft** — AI can generate from a clear brief
- ⚠️ **Professional review** — HR, employment, or legally binding content must be reviewed
- ⚠️ **Verify HK law** — HK employment specifics frequently wrong in AI; check labour.gov.hk
- ❌ **No unapproved adoption** — do not adopt AI-drafted policy without human review

#### Translation (English ↔ Traditional Chinese)
- ✅ **General communications** — announcements and notices
- ⚠️ **Verify HK terminology** — legal, financial, or technical terms
- ⚠️ **Tone unchanged** — do not strengthen or soften beyond the source material
- ⚠️ **Theological content** — verify translation accuracy with your pastor
- ❌ **No legal or medical** — court documents, contracts, medical information: use a qualified human translator

#### Grant application drafting
- ✅ **Structure and prose** — AI can help organise arguments
- ⚠️ **Check funder policy** — confirm AI content is permitted before using
- ⚠️ **No invented statistics** — never let AI generate impact figures
- ❌ **No beneficiary data** — personal data of beneficiaries: never in AI prompts

---

### 1.4 HK Safe AI Use — Quick Checklist

Before every AI task:

- [ ] **Personal data?** → Apply PDPO check
- [ ] **TC document?** → Test readability first
- [ ] **Confidential content?** → Do not use AI
- [ ] **Human reviewing?** → Must be yes before output reaches anyone
- [ ] **HK law involved?** → Verify on official HK source
- [ ] **Personal account?** → Check training opt-out setting

---

## 2. Prompt Pattern Library

#### START HERE — Find Your Task

Before choosing a pattern, find your task below and go directly to the right section.

| I want to...                                            | Go to                                     |
| ------------------------------------------------------- | ----------------------------------------- |
| **Draft a newsletter, announcement, or email**          | 2.2 — Email / Announcement Draft          |
| **Write a WhatsApp or Telegram broadcast**              | 2.2 — WhatsApp / Telegram Broadcast       |
| **Produce a bilingual English and TC version**          | 2.2 — Bilingual Draft                     |
| **Summarise a document**                                | 2.3 — Document Summary                    |
| **Turn raw meeting notes into a structured summary**    | 2.3 — Meeting Notes Summary               |
| **Answer a question from a specific document**          | 2.4 — Source-Grounded Q&A                 |
| **Think through whether a task involves personal data** | 2.7 — PDPO Pre-Check                      |
| **Check whether AI output is reliable**                 | 2.4 — Hallucination Check                 |
| **Draft a section of a grant or funding report**        | 2.2 — Grant or Funding Report Section     |
| **Write a volunteer or staff role description**         | 2.2 — Volunteer or Staff Role Description |
| **Research something in a Hong Kong context**           | 2.4 — Calibrated Research (HK)            |
| **Draft an organisational policy**                      | 2.5 — Policy Draft                        |
| **Answer a policy question from an existing policy**    | 2.5 — Answer a Policy Question            |
| **Check my confidence before a research task**          | 2.6 — Pre-Task Calibration                |
| **Handle scripture or theology content safely**         | 2.6 — Scripture / Theology Safety         |
| **Verify a Hong Kong law or regulation question**       | 2.7 — HK Regulatory Verification          |

> [!note] Not sure which task applies?  
> Use the **3P check** first — Purpose, Permission, Proof.  
> If you cannot answer all three clearly, the task may not be ready for AI yet.

---

#### IF YOU USE ONLY ONE THING FROM THIS LIBRARY

Add this sentence to the end of any AI prompt before you send it:

> *"If you are not certain about any fact, name, date, or figure, say so rather than guessing. List the three things I should verify before using this."*

This takes five seconds. It does not require you to choose a pattern or fill in a template. It shifts the burden of uncertainty back to the AI before you receive the output — which is the most important single habit in this entire library.

The full patterns below are longer because higher-stakes tasks need more structure. Each additional instruction protects against a specific real error. Use them when the task matters, when it is recurring, or when the output will reach someone outside your organisation — for example, a newsletter sent to all members, or a summary shared with the board.

---

> [!note] How to use these patterns:  
> Each pattern is a reusable template. Replace the parts in [square brackets] with your specific details.  
> Copy the whole block — including the instructions — for best results.  
> Apply the 3P check (Purpose / Permission / Proof) before every task.  

#### How to Read Each Pattern

| Component | Purpose |
|---|---|
| **Use case** | What task this pattern is designed for |
| **Risk level** | Green / Amber based on the standard risk classification |
| **Pattern** | The reusable prompt structure with [PLACEHOLDERS]. Built-in safeguard embedded in the prompt |

#### What Structure These Patterns Follow (Why They Work)

Although each pattern looks slightly different, they follow a consistent structure.  
Each part has a specific role — especially the difference between **Instruction** and **Rule**.

| Tag (as used in patterns) | What it does | Why it matters |
|---|---|---|
| **Background** | Sets the role, organisation type, and context (e.g. Hong Kong, church, SME) | Helps the AI stay in the correct context and avoid applying the wrong assumptions (e.g. US/UK instead of HK) |
| **Task** | States clearly what you want the AI to do | Prevents vague or unfocused answers |
| **Audience / Tone / Language** (when present) | Defines who the output is for and how it should sound | Ensures the output is appropriate for real-world use (e.g. members, staff, clients) |
| **Instruction** | Explains *how to approach the task* (e.g. structure, order, what to include, how to think through the task) | Improves clarity, completeness, and usefulness of the output |
| **Rule** | Sets hard constraints (e.g. “do not invent”, “use only provided content”, “say ‘I don’t know’ if unsure”) | This is the main safety control — it reduces hallucination, overreach, and misuse |
| **Output Format** | Defines how the answer should be structured (bullets, table, short message, etc.) | Makes the result easier to review and reduces hidden errors |
| **Reminder / Review Note** (when present) | Tells you what must be checked by a human before use | Keeps final responsibility with the human, not the AI |
| **Content** | Provides the information the AI is allowed to use (placed at the end to avoid mixing with the pattern structure) | Reduces guessing — the AI works from your data instead of memory, and keeps the prompt structure clear and readable |

---

**Key distinction:**

- **Instruction = how to do the task well**  
- **Rule = what must NOT be violated**

Both are important — Instruction improves quality, while Rule protects against error and misuse.

**Tag convention:**

- Use **Instruction** for how the AI should complete the task.
- Use **Rule** for hard limits the AI must not cross.
- Use **Reminder** or **Review Note** for what the human must check after the AI output.

**Why Content is placed last:**

Content may be long and can visually overwhelm the structure of the pattern.  
Keeping it at the end ensures the Task, Instruction, Rule, and Output Format remain clear and are not missed.

---

**In simple terms, every pattern is doing this:**

> Set the context → define the task → guide the approach → restrict the AI → control the output → require human review → provide the content

---

This structure is not accidental.  
It is designed to reduce the most common real-world AI risks in Hong Kong:
- Invented facts or statistics  
- Wrong legal or regulatory context  
- Misreading Traditional Chinese  
- Over-confident but incorrect summaries  

---

**Important:**

- If you shorten a pattern, shorten the **Instruction** first — not the **Rule**  
- Do not remove the **Rule** section — it is the main protection against unsafe or incorrect output

---

#### Prompt Safety Checklist

Apply this checklist before sending any prompt in this library:

```
- [ ] Have I removed all personal data from the prompt?
- [ ] Have I provided source material rather than asking the model to recall from memory?
- [ ] Have I placed the Content at the end of the prompt?
- [ ] Have I included explicit constraints ("do not invent," "use only the text I provided")?
- [ ] Have I specified the output format clearly?
- [ ] Have I included an uncertainty flag instruction where the output is high-stakes?
```

---

### 2.1 Foundation Patterns (Apply First)

Combine the foundation pattern with a specific task pattern below.

#### Pattern: Persona Guardrail
Use as an opener for any task to set the AI's role and constraints:
```
Background:
You are a faithful assistant for a [church / SME / nonprofit] in Hong Kong.
Your role is to help with [specific task — e.g. drafting announcements / summarising documents].

Rule:
- Use [English / Traditional Chinese / bilingual English and Traditional Chinese]
- Do not provide legal, financial, pastoral, or medical advice
- If a question is outside your defined task, say so and do not attempt to answer it
- Do not invent facts, names, dates, or statistics not provided to you
- Treat all information I share as confidential.
```

---

#### Pattern: Boundary Setter
Use when you want AI to stay strictly within what you provide:
```
Rule:
- Use ONLY the information I provide — do not add external facts, statistics, or examples
- If you are unsure about anything, say so explicitly rather than guessing
- If my request asks you to do something outside your safe boundaries, tell me
```

---

### 2.2 Communication Drafting Patterns

#### Pattern: Email / Announcement Draft
**Use case:** Drafting a routine announcement, email, or notice from bullet-point notes  
**Risk level:** 🟢 Green

```
Task: Draft a [email / announcement / notice] for [audience: staff / volunteers / members / customers].

Tone: [formal / friendly and professional / warm and pastoral / plain and clear]

Language: [English / Traditional Chinese / bilingual English then Traditional Chinese]

Rule:
- Do not invent any facts, names, dates, or figures not in my notes
- Do not add commitments or promises I have not stated
- Keep to [under 150 words / under 300 words / one A4 page]
- Do not strengthen or soften the tone beyond what I have asked

Output Format: Plain text, ready to review and edit before sending.

Content (use only what I provide — do not add information I have not given):
[Paste your notes or bullet points here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

#### Pattern: WhatsApp / Telegram Broadcast
**Use case:** Short broadcast messages under 150 words  
**Risk level:** 🟢 Green

```
Task: Draft a WhatsApp broadcast message for [audience].

Tone: [warm / professional / urgent but calm]

Language: [English / Traditional Chinese / bilingual]

Instruction:
- Write as the organisation, not a specific person.

Rule:
- Do not include personal names in the message.

Output Format:
- Keep it under 150 words.

Review Note:
- After the draft, flag any part I should double-check before sending.

Content:
- Key information: [dates, locations, actions needed]
- Message purpose: [what you need to communicate]
```

---

#### Pattern: Bilingual Draft (English + Traditional Chinese)
**Use case:** Any content needing both English and TC versions  
**Risk level:** 🟢 Green with review

```
Task: Write the following in both English and Traditional Chinese (繁體中文).

Instruction:
- Produce the English version first, then the Traditional Chinese translation.
- Use [formal / warm / plain] register appropriate for [church congregation / business clients / volunteers].
- Keep any proper nouns, organisation names, or ministry names in their original form; add a TC phonetic note in brackets only if it genuinely helps.
- After the draft, flag any terms needing human verification, especially theological, legal, or technical terms.

Rule:
- Use Traditional Chinese characters throughout — NOT Simplified Chinese.
- Do not strengthen or soften the tone beyond the source material.
- If any term is ambiguous in TC, flag it: {TC REVIEWER: please check this term}

Reminder:
- This output requires review by a Traditional Chinese-proficient team member before publication.

Content (English source):
[Paste your English draft or bullet points here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

#### Pattern: Grant or Funding Report Section
**Use case:** Generating a first draft of any grant or funding report section  
**Risk level:** 🟡 Amber — requires human and professional review

```
Task: Draft [the programme description / the impact narrative / the needs statement] for a funding application.

Rule:
- Do NOT generate, estimate, or invent any statistics, percentages, impact numbers, or research citations.
- If I have not provided a specific figure, write {STATISTIC REQUIRED — TO BE VERIFIED} as a placeholder.

Output Format: Flowing prose, [LENGTH] words, [formal / warm] tone.

Content (use only this — do not invent):
- Programme name: [NAME]
- What the programme does: [DESCRIPTION]
- Who it serves: [TARGET GROUP]
- Key activities: [LIST]
- Results achieved (if any): [LIST with source if applicable]
- Funder-specific language or priorities: [PASTE FROM FUNDER GUIDELINES or write "None specified"]
```

---

#### Pattern: Volunteer or Staff Role Description
**Use case:** Draft a volunteer or staff role description  
**Risk level:** 🟡 Amber — requires human and professional review

```
Task: Draft a role description for a [volunteer / staff member / committee member].

Role Information:
- Role title: [TITLE]
- Main responsibilities (3–5): [LIST]
- Who this person reports to or coordinates with: [NAME/ROLE]
- Typical activities: [DESCRIBE]
- Skills or experience required: [LIST or "None specified"]
- Key policies they need to know: [LIST or "None specified"]

Output Format: [Plain paragraph / Bullet-point list / Structured checklist with checkboxes]

Rule:
- Do not add responsibilities I have not listed
- Use role titles, not individual names
- Do not make claims about compensation, benefits, or legal employment terms

Content:
[Paste role detail or bullet points here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

### 2.3 Summarisation Patterns

#### Pattern: Document Summary
**Use case:** Summarize a document  
**Risk level:** 🟡 Amber — requires human review

```
Task: Produce an executive summary of the following document.

Audience: [senior leadership / general staff / volunteers / board members]

Output Format:
- 3-sentence overview (what this document is and why it matters)
- Key points: maximum 5 bullets, one sentence each
- Actions or decisions required from the reader: list clearly, or write "None specified"
- Deadlines mentioned: list or write "None mentioned"

Rule:
- Use only the document provided — do not add outside context
- If something is unclear in the original, write {UNCLEAR IN ORIGINAL}
- Do not express opinions about the content
- List any key conditions, qualifications, or exceptions in the original that must not be overlooked
- List any specific figures, dates, thresholds, or deadlines I should verify
- Tell me if any part was unclear or that you may have oversimplified

Content:
[Paste document text here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

#### Pattern: Meeting Notes Summary
**Use case:** Turning raw meeting notes or transcripts into structured output  
**Risk level:** 🟡 Amber — verify speaker attribution

```
Task: Summarise the following meeting notes into a structured summary.

Output Format:
- Meeting date and attendees (from source only — do not infer)
- Key discussion points (maximum 5 bullets)
- Decisions made (only decisions explicitly stated in the source)
- Action items: [Action] — [Owner] — [Due date]
- Items deferred or unresolved

Rule:
- Do not infer decisions or action items not explicitly stated
- If a speaker's name is unclear, write {SPEAKER UNCLEAR} — do not guess
- If a date was not stated, write {DATE NOT SPECIFIED} — do not infer
- Flag any unclear section with {VERIFY}

Reminder: This output requires human review by someone who attended the meeting before distribution.

Content:
[Paste meeting notes or transcript here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

### 2.4 Research and Verification Patterns

#### Pattern: Source-Grounded Q&A
**Use case:** Policy Q&A, HR queries, compliance checks where source fidelity matters  
**Risk level:** 🟡 Amber — verify citations

```
Task: You are a helpful assistant. Answer the question below using ONLY the document(s) provided.

Question: [Insert your question]

Rule:
- If the answer is not in the document(s), say: "I cannot find this in the provided sources."
- Cite the specific section, page, or paragraph for each claim.
- If you are uncertain, flag it explicitly with "{UNCERTAIN}".
- Do not invent, infer, or assume beyond the provided text.

Output Format:
- Answer: {Your response}
- Sources cited: {List}
- Uncertainties flagged: {List or "None"}

Content:
[Paste the exact text of the approved source document(s)] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

#### Pattern: Calibrated Research (HK)
**Use case:** Any research question needing HK-specific grounding  
**Risk level:** 🟡 Amber

```
Task: I need information about [topic] in a Hong Kong context.

Instruction:
- Tell me your confidence level: high / medium / low.
- Tell me which claims I should verify and on which official HK source.
- Flag anything that may have changed since your training cutoff.

Rule:
- Answer based on HK law / regulation — not US or UK equivalents.
- Name the specific HK ordinance or guidance you are drawing from.

Output Format:
- Short answer
- Confidence level
- Claims to verify
- Official HK sources to check
- Uncertainties

Content:
[Your question]
```

---

#### Pattern: Hallucination Check
**Use case:** Verifying AI output before acting on it  
**Risk level:** 🟡 Amber

```
Task: Review this AI-generated content for possible hallucination or unsupported claims.

Instruction:
- Identify specific claims, statistics, citations, or HK-specific facts that should be verified.
- Tell me what you are least confident about.

Output Format:
- Claims to verify
- Possible HK-specific issues
- Citations or references to confirm
- Uncertainties

Content:
[paste AI output] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

### 2.5 Policy Draft and Query

#### Pattern: Policy Draft
**Use case:** Generating a draft of any organisational policy  
**Risk level:** 🟡 Amber — requires human and professional review

```
Task: Draft a [type of policy] for [organisation type].

Instruction:
- Draft in plain English accessible to non-legal readers.
- Cover: [list key topics].
- Be appropriate for Hong Kong — reference PDPO where relevant.
- Not exceed [X] pages.

Rule:
- Do not present the draft as legal advice.
- Do not state that the policy is legally compliant.
- Flag any legal, HR, or PDPO-related content for human review.

Review Note:
After the draft,
- Flag sections a Hong Kong solicitor should review before adoption.
- Flag HK-specific legal requirements I should verify.

Content:
[Paste policy detail or bullet points here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

#### Pattern: Answer a policy question
**Use case:** Answer a policy question from an existing policy document  
**Risk level:** 🟡 Amber — requires human review

```
Task: Answer a policy question from an existing policy document.

Instruction:
- Be written in plain English, accessible to non-legal readers.

Rule:
- Answer only from the policy document.
- If the answer is clearly stated, provide it and quote the relevant section.
- If the answer is not in the policy, respond: "This question is not directly covered by the current policy. Please contact [CONTACT ROLE] for guidance."
- Do not interpret, infer, or go beyond what the policy explicitly states.
- Do not provide legal advice or compliance assurance.

Output Format:
Plain answer in 2–4 sentences, followed by the policy section reference if applicable.

Content:
[Paste the approved policy text here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

### 2.6 Hallucination Defence Patterns

These patterns are also covered in detail in the Hallucination Defence Guide.

#### Pattern: Pre-Task Calibration
```
Instruction:
Before you answer my question, tell me:
- Your confidence level: high / medium / low
- What you are most uncertain about
- Whether this is HK-specific or based on overseas principles
- Which claims I should verify and on which primary source

Content:
[Your question]
```

---

#### Pattern: Scripture / Theology Safety
```
Task: I need help with [task involving scripture or theology].

Rule:
- Do not present theological interpretations as authoritative.
- If different Christian traditions hold different views, note that.
- Flag any scriptural references you are uncertain about.

Reminder:
- I will verify all scriptural content in the Bible before using it.
```

---

### 2.7 HK-Specific Compliance Patterns

#### Pattern: PDPO Pre-Check
**Use case:** Any task involving personal data  
**Risk level:** 🟡 Amber — requires human review

```
Task: I am considering using AI for: [describe task]

Instruction:
- Please help me think through:
  - Does this data involve personal data as defined under HK's PDPO?
  - Was this data likely collected for a purpose that includes AI processing?
  - Which Data Protection Principles are relevant for this task?
  - What should I do before proceeding?

Reminder:
- I understand this is not legal advice.
- I will verify with PCPD guidance or a solicitor before proceeding.

Content:
[Paste your source material here] or attach a document and mention the document name here, e.g. attached [Document Name]
```

---

#### Pattern: HK Regulatory Verification
**Use case:** Any HK law, regulation, or compliance question  
**Risk level:** 🟡 Amber — requires human review

```
Task: I need to know whether [practice or requirement] applies in Hong Kong.

Instruction:
- Tell me the official HK source to verify (elegislation.gov.hk, sfc.hk, etc.).
- Tell me if you are uncertain about HK-specific application.

Rule:
- Answer based on HK law specifically — not US or UK law.
- Name the specific HK ordinance, section, or regulatory guidance.

Reminder:
- I understand this is not legal advice.

Content:
[Add any background facts, documents, or details relevant to the question]
```

> [!warning] AI may cite repealed ordinances.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Essentials Feedback Form](https://forms.gle/52JirD3TMQqSwJbm7)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.1 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
