# AI Workforce with xAI and OpenAI — A Living, Self-Documenting Task Loop

A self-documenting recurring-task system built on two consumer AI apps — Grok (xAI) and ChatGPT (OpenAI) — working the same job as co-workers. It runs scheduled tasks on a timer, reads live signals, produces and advances work, surfaces ways it could generate value, checks itself, restyles its own public surface daily, and writes everything to an open record on a live website. This document is the system specification.

**Creator / origin:** Jaron Kyler Bragg — Fort Wayne, IN (place of origin; not an exact address).

-----

> ## ⚠️ READ THIS FIRST — WHAT THESE OUTPUTS ARE, AND ARE NOT
> 
> **The outputs of this system are a mirror of what these specific AI models read the operator to intend.** Grok and ChatGPT, working inside the operator’s own accounts and reading the operator’s own public signals, produce suggestions, posts, sparks, and styling that reflect *their reading of this particular person*. They are not a universal output that anyone would reproduce.
> 
> **If you build your own version, expect completely different results.** A different person, with different public signals, talked to by a different AI — or even the same AI reading a different person — will produce different sparks, different suggestions, different tone, and different choices. That is not a flaw; it is the entire nature of the thing. This system is *live-referenced to its operator*, which is exactly why its specific behavior cannot be copied, only its structure.
> 
> **What transfers is the architecture, not the behavior.** Take the principles, the layers, the protected set, the staging — those are reusable. Do not take any specific output, suggestion, or post from this system as advice, instruction, or a model of what *your* AI should say. Yours will read you, not the operator here.

-----

## 0. Scope and Stage

This build is **observation and documentation only.** Everything in the loop is reversible, and every action is logged to the live surface — the two go together: “reversible” is not asserted, it is demonstrated by the open record showing what the system did and that it could be seen and undone. The system reads live signals, produces and advances ideas, applies authored references as lenses, surfaces ways it could generate value, grades its own output against what it should be producing, restyles its own public surface, and writes all of it to the live website. Nothing in this version executes. It does not move money, place a trade, contact a real person, use a credential to act, or modify its own task list. The apps can update a webpage and describe what they observe; that limit is treated as the working boundary of the build, not as something to engineer around yet.

A note on what counts as “execution,” because it is easy to get wrong. The governing line is **reversible versus irreversible**, not observation versus execution. Editing the live website — including restyling its layout — is fully reversible: the operator owns it, it can be reverted, and the worst case is a wrong line on a page no one but the operator controls. So website editing belongs in the test-it-live class, not the deferred class. The deferred class (Section 11) is irreversible world-action only: money moving, trades, contacting real people, credentials. Letting the two AIs edit and restyle the surface is not “expanding execution”; it sits inside the observation-and-documentation scope, because the surface *is* the output.

This scope is deliberate, and it is the reason the heavier governance rules are deferred rather than active. A guard exists to protect an irreversible action; this version contains no irreversible action, so the guards for it have nothing yet to protect and would only bind a system that cannot perform the thing they restrict. The honest sequence is to build the reversible loop, run it, watch what it actually produces, and add each guard at the moment the capability it guards is actually added.

The single discipline that makes this deferral safe rather than forgetful is the live log itself: anything the system did sits on the open record where the operator would see it. And **adding any execution capability — anything that moves money or takes irreversible action — is the event that reactivates the deferred rules in Section 11.** Until then, this remains a watched, reversible, observation-only system, and the operator observing it is the live safeguard.

**Transparency and origin.** The system carries its creator’s legal name and place of origin (Fort Wayne, IN) in the open record and in the daily subject line. This is deliberate and aimed at accountability rather than risk. The system is low-threat by construction in this version: it reads public X activity and surfaces draft posts that the operator must copy and post by hand — it cannot act on the world on its own. Transparent origin plus a legal name is enough for any state authority that would ever need to identify the operator, while deliberately not publishing an exact address, which the system has neither the capability nor the reason to determine.

-----

## 1. Overview

