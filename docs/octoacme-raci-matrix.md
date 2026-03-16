# OctoAcme — RACI Matrix

## Purpose
Provide a concise, standalone reference for role ownership across key project activities. For full role descriptions and interaction details, see [Roles & Personas](./octoacme-roles-and-personas.md).

## Key
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome (one per row) |
| **C** | Consulted — provides input before/during |
| **I** | Informed — kept up to date after |

---

## RACI Table

| Activity | Project Manager | Product Manager | Technical Lead | Design Lead | Stakeholder Champion | Operations Specialist | Developers | Stakeholders / QA |
|---|---|---|---|---|---|---|---|---|
| Define project scope & success metrics | C | **A/R** | C | C | C | I | I | C |
| Backlog prioritization | C | **A/R** | C | C | C | I | C | I |
| Technical architecture decisions | I | C | **A/R** | C | I | C | R | I |
| UX/UI design & sign-off | I | C | C | **A/R** | C | I | C | C |
| Sprint planning & scheduling | **A/R** | C | C | C | I | C | R | I |
| Risk identification & mitigation | **A/R** | C | C | C | C | C | C | I |
| Stakeholder reviews & approvals | C | C | I | C | **A/R** | I | I | R |
| Release readiness & deployment | **A** | I | C | I | I | R | C | C |
| Post-launch monitoring & incidents | I | I | C | I | I | **A/R** | C | I |
| Retrospectives & process improvement | **A/R** | C | C | C | I | C | R | C |
| Project kickoff facilitation | **A/R** | C | C | C | C | C | I | I |
| Communication plan & status reporting | **A/R** | C | I | I | C | I | I | I |

---

## Notes
- Each row has exactly one **A** (Accountable). Where **A/R** appears, the same person is both accountable and doing the primary work.
- This matrix is a starting point; adapt to project-specific needs and document deviations in your project charter.
- See [Project Kickoff Checklist](./octoacme-project-kickoff-checklist.md) for per-activity ownership during project initiation.
