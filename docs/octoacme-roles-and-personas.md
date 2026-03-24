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

## UX/UI Designer

### Role Summary
UX/UI Designers create user experiences and interfaces that align with business requirements and technical constraints. They bridge the gap between user needs and product delivery by producing clear, usable designs.

### Responsibilities
- Design wireframes, prototypes, and high-fidelity mockups
- Conduct usability testing and incorporate user feedback
- Define and maintain design standards and component libraries
- Collaborate with Product Managers to understand requirements and priorities
- Work with Developers to ensure technical feasibility and accurate implementation

### Goals
- Deliver intuitive, accessible, and visually consistent experiences
- Reduce friction and increase user satisfaction
- Ensure design decisions are grounded in user research and data

### Typical Communication
- Design reviews and prototype walkthroughs with Product Managers and Developers
- Usability test summaries and feedback reports
- Handoff documentation and annotated design specs

### Interaction with Existing Roles
- **Product Managers (PdM):** Receive requirements and success criteria; collaborate on feature scope and user stories
- **Developers:** Share design specs, participate in feasibility discussions, and review implemented UIs
- **Project Managers (PM):** Align on design milestones and flag blockers affecting delivery timelines

---

## QA Engineer

### Role Summary
QA Engineers ensure the quality and reliability of released software by developing test plans, executing manual and automated tests, and validating that acceptance criteria are met before releases.

### Responsibilities
- Develop and maintain test plans, test cases, and test scripts
- Execute manual and automated regression, integration, and end-to-end tests
- Report, track, and verify bugs through resolution
- Collaborate with Developers on root cause analysis and fix verification
- Validate that acceptance criteria defined by Product Managers are fully satisfied

### Goals
- Prevent defects from reaching production
- Shorten feedback loops between development and quality validation
- Continuously improve test coverage and automation reliability

### Typical Communication
- Test summary reports before releases
- Bug reports with reproduction steps and severity ratings
- Participation in sprint planning and acceptance criteria reviews

### Interaction with Existing Roles
- **Developers:** Collaborate on defect triage, root cause analysis, and fix verification
- **Product Managers (PdM):** Review acceptance criteria and confirm feature completeness
- **Project Managers (PM):** Report test status, surface quality risks, and communicate release readiness

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for products, processes, and APIs. They ensure that documentation serves the needs of both internal teams and end users.

### Responsibilities
- Author and maintain product documentation, user guides, and release notes
- Document internal processes and runbooks
- Collaborate with all team members to verify accuracy and completeness of content
- Review and edit contributor-submitted documentation for clarity and consistency
- Maintain a documentation style guide and standards

### Goals
- Ensure that all stakeholders have access to clear, up-to-date documentation
- Reduce onboarding time for new team members and users
- Improve self-service and reduce support burden through effective documentation

### Typical Communication
- Documentation reviews and sign-offs with subject matter experts across all roles
- Release note drafts shared with Product Managers before publication
- Style guide updates communicated to the broader team

### Interaction with Existing Roles
- **Developers:** Gather technical details for API docs, runbooks, and architectural overviews
- **Product Managers (PdM):** Align on feature descriptions, release notes, and user-facing content
- **Project Managers (PM):** Document process changes, meeting outcomes, and status updates as needed
- **QA Engineers:** Incorporate known issues and workarounds into release documentation

---

## DevOps/SRE (Site Reliability Engineer)

### Role Summary
DevOps/SRE engineers own the reliability, automation, and operational health of the platform. They design and maintain CI/CD pipelines, manage deployments, monitor system health, and lead incident response.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Monitor system uptime, performance, and reliability metrics
- Lead incident response, conduct post-incident reviews, and drive root cause analysis
- Manage infrastructure-as-code and environment configurations
- Collaborate with Developers on deployment readiness and operational best practices

### Goals
- Maximize system availability and reduce mean time to recovery (MTTR)
- Automate repetitive operational tasks to free up engineering capacity
- Ensure deployments are safe, repeatable, and auditable

### Typical Communication
- Incident reports and post-mortems
- Deployment status updates and release checklists
- Infrastructure change notifications and on-call runbooks

### Interaction with Existing Roles
- **Developers:** Advise on deployment readiness, review infrastructure changes, and support local environment setup
- **Project Managers (PM):** Provide deployment status and flag operational risks that could affect release timelines
- **Product Managers (PdM):** Communicate service-level impacts and capacity constraints that influence roadmap decisions

---

## Support Lead

### Role Summary
The Support Lead acts as the primary liaison between users or customers and the delivery team. They surface user feedback, escalate critical issues, and help refine requirements based on real-world usage.

### Responsibilities
- Triage and escalate user-reported issues to the appropriate team members
- Maintain a feedback loop between customers and the product/engineering team
- Document recurring user pain points and propose improvements
- Assist Product Managers in refining requirements based on support trends and user feedback
- Communicate known issues and workarounds to users in a timely manner

### Goals
- Reduce user friction by ensuring issues are resolved quickly and transparently
- Provide the product team with actionable, data-driven customer insights
- Improve user satisfaction and reduce escalation volume over time

### Typical Communication
- Support ticket summaries and escalation reports shared with Product Managers and Project Managers
- Weekly feedback digests highlighting trends and recurring issues
- Coordination with Developers on hotfixes and urgent bug resolution

### Interaction with Existing Roles
- **Product Managers (PdM):** Share user feedback and support trends to inform backlog prioritization and requirement refinement
- **Developers:** Escalate high-severity bugs and collaborate on reproducing and resolving user-reported issues
- **Project Managers (PM):** Flag issues that may affect release readiness or require expedited delivery

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

