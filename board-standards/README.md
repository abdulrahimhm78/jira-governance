# Board Standards (Enterprise Scrum)

Enterprise board standards define how work is visualized, tracked, and governed to ensure transparency, flow, and predictable delivery across teams.

---

## Purpose

To establish a consistent, auditable, and outcome-focused way of managing work on Scrum and Kanban boards while preserving team autonomy.

---

## Scope

Applies to all delivery teams using Jira, Azure DevOps, or equivalent tooling across product, platform, data, and infrastructure domains.

---

## Board Structure

### Required Columns
- **Backlog** – Prioritized, refined, and DoR-compliant items only
- **Ready** – Sprint-ready items approved for pull
- **In Progress** – Actively worked items (WIP enforced)
- **In Review / Test** – Validation, QA, or peer review
- **Done** – Meets Definition of Done

Optional (context-dependent):
- Blocked
- Awaiting Dependency
- Release Ready

---

## Work Item Standards

### Required Fields
- Clear title (business outcome–oriented)
- Description with context
- Acceptance criteria
- Owner
- Priority
- Sprint / Iteration
- Estimate (if applicable)
- Dependencies (linked)

### Prohibited
- Placeholder or vague titles
- Unestimated work entering a sprint
- Work without acceptance criteria
- “Parking lot” tickets with no owner

---

## WIP (Work In Progress) Limits

- Enforced per column where applicable
- Explicitly defined by the team
- Breaches require team discussion, not silent overflow

**Guiding Principle:** Stop starting, start finishing.

---

## Flow & Status Rules

- Only one active status per work item
- Status reflects *actual* work state, not intent
- Blocked items must:
  - Be clearly marked
  - Include a reason
  - Have an escalation owner

---

## Sprint Discipline

- No scope added mid-sprint without explicit trade-off
- Incomplete work returns to backlog with context
- Done means Done per Definition of Done—no exceptions

---

## Dependency Management

- Dependencies must be:
  - Identified before sprint start
  - Linked to external work items
  - Reviewed daily during the Daily Scrum
- Cross-team dependencies tracked at program level

---

## Metrics & Visibility

Boards must support the following:
- Sprint commitment vs completion
- Cycle time
- Throughput
- WIP aging
- Blocker duration

Metrics are for inspection and improvement—not performance management.

---

## Governance & Hygiene

### Required Practices
- Daily board updates by the team
- Weekly backlog hygiene
- Sprint-end cleanup (no stale items)

### Auditable Signals
- Accurate timestamps
- Clear ownership
- Traceable decisions

---

## Anti-Patterns

- Boards used as status reports for management
- Tickets moving without work occurring
- Excessive columns masking bottlenecks
- Zombie tickets spanning multiple sprints

---

## Guiding Principles

- Visualize real work
- Optimize for flow, not utilization
- Make impediments impossible to ignore
- Let the board tell the truth

---

## Ownership

- **Team:** Accuracy and daily maintenance
- **Scrum Master:** Flow, discipline, and continuous improvement
- **Product Owner:** Priority integrity and backlog readiness

---

Consistent board standards enable clarity, trust, and predictable delivery at enterprise scale.
