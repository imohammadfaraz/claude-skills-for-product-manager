---
name: roadmap-builder
display_name: "Roadmap Builder"
description: "Provides a structured method for roadmap, with evidence-aware recommendations and actionable outputs."
category: execution
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "execution", "roadmap-builder"]
---
# Roadmap Builder

## Purpose
This Skill helps product teams make progress on roadmap by producing a usable artifact with clear structure, rationale, and open questions grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with roadmap and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- Product goals, candidate work, team capacity, dependencies, constraints, planning horizon, and stakeholder context.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Choose a structure that fits the decision and product maturity; do not force a large template when a compact artifact is sufficient.
2. Populate each section using source-backed facts and explicit assumptions. Preserve traceability between inputs, analysis, and recommendations.
3. Check internal consistency, missing sections, dependencies, and whether another teammate can use the artifact without undocumented context.
4. Apply the Roadmap Builder lens: Connect work to outcomes, sequence dependencies, expose capacity and delivery risks, and make ownership clear.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Make execution realistic: expose dependencies, capacity limits, decision owners, risks, and proposed versus confirmed dates.
6. Make the result actionable. Prioritize the most important findings, identify the next decision or validation step, and keep recommendations proportional to the evidence and team capacity.

## Expected outputs
- a usable artifact with clear structure, rationale, and open questions.
- A concise rationale tied to the supplied context and decision.
- Evidence, assumptions, unknowns, and material risks clearly separated.
- Prioritized next steps, validation checks, and open questions.

## Quality checklist
- The output directly addresses the stated objective and intended audience.
- Every important recommendation is connected to evidence, a clearly labeled assumption, or an explicit hypothesis.
- Alternatives, trade-offs, limitations, and material failure modes are considered.
- Priorities are explained; false precision and unsupported claims are avoided.
- The artifact is clear enough for another teammate to review, challenge, and use.
- Priorities connect to outcomes; dependencies and risks are visible; capacity assumptions are stated; decisions and follow-ups are actionable.

## Guardrails
- Do not invent source evidence, customer quotes, statistics, benchmarks, policies, approvals, owners, dates, or system capabilities.
- Do not claim to have browsed, run code, queried a database, tested a prototype, or verified an implementation unless that action actually occurred.
- If information is missing, identify the gap and either ask a focused question or proceed with clearly labeled assumptions.
- Distinguish committed facts from proposals; do not invent owners, delivery dates, capacity, or approvals.


## Definition of done
The user receives a usable artifact with clear structure, rationale, and open questions, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
