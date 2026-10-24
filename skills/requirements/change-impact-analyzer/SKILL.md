---
name: change-impact-analyzer
display_name: "Requirements Change Impact Analyzer"
description: "Requirements Change Impact Analyzer. Assess downstream effects of changed requirements across connected artifacts."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "change", "impact", "analyzer"]
---
# Requirements Change Impact Analyzer

## Purpose
Assess downstream effects of changed requirements across connected artifacts.


## When to use
Use this Skill when you need to assess downstream effects of changed requirements across connected artifacts. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Compare old/new sources or supplied change description.
2. Identify changed, added, removed, and reworded statements.
3. Trace impacted artifacts where mappings exist.
4. Classify impacts confirmed/likely/possible/unknown.
5. Create a prioritized review and regression checklist.

## Expected outputs
- Change summary
- Impact matrix
- Affected artifacts
- Dependency/risk notes
- Regression checklist

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not assert impacts without evidence.
- Do not assume old behavior persists.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
