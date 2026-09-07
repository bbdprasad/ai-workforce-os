# Business model

No pricing or packaging has been chosen. This document lists candidate revenue models to test once a wedge is selected, not a committed plan.

## Candidate models

### Per-agent or per-seat pricing

Charge per registered/managed agent, similar to per-user identity or seat pricing. Familiar to enterprise buyers and easy to forecast. Risk: agent counts may be volatile (spun up and torn down constantly), making a per-agent price feel arbitrary to the buyer compared to per-human seats.

### Usage-based pricing

Charge on volume of activity monitored, evaluated, or governed (tasks, tool calls, tokens passed through the system, incidents processed). Matches how several FinOps and observability competitors already price. Risk: usage-based pricing on top of already-metered AI spend can be a hard sell to a buyer who is trying to control costs, not add another variable cost line.

### Platform / flat governance fee

Charge a flat platform fee independent of agent count or usage, positioned as infrastructure rather than metered software. Simpler for the buyer to budget. Risk: harder to prove value/ROI early, since price is not tied to a metric the customer already cares about.

### Value-based / outcome pricing

Price against a measurable outcome the product enables (incidents prevented, cost savings identified, audit hours saved). Strongest alignment with the "measurable business value" principle in the README, but requires a mature enough product to reliably measure the outcome, and a customer willing to share the baseline data needed to prove it.

### Hybrid: platform fee plus usage

A base platform/access fee (covers the neutral-layer, always-on cost of being a system of record) plus a usage or per-agent component that scales with actual footprint. Common pattern among the FinOps and identity incumbents already in `research/competitors.md`, which suggests it is what enterprise buyers are already used to evaluating.

## Buyer considerations

The pricing model cannot be finalized before the buyer is confirmed (see `docs/problem.md`, question 2). A CISO-led budget, a platform-engineering budget, and a FinOps budget respond differently to per-agent versus usage versus flat pricing, and the wedge selection and buyer identification should happen before this document is treated as anything more than a list of options.

## What would validate a model

- Direct evidence from customer discovery interviews about how they already budget for adjacent tools (per-seat identity licenses, usage-based cloud spend, flat platform contracts).
- Willingness-to-pay signals tied to a specific number, not a general "yes we'd pay for this."
- Evidence of what a design partner or early customer would accept in a pilot, since Phase 0 pricing rarely survives contact with a real deal.

## Status

Unvalidated. No model should be presented to a prospect as final until it has been tested against at least one real buyer conversation.
