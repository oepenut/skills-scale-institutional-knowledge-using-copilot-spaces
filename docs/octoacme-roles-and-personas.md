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
QA/Testing Leads own quality assurance strategy, test planning, and validation of acceptance criteria across projects. They collaborate with developers and product managers to ensure solutions meet quality standards before release.

### Responsibilities
- Develop and maintain test plans aligned with acceptance criteria
- Define testing strategy (unit, integration, end-to-end, performance, security)
- Identify and log defects with clear reproduction steps
- Validate that acceptance criteria are met before feature handoff
- Partner with developers on test automation and coverage targets
- Conduct manual QA testing when automation is not applicable
- Report quality metrics and risk to PM and delivery team

### Goals
- Ensure all releases meet quality and acceptance criteria
- Reduce defects reaching production and customer impact
- Enable fast, confident deployments through robust testing

### Typical Communication
- Acceptance criteria reviews with Product Manager
- Test plan discussions in planning and kickoff meetings
- Daily standups with delivery team on test progress
- Quality reports in weekly syncs and releases

### Interaction with Existing Roles
- **Developers**: Collaborates on test automation strategy, reviews test coverage, and validates fixes for logged defects
- **Product Managers**: Aligns test approach with acceptance criteria and validates feature completeness
- **Project Managers**: Reports quality status, identifies testing risks, and coordinates test execution timeline

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, design oversight, and technical risk identification. They ensure solutions are scalable, maintainable, and aligned with long-term technical strategy.

### Responsibilities
- Review technical designs and architecture decisions
- Identify technical risks, scalability concerns, and performance implications
- Guide decisions on technology choices and trade-offs
- Mentor developers and drive technical excellence
- Ensure code quality and adherence to standards through reviews
- Collaborate with Product Lead on technical feasibility and constraints
- Escalate technical blockers and dependencies

### Goals
- Deliver solutions that are scalable, secure, and maintainable
- Reduce technical debt and risk
- Ensure architectural consistency across projects

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and feedback
- Weekly sync with Product Lead and PM on technical progress
- Risk escalation and dependency coordination

### Interaction with Existing Roles
- **Developers**: Provides technical mentorship, reviews designs and code, removes technical blockers
- **Product Managers**: Advises on technical feasibility, constraints, and trade-offs for feature prioritization
- **Project Managers**: Escalates technical risks and dependencies that impact timeline and scope

---

## Scrum Master / Delivery Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove process blockers, and coach teams on process adherence and continuous improvement. They enable teams to work efficiently within their chosen framework (Scrum, Kanban, etc.).

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and reviews
- Remove impediments that block team progress
- Coach team members on agile practices and mindsets
- Track and report on team velocity and process health
- Identify and escalate systemic process issues
- Foster psychological safety and team collaboration
- Guide the team through process improvements

### Goals
- Enable team productivity and predictability
- Reduce cycle time and improve delivery efficiency
- Create a high-performing, self-organizing team
- Build a culture of continuous improvement

### Typical Communication
- Daily standups with delivery team
- Sprint retrospectives and planning sessions
- Weekly process health reports
- One-on-one coaching with team members

### Interaction with Existing Roles
- **Developers**: Removes blockers, facilitates ceremonies, coaches on technical practices
- **Product Managers**: Coordinates on backlog readiness and sprint planning
- **Project Managers**: Works collaboratively on timeline management and risk escalation

---

## Product Operations / PMO Lead

### Role Summary
Product Operations and PMO leads manage cross-project dependencies, portfolio prioritization, and resource allocation. They provide operational support and visibility across multiple concurrent projects to ensure organizational alignment and efficient resource utilization.

### Responsibilities
- Maintain portfolio-level view of all active projects and initiatives
- Identify and manage cross-project dependencies
- Coordinate resource allocation and capacity planning across teams
- Provide project governance and ensure adherence to standards
- Consolidate and report on portfolio metrics and health
- Escalate portfolio-level risks and blockers
- Support project teams with tools, templates, and processes

