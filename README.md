# Jira Governance (Enterprise Standard)

## Purpose
This document defines enterprise-wide Jira governance standards to ensure consistency, transparency, traceability, and delivery predictability across all Agile teams.

Jira is the **system of record** for work intake, execution, and delivery reporting. If work is not in Jira, it does not exist.

---

## Governance Objectives
- Establish a single source of truth for delivery
- Enforce consistent backlog, sprint, and workflow hygiene
- Enable reliable metrics and executive reporting
- Prevent misuse of Jira as a task list or ticket dump
- Support auditability and compliance where required

---

## Scope
Applies to:
- All Scrum and Kanban teams
- Product Owners / Squad Leads
- Scrum Masters
- Engineering and QA teams
- Program and Delivery leadership

---

## Jira Ownership Model
| Area | Owner |
|-----|------|
| Jira Configuration | Agile Tools / Platform Team |
| Project Setup & Workflows | Scrum Master (with Tooling Team) |
| Backlog Quality | Product Owner |
| Board Hygiene | Scrum Master |
| Metrics & Reporting | Scrum Master / Program Leadership |
| Access & Permissions | Tooling / Admin Team |

---

## Issue Types (Standardized)
- **Epic** – Large business outcome spanning multiple sprints
- **Story** – User-facing or business-value work
- **Enabler / Technical Story** – Non-user-facing technical work
- **Bug** – Defect requiring correction
- **Spike** – Time-boxed research (must produce outcome)

No custom issue types without governance approval.

---

## Required Fields (Minimum)
All backlog items must include:
- Summary (clear, concise, outcome-oriented)
- Description (business context)
- Acceptance Criteria
- Priority
- Story Points (or size)
- Sprint (once committed)
- Assignee
- Labels (team, domain, or initiative-based)

Items missing required fields are **not eligible** for sprint commitment.

---

## Workflow Governance
### Standard Workflow States
- Backlog
- Ready
- In Progress
- Code Review
- Testing
- Done

Rules:
- No skipping states
- No custom states per team
- “Done” requires Definition of Done compliance
- Reopened work must re-enter workflow appropriately

---

## Backlog Governance
- Backlog ordered by **business value**
- Only Product Owner can prioritize
- Refinement occurs continuously
- Items must meet **Definition of Ready** before sprint planning
- No stale items older than 90 days without review

---

## Sprint Governance
- Sprint created before Sprint Planning
- Commitment finalized during Sprint Planning only
- Scope changes require PO + Scrum Master agreement
- Carryover tracked and reviewed explicitly
- Sprint closed only after Review and Retrospective

---

## Estimation & Capacity
- Estimation is team-owned
- Historical velocity used for planning, not targets
- Capacity accounts for PTO, support, and known interruptions
- No forced commitments

---

## Metrics Governance
Approved metrics:
- Velocity (trend-based)
- Sprint predictability
- Cycle time
- Throughput
- Work item aging
- Defect trends

Prohibited uses:
- Individual performance evaluation
- Comparing teams directly
- Velocity as a target

---

## Board Hygiene Standards
- Daily updates during the sprint
- No items stuck without comments > 2 days
- Blocked items explicitly flagged
- WIP limits respected
- Done items validated against DoD

---

## Reporting & Transparency
- Jira dashboards used for status, not slides
- Sprint reports reviewed every sprint
- Program-level rollups use Jira data only
- Manual status reporting is discouraged

---

## Compliance & Audit Readiness
- All delivery decisions traceable in Jira
- Acceptance captured explicitly
- Defects linked to stories when applicable
- Releases documented via versions or tags

---

## Anti-Patterns (Not Allowed)
- Using Jira only for reporting
- Updating tickets after the sprint
- Assigning work outside Jira
- Treating Jira as a personal to-do list
- Closing work without meeting DoD

---

## Enforcement
- Scrum Master enforces day-to-day governance
- Repeated violations escalated to Delivery Leadership
- Tooling team audits quarterly for compliance

---

## Guiding Principle
Jira exists to **enable delivery, learning, and transparency**—not to control people.

Govern the system. Trust the team.
