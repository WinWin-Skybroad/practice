---
title: Hallucination Defence Guide
created: 2026-04-04
version: "1.1"
tags:
  - WinWin-Skybroad
  - hallucination
  - AI-safety
status: active
type: guide
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# Hallucination Defence Guide

**How to catch confident mistakes and made-up details**

> [!quote] The core principle:  
> Treat AI as a draft engine, not a truth engine.  
> AI does not know when it is wrong. It produces incorrect answers with the same confident tone as correct ones.  
> Defending against hallucination is not about trusting AI less — it is about knowing where and how to check.  
>  
> **Polished is not proof**.

**What this guide is for:** Building habits that catch AI errors before they cause harm.

**What this guide is not:** A guarantee that following these steps will eliminate AI errors. AI systems do not give guaranteed answers — they predict what seems most likely, which means errors remain possible even with good practice. Human review is always required.

---

## 1. What Is Hallucination?

AI hallucination is when a model produces output that is **factually incorrect, fabricated, or misleading — but stated with confidence**.

It is not a bug that will be fixed. It is a structural feature of how AI systems work: they are built to produce outputs that sound plausible, coherent, and convincing — but not to reliably check whether those outputs are actually correct. A well-written answer and a wrong answer can look exactly the same.

### Why Does It Happen?

| Cause | Plain-English Explanation |
|---|---|
| **Training data gaps** | The model was never trained on the specific fact — so it fills in what seems likely |
| **No real-time knowledge** | Most models have a knowledge cutoff; facts that changed after that date may be wrong |
| **Confident extrapolation** | The model extends a pattern it recognises even when it should not |
| **Prompt ambiguity** | A vague question produces a vague — and potentially invented — answer |
| **Long conversation memory limits** | In a long conversation, AI may lose track of earlier details and later contradict what it said before |
| **Retrieval failure (RAG)** | In document Q&A systems, if the wrong source is retrieved, the answer is built on the wrong foundation |

**Hallucination is not:**
- **Dishonesty** — the AI is not lying
- **A broken model** — it happens even in strong models
- **Only for weaker AI** — all current models can hallucinate

**Hallucination is also:**
- **Wrong summary** — of a real document
- **Invented citation** — a false reference
- **Outdated fact** — stated in the present tense
- **Dropped exception** — a condition omitted that changes meaning
- **Confident with no basis** — especially on niche or recent topics

> [!important] AI tools are designed to generate a response rather than acknowledge missing context. Unlike a human professional who feels uncertain when asked a question outside their competence, an AI tool has no internal signal that tells it to stop and ask for clarification. It will attempt to answer whether it has sufficient context or not — and the answer will sound equally confident in both cases. This is not dishonesty. It is a structural property of how these systems work. 

> [!important] **The responsibility for providing sufficient context, and for verifying that the response reflects that context, belongs entirely to the human.**

---

## 2. Why It Matters More in Hong Kong

| HK-specific risk | Why hallucination risk is higher |
|---|---|
| **HK law and regulation** | AI training dominated by US/UK law; HK ordinances frequently wrong |
| **Traditional Chinese** | Fewer high-quality TC training sources; translation errors compound silently |
| **Recent policies** | Training cutoff means recent PDPO guidance and new regulations may be wrong |
| **Scripture and theology** | AI may generate plausible but doctrinally incorrect interpretations |
| **Named HK organisations** | AI frequently confuses similar names or invents details |
| **Grant and government forms** | AI may apply overseas criteria to HK-specific requirements |

---

## 3. The Five Hallucination Patterns

### Pattern 1 — The Confident Fabrication
AI states a specific fact — statistic, name, date, case number — that does not exist or is wrong.

**How to spot it:** Very specific figures with no named source.  
**Defence:** Search the exact figure. If you cannot find the primary source in 60 seconds, do not use it.

---

### Pattern 2 — The Plausible Citation
AI invents a real-sounding academic paper, legal case, or government document that does not exist.

