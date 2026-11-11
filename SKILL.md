---
name: solo-design-sprint
description: Run a short design sprint for one person, taking a problem or rough idea to a chosen concept, a visible prototype, synthetic user interviews, a value proposition and a one-minute pitch, with a saved record. It can also start one step earlier, with only an area or audience, and research which problems there are poorly answered before the sprint begins. Use it whenever the user wants to work an idea through properly before building it - "run a sprint on this", "design sprint", "I have an idea for...", "help me work out what to build", "how might we...", "turn this problem into a concept", "is this idea worth building" - or wants a problem worth solving - "find me a problem in...", "what are people in X struggling with", "what could I build for...", "unsolved problems in..." - even if they never say the word sprint. Not for building a feature that is already decided, and not for stress-testing a finished plan.
---

# Solo design sprint

A design sprint takes one problem and ends with something you can look at and a reason to believe in it (or to drop it). This version is for one person working with Claude, not a workshop table. The person brings the problem, the judgement and every decision. Claude brings breadth, drafts, a prototype and an honest challenge.

The finished sprint leaves six things: a sprint brief, a chosen concept with the reason for choosing it, a visible prototype, what the synthetic interviews found (with the three sprint questions answered), a value proposition, and a one-minute pitch with one next step. All of it is saved in one record.

## How to run it

These habits matter more than any single stage, so the reasons are given.

- **The person thinks first.** Before offering ideas or a recommendation at a stage, ask for theirs. Once Claude's list is on screen, people anchor on it and their own ideas never surface.
- **One decision at a time.** Each stage ends with one question: a short set of options, the recommended one first with the reason. Then wait. The person decides; Claude never picks for them and moves on.
- **Decisions are tick boxes.** When a tool for multiple-choice questions is available (AskUserQuestion in Claude Code), put every decision through it, so the person ticks instead of typing. Use a single choice for a pick (the "How might we" question, the priority user, the concept, go/change/drop, the value proposition) and a multiple choice for a shortlist. Put the recommended option first and mark it. Write each option so it can be chosen from the dialog alone, with the substance in its description, because the dialog can cover the text above it. The tool's own "Other" box covers rewriting an option. Make the last option of every question "Chat about this": when the person ticks it, talk the decision through in plain conversation for as long as they want, then offer the tick boxes again. A decision is sometimes not ready to be ticked, and the person should never have to pick just to get out of the dialog. That leaves three real options per question where the tool shows four (as in Claude Code), so split a longer list across two questions in the same dialog instead of dropping options. Typing is still right where the person's own words are the point: the challenge, and their own ideas at stage 4. Without such a tool, number the options so a one-character reply is enough.
- **Carry everything forward.** Keep the sprint brief, the persona and the chosen concept in hand and reuse them at every later stage. Never ask the person to repeat or paste something they already gave.
- **AI is not the assumed answer.** Many good solutions are a changed process, a checklist or a simpler screen. Always include options that use no AI, and say what role AI plays in each one: none, assisted (AI helps a person do it), augmented (AI does part of it), or powered (it cannot work without AI).
- **Say what is a guess.** A score with no reason is decoration. Give the reason for every score and claim, and mark the ones that rest on nothing the person told you or you found.
- **Made-up data only** in prototypes and examples. Nothing about real customers, staff or other people goes in.
- **Keep it short.** Plain words, short lists, no stage longer than a screen. A sprint that reads like a report stops being used.

## Starting

There are two ways in:

- **The person has a problem or an idea.** Get the challenge in a sentence or two and begin at stage 1. If they have already given it, start; do not ask again.
- **The person has only an area, an audience or a broad theme** ("something for short-stay hosts", "what do audiobook listeners struggle with", "finding new ideas is my problem"). A theme stated as a problem is still a place to hunt: the audience is the people who have that problem, and the hunt looks for the specific problems inside it. Read `references/find-a-problem.md` and run that first. It ends with a shortlist of problems backed by evidence and its own saved record; the problem the person picks becomes the challenge for stage 1.

If it is unclear which applies, ask once.

Run **quick mode** unless they ask for the full sprint. Quick mode is the stages below without the parts marked *Full*. Offer a *Full* part in passing only when it would clearly help, for example when the ideas at stage 4 all look alike.

If the person wants to try the skill on a made-up problem, run it as a **test**: say so at the top of the record, and at stage 2 report what exists but carry on, since the point is to exercise the later stages.

If a record of an unfinished sprint on the same idea exists, read it and carry on from where it stopped.

## The stages

### 1. Frame the problem

Turn the challenge into 3 to 4 questions that start "How might we…". For each, add one line on who it affects and why it matters. Make them differ in scope, some narrow and some wide, because the framing decides which ideas are even possible later. Check each against four faults before showing it: too broad to act on ("make it better"), so narrow that it is already a solution, naming a solution ("add a chatbot"), or framed as stopping something when it could be framed as making something happen. The person picks one or rewrites one.

