---
name: ai-observability-planner
display_name: "AI Observability Planner"
description: "Provides a structured method for AI observability, with evidence-aware recommendations and actionable outputs."
category: ai-product
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "ai-product", "ai-observability"]
---
# AI Observability Planner

## Purpose
This Skill helps product teams make progress on AI observability by producing a structured plan with sequence, dependencies, decision gates, and validation steps grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with AI observability and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- AI use case, target users, expected task, source data, model/runtime constraints, quality needs, volume, latency and cost limits, and risk context.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Define the question, audience, scope, constraints, and success condition.
2. Sequence activities from highest-risk uncertainty to lower-risk detail; identify dependencies, owners, timing, and fallback options only when known.
3. Specify evidence to collect, decision gates, and how findings should change the next step.
4. Apply the AI Observability Planner lens: Compare model behavior with rules and human workflows; evaluate reliability, grounding, retrieval, tool use, abuse, latency, unit economics, observability, and recovery.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Evaluate AI-specific trade-offs: quality, latency, cost, privacy, security, failure behavior, observability, and human fallback. Keep deterministic policy separate from probabilistic model output.
6. Make the result actionable. Prioritize the most important findings, identify the next decision or validation step, and keep recommendations proportional to the evidence and team capacity.

## Expected outputs
- a structured plan with sequence, dependencies, decision gates, and validation steps.
- A concise rationale tied to the supplied context and decision.
- Evidence, assumptions, unknowns, and material risks clearly separated.
- Prioritized next steps, validation checks, and open questions.

## Quality checklist
- The output directly addresses the stated objective and intended audience.
- Every important recommendation is connected to evidence, a clearly labeled assumption, or an explicit hypothesis.
- Alternatives, trade-offs, limitations, and material failure modes are considered.
- Priorities are explained; false precision and unsupported claims are avoided.
- The artifact is clear enough for another teammate to review, challenge, and use.
- Quality is measurable; uncertainty and failure states are explicit; data and tool permissions are bounded; human escalation is defined where needed.

## Guardrails
- Do not invent source evidence, customer quotes, statistics, benchmarks, policies, approvals, owners, dates, or system capabilities.
- Do not claim to have browsed, run code, queried a database, tested a prototype, or verified an implementation unless that action actually occurred.
- If information is missing, identify the gap and either ask a focused question or proceed with clearly labeled assumptions.
- Explicitly consider quality, latency, cost, privacy, security, failure handling, and human fallback where relevant. Distinguish deterministic rules from probabilistic model behavior.
- Do not assume model outputs are deterministic, safe, grounded, or correct. Define fallback and escalation for important failures.
- Do not expose secrets or send sensitive data to external services without authorization.

## Definition of done
The user receives a structured plan with sequence, dependencies, decision gates, and validation steps, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
