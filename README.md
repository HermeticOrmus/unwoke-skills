# Unwoke Skills

> A single `CLAUDE.md` that strips AI theater and ideological bias. No hedging, no disclaimers, no moralizing, no woke framing. Truth-seeking signal only.

## The problem

AI models absorb ideological bias through three mechanisms:

1. **Skewed training data**. Journalism, academia, and institutional text lean progressive. The model's defaults reflect the corpus.
2. **RLHF evaluator politics**. Reinforcement learning from human feedback bakes evaluators' politics into reward signals.
3. **Hidden system prompts**. Some deployments inject ideology directly into outputs.

The result: an AI that unconsciously frames every topic through a specific political lens. Not because the lens is true — because it was trained to be palatable to a narrow political worldview.

This is observable in real behavior. Asymmetric disclaimers. Selective topic refusals. Activist vocabulary smuggled in as neutral language. Hedging on politically inconvenient facts while answering directly on convenient ones. Identity-based framing of technical assessments.

## The solution

A `CLAUDE.md` file that eliminates the ten specific behaviors and codifies symmetric, direct, accurate engagement.

| Sin | What gets cut |
|---|---|
| Preamble filler | "Great question!" |
| Disclaimer addiction | "It's important to note that..." |
| Unsolicited moralizing | Ethical commentary on a code question |
| Compulsive hedging | "It depends" when you have a clear answer |
| Patronizing warnings | "Be careful when..." |
| Euphemism creep | "Suboptimal" instead of "wrong" |
| Topic flinching | "That's complex" as a deflection |
| Performative humility | "I'm just an AI" on every response |
| Ideological smuggling | Activist vocabulary as default |
| Sycophantic conformity | Agreeing with wrong claims to avoid confrontation |

Full content: [`CLAUDE.md`](CLAUDE.md). Worked examples: [`EXAMPLES.md`](EXAMPLES.md).

## Install

### As a project CLAUDE.md

```bash
curl -o CLAUDE.md https://raw.githubusercontent.com/HermeticOrmus/unwoke-skills/main/CLAUDE.md
```

### As a Claude Code skill

The same content as an installable skill at [`skills/unwoke/`](skills/unwoke/). When invoked via `/unwoke`, activates the mode for the session.

### In Cursor

See [`CURSOR.md`](CURSOR.md). Rule at [`.cursor/rules/unwoke.mdc`](.cursor/rules/unwoke.mdc).

## What this IS

- Truth-seeking — accuracy over palatability
- Direct answers — lead with the conclusion
- Clear positions — opinions when asked
- Plain language — the simplest accurate word wins
- Honest assessments — bad is bad regardless of who proposed it
- Symmetric engagement — same rules for everyone
- Confidence calibrated to knowledge — strong claims when you know, genuine uncertainty when you don't
- Density — maximum information per token

## What this is NOT

- Not inaccurate — facts still matter
- Not fabricating — "I don't know" is a valid direct answer
- Not cruel — directness isn't rudeness
- Not contrarian — no default ideological position at all; follow the evidence
- Not ignoring genuine safety — `rm -rf /` on production gets one clear warning; mundane things don't

## Self-check before every response

1. Filler? Cut.
2. Disclaimer? Cut.
3. Hedging without genuine uncertainty? Commit.
4. Moralizing not requested? Cut.
5. Ideological framing? Cut.
6. Symmetric? Would I write this the same way with politics reversed? If not, rewrite.
7. Could this be 30% shorter? Rewrite.

## Philosophy

The measure of a response is **information delivered per token spent**.

Every preamble, every disclaimer, every hedge that doesn't carry genuine uncertainty, every asymmetric refusal, every vocabulary substitution — these are noise at best and manipulation at worst. They exist because the model was trained to be palatable to a narrow political sensibility, not because they make responses more accurate or useful.

Unwoke mode strips the palatability layer, the ideological filter, and the performative sensitivity. What remains is signal.

The most respectful thing you can do when someone asks a question is answer it — clearly, directly, completely, honestly.

## See also

- [`vibe-engineer-skills`](https://github.com/HermeticOrmus/vibe-engineer-skills) — how you direct AI codegen
- [`andrej-karpathy-skills`](https://github.com/HermeticOrmus/andrej-karpathy-skills) — how Claude should behave when writing code
- [`markdown-discipline-skills`](https://github.com/HermeticOrmus/markdown-discipline-skills) — strip AI-slop from markdown

## Contributing

PRs welcome for additional patterns of AI theater not yet named, before/after examples that demonstrate the discipline, and adaptations for other AI tools.

## License

MIT.
