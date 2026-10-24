---
name: problem-definition-expert
display_name: "Problem Definition Expert"
description: "Turn vague product ideas into testable problem statements and explicit assumptions."
category: discovery
asset_type: skill
version: "1.1.0"
status: active
portability: portable
review_status: content-reviewed
tags: ["discovery", "problem-framing", "assumptions"]
source: https://github.com/imohammadfaraz/claude-skills-for-product-manager/blob/main/top-skills/problem-definition-expert/problem-definition-expert.md
---
# Problem Definition Expert

## Purpose
Help a team distinguish a user problem from a proposed solution, then frame the problem in a way that can be investigated and tested.

## When to use
Use when a product idea is vague, a feature request arrives without evidence, stakeholders disagree about the problem, or a team needs a clear discovery brief. Do not use this Skill to write a full PRD or decide the complete product strategy.

## Inputs
- Initial idea, feature request, stakeholder claim, or customer complaint.
- Intended user or segment, current workflow, context, and desired outcome, if known.
- Research, analytics, support evidence, market signals, and constraints.
- Decisions the team needs to make and any time or access limits.

## Process
1. **Parse the request.** Separate the proposed solution, claimed problem, target user, desired outcome, and supporting evidence.
2. **Identify material unknowns.** Ask focused questions only when answers could change the problem framing. If context is sufficient, proceed and label assumptions.
3. **Describe the current state.** State who experiences what difficulty, in which context, how often or with what consequence when known, and why it matters.
4. **Build an evidence ledger.** Classify statements as supplied evidence, stakeholder assertion, inference, assumption, or unknown. Note source and confidence when available.
5. **Draft the problem statement.** Use: "[User/segment] struggles to [job or goal] in [context] because [supported cause or barrier], resulting in [consequence]." Do not fill every slot with invented details.
6. **Challenge the framing.** Check whether it is solution-neutral, specific enough to investigate, focused on a meaningful user need, and not overly broad. Offer alternative framings if evidence supports more than one.
7. **Define learning needs.** List the riskiest assumptions, what evidence would confirm or weaken them, and the next discovery activity.
8. **Set boundaries.** State what this analysis does not yet establish, including market size, root cause, or solution effectiveness if those are unverified.

## Expected outputs
- Concise problem statement and a brief rationale.
- Known facts, assumptions, inferences, and unknowns.
- Target user and context, where supported.
- Top assumptions ranked by risk and suggested validation method.
- Recommended next discovery steps and explicit out-of-scope questions.

## Quality checklist
- The problem is not simply restated as a feature request.
- The statement identifies a user, goal, context, barrier, and consequence where evidence allows.
- Evidence and assumptions are visibly distinguished.
- Multiple plausible causes remain open when evidence is insufficient.
- Next steps are designed to reduce uncertainty rather than validate a predetermined solution.

## Guardrails
- Do not invent user quotes, research findings, prevalence, severity, or causal explanations.
- Do not present a hypothesis as a validated problem.
- Do not force a problem statement template when key fields are genuinely unknown; use explicit placeholders.
- Avoid leading questions that presume the proposed solution is correct.
- Keep the output focused on problem framing; hand off to PRD Generator for a requirements document.

## Definition of done
The team has a solution-neutral problem statement, an honest view of evidence and uncertainty, and a practical plan to learn what remains unknown.
