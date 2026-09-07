# Validation hypotheses

Each hypothesis must be tested with evidence before product commitment.

## H001 — Agent sprawl

**Claim:** Enterprises will accumulate agents from multiple vendors/frameworks and need a neutral inventory.

**Evidence sought:** Interviews with organizations operating multiple production agents; evidence of spreadsheets, CMDB entries, internal registries, or similar workarounds.

**Kill signal:** Enterprises consistently report that vendor-native inventory is sufficient and agent sprawl is not a meaningful operational problem.

## H002 — Accountability gap

**Claim:** Enterprises will need a clear owner/supervisor model for autonomous agents.

**Evidence sought:** Production incidents, approval workflows, ownership gaps, audit requirements, or escalation processes involving agents.

**Kill signal:** Existing IAM/workflow tooling solves ownership adequately without a new product layer.

## H003 — Reliability is budget-worthy

**Claim:** Agent reliability failures will create enough business impact to justify dedicated evaluation/simulation tooling.

**Evidence sought:** Failed tasks, human rework, production incidents, costly incorrect actions, or blocked deployments.

**Kill signal:** Reliability problems remain too small or are solved adequately by existing observability/evaluation products.

## H004 — Economics matter

**Claim:** Organizations will need agent-level cost and value attribution as autonomous work scales.

**Evidence sought:** Agent spend reports, unexpected model/tool costs, cost allocation problems, or ROI measurement requests.

**Kill signal:** Existing FinOps/APM/model observability products provide sufficient attribution and optimization.

## H005 — Pre-deployment simulation is valuable

**Claim:** Enterprises will pay to test agents against realistic workflows before allowing autonomous production actions.

**Evidence sought:** Manual staging environments, red-team exercises, approval gates, sandboxing, or delayed deployments caused by uncertainty.

**Kill signal:** Customers do not see enough risk or value in pre-deployment simulation to allocate budget.
