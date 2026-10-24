---
name: business-rule-builder
display_name: "Business Rules & Decision Table Builder"
description: "Business Rules & Decision Table Builder. Structure stated business rules into explicit rules and decision tables."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "business", "rule", "builder"]
---
# Business Rules & Decision Table Builder

## Purpose
Structure stated business rules into explicit rules and decision tables.


## When to use
Use this Skill when you need to structure stated business rules into explicit rules and decision tables. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Collect explicit rules and source refs.
2. Normalize conditions, actions, precedence, exceptions, and ownership where supplied.
3. Build decision tables for defined combinations.
4. Identify missing branches, conflicts, and unknown precedence.
5. Create questions for gaps.

## Expected outputs
- Business rule register
- Decision tables
- Source mapping
- Conflict log
- Missing-branch questions

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not create defaults merely to fill tables.
- Do not infer precedence without evidence.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