### Goals
- Maximize organizational throughput and resource utilization
- Reduce delays caused by cross-project dependencies
- Ensure portfolio alignment with strategic objectives
- Improve visibility and predictability of delivery

### Typical Communication
- Weekly portfolio health reviews
- Cross-project dependency coordination
- Resource allocation and capacity planning meetings
- Portfolio-level reporting to leadership

### Interaction with Existing Roles
- **Project Managers**: Coordinates across projects, manages dependencies, supports with governance
- **Product Managers**: Aligns portfolio prioritization with business strategy
- **Developers**: Provides visibility on resource availability and cross-project scheduling

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers advise on security requirements, compliance standards, and risk mitigation throughout the project lifecycle. They ensure solutions meet organizational security policies and regulatory obligations.

### Responsibilities
- Define security requirements and threat models for projects
- Advise on secure design patterns and implementation practices
- Conduct security reviews and threat assessments
- Ensure compliance with regulatory requirements and policies
- Identify security risks and recommend mitigations
- Coordinate security testing and vulnerability assessments
- Report on security posture and compliance status

### Goals
- Deliver secure, compliant solutions that protect customer data
- Reduce security vulnerabilities and compliance risks
- Build security awareness and capability across teams
- Enable confident releases without security delays

### Typical Communication
- Security requirements reviews during planning
- Threat assessments and design reviews
- Security testing coordination
- Risk escalation and compliance reporting

### Interaction with Existing Roles
- **Developers**: Advises on secure coding practices, reviews implementations for security
- **QA/Testing Lead**: Coordinates security testing and vulnerability assessment
- **Technical Lead**: Collaborates on architectural security decisions and threat modeling
- **Project Managers**: Escalates security risks and manages security review timelines

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers manage deployment pipelines, infrastructure, and operational readiness. They enable fast, reliable delivery of software and maintain production systems that support business operations.

### Responsibilities
- Design and maintain deployment pipelines and CI/CD infrastructure
- Provision and manage infrastructure (cloud, on-premise, hybrid)
- Implement monitoring, logging, and alerting for production systems
- Conduct performance and load testing
- Manage infrastructure security and access controls
- Support incident response and post-mortem actions
- Document infrastructure and runbooks for operational support

### Goals
- Enable fast, automated, and reliable deployments
- Maximize system availability and performance
- Reduce deployment risk and time-to-recovery from incidents
- Provide operational visibility and support

### Typical Communication
- Deployment planning and coordination with delivery team
- Infrastructure requirements during project planning
- Performance and reliability reports
- Incident response and post-mortem participation

### Interaction with Existing Roles
- **Developers**: Supports CI/CD pipelines, provides infrastructure APIs and tools
- **QA/Testing Lead**: Coordinates performance testing and staging environment setup
- **Project Managers**: Communicates deployment readiness and timeline constraints
- **Technical Lead**: Collaborates on infrastructure architecture and scalability decisions

---

## Business Analyst

### Role Summary
Business Analysts bridge stakeholders and engineering by translating business requirements into technical specifications. They validate that solutions address business needs and help identify opportunities for value creation.

### Responsibilities
- Conduct stakeholder interviews and gather business requirements
- Translate business needs into detailed user stories and acceptance criteria
- Create requirements documentation and use case models
- Validate solutions against business requirements
- Identify process improvements and optimization opportunities
- Communicate with stakeholders to gather feedback
- Support testing by defining test scenarios aligned with business outcomes

### Goals
- Ensure delivered solutions directly address business needs and create value
- Reduce miscommunication and rework due to unclear requirements
- Enable data-informed decision-making through business insights
- Improve stakeholder satisfaction and product adoption

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story definition and acceptance criteria refinement
- Business requirements documentation
- Solution validation with stakeholders

### Interaction with Existing Roles
- **Product Managers**: Collaborates on requirements definition and backlog prioritization
- **Developers**: Clarifies requirements, answers questions during implementation
- **QA/Testing Lead**: Defines business-driven test scenarios and acceptance criteria
- **Project Managers**: Communicates requirement changes and their impact on timeline

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- New roles provide complete coverage of typical project needs and reduce ambiguity about responsibilities.
