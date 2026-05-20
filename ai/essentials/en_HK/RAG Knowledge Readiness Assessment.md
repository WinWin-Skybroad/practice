---
title: RAG Knowledge Readiness Assessment
created: 2026-04-04
version: "1.0.1"
tags:
  - WinWin-Skybroad
  - RAG
  - knowledge-base
  - data-readiness
  - PDPO
  - 3R
status: active
type: assessment
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
---
# RAG Knowledge Readiness Assessment

**Before building AI that answers from your documents**

> [!quote] What this is for:  
> RAG (Retrieval-Augmented Generation) lets AI answer questions by searching your own documents rather than relying on its training data alone. It sounds powerful — and it can be. But it only works if your documents are clean, current, organised, and legally permitted to use.  
> This assessment helps you find out whether you are ready before you start building.

**What this assessment is:** A structured readiness check for any AI use case that relies on searching and retrieving from a document corpus.

**What this assessment is not:** A technical RAG implementation guide or a guarantee that a passing score means your system will work correctly. Document readiness reduces hallucination risk — it does not eliminate it.

---

## 1. What Is RAG and Why Does Readiness Matter?

In a standard AI conversation, the model draws on its training data. In a RAG system, the model first retrieves relevant content from a document library you provide, then uses that content to generate an answer.

This means: **the quality of your answers is bounded by the quality of your documents.**

A RAG system built on bad documents produces bad answers — confidently. Unlike a simple search, RAG does not show you the raw documents. It synthesises them. Errors are invisible until something goes wrong.

**Common RAG failure modes:**
- **Outdated policy** — answers a client with last year's rules
- **Blank TC documents** — scanned Chinese returns blank; AI invents answers
- **Format gaps** — mixed document formats cause retrieval gaps; some content never surfaces
- **Personal data exposed** — sensitive data ends up embedded in AI responses
- **Contradictory answers** — conflicting documents produce contradictory answers
- **Missing source** — AI answers confidently when the right source is missing from the corpus

---

## 2. Assessment Structure

This assessment has four gates. A failure at any gate means the work to fix that gate must happen before the RAG system is built.

| Gate | What it checks | Failure effect |
|---|---|---|
| **Gate 1 — Legal Permission** | Are you allowed to use these documents in an AI system? | Data breach, PDPO violation, trust damage |
| **Gate 2 — Document Quality** | Are the documents machine-readable, current, accurate, and consistent? | Hallucination, gaps, wrong answers |
| **Gate 3 — Knowledge Architecture** | Is the document library organised so AI can retrieve the right thing? | Retrieval failures, irrelevant answers |
| **Gate 4 — Governance** | Are there controls to keep the system accurate and bounded over time? | Drift, uncontrolled scope, undetected errors |

> [!warning] A failure at any gate means: fix that gate before building. Do not pilot a RAG system with unresolved gate failures.

---

## 3. Readiness Gates — Four Sequential Checks

Complete each gate in sequence. A failure at any gate is a stop condition — resolve it before moving to the next gate. Do not proceed to Gate 2 if Gate 1 has unresolved items. The gates are designed this way deliberately: a legal permission problem found after building is far more costly than finding it now.

### G1 Gate 1 — Legal Permission

Answer every question. A single "No" or "Unsure" in this gate means: **stop and resolve before proceeding.**

#### G1.1 Data Collection Purpose
- [ ] **Compatible purpose** — documents were created for purposes compatible with AI processing
- [ ] **Purpose articulated** — we can explain why AI processing is consistent with the original collection purpose

> [!warning] PDPO Principle 3:  
> Personal data collected for one purpose must not be used for a materially different purpose without consent. Using HR files, client records, or pastoral notes to power an AI Q&A system is almost certainly a new purpose requiring fresh assessment.

#### G1.2 Personal Data Assessment
- [ ] **Personal data identified** — documents containing names, HKID, contacts, health, financial, or HR information identified
- [ ] **Excluded or justified** — personal data excluded from corpus, OR inclusion confirmed legally appropriate and documented
- [ ] **Pastoral records excluded** — no beneficiary records, counselling notes, prayer requests, or sensitive disclosures in the corpus

