---
name: workflow-orchestrator
display_name: "Acceptance Criteria Workflow Orchestrator"
description: "Acceptance Criteria Workflow Orchestrator. Select and coordinate a suitable sequence of requirements and acceptance-criteria capabilities."
category: requirements
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["requirements", "workflow", "orchestrator"]
---
# Acceptance Criteria Workflow Orchestrator

## Purpose
Select and coordinate a suitable sequence of requirements and acceptance-criteria capabilities.


## When to use
Use this Skill when you need to select and coordinate a suitable sequence of requirements and acceptance-criteria capabilities. If required source information is missing, ask focused questions or mark the gap explicitly rather than inventing product behavior.

## Inputs
- Relevant PRD, feature brief, requirement register, story, business rules, test artifacts, or change record.
- Source IDs and version/date information where available.
- Desired deliverable and constraints.
- Approved decisions and related artifacts, if supplied.

## Process
1. Identify goal, input maturity, artifacts, and deliverable.
2. Select relevant Skills and identify required/optional steps.
3. Define inputs, outputs, handoffs, and traceability IDs.
4. Track steps as not started, completed, blocked, or skipped with evidence.
5. Consolidate decisions, gaps, readiness, and next actions.

## Expected outputs
- Workflow plan/status
- Handoff map
- Artifact inventory
- Blocking decisions/gaps
- Next-action checklist

## Quality checklist
- [ ] Material outputs have source references or clearly labeled generated IDs.
- [ ] Facts are distinguished from interpretations, assumptions, unknowns, conflicts, and proposals.
- [ ] Missing information has not been silently converted into product behavior.
- [ ] Recommendations include rationale and uncertainty where relevant.
- [ ] Output matches the requested format and supports the next reviewer.

## Guardrails
- Workflow documentation does not automatically execute Skills.
- Do not claim unrun steps.
- Mark unresolved decisions as blockers.
- Do not claim tool execution, automated checks, stakeholder approvals, or tests unless they occurred.

## Definition of done
The artifact is delivered with traceability, quality checks, and unresolved decisions clearly represented. Any blocker is explicit.
