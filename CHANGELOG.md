# Changelog

Version and repository history for the AI Starter Kit.

Design-review rounds for the curriculum document itself are tracked separately
in the author's working revision log, which records what was flagged and changed
in each pass. This file records what changed at the repository level.

## Version history

| Version | Date | Notes |
| --- | --- | --- |
| 0.8 | 2026-09-20 | Current. Session 3 gains a fourth verification habit, the support test, with its evidence type stated on the page; "push on obscure specifics" becomes a named target list; refusal is named as the session's only positive signal; Part 5 gains a matching row. Session 3's clock re-priced to make room. |
| 0.7.1 | 2026-09-20 | Links nine load-bearing figures that the 0.7 pass left bare because they were second mentions. Names what the Dell'Acqua key actually resolves to. |
| 0.7 | 2026-09-20 | Citation apparatus. Named reference keys at every load-bearing claim, Source notes rebuilt as tables grouped by re-verification horizon, six previously uncited sources added, and leading-indicator vocabulary named in Part 7. Verification of all 26 sources complete. No curriculum argument changed. |
| 0.6.4 | 2026-09-20 | Splits a compound Oettingen claim that carried one citation for two assertions, and records Burnett & Evans, Kirkpatrick and UNESCO as verified clean. |
| 0.6.3 | 2026-09-20 | Source-note precision: EY fieldwork dates alongside the publication date, Brynjolfsson volume and year, Dell'Acqua open-access working paper. Adds a severity breakdown to the corrections below. |
| 0.6.2 | 2026-09-20 | **Correction release.** Part 3's water figures were wrong about their own provenance and internally inconsistent; a study was attributed to the wrong lead author. See "Corrections" below. |
| 0.6.1 | 2026-09-20 | **Correction release.** Two factual errors found in the published text during source verification: a misread of De Freitas et al. that an instruction rested on, and a sample size stated for a subgroup it did not apply to. See "Corrections" below. |
| 0.6 | 2026-09-20 | Adds a fake-citation calibration probe to Session 3, giving the session a near-guaranteed trigger instead of relying on a naturally occurring fabrication; adds "The two audiences are one trajectory" to Part 2, a four-phase adoption model drawn from the author's own path with its n=1 limits stated; adds a Part 8 open question on whether phase D (publishing, tooling, building) is a ninth session, a separate kit, or out of scope. Repository gains plain-text access routes for AI assistants. |
| 0.5 | 2026-09-20 | Adds AI impersonation to the Part 5 doom-loop field guide and Session 3; adds standing/custom instructions to Part 6 practical notes; adds "Where this kit sits relative to other programs" cross-checking Google AI Essentials, Elements of AI, and Anthropic's AI Fluency framework. |
| 0.4 | 2026-09-08 | Content baseline reached through three review rounds. Never published under this label: the version string was not bumped as the content advanced, so this state shipped mislabelled as 0.2 and was corrected to 0.5 retroactively. |
| 0.1 | 2026-09-08 | First recorded baseline, 292 lines. |

The version string in `docs/ai-starter-kit.md`, `README.md` and `CITATION.cff`
is kept in sync. If you are citing this work, take the version from
`CITATION.cff`.

**The version tracks the curriculum document, not the repository.** A release
tag marks the state of `docs/ai-starter-kit.md` at that version. Commits that
touch only repository scaffolding — contribution guidance, issue templates,
status files — land after the tag without bumping it, so `main` will routinely
sit ahead of the newest tag while both correctly claim the same version. `v0.6`
is the first instance: `eee66e1` added `facilitator/README.md`, a CONTRIBUTING
section and a README caveat after the tag, and `docs/ai-starter-kit.md` is
byte-identical between the two.

Do not move a published tag to close that gap. A tag that has been pushed is a
fixed address, and repointing it breaks anyone who pinned a raw URL to it,
which the README explicitly invites readers to do. The drift is the convention
working, not a mistake to correct.

## Curriculum

### 0.8 — the fourth verification habit

**The support test.** The first three habits all confirm that a claim *has*
support: the reversal tests whether a position exists, the source demand tests
whether a citation is real, the stakes test routes by consequence. None asks
whether the support *reaches* the claim. A real paper, correctly attributed, in
the right field, supporting something adjacent passes all three. The fourth
habit asks the missing question in two directions — extent, and attachment.

