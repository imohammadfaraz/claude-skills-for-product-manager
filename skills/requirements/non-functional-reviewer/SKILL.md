---
name: non-functional-reviewer
display_name: "Non-Functional Acceptance Criteria Reviewer"
description: "Non-Functional Acceptance Criteria Reviewer. Review non-functional expectations for relevance, measurability, and verifiability."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "non", "functional", "reviewer"]
---
# Non-Functional Acceptance Criteria Reviewer

## Purpose
Review non-functional expectations for relevance, measurability, and verifiability.


## When to use
Use this Skill when you need to review non-functional expectations for relevance, measurability, and verifiability. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Inspect relevant performance, availability, reliability, accessibility, compatibility, security, privacy, observability, localization, and operations.
2. Map expectations to source references and verification approaches.
3. Flag vague terms.
4. Ask for missing thresholds and context.
5. Draft criteria only from supplied or approved targets.

## Expected outputs
- NFR inventory
- Measurability findings
- Clarification questions
- Verification approach
- Readiness assessment

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Do not fabricate SLAs, guarantees, conformance, or compliance claims.
- Label target suggestions as proposals.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
