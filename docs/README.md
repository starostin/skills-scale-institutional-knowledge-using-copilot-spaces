# OctoAcme Project Management Docs

This folder centralizes OctoAcme's project management process documentation. It is the single entry point for understanding how cross-functional projects are initiated, planned, executed, released, and continuously improved. All documents are version-controlled so that workflows stay searchable, auditable, and easy to share with new teammates.

## Purpose of This Folder

| Goal | How these docs help |
|------|---------------------|
| **Centralize PM knowledge** | One place for every stage of the project lifecycle |
| **Improve onboarding** | New teammates can read sequentially or jump to the relevant section |
| **Enable consistent execution** | Shared artifacts, checklists, and templates remove ambiguity |
| **Support Copilot Spaces** | Add docs to `.copilot/` so GitHub Copilot can surface them as context |

Whenever a process changes, update the relevant document in this folder and open a pull request so the change is peer-reviewed and traceable.

---

## OctoAcme Project Management — Overview

OctoAcme runs projects using a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. In initiation, teams validate the business need and define success up front via a **Project One-pager** (problem, SMART objective, success metrics), identify stakeholders, outline a high-level timeline, capture early risks, and confirm resourcing and a go/no-go decision to proceed. Planning then converts the approved idea into an actionable delivery plan: a prioritized backlog with acceptance criteria, estimates, a documented **Definition of Done**, and an initial QA/testing approach, alongside explicit tracking of dependencies and risks.

Roles are clearly defined to support "clear ownership." A named **Project Manager (PM)** coordinates delivery logistics — timeline, risks, dependencies, and communications — while a **Product Manager (PdM/Product Lead)** owns outcomes, prioritization, and measuring impact. **Developers** implement features, contribute to estimates, and uphold testability and maintainability, while **QA/Testing** validates quality and acceptance criteria. Stakeholders provide input and approvals at agreed checkpoints, and the process emphasizes psychological safety and iterative delivery so teams can ship in small, testable increments and adjust based on evidence.

Day-to-day execution is managed with a project board (e.g., GitHub Projects) and a consistent workflow from **Backlog → Ready → In Progress → In Review → QA → Done**. The team maintains a steady operating rhythm with **daily standups** for progress/blockers, a **weekly delivery sync** for updates and risk flags, and **demos/reviews** at sprint or milestone boundaries. Risk management is continuous: teams keep a simple **risk register** (impact, likelihood, owner, mitigation, status), review it regularly, and escalate blockers through a defined path (team triage → PM/Product Lead → sponsor-level if business-impacting).

Quality is built into both development and release practices. OctoAcme favors **small PRs**, requires clear PR context (issue links and acceptance criteria), and expects CI to run tests/linting before review, with at least one approval required per team policy. Testing includes unit tests for new logic, integration tests where needed, and end-to-end smoke tests for critical flows prior to release, supported by security scanning in CI and manual QA when appropriate. Releases follow a standardized checklist (acceptance criteria met, CI/security passing, release notes and rollback plan prepared), deploy through staging with smoke tests, verify post-deploy, and communicate outcomes to stakeholders; afterwards, retrospectives convert learnings into owned action items that feed back into the backlog for continuous improvement.

---

## Process Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation](octoacme-project-initiation.md) | One-pager template, stakeholder identification, go/no-go decision |
| [Project Planning](octoacme-project-planning.md) | Backlog setup, Definition of Done, dependency and risk tracking |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Board workflow, standups, delivery sync cadence, escalation path |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, communication plan, stakeholder updates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release checklist, staging, smoke tests, rollback plan, announcements |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro format, action items, feeding learnings back into the backlog |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication norms for each role |

---

## How to Update These Docs

1. Open a new branch and edit the relevant Markdown file(s).
2. Submit a pull request — link it to the related issue if one exists.
3. Request a review from the PM or process owner before merging.
4. If the change affects how Copilot Spaces surfaces guidance, update `.copilot/` accordingly.