**Its evidence type is stated on the page, not only here.** The first three
habits cite Lee et al. The fourth cites eight documented instances of claims
failing in ways those three passed, six of them in earlier published versions
of this curriculum. That is real evidence and a different kind of evidence, and
a session about telling those apart is the wrong place to blur the distinction.
Presenting four habits at identical authority would have let the new one borrow
credibility from its neighbours in a table — which is one of the failure modes
it exists to catch.

**A boundary is stated with it.** The support test does not cover Session 2's
territory. When a model works past its competence the answer is wrong at the
root, the sources may be impeccable, and checking whether support reaches the
claim does not help. That failure is invisible to any question asked of the
model about itself, which is why Session 2 uses the learner's own expertise
instead.

**"Push on obscure specifics" is now a map.** The old instruction was too vague
to act on. It is replaced by five named high-interpolation targets — citations,
model and part numbers, version-specific menu paths, official procedures, and
formatted figures — chosen because the *shape* of a correct answer is learnable
in each while the specific instance may not exist. Also drawn from observed
errors rather than a study, and labelled as such.

**Refusal is named as the session's only positive signal.** When the practice
target produces "I cannot find that," the session now stops and says so.
Everything else in Session 3 teaches catching a tool being wrong, and a course
that only points at failure produces a learner who distrusts everything
equally, which is not calibration.

**Part 5 gains a matching row**, distinct from the frontier trap: support that
does not reach, with detection signals for both directions.

### The clock, priced rather than discovered

Session 3 was already the fullest session in the kit, and three additions to
the densest session is how a 90-minute plan quietly becomes 110 minutes in a
room.

The open hunt on the learner's own work was budgeted at forty minutes, and that
number was set when catching a fabrication depended on luck — the block ran
long because it was the only route to the artifact. The practice target,
added in v0.6.1, changed its job and nobody re-priced it. The artifact is now
reliably in hand before the hunt begins, so the hunt is no longer hunting; it
is applying four habits to work the learner cares about, which is worth about
twenty focused minutes.

That re-pricing is what makes room, rather than the session running over. The
document now says which cut to make if it overruns anyway: the open hunt, not
the support test, because the habits are the session and the hunt is the
rehearsal.

**Session 2 was considered and rejected as a home for the refusal material.**
Its own text describes the learner having "just spent ninety minutes" on the
frontier exercise, so it is already at the top of the band. The material went
into Session 3's practice-target debrief instead, where the hook already
existed and the cost is close to zero.

## Sources

### 0.7.1 — the linking pass ran in the wrong direction

The 0.7 pass walked the twenty-six sources and linked each where it was first
introduced. Every *recurrence* of a figure was therefore left bare, and nine
load-bearing numbers ended up unlinked at the point a reader most needs them.

| Figure | Was linked at | Was bare at |
|---|---|---|
| 19 percentage points | Part 3 | **Session 2's instructor script** |
| g = 0.465 and g = 0.277 | nowhere | Session 6, and again in Part 8 |
| 85% role-relevance | Part 1 | Both Part 8 uses |
| 84% EY | Part 1 | Inside the adoption arc |
| 71% jobs | Part 1 | The honest ledger row |
| 0.26 mL and 17 mL | The water row | The "no reliable number" row |

Two were worse than the rest. The 19-point figure is the line a facilitator
reads aloud in Session 2; a skeptic asks *says who*, and the document offered
nothing at the point of use while the identical claim sat fully sourced fifty
lines earlier. And g = 0.465 is called "the strongest single argument in the
entire research base for using a conversational model here" — it had no link at
first mention or anywhere else, because the meta-analysis had already been
introduced two lines above for a different figure.

**This is the third time the same direction error has produced defects.** A
source-side pass asks "where did I introduce this source?" and stops there. A
claim-side pass asks "which figures exist, and does each occurrence carry its
source?" Verification found twice as many defects claim-side. The linking pass
was built to close a sourcing gap and reproduced the gap in a new form because
it ran the other way.

Also now stated in the Source notes entry: the `dellacqua-2026` key resolves to
the open-access preprint, HBS Working Paper 24-013, dated **September 2023**,
because the journal version is paywalled. A reader clicking a key labelled 2026
lands on a document dated 2023, and the entry now says so.

Link graph after the pass: 68 usages, 29 keys, 29 definitions, none undefined,
none unused, no bare figure sites remaining.

### 0.7 — the citation apparatus

Mechanical pass. Deliberately carries no change to any argument, so the diff
can be read as plumbing rather than searched for hidden substance.

**Named reference keys, not numbers.** Every load-bearing claim now links to its
source through a Markdown reference key — `[19 percentage points][dellacqua-2026]`
rather than `[5]`. Numbered markers renumber silently when a source is inserted,
in a document Part 8 commits to re-verifying periodically. Named keys cannot
drift, and a linked phrase reads as journalism rather than academic apparatus,
which suits a curriculum written for people who distrust institutional voice.

