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
> "An app that helps people sleep better."

The skill picks a specific first user (e.g. shift workers vs new parents vs anxious overthinkers), narrows the MVP to one wedge — say, a 60-second wind-down ritual — defines the magic moment, lists non-goals, and hands you a build prompt. No 20-feature wellness dump.

**Scattered notes →**
> "An AI sales coach that listens to your calls, scores them, drafts follow-ups, syncs to the CRM, and trains new reps."

The skill picks the sharpest wedge (probably call scoring), separates what the agent does autonomously from what it suggests, adds a review/approval flow, and produces a launch plan aimed at one specific buyer instead of "all sales teams."

**Feature spec →**
> "Add a streak system to my habit tracker so users keep coming back."

The skill stays scoped to one feature, defines the user flow, the data model, the rules around streak freezes and timezone edge cases, and the failure states — instead of redesigning the whole app.

## Style

- Opinionated over open-ended
- MVP clarity over feature bloat
- Always names the riskiest assumption and the magic moment
- Avoids startup clichés and generic brainstorming
