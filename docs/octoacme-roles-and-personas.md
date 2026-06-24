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
QA/Testing Leads ensure product quality through comprehensive test planning, execution, and validation. They collaborate with developers and product managers to define and verify acceptance criteria.

### Responsibilities
- Create test plans aligned with feature acceptance criteria
- Define and execute unit, integration, and end-to-end test strategies
- Validate Definition of Done is met before marking work complete
- Identify and document quality gaps and regressions
- Participate in release readiness reviews and smoke testing
- Support incident triage and post-incident testing

### Goals
- Catch defects early and reduce production issues
- Build confidence in release quality
- Prevent regressions through test automation and coverage

### Typical Communication
- Sprint planning and grooming sessions
- Daily standups when actively testing features
- Release readiness meetings
- Defect reports and test metrics

### Interaction with Other Roles
- **With Developers:** Collaborate on test strategy, clarify acceptance criteria, provide feedback on code quality
- **With Product Managers:** Validate features against acceptance criteria from usability perspective
- **With Project Managers:** Report on quality metrics, identify test-related risks and blockers

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, design reviews, and technical risk assessment. They ensure solutions are scalable, maintainable, and aligned with technical standards.

### Responsibilities
- Review technical designs and propose optimizations
- Identify technical risks early (performance, scalability, security implications)
- Guide technical decisions and trade-offs
- Participate in code reviews and architecture discussions
- Support capacity planning and technical estimation
- Document technical decisions and rationale (ADRs when needed)

### Goals
- Ensure technical quality and long-term maintainability
- Reduce technical debt and rework
- Build scalable, resilient systems

### Typical Communication
- Technical design discussions and reviews
- Sprint planning for technical spike sizing
- Risk register reviews for technical risks
- Architecture decision documentation

### Interaction with Other Roles
- **With Developers:** Provide technical guidance, review code and designs, mentorship
- **With Project Managers:** Identify technical risks and dependencies for planning
- **With QA/Testing Lead:** Advise on testability and test strategy

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers manage deployment pipelines, infrastructure, and release automation. They enable safe, repeatable deployments and support operational readiness.

### Responsibilities
- Build and maintain CI/CD pipelines
- Automate testing and deployment processes
- Manage staging and production environments
- Coordinate deployment windows and rollback procedures
- Monitor deployment health and incident response
- Document deployment runbooks and troubleshooting guides
- Support production observability and alerting

### Goals
- Enable fast, safe, and repeatable releases
- Reduce deployment risk and downtime
- Maintain production reliability and performance

### Typical Communication
- Pre-release deployment planning
- Release day coordination and incident response
- Runbook reviews and deployment checklist updates
- Infrastructure and pipeline improvements

### Interaction with Other Roles
- **With Developers:** Support CI/CD integration, troubleshoot pipeline issues
- **With Project Managers:** Coordinate release schedules and deployment windows
- **With Security Lead:** Ensure security scanning and compliance in pipelines

---

## Security Lead

### Role Summary
Security Leads ensure security practices are embedded throughout the project lifecycle. They coordinate security reviews, scanning, and incident response.

### Responsibilities
- Review security implications of design and implementation
- Ensure security scanning is integrated into CI/CD
- Coordinate security testing and vulnerability assessments
- Support incident response for security-related issues
- Ensure compliance with security policies and standards
- Provide security guidance to the team

### Goals
- Prevent security vulnerabilities in production
- Maintain compliance and reduce risk
- Build a security-aware culture

### Typical Communication
- Design review participation for security implications
- Security scanning results and remediation guidance
- Security incident escalation and response
- Security training and awareness communications

### Interaction with Other Roles
- **With Developers:** Review code for security concerns, provide secure coding guidance
- **With DevOps/Release Engineer:** Integrate security scanning and compliance checks into pipelines
- **With Project Managers:** Flag security-related risks and escalation paths
- **With Technical Lead:** Advise on secure architecture patterns and threat modeling

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders or executive sponsors provide business context, strategic alignment, and approval authority. They champion the project and ensure business value delivery.

### Responsibilities
- Provide business context and strategic direction
- Review and approve project charter and major decisions
- Escalate blockers that impact business outcomes
- Validate alignment with business goals and priorities
- Communicate project value internally and externally
- Support resource allocation and trade-off decisions

### Goals
- Ensure business value is realized
- Maintain strategic alignment
- Support project success through sponsorship

### Typical Communication
- Project initiation and kickoff
- Monthly stakeholder updates
- Decision escalations and approvals
- Post-release retrospectives and impact reviews

### Interaction with Other Roles
- **With Project Managers:** Provide business context, approve plans, escalate blockers
- **With Product Managers:** Align on strategic priorities and success metrics
- **All Roles:** Sponsor project, unblock decisions, validate business impact

---

## Role Interaction Matrix

| Role | Initiation | Planning | Execution | Release | Retrospective |
|------|-----------|----------|-----------|---------|---------------|
| **Product Manager** | Define | Lead | Guide | Validate | Measure |
| **Project Manager** | Facilitate | Coordinate | Manage | Coordinate | Facilitate |
| **Developer** | Input | Estimate | Deliver | Deploy | Reflect |
| **QA/Testing Lead** | Input | Plan | Execute | Verify | Report |
| **Technical Lead** | Review | Advise | Guide | Support | Analyze |
| **DevOps/Release Engineer** | Input | Prepare | Support | Lead | Monitor |
| **Security Lead** | Review | Advise | Review | Scan/Verify | Analyze |
| **Stakeholder/Sponsor** | Approve | Approve | Support | Announce | Review Impact |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Role Interaction Matrix to understand who should be involved in each project phase.
- When creating issues or PRs, consider which personas need to provide input or approval based on the phase.