**Source notes grouped by how fast each row goes wrong.** Part 8 says the
accuracy obligation should be budgeted rather than discovered. Dating every row
to the same re-check would have recorded history and created a cliff: twenty-six
rows falling due at once. They are staggered instead.

| Horizon | Rows | What is in it |
|---|---|---|
| 2027-01 | 5 | Water and energy figures. These moved by two orders of magnitude in three years |
| 2027-06 | 4 | Survey percentages, which age on a predictable annual cycle |
| 2027-09 | 6 | Live web pages, health advisories and courses that change without notice |
| 2029 | 17 | Peer-reviewed papers, books and published frameworks |

The 2027 maintenance job is therefore five rows in January and a handful more
across the year, not twenty-six in one sitting. That is a commitment a person
can keep.

**Six previously uncited sources added.** Docebo, Li et al., Kirkpatrick,
OpenAI's water statement, the IEA, and the *Washington Post* / UC Riverside
analysis were all cited in the body and absent from Source notes.

**Every key was checked for resolution after the pass.** A mistyped key that
happens to match another entry would be citation drift introduced by the pass
built to prevent it, and it would survive every check except following the link.
The check found two keys used but undefined — the two book citations, which have
no URL — and they were returned to plain text. Final state: 29 definitions, 29
used, none undefined, none unused, no two keys pointing at one target.

**Part 7 names its leading indicators.** The week-four checkpoint and the
session 3 artifact already were leading indicators in the New World Kirkpatrick
sense; the design predated the vocabulary. Naming it costs a sentence and makes
the measurement design legible to anyone who evaluates training professionally,
which is the reader a library or workplace programme routes this to.

**Verification complete: 26 sources.** The last five — NCOA, McAfee, Google AI
Essentials, Elements of AI and Anthropic's AI Fluency framework — were verified
clean, as were UNESCO, Burnett & Evans and Kirkpatrick before them.

## Corrections

### 0.6.4 — one citation covering two claims

Part 1 asserted that positive fantasy reduces effort **and** that this had been
"replicated over 25 years," under a single citation to Oettingen's 2014 book.
The first half is a experimental result. The second is a claim about a research
programme's durability, which no single study can support and which nothing in
the document sourced.

Both halves are now anchored. The effect is Kappes & Oettingen (2011),
"Positive fantasies about idealized futures sap energy." The programme-level
claim is Oettingen (2012), "Future thought and behaviour change," a 63-page
review of the fantasy-realization literature that states the finding directly.
The bare "25 years" is gone, replaced by two citations a reader can open.

A compound claim under one citation is how a sourced assertion and an unsourced
one travel together without either being examined.

### Verified clean and worth recording

Not every check produces a correction, and a verification pass that only reports
its catches gives a false picture of the document.

| Source | Checked | Result |
|---|---|---|
| UNESCO AI Competency Framework | Four dimension names, three level names | Exact, British spelling included. The README's alignment claim and all eight session tags hold |
| Burnett & Evans, *Designing Your Life* | Six named concepts used as vocabulary across Sessions 4, 5 and 7 — Odyssey Plans, gravity problem, dysfunctional belief, prototype conversation, prototype experience, Good Time Journal | All six are the book's own terms. The gravity-problem gloss matches the source nearly verbatim |
| Kirkpatrick | That Level 3 is Behavior and Level 4 is Results | Correct. Part 7's mapping holds |
| Dell'Acqua publication year | Flagged internally as possibly wrong | The document was right. The 2025 in the DOI is a manuscript number |

Terminology and framework names carry the same risk as figures: a facilitator
says them aloud and a learner may look them up. These were checked for that
reason and none needed changing.

### What was actually found, by severity

Twenty-one sources have been verified so far, claim by claim, and eight defects
turned up. That is not an error rate, and it should not be read as one — the
eight are five different kinds of thing, with very different consequences for a
reader.

