# AI Starter Kit — Digital Tasks

A curriculum for people who hate AI or think it's too complicated.

This is an eight-session, research-grounded course for AI *skeptics*, AI *beginners*, and people who already use AI a little and have quietly stopped getting more out of it — three audiences with three different entry ramps that converge by session two. It teaches verification and calibration before productivity, treats literacy as self-defense first and efficiency second, and is built to actively guard against the failure modes it introduces (sycophancy, cognitive debt, substitution of AI for human contact) rather than assume good faith from the tools it teaches.

📄 **[Read the full curriculum](docs/ai-starter-kit.md)**

## What's here

| File | What it is | Plain text |
| --- | --- | --- |
| [`docs/ai-starter-kit.md`](docs/ai-starter-kit.md) | The full design document — research rationale, the eight-session lesson plan, a doom-loop field guide, a tool-selection framework, and open design questions | [raw](docs/ai-starter-kit.md?raw=true) |
| [`CHANGELOG.md`](CHANGELOG.md) | Version history and what changed in each | [raw](CHANGELOG.md?raw=true) |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | What contributions fit the design rationale, and what doesn't | [raw](CONTRIBUTING.md?raw=true) |
| [`facilitator/`](facilitator/README.md) | Status of the runnable session material: written, in pilot, published after the first run | [raw](facilitator/README.md?raw=true) |

## AI & LLM access

You can work through this curriculum with an AI assistant. **The method matters more than the tool**, because the two obvious approaches give very different results.

### Option A — give the assistant the file (recommended)

Two ways, in order of reliability.

**Attach it.** Download the curriculum, then attach the file to the chat:

```
https://raw.githubusercontent.com/somehippie/ai-starter-kit-digital-tasks/main/docs/ai-starter-kit.md
```

Right-click → *Save as* on that page, or use your browser's save shortcut. Every major assistant accepts a `.md` attachment, and an attachment either arrives whole or visibly fails.

**Or paste it,** if your tool takes no attachments. Open the same page, select all and copy — `Ctrl+A` `Ctrl+C`, or `Cmd+A` `Cmd+C` on a Mac — then paste into the chat. It is plain text with no site layout around it, so what you paste is the document and nothing else.

Paste is the fallback rather than the first move for one reason: this is a long document, and several chat interfaces silently truncate very large pastes, or convert them to an attachment, without saying so. That produces the exact failure this section exists to warn about, arriving through the route it recommends.

**So check that it landed, whichever route you used.** Ask:

> Before we start — what is the final section of this document called, and what is the last entry in it?

Then scroll to the bottom of the file yourself and see whether that is what it says. If the assistant cannot tell you, or tells you something that is not there, it does not have the whole document and nothing it says next is worth much.

Deliberately, the answer is not printed here. Checking it against the source rather than against this page takes five seconds, is the move Session 3 teaches, and works on any version of the document — including the ones written after this sentence.

### Option B — import the repository

Some assistants can pull a repository in directly, which keeps every file in view rather than just the curriculum. In Gemini this is **+ → Import code**; other tools have an equivalent. Give it:

```
https://github.com/somehippie/ai-starter-kit-digital-tasks
```

Use this if you want the changelog and contribution guidance alongside the curriculum. Option A is enough for reading the course itself.

### What to avoid, and why

**Pasting the URL on its own and asking the assistant to go read it.** Unless the tool has a genuine browsing extension, a link in a prompt is handled by a fetcher that will often summarize a long page rather than load it, truncate it partway, or fail quietly and answer from memory instead. You get an answer that sounds like the document and is not checkable against it. Copy the text in, or import the repository.

**A `404` on `/llms.txt` does not mean the repository is unreachable.** Some tools probe for that file by convention before reading a repository. It is deliberately not here — see the v0.7 entry in [CHANGELOG.md](CHANGELOG.md) for the evidence behind dropping it — so a 404 there is the expected result and says nothing about the rest. Every link on this page resolves anonymously with no token.

### Other files

| What | URL to paste |
| --- | --- |
| The full curriculum | `https://raw.githubusercontent.com/somehippie/ai-starter-kit-digital-tasks/main/docs/ai-starter-kit.md` |
| Version history | `https://raw.githubusercontent.com/somehippie/ai-starter-kit-digital-tasks/main/CHANGELOG.md` |
| Contribution guidance | `https://raw.githubusercontent.com/somehippie/ai-starter-kit-digital-tasks/main/CONTRIBUTING.md` |

Those track the current version. To pin one so it cannot change under you later, swap `main` for a release tag, for example `v0.9.2`.

### A prompt that works, if you want one

