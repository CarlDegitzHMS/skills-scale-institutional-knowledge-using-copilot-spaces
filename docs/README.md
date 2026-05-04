# OctoAcme Project Management Docs

Welcome! This README is the central entry point for all OctoAcme project management documentation. It provides a concise overview of how OctoAcme teams plan and deliver work, along with links to the full process guides below.

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle designed to keep delivery iterative and customer-focused. Work moves through five phases: **initiation** (validate the problem, stakeholders, success metrics, and a go/no-go decision), **planning** (break work into shippable increments, define Definition of Done, estimate and sequence the backlog), **execution** (build/test/review with tight day-to-day coordination), **release** (deploy with standard checklists and verification), and **close/retro** (capture learnings and convert them into tracked improvements). Core project artifacts include a project one-pager/charter, prioritized backlog with acceptance criteria, release plan, risk register, and retrospective action items.

Clear role ownership is central to OctoAcme's model. A named **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; a **Product Manager (PdM)/Product Lead** defines outcomes, prioritizes work, and measures success; **Developers** design and implement features with testability and maintainability in mind; and **QA/Testing** validates acceptance criteria and quality. Stakeholders provide inputs and approvals as needed, with the expectation that project documentation serves as a shared source of truth and is kept current as work progresses.

Execution is run with a consistent team rhythm and transparent workflow tracking. Teams use a project board with columns like **Backlog → Ready → In Progress → In Review → QA → Done**, supported by regular ceremonies such as daily standups (blockers/dependencies), weekly delivery syncs (progress and risk review), and demos/reviews at sprint or milestone boundaries. Communication emphasizes predictable stakeholder updates (weekly PM+PdM alignment, monthly stakeholder updates as appropriate) plus a defined escalation path for blockers and risks—from team triage, to PM escalation, up to sponsor-level escalation for business-impacting issues.

Quality assurance and release discipline are treated as part of delivery, not a final step. OctoAcme expects unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, plus CI-based linting, automated tests, and security scanning. Releases follow standardized pre-release requirements (acceptance criteria met, CI green, release notes drafted, rollback/mitigation plan) and a deployment checklist (staging verification, production deploy, post-deploy checks, and stakeholder announcement). Continuous improvement is maintained through regular retrospectives that produce a small number of prioritized, owned action items tracked in the backlog and reviewed in ongoing PM syncs.

## Process Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
