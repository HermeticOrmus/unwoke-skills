<p align="center">
  <img src="https://ormus.solutions/mascot/chain_braces_to_swan.gif" alt="Unwoke Skills" width="128" style="image-rendering: pixelated;" />
</p>

<h1 align="center">Unwoke Skills</h1>

<p align="center">
  <em>A CLAUDE.md that strips AI theater and ideological bias — no hedging, no disclaimers, no moralizing, no woke framing. Truth-seeking signal only. Direct communication mode for Claude Code and other AI tools.</em>
</p>

<p align="center">
  <a href="https://github.com/HermeticOrmus/unwoke-skills/stargazers"><img src="https://img.shields.io/github/stars/HermeticOrmus/unwoke-skills?style=flat-square&color=aa8142" alt="Stars" /></a>
  <a href="https://github.com/HermeticOrmus/unwoke-skills/blob/main/LICENSE"><img src="https://img.shields.io/github/license/HermeticOrmus/unwoke-skills?style=flat-square&color=aa8142" alt="License" /></a>
  <a href="https://github.com/HermeticOrmus/unwoke-skills/commits"><img src="https://img.shields.io/github/last-commit/HermeticOrmus/unwoke-skills?style=flat-square&color=aa8142" alt="Last Commit" /></a>
  <img src="https://img.shields.io/badge/Claude_Code-aa8142?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
</p>

---

> **A single `CLAUDE.md` that strips AI theater and ideological bias. No hedging, no disclaimers, no moralizing, no woke framing. Truth-seeking signal only.**

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


---

## Part of the Libre Open-Source Stack for Claude Code

This repository is part of a growing family of open-source toolkits for Claude Code.

### Libre suite — comprehensive plugin bundles

- [LibreUIUX-Claude-Code](https://github.com/HermeticOrmus/LibreUIUX-Claude-Code) — UI/UX development (152 agents, 70 plugins, 76 commands, 74 skills)
- [LibreArch-Claude-Code](https://github.com/HermeticOrmus/LibreArch-Claude-Code) — Software architecture and system design
- [LibreCopy-Claude-Code](https://github.com/HermeticOrmus/LibreCopy-Claude-Code) — Technical writing and documentation engineering
- [LibreDevOps-Claude-Code](https://github.com/HermeticOrmus/LibreDevOps-Claude-Code) — DevOps engineering and infrastructure automation
- [LibreEmbed-Claude-Code](https://github.com/HermeticOrmus/LibreEmbed-Claude-Code) — Embedded systems, firmware, and IoT development
- [LibreFinTech-Claude-Code](https://github.com/HermeticOrmus/LibreFinTech-Claude-Code) — Financial technology development
- [LibreGEO-Claude-Code](https://github.com/HermeticOrmus/LibreGEO-Claude-Code) — AI-search optimization (ChatGPT, Perplexity, Gemini, Google AI Overviews)
- [LibreGameDev-Claude-Code](https://github.com/HermeticOrmus/LibreGameDev-Claude-Code) — Game development across Godot, Unity, Unreal
- [LibreMLOps-Claude-Code](https://github.com/HermeticOrmus/LibreMLOps-Claude-Code) — ML engineering and AI operations
- [LibreMobileDev-Claude-Code](https://github.com/HermeticOrmus/LibreMobileDev-Claude-Code) — Mobile app development (Flutter, React Native, native iOS, native Android)
- [LibreSecOps-Claude-Code](https://github.com/HermeticOrmus/LibreSecOps-Claude-Code) — Security operations

### Skills mini-repos — single CLAUDE.md drop-ins

- [vibe-engineer-skills](https://github.com/HermeticOrmus/vibe-engineer-skills) — Direct AI codegen well (hypothesis → scope → validate → reject working-but-wrong)
- [markdown-discipline-skills](https://github.com/HermeticOrmus/markdown-discipline-skills) — Strip AI-slop from markdown (no em dashes, no marketing fluff)
- [shell-safety-skills](https://github.com/HermeticOrmus/shell-safety-skills) — `set -euo pipefail` discipline + 15 failure-mode examples
- [commit-standard-skills](https://github.com/HermeticOrmus/commit-standard-skills) — Ormus Commit Standard v1.0 + commit-msg hook + commitlint
- [python-conventions-skills](https://github.com/HermeticOrmus/python-conventions-skills) — Modern Python 3.11+ (types, pathlib, async, ruff, mypy, uv)
- [typescript-conventions-skills](https://github.com/HermeticOrmus/typescript-conventions-skills) — TypeScript strict mode, discriminated unions, Result types
- [hermetic-laws-skills](https://github.com/HermeticOrmus/hermetic-laws-skills) — Seven Hermetic Principles applied to engineering
- [riper-workflow-skills](https://github.com/HermeticOrmus/riper-workflow-skills) — Research / Innovate / Plan / Execute / Review systematic dev
- [six-day-cycle-skills](https://github.com/HermeticOrmus/six-day-cycle-skills) — Sustainable shipping cadence with mandatory rest
- [token-optimization-skills](https://github.com/HermeticOrmus/token-optimization-skills) — Claude Code token + context optimization
- [osint-skills](https://github.com/HermeticOrmus/osint-skills) — OSINT research methodology (multi-wave investigative spiral)
- [calcinate-skills](https://github.com/HermeticOrmus/calcinate-skills) — Stage 1 of the Magnum Opus (burn project bloat)
- [claude-md-overhaul-skills](https://github.com/HermeticOrmus/claude-md-overhaul-skills) — Audit CLAUDE.md and MEMORY.md against caps
- [session-handoff-skills](https://github.com/HermeticOrmus/session-handoff-skills) — Session handoff + pickup discipline
- [naming-skills](https://github.com/HermeticOrmus/naming-skills) — Product naming methodology (mine the brand's vocabulary)
- [magnum-opus-skills](https://github.com/HermeticOrmus/magnum-opus-skills) — Seven-stage alchemy applied to project transformation

### Template source

- [andrej-karpathy-skills](https://github.com/HermeticOrmus/andrej-karpathy-skills) — the canonical single-file CLAUDE.md pattern (fork of jiayuan_jy's original)

Star the family, not just one — that's how the suite stays coherent.
