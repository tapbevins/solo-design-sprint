# Find a problem

The front part of the sprint, for when the person has an area or an audience in mind but no problem yet. It ends with a shortlist of problems backed by evidence, and the person picks one to take into stage 1.

## What this can and cannot show

Web research finds problems that people describe in public. It can show signs that a problem is poorly answered: repeated complaints, weak existing tools, home-made workarounds. It cannot prove that a problem is unanswered or measure how many people have it. Say this to the person once, at the start, so the shortlist is read as leads worth a sprint and not as market research.

## Evidence rules

These apply to every step, because a discovery report is only as good as its weakest claim.

- Mark each fact as **read** (seen on a page, with its link and date) or **guess**.
- Quote people's own words. A complaint rewritten into a tidy problem statement loses the detail that makes it believable.
- Give no search volumes, market sizes or user counts unless a source states them, and name the source.
- Note the date of each complaint. An old complaint may have been solved since.
- If a source could not be read, say so. "Not found" does not mean "not there".
- Say how each quote was seen: the page's exact words, a tool's summary of the page, or a search-result snippet. Only exact words count as a quote.
- Before building the shortlist, check a few of the quotes it will rest on against their sources yourself. Helpers read fast and sometimes tidy a quote or take a summary for the page.

## The steps

### 1. Brief

Get four things, asking only for what is missing, in one round:

- the **area or audience** (for example "people who run short-stay rentals", "home audiobook listeners")
- the **kind of thing** the person would build: a site, an app, a service, a tool, a guide
- their **limits**: time, money, and what they know how to do
- what would make it **worth it** for them: income, an audience, solving their own itch

Take the area as the person gives it. A broad theme such as "finding new ideas" is an area: the audience is whoever has that problem. Do not swap it for areas of your own choosing. If the other three are missing, assume sensible defaults, say what they are in one line, and start; the person can correct them while the sweep runs.

If the person has no area at all, do not hunt across everything; the results are shallow and they cannot judge them. Ask about their work, their hobbies and the communities they already belong to, and suggest two or three areas from that. People judge problems best in worlds they know.

### 2. Plan the sweep

List five to eight specific places where this audience talks or complains, drawn from these types:

| Source type | What it shows |
|---|---|
| Forums and community threads | problems in people's own words, and how often they recur |
| Low-star reviews of existing products | what the current answers get wrong |
| "Alternative to X" searches and comparison threads | people already looking to leave a tool |
| Questions with no accepted or useful answer | demand nobody has met |
| Templates, spreadsheets and scripts shared or sold as workarounds | effort people spend because no proper tool exists |
| Paid help: freelance jobs, agencies, courses | money already being spent on the problem |

Show the list and ask whether the person knows other places. They often know the communities better than a search does.

### 3. Sweep

This step is reading, not judgement. If helper agents are available, give each one a source type and run them side by side on a cheaper model; each returns problem cards and nothing else. Without helpers, work through the sources in turn.

Read what is public. Do not log in, do not get round a block, and stop reading a site that refuses automated visits.

### 4. Problem cards

Aim for a long list of 20 to 30 cards. Merge cards that describe the same problem, and keep the count of separate mentions, since several unconnected people describing one problem is itself evidence.

```markdown
**<Problem in one plain line>**
- Who has it:
- In their words: "<quote>" (link, date)
- How they cope today:
- Sign of money or effort spent:
- Existing answers and what is wrong with them:
- Mentions found: <number>, most recent <date>
```

### 5. Quick kill

Drop a card when any of these is true, and list each dropped card with a one-line reason so the person can rescue one:

- **Already well answered.** A good, affordable solution exists and people recommend it.
- **No sign of spend.** Nobody is paying, building workarounds or putting in effort; people grumble and move on.
- **Out of reach.** The person has no realistic way to get in front of these people.
- **Outside the limits.** It needs more time, money or know-how than the brief allows.

Signs that a problem is poorly answered, worth pointing out on the cards that survive: the same question asked again and again with no good reply; old threads still collecting "any update on this?"; one dominant tool with consistent complaints; workarounds passed around as spreadsheets or scripts; people paying for manual help.

### 6. Shortlist

Before recommending anything, show the surviving cards and ask which ones stand out to the person. Their own knowledge of the area counts for more than a score.

Then, for each problem headed for the shortlist, run one search for an existing answer to its specific gap, free ones included (open-source tools, shared prompts, templates, skills). The sweep finds complaints, and complaints lag behind the fixes; a problem can look open in forum threads from last year and be closed by something released since.

Then give three to five in a table, with a recommendation:

| Problem | Who | Evidence | How they cope | Sign of spend | Can you reach them | Fit with your limits | Why it is here |
|---|---|---|---|---|---|---|---|

Mark guesses in every cell that holds one. The person picks one, or sends the hunt back to the sweep with a narrower area.

### 7. Save and hand over

Save the hunt as its own record, then stop. The sweep is slow, and a fresh look at the shortlist another day is worth having. Use the project's own place and naming for dated reports if it has one; otherwise name it `YYYY-MM-DD-problem-hunt-<area>.md` and ask where it should go.

```markdown
# Problem hunt: <area>

Date · brief (area, kind of thing, limits, what makes it worth it)

## Shortlist
## Picked
## All problem cards
## Dropped, with reasons
## Sources read, and sources that could not be read
```

When the person is ready, start the sprint at stage 1 with the picked card as the challenge. The card's quotes become the raw material for the "How might we" questions and the persona. Stage 2 then starts from the card's "existing answers" and searches only for what is missing.
