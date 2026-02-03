# Jira Status to Metric Mapping

This document defines a **standardized mapping between Jira workflow statuses and delivery metrics** to ensure consistent, accurate, and executive-ready reporting across teams, programs, and portfolios.

The goal is to eliminate metric ambiguity, prevent status misuse, and align Jira data with Agile delivery outcomes.

---

## Purpose

- Establish a **single source of truth** for how Jira statuses roll up into metrics
- Ensure **cycle time, throughput, WIP, and predictability** are measured consistently
- Enable **reliable team-level and executive-level reporting**
- Prevent metric distortion caused by inconsistent workflow usage

---

## Core Principle

> **Metrics are derived from workflow state transitions — not subjective interpretation.**

If a Jira status is ambiguous, metrics become unreliable.

---

## Standard Jira Status Categories

Jira workflows may vary by team, but **all statuses must map to one of the categories below**.

| Metric Category | Description |
|----------------|------------|
| Backlog | Not started, not committed |
| Ready | Approved and ready to start |
| In Progress | Actively being worked |
| In Review | Work completed, pending validation |
| Blocked | Work stopped due to impediment |
| Done | Completed and releasable |

---

## Jira Status to Metric Mapping

### 1. Backlog (Not Started)

| Jira Status | Metric Impact |
|------------|---------------|
| Backlog | Not counted in any flow metric |
| To Do | Not counted |
| Open | Not counted |

**Metrics Affected**
- Excluded from Cycle Time
- Excluded from WIP
- Excluded from Throughput

---

### 2. Ready (Sprint-Eligible)

| Jira Status | Metric Impact |
|------------|---------------|
| Ready | Entry point for commitment analysis |
| Refinement Complete | Eligible for Sprint Planning |

**Metrics Affected**
- Used for **Backlog Health**
- Used for **Sprint Readiness**
- Not counted in Cycle Time until work starts

---

### 3. In Progress (Active Work)

| Jira Status | Metric Impact |
|------------|---------------|
| In Progress | Cycle Time starts |
| Development | Counts toward WIP |
| In Analysis | Counts toward WIP |
| In Build | Counts toward WIP |

**Metrics Affected**
- Cycle Time (Start)
- Work In Progress (WIP)
- Flow Efficiency
- Throughput (pending completion)

---

### 4. In Review / Validation

| Jira Status | Metric Impact |
|------------|---------------|
| Code Review | Still counts as In Progress |
| QA | Still counts as In Progress |
| UAT | Still counts as In Progress |
| Validation | Still counts as In Progress |

**Metrics Affected**
- Cycle Time continues
- WIP continues
- Highlights bottlenecks when dwell time is high

---

### 5. Blocked

| Jira Status | Metric Impact |
|------------|---------------|
| Blocked | Flags flow interruption |
| Waiting | Counts as blocked time |
| External Dependency | Counts as blocked time |

**Metrics Affected**
- Blocked Time
- Flow Efficiency degradation
- Dependency Risk Indicators

> Blocked work **still counts as WIP** but should be measured separately.

---

### 6. Done (Completed Work)

| Jira Status | Metric Impact |
|------------|---------------|
| Done | Cycle Time ends |
| Closed | Throughput incremented |
| Released | Confirms value realization |

**Metrics Affected**
- Cycle Time (End)
- Throughput
- Sprint Completion Rate
- Predictability Metrics

---

## Metric Definitions (Aligned to Status Mapping)

### Cycle Time
- **Start:** First transition into any *In Progress* status  
- **End:** Transition into *Done*

### Throughput
- Count of issues transitioned to *Done* per sprint or time period

### Work In Progress (WIP)
- Count of issues in:
  - In Progress
  - In Review
  - Blocked

### Flow Efficiency
- Active work time ÷ Total Cycle Time

### Predictability
- Planned vs Completed work transitioned to *Done* within sprint

---

## Reporting Guardrails

### Required Rules
- Status changes must reflect **actual work state**
- Work may not move directly from *To Do → Done*
- Blocked status must be used when work cannot proceed
- Done means **Done per Definition of Done**

### Anti-Patterns to Avoid
- Using “In Progress” as a catch-all
- Leaving completed work in QA or Review indefinitely
- Closing work without meeting DoD
- Creating custom statuses without metric mapping

---

## Executive Reporting Alignment

| Executive Question | Metric Source |
|-------------------|--------------|
| Are teams delivering predictably? | Throughput, Predictability |
| Where is work getting stuck? | Blocked Time, WIP Aging |
| How fast is work flowing? | Cycle Time |
| Are we overloading teams? | WIP |
| Is improvement happening? | Trend analysis across sprints |

---

## Ownership

- **Scrum Master:** Enforces workflow discipline and metric integrity
- **Product Owner:** Ensures readiness before commitment
- **Team:** Updates Jira honestly and consistently
- **Leadership:** Uses metrics for insight, not punishment

---

## Guiding Principle

> **If Jira data is clean, metrics are trustworthy.  
If metrics are trustworthy, decisions improve.**

This mapping is mandatory for all teams using Jira-based delivery metrics.