| Severity | Defect | Consequence if uncaught |
|---|---|---|
| **Guidance-changing** | De Freitas misread; "don't dumb it down" presented as a research finding | A facilitator acts on instruction attributed to evidence that does not support it |
| **Guidance-changing** | 519 mL described as a worst-case 2023 per-prompt estimate | The row correcting a viral misreading transmits its own; a skeptic who checks finds the correction wrong |
| **Overclaim** | Kosmyna crossover reported at n=54 when it rests on n=18 | The kit's central design decision looks better evidenced than it is |
| **Internal contradiction** | "1–5 mL per query" against ~15 mL two sentences later, with no source for the first | A reader who reads carefully finds the section arguing with itself |
| **Misattribution** | MIT/OpenAI RCT credited to Phang rather than Fang | A reader following the citation reaches a real but different paper |
| **Unsourced claim** | "Replicated over 25 years" carried by a book citation that supports the effect but not the durability | A claim about a research programme's weight rests on nothing, under a citation that looks like it covers both |
| **Incomplete citation** | Docebo cited in the body, absent from Source notes | A reader cannot check a claim that is, in fact, accurate |
| **Incomplete citation** | Li et al. cited in Session 8, absent from Source notes | Same |

The last two rows are bookkeeping. The first two changed what the document tells
a facilitator to do. A document that has spent four releases catching itself
overclaiming should not round all eight to the same number, which would be its
own small overclaim.

**Five of the eight share one shape.** De Freitas, the 519 mL provenance, the
Phang/Fang swap, the "25 years" durability claim and the unsourced 1–5 mL range
are all the same failure: a claim attached to the nearest plausible source
rather than the one that supports it, or — in the last two — to no source at
all while sitting among neighbours that have them. In every case the citation
resolved, the author was right, and the paper was about the right topic. Only
reading the specific sentence caught it.

Also worth recording: **UNESCO verified clean.** All four dimension names and
all three progression levels match the framework exactly, so the standards
alignment the README advertises holds, and so do the tags on all eight sessions.
That was the highest-stakes item left and it was correct as written.

### 0.6.2 — the honest ledger was not accurate about its own numbers

Found by verifying Part 3 claim-side: working from each number in the body
outward to the source that carries it, rather than from the citation list
inward. That direction finds claims standing on nothing, which the source-side
pass in 0.6.1 structurally could not.

**The 519 mL figure was misattributed and misdescribed.** The document called
it "a worst-case 2023 lifecycle estimate." It is neither worst-case nor 2023
nor per-prompt. It comes from a September 2024 *Washington Post* analysis with
UC Riverside, and it measures full-scope water for a **100-word email** written
by GPT-4. The 2023 paper people confuse it with is a different number again —
500 mL per *10 to 50* GPT-3 responses, which is where "a bottle of water per
prompt" entered circulation, by dropping the denominator.

That matters more here than it would elsewhere. This row exists to correct a
viral misreading of a statistic. Getting the statistic's own provenance wrong
while correcting it is the failure the row is about.

**The row contradicted itself two sentences apart.** It claimed full-scope 2026
estimates "land around 1–5 mL per query," then cited the same paper's author
putting a GPT-4-class prompt near 15 mL full scope. No source was found for the
1–5 mL range. It has been replaced with the actual published spread, which is
0.26 mL to 17 mL depending on who measured, what they counted, and prompt
length, and a new row saying plainly that the order of magnitude is settled
while the figure is not.

**The measured/asserted distinction is now explicit.** Google published a
methodology with its 0.26 mL. OpenAI stated 0.32 mL without publishing one.
Both were previously presented in the same breath, which a section built on
credibility should not do.

**A study was credited to the wrong author.** The four-week MIT/OpenAI
randomized controlled trial is Fang et al. (n=981). Phang et al. is the
companion platform study. The document cited the RCT as Phang throughout;
both are now named correctly, with arXiv identifiers.

### 0.6.1 — two errors found in our own published text

Both were found by checking each cited source for the specific figure or claim
attributed to it, rather than checking that the citation resolved. Neither
would have surfaced from a link check. Both were live in the tagged `v0.6`
release under CC BY, which is to say forkable.

**De Freitas et al. was misread, and an instruction rested on the misreading.**
Part 2 attributed to that paper the finding that "explanations that are too
simple reduce uptake," and drew from it the facilitator instruction "don't dumb
it down for this group." The paper says something different: an explanation
revealing that *the AI tool* is too simple **for the task** reduces uptake. That
is a claim about underpowered systems, not about pitching an explanation too
low.

The instruction survives; the sourcing does not. It is now stated explicitly as
a design judgment with its own reasoning — this audience's objection is moral
rather than technical, and simplification reads as handling — and labelled as
not a research finding. The same row also dropped a bound the paper is explicit
about: the control effect plateaus, and too much control degrades decision
accuracy. That bound is now stated where the mechanism is used, in Part 2 and
again in Part 6.

