---
name: test-data-builder
display_name: "Test Data & Boundary Value Builder"
description: "Test Data & Boundary Value Builder. Build test-data matrices and boundary-value candidates from defined validation rules."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "test", "data", "builder"]
---
# Test Data & Boundary Value Builder

## Purpose
Build test-data matrices and boundary-value candidates from defined validation rules.


## When to use
Use this Skill when you need to build test-data matrices and boundary-value candidates from defined validation rules. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Extract types, allowed values, ranges, formats, uniqueness, relationships, and defaults.
2. Propose values around defined boundaries.
3. Include valid/invalid/missing/malformed/duplicate cases when grounded in rules.
4. Track setup, privacy, and expected outcomes when defined.
5. Flag unknown constraints.

## Expected outputs
- Test-data matrix
- Boundary values
- Equivalence partitions
- Setup notes
- Expected-outcome gaps

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not invent ranges or formats.
- Use synthetic data.
- Mark undefined outcomes TBD.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
