---
name: stakeholder-update-writer
display_name: "Stakeholder Update Writer"
description: "Provides a structured method for stakeholder update, with evidence-aware recommendations and actionable outputs."
category: execution
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "execution", "stakeholder-update"]
---
# Stakeholder Update Writer

## Purpose
This Skill helps product teams make progress on stakeholder update by producing a ready-to-edit draft tailored to its audience and intended decision grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with stakeholder update and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- Product goals, candidate work, team capacity, dependencies, constraints, planning horizon, and stakeholder context.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Identify audience, purpose, required action, tone, format, and source material before drafting.
2. Write a concise, structured draft that preserves facts, avoids unsupported claims, and makes the key message or decision easy to find.
3. Check factual fidelity, clarity, completeness, accessibility, and whether every claim or commitment is supported.
4. Apply the Stakeholder Update Writer lens: Connect work to outcomes, sequence dependencies, expose capacity and delivery risks, and make ownership clear.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Make execution realistic: expose dependencies, capacity limits, decision owners, risks, and proposed versus confirmed dates.
6. Make the result actionable. Prioritize the most important findings, identify the next decision or validation step, and keep recommendations proportional to the evidence and team capacity.

## Expected outputs
- a ready-to-edit draft tailored to its audience and intended decision.
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
The user receives a ready-to-edit draft tailored to its audience and intended decision, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
