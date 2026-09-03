# OctoAcme Project Management Docs

## Project Management Processes Summary

OctoAcme uses a customer-first, iterative lifecycle with clear ownership, measurable outcomes, and continuous improvement. Work begins with initiation, where teams validate the problem, identify stakeholders, define success metrics, assess initial risks, and confirm the resources needed to plan. Planning turns approved work into a prioritized, estimated backlog of shippable increments, with acceptance criteria, a Definition of Done, dependencies, milestones, and a release plan.

During execution, delivery teams track work through Backlog, Ready, In Progress, In Review, QA, and Done, while using regular standups, delivery syncs, and sprint or milestone demos to surface progress, blockers, and risks. Project Managers coordinate delivery, timelines, risks, and communication; Product Managers define outcomes and priorities; developers implement, test, and review work; QA validates acceptance criteria; and stakeholders provide input and approvals. Status is maintained through a single source of truth, regular stakeholder updates, and escalation from team triage through the PM, Product Lead, and sponsor as needed.

Quality assurance is integrated throughout delivery: pull requests reference their issue and acceptance criteria, receive review, and pass automated tests and linting before merge. Teams use unit tests for new logic, integration tests where appropriate, smoke tests for critical flows, CI security scanning, and manual QA when required for feature acceptance. Releases require completed acceptance criteria, passing CI and security checks, release notes, smoke-test preparation, rollback planning, post-deployment verification, and stakeholder communication. Retrospectives after sprints, releases, milestones, and incidents convert learnings into owned, tracked improvements.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, lifecycle, artifacts, and communication cadence.
- [Project Initiation](octoacme-project-initiation.md) — Validating and authorizing work, stakeholders, and the project one-pager.
- [Project Planning](octoacme-project-planning.md) — Backlogs, estimates, Definition of Done, dependencies, and releases.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Team rhythm, board workflow, quality checks, and escalation.
- [Risk Management and Communication](octoacme-risks-and-communication.md) — Risk registers, status updates, and escalation paths.
- [Release and Deployment](octoacme-release-and-deployment.md) — Release preparation, deployment, verification, and rollback.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Learning, action items, and iterative improvement.
- [Roles and Personas](octoacme-roles-and-personas.md) — Responsibilities and communication patterns for OctoAcme roles.
