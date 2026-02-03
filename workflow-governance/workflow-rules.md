# Workflow Rules (Enterprise Delivery Governance)

## Purpose
Workflow Rules define the mandatory, non-negotiable flow constraints that govern how work items move across states in an enterprise Agile delivery system.  
They ensure delivery discipline, transparency, predictability, and auditability across teams and programs.

These rules apply regardless of team maturity, tooling, or framework variant (Scrum, Kanban, Scrumban).

---

## Core Principles
- **Flow over activity** – Progress is measured by value moving to Done, not by effort spent.
- **Explicit policies** – Every state has clear entry and exit criteria.
- **Pull, not push** – Work is pulled only when capacity exists.
- **Stop starting, start finishing** – WIP limits are enforced.
- **Quality is built in** – No downstream handoffs of incomplete work.

---

## Standard Workflow States
The following workflow states are mandatory at the enterprise level.  
Teams may add sub-states, but may not remove or bypass these.

1. Backlog
2. Ready
3. In Progress
4. In Review / Validation
5. Done

---

## State Rules and Constraints

### 1. Backlog
**Definition**
- Items are candidates for future work but not ready for commitment.

**Rules**
- Items may exist in any level of refinement.
- No work may begin from this state.
- Items without a clear owner are invalid.

**Exit Criteria**
- Meets Definition of Ready (DoR)
- Dependencies identified
- Acceptance criteria defined

---

### 2. Ready
**Definition**
- Items are fully prepared and eligible to be pulled into a sprint or flow.

**Rules**
- Only items that meet DoR may enter this state.
- Items must be sized small enough to complete within a sprint.
- Ready is a **buffer**, not a parking lot.

**Exit Criteria**
- Team has available capacity
- Item is explicitly pulled during planning or flow replenishment

---

### 3. In Progress
**Definition**
- Work has started and is actively being developed.

**Rules**
- WIP limits are mandatory.
- Items may not be reassigned without team visibility.
- Partial work is not counted as progress.

**Constraints**
- If blocked for more than one business day, the item must be flagged.
- New work may not start while blockers remain unresolved unless explicitly agreed.

---

### 4. In Review / Validation
**Definition**
- Work is complete from a development perspective and is undergoing validation.

**Rules**
- Code review, testing, and validation are mandatory.
- No new scope may be added.
- Items failing validation return to In Progress.

**Exit Criteria**
- Acceptance criteria met
- Quality checks passed
- No critical defects open

---

### 5. Done
**Definition**
- Work is complete, usable, and releasable.

**Rules**
- Done is binary; there is no “almost done”.
- Items may not be reopened without explicit justification.
- Done items contribute to metrics and reporting.

**Constraints**
- Items not meeting Definition of Done (DoD) may not enter this state.

---

## Prohibited Practices
The following actions are explicitly disallowed:

- Skipping workflow states
- Moving items backward without explanation
- Inflating progress by splitting incomplete work
- Treating “In Review” as a waiting queue
- Closing items to meet dates without meeting DoD

---

## Flow Metrics Alignment
Workflow rules directly support enterprise metrics:

- Cycle Time
- Lead Time
- Throughput
- Work Item Age
- WIP Compliance

Metrics are invalid if workflow rules are violated.

---

## Governance and Enforcement
- Scrum Masters are accountable for enforcement.
- Product Owners may not override workflow rules.
- Exceptions require documented rationale and leadership visibility.
- Repeated violations trigger coaching and corrective action.

---

## Guiding Statement
> If work does not follow the workflow, it does not exist for reporting, forecasting, or decision-making.

Discipline in flow creates trust in outcomes.
