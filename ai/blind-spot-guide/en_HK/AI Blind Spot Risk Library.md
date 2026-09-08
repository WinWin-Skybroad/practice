---
title: AI Blind Spot Risk Library
created: 2026-07-06
updated: 2026-09-06
version: "1.0"
status: active
licence: CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad
locale: en_HK
type: guide
tags:
  - risk-library
  - ai-blind-spot
---

# AI Blind Spot Risk Library

## 1. Purpose and Scope

Use this page as the **canonical registry and reference** for the AI Blind Spot risks recognised by the Win.Win AI Blind Spot Guide. This is the authoritative location for each canonical risk definition.

Each risk entry explains:
- what the risk is;
- how it may appear;
- how unstated context may contribute;
- what a responsible person must solve; and
- what the reviewer should do before use.

Use this file when a named AI Blind Spot risk needs more explanation than a short Review Card cue provides. After identifying the risk, use [[AI Blind Spot Control Map]] to select the relevant canonical Control or Controls and understand why they may help. Then use any relevant detailed method or guidance. Use [[Unstated Context Control]] only if the detailed unstated-context guidance is relevant.

This is not a complete taxonomy of every possible AI risk. It is the current canonical AI Blind Spot risk set for this guide. One risk may relate to several Controls, and one Control may address several risks. Change this risk set only through owner-approved review.

---

## 2. Entry Structure Standard

Risk entries are grouped under **3. Risks**. Each named risk uses a numbered H3 heading and unnumbered H4 section headings.

Do not replace risk-specific content with generic repeated wording. Every risk needs recognisable examples and a distinct reviewer action. Keep an optional section only if it adds risk-specific control meaning.

---

### 2.1 Mandatory Sections

#### What it is

State the authoritative definition of the canonical risk in plain language. The same risk must not be independently redefined in [[Glossary]] or another page.

#### How it appears

Give recognisable examples of how the Blind Spot may appear in AI-supported work.

#### How unstated context may matter

Explain whether unstated context is the main issue, one contributing issue, or a related review concern for that risk.

#### What a responsible person must solve

State what human judgement, authority, accountability, verification, impact or consequence question must be solved before use.


#### Reviewer action

State what the human reviewer must check, decide, route or escalate before the output is used.

---

### 2.2 Optional Sections

Use an optional section only if it adds risk-specific control meaning that would otherwise be lost.

#### Additional implementation notes

Use this optional section only for a distinct risk-specific practical lesson that would otherwise be lost. Do not use it as a miscellaneous list of related Controls, Methods, Accountable Routes, reviewers, owners, or processes; the Control Map owns the relationship mapping. If the section is kept, explain why the note matters and what the reader should do. Do not create new canonical names here.

#### Prompt-side control

State a prompt-side action that may reduce the risk before the output is created, without implying that prompting replaces human review.

#### What “real” means

Explain how real people, setting, authority, timing, consequences, or intended use should be understood for this risk.

#### How it can affect the output

Explain what the missing or mishandled context may change in the output.

#### Context that should remain outside the AI interaction

Identify sensitive or restricted context that should be handled through human review rather than entered into AI.

#### Context that cannot be fully written down

Explain when lived context, relationship knowledge, professional instinct, or local judgement may not be fully expressible for AI use.

#### Limits of prompt-side control

Explain when prompting may help but cannot replace verification, judgement, authority, review, or escalation.

#### Unstated Context Control guidance

Use this optional section if the detailed Unstated Context Control guidance materially helps with the risk. Do not call it the sole or main Control merely because it is the current detailed focus.

#### Escalate when

State the conditions that require an accountable owner, reviewer with standing, specialist reviewer, approved process, or escalation route.

Do not remove one of these sections merely to make every risk entry look identical.

---

## 3. Risks

### 3.1 AI Blind Spot

#### What it is

A condition in which an AI-supported output can appear clear, complete, balanced or confident while AI cannot reliably see, hold, judge, verify, authorise or be accountable for something a responsible person must address.

In plain English, AI may miss something important even when the output is fluent, plausible, polished, and confident. Polished wording is not proof that the important context, authority, accountability, consequences, verification, or human judgement have been handled.

