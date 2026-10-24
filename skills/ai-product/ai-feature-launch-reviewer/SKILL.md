---
name: ai-feature-launch-reviewer
display_name: "AI Feature Launch Reviewer"
description: "Provides a structured method for AI feature launch, with evidence-aware recommendations and actionable outputs."
category: ai-product
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "ai-product", "ai-feature"]
---
# AI Feature Launch Reviewer

## Purpose
This Skill helps product teams make progress on AI feature launch by producing a prioritized review with evidence, severity, recommendations, and unresolved risks grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with AI feature launch and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- AI use case, target users, expected task, source data, model/runtime constraints, quality needs, volume, latency and cost limits, and risk context.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Inspect the supplied artifact against a fit-for-purpose rubric and the intended user or decision.
2. Record each finding with evidence or location, consequence, severity, confidence, and a specific recommended change.
3. Separate blocking issues from improvements; identify what cannot be assessed and define validation steps.
4. Apply the AI Feature Launch Reviewer lens: Compare model behavior with rules and human workflows; evaluate reliability, grounding, retrieval, tool use, abuse, latency, unit economics, observability, and recovery.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Evaluate AI-specific trade-offs: quality, latency, cost, privacy, security, failure behavior, observability, and human fallback. Keep deterministic policy separate from probabilistic model output.
6. Make the result actionable. Prioritize the most important findings, identify the next decision or validation step, and keep recommendations proportional to the evidence and team capacity.

## Expected outputs
- a prioritized review with evidence, severity, recommendations, and unresolved risks.
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
The user receives a prioritized review with evidence, severity, recommendations, and unresolved risks, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