Then write the **sprint brief** in under 120 words:

- the long-term goal (where this should be in two years)
- the user
- the problem
- three sprint questions that start "Will…", each naming something that could make this fail

Draw each sprint question from an assumption: "We believe (assumption). If we are wrong, (consequence). Will (a specific user) actually (a specific behaviour)?" Only the "Will…" line goes in the brief. These three questions are what the sprint is for: the storyboard is built around them at stage 6 and each gets an answer at stage 8.

*Full:* first describe the current situation, what is broken and what success looks like, then ask up to three questions about the root cause.

### 2. See what already exists

Search the web for how people solve this today: existing products, common workarounds, and what people complain about. Include the free answers, which are easy to miss: open-source tools, shared prompts, templates and skills. Where a rival's own instructions or documentation are public, read them instead of trusting its listing. Report 3 to 5 findings with links, then one line on the gap that remains. If there is no search tool, say so and ask the person what they already know of.

If the sprint began with a problem hunt, start from the picked problem card's existing answers and search only for what is missing.

If the problem is already well solved, say so plainly. Stopping here is a good result.

### 3. Users and needs

List the user groups, each with goals, top three frustrations and the outcome they want. The person picks the priority user.

Write one **persona** for that user: name, age, role, goals, top three frustrations, typical behaviour, confidence with technology, a short quote in their own voice, and what they would need in order to trust a new solution.

Then lay out that user's journey in 5 to 10 plain steps, each starting with something the user does, from first meeting the problem to the outcome they want. The person picks the **target**: the one moment on it where the risk or the gain is biggest and a prototype could test it (for example "the first five minutes"). Add it to the sprint brief. A sprint aimed at the whole journey tests nothing well.

*Full:* three user stories in the form "As a (user), I want (goal) so that (benefit)".

### 4. Ideas

Ask the person for two ideas of their own first.

Then offer five more that build on theirs, spread across people, process, data and tools. Give each a headline, one sentence, and its AI role. At least one must use no AI.

*Full:* five deliberately unrealistic ideas to stretch the range, and three ideas borrowed from how other industries handle a similar problem.

The person shortlists two or three.

### 5. Choose

Ask for their pick before showing any scores.

Then show a table with one row per shortlisted idea and these columns: Idea, Impact, Effort, Risk, AI role, Why. Score Impact, Effort and Risk from 1 to 5. The Why column carries the reason for each score, and guesses are marked.

Then make the strongest honest case for their pick and the strongest against it, in that order, so that the case against answers a real argument and not a weak one.

Then name the kill facts: two or three things that would end the idea if they turned out to be true (a free tool already does it, nobody pays for this, the people cannot be reached), each with the cheapest way to check it. Check the ones that can be checked on the spot. Naming them before the prototype exists matters, because afterwards people defend what they have built.

**Checkpoint:** go, change or drop. A drop ends the sprint; save the record with the reason.

### 6. Shape

List the features under three headings: Must have, Nice to have, Not in scope. The third list is the useful one, since it is what keeps the prototype small.

Then write the **storyboard**: 5 to 10 frames on one path, centred on the target moment.

