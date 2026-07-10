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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute quality assurance strategies, validate acceptance criteria, and ensure features meet quality standards before release.

### Responsibilities
- Define and maintain test plans aligned with acceptance criteria
- Create and maintain automated test suites
- Execute manual QA and acceptance testing
- Identify and document defects and quality issues
- Collaborate with developers on testability improvements
- Validate compliance with security and performance requirements
- Report quality metrics and test coverage status

### Goals
- Minimize defects reaching production
- Ensure features meet acceptance criteria and user expectations
- Build confidence in release readiness
- Maintain test automation coverage and execution efficiency

### Typical Communication
- Sprint planning and Definition of Done discussions
- Test plan reviews and acceptance criteria clarification
- QA metrics in weekly status reports
- Release readiness sign-off

### Interactions with Other Roles
- **Developers**: Collaborate on testability, test automation, and defect resolution
- **Product Managers**: Clarify acceptance criteria and validate features meet requirements
- **Project Managers**: Provide QA status, timelines, and risk escalation
- **Engineering Lead**: Partner on technical testing strategy and automation architecture

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, decision-making authority, and resource approval. They ensure projects align with organizational strategy and remove blockers at the executive level.

### Responsibilities
- Approve project charter and success metrics
- Provide business requirements and constraints
- Make prioritization and trade-off decisions
- Remove organizational and resource blockers
- Provide executive visibility and governance
- Approve major scope changes and release decisions
- Support escalations and risk mitigation

### Goals
- Ensure project delivers business value and ROI
- Align project execution with organizational priorities
- Reduce approval delays and enable faster decision-making
- Mitigate business and organizational risks

### Typical Communication
- Project initiation and approval
- Monthly or milestone-based stakeholder updates
- Escalation of risks and blocker resolution
- Release announcement and post-launch reviews

### Interactions with Other Roles
- **Project Manager**: Primary escalation path for blockers and decisions
- **Product Manager**: Provide business context and prioritization guidance
- **Team**: Executive sponsorship and resource support

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads provide technical direction, architecture guidance, and ensure implementation quality. They mentor developers and drive technical decision-making aligned with organizational standards.

### Responsibilities
- Define technical architecture and design patterns
- Review and approve technical designs and proposals
- Mentor developers and support technical growth
- Identify technical risks and propose mitigations
- Ensure adherence to coding standards and best practices
- Make trade-off decisions between speed and maintainability
- Lead design reviews and code quality initiatives
- Collaborate with QA on testability and automation strategy

### Goals
- Deliver technically sound, maintainable solutions
- Build team technical capabilities and consistency
- Reduce technical debt and long-term maintenance burden
- Enable scalable, reliable systems

### Typical Communication
- Technical design discussions and reviews
- Code review comments and mentoring
- Architecture decisions documented in ADRs (Architecture Decision Records)
- Technical risk assessment in planning and retrospectives

### Interactions with Other Roles
- **Developers**: Technical mentorship, design reviews, and code quality guidance
- **QA/Testing Lead**: Partner on testability, automation architecture, and technical quality standards
- **Project Manager**: Provide technical risk assessment and timeline estimates
- **Product Manager**: Translate business requirements into technical feasibility

---

## Designer / UX Lead

### Role Summary
Designers and UX Leads define user experience, usability, and visual design for features. They advocate for user needs and ensure features are intuitive and accessible.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specs
- Define interaction patterns and user flows
- Review implementation for design fidelity and usability
- Ensure accessibility and inclusive design principles
- Collaborate with product on feature scoping and prioritization
- Document design decisions and design system updates

### Goals
- Maximize user adoption and satisfaction
- Reduce user errors and support burden
- Ensure consistent, accessible user experience
- Drive product differentiation through thoughtful design

### Typical Communication
- Design reviews and feedback cycles
- Acceptance criteria definition around UX and usability
- User research findings and recommendations
- Collaboration in sprint planning around design dependencies

### Interactions with Other Roles
- **Product Manager**: Validate user research findings and prioritize design improvements
- **Developers**: Review implementation for design fidelity and iterate on interactions
- **QA/Testing Lead**: Define usability test plans and acceptance criteria validation
- **Project Manager**: Communicate design timelines and dependencies

---

## Role Interaction Map

The following matrix shows primary communication and collaboration patterns between roles:

| Role | Developers | Product Manager | Project Manager | QA/Testing | Stakeholder | Engineering Lead | Designer |
|------|-----------|-----------------|-----------------|-----------|------------|-----------------|----------|
| **Developers** | Code reviews | Feature specs | Planning | Testability | — | Architecture | Design specs |
| **Product Manager** | Feature specs | Roadmap alignment | Prioritization | Acceptance | Approval | Feasibility | User research |
| **Project Manager** | Planning | Status | Timeline mgmt | QA status | Escalation | Estimates | Dependencies |
| **QA/Testing** | Defects | Acceptance | QA status | Testing strategy | — | Test architecture | Usability tests |
| **Stakeholder** | — | Business context | Decisions | — | — | — | — |
| **Engineering Lead** | Mentorship | Feasibility | Risk assessment | Test strategy | — | Standards | — |
| **Designer** | Design specs | Research | Dependencies | Usability tests | — | — | Design system |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Role Interaction Map to understand cross-functional collaboration patterns.
