# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles describe areas of ownership, not required headcount: tailor them to the project, and let one person cover multiple roles when appropriate. Make ownership and handoffs explicit during kickoff and revisit them as the project changes.

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

## UX / Product Designer

### Role Summary
The UX / Product Designer translates user needs and product goals into accessible, understandable, and testable experiences.

### Responsibilities and deliverables
- Plan or conduct appropriate user research and synthesize findings
- Create flows, prototypes, interaction and visual designs, and design specifications
- Validate usability and accessibility, and capture open questions and design decisions

### Decisions and boundaries
Owns design methods and recommendations within agreed product goals and standards. Partners with the Product Manager on scope and acceptance criteria; product priority and business trade-offs remain with the Product Manager and relevant stakeholders.

### Collaboration and lifecycle touchpoints
- Works with users and stakeholders during discovery; shares findings with the Product Manager.
- Reviews feasibility and edge cases with the Technical Lead and Developers before implementation.
- Gives QA / Testing testable experience states, expected behavior, and accessibility considerations; reviews the implemented experience and helps triage usability issues.
- Coordinates design handoff and changes with the Project Manager so dependencies and timing are visible.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides the technical approach so the solution is maintainable, secure, and compatible with the project’s systems and engineering standards.

### Responsibilities and deliverables
- Lead technical design, integration choices, and engineering standards
- Surface technical risks, dependencies, and capacity or sequencing concerns
- Provide design guidance and code-review support; document significant decisions and mitigations

### Decisions and boundaries
Owns or recommends technical design within agreed product scope and organizational standards. Escalates material scope, schedule, cost, or risk trade-offs to the Product Manager, Project Manager, or appropriate stakeholder rather than making product-priority decisions unilaterally.

### Collaboration and lifecycle touchpoints
- Works with Developers on estimates, implementation, reviews, and technical debt.
- Partners with the Product Manager to explain technical options and consequences, and with the Project Manager to plan dependencies and track risks.
- Consults Security / Privacy and DevOps / Release roles early on controls, architecture, deployment, and operability.
- Supports QA / Testing with testability, integration environments, and investigation of defects.

---

## DevOps / Release Engineer

### Role Summary
The DevOps / Release Engineer coordinates the systems and operational practices needed to build, deploy, monitor, and safely roll back the product.

### Responsibilities and deliverables
- Maintain or coordinate CI/CD pipelines, build and deployment automation, and environments
- Define release-readiness checks, monitoring and alerting, and rollback or recovery procedures
- Identify reliability and operational risks and document release and runbook information

### Decisions and boundaries
Owns operational readiness practices and advises on deployment safety. Release timing and acceptable business risk are agreed with the Product Manager, Project Manager, and accountable stakeholders; production changes follow the organization’s approval and incident processes.

### Collaboration and lifecycle touchpoints
- Partners with Developers to make builds and deployments repeatable and observable.
- Coordinates with QA / Testing on stable environments, test execution, and release criteria.
- Shares readiness, dependencies, and rollback plans with the Project Manager and Product Manager before a release decision.
- Works with Customer Support / Operations on handoff, monitoring expectations, escalation paths, and post-release follow-up; involves Security / Privacy for relevant controls.

---

## Security / Privacy Lead

### Role Summary
The Security / Privacy Lead helps the team identify and address security, privacy, and compliance risks throughout delivery.

### Responsibilities and deliverables
- Advise on applicable security and privacy requirements, threat scenarios, and data handling
- Coordinate risk reviews and recommend controls, mitigations, or specialist review
- Document findings, unresolved risks, and escalation or incident contacts

### Decisions and boundaries
Provides expert guidance and identifies when required reviews or controls are incomplete. Risk acceptance, compliance determinations, and incident response follow organizational policy and belong to the designated accountable authority; this role does not replace those approvals.

### Collaboration and lifecycle touchpoints
- Works with the Product Manager and stakeholders to clarify data use, user expectations, and requirements.
- Partners with the Technical Lead and Developers to select and implement appropriate controls.
- Helps QA / Testing include security and privacy cases in validation, and coordinates with DevOps / Release on secrets, access, and deployment controls.
- Raises material risks promptly with the Project Manager and accountable stakeholders, and supports operations during incident preparation or response as assigned.

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead helps define how the team will measure product outcomes and ensure that collected data is reliable and appropriately handled.

### Responsibilities and deliverables
- Translate product success measures into instrumentation and reporting requirements
- Define data-quality checks, metric definitions, and analysis or evaluation plans
- Document assumptions, limitations, and relevant data access or retention considerations

### Decisions and boundaries
Owns analytics methods and communicates what the data can and cannot show. The Product Manager owns product goals and prioritization; stakeholders interpret results with context, and data collection must meet applicable privacy and security requirements.

### Collaboration and lifecycle touchpoints
- Aligns with the Product Manager on success metrics and evaluation timing.
- Works with Developers on event definitions, implementation, and data quality; coordinates with QA / Testing to validate instrumentation and reporting.
- Shares understandable findings and caveats with stakeholders and the Project Manager to inform decisions and status updates.
- Consults Security / Privacy when measurement involves personal, sensitive, or regulated data.

---

## Customer Support / Operations Representative

### Role Summary
The Customer Support / Operations Representative brings customer-impact and operational-readiness needs into planning, release, and post-release learning.

### Responsibilities and deliverables
- Identify common customer questions, support impacts, and operational constraints
- Prepare or coordinate support documentation, escalation paths, and service handoff information
- Collect and route customer feedback and production issues after release

### Decisions and boundaries
Advises on supportability and operational impact, and owns or coordinates assigned support processes. Product scope and priority remain with the Product Manager; project communications and delivery coordination remain with the Project Manager. Incidents follow established operational authority and escalation procedures.

### Collaboration and lifecycle touchpoints
- Shares customer needs and recurring issues with the Product Manager and relevant stakeholders during discovery and prioritization.
- Coordinates launch communications, training, and handoff timing with the Project Manager.
- Works with Developers and QA / Testing to reproduce, triage, and communicate issues, and with DevOps / Release on monitoring, runbooks, and escalation paths.
- Returns post-release feedback and operational learnings to the team for follow-up and product evaluation.

---

## QA / Testing

### Role Summary
QA / Testing is the function responsible for providing evidence that the solution meets agreed requirements and for surfacing quality risks. It may be performed by dedicated testers, Developers, or a combination, but test ownership should be explicit.

### Responsibilities
- Plan and execute appropriate functional, integration, regression, and other risk-based testing
- Record results, defects, and coverage gaps; verify fixes
- Coordinate with role owners to make requirements and acceptance criteria verifiable

### Collaboration and boundaries
QA / Testing provides quality evidence and recommendations; the team and designated release decision-makers use that evidence to make readiness decisions. QA / Testing works with the Product Manager on acceptance criteria, Designers on expected user experience, Developers and the Technical Lead on testability and defect resolution, and DevOps / Release on environments and release checks. It also validates relevant security, privacy, analytics, and support scenarios with those role owners.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These are adaptable areas of responsibility, not mandatory separate hires. At kickoff, identify an accountable owner for each area needed by the project, note where roles are combined, and agree on decision and escalation paths.
