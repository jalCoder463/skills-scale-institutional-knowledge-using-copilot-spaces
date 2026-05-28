# OctoAcme Project Management Docs

Welcome! This repository centralizes OctoAcme's program and project management processes. Use this README as your home base for accessing living documentation, templates, and team knowledge.

## Project Management Process Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer value and iterative delivery. The organization operates across five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective & Continuous Improvement**. Each phase has defined deliverables and decision gates. Projects begin with a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline. Once stakeholders approve the initiative, the team moves into detailed planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a release plan is established. Throughout execution, the team follows a structured rhythm of daily standups, weekly delivery syncs, and sprint-based iterations using GitHub Projects to track work through Backlog → Ready → In Progress → In Review → QA → Done columns.

The organization defines clear ownership through three core delivery roles: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; and **Developers** implement features while participating in design and quality reviews. This role clarity, combined with a transparent communication cadence—including daily standups, weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates—ensures alignment across the organization. Risk management is embedded throughout the lifecycle via a Risk Register that tracks identification, assessment, mitigation, and monitoring, with escalation paths flowing from team-level through PM, Product Lead, and Sponsor levels when blockers emerge.

Quality and reliability are embedded into execution through multiple mechanisms: small PRs (≤400 lines), automated CI/CD with testing and security scanning, unit and integration tests for new logic, end-to-end smoke tests before release, and manual QA for feature acceptance. Before any release, the team ensures all acceptance criteria are met, passing CI/security scans, release notes are drafted, and rollback plans are documented. A structured retrospective process—held after sprints, releases, or milestones—captures learnings and converts them into actionable improvement items with clear owners and due dates, reinforcing a culture of continuous learning and incremental improvement.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Documentation

Explore each phase of the OctoAcme project lifecycle:

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to roles, artifacts, and high-level lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need and authorize work
- [Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution and track progress
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize releases to production
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of key roles and responsibilities

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate and authorize work.
3. **Looking for templates?** Each process document includes checklists, templates, and examples tailored to its phase.
4. **Need to contribute or improve a process?** Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

## How to Use These Docs

- Keep process documentation updated as team practices evolve
- Use these docs as context in Copilot Spaces for role-specific guidance
- Reference templates and checklists in your project repos and artifacts
- Link to relevant sections when onboarding new team members

---

**Have suggestions or updates?** Open a process doc update issue using the provided template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`.
