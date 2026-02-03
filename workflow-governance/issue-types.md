# Issue Types (Enterprise Agile Standard)

## Purpose
Issue Types provide a consistent classification model for work items across teams, enabling clear flow, reporting, prioritization, and governance in enterprise Agile environments.

Standardized issue types reduce ambiguity, improve metrics accuracy, and support predictable delivery.

---

## Standard Issue Types

### Epic
**Purpose:** Represents a large business objective or initiative that spans multiple sprints and may involve multiple teams.  
**Ownership:** Product Owner / Product Management  
**Characteristics:**
- High-level business outcome
- Broken down into Features or Stories
- Tracked across Program Increment(s)

---

### Feature
**Purpose:** Delivers a distinct, valuable capability aligned to an Epic.  
**Ownership:** Product Owner  
**Characteristics:**
- Measurable business value
- Decomposed into Stories
- Often planned at PI or roadmap level

---

### User Story
**Purpose:** Small, testable unit of customer or system value deliverable within a sprint.  
**Ownership:** Product Owner (definition), Team (execution)  
**Characteristics:**
- Meets Definition of Ready before sprint
- Meets Definition of Done before closure
- Independently testable and valuable

---

### Task
**Purpose:** Represents implementation or supporting work required to complete a Story.  
**Ownership:** Team  
**Characteristics:**
- Technical or execution-focused
- Does not deliver standalone user value
- Linked to a parent Story

---

### Bug / Defect
**Purpose:** Captures unintended behavior or failure against expected outcomes.  
**Ownership:** Team (triage with Product Owner)  
**Characteristics:**
- May originate from production, testing, or user feedback
- Prioritized based on severity and impact
- Can be planned or expedited

---

### Spike
**Purpose:** Time-boxed research or investigation to reduce uncertainty.  
**Ownership:** Team  
**Characteristics:**
- Has a clear question and expected learning outcome
- Time-bound (not scope-bound)
- Produces knowledge, not production code

---

### Enabler (Optional / Scaled Context)
**Purpose:** Supports architectural, infrastructure, or compliance needs that enable future value delivery.  
**Ownership:** Team / Architecture  
**Characteristics:**
- Technical or platform-focused
- Often required for long-term sustainability
- Planned deliberately to avoid hidden work

---

## Usage Guidelines

- Every work item must use an approved Issue Type
- Issue Type determines:
  - Required fields
  - Workflow
  - Metrics treatment
- Mixing purposes within a single issue type is not permitted

---

## Governance Principles

- Issue Types are standardized across the organization
- Teams do not create custom issue types without approval
- Reporting and metrics rely on correct issue classification

---

## Guiding Principle
Clarity in work classification drives transparency, flow efficiency, and trust in delivery metrics.
