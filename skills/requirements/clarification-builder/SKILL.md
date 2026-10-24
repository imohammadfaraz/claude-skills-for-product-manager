---
name: clarification-builder
display_name: "Clarification & Decision Builder"
description: "Clarification & Decision Builder. Turn requirement gaps and conflicts into actionable questions and decision records."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "clarification", "builder"]
---
# Clarification & Decision Builder

## Purpose
Turn requirement gaps and conflicts into actionable questions and decision records.


## When to use
Use this Skill when you need to turn requirement gaps and conflicts into actionable questions and decision records. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Cite source requirement.
2. Describe gap and consequence.
3. Ask one focused question per decision; offer options only when grounded.
4. Suggest owner roles without inventing real owners.
5. Record confirmed decisions and downstream impact only when supplied.

## Expected outputs
- Prioritized clarification backlog
- Grounded options
- Decision log
- Blocking classification
- Downstream impact notes

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not present invented options as policy.
- Do not assign real people without evidence.
- Keep unanswered decisions unresolved.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
