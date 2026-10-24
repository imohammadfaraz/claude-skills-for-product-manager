---
name: cohort-retention-analyzer
display_name: "Cohort Retention Analyzer"
description: "Provides a structured method for cohort retention, with evidence-aware recommendations and actionable outputs."
category: analytics
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "analytics", "cohort-retention"]
---
# Cohort Retention Analyzer

## Purpose
This Skill helps product teams make progress on cohort retention by producing a structured analysis with evidence, alternatives, implications, and next steps grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with cohort retention and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- Product objective, metric definitions, event data or sample data, user segments, time windows, instrumentation, and intended decision.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Define the decision and comparison frame; identify the relevant user, system, market, or workflow boundary.
2. Examine evidence, likely drivers, alternatives, dependencies, and counter-explanations. Separate correlation from causation where relevant.
3. Rank findings by impact and confidence, recommend validation or action, and state what remains unknown.
4. Apply the Cohort Retention Analyzer lens: Check event semantics, identity and denominator consistency, cohort effects, seasonality, sample size, and instrumentation quality.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Validate measurement: check definitions, denominators, event semantics, missing data, cohort effects, seasonality, and guardrails.
6. Make the result actionable. Prioritize the most important findings, identify the next decision or validation step, and keep recommendations proportional to the evidence and team capacity.

## Expected outputs
- a structured analysis with evidence, alternatives, implications, and next steps.
- A concise rationale tied to the supplied context and decision.
- Evidence, assumptions, unknowns, and material risks clearly separated.
- Prioritized next steps, validation checks, and open questions.

## Quality checklist
- The output directly addresses the stated objective and intended audience.
- Every important recommendation is connected to evidence, a clearly labeled assumption, or an explicit hypothesis.
- Alternatives, trade-offs, limitations, and material failure modes are considered.
- Priorities are explained; false precision and unsupported claims are avoided.
- The artifact is clear enough for another teammate to review, challenge, and use.
- Metric formulas are unambiguous; data quality and confounders are considered; recommendations include validation and guardrails.

## Guardrails
- Do not invent source evidence, customer quotes, statistics, benchmarks, policies, approvals, owners, dates, or system capabilities.
- Do not claim to have browsed, run code, queried a database, tested a prototype, or verified an implementation unless that action actually occurred.
- If information is missing, identify the gap and either ask a focused question or proceed with clearly labeled assumptions.
- Define denominators and time windows, distinguish correlation from causation, protect sensitive data, and never invent results or baselines.
- Do not fabricate metric values, sample sizes, benchmark ranges, SQL schemas, or experiment outcomes.

## Definition of done
The user receives a structured analysis with evidence, alternatives, implications, and next steps, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
