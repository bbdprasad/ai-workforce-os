# Customer discovery

A practical guide for running interviews that produce real evidence against `research/hypotheses.md`, not just friendly conversation.

## Who to talk to

Target a mix across the roles named in `docs/problem.md` question 2: CIO/CTO, CISO, platform engineering lead, AI engineering lead, and business operations owner of an AI-enabled workflow. Do not only interview AI-enthusiast early adopters; include at least a few skeptical or reluctant-adopter organizations, since their objections are often the most useful evidence.

Prioritize organizations that already run more than one AI agent in production, since pre-agent organizations cannot speak to the actual pain, only to the hypothesis in the abstract.

## Ground rules

- Ask about what they have already done, not what they would do. Past behavior (a spreadsheet they built, an incident they had, a budget they allocated) is evidence. A hypothetical "yes I'd probably use that" is not.
- Do not pitch the product. Describe the problem space and let them tell you whether it resonates, in their own words, before naming a solution.
- Every interview should produce a clear mapping to one or more hypothesis IDs (H001-H005) and either supports, contradicts, or is inconclusive for each one it touches.
- Log kill signals as seriously as supporting signals. An interview that weakens a hypothesis is as valuable as one that strengthens it.

## Question guide by hypothesis

### H001 — Agent sprawl

- How many AI agents, copilots, or automated workflows are running in production today, across all vendors and teams?
- Is there a single place that lists all of them, or would you have to ask multiple teams to find out?
- Has anyone ever been surprised to discover an agent running that they did not know about?

### H002 — Accountability gap

- When an agent takes an action that turns out to be wrong, who is responsible for it today?
- Has an agent-related incident ever been hard to investigate because it was unclear who owned the agent or what it was allowed to do?
- Do you have an approval process for turning on a new agent, and who runs it?

### H003 — Reliability is budget-worthy

- Can you describe a specific incident where an agent produced a wrong or costly result?
- What did it cost in rework, money, or trust with a customer?
- What did you do afterward: nothing, a manual fix, or a new process/tool?

### H004 — Economics matter

- Do you know what your AI agents cost, broken down by agent, team, or workflow?
- Has anyone been surprised by an AI-related bill?
- Who currently owns that number: FinOps, engineering, finance, or nobody?

### H005 — Pre-deployment simulation is valuable

- How do you test an agent before it is allowed to take real production actions?
- Has a deployment ever been delayed or blocked because of uncertainty about how the agent would behave?
- Would you trust a simulated test enough to skip a staged rollout, or do you always need to see real traffic first?

## Recording results

Log each interview's outcome directly in `research/hypotheses.md` under the relevant hypothesis's evidence, and update `research/killed-ideas.md` if an interview produces a clear kill signal. Do not let interview notes accumulate only in this file; the hypotheses file is the source of truth for where each claim stands.

## Cadence

Phase 0 priority, per `experiments/README.md`, is customer and market validation before application development. Target a standing rhythm of interviews rather than a single batch, so evidence accumulates over multiple weeks and is less biased by whoever happened to be available first.
