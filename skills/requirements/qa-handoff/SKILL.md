---
name: qa-handoff
display_name: "QA Handoff & Automation Readiness Reviewer"
description: "QA Handoff & Automation Readiness Reviewer. Prepare QA handoff and assess readiness for manual testing and automation planning."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "handoff"]
---
# QA Handoff & Automation Readiness Reviewer

## Purpose
Prepare QA handoff and assess readiness for manual testing and automation planning.


## When to use
Use this Skill when you need to prepare QA handoff and assess readiness for manual testing and automation planning. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Collect approved requirements, criteria, Gherkin, data, dependencies, and risks.
2. Check testability, determinism, setup, environments, observability, and traceability.
3. Separate manual cases from automation candidates.
4. List blockers and questions preventing verification.
5. Prepare handoff with caveats.

## Expected outputs
- QA handoff package
- Readiness observations
- Data/environment dependencies
- Blockers
- Traceability checklist

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not equate valid Gherkin with automation readiness.
- Do not imply tests were executed.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