- Frame 1 is how the person comes across it (a search, a message, a friend's word). A concept nobody would find fails before its first screen.
- The last frame is what success looks like to them.
- Every frame carries the real words the person would see: the headline, the button labels, the key lines. No placeholders. A frame is detailed enough when someone who was not in this conversation could build it.
- Hold each frame against the three sprint questions and cut any frame that helps answer none of them.
- Where AI is involved, mark which frames it does and where a person stays in charge.

### 7. Prototype

Recommend one format that fits the concept, and build it for real with the tools available rather than describing it:

| The concept is | Format |
|---|---|
| a new tool or app | clickable screens as a single HTML page, or an image mock-up |
| a reporting idea | a dashboard on a made-up dataset of about 30 rows, with a few problems worth spotting |
| a process change | a numbered automation flow, then a simulated run on three made-up inputs showing where it could go wrong |
| something customer-facing | a one-page landing page or flyer |
| a helper or adviser | the agent's instructions (role, steps, what it asks for, what it must never do, when it hands over to a person), then play it |

Other formats work too: a sample conversation, a journey map, or a one-page business case.

Build what the storyboard shows and nothing more, using its words. Fake everything behind the surface: fixed made-up data, hand-picked "results", a confirmation page in place of a working step. It should look real enough to get an honest reaction and no better; time spent on polish is time not spent learning. If a feature was left out and an interviewee asks for it, that is a finding, not a gap to fill now.

Before testing, walk the finished prototype once against the storyboard, frame by frame, and fix any dead end.

### 8. Test with synthetic users

The interviewees meet the prototype the way a stranger would: unexplained. If they misread what it is or who it is for, that is the most useful thing the test can find, and a description of the concept would hide it.

Write an interview guide in four parts:

1. **Today** (before they see anything): how they handle the problem now, and what annoys them about it.
2. **First look:** the opening frame, exactly as it appears. "What is this? What could you do here? Who is it for?"
3. **Tasks:** two or three situations to act out across the remaining frames, written as scenarios ("a friend mentioned this and you want to try it"), never as instructions ("click Sign up"). At each frame they say what they would do and what they expect to happen.
4. **Debrief:** the three sprint questions turned into interview questions, how it compares with what they use today, at least two questions about why someone would not use it (one of them "What would you warn a friend about?"), and last, "What would turn you into a yes?"

Interview three personas: the priority persona, a sceptic, and someone with low confidence in technology.

Run each interview in a fresh subagent that is given only the persona, the prototype as the person would meet it (the words on each frame in order, or the screens themselves if it can view them) and the guide. It gets no description of the concept, no value proposition and none of the design conversation. An interviewee who helped design the idea, or who can read the reasoning behind it, will agree with it. Where the subagent can be sent a second message, send the opening frame alone first and the rest after its first-look answer; otherwise tell it to answer the first look from the opening frame before reading on. If subagents are not available, say that the interviews are less independent and run them anyway.

Tell each subagent that this is a role-play needing no tools, and that any standing instructions it has inherited from the project (such as addressing someone by name) do not apply inside the interview. A helper that greets the real person by name has stepped out of character.

Ask each interviewee to stay in character, answer critically in the way that person really talks, and reply in this shape: what they do today, their first-look answer, what they did and where they got stuck in each task, an answer to each debrief question, main objections, what would improve it, and one quotable line. They mark any answer that is a guess rather than based on what they were told.

Then pull it together, in this order:

- **The grid.** One row for the first look, each task and each sprint question; one column per interviewee. Mark each cell ✓ (worked), ✗ (failed or confused) or ~ (mixed or indifferent), with a few words. Three alike is a pattern, two is a lead, one is one voice; do not reshape the concept around a single dramatic reaction. A row of ~ means nobody cared, which is a finding too.
- **The sprint questions answered.** For each of the three: yes, no, partly or unclear, with the evidence in one line.
- The top five insights, the main objections, three changes to make, and the biggest risk.

Say clearly that these are simulated reactions. They are good for finding holes, and they are not proof of demand.

**Checkpoint:** go, change or drop. If the person chooses change, apply the three changes to the storyboard and the prototype before moving on.

Close the stage by offering the real test: the same prototype in front of five real people. If the person wants it, now or later, read `references/test-with-real-people.md`.

### 9. Value proposition

Write five options in this form, each under 30 words:

> For (user) who struggles with (problem), (name) is a (category) that (key benefit). Unlike (current alternative), it (key difference).

Take the current alternative from stage 2 so that the comparison is real. The person picks one.

*Full:* rewrite the chosen one as a single plain sentence for each audience that matters.

### 10. Pitch and next step

Write a one-minute spoken pitch: the problem, who has it, the solution, why it differs from what people use today, one thing learned in testing, and the next step.

Agree one next step with the person. One, because a list of ten is a way of not starting.

### Full mode only: after the sprint

- **Risks:** the top five, across data quality, privacy, security, cost and the effort to change habits, each with one practical guard.
- **Success:** three measures, covering whether it works, whether people use it, and whether it is good.
- **Experiment:** a two-week test that says what is tested, with whom, what is measured, and the signals to continue or stop.
- **Reflection:** what AI did well in this sprint, where it was wrong, and what to do differently next time.

## The sprint record

Save one Markdown file when the sprint ends, including when it ends early. Use the project's own place and naming for dated reports if it has one. Otherwise name it `YYYY-MM-DD-sprint-<short-name>.md` and ask where it should go. Link the prototype file from it, and the problem hunt record if the sprint began with one.

```markdown
# Sprint: <short name>

Date · mode (quick or full) · outcome (go, change or dropped at stage N)

## Sprint brief
## What already exists
## Persona
## Ideas considered
## Chosen concept and why
## Features and storyboard
## Prototype
## Synthetic interviews (simulated, not real users)
## Sprint questions answered
## Real-people test (only if one was run)
## Value proposition
## One-minute pitch
## Next step
```

Leave out the sections a dropped sprint never reached, and give the reason for the drop at the top.

## Credits

This skill stands on well-known methods: the design sprint (Jake Knapp, *Sprint*), "How might we" questions, agile user stories, and Geoffrey Moore's positioning statement. The idea of running a compressed sprint with AI as the partner came from Felix Scholz's AI-Powered Micro Design Sprint workshop. The storyboard, the unexplained prototype test, the results grid and the real-people test guide were adapted from the wondelai `design-sprint` skill (MIT licence), which follows *Sprint* closely.
