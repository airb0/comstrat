# comstrat

A Claude Code skill for communication strategy. It turns raw client inputs into a Get-To-By creative brief with a real insight ("I want X, but Y"), builds the brand and product value proposition on Why-How-What, tests it with a message ladder, picks a leading + complementary brand archetype, and writes principles and tone of voice.

**[See the skill present itself →](https://tsytkin.com/tools/comstrat/)** — a page built by comstrat, about comstrat.

## Install

Copy `SKILL.md` and `rules/` into `.claude/skills/comstrat/` in your project, or into `~/.claude/skills/comstrat/` to use it everywhere.

```bash
git clone https://github.com/airb0/comstrat.git ~/.claude/skills/comstrat
```

## Use

Ask Claude Code in your own words, for example: *make a brief from these inputs*, *Get-To-By*, *write the value proposition*, *build the message ladder*, *pick the brand archetype*, *check our platform for holes*. It works in English and Russian.

## Files

| File | What it covers |
|---|---|
| `SKILL.md` | The tools, how to work, the non-negotiables |
| `rules/brief-get-to-by.md` | The Get-To-By brief and its open questions |
| `rules/insight.md` | "I want X, but Y" and its tests |
| `rules/value-proposition.md` | Brand and product CVP on Why-How-What |
| `rules/message-ladder.md` | The "so that" chain and break checks |
| `rules/archetypes.md` | Twelve archetypes, leading + complementary |
| `rules/principles-tone-visual.md` | Principles, tone of voice, visual principle |
| `rules/platform-structure.md` | Working order and presentation order |

## Sources

Simon Sinek, *Start With Why*; Margaret Mark and Carol S. Pearson, *The Hero and the Outlaw*.

## Licence

MIT — see [LICENSE](LICENSE).
