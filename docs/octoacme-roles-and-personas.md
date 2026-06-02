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

## Additional Suggested Personas (NEW)

### Release Manager
- Responsibilities:
  - Coordinates and owns release planning and execution.
  - Maintains the release checklist, verifies pre-release criteria (CI, security scans, smoke tests).
  - Schedules deployment windows and coordinates rollback/mitigation plans.
  - Communicates release status to stakeholders and support teams.
- Interactions:
  - Works closely with Project Manager for timing and risk assessment.
  - Partners with Developers and QA to ensure release readiness.
  - Notifies Product Manager and Stakeholder Advocate of release impacts.

### QA Lead
- Responsibilities:
  - Owns QA strategy and test plan for releases and major features.
  - Coordinates test runs (unit, integration, regression, E2E smoke).
  - Tracks defects and ensures they are triaged and prioritized.
  - Maintains test-environment readiness and test data management.
- Interactions:
  - Collaborates with Developers on defect reproduction and fixes.
  - Works with Product Manager to understand acceptance criteria.
  - Provides Release Manager confidence checks before deployment.

### UX / Design Lead
- Responsibilities:
  - Leads user experience design, prototyping, and usability validation.
  - Ensures accessibility standards and design system consistency.
  - Conducts or coordinates user research and feedback cycles.
- Interactions:
  - Partners with Product Manager on user needs and acceptance criteria.
  - Handoffs designs and specs to Developers; iterates during implementation.
  - Works with QA to validate visual/UX acceptance criteria.

### Stakeholder Advocate
- Responsibilities:
  - Acts as the primary liaison for external or cross-functional stakeholders (customers, sales, support).
  - Aggregates stakeholder feedback and ensures it is considered in prioritization.
  - Communicates tradeoffs and impacts back to stakeholders.
- Interactions:
  - Works with Product Manager to translate stakeholder needs into backlog requests.
  - Keeps Project Manager informed about stakeholder constraints and deadlines.
  - Coordinates stakeholder-facing communications with the Release Manager.

### Platform / SRE Lead (optional)
- Responsibilities:
  - Ensures operational readiness, monitoring, and runbook coverage.
  - Coordinates platform changes, capacity planning, and incident response readiness.
- Interactions:
  - Works with Release Manager for deployment impacts.
  - Partners with Developers and QA on performance and reliability testing.

---

## Using these Personas
- Each project should name primary and backup owners for roles where possible (e.g., "QA Lead: @username, backup: @username").
- When a role is not assigned, the Project Manager should capture who will pick up the responsibilities for that delivery.
- Add persona owners to release notes and relevant issues when their responsibilities are required (e.g., QA Lead sign-off for a release).
