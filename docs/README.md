# OctoAcme Project Management Docs

## Overview

OctoAcme uses a customer-focused, iterative project management methodology tailored for cross-functional, product-oriented teams. Its approach aligns project initiation, collaborative planning, incremental delivery, risk management, and regular retrospectives to drive measurable outcomes and continuous improvement.

### Core Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments with frequent demos and fast feedback
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Project Lifecycle & Workflows

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Close & Retrospective**. 

The **initiation phase** validates business need and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, success metrics, and key risks. Once approved, the **planning phase** breaks work into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. 

**Execution** emphasizes iterative delivery through daily standups, weekly delivery syncs, and structured pull request workflows (aiming for ≤400 lines per PR). Finally, **release and retrospective phases** ensure quality deployment and continuous learning through blameless post-mortems and tracked action items.

## Roles & Communication

OctoAcme operates with clear role definition to ensure accountability and efficient collaboration:

- **Project Manager:** Coordinates schedules, risks, and communications
- **Product Manager:** Defines outcomes and prioritizes the backlog
- **Developers:** Implement features and maintain quality standards
- **QA/Testing:** Validates acceptance criteria and quality

Communication occurs on a regular cadence: daily standups and sprint planning with the delivery team, weekly syncs between PM and Product Lead, and monthly stakeholder updates. This multi-tiered communication approach—combined with defined escalation paths (team-level → PM → Product Lead → Sponsor)—keeps all parties informed and prevents critical issues from silently festering.

## Quality & Risk Management

Quality assurance is embedded throughout the delivery cycle via:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI/CD
- Manual QA for feature acceptance when needed

The pull request workflow requires at least one approval and automated test passage before merge. Beyond quality gates, OctoAcme maintains a formal **Risk Register** that tracks risks by ID, description, impact, likelihood, owner, and mitigation plan. Risks are identified during planning and reviewed continuously at weekly syncs; blocker escalation is tiered to ensure both rapid team resolution and sponsor-level awareness of business-impacting issues.

## Artifacts & Continuous Improvement

Key artifacts anchor OctoAcme's transparency:
- Project Charter / One-pager
- Release Plan
- Sprint / Iteration Backlog
- Risk Register
- Retrospective notes and action items

All documentation is maintained in the project repository (under `docs/` or `.copilot/`) to ensure it remains a single source of truth. Retrospectives are held after sprints, releases, or milestones and follow a structured format: what went well, what could improve, and prioritized action items (capped at 2–3 per cycle to avoid overload). This discipline of capturing, tracking, and measuring the impact of improvements creates a culture of iterative refinement, where lessons learned directly shape how the team executes future projects.

## Process Documents

Navigate to each guide for detailed workflows, checklists, and templates:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production to reduce risk and improve observability
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Definitions of typical roles and responsibilities in OctoAcme projects

---

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a concise introduction.

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to define scope and stakeholder alignment.

**Need process guidance?** Browse the links above to find the specific workflow or phase you're working on.

For questions or suggestions on improving these docs, please open an issue or pull request.
