# Verilogix Project Registry Standard

**Version:** 1.0
**Status:** Foundational

---

# Purpose

The Project Registry Standard defines the minimum requirements for any project operating within Verilogix.

A project represents a governed unit of work that progresses through defined stages under constitutional governance.

All work within Verilogix shall exist within a project.

No governed activity may exist outside a project.

---

# Definition

A project is a governed container that:

* Has a defined objective
* Has a defined owner
* Contains one or more stages
* Produces evidence
* Generates intelligence
* Progresses through governance controls

A project is the primary operational object within Verilogix.

---

# Mandatory Project Components

Every project must contain the following fields.

---

## Project ID

Unique identifier.

Format:

```text
FRAMEWORK-YEAR-SEQUENCE
```

Examples:

```text
RF-2026-001
MIDTS-2026-014
BOXIT-2026-087
```

Requirements:

* Unique
* Immutable
* Traceable

---

## Project Name

Human-readable title.

Examples:

```text
Nanga Parbat Base Camp Expedition
Reverse Engineering Package
Custom Packaging Production Order
```

Requirements:

* Clear
* Unique
* Descriptive

---

## Framework

Defines which governance framework applies.

Examples:

```text
Rugged Frontiers
MIDTS
Boxit
```

A project may only operate under one primary framework.

---

## Project Type

Defines the classification of work.

Examples:

```text
Expedition
Assessment
Engineering Package
Production Order
Audit
Training Programme
```

Project type determines governance behaviour.

---

## Purpose

Defines the intended outcome.

Requirements:

* Outcome-focused
* Measurable
* Clear

Example:

```text
Deliver a guided expedition to Nanga Parbat Base Camp.
```

---

## Owner

Defines overall accountability.

Examples:

```text
Operations Manager
Project Manager
Technical Lead
Commercial Manager
```

Every project must have a single accountable owner.

---

## Stakeholders

Defines parties involved.

Examples:

```text
Customer
Supplier
Guide
Engineer
Client Representative
```

Stakeholders may participate but do not automatically hold authority.

---

## Status

Defines current project state.

Valid statuses:

```text
Draft
Active
On Hold
Blocked
Completed
Cancelled
Archived
```

Status changes must be auditable.

---

## Current Stage

Represents the project's active stage.

Examples:

```text
RF-003 Experience Matching
MIDTS-004 Technical Review
BOXIT-005 Artwork Approval
```

Only one active stage may exist at a time unless explicitly permitted by framework rules.

---

## Stage History

Records all completed stages.

Requirements:

* Timestamped
* Immutable
* Auditable

Stage history provides progression traceability.

---

## Dependencies

Defines project-level prerequisites.

Examples:

```text
Signed Agreement
Funding Approval
Resource Allocation
Supplier Confirmation
```

Unsatisfied dependencies may prevent project activation.

---

## Risks

Defines project-level risks.

Examples:

```text
Commercial Risk
Operational Risk
Safety Risk
Resource Risk
Technical Risk
```

Risks must be reviewed throughout the project lifecycle.

---

## Evidence Repository

Stores project evidence.

Examples:

```text
Documents
Images
Reports
Certificates
Forms
Approvals
```

Evidence must remain linked to the project.

---

## Approvals

Records governance approvals.

Examples:

```text
Commercial Approval
Technical Approval
Operational Approval
Final Approval
```

Approvals must be traceable to evidence.

---

## Deviations

Records departures from expected execution.

Examples:

```text
Schedule Change
Scope Change
Resource Shortage
Weather Delay
Technical Issue
```

All deviations must be retained.

---

## Outputs

Defines project deliverables.

Examples:

```text
Completed Expedition
Issued Engineering Package
Delivered Product Order
Assessment Report
```

Outputs represent project outcomes.

---

## Intelligence Capture

Defines lessons learned.

Examples:

```text
Customer Feedback
Operational Observations
Performance Metrics
Lessons Learned
```

Projects contribute intelligence to future governance.

---

# Project Lifecycle

Every project follows the same lifecycle.

```text
Created
    ↓
Activated
    ↓
In Progress
    ↓
Stage Progression
    ↓
Completed
    ↓
Intelligence Capture
    ↓
Archived
```

Alternative paths:

```text
Blocked
On Hold
Cancelled
```

---

# Progression Rule

A project may only progress when:

* Current stage completed
* Exit criteria satisfied
* Required evidence present
* Validation passed
* Required approvals granted

Projects do not progress through assumption.

Projects progress through governance.

---

# Audit Requirements

Every project shall record:

* Creation Date
* Owner
* Status History
* Stage History
* Evidence
* Approvals
* Deviations
* Intelligence Records

All project activity must be auditable.

---

# Constitutional Compliance

Every project shall comply with:

* Constitution
* Governance Model
* Framework Rules
* Stage Registry Standard

No project may bypass governance controls.

---

# Foundational Principle

A project is not a collection of tasks.

A project is a governed journey from initiation to outcome.

Its purpose is not merely execution.

Its purpose is controlled progression.