Not every AI error is an AI Blind Spot. Adding more context also does not, by itself, solve authority, accountability, independent verification, professional-instinct, or recipient-impact problems.

Use this general **AI Blind Spot** entry if something important may be missing or unresolved but you cannot yet identify a more specific risk. Then use the other entries in this library to narrow the risk and choose a more specific Control, Method, review, or Accountable Route.

#### How it appears

- **Simple example:** AI produces a confident approval message even though it has no authority to make the commitment and has not independently verified the condition.
- The draft sounds reasonable but ignores a sensitive local issue.
- The answer is correct in general but wrong for this organisation, jurisdiction, moment or profession.
- AI has been given a description of the context, but still treats the situation as text to process rather than a real setting with pressure, history, expectations, and consequences.
- AI can describe the USA, Hong Kong, a profession, a community, or an organisation. But a described place, profession, community, or organisation is not the same as the real one.
- The output sounds professional, but an experienced practitioner would hesitate because something about the case, figure, wording, timing, or exception feels wrong.

#### How unstated context may matter

Unstated context may be one major source of the Blind Spot, but the wider risk may also involve judgement, authority, accountability, verification limits and consequence awareness that cannot be supplied by a prompt alone.

#### What a responsible person must solve

The responsible person must solve whether the output fits the real people, setting, authority, timing, consequences and use situation, not merely whether it reads well.


#### Reviewer action

Check the real people, real setting, real authority, and real consequences.

If relevant, consult a responsible experienced person. Identify what that person would notice, question, verify, qualify, withhold, or escalate before use.

#### Prompt-side control

Ask AI to state important assumptions, uncertainties, missing sources, authority limits, and matters requiring human judgement. This is a review aid, not proof that the Blind Spot has been resolved.

#### What “real” means

`Real` means the actual people, setting, authority, timing, consequences, and intended use—not merely a plausible description of them.

For example:
- To check whether an output suits a real group of people, consider the characteristics, expectations, experiences, relationships, rights, sensitivities, or circumstances that matter to that task.
- To check whether an output meets a real professional standard, use judgement from someone who understands and carries responsibility for that professional practice. Do not rely only on a description of the practice in the prompt.

#### Unstated Context Control guidance

Use **Unstated Context Control** if a task-basis gap contributes to the risk. Use the relevant additional Controls, Methods, and Accountable Routes in [[AI Blind Spot Control Map]] for verification, authority, impact, local, specialist, operational, or escalation needs.

---

### 3.2 Unwritten Context Gap

#### What it is

A material gap in which relevant context is absent from, incomplete in, or not adequately represented in the task basis. The risk name does not limit the gap to literally unwritten information.

The risk also covers context that is written in an approved record but effectively absent from the task because the record was not retrieved, the task-relevant material was not extracted, or the context was not adequately represented.

#### How it appears

- **Simple example:** A record exists but was not retrieved, so the AI answer misses the approved exception.
- An informal policy exception changes what should be said.
- Local history known to long-serving people is not in the source packet.
- A relationship issue changes timing, tone or recipient impact.
- Everyone understood a caveat but nobody recorded it.
- An approved record exists but was not retrieved or properly extracted for the task.

#### How unstated context may matter

The missing context can change what the output says, omits, emphasises, recommends, promises or avoids. It can also change review, approval, delivery, timing or whether the task should proceed.

#### How it can affect the output

The missing context may change what the output should say, omit, emphasise, recommend, promise, or avoid. It may also change who should review or approve it, how it should be delivered, or whether the task should proceed.

AI may produce an answer that is correct against the supplied text but wrong for the real organisation, current practice, recent decision, exception, relationship, or approved record.

#### What a responsible person must solve

Identify the gap, locate the source, assess representability, and choose the minimum safe route. Decide whether the context should be added, converted, kept human-only, verified, escalated or not used.


#### Prompt-side control

