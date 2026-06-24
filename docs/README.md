# OctoAcme Project Management Docs

Welcome — this README links to the OctoAcme project management process documents and provides a comprehensive summary of how we run projects.

## Quick links

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## OctoAcme Project Management Overview

### Core Approach

OctoAcme follows a structured, lifecycle-based approach to project management grounded in clear ownership, iterative delivery, and data-driven decision-making. The organization applies five core phases—**Initiation, Planning, Execution, Release, and Close & Retrospective**—to all cross-functional projects. Each project is sponsored by a named Project Manager (PM) and Product Manager (PdM), supported by developers, QA/testing specialists, and stakeholders. This clear role delineation ensures accountability while fostering psychological safety and customer-first thinking. The PM owns delivery schedules, risks, and communications; the PdM defines outcomes and prioritizes the backlog; and developers implement features collaboratively with design and testability in mind.

### Communication & Transparency

Communication and transparency are central to OctoAcme's execution model. The team maintains a regular rhythm of **daily standups (15 min), weekly PM-PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates**. Risk and dependency management happens through a formal Risk Register updated weekly, with escalation paths progressing from team-level triage to PM to Product Lead to Sponsor. Status is tracked using GitHub Projects with columns for Backlog, Ready, In Progress, In Review, QA, and Done, while pull requests remain small (≤400 lines when possible) with mandatory CI checks and at least one approval before merge.

### Quality & Continuous Improvement

Quality assurance and continuous improvement are embedded throughout the delivery lifecycle. Teams implement unit tests, integration tests, and end-to-end smoke tests before release; include security scanning in CI; and conduct manual QA for feature acceptance. Release deployments follow a standardized checklist including staging verification, post-deploy checks, and documented rollback plans. After each sprint, release, or milestone, OctoAcme holds structured retrospectives to capture learnings and convert them into prioritized action items, ensuring that process improvements are measured and tracked alongside product delivery.

## Using These Docs

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction to our principles, roles, and key artifacts.
- **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) guides.
- **Managing day-to-day execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md), [Risks & Communication](./octoacme-risks-and-communication.md), and [Roles & Personas](./octoacme-roles-and-personas.md).
- **Preparing a release?** See [Release & Deployment](./octoacme-release-and-deployment.md).
- **Capturing lessons learned?** Review [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

Each document contains checklists, templates, and detailed guidance for its phase or topic.
