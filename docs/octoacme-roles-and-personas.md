```markdown
# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional personas (expanded)

The following personas are commonly involved in OctoAcme projects. Adding them clarifies ownership, handoffs, and expectations.

### Tech Lead
- Role summary: Technical leader responsible for architecture, design decisions, and technical direction for an initiative.
- Responsibilities:
  - Define high-level design and drive architecture decisions.
  - Make technical trade-offs and scope recommendations.
  - Mentor engineers, lead design/PR reviews, and ensure code quality.
  - Coordinate technical dependencies with Platform, SRE, and other teams.
- Interaction with existing roles:
  - Works with PdM to translate product requirements into technical stories and estimations.
  - Partners with QA to define testability and acceptance criteria.
  - Escalates cross-team blockers to the Project Manager.

### Engineering Manager
- Role summary: Responsible for people management, team health, capacity planning, and delivery effectiveness.
- Responsibilities:
  - Manage capacity planning, hiring needs, and performance coaching.
  - Remove organizational and resourcing blockers.
  - Promote engineering best practices (code review, CI, documentation).
- Interaction:
  - Coordinates with PM on sprint commitments and capacity adjustments.
  - Works with Tech Lead to balance technical debt and feature work.

### UX Designer / Researcher
- Role summary: Owns user experience design, interaction patterns, and lightweight research.
- Responsibilities:
  - Deliver wireframes, designs, prototypes, and accessibility checks.
  - Conduct rapid usability tests or research to validate assumptions.
  - Provide acceptance criteria related to UX and accessibility.
- Interaction:
  - Partners with PdM to shape requirements and success metrics.
  - Collaborates with Developers and QA on implementation fidelity.

### Data Analyst / Data Scientist
- Role summary: Owner of instrumentation, analytics, and measurement for validating success metrics.
- Responsibilities:
  - Define event tracking, dashboards, and measurement plans.
  - Analyze experiments and usage data to inform prioritization.
  - Validate post-release impact and share findings with the team.
- Interaction:
  - Works with PdM to define success metrics and experiments.
  - Partners with Developers to ensure instrumentation is implemented.

### SRE / On-call Engineer
- Role summary: Responsible for production reliability, monitoring, incident response, and operability.
- Responsibilities:
  - Define SLIs/SLOs, implement alerting, and maintain runbooks.
  - Participate in incident response and postmortems.
  - Work on performance and operational improvements.
- Interaction:
  - Coordinates with Developers and Tech Lead for deploy readiness and mitigations.
  - Advises PM on operational risks and incident communications.

### Release Manager
- Role summary: Coordinates release activities, schedules deployments, and ensures rollback plans exist.
- Responsibilities:
  - Maintain release checklist, schedule deployment windows, and coordinate staging validation.
  - Draft release notes and stakeholder announcements.
  - Ensure rollback and mitigation plans are ready.
- Interaction:
  - Works with PM, SRE, QA, and Tech Lead to confirm deploy readiness and post-release verification.

### Product Operations (ProdOps)
- Role summary: Operationalizes product processes, runbooks, enablement, and internal tooling.
- Responsibilities:
  - Maintain operational playbooks, dashboards, and onboarding materials.
  - Improve handoffs between teams and reduce process friction.
- Interaction:
  - Works with PM and EM to ensure smooth operational workflows and enablement.

### Support / Customer Success Lead
- Role summary: Frontline for customer issues, feedback, and escalations.
- Responsibilities:
  - Triage customer-reported issues and capture reproducible steps and impact.
  - Communicate patterns and customer context back to PdM and engineering.
  - Coordinate customer-facing communications for releases and incidents.
- Interaction:
  - Escalates production issues to PM/SRE and provides prioritization context to PdM.

---

## Interactions & typical handoffs (summary)
- Planning: PdM owns outcomes, Tech Lead and UX define solution approach, EM verifies capacity, BA/Analyst defines measurement, PM schedules work and tracks dependencies.
- Execution: Developers implement; Tech Lead supports complex design; QA verifies; SRE ensures operability and monitoring; ProdOps enables runbooks.
- Release: Release Manager coordinates the release window and communications; Support receives customer impact information and closes the loop.
- Incidents: SRE leads on-call response, PM coordinates stakeholder communication, Tech Lead and Developers assist triage and fix, Support maintains customer updates.

## Why these additions matter
- Reduce ambiguity about who does what and who to escalate to.
- Improve reliability, measurement, and customer communication coverage.
- Faster onboarding: new team members can find the right contact for specific concerns.
- Better cross-team coordination reduces delivery risk and incident impact.
```
