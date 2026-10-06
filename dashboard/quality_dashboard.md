# Quality Dashboard – Release v3.5

## Executive Scorecard

| KPI | Actual | Target | RAG |
|---|---:|---:|---|
| Test execution | 96% | ≥95% | 🟢 |
| Pass rate | 94% | ≥90% | 🟢 |
| Requirement coverage | 98% | 100% | 🟠 |
| Critical requirement coverage | 100% | 100% | 🟢 |
| Automation coverage | 82% | ≥80% | 🟢 |
| Critical defects open | 0 | 0 | 🟢 |
| High defects open | 2 | ≤2 | 🟠 |
| Defect leakage | 2% | <3% | 🟢 |
| Regression pass | 96% | ≥95% | 🟢 |
| Performance acceptance | 95% | 100% | 🟠 |
| UAT sign-off | Yes | Yes | 🟢 |

## Quality interpretation

Overall quality is **AMBER** because the release has two High defects and a performance risk, although all critical requirements are covered and no Critical defects remain open.

## Management message

The release is technically ready with controlled residual risk. Release should proceed only with documented mitigation for payment defects and peak-load performance monitoring.

## Test Manager actions

1. Close or formally accept the two High defects.
2. Execute final performance validation.
3. Confirm production monitoring and rollback readiness.
4. Obtain Product Owner/customer approval for residual risk.
5. Continue production smoke testing after deployment.
