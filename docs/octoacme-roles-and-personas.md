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
UX Designers lead user research, prototyping, and usability testing to ensure the product is user-centered and intuitive. They translate user insights into actionable design requirements and work closely with Product Managers and Developers to deliver seamless user experiences.

### Responsibilities
- Conduct user research and usability testing to understand user needs and pain points
- Create wireframes, prototypes, and high-fidelity designs
- Define information architecture and interaction patterns
- Collaborate with Product Managers to translate user insights into product requirements
- Work with Developers to ensure design feasibility and implementation fidelity
- Maintain design systems and component libraries for consistency

### Goals
- Create intuitive, accessible user experiences that delight users
- Reduce user friction and increase product adoption
- Ensure design consistency across the product
- Balance user needs with business goals and technical constraints

### Interactions with Other Roles
- **Product Managers**: Collaborate on product vision, feature prioritization, and user research insights; validate that designs address user needs and business goals
- **Developers**: Partner on technical feasibility, design implementation, and responsive behavior; participate in design reviews and provide design specs
- **Project Managers**: Contribute to timeline planning with design milestones; communicate design dependencies and risks

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholders, customers, and the delivery team. They document business requirements, analyze process flows, and ensure that technical solutions align with business objectives.

### Responsibilities
- Gather and document business requirements from stakeholders and customers
- Create process flows, business rules, and requirement specifications
- Support backlog refinement and decomposition of complex work items
- Conduct feasibility analysis and impact assessments
- Facilitate requirements workshops and validation sessions
- Ensure traceability between business needs and delivered solutions

### Goals
- Translate business needs into clear, actionable requirements
- Prevent requirement gaps and miscommunication
- Ensure solutions deliver measurable business value
- Facilitate alignment between business and technical teams

### Interactions with Other Roles
- **Product Managers**: Support product discovery and requirement definition; provide business analysis and process documentation
- **Developers**: Clarify requirements and acceptance criteria; assist with technical questions about business rules and workflows
- **Project Managers**: Contribute to project planning with requirement analysis; identify dependencies and risks related to business processes

---

## Release Manager

### Role Summary
Release Managers coordinate and orchestrate release activities across teams to ensure smooth, reliable deployments. They own the release schedule, manage deployment checklists, and coordinate incident response during releases.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Manage release checklists and gate criteria
- Communicate release schedules, risks, and status to all stakeholders
- Coordinate cross-team dependencies for complex releases
- Own incident response and rollback coordination during deployments
- Maintain release documentation and post-release reports
- Track release metrics and identify improvement opportunities

### Goals
- Achieve zero-downtime releases with minimal business disruption
- Reduce deployment risk through standardized processes
- Maintain clear communication and transparency during releases
- Continuously improve release velocity and reliability

### Interactions with Other Roles
- **Developers**: Coordinate code freeze timelines and deployment readiness; facilitate technical release validation
- **Product Managers**: Align release content with product roadmap; communicate release scope and feature availability
- **Project Managers**: Sync on project milestones and release dependencies; escalate release risks and blockers
- **QA Automation Engineer**: Ensure automated test coverage is adequate before release; coordinate smoke testing and validation
- **Support Lead**: Prepare support team for upcoming releases; coordinate handoff of release notes and known issues

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers design, implement, and maintain automated test frameworks that enable continuous integration and delivery. They ensure quality through comprehensive automated testing and mentor the team on testing best practices.

### Responsibilities
- Design and implement automated test frameworks and infrastructure
- Create and maintain automated test suites (unit, integration, end-to-end)
- Integrate automated tests into CI/CD pipelines
- Monitor test results and investigate failures
- Mentor developers on writing testable code and reliable tests
- Define testing strategies and coverage goals
- Identify and implement test automation tools and best practices

### Goals
- Maximize test coverage while minimizing test maintenance burden
- Enable fast, reliable feedback through automated testing
- Reduce manual testing effort and increase release confidence
- Foster a culture of quality and testability across the team

### Interactions with Other Roles
- **Developers**: Collaborate on test design and implementation; provide guidance on testability and mocking strategies; review test code in PRs
- **Product Managers**: Understand acceptance criteria to ensure comprehensive test coverage; provide quality metrics and testing status
- **Project Managers**: Report on test automation progress and quality metrics; identify testing risks and resource needs
- **Release Manager**: Validate test coverage before releases; coordinate automated smoke testing during deployments

---

## Support Lead

### Role Summary
Support Leads monitor post-release product health, manage customer feedback and incidents, and serve as the voice of the customer back to the product and engineering teams. They ensure smooth handoffs between development and support.

### Responsibilities
- Monitor post-release incidents and customer-reported issues
- Triage and escalate critical bugs to development teams
- Coordinate with Developers and PM on hotfixes and patches
- Gather and synthesize customer feedback for product improvement
- Maintain knowledge base and support documentation
- Facilitate knowledge transfer sessions before major releases
- Represent customer voice in retrospectives and planning

### Goals
- Minimize mean time to resolution (MTTR) for customer issues
- Ensure smooth customer experience during and after releases
- Create feedback loops between support, product, and engineering
- Build comprehensive knowledge base to enable customer self-service

### Interactions with Other Roles
- **Developers**: Escalate bugs with reproduction steps; coordinate on hotfix priorities and deployment
- **Product Managers**: Share customer feedback and pain points; influence backlog priorities based on support trends
- **Project Managers**: Report on support impact of releases; participate in retrospectives with customer insights
- **Release Manager**: Receive release notes and prepare support team; provide feedback on release communication effectiveness

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

