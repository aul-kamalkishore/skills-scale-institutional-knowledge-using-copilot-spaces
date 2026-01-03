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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile best practices. They ensure the team follows agreed-upon processes and continuously improve their ways of working.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and impediments to team progress
- Coach team members on agile principles and practices
- Shield the team from external distractions
- Track and communicate team velocity and capacity
- Ensure adherence to Definition of Done and quality standards

### Goals
- Maximize team productivity and efficiency
- Foster a culture of continuous improvement
- Maintain predictable delivery cadence
- Enable self-organization and accountability

### Typical Communication
- Daily facilitation of standups and team ceremonies
- Weekly metrics reports (velocity, burndown, capacity)
- Regular coaching sessions with team members
- Coordination with Product Manager and Project Manager on scope and timelines

### Interactions with Other Roles
- **Developers**: Coaches on agile practices, removes blockers, facilitates sprint ceremonies
- **Product Manager**: Collaborates on backlog refinement, communicates team capacity and velocity
- **Project Manager**: Coordinates on delivery timelines, escalates systemic impediments
- **UX Designer**: Ensures design work is integrated into sprint planning and acceptance criteria
- **DevOps Engineer**: Collaborates on process improvements and automation of workflows

### Example Collaboration Scenario
During sprint planning, the Scrum Master notices the team is committing to more story points than their recent velocity suggests is achievable. They facilitate a discussion with the Product Manager to prioritize the most critical features and defer lower-priority items, ensuring a realistic sprint commitment. They also identify a recurring blocker around environment provisioning and work with the DevOps Engineer to automate the process for future sprints.

---

## UX Designer

### Role Summary
UX Designers research user needs, create design solutions, and validate usability. They ensure that products are intuitive, accessible, and deliver exceptional user experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and information architecture
- Collaborate with Product Managers to align designs with product vision
- Work with Developers to ensure design feasibility and implementation quality
- Maintain design systems and component libraries

### Goals
- Create intuitive and delightful user experiences
- Validate designs through user research and testing
- Ensure accessibility and inclusive design
- Reduce friction and improve user task completion rates

### Typical Communication
- Design reviews with Product Managers and stakeholders
- Implementation guidance and collaboration with Developers
- User research findings and usability test reports
- Design specs and component documentation

### Interactions with Other Roles
- **Product Manager**: Collaborates on feature definition, validates solutions with user research
- **Developers**: Provides design specs, reviews implementations, answers questions during development
- **Scrum Master**: Participates in sprint planning to estimate design work and dependencies
- **Project Manager**: Communicates design milestone timelines and dependencies
- **DevOps Engineer**: Ensures design assets are properly integrated into build and deployment pipelines

### Example Collaboration Scenario
The UX Designer conducts usability testing on a new checkout flow and discovers users are confused by the payment options layout. They create an alternative design and collaborate with the Product Manager to validate it addresses business requirements. During sprint planning, facilitated by the Scrum Master, they work with Developers to break the implementation into smaller stories and agree on acceptance criteria that include both functional requirements and design quality standards. The DevOps Engineer ensures the design assets are properly versioned and deployed through the CI/CD pipeline.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and monitoring systems. They enable fast, reliable, and secure software delivery through automation and operational excellence.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure and environments (dev, staging, production)
- Implement monitoring, logging, and alerting systems
- Ensure security scanning and compliance in deployment processes
- Optimize build times and deployment reliability
- Support incident response and troubleshooting

### Goals
- Reduce deployment time and increase deployment frequency
- Improve system reliability and observability
- Automate repetitive operational tasks
- Ensure security and compliance throughout the delivery pipeline

### Typical Communication
- Infrastructure status updates and incident reports
- Pipeline performance metrics and optimization proposals
- Security scan results and remediation recommendations
- Runbooks and operational documentation

### Interactions with Other Roles
- **Developers**: Provides tooling and automation, troubleshoots build and deployment issues
- **Project Manager**: Communicates infrastructure timelines, resource requirements, and risks
- **Scrum Master**: Collaborates on process improvements and automation opportunities
- **Product Manager**: Ensures infrastructure supports product goals and scalability requirements
- **UX Designer**: Integrates design assets into build and deployment processes

### Example Collaboration Scenario
A Developer raises a concern during standup that the CI pipeline is taking 45 minutes to run, slowing down their feedback cycle. The DevOps Engineer investigates and identifies opportunities to parallelize tests and cache dependencies. They collaborate with the Scrum Master to prioritize this improvement work in the next sprint. After implementing the changes, build times drop to 15 minutes, significantly improving developer productivity. The DevOps Engineer documents the changes in a runbook and shares the metrics with the Project Manager for the weekly status report.

---

## Role Onboarding Checklist

Use this checklist when onboarding new team members to any role:

- [ ] Review the persona definition for their role in this document
- [ ] Understand primary responsibilities and goals
- [ ] Identify key interaction points with other roles
- [ ] Review relevant project artifacts (charter, backlog, documentation)
- [ ] Schedule introductory meetings with key collaborators from other roles
- [ ] Review communication cadences and meeting schedules
- [ ] Access required tools, systems, and repositories
- [ ] Review recent retrospective notes to understand ongoing improvements
- [ ] Shadow at least one full sprint/iteration cycle before taking full ownership
- [ ] Complete role-specific training or certification if required

---

## Role Interaction Expectations

### General Principles
- **Respect expertise**: Trust each role's domain knowledge and decision-making authority
- **Communicate proactively**: Share information early, especially about blockers or changes
- **Collaborate openly**: Seek input from relevant roles before making decisions that affect their work
- **Document decisions**: Capture key decisions and context for future reference
- **Give constructive feedback**: Focus on behaviors and outcomes, not personal attributes

### Cross-Role Collaboration Checklist
- [ ] Clarify ownership and accountability for deliverables
- [ ] Define communication channels and response time expectations
- [ ] Establish regular sync meetings or touchpoints
- [ ] Agree on Definition of Done and acceptance criteria
- [ ] Identify dependencies and handoff points
- [ ] Create escalation paths for blockers or conflicts
- [ ] Document shared processes and workflows
- [ ] Review and adjust collaboration patterns during retrospectives

---

## Reference Template: Adding or Updating Roles

Use this template when adding new roles or updating existing role definitions:

### 1. Role Definition
- **Role Title**: [Official role name]
- **Role Summary**: [1-2 sentence overview]
- **Responsibilities**: [Bulleted list of key duties]
- **Goals**: [Primary objectives and success metrics]
- **Typical Communication**: [How this role communicates and reports]

### 2. Interactions
- **[Other Role Name]**: [Description of how they collaborate]
- [Repeat for each relevant role]

### 3. Example Scenario
[Provide at least one concrete example of effective collaboration that illustrates the role in action]

### 4. Impact Assessment
Document where this role should be referenced in other process documents:
- [ ] Project Management Overview (Core Roles section)
- [ ] Project Planning (if involved in planning activities)
- [ ] Execution & Tracking (if involved in day-to-day delivery)
- [ ] Release & Deployment (if involved in release activities)
- [ ] Retrospective & Continuous Improvement (if facilitating or driving improvements)

### 5. Onboarding Considerations
- [ ] Add role-specific onboarding steps to the Role Onboarding Checklist
- [ ] Update interaction expectations with existing roles
- [ ] Create or update role-specific documentation or runbooks

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

