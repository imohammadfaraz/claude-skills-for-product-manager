---
name: prd-analyzer
display_name: "PRD Analyzer"
description: "PRD Analyzer. Assess PRDs for clarity, completeness, consistency, testability, dependencies, and unresolved decisions."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "prd", "analyzer"]
---
# PRD Analyzer

## Purpose
Assess PRDs for clarity, completeness, consistency, testability, dependencies, and unresolved decisions.


## When to use
Use this Skill when you need to assess PRDs for clarity, completeness, consistency, testability, dependencies, and unresolved decisions. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Inventory atomic requirements and source references.
2. Find ambiguity, omissions, conflicts, duplicates, vague terms, testability issues, and scope gaps.
3. Review relevant user journeys, data, analytics, privacy, security, rollout, and operations.
4. Prioritize findings and write precise questions.

## Expected outputs
- Readiness assessment
- Findings by requirement
- Prioritized issues
- Clarification questions
- Blockers

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Absence does not mean out of scope.
- Do not invent targets or policies.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
