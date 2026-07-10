# OctoAcme — Team Structure & Composition Guide

## Purpose
Provide guidance on typical team composition, role allocation, and cross-functional collaboration patterns for OctoAcme projects.

## Overview
Successful project execution depends on clear role definition and effective cross-functional collaboration. This guide outlines typical team structures, role responsibilities, and collaboration models.

## Typical Project Team Structure

### Core Team (Required)
- **1 Project Manager** — Coordinates delivery and manages timeline/risks
- **1 Product Manager** — Defines outcomes and prioritizes backlog
- **2-4 Developers** — Implement features and technical solutions
- **1 QA/Testing Lead** — Validates quality and acceptance criteria

### Extended Team (Recommended)
- **1 Engineering Lead** — Provides technical direction and mentorship
- **1 Designer/UX Lead** — Defines user experience and usability
- **1 Stakeholder/Sponsor** — Provides business context and approvals
- **Supporting roles** — Security, DevOps, Data, depending on project needs

## Team Sizing Guidelines

### Small Projects (2-4 week sprint)
- 1 PM, 1 PdM, 2 Developers, 1 shared QA resource
- Engineering Lead and Designer roles shared with other projects

### Medium Projects (4-8 week sprint)
- 1 PM, 1 PdM, 3-4 Developers, 1 QA Lead
- Dedicated Engineering Lead and Designer for the project
- 1 Stakeholder/Sponsor for approvals and governance

### Large Projects (8+ weeks)
- 1 PM, 1 PdM, 5+ Developers, 1-2 QA Leads
- 1-2 Engineering Leads (distributed across technical areas)
- 1-2 Designers (UX and visual design)
- 1 Stakeholder/Sponsor
- Supporting roles (Security, DevOps, etc.)

## Cross-Functional Collaboration Patterns

### Daily Collaboration
- **Developers + Engineering Lead**: Code reviews, architecture decisions, pair programming
- **Developers + QA Lead**: Testability discussions, defect triage, acceptance criteria clarification
- **Product Manager + Designers**: Feature validation, user feedback integration

### Weekly Collaboration
- **PM + PdM + Engineering Lead**: Planning, scope adjustments, risk assessment
- **PM + QA Lead + Developers**: QA status, release readiness, testing strategy
- **All Core Team**: Sprint planning and status sync

### Milestone Collaboration
- **PM + Stakeholder + PdM**: Project charter approval, scope decisions, release gates
- **Engineering Lead + QA Lead**: Technical quality standards, automation strategy
- **Designer + Developers + QA**: Feature acceptance and usability validation

## Responsibility Assignment Matrix (RACI)

For key project activities:

| Activity | PM | PdM | Developer | QA Lead | Eng Lead | Designer | Sponsor |
|----------|----|----|-----------|---------|----------|----------|----------|
| Define requirements | C | R | I | C | I | R | A |
| Technical design | A | I | R | I | R | C | — |
| Implementation | I | I | R | I | C | C | — |
| QA planning | C | I | I | R | C | I | — |
| User testing | I | C | I | A | I | R | — |
| Release approval | A | A | I | R | C | — | A |
| Post-launch review | R | R | I | C | C | C | C |

**Legend**: R=Responsible, A=Accountable, C=Consulted, I=Informed

## Communication Protocols

### Decision Making
1. **Low-risk decisions** (technical implementation details): Engineering Lead makes decision, consults Developers
2. **Medium-risk decisions** (scope, timeline, quality): PM + PdM + Engineering Lead discuss, PM decides
3. **High-risk decisions** (business impact, major scope changes): Stakeholder/Sponsor, PM, PdM align before decision

### Escalation Paths
1. **Technical blockers**: Escalate to Engineering Lead, then to PM if resource/priority conflict
2. **Quality concerns**: QA Lead escalates to Engineering Lead and PM
3. **Schedule conflicts**: PM escalates to Stakeholder/Sponsor
4. **Business trade-offs**: PdM escalates to Product Lead or Sponsor

### Status Communication
- **Daily standup**: 15 min, core team, focus on progress and blockers
- **Weekly sync**: 30 min, extended team, review metrics and risks
- **Stakeholder update**: 30 min bi-weekly or monthly, highlight progress and decisions needed

## Onboarding New Team Members

### Week 1
- [ ] Review OctoAcme Project Management Overview
- [ ] Review their persona definition in octoacme-roles-and-personas.md
- [ ] Review project charter and current sprint plan
- [ ] Meet with PM and direct lead for role-specific orientation

### Week 2-3
- [ ] Participate in sprint planning and daily standups
- [ ] Shadow existing team members in their role
- [ ] Contribute to first sprint work items
- [ ] Review and provide feedback on role-specific processes

## Remote Team Collaboration

### Best Practices
- Use async-first communication where possible (written updates, decision logs)
- Schedule syncs at times convenient for distributed teams
- Record standups and key meetings for asynchronous review
- Document decisions in a central location (GitHub issues, wiki)
- Use pair programming and screen sharing for complex technical work

## Checklist: Team Setup

- [ ] All core roles assigned and committed to project
- [ ] Team members reviewed OctoAcme processes and their persona definition
- [ ] Communication cadence scheduled (standups, syncs, stakeholder updates)
- [ ] Decision-making authority and escalation paths clarified
- [ ] RACI matrix customized for specific project needs
- [ ] Onboarding plan created for new team members
- [ ] Collaboration tools and access set up
- [ ] First sprint planning scheduled