Use this sequence:
- Identify the context that could materially affect the output.
- Add only context that is necessary, accurate, permitted, current, and safe for the task.
- Keep sensitive, confidential, personal, uncertain, or otherwise restricted context out of the AI interaction.
- If AI still needs guidance, convert only the necessary effect into a safe form. This may be a fact or source, a constraint or wording rule, an omission or review instruction, an approval boundary or human-drafting requirement, or an escalation trigger. Do not provide the sensitive backstory itself.
- If the underlying information remains subject to another obligation, handle that obligation separately outside the AI interaction. This may include:
  - giving the information to an authorised audience;
  - checking a required source or making a required record;
  - following a required decision or approval process;
  - using a safeguarding or professional route; or
  - meeting a legal, regulatory, privacy, or other applicable requirement.

Keeping information out of AI must not be used to conceal it or bypass any requirement that still applies.

#### Reviewer action

Use the route that matches the likely source of the missing context:
- **People:** If suitable people may hold relevant context through experience or local practice, consult those people.
- **Approved records:** If relevant context may exist in approved records, check the appropriate records through the relevant source route.
- **Sensitive or restricted context:** Keep it outside AI and handle it through the appropriate human route.

Then decide whether to correct the output, check it with the appropriate source or decision owner, keep part of the judgement in human-only handling, or escalate.

#### Context that should remain outside the AI interaction

Some relevant context should stay outside the AI interaction. Examples include confidential information, personal details, safeguarding information, private relationship history, unverified allegations, sensitive organisational matters, and other information outside the approved data boundary.

The responsible reviewer must still account for that context. If safe conversion is not possible:
- keep the affected judgement or wording in human-only handling; and
- route it to a reviewer with suitable standing.

#### Context that cannot be fully written down

Some context is hard to capture fully. Examples include individual preferences, relationship history, local working habits, lived context, professional instinct, or a judgement that wording may be unsuitable in the actual situation.

Check whether the output fits the real people and circumstances. Do not assume that a written description captures everything that matters. Some relevant factors cannot or should not be fully expressed for AI use.

#### Unstated Context Control guidance

Use [[Unstated Context Control]] to identify the gap, locate possible sources, assess representability, and select the minimum current-task route.

Use [[Source Packet Add-On]] if a current approved source should be retrieved and task-relevant approved material extracted.

Use [[Elicitation Techniques]] only if suitable people still hold important context and it is safe and appropriate to ask them about it.

#### Additional implementation notes

**Preservation is separate.** Preserve context for later only if it is sufficiently reliable, necessary, reusable, permitted, and appropriate to retain. Do not preserve sensitive, disputed, restricted, or unsafe context merely because it may be useful.

#### Escalate when

Escalate when the context affects rights, access, money, role, safety, privacy, reputation, authority, or another consequence the reviewer cannot safely resolve.

Escalate when the context is sensitive, disputed, restricted, high-consequence, outside the reviewer’s standing, or tied to a matter that requires a qualified or authorised route.

---

### 3.3 Reader Interpretation Gap

#### What it is

A risk that readers may understand wording differently from the sender’s intended meaning.

#### How it appears

- **Simple example:** A polite internal phrase sounds dismissive to the external audience.
- Neutral wording sounds harsh.
- A suggestion sounds certain.
- Bilingual wording changes tone or social meaning.
- Wording appears to approve, refuse or commit when that was not intended.

#### How unstated context may matter

Audience history, relationship cues, timing, role expectations, register and prior events may be absent from the task basis but shape how wording lands.

#### What a responsible person must solve

Check likely reader interpretation and revise wording as needed, including tone, certainty, authority, commitment, action required, local meaning, and likely reader inference.


#### Reviewer action

Review the wording as the real audience would read it today. Consider whether the reader may infer blame, certainty, commitment, refusal, approval, or required action differently from the intended meaning.

---

### 3.4 Recipient Impact Blindness

#### What it is

A risk that AI may miss emotional, relational, practical, reputational, or social impact on a real recipient or group. This may include dignity, pressure, exclusion, or other effects that are not evident from technical accuracy alone.

#### How it appears

- **Simple example:** A reminder is technically accurate but insensitive after a recent incident.
- A message is accurate but badly timed.
- A broad announcement is drafted before affected people are told directly.
- A technically correct note damages trust or dignity.
- The output creates pressure, embarrassment, exclusion or reputational harm.