#### G1.3 Access Control
- [ ] **Users see only what they should** — RAG system only surfaces documents permitted for the querying user
- [ ] **No cross-role leakage** — no risk of a staff member retrieving documents for a different team or role
- [ ] **Sensitive documents protected** — HR, financial, and pastoral documents excluded or behind access controls

#### G1.4 Tool and Vendor Terms
- [ ] **Provider terms reviewed** — AI tool provider's terms of service and data handling policy reviewed
- [ ] **Training terms understood** — whether the tool retains, indexes, or trains on uploaded documents
- [ ] **Data residency acceptable** — tool's data residency terms are acceptable for this content type

#### G1.5 Third-Party Content Rights
- [ ] **Ownership confirmed** — we own or have rights to use all documents for AI processing
- [ ] **Copyrighted content excluded** — no third-party copyrighted content without checking licence terms
- [ ] **Government documents permitted** — used within their permitted terms

#### G1.6 Confidentiality and Sensitivity
- [ ] **Confidential excluded** — no documents marked Confidential or Restricted unless separately approved
- [ ] **Trade secrets excluded** — no commercially sensitive information or pricing data
- [ ] **Legal privilege excluded** — legally privileged communications excluded

#### Gate 1 result: Pass / Fail

> [!warning] Gate 1 is a hard stop:  
> If any item above is "No" or "Unsure" — do not proceed to Gate 2 until it is resolved.  
> A legal or data permission problem found after building is far more costly than finding it now.

---

### G2 Gate 2 — Document Quality

#### G2.1 Machine Readability

| Document type | Readability | Action |
|---|---|---|
| Typed Word / Google Docs | ✅ Usually readable | Verify character encoding |
| Typed PDF (digital text) | ✅ Usually readable | Spot-check text extraction |
| Scanned PDF — English | ⚠️ Depends on OCR quality | Test extraction; apply OCR if needed |
| Scanned PDF — Traditional Chinese | 🔴 Often NOT readable | Must convert to digital text first |
| Image files (JPG, PNG of document) | 🔴 Not readable as text | Must OCR and validate |
| WhatsApp / messaging exports | ⚠️ Mixed quality | Clean and reformat before including |
| Audio/video transcripts | ⚠️ Depends on transcript quality | Validate accuracy before including |

- [ ] **Digital text only** — all documents in machine-readable text format; no scanned images
- [ ] **Converted where needed** — tables, multi-column layouts, and formatted documents extracted to plain text
- [ ] **Every document tested** — representative section extracted and verified as accurate
- [ ] **TC readability tested** — every Traditional Chinese document tested for text selectability
- [ ] **TC scanned converted** — all Traditional Chinese scanned documents converted to machine-readable text and verified
- [ ] **Unextractable removed** — documents that cannot be reliably extracted have been removed

**HK-specific test:** For any TC document — try selecting and copying a paragraph. If it copies as readable characters, it is likely machine-readable. If it selects as a single image block, it needs OCR preprocessing before use.

#### G2.2 Timeliness and Accuracy
- [ ] **Version date on every document** — or last-reviewed date
- [ ] **Old documents reviewed** — documents older than [set threshold] checked for accuracy
- [ ] **Outdated content removed** — superseded policies, old staff, or outdated procedures updated or removed
- [ ] **Update process exists** — process for updating the corpus when policies change
- [ ] **Named owner per document** — responsible for updates
- [ ] **Sample spot-checked** — 3–5 documents checked: 3–5 specific facts each verified against current source of truth
- [ ] **Facts match reality** — names, dates, fees, policies, and procedures match current real-world state
- [ ] **No conflicting versions** — or if they exist, the correct version is clearly identified
- [ ] **OCR errors checked** — scanned or OCR-processed documents checked for extraction errors

> [!warning] Stale documents are a silent hallucination source:  
> A RAG system does not know a document is outdated. It will answer with last year's policy — confidently. Date-stamp every document and set a review cycle before building.

#### G2.3 Completeness
- [ ] **Questions mapped** — top 20 recurring questions mapped to specific documents: Fully covered / Partly covered / Not covered
- [ ] **Critical policies present** — not just partial coverage
- [ ] **Exceptions documented** — edge cases and escalation paths documented, not just standard flow
- [ ] **Gap threshold** — if more than 25% of target questions are Not covered, the corpus has gaps that will cause the AI to guess

