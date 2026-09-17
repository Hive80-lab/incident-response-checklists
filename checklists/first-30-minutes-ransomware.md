# First 30 Minutes After Ransomware: Field Checklist (Small IT Teams)

> Full guide on dev.to: https://dev.to/hive80lab/the-first-30-minutes-after-ransomware-a-field-checklist-for-small-it-teams-3fgc

## Minute 0-5: Confirm and isolate
- [ ] Do NOT reboot or power off (preserve volatile forensics)
- [ ] Disconnect affected hosts from network (unplug NIC / disable Wi-Fi) — do not shut down
- [ ] Snapshot: photo of the ransom note + a copy of any .txt/.html note left behind

## Minute 5-15: Scope
- [ ] Which shares/volumes show encrypted extensions?
- [ ] Check backups NOW: are they network-reachable by the infected hosts? If yes, sever them.
- [ ] Identify patient zero via recent logins/VPN logs if available

## Minute 15-30: Decide and escalate
- [ ] DO NOT pay yet — verify decryptability first (ID Ransomware / nomoreransom.org)
- [ ] Engage insurance/legal per policy; preserve evidence (no wiping)
- [ ] Begin restore plan from known-clean offline backups

## After stabilization
Run the one-question postmortem: *what single automated check would have caught this?*
(Usually: offline/immutable backup verification + EDR on file-server mass-rename patterns.)

**Done-for-you runbooks:** https://hive80lab.gumroad.com/l/custom-incident-runbook
