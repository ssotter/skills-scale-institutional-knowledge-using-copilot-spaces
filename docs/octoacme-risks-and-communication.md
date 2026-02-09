# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths

### Standard Escalation Hierarchy
**Level 1: Team-Level Resolution**
- **Who**: Development team, Agile Coach, immediate team members
- **When**: Day-to-day blockers, technical questions, minor issues
- **Timeframe**: Resolve within 1-2 business days
- **Examples**: Code review questions, minor technical decisions, task clarifications

**Level 2: Project Management Escalation**
- **Who**: Project Manager, Product Owner, Business Analyst
- **When**: Cross-team dependencies, resource conflicts, scope questions
- **Timeframe**: Resolve within 3-5 business days
- **Examples**: Dependency blockers, priority conflicts, resource availability issues

**Level 3: Leadership Escalation**
- **Who**: Product Lead, Executive Sponsor, Department Heads
- **When**: Strategic decisions, budget impacts, timeline risks
- **Timeframe**: Decision needed within 1 week
- **Examples**: Significant scope changes, budget overruns, major timeline shifts

**Level 4: Executive/Crisis Escalation**
- **Who**: C-level executives, Crisis management team
- **When**: Business-critical issues, major incidents, regulatory concerns
- **Timeframe**: Immediate attention required
- **Examples**: Security breaches, compliance violations, customer-impacting outages

### Role-Specific Escalation Paths

**For Technical Issues**:
Team → Agile Coach/Tech Lead → Engineering Manager → CTO

**For Compliance/Regulatory Issues**:
Compliance Analyst → Legal/Security Team → General Counsel → CEO

**For Change Management Issues**:
Change Manager → Project Manager → Change Sponsor → Executive Sponsor

**For Quality Issues**:
Quality Champion → Product Owner → Product Manager → Product Lead

**For Business Requirements**:
Business Analyst → Product Owner → Product Manager → Business Stakeholder Lead

### Special Escalation Scenarios

**Security Incidents**:
- Immediate notification to Security on-call
- Follow security incident runbook
- Compliance Analyst engaged for regulatory impact assessment
- Communications team engaged for external impact

**Compliance Violations**:
- Immediate notification to Compliance Analyst
- Legal team engaged
- Work may be paused pending review
- Remediation plan required before proceeding

**Customer-Impacting Issues**:
- Immediate notification to Product Manager and Support team
- Communication plan activated
- Incident commander assigned
- Post-incident review scheduled

---

## Role Handoffs & Transitions

### Purpose
Ensure smooth transitions between project phases and roles, with clear accountability and complete knowledge transfer.

### Handoff Principles
- Document decisions and context before handoff
- Include next role in final meetings/reviews
- Provide time for questions and knowledge transfer
- Use written handoff summaries
- Confirm understanding before closing handoff

### Key Project Phase Handoffs

#### Initiation → Planning
**From**: Business stakeholders, Product Manager  
**To**: Project Manager, Product Owner, Business Analyst

**Handoff Package**:
- [ ] Project one-pager approved
- [ ] Initial stakeholder list and communication plan
- [ ] Success metrics defined
- [ ] High-level timeline and milestones
- [ ] Initial risk assessment
- [ ] Business case and justification

**Handoff Meeting**: Project Kickoff
- Review project charter
- Confirm understanding of business objectives
- Clarify success criteria
- Identify open questions

#### Planning → Execution
**From**: Project Manager, Business Analyst, Product Owner  
**To**: Development Team, Agile Coach, Quality Champion

**Handoff Package**:
- [ ] Detailed project plan with milestones
- [ ] Refined and prioritized backlog
- [ ] Technical architecture and design documents
- [ ] Resource allocation confirmed
- [ ] Risk register with mitigation plans
- [ ] Acceptance criteria for features
- [ ] Definition of Done established

**Handoff Meeting**: Sprint 0 or Planning Complete Review
- Walkthrough of backlog and priorities
- Review technical approach
- Confirm team capacity and commitments
- Clarify escalation paths

#### Execution → Testing/QA
**From**: Developers  
**To**: Quality Champion, QA Team, Compliance Analyst (if applicable)

**Handoff Package**:
- [ ] Feature complete and code frozen
- [ ] Unit and integration tests passing
- [ ] Known issues documented
- [ ] Test data and environments prepared
- [ ] Test plan reviewed
- [ ] Compliance checkpoints completed (if applicable)

**Handoff Meeting**: QA Kickoff
- Demo of completed features
- Review test scope and timeline
- Discuss known limitations
- Confirm acceptance criteria

