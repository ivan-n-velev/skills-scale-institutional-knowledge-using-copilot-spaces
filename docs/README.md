# OctoAcme Project Management Documentation

## Project Management Process Summary

OctoAcme follows a five-phase project lifecycle — **Initiation, Planning, Execution, Release, and Close & Retrospective** — applied to all cross-functional projects that deliver product features, services, or integrations. During Initiation the team validates the business need, aligns stakeholders, and produces a Project One-pager with problem statement, SMART goal, success metrics, and a high-level timeline. A clear go/no-go decision gate must be passed before moving into Planning, where the work is broken into shippable increments, a prioritized backlog with acceptance criteria is created, a Definition of Done is documented, and a release plan with milestones is agreed upon.

Execution is guided by a consistent team rhythm: daily standups, weekly delivery syncs, and end-of-sprint demos. Work moves through a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests should be small (≤ 400 lines when possible), link to the relevant issue, and pass automated tests and linting in CI before review. Quality is maintained through unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in CI.

Risk management runs throughout all phases. Risks are captured in a Risk Register (ID, description, impact, likelihood, owner, mitigation, status) and reviewed at weekly syncs. Communication follows a defined cadence — weekly PM/PdM syncs, twice-weekly team standups, and monthly stakeholder updates — with a clear escalation path from team level through PM and Product Lead to Sponsor for blockers or incidents.

After each sprint, release, or major milestone the team holds a **Retrospective** (45–75 min) covering what went well, what to improve, and 2–3 prioritized action items with owners and due dates. Improvements are tracked in the project backlog and reviewed in weekly PM syncs, supporting OctoAcme's culture of iterative, data-informed continuous improvement.

---

## Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
