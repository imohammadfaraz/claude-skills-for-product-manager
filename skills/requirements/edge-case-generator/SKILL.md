---
name: edge-case-generator
display_name: "Edge Case & Negative Path Generator"
description: "Edge Case & Negative Path Generator. Identify meaningful boundary, negative, interruption, permission, and recovery scenarios."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "edge", "case", "generator"]
---
# Edge Case & Negative Path Generator

## Purpose
Identify meaningful boundary, negative, interruption, permission, and recovery scenarios.


## When to use
Use this Skill when you need to identify meaningful boundary, negative, interruption, permission, and recovery scenarios. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Extract defined constraints, states, actors, and failure modes.
2. Explore empty, missing, invalid, duplicate, stale, conflicting, concurrent, interrupted, and unauthorized cases where relevant.
3. Link candidates to source rules or label them as questions.
4. Explain likely impact.
5. Deduplicate and prioritize.

## Expected outputs
- Edge-case inventory
- Negative-path candidates
- Source links
- Risk rationale
- Questions

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not invent retries, rate limits, error copy, lockout, or recovery semantics.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
