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

## Product Lead

### Role Summary
The Product Lead guides overall product strategy and aligns cross-functional teams around priorities, outcomes, and trade-offs. They serve as the escalation point for product decisions that affect roadmap and portfolio health.

### Responsibilities
- Set product vision and strategic roadmap for the initiative
- Review and approve project one-pagers and high-level scope decisions
- Resolve conflicts between competing priorities and projects
- Monitor portfolio outcomes, customer value, and return on investment
- Escalate business-impacting issues to sponsors and stakeholders when needed

### Goals
- Ensure projects align with business strategy and customer value
- Drive consistent prioritization across teams and initiatives
- Enable clear decision-making on scope, sequencing, and impact

### Typical Communication
- Monthly portfolio reviews and roadmap updates
- Weekly PM and product syncs
- Stakeholder briefings and escalation reviews

### Interaction with Existing Roles
- Works with Product Managers to refine priorities and success metrics
- Partners with Project Managers on schedule, reporting, and cross-team dependencies
- Aligns with Developers and Technical Leads on feasibility, trade-offs, and delivery risk

---

## QA & Testing Engineer

### Role Summary
QA and Testing Engineers define and execute quality assurance strategies to ensure solutions meet acceptance criteria, quality standards, and release readiness expectations.

### Responsibilities
- Design test plans, quality gates, and automation strategies
- Execute manual and automated tests across product features and workflows
- Validate acceptance criteria and release readiness
- Identify, document, and track defects and quality risks
- Coordinate testing dependencies with Development and Release teams
- Support validation during pre-release and production signoff

### Goals
- Deliver high-quality releases with minimal production defects
- Improve confidence and speed through test automation
- Ensure customer-facing experiences meet expected reliability and usability standards

### Typical Communication
- Sprint planning and daily standups
- Test reports and defect triage
- Release readiness reviews and signoff checkpoints

### Interaction with Existing Roles
- Works closely with Developers to validate fixes, regressions, and acceptance criteria
- Collaborates with Project Managers on release timing and QA planning
- Supports Product Managers and Stakeholders by confirming readiness and quality risks

---

## Stakeholder & Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, funding, strategic direction, and approval authority. They help ensure projects remain aligned to business outcomes and organizational priorities.

### Responsibilities
- Approve project initiation, investment, and key milestones
- Define business objectives, success criteria, and strategic priorities
- Provide oversight and steer major decisions or escalations
- Review release readiness and business impact
- Support resource allocation and issue resolution at the business level

### Goals
- Ensure the project delivers expected business value
- Minimize risk to organizational objectives and customer commitments
- Maintain sponsorship and support for successful execution

### Typical Communication
- Monthly steering reviews and status check-ins
- Gate approvals and decision meetings
- Escalation handling and post-project reviews

### Interaction with Existing Roles
- Works with Product Leads and Product Managers to confirm strategy and expected outcomes
- Coordinates with Project Managers on progress, risk, and major decisions
- Provides executive direction while allowing the delivery team to manage day-to-day execution

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect sets technical direction, design standards, and architectural guardrails. They help the team build solutions that are scalable, reliable, maintainable, and aligned with organizational engineering practices.

### Responsibilities
- Review and approve technical designs and major implementation decisions
- Identify technical risks, dependencies, and architectural constraints
- Mentor developers on standards, patterns, and trade-offs
- Lead technical spike investigations and solution design discussions
- Guide long-term maintainability, scalability, and technical debt management

### Goals
- Deliver robust, scalable, and maintainable solutions
- Reduce technical risk and avoid avoidable rework
- Build technical consistency across the delivery team

### Typical Communication
- Design reviews and architecture discussions
- Technical planning sessions and dependency alignment
- Code review feedback and implementation guidance

### Interaction with Existing Roles
- Works with Developers to guide implementation quality and technical feasibility
- Partners with Product Leads and Product Managers on delivery trade-offs and sequencing
- Supports Project Managers by surfacing technical dependencies and delivery risk

---

## Security & Compliance Officer

### Role Summary
The Security and Compliance Officer ensures projects meet required security, privacy, and compliance standards. They help embed risk controls into project planning and delivery.

### Responsibilities
- Review project requirements for security and compliance implications
- Assess designs, code, and infrastructure against security practices
- Coordinate security scanning, testing, and remediation plans
- Advise on regulatory, privacy, and governance obligations
- Support incident response and escalation for security concerns

### Goals
- Prevent security incidents and compliance violations
- Embed secure practices into project execution
- Protect customer trust, organizational risk posture, and regulatory alignment

### Typical Communication
- Security design reviews and risk assessments
- Compliance checkpoints and release approvals
- Incident response and remediation discussions

### Interaction with Existing Roles
- Advises Product Leads and Project Managers on security-related constraints and decision gates
- Reviews technical decisions with the Technical Lead and Developers
- Helps QA and Release teams confirm security readiness before deployment

---

## On-Call & Support Engineer

### Role Summary
The On-Call and Support Engineer monitors production systems, handles incidents, and supports quick recovery when customer-impacting issues arise. They provide operational feedback to improve reliability and support the health of released features.

### Responsibilities
- Monitor alerts, system health, and production signals
- Triage and respond to incidents according to the playbook
- Coordinate communication, escalation, and mitigation during disruptions
- Contribute to post-incident reviews and action items
- Share operational feedback on reliability, alerts, and customer impact

### Goals
- Minimize service disruption and recovery time
- Improve system reliability and observability
- Turn incidents into preventive improvements for future releases

### Typical Communication
- Incident channels and on-call alerts
- Standups and operational reviews
- Post-incident retrospectives and support follow-ups

### Interaction with Existing Roles
- Collaborates with Developers and Technical Leads during incident diagnosis and fixes
- Provides status updates to Project Managers and Product Leads during service-impacting events
- Helps QA and Release teams identify production regression risk and support readiness

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles clarify how ownership, approvals, delivery, quality, security, and support fit into the project lifecycle.

