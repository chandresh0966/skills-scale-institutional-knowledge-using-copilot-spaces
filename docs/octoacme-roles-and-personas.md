# OctoAcme — Roles & Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. See also the [RACI Matrix](./octoacme-raci-matrix.md) for a concise ownership reference.

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

## Stakeholders / QA

### Role Summary
Stakeholders are individuals or groups with an interest in project outcomes. QA/Testing validates that deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- **Stakeholders**: Provide business requirements, approve deliverables, and give sign-off at key milestones.
- **QA/Testing**: Define and execute test plans, report defects, verify fixes, and confirm release readiness.

### Goals
- Ensure the delivered solution meets business needs and quality standards.
- Reduce post-release defects and rework.

### Typical Communication
- Stakeholder reviews and approval emails at milestones.
- QA test reports, defect logs, and release sign-off notes.

---

## Technical Lead

### Role Summary
The Technical Lead drives technical direction, owns architecture decisions, and ensures engineering best practices are followed throughout the project.

### Responsibilities
- Lead technical design and architecture decisions.
- Review and approve technical solutions and significant pull requests.
- Identify and resolve technical blockers and risks.
- Mentor Developers and facilitate knowledge sharing.
- Estimate technical effort and feed into project planning.

### Goals
- Deliver a maintainable, scalable, and secure solution.
- Reduce technical debt and cycle time.
- Ensure knowledge is distributed across the team.

### Typical Communication
- Architecture Decision Records (ADRs) and technical design docs.
- Code review comments and PR approvals.
- Technical risk updates in weekly syncs.

### How they interact with existing roles
- **Project Manager**: Provides effort estimates and flags technical risks to timelines.
- **Product Manager**: Assesses technical feasibility of proposed features and trade-offs.
- **Developers**: Guides implementation approach, reviews code, and unblocks team members.
- **Operations Specialist**: Coordinates on deployment architecture and infrastructure readiness.
- **Stakeholders / QA**: Advises on technical constraints relevant to acceptance criteria and testing strategy.

---

## Design Lead

### Role Summary
The Design Lead owns the UX/UI direction, maintains design consistency, and ensures the product experience aligns with user needs and the product vision.

### Responsibilities
- Define and maintain UX/UI guidelines and the design system.
- Create and review design artifacts (wireframes, prototypes, specs).
- Facilitate usability reviews and incorporate feedback.
- Ensure accessibility and brand consistency across deliverables.
- Provide design input during backlog refinement and planning.

### Goals
- Deliver a consistent, accessible, and user-centered product experience.
- Reduce design rework by aligning early with engineering and product.
- Improve time-to-design-sign-off.

### Typical Communication
- Design specs and prototype links shared in project tools.
- Design review sessions at key milestones.
- Feedback threads in design and project management tools.

### How they interact with existing roles
- **Product Manager**: Translates product requirements into design direction; validates solutions against user needs.
- **Developers**: Provides detailed specs and clarifications to guide accurate implementation.
- **Technical Lead**: Aligns on technical constraints that affect design decisions.
- **Stakeholders / QA**: Presents designs for feedback; verifies delivered UI matches approved designs.
- **Project Manager**: Reports design milestone status and flags design-related blockers.

---

## Stakeholder Champion

### Role Summary
The Stakeholder Champion represents one or more stakeholder groups within the project team, ensuring their needs, priorities, and feedback are systematically incorporated into decisions.

### Responsibilities
- Act as the primary liaison between external stakeholders and the project team.
- Gather, synthesize, and communicate stakeholder requirements and feedback.
- Review project proposals, demos, and deliverables on behalf of stakeholders.
- Facilitate stakeholder approvals and sign-offs at decision gates.
- Escalate unresolved stakeholder concerns to the Project Manager or Product Manager.

### Goals
- Ensure stakeholder needs are understood and addressed throughout the project.
- Reduce last-minute change requests by engaging stakeholders early and consistently.
- Build stakeholder trust and satisfaction.

### Typical Communication
- Regular stakeholder briefings and review sessions.
- Written summaries of feedback and decisions shared with the project team.
- Escalation memos when stakeholder concerns cannot be resolved at team level.

### How they interact with existing roles
- **Project Manager**: Coordinates timing of stakeholder reviews and communicates approval status.
- **Product Manager**: Shares stakeholder priorities and feedback to inform backlog decisions.
- **Technical Lead / Design Lead**: Conveys stakeholder constraints and preferences affecting technical or design direction.
- **Stakeholders / QA**: Directly represents stakeholder groups and consolidates input for the project team.
- **Developers**: Clarifies stakeholder expectations on feature behavior and acceptance criteria.

---

## Operations Specialist

### Role Summary
The Operations Specialist ensures smooth deployment, system reliability, and post-launch support by bridging development and production operations.

### Responsibilities
- Coordinate and execute deployment activities in alignment with the release plan.
- Maintain and update runbooks, deployment checklists, and incident response playbooks.
- Monitor systems post-release and respond to incidents.
- Communicate operational requirements and constraints to the project team.
- Support post-launch review with operational metrics and incident summaries.

### Goals
- Achieve reliable, low-risk releases with minimal downtime.
- Ensure the team is operationally ready before each deployment.
- Reduce mean-time-to-recovery (MTTR) for incidents.

### Typical Communication
- Deployment readiness checklists and release notes.
- Incident reports and post-mortem summaries.
- Operational status updates in weekly syncs.

### How they interact with existing roles
- **Project Manager**: Reports deployment readiness status and flags operational risks to the release timeline.
- **Technical Lead**: Aligns on infrastructure requirements, deployment architecture, and rollback strategies.
- **Developers**: Coordinates on deployment scripts, feature flags, and environment configuration.
- **Stakeholders / QA**: Confirms release readiness; communicates maintenance windows and expected impact.
- **Stakeholder Champion**: Provides operational context (e.g., downtime windows) for stakeholder communication.

---

## RACI Summary

The table below provides a lightweight reference for who is **Responsible (R)**, **Accountable (A)**, **Consulted (C)**, or **Informed (I)** for key project activities.

| Activity | Project Manager | Product Manager | Technical Lead | Design Lead | Stakeholder Champion | Operations Specialist | Developers | Stakeholders / QA |
|---|---|---|---|---|---|---|---|---|
| Define project scope & success metrics | C | A/R | C | C | C | I | I | C |
| Backlog prioritization | C | A/R | C | C | C | I | C | I |
| Technical architecture decisions | I | C | A/R | C | I | C | R | I |
| UX/UI design & sign-off | I | C | C | A/R | C | I | C | C |
| Sprint planning & scheduling | A/R | C | C | C | I | C | R | I |
| Risk identification & mitigation | A/R | C | C | C | C | C | C | I |
| Stakeholder reviews & approvals | C | C | I | C | A/R | I | I | R |
| Release readiness & deployment | A | I | C | I | I | R | C | C |
| Post-launch monitoring & incidents | I | I | C | I | I | A/R | C | I |
| Retrospectives & process improvement | A/R | C | C | C | I | C | R | C |

> **Key**: R = Responsible · A = Accountable · C = Consulted · I = Informed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-raci-matrix.md`](./octoacme-raci-matrix.md) if a standalone RACI reference is needed.