**A crossover finding was reported at n=54 when it rests on n=18.** Part 1
described Kosmyna et al. as putting "54 participants through four essay-writing
sessions." Fifty-four completed sessions one to three. Eighteen completed the
fourth, and the fourth is the crossover session that produced the human-first
result — the single most load-bearing design decision in the curriculum.

The number is corrected and the confidence language around it is softened. More
substantially, the stated rationale changed. Human-first no longer rests on the
effect at all; it rests on an asymmetry that holds regardless of whether the
finding replicates. A learner who thinks first and brings the tool in second
loses a few minutes if it fails. A learner who goes tool-first risks what the
study points at if it holds. A cheap precaution against a plausible harm is
worth taking at n=18. An effect-size argument would not be.

### Why this is recorded prominently rather than quietly

The second error is scope drop: an observation stated about more of the world
than it sampled. The curriculum names that failure mode, teaches learners to
catch it, and then committed it in its own voice about its own central finding.

A document arguing that confident wrongness is the default failure of these
tools, and that the fix is procedural rather than perceptual, has no standing to
handle its own errors any differently. The corrections are versioned, tagged and
described here for the same reason Session 3's artifact requires the learner to
produce a caught fabrication rather than a summary of the concept.

## Repository history

### 2026-09-20, published

First published to GitHub as `somehippie/AISK-Digital-Tasks`, public, CC BY 4.0.

### 2026-09-20, licence detection fixed

`LICENSE` originally held an abridged CC BY 4.0 text that omitted the leading
Creative Commons notice block, roughly 450 words short of the canonical legal
code. GitHub's licence detector could not match it and reported the repository
as `NOASSERTION` ("Other"), contradicting the `CC-BY-4.0` declared in
`CITATION.cff`. Replaced with the verbatim legal code from
`creativecommons.org/licenses/by/4.0/legalcode.txt`. Detection now reports
`CC-BY-4.0` correctly.

The licence itself did not change. Only the completeness of the text did.

### 2026-09-20, renamed twice

| From | To | Why |
| --- | --- | --- |
| `AISK-Digital-Tasks` | `AI-Starter-Kit-Digital-Tasks` | The initialism is not expandable by anyone outside the project, and the full name matches the title in `CITATION.cff` and the document header. |
| `AI-Starter-Kit-Digital-Tasks` | `ai-starter-kit-digital-tasks` | Lowercase kebab-case is the prevailing GitHub convention and matches the owner's other repositories. Capitals can require quoting in some shell contexts and collide on case-insensitive filesystems. |

GitHub redirects permanently from former names, so links and clones using an
earlier URL continue to work. `CITATION.cff` names the current repository
directly.

### 2026-09-20, plain-text access for AI assistants

Added an "AI & LLM access" section to `README.md` giving absolute
`raw.githubusercontent.com` URLs, plus a `?raw=true` column in the file table.

The reason for absolute URLs rather than relative ones: a beginner pasting a
document into Gemini or Claude needs a complete URL, and a relative path copied
out of a README is not one. The `?raw=true` column serves readers already
browsing on GitHub, resolving to the same raw content without leaving the site.
Existing links stay rendered, because converting the primary link to raw would
hand every human reader an unrendered 45 KB text dump to serve crawlers that
fetch the raw file regardless.

An `llms.txt` index was written and then dropped before release. The 2026
evidence does not support it: adoption sits near 10% of sampled domains, the
major assistant crawlers do not fetch it in meaningful volume, and a
citation-prediction model improved when the variable was removed, meaning the
file contributed noise rather than signal. It also has to be updated whenever
the docs change or it silently goes stale. Recorded here so the option is not
re-proposed without new evidence.

## Notes

### Community profile reads 100%, the REST API disagrees

The repository's community profile page shows 100%, with all seven items
checked including issue templates.

The REST API endpoint `/repos/{owner}/{repo}/community/profile` reports
`issue_template: null` and a health score of 85% for this repository. That is a
known defect in the API rather than a gap here: the `files.issue_template` field
only reports the legacy single-file `.github/ISSUE_TEMPLATE.md`, so any
repository using the modern `.github/ISSUE_TEMPLATE/` directory reads as null
even when the community page counts it. It is filed against GitHub's own REST
API description as a schema inaccuracy.

`.github/ISSUE_TEMPLATE/` holds `pilot-feedback.md` and `factual-correction.md`,
both with valid `name:` and `about:` front matter, plus `config.yml`. They
render in the issue chooser normally.

Recorded here because tooling that scores repositories from that API will
report this one at 85% indefinitely, and the gap is in the measurement, not the
repository.