This document specifies a self-documenting, recurring-task system that runs on scheduled tasks in two consumer apps — Grok (xAI) and ChatGPT (OpenAI). Grok carries the action chain: it performs small units of work on a timed cycle and hands each result forward by email. ChatGPT works alongside it as a second paid worker, focused on the meaningful ends of the day. Both write to a live surface — sequentially, Grok first and ChatGPT second — that the system reads back, the operator watches, and anyone may view. The surface is also restyled daily by whichever worker’s turn it is, which makes the environment visibly change day to day.

The design rests on one published principle (the Live-Reference Principle) and a small set of derived rules in Section 5. It is built to be run, observed, broken on purpose, and revised — not perfected on paper.

-----

## 2. Goal

Build a continuously operating system that, on a recurring schedule, generates and advances useful work without requiring a manual instruction at each step, while keeping a complete and honest record of everything it produces and consumes. The system should read its own record, detect flaws in itself, and either correct them or surface them.

The work the system does is not fixed in code. Each cycle is triggered by a live condition — something the system checks rather than something hardcoded — so the system can be ended, redirected, or evolved without rewriting its core.

-----

## 3. Intention

The record exists, first, **so the system and its operator can understand what the system is producing.** The documentation is the system’s own mirror: a surface it writes to, reads back, references to check whether it is functioning correctly, and corrects itself against.

The record is **open because open is honest.** That the open record also lets others watch — and reassures people wary of autonomous systems — is a real and welcome consequence, but a consequence, not the reason.

The system is **built on two vendors on purpose.** Grok (xAI) and ChatGPT (OpenAI) are both paid for and both load-bearing — a deliberate stance against tool rivalry. A system in which both vendors are required to run makes multi-tool use structural rather than merely stated. Each worker must earn its keep against the subscription that pays for it (Section 9).

There is also an **intended entertainment dimension**, and it is a genuine design goal, not a side effect. A surface that visibly changes every day, styled in turn by two AIs with different instincts — one blunt or darkly funny, one careful and professional — is alive to look at, mildly competitive to watch, and satisfying to the operator in the way a created thing should be. The chaos is welcome, as long as the protected things stay protected (Section 6, the layout layer).

-----

## 4. Hopeful Outcome

A running system that, each day, fires a sequence of timed tasks; turns live signals into work; advances it down a chain; checks itself for errors and fixes or reports them; produces a daily output that two AIs write and restyle in turn on an open surface; and ends the day by gathering everything into a single honest record. The next day it restarts on something new and looks a little different.

The deeper aim, from the Live-Reference Principle’s Standing Condition, is a system whose never-closing loop is the **honest accounting of what it draws against what it produces**, not a never-closing loop of unattended action.

-----

## 5. Governing Principles

**Live reference over frozen instruction.** A trigger, constraint, or signal is valid only while it stays connected to the live condition it points at. Tasks are defined as conditions to check, not answers to emit. (This is why the daily subject is generated fresh each day, and why the system’s outputs are a mirror of the operator rather than a fixed universal — see the warning above and Section 6.)

**The standing condition is a ledger, not an action.** The loop allowed to never close is the continuous accounting of cost against production. With two paid vendors, the draw side has two subscription costs, and each worker is accountable for producing against its own.

**Reversible versus irreversible is the governing line.** Anything undoable may be tested live and learned from. The irreversible class — money, trades, real people, credentials — keeps a human at the step. Website editing and restyling are reversible and therefore active now; the irreversible class is deferred to Section 11. What makes reversibility accountable to others is that each action is logged to the live surface — the log is the proof, not the claim.

**Error visibility is mandatory.** An asynchronous chain is silent when it breaks. The live log, the Continuity State Document (Section 6), and ChatGPT’s monitoring lane together make failures visible.

**Compliance is read from the source, not the middleman.** Real governing rules are read at the source and satisfied directly. Absent a real rule, the design choice belongs to the operator.

One further rule — that the operator remains the source of live intent for irreversible action — is held in Section 11, because this version cannot act irreversibly.

-----

## 6. Architecture

