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

## Delivery Lead

### Role Summary
Delivery Leads focus on cross-team coordination and delivery rhythm for a project or program. They ensure dependencies are managed and teams move in sync toward milestones.

### Responsibilities
- Coordinate dependencies across teams and manage release schedules
- Keep the project board up to date and visible to all stakeholders
- Facilitate cross-team planning sessions and resolve blockers
- Unblock inter-team escalations and manage integration points
- Track milestone progress and flag risks early

### Goals
- Enable smooth, predictable delivery across multiple teams
- Minimize integration delays and dependencies bottlenecks
- Maintain clear visibility of program-level progress

### Typical Communication
- Cross-team planning and sync meetings
- Dependency tracking and integration updates
- Program-level status reports to sponsors
- When to involve: Program kickoff, sprint planning, pre-release coordination

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads own technical direction for a feature or subsystem. They guide architectural decisions, mentor developers, and ensure solutions are testable and maintainable.

### Responsibilities
- Make architecture and design decisions aligned with team standards
- Mentor developers and review technical trade-offs
- Ensure technical debt is visible, prioritized, and managed
- Validate that solutions meet performance, scalability, and quality standards
- Identify and propose mitigations for technical risks

### Goals
- Deliver scalable, maintainable technical solutions
- Build team technical capability through mentoring
- Minimize technical debt and reduce long-term maintenance burden

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Technical debt tracking and prioritization
- When to involve: Design phase, architecture reviews, code reviews, technical risk assessment

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers own user research, design decisions, and usability validation. They ensure solutions address real user needs and are intuitive to use.

### Responsibilities
- Conduct user interviews, usability tests, and user research to validate problems and solutions
- Create design assets, wireframes, prototypes, and specifications
- Validate designs against user needs and iterate based on feedback
- Ensure accessibility and usability standards are met
- Provide acceptance criteria for implementation and participate in feature acceptance

### Goals
- Deliver user-centered solutions that solve real problems
- Reduce rework due to usability issues
- Increase user satisfaction and adoption

### Typical Communication
- User research findings and insights
- Design specs and interaction documentation
- Feedback during development and testing phases
- When to involve: Problem definition, solution design, feature review, acceptance testing

---

## Data Analyst / Analytics Engineer

### Role Summary
Data Analysts and Analytics Engineers provide measurement strategy, instrumentation guidance, and outcome analysis. They help define and validate success metrics.

### Responsibilities
- Define success metrics aligned with business goals and user outcomes
- Advise on telemetry, event tracking, and data collection strategy
- Validate experiments and measure feature impact
- Produce dashboards and reports for stakeholder decision-making
- Identify trends, anomalies, and optimization opportunities

### Goals
- Enable data-driven decision-making
- Measure and demonstrate feature impact on business outcomes
- Provide actionable insights for continuous improvement

### Typical Communication
- Metric definitions and instrumentation guidance
- Experiment results and impact analysis
- Dashboard and reporting cadence
- When to involve: Planning phase (metrics definition), development (instrumentation), post-release (analysis and reporting)

---

## Release Manager

### Role Summary
Release Managers coordinate deployments and gating for production releases. They ensure releases are safe, predictable, and well-communicated.

### Responsibilities
- Own the deployment checklist and pre-release verification process
- Coordinate staging validations and sign-off from QA and product teams
- Document and execute rollback and incident mitigation plans
- Notify stakeholders of release windows and status
- Track and communicate release notes, migrations, and known issues

### Goals
- Minimize release risk and incidents
- Ensure predictable, high-confidence deployments
- Keep all stakeholders informed and prepared

### Typical Communication
- Release notes and deployment readiness reviews
- Release coordination and scheduling
- Post-deployment verification and incident communication
- When to involve: Pre-release planning, deployment coordination, incident response

---

## SRE / On-call Engineer

### Role Summary
Site Reliability Engineers (SREs) and On-call Engineers ensure system reliability, observability, and incident response readiness. They own operational excellence.

### Responsibilities
- Define SLOs (Service Level Objectives) and monitor compliance
- Create runbooks and incident response procedures
- Set up monitoring, alerts, and observability tooling
- Participate in incident triage, response, and post-incident reviews
- Advise development teams on operational best practices
- Plan capacity and improve system resilience

### Goals
- Maintain reliable, observable systems in production
- Reduce mean time to resolution (MTTR) for incidents
- Improve system resilience and operational maturity

### Typical Communication
- Incident alerts and on-call updates
- SLO tracking and reliability reports
- Runbook documentation and training
- When to involve: Architecture review, deployment preparation, incident response, post-incident retrospectives

---

## Security Liaison

### Role Summary
Security Liaisons advise on security requirements and coordinate security reviews and scans. They ensure security risks are identified and mitigated early.

### Responsibilities
- Review security requirements and threat models for features
- Ensure security scanning and code analysis tools are run in CI
- Interpret scan results and recommend mitigations
- Coordinate with security team on findings and remediation
- Advise on secure coding practices and compliance requirements

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness and best practices across teams
- Maintain compliance with security and regulatory standards

### Typical Communication
- Security requirement reviews and threat assessments
- Security scan results and remediation recommendations
- Compliance and audit documentation
- When to involve: Design phase, pre-PR merge, pre-release, incident triage

---

## Business Analyst / Stakeholder Representative

### Role Summary
Business Analysts bridge business stakeholders and the delivery team. They clarify requirements, validate business value, and ensure outcomes align with business goals.

### Responsibilities
- Capture and translate business stakeholder needs into requirements
- Prepare business cases and value propositions for initiatives
- Validate that delivered solutions meet business acceptance criteria
- Represent stakeholder interests throughout the project lifecycle
- Facilitate alignment between business and delivery teams on priorities and trade-offs

### Goals
- Ensure solutions deliver measurable business value
- Reduce misalignment between business expectations and delivery
- Accelerate stakeholder buy-in and adoption

### Typical Communication
- Requirements gathering and documentation
- Business case and value proposition development
- Stakeholder alignment and feedback loops
- When to involve: Initiation and planning, design reviews, acceptance testing, stakeholder updates

---

## QA Lead / Test Architect

### Role Summary
QA Leads and Test Architects own test strategy and quality assurance. They ensure sufficient test coverage across all levels and that acceptance criteria are verifiable.

### Responsibilities
- Define comprehensive test plans covering unit, integration, and end-to-end testing
- Coordinate test automation strategy and maintain automated test suites
- Confirm acceptance criteria are clear, testable, and verifiable
- Conduct manual testing and quality validation when automation is insufficient
- Track and report quality metrics (test coverage, defect rates, escape rates)
- Advise on quality standards and Definition of Done

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce defects reaching production
- Provide confidence in release quality

### Typical Communication
- Test plan documentation and strategy
- Automated test suite maintenance
- Defect reports and quality metrics
- When to involve: Planning (test strategy), development (testability reviews), pre-release (final QA sign-off)

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning work or responsibilities, reference the relevant persona to clarify expectations and interactions.
- During project reviews, ensure the appropriate personas are represented and their needs are being met.