#### G2.4 Provenance
- [ ] **Known source** — every document has a known origin; not "downloaded from somewhere"
- [ ] **Named owner** — every document has a named responsible person
- [ ] **Transformation traced** — documents that were scanned, OCR'd, or reformatted still trace back to the original

#### G2.5 Consistency and Conflicts
- [ ] **Consistent across documents** — same topic covered consistently in multiple documents
- [ ] **Contradictions resolved** — contradictory documents reconciled or one version designated as authoritative

> [!note] Hierarchy of Truth:  
> If two documents give different answers to the same question, establish in advance which one is the authoritative source. Without this, the AI will produce contradictory answers depending on which chunk is retrieved.

#### G2.6 Scope and Completeness
- [ ] **Covers real questions** — corpus covers the questions users will actually ask

> [!note] Practical test:  
> Take 10–20 real questions the AI system will need to answer. Can the answer be found in the documents you have assembled? If more than 3 of 10 cannot be answered from your documents — the corpus is not ready.

- [ ] **No hallucination gaps** — no obvious gaps where AI will have no content to retrieve and may hallucinate
- [ ] **Scope bounded** — decided what the system will and will not answer
- [ ] **Out-of-scope fallback** — out-of-scope questions have a defined fallback response

#### Gate 2 result: Pass / Fail

> [!warning] Gate 2 key insight:  
> Most organisations discover their document problem in Gate 2 — not in technical setup.  
> Cleaning documents before building is faster than debugging a live system with bad answers.

---

### G3 Gate 3 — Knowledge Architecture

#### G3.1 Relevance and Scope
- [ ] **Use case focused** — corpus contains only documents directly tied to the use case; not everything in the shared drive
- [ ] **Noise excluded** — irrelevant or tangential documents removed
- [ ] **Scope in writing** — what is included and what is not, defined in writing

**Relevance test:** Take 10–20 real questions the AI system will need to answer. Can the answer be found in the documents you have assembled? If more than 3 of 10 cannot be answered — the corpus is incomplete for this use case.

#### G3.2 Structure and Retrievability
- [ ] **Logically categorised** — by topic, department, or document type
- [ ] **Headings and structure** — meaningful headings; not one long undivided block of text
- [ ] **Useful metadata** — title, owner, date, topic, document type on every document
- [ ] **Filterable** — system can filter by date, department, or document type
- [ ] **Long documents split** — split at logical boundaries so retrieval surfaces the right section
- [ ] **Master index exists** — list or index of what is in the corpus
- [ ] **Duplicates removed** — duplicate or near-duplicate versions consolidated

#### G3.3 Chunk Design and Retrieval Testing
- [ ] **Complete thoughts** — chunks sized to contain a complete thought; not cut mid-sentence or mid-policy
- [ ] **Source metadata per chunk** — document name, section, date, and version
- [ ] **TC boundaries respected** — for Traditional Chinese content, chunks respect TC sentence and paragraph boundaries
- [ ] **Representative questions tested** — 10–20 representative user questions written and tested
- [ ] **Right documents surfaced** — retrieval system surfaces the right documents for representative questions
- [ ] **Out-of-scope tested** — at least 5 out-of-scope questions tested; system declines appropriately

#### G3.4 Retrieval Quality Testing
- [ ] **Answers correct** — test answers checked: is the answer correct? Does it cite the right source?
- [ ] **Right source retrieved** — relevant source being retrieved, not an unrelated document
- [ ] **"I don't know" tested** — system says so when it does not know; does not hallucinate
- [ ] **Poor result types identified** — query types that return poor results identified and understood

#### G3.5 Access Control (PDPO Alignment)
- [ ] **Permissions respected** — retrieval respects user permissions; users only see permitted documents
- [ ] **Sensitive excluded or redacted** — before indexing
- [ ] **Audit logging** — queries and retrieved chunks logged for PDPO accountability

#### G3.6 Language and Bilingual Handling
- [ ] **Language decided** — whether system responds in English, Traditional Chinese, or both
- [ ] **Corpus language matches** — query language expected
- [ ] **Bilingual consistency** — for bilingual systems: same policy expressed consistently in both languages

#### Gate 3 result: Pass / Fail

---

### G4 Gate 4 — Governance

#### G4.1 Output Verification
- [ ] **Sources cited** — system cites sources for every claim; users can check the source section
- [ ] **Uncertainty flagged** — when the system is not sure, it says so rather than guessing
- [ ] **Feedback process** — clear process for users to flag an answer they believe is incorrect

