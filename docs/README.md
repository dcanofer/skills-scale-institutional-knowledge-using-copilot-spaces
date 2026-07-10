# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, customer-first approach to project management centered on clear ownership, iterative delivery, and data-informed decisions. This folder contains comprehensive guides for managing projects across all lifecycle stages.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Project Management Approach

OctoAcme operates projects through a structured lifecycle that emphasizes customer value, iterative delivery, and clear ownership across five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. The initiation phase validates business need and stakeholder alignment through a lightweight One-pager that defines the problem, goals, success metrics, and resource needs. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done.

Execution and tracking operate on a rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations managed through GitHub Projects. The team follows a disciplined pull request workflow with small PRs (≤400 lines), automated testing and linting in CI, and at least one approval before merge. Quality is embedded throughout—unit tests, integration tests, smoke tests for critical flows, and security scanning all happen before code reaches production. Risk escalation is tiered: team-level triage in standups, PM escalation to Product Leads for cross-team dependencies, and sponsor escalation for business-impacting issues.

OctoAcme defines three core personas—**Developers**, **Product Managers**, and **Project Managers**—each with distinct ownership and communication responsibilities. Developers implement features, write tests, and surface technical risks; Product Managers prioritize the backlog and measure outcomes; Project Managers coordinate schedules, manage dependencies, and facilitate planning and retrospective meetings. Communication is formalized through weekly syncs between PM and PdM, twice-weekly standups, monthly stakeholder updates, and a consistent status template covering progress, next steps, blockers, and decisions needed.

Release and deployment are treated as carefully orchestrated activities with pre-release requirements including passing CI and security scans, drafted release notes, and a documented rollback plan. Post-deployment verification and stakeholder announcements ensure visibility. Finally, each sprint, release, or significant milestone closes with a retrospective that captures learnings and prioritizes actionable improvements with clear owners and timelines. This commitment to continuous improvement and documented learnings embeds resilience and adaptation into OctoAcme's culture.

---

## Project Lifecycle & Documentation

### 1. Initiation
- **Document**: [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- **Purpose**: Validate business need, align stakeholders, create lightweight plan
- **Key Deliverables**: Project One-pager, stakeholder list, high-level timeline, risk list
- **When to use**: Whenever a new project idea or feature proposal is ready to be explored

### 2. Planning
- **Document**: [OctoAcme — Project Planning](./octoacme-project-planning.md)
- **Purpose**: Turn approved initiative into actionable plan and backlog
- **Key Activities**: Kickoff meeting, backlog creation, estimation, Definition of Done, dependency mapping
- **When to use**: After initiation approval and before execution begins

### 3. Execution & Tracking
- **Document**: [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Purpose**: Manage day-to-day execution and track progress toward milestones
- **Key Activities**: Daily standups, weekly delivery sync, quality assurance, blocker escalation
- **When to use**: During active development and delivery of work

### 4. Release & Deployment
- **Document**: [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Purpose**: Standardize release process to reduce risk and improve observability
- **Key Activities**: Pre-release verification, deployment checklist, rollback procedures
- **When to use**: When ready to deploy features to production

### 5. Close & Continuous Improvement
- **Document**: [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Purpose**: Capture learnings and convert to actionable improvements
- **Key Activities**: Retrospective meetings, action item tracking, process refinement
- **When to use**: After each sprint, release, or important milestone

---

## Cross-Cutting Processes

### Risk Management & Communication
- **Document**: [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Purpose**: Identify, manage, and communicate risks and dependencies throughout project lifecycle
- **Key Artifacts**: Risk register, escalation paths, stakeholder communication templates

### Roles & Personas
- **Document**: [OctoAcme Personas](./octoacme-roles-and-personas.md)
- **Purpose**: Define typical roles, responsibilities, goals, and communication patterns
- **Personas Covered**: Developers, Product Managers, Project Managers

### Management Overview
- **Document**: [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- **Purpose**: Concise introduction to OctoAcme approach for new team members
- **Contents**: Principles, roles, artifacts, lifecycle, communication cadence

---

## Quick Reference: Which Document to Use?

| Scenario | Document |
|----------|----------|
| Starting a new project idea | [Project Initiation Guide](./octoacme-project-initiation.md) |
| Planning the first sprint | [Project Planning](./octoacme-project-planning.md) |
| Daily team coordination | [Execution & Tracking](./octoacme-execution-and-tracking.md) |
| Identifying and managing project risks | [Risk Management & Communication](./octoacme-risks-and-communication.md) |
| Ready to release to production | [Release & Deployment Guide](./octoacme-release-and-deployment.md) |
| After a sprint or milestone | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) |
| New to OctoAcme | [Project Management Overview](./octoacme-project-management-overview.md) |
| Understanding team roles | [Personas](./octoacme-roles-and-personas.md) |

---

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction
2. **Starting a project?** Follow the lifecycle stages: Initiation → Planning → Execution → Release → Retrospective
3. **Looking for a specific process?** Use the Quick Reference table above
4. **Need role clarity?** Check the [Roles & Personas](./octoacme-roles-and-personas.md) document
5. **Managing risks?** Reference [Risk Management & Communication](./octoacme-risks-and-communication.md)

---

## Contributing to Documentation

To propose updates or additions to these process documents, please create an issue using the **"Add Content to Project Management Process Docs"** template.

**Acceptance criteria for updates:**
- Content aligns with existing process docs
- Update improves clarity or closes a documented gap
- Proposed content has been reviewed with stakeholders (if needed)

---

*Last updated: 2026-07-10*
