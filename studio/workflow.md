# The Public Data Lab — Operating Workflow

*How the studio builds. The constitution (`philosophy.md`) says what we believe and why; this handbook says how a belief becomes a shipped, stewarded observatory. When the two disagree, the constitution wins and this document is wrong. Read that first; this second.*

---

## How to read this

This is the operating model for every observatory the studio will ever build — the Water Observatory, the Health Observatory, the Cities Observatory, and the dozens that follow. It is deliberately not a software process. It is the full lifecycle of turning public data into public understanding, from the decision to build at all through the years of keeping it true.

One rule governs the whole document: **the same workflow runs whether a project lasts two weeks or two years.** The phases do not change with the size of the job; only the depth we spend inside each one does. A two-week explainer and a two-year flagship pass through the identical gates. Skipping a phase is never a schedule decision — it is a decision to lower the standard, and we do not make that decision.

A newcomer should be able to read this once and know: what the phases are, what they must produce, who signs off, when to loop back, and where every important thing is written down. If any of that is unclear, this handbook has failed and should be revised, not worked around.

---

## The operating principles

The constitution has eleven principles about the *work*. These six are about the *way we work*. They are numbered so they can be cited — "this violates Operating Principle 3" should mean something to everyone.

### O1. Documents are the memory; conversation is scratch.
The durable record of a project is its written artifacts, never its chat history. Any decision, finding, or rationale that lives only in a conversation — with a person or with an AI — does not exist. It will be lost, contradicted, or silently reversed. Every phase ends by writing what it learned into a named, versioned artifact. If it wasn't written down, it didn't happen.

### O2. Freeze the foundation early; keep the surface fluid.
A project has a small number of decisions that are expensive to reverse and that everything downstream depends on — the question, the audience, the units, the uncertainty taxonomy. These we freeze deliberately and early, and changing them costs a formal re-opening. Everything cheap to reverse — wording, styling, chart choices, layout — we keep loose and let feedback shape. Chaos comes from getting this backwards: leaving the foundation negotiable and bikeshedding the surface.

### O3. Every phase leaves the studio smarter.
No project is only for itself. Each phase produces knowledge — a method, a component, a vocabulary, a lesson — that outlives the project and raises the floor for the next one (Principle 11). A phase that produces only a private result and no reusable knowledge has done half its job.

### O4. Gates before advancement. Never proceed on hope.
Between every phase is a gate with explicit pass/fail criteria and a named human owner. "We'll fix it later" is not a passing grade. Advancing a broken foundation does not save time; it moves the cost downstream and multiplies it. The gate exists to make skipping the thinking harder than doing it.

### O5. Decide once, record forever.
Irreversible and contested decisions become Decision Records — written, dated, append-only, and never quietly changed. We do not re-litigate settled questions from memory, and we do not discover six months later that nobody knows why a thing is the way it is. The reasoning is captured while it is fresh, or it is lost.

### O6. The process scales down as cleanly as it scales up.
Every mechanism here has a lightweight form. A two-week project still writes a Charter — it may be half a page. It still records decisions — there may be three. The workflow must never be so heavy that a small honest project routes around it, because a process that gets skipped protects nothing.

---

## The lifecycle at a glance

Nine phases. Phase 0 is a gate before the project truly begins; Phase 8 never ends. The shape is a spiral, not a line — later phases routinely send work back to earlier ones, and that is the design working, not failing.

| # | Phase | The question it answers | Accountable owner | Primary artifact |
|---|-------|------------------------|-------------------|------------------|
| 0 | **Commission** | Should this observatory exist at all? | Lead | Mandate |
| 1 | **Frame** | What question, for whom? | Lead | Charter *(frozen)* |
| 2 | **Ground** | What data, from where, how trustworthy? | Data | Source Register |
| 3 | **Reconcile** | How does raw data become an honest dataset? | Data | Methodology |
| 4 | **Design** | What is the argument, and how is it read? | Design | Design Brief |
| 5 | **Build** | How do we make it real? | Build | The product |
| 6 | **Prove** | Does it meet the standard? | Lead | Gate Record |
| 7 | **Publish** | Release it — and record why it is the way it is. | Build | Release Note |
| 8 | **Steward** | Keep it true for years, then end it with dignity. | Lead | Steward Log |