**How to spot it:** A citation that looks well-formatted but leads nowhere.  
**Defence:** Search the exact title. Verify author, publisher, and date independently. Never cite a source you have not confirmed exists.

---

### Pattern 3 — The Outdated Fact
AI states something that was true at training cutoff but is no longer true.

**How to spot it:** Information about regulations or policies stated in present tense with no date anchor.  
**Defence:** For anything regulatory, always verify against the current official source such as www.pcpd.org.hk, www.elegislation.gov.hk.

---

### Pattern 4 — The Confident Extrapolation
AI applies a rule from one jurisdiction or context to another where it does not apply.

**How to spot it:** Advice that applies US/UK rules to a HK context, or enterprise-scale guidance applied to an SME.  
**Defence:** Always check jurisdiction. If compliance is involved, involve a qualified professional.

---

### Pattern 5 — The Smooth Paraphrase Error
AI summarises a real document but subtly changes meaning — omitting a condition, misrepresenting a threshold, or dropping an exception.

**How to spot it:** Summaries of complex documents, policy paraphrases, legal or financial summaries.  
**Defence:** For summaries that affect decisions, compare AI output directly against the source section by section.

---

## 4. Prompt-Level Defences (Before the Error Happens)

The best time to reduce hallucination is before you receive the output.

| Technique | How to use it | Why it works |
|---|---|---|
| **Source grounding** | "Answer only from my document. No outside knowledge." | Cannot hallucinate what it was not given |
| **Uncertainty prompting** | "Flag uncertain claims with [UNCERTAIN]." | Models express uncertainty when asked |
| **Explicit constraints** | "Don't invent. If missing, say so." | Hard stop on common hallucination types |
| **Step-by-step reasoning** | "First list sections. Then summarise. Then identify gaps." | Makes reasoning traceable |
| **Role framing** | "You are a careful reviewer. Flag uncertainties, don't fill them in." | Aligns model behaviour toward caution |

**Safer response patterns for higher-risk tasks:**
- **From supplied text** — summarise only what you gave it
- **Separate uncertain** — list uncertainties apart from confirmed facts
- **Options, not decisions** — you decide; AI gives choices
- **Stop when missing** — ask it to stop, not guess, when evidence is absent

---

## 5. Quick Verification Habits

### Nugget Check

- **Step 1 — Pick one** — the single most specific detail: a date, statistic, or study name
- **Step 2 — Google it** — just that one thing
- **Step 3 — Not found?** — treat the rest of the AI output as suspect

---

### Exit Clauses

Add these to any important prompt:

- **"I don't know"** — "If you're not confident, say 'I don't know' rather than guessing."
- **"What to check"** — "List the 3 things I should double-check."

---

## 6. 3-Check Verification System

Named for the navigation technique: you need at least three reference points to confirm your position. Apply the same logic to AI output.

### Check 1 — The Source Check (2–5 minutes)
Ask AI: *"What is your source for this claim? Name the specific document, author, date, and where I can find it."*  
For anything going into a client document, a decision, or an external communication — verify against the original source, not another AI or a summary.

> [!warning] AI giving you a source does not mean the source exists:  
> AI can hallucinate references with the same confidence as facts. Always verify independently — not by asking AI again.

**HK primary sources by topic:**

> If the site does not redirect to its formal site, you may try to put prefix "https://www." before following primary sources. For example, it should be https://www.gov.hk for gov.hk.

| Topic | Primary source |
|---|---|
| **PDPO / personal data** | pcpd.org.hk |
| **Company law** | cr.gov.hk |
| **Employment law** | labour.gov.hk |
| **SFC regulations** | sfc.hk |
| **HKMA / banking** | hkma.gov.hk |
| **Government policy** | gov.hk |
| **Ordinances / legislation** | elegislation.gov.hk |
| **HKPC AI guidance** | hkpc.org |
| **PCPD AI guidance** | www.pcpd.org.hk/english/artificial_intelligence/index.html |
| **Scripture / theology** | The Bible itself; your pastor |

