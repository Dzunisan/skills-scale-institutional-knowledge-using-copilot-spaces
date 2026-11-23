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

## QA / Test Engineers

### Role Summary
QA / Test Engineers make sure each increment meets its acceptance criteria and the Definition of Done before it is released.

### Responsibilities
- Write the test strategy and test plans for each milestone
- Review acceptance criteria during planning so they can be tested
- Run manual and exploratory tests; maintain automated smoke tests
- Report defects with clear steps to reproduce
- Give quality sign-off before a release

### Goals
- Find defects early, before production
- Keep release quality high and predictable

### Typical Communication
- Defect reports and test results in issues and PRs
- Quality status in the weekly delivery sync

### Works With
- **Developers**: pair on test coverage and fix defects
- **Product Managers**: clarify acceptance criteria
- **Release Manager**: give the quality sign-off for each release

---

## Release Managers

### Role Summary
Release Managers own the path from merged code to production. They make releases safe, planned and well communicated.

### Responsibilities
- Own the release checklist and deployment window
- Confirm CI, security scans and smoke tests pass before release
- Make sure a rollback / mitigation plan exists
- Publish release notes and announce releases to stakeholders and support

### Goals
- Release often with low risk
- Recover quickly if a release fails

### Typical Communication
- Release plans, release notes and go/no-go calls
- Post-deploy status updates

### Works With
- **Project Managers**: align release dates with the milestone plan
- **QA / Test Engineers**: get quality sign-off
- **Developers**: coordinate hotfixes and rollbacks

---

## Stakeholders / Business Sponsors

### Role Summary
Stakeholders and Business Sponsors fund and approve the work. They make the final scope and go/no-go decisions.

### Responsibilities
- Approve the project one-pager, scope and budget
- Make go/no-go decisions at initiation and major milestones
- Act as the escalation point for high risks and trade-offs
- Review demos and give feedback

### Goals
- Make sure the project delivers business value
- Keep decisions timely and clear

### Typical Communication
- Milestone reviews and demos
- Escalations from the Project Manager

### Works With
- **Project Managers**: receive status, risks and escalations
- **Product Managers**: agree on outcomes and priorities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

