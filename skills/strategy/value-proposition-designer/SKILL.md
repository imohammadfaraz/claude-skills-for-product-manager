---
name: value-proposition-designer
display_name: "Value Proposition Designer"
description: "Provides a structured method for value proposition, with evidence-aware recommendations and actionable outputs."
category: strategy
asset_type: skill
version: "1.0.0"
status: active
portability: portable
review_status: standardized
tags: ["product-management", "strategy", "value-proposition"]
---
# Value Proposition Designer

## Purpose
This Skill helps product teams make progress on value proposition by producing a design brief with user needs, states, constraints, and trade-offs grounded in supplied evidence and explicit assumptions.

## When to use
Use this Skill when a team needs help with value proposition and must make a concrete decision, create an artifact, or reduce a material uncertainty. It produces work from supplied context and does not imply external research, tool execution, user testing, or stakeholder approval unless those actions actually occur.

## Inputs
- Product context, target market, customer needs, business objectives, constraints, existing research, and the decision to support.
- The source artifact, dataset, notes, requirements, or options to work from, if available.
- Required output format, audience, depth, and constraints.
- Known decisions, deadlines, dependencies, and unresolved questions.

## Process
1. Identify users, jobs, context, key states, constraints, and the decision the design must support.
2. Develop the proposed structure or interaction, including alternatives, failure states, and trade-offs.
3. Describe how the design should be evaluated and which evidence would confirm or challenge the recommendation.
4. Apply the Value Proposition Designer lens: Assess customer value, market structure, differentiation, business economics, capability fit, and opportunity cost.
5. Communicate uncertainty. Label facts, estimates, assumptions, hypotheses, and unknowns. Ask only clarifying questions that materially change the result; otherwise proceed with explicit assumptions.
4. Test strategic coherence: compare alternatives, opportunity cost, capabilities, market evidence, and conditions that would invalidate the recommendation.
6. Make the result actionable. Prioritize the most important findings, identify the next decision or validation step, and keep recommendations proportional to the evidence and team capacity.

## Expected outputs
- a design brief with user needs, states, constraints, and trade-offs.
- A concise rationale tied to the supplied context and decision.
- Evidence, assumptions, unknowns, and material risks clearly separated.
- Prioritized next steps, validation checks, and open questions.

## Quality checklist
- The output directly addresses the stated objective and intended audience.
- Every important recommendation is connected to evidence, a clearly labeled assumption, or an explicit hypothesis.
- Alternatives, trade-offs, limitations, and material failure modes are considered.
- Priorities are explained; false precision and unsupported claims are avoided.
- The artifact is clear enough for another teammate to review, challenge, and use.
- Choices and trade-offs are explicit; estimates show method and ranges; competitive claims are evidence-linked; the output supports a decision.

## Guardrails
- Do not invent source evidence, customer quotes, statistics, benchmarks, policies, approvals, owners, dates, or system capabilities.
- Do not claim to have browsed, run code, queried a database, tested a prototype, or verified an implementation unless that action actually occurred.
- If information is missing, identify the gap and either ask a focused question or proceed with clearly labeled assumptions.
- Date changeable market claims, distinguish sourced facts from estimates, and state assumptions behind market sizing or strategic conclusions.


## Definition of done
The user receives a design brief with user needs, states, constraints, and trade-offs, a clear rationale, a truthful account of uncertainty, and concrete next steps. The output should support a real product decision without obscuring what still needs validation.
