# One-Page Postmortem Template

**Incident:** <title>  **Date:** <date>  **Severity:** <S1-S4>  **Author:** <you>

## 1. Impact (3 lines max)
- Duration: from <t1> to <t2> (<N> min)
- Scope: <users/services affected>
- Money/SLA impact: <e.g. 45 min of checkout downtime>

## 2. Timeline (only state changes)
| Time (UTC) | Event |
|---|---|
| hh:mm | First alert fired |
| hh:mm | Confirmed from external vantage |
| hh:mm | Rollback deployed — impact stopped |
| hh:mm | Verified healthy |

## 3. Root Cause
The *change* that caused it (not the person). One paragraph.

## 4. Detection
- How did we find out? (user report / alert / dashboard)
- Minutes from impact start to detection: <N>

## 5. THE action item (one per incident)
- [ ] Automated check that would have caught this: <describe>
- Owner: <name>  Due: <date>

## 6. Secondary action items (max 3)
- [ ] ...
- [ ] ...

*Rule: one automated check per incident. Blameless. Ship the check before adding more text.*
