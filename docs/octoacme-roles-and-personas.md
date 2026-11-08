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

## UX/UI Designers and Researchers

### Role Summary
UX/UI Designers and Researchers investigate user needs and shape accessible, usable experiences. Depending on the project, these responsibilities may be held by one person or shared across roles.

### Responsibilities
- Plan and conduct user research or usability testing appropriate to the work
- Translate user needs and findings into journey maps, workflows, prototypes, or design specifications
- Define interaction patterns and contribute to accessibility and usability reviews
- Document design decisions and open questions for the team
- Validate proposed solutions with users and incorporate findings into iteration plans

### Goals
- Ensure the solution addresses validated user needs
- Make experiences understandable, usable, and accessible
- Identify usability risks early enough to inform planning and implementation

### Typical Communication
- Research findings, design reviews, prototypes, and usability reports
- Collaboration with Product Managers during discovery and backlog refinement
- Design specifications and implementation feedback with Developers and QA/Testing

### Collaboration with Existing Roles
- Partners with Product Managers to connect user research and design choices to product goals, priorities, and acceptance criteria
- Works with Developers to assess feasibility and clarify design specifications before and during implementation
- Collaborates with QA/Testing to make usability and accessibility expectations testable
- Shares findings and design decisions with the Project Manager so dependencies, review points, and risks can be reflected in the plan
- Incorporates relevant input from Stakeholders while keeping user needs and evidence visible

---

## Technical Leads and Architects

### Role Summary
Technical Leads and Architects guide technical design and engineering quality. They help the team make maintainable, secure, and compatible implementation choices; the role may be shared or combined with a Developer role.

### Responsibilities
- Guide technical design and document significant decisions and trade-offs
- Identify architecture, integration, scalability, reliability, and technical-debt risks
- Support Developers with technical direction, reviews, and resolution of complex issues
- Coordinate technical interfaces and dependencies across components or teams
- Advise on technical estimates and implementation sequencing

### Goals
- Deliver a coherent, maintainable technical solution
- Identify and address technical risks early
- Help the team make informed implementation trade-offs

### Typical Communication
- Technical design documents and decision records
- Design discussions, code reviews, and engineering planning
- Risk and dependency updates with the Project Manager and relevant teams

### Collaboration with Existing Roles
- Works with Developers to clarify design, resolve technical questions, and maintain engineering quality without replacing their implementation ownership
- Partners with Product Managers to explain technical options and trade-offs that affect scope, customer value, or sequencing
- Informs the Project Manager about technical risks, dependencies, and estimate changes that may affect delivery plans
- Collaborates with QA/Testing on testability, integration points, and technical quality risks
- Seeks input from Security/Privacy Leads where architecture or implementation choices affect security or privacy

---

## Delivery or Engineering Leads

### Role Summary
Delivery or Engineering Leads coordinate the engineering team's day-to-day execution, capacity, and delivery concerns. They complement the Project Manager's cross-functional coordination and do not replace the Project Manager's ownership of the overall project plan.

### Responsibilities
- Help the engineering team plan and sequence implementation work
- Monitor engineering capacity, progress, and delivery risks
- Surface blockers and coordinate resolution with the appropriate owners
- Support consistent engineering practices and clear handoffs
- Provide engineering status and forecast changes to the Project Manager

### Goals
- Keep engineering work coordinated and visible
- Raise delivery risks and capacity constraints early
- Enable Developers to focus on well-understood, prioritized work

### Typical Communication
- Engineering planning and delivery check-ins
- Project board updates, blocker discussions, and engineering status
- Coordination with the Project Manager on milestones, dependencies, and risks

### Collaboration with Existing Roles
- Partners with the Project Manager, who remains responsible for the overall schedule, cross-functional coordination, and stakeholder reporting
- Works with Product Managers to clarify priorities and prepare engineering work for delivery
- Coordinates Developers' execution while preserving their ownership of implementation and technical contributions
- Consults Technical Leads and Architects on technical sequencing, dependencies, and engineering risks
- Coordinates with QA/Testing to plan validation handoffs and communicate readiness

---

## Data and Analytics Leads

### Role Summary
Data and Analytics Leads help teams define, instrument, and interpret measures of product and project outcomes. This responsibility may be held by an analyst, data specialist, or another team member with the relevant expertise.

### Responsibilities
- Translate success metrics into measurable definitions and data requirements
- Advise on instrumentation, data quality, and reporting needs
- Help establish baselines and interpret results after delivery
- Communicate limitations or uncertainty in data and analysis
- Recommend follow-up measurement or analysis when outcomes are unclear

### Goals
- Make project outcomes measurable and interpretable
- Provide reliable evidence to inform product decisions
- Help teams detect whether delivered changes achieve their intended impact

### Typical Communication
- Metric definitions, dashboards, and analysis summaries
- Planning discussions about instrumentation and data dependencies
- Outcome reviews with Product Managers and Stakeholders

### Collaboration with Existing Roles
- Partners with Product Managers to define success measures and use evidence to inform prioritization
- Works with Developers to identify and implement instrumentation and to address data-quality concerns
- Coordinates with QA/Testing to validate that measurement events and reporting behave as expected
- Shares measurement dependencies and risks with the Project Manager for inclusion in plans and status updates
- Presents findings to Stakeholders in terms of the agreed goals and known limitations

---

## Security and Privacy Leads

### Role Summary
Security and Privacy Leads advise teams on security, privacy, and related risks throughout delivery. They help identify appropriate controls and review needs; they do not replace Developers' responsibility for secure implementation or the organization's incident-response process.

### Responsibilities
- Identify security and privacy considerations, risks, and applicable review needs
- Advise on appropriate controls, data handling, and threat or privacy assessments
- Review designs or implementation plans when risk or policy requires specialist input
- Help define security and privacy validation needs for testing and release
- Escalate significant concerns through the established security or privacy channels

### Goals
- Address security and privacy risks early in the project lifecycle
- Make required controls and reviews clear to the delivery team
- Support delivery of trustworthy features and services

### Typical Communication
- Risk assessments, design reviews, and control recommendations
- Coordination with Developers and QA/Testing on implementation and validation
- Risk and review updates with the Project Manager and appropriate security or privacy contacts

### Collaboration with Existing Roles
- Works with Developers and Technical Leads to identify risks and incorporate suitable controls into designs and implementation
- Partners with QA/Testing to clarify security and privacy validation needs
- Advises Product Managers about risks or requirements that affect scope, user experience, or release decisions
- Informs the Project Manager about review dependencies, risks, and escalation needs so they can be tracked in the plan
- Provides Stakeholders with appropriate risk or readiness information through agreed communication channels

---

## Applying These Roles

These personas describe responsibilities, not mandatory separate positions. Teams may combine responsibilities or assign them to different people based on project size, complexity, and available expertise. At project initiation or planning, clarify who owns each relevant responsibility, who makes decisions, and how gaps or escalations will be handled.
---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

