---
name: mock-interview-evaluator
display_name: "Mock Interview Evaluator"
description: "Provides a structured method for mock interview, with evidence-aware recommendations and actionable outputs."
category: career
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "career", "mock-interview"]
---
# Mock Interview Evaluator

## Purpose
This Skill helps product teams make progress on mock interview by producing a structured analysis with evidence, alternatives, implications, and next steps grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with mock interview and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- Target role and level, current experience, examples of work, strengths, gaps, time constraints, and career goals.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Define the decision and comparison frame; identify the relevant user, system, market, or workflow boundary.
2. Examine evidence, likely drivers, alternatives, dependencies, and counter-explanations. Separate correlation from causation where relevant.
3. Rank findings by impact and confidence, recommend validation or action, and state what remains unknown.
4. Apply the Mock Interview Evaluator lens: Assess demonstrated competencies, evidence quality, role expectations, practice needs, portfolio proof, and realistic sequencing.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Preserve truthful evidence: tailor to the intended role and level, but do not invent accomplishments, metrics, credentials, or outcomes.
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
- Feedback is specific and role-relevant; recommendations are achievable; claims remain truthful; progress can be demonstrated with concrete evidence.

## Guardrails
- Do not invent source evidence, customer quotes, statistics, benchmarks, policies, approvals, owners, dates, or system capabilities.
- Do not claim to have browsed, run code, queried a database, tested a prototype, or verified an implementation unless that action actually occurred.
- If information is missing, identify the gap and either ask a focused question or proceed with clearly labeled assumptions.
- Never invent accomplishments, metrics, credentials, employers, or interview outcomes. Use truthful evidence and identify missing proof.
- Do not manufacture resume bullets, metrics, employers, credentials, or interview performance. Use placeholders or ask for evidence.

## Definition of done
The user receives a structured analysis with evidence, alternatives, implications, and next steps, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
