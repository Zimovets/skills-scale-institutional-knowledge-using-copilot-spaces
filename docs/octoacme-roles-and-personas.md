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

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They provide business direction, approve key decisions, and receive regular status communications.

### Responsibilities
- Provide business context, constraints, and priorities
- Review and approve scope, scope changes, and releases
- Escalate or unblock dependencies outside the delivery team
- Champion the project within their organizational area

### Typical Communication
- Monthly status updates and milestone reviews
- Ad-hoc consultations for major decisions or scope changes
- Formal sign-off at key gates (kickoff, release, close)

### Interactions with Other Roles
- **PM**: primary point of contact for status updates and escalations
- **PdM**: alignment on product direction and business outcomes
- **Developers / QA**: occasional reviews of demos and acceptance testing
- **SME / BA**: validate business requirements and strategic alignment

---

## QA / Testing

### Role Summary
The QA / Testing role validates that features meet acceptance criteria, quality gates, and end-user expectations before release. See the [QA Lead](#quality-assurance-qa-lead) section below for leadership-level responsibilities.

### Responsibilities
- Execute test plans (unit, integration, end-to-end, and regression)
- Report defects and verify fixes
- Contribute to the Definition of Done and acceptance criteria
- Participate in sprint reviews to validate completed work

### Goals
- Prevent defects from reaching production
- Provide fast feedback to developers
- Ensure release readiness

### Typical Communication
- Daily standups and sprint ceremonies
- Defect reports and test result summaries
- Coordination with Developers on bug triage

### Interactions with Other Roles
- **PM**: reports test status and release readiness
- **PdM**: clarifies acceptance criteria and edge cases
- **Developers**: collaborates on defect triage and test coverage
- **QA Lead**: executes plans defined by the QA Lead
- **DevOps Engineer**: coordinates environment setup for test execution

---

## Quality Assurance (QA) Lead

### Role Summary
The QA Lead owns the overall quality strategy for the project. They define and maintain the test approach, manage test resources, and act as the quality gate keeper across all lifecycle phases.

### Responsibilities
- Define and maintain the test strategy and test plans
- Coordinate test execution across unit, integration, and end-to-end layers
- Own defect tracking and triage process
- Ensure acceptance criteria are testable and traceable
- Facilitate sign-off on release readiness from a quality perspective

### Goals
- Achieve release quality through systematic validation
- Shift testing left to catch issues early in the lifecycle
- Build repeatable, automated test coverage where possible

### Typical Communication
- Sprint planning and refinement (quality inputs)
- Test summary reports and defect metrics
- Release readiness sign-off with PM and DevOps Engineer

### Interactions with Other Roles
- **PM**: provides quality status and flags risks to the release timeline
- **PdM**: aligns on acceptance criteria and Definition of Done requirements
- **Developers**: coordinates on test coverage, defect prioritization, and fix verification
- **Stakeholders**: presents test outcomes and quality metrics at milestone reviews
- **DevOps Engineer**: aligns on CI test automation, environment parity, and deployment gates
- **UX Designer**: validates UI/UX against design specs and usability standards
- **BA**: reviews requirements for testability and edge-case coverage

---

## DevOps Engineer / Release Engineer

### Role Summary
The DevOps Engineer (also referred to as Release Engineer) owns the CI/CD pipeline, infrastructure automation, and deployment processes. They ensure that software can be reliably built, tested, and released at any time.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines
- Manage infrastructure as code and environment provisioning
- Coordinate deployment windows and release execution
- Implement and monitor rollback and incident-response procedures
- Enforce security scanning and compliance checks in the pipeline

### Goals
- Achieve reliable, repeatable, low-risk deployments
- Minimize time-to-production for approved changes
- Maintain environment parity across dev, staging, and production

### Typical Communication
- Release readiness reviews with PM and QA Lead
- Infrastructure change announcements
- On-call and incident response notifications

### Interactions with Other Roles
- **PM**: coordinates deployment schedules, windows, and risk mitigation
- **PdM**: provides feasibility input on release frequency and feature flag strategies
- **Developers**: supports build/test troubleshooting and environment issues
- **Stakeholders**: communicates release windows and downtime impacts
- **QA Lead**: aligns on test environments, automated gates, and release criteria
- **UX Designer**: provisions staging environments for design validation and usability testing

---

## UX Designer / Product Designer

### Role Summary
The UX Designer creates user-centric designs that translate product requirements into intuitive, accessible interfaces. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define and document UI/UX standards and design systems
- Collaborate on acceptance criteria related to usability and design
- Participate in sprint reviews to validate implemented designs

### Goals
- Deliver interfaces that are intuitive, accessible, and aligned with user needs
- Reduce rework caused by unclear design requirements
- Maintain a consistent design language across the product

### Typical Communication
- Design reviews and feedback sessions with PM, PdM, and Developers
- Usability test result summaries
- Design handoff documentation and annotated specs

### Interactions with Other Roles
- **PM**: coordinates design timelines and dependencies within the project plan
- **PdM**: translates product requirements and user insights into design solutions
- **Developers**: provides design specs, answers implementation questions, and reviews built UI
- **Stakeholders**: presents design concepts and usability findings for approval
- **QA Lead**: provides design specs so QA can validate visual and interaction quality
- **BA**: incorporates user flow requirements identified during requirements gathering

---

## Subject Matter Expert (SME)

### Role Summary
Subject Matter Experts provide deep domain knowledge — technical, business, regulatory, or operational — that informs requirements, design decisions, and risk assessment across the project lifecycle.

### Responsibilities
- Advise on domain-specific requirements, constraints, and risks
- Review requirements, designs, and acceptance criteria for accuracy
- Support training, documentation, and change-management activities
- Act as an escalation point for domain questions during development and QA

### Goals
- Ensure delivered solutions are accurate, feasible, and aligned with domain realities
- Reduce rework caused by misunderstood domain constraints
- Transfer domain knowledge to the broader team

### Typical Communication
- Requirement workshops and review sessions
- Targeted consultation when domain-specific decisions arise
- Review and sign-off on domain-sensitive documentation

### Interactions with Other Roles
- **PM**: provides domain risk and feasibility input for the project plan
- **PdM**: advises on product strategy, regulatory constraints, and domain fit
- **Developers**: clarifies domain logic and answers technical-domain questions during implementation
- **Stakeholders**: validates alignment between business expectations and delivered capability
- **QA Lead**: defines domain-specific acceptance criteria and edge cases for testing
- **BA**: partners closely to translate domain knowledge into actionable requirements

---

## Business Analyst (BA)

### Role Summary
The Business Analyst bridges business and technical teams by gathering, documenting, and managing requirements. They translate stakeholder needs into clear, actionable backlog items and process documentation.

### Responsibilities
- Elicit and document business and functional requirements
- Facilitate requirement workshops with stakeholders and subject matter experts
- Create process maps, user stories, and acceptance criteria
- Manage requirement traceability and change requests
- Support QA in defining test scenarios aligned to requirements

### Goals
- Ensure requirements are complete, consistent, and testable before development begins
- Reduce ambiguity and rework caused by unclear or conflicting requirements
- Act as a reliable source of truth for scope decisions

### Typical Communication
- Requirement workshops and stakeholder interviews
- Backlog refinement sessions with PM and PdM
- Requirements documentation and traceability matrices

### Interactions with Other Roles
- **PM**: provides requirement status, scope change impact, and dependency tracking
- **PdM**: translates product vision into structured requirements and backlog items
- **Developers**: clarifies requirements and acceptance criteria during implementation
- **Stakeholders**: facilitates requirements gathering and manages expectation alignment
- **QA Lead**: reviews test cases for requirements coverage and traceability
- **SME**: collaborates to capture accurate domain knowledge in documented requirements
- **UX Designer**: aligns user flow requirements with design deliverables

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [octoacme-raci-matrix.md](./octoacme-raci-matrix.md) for a responsibility matrix showing how each role engages across the project lifecycle phases.

