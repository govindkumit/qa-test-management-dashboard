# QA Risk Register – Release v3.5

| ID | Risk | Probability | Impact | Exposure | Mitigation | Owner | Status |
|---|---|---|---|---|---|---|---|
| RISK-01 | Payment gateway instability | Medium | High | High | Retry tests, gateway monitoring, rollback plan | API Lead | Mitigated |
| RISK-02 | High defect in checkout edge case | Medium | High | High | Fix + targeted regression + business acceptance | Dev Lead | Open |
| RISK-03 | Test environment instability | Medium | Medium | Medium | Daily health check and backup environment | DevOps | Controlled |
| RISK-04 | Peak-load performance below target | Medium | High | High | Final load test, autoscaling check, monitoring | Perf Lead | Open |
| RISK-05 | Late requirement change | Low | High | Medium | Change-control impact assessment | Product Owner | Controlled |

## Risk approach

Risk exposure = Probability × Impact. High exposure requires mitigation, an owner and an explicit decision before release.

## Escalation rule

Any Critical business risk, Critical defect, or risk without an owner is escalated immediately to Engineering/Product leadership.
