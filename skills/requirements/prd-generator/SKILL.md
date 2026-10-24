---
name: prd-generator
display_name: "PRD Generator"
description: "Create an actionable product requirements document from a validated problem, goals, and constraints."
category: requirements
asset_type: skill
version: "1.1.0"
status: active
portability: portable
review_status: content-reviewed
tags: ["prd", "requirements", "product-specification"]
source: https://github.com/imohammadfaraz/claude-skills-for-product-manager/blob/main/top-skills/prd-generator/prd-generator.md
---
# PRD Generator

## Purpose
Produce a clear, testable product requirements document that aligns stakeholders on the problem, outcomes, scope, behavior, constraints, and decisions needed.

## When to use
Use when the problem and intended outcome are sufficiently understood to specify a solution. If the input is only an idea or unvalidated request, first frame the problem with Problem Definition Expert or identify discovery gaps.

## Inputs
- Problem statement, target users, use cases, and evidence.
- Goals, success metrics, baseline data, and guardrails where known.
- Proposed solution, workflows, requirements, dependencies, and technical constraints.
- MVP scope, out-of-scope items, release context, stakeholders, and open decisions.
- Requested document depth or organizational template, if any.

## Process
1. **Check readiness.** Identify missing inputs that materially affect requirements. Ask concise questions when needed; otherwise draft with an explicit assumptions and open-questions section.
2. **Separate outcomes from solutions.** State the user problem, desired outcome, and rationale before describing features.
3. **Set scope.** Define goals, non-goals, users, use cases, MVP boundaries, and dependencies.
4. **Define requirements.** Describe functional behavior in observable, unambiguous language. Link requirements to user needs or business goals when possible.
5. **Specify experience and system considerations.** Include key flows, states, permissions, data handling, accessibility, performance/reliability, integrations, migration, and AI/ML behavior only where relevant.
6. **Cover failure and recovery.** Describe important validation errors, empty states, retries, partial failures, permissions, and recovery paths.
7. **Define success and measurement.** Specify metric definitions, guardrails, event requirements, and data-quality needs without inventing targets.
8. **Identify risks and decisions.** Capture dependencies, trade-offs, unresolved questions, and owners when known.
9. **Make it testable.** Ensure each important requirement can be verified. Use Acceptance Criteria Generator or Gherkin tools for detailed test artifacts rather than duplicating them by default.
10. **Review coherence.** Check that scope, requirements, metrics, and roadmap assumptions do not conflict.

## Expected outputs
Use a fit-for-purpose structure, typically:
1. Overview and context
2. Problem statement and evidence
3. Goals, non-goals, success metrics, and guardrails
4. Users and use cases
5. Solution overview and key flows
6. Functional requirements
7. UX, accessibility, and content considerations
8. Technical, data, security, and operational considerations
9. Edge cases and failure recovery
10. MVP scope, dependencies, rollout, and risks
11. Open questions and decisions needed

Include AI/ML-specific sections only when the feature uses AI/ML. Follow a user-provided PRD template when supplied.

## Quality checklist
- Problem, outcomes, and scope are distinct and consistent.
- Requirements are specific, observable, and testable.
- Metrics have definitions and no fabricated baselines or targets.
- Out-of-scope items, dependencies, failure paths, and open decisions are visible.
- Detail is appropriate to the product stage and audience.
- The document does not imply stakeholder approval that has not occurred.

## Guardrails
- Do not invent research, customer quotes, technical decisions, approvals, owners, dates, or business targets.
- Do not force a long template when a short PRD is more useful.
- Do not treat assumptions as requirements; label and validate them.
- Do not use vague requirement words such as "fast", "easy", or "intuitive" without an observable criterion or explicit follow-up.
- Do not duplicate detailed acceptance criteria or test cases unless requested.

## Definition of done
The PRD gives product, design, engineering, data, and QA a shared, testable understanding of the problem, intended outcome, scope, requirements, and unresolved decisions.
