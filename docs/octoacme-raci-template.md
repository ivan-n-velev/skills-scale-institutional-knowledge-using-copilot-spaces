# OctoAcme — RACI Matrix Template

## Purpose
Provide a reusable template for mapping roles to project activities using the RACI model to ensure clear ownership, accountability, and traceability across the project lifecycle.

## How to Use
1. Copy this template into your project repository or project planning doc.
2. List your project-specific activities in the **Activity** column.
3. Assign RACI codes for each role involved. Use only one **Accountable (A)** per row.
4. Review the matrix in the project kickoff and update it as team composition changes.

## RACI Key
| Code | Meaning |
|------|---------|
| **R** | **Responsible** – Does the work to complete the activity |
| **A** | **Accountable** – Owns the outcome; approves the result (one per row) |
| **C** | **Consulted** – Provides input before or during the activity |
| **I** | **Informed** – Notified of progress or outcome |

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Developer | UX Designer | Scrum Master | DevOps Engineer | Customer Success Manager |
|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | |
| Define problem statement & goals | C | A | I | C | I | I | C |
| Identify stakeholders | A | R | I | I | I | I | C |
| Draft project one-pager | R | A | I | C | I | I | I |
| Approve go/no-go to planning | A | R | I | I | I | I | C |
| **Planning** | | | | | | | |
| Facilitate kickoff meeting | R | C | I | I | A | I | I |
| Define backlog and acceptance criteria | C | A | C | C | R | I | C |
| Estimate scope and capacity | C | C | R | C | A | C | I |
| Draft release plan and milestones | A | C | C | I | R | C | I |
| Define Definition of Done | C | A | R | C | R | C | I |
| Set up CI/CD and environments | I | I | C | I | I | A | I |
| **Execution & Tracking** | | | | | | | |
| Implement features | I | C | R | C | I | C | I |
| Create and review UI/UX designs | I | C | C | A | I | I | I |
| Code review and PR approval | I | I | A | C | I | C | I |
| Maintain CI pipelines and infra | I | I | C | I | I | A | I |
| Facilitate standups and sprint ceremonies | C | C | I | I | A | I | I |
| Update risk register | A | C | C | I | C | C | I |
| Weekly status reporting | A | C | I | I | C | I | I |
| **Release & Deployment** | | | | | | | |
| Confirm release readiness | A | C | C | C | C | C | C |
| Execute deployment | I | I | C | I | I | A | I |
| Post-deploy verification | C | I | C | I | I | A | I |
| Announce release to stakeholders | A | C | I | I | I | I | R |
| Customer onboarding / training | I | C | I | I | I | I | A |
| **Risk & Communication** | | | | | | | |
| Identify and log risks | A | C | C | C | C | C | C |
| Escalate blockers | A | C | C | I | R | C | I |
| Stakeholder communication | A | C | I | I | I | I | C |
| Customer incident communication | C | C | I | I | I | C | A |
| **Retrospective & CI** | | | | | | | |
| Facilitate retrospective | C | I | I | I | A | I | I |
| Capture and track action items | A | C | C | I | R | C | I |
| Report on post-launch adoption | I | A | I | I | I | I | R |

---

## Notes
- Adapt the activity list to match your project's actual phases and scope.
- If a role is not involved in an activity, leave the cell blank.
- For large projects, consider creating phase-specific RACI sheets.
- Cross-reference with [Roles & Personas](./octoacme-roles-and-personas.md) for full role definitions.
- Align with the principles in [Project Management Overview](./octoacme-project-management-overview.md).
