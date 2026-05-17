# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Not every initiative needs every persona below. During initiation and planning, teams should explicitly identify which roles are active, who is filling them, and which approvals, handoffs, or decisions they own.

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

## QA / Test Engineers

### Role Summary
QA / Test Engineers validate that delivered work meets acceptance criteria, quality expectations, and release-readiness standards.

### Responsibilities
- Create and maintain test approaches for features and releases
- Validate acceptance criteria, edge cases, and regression risk
- Document defects clearly and verify fixes
- Support smoke testing and release readiness checks

### Goals
- Prevent defects from reaching customers
- Give the team fast feedback on quality risk
- Keep testing aligned with the most critical user flows

### Typical Communication
- Test plans, bug reports, and release readiness updates
- Daily coordination with developers during active testing
- Quality sign-off input during release preparation

### How this role works with Developers, Product Managers, and Project Managers
- Partners with Developers to reproduce issues, verify fixes, and improve testability
- Confirms acceptance criteria and edge cases with Product Managers
- Aligns test timing, risk reporting, and release readiness with Project Managers

### When to involve
- During planning to shape the QA approach for high-risk work
- During execution when stories move into review, QA, or regression testing
- Before release to confirm smoke tests and unresolved defect decisions
- In retrospectives when quality gaps or escaped defects need follow-up actions

---

## Engineering Managers / Technical Leads

### Role Summary
Engineering Managers / Technical Leads provide technical direction, staffing support, and escalation paths for engineering delivery.

### Responsibilities
- Guide technical approach, architecture, and implementation trade-offs
- Support estimation, sequencing, and dependency planning
- Remove technical blockers and coach developers
- Maintain engineering standards for quality, reliability, and security

### Goals
- Keep delivery plans realistic and technically sound
- Reduce technical risk before it becomes schedule risk
- Support a healthy, effective engineering team

### Typical Communication
- Design reviews and technical planning sessions
- Capacity, staffing, and blocker discussions
- Escalations on technical risk or cross-team dependencies

### How this role works with Developers, Product Managers, and Project Managers
- Supports Developers with design decisions, reviews, and escalation handling
- Helps Product Managers evaluate feasibility, trade-offs, and scope options
- Partners with Project Managers on sequencing, dependencies, and delivery risk

### When to involve
- During initiation or planning when scope depends on architecture or staffing decisions
- During execution when blockers, dependency changes, or technical trade-offs surface
- Before release for readiness decisions on operational or implementation risk
- In retrospectives when process issues connect to technical debt or team capacity

---

## UX / Product Designers

### Role Summary
UX / Product Designers ensure solutions are usable, accessible, and aligned with customer needs before and during implementation.

### Responsibilities
- Create wireframes, prototypes, or interaction guidance
- Define user flows, states, and accessibility considerations
- Clarify design intent during implementation and review
- Help validate whether the delivered experience solves the intended problem

### Goals
- Improve usability and adoption
- Reduce ambiguity in how features should behave
- Ensure design quality keeps pace with delivery speed

### Typical Communication
- Design reviews, walkthroughs, and annotated mocks
- Feedback on usability and accessibility risks
- Ongoing clarification with product and engineering during implementation

### How this role works with Developers, Product Managers, and Project Managers
- Works with Developers to clarify states, edge cases, and implementation details
- Partners with Product Managers to translate problem statements into usable solutions
- Coordinates with Project Managers so design milestones align with delivery plans

### When to involve
- During initiation or planning for user-facing features, workflows, or content changes
- During execution when implementation details affect usability or accessibility
- Before release when customer-facing changes need final design validation
- In retrospectives when adoption, usability, or handoff quality needs improvement

---

## Executive Sponsors / Business Stakeholders

### Role Summary
Executive Sponsors / Business Stakeholders provide strategic alignment, decision-making support, and escalation help for business-impacting work.

### Responsibilities
- Confirm business goals, constraints, and success measures
- Approve major scope, timeline, or investment decisions when needed
- Help remove blockers that require organizational support
- Review progress, outcomes, and business impact at key milestones

### Goals
- Keep the initiative aligned to business value
- Enable fast decisions on high-impact trade-offs
- Ensure delivery outcomes match stakeholder expectations

### Typical Communication
- Milestone reviews and status updates
- Decision requests and escalation summaries
- Release, adoption, and outcome readouts

### How this role works with Developers, Product Managers, and Project Managers
- Receives implementation impact and risk summaries through Project Managers
- Aligns with Product Managers on goals, scope changes, and expected outcomes
- Gives teams escalation support when decisions exceed delivery-team authority

### When to involve
- During initiation to confirm goals, success measures, and key constraints
- During planning when timelines, scope, or dependencies need business alignment
- During execution if major risks or trade-offs require sponsor decisions
- After release and in retrospectives to review outcomes and improvement priorities

---

## Support / Customer Success Representatives

### Role Summary
Support / Customer Success Representatives bring customer-facing operational knowledge that helps the team plan rollout, enable support teams, and respond to real-world issues.

### Responsibilities
- Share recurring customer pain points and operational feedback
- Identify support readiness needs such as macros, FAQs, or training
- Help plan rollout communication and post-release monitoring
- Surface production issues and adoption trends back to the team

### Goals
- Improve rollout readiness and customer experience
- Reduce avoidable support load after launch
- Turn customer feedback into actionable improvements

### Typical Communication
- Customer issue summaries and trend reports
- Release readiness reviews and enablement requests
- Post-release feedback loops with product and project leads

### How this role works with Developers, Product Managers, and Project Managers
- Gives Developers real-world issue patterns and reproduction context
- Informs Product Managers about adoption gaps, friction points, and support trends
- Coordinates with Project Managers on rollout timing, communications, and readiness

### When to involve
- During planning when customer workflows or rollout impact should shape scope
- During execution when documentation, training, or support preparation is needed
- Before release to confirm enablement materials and customer communication plans
- In retrospectives to review ticket trends, onboarding friction, and follow-up actions

---

## Security / Compliance Reviewers

### Role Summary
Security / Compliance Reviewers ensure solutions meet organizational requirements for security, privacy, and regulatory obligations.

### Responsibilities
- Review changes for security, privacy, or compliance risk
- Identify required controls, mitigations, and approvals
- Advise on secure release practices and incident considerations
- Support sign-off when systems or data sensitivity require formal review

### Goals
- Reduce security and compliance risk before release
- Make required reviews predictable instead of last-minute blockers
- Help teams ship safely and in line with policy

### Typical Communication
- Security review findings and mitigation guidance
- Threats, control requirements, and sign-off status
- Escalations for high-risk gaps or compliance deadlines

### How this role works with Developers, Product Managers, and Project Managers
- Works with Developers on secure implementation and remediation steps
- Helps Product Managers understand scope or timeline impact from security requirements
- Supports Project Managers in planning review windows, approvals, and risk tracking

### When to involve
- During planning for work that touches sensitive data, auth, payments, or regulated flows
- During execution when designs change or new risks are discovered
- Before release for final review, sign-off, or control verification where required
- After incidents or in retrospectives when corrective actions affect future delivery

---

## Practical Accountability Guidance

Use the right roles at the right time instead of treating every project the same way.

- Planning: confirm which personas are active, document the named owner for each role, and align on approvals, dependencies, and handoffs.
- Execution: involve the relevant delivery roles early when scope, design, quality, or risk decisions change.
- Release: confirm QA, support, security, and stakeholder readiness before announcing or deploying customer-facing work.
- Retrospective: invite the roles that saw the most delivery friction so action items reflect what happened in practice.

For a lightweight lifecycle checklist, use `octoacme-role-engagement-checklist.md`.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
