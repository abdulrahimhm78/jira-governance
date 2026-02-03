# SAFe-Aligned Board Template (Enterprise Execution)

A standardized Agile board structure aligned with SAFe to support predictable delivery, transparency, and cross-team coordination at scale.

---

## Purpose

This board enables teams and programs to:
- Visualize flow from intake to release
- Enforce Definition of Ready (DoR) and Definition of Done (DoD)
- Manage dependencies, risks, and capacity
- Provide execution-level and program-level visibility

---

## Board Structure (Columns)

### 1. Funnel / Intake
**Usage**
- New ideas, features, enablers, defects
- Not yet analyzed or prioritized

**Entry Criteria**
- High-level description
- Business owner identified

---

### 2. Backlog (Refined & Prioritized)
**Usage**
- Items approved for refinement
- Ordered by Product Owner / Product Management

**Exit Criteria (DoR)**
- Clear business value
- Acceptance criteria defined
- Dependencies identified
- Estimated / sized
- Ready for sprint or iteration

---

### 3. Ready for Sprint / Iteration
**Usage**
- Items meeting Definition of Ready
- Candidates for Sprint Planning or Iteration Planning

**Rules**
- No work pulled without meeting DoR
- Capacity validated before pull

---

### 4. In Progress
**Usage**
- Actively worked items

**WIP Rules**
- Enforce strict WIP limits
- One primary owner per item

**Signals**
- Aging indicators enabled
- Blockers visible within 24 hours

---

### 5. Blocked
**Usage**
- Work stopped due to impediments

**Required Fields**
- Blocker reason
- Owner
- Escalation path
- Date blocked

**SAFe Alignment**
- Feeds program-level risk and dependency tracking

---

### 6. Code Review / Validation
**Usage**
- Peer review, testing, security, compliance

**Exit Criteria**
- Code reviewed and approved
- Tests passing
- Non-functional requirements validated

---

### 7. Ready for Release
**Usage**
- Meets Definition of Done
- Awaiting release window or deployment approval

**Checks**
- Release notes prepared
- Dependencies resolved
- Deployment plan confirmed

---

### 8. Done
**Usage**
- Released or production-ready increment

**Rules**
- Only items meeting full DoD allowed
- No partial completion

---

## Swimlanes (Optional but Recommended)

- **Features**
- **Enablers**
- **Defects**
- **Tech Debt**
- **Expedite (Exception-only)**

---

## Required Fields (Enterprise Standard)

- Business Owner
- Sprint / Iteration
- Feature / Epic link
- Dependency flag
- Risk level (Low / Medium / High)
- Acceptance Criteria
- DoR checklist
- DoD checklist

---

## Metrics Enabled by This Board

- Flow Distribution
- Cycle Time
- Throughput
- WIP Aging
- Blocker Frequency
- Predictability (Planned vs Done)
- Dependency Impact

---

## Governance Rules

- No bypassing DoR or DoD
- Blocked items escalated within 24 hours
- WIP limits reviewed every retrospective
- Board reviewed daily during Daily Scrum
- Metrics reviewed in Sprint Review and PI Syncs

---

## Guiding Principle

> If work is not visible on the board, it does not exist.

This board is a **system of execution**, not a reporting artifact.