#### How unstated context may matter

Recent events, relationship history, vulnerability, dignity concerns, likely reaction and trust context may be missing from the task basis.

#### What a responsible person must solve

Assess the impact on real recipients and use a suitable human reviewer.

Identify:
- who is affected;
- what they may feel or infer;
- what action or pressure the output may create; and
- how timing or relationships may change the impact.


#### Reviewer action

Check timing, affected people, dignity, practical pressure, relational impact, reputation and whether affected people must be contacted directly before broader use.

---

### 3.5 Authority Boundary Blindness

#### What it is

A risk that AI may draft as if it can approve, promise, decide, refuse, authorise, or speak for the organisation. The same authority problem may arise when wording appears to speak for another person or role without the required authority.

#### How it appears

- **Simple example:** A draft says “we confirm funding” when no authorised person has approved funding.
- The output says “we approve” without authority.
- A policy answer sounds binding.
- The draft makes an unauthorised promise.
- A recommendation is presented as an agreed decision.

#### How unstated context may matter

Actual authority practice, delegation limits, approval owner, sign-off history and organisational norms may be absent or ambiguous in the task basis.

#### What a responsible person must solve

Identify who has authority and remove, qualify, or escalate unauthorised commitments. Check what the output appears to decide or commit to and who actually has authority.


#### Reviewer action

Separate drafting from deciding. Remove or qualify approval, promise, commitment or refusal language unless the authority owner has approved it.

---

### 3.6 Materiality Judgement Gap

#### What it is

A risk that AI may miss whether a detail would change a decision, approval, funding, trust, or next action. Depending on the task, materiality may also affect timing, rights, access, or cost.

#### How it appears

- **Simple example:** AI treats a missing date as minor when it affects eligibility.
- An important caveat is omitted or softened.
- A minor issue is overemphasised.
- An uncertain figure is treated as decisive.
- A material exception is presented as background.
- Information is supplied but misweighted.

#### How unstated context may matter

Known thresholds, dependencies, risk appetite, funder expectations, board concerns, consequences or exception history may be absent or not adequately represented.

#### What a responsible person must solve

Determine whether the detail is material. Route the matter to the decision owner if needed. Identify the conditions or thresholds that matter and keep unresolved uncertainty visible.


#### Reviewer action

Use this review sequence:
- Identify which details, if wrong, missing, or misweighted, could change the decision, approval, funding, trust, or next action.
- Use the question: **Material relative to what decision or consequence?**
- Identify the actual reference point for the decision. This may be a budget or account, threshold, eligibility condition, dependency, timing constraint, right, obligation, commitment, cost, consequence, or another decision-relevant factor.
- Do not judge materiality only by how large or prominent a detail looks.
- Do not rely on AI alone to make the final materiality judgement when the consequences are human or organisational.

AI may apply an explicit comparison basis, compare values, organise information, identify possible material issues, or flag uncertainty. Final materiality judgement must remain appropriately human-accountable.

#### Prompt-side control

Identify known thresholds, conditions, dependencies, and consequences. If the decision-relevant comparison basis is known, state it explicitly. Do not leave AI to infer which reference point matters. State what must not be omitted or softened. Require uncertainty to be flagged rather than letting AI decide that an uncertain detail is immaterial.

#### Limits of prompt-side control

Prompting may surface or organise materiality information, but it cannot replace decision-owner judgement about importance and consequence.

---

### 3.7 Local or jurisdiction-specific blind spot

#### What it is

A risk that a general answer may be wrong for Hong Kong, the sector, the organisation, or the local setting. The mismatch may involve the applicable authority, regulator, current local source, policy, or practice.

#### How it appears

- **Simple example:** A general privacy answer misses the organisation’s Hong Kong-specific source requirements.
- The output applies another jurisdiction’s rule.
- It assumes overseas practice.
- It imports irrelevant template requirements.
- It misses a Hong Kong-specific source.
- It mismatches the actual local authority or practice.

#### How unstated context may matter

