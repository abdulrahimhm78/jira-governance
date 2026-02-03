# Jira Workflow – Validator Rules (Enterprise Standard)

This document defines mandatory Jira workflow validator rules to enforce discipline, quality, and predictability across enterprise Scrum teams. Validators prevent work items from progressing unless minimum standards are met.

---

## Purpose

To ensure:
- High-quality backlog items
- Predictable delivery
- Reduced rework
- Clear accountability
- Consistent governance across teams

Validators act as **quality gates**, not administrative friction.

---

## Guiding Principles

- Enforce **Definition of Ready (DoR)** before work starts
- Enforce **Definition of Done (DoD)** before work completes
- Fail fast on incomplete or unclear work
- Prefer objective, automatable checks
- Avoid subjective or manual policing

---

## Status-Level Validator Rules

### Backlog → Ready

**Validators**
- Summary is not empty
- Description is not empty
- Acceptance Criteria field is populated
- Business Value / Outcome field is populated
- Priority is set
- Story Points or Size is assigned
- Dependencies field reviewed (can be empty but must be acknowledged)

**Rationale**
Prevents poorly formed work from entering sprint planning.

---

### Ready → In Progress

**Validators**
- Definition of Ready checkbox = true
- Acceptance Criteria approved by Product Owner
- Story Points present
- No unresolved blocking dependencies
- Sprint is assigned

**Rationale**
Ensures the team only pulls fully ready work.

---

### In Progress → Code Review / Testing (if applicable)

**Validators**
- Assignee is set
- Work Log has entries
- Code branch or PR link field is populated (for development work)

**Rationale**
Ensures traceability and accountability.

---

### Testing → Ready for Review

**Validators**
- Test Cases field populated
- All linked defects resolved or explicitly deferred
- QA sign-off checkbox = true

**Rationale**
Prevents unfinished or unstable work from reaching review.

---

### Ready for Review → Done

**Validators**
- All Acceptance Criteria marked as met
- Definition of Done checkbox = true
- Code merged to main branch (if applicable)
- Documentation updated (link required if applicable)
- No open blocking defects
- Product Owner approval checkbox = true

**Rationale**
Protects production quality and prevents false “Done” states.

---

## Defect-Specific Validators

### Open → In Progress
- Root Cause field populated
- Severity set
- Linked to a Story or Incident

### In Progress → Done
- Fix version set
- Test evidence attached
- Regression impact assessed

---

## Epic-Level Validators

### Draft → Active
- Epic Owner assigned
- Business Objective defined
- Success Metrics populated
- Target PI or Quarter assigned

### Active → Done
- All child issues closed or explicitly descoped
- Outcome review completed

---

## Anti-Patterns to Avoid

- Validators that rely on free-text judgment
- Excessive mandatory fields unrelated to delivery
- Bypassing validators via admin overrides
- Using validators as performance controls

---

## Governance and Exceptions

- Validators may only be changed by Agile CoE or Platform Governance
- Emergency bypass requires documented approval
- Validator effectiveness reviewed quarterly

---

## Expected Outcomes

- Cleaner backlogs
- Fewer mid-sprint surprises
- Higher sprint predictability
- Reduced carryover
- Improved stakeholder trust

---

## Final Note

Validators are not bureaucracy.  
They are **guardrails for excellence**.

Enforce rigor early to enable speed later.
