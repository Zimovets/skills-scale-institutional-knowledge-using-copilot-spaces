# OctoAcme Project Management Docs

Welcome! This is the central index for OctoAcme's project management process documentation. Use this README to quickly understand how the team delivers work and to navigate directly to the relevant process guides.

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. In initiation, the team validates an idea with a concise one-pager covering the problem, goal, and success metrics, identifies stakeholders, drafts a high-level timeline and initial risks, and makes an explicit go/no-go decision before investing in detailed planning. Once approved, planning turns the initiative into an actionable backlog of shippable increments with acceptance criteria, estimates, dependencies, a release/milestone map, and a documented Definition of Done (DoD).

Roles are clearly defined to ensure ownership and smooth cross-functional delivery. A **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; a **Product Manager (PdM/Product Lead)** defines outcomes, prioritizes work, and measures success; **Developers** design, implement, and document solutions; **QA/Testing** validates acceptance criteria and quality gates; and **Stakeholders** provide input and approvals. Work is managed in a shared project board (e.g., GitHub Projects) with standard states—Backlog, Ready, In Progress, In Review, QA, and Done—and delivery is supported by a pull request workflow that emphasizes small changes, clear acceptance criteria, and required review approvals.

Communication is structured around a consistent team rhythm and transparent escalation. OctoAcme uses short daily standups to surface progress and blockers, weekly delivery syncs to review progress and risks, and demos/reviews at the end of each sprint or milestone. Stakeholder updates follow a regular cadence (weekly PM+PdM alignment and periodic stakeholder communication) supported by simple status templates. Risks and dependencies are tracked in a maintained risk register and escalated through defined levels—from team triage, to PM + product lead coordination, to sponsor escalation for business-impacting issues.

Quality assurance is embedded throughout delivery and release. New logic includes unit tests, with integration tests where appropriate, plus end-to-end smoke tests for critical flows before release. CI runs automated tests, linting, and security scanning prior to review and merge. Releases require confirmed acceptance criteria, passing checks, release notes, and a rollback/mitigation plan, with staged deployment and post-deploy verification. After sprints, milestones, or incidents, retrospectives capture what worked, what didn't, and a small set of owned action items that feed back into the backlog for continuous improvement.

## Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