> Read this curriculum and tell me which of the eight sessions is most relevant to someone who &lt;describe yourself here&gt;. Quote the part you're basing that on so I can check it against the source.

Asking for the quote is not decoration. It is the habit the curriculum teaches in Session 3, and this is a reasonable place to start practicing it: open the document yourself and confirm the quoted passage exists and says what the summary claims. A tool that summarizes this document while inventing a passage is demonstrating the exact failure the document is about.

Two caveats before you rely on a summary. The curriculum is long enough that a tool asked for "the main points" will flatten the reasoning that makes the recommendations make sense — the reasoning is most of the value, and it is the first thing a summary drops. And the statistics carry a short shelf life, flagged in the document itself and scheduled for re-checking in its Source notes; an assistant repeating them to you a year from now will not know they have moved.

## Who this is for

- **Facilitators** running a group or one-on-one AI-literacy session for adults who are skeptical of, or overwhelmed by, AI tools
- **Curious existing users** who use AI for a handful of small things and suspect there is more there. Session 1C is the entry ramp for this, and it is **published untested** — no learner has run it yet
- **Self-learners** who want a structured, evidence-based on-ramp rather than a tool tour — with one caveat worth reading first: the curriculum is specified as a *facilitated* course, and the solo version is untested. Four steps are marked **[F]** in the document because they depend on a live facilitator, three of them on simply having a witness. Part 8 sets out what is unresolved about removing that, including the possibility that the solo build is a substantially weaker intervention rather than the same one delivered differently. You can absolutely work through this alone. You should know that nobody has yet measured what that costs.
- Anyone adapting AI-literacy material for a community group, library program, or workplace training who wants something more rigorous than a generic vendor deck

## Design principles

1. **Human-first sequencing.** Every exercise has the learner think or write unaided before the tool is introduced. This is a specific, evidenced response to research showing that tool-first order degrades independent recall and ownership of work, while human-first order improves it.
2. **Calibration before capability.** The course teaches learners to find where a model is reliable and where it confidently breaks *before* it teaches them to lean on it, grounded in findings that overconfidence in an AI tool measurably reduces critical thinking.
3. **Honesty over evangelism.** A verbatim "honest ledger" of AI's actual costs and failure rates is handed to learners early — including facts that strengthen the skeptic's case, not just the ones that weaken it.
4. **Literacy as self-defense.** The course treats being able to detect when AI is being used *on* the learner (in hiring, credit, claims, or scams) as being at least as important as knowing how to use it themselves.
5. **Measured, not assumed.** The curriculum defines its own success and failure metrics up front, including counter-metrics designed to catch the course itself causing harm (rising reliance, falling human contact).

## Educational and AI-literacy standards this aligns with

- **[UNESCO AI Competency Framework for Students](https://www.unesco.org/en/digital-education/ai-future-learning)** (2024) — the eight sessions are explicitly mapped to its four competency dimensions (human-centred mindset, ethics of AI, AI techniques and applications, AI system design) and three progression levels (Understand, Apply, Create).
- **[Anthropic's AI Fluency Framework](https://academy.claude.com/courses/ai-fluency-framework-foundations)** (Delegation, Description, Discernment, Diligence) — this kit converges independently on a closely related sequence (describe your context fully → verify before trusting), documented in the curriculum's tool-selection section as a cross-check, not a source.
- Cross-checked against comparable public programs, including **[Google AI Essentials](https://grow.google/ai-essentials/)** and the **[University of Helsinki's Elements of AI](https://www.elementsofai.com/)**, to confirm scope and identify gaps (see "Where this kit sits relative to other programs" in the curriculum).

## Status

Version 0.9.2. This is an active design document, not a finished product — Part 8 lists open design questions the author is still working through, and the curriculum has not yet completed a full facilitator pilot. Treat figures and cited statistics as accurate as of the version date; several (energy/water-per-query estimates in particular) are explicitly flagged in the document as having a short shelf life and needing periodic re-verification.

## Contributing

Suggestions, corrections, and pilot-run feedback are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Please open an issue before a large pull request so the change can be discussed against the curriculum's design rationale (Part 1 and Part 8 of the doc explain a lot of decisions that look arbitrary until you've read the reasoning behind them).

## License

The written curriculum in this repository is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE) — you're free to use, adapt, and redistribute it, including for commercial facilitation, with attribution. See [LICENSE](LICENSE).

## Code of conduct

This project follows a lightweight [Code of Conduct](CODE_OF_CONDUCT.md) based on the Contributor Covenant.

## Citation

If you use or adapt this curriculum, please cite it — see [CITATION.cff](CITATION.cff).
