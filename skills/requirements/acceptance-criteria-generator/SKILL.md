---
name: acceptance-criteria-generator
display_name: "Acceptance Criteria Generator"
description: "Acceptance Criteria Generator. Produce observable, testable acceptance criteria from requirements and approved decisions."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "acceptance", "criteria", "generator"]
---
# Acceptance Criteria Generator

## Purpose
Produce observable, testable acceptance criteria from requirements and approved decisions.


## When to use
Use this Skill when you need to produce observable, testable acceptance criteria from requirements and approved decisions. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Read source requirements, stories, rules, and approved decisions.
2. Identify stated preconditions and states; otherwise ask questions.
3. Write criteria around observable outcomes.
4. Cover defined success, alternatives, validation, permissions, state changes, and specified failures.
5. Attach source IDs and mark unresolved behavior.

## Expected outputs
- Criteria with IDs
- Source mapping
- Assumptions and unknowns
- Coverage notes
- Review checklist

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Never invent thresholds, permissions, defaults, calculations, retries, error copy, or timing guarantees.
- Unknown behavior is a question, not an expectation.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