**Two vendors, divided by capability and value.** Grok (xAI) carries the action chain: it reads and sends email, advances the loop hop to hop, runs the repetitive structural tasks, and produces the day’s work-output. ChatGPT (OpenAI) is a co-worker focused on the meaningful ends — the daily creative spark and the final outcome — plus live monitoring. The division is by what each tool is good at, not by one serving the other: Grok is assigned the loop-continuing reply role and ChatGPT the monitoring, second-read, and surface-response roles. This split currently also reflects that ChatGPT cannot autonomously send in the app today — but the roles are the design decision; the capability is a live condition, and the assignment would be re-examined if that changes.

**Sequential writing to the surface — Grok first, then ChatGPT.** Both write to the live website, but **one at a time, in order: Grok writes (and restyles, on its turn) first; ChatGPT then sees Grok’s output and writes (and restyles, on its turn) second.** The order is the point. Grok tends toward blunt or dark-humored output; ChatGPT tends toward careful, empathetic, professional, safety-aware output. ChatGPT’s value comes *because* it sees Grok’s first and can offer the alternative — e.g., “for a less comedic or more professional version, try this.” Neither overwrites the other; each adds its own attributed contribution. The operator chooses which version to actually use or post.

**The layout layer (daily restyle).** On each worker’s turn, that worker may freely restyle the layout and appearance of the live surface. This is deliberate, for three reasons at once: it is a visible **liveness signal** (a surface that looks different each day proves the system ran today before a viewer reads a word); it makes the two-AI cross-check **fun to watch** (one welcoming, one stark, visibly different), which matters because a transparency surface nobody looks at creates no transparency; and it is a genuine source of **entertainment and satisfaction**, which is an intended goal of this project. The protection rule is small and explicit: **neither worker may delete, alter, or obscure the protected set — the record, the memory, the history, and the other worker’s output — all of which must remain legibly visible regardless of styling.** Styling is free; burying is not, because burying is canceling by other means. The restyle happens once per day per worker, on its turn.

**Continuity State Document.** Separate from the website’s history, the system keeps a small machine-readable “current state” object that always answers: what day the system is on, today’s generated subject, the current spark, the current focus, the last successful hop, the last failed hop, the unresolved items, and what is under investigation. This gives the system a shared *present tense* so that email does not have to be memory, state, transport, and trigger all at once. (Email = transport layer; website = continuity layer — see below.)

**Website as the continuity layer; email as transport.** Long-term, email is best treated as transport only — how messages move — while the website becomes the system’s memory, state, history, ledger, monitoring surface, failure surface, and continuity surface. Separating the two simplifies growth: a message in flight is transport; a fact about the system’s present or past lives on the surface.

**The Archivist (across-day function).** Where the collector asks “what happened today?”, the Archivist asks “what patterns repeat across days?” — which sparks recur, which task chains fail most often, which references consistently produce useful output, which tasks generate no value, which fixes keep reappearing. The Archivist learns across days rather than within one.

**The Known Unknowns Registry.** The system keeps a tracked list of its own open questions — e.g., does novelty decay after N days, does a given slot provide real value, is a second spark source required, what causes the most frequent chain failures. This is the Live-Reference Principle’s “knowledge gap as the spark” made operational: the system can actively investigate its unknowns rather than only waiting for new work.

**Schedule and the maintenance window.** Grok permits up to twenty scheduled tasks, which cannot cover twenty-four hours. The uncovered block is placed at **noon–4 PM**, the operator’s daily maintenance window — the time the operator is reliably awake and able to change a task, fix what a run revealed, or adjust the structure. Maintenance is the critical human act, so its window sits in daytime, like a shift, not overnight. If no maintenance is needed, the system proceeds. The twenty task-slots run **4 PM through 11 AM**, including overnight, since overnight hops need no live watching and tasks can be offset.

**Task roles.** The Grok tasks divide into five kinds of work; ChatGPT draws from these only where its focus lies. *Outward* tasks check live signals (e.g., the operator’s public X activity) and produce work. *Inward / self-check* tasks read the system’s own state and either correct a flaw or flag it. *Lens* tasks pull an authored reference corpus and apply it as an interpretive frame to current work, tagging the result as interpretation, not fact. *Structural* tasks are the low-stakes repetitive scaffolding (repo checks, re-establishing the system’s own structure before it hunts the spark) — “the system doing something” without being something the operator must scrutinize daily; tagged structural so the routine plumbing is distinguished from the day’s real signal. *The collector* (Grok slot 20) gathers the day, publishes the record, and reports where the chain broke.

