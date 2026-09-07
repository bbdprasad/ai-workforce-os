# Competitive landscape

Snapshot as of September 2026. This file tracks who already operates in each candidate wedge so the project does not rediscover crowded categories through expensive customer interviews. Update it as evidence changes; treat every entry as provisional.

## Agent identity and permissions

**Status: crowded, moving fast.**

Major identity incumbents have already extended into non-human/agent identity: Okta, CyberArk, SailPoint, and PlainID all shipped agent-identity products or GA features in the first half of 2026. Gartner named agent IAM a 2026 CISO priority. Several funded startups (Token Security, OAK, Securden's agent governance line) are also building here.

**Implication:** this matches the existing `killed-ideas.md` entry. A generic identity/permissions product would compete directly with well-capitalized incumbents extending an existing budget line, not create a new one. Any future play here would need a wedge the incumbents structurally cannot reach (for example a specific vertical, a specific runtime, or a specific compliance regime), not a horizontal identity layer.

## Agent reliability, evaluation, and observability

**Status: crowded, consolidating.**

An established set of vendors already covers agent tracing, evaluation, and observability: LangSmith (LangChain-native), Arize/Arize Phoenix, Langfuse (open source), Galileo, Braintrust, Maxim AI, Patronus AI, TruLens, Humanloop. Comparison content and "top N" roundups for this category are now a content-marketing genre in their own right, which is itself a signal of category maturity.

**Implication:** a general-purpose eval/observability product is a weak wedge. Differentiation would need to come from a specific failure mode, workflow, or buyer these platforms do not serve well (for example simulation before production deployment, rather than monitoring after).

## Agent economics / FinOps

**Status: emerging, less crowded than identity or eval, but incumbents are moving in.**

Cloud FinOps vendors (Finout, and cloud providers themselves via AWS FinOps Agent and Bedrock attribution) are extending existing cost-management products to cover AI agent spend. Newer, more narrowly agent-cost-focused entrants (Revenium, several YC-funded seed startups such as Carrot Labs) are targeting attribution specifically: which agent, workflow, customer, or feature drove a given cost. Anthropic and Snowflake have also shipped their own usage/cost attribution APIs during 2026, narrowing the gap that third-party tools fill.

**Implication:** this space is younger than identity or eval but filling in quickly, largely from two directions at once: cloud FinOps incumbents extending downward, and model/platform vendors extending their own native attribution upward. A wedge here would need to sit in the gap those two directions do not cover, for example cross-vendor attribution (spend spread across multiple model providers, tools, and human review time in one place) rather than single-platform reporting.

## Agent supervision, simulation, and pre-deployment testing

**Status: least validated, worth deeper research.**

This category overlaps with evaluation vendors above but is not fully the same claim. Evaluation and observability tools largely measure production behavior after the fact. Pre-deployment simulation, staged rollout gating, and "red team before autonomous production access" tooling is a narrower, less crowded claim, though some of the eval vendors above are moving into it.

**Implication:** this is the wedge most worth further customer discovery before ranking. It has not been searched as thoroughly as the other three.

## Open questions for further research

1. Who is the buyer for each category above (security, platform engineering, FinOps, AI engineering) and does that buyer already have signed vendor relationships that block a new entrant?
2. Which incumbents above are extensions of an existing product (bolt-on) versus purpose-built for agents? Bolt-ons may be weaker on depth even where they win on distribution.
3. Is there a wedge that is intentionally cross-cutting (for example, a neutral registry that other tools read from) rather than competing head-on in any one category?

## How to keep this current

Re-run a lightweight market scan before each MVP-selection decision point, not on a fixed schedule. This category moves fast enough that a scan older than one quarter should be treated as stale.
