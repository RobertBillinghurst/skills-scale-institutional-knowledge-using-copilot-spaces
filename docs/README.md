# OctoAcme Project Management Docs

This README serves as the entry point to OctoAcme's project management process documentation. It is intended for new team members, contributors, and stakeholders who want to understand how projects are planned, delivered, and improved at OctoAcme.

## Overview

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle that emphasizes clear ownership, iterative delivery, and measurable outcomes. Work moves through five phases: **initiation** (align on problem, goal, stakeholders, and success metrics), **planning** (turn the initiative into an actionable backlog and release plan), **execution** (deliver in small increments with strong tracking), **release** (deploy with safeguards and clear communication), and **retrospective/continuous improvement** (capture learnings and feed improvements back into the backlog). Across all phases, the process prioritizes customer value, transparency, and data-informed decision-making, with project artifacts such as a charter/one-pager, backlog with acceptance criteria, risk register, and retrospective action items serving as the consistent source of truth.

Roles are explicitly defined to ensure accountability and reduce ambiguity. A **Project Manager (PM)** coordinates delivery, schedules, risks, and communications, while a **Product Manager (PdM/Product Lead)** owns outcomes, backlog prioritization, and measurement of success. **Developers** are responsible for designing and implementing features, maintaining tests and documentation, and participating in estimation and reviews. **QA/Testing** validates quality and acceptance criteria, and **Stakeholders** provide inputs and approvals. These personas are used consistently across the process docs to clarify who owns which decisions and which deliverables must exist before work advances to the next phase — initiation and planning checklists act as decision gates.

Communication is structured around a steady team rhythm plus targeted stakeholder updates. Execution is supported by short daily standups (focused on progress, blockers, and dependencies), a weekly delivery sync to show progress and flag risks, and a demo/review at the end of each sprint or milestone. Stakeholder updates are delivered on a regular cadence (weekly or milestone-based) using a consistent status template covering progress, next steps, risks/blockers, and decisions needed, with a single source of truth maintained in the project repository. Risks and dependencies are tracked via a risk register and reviewed routinely, with defined escalation paths that move from team triage to PM-led escalation, then to the product lead and sponsors as needed.

Quality assurance is embedded throughout delivery via both workflow standards and testing expectations. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and delivered through a pull request workflow that favors small PRs, links to issues and acceptance criteria, and requires passing CI (tests, linting, security scanning) before review and merge. Testing expectations include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows prior to release, supplemented by manual QA for feature acceptance when needed. Releases follow a standardized checklist (acceptance criteria met, scans passing, release notes and rollback plan prepared, staged deployment with verifications), and retrospectives after sprints, releases, and incidents turn learnings into owned, time-bound action items tracked like any other backlog work.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle, and communication cadence. |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a project: problem statement, stakeholders, charter, and initiation checklist. |
| [Project Planning](octoacme-project-planning.md) | Scope, backlog, milestones, dependencies, and the planning checklist. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint workflow, project board, standups, and tracking progress. |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, communication templates, escalation paths, and status updates. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment process, rollback plan, and incident response. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action items, and feeding learnings back into the backlog. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role. |
