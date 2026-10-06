# Defect Management Report

## Defect Summary

| Severity | Found | Closed | Open | Status |
|---|---:|---:|---:|---|
| Critical | 0 | 0 | 0 | Green |
| High | 14 | 12 | 2 | Amber |
| Medium | 31 | 29 | 2 | Green |
| Low | 18 | 18 | 0 | Green |
| **Total** | **63** | **59** | **4** | **Amber** |

## Key KPIs

- Defect closure rate: 94%
- Defect reopen rate: 4%
- Defect leakage: 2%
- Defects older than 14 days: 1

## Test Manager actions

- Daily triage for High/Critical defects
- Root-cause analysis for repeated failures
- Track aging and ownership in Jira
- Escalate unresolved High defects before release gate
- Trend escaped defects after production release

## Example Jira workflow

`Open → Triage → Assigned → In Progress → Fixed → QA Retest → Closed`

Rejected/duplicate/won't-fix outcomes require documented rationale.
