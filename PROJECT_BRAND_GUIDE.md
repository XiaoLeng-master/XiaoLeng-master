# XiaoLeng Open-Source Project Brand Guide

This guide keeps XiaoLeng's public projects recognizable, honest, and easy to
use. It is a working system rather than a decorative style sheet.

## Positioning

**Identity:** Full-stack Developer · AI Native Builder  
**Tagline:** Build with AI, ship to the real world.  
**Promise:** Prefer evidence, evaluation, and real delivery over impressive but
unsupported claims.

## Visual system

### Palette

| Role | Color | Hex |
| --- | --- | --- |
| Ink | Near black | `#111827` |
| Canvas | White | `#FFFFFF` |
| Glacier | Pale ice blue | `#DCEEFF` |
| Primary | Cobalt blue | `#2563EB` |
| Accent | Blue violet | `#6366F1` |
| Boundary | Deep navy | `#172A46` |

Use black and white as the base. Glacier blue creates recognition; cobalt and
blue violet are accents, not full-screen neon effects.

### Symbols

- ❄️ XiaoLeng identity and project-family marker
- 🤖 AI Agent and Agent Skill
- 🛠️ building and delivery
- 🧪 evaluation, experiments, and evidence
- 🚀 deployment and release

Do not use every symbol at once. Prefer one identity symbol plus one
task-specific symbol.

## Social preview

- Size: `1280 × 640`
- Keep the project name readable at small link-card size.
- Use one value statement, not a feature list.
- Preserve generous negative space.
- Use the same palette across projects.
- Add `XiaoLeng Open Source` as a small family signature.
- Avoid technology-logo walls, fake metrics, and dense screenshots.

## README order

1. Project name and language switch
2. Current release or maturity label
3. One-sentence value proposition
4. Demo or workflow
5. Core modes/capabilities
6. Quick start
7. Evidence and evaluation
8. Known limits and safety boundaries
9. Roadmap
10. Contributing
11. Support / Star call to action
12. License

## Bilingual navigation

Use one primary language per file:

```markdown
[English](README.md) · [简体中文](README.zh-CN.md)
```

Do not alternate languages paragraph by paragraph. English copy should be
rewritten for clarity rather than translated word for word.

## Release notes

Every release should state:

- What is included
- How to install or verify
- What changed
- Known limits
- Safety or truthfulness boundaries
- Where to report failures

A release must point to a real tag. Never use adoption numbers or success rates
without a reproducible source.

## Roadmap

Separate roadmaps into:

- `v0.1.x`: fixes, documentation, validation, and installation experience
- `v0.2.0`: the next coherent product capability
- `Future`: directional ideas without delivery promises

Planned validation is not completed evidence. Use explicit labels.

## Support language

Preferred call to action:

> If this project helped you complete a real task, consider starring it to
> follow future releases. If it failed, report the failure—real counterexamples
> are more useful than empty metrics.

Do not ask for stars before explaining user value. Do not use follow-for-follow,
star exchanges, purchased engagement, or automated interaction.

## Truthfulness rules

- Separate verified facts, inferences, conflicts, and unknowns.
- Do not invent users, customers, ownership, production status, benchmarks, or
  business impact.
- Label manual evaluation as manual evaluation.
- Date time-sensitive sources.
- Publish failed and partial results when they materially affect conclusions.
- Treat confidence as a communication property, not evidence.

## Repository checklist

Before calling a public project ready:

- [ ] Clear About description and Topics
- [ ] Social preview
- [ ] Quick start
- [ ] CI or reproducible validation command
- [ ] Release and tag
- [ ] Roadmap
- [ ] Contribution guidance
- [ ] License
- [ ] English and Chinese entry points when relevant
- [ ] No unsupported metrics or claims
