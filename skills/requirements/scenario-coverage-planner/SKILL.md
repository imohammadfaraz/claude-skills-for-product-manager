---
name: scenario-coverage-planner
display_name: "Scenario Coverage Planner"
description: "Scenario Coverage Planner. Plan scenario coverage across requirements, actors, states, journeys, constraints, and risk dimensions."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "scenario", "coverage", "planner"]
---
# Scenario Coverage Planner

## Purpose
Plan scenario coverage across requirements, actors, states, journeys, constraints, and risk dimensions.


## When to use
Use this Skill when you need to plan scenario coverage across requirements, actors, states, journeys, constraints, and risk dimensions. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Inventory coverage dimensions supported by source.
2. Map requirements to existing and candidate scenarios.
3. Prioritize using available risk evidence and explain the basis.
4. Find untested combinations, duplicates, orphan scenarios, and blockers.
5. Propose a defensible coverage plan.

## Expected outputs
- Coverage plan
- Requirement-scenario matrix
- Priorities
- Gap/duplicate list
- Blocked/not-applicable rationale

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not equate scenario count with quality.
- Do not claim exhaustive coverage without analysis.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