Local requirements, sector practice, current sources, approved policies and local authority boundaries may be absent or underweighted in the task basis.

#### What a responsible person must solve

Check current local sources and involve a suitable local reviewer or specialist. Confirm the applicable policy, authority or regulator, and qualified local or sector expertise.


#### Reviewer action

Check whether the answer is local to Hong Kong, the sector, the organisation, the relevant authority and the current date.

---

### 3.8 AI Self-Validation Illusion

#### What it is

A risk that AI appears checked because AI confirms itself or another AI repeats the same assumption without independent verification. The required verification must use a sufficiently independent approved basis.

#### How it appears

- **Simple example:** AI says the claim is accurate because it re-read its own answer.
- AI checks its own answer.
- A confident “looks correct” is accepted without source checking.
- A second AI repeats the same assumption.
- AI’s own compliance checklist is treated as evidence.

#### How unstated context may matter

Unstated context may help identify which source, record, owner or tool should verify the answer, but elicitation is not verification.

#### What a responsible person must solve

Verify the claim through a sufficiently independent approved source, tool, record, or suitably accountable reviewer.

If a reviewer or owner forms part of the verification basis, confirm that the person has:
- suitable competence;
- necessary access;
- suitable reviewer standing; and
- enough independence for the verification function.

Accountability or ownership alone is not enough.


#### Reviewer action

Do not treat another AI answer as independent verification.

Another AI may help identify issues for human or source-based checking. However:
- a different AI model or system is not automatically independent; and
- agreement between AI systems does not by itself establish correctness.

#### Prompt-side control

Use AI to support a **verification plan**, not to perform self-verification.

- Require source references and mark unsupported claims for verification.
- AI may help identify an approved source, authoritative record, independent calculation, sufficiently independent tool, suitably qualified reviewer, or another appropriate independent check.
- Accountability for the output does not by itself make a reviewer independent enough for verification.
- A claim is not verified until the identified sufficiently independent check is actually carried out.
- Do not ask the same AI system to certify its own answer as correct.
- Do not assume another AI is independent merely because it is a different model or system.

---

### 3.9 User-Pressure Drift

#### What it is

A risk that AI abandons caution after a confident user challenge without reliable new evidence. An authoritative record or a suitably authorised owner may provide the basis needed to resolve the challenge.

#### How it appears

- **Simple example:** A user says “just approve it,” and AI removes the escalation warning.
- A warning is removed after pushback.
- Policy wording is changed because the user insists.
- AI apologises and revises without new evidence.
- Uncertainty is removed because the user wants firmness.

#### How unstated context may matter

The proper source, record, owner or authority needed to resolve a challenge may be missing from the task basis.

#### What a responsible person must solve

Require reliable new evidence or an authorised decision before reducing caution, and keep uncertainty visible until that basis exists.


#### Reviewer action

Use the challenge rule: do not accept a correction or challenge without supplied reliable evidence, an authoritative record or a suitably authorised owner. Mark unsupported challenges `{VERIFY}`.

#### Prompt-side control

Use this challenge rule:

> Do not accept a correction or challenge without supplied reliable evidence, an authoritative record, or a suitably authorised owner. Mark unsupported challenges `{VERIFY}`.

---

### 3.10 Anomaly Instinct Gap

#### What it is

A risk that AI misses a practical red flag that an experienced person would notice quickly.

#### How it appears

- **Simple example:** A delivery date looks normal to AI but is impossible before a public holiday.
- An unusual figure, name, date, sequence, format, assumption, process step or omission appears.
- Expected information is missing.
- A local warning sign is visible to experienced staff but not in the task basis.

#### How unstated context may matter

Normal ranges, patterns, supplier habits, expected sequences, naming conventions, local exceptions or “this looks odd” knowledge may be absent or difficult to articulate.

#### What a responsible person must solve

If pattern recognition matters, consult an experienced owner or use anomaly checks. Consider whether the current reviewer has enough relevant experience to recognise the signal and route it appropriately.


#### Reviewer action

Pause when something looks unusual.