Each phase below follows the same shape: **why it exists** (the failure it prevents), **owner**, **inputs**, **outputs**, **the gate to advance**, and **expected iteration**. The consistency is deliberate — it is what makes the workflow teachable and hard to skip.

---

## The roles

Four human roles and one instrument. These are **responsibilities, not headcount.** On a two-year flagship, each may be a team; on a two-week explainer, one person wears all four hats in a day. The roles never merge or disappear — the accountability does not — but the people can.

- **Lead** — owns the question, the standard, and the final call. Guards scope against creep, breaks ties, and is accountable for whether the product meets "what done means." The Lead owns every gate.
- **Data** — owns everything from source to trustworthy dataset: sourcing, verification, provenance, transformation, and the honest quantification of uncertainty (Principle 4).
- **Design** — owns the editorial argument (Principle 6) and its expression: what the product foregrounds, how it reads, the visual and interaction system.
- **Build** — owns making it real and keeping it real: implementation, release, and the mechanics of the update (Principle 9).
- **AI** — not a role but an **instrument every role uses.** AI drafts, finds, reconciles, translates, and scales; it never decides and never authors an unaccountable claim (see *Working with AI*, below). Every AI contribution is owned, checked, and signed off by the human whose phase it lives in. The reader must never have to trust our model — only our source.

**Accountability vs. drafting.** Each phase names one accountable human owner. That owner may hand the *drafting* to AI or to another person, but they cannot hand off the *accountability*. Gates are always owned by a human, always the Lead, and never delegated to a model.

---

## The phases

### Phase 0 — Commission

**Why it exists.** To refuse the wrong projects before they consume a year. The studio's scarcest resource is not effort but standard; every observatory we build we must be prepared to keep correct for a decade (Principle 9). Commission is where we decline the orphan product, the off-mission project, and the dataset in search of a purpose — while declining is still free.

**Owner.** Lead.

**Inputs.** A proposal; the constitution; the current studio canon; an honest read of what the studio can commit to maintaining.

**Outputs.** A **Mandate** — a short written statement of what this observatory is for, why it belongs in the studio, who it is prepared to serve, and what the studio commits to sustain. Or a written decision *not* to build, with the reason. A "no" is a valid, valuable output and is recorded like any other decision.

**The gate to advance.** All must be true: the project serves the mission and a real audience; a plausible one-sentence question exists (it will be sharpened in Frame); the data plausibly exists and can plausibly be kept current; and the studio can commit to stewarding it. If any is false, the answer is no, or not yet.

**Iteration.** Rare but real: a "not yet" returns here when its blocking condition changes.

---

### Phase 1 — Frame

**Why it exists.** Because every failure mode we study begins with a project that never fixed its question (Principle 1). A dataset with no question becomes a dashboard that answers none. Frame is where the foundation is set and frozen, so that everything downstream has something solid to stand on.

**Owner.** Lead.

**Inputs.** The Mandate.

**Outputs.** The **Charter** — the frozen foundation of the project. It states, in language its reader would recognize as their own:

- **The one-sentence question.** The single real question a real person has, that this observatory answers. If we cannot write it, we do not have a product yet.
- **The audience and its order.** Who we serve, and — per the constitution — who we serve *first* when needs conflict.
- **The scope boundary.** What is in, and explicitly what is out. Out-of-scope is written down so that "wouldn't it be cool if…" has somewhere to be refused.
- **The definition of success.** What "this worked" means for *this* observatory, derived from "what done means."

The Charter is **frozen** at the end of this phase. Frozen does not mean forbidden — it means changing it requires re-opening Frame formally and recording why (Operating Principle 2), because everything built on it must be told the ground moved.

**The gate to advance.** The one-sentence question exists and survives being read aloud to someone outside the project. The audience order is stated. Scope has an explicit edge. If the question is still vague, we do not proceed to buy data for a question we cannot state.