#### Testing → Release/Deployment
**From**: Quality Champion, QA Team  
**To**: DevOps/Release Team, Product Owner, Change Manager

**Handoff Package**:
- [ ] Test results and quality metrics
- [ ] All critical defects resolved
- [ ] Accepted defects documented with workarounds
- [ ] Release notes drafted
- [ ] Deployment runbook prepared
- [ ] Rollback plan documented
- [ ] Change management plan (for significant changes)

**Handoff Meeting**: Release Readiness Review
- Review test results and quality status
- Confirm deployment approach
- Review rollback procedures
- Finalize go/no-go decision

#### Release → Operations/Support
**From**: Development Team, Product Owner  
**To**: Support Team, Operations Team

**Handoff Package**:
- [ ] Production deployment completed
- [ ] Monitoring and alerts configured
- [ ] Support documentation and runbooks
- [ ] Known issues and workarounds
- [ ] Training materials for support team
- [ ] Escalation contacts for development team
- [ ] Success metrics and dashboards

**Handoff Meeting**: Production Handoff
- Walkthrough of new features
- Review monitoring and support procedures
- Q&A session with support team
- Establish on-call/support rotation

#### Project Close → Continuous Improvement
**From**: Project Manager, entire team  
**To**: Leadership, Future projects

**Handoff Package**:
- [ ] Project retrospective completed
- [ ] Lessons learned documented
- [ ] Final metrics and outcomes report
- [ ] Process improvements identified
- [ ] Documentation archived appropriately
- [ ] Team recognition and celebration

**Handoff Meeting**: Project Retrospective
- Celebrate successes
- Identify improvement opportunities
- Document lessons learned
- Close out project formally

### Cross-Role Collaboration & Handoffs

**Product Owner ↔ Business Analyst**
- Regular requirement refinement sessions
- Shared ownership of requirements documentation
- Handoff: Business Analyst completes analysis → Product Owner prioritizes

**Project Manager ↔ Change Manager**
- Alignment on change timelines and project schedule
- Shared responsibility for stakeholder communication
- Handoff: Change impact identified → Change Manager executes plan

**Compliance Analyst ↔ Quality Champion**
- Shared responsibility for quality and compliance standards
- Compliance requirements integrated into quality checks
- Handoff: Compliance requirements defined → Quality tests validate compliance

**Agile Coach ↔ Project Manager**
- Collaborative process improvement
- Shared facilitation of team ceremonies
- Handoff: Process impediment identified → Resolution owner determined

### Handoff Checklist Template

**Handoff From**: __________ **To**: __________  
**Date**: __________ **Phase**: __________

- [ ] Handoff package complete and shared
- [ ] Handoff meeting scheduled and completed
- [ ] Questions answered and concerns addressed
- [ ] Next steps and accountabilities confirmed
- [ ] Documentation updated and accessible
- [ ] Receiving role confirms readiness to proceed

**Notes**: 

**Sign-off**:
- From: _________________ Date: _________
- To: _________________ Date: _________

---

## Escalation Triggers

### When to Escalate
Escalate proactively when you observe:
- Issues that cannot be resolved at current level within expected timeframe
- Risks that could impact project timeline, budget, or quality significantly
- Decisions that exceed your authority or expertise
- Conflicts between teams or stakeholders
- Compliance or security concerns
- Customer impact or potential customer impact
- Resource constraints preventing progress

### How to Escalate Effectively
1. **Prepare**: Gather facts, document the issue, identify options
2. **Context**: Explain business impact and urgency
3. **Options**: Present alternatives with pros/cons
4. **Recommendation**: Suggest a preferred path forward
5. **Ask**: Be clear about what decision or help you need
6. **Follow-up**: Document the decision and next steps

### Escalation Communication Template
**Subject**: Escalation: [Brief Issue Description]

**Issue Summary**: [What is the problem?]

**Impact**: [How does this affect the project/business?]

**Urgency**: [When do we need a decision/resolution?]

**Context**: [Background and relevant details]

**Options Considered**:
1. Option A: [Description, Pros, Cons]
2. Option B: [Description, Pros, Cons]

**Recommendation**: [Your suggested approach and why]

**Decision Needed**: [What specifically needs to be decided?]

**Next Steps**: [What happens after the decision?]

---

## Related Documents
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) - See all role descriptions
- [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md) - See blocker escalation
- [OctoAcme Change Management Template](octoacme-change-management-template.md)
- [OctoAcme Compliance Checklist](octoacme-compliance-checklist.md)
