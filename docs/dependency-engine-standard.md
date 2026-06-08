# Verilogix Dependency Engine Standard

**Version:** 1.0
**Status:** Foundational

---

# Purpose

The Dependency Engine defines how prerequisites, requirements, constraints, and conditions are managed within Verilogix.

The Dependency Engine determines readiness.

The Dependency Engine determines eligibility.

The Dependency Engine determines whether progression may occur.

No project, stage, activity, validation, approval, or progression may bypass dependency evaluation.

---

# Constitutional Principle

Progression shall not occur unless required dependencies have been satisfied.

Unsatisfied dependencies shall prevent progression.

Dependencies take precedence over execution.

---

# Definition

A dependency is any requirement that must be satisfied before a governed object may proceed.

Dependencies may apply to:

* Projects
* Stages
* Activities
* Validations
* Approvals
* Deliverables
* Framework Rules

Dependencies represent prerequisites.

Dependencies are not optional.

---

# Dependency Object

Every dependency shall contain:

* Dependency ID
* Dependency Name
* Dependency Type
* Dependency Scope
* Dependency Status
* Dependency Owner
* Dependency Evidence
* Dependency Validation
* Dependency Outcome

No dependency may exist without traceability.

---

# Dependency ID

Every dependency shall possess a unique identifier.

Format:

```text
DEP-YYYY-NNNNN
```

Examples:

```text
DEP-2026-00001
DEP-2026-00002
DEP-2026-00003
```

Requirements:

* Unique
* Immutable
* Auditable

---

# Dependency Scope

Dependencies may apply to:

```text
Project
Stage
Validation
Approval
Risk
Activity
Deliverable
```

Scope must be declared.

---

# Dependency Types

---

## Document Dependency

Requires documentation to exist.

Examples:

* Signed Contract
* Passport Copy
* Permit
* Technical Drawing
* Risk Assessment

---

## Evidence Dependency

Requires evidence to exist.

Examples:

* Site Images
* Assessment Results
* Inspection Reports
* Completion Records

---

## Validation Dependency

Requires validation to be completed.

Examples:

* Technical Validation
* Operational Validation
* Risk Validation

---

## Approval Dependency

Requires formal approval.

Examples:

* Commercial Approval
* Technical Approval
* Risk Acceptance

---

## Resource Dependency

Requires resources to exist.

Examples:

* Staff
* Equipment
* Vehicles
* Accommodation
* Manufacturing Capacity

---

## Qualification Dependency

Requires competence or qualification.

Examples:

* Training Completion
* Certification
* Experience Requirement
* Licence Verification

---

## Financial Dependency

Requires commercial readiness.

Examples:

* Deposit Received
* Invoice Paid
* Budget Approved
* Purchase Order Issued

---

## Risk Dependency

Requires acceptable risk status.

Examples:

* Risk Assessment Completed
* Residual Risk Accepted
* Safety Controls Implemented

---

# Dependency Status

Valid statuses include:

```text
Pending
Submitted
Under Review
Satisfied
Unsatisfied
Expired
Waived
```

Only satisfied dependencies support progression.

---

# Dependency Relationships

Dependencies may depend on other dependencies.

Example:

```text
Permit Approved
      ↓
Insurance Confirmed
      ↓
Expedition Authorised
```

Dependency chains shall be supported.

Circular dependencies are prohibited.

---

# Dependency Evaluation

Every dependency shall be evaluated.

Evaluation criteria may include:

* Presence
* Completeness
* Accuracy
* Validity
* Currency

Dependencies that fail evaluation remain unsatisfied.

---

# Dependency Satisfaction

A dependency becomes satisfied when:

* Required object exists
* Required evidence exists
* Validation completed
* Governance requirements met

All conditions must be met.

---

# Dependency Expiry

Dependencies may expire.

Examples:

```text
Insurance Policy
Medical Certificate
Permit
Training Certification
```

Expired dependencies automatically become unsatisfied.

Progression may be blocked.

---

# Dependency Waivers

Certain dependencies may be waived.

Waivers require:

* Justification
* Approval
* Audit Record

Waivers shall be exceptional.

Waivers shall not bypass constitutional principles.

---

# Dependency Blocking

Unsatisfied dependencies shall create governance blocks.

Examples:

```text
Missing Permit
Missing Contract
Missing Validation
Missing Payment
```

Blocked objects may not progress.

---

# Dependency Severity

Dependencies may be classified.

Levels:

```text
Critical
Major
Minor
Informational
```

Critical dependencies automatically block progression.

---

# Dependency Lifecycle

Every dependency follows the same lifecycle.

```text
Created
    ↓
Assigned
    ↓
Submitted
    ↓
Evaluated
    ↓
Satisfied
```

Alternative paths:

```text
Unsatisfied
Expired
Waived
Cancelled
```

---

# Dependency Audit Requirements

Every dependency shall record:

* Dependency ID
* Owner
* Status History
* Evidence References
* Validation References
* Approval References
* Waivers
* Expiry Dates

Dependency activity must be auditable.

---

# Dependency Engine Decision

The Dependency Engine shall determine one of the following outcomes:

```text
Ready
Not Ready
Blocked
Escalate
```

These outcomes shall be visible to governance authorities.

---

# Governance Effect

The Dependency Engine determines readiness.

The Validation Engine determines compliance.

The Approval Engine determines authority.

Together they determine progression.

---

# Foundational Principle

Work does not progress because someone wants it to.

Work progresses because every required dependency has been satisfied, validated, approved, and governed.
