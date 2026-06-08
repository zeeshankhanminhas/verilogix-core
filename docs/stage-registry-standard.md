# Verilogix Stage Registry Standard

**Version:** 1.0
**Status:** Foundational

---

# Purpose

The Stage Registry Standard defines the minimum requirements for any stage operating within Verilogix.

A stage represents a controlled progression point within a governed process.

No stage may exist outside this standard.

---

# Definition

A stage is a governed state within a process that contains:

* Purpose
* Entry Criteria
* Exit Criteria
* Dependencies
* Validation Requirements
* Evidence Requirements
* Approval Requirements

A stage exists to determine whether progression is permitted.

---

# Mandatory Stage Components

Every stage must contain the following fields.

---

## Stage ID

Unique identifier.

Format:

```text
FRAMEWORK-STAGE-NUMBER
```

Examples:

```text
RF-001
RF-002
MIDTS-003
BOXIT-004
```

Requirements:

* Unique
* Immutable
* Traceable

---

## Stage Name

Human-readable name.

Examples:

```text
Lead Qualification
Commercial Review
Technical Approval
Expedition Planning
Production Release
```

Requirements:

* Clear
* Concise
* Unambiguous

---

## Purpose

Defines why the stage exists.

Requirements:

* Single objective
* Outcome-focused
* Measurable

Example:

```text
Determine whether a traveller is suitable
for the proposed expedition.
```

---

## Owner

Defines responsibility.

Examples:

```text
Sales Manager
Operations Manager
Guide Coordinator
Technical Reviewer
Project Manager
```

Requirements:

* Mandatory
* Named role
* Accountable for progression

Unowned stages are invalid.

---

## Entry Criteria

Defines what must be true before a stage may begin.

Examples:

```text
Lead submitted
Assessment completed
Contract signed
Deposit received
```

Requirements:

* Objective
* Verifiable
* Measurable

---

## Dependencies

Defines prerequisites required by the stage.

Dependencies may include:

* Documents
* Contracts
* Approvals
* Qualifications
* Risk Assessments
* Resources
* External Inputs

Unsatisfied dependencies shall block execution.

---

## Activities

Defines work performed within the stage.

Examples:

```text
Review application
Conduct interview
Prepare itinerary
Generate proposal
Perform audit
```

Activities produce evidence.

Activities do not determine progression.

---

## Required Evidence

Defines proof required by the stage.

Examples:

```text
Assessment Form
Risk Assessment
Proposal Document
Customer Approval
Technical Drawing
Photographic Evidence
```

Requirements:

* Auditable
* Traceable
* Retained

Evidence is mandatory.

---

## Validation Requirements

Defines how evidence is evaluated.

Validation methods may include:

* Human Review
* Technical Review
* Operational Review
* Automated Validation
* AI-Assisted Validation

Validation determines compliance.

---

## Approval Requirements

Defines who may authorise progression.

Examples:

```text
Operations Manager
Engineering Lead
Commercial Director
Project Sponsor
```

Approval may only occur after validation.

---

## Exit Criteria

Defines what must be true before progression.

Examples:

```text
Assessment Passed
Proposal Approved
Payment Received
Technical Review Complete
```

Requirements:

* Objective
* Verifiable
* Binary

A stage either satisfies exit criteria or it does not.

---

## Risks

Defines known risks associated with progression.

Examples:

```text
Weather Risk
Technical Risk
Commercial Risk
Resource Risk
Safety Risk
```

Risks must be documented.

Uncontrolled risks may block progression.

---

## Deviations

Defines exceptions occurring during execution.

Requirements:

* Recorded
* Classified
* Reviewed

Deviations become intelligence.

---

## Outputs

Defines deliverables produced by the stage.

Examples:

```text
Approved Proposal
Validated Assessment
Issued Drawing Pack
Confirmed Itinerary
```

Outputs become inputs for future stages.

---

# Stage Lifecycle

Every stage follows the same lifecycle.

```text
Not Started
      ↓
In Progress
      ↓
Evidence Submitted
      ↓
Validation
      ↓
Approval
      ↓
Completed
```

Alternative paths:

```text
Blocked
Rejected
Returned
Cancelled
```

---

# Progression Rule

A stage may only progress when:

* Entry Criteria satisfied
* Dependencies satisfied
* Evidence submitted
* Validation passed
* Approval granted
* Exit Criteria satisfied

Failure of any requirement shall prevent progression.

---

# Audit Requirements

Every stage shall record:

* Created Date
* Modified Date
* Owner
* Evidence
* Validation Results
* Approvals
* Status Changes
* Deviations

All stage activity must be auditable.

---

# Constitutional Compliance

Every stage operating within Verilogix shall comply with:

* Constitution
* Governance Model
* Framework Rules

No stage may override constitutional principles.

---

# Foundational Principle

A stage does not exist to perform work.

A stage exists to determine whether work has earned the right to progress.
