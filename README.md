# LLM Council

> Run any question, idea, or decision through a council of 5 AI advisors who independently analyze it, peer-review each other anonymously, and synthesize a final verdict.

Based on [Andrej Karpathy's LLM Council methodology](https://x.com/karpathy).

## How it Works

1. **Frame** — Your question gets enriched with workspace context
2. **Convene** — 5 advisors analyze independently in parallel (Contrarian, First Principles, Expansionist, Outsider, Executor)
3. **Peer Review** — Advisors review each other's work anonymously
4. **Synthesize** — A chairman produces the final verdict with agreements, clashes, blind spots, and a clear recommendation
5. **Report** — Visual HTML report + full markdown transcript

## The Five Advisors

| Advisor | Thinking Style |
|---------|---------------|
| **The Contrarian** | Finds what's wrong, missing, or will fail |
| **The First Principles Thinker** | Strips assumptions, rebuilds from ground up |
| **The Expansionist** | Finds upside everyone else is missing |
| **The Outsider** | Zero context, fresh eyes, catches curse of knowledge |
| **The Executor** | What do you do Monday morning? |

## Triggers

- `council this`
- `run the council`
- `war room this`
- `pressure-test this`
- `stress-test this`
- `debate this`

## Install

Copy `SKILL.md` to your Claude Code skills folder:

```bash
# Project-level
cp SKILL.md .claude/skills/llm-council/SKILL.md

# Global (all projects)
cp SKILL.md ~/.claude/skills/llm-council/SKILL.md
```

Or for [OpenClaw](https://openclaw.ai) users, place in your workspace `skills/` directory.

## Output

Every council session produces:
- `council-report-[timestamp].html` — Visual report for scanning
- `council-transcript-[timestamp].md` — Full transcript for reference

## When to Use

✅ Decisions with real stakes and trade-offs
✅ Multiple viable options where being wrong is expensive
✅ Ideas that need pressure-testing from different angles

❌ Factual lookups with one right answer
❌ Creation tasks (write me a tweet)
❌ Processing tasks (summarize this)

## Credits

- Methodology: [Andrej Karpathy](https://x.com/karpathy)
- Skill adaptation: [Bruno Okamoto](https://x.com/obrunookamoto)
- Source article: [Google Doc](https://docs.google.com/document/d/e/2PACX-1vSvw_Mk4iq4DkeMM3YVcvHgkzY-bsmnkXBC2TaEVBUDMjU4RtwDrKdxenpc-x7Vnzw5THGA4wVJd-LX/pub)

## License

MIT
