---
name: prd-to-gherkin
display_name: "PRD-to-Gherkin Converter"
description: "PRD-to-Gherkin Converter. Convert source-backed requirements into readable, testable Gherkin while preserving traceability and surfacing unknowns."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "prd", "gherkin"]
---
# PRD-to-Gherkin Converter

## Purpose
Convert source-backed requirements into readable, testable Gherkin while preserving traceability and surfacing unknowns.


## When to use
Use this Skill when you need to convert source-backed requirements into readable, testable Gherkin while preserving traceability and surfacing unknowns. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Parse requirements, rules, actors, states, constraints, and approved decisions.
2. Preserve IDs and create source mapping before drafting.
3. Identify relevant success, alternative, validation, permission, transition, failure, recovery, boundary, and specified NFR scenarios.
4. Write Given/When/Then around preconditions, events, and observable outcomes.
5. Use Background and Scenario Outline/Examples only when meaningful.
6. Tag source IDs and flag unknown behavior as questions.
7. Review structure, ambiguity, duplicates, assumptions, and coverage.

## Expected outputs
- Feature files
- Scenario IDs
- Traceability matrix
- Open decisions
- Review checklist

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not invent policies, errors, retries, timeouts, permissions, thresholds, defaults, or expected outcomes.
- Do not claim linting or execution unless performed.
- Prefer domain language and observable outcomes.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
