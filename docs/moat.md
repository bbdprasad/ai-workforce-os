# Moat

No moat exists yet. Nothing has been built, so nothing is defensible. This document records hypotheses about where defensibility could come from, to be tested rather than assumed.

## Why this matters now

`research/competitors.md` shows that the most obvious wedges (identity, evaluation/observability, FinOps) already have funded, moving incumbents. A neutral inventory or governance layer with no other advantage would be easy to copy and easy for an incumbent to bolt on. Any viable moat has to come from something harder to replicate than a feature.

## Candidate sources of defensibility

### Data / network effects

If the product accumulates cross-agent, cross-vendor performance, cost, or incident data over time, later customers benefit from patterns earlier customers generated (benchmarks, anomaly baselines, common failure signatures). This is the strongest theoretical moat but takes real usage to prove. It cannot be claimed until there is evidence customers value the aggregated data, not just their own.

### Neutrality as a feature

Vendor-native tools (Okta for identity, AWS FinOps Agent for cost, LangSmith for LangChain) have an inherent conflict: they are strongest inside their own ecosystem and weaker across others. A genuinely neutral, cross-vendor layer could be the wedge itself rather than a side benefit, but neutrality only matters if customers actually run multi-vendor agent stacks, which needs validation (see `research/hypotheses.md`, H001).

### Workflow lock-in

If the product becomes the system of record that other tools and processes depend on (approval workflows, audit trails, incident response), switching cost rises independent of feature parity. This is a later-stage moat, not a Phase 0 one; it presumes the product is already embedded.

### Regulatory / compliance surface

If AI agent governance becomes an explicit audit or compliance requirement (as opposed to a best practice), being the system that produces the required evidence trail is defensible in a way a preference-based tool is not. Worth tracking as a possible external tailwind rather than something to build directly.

### Speed and focus against slower incumbents

Large identity and FinOps vendors move slowly by nature. A narrow, fast-moving product could out-execute them on a specific workflow before they get there, but this window closes as the category matures, and `research/competitors.md` suggests it may already be closing in identity and evaluation.

## What would kill this thesis

- Evidence that customers are satisfied extending an existing vendor relationship (identity, FinOps, or observability) rather than adding a neutral layer.
- Evidence that agent stacks are single-vendor in practice, undermining the neutrality argument.
- Evidence that the data/network effect never materializes because customers do not want to share performance or cost data across a shared benchmark, even anonymized.

## Status

Unvalidated. No moat should be assumed or pitched externally until at least one of the above has customer evidence behind it.
