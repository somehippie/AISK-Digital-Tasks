# Changelog

Version and repository history for the AI Starter Kit.

Design-review rounds for the curriculum document itself are tracked separately
in the author's working revision log, which records what was flagged and changed
in each pass. This file records what changed at the repository level.

## Version history

| Version | Date | Notes |
| --- | --- | --- |
| 0.6.1 | 2026-09-20 | Current. **Correction release.** Two factual errors found in the published text during source verification: a misread of De Freitas et al. that an instruction rested on, and a sample size stated for a subgroup it did not apply to. See "Corrections" below. |
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
