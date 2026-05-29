# OctoAcme Project Management Docs

## Overview

This README provides an index and short summary of all OctoAcme program management process documents. OctoAcme program/project delivery follows these practices:

- **Customer-first approach and iterative delivery**: Prioritize customer value and deliver small, testable increments
- **Clear roles and ownership**: Each project has a named Project Manager (PM) and Product Lead with defined responsibilities for Developers, QA/Testing, and Stakeholders
- **Structured lifecycle**: Five core phases (Initiation, Planning, Execution, Release, Close & Retrospective) with formal decision gates
- **Project boards for visibility**: Use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to track and manage work
- **Risk management and communication best practices**: Maintain risk registers, escalation paths, and regular stakeholder updates
- **Strong feedback and improvement cycles**: Conduct retrospectives after each sprint or release to capture learnings and drive continuous improvement

---

## OctoAcme Project Management: Key Workflows & Practices

OctoAcme operates a structured, lifecycle-based project management approach designed around five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each project is anchored by a lightweight **Project One-pager** that captures the problem statement, measurable success metrics, stakeholders, and initial timeline. Projects move through formal decision gates—particularly after initiation—where stakeholders must align on priorities, success criteria, and team availability before committing resources to planning. This gating mechanism ensures that only well-scoped, business-justified work enters the delivery pipeline, reducing scope creep and miscommunication early.

The organizational structure relies on four primary personas with distinct responsibilities: **Product Managers** define what should be built and own prioritization and success metrics; **Project Managers** coordinate delivery, manage schedules, risks, and cross-team dependencies; **Developers** implement features, write tests, and collaborate on design; and **QA/Testing** validates quality and acceptance criteria. This clear role separation prevents ambiguity and enables efficient decision-making. Communication cadences are deliberately designed—weekly syncs between PM and Product Manager, twice-weekly team standups, and monthly stakeholder updates—to balance transparency with meeting fatigue. Risk management and escalation are formalized into three levels: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues.

Execution is governed by lean practices: small pull requests (≤400 lines), prioritized backlogs with acceptance criteria, and a Definition of Done that includes unit tests, integration tests, security scanning, and CI automation before code review. The project board uses standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to provide visibility and enable bottleneck identification. Pre-release requirements mandate passing CI, security scans, smoke tests, and a documented rollback plan. Quality assurance is woven throughout—not relegated to the end—with continuous measurement of velocity, burndown, and success metrics identified in the One-pager. Finally, OctoAcme institutionalizes learning through structured retrospectives after each sprint or release, where teams capture what went well, identify improvements, and track action items with clear owners and timelines, feeding validated improvements back into the living documentation and processes.

---

## Process Documentation Index

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](./octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog for delivery |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Guidance for managing day-to-day execution and tracking progress toward project milestones |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize how OctoAcme releases features to production to reduce risk and improve observability |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities |

## Getting Started

**New to OctoAcme projects?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles and how projects flow through our lifecycle.

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate the idea, align stakeholders, and create your One-pager.

**Already in planning?** Use the [Project Planning](./octoacme-project-planning.md) guide to break work into shippable increments and create your backlog.

**Executing a project?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily standups, PR workflow, quality standards, and blocker escalation.

**Managing risks or communicating status?** Check [Risk Management & Communication](./octoacme-risks-and-communication.md) for templates and escalation paths.

**Ready to release?** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release requirements, deployment checklists, and rollback procedures.

**Wrapping up a project?** Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements.

## Key Artifacts

Across all projects, you'll commonly work with:

- **Project One-pager**: Problem, Goal, Success Metrics, Stakeholders, Timeline, Risks, Proposed Team
- **Project Board**: Organized with Backlog, Ready, In Progress, In Review, QA, Done columns
- **Risk Register**: ID, Description, Impact, Likelihood, Owner, Mitigation, Status
- **Backlog Items**: Title, Description, Acceptance Criteria, Priority, Estimate, Owner
- **Release Notes**: Release name, date, summary, notable changes, migration steps, known issues
- **Retrospective Notes**: What went well, what could improve, action items with owners and due dates

## Roles at a Glance

- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Project Manager**: Coordinates delivery, manages schedules, risks, and communications
- **Developers**: Implement features, write tests, collaborate on design
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

For detailed role definitions, see [Roles & Personas](./octoacme-roles-and-personas.md).

## Questions or Feedback?

If you have questions about these processes or would like to propose improvements, please:

1. Review the relevant process document
2. Create an issue using the **"Add Content to Project Management Process Docs"** template
3. Include your suggested content and rationale for the update

This ensures all process improvements are tracked, reviewed, and incorporated into our living documentation.
