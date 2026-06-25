# OctoAcme Project Management Docs

This README is the central index for OctoAcme project management documentation. It provides quick access to all process guides and a concise overview of how projects are initiated, planned, executed, released, and continuously improved.

## Project Management Process Overview

OctoAcme uses a lightweight, iterative project management approach built around five lifecycle phases:

### Key Workflows

| Phase | Purpose |
|-------|---------|
| **Initiation** | Validate business need, define measurable outcomes, identify stakeholders, confirm team availability. |
| **Planning** | Convert approved ideas into a prioritized backlog with acceptance criteria, estimates, Definition of Done, dependency maps, and release milestones. |
| **Execution & Tracking** | Build, test, and review in small increments using a board flow (Backlog → Ready → In Progress → In Review → QA → Done). Run daily standups, weekly delivery syncs, and end-of-sprint demos. |
| **Release & Deployment** | Meet pre-release requirements (passing CI/security scans, rollback plan, smoke tests), deploy with a staged checklist, verify post-deploy, and announce to stakeholders. |
| **Retrospective & Continuous Improvement** | After each sprint, release, or incident: capture what went well, what to improve, and 2–3 owned action items tracked in the backlog. |

### Personas & Roles

| Role | Key Responsibilities |
|------|---------------------|
| **Project Manager (PM)** | Coordinates timelines, dependencies, risk management, and stakeholder communication. |
| **Product Manager (PdM)** | Owns problem framing, backlog prioritization, and outcome measurement. |
| **Developers** | Implement features, write tests and documentation, participate in design and code reviews. |
| **QA/Testing** | Validate acceptance criteria and quality expectations. |
| **Stakeholders** | Provide input and approvals throughout the lifecycle. |

### Communication Strategy

- **Twice-weekly standups** — progress, blockers, dependencies (15 min).
- **Weekly delivery sync** — PM + PdM alignment, risk review.
- **Monthly stakeholder updates** — milestone and health status.
- **Status update template:** Progress this week / Next steps / Risks & blockers / Decisions needed.
- **Escalation path:** Team triage → PM → Product Lead → Sponsor. Security incidents follow the security incident runbook.

### Quality Assurance Practices

- Unit tests for all new logic.
- Integration tests where applicable.
- End-to-end smoke tests for critical paths before each release.
- Security scanning in CI (required before merge).
- Manual QA for feature acceptance when needed.
- PR expectations: small PRs (≤ 400 lines when possible), linked issues and acceptance criteria, passing CI before requesting review, at least one approval before merge.

---

## Documentation Index

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](./octoacme-roles-and-personas.md)

---

> Keep this index updated when new process documents are added.