#### G4.2 Human Review
- [ ] **Named reviewer** — person responsible for reviewing AI responses before high-stakes use
- [ ] **Review before external use** — human review required before any RAG output is used in an external communication or formal decision
- [ ] **AI disclosed** — users know they are interacting with AI, not a human

#### G4.3 Ongoing Maintenance
- [ ] **Named corpus owner** — responsible for keeping documents current
- [ ] **Review cadence defined** — how often will documents be checked and updated?
- [ ] **Update process** — when a policy changes, clear process for updating the relevant document
- [ ] **Outdated archived** — outdated documents archived or removed; not left in the live corpus
- [ ] **Change log** — version record of what corpus version was live at any given time

#### G4.4 Scope Boundaries
- [ ] **Scope statement** — system has a clearly defined scope: what it will and will not answer
- [ ] **Graceful refusal** — out-of-scope questions produce a refusal and referral to a human
- [ ] **Always out of scope** — system does not attempt to answer: pastoral care, medical, legal, beneficiary eligibility, or HR decisions
- [ ] **Users informed** — users told what the system can and cannot do

#### G4.5 Monitoring and Error Response
- [ ] **User flagging** — mechanism for users to report wrong answers
- [ ] **Investigation process** — defined process for investigating reported errors
- [ ] **Pause rule** — under what conditions will the system be taken offline for review?
- [ ] **Post-incident learning** — documented and fed back into document improvements
- [ ] **Question logging** — process for logging questions and answers for periodic review
- [ ] **Flag response** — process for acting on flagged wrong answers, including corpus update
- [ ] **Escalation path** — defined if a serious error occurs

#### Gate 4 result: Pass / Fail

---

## 4. Summary Assessment

| Gate | Result | Priority fixes |
|---|---|---|
| Gate 1 — Legal Permission | Pass / Fail | |
| Gate 2 — Document Quality | Pass / Fail | |
| Gate 3 — Knowledge Architecture | Pass / Fail | |
| Gate 4 — Governance | Pass / Fail | |

---

## 5. Red / Amber / Green Decision

Based on all four gates:

| Status | Meaning | Decision |
|---|---|---|
| 🟢 **Green** | All gate items pass | Proceed to pilot — build and test with a limited audience first |
| 🟡 **Amber** | Specific items fail — gaps identified | Fix identified gaps; re-assess before building |
| 🔴 **Red** | Gate 1 fails, or multiple Gate 2/3 items fail | Do not proceed — address root causes first |

**Most common reasons for Amber or Red:**
- **No document owner** — Gate 2 / Gate 4
- **No version dates** — Gate 2
- **Multiple versions** — no clear current copy circulating, Gate 2
- **Personal data in corpus** — without legal review, Gate 1
- **Scanned TC without OCR** — Gate 2
- **Confident wrong answers** — system answers when source does not cover the question, Gate 4

---

## 6. HK-Specific Checklist Before Go-Live

- [ ] **TC scanned converted** — all Traditional Chinese scanned documents converted and verified
- [ ] **PDPO Principle 3** — compliance confirmed for all personal data documents
- [ ] **Pastoral records out** — no pastoral, counselling, or sensitive ministry records in the corpus
- [ ] **Bilingual tested** — retrieval tested with both English and Traditional Chinese queries
- [ ] **HK regulatory verified** — HK regulatory content verified against official sources before including
- [ ] **Funder AI policy** — if grant-related documents included, funder confirmed AI processing is permitted

---

## 7. Ongoing Monitoring — Before Going Live, Confirm These

| Requirement | Named Owner | Review Frequency |
|---|---|---|
| Document updates when policies change | | |
| Full corpus review for accuracy and currency | | |
| User feedback collection on wrong or unhelpful answers | | |
| Pause / rollback rule definition | | |

> [!important] The invisible degradation problem:  
> A knowledge base that passes this assessment on Day 1 can fail silently six months later.  
> A policy changes, no one updates the document, and the system continues to give confidently wrong answers.  
> The most important governance question is not "Is it ready now?" but "Who keeps it ready after we launch?"

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Essentials Feedback Form](https://forms.gle/52JirD3TMQqSwJbm7)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0.1 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