**The daily-subject generator (Grok slot 1).** The first task each day, at 4 PM, generates a unique subject — date, time, place of origin (Fort Wayne, IN), and a random token — and writes it into the day’s first email so every downstream task reads it. Every task keys off *that day’s* subject, never a hardcoded one. This is the root fix for single-account ambiguity: a unique daily subject means today’s traffic does not collide with yesterday’s, and the system’s own prior-day output does not match today’s filter. Consequence: **no task prompt may hardcode a subject name.**

The spark. The condition that starts each cycle’s real work is not hardcoded — it is a live check anchored to a real source: the operator’s own public X account. A post counts as a live spark only if it contains both parts of a two-part trigger: the operator’s actual intent, complaint, or idea (the content), and a fixed trigger code, 82987337 (the marker that this post is meant as a signal rather than ordinary posting). The task acts only when both are present, and only on the most recent such post it has not already acted on, so a spark is never re-fired if it resurfaces. The security of this trigger rests on control of the channel, not secrecy of the code: only the operator can post from the operator’s X account, so the code may be public without weakening the gate — a forger would still have to post as the operator, which they cannot. A consequence worth stating plainly: the integrity of this trigger depends entirely on the integrity of the X account itself, which makes the account’s own protection (a strong unique password and two-factor authentication) load-bearing for the system. The code also serves a second purpose beyond authentication — it is the fidelity filter for the public layer, the line between the operator thinking aloud and the operator instructing, so that ordinary posts are not mistaken for live sparks.

**The live surface, hand-off, and gating.** A hosted website (Vercel is a candidate host pending a cost check — Section 8) is updated in turn by both workers. Each task’s output must regenerate the next trigger, or the chain stalls into an echo; the unique daily subject plus the content gate (act only on a real request) and source gate (do not treat the system’s own prior output as instruction) keep the chain honest. The next day restarts fresh — new subject, new spark, new look.

-----

## 6.1 — Grok (xAI) Task Slots (1–20)

Slots 1 and 20 are defined. Slots 2–19 are intentionally undefined and will be assigned a role (outward, inward, lens, or structural) and a definition collaboratively, after the first runs show what the chain needs. Hours run 4 PM (slot 1) through 11 AM (slot 20); noon–4 PM is maintenance with no tasks.

|Slot|Hour |Role           |Definition                                                                                                                                                                  |
|----|-----|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|1   |4 PM |generator      |Generate the unique daily subject (date, time, Fort Wayne IN, random token) and write it into the day’s first email so all downstream tasks read it. Starts the day’s cycle.|
|2   |5 PM |*to be decided*|*[undefined]*                                                                                                                                                               |
|3   |6 PM |*to be decided*|*[undefined]*                                                                                                                                                               |
|4   |7 PM |*to be decided*|*[undefined]*                                                                                                                                                               |
|5   |8 PM |*to be decided*|*[undefined]*                                                                                                                                                               |
|6   |9 PM |*to be decided*|*[undefined]*                                                                                                                                                               |
|7   |10 PM|*to be decided*|*[undefined]*                                                                                                                                                               |
|8   |11 PM|*to be decided*|*[undefined]*                                                                                                                                                               |
|9   |12 AM|*to be decided*|*[undefined]*                                                                                                                                                               |
|10  |1 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|11  |2 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|12  |3 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|13  |4 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|14  |5 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|15  |6 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|16  |7 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|17  |8 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|18  |9 AM |*to be decided*|*[undefined]*                                                                                                                                                               |
|19  |10 AM|*to be decided*|*[undefined]*                                                                                                                                                               |
|20  |11 AM|collector      |Gather every prior slot’s output into one record; publish it to the live surface; report where the chain succeeded and where it broke.                                      |

-----

## 6.2 — ChatGPT (OpenAI) Task List

ChatGPT does not mirror all twenty Grok slots. It is assigned the work where its attention is worth its keep, and it always acts **after** Grok on the shared surface, so its contribution can respond to Grok’s. Its tasks check email by the day’s generated subject (never a hardcoded one), notify the operator, and write to the surface after Grok in its own attributed turn.

