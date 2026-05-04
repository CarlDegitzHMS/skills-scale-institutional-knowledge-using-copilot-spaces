# OctoAcme — Role Handoffs & RACI Reference

## Purpose
Provide a lightweight, single-page reference mapping key activities across the project lifecycle to role ownership.  
**R** = Responsible (does the work) · **A** = Accountable (decision-maker/sign-off) · **C** = Consulted (provides input) · **I** = Informed (kept up to date)

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Developer | UX Designer | Security Lead | DevOps Engineer | Business Analyst |
|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | |
| Define problem statement & goals | C | A/R | I | C | I | I | R |
| Stakeholder identification & alignment | A/R | R | I | I | I | I | C |
| Initial risk identification | R | C | C | I | R | C | C |
| Go/no-go decision | A | A | I | I | C | I | C |
| **Planning** | | | | | | | |
| Backlog creation & prioritization | C | A/R | C | C | C | I | R |
| Acceptance criteria definition | C | A | C | C | C | I | R |
| Threat modeling | C | I | C | I | A/R | C | C |
| CI/CD & infrastructure planning | C | I | C | I | C | A/R | I |
| Release plan & milestone mapping | A/R | C | C | I | C | C | I |
| Definition of Done agreement | R | A | R | C | C | C | C |
| **Execution** | | | | | | | |
| Feature implementation | I | C | A/R | C | C | C | I |
| UX design & prototyping | I | C | C | A/R | I | I | C |
| Code review & PR approval | C | I | A/R | I | C | I | I |
| Security scanning & remediation | I | I | R | I | A/R | R | I |
| CI/CD pipeline operation | I | I | C | I | C | A/R | I |
| Risk register updates | A/R | C | C | I | R | C | C |
| Blocker escalation | A/R | C | C | I | C | C | I |
| **Release** | | | | | | | |
| Release readiness sign-off | A | R | C | C | C | C | I |
| Security clearance for release | I | I | I | I | A/R | C | I |
| Deployment execution | C | I | C | I | I | A/R | I |
| Smoke testing & post-deploy verification | C | C | R | I | C | R | I |
| Rollback decision & execution | A | C | C | I | C | R | I |
| Incident response ownership | C | I | C | I | C | A/R | I |
| Release announcement | R | R | I | I | I | I | I |
| **Retrospective & Close** | | | | | | | |
| Retrospective facilitation | A/R | C | C | C | C | C | C |
| Action item tracking | A/R | C | C | I | C | C | I |
| Documentation updates | R | C | C | C | C | C | C |
| Lessons-learned capture | R | R | R | R | R | R | R |

---

## Key Handoff Points

### Initiation → Planning
- **Business Analyst** hands off documented requirements and process maps to **Product Manager** and **Developers**.
- **UX Designer** delivers initial user research findings to **Product Manager** to inform backlog prioritization.
- **Security Lead** delivers initial threat model inputs to **Project Manager** for inclusion in the Risk Register.

### Planning → Execution
- **Product Manager** hands off a prioritized, estimated backlog with acceptance criteria to the **delivery team**.
- **DevOps Engineer** confirms CI/CD readiness and environment access for the **Developers**.
- **Security Lead** confirms threat model review is complete and security acceptance criteria are on backlog items.

### Execution → Release
- **Developer** and **QA** confirm all acceptance criteria are met; **Business Analyst** validates business intent.
- **DevOps Engineer** confirms pipeline health, deployment scripts, and rollback plan are ready.
- **Security Lead** signs off on security scan results before release proceeds.

### Release → Retrospective
- **Project Manager** collects release metrics and incident data for retrospective input.
- **DevOps Engineer** documents any operational issues for the post-release review.
- **Security Lead** logs any security findings and remediation actions for the retrospective.

---

## Notes
- This matrix is a reference, not a rigid contract. Adapt ownership based on project size and team structure.
- Where a role is both **A** and **R**, one person or a small group owns both decision and execution.
- All roles participate in retrospectives as **Responsible** for capturing their domain's lessons learned.
