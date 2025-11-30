# OctoAcme Project Management Docs

This README centralizes OctoAcme’s project and program management documentation for easy access. Use these docs to onboard new teammates, follow standard workflows, and keep project artifacts in a single, discoverable place.

## Project Management Summary

OctoAcme projects flow through a lifecycle: initiation (validate business need and align stakeholders), planning (scope work, identify dependencies and risks, build a prioritized backlog), execution (short iterations, visible boards, disciplined PR checks and QA), release (pre-release checks, staged deploys, rollback plans), and retrospective (capture learnings and convert them into tracked improvements). Each stage has lightweight decision gates and minimum artifacts (for example, a Project One-pager at initiation and a release checklist before deployment) so teams move forward with clarity and reduced rework.

Work is managed using a prioritized backlog and a project board that shows item states (Backlog → Ready → In Progress → In Review → QA → Done). The PR workflow enforces small, well-described changes (link to issues, include acceptance criteria), CI-run tests and security scans, and at least one reviewer approval before merging. Team rhythm includes daily standups for blockers, weekly delivery syncs for cross-team coordination, and demos at the end of sprints or milestones to keep stakeholders aligned.

Roles and responsibilities are explicit: Product Managers own outcomes and success metrics, Project Managers coordinate delivery, schedules, risks, and communications, Developers implement and maintain tests and documentation, and QA validates acceptance criteria and undertakes manual checks when needed. Quality is enforced through automated unit/integration/e2e smoke tests in CI, security scanning, monitoring dashboards, and a documented incident/rollback playbook. Risks, blockers, and retrospective action items are tracked and fed back into the backlog for continuous improvement.

## Docs in this folder

- octoacme-project-management-overview.md — Overview, principles, lifecycle and core roles.
- octoacme-project-initiation.md — One-pager template and initiation checklist.
- octoacme-project-planning.md — Backlog templates, estimation, and planning activities.
- octoacme-execution-and-tracking.md — Daily execution rhythms, PR workflow, QA and reporting.
- octoacme-risks-and-communication.md — Risk register, communication templates, and escalation paths.
- octoacme-release-and-deployment.md — Release planning, deployment, rollback and incident playbook.
- octoacme-retrospective-and-continuous-improvement.md — Retrospectives and tracking improvement actions.
- octoacme-roles-and-personas.md — Persona definitions and communication expectations.
