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

## Business Sponsor

### Role Summary
Business Sponsors represent the strategic owner of the initiative and ensure the work remains aligned to business goals, funding, and executive priorities.

### Responsibilities
- Confirm business value and expected outcomes
- Sponsor funding, staffing, and key decisions when needed
- Align the project with broader business strategy and stakeholder priorities
- Help resolve escalations that impact scope, budget, or timing
- Review progress against outcomes and approve major milestones

### Goals
- Ensure strategic alignment and investment value
- Remove organizational barriers to delivery
- Support successful adoption and measurable business impact

### Typical Communication
- Steering committee updates and milestone reviews
- Executive summaries and approval checkpoints
- Escalation discussions when trade-offs are needed

### Interaction with Existing Roles
- Works with the Product Manager to confirm priorities and business outcomes
- Partners with the Project Manager to support scope, timeline, and decision-making
- Provides context for Developers and QA teams when trade-offs affect delivery or release readiness
- Helps Stakeholders understand why the initiative matters and what success looks like

---

## Release Manager / Delivery Enablement Lead

### Role Summary
Release Managers coordinate launch readiness, deployment execution, and communication so changes move to production with clear ownership and minimal disruption.

### Responsibilities
- Coordinate release planning, deployment windows, and rollback readiness
- Align engineering, support, and stakeholder communication before launch
- Validate operational readiness, verification steps, and release notes
- Help manage dependencies across teams during production rollout
- Support post-release monitoring and issue triage

### Goals
- Reduce release risk and production disruption
- Improve deployment predictability and operational confidence
- Ensure communication is clear before, during, and after launch

### Typical Communication
- Release checklists and launch readiness reviews
- Deployment coordination across engineering and support teams
- Incident or rollback communications when needed

### Interaction with Existing Roles
- Works closely with Project Managers to align milestones and deployment timing
- Collaborates with Developers to confirm release scope and rollback options
- Coordinates with QA/Test Lead on validation evidence and production readiness
- Supports Support / Operations representatives during launch and post-release stabilization

---

## QA / Test Lead

### Role Summary
QA / Test Leads define the quality strategy, validate that requirements are met, and help teams release products with confidence.

### Responsibilities
- Define test strategy, regression coverage, and acceptance validation plans
- Review requirements and acceptance criteria for testability
- Own test execution, defect triage, and release-quality signoff
- Partner with engineering to prioritize bug fixing and quality gates
- Measure and communicate quality risk before release

### Goals
- Improve confidence in product quality and release readiness
- Catch defects early and reduce downstream customer impact
- Align validation work with project goals and milestones

### Typical Communication
- Test plans, defect reviews, and quality signoff discussions
- Daily or sprint-level quality updates with engineering leads
- Release readiness summaries for PMs and sponsors

### Interaction with Existing Roles
- Partners with Developers on quality standards and automated testing coverage
- Works with Product Managers to validate that acceptance criteria reflect customer expectations
- Coordinates with the Release Manager to confirm production readiness and smoke test coverage
- Escalates blockers to the Project Manager when quality issues affect delivery or release dates

---

## Security / Compliance Partner

### Role Summary
Security and Compliance Partners ensure the project follows required controls, policies, and risk practices so that delivery stays safe, compliant, and resilient.

### Responsibilities
- Review risks related to data, access, privacy, and infrastructure security
- Validate compliance with internal standards, regulatory requirements, and security policies
- Help identify mitigation strategies for high-risk changes or sensitive work
- Participate in threat reviews, secure design discussions, and release risk checks
- Support escalation paths for incident response or policy exceptions

### Goals
- Reduce security and compliance risk across the lifecycle
- Protect customer trust, data integrity, and business continuity
- Enable secure delivery without unnecessary delays

### Typical Communication
- Security reviews, policy updates, and risk summaries
- Compliance checkpoints tied to projects or milestones
- Incident coordination when urgent action is needed

### Interaction with Existing Roles
- Provides guidance to Developers and QA teams on secure design and testing requirements
- Supports Product Managers and Sponsors when business decisions involve risk trade-offs or governance needs
- Coordinates with the Project Manager on dependency tracking and escalation plans
- Works with Release Managers to assess launch readiness and incident response readiness

---

## Support / Operations Representative

### Role Summary
Support and Operations representatives ensure the team considers the real-world operational impact of a project, including service health, supportability, and post-release operations.

### Responsibilities
- Review operational readiness for new features, services, or process changes
- Define monitoring, alerting, and escalation expectations
- Help prepare support documentation, failure handling, and service ownership
- Participate in launch reviews and post-release stabilization efforts
- Gather feedback from operational teams to improve product reliability and usability

### Goals
- Minimize service disruption and support burden after launch
- Improve system reliability and response readiness
- Ensure teams can support and maintain the solution over time

### Typical Communication
- Operational readiness reviews and support handoff discussions
- Runbooks, incident updates, and support escalation workflows
- Post-release feedback loops with engineering and product teams

### Interaction with Existing Roles
- Partners with Developers and QA to validate supportability and monitoring requirements
- Coordinates with the Release Manager on deployment verification and post-launch support
- Provides stakeholder context to Product Managers and Project Managers about operational impact and user experience
- Helps Business Sponsors understand service quality expectations and adoption readiness

---

## Customer / User Advocate

### Role Summary
Customer and User Advocates represent end-user needs, feedback, and adoption considerations to keep the project grounded in real-world value.

### Responsibilities
- Bring customer or user perspective into planning and prioritization
- Validate problems, expectations, and outcomes with real-world use cases
- Help the team interpret feedback, usage trends, and adoption barriers
- Participate in user research, usability reviews, and stakeholder feedback sessions
- Advocate for clarity, accessibility, and customer experience in delivery decisions

### Goals
- Ensure the solution delivers meaningful value to the target audience
- Improve usability, adoption, and customer satisfaction
- Keep teams focused on outcomes rather than output alone

### Typical Communication
- Customer interviews, usability findings, and feedback summaries
- Stakeholder briefings and adoption readiness reviews
- Product or roadmap discussions tied to user value

### Interaction with Existing Roles
- Provides insight to Product Managers and sponsors when prioritization or scope trade-offs are needed
- Helps Developers and QA teams understand user expectations and acceptance criteria
- Partners with Project Managers to flag resourcing, timing, or communication needs that affect adoption
- Supports stakeholder alignment by translating user needs into shared language and prioritization

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles create a clearer map of accountability, decision-making, and collaboration across planning, delivery, quality, release, and adoption.