**Iteration.** The Charter is revisited only through a formal re-open — typically triggered by the Stop-and-Rethink circuit breaker (below), never by drift.

---

### Phase 2 — Ground

**Why it exists.** Trust is earned at the source or not at all (Principle 3). Ground is where we find the data, prove it means what we think, and write down its provenance so that every number we later publish can trace home in one action. Skipping the discipline here is how a project ends up unable to answer "how do we know this?" — the one question that, unanswered, ends us.

**Owner.** Data.

**Inputs.** The Charter (the question tells us what data would answer it).

**Outputs.** The **Source Register** — a living record of every source: what it is, who publishes it, its license and terms of use, its vintage and update cadence, its known limitations, and an honest reliability assessment. Data we cannot cite is data we do not use.

**The gate to advance.** Sources sufficient to answer the Charter's question are identified, licensed for our use, and documented. Their limitations are known and written, not discovered later. Their vintage and update cadence are recorded, because Phase 8 depends on it. If the data to honestly answer the question does not exist, we do not proceed — we trip the circuit breaker.

**Iteration.** Ground and Reconcile interleave constantly; reconciliation routinely reveals that a source cannot bear the weight we hoped and sends us back here for another.

---

### Phase 3 — Reconcile

**Why it exists.** This is where the studio does the hard work so the reader does not have to (Principle 5). Cleaning, joining, standardizing, and — above all — separating what is **measured** from what is **estimated**, **modeled**, and **projected** (Principle 4). The reader's simplicity is bought with our complexity here; a project that shortcuts this phase launders estimates into facts and betrays the trust the whole studio depends on.

**Owner.** Data.

**Inputs.** The Source Register and the raw data it points to.

**Outputs.** The **Methodology** — a living, versioned account of exactly how raw data becomes the published dataset: every transformation, every assumption, every reconciliation of conflicting sources, and the explicit uncertainty class of every derived figure. Written so a domain expert who reads it finds rigor, not embarrassment. Alongside it, the processed dataset itself, reproducible from raw.

**The gate to advance.** The pipeline runs from raw to output and can be re-run. Every published figure has a documented lineage and a declared uncertainty class. Conflicting sources are reconciled with stated reasoning, not silently averaged. Nothing measured, estimated, modeled, or projected is presented as anything other than what it is.

**Iteration.** Reconcile ⇄ Ground (as above). Reconcile also anticipates Design: how a figure will be shown shapes how it must be prepared, so these two phases talk early and often.

---

### Phase 4 — Design

**Why it exists.** There is no neutral chart (Principle 6). Design is where we decide what the product argues, what it foregrounds, and how a first-time reader comes to understand it in their first minute while an expert finds depth in their tenth hour. This is where the default view is made to already answer something (Principle 2), and where beauty is made to carry meaning rather than compete with it (Principle 7).

**Owner.** Design.

**Inputs.** The Charter (the question and audience) and the Methodology (what is true and how certain).

**Outputs.** The **Design Brief** — the editorial argument stated plainly (what this product wants the reader to understand, and what evidence, including disconfirming evidence, it shows), plus the interaction and visual specification for how the argument is read. It commits to the studio's shared visual system and shared chart grammar (Principle 8, `design-principles.md`) and notes any deliberate departure with its reason.

**The gate to advance.** The default view answers the Charter's question with no configuration required. Progressive disclosure carries the reader from headline to depth without a cliff. Uncertainty is visible, not hidden. The design uses the shared system, so a reader arriving from another observatory does not have to relearn how to read. Nothing in the design distorts the data to strengthen the argument.

**Iteration.** Design ⇄ Reconcile (a design need reveals a data gap; a data limit reshapes the design) and Design ⇄ Build (see below). Design is expected to loop; that is cheap here and expensive later, which is exactly why we loop here.

---

### Phase 5 — Build

**Why it exists.** To make the argument real, correct, and durable — built not for launch day but for the decade (Principle 9). The failure this phase prevents is the beautiful prototype that cannot survive its first data update: correct today, quietly wrong next year, an orphan by year two.

