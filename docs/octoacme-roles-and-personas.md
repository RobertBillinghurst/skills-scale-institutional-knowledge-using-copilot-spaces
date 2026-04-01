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

---

## UX Designer

### Role Summary
UX Designers ensure that features are usable, accessible, and aligned with user needs. They translate business requirements into user-centered designs and validate solutions through research and testing.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers on requirements and acceptance criteria
- Partner with Developers to ensure designs are implemented accurately
- Maintain a design system and document UX patterns

### Goals
- Deliver intuitive, accessible experiences that reduce friction for end users
- Surface user insights early to minimize costly rework
- Build consistency across product surfaces through shared design patterns

### Typical Communication
- Design critiques and review sessions with Developers and Product Managers
- Usability test reports shared with the broader team
- Figma (or equivalent) files linked from backlog items and acceptance criteria

### Key Artifacts
- Wireframes and prototypes
- Usability test notes and findings reports
- Design system documentation

---

## Data Analyst

### Role Summary
Data Analysts define how success is measured, build reporting infrastructure, and surface insights that guide product and project decisions throughout the lifecycle.

### Responsibilities
- Define and document success metrics aligned with project goals
- Build and maintain dashboards tracking key signals (usage, errors, conversion)
- Provide data-driven analysis during planning, execution, and retrospectives
- Partner with Product Managers to validate hypotheses and interpret outcomes
- Identify data quality issues and escalate to engineering

### Goals
- Ensure every initiative has clear, measurable success criteria
- Enable the team to make confident, evidence-based decisions
- Surface leading indicators of risk or underperformance early

### Typical Communication
- Dashboard links and metric reviews in weekly delivery syncs
- Analysis summaries in retrospectives and release reviews
- Collaboration with Product Managers on OKRs and feature success criteria

### Key Artifacts
- Metrics dashboards (e.g., GitHub Insights, Grafana, or equivalent)
- Success metric definitions and tracking docs
- Post-release impact analysis reports

---

## DevOps/Platform Engineer

### Role Summary
DevOps/Platform Engineers build and maintain the infrastructure, deployment pipelines, and observability tooling that enable reliable, repeatable delivery. They are the primary owners of release mechanics and production health.

### Responsibilities
- Design and operate CI/CD pipelines and deployment automation
- Maintain infrastructure-as-code, environments, and configuration management
- Define and enforce release readiness standards (health checks, rollback procedures)
- Monitor production observability (logs, metrics, alerts) and respond to incidents
- Collaborate with Developers and QA on testability, security, and non-functional requirements

### Goals
- Maximise deployment frequency while minimising mean time to recovery (MTTR)
- Ensure production environments are stable, observable, and auditable
- Reduce toil through automation and self-service tooling

### Typical Communication
- Release readiness sign-off in pre-release meetings
- Runbooks and incident playbooks shared with the on-call rotation
- Infrastructure change reviews with Developers and Security

### Key Artifacts
- CI/CD pipeline configuration and runbooks
- Release readiness checklists
- Incident post-mortem reports

---

## Customer Support/Success Lead

### Role Summary
Customer Support/Success Leads act as the voice of the customer inside the delivery team. They ensure features are supportable at launch, channel real-world feedback into the backlog, and participate in go/no-go release decisions.

### Responsibilities
- Represent customer needs and escalated issues in planning and release discussions
- Define supportability requirements (documentation, FAQs, error messages)
- Participate in release readiness reviews to confirm support tooling and runbooks are ready
- Gather and triage post-release customer feedback and route to Product or Engineering
- Contribute acceptance criteria covering edge cases raised by customers

### Goals
- Reduce customer-impacting incidents through proactive supportability planning
- Ensure the support team is prepared for every release
- Close the feedback loop between customers and the delivery team

### Typical Communication
- Release readiness review attendance and go/no-go input
- Weekly customer feedback summaries shared with Product Managers
- Support runbooks and escalation guides co-created with DevOps

### Key Artifacts
- Support runbooks and escalation guides
- Customer feedback summaries
- Release communication drafts (customer-facing notes)

---

## How roles collaborate

The table below summarises key handoffs and shared accountability across the core roles.

| Activity | Product Manager | Project Manager | Developer | UX Designer | Data Analyst | DevOps/Platform Eng. | Support/Success Lead |
|---|---|---|---|---|---|---|---|
| Define success metrics | **Owner** | Informed | Consulted | Consulted | **Owner** | Informed | Consulted |
| Prioritise backlog | **Owner** | Consulted | Consulted | Consulted | Consulted | Informed | Consulted |
| Cross-functional kickoff | **Owner** | Facilitator | Attendee | Attendee | Attendee | Attendee | Attendee |
| Sprint / iteration planning | Consulted | Facilitator | **Owner** | Consulted | Informed | Consulted | Informed |
| Design review | Consulted | Informed | **Owner** | **Owner** | Informed | Informed | Consulted |
| Release readiness review | Approver | Facilitator | Responsible | Consulted | Consulted | **Owner** | Responsible |
| Incident response | Informed | Coordinator | Responsible | Informed | Consulted | **Owner** | Responsible |
| Retrospective | Attendee | Facilitator | Attendee | Attendee | **Owner** (metrics) | Attendee | Attendee |
| Post-release impact review | **Owner** | Informed | Consulted | Consulted | **Owner** | Consulted | Consulted |

> **Key:** Owner = accountable decision-maker; Responsible = does the work; Consulted = provides input; Informed = kept up to date; Facilitator = runs the ceremony.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

