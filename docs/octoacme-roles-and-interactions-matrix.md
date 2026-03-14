# OctoAcme — Roles & Interactions Matrix

## Purpose
Provide a RACI-style reference showing which roles are **Responsible (R)**, **Accountable (A)**, **Consulted (C)**, or **Informed (I)** for key project artifacts and ceremonies.

> **Legend:** R = Responsible (does the work) · A = Accountable (final sign-off) · C = Consulted (input required) · I = Informed (kept up to date)

---

## RACI Matrix

| Artifact / Ceremony | Project Manager | Product Manager | Tech Lead | Developer | UX Designer | Business Analyst | Scrum Master | Release Manager | Security Engineer | SRE / DevOps | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Project Charter / One-pager | A/R | C | C | I | I | C | I | I | I | I | C |
| Stakeholder Alignment & Comms | A/R | C | I | I | I | C | I | I | I | I | I |
| Requirements & User Stories | C | A | C | C | C | R | C | I | C | I | C |
| Backlog Prioritization | C | A/R | C | C | C | C | C | I | I | I | C |
| Definition of Done (DoD) | C | C | A/R | R | C | C | R | C | C | C | I |
| Sprint / Iteration Planning | C | C | C | R | C | C | A/R | I | I | I | I |
| Daily Standup | I | I | C | R | R | R | A/R | I | I | I | I |
| UX Research & Design Specs | I | C | C | C | A/R | C | I | I | I | I | I |
| Architecture / Technical Design | C | C | A/R | R | I | C | I | I | C | C | I |
| Risk Register | A/R | C | C | C | I | C | C | C | C | C | I |
| Security Review / Threat Model | C | I | C | C | I | I | I | C | A/R | C | I |
| Release Plan | A | C | C | I | I | I | C | R | C | C | I |
| Release Go/No-Go | A | C | C | I | I | I | I | R | C | C | I |
| Deployment & Rollback | C | I | C | C | I | I | I | A | C | R | I |
| Release Notes | C | C | C | R | C | C | I | A/R | I | I | I |
| Stakeholder Updates | A/R | C | I | I | I | C | I | C | I | I | I |
| Sprint Review / Demo | C | C | C | R | R | R | A/R | I | I | I | C |
| Retrospective | C | C | C | R | R | R | A/R | C | I | I | I |
| Incident Post-mortem | C | I | C | C | I | I | I | C | C | A/R | I |

---

## Key Interaction Pairs

The following pairs have frequent, structured interactions across the project lifecycle:

| Pair | Primary Interaction |
|---|---|
| Project Manager ↔ Product Manager | Weekly sync on scope, priorities, and stakeholder status |
| Product Manager ↔ Business Analyst | Backlog refinement and requirements validation |
| Product Manager ↔ UX Designer | User research, design reviews, and feature acceptance |
| Tech Lead ↔ Developers | Code reviews, architecture guidance, and mentoring |
| Scrum Master ↔ Developers | Sprint ceremonies, impediment removal, and agile coaching |
| Release Manager ↔ SRE / DevOps | Deployment coordination, pipeline readiness, and rollback |
| Release Manager ↔ Security Engineer | Security sign-off before go/no-go |
| Project Manager ↔ Release Manager | Milestone alignment and stakeholder communication |
| Business Analyst ↔ Developers | Requirement clarification and acceptance validation |
| UX Designer ↔ Developers | Design handoff and implementation review |

---

## Project Kickoff Checklist

Use this checklist at the start of every project to ensure all roles are identified and aligned.

- [ ] Project Charter / One-pager drafted and shared
- [ ] Project Manager and Product Manager assigned
- [ ] Tech Lead identified and engaged
- [ ] UX Designer included if there are user-facing components
- [ ] Business Analyst engaged if requirements complexity warrants it
- [ ] Scrum Master / Agile Coach assigned (if using agile ceremonies)
- [ ] Release Manager identified for the release plan
- [ ] Security Engineer consulted for threat modeling
- [ ] SRE / DevOps Engineer aligned on infrastructure and pipeline needs
- [ ] Stakeholders identified and communication cadence agreed
- [ ] Risk Register initialized
- [ ] Definition of Done agreed

---

## Release Readiness Checklist

Use this checklist before any production release to confirm readiness.

- [ ] All acceptance criteria met and verified by Product Manager or Business Analyst
- [ ] Pull requests merged and CI passing
- [ ] Security scan completed and issues triaged (Security Engineer sign-off)
- [ ] UX / design review completed for user-facing changes
- [ ] Release notes drafted and reviewed (Product Manager)
- [ ] Staging deployment successful and smoke tests passed
- [ ] Rollback plan documented (Release Manager + SRE/DevOps)
- [ ] Deployment window confirmed and stakeholders notified (Release Manager)
- [ ] Support team briefed on new features and known issues
- [ ] Go/No-Go decision recorded

---

_For full role descriptions and responsibilities, see [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md)._
