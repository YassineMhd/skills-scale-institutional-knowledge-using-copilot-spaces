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

### Interactions
- Works with QA Lead to define testability requirements
- Collaborates with Designer on implementation feasibility
- Partners with Technical Writer on API/feature documentation
- Reports blockers to Project Manager

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

### Interactions
- Reviews designs with Designer for user experience alignment
- Works with Technical Writer to shape documentation strategy
- Coordinates with Release Manager on feature rollout timing
- Engages Stakeholders for feature prioritization and feedback

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

### Interactions
- Escalates technical blockers identified by Developers
- Coordinates with Release Manager on deployment scheduling
- Tracks QA status and readiness gates with QA Lead
- Reports progress to Stakeholders and senior leadership

---

## Designer

### Role Summary
Designers create intuitive user experiences and maintain visual consistency across products. They work closely with Product Managers and Developers to ensure that features are not only functionally sound but also usable and aligned with brand standards.

### Responsibilities
- Create wireframes, mockups, and prototypes
- Conduct user research and usability testing
- Participate in design reviews with stakeholders
- Document design specifications and component libraries
- Collaborate on accessibility and inclusive design standards
- Iterate based on feedback and user metrics

### Goals
- Deliver user-centered, accessible designs
- Ensure visual and interaction consistency
- Reduce rework due to design-development misalignment
- Improve user satisfaction and adoption

### Typical Communication
- Design critiques and review sessions
- Design specs and component documentation
- Collaboration with Developers on implementation feasibility
- Feedback loops with Product Manager on user research findings

### Interactions
- Partners with Product Manager to translate customer needs into designs
- Works with Developers to ensure feasibility and quality implementation
- Collaborates with Technical Writer on UI terminology and documentation
- Provides design guidance to QA Lead for testing coverage

---

## QA Lead

### Role Summary
QA Leads own the quality strategy, coordinate testing efforts, and ensure that features meet acceptance criteria before release. They manage both manual and automated testing approaches and serve as gatekeepers for quality in the release process.

### Responsibilities
- Define test strategy and testing approach for projects
- Coordinate manual and automated testing efforts
- Create and maintain test plans and test cases
- Identify, triage, and track defects
- Participate in acceptance criteria refinement
- Sign off on quality readiness for releases
- Manage regression testing and release verification

### Goals
- Ensure high quality and reliability of released features
- Reduce production defects and escalations
- Build confidence in the deployment process
- Enable faster release cycles through efficient testing

### Typical Communication
- Test plans and strategy documents
- Defect reports and quality metrics
- QA sign-off gates in release process
- Feedback to Developers on bug reproducibility and impact

### Interactions
- Collaborates with Developers to understand technical implementation and identify edge cases
- Works with Designer to validate UI/UX acceptance criteria
- Coordinates with Release Manager on pre-release verification
- Reports quality metrics and blockers to Project Manager

---

## Technical Writer

### Role Summary
Technical Writers prepare clear, accurate documentation for both internal and external audiences. They participate in feature definition to ensure documentation needs are captured early, and they work across teams to create guides, API documentation, and release notes.

### Responsibilities
- Create user guides, API documentation, and help content
- Participate in acceptance criteria refinement to include documentation needs
- Draft and maintain release notes
- Collaborate on terminology and messaging consistency
- Review technical content for clarity and accuracy
- Maintain documentation in version control alongside code

### Goals
- Enable users and internal teams to understand and effectively use features
- Reduce support escalations through clear documentation
- Ensure consistency in messaging and terminology
- Maintain up-to-date, accessible documentation

### Typical Communication
- Documentation drafts and reviews
- Participation in feature kickoff meetings
- Release notes and changelog updates
- Collaboration on API documentation with Developers

### Interactions
- Partners with Product Manager to understand feature context and messaging
- Works with Developers to gather technical details and examples
- Collaborates with Designer on UI terminology and user journey documentation
- Provides content input to Release Manager for announcements

---

## Release Manager

### Role Summary
Release Managers orchestrate the release process, ensuring smooth coordination across engineering, QA, support, and communications teams. They manage release scheduling, documentation, deployment procedures, and post-release verification.

### Responsibilities
- Schedule and plan release windows and timelines
- Coordinate communication across teams (engineering, QA, support, marketing)
- Maintain release checklists and deployment procedures
- Manage release notes and customer-facing communications
- Verify successful deployment and monitor post-release health
- Coordinate rollback procedures if issues arise
- Document lessons learned after each release

### Goals
- Execute smooth, predictable releases with minimal disruption
- Reduce release-related incidents and rollbacks
- Ensure timely and clear communication with all stakeholders
- Enable fast iteration and frequent releases

### Typical Communication
- Release schedules and deployment windows
- Release checklists and deployment runbooks
- Release announcements and customer communications
- Post-release retrospective notes

### Interactions
- Coordinates with Product Manager on feature readiness and messaging
- Works with QA Lead to verify quality gates and smoke test results
- Partners with Developers to review deployment procedures and rollback plans
- Collaborates with Technical Writer on release notes and announcements
- Reports release status to Project Manager and Stakeholders

---

## Stakeholder

### Role Summary
Stakeholders represent business, customer, or strategic interests in a project. They provide input on priorities, review progress at key milestones, and participate in go/no-go decisions. Stakeholders can be internal (executives, leads) or external (clients, partners).

### Responsibilities
- Define business objectives and success criteria
- Provide domain expertise and customer insights
- Review deliverables and provide feedback at key milestones
- Participate in prioritization and scope decisions
- Approve go/no-go decisions at major gates
- Communicate project value to their organizations

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Reduce scope creep through clear prioritization
- Enable informed decision-making across the organization

### Typical Communication
- Milestone reviews and status reports
- Roadmap and priority discussions
- Go/no-go decision gates
- Stakeholder briefings and executive updates

### Interactions
- Works with Product Manager to define business value and success metrics
- Reviews progress with Project Manager at key milestones
- Provides feedback to team on feature priorities and trade-offs
- Approves resource allocation and major scope decisions

---

## Cross-Role Collaboration Matrix

| | Developer | Designer | QA Lead | Tech Writer | Release Manager | Product Manager | Project Manager | Stakeholder |
|---|---|---|---|---|---|---|---|---|
| **Developer** | Code reviews | Feasibility checks | Testing requirements | Doc requests | Deployment support | Implementation details | Blockers/estimates | - |
| **Designer** | Implementation feedback | Design critiques | Design validation | UI terminology | - | User research insights | Scope impact | Feedback |
| **QA Lead** | Bug reproducibility | Test coverage | QA strategy | Test docs | Pre-release verification | Acceptance criteria | Quality status | Sign-off |
| **Tech Writer** | Code examples | Screenshot coordination | Test case wording | Content review | Release notes | Messaging alignment | Documentation status | - |
| **Release Manager** | Deployment coordination | - | Smoke tests | Release notes | Release planning | Feature readiness | Timeline coordination | Status updates |
| **Product Manager** | Requirements clarity | Design review | Quality standards | Feature context | Feature go/no-go | Strategy alignment | Progress tracking | Value delivery |
| **Project Manager** | Risk management | Timeline impact | QA readiness | Delivery status | Release readiness | Progress reporting | Execution coordination | Escalations |
| **Stakeholder** | Technical questions | Design approval | Quality concerns | Messaging feedback | Release timing | Priorities/trade-offs | Progress review | Strategy alignment |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Cross-Role Collaboration Matrix to understand how different roles interact and communicate.
