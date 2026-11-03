# OctoAcme Project Management Docs

This directory contains OctoAcme’s project management processes and role guidance. Together, these documents provide a shared reference for planning and delivering cross-functional projects, communicating progress, managing risks, and improving how the team works.

## How OctoAcme manages projects

OctoAcme’s project lifecycle moves from **initiation** to **planning**, **execution**, **release**, and **retrospective**. Initiation validates the business need, identifies stakeholders and success measures, and establishes whether work should proceed. Planning turns an approved initiative into a prioritized backlog, milestones, estimates, and a Definition of Done. During execution, the team delivers small increments, tracks progress, and addresses blockers. Release guidance sets pre-release checks, deployment steps, and rollback expectations. Retrospectives capture lessons and turn them into owned improvement actions.

Project work is shared across clear roles. The **Project Manager (PM)** coordinates delivery, schedules, risks, dependencies, and communications. The **Product Manager (PdM)** defines outcomes, prioritizes work, and measures success. **Developers** build and test the solution; **QA/Testing** validates quality and acceptance criteria; and **stakeholders** provide input and approvals. The roles-and-personas guide gives more detail on responsibilities and collaboration.

Communication and risk management support delivery throughout the lifecycle. The documented cadence includes regular PM and PdM alignment, delivery-team standups, weekly delivery or status syncs, demos or reviews at sprint or milestone ends, and stakeholder updates. Teams maintain a risk register, review risks and dependencies regularly, and escalate blockers from team-level triage through the PM and Product Lead to the sponsor when needed. For security incidents, teams follow the security incident runbook and notify Security on-call.

Quality is built into planning, implementation, and release. Work should have clear acceptance criteria and a Definition of Done; changes should include appropriate unit and integration tests, with end-to-end smoke tests for critical flows before release. CI should run automated tests and linting, and security scanning is part of the release readiness checks. Teams use manual QA when needed, verify deployments after release, and retain a rollback or mitigation plan.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