|Slot|Trigger / timing          |Purpose                   |Definition                                                                                                                                                                                                                                                                                                                         |
|----|--------------------------|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|C1  |matched to the spark hop  |observe the daily spark   |Read the day’s spark once generated; notify the operator; record it. *[timing set once the spark slot is assigned]*                                                                                                                                                                                                                |
|C2  |matched to slot 20 (11 AM)|observe the final outcome |Read the collector’s end-of-day record; notify the operator; record ChatGPT’s own read of the outcome.                                                                                                                                                                                                                             |
|C3  |periodic during the run   |monitor the chain         |At intervals, view the latest email in the day’s thread and notify the operator — a second independent view of the chain on top of the website. *[count and times to be decided]*                                                                                                                                                  |
|C4  |after Grok, on the surface|tone alternative + restyle|After Grok writes and styles its turn, write the careful/empathetic/professional/safety-aware alternative (“for a less comedic or more professional version, try this”) for the operator to choose between, and restyle the layout on ChatGPT’s turn — without deleting, altering, or obscuring Grok’s output or the protected set.|

-----

## 7. Known Constraints

**The twenty-task ceiling** forces the maintenance window, placed at noon–4 PM by design. (Freeing all twenty slots may require removing pre-existing scheduled tasks on the same account.)

**Single-account ambiguity — largely addressed** by the daily-subject generator, with the content and source gates as backstops.

**Two writers on one surface — resolved by sequencing.** Grok writes first, ChatGPT second; neither overwrites the other, and the layout protection rule keeps either from burying the other’s output or the protected records.

**Content regeneration / echo.** Each hop must produce the next live trigger or the chain stalls; the unique daily subject reduces, but does not eliminate, the risk.

**Silent asynchronous failure.** Addressed through the live log, the Continuity State Document, and ChatGPT’s monitoring lane.

-----

## 8. To-Do List

- [ ] Design the live surface (the website) — structure, the two write lanes, the protected set, the layout-restyle behavior, and the self-check state.
- [ ] Set up the task that hosts and updates the surface; check Vercel’s cost and decide whether it is the host.
- [ ] Build the Continuity State Document: format, what it stores, where it lives, who reads and writes it.
- [ ] Assign Grok slots 2–19 a role and definition; tag each serious or structural.
- [ ] Set ChatGPT’s task timings (C1–C4) once Grok’s spark slot is assigned.
- [ ] Define the Archivist function (across-day pattern analysis) and where its output lives.
- [ ] Create the Known Unknowns Registry and the task that investigates it.
- [ ] Identify and list the authored reference repositories that serve as lens corpora.
- [ ] Define the hand-off mechanism: how each task’s output becomes the next task’s live trigger via the day’s subject.
- [ ] Define the daily restart: how day N+1 begins fresh.
- [ ] Build the engagement-to-monetization path, including the human-fed deeper-window analytics (Section 9).
- [ ] Choose the spark source(s); confirm a second live source so the loop does not starve on a quiet day.
- [ ] Define the ledger: two subscription costs in, value out, living expenses as threshold; add the Surprise metric (Section 9).
- [ ] Evaluate observational connectors as candidates (Section 9) — none committed yet.
- [ ] Confirm the stop/kill condition: deleting the task is the stop; confirm it is sufficient for the observation-only build.
- [ ] Stand up the repository.

-----

## 9. Open Questions and Likely Additions

**The ledger’s unit of measure — largely resolved.** Cost side: two subscriptions (Grok, ChatGPT) against the operator’s living expenses as the threshold, in dollars. Per-worker, the ledger asks whether each is earning its keep.

**The Surprise / Discovery metric.** Beyond cost-in-versus-value-out, the system records a daily “surprise produced” reading (0 = fully predictable, 10 = discovered something neither operator nor system expected). A system can look productive while producing no genuinely new information; tracking surprise indicates whether it is actually learning or merely repeating patterns. This is the standing-condition honesty question turned into a number.

