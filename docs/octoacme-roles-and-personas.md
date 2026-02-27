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

## UX Designer

### Role Summary
UX Designers create user interfaces, conduct user research, and ensure usability standards are met throughout the product lifecycle. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Design wireframes, prototypes, and high-fidelity mockups
- Conduct user research and usability testing
- Define and maintain design guidelines and component libraries
- Collaborate with Product Managers to refine requirements and acceptance criteria
- Provide design assets and feedback during implementation reviews

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce friction in user journeys through iterative testing
- Ensure designs are technically feasible and aligned with product goals

### Typical Communication
- Design reviews with Product Managers and Developers
- Usability test reports shared with the delivery team
- Annotated mockups and design assets in shared repositories

### Interactions with Existing Roles
- **Developers:** Provides specifications and assets; collaborates during implementation to ensure fidelity to design intent; reviews delivered UI against acceptance criteria.
- **Product Managers:** Clarifies requirements and translates them into user experiences; provides input to prioritization based on usability findings.
- **Project Managers:** Flags design dependencies and timeline needs; participates in sprint planning to ensure design readiness before development begins.

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, help remove blockers, and coach the team on continuous improvement. They are stewards of the team's process—not directly responsible for delivery outcomes, but critical to team health and efficiency.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove impediments to team progress
- Coach team members and leads on agile principles and practices
- Track process health metrics (velocity, cycle time, retrospective action items)
- Shield the team from unplanned interruptions and scope creep

### Goals
- Foster a high-performing, self-organizing team
- Continuously improve team processes and reduce waste
- Maintain psychological safety and a culture of learning

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective summaries and action item tracking
- One-on-one coaching sessions with team members and leads

### Interactions with Existing Roles
- **Developers:** Removes blockers and helps the team self-organize; advocates for sustainable pace and quality practices.
- **Product Managers:** Ensures the backlog is healthy and sprint goals are realistic; escalates prioritization conflicts.
- **Project Managers:** Aligns on cadence and reporting; surfaces process risks that may affect delivery timelines.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, manage infrastructure as code, and ensure smooth, reliable deployments. They bridge development and operations to improve delivery speed and system stability.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and automation
- Manage infrastructure provisioning and configuration (IaC)
- Monitor system health and lead incident response for infrastructure issues
- Enforce security and compliance controls in the deployment pipeline
- Support environment readiness for QA and staging deployments

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize mean time to recovery (MTTR) for production incidents
- Ensure observability and traceability across the delivery pipeline

### Typical Communication
- Release coordination meetings with Project Managers and Developers
- Incident post-mortems and runbook updates
- Pipeline and infrastructure status dashboards

### Interactions with Existing Roles
- **Developers:** Collaborates on build/deploy configurations and troubleshooting; reviews infrastructure changes related to new features.
- **Product Managers:** Provides input on feasibility and timing of deployment strategies (e.g., feature flags, canary releases).
- **Project Managers:** Coordinates deployment windows and communicates infrastructure risks during release planning; updates the risk register with infrastructure-related items.

---

## Customer Success Manager

### Role Summary
Customer Success Managers (CSMs) act as the customer champion post-release. They track product adoption, collect customer feedback, and relay customer needs back to Product and Project teams to drive continuous improvement.

### Responsibilities
- Monitor customer adoption and health metrics after release
- Collect and synthesize customer feedback and feature requests
- Onboard and train customers on new features
- Communicate customer insights to Product and Project Managers
- Escalate critical customer issues and coordinate resolution

### Goals
- Maximize customer retention and satisfaction
- Close the feedback loop between customers and the product team
- Drive post-launch improvements based on real-world usage data

### Typical Communication
- Regular check-ins with customers and customer health reports
- Feedback summaries and feature request logs shared with Product Managers
- Participation in retrospectives to surface customer-facing learnings

### Interactions with Existing Roles
- **Developers:** Provides context on customer-reported bugs and usability issues; validates fixes from a customer perspective.
- **Product Managers:** Shares adoption data and customer feedback to inform roadmap prioritization; contributes to post-launch success metrics.
- **Project Managers:** Reports on post-launch customer health and escalates critical issues; helps coordinate customer communication during incidents or major releases.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a full view of how roles map to project activities, see the [RACI Template](./octoacme-raci-template.md).

