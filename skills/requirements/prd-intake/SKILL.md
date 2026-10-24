---
name: prd-intake
display_name: "PRD Intake & Normalizer"
description: "PRD Intake & Normalizer. Normalize PRDs, feature briefs, notes, and references without changing meaning."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "prd", "intake"]
---
# PRD Intake & Normalizer

## Purpose
Normalize PRDs, feature briefs, notes, and references without changing meaning.


## When to use
Use this Skill when you need to normalize PRDs, feature briefs, notes, and references without changing meaning. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Inventory source artifacts and provenance.
2. Extract goals, scope, journeys, constraints, dependencies, rules, requirements, metrics, decisions, and gaps.
3. Preserve source wording and IDs where available; label generated IDs.
4. Separate facts, interpretations, assumptions, conflicts, unknowns, and proposals.
5. Return normalized intake and source gaps.

## Expected outputs
- Source inventory
- Normalized requirement register
- Uncertainty log
- Open questions
- Intake checklist

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not infer approval.
- Do not invent policies or expected behavior.
- Keep provenance attached.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
