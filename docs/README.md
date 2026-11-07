# OctoAcme Project Management Docs

This directory contains OctoAcme's shared guidance for managing cross-functional projects, from validating an idea through delivery, release, and continuous improvement. The approach emphasizes customer value, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

## Project lifecycle at a glance

1. **Initiate:** Validate the business need and measurable outcome, identify stakeholders and a champion, outline risks and resources, and make a go/no-go decision for planning.
2. **Plan:** Translate approved work into a prioritized backlog with acceptance criteria and estimates. Agree on ownership, the Definition of Done, milestones, dependencies, and an initial QA approach.
3. **Execute and track:** Deliver in small increments using the project board. Review progress, metrics, risks, and blockers regularly; escalate issues through the agreed path when needed.
4. **Release:** Confirm acceptance criteria, CI and security checks, release notes, smoke tests, and rollback or mitigation plans. Deploy, verify the result, and communicate the release.
5. **Reflect and improve:** Hold a retrospective after sprints, releases, milestones, or incidents. Choose a small number of actionable improvements, assign owners and due dates, and follow up on their impact.

## Core roles

- **Project Manager (PM):** Coordinates plans, schedules, risks, dependencies, meetings, and stakeholder communication.
- **Product Manager (PdM):** Defines outcomes and success measures, prioritizes the roadmap and backlog, and helps make product trade-offs.
- **Developers:** Design, implement, test, document, and review changes while identifying technical risks.
- **QA/Testing:** Validates quality and acceptance criteria.
- **Stakeholders:** Provide input, alignment, and approvals.

## Communication and coordination

Use regular PM–PdM alignment, delivery-team standups, weekly delivery or stakeholder updates, and demos at sprint or milestone ends. Keep status in a shared source of truth, such as the project README or release documentation. Track risks and dependencies with owners and mitigation plans, review them regularly, and escalate from the team to the PM, Product Lead, and sponsor as appropriate. Security incidents follow the security incident runbook and notify Security on-call.

## Quality practices

Write unit tests for new logic, add integration tests where applicable, and run end-to-end smoke tests for critical flows before release. CI should run automated tests and linting, and security scanning should be included. PRs should be small where possible, link the relevant issue and acceptance criteria, and receive the required review before merging. Before production deployment, verify release readiness, prepare smoke tests and rollback or mitigation guidance, then perform post-deployment checks.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, key artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — Validating and authorizing new work, defining outcomes, and aligning stakeholders.
- [Project Planning](octoacme-project-planning.md) — Turning approved initiatives into prioritized backlogs, milestones, estimates, and risk plans.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery, project-board workflow, testing, reporting, and blocker escalation.
- [Risk Management and Communication](octoacme-risks-and-communication.md) — Identifying, assessing, mitigating, and communicating risks and dependencies.
- [Release and Deployment Guide](octoacme-release-and-deployment.md) — Release readiness, deployment checks, verification, and rollback.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing lessons and tracking improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — Responsibilities and communication patterns for developers, product managers, and project managers.
