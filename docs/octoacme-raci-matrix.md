# OctoAcme — RACI Responsibility Matrix

## Purpose
Map each project role to its level of involvement (**R**esponsible, **A**ccountable, **C**onsulted, **I**nformed) across the five core lifecycle phases. Use this matrix to clarify ownership and reduce ambiguity during planning and execution.

## RACI Key
| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; approves/signs off |
| **C** | **Consulted** — provides input before work is done |
| **I** | **Informed** — kept up to date on progress or decisions |

> A single phase/task should have exactly one **A**. Multiple **R**s are acceptable.

---

## Lifecycle Phase Matrix

| Role | Initiation | Planning | Execution | Release | Retro |
|------|-----------|---------|-----------|---------|-------|
| **Project Manager (PM)** | A | A | A | A | A |
| **Product Manager (PdM)** | R | R | C | C | C |
| **Developers** | I | C | R | R | C |
| **QA / Testing** | I | C | R | R | C |
| **QA Lead** | I | C | R | A* | C |
| **DevOps Engineer** | I | C | C | R | C |
| **UX Designer** | I | C | R | I | C |
| **Business Analyst (BA)** | R | R | C | I | C |
| **Subject Matter Expert (SME)** | C | C | C | I | I |
| **Stakeholders** | C | C | I | I | R† |

> \* QA Lead is **Accountable** for release quality sign-off; PM remains Accountable for overall release go/no-go.  
> † Stakeholders are **Responsible** for final retrospective action-item acceptance/prioritization.

---

## Phase Summaries

### 1. Initiation
Define the problem, identify stakeholders, and establish the high-level timeline and goals.

| Activity | Owner (A) | Doers (R) | Input (C) | FYI (I) |
|----------|-----------|-----------|-----------|---------|
| Problem statement & goals | PM | PdM, BA | SME, Stakeholders | Developers, QA Lead, DevOps |
| Stakeholder identification | PM | PM, PdM | Stakeholders | All |
| Initial risk assessment | PM | PM, BA | SME, Stakeholders | Developers, DevOps |

### 2. Planning
Define scope, resources, milestones, and dependencies.

| Activity | Owner (A) | Doers (R) | Input (C) | FYI (I) |
|----------|-----------|-----------|-----------|---------|
| Backlog creation & prioritization | PM | PdM, BA | Developers, QA Lead, UX Designer | SME, Stakeholders |
| Architecture & technical design | PM | Developers | DevOps, QA Lead | PdM, BA |
| Test strategy | PM | QA Lead | Developers, DevOps | PdM, BA |
| UX/Design planning | PM | UX Designer | PdM, Developers | Stakeholders |
| Release plan | PM | PM, DevOps | QA Lead, PdM | Stakeholders |

### 3. Execution
Build, test, review, and iterate toward milestones.

| Activity | Owner (A) | Doers (R) | Input (C) | FYI (I) |
|----------|-----------|-----------|-----------|---------|
| Feature development | PM | Developers | UX Designer, BA, QA Lead | PdM, DevOps |
| UI/UX implementation | PM | Developers, UX Designer | QA Lead | PdM |
| Test execution | PM | QA / Testing | Developers, DevOps | PM, PdM |
| CI/CD pipeline maintenance | PM | DevOps | Developers, QA Lead | PM |
| Requirements clarification | PM | BA, SME | PdM, Developers | QA Lead |
| Risk and status tracking | PM | PM | PdM, QA Lead | Stakeholders |

### 4. Release
Deploy, verify, and announce the release.

| Activity | Owner (A) | Doers (R) | Input (C) | FYI (I) |
|----------|-----------|-----------|-----------|---------|
| Release readiness sign-off | PM | QA Lead | DevOps, PdM | Stakeholders |
| Deployment execution | PM | DevOps, Developers | QA Lead | PM, Stakeholders |
| Post-deploy smoke tests | PM | QA / Testing | DevOps | PM, PdM |
| Release announcement | PM | PM, PdM | Stakeholders | All |
| Rollback decision | PM | PM, DevOps | QA Lead | Stakeholders |

### 5. Retrospective & Close
Capture learnings, celebrate wins, and define next steps.

| Activity | Owner (A) | Doers (R) | Input (C) | FYI (I) |
|----------|-----------|-----------|-----------|---------|
| Retro facilitation | PM | PM | All team members | Stakeholders |
| Action item capture | PM | PM, PdM | QA Lead, DevOps, BA | Stakeholders |
| Action item prioritization | PM | Stakeholders | PM, PdM | All |
| Documentation updates | PM | PM, BA | SME | All |

---

## Related Documents
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — full role definitions and interaction details
- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — lifecycle overview
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) — day-to-day execution guidance
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) — release and deployment checklist
