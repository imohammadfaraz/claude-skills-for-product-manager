---
name: metrics-analytics-designer
display_name: "Metrics & Analytics Designer"
description: "Design decision-oriented product metrics, event tracking, and analytics plans."
category: analytics
asset_type: skill
version: "1.1.0"
status: active
portability: portable
review_status: content-reviewed
tags: ["analytics", "metrics", "event-tracking"]
source: https://github.com/imohammadfaraz/claude-skills-for-product-manager/blob/main/top-skills/metrics-analytics-designer/metrics-analytics-designer.md
---
# Metrics & Analytics Designer

## Purpose
Translate product goals and user value into a measurable framework that supports decisions, not just reporting.

## When to use
Use for a new product or feature measurement plan, a metrics audit, an event instrumentation plan, or diagnosis of metric movement. This Skill designs the plan; it does not claim to inspect live analytics unless data or tool access is actually provided.

## Inputs
- Product or feature, target users, user problem, lifecycle stage, and intended decision.
- Business objective, known baseline data, constraints, and available analytics capabilities.
- Requested depth: focused brief, full framework, or executive summary.
- Existing metric definitions, events, dashboards, or data-quality concerns, if available.

## Process
1. **Establish the decision.** Identify what decision the metrics should inform and the user value the product is expected to deliver.
2. **Clarify only material gaps.** Ask concise questions if missing information changes the metric design. Otherwise proceed with clearly labeled assumptions.
3. **Map the value journey.** Describe the key user journey and the observable behavior that signals value realization.
4. **Choose outcome and driver metrics.** Recommend one North Star metric only when a credible candidate exists, plus input metrics across relevant stages such as acquisition, activation, engagement, retention, and monetization.
5. **Define guardrails.** Include quality, trust, reliability, user harm, or cost measures that prevent local optimization from damaging the overall experience.
6. **Specify instrumentation.** Provide event names, triggers, required properties, identity rules, and failure/edge events. Avoid collecting unnecessary personal data.
7. **Design reporting and diagnosis.** Recommend dashboards, segments, review cadence, and plausible responses to metric changes.
8. **State limits.** Separate observed facts from hypotheses, proposed targets, and unverified assumptions. Do not invent benchmarks or claim a metric is validated without evidence.

## Expected outputs
Choose the smallest useful set of deliverables:
- Metric tree or value-to-outcome map.
- Definitions and formulas for primary, input, and guardrail metrics.
- Event tracking table with event, trigger, properties, purpose, and priority.
- Segmentation and dashboard recommendations.
- Diagnostic decision table and data-quality risks.
- Assumptions, open questions, and next steps.

## Quality checklist
- Every metric connects to user value, a business outcome, or a named risk.
- Each metric has a precise definition, numerator/denominator where applicable, and time window.
- Leading indicators are distinguished from lagging outcomes.
- Event definitions are implementable and do not collect sensitive data without a clear need.
- Recommendations are calibrated to product stage, traffic, and team capacity.
- Proposed thresholds are labeled as hypotheses unless supplied or evidence-backed.

## Guardrails
- Do not treat a metric as a North Star merely because it is easy to measure.
- Do not recommend every possible funnel metric by default; include only relevant stages.
- Do not invent baselines, benchmarks, targets, or event coverage.
- Do not imply analytics tools, datasets, or dashboards were accessed unless they were.
- Flag denominator changes, instrumentation gaps, seasonality, cohort effects, and metric gaming risks where relevant.

## Definition of done
A team can tell what to measure, why it matters, how to calculate it, what data to collect, and which decisions the measurement should inform.
