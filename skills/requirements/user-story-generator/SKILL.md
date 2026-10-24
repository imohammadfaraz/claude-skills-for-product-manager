---
name: user-story-generator
display_name: "User Story Generator"
description: "User Story Generator. Create outcome-oriented user stories from traceable requirements and user needs."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "user", "story", "generator"]
---
# User Story Generator

## Purpose
Create outcome-oriented user stories from traceable requirements and user needs.


## When to use
Use this Skill when you need to create outcome-oriented user stories from traceable requirements and user needs. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Identify actor and need from source evidence.
2. Write concise stories in a consistent format.
3. Link each story to source IDs.
4. Include context and dependencies only when grounded.
5. Flag missing value hypotheses and decisions.

## Expected outputs
- Stories with IDs
- Traceability
- Context/dependencies
- Open questions
- Quality checklist

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not fabricate personas or unsupported value claims.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