**Owner.** Build.

**Inputs.** The Design Brief and the processed dataset.

**Outputs.** The working product, and — as a first-class deliverable, not an afterthought — the mechanics of its update: how new data enters, what recomputes, and what a maintainer must check. The update is designed here, not improvised in Phase 8.

**The gate to advance.** The product faithfully implements the Design Brief. Every figure on screen traces to its source in one action and shows its vintage. It works in light and dark and on a small screen, and meets the studio's accessibility bar (`quality-standards.md`). The update path exists and has been exercised at least once, not merely imagined.

**Iteration.** Build ⇄ Design, tightly — implementation reveals what the design got wrong, and the two converge. Loops here are normal; a Build that needs no design change is the exception, not the rule.

---

### Phase 6 — Prove

**Why it exists.** Because "good enough to ship" and "meets the standard" are different sentences, and the studio only permits itself the second (constitution, *What "done" means*). Prove is the hard gate: an adversarial review against the standard, owned by the Lead, that a product must pass before it reaches a reader. It exists to be the moment where wishful thinking meets the checklist and loses.

**Owner.** Lead.

**Inputs.** The product and every artifact behind it.

**Outputs.** A **Gate Record** — the completed pre-publish review (from the project's `checklists/`), each criterion marked pass or fail, signed and dated. A fail is not a defect in the process; it is the process working.

**The gate to advance — the seven conditions of "done."** Every one must be true, verified, not asserted:

1. A first-time reader understands the central point within the first minute, without instruction.
2. Every figure traces to a documented source in one action, and its vintage is visible.
3. Measured, estimated, modeled, and projected values are unmistakably distinguished.
4. A domain expert who digs to the bottom finds rigor, not embarrassment.
5. Nothing on screen misleads — even at a glance, even to someone who reads only the headline and the chart shape.
6. It is beautiful, and its beauty carries meaning rather than competing with it.
7. It will survive its next data update, and we know exactly how that update will happen.

**Iteration.** A failed condition returns the project to whichever phase owns it — a provenance failure to Ground or Reconcile, a comprehension failure to Design, an update-survival failure to Build. Prove does not fix; it routes. We do not negotiate a condition down to pass; we fix the product until it passes honestly.

---

### Phase 7 — Publish

**Why it exists.** Release is an editorial and ethical act, not a button (Principle 10). Before a number reaches the public we ask who it helps and who it could harm, and we make the choice to publish deliberately and own it. Publish is also where the project's reasoning is sealed into the record so the studio remembers *why*, not just *what*.

**Owner.** Build (release), Lead (the call).

**Inputs.** A passed Gate Record.

**Outputs.** The live observatory, and a **Release Note** — what shipped, as of what date, at what method version, with which sources at which vintage, and the known limitations stated plainly. Any decision that was contested, irreversible, or ethically weighed becomes a **Decision Record** if it is not one already. The harm review is written down, not merely held in someone's head.

**The gate to advance.** The Gate Record is fully passed. The harm question has been asked and answered in writing. The Release Note is complete and truthful about limitations. Nothing ships that we are not prepared to steward.

**Iteration.** Publish is a threshold, not a loop — but crossing it opens Phase 8, which never closes.

---

### Phase 8 — Steward

**Why it exists.** Because a product correct on launch day and quietly wrong a year later has betrayed everyone who trusted it in between (Principle 9). Most public data products die not at launch but afterward — abandoned, un-updated, link-rotted into a museum of a moment. Steward is our refusal to ship orphans. It is a phase without an end, and it is where the constitution's hardest promise is kept or broken.

**Owner.** Lead (with Data and Build).

**Inputs.** The live observatory and every artifact behind it, especially the update mechanics from Build and the cadences in the Source Register.

**Outputs.** A living **Steward Log** — every update applied, every source that changed, every method version bumped, every link repaired, and the results of the recurring **"still true?" audit**: is every figure still current, every source still live, every claim still supported? New Decision Records for anything the passage of time forces us to change.

**The gate — the standing checks.** On the cadence the Source Register demands: apply data updates through the path Build proved; re-run the pipeline; re-verify that live sources still resolve and still mean what they did; bump the method version when the method changes and say so publicly; and periodically re-run the seven conditions of Prove against the live product, because a thing that passed once can rot.

**The dignified end.** When an observatory can no longer be kept correct — its source is gone, its method superseded, its question no longer live — we do not abandon it to quietly mislead. We deprecate it deliberately: mark it clearly as historical, freeze it with its final vintage stated, or retire it with a written record of why. A dignified sunset is a stewardship success. A silent orphan is the one failure the constitution names by name and forbids.

**Iteration.** Steward is the loop. Significant change re-enters the lifecycle at the appropriate phase — a new question is a new Frame, a new source is a new Ground — carrying the same standard the original did.

---

## Artifacts: the studio's memory

Operating Principle 1 made concrete. The conversation is volatile; these artifacts are the record. Each has an owner, a home in the observatory folder, and a status. **Frozen** means changing it requires a formal re-open and a Decision Record. **Living** means it is expected to grow, versioned as it does. **Append-only** means entries are added, never edited or deleted.

| Artifact | Phase | Owner | Home | Status |
|----------|-------|-------|------|--------|
| Mandate | 0 | Lead | `docs/` | Frozen |
| Charter | 1 | Lead | `docs/` | Frozen |
| Source Register | 2 | Data | `docs/` | Living |
| Methodology | 3 | Data | `docs/` | Living, versioned |
| Design Brief | 4 | Design | `docs/` | Semi-frozen |
| Decision Records | any | whoever decides | `decisions/` | Append-only |
| Review checklists | 6 | Lead | `checklists/` | Living |
| Gate Record | 6 | Lead | `checklists/` | Append-only |
| Release Note | 7 | Build | `docs/` | Append-only |
| Steward Log | 8 | Lead | `docs/` | Append-only |
| Reusable prompts | any | whoever wrote them | `prompts/` | Living |

Two artifacts deserve their own rules.

**Decision Records** are how we decide once and never re-argue from memory (Operating Principle 5). One file per decision, in `decisions/`, named so it sorts by number. Each states: the decision, its date and status, the context that forced it, the alternatives we weighed, the consequences we accept, and whether it freezes anything. They are **append-only** — a decision we reverse gets a *new* record that supersedes the old one; we never rewrite history, because the reasoning of a choice we later abandoned is often the most valuable thing we own. A contested or irreversible decision that is not written here did not happen.

**Reusable prompts.** The AI instructions that reliably produced good work are themselves reusable knowledge (Operating Principle 3). We save the ones worth reusing to `prompts/`, so the next observatory inherits them instead of rediscovering them. This is how AImethod compounds across projects the way the visual system does.

---

## How we decide, and how we record it

**Two kinds of doors.** Before deciding, we ask which kind of door we are walking through.

- A **two-way door** is cheap to reverse. We decide it fast, at the lowest responsible level, and we do not over-document it. Deliberating a reversible choice to death is its own failure. Most surface decisions — wording, a chart type, a layout — are two-way doors.
- A **one-way door** is expensive or impossible to reverse, or it is a foundation others will build on. We slow down, weigh alternatives, decide at the accountable level, and write a Decision Record. The question, the audience order, the units and vocabulary, the uncertainty taxonomy, the source of truth for a dataset — all one-way doors.

Getting this classification right *is* Operating Principle 2 in practice: freeze the one-way doors, keep the two-way doors swinging.

**Who decides.** The accountable owner of the phase decides within their phase. The Lead breaks ties and owns any decision that crosses phases or touches the standard. When a decision is genuinely hard and roles disagree, the tiebreaker is not seniority, taste, or the deadline — it is the constitution. "Which choice better helps a real person understand something true they can check?" settles more arguments than any hierarchy.

**When to escalate.** A decision that would change the Charter is never made quietly inside a later phase. It goes to the Lead and, if it reopens the foundation, it trips the circuit breaker below.

---

## Iteration, and the Stop-and-Rethink circuit breaker

The lifecycle is a spiral. **Expected loops** — Ground ⇄ Reconcile, Reconcile ⇄ Design, Design ⇄ Build, and Prove routing failures back to their owning phase — are the workflow functioning as designed. Looping early, where it is cheap, is how we avoid looping late, where it is ruinous. A project that reached Prove without a single loop was probably not looking hard enough.

But some problems are not loops to be worked through — they are signals to stop. The **Stop-and-Rethink circuit breaker** is a deliberate, blameless halt that any role can pull and the Lead must honor. Pulling it is a mark of judgment, never of failure. Its triggers:

- **The question cannot survive the data.** Ground or Reconcile reveals that the data to honestly answer the Charter's question does not exist, or exists only at a quality that would force us to launder estimates into facts. We do not force it. We halt and re-Frame or decline.
- **The honest answer is "we don't know."** The rigorous result is that the question has no trustworthy answer yet. That is a finding worth publishing as such — or worth stopping for — but never worth faking past.
- **The foundation is being renegotiated in the hallway.** If the one-sentence question or the audience is quietly shifting phase to phase, the project has lost its foundation and is accumulating rework. Stop, and either re-Frame formally or hold the line.
- **The standard cannot be met on the current path.** If Prove is failing the same condition repeatedly and each patch breaks another, the design or the data is wrong at the root. Stop patching; rethink.

When the breaker is pulled, work halts, the Lead convenes the roles, and the outcome is written down: re-Frame, re-Ground, re-Design, or a decision not to proceed. A recorded "we stopped and rethought" is a healthy project. A project that never stops to rethink is not disciplined — it is not paying attention.

---

## Working with AI without losing the thread

AI is how the studio holds one standard across ten observatories that it could once barely hold across one (constitution, *On being "AI-first"*). Used well it is our largest advantage; used carelessly it is the fastest route to the chaos this whole workflow exists to prevent. AI-assisted projects go chaotic for four specific reasons, and the workflow answers each one directly:

- **Decisions vanish into chat.** A choice made in conversation and never written down is reversed by the next conversation. *Answer:* Operating Principle 1 and the Decision Record. Chat is scratch; the artifact is the record. Any decision that matters is promoted out of the transcript immediately, or it did not happen.
- **Context is re-explained every session, and drifts each time.** *Answer:* the frozen artifacts *are* the context. Every AI working session begins by loading the Charter and the relevant living docs, and ends by writing its output back into a named artifact. The model is briefed from the record and reports to the record — never from or to memory.
- **Nothing is frozen, so everything is renegotiable, so nothing converges.** *Answer:* Operating Principle 2. A frozen Charter gives the model — and the humans — a foundation that does not move under them.
- **The model happily rebuilds what already exists.** *Answer:* Operating Principle 3 and the shared canon. The studio's standards, systems, and reusable prompts are the model's starting context, so it extends the studio's work instead of reinventing it every session.

Three commitments are non-negotiable, straight from the constitution and binding on every phase: **no unaccountable claims** — nothing a model generates reaches a reader without the provenance we demand of ourselves; **judgment stays human** — AI drafts, people decide and sign the gate; and **scale multiplies the standard, never replaces it** — if AI is ever producing more at a lower bar, we are using it exactly backwards. The reader must never be able to tell which sentence a machine drafted, because every sentence cleared the same gate.

---

## What freezes early, and what stays fluid

The single most important operating judgment, stated plainly so a newcomer can apply it on day one.

**Freeze early** — expensive to reverse, foundational to trust, and depended on by everything downstream:

- the one-sentence question and the audience order (the Charter);
- the units, vocabulary, and comparability conventions (so a figure means one thing throughout, and across observatories — Principle 8);
- the uncertainty taxonomy: what counts as measured, estimated, modeled, projected (Principle 4);
- the declared source of truth for each dataset.

**Keep fluid** — cheap to reverse, and improved by feedback and iteration:

- wording and copy;
- specific chart types and encodings, within the shared grammar;
- layout, ordering, and visual styling, within the shared system;
- marginal feature scope.

The rule beneath the lists: **freeze what is expensive to change and load-bearing for trust; keep loose what is cheap to change and improved by contact with readers.** A studio that freezes the surface and negotiates the foundation has it exactly backwards, and will feel busy while going nowhere.

---

## What must never be skipped

Under deadline pressure, everything feels optional. These are not. Skipping any of them is not moving faster — it is lowering the standard, which the studio does not do at any speed:

1. **The one-sentence question** (Frame). No question, no product — only data looking for a purpose.
2. **The Source Register** (Ground). A figure we cannot trace is a figure we do not publish.
3. **The uncertainty taxonomy** (Reconcile). We never let an estimate reach a reader dressed as a fact.
4. **A Decision Record for every one-way door** (any phase). Decide once; never re-argue from memory.
5. **The seven-condition Prove gate** (Prove). "Good enough to ship" is not "meets the standard."
6. **The stewardship plan** (Build and Steward). We do not ship what we are not prepared to keep true.

If a phase feels skippable, that is the signal to slow down, not speed up. The workflow is designed to make skipping the thinking harder than doing it — and when it fails to, that is a bug in the workflow to be fixed here, not a shortcut to be taken there.

---

## Staying consistent across many observatories and many years

The studio is the product (Principle 11). What compounds is not any one observatory but the standard, the method, the vocabulary, and the reputation shared across all of them. The workflow protects that compounding through five mechanisms:

- **One canon, versioned.** The constitution and these studio documents are the shared law every project inherits. They are versioned, and each observatory records which version of the canon it was built against — so we can improve the canon without silently invalidating what came before.
- **One template.** Every observatory starts from the same folder structure and the same artifact set (`templates/observatory/`), so a person moving between projects — or an AI briefed on one — already knows where everything lives.
- **One system, one grammar, one vocabulary.** Shared naming, shared scales, shared chart grammar, and shared terms (Principle 8, `naming.md`, `design-principles.md`) mean a reader moving from the Water Observatory to the Air Quality Explorer never relearns how to read, and a maker never rebuilds what the studio already knows.
- **The Compound step.** Operating Principle 3 in practice: at the end of a project, and continuously during Steward, reusable patterns, components, methods, and prompts are promoted out of the project and back into the canon. Every observatory pays into the common well it drew from.
- **The guard against both failure modes.** We guard against soulless template-stamping *and* against every project vainly reinventing what the studio already decided. The test between them: sameness in service of quality is a feature; sameness that has stopped serving the reader is rot. When in doubt, the constitution decides.

---

## When is a project complete?

A project is never "complete" in the sense of finished-and-forgotten — Steward has no end while the observatory lives. But it reaches two distinct milestones the whole studio should be able to name:

**Publishable** — it has passed all seven conditions of Prove, its harm review is written, its Release Note is truthful, and every one-way door is recorded. This is the milestone that lets a reader in.

**Stewardable** — its update path is proven and exercised, its Source Register carries every cadence, its Steward Log is open, and a person who has never seen the project could pick it up from the artifacts alone and keep it correct. This is the milestone that lets us walk away without leaving an orphan.

A project that is publishable but not stewardable is not done — it is a beautiful liability with a countdown on it. We ship only what clears both.

And the milestone that closes the loop: **Compounded** — the reusable knowledge this project produced has been returned to the canon, so the next observatory starts ahead of where this one did. A project that made a great product but left the studio no smarter has, by Operating Principle 3, done only half its job.

---

## The test

When the phases seem to point in different directions and the gates feel like obstacles rather than protections, return to the single question the constitution exists to serve, and that this workflow exists to protect:

**Does this help a real person understand something true that matters to them — and could they check us if they doubted us?**

The workflow is not the point. The standard is the point, and the workflow is how we hold it across many people, many observatories, and many years — reliably, and on purpose, long after the enthusiasm of any one project has worn off.

The observatories are what we build. The way we build them is what makes us a studio.
