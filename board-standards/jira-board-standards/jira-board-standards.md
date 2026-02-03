# Jira Board Standards (Enterprise)

This document defines the minimum standards for configuring, maintaining, and operating Jira boards to ensure transparency, predictability, and delivery discipline across enterprise Scrum teams.

---

## Purpose

To provide a consistent, auditable, and outcome-focused Jira board structure that supports:
- Accurate delivery tracking
- Flow-based execution
- Clear accountability
- Reliable metrics for teams and leadership

---

## Scope

These standards apply to:
- Scrum and Scrumban teams
- Delivery and platform teams
- Enterprise and scaled Agile environments

---

## Board Design Principles

- The board reflects **how work actually flows**
- Statuses represent **states of work**, not people or roles
- Every column must have **clear entry and exit criteria**
- The board is the **single source of truth** for delivery status

---

## Standard Workflow (Scrum)

### Required Statuses

| Status | Description |
|------|-------------|
| Backlog | Approved, refined work not yet committed |
| Selected for Sprint | Work committed for the sprint |
| In Progress | Actively being worked |
| Code Review | Development complete, under review |
| Testing | Functional, integration, or regression testing |
| Ready for Release | Meets DoD, awaiting deployment |
| Done | Released and verified |

> Status names may vary, but intent and flow must remain consistent.

---

## Work Item Rules

- Every item must have:
  - Clear title and description
  - Acceptance criteria
  - Owner or accountable role
  - Sprint assignment (if in progress)
- No item may move to **Done** without meeting Definition of Done
- No work may start without meeting Definition of Ready

---

## WIP (Work In Progress) Discipline

- WIP limits must be defined for:
  - In Progress
  - Code Review
  - Testing
- Teams should:
  - Finish work before starting new work
  - Swarm to unblock stalled items
- Aging work items must be reviewed daily

---

## Blockers and Impediments

- Blocked items must be explicitly flagged
- Reason for block must be documented
- Blockers older than 24 hours require:
  - Escalation
  - Clear owner
  - Expected resolution date

---

## Sprint Usage Rules

- Only committed sprint work appears on the active board
- Scope changes during a sprint must be:
  - Visible
  - Explicitly discussed
  - Approved by Product Owner
- Completed work must be moved to Done before sprint close

---

## Metrics and Reporting Standards

### Required Metrics

- Sprint commitment vs completion
- Cycle time
- Work item aging
- Blocker frequency and duration
- Carryover rate

### Metric Integrity Rules

- Status changes must reflect real work state
- No bulk or retroactive status updates
- Automation rules must be transparent and documented

---

## Board Hygiene Expectations

- Daily updates by the team
- No stale items in active columns
- No duplicate or orphaned tickets
- Clear linkage between:
  - Epics → Stories → Tasks (if used)

---

## Anti-Patterns (Not Allowed)

- Using Jira as a status reporting tool only
- Moving items without real progress
- Closing work to meet metrics
- Hidden work outside the board
- Long-lived “In Progress” items

---

## Ownership and Accountability

- The team owns board accuracy
- The Scrum Master enforces discipline and flow
- The Product Owner ensures backlog clarity and priority
- Leadership relies on the board for delivery visibility

---

## Guiding Principle

> If the Jira board does not reflect reality, delivery risk is already present.

Transparency over perfection. Flow over activity. Outcomes over output.
