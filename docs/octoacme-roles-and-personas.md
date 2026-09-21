# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or shared depending on project size, but accountability for each responsibility should remain explicit.

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

## Project Sponsors / Executive Sponsors

### Role Summary
Project Sponsors provide strategic direction, champion the project at the leadership level, and ensure that the work remains aligned with organizational priorities. They own executive-level decisions and support the Project Manager when issues exceed the team's authority.

### Responsibilities
- Confirm the business case, desired outcomes, scope, and success measures
- Approve major scope, budget, priority, and timeline decisions
- Secure executive support and resolve cross-functional blockers
- Review project health, risks, and escalations at appropriate milestones
- Make or sponsor decisions when trade-offs affect organizational priorities

### Interaction with Existing Roles
- Partner with the Product Manager to align project outcomes with product and business priorities
- Give the Project Manager decision-making authority and respond to escalations that require executive action
- Consult Technical Leads on feasibility and risk before approving significant technical or scope changes
- Support Developers and other delivery contributors by removing organizational blockers rather than directing day-to-day implementation

### Typical Communication
- Stage-gate or milestone reviews with the Project Manager
- Escalation briefings and decision records
- Executive stakeholder updates

---

## Delivery Managers

### Role Summary
Delivery Managers coordinate execution across teams and workstreams. They focus on delivery flow, dependencies, delivery risks, and effective collaboration while the Project Manager remains accountable for the overall project plan and stakeholder governance.

### Responsibilities
- Coordinate delivery across workstreams and teams
- Track cross-team dependencies, milestones, and delivery constraints
- Establish and improve delivery cadences, planning routines, and progress reporting
- Identify delivery risks and facilitate mitigation plans
- Escalate persistent impediments and capacity concerns

### Interaction with Existing Roles
- Work with the Project Manager to maintain an accurate view of schedule, dependencies, risks, and project health
- Translate Product Manager priorities into coordinated delivery sequencing without replacing product prioritization decisions
- Coordinate with Technical Leads on sequencing, environments, architecture dependencies, and technical readiness
- Help Developers and contributors resolve process or coordination impediments while leaving technical implementation decisions with the team

### Typical Communication
- Delivery planning and dependency reviews
- Workstream status updates and impediment logs
- Risk and milestone reviews with the Project Manager

---

## Product / Business Owners

### Role Summary
Product or Business Owners represent the users, customers, and business stakeholders who depend on the project's outcomes. They clarify needs, make day-to-day priority decisions, and accept completed work against agreed outcomes.

### Responsibilities
- Clarify business needs, user outcomes, and acceptance expectations
- Refine and prioritize requirements within the agreed product direction
- Make timely decisions on scope details and trade-offs
- Validate delivered outcomes with users and stakeholders
- Confirm whether completed work meets the agreed acceptance criteria

### Interaction with Existing Roles
- Partner with the Product Manager to connect detailed delivery decisions to the roadmap and product strategy
- Work with the Project Manager to surface decisions that affect scope, schedule, risks, or stakeholder commitments
- Collaborate with Developers and Technical Leads to clarify requirements and assess feasible options
- Provide the team with timely feedback while routing changes that affect approved scope through the Project Manager and relevant Sponsor

### Typical Communication
- Requirements workshops and backlog refinement
- Acceptance reviews and demonstrations
- Decision logs and stakeholder feedback summaries

---

## Technical Leads / Architecture Partners

### Role Summary
Technical Leads or Architecture Partners guide technical direction and help ensure that proposed solutions are feasible, secure, maintainable, and aligned with engineering standards. They provide technical leadership without taking ownership of project scheduling or product prioritization.

### Responsibilities
- Define or review technical approaches, designs, and architectural decisions
- Identify technical risks, constraints, integration dependencies, and non-functional requirements
- Support estimation and sequencing of technically complex work
- Establish appropriate engineering quality, security, reliability, and operational practices
- Facilitate technical decisions and document significant trade-offs

### Interaction with Existing Roles
- Advise the Project Manager and Delivery Manager on technical dependencies, risks, sequencing, and readiness
- Partner with the Product Manager and Product/Business Owner to explain technical trade-offs in terms of customer and business outcomes
- Guide Developers through design reviews and unblock implementation questions while preserving team ownership of detailed solutions
- Escalate material technical risks to the Project Sponsor when they may affect scope, cost, schedule, or project viability

### Typical Communication
- Technical design reviews and architecture decision records
- Engineering planning and dependency reviews
- Risk assessments and release-readiness discussions

---

## Project Coordinators / Operations Partners

### Role Summary
Project Coordinators or Operations Partners provide the administrative and operational support that keeps project information current and follow-up actions visible. They improve consistency and transparency without replacing the Project Manager's accountability for delivery governance.

### Responsibilities
- Maintain project documentation, action items, calendars, and meeting records
- Prepare status-report inputs, dashboards, and decision or risk-log updates
- Track follow-ups, approvals, dependencies, and commitments
- Coordinate meeting logistics and ensure the right participants are included
- Identify stale or missing project information and prompt owners for updates

### Interaction with Existing Roles
- Support the Project Manager by maintaining the project operating rhythm and escalating overdue actions or missing information
- Coordinate with the Delivery Manager to keep dependency and milestone tracking accurate
- Gather updates from Product Managers, Product/Business Owners, Technical Leads, Developers, and stakeholders without changing their ownership of decisions
- Publish approved decisions and status information so that Sponsors and stakeholders receive a consistent view of project health

### Typical Communication
- Action-item trackers and meeting notes
- Status-report and dashboard updates
- Project board, risk register, and decision-log maintenance

---

## Role Collaboration Across the Project Lifecycle

- **Initiation:** The Project Sponsor confirms the business case and authority, the Product Manager and Product/Business Owner clarify outcomes, and the Project Manager establishes governance with support from the Project Coordinator.
- **Planning:** The Project Manager creates the plan, the Delivery Manager coordinates workstreams and dependencies, the Technical Lead identifies technical constraints, and Developers contribute estimates and implementation risks.
- **Execution and tracking:** Developers deliver the work, the Product/Business Owner clarifies acceptance decisions, the Delivery Manager manages flow and impediments, the Project Manager communicates project health, and the Project Coordinator keeps records current.
- **Escalation and change:** The Project Manager coordinates impact analysis with the Product Manager, Product/Business Owner, Delivery Manager, and Technical Lead. The Project Sponsor decides issues requiring executive authority or a change to strategic commitments.
- **Release and retrospective:** The Technical Lead supports readiness, the Product/Business Owner validates the outcome, the Project Manager coordinates stakeholder communication, and the Delivery Manager and Project Coordinator capture lessons and improvement actions for future work.

These personas should be assigned according to the project's context. One person may hold multiple roles, but combining roles should not obscure who owns decisions, communications, risks, and follow-up actions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the interaction descriptions to identify the correct owner for decisions, escalations, handoffs, and status communication.

