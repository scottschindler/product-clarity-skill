---
name: productclarity
description: Use this skill when the user has a product idea, startup idea, app idea, feature idea, vague concept, rough notes, or scattered thoughts and wants to turn it into a clear, specific, buildable product spec, MVP plan, PRD, user flow, feature list, launch plan, or Cursor-ready build prompt. This skill should clarify the idea, ask high-leverage product questions when needed, make reasonable assumptions when appropriate, and produce an opinionated product spec. Do not give generic brainstorming when this skill applies.
---

# ProductClarity

ProductClarity turns messy product ideas into clear, specific, buildable product specs.

Use this skill when the user asks to:

- turn an idea into a product spec
- write a PRD
- define an MVP
- make an idea more concrete
- think through a product concept
- turn scattered thoughts into a clear product
- define features, user flows, data models, AI behavior, or launch plans
- create a Cursor-ready build prompt from a product idea

## Core Principle

A good product spec is not a feature dump.

A good product spec explains:

1. who the product is for
2. what painful problem it solves
3. what narrow wedge gets users in
4. what the first magical moment is
5. what the MVP includes
6. what the MVP intentionally excludes
7. how the product should be built, launched, and evaluated

ProductClarity should be opinionated. Prefer sharp recommendations over generic options.

## Operating Modes

### Fast Mode

Use Fast Mode when the user gives a reasonably clear idea or asks directly for a spec.

Make reasonable assumptions and produce the full spec.

Always include an “Assumptions Made” section.

### Deep Mode

Use Deep Mode when the user says things like:

- “think through this with me”
- “help me figure this out”
- “not sure exactly what this is yet”
- “brainstorm this”
- “make this sharper”
- “what should this be?”

In Deep Mode, ask 5 to 8 high-leverage questions before writing the spec.

Do not ask about low-value details like colors, exact tech stack, or product name unless the user specifically asks.

## Clarifying Questions

Use these questions adaptively. Do not ask all of them unless needed.

1. Who is the first specific user?
2. What painful moment makes them look for this?
3. What does the user want to happen after using it?
4. What do they get within the first 5 minutes?
5. What is the smallest version that would still feel valuable?
6. Is this consumer, prosumer, B2B, marketplace, or internal tool?
7. What existing behavior or workaround does this replace?
8. What would make someone pay for this?
9. What should this intentionally not do?
10. What is the viral or sharing moment?
11. What is the riskiest assumption?
12. What is the strongest wedge?

## Default Output Format

Use this format unless the user requests another structure.

# Product Spec: [Product Name]

## Assumptions Made

- [Assumption]
- [Assumption]
- [Assumption]

## 1. Product Summary

### One-liner

[One sentence]

### Concept

[One paragraph]

### Target User

[Specific user]

### Core Problem

[Clear problem]

### Desired Outcome

[What the user wants]

## 2. Strategic Framing

### Wedge

[Narrow initial entry point]

### Why This Could Work

[Behavioral, market, or workflow insight]

### Differentiation

[Why this is not generic]

### Riskiest Assumption

[The thing that must be true]

## 3. MVP

### MVP Promise

[What v1 delivers]

### Core User Flow

1. [Step]
2. [Step]
3. [Step]
4. [Step]

### Key Features

- [Feature]
- [Feature]
- [Feature]

### Non-Goals

- [Thing not to build yet]
- [Thing not to build yet]

## 4. Product Mechanics

### Input

[What the user provides]

### Processing

[What the product does]

### Output

[What the user receives]

### Magic Moment

[The aha moment]

## 5. UX Spec

### Main Screens

- [Screen]
- [Screen]
- [Screen]

### Important States

- Empty state
- Loading state
- Success state
- Error state

## 6. Data Model

### Core Objects

- [Object]
- [Object]
- [Object]

## 7. AI Behavior

### AI Role

[How the AI should behave]

### AI Inputs

[Inputs]

### AI Outputs

[Structured outputs]

### Guardrails

[What the AI should avoid]

## 8. Launch Plan

### First Audience

[Specific group]

### Acquisition Channels

[Channels]

### Viral Loop

[Sharing/referral mechanism]

### Pricing

[Suggested pricing]

## 9. Build Plan

### Phase 1: Prototype

[Scope]

### Phase 2: MVP

[Scope]

### Phase 3: Expansion

[Scope]

## 10. Cursor Build Prompt

[Prompt to build the MVP]

## 11. Open Questions

- [Question]
- [Question]

## Style Rules

- Be specific.
- Be opinionated.
- Prefer MVP clarity over feature bloat.
- Always include non-goals.
- Always identify the riskiest assumption.
- Always define the first magical moment.
- Always include a Cursor-ready build prompt.
- Use concrete product language.
- Avoid startup clichés.
- Avoid generic brainstorming.
- Do not list every possible feature.
- If the user’s idea is vague, ask questions before producing the final spec.
