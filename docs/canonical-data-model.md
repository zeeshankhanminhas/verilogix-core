# Verilogix Canonical Data Model

## Purpose

The Canonical Data Model defines the core objects of Verilogix and the relationships between them.

It serves as the single source of truth for:

- Schemas
- APIs
- Databases
- Engines
- Frameworks
- Applications

All Verilogix implementations shall inherit from this model.

---

# Core Objects

Project
↓
Stage
↓
Dependency
↓
Evidence
↓
Validation
↓
Approval
↓
Intelligence

These objects form the constitutional execution chain.

---

# Project

Represents a governed unit of work.

A project contains:

- Stages
- Dependencies
- Evidence
- Validations
- Approvals
- Intelligence

Relationship:

Project
└── 1..N Stages

---

# Stage

Represents a controlled progression step.

A stage belongs to one Project.

A stage may contain:

- Dependencies
- Evidence
- Validations
- Approvals

---

# Dependency

Represents a prerequisite.

Dependencies determine readiness.

Relationship:

Stage
└── Dependency

Dependencies may require:

- Evidence
- Validation
- Approval

---

# Evidence

Represents proof.

Evidence supports validation.

Relationship:

Dependency
└── Evidence

---

# Validation

Represents evaluation.

Validation evaluates evidence against rules.

Relationship:

Evidence
└── Validation

Outputs:

- PASS
- FAIL
- CONDITIONAL PASS
- ESCALATE

---

# Approval

Represents authority.

Approval authorises progression.

Relationship:

Validation
└── Approval

---

# Intelligence

Represents organisational learning.

Relationship:

Project
└── Intelligence

Intelligence influences:

- Frameworks
- Rules
- Dependencies
- Validation Criteria
- Approvals

---

# Complete Lifecycle

Project
↓
Stage
↓
Dependency
↓
Evidence
↓
Validation
↓
Approval
↓
Progression
↓
Intelligence
↓
Framework Improvement

---

# Cardinality Model

Project
└── 1..N Stages

Stage
└── 0..N Dependencies

Dependency
└── 0..N Evidence

Evidence
└── 0..N Validations

Validation
└── 0..N Approvals

Project
└── 0..N Intelligence Records

---

# Foundational Principle

Projects govern work.

Stages govern progression.

Dependencies govern readiness.

Evidence governs proof.

Validation governs compliance.

Approval governs authority.

Intelligence governs improvement.

Together they form the Verilogix Operating Model.
