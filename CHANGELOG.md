# Changelog

Version and repository history for the AI Starter Kit.

Design-review rounds for the curriculum document itself are tracked separately
in the author's working revision log, which records what was flagged and changed
in each pass. This file records what changed at the repository level.

## Version history

| Version | Date | Notes |
| --- | --- | --- |
| 0.6.4 | 2026-09-20 | Current. Splits a compound Oettingen claim that carried one citation for two assertions, and records Burnett & Evans, Kirkpatrick and UNESCO as verified clean. |
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

Seventeen sources have been verified so far, claim by claim, and six defects
turned up. That is not an error rate, and it should not be read as one — the
six are four different kinds of thing, with very different consequences for a
reader.

| Severity | Defect | Consequence if uncaught |
|---|---|---|
| **Guidance-changing** | De Freitas misread; "don't dumb it down" presented as a research finding | A facilitator acts on instruction attributed to evidence that does not support it |
| **Guidance-changing** | 519 mL described as a worst-case 2023 per-prompt estimate | The row correcting a viral misreading transmits its own; a skeptic who checks finds the correction wrong |
| **Overclaim** | Kosmyna crossover reported at n=54 when it rests on n=18 | The kit's central design decision looks better evidenced than it is |
| **Internal contradiction** | "1–5 mL per query" against ~15 mL two sentences later, with no source for the first | A reader who reads carefully finds the section arguing with itself |
| **Misattribution** | MIT/OpenAI RCT credited to Phang rather than Fang | A reader following the citation reaches a real but different paper |
| **Incomplete citation** | Docebo and Li et al. cited in the body, absent from Source notes | A reader cannot check a claim that is, in both cases, accurate |

The last two rows are bookkeeping. The first two changed what the document tells
a facilitator to do. A document that has just spent three releases catching
itself overclaiming should not round all six to the same number, which would be
its own small overclaim.

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
