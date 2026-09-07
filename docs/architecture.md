# Architecture direction

The architecture is intentionally conceptual during Phase 0.

## Long-term model

```text
Humans ───────┐
              ├── Workforce Graph ── Policies ── Audit
AI Workers ───┤
              ├── Tasks / Workflows
Systems ──────┤
              ├── Evaluation / Observability
              └── Cost / Business Outcomes
```

Potential platform components include:

- workforce graph
- agent identity and ownership
- authorization/policy engine
- execution/runtime integration
- evaluation and simulation
- observability and audit
- cost and value attribution
- lifecycle management

These components are not commitments. The eventual architecture will be driven by the first validated wedge.
