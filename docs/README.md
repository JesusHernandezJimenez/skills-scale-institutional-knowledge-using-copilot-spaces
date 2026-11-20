# OctoAcme Project Management Docs

## Overview

OctoAcme manages cross-functional projects with a customer-first mindset and an emphasis on iterative delivery, clear ownership, data-informed decisions, and psychological safety. Projects are guided through a shared lifecycle, with a named Project Manager (PM) coordinating delivery and communication and a Product Manager (PdM) owning outcomes and prioritization. Developers, QA, and stakeholders collaborate to deliver measurable value and learn from each release.

## Project lifecycle

1. **Initiation:** Validate the business need, define the goal and success metrics, identify stakeholders and champions, estimate resource needs, and decide whether to proceed to planning. The core artifact is a reviewed project one-pager.
2. **Planning:** Hold a kickoff, shape and prioritize a backlog with acceptance criteria, estimate work, define the Definition of Done, identify risks and dependencies, and agree on milestones and a release plan.
3. **Execution and tracking:** Deliver in small increments and track work on a project board. Use regular standups, delivery syncs, and demos to surface progress and blockers. Keep risks and dependencies visible, communicate status from a shared source of truth, and escalate issues through the defined path when needed.
4. **Release and deployment:** Confirm acceptance criteria, passing CI and security checks, release notes, smoke tests, and a rollback or mitigation plan. Deploy, verify the release, and communicate it to stakeholders and support.
5. **Closeout and continuous improvement:** Hold retrospectives after sprints, releases, milestones, or incidents. Record a small number of actionable improvements with owners, due dates, and success criteria, then follow up on their impact.

## Quality and communication

Quality is built into delivery through unit and applicable integration tests, automated CI testing and linting, security scanning, end-to-end smoke tests for critical flows, and manual QA where needed. Pull requests should be small when practical, link the relevant issue and acceptance criteria, and receive the required review before merging.

The team uses daily standups for progress and blockers, weekly delivery and PM/PdM alignment, demos at sprint or milestone boundaries, and regular stakeholder updates. The PM coordinates schedules, risks, dependencies, and communications; the PdM defines outcomes and prioritizes the backlog; developers build and test; QA validates acceptance; and stakeholders provide input and approvals. Risks are reviewed regularly and escalated from the team to the PM, Product Lead, and Sponsor according to impact.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — principles, roles, lifecycle, artifacts, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validation, one-pager, stakeholder alignment, and the decision gate for planning.
- [Project Planning](octoacme-project-planning.md) — kickoff, backlog, estimates, Definition of Done, risks, dependencies, and milestones.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — team rhythm, project board, pull request workflow, quality practices, and escalation.
- [Risk Management and Communication](octoacme-risks-and-communication.md) — risk register, stakeholder updates, incident communications, and escalation paths.
- [Release and Deployment Guide](octoacme-release-and-deployment.md) — pre-release requirements, deployment checklist, rollback, and release notes.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospective structure, action items, and follow-up.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for developers, Product Managers, and Project Managers.
