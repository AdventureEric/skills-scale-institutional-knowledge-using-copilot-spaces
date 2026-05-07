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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define test strategy, execute quality validation, and own acceptance testing before release. They partner with developers on testability and with product on acceptance criteria clarity.

### Responsibilities
- Create test plans aligned with acceptance criteria and Definition of Done
- Execute manual and automated testing across features
- Identify, triage, and track defects with severity levels
- Validate pre-release quality metrics and gate requirements
- Collaborate with developers on test infrastructure and CI improvements

### Goals
- Catch quality issues before production impact
- Maintain fast feedback loops that unblock developers
- Build team and stakeholder confidence in release readiness

### Typical Communication
- Sprint planning (test strategy for features)
- Daily standups (test blockers and coverage)
- Release readiness reviews (quality sign-off)
- Post-incident triage and root cause analysis

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical direction, design oversight, and risk assessment. They enable developers to make sound architectural decisions and maintain code quality standards.

### Responsibilities
- Review and guide architectural decisions and technical designs
- Set code review standards and provide coaching
- Identify technical risks and propose mitigation approaches
- Mentor junior developers on best practices and patterns
- Advocate for technical debt reduction in prioritization

### Goals
- Maintain code quality and architectural consistency
- Reduce technical debt and long-term maintenance burden
- Enable developers to make sound design decisions independently

### Typical Communication
- Design review sessions and PR comments
- Planning kickoffs (technical feasibility assessment)
- Risk register discussions (technical risks)
- Retrospectives (patterns and improvements)

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and coach the team on agile practices. They ensure consistent process execution and continuous improvement.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help resolve team blockers and process impediments
- Coach team members on agile practices and mindset
- Track team velocity and sprint health metrics
- Escalate systemic blockers to PM or leadership

### Goals
- Enable high team velocity and sustainable pace
- Build agile maturity and self-organizing capability
- Reduce time spent in meetings through effective facilitation

### Typical Communication
- Daily standups and ceremony facilitation
- One-on-ones with team members (coaching)
- Weekly team health check-ins
- Retrospectives and process improvement discussions

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors represent business authority and make go/no-go decisions at key gates. They provide business context, align priorities, and remove organizational blockers.

### Responsibilities
- Approve project charter and major scope changes
- Make prioritization decisions when trade-offs arise
- Allocate resources and resolve organizational dependencies
- Attend kickoff, planning, and gate meetings
- Receive escalations for business-impacting issues

### Goals
- Ensure project alignment with business strategy
- Unblock projects at the organizational level
- Make timely decisions that keep projects on track

### Typical Communication
- Project initiation and planning gates
- Monthly stakeholder updates
- Escalations for business or strategic issues
- Release announcements and retrospective summaries

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet security and regulatory requirements. They partner with the team on threat modeling, secure design, and compliance validation.

### Responsibilities
- Define security and compliance requirements early in planning
- Review designs and code for security risks
- Validate that security scanning and testing are in place
- Participate in release sign-off and compliance checks
- Lead or support incident response for security issues

### Goals
- Prevent security incidents and data breaches
- Maintain compliance with regulations and standards
- Build security practices into the development process (shift-left)

### Typical Communication
- Planning sessions (security requirements gathering)
- Design reviews (threat modeling and mitigation)
- Pre-release security checklist
- Risk register (security risks)
- Incident response (if security issue occurs)

---

## Operations/DevOps Engineer

### Role Summary
DevOps Engineers own deployment infrastructure, CI/CD pipelines, and production observability. They enable reliable, frequent releases and support incident response.

### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Provision and manage infrastructure (staging and production)
- Execute deployments and validate post-deploy health
- Set up monitoring, logging, and alerting for observability
- Participate in incident response and root cause analysis

### Goals
- Enable fast, reliable, and repeatable deployments
- Maintain high availability and performance of production systems
- Reduce manual effort in release processes

### Typical Communication
- Sprint planning (deployment requirements)
- Execution syncs (deployment readiness)
- Release checklist and deployment execution
- Post-incident reviews and monitoring discussions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interaction Matrix](./octoacme-roles-interaction-matrix.md) for how these roles collaborate across the project lifecycle.