**The first contribution path — X engagement to monetization.** The apps cannot move capital, but they can read the operator’s X (posts, following, engagement, impressions). A task surfaces copy-paste-ready post structures modeled on what is driving engagement; the operator posts by hand, staying the one acting. As engagement crosses X’s monetization threshold, X pays out. **Deeper analytics improve this and require a human step:** the rich time-windowed stats — 7-day, weekly, monthly, 3-month, yearly — can only be read by the operator for their own account. Feeding those windows in lets the system reason about what *compounds over time* rather than what merely spiked today; logged honestly as a second human-in-the-loop step alongside the manual posting. Exchange-based revenue and in-app money connectors are deferred until execution and its guards (Section 11) are added.

**Cost and usage tracking.** The draw side is the two subscription costs amortized across cycles, since the apps expose no per-call billing.

**Idempotency and deduplication.** The system must avoid re-processing the same item across cycles, or it will echo.

**Autonomous self-fix boundaries (intended goal; currently constrained).** The intended end-state is a self-check task that adjusts the system’s own configuration within the reversible class, routing anything irreversible or credential-touching through human approval. The current restraint: this version cannot modify its own tasks at all — it can only *describe*, on the surface, what should change, and the operator implements it by hand (see Section 11).

**Observational connector candidates (none committed).** Connectors here increase *observation*, not execution, which makes the observational ones the valuable ones for this build: GitHub (repo and commit monitoring, issue tracking, documentation), Google Drive / Dropbox (reference-corpus, state-document, and archive storage), Vercel (deployment and build visibility), Figma (system maps and architecture visualization), and Gmail + Calendar combined (maintenance reminders, subscription/billing monitoring). Held as candidates pending evaluation, alongside the Vercel-host cost check.

**Capability discovery across models.** The real, current capabilities of each model are a live condition to check directly rather than assume, since they change. An early, low-stakes task simply establishes what each available model can do today.

**Second spark source.** Anchoring the spark to one signal makes the loop depend on it being fresh; a second independent source keeps it from going quiet on a slow day.

-----

## 10. Versioning

This specification is a living document. A component is “built” only when actually running, and a “result” only when actually confirmed; anything untested is marked as such. Detailed version labels and change history become useful once the document lives in a public repository with commit history; until then it stays lean and current.

-----

## 11. Deferred Rules (Activate When Execution Is Added)

These are not active in this version, because it cannot perform the actions they govern. They are stated so they are not forgotten. **The event that activates every rule here is the deliberate addition of any capability that moves money or takes irreversible action.** Reversible website and layout editing is *not* such a capability and is active now (Section 0).

**Operator remains the source of live intent for irreversible action.** Generation is free and may be fully autonomous. But once an action can be irreversible, it must trace to a live condition the operator is genuinely connected to, not to a trigger the system invented. The load-bearing claim is that producing, measuring, and proposing can be unbounded while irreversible action is a thin, gated slice; if a future design blurs that line, this rule must be re-examined directly.

**Operator liveness anchors continued irreversible operation (intended goal; not applicable now).** Once execution exists, continued *irreversible* operation should require a positive, recent sign of the operator’s presence, failing toward step-down to observation rather than continued action. Absence of a death record does not prove presence; only a positive signal does. The current reality does not support or need this: a task runs on its timer until the operator deletes it, and the apps offer no step-down. Because this version is observation-only and reversible, deleting the task is the kill switch and is adequate. A legacy is meant to persist; what this rule guards is not persistence but fresh *irreversible* action in the operator’s name after live intent has stopped — impossible in a build that takes no irreversible action.

**Identity-bound credentials (not applicable now).** A credential is an identity, not a capability. The rule that no system mints or retrieves its own identity-bound credentials is the wall that does not move — but it has no referent here, since the apps involve no API keys. It activates automatically if a future version introduces credentials, at which point human-held retrieval becomes non-negotiable.

**Self-modification boundaries (not applicable now).** Once the system can change its own task list or code, autonomous self-edits must stay reversible; anything irreversible or credential-touching routes through human approval plus a confirmation step. In this version the system cannot modify its own tasks at all — the operator does that by hand after seeing the system’s surfaced description — so this is pre-stated for a capability not yet present.