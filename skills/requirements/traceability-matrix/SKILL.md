---
name: traceability-matrix
display_name: "Requirements Traceability Matrix Builder"
description: "Requirements Traceability Matrix Builder. Map requirements to stories, criteria, scenarios, tests, and releases where data exists."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "traceability", "matrix"]
---
# Requirements Traceability Matrix Builder

## Purpose
Map requirements to stories, criteria, scenarios, tests, and releases where data exists.


## When to use
Use this Skill when you need to map requirements to stories, criteria, scenarios, tests, and releases where data exists. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Collect artifacts and stable IDs.
2. Build forward and backward links.
3. Classify coverage with rationale.
4. Identify orphans and changed artifacts.
5. Return a maintainable table or machine-readable matrix.

## Expected outputs
- Traceability matrix
- Coverage statuses
- Orphan list
- Missing mappings
- Artifact inventory

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not invent links.
- Label generated IDs.
- Missing data is not proof of no dependency.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
