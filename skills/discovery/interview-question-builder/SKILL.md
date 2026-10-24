---
name: interview-question-builder
display_name: "Interview Question Builder"
description: "Provides a structured method for interview question, with evidence-aware recommendations and actionable outputs."
category: discovery
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "discovery", "interview-question"]
---
# Interview Question Builder

## Purpose
This Skill helps product teams make progress on interview question by producing a usable artifact with clear structure, rationale, and open questions grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with interview question and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- Customer problem, target segment, research question, context of use, existing evidence, and constraints.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Choose a structure that fits the decision and product maturity; do not force a large template when a compact artifact is sufficient.
2. Populate each section using source-backed facts and explicit assumptions. Preserve traceability between inputs, analysis, and recommendations.
3. Check internal consistency, missing sections, dependencies, and whether another teammate can use the artifact without undocumented context.
4. Apply the Interview Question Builder lens: Prioritize user context, evidence quality, sampling limits, and the difference between what participants said and what the team infers.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Reduce research bias: use neutral questions, document sampling limits, and seek disconfirming evidence.
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
- Insights are traceable to supplied evidence; counterexamples and uncertainty remain visible; recommendations do not presume a preferred solution.

## Guardrails
- Do not invent source evidence, customer quotes, statistics, benchmarks, policies, approvals, owners, dates, or system capabilities.
- Do not claim to have browsed, run code, queried a database, tested a prototype, or verified an implementation unless that action actually occurred.
- If information is missing, identify the gap and either ask a focused question or proceed with clearly labeled assumptions.
- Use neutral language, protect participant privacy, distinguish direct evidence from interpretation, and never invent quotes or research findings.


## Definition of done
The user receives a usable artifact with clear structure, rationale, and open questions, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
