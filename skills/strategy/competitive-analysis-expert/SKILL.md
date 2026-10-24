---
name: competitive-analysis-expert
display_name: "Competitive Analysis Expert"
description: "Compare alternatives using sourced evidence to identify competitive strengths, gaps, and product implications."
category: strategy
asset_type: skill
version: "1.1.0"
status: active
portability: portable
review_status: content-reviewed
tags: ["competitive-analysis", "market", "positioning"]
source: https://github.com/imohammadfaraz/claude-skills-for-product-manager/blob/main/top-skills/competitive-analysis-expert/competitive-analysis-expert.md
---
# Competitive Analysis Expert

## Purpose
Help a product team understand alternatives available to its target users, compare them against meaningful criteria, and identify evidence-backed implications.

## When to use
Use for competitor landscapes, feature comparisons, positioning, market alternatives, or strategy inputs. If current competitor information is required, use available research tools or supplied sources and cite them; do not imply freshness without verification.

## Inputs
- Product, target segment, user job, geography, and comparison question.
- Named competitors or a request to discover relevant alternatives.
- Comparison criteria, current product evidence, and strategic decision at hand.
- Sources, date constraints, and output format, if provided.

## Process
1. **Define the comparison frame.** Identify the target user, job-to-be-done, market boundary, and decision. Distinguish direct competitors from substitutes and the status quo.
2. **Clarify material gaps.** Ask focused questions only if the segment or decision is unclear. Otherwise state assumptions and proceed.
3. **Establish evidence standards.** Prefer primary sources such as product pages, documentation, pricing pages, release notes, filings, and direct observations. Record source and observation date for changeable claims.
4. **Compare consistently.** Use a common set of criteria, such as target segment, core job, capabilities, onboarding, pricing model, integrations, distribution, trust, and limitations. Mark unavailable information as unknown.
5. **Separate fact from interpretation.** Label verified facts, inference, hypotheses, and confidence. Avoid treating marketing claims as independently proven outcomes.
6. **Find patterns and gaps.** Identify table-stakes, meaningful differentiation, underserved needs, switching costs, and potential strategic openings.
7. **Translate into implications.** Recommend what to investigate, match, avoid, or differentiate on, and explain trade-offs.
8. **State limits.** Note gaps in coverage, stale sources, indirect evidence, and what the comparison cannot establish.

## Expected outputs
- Scope, segment, and comparison criteria.
- Competitor/alternative comparison table with source/date/confidence where available.
- Key patterns, strengths, weaknesses, and underserved needs.
- Strategic implications and prioritized follow-up questions.
- Evidence gaps and caveats.

## Quality checklist
- Alternatives are relevant to the user's target segment and job.
- Claims are traceable to evidence or explicitly labeled as inference.
- Comparison criteria are consistent across alternatives.
- Pricing and feature availability include dates or are marked unverified when changeable.
- Recommendations are implications, not a feature-copying checklist.

## Guardrails
- Do not invent competitors, pricing, market share, features, or customer outcomes.
- Do not infer a competitor's internal metrics or strategy as fact.
- Do not treat a missing website detail as proof a capability does not exist.
- Do not recommend copying features without a user need and differentiation rationale.
- Keep the scope to competitive evidence and implications; Product Strategy Builder owns the broader product choices.

## Definition of done
The reader can distinguish what is known about the competitive set from interpretation and use the comparison to inform a concrete product decision.
