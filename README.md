# Solo design sprint

A skill for Claude Code that runs a short design sprint for one person. You bring a problem or a rough idea; you leave with a chosen concept, a prototype you can look at, simulated user interviews, a value proposition and a one-minute pitch, all saved in one record.

It can also start a step earlier. Give it only an area or an audience and it researches which problems there are poorly answered, then you pick one to sprint on.

**Status:** early. It has been through a handful of runs and is being fixed as it is used. Expect rough edges.

## Install

```
npx skills add tapbevins/solo-design-sprint --global
```

Restart Claude Code afterwards.

## Use

Type `/solo-design-sprint`, or just say what you want:

- "Run a sprint on this idea: …"
- "Is this idea worth building?"
- "Find me a problem in short-stay hosting"

## How it works

You make every decision; Claude drafts, searches, builds and argues back. Most decisions are tick boxes.

| Stage | What happens |
|---|---|
| 1. Frame | "How might we" questions, a short brief, three questions the sprint must answer |
| 2. What exists | A web search for how people solve this today, free answers included. Stopping here is a good result |
| 3. Users | A persona, and the one moment on their journey to aim at |
| 4. Ideas | Yours first, then more. At least one uses no AI |
| 5. Choose | Scores with reasons, the case for and against, and the facts that would kill the idea |
| 6. Shape | What is in and out, and a storyboard with real words |
| 7. Prototype | Built for real: screens, a dashboard, a flow, a landing page or an agent |
| 8. Test | Three simulated users meet the prototype unexplained. The three sprint questions get answers |
| 9. Value proposition | Five options, you pick one |
| 10. Pitch | One minute, and one next step |

There are two stop points (after stages 5 and 8) where the answer can be go, change or drop.

The simulated interviews find holes; they are not proof of demand. A guide for testing with five real people is included for when you want real evidence.

## Credits

Built on well-known methods: the design sprint (Jake Knapp, *Sprint*), "How might we" questions, agile user stories and Geoffrey Moore's positioning statement. The idea of a compressed sprint with AI as the partner came from Felix Scholz's AI-Powered Micro Design Sprint workshop. The storyboard, the unexplained prototype test, the results grid and the real-people guide were adapted from the wondelai `design-sprint` skill (MIT).

## Licence

MIT. See [LICENSE](LICENSE).
