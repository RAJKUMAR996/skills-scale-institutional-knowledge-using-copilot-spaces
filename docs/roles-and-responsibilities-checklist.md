```markdown
# Roles & Responsibilities — Checklists

Purpose: Practical checklists to reduce handoff ambiguity and speed decision-making during Planning, Release, and Incident flows.

---

## Planning checklist (to be completed before sprint/release planning)
- [ ] PdM: One-pager / outcome & success metrics defined
- [ ] Tech Lead: High-level design and architecture notes present
- [ ] EM: Team capacity and hiring/availability confirmed
- [ ] UX: Wireframes / acceptance criteria for user flows provided
- [ ] Data: Measurement & events planned (dashboard owners assigned)
- [ ] PM: Dependencies documented and scheduled on project board
- [ ] QA: Test strategy and test owners identified
- [ ] SRE/ProdOps: Any operability requirements or infra changes documented
- [ ] Release Manager: Tentative release window and rollback plan identified

---

## Release readiness checklist (must be completed before production deploy)
- [ ] All acceptance criteria met and PRs merged
- [ ] CI green and security scans passed
- [ ] Release notes drafted and owner assigned
- [ ] Rollback / mitigation plan documented and tested
- [ ] SRE: SLIs/SLOs and alerts verified for the change
- [ ] QA: Post-deploy smoke tests and owners assigned
- [ ] Support: Customer-facing notes prepared and triage steps documented
- [ ] PM: Stakeholder notification list and comms drafted
- [ ] Release Manager: Final sign-off and deployment schedule confirmed

---

## Incident & on-call checklist (rapid response)
- [ ] SRE/On-call: Acknowledge alert and assess scope & impact
- [ ] PM: Notify stakeholders & coordinate external communications
- [ ] Tech Lead & Developers: Triage and produce mitigation or rollback
- [ ] Support: Collect customer reports and maintain updates
- [ ] Data: Provide metrics/dashboards that show impact
- [ ] Post-incident: Schedule blameless postmortem, action owner(s), and due dates

---

## Role handoff expectations
- When a role transitions ownership (e.g., temporary cover, rotation):
  - [ ] Document temporary owner and duration in project README
  - [ ] Notify stakeholders in the weekly sync and add to project board
  - [ ] Update any runbooks or handoff notes in docs/

---

## How to use
- Add these checklists as a checklist in the project repo (docs/) and reference them from project READMEs and release pages.
- The Release Manager or PM should own verifying the release checklist prior to deploy.
```
