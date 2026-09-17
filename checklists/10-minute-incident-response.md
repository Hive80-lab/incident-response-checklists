# Incident Response Checklists — Solo Devs & Small Teams

Free, battle-tested checklists distilled from 100+ production incidents.

## The 10-Minute Incident Response Checklist
Full write-up: [dev.to article](https://dev.to/hive80lab/the-10-minute-incident-response-checklist-every-solo-dev-needs-4dg8)

| Minute | Action |
|--------|--------|
| 0-2 | Confirm externally · audit last-hour changes · contain (rollback > debug) |
| 2-5 | Communicate: status update + 15-min update timer |
| 5-8 | Stabilize: restart → rollback → `df -h` / `free -m` → clear queues/caches |
| 8-10 | Decide: resolved → postmortem today · unresolved → escalate/runbook |

## Postmortem rule
One question: *what single automated check would have caught this?* Add one per incident — 20+ checks/year, incident rate falls off a cliff.

## Files
- `checklists/10-minute-incident-response.md` — the core checklist
- `checklists/postmortem-template.md` — one-page postmortem template
- `checklists/first-30-minutes-ransomware.md` — ransomware field checklist

## Ready-made kits (instant download)
- [Custom Incident Runbook — done-for-you, 48h delivery](https://hive80lab.gumroad.com/l/custom-incident-runbook)
- [AI Ops Workflow Kit](https://hive80lab.gumroad.com/l/ai-ops-workflow-kit)
- [Ops Mega Bundle — all kits](https://hive80lab.gumroad.com/l/ops-mega-bundle)

MIT licensed. Steal everything.