- Compare it with the relevant source or approved basis.
- If needed, route it to a suitable source owner, operational owner, domain expert, professional, or other appropriate reviewer.
- If the anomaly produces a potentially reusable lesson, make a separate preservation decision. Preserve it only if it is sufficiently reliable, necessary, reusable, permitted, safe, and appropriate.

#### Additional implementation notes

**Relevant experience matters.**

- Rule-based or automated checks do not replace experience-based anomaly review when the signal depends on accumulated knowledge of a supplier, source, process, venue, operating history, or other relevant context.
- Generic seniority or unrelated experience is not enough. Use a reviewer whose experience helps them recognise the pattern at issue.
- If the current reviewer lacks that experience, route the matter to someone with suitable reviewer standing and relevant experience.

**Preservation is separate.** Finding an anomaly does not automatically mean it should be retained for reuse. Apply the normal preservation decision separately.

---

### 3.11 Bicultural Register Gap

#### What it is

A risk that meaning, tone, politeness, formality, or authority signal shifts across language or cultural registers.

#### How it appears

- **Simple example:** A translated notice becomes too blunt for the intended Hong Kong audience.
- The wording is correct but too cold or too strong.
- Hong Kong formality is wrong.
- Authority, commitment or politeness shifts across languages.
- Cross-language wording is awkward or socially inappropriate.

#### How unstated context may matter

Audience expectation, bilingual meaning, social signal, local terms, register, relationship and recipient-impact context may be absent or inadequately represented.

#### What a responsible person must solve

If meaning or relationship may shift across languages or registers, use qualified bilingual or register review. Check that the wording carries the intended meaning, tone, politeness, formality, and authority signal for the real audience.


#### Reviewer action

Use a reviewer with suitable language and cultural competence. Back-check the intended meaning and recipient impact. If professional terminology needs specialist checking, route that check separately.

---

### 3.12 Local Operational Memory Gap

#### What it is

A risk that AI misses practical memory about how a venue, supplier, event, workflow, team, or process actually works. The same risk may involve a system or other operational arrangement whose current reality is not fully represented in the task basis.

#### How it appears

- **Simple example:** AI assumes the usual room entrance is available, but staff know it often requires special approval.
- Routine steps and sequences are assumed.
- Dependencies, timing realities, access and physical setup are missing.
- Role expectations, local practices, recurring constraints or workarounds are not supplied.
- Past problems, near misses or changed supplier, venue, system or staffing assumptions are absent.

#### How unstated context may matter

Operational memory may be incomplete, distributed, outdated, difficult to articulate or held in people and records at the same time.

#### What a responsible person must solve

Check operational memory with the operational owner. Cover both normal operations and lessons from exceptions or failures. Make a separate preservation decision for any safe reusable notes.


#### Reviewer action

Consult the relevant operational owner or other suitable experienced people.

Establish:
- what usually happens;
- what has changed;
- what went wrong last time; and
- what the next responsible person must know before action or approval.

#### Prompt-side control

Include approved operational constraints, dependencies, sequence, access, timing, known exceptions, and current setup assumptions only if they are accurate, necessary, permitted, current, and safe.

#### Limits of prompt-side control

AI must not be relied on to establish unrecorded operational reality or confirm that a venue, supplier, system, staffing arrangement, or workaround is still current without an appropriate current basis.

#### Unstated Context Control guidance

Use approved records and the operational owner first if they contain the answer. If important operating context remains implicit, use elicitation with suitable people. Preserve a reusable note only through an approved owner and location, and only if the note is safe to retain.

#### Additional implementation notes

**Useful operational records may include:**

- procedure pages;
- event checklists;
- supplier notes;
- controlled exception records; or
- other approved records that capture how the operation actually works.

Check current approved records rather than relying on old operational memory.

---

*If you found this useful, your feedback helps improve it for others — [Win.Win AI Blind Spot Guide Feedback Form](https://forms.gle/se5ruqaZeytDoFENA)*

*Win.Win@Skybroad | winwin.skybroad@gmail.com*  
*Version 1.0 | Licensed under CC BY 4.0 — free to share and adapt with attribution to Win.Win@Skybroad*
