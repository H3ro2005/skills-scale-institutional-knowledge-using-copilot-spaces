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

## Delivery Facilitator / Scrum Master

### Role Summary
Delivery Facilitators protect the team's sustainable pace, facilitate agreed delivery ceremonies, and help remove impediments that block progress.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Identify and help remove team-level impediments
- Coach the team on iterative delivery and agreed working practices
- Surface capacity, dependency, and delivery-flow risks
- Follow up on retrospective and continuous-improvement actions

### Goals
- Improve predictability and team collaboration
- Minimize avoidable delays and process friction
- Maintain a healthy, psychologically safe delivery environment

### Typical Communication
- Works with Project Managers on capacity, dependencies, and risks
- Coordinates with Developers, Product Managers, and QA on planning and review readiness
- Uses standups and retrospectives to make blockers visible and drive follow-up

---

## UX / Design Lead

### Role Summary
UX / Design Leads represent users throughout discovery and delivery, translating needs into coherent, usable product experiences.

### Responsibilities
- Research customer needs and translate findings into flows and prototypes
- Define interaction patterns and usability acceptance criteria
- Maintain design consistency and accessibility guidance
- Support delivery trade-offs through design rationale

### Goals
- Improve usability and user satisfaction
- Reduce rework caused by unclear or unvalidated experience decisions
- Deliver accessible, consistent product experiences

### Typical Communication
- Works with Product Managers to shape problems, outcomes, and priorities
- Partners with Developers on feasibility and implementation details
- Collaborates with QA to validate usability and acceptance criteria
- Presents design options and research findings to stakeholders

---

## QA Lead / Quality Engineer

### Role Summary
QA Leads own the quality strategy and help the team identify, prevent, and resolve defects across the delivery lifecycle.

### Responsibilities
- Define test strategy, coverage, quality gates, and test evidence
- Identify quality risks and coordinate testing activities
- Partner with Developers on testability, automation, and defect prevention
- Advise Project Managers and Product Managers on release readiness

### Goals
- Improve defect detection and release confidence
- Increase useful automated and exploratory test coverage
- Make quality ownership a shared responsibility

### Typical Communication
- Works with Developers on test design, debugging, and acceptance criteria
- Aligns with Product Managers on acceptance and user-impact risks
- Provides QA evidence and go/no-go input to Project Managers
- Coordinates release verification with release owners and support teams

---

## Security Lead / Security Champion

### Role Summary
Security Leads identify and reduce security risk throughout planning, implementation, testing, and operations.

### Responsibilities
- Define security requirements and review threat and compliance risks
- Recommend preventive controls and verify security measures
- Support Developers and QA with secure design and testing guidance
- Coordinate security incidents through the organization's incident runbook

### Goals
- Reduce security exposure and avoidable vulnerabilities
- Integrate security checks into normal delivery workflows
- Ensure timely escalation and response to security events

### Typical Communication
- Advises Developers and QA during design, implementation, and verification
- Coordinates material security risks and mitigations with Product and Project Managers
- Escalates incidents to Security on-call and follows established response procedures
- Updates stakeholders on risk, response, and residual impact when required

---

## Release Manager / Change Owner

### Role Summary
Release Managers coordinate operationally safe releases and ensure teams are ready to deploy, verify, communicate, and recover.

### Responsibilities
- Plan release windows and required approvals
- Verify deployment, rollback, monitoring, and support readiness
- Coordinate release notes and stakeholder communications
- Initiate rollback or incident procedures when needed

### Goals
- Reduce release risk and service disruption
- Provide a consistent, observable release and rollback process
- Ensure clear operational handoff to support and on-call teams

### Typical Communication
- Aligns with Project Managers on timing, risk, dependencies, and approvals
- Works with Developers and QA on build, test, deployment, and verification readiness
- Coordinates product announcements with Product Managers and stakeholders
- Provides operational handoff and incident updates to support and on-call teams

---

## Data / Analytics Lead

### Role Summary
Data / Analytics Leads turn project goals into measurable signals and help teams understand whether delivered changes achieve their intended outcomes.

### Responsibilities
- Define success metrics, baselines, and instrumentation requirements
- Review data quality and analysis approaches
- Measure and communicate project and product outcomes
- Identify emerging trends or unmet success criteria

### Goals
- Enable reliable, evidence-based decisions
- Improve measurement coverage and interpretation quality
- Close the loop between delivery and customer or business impact

### Typical Communication
- Partners with Product Managers to define metrics and analyze outcomes
- Advises Developers on event and telemetry requirements
- Shares findings and decision options with Project Managers and stakeholders
- Proposes follow-up experiments or improvements based on evidence

---

## Stakeholder Liaison / Customer Advocate

### Role Summary
Stakeholder Liaisons and Customer Advocates represent stakeholder and customer needs across planning, delivery, and validation.

### Responsibilities
- Gather and synthesize stakeholder or customer feedback
- Communicate priorities, constraints, and decision context
- Represent affected groups in reviews and planning activities
- Help clarify acceptance expectations and unresolved needs

### Goals
- Ensure decisions reflect stakeholder and customer needs
- Improve transparency and alignment across affected groups
- Reduce surprises and late-stage requirement changes

### Typical Communication
- Provides prioritized needs and feedback to Product Managers
- Shares decision context and progress with stakeholder groups
- Supports Project Managers with alignment, approvals, and escalation inputs
- Helps Developers and QA understand real-world use and acceptance scenarios

---

## Support / Operations Representative

### Role Summary
Support / Operations Representatives bring operational experience and service-readiness concerns into project delivery and ongoing improvement.

### Responsibilities
- Identify operational constraints, known issues, and support needs
- Prepare documentation, training, monitoring, and escalation information
- Participate in release readiness and post-release verification
- Provide support trends and incident feedback to the delivery team

### Goals
- Improve service readiness and operational stability
- Reduce support burden and time to resolve customer issues
- Close the loop between production experience and future planning

### Typical Communication
- Coordinates release and support readiness with Project and Release Managers
- Shares operational constraints with Product Managers and Developers
- Provides feedback and recurring issue patterns to QA and Delivery Facilitators
- Communicates customer-impact updates to stakeholders and on-call teams

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign personas only where they add clarity; roles may be combined in smaller projects when one person has multiple responsibilities.