---

### Check 2 — The Doubt Question (30 seconds)
Ask AI: *"What are you uncertain about in this answer? What might you have wrong?"*

**Prompt template:**
```
Before I use this, tell me:
- What parts of this answer are you least confident about?
- What would change your answer if I told you [relevant context]?
- Are there HK-specific rules that might make this different?
- What claims should I verify, and where?
```

---

### Check 3 — The Ground and Attribute Check (30–60 seconds)
Provide the source material directly in the prompt. Ask the AI to work only from what you provide, and to cite which section supports each claim.

**Prompt to use (source grounding):**
```
Based only on the following text, answer the question below.
Do not add any information that is not in the text.
If the answer is not in the text, say: "I cannot find this in the provided sources."
After each key point, indicate which paragraph or section of the source supports it.

Question: [your question]
Text: [paste your source document]
```

**Why it works:** Grounding forces the model to work from your source, not its training. Errors become misreadings of a visible document — detectable — rather than invisible fabrications.

---

## 7. The S-A-F-E-R Framework

If you are using AI for technical or project work, "Think step by step" isn't enough. You need a source-grounded framework.

Use the **S-A-F-E-R** mental checklist:

- **S — Source-bounded** — only use stated sources; no free recall
- **A — Admit uncertainty** — force the AI to say "I don't know"
- **F — Fact-evidence** — each claim tied to specific evidence
- **E — Expiry awareness** — flag risks of outdated data (critical for standards)
- **R — Review format** — use tables to separate facts from inference

**S-A-F-E-R Structured Output Template:**
```
Return your answer as a table with these columns:
  Claim | Evidence | Source | Source date | Confidence | Needs checking
```

**Self-Audit Prompt:**
```
List the 5 most important factual claims in your answer. For each, provide: 1) The best source, 2) the date, 3) a Google search query to verify it.
```

**Why this works:** It shifts the burden of proof back to the AI. Hallucinations often collapse when the AI is forced to cite its work.

---

## 8. What Works — and What Doesn't

| Effectiveness | Prompt additions |
|---|---|
| **Most effective** | "Use only these sources" · "Say 'I don't know' if unsure" · "Cite each claim with source and date" · "Mark unsupported claims" · "Extract exact quotes first, then answer" |
| **Moderately effective** | "Summarise your assumptions" · "List possible weaknesses" · "Give a confidence level per claim" |
| **Less reliable** | "Explain your chain-of-thought" · "Think step by step" (alone) · Long reasoning without evidence anchoring |

**Note on Chain-of-Thought:** Asking for chain-of-thought is **NOT** the best defence against hallucination. Models can produce confabulated logic — the explanation sounds convincing while still being wrong.

Better alternatives:
- **Brief reasoning** — ask for a short reasoning summary
- **Key assumptions** — ask what assumptions are being made
- **What's wrong?** — ask "what could be wrong with this?"
- **Evidence per claim** — ask for evidence for each claim
- **What to verify?** — ask "what needs independent verification?"

---

## 9. Red Flags — Hallucination Warning Signs

| Flag | Warning sign |
|---|---|
| 🔴 **Precise numbers** | Specific figures with no source given |
| 🔴 **Unfindable citation** | Cannot be found on Google |
| 🔴 **Unnamed experts** | "Studies show..." or "experts say..." with no name |
| 🔴 **100% confident tone** | On a nuanced or contested topic |
| 🔴 **Unknown framework** | "The XYZ 7-Step Model" nobody else mentions |
| 🔴 **Recent events** | Anything in the last 12–18 months may be outdated |
| 🟡 **Plausible but new** | Sounds right but you've never heard it before |
| 🟡 **Slightly odd mix** | Correct information mixed with odd claims |
| 🟡 **Outdated specifics** | Tools, laws, software versions, or product features |

---

## 10. Prompt Templates for Hallucination Defence

