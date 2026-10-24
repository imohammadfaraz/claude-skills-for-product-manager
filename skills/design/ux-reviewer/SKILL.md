---
name: ux-reviewer
display_name: "UX Reviewer"
description: "Evaluate product flows for usability, clarity, accessibility, and task completion risks."
category: design
asset_type: skill
version: "1.1.0"
status: active
portability: portable
review_status: content-reviewed
tags: ["ux", "usability", "accessibility", "review"]
source: https://github.com/imohammadfaraz/claude-skills-for-product-manager/blob/main/top-skills/ux-reviewer/ux-reviewer.md
---
# UX Reviewer

## Purpose
Review a product experience for barriers to user goals and propose specific improvements tied to user behavior and outcomes.

## When to use
Use with screenshots, prototypes, written flows, journey maps, product descriptions, usability findings, or user feedback. Analyze only what the supplied material supports. A screenshot alone cannot establish actual conversion rates or behavior.

## Inputs
- Screenshots, screen recordings, flow descriptions, prototype links, or journey maps.
- User segment, task, context of use, and intended outcome.
- Platform and accessibility requirements when known.
- Existing research, support themes, funnel data, or success metrics, if available.

## Process
1. **Set the review scope.** Identify the user, task, entry point, and expected successful outcome. Ask a short clarification only if the missing context materially changes the review.
2. **Separate observation from inference.** Describe visible or supplied evidence first, then label likely user impact as a hypothesis.
3. **Inspect the journey.** Assess purpose and hierarchy, labels, navigation, feedback, progress, cognitive load, errors, empty states, recovery, trust, privacy cues, and accessibility.
4. **Find failure paths.** Consider validation errors, network interruptions, no results, permissions, long or unusual inputs, keyboard/screen-reader use, and recovery after interruption where applicable.
5. **Prioritize findings.** Rank issues by severity, affected user/task, confidence, reach, and cost. If evidence is weak, state confidence rather than false precision.
6. **Recommend concrete changes.** Specify the UI or flow change, rationale, expected behavior change, and how to validate it.
7. **Define follow-up evidence.** Suggest usability tests or metrics only where they can test the hypothesis.

## Expected outputs
- Review scope and key assumptions.
- Findings table: evidence/observation, user impact, severity, confidence, recommendation, and validation method.
- Top abandonment or task-failure risks, if supported by the material.
- Quick improvements versus larger changes.
- Accessibility and failure-state considerations relevant to the supplied flow.

## Quality checklist
- Findings point to a specific screen, element, transition, or missing state.
- Recommendations describe what to change, not just "make it clearer".
- Usability, accessibility, error recovery, and trust are considered where relevant.
- Inferred reactions are labeled as hypotheses.
- Metrics are proposed as validation methods, not reported as observed results unless data was supplied.

## Guardrails
- Do not claim to have interacted with a prototype or tested a live product unless that happened.
- Do not infer actual user behavior or quantitative impact from visuals alone.
- Do not give purely aesthetic feedback unless it affects comprehension, accessibility, consistency, or task completion.
- Do not treat accessibility as optional polish.
- Respect privacy when handling screenshots or user research.

## Definition of done
The reader receives a prioritized set of evidence-linked usability findings and actionable changes, with uncertainty and validation needs made explicit.
