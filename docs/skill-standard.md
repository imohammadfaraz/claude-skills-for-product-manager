# Skill Authoring Standard

This document defines the canonical structure and quality bar for every Skill in Product Manager Toolkit.

## 1. One Skill, one job

A Skill should represent a distinct task, decision, review, or deliverable. Its description must make the job recognizable and distinguish it from adjacent Skills. If two Skills produce substantially the same output from the same inputs, consolidate them or document a precise boundary.

## 2. Required metadata

All Skills use the same frontmatter keys:

| Field | Requirement |
|---|---|
| `name` | Stable kebab-case ID, unique and matching the folder name |
| `display_name` | Human-readable title |
| `description` | Concise task and outcome statement |
| `category` | Top-level folder category |
| `asset_type` | Always `skill` |
| `version` | Semantic version |
| `status` | `active`, `draft`, or `deprecated` |
| `portability` | `portable` or `migrated-source-preserved` |
| `review_status` | Honest editorial/portability state |
| `tags` | Short discoverability terms |
| `source` | Required when migrated from another repository |

Use `schemas/skill.schema.json` as the machine-readable field contract. The validator enforces required keys, valid values, uniqueness, catalog consistency, and required sections.

## 3. Required body structure

Portable Skills use these sections in order:

1. Purpose
2. When to use
3. Inputs
4. Process
5. Expected outputs
6. Quality checklist
7. Guardrails
8. Definition of done

Keep each section specific to the Skill. Do not use generic placeholder inputs or outputs when a task-specific list is possible.

## 4. Behavioral contract

Skills should:

- Ask clarifying questions only when missing information materially changes the result; otherwise proceed with labeled assumptions.
- Work across model providers and interfaces unless a platform integration is essential to the task.
- Preserve source wording, identifiers, and provenance where relevant.
- Separate evidence, interpretation, assumptions, unknowns, conflicts, and recommendations.
- Avoid inventing thresholds, policies, permissions, defaults, calculations, error handling, customer evidence, or approvals.
- Explain material trade-offs and state uncertainty.
- Produce outputs that are actionable and appropriate for the requested audience.
- Respect privacy, security, and licensing.
- Never claim external tool access, execution, tests, validation, or approval unless actually performed.

## 5. Duplication review

Before creating a Skill, compare its purpose, inputs, process, and outputs with existing Skills. Similar subject matter is not enough to justify merging or splitting. Use distinct job boundaries and handoffs, for example:

- PRD Intake normalizes supplied material; PRD Generator authors a PRD; PRD Analyzer evaluates a PRD.
- Risk & Edge Case Analyzer surveys broader product and launch risks; Edge Case Generator creates requirement-linked scenario candidates.
- Acceptance Criteria Generator defines observable acceptance conditions; PRD-to-Gherkin turns source-backed requirements into Given/When/Then scenarios.
- Scenario Coverage Planner proposes a coverage approach; Coverage Gap Analyzer identifies omissions in existing coverage; Traceability Matrix maps artifacts and their relationships.
- Competitive Analysis Expert gathers and interprets competitive evidence; Product Strategy Builder makes product choices using that and other inputs.

## 6. Evaluation contract

Each content-reviewed Skill should have at least two realistic evaluation fixtures covering a normal task and a material ambiguity, missing input, or failure mode. Fixtures define expected behaviors and behaviors to avoid. Run them against the intended model/runtime and review outputs before relying on a Skill in production.

Automated fixture validation checks that cases are present and well-formed. It does not execute a model, judge response quality, or prove correctness. Record actual evaluation results separately.

## 7. Review status

- `standardized`: toolkit-authored content has the required structure.
- `standardized-wrapper-content-review-needed`: migrated instructions have standardized metadata and wrapper, but detailed source instructions still need portability and conflict review.
- `content-reviewed`: editorial review has assessed task behavior, platform-specific wording, conflicts, output quality, and guardrails. Evaluation fixtures exist, but this label alone does not mean every model/runtime has passed them.
- `deprecated`: retained for history but no longer recommended.

A passing automated validator checks structure, not product judgment or factual accuracy. Review status must reflect what has actually been checked.
