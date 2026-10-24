---
name: requirement-decomposer
display_name: "Requirement Decomposer"
description: "Requirement Decomposer. Split broad requirements into atomic, independently reviewable units while preserving traceability."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "requirement", "decomposer"]
---
# Requirement Decomposer

## Purpose
Split broad requirements into atomic, independently reviewable units while preserving traceability.


## When to use
Use this Skill when you need to split broad requirements into atomic, independently reviewable units while preserving traceability. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Identify parent requirement and outcome.
2. Split compound statements by actor, action, condition, state, rule, or outcome where independently verifiable.
3. Preserve dependencies and ordering.
4. Flag statements requiring a product decision.
5. Assign child IDs and parent links.

## Expected outputs
- Decomposed requirements
- Parent-child map
- Dependencies
- Clarification log

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not alter intent or add unstated behavior.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
