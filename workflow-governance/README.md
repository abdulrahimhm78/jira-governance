# Workflow Governance (Enterprise Standard)

## Purpose
Workflow Governance establishes clear, enforceable rules for how work flows from ideation to delivery across teams. It ensures consistency, predictability, compliance, and transparency while enabling teams to operate autonomously within defined guardrails.

## Scope
This governance applies to:
- All Scrum and Kanban teams
- Backlog intake through delivery and release
- Portfolio, program, and team-level workflows
- Jira/Azure DevOps workflow configurations

## Guiding Principles
- **Flow over utilization**: Optimize for end-to-end delivery, not individual efficiency
- **Explicit policies**: Make workflow rules visible and unambiguous
- **Built-in quality**: Enforce quality gates early, not at the end
- **Decentralized execution, centralized standards**
- **Inspect and adapt continuously**

## Standard Workflow States
The following states are the enterprise baseline. Teams may extend but not remove required states.

1. **Intake**
   - Idea captured
   - High-level business context defined
   - Not committed to delivery

2. **Refinement**
   - Meets Definition of Ready (DoR)
   - Dependencies identified
   - Sized and prioritized

3. **Ready**
   - Approved for sprint pull
   - No unresolved blockers

4. **In Progress**
   - Actively being worked
   - WIP limits enforced

5. **Code Review / Validation**
   - Peer review completed
   - Automated checks executed

6. **Testing**
   - Functional and non-functional validation
   - Defects tracked explicitly

7. **Done**
   - Meets Definition of Done (DoD)
   - Potentially shippable

8. **Released (if applicable)**
   - Deployed to production or customer-accessible environment

## Entry and Exit Criteria
Each workflow state must have:
- Clear **entry criteria**
- Clear **exit criteria**
- Ownership accountability

Items may not move forward unless exit criteria are met.

## WIP Limits
- WIP limits are mandatory for all active states
- Default guidance:
  - In Progress: 1–2 items per team member
  - Review/Test: Based on team capacity
- Breaching WIP limits requires explicit team agreement

## Governance Controls
### Required Controls
- DoR enforced before sprint planning
- DoD enforced before closure
- Blockers explicitly tracked
- Aging work reviewed weekly
- Dependency tags applied consistently

### Prohibited Practices
- Skipping workflow states
- Moving work backward without explanation
- Closing work that does not meet DoD
- Using workflow transitions to hide delays

## Roles and Accountability
- **Product Owner**
  - Owns backlog flow and prioritization
  - Ensures readiness and value clarity

- **Scrum Master**
  - Enforces workflow discipline
  - Monitors flow metrics
  - Escalates systemic issues

- **Delivery Team**
  - Respects WIP limits
  - Maintains workflow integrity
  - Owns quality

- **Leadership**
  - Removes systemic constraints
  - Uses metrics for learning, not blame

## Metrics and Inspection
Workflow governance is inspected using:
- Cycle Time
- Lead Time
- Throughput
- Work Item Aging
- WIP adherence
- Flow efficiency

Metrics are reviewed at:
- Sprint Reviews
- Retrospectives
- Program-level syncs

## Exceptions and Escalation
- Exceptions to workflow rules require:
  - Explicit documentation
  - Time-bound approval
- Repeated exceptions trigger governance review

## Continuous Improvement
Workflow policies are:
- Reviewed quarterly
- Updated based on empirical data
- Communicated before enforcement

## Guiding Statement
> Governance exists to enable flow, not restrict it.  
> If governance does not improve delivery, it must be changed.
