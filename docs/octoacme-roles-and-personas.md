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
UX Designers advocate for the end user by conducting research, synthesizing insights, and translating user needs into usable, accessible designs. They bridge the gap between business goals and user experience.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity mockups
- Define and document user flows and interaction patterns
- Collaborate on design systems and accessibility standards
- Validate designs with real users before and during development

### Goals
- Ensure the product is intuitive, accessible, and user-centered
- Reduce rework by validating designs early in the process
- Align visual and interaction design with product goals

### Typical Interactions
- **Product Managers**: Collaborate during problem framing and solution ideation; share user research findings to inform prioritization.
- **Developers**: Hand off annotated designs and prototypes; clarify interaction behavior during implementation.
- **Project Managers**: Flag scope implications of design changes and contribute to sprint planning.
- **Business Analyst**: Work together to map user journeys to business processes and align on acceptance criteria.

### Typical Communication
- Design reviews and feedback sessions during planning and execution
- Usability test reports shared with Product Managers and Developers
- Annotated prototypes or design specs in shared tooling (e.g., Figma)
- Attendance at sprint demos to verify implemented designs

---

## Security Lead

### Role Summary
The Security Lead identifies, assesses, and mitigates security risks throughout the project lifecycle. They ensure the team follows secure development practices and that security requirements are addressed early, not as an afterthought.

### Responsibilities
- Conduct threat modeling during planning phases
- Review architectures and designs for security vulnerabilities
- Define and enforce security acceptance criteria (e.g., authentication, authorization, data handling)
- Own or coordinate security scanning in CI/CD pipelines
- Lead security incident triage and post-incident reviews
- Maintain the security-related entries in the Risk Register

### Goals
- Shift security left — catch issues in design and code review, not in production
- Reduce risk exposure and ensure regulatory/compliance alignment
- Provide clear security guidance to Developers and DevOps

### Typical Interactions
- **Developers**: Advise on secure coding patterns, review PRs for security concerns, and pair during remediation.
- **DevOps Engineers**: Coordinate security scanning tooling in CI/CD; define hardening requirements for infrastructure.
- **Product Managers**: Surface security requirements that affect feature scope or release timelines.
- **Project Managers**: Contribute to the Risk Register; escalate high-severity findings that affect the release plan.
- **Business Analyst**: Clarify compliance and regulatory requirements that affect acceptance criteria.

### Typical Communication
- Threat modeling sessions during planning kickoff
- Security findings surfaced in Risk Register and PR reviews
- Security scan reports reviewed at weekly delivery sync
- Incident communication per the security incident runbook

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, tooling, and pipelines that allow teams to deliver software reliably and efficiently. They focus on automation, observability, and operational stability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Manage infrastructure provisioning and configuration (IaC)
- Monitor system health, availability, and performance metrics
- Own deployment automation and release tooling
- Define and maintain rollback and incident response runbooks
- Support Developers with local environment setup and build tooling

### Goals
- Enable frequent, low-risk deployments
- Maximize system reliability and minimize mean time to recovery (MTTR)
- Reduce manual toil through automation

### Typical Interactions
- **Developers**: Support development environment setup and CI integration; collaborate on deployment strategies.
- **Security Lead**: Implement security scanning in pipelines; harden infrastructure per Security Lead guidance.
- **Project Managers**: Provide operational metrics and deployment readiness status; flag infrastructure risks.
- **Product Managers**: Advise on deployment strategies (feature flags, canary releases) that affect rollout plans.

### Typical Communication
- Deployment readiness updates before releases
- Operational dashboards and alerting surfaced in weekly syncs
- Incident response communications and post-mortem participation
- Pipeline and infrastructure change notifications

---

## Business Analyst

### Role Summary
Business Analysts bridge business stakeholders and the delivery team. They clarify requirements, map processes, and ensure work items have clear, testable acceptance criteria before development begins.

### Responsibilities
- Elicit, document, and validate requirements from business stakeholders
- Map current-state and future-state business processes
- Translate business needs into user stories and acceptance criteria
- Support QA efforts with test scenario definitions
- Facilitate workshops and requirements review sessions
- Maintain traceability between business requirements and delivered features

### Goals
- Prevent rework by ensuring requirements are well-understood before development
- Improve alignment between business stakeholders and the delivery team
- Ensure delivered features meet business intent and measurable outcomes

### Typical Interactions
- **Product Managers**: Collaborate to refine the backlog; provide detailed requirements analysis to support prioritization.
- **Developers**: Clarify acceptance criteria and answer questions during implementation.
- **Project Managers**: Surface requirement-related risks and scope changes that affect the project plan.
- **UX Designer**: Align user journey maps with business process flows to ensure coherent end-to-end experiences.
- **Security Lead**: Identify regulatory or compliance requirements that must be captured as security acceptance criteria.

### Typical Communication
- Requirements workshops during initiation and planning
- Acceptance criteria documented on backlog items
- Process flow diagrams shared with delivery team
- Weekly sync with Product Managers to review refinement progress

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