### The Calibration Prompt
Use before any research or fact-finding task:
```
Instruction (Before you answer):
- Tell me your confidence level (high / medium / low)
- Tell me what you are most uncertain about
- Flag anything time-sensitive or jurisdiction-specific
- Tell me which claims I should verify and where
- Tell me if you are drawing from general training rather than from a source I have provided
```

### The HK Law / Regulation Prompt
Use for any legal or regulatory question:
```
Task:
I am asking about this in a Hong Kong context.

Instruction:
- Tell me if this is based on HK law or overseas principles
- Name the specific HK ordinance, regulation, or guidance you are drawing from
- Flag where HK law differs significantly from UK or US law
- Tell me if I should verify on elegislation.gov.hk or with a HK solicitor
```

### The Summary Check Prompt
Use when asking AI to summarise a document:
```
Task: Summarise this document.

Instruction (after your summary):
- List any part of the original document that was complex, conditional, or nuanced, and note whether your summary preserved that complexity
- Identify conditions or exceptions that must not be omitted
- Note any figures, thresholds, or dates I should double-check
```

### The Scripture / Theology Safety Prompt
Use for any task involving scripture or theological content:
```
Task: I need help with [task involving scripture or theology].

Instruction:
- Do not present theological interpretations as authoritative
- If different Christian traditions hold different views, note that
- Flag any scriptural references you are uncertain about
- I will verify all scriptural content in the Bible before using it
```

---

## 11. The Human Review Gate

Before using any AI output, answer these four questions:

| Question | If No — stop here |
|---|---|
| **Read full output?** | Do not skim and assume |
| **Facts and citations verified?** | Do not forward unverified claims |
| **Qualified human available?** | Do not rely on AI for professional judgment |
| **Can stand behind it?** | If not — check more |

> [!important] The accountability test:  
> Would I be comfortable standing behind this output if challenged?  
> If yes — you have done enough. If no — check more before using it.

---

## 12. Hallucination Risk by Task Type

| Task | Risk | Key defence |
|---|---|---|
| **Summarising your document** | Low–Medium | Check conditions and exceptions preserved |
| **Drafting from your notes** | Low | Read full output before use |
| **Researching facts or law** | High | Verify against the primary source |
| **Generating citations** | Very High | Never use without confirming the source exists |
| **HK legal / regulatory Q&A** | Very High | Verify on official HK source or with a solicitor |
| **TC translation** | Medium | Check terminology with a qualified bilingual reviewer |
| **Scriptural interpretation** | High | Verify in the Bible; consult your pastor |
| **Grant statistics** | Very High | Never let AI fabricate figures; ask AI to use placeholder text like [INSERT ACTUAL STATISTIC] instead |

---

## 13. If Hallucination Has Already Happened

- **Correct immediately** — notify anyone who received the wrong information
- **Preserve the record** — keep the original AI output and your correction
- **Assess impact** — who received it, what decisions it may have affected
- **Review the gap** — which check did not happen that should have?
- **Update your process** — add the specific check that would have caught this
- **PDPO obligation?** — if personal data was involved, this may trigger a reporting obligation; raise it immediately

---

## 14. Quick Reference Card

```
BEFORE using AI output:
- [ ] Did I ground the prompt in source material? - Reduces fabrication
- [ ] Did I ask for uncertainty flags? - Surfaces weak spots
- [ ] Did I ask for the source? - Verify it exists
- [ ] Did I read the full output? - Not just the first paragraph
- [ ] Can I stand behind this? - Accountability test

HIGH-RISK — always verify independently:
- Specific statistics · Named cases or laws · Dates and thresholds
- Citations and references · Recent events · HK regulatory conclusions

HK PRIMARY SOURCES — bookmark these:
- pcpd.org.hk · elegislation.gov.hk · gov.hk
- cr.gov.hk · sfc.hk · hkma.gov.hk
```

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Essentials Feedback Form](https://forms.gle/52JirD3TMQqSwJbm7)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.1 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
