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

## UX Designer

### Role Summary
UX Designers lead user research and interface design to ensure products are usable, accessible, and aligned with customer needs. They bridge the gap between user expectations and technical implementation.

### Responsibilities
- Plan and conduct user research, usability testing, and accessibility reviews
- Create wireframes, prototypes, and design specs
- Collaborate with Product Managers to translate requirements into user flows
- Review implemented features to verify design fidelity
- Maintain design system and component library contributions

### Goals
- Deliver intuitive, accessible user experiences
- Reduce rework by validating designs before development begins
- Ensure usability and accessibility standards are met

### Typical Communication
- Design reviews with Developers and Product Managers
- Usability test reports and research summaries
- Annotated prototypes and design specs in shared design tools

### Interactions with Existing Roles
- **Product Managers**: align on user needs, feature requirements, and success metrics
- **Developers**: hand off designs, clarify implementation questions, and review built UIs
- **Project Managers**: surface design dependencies and flag timeline risks from design iteration

---

## Business Analyst

### Role Summary
Business Analysts clarify requirements, map business processes, and ensure project outcomes align with organizational goals. They act as a bridge between business stakeholders and the delivery team.

### Responsibilities
- Elicit, document, and validate requirements with stakeholders
- Map current and future-state business processes
- Write clear acceptance criteria and user stories
- Validate delivered solutions against business goals
- Support change management and process adoption

### Goals
- Ensure requirements are complete, unambiguous, and prioritized
- Reduce defects caused by misunderstood requirements
- Align delivered features to measurable business outcomes

### Typical Communication
- Requirements workshops with stakeholders and Product Managers
- User stories and acceptance criteria in the backlog
- Gap analysis and process flow diagrams

### Interactions with Existing Roles
- **Product Managers**: collaborate on backlog refinement and acceptance criteria
- **Developers**: answer clarifying questions and validate implementations against requirements
- **Project Managers**: provide input on scope changes, risk, and stakeholder dependencies
- **Stakeholders**: facilitate requirements gathering and validate proposed solutions

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They protect team focus and continuously improve delivery efficiency.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and remove blockers and impediments
- Coach team members on agile principles and practices
- Track and report team metrics (velocity, cycle time, impediment logs)
- Support continuous improvement initiatives from retrospectives

### Goals
- Maintain a predictable, sustainable delivery cadence
- Foster a culture of continuous improvement and psychological safety
- Remove friction so the team can focus on delivering value

### Typical Communication
- Daily standup facilitation
- Sprint retrospective reports and action item tracking
- Impediment logs and escalation summaries

### Interactions with Existing Roles
- **Project Managers**: align on delivery timelines, escalations, and organizational dependencies
- **Product Managers**: support backlog refinement and sprint goal clarity
- **Developers**: coach on agile practices and facilitate technical retrospectives
- **Stakeholders**: communicate sprint outcomes and manage expectations at demos

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and communicate software releases. They own the release process end-to-end — from readiness checks through deployment and post-release verification.

### Responsibilities
- Define and maintain the release plan and calendar
- Coordinate release readiness across development, QA, and operations
- Own the deployment checklist and go/no-go decisions
- Communicate release status and outcomes to stakeholders and support teams
- Manage rollback plans and post-release incident coordination

### Goals
- Deliver releases on schedule with minimal risk and disruption
- Ensure all stakeholders are informed and prepared
- Drive continuous improvement of the release process

### Typical Communication
- Release readiness calls and go/no-go meetings
- Release notes and stakeholder announcements
- Post-release retrospectives and incident reports

### Interactions with Existing Roles
- **Developers**: coordinate code freeze, merge readiness, and release branch management
- **Project Managers**: align release dates with project milestones and stakeholder commitments
- **Product Managers**: confirm feature scope and release notes content
- **QA/Testing**: confirm sign-off and smoke test results before go/no-go
- **Support/Stakeholders**: communicate release timelines and known issues

---

## Tech Lead / Engineering Lead

### Role Summary
Tech Leads provide technical direction and ensure high engineering standards across the project. They bridge the gap between architecture decisions and day-to-day development work.

### Responsibilities
- Define technical architecture and guide key design decisions
- Review and approve significant code changes and pull requests
- Identify and mitigate technical debt and systemic risks
- Mentor Developers and facilitate technical knowledge sharing
- Coordinate with cross-functional teams on integration and API contracts

### Goals
- Maintain a healthy, scalable codebase
- Ensure technical decisions align with business and product goals
- Grow the engineering team's capabilities

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code review feedback and pairing sessions
- Engineering syncs and tech retrospectives

### Interactions with Existing Roles
- **Developers**: provide technical guidance, code reviews, and mentoring
- **Product Managers**: advise on technical feasibility and trade-offs
- **Project Managers**: surface technical risks and dependency blockers
- **Release Manager**: confirm technical readiness for release

---

## Security Engineer

### Role Summary
Security Engineers embed security practices into the development lifecycle, assess risk, and ensure compliance with security standards. They act as an advisor to all teams on secure design and implementation.

### Responsibilities
- Conduct threat modeling and security reviews for new features
- Define and enforce security standards and scanning requirements
- Triage and coordinate remediation of security vulnerabilities
- Support compliance audits and documentation
- Promote security awareness across the team

### Goals
- Prevent security incidents through proactive risk management
- Ensure vulnerabilities are identified and addressed before production
- Maintain compliance with applicable security standards

### Typical Communication
- Security review reports and threat models
- Vulnerability triage meetings
- Secure coding guidelines and policy updates

### Interactions with Existing Roles
- **Developers**: advise on secure coding practices and review security-sensitive changes
- **Tech Lead**: collaborate on architecture decisions with security implications
- **Release Manager**: confirm security sign-off before go/no-go
- **Project Managers**: surface security risks and compliance dependencies

---

## SRE / DevOps Engineer

### Role Summary
SRE and DevOps Engineers own the reliability, observability, and automation of the delivery pipeline and production systems. They enable fast, safe deployments and maintain system health.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Define and monitor SLOs, SLAs, and error budgets
- Lead incident response, root cause analysis, and post-mortems
- Manage infrastructure as code and environment configurations
- Identify and implement reliability improvements

### Goals
- Maximize system reliability and deployment frequency
- Reduce mean time to recovery (MTTR) for incidents
- Automate toil to free up engineering capacity

### Typical Communication
- On-call runbooks and incident post-mortems
- SLO dashboards and reliability reports
- Infrastructure change proposals and pipeline documentation

### Interactions with Existing Roles
- **Developers**: support CI/CD pipeline configuration and deployment troubleshooting
- **Release Manager**: coordinate deployment windows and rollback procedures
- **Security Engineer**: align on infrastructure security controls and scanning
- **Project Managers**: surface infrastructure risks and environment dependencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-roles-and-interactions-matrix.md`](octoacme-roles-and-interactions-matrix.md) for a RACI-style overview of which roles own, contribute to, or are informed about key project artifacts and ceremonies.

