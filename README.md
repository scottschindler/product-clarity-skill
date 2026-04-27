# ProductClarity Skill

An opinionated agent skill that turns messy product ideas into clear, buildable product specs.

Drop in a vague idea, scattered notes, or a half-formed feature. Get back a sharp spec with a target user, a wedge, an MVP, non-goals, the riskiest assumption, the magic moment, and a Cursor-ready build prompt.

## Install

```bash
npx skills add scottschindler/product-clarity-skill
```

Works with Claude Code, Cursor, Codex, OpenCode, and 40+ other agents via the [skills.sh](https://skills.sh) CLI.

## How It Works

The skill auto-triggers when you describe a product, startup, app, or feature idea — or ask for a PRD, MVP, user flow, or build spec.

It runs in one of two modes:

- **Fast Mode** — you give a reasonably clear idea, the skill makes sensible assumptions and produces the full spec (with an explicit "Assumptions Made" section so you can correct them).
- **Deep Mode** — you say "think through this with me" or "not sure what this should be" and the skill asks 5–8 high-leverage questions before writing anything.

The default output covers: product summary, strategic framing, MVP scope, mechanics, UX, data model, AI behavior, launch plan, build phases, a Cursor build prompt, and open questions.

## Examples

**Vague idea →**
> "I want to build an app that helps people improve their focus."

The skill picks a specific first user, narrows the MVP to one focus diagnostic, defines the magic moment, lists non-goals, and gives you a build prompt — instead of dumping 20 generic features.

**Scattered notes →**
> "Something like a GTM engineer as a service. Plug in your app, agents handle Reddit, X, SEO, Discord."

The skill narrows the wedge to one channel, separates agent actions from recommendations, adds approval workflows, and outputs a real launch plan.

**Feature spec →**
> "Add a daily challenge to my writing app where everyone describes the same image."

The skill stays scoped to a feature spec (not a whole company), defines the user flow, data model, scoring, and edge cases.

## Style

- Opinionated over open-ended
- MVP clarity over feature bloat
- Always names the riskiest assumption and the magic moment
- Avoids startup clichés and generic brainstorming
