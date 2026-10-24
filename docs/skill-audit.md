# Skill Coverage and Duplication Audit

**Scope:** 28 current Skills in `skills/**/SKILL.md` on the foundation-standardization branch. This is a structural and purpose-level review, not a claim that every source instruction has been fully rewritten or portability-tested.

## Summary

- 28 Skills reviewed for metadata and folder placement.
- 18 toolkit-authored requirements Skills use the standardized portable template.
- 10 Skills migrated from the earlier Claude-focused repository now use standardized metadata and a common operating wrapper. Their original detailed instructions are retained and are still flagged for content/portability review.
- No exact duplicate pair was identified from the current Skill names and stated jobs.
- Several adjacent Skills have overlapping vocabulary but different intended outputs. Their boundaries should be preserved and evaluated in future examples.

## Adjacent Skills and boundaries

| Skills | Overlap risk | Intended boundary |
|---|---|---|
| PRD Intake & Normalizer / PRD Generator / PRD Analyzer | High if treated as generic PRD assistants | Intake preserves and structures supplied information; Generator authors a PRD; Analyzer reviews an existing PRD for gaps and readiness. |
| Risk & Edge Case Analyzer / Edge Case & Negative Path Generator | Medium | Risk Analyzer covers broader product, operational, user, and launch risks; Edge Case Generator derives concrete, requirement-linked scenario candidates. |
| Acceptance Criteria Generator / PRD-to-Gherkin Converter | Medium | Criteria Generator writes observable acceptance conditions; Gherkin Converter represents source-backed behavior as Given/When/Then scenarios. |
| Scenario Coverage Planner / Coverage Gap Analyzer / Traceability Matrix Builder | High if outputs are not differentiated | Planner proposes coverage dimensions; Gap Analyzer audits existing coverage for omissions; Traceability Matrix maintains mappings between artifacts. |
| Competitive Analysis Expert / Product Strategy Builder | Medium | Competitive Analysis develops market and competitor evidence; Strategy Builder makes choices and trade-offs using broader product context. |
| UX Reviewer / Risk & Edge Case Analyzer | Medium | UX Reviewer evaluates experience quality and usability; Risk Analyzer evaluates failure modes and broader launch risk. |
| Workflow Orchestrator Skill / workflow guide files | Medium | The Skill selects and describes a workflow; workflow files document repeatable steps and handoffs. They do not imply automatic execution. |

## Gaps not solved by this standardization pass

- The 10 migrated Skills still need line-by-line review for runtime-specific wording, conflicting clarification rules, and consistency with the toolkit behavioral contract.
- Automated checks validate metadata, section presence, IDs, catalog paths, and local links. They do not establish that recommendations are correct or outputs are useful.
- The current collection is heavily weighted toward requirements and acceptance criteria. Discovery, roadmap/execution, analytics depth, AI product management, product building, leadership, and career development remain broader roadmap gaps.

## Recommended follow-up

1. Review the 10 migrated source instruction bodies and either rewrite them to the canonical structure or explicitly document any runtime-specific behavior.
2. Add one positive and one adversarial evaluation case to each flagship Skill.
3. Revisit the overlap table whenever a new Skill is proposed.
4. Keep the catalog and README generated or validated against the actual Skill files to avoid drift.
