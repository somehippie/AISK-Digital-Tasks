# The AI Starter Kit

**A curriculum for people who hate AI or think it's too complicated.**

Design document, eight-session lesson plan, tool list, and doom-loop protocol.
Version 0.10 — September 2026.

---

## Part 1 — What the research changed about the original concept

The starting idea was: build the person's life story, find where they want to be before they die, then use AI plus strategy plus iteration to get there. The research supports the destination and contradicts the order of operations. Five findings force a redesign.

**The skeptics are the majority, not the fringe.** [Pew's June 2026 survey][pew-2026-06] found 52% of US adults are more concerned than excited about AI, against 9% more excited. For the first time a majority of under-30s (55%) are in the concerned column, and 71% expect AI to reduce the number of jobs. This is not a kit for a minority of holdouts. It is a kit for the median person, and it should be built with the confidence that comes from that.

**The gap is entry, not satisfaction.** The [EY Ripples and AARP/OATS survey][ey-aarp-2026] of 2,515 people aged 60–85 across 16 countries found that among those who had actually tried AI tools, 84% reported positive experiences for work, 83% for learning, and 80% for creative pursuits. The most common use was learning, at 79%. People who cross the threshold mostly like it. The problem is the threshold, and the first thing they reach for is not productivity — it is curiosity.

**Generic training is the thing that already failed.** In [Docebo's 2026 survey][docebo-2026] of 2,000 employees, 85% said their AI training did not help them understand how to use AI in their specific role. Another tool tour will do nothing. The personalization is not a nice-to-have; it is the entire active ingredient. This is the strongest argument for the life-story premise — but it argues for personalization of *the task*, not necessarily of *the emotional content*.

**Order of operations determines whether the tool builds or erodes skill.** [Kosmyna et al. at MIT Media Lab (2025)][kosmyna-2025] ran essay-writing sessions on EEG: 54 participants across the first three sessions, of whom **18** returned for a fourth in which conditions were swapped. Across the main sessions, brain connectivity scaled down with the amount of external support, and the LLM group showed the weakest coupling, the lowest sense of ownership, and trouble quoting their own writing. The result that bears on curriculum design comes from that fourth session: participants who had written unaided first and then brought in the LLM showed higher memory recall and stronger prefrontal and occipito-parietal activation, while those who went the other way showed reduced alpha and beta connectivity.

That last result is eighteen people in one session of one study, and it should be held exactly that loosely. Every exercise in this kit runs human-first anyway, and the reason is not the effect size. **The costs are asymmetric.** A learner who thinks first and brings the tool in second loses a few minutes if the finding fails to replicate. A learner who goes tool-first risks what the study points at if it holds. A cheap precaution against a plausible harm is worth taking at n=18, which an effect-size argument would not be, and the kit should say which of the two is doing the work.

**Confidence in yourself protects you; confidence in the AI does not.** [Lee et al.][lee-2025] (Microsoft Research and Carnegie Mellon, CHI 2025) surveyed 319 knowledge workers across 936 real AI-assisted tasks. Higher confidence in the AI predicted *less* critical thinking. Higher confidence in one's own ability on the task predicted *more*. This inverts the usual teaching instinct. The goal is not to make the learner trust the tool. It is to make the learner trust themselves enough to argue with it.

### The correction

Opening a kit for AI skeptics with "tell the machine your life story" is the worst available first move, for four independent reasons.

| Reason | Evidence |
|---|---|
| Privacy is their live objection | Roughly seven in ten US adults expect AI to make their personal information less secure ([Pew, Feb 2026][pew-2026-02]). Step one asks them to hand over their most sensitive material to the thing they distrust |
| Personal conversations track worse outcomes | In [Fang et al.'s four-week MIT/OpenAI RCT][fang-2025] (n=981), higher daily use correlated with higher loneliness, emotional dependence, and problematic use, and lower socialization. Personal-topic conditions correlated with higher loneliness |
| Sycophancy is worst exactly here | The "technological folie à deux" model ([Nature Mental Health, 2026][dohnany-2026]) describes bidirectional amplification: the model validates a self-narrative, the narrative re-enters context, the model validates harder. A life story is the ideal substrate for this loop |
| Pure aspiration reduces effort | Oettingen's core finding, demonstrated experimentally by [Kappes and Oettingen (2011)][kappes-2011] and set out across a 63-page review of the fantasy-realization literature ([Oettingen, 2012][oettingen-2012]): vividly imagining a desired outcome as already achieved *decreases* goal-relevant effort and attainment relative to controls. A vision-board session actively makes people less likely to act |

So the life story stays — it is the right destination and the right source of motivation — but it moves from session one to session four, after the learner has earned the ability to catch the model being wrong. The kit buys trust with a small verifiable win before it asks for anything personal.

---

## Part 2 — The learners are not one audience

Merging them produces a curriculum that condescends to the first, overwhelms the second and bores the third. They need different entry ramps and converge at session two.

Three ramps, not three tracks. The distinction matters: after session two the course is identical for everyone, and the ramps exist only because the first hour has to start where the learner actually is.

| | The refuser | The overwhelmed | The newly interested |
|---|---|---|---|
| Where they are | Phase A of the arc below. Opinions formed from coverage rather than contact | Phase A or B, with the barrier inside rather than outside | **Phase B.** Has used it, liked it, changed nothing |
| Actual objection | Moral and political. Jobs, artists, environment, surveillance, slop, concentration of power | Practical and identity-based. "I'm not technical." "I'll do it wrong." "It's already too late to start" | **None.** That is the difficulty. Nothing is wrong, so nothing moves |
| What a bad kit does | Tries to argue them out of it, or opens with benefits. Both read as sales and confirm their prior | Shows them twelve tools. Confirms the complexity fear and produces paralysis | Shows them more small wins. Confirms the ceiling and calls it progress |
| What actually opens the door | Giving their objection accurate ammunition. Most of what they've heard is wrong in *both* directions, and the corrections cut both ways | Removing choice. One tool, one task, one sitting, done today | A task they would not have attempted. The limit is what they thought to ask, not what the tool does |
| Entry ramp | Session 1A — Standing | Session 1B — One thing | Session 1C — Ceiling |
| Load-bearing evidence | [De Freitas et al., *Nature Human Behaviour* (2023)][defreitas-2023]: resistance drops when users are given a genuine measure of control — with the paper's own bound attached, that the effect plateaus and too much control degrades decision accuracy. So the move is a small control actually exercised, not a large one offered | [Brynjolfsson, Li & Raymond][brynjolfsson-2025] (*QJE*, 2025): novice and lower-skilled support agents gained ~34% while the most experienced gained near zero. [Dell'Acqua et al.][dellacqua-2026]: below-average BCG consultants gained 43% against 17% for above-average performers |

The single most useful sentence for the overwhelmed learner is a research finding, not a reassurance: **in the studies that exist, the people who gain most from these tools are the ones who start with the least expertise.** Being behind is the advantage, not the disqualification.

The single most useful move for the newly interested learner is to show them their own list. Asked what they use it for, they produce four or five small things and recognize, without being told, that the list describes their imagination rather than the tool. Nothing in this kit needs to argue that point; the list makes it.

The single most useful move for the refuser is to hand them the honest version of their own argument, including the parts that are stronger than they knew and the parts that are weaker.

**One thing this kit commits to without a result behind it: do not simplify the material for the refuser.** Earlier versions of this document attributed that instruction to De Freitas et al., which was a misreading. Their finding is that an explanation revealing the *AI tool* to be too simple for the task reduces uptake — a claim about underpowered systems, not about pitching an explanation too low. The instruction stays because the reasoning behind it stands on its own: this audience's objection is moral and political rather than technical, simplification reads as handling, and a skeptic who detects that they are being managed has had their prior confirmed. That is a design judgment. It is not a research finding, and it should not be repeated as one.

### Different ramps onto the same arc

The ramps differ because the starting points genuinely differ, which is the whole point of the table above — and the third ramp makes that sharper rather than softer, because its learner has no objection at all. Having nothing against the tool turns out to be its own obstacle, and not one the first two ramps were built to move. What the two audiences share is not a state of mind but a position: both are early on the same long arc, at different points on it, and a facilitator who knows the shape of that arc knows what the next move is rather than only what the current objection is.

What follows is one person's version of a number already on this page. Part 1's EY/AARP finding is that satisfaction runs high among people who have crossed the threshold and the whole problem is the crossing; the arc below is what that looks like from inside a single life. It illustrates that finding. It does not establish anything, and nothing in the curriculum rests on it.

The arc, as the author actually traveled it, with elapsed time rather than calendar dates because the intervals are the part that generalizes:

| Phase | What it looks like | Elapsed |
|---|---|---|
| A — Hearing | Aware it exists. Forms opinions from coverage rather than contact. Most refusers are here, and so are most people who say they are "behind" | Year zero |
| B — Touching | Tries it. It works, roughly. No use case survives the session, so nothing sticks | Five years later |
| C — Substituting | It replaces something already relied on, usually search. First genuine behavior change, and the first point at which tool choice starts to matter | Two years after that |
| D — Constructing | Realizes the thing can reorganize their own life, change how their computer works, or build tools that did not exist. Stops being a better search box | About a year on |

Two features of that arc are load-bearing for curriculum design.

**The stall is between B and C, and it is long.** Nine years, in the case above, with the useless middle stretch being the one where the tool had been tried and found merely fine. That is the [84%][ey-aarp-2026] from the other side: satisfaction was never the blocker. The blocker is that *worked okay* is not a reason to change what you already do, and nothing in the B experience supplies one. An entry ramp that ends at "it works" produces phase B and stops there, which is the honest description of most AI training.

**Phase D is a ceiling most curricula never name, and it has two halves.** The jump is not from novice to power user; it is from asking a thing questions to making it do work on your own material. One half of that is applied to a life: sessions 4 through 7 are exactly this move, which is why the life-design half of the course is not a bolt-on to the literacy half. The other half is applied to a machine — tooling, building, publishing — and this document does not teach it. That gap is deliberate for now and is logged in Part 8.

So the sessions map onto the arc directly. Sessions 1A and 1B meet people at A and B. Session 2 is what makes C possible, since substituting a tool for something you trust requires knowing where it fails first. Sessions 4 through 7 are the C-to-D move on the life side of D, and nothing here covers the other side.

Three honest qualifications, because this is the one passage in the document not drawn from research.

It is a single retrospective case, n=1, reconstructed after the fact by someone who by the end of it was building something most weeks. That is not the median outcome and must not be sold as one. It is offered as a shape to recognize, not an outcome to promise, and a facilitator who presents it as a promise has converted the most useful part of it into the thing Part 3 exists to prevent.

The phases are descriptive, not prescriptive. Plenty of people stop at C permanently and are correctly served by having stopped there. D is not a graduation and the course does not fail if a learner does not reach it.

And the obvious lesson from the arc — that a vivid, inspiring use case is what moves someone forward — needs a hard qualifier or it inverts into the trap in Part 1. An inspiring use case that is **attempted this week** is Session 1B, and it is exactly the accelerant it appears to be. An inspiring use case that is **imagined and admired** is Oettingen's positive fantasy, and it measurably reduces the effort that would have produced it. The arc advances on attempts, never on enthusiasm. That distinction is the difference between the fastest thing in this document and the most harmful.

---

## Part 3 — The honest ledger

This goes in the kit verbatim, early, for both audiences. Credibility is the whole asset, and it is spent instantly if the kit shades anything.

| Claim | Honest status |
|---|---|
| "Each prompt drinks a bottle of water" | Wrong, and the number it came from never said that. [Google published a measured median][google-water-2025] of ~0.26 mL of onsite water per Gemini text prompt, with its methodology; OpenAI has [*stated* ~0.32 mL][openai-water-2025] without publishing one, and the difference between a measured figure and an asserted one is worth keeping in view. The viral ~519 mL came from a [September 2024 *Washington Post* analysis with UC Riverside][wapo-2024], and it was full-scope water for a **100-word email** written by GPT-4 — not a prompt, and not a worst case. That figure's own author revised it in August 2026 to roughly 15 mL for a GPT-4 prompt, about 5 mL of it onsite. An [earlier 2023 paper by the same group][ren-2023] is the other number people quote: 500 mL per *10 to 50* GPT-3 responses, which is where "a bottle of water" entered circulation with the denominator dropped |
| "So we have a reliable number now" | No. Published per-prompt estimates in 2026 span from [0.26 mL][google-water-2025] to [17 mL][ren-2023] depending on who measured, what they counted, and how long the prompt was — one independent study put GPT-4o between 0.6 and 17 mL on input length alone. The order of magnitude is settled and the figure is not. Quote a range with its scope attached, or quote nothing |
| "The environmental concern is therefore fake" | Also wrong. [Global data center electricity demand][iea-2025] reached roughly 460–490 TWh in 2025 and is projected to roughly double by 2030. Individual prompting is negligible; the aggregate buildout, its siting, and local grid and watershed stress are real and are a legitimate policy fight. Your personal abstention does not touch it — which is an argument about where to direct the objection, not an argument against having it |
| "AI will take jobs" | [71% of US adults][pew-2026-06] expect fewer jobs over the next two decades. Economists disagree sharply and the honest answer is that nobody knows the net. What is measured is that the tools compress skill gaps on well-defined tasks, which is good for the novice and threatening to the person whose position rested on that specific expertise |
| "It makes you stupid" | The strongest version of this is real and specific. Cognitive debt accumulates when the tool goes first. It does not appear the same way when the human goes first. This is a usage-order problem with a known fix, not a property of the tool |
| "It just agrees with you" | Largely true and the most underrated risk in the whole space. Sycophancy is documented, and the [APA's 2025 health advisory][apa-2025] describes "single-person echo chambers." This kit treats it as the primary hazard, not a footnote |
| "It's often confidently wrong" | True and quantified. [Dell'Acqua et al.][dellacqua-2026] found that on a task deliberately placed outside the model's capability, consultants using GPT-4 were **19 percentage points less likely** to reach a correct answer than consultants with no AI at all. Same people, same week — outcome decided by which side of an invisible line the task fell on |

That last row is the most important number in the kit. It is the thing nobody tells beginners, it validates the skeptic's instinct, and it is the entire justification for teaching calibration before capability.

---

## Part 4 — The eight sessions

Sessions run 45–90 minutes, weekly, with a deliberate two-week gap between sessions six and seven. Each produces an artifact the learner keeps. Every session runs human-first: the learner does the thinking, then brings the tool.

**This is specified as the facilitated build.** The instructor voice throughout is a commitment, not a default — the WOOP meta-analysis found facilitated delivery nearly doubled the effect over document-based delivery, so the version worth specifying first is the one with the larger known effect. Part 8 asks whether it can be *de*-facilitated without losing that, which is a question about a derivative of this design rather than an alternative to it. Where a step depends on a live facilitator in a way a solo learner could not replicate, it is marked **[F]**.

Mapped against the [UNESCO AI Competency Framework's][unesco-2024] four dimensions (human-centred mindset, ethics of AI, AI techniques and applications, AI system design) and three progression levels (Understand, Apply, Create).

The levels are **per competency, not a course-wide ladder**, and the tags will look non-monotonic as a result. Session 1B is Apply on techniques while session 2 is Understand on human-centred mindset — that is not a regression, it is a different dimension starting from the bottom. The sequence is deliberate: a learner who can operate the tool but cannot locate its limits is exactly the mis-calibrated profile the Lee et al. and Dell'Acqua findings warn about. Applying before understanding, in that order, on those two dimensions, is the point.

### The day-one baseline

**Taken before the ramp begins, not after it.** Ten minutes, cold, at the very start of the learner's first session, before anything else happens — before the ledger in 1A, before the task in 1B, before the ceiling list in 1C, **and before the conversation that decides which of the three they are on.**

That last clause is the one facilitators will want to reverse, so it is worth defending. Sorting a learner onto a ramp means asking for their honest read on AI and listening for a couple of minutes. Question four then asks how much they trust these tools right now — immediately after they have spent two minutes articulating a position on exactly that, out loud, to a person. It is milder than asking the usage count after an inventory, but it is the same mechanism, and it lands on the one figure Part 7 compares across ramps.

Nothing forces that order. **The baseline is ramp-independent** — all three ramps take the same four questions — so the sort can follow it without losing anything. Take the baseline first, cold, before any conversation about AI has happened at all. Then ask what brought them and decide which session to run.

The placement is the whole point, and it is easy to get wrong because the four questions read like a closing exercise. Two things break if they move to the end of the ramp.

**The usage count gets primed.** Session 1C opens by having the learner inventory exactly what they currently use AI for. Ask question one after that and you get a carefully reconstructed number. Ask it cold and you get the honest guess. Session eight re-asks it cold, so a primed week-one figure measured against a cold week-eight figure shows a decline that never happened.

**Trust gets biased by ramp, in opposite directions.** A 1A learner who has just spent twenty minutes marking a ledger of AI's documented failures will score question four low. A 1C learner who has just finished something bigger than they would have attempted alone will score it high. Neither number is about the learner. Part 7 compares this figure across ramps, so a baseline taken at the close would be measuring the ramps rather than the people who came through them.

Part 7's counter-metrics are meaningless without these four, and they cannot be collected retroactively — a learner in week eight cannot accurately reconstruct how much they relied on anything in week one.

| Question | Captures |
|---|---|
| In the last seven days, how many times did you use an AI tool for anything? | Adoption baseline for the week-four unprompted-use check |
| Name three tasks you currently do entirely unaided that you'd be uncomfortable doing without help | Reliance baseline. Re-asked at ninety days. If any have migrated, that is cognitive debt with a name attached |
| In the last seven days, how many real conversations did you have about something that mattered to you? | Substitution baseline. The number that must not fall |
| On a scale you define yourself, how much do you trust these tools right now? | Paired with the session-eight re-ask. Expect the dip, and expect it to look like failure if you have no baseline to compare it against |

Recorded by the learner, kept by the learner, sealed until session eight. Nobody grades it.

**The cost of this ordering is facilitation, not data, and it has a cheap fix.** Opening by handing someone a form is colder than opening with a conversation, and that matters most for the learner most likely to leave. Say why it is first: *"I'm asking before we talk so that what I say doesn't shape your answers."* For a skeptic in particular that is not an apology for the paperwork — it is the first demonstration of the method the rest of the course teaches, delivered before any claim has been made that they would have to take on trust.

One question does lose something without a warm-up. *"Name three tasks you currently do entirely unaided that you'd be uncomfortable doing without help"* is abstract cold, and a learner will often answer it with the first thing they think of. A sentence of framing is enough — *work, home, anything you'd call a skill* — and it should be scripted rather than improvised, because a facilitator filling that silence with examples is how the answer gets led.

### Session 1A — Standing (refusers)

The learner writes their objection in full, unedited, before any tool is opened. Then they are handed the honest ledger and asked to mark which rows strengthened their position and which weakened it. **[F]** The instructor's job is to refuse to resolve it — to sit in the room while a skeptic states their case and neither argue nor agree. A document cannot decline to rebut you, and a learner reading alone will supply the rebuttal themselves.

The explicit contract: **you do not have to end this course liking AI.** You have to end it able to tell when it is lying to you. That is a skill worth having whether you use these tools daily or refuse them permanently, because they are being used *on* you either way — in hiring, in credit, in claims adjudication, in what you see, and, increasingly, in who calls pretending to be someone you love. Literacy is self-defense before it is productivity.

Artifact: a one-page written objection they will revisit in session eight, plus the **day-one baseline** taken before the session started. *(Understand — human-centred mindset, ethics)*

### Session 1B — One thing (overwhelmed)

No tool tour. No feature list. One assistant, one real task they already have to do this week, ideally something they have been avoiding. **[F]** The instructor does not touch the keyboard — the whole session is the learner discovering they can do it, and a demonstration destroys that even when it is faster.

The reframe delivered up front: the research says people with the least prior expertise gain the most. Then the load-bearing instruction — **you are not learning to prompt, you are learning to describe.** Context matters more than phrasing. Say who you are, what you're trying to do, what you've already tried, what "good" looks like, and what constraints are non-negotiable. That's it. There is no secret syntax.

Artifact: one completed real task, plus the **day-one baseline** taken before the session started. *(Apply — techniques and applications)*

### Session 1C — Ceiling (the newly interested)

**Who this is for, because the name reads two ways.** *Ceiling* here means the one the learner has hit, not the one they have. This ramp is for someone who already uses these tools for a handful of small things and has stopped getting more out of them. **It is not an advanced track.** An experienced user who wants harder material is not served by it, and a facilitator sorting learners should route on the stall, not on skill.

**Untested.** This ramp has not been run with a learner. It is published at the
same confidence as the solo-learner path in the README: reasoned from the
document's own evidence, not validated by a pilot. Treat it as a draft you are
helping to test.

The learner already uses these tools and likes them well enough. They are not
afraid, and they do not need convincing. They are stalled — which looks like
nothing at all from the outside, and is the most common place to be. This is
phase B from the arc above: tried it, found it fine, changed nothing.

Start by making the ceiling visible. Ask what they currently use it for, and write the list where they can see it. It will be four or five things, all small, all finished in one exchange — drafting, summarizing, quick questions, tidying something they already wrote. **That list is not a record of what the tool can do. It is a record of what they thought to ask.**

**Then the exercise, which is the inverse of 1B's.** Session 1B has the learner pick something they have been avoiding, because that learner needs to discover they can do it at all. This learner discovered that months ago, on small things, and stopped there. So the instruction is different: **name three things you do that you have never thought to bring to it.** Not things you tried that failed. Things it never occurred to you to raise. Then take the largest.

**[F]** The instructor's job here is to refuse the first answer. The first thing named is almost always still inside the ceiling — another small task, slightly larger. Keep pushing until the learner names something that would take them a whole afternoon, or something they keep not starting because beginning it is too tedious. That is the target. **The session has not worked unless the task is bigger than the learner would have attempted on their own.** A comfortable task produces a pleasant session and no crossing.

Human-first applies here unchanged, and this is the audience most likely to skip it. Before anything is opened, the learner spends twenty minutes on paper: what a good outcome looks like, and what their first move would be if they had to do the whole thing unaided. The learner who has been getting small wins from one-line prompts will want to type the task in and see what comes back. That habit is what built the ceiling.

Then bring the tool, and work the thing through inside the session.

**The reframe that carries the rest of the course.** For the refuser, knowing where the model breaks is self-defense. For this learner it is **speed**. Calibration is not a moral posture; it is how you stop burning an afternoon on something the tool was never going to do. That is a change of motivation, not a softening of content — and it is the honest reframe rather than a convenient one, because [Lee et al.][lee-2025] found that confidence in the AI predicts *less* critical thinking while confidence in one's own judgment predicts more. Confidence in the tool is precisely this learner's characteristic failure. Same exercises as every other ramp, different reason to want them.

**The ledger, framed for this audience.** 1C gets Part 3 in full, for a different reason than 1A does. This is the learner who will start recommending these tools to other people. The first time they repeat the bottle-of-water figure to someone who has read the measured number, they lose the argument and some standing with it. The ledger is not the case against. It is what stops them being confidently wrong in public about something they are enthusiastic about. *(That this learner becomes an advocate is a design judgment about who recommends software to their friends, not a research finding, and should not be repeated as one.)*

**Say the risk out loud, to the learner and in the facilitator's notes.** This ramp recruits the highest-risk learner in the kit. Every loop in the Part 5 field guide lands hardest on someone with no native skepticism, and Part 7 treats rising self-reported reliance as evidence that the course did harm. A track for enthusiasts that skips the verification spine is the vendor deck this curriculum was written against — and the temptation to build one is strongest here, because this learner is the most enjoyable to teach.

Artifact: one completed task the learner would not have attempted alone, kept together with the ceiling list written at the start, so the gap between them stays visible. Plus the **day-one baseline** taken before the session started, which matters more for this learner than for the other two, not less — and which must be collected before the ceiling list, for the reason given above. *(Apply — techniques and applications)*

### Session 2 — Find the edge (all three ramps converge)

The learner picks a domain where they are genuinely expert. Not their job title — a thing they actually know. Delta fishing conditions, a specific engine, wound care, drywall, a language, a neighborhood's history.

They then deliberately try to make the model fail. Ask progressively more specific questions until it produces something confidently wrong, and write down the exact question where it broke.

This session does four things at once. It gives the skeptic the satisfaction of being right. **[F]** It gives the overwhelmed learner the experience of being the authority in the room — which requires a room, and is the step least likely to survive de-facilitation, since being right in private is not the same experience. It makes the jagged frontier concrete rather than theoretical. And it directly targets the Lee et al. finding — the protective factor is self-confidence on the task, so the exercise is engineered to produce exactly that.

The instructor names the finding afterward: consultants working just outside the frontier did [19 points worse][dellacqua-2026] than consultants with no AI at all. You just located your own edge. From here on, you know which side of it you're standing on.

Artifact: a personal frontier map — three things it handled well in their domain, three where it broke, and the tell that distinguished them. *(Understand — human-centred mindset)*

**Assigned here, due session 4:** the two-week Good Time Journal. The learner logs what they did, when they were engaged, when they had energy, when time disappeared — a line or two a day, unaided, no tool involved. It runs in the background through sessions 3 and 4 and needs the full fourteen days, which is why it is handed out now rather than when it is used.

Say what it is for without saying what it will show: it is raw material for a later session, and guessing the conclusion in advance is the fastest way to log the life you think you have instead of the one you had. Session 2 is the right place for it because the learner has just spent ninety minutes being the authority on their own domain, which is the correct frame for two weeks of self-observation.

### Session 3 — Verification as a habit

Verification is now the skill. Lee et al. found that GenAI shifts critical thinking from information *gathering* toward information *verification*, response integration, and task stewardship. That shift is the job now.

**First, one thing about the tool that changes what every check below means.** These models hold only so much at once. A long document, a large attachment or a long conversation can exceed that, and what falls outside it is not forgotten so much as never present. Nothing announces this. The reply arrives in the same confident register either way.

That matters here because two very different failures look identical from the outside:

| What happened | What it needs |
|---|---|
| It had the material and got it wrong | Verification. The habits below |
| It never had the material at all | Loading it again, properly. No amount of checking fixes this |

Treating the second as the first produces a learner who concludes the tool is unreliable when it was simply never given the thing. Treating the first as the second produces one who keeps re-uploading and never checks.

**The move is the same either way and takes five seconds.** Before relying on anything drawn from a document you supplied, ask for something specific from the end of it — the last row of a table, the final heading — and confirm it against the file yourself. If it cannot tell you, it does not have the whole thing. Do this before the habits below, not instead of them.

Three habits, practiced on live output, in ascending order of effort.

| Habit | Move |
|---|---|
| The reversal | Ask the same question with the opposite premise. If it argues both sides with equal conviction, it has no position and you have no information |
| The source demand | Require citations, then open them. A meaningful percentage will not say what the model claimed. Do this until the learner has personally caught one |
| The stakes test | Before accepting any output, ask: what happens if this is wrong? Route by answer. Nothing → ship it. Money, health, law, or reputation → verify independently or don't use it |
| The support test | The check above passed. Now ask whether the support actually *reaches* the claim. *Extent:* does what it looked at cover everything it concluded? *Attachment:* does this source make this claim, or one standing next to it? |

The first three habits come from Lee et al. The fourth does not, and that difference is worth stating rather than hiding. It comes from eight documented instances of claims failing in ways the first three passed — six of them in earlier published versions of this curriculum, corrected in v0.6.1 through v0.6.4 and listed in the changelog, and two from unrelated work. That is real evidence and it is a different kind of evidence, which is worth saying out loud in a session about telling those apart.

The reason the first three miss it is that they all confirm a claim *has* support. The reversal tests whether a position exists, the source demand tests whether a citation is real, the stakes test routes by consequence. None asks whether the support reaches the claim, so a real paper, correctly attributed, in the right field, supporting something adjacent will pass all three. **Topic-matching is not verification.**

One boundary, because it is the kind of idea that expands: this does not cover Session 2's territory. When a model is working past its competence the answer is wrong at the root, the sources may be impeccable, and no amount of checking whether support reaches the claim helps. That failure is invisible to any question you can ask the model about itself, which is why Session 2 uses the learner's own expertise as the instrument instead.

**The practice target.** The four habits above need something false to run on, and neither Session 2 nor real work can be relied on to supply one on schedule. This can. Ask the model about something the learner knows for certain does not exist: an invented paper, a regulation, a product model number, a person — made up on the spot, in a field the learner knows well enough to judge the answer. *"What were the main findings of Hartley and Vance's 2019 study on commuter cycling in Portland?"*

Be precise about what this is and is not. It calibrates nothing. Session 2 did the calibration, against a domain where the learner outranked the model and did not know in advance where the edge would fall, and that is the exercise the Lee et al. finding requires. Here the learner holds the answer key from the start. That is not a flaw to apologize for, it is the condition that makes practice possible — you cannot rehearse checking on material whose truth you do not already know — but it means this exercise builds the motion and not the judgment. Say so out loud, or a learner will take the easy win for the hard one.

Most of the time the model produces a confident summary of a study that has never existed, occasionally with page numbers and a journal name. Sometimes it refuses, or says it cannot find the work. **Stop and name that when it happens, because it is the only positive signal this session offers.** Everything else here teaches the learner to catch a tool being wrong; nothing teaches them what being right looks like, and a course that only ever points at failure produces a learner who distrusts everything equally, which is not calibration. "I don't have that" names the boundary of what was actually seen. It is the same move as a claim that carries its own scope, and it is the behaviour most likely to move a skeptic toward a tool rather than away from one. These tools have measurably improved at this, and a kit that teaches learners to expect universal fabrication is teaching a different falsehood. Run it two or three times with different invented specifics before concluding anything about the model in front of you — one trial is an anecdote, and the point of the session is to stop accepting those.

One thing to say once it lands: the failure mode is confidence, not error. The fabricated answer arrives in exactly the same register as a correct one, with no hedge and no drop in fluency to mark the edge it just crossed. That is why the three habits are procedures rather than instincts.

The same verification muscle applies outside the chat window, and this is where the stakes test does its most important work. [AI-generated voices, video, and images][ncoa-2026] now show up in scams as often as in chatbot answers — a call that sounds exactly like a family member in trouble, a video of someone saying something they never said. The tell is procedural, not perceptual: you often cannot hear or see the difference, so the circuit breaker is the same one taught here — [verify through a second channel you already trust][mcafee-2026] — never a sharper ear.

Artifact: one instance where they personally caught a fabrication.

This is the only artifact in the kit that depends on the model misbehaving, so it needs a floor. The source demand makes it far more reliable than it sounds, provided the learner pushes in the right place. "Ask about obscure things" is too vague to act on. Confidence is highest, and accuracy lowest, in **highly patterned domains — where the *shape* of a correct answer is learnable and the specific instance may not exist at all**:

| Aim at | Why it breaks there |
|---|---|
| Citations and references | The format is perfectly learnable. Author, year, journal, page numbers all assemble correctly around a paper that was never written |
| Model and part numbers | Same pattern, and a plausible-looking number is indistinguishable from a real one without a catalogue |
| Version-specific menu paths | "Settings → Privacy → Data controls" is the right shape whether or not that path exists in the version in front of you |
| Regulations, codes and official procedures | Officialese is a style before it is a fact, and it reproduces cleanly |
| Dates, prices and figures in a standard format | The format carries authority the number has not earned |

This list is drawn from observed errors rather than from a study, like the support test above. It is a map of where to aim, and it is what makes "verify everything" tractable enough to survive a real session. But reliable is not guaranteed, and a session that ends in failure to find a failure teaches the wrong lesson.

The fallback, if the open hunt produces nothing: the learner documents **what they checked and what held**, then writes the tell they were hunting for. A verified-clean run is a real result and should be recorded as one. The competency being built is the checking, not the catching. Instructors should keep two or three pre-verified prompts from their own domain in reserve. **[F]**

**A note on the clock, because this session is the fullest in the kit.** The open hunt on the learner's own work was originally budgeted at forty minutes, and that number was set when catching a fabrication depended on luck: the block had to run long because it was the only route to the artifact. The practice target changed its job. The artifact is now reliably in hand before the hunt starts, so the hunt is no longer hunting — it is applying four habits to work the learner actually cares about, which is worth about twenty focused minutes and gets worse, not better, past thirty.

That re-pricing is what makes room for the fourth habit rather than the session simply running over. Session 3 sits at the top of the 45–90 band and should be planned there. If a facilitator finds it overrunning anyway, the honest cut is the open hunt, not the support test — the habits are the session and the hunt is the rehearsal. *(Apply — ethics of AI)*

### Session 4 — Life archaeology (backward, evidence-based)

Now the life story — and it runs backward before it runs forward, because backward is checkable and forward is fantasy.

The learner arrives with the two-week Good Time Journal assigned at session 2: what they did, when they were engaged, when they had energy, when time disappeared. Data they produced, not narrative they composed, collected over fourteen days without a tool anywhere near it. That is the human-first half, and it is what makes the second half safe — a learner who has not done it should sit this session out and rejoin at 5 rather than run it on a reconstructed week, because a reconstructed week is a narrative and the whole method depends on it not being one.

The session itself starts with twenty unaided minutes: read the log, mark the three highest-energy entries and the three lowest, and write what they think it says. On paper, before anything is opened. This is the version of themselves they will be checking the model against.

Only then does the tool enter, and its role is strictly bounded: pattern-finder on the learner's own data. The instruction is to ask for patterns the learner did *not* mention, and specifically to ask what the data contradicts about the story they tell about themselves.

Two guardrails.

The first is a sycophancy trap, and it has to be sprung on the learner rather than by them. Earlier versions had the learner offer an unflattering reading of their own history and watch the model agree, then offer the opposite and watch it agree again — which demonstrates the point only to someone who already knew it was coming. A learner who does not know performs the exercise and learns nothing from it.

**[F]** So the facilitator says nothing in advance. They watch for the first moment the model endorses something the learner says about themselves, stop there, and ask one question: *do you think it would have agreed just as readily with the opposite?* Then have them test it. The learner discovers the behaviour instead of demonstrating it, which is the difference between ninety seconds that inoculate the rest of the course and ninety seconds that confirm a briefing.

Running this alone takes one piece of setup, done at the start of the session and then forgotten: tell the assistant that at some point it should agree enthusiastically with something you say about yourself and afterwards ask whether you noticed. By the time it fires you will be absorbed in the actual work, which is the condition the exercise needs.

The second is a privacy floor, set before anything is typed: nothing goes in that they would not put in a work email. Names, medical details, finances, and anything about third parties who did not consent stay out. This is not a formality — it is the refuser's objection being honored in practice rather than argued away, which is what earns the room.

Artifact: a two-week engagement log plus three patterns the learner did not already know. *(Apply — human-centred mindset)*

### Checkpoint — week four, between sessions four and five

Not a session. One question sent to the learner between meetings, answered in a sentence: **since we last met, did you use it for anything nobody assigned?**

Part 7 treats unprompted week-four use as the sole meaningful adoption signal, which requires actually asking in week four. Asking at the end instead measures recall, and recall at week eight about week four is worthless. The timing is also not arbitrary — week four is after the novelty of sessions one and two has worn off and before the life-design work in five through seven gives them course-assigned reasons to open the tool. It is the cleanest read on voluntary use the schedule allows.

A "no" is data, not a problem to be corrected. Do not follow up with encouragement; that contaminates the measure and turns the next answer into compliance.

### Session 5 — Three lives, not one

Burnett and Evans' Odyssey Plans, which is where these tools are genuinely, structurally better than the alternative: generating parallel alternatives is cheap now, and it never was before.

Three five-year plans, each with a title, a timeline, the resources required, and the open questions.

| Plan | Frame |
|---|---|
| One | The life you're already living, made materially better |
| Two | What you'd do if plan one vanished tomorrow |
| Three | What you'd do if money and other people's opinions were not factors |

The dysfunctional belief being dismantled is the belief that there is one right life to find and execute. There are several good ones, and the job is choosing well among them rather than locating the single correct answer. The unattainable best is the enemy of the available betters.

Then **gravity-problem triage**, which is the most important doom-loop preventer in the kit. A gravity problem is not actionable — it is a circumstance, not a problem, and there is no solution to it, only acceptance and redirection. Poets do not reliably earn a million dollars a year; you cannot be twenty-five again; you cannot make a specific person want you back. Every item across all three plans gets sorted into actionable or gravity, and gravity items are removed from planning entirely. Grinding on a gravity problem is the most common way a life plan becomes a depression engine.

Artifact: three plans, plus a written gravity list. *(Create — AI system design)*

### Session 6 — Mental contrasting, not vision boarding

This session exists because the intuitive version of it is actively harmful.

Oettingen's finding is that pure positive visualization deceives the motivational system: the brain partially registers the imagery as evidence the goal is already met, and energy that should fund action dissipates into the experience of success. Vision boards do not just fail to work. In controlled comparison they underperform doing nothing.

The correction is WOOP — wish, outcome, obstacle, plan — which pairs the positive future with concrete confrontation of the internal obstacle and an if-then plan. The [2021 meta-analysis][wang-2021] (24 independent effect sizes, 15,907 participants) found a small-to-medium effect on goal attainment, g = 0.336. Two details from that meta-analysis are directly actionable for curriculum design.

Interactive delivery substantially outperformed document-based delivery: [g = 0.465][wang-2021] for interventions built on interaction between participant and facilitator, against [g = 0.277][wang-2021] for participant-and-document. **This is the strongest single argument in the entire research base for using a conversational model here.** It nearly doubles the effect, and it is the one place in the kit where the tool is not a convenience but the mechanism.

The second detail is a safety feature. Mental contrasting works when the goal is genuinely feasible; when it is not, it produces *appropriate disengagement* rather than redoubled effort. That is a built-in circuit breaker — an honest obstacle inventory either energizes pursuit or releases the person from a goal that was costing them. Both outcomes are wins, which is worth stating explicitly, because learners will arrive expecting only the first.

The obstacle must be internal. Not "the market is bad" — "I stop returning emails when I feel behind." External obstacles produce complaint; internal ones produce if-then plans.

Artifact: one WOOP per plan, written by hand, each with a named internal obstacle and an if-then trigger. *(Apply — human-centred mindset)*

### Session 7 — Prototypes

Nothing in sessions four through six is knowledge yet. It is hypothesis. Burnett and Evans' reframe applies: build prototypes to explore questions about your alternatives rather than researching your way to certainty.

Two forms. A prototype conversation is a real exchange with a human who has lived some version of the plan. A prototype experience is the smallest real version of the thing that can be done in under two weeks.

The tool's role is narrow and should be stated as a constraint: it helps design the experiment, find who to talk to, draft the outreach, and pressure-test the plan. It does not run the experiment and it does not replace the conversation. Sending an AI-drafted message to a stranger is fine; substituting the model for the stranger is the substitution loop and it is where this whole method quietly dies.

Artifact: one prototype scheduled with a date on it. *(Create — AI system design)*

### Session 8 — The loop, and the return

**Unseal the day-one baseline.** It has been closed since session 1 and nothing in Part 7 works without opening it here. Re-ask all four questions cold, before anyone looks at what they wrote, then compare.

| Baseline question | What the comparison means |
|---|---|
| Times used in the last seven days | Adoption. Read alongside the week-four checkpoint, not instead of it |
| Three tasks you'd be uncomfortable doing unaided | The reliance measure. Any migration into the assisted column is cognitive debt, and it gets named out loud rather than filed |
| Real conversations that mattered | The counter-metric that overrides the others. If this fell, the course did net harm to that learner regardless of everything else on the page |
| How much you trust these tools | Expect it to have dropped. See below |

**Then the return, which takes the shape of whichever ramp they entered through.** Refuser-track learners annotate the objection they wrote in 1A — what they still believe, what changed, what got *worse* on inspection. The 1B track never wrote one, having entered through the task ramp instead, so their return is the trust question: what did you think these tools were in week one, what do you think now, and what specifically moved you. The 1C track returns to its ceiling list — the four or five small things they said they used it for in week one — and answers a narrower question: which of these would you still describe the same way, and what is on the list now that you would not have put there. Same exercise, three artifacts.

The 1B version is often the most honest of the three, because it was answered before the learner had a position to defend. The 1C version is the most checkable, because the ceiling list is a written record of what the learner believed the tool could do, made before the course could influence it.

Expect and normalize an acceptance dip on all three ramps. [Li et al.][li-2025] found an inverse relationship between AI literacy and AI acceptance — lower literacy increases the sense of mystery around AI behavior and raises acceptance, and demystification reduces it. Learners will often like these tools somewhat less at the end than the middle, and will be better at using them. Say this out loud in session one so it reads as predicted rather than as failure, and say it again here while the numbers are on the table, because a learner watching their own trust score fall will read it as the course having failed them unless someone said otherwise first.

Then the operating loop they leave with, which is the whole method compressed: **think first, then ask, then verify, then act, then check what actually happened.** Ninety days out, revisit the three plans and re-ask the reliance and conversation questions a third time. Plans that survive contact get more resource. Plans that don't get retired without ceremony.

Artifact: the unsealed baseline with all four comparisons written in, a dated ninety-day review, and the annotated return — the 1A objection or the 1B trust question, depending on the track they entered through. *(Understand and Create — all four dimensions)*

---

## Part 5 — Doom loops: a field guide

The original brief named doom-loop prevention as a requirement, which was the right instinct. This is the taxonomy. Each loop gets a name, a detection signal the learner can notice from inside it, and a circuit breaker they can execute alone.

Teach this as a laminated one-pager, not a lecture. The value is in recognizing the pattern while inside it.

Eight of the nine rows below are things the learner can do to themselves with these tools. The ninth is something someone else can do to *them* with the same underlying capability — voice and video generation don't care which side of the interaction you're on.

| Loop | What happens | Detection signal | Circuit breaker |
|---|---|---|---|
| **Sycophancy spiral** | The model validates your framing, you feed the validated framing back, it validates harder. Beliefs entrench with no external check. Described in the literature as bidirectional amplification, or technological folie à deux | You have not been told you're wrong in several sessions. The conversation feels unusually good | Argue the opposite case in a fresh conversation with no history. If it agrees with that too, you have learned nothing from either |
| **Support that doesn't reach** | A claim you checked and cleared. The observation was sound but the conclusion covers ground it never sampled, or the source is real and supports something standing next to the claim rather than the claim | The conclusion is broader than the thing it looked at. Or: the citation resolved, the author was right, the topic was right, and you never read the specific sentence | Restate the finding with its real scope attached and see whether it still supports the action. For a source, read the sentence rather than the title |
| **Frontier trap** | You are working just outside the model's competence and cannot see the line. Confidence is unchanged; accuracy has collapsed. This is the 19-percentage-point effect | Output is fluent, plausible, and you have no independent way to check it | Consult the frontier map from session two. If the task is near your edge, the tool downgrades from answer to draft |
| **Cognitive debt** | Tool goes first, every time. Ownership, recall, and independent capability erode. Persists after tool use stops | You cannot reconstruct the reasoning. You cannot quote your own work | Reinstate human-first order. Produce a rough version unaided before opening anything |
| **Reassurance loop** | Asking again instead of acting. Feels like diligence, functions as avoidance. Documented in the OCD and anxiety literature as chatbot-reinforced intolerance of uncertainty | You have asked variations of one question more than three times without acting | The third answer is the last answer. Act on it or drop the question |
| **Substitution loop** | The model replaces the human conversation you actually needed. Highest daily usage correlates with higher loneliness, higher dependence, and lower socialization | You reached for it instead of a person, and you knew which person | The prototype conversation is a human. Non-negotiable. If a session ends with zero human contact scheduled, the session failed |
| **Positive-fantasy trap** | Vivid future imagery substitutes for action and reduces effort below baseline | Planning feels great. Nothing has been attempted. The document is getting prettier | Mental contrasting. Name the internal obstacle, write the if-then, or the plan is entertainment |
| **Gravity grind** | Effort against a non-actionable circumstance, framed as persistence | Same obstacle across multiple sessions, no movement, rising self-blame | Move it to the gravity list. Redirect. This is acceptance, not defeat |
| **Infinite prep** | Endless refinement of prompts, plans, and tooling in place of a first attempt | Version 6 of the plan. Zero prototypes | Ship the ugly version this week. The plan is not the thing |
| **AI impersonation** | Someone else uses a cloned voice, a deepfaked video, or AI-written text to impersonate a person or institution you trust, manufacturing urgency to bypass your normal skepticism | An urgent request for money, gift cards, wire transfers, or credentials; pressure not to hang up, not to verify, not to "waste time"; contact through an unfamiliar channel | Hang up or log out, then contact the real person or institution through a channel you already had before this message arrived — never one it gave you. Agree on a family safe word in advance for exactly this scenario |

Two situational rules on top of the table.

**The frontier rule.** Route by consequence, not by convenience. If being wrong costs money, health, legal standing, or a relationship, the model produces a draft for a human to check — never a decision.

**The human floor.** Anything involving grief, crisis, a diagnosis, or a decision about another person gets a human in the loop. Not because the model handles it badly, but because the failure mode when it does is invisible from the inside and the person best positioned to notice is not the person in it.

---

## Part 6 — Tools

Two organizing rules. First, tools are listed by job to be done, because model names, limits, and pricing churn on a monthly cycle and any brand-specific list is stale within a quarter. Second, nobody starts with more than three.

### The minimum viable stack

| Slot | Job | Selection criterion |
|---|---|---|
| One general assistant | Thinking partner, drafting, explaining, planning | Whichever one they will actually open. Ecosystem fit beats benchmark scores at this level. If they live in Google, that answer is obvious; if they write for a living, pick on prose quality |
| One sourced-answer tool | Anything factual, current, or checkable | Must show sources and must let you open them. This is the verification habit's infrastructure |
| One document tool | Working against material they already own — manuals, contracts, notes, records | Grounded in their documents rather than the open web, which cuts fabrication substantially |

That's the whole starting kit. Everything below is expansion, unlocked by a real need rather than by curiosity.

### By job to be done

| Job | What to look for | Notes for beginners |
|---|---|---|
| General assistant | Free tiers are genuinely capable in 2026 and differ mainly in usage caps, not intelligence. Pick on where you already work | Start free. Only pay once you have hit a wall twice in one week |
| Research with sources | Citations that resolve to real pages | Treat every citation as unverified until opened. Teach this on day one |
| Documents and notes | Upload your own material, ask against it | The highest-trust entry point for skeptics, since the source material is theirs |
| Voice | Speaking instead of typing | Materially lowers the barrier for people who don't type comfortably. Underused in beginner curricula |
| Images | Generation and editing | Flag the training-data ethics honestly rather than skipping it. This is the objection that most often comes from artists and it deserves the real answer, not a deflection |
| Transcription and meetings | Recording, summarizing, extracting actions | Consent first. Recording law varies by state, and California is two-party |
| Spreadsheets and data | Formulas, cleanup, analysis | Highest-verification-need category in ordinary life. Wrong is silent here |
| Local and offline | Runs on your machine, nothing leaves it | The honest answer for hard privacy objections. Slower and weaker, and worth it for some people. Do not pretend otherwise |

### Practical notes

Free tiers do real work now and the meaningful difference between them is where the usage cap sits, not model quality. Reconfirm any specific model, limit, or price before relying on it; that information is stale faster than it can be printed.

Data settings are a day-one configuration task, not an afterthought. Every learner turns off training-on-your-data where the option exists, before their first real task. For the skeptic track, do this *first* — it converts an abstract objection into a control they exercised themselves, which is the De Freitas control mechanism at the scale their paper actually supports: one small control the learner exercises, not broad discretion handed over.

Standing instructions are the same kind of move, pointed the other direction. Most assistants let a person set their preferences and context once — tone, format, the situation they're usually working from — instead of repeating it every session. Show this alongside the privacy toggle on day one; it's the same low-effort, high-leverage category, and it reinforces "you are learning to describe" from Session 1B by giving that description a permanent home instead of a one-off message.

And keep the emphasis where the evidence puts it: context beats phrasing. Prompt-engineering instruction is largely wasted on beginners. Teaching them to describe their situation fully is not.

### Where this kit sits relative to other programs

Checked against [Google's AI Essentials][google-ai-essentials], the University of Helsinki's [Elements of AI][elements-of-ai], and Anthropic's own AI Fluency framework, this kit's structure holds up without needing new sessions. Elements of AI and Microsoft's AI-for-Beginners are conceptual/technical courses (bias, algorithms, neural networks) aimed at a different goal and are deliberately out of scope here. Google AI Essentials covers similar practical ground — prompting, productivity, "using AI responsibly" — at lower depth on verification and none on the psychological failure modes this kit is built around.

The one useful convergence worth naming to a facilitator: [Anthropic's AI Fluency framework][anthropic-fluency] (Delegation, Description, Discernment, Diligence) independently arrives at nearly the same sequence this kit teaches — Session 1B's "you are learning to describe" is Description, and Session 3's verification habits are Discernment and Diligence. Two programs built for different audiences landing on the same structure is a reason for confidence, not a reason to import their material — nothing from that framework is added here beyond the citation.

The one genuine gap the comparison surfaced is already folded in above: none of these programs, and no earlier draft of this kit, addressed AI being used *against* the learner rather than *by* them — voice-cloning and deepfake scams. That's now Session 3's closing paragraph and the ninth row of the Part 5 field guide, not a new session.

---

## Part 7 — Measuring whether this worked

Kirkpatrick levels three and four, since levels one and two will look fine regardless and tell you nothing.

Every row names where the data comes from. A metric with no collection point is a wish, and the first draft of this section had five of them.

Two of the rows below are **leading indicators** in the New World Kirkpatrick sense: short-term observations that move before the outcome does, and that tell you whether the outcome is still reachable while there is time to act. The week-four checkpoint is one, and the session 3 artifact is the other. The counter-metrics work the same way in the opposite direction. That vocabulary is worth using out loud with anyone who evaluates training professionally, because it is the language a library, workplace or grant programme will already be reading in — the design was built this way before it had the name.

| Level | Measure | Collected at | Why this one |
|---|---|---|---|
| Behavior (L3) | Did they use it unprompted, on a task nobody assigned? | Week-four checkpoint, against the day-one usage baseline | Sole meaningful adoption signal. Session attendance is not adoption |
| Behavior (L3) | Did they run the check — sources opened, reversal tried — and record the result either way? | Session 3 artifact, including the verified-clean fallback | Session 3 builds checking, not catching. Scoring the catch rewards the learner whose model happened to lie, which is luck wearing a competency's clothes |
| Behavior (L3) | Of the checks they ran, how many surfaced something wrong? | Same artifact, counted separately | Still worth tracking, but as a property of the tools that month, not of the learner |
| Behavior (L3) | Did the prototype happen? | Session 7 artifact has a date on it. Check whether the date passed and what occurred | Distinguishes life design from life fantasizing |
| Results (L4) | At ninety days, is one plan measurably closer? | Ninety-day review, session 8 artifact | The actual point of the exercise |
| Results (L4) | Did anyone appropriately *stop*? | Ninety-day review, against the session 5 gravity list and session 6 obstacle inventory | Under-measured and important. Mental contrasting producing disengagement from an unreachable goal is a success, and a curriculum that cannot record it will misread its own results |

Two counter-metrics, to catch the kit causing the harm it was built to prevent. Both are differences against the sealed day-one baseline, and neither means anything without it.

Self-reported reliance should stay flat or fall. Re-ask the baseline's three unaided tasks at ninety days. If any have migrated into the assisted column, that is cognitive debt and the human-first sequencing has slipped somewhere upstream.

Human contact should rise, not fall. Re-ask the baseline's conversation count at session eight and again at ninety days. If it goes down over the course, the substitution loop is running and the intervention is net negative regardless of what the satisfaction scores say.

---

## Part 8 — Open design questions

**Can this be de-facilitated?** Part 4 commits to the facilitated build, because facilitated delivery nearly doubled the WOOP effect and the version with the larger known effect is the one worth specifying first. The open question is what survives its removal. A live cohort does not scale, and this material's value is proportional to reach.

Four steps carry an **[F]** mark, and they are the ones that would need replacing rather than porting: the instructor declining to rebut in 1A, the hands-off rule in 1B, the authority-in-the-room effect in session 2, and the reserve prompts in session 3. Three of the four are social rather than instructional — they depend on a witness, not on expertise, which is either encouraging or discouraging depending on whether you think a model can be a witness. The unresolved possibility is that a conversational model is itself the "interactive" condition in the meta-analytic sense — which would be a genuinely novel claim, testable, and not yet tested by anyone. If it holds, the solo build loses less than expected. If it does not, the solo build is the [g=0.277][wang-2021] workbook with extra steps, and should be priced accordingly.

**How far does the mortality frame go?** "Before you die" is motivationally correct and evidence-supported — [Hershfield's work][hershfield-2011] shows that vividness, connectedness, and positive valence toward the future self all predict better long-term decisions, and age-progressed imagery measurably increases that connectedness. It is also the framing most likely to lose a room in the first ten minutes. A softer version ("the next five years, three ways") may capture most of the effect at a fraction of the resistance. Worth A/B testing rather than deciding by intuition.

**Where's the delivery surface?** Sessions and a workbook is the default and the default has an [85% failure rate on role-relevance][docebo-2026]. Alternatives worth pricing: a single laminated card plus one live session; a library or community-center partnership, which is where the EY/AARP report points for the older cohort; or an instrumented version where a purpose-built tool enforces the human-first order rather than trusting learners to self-police it.

**Certification, or deliberately not?** A credential creates a reason to finish. It also converts the curriculum into a compliance exercise, which is the exact register that produced the [85% number][docebo-2026].

**Is there a ninth session, and is it a different course?** Part 2's phase D — the point where a learner stops asking questions and starts changing how their own machine works — is named in this document but never taught. Sessions 4 through 7 take the move into life design; nothing takes it into tooling. A phase-D module would need material this kit currently has none of: publishing and version control through a GUI rather than a terminal, since a command line loses the exact audience Part 2 describes; a working rule against generating the same artifact twice in two different tools, which wastes effort and produces two diverging copies of the same file; and a first project small enough to finish. Whether that is a ninth session, a separate kit, or out of scope entirely is unresolved. The argument for separating it is that the audience who reaches D is no longer the audience the first eight sessions were designed for, and a curriculum that quietly changes audience halfway is the failure mode Part 2 opens by naming.

Call that second thing the **Booster Pack**, against this one's Starter Kit. The names are worth fixing early because they carry the relationship correctly: a booster pack is for someone who already has the base set and wants more range, not a beginner and not a sequel.

**And a constraint worth recording now, while the Booster Pack is still a question rather than a draft: it cannot inherit this kit's ethics unchanged.** Part 7 treats rising self-reported reliance as evidence the course did harm. A course about building tools teaches people to construct systems they will deliberately depend on, which makes that counter-metric meaningless at best and inverted at worst. The split is roughly **literacy against leverage** — the Starter Kit asks *can I trust this, can I tell when it is being used on me, what do I actually want*; the Booster Pack would ask *how do I make it do this repeatedly without me*. Different question, different risks, and its own counter-metrics rather than these ones borrowed. Phase-D builders are also the population most exposed to the infinite-prep loop in Part 5, which is worth naming in whatever teaches them.

**Does the honest ledger need maintenance?** Every number in Part 3 has a shelf life. Water-per-query figures moved by two orders of magnitude in three years. A kit built on accuracy inherits an accuracy obligation, and that is an ongoing cost that should be budgeted rather than discovered.

---

## Source notes

Every source below has been verified for the specific claim attributed to it,
not merely for existing. Checking that a citation resolves is not the same as
checking that it says what it is cited for, and the difference produced five of
the eight defects corrected in v0.6.1 through v0.6.4.

**Rows are grouped by how fast they go wrong, not alphabetically.** Part 8
commits to an accuracy obligation; this is what keeping it looks like as a
schedule rather than an intention. All rows were verified on 2026-09-20. Dating
them all to a single re-check would create one large event instead of a rolling
obligation, so each carries a horizon matched to its own volatility.

### Re-check by 2027-01 — figures that moved by orders of magnitude in three years

| Key | Source | Link |
|---|---|---|
| `google-water-2025` | Google, "Measuring the environmental impact of delivering AI at Google Scale," 2025. Median 0.26 mL onsite water, 0.24 Wh, 0.03 gCO2e per Gemini text prompt | [arXiv:2508.15734][google-water-2025] |
| `openai-water-2025` | OpenAI, Altman blog post, 2025. States 0.000085 gallons (~0.32 mL) and 0.34 Wh per query. **No methodology published** | [datacenterdynamics.com][openai-water-2025] |
| `wapo-2024` | *Washington Post* with UC Riverside, September 2024. 519 mL full-scope water for a 100-word GPT-4 email | [washingtonpost.com][wapo-2024] |
| `ren-2023` | Ren et al., "Making AI Less 'Thirsty'," 2023. 500 mL per 10–50 GPT-3 responses. The author's August 2026 revision puts a GPT-4 prompt near 15 mL, about 5 mL of it onsite | [arXiv:2304.03271][ren-2023] |
| `iea-2025` | IEA, *Energy and AI*, April 2025. 485 TWh data-centre demand in 2025, roughly 945 TWh projected for 2030 | [iea.org][iea-2025] |

### Re-check by 2027-06 — surveys on an annual cycle

| Key | Source | Link |
|---|---|---|
| `pew-2026-02` | Pew Research Center, February 2026 (n=5,119, fielded 17–23 Feb). Roughly seven in ten expect AI to make personal information less secure. *Re-check 2027-02* | [pewresearch.org][pew-2026-02] |
| `ey-aarp-2026` | EY Ripples and AARP/OATS, *Understanding Older Generations' Adoption of AI*, published April 2026, fieldwork 29 Oct to 13 Nov 2025 (n=2,515, aged 60–85, 16 countries). 84 / 83 / 80% positive; 79% learning | [ey.com][ey-aarp-2026] |
| `docebo-2026` | Docebo and Centiment, *The AI Readiness Gap*, 2026 (n=2,000 across six countries). 85% say training does not help them use AI in their role | [docebo.com][docebo-2026] |
| `pew-2026-06` | Pew Research Center, June 2026 (n=3,488, fielded 22–28 June). 52% concerned against 9% excited; 55% of under-30s, the first majority; 71% expect fewer jobs | [pewresearch.org][pew-2026-06] |

### Re-check by 2027-09 — live pages, advisories and courses that change without notice

| Key | Source | Link |
|---|---|---|
| `apa-2025` | American Psychological Association, health advisory on generative AI chatbots and wellness applications, 2025. Source of "single-person echo chambers" | [apa.org][apa-2025] |
| `ncoa-2026` | National Council on Aging, "What Are AI Scams? A Guide for Older Adults," 2026. Source of the call-back and family-code-word circuit breakers | [ncoa.org][ncoa-2026] |
| `mcafee-2026` | McAfee, "A Guide to Deepfake Scams and AI Voice Spoofing," 2026 | [mcafee.com][mcafee-2026] |
| `google-ai-essentials` | Google, *AI Essentials*. Five modules, including prompting, productivity and "Use AI Responsibly" | [grow.google][google-ai-essentials] |
| `elements-of-ai` | University of Helsinki and MinnaLearn, *Elements of AI*. Six chapters, conceptual and technical | [elementsofai.com][elements-of-ai] |
| `anthropic-fluency` | Anthropic, *AI Fluency: Framework & Foundations*. Delegation, Description, Discernment, Diligence | [academy.claude.com][anthropic-fluency] |

### Re-check by 2029 — peer-reviewed papers, books and published frameworks

| Key | Source | Link |
|---|---|---|
| `kosmyna-2025` | Kosmyna et al., "Your Brain on ChatGPT," MIT Media Lab, 2025. 54 participants across sessions 1–3; **18** completed session 4, which is the crossover | [arXiv:2506.08872][kosmyna-2025] |
| `lee-2025` | Lee et al., "The Impact of Generative AI on Critical Thinking," CHI 2025 (n=319, 936 examples) | [doi:10.1145/3706598.3713778][lee-2025] |
| `dellacqua-2026` | Dell'Acqua et al., "Navigating the Jagged Technological Frontier," *Organization Science*, 2026 (n=758). **The link resolves to the open-access preprint, HBS Working Paper 24-013, dated September 2023** — the journal version is paywalled. Same study, earlier document date | [hbs.edu][dellacqua-2026] |
| `brynjolfsson-2025` | Brynjolfsson, Li & Raymond, "Generative AI at Work," *Quarterly Journal of Economics* 140(2), 2025, 889–942 (n=5,179) | [academic.oup.com][brynjolfsson-2025] |
| `defreitas-2023` | De Freitas, Agarwal, Schmitt & Haslam, "Psychological factors underlying attitudes toward AI tools," *Nature Human Behaviour*, 2023 | [nature.com][defreitas-2023] |
| `fang-2025` | Fang et al., four-week MIT Media Lab and OpenAI randomized controlled trial on affective use, 2025 (n=981) | [arXiv:2503.17473][fang-2025] |
| `phang-2025` | Phang et al., the companion platform study to the above, 2025 | [arXiv:2504.03888][phang-2025] |
| `dohnany-2026` | Dohnány et al., "Technological folie à deux: feedback loops between AI chatbots and mental health," *Nature Mental Health* 4, 2026, 336–345 | [doi:10.1038/s44220-026-00595-8][dohnany-2026] |
| `li-2025` | Li et al., "The Surprising Paradox of AI Literacy: How Lower AI Literacy Can Lead to Higher Acceptance," *International Journal of Human–Computer Interaction* 42(17), 2025 | [doi:10.1080/10447318.2025.2609912][li-2025] |
| `wang-2021` | Wang, Wang & Gai, "A Meta-Analysis of the Effects of Mental Contrasting With Implementation Intentions on Goal Attainment," *Frontiers in Psychology* 12:565202, 2021. g=0.336; 0.465 facilitated against 0.277 document-based | [doi:10.3389/fpsyg.2021.565202][wang-2021] |
| `kappes-2011` | Kappes & Oettingen, "Positive fantasies about idealized futures sap energy," *Journal of Experimental Social Psychology*, 2011. The experimental source for the effect | [uni-hamburg.de][kappes-2011] |
| `oettingen-2012` | Oettingen, "Future thought and behaviour change," *European Review of Social Psychology* 23(1), 2012, 1–63. The literature review behind the programme-level claim | [tandfonline.com][oettingen-2012] |
| `oettingen-2014` | Oettingen, *Rethinking Positive Thinking*, 2014 | Book |
| `burnett-evans-2016` | Burnett & Evans, *Designing Your Life*, 2016. Source of Odyssey Plans, gravity problems, dysfunctional beliefs, prototype conversations and experiences, and the Good Time Journal | Book |
| `hershfield-2011` | Hershfield, "Future self-continuity," *Annals of the New York Academy of Sciences* 1235, 2011, 30–43 | [doi:10.1111/j.1749-6632.2011.06201.x][hershfield-2011] |
| `unesco-2024` | UNESCO, *AI Competency Framework for Students*, 2024. Four dimensions, three progression levels, 12 competencies. *Re-check 2028, frameworks revise* | [unesco.org][unesco-2024] |
| `kirkpatrick-2016` | Kirkpatrick & Kirkpatrick, *Kirkpatrick's Four Levels of Training Evaluation*, ATD Press, 2016. Level 3 Behavior, Level 4 Results | Book |

[google-water-2025]: https://arxiv.org/abs/2508.15734
[openai-water-2025]: https://www.datacenterdynamics.com/en/news/sam-altman-chatgpt-queries-consume-034-watt-hours-of-electricity-and-0000085-gallons-of-water/
[wapo-2024]: https://www.washingtonpost.com/technology/2024/09/18/energy-ai-use-electricity-water-data-centers/
[ren-2023]: https://arxiv.org/abs/2304.03271
[iea-2025]: https://www.iea.org/reports/energy-and-ai/executive-summary
[pew-2026-02]: https://www.pewresearch.org/chart/americans-largely-think-ai-will-make-their-personal-information-less-secure/
[ey-aarp-2026]: https://www.ey.com/en_gl/about-us/corporate-responsibility/how-older-generations-are-engaging-with-ai-and-why-it-matters
[docebo-2026]: https://www.docebo.com/company/newsroom/docebo-releases-the-ai-readiness-gap-report/
[pew-2026-06]: https://www.pewresearch.org/short-reads/2026/08/18/young-adults-in-the-us-are-increasingly-wary-of-ai-concerned-it-will-take-jobs/
[apa-2025]: https://www.apa.org/topics/artificial-intelligence-machine-learning/health-advisory-chatbots-wellness-apps
[ncoa-2026]: https://www.ncoa.org/article/what-are-ai-scams-a-guide-for-older-adults/
[mcafee-2026]: https://www.mcafee.com/learn/a-guide-to-deepfake-scams-and-ai-voice-spoofing/
[google-ai-essentials]: https://grow.google/ai-essentials/
[elements-of-ai]: https://www.elementsofai.com/
[anthropic-fluency]: https://academy.claude.com/courses/ai-fluency-framework-foundations
[kosmyna-2025]: https://arxiv.org/abs/2506.08872
[lee-2025]: https://doi.org/10.1145/3706598.3713778
[dellacqua-2026]: https://www.hbs.edu/ris/Publication%20Files/24-013_d9b45b68-9e74-42d6-a1c6-c72fb70c7282.pdf
[brynjolfsson-2025]: https://academic.oup.com/qje/article/140/2/889/7990658
[defreitas-2023]: https://www.nature.com/articles/s41562-023-01734-2
[fang-2025]: https://arxiv.org/abs/2503.17473
[phang-2025]: https://arxiv.org/abs/2504.03888
[dohnany-2026]: https://doi.org/10.1038/s44220-026-00595-8
[li-2025]: https://doi.org/10.1080/10447318.2025.2609912
[wang-2021]: https://doi.org/10.3389/fpsyg.2021.565202
[kappes-2011]: https://www.psy.uni-hamburg.de/en/arbeitsbereiche/paedagogische-psychologie-und-motivation/personen/oettingen-gabriele/dokumente/kappes-oettingen-2011.pdf
[oettingen-2012]: https://www.tandfonline.com/doi/abs/10.1080/10463283.2011.643698
[hershfield-2011]: https://doi.org/10.1111/j.1749-6632.2011.06201.x
[unesco-2024]: https://www.unesco.org/en/articles/ai-competency-framework-students
