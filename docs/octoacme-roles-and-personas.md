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

## Release Managers

### Role Summary
Release Managers coordinate the path from completed work to a safe, observable production release. They make release readiness and handoffs explicit without taking ownership of product priority or implementation.

### Responsibilities
- Maintain the release plan, checklist, and deployment window
- Confirm acceptance criteria, CI, security checks, release notes, and rollback plans are complete
- Coordinate staging validation, go/no-go decisions, and post-deployment verification
- Track release risks, dependencies, and follow-up actions

### Goals
- Make releases predictable, low-risk, and well communicated
- Ensure every release has a clear owner, rollback path, and verification plan

### Collaboration
- The PM aligns release milestones, dependencies, and stakeholder communications with the project plan.
- The Product Manager confirms scope, customer value, and the decision to release.
- Developers and QA/Testing provide build status, test evidence, smoke tests, and technical mitigations.
- Stakeholders receive readiness updates and release announcements, and provide approval when required.

---

## Technical Leads

### Role Summary
Technical Leads guide technical direction and engineering decisions for a project. They help the team make sustainable trade-offs while Developers remain accountable for implementation.

### Responsibilities
- Define or review technical approach, interfaces, and architectural decisions
- Break down complex work and identify technical dependencies and risks
- Support estimates, design reviews, code reviews, and incident response
- Keep technical decisions and constraints documented and current

### Goals
- Deliver a coherent, maintainable solution that can evolve safely
- Resolve technical ambiguity early and reduce delivery risk

### Collaboration
- The PM uses the Technical Lead's estimates, risks, and dependencies in plans and escalations.
- The Product Manager collaborates on feasibility and scope trade-offs.
- Developers receive direction, review, and support while owning the code they deliver.
- QA/Testing partners on testability, quality risks, and non-functional acceptance criteria.
- Stakeholders receive clear explanations of technical impact when decisions affect scope, timeline, or risk.

---

## Business Analysts

### Role Summary
Business Analysts translate business needs and stakeholder input into clear, traceable requirements. They clarify the problem and expected behavior without replacing the Product Manager's prioritization decisions.

### Responsibilities
- Elicit, document, and validate business processes, requirements, and constraints
- Identify gaps, assumptions, dependencies, and edge cases
- Maintain traceability from goals and requirements to backlog items and acceptance criteria
- Support walkthroughs and clarify questions during delivery and acceptance

### Goals
- Give the team a shared understanding of the problem and intended outcome
- Reduce rework caused by ambiguous or incomplete requirements

### Collaboration
- The PM relies on the Business Analyst to surface dependencies, decisions, and unresolved questions.
- The Product Manager validates value, priority, and scope.
- Developers use clarified requirements and edge cases during design and implementation.
- QA/Testing turns validated requirements into test scenarios and confirms coverage.
- Stakeholders validate business workflows and approve requirements or changes within their authority.

---

## UX Designers

### Role Summary
UX Designers make products understandable, accessible, and useful by representing user needs in the solution design. They partner with the Product Manager on experience outcomes and with Developers on feasible implementation.

### Responsibilities
- Research user needs and map relevant journeys or workflows
- Create and document flows, wireframes, prototypes, and interaction decisions
- Define usability and accessibility considerations for acceptance
- Validate designs with users or stakeholders and incorporate feedback

### Goals
- Deliver an experience that solves the intended user problem and is inclusive
- Identify usability issues before implementation or release

### Collaboration
- The PM coordinates design milestones, decisions, and dependencies.
- The Product Manager aligns user research and designs to product outcomes and priorities.
- Developers review feasibility, estimate design-related work, and implement the approved experience.
- QA/Testing verifies user flows, accessibility expectations, and visual or interaction acceptance criteria.
- Stakeholders provide domain context and review designs without bypassing the agreed prioritization process.

---

## Security and Compliance Reviewers

### Role Summary
Security and Compliance Reviewers identify security, privacy, regulatory, and policy obligations throughout the lifecycle. They provide risk-based guidance and approvals where required.

### Responsibilities
- Identify applicable threats, data handling requirements, and compliance controls
- Review designs, implementation plans, and release evidence for security and compliance risks
- Define required mitigations, approvals, and evidence before release
- Track exceptions and escalate unacceptable residual risk

### Goals
- Protect customers, data, and the organization while enabling delivery
- Prevent late security or compliance surprises and make risk decisions auditable

### Collaboration
- The PM records review work, risks, owners, and deadlines in the project plan and risk register.
- The Product Manager balances customer and business outcomes with security or compliance constraints.
- Developers and the Technical Lead implement mitigations and provide technical evidence.
- QA/Testing includes security, privacy, and compliance checks in the test and release evidence.
- Stakeholders and accountable approvers make informed decisions about residual risk and exceptions.

---

## Support and Operations Representatives

### Role Summary
Support and Operations Representatives bring production-readiness and customer-support expertise into delivery. They help the team prepare to operate, support, and learn from the released product.

### Responsibilities
- Define operational requirements, monitoring, runbooks, and support workflows
- Review release communications, known issues, and customer-facing documentation
- Participate in readiness reviews, deployment verification, and incident follow-up
- Feed production and support trends back into planning and prioritization

### Goals
- Make releases supportable and observable from day one
- Reduce customer disruption and shorten incident response and recovery

### Collaboration
- The PM coordinates operational dependencies, readiness actions, and escalation paths.
- The Product Manager uses customer and support feedback to prioritize improvements.
- Developers and the Technical Lead provide instrumentation, runbooks, and fixes.
- QA/Testing validates critical operational and recovery scenarios alongside feature behavior.
- Stakeholders and support teams receive timely release, impact, and incident communications.

---

## Data and Analytics Owners

### Role Summary
Data and Analytics Owners ensure that product and project decisions can be evaluated with trustworthy data. They define measurement approaches and maintain the metrics or reporting needed to assess outcomes.

### Responsibilities
- Define success metrics, event instrumentation, data sources, and reporting needs
- Validate data quality, privacy considerations, and metric definitions
- Establish baselines and monitor outcomes after release
- Share insights and recommend follow-up actions when results differ from expectations

### Goals
- Make impact visible and support evidence-based prioritization
- Give the team reliable measures for learning, iteration, and accountability

### Collaboration
- The PM tracks measurement dependencies and outcome reviews alongside delivery milestones.
- The Product Manager owns the outcome hypothesis and uses analytics to prioritize decisions.
- Developers implement instrumentation and resolve data-quality issues with the Data and Analytics Owner.
- QA/Testing verifies events, dashboards, and reporting behavior as part of acceptance and release checks.
- Stakeholders align on definitions, review results, and use evidence to approve follow-up work.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
