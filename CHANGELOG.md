# Changelog

Version and repository history for the AI Starter Kit.

Design-review rounds for the curriculum document itself are tracked separately
in the author's working revision log, which records what was flagged and changed
in each pass. This file records what changed at the repository level.

## Version history

| Version | Date | Notes |
| --- | --- | --- |
| 0.5 | 2026-09-20 | Current. Adds AI impersonation to the Part 5 doom-loop field guide and Session 3; adds standing/custom instructions to Part 6 practical notes; adds "Where this kit sits relative to other programs" cross-checking Google AI Essentials, Elements of AI, and Anthropic's AI Fluency framework. |
| 0.4 | 2026-09-08 | Content baseline reached through three review rounds. Never published under this label: the version string was not bumped as the content advanced, so this state shipped mislabelled as 0.2 and was corrected to 0.5 retroactively. |
| 0.1 | 2026-09-08 | First recorded baseline, 292 lines. |

The version string in `docs/ai-starter-kit.md`, `README.md` and `CITATION.cff`
is kept in sync. If you are citing this work, take the version from
`CITATION.cff`.

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

## Known issues

- GitHub's community profile reports `issue_template` as missing and the health
  score as 85%, although `.github/ISSUE_TEMPLATE/` contains `pilot-feedback.md`,
  `factual-correction.md` and `config.yml`, and all three serve correctly. Under
  investigation; may be a detection lag rather than a fault in the templates.
