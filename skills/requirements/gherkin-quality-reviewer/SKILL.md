---
name: gherkin-quality-reviewer
display_name: "Gherkin Quality Reviewer"
description: "Gherkin Quality Reviewer. Review Gherkin for structure, clarity, traceability, testability, independence, duplication, and unsupported behavior."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "gherkin", "quality", "reviewer"]
---
# Gherkin Quality Reviewer

## Purpose
Review Gherkin for structure, clarity, traceability, testability, independence, duplication, and unsupported behavior.


## When to use
Use this Skill when you need to review Gherkin for structure, clarity, traceability, testability, independence, duplication, and unsupported behavior. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Check Feature, Rule, Scenario, and Given/When/Then usage.
2. Find ambiguous/compound steps, unobservable outcomes, hidden setup, and implementation coupling.
3. Verify source links and expected results.
4. Check duplicates, examples, Background, and Scenario Outline usage.
5. Separate syntax issues from semantic questions.

## Expected outputs
- Ranked findings
- Locations
- Traceability gaps
- Duplicate notes
- Suggested revisions

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not claim linting or execution unless performed.
- Do not assert unknown behavior.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
