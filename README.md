# AI Workforce OS

> The operating system for companies where humans and AI workers work together.

## Phase 0 — Thesis & validation

AI agents are moving from assistants toward systems that can reason, use tools, execute workflows, and collaborate with people. We are exploring the infrastructure required when AI workers become first-class participants in enterprise work.

### Initial hypothesis

> Companies will accumulate AI agents from multiple vendors and frameworks faster than they develop a neutral way to inventory, govern, evaluate, and measure those agents.

This is a hypothesis, not a conclusion. The goal is to try to disprove it.

## What we are looking for

The first product should be a narrow wedge that:

1. solves a painful enterprise problem;
2. has a clear buyer and budget;
3. exists because AI workers are becoming real;
4. can be prototyped cheaply;
5. produces measurable business value; and
6. can expand into a much larger platform.

Potential wedges under investigation:

- agent workforce inventory
- agent identity and permissions
- agent supervision
- agent reliability and evaluation
- agent simulation / pre-deployment testing
- agent performance management
- agent economics / FinOps
- agent procurement / commerce

## Operating model

Every major assumption follows:

**Hypothesis → Experiment → Evidence → Decision**

We optimize for evidence, not attachment to the original idea.

## Principles

- **Artifact over activity.** Working experiments and evidence beat passive learning.
- **Evidence over opinion.** Claims should be traceable to customer or market evidence.
- **Business outcome over AI novelty.** Value must be measurable.
- **Kill weak ideas quickly.** A failed hypothesis is useful progress.
- **Think 10 years ahead; build for today's capabilities.**

## Repository

```text
README.md
├── docs/             # vision, problem, product, architecture, moat, business model
├── research/         # market, competitors, ecosystem, customer discovery
├── product/          # personas, use cases, requirements, MVP
├── architecture/     # identity, permissions, runtime, evaluation, audit
└── experiments/      # hypotheses and validation experiments
```

## Current status

**Phase 0: thesis and market validation.**

We are deliberately not building the full OS yet. The immediate objective is to discover the painful wedge worth building.

A first look at the competitive landscape (`research/competitors.md`) suggests the more obvious wedges (agent identity, agent evaluation/observability) are already crowded with funded, moving incumbents. This does not kill the overall thesis, but it sharpens the immediate question: find the wedge, buyer, or angle that incumbents structurally cannot reach, rather than a horizontal version of what they already sell. See `docs/moat.md` for the current thinking on defensibility.
