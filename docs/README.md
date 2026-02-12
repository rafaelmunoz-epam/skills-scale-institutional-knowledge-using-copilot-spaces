# OctoAcme Project Management Docs

Welcome! This README serves as a guide to all project management process documentation for the OctoAcme team.

## Project Management Processes Summary

OctoAcme uses a **structured, iterative project management approach** that emphasizes customer value, clear ownership, and continuous improvement. Our processes are designed to ensure consistent, repeatable project execution across all cross-functional teams.

### Core Framework and Lifecycle

OctoAcme follows a five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. In the Initiation phase, teams validate business need and establish success metrics through a lightweight Project One-pager. During Planning, work is broken into shippable increments with clear acceptance criteria and estimated using T-shirt sizing or story points. Execution leverages daily standups and weekly delivery syncs supported by GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). The Release phase includes rigorous pre-deployment checks and smoke tests with documented rollback plans. Projects close with a Retrospective where learnings are captured and converted into actionable improvements tracked in future sprints.

### Key Roles and Communication Cadence

OctoAcme defines three primary personas with distinct responsibilities: **Project Managers** coordinate schedules, risks, and communications to ensure on-time delivery; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes; and **Developers** implement features while collaborating on design, testing, and risk identification. Communication occurs through a consistent rhythm—daily 15-minute standups focused on progress and blockers, weekly syncs between PM and Product Lead, twice-weekly team standups, and monthly stakeholder updates. Ad-hoc escalations follow a three-level path: team-level triage, PM escalation to Product Lead and dependent teams, and sponsor-level involvement for business-impacting issues.

### Quality Assurance and Risk Management

Quality is built into every phase through unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI pipelines. Teams maintain a living Risk Register that tracks ID, description, impact, likelihood, owner, and mitigation plan—reviewed weekly during syncs to ensure proactive risk reduction. Dependencies across teams are clearly marked on the project board and escalated during weekly synchronization meetings.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's project management approach, principles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — How to validate and authorize new projects with a Project One-pager and stakeholder alignment
- [Project Planning](./octoacme-project-planning.md) — Breaking work into shippable increments, creating backlogs, and planning releases
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, workflows, quality practices, and blocker escalation
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Managing risks, maintaining the Risk Register, and communicating with stakeholders
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release procedures, deployment checklists, and rollback playbooks
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of Project Manager, Product Manager, and Developer roles and responsibilities

## How to Use These Docs

- **For new team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach, then dive into specific guides based on your role and project phase.
- **For ongoing projects**: Keep the Project Charter updated in your project repository. Reference the relevant process docs as your project progresses through each phase.
- **For Copilot Spaces context**: Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context for generating role-specific guidance and assistance.
- **Contributing improvements**: These are living resources. If you identify gaps, improvements, or best practices to add, create an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

## Quick Reference

| Phase | Purpose | Key Artifacts |
|-------|---------|---------------|
| **Initiation** | Validate business need and authorize work | Project One-pager, Stakeholder list, Timeline |
| **Planning** | Turn approved initiatives into actionable plans | Backlog, Release Plan, Definition of Done, Risk Register |
| **Execution** | Build, test, and iterate | Sprint Backlog, Project Board, Status Reports |
| **Release** | Deploy to production safely | Deployment Checklist, Release Notes, Rollback Plan |
| **Retrospective** | Capture learnings and drive improvements | Action Items, Lessons Learned |

---

All documents are living resources for the team to reference and improve as practices evolve.
