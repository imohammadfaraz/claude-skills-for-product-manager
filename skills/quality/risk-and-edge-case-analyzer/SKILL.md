---
name: risk-and-edge-case-analyzer
display_name: "Risk & Edge Case Analyzer"
description: "Identify product, operational, user-impact, and launch risks with mitigations and validation needs."
category: quality
asset_type: skill
version: "1.1.0"
status: active
portability: portable
review_status: content-reviewed
tags: ["risk", "edge-cases", "quality", "launch-readiness"]
source: https://github.com/imohammadfaraz/claude-skills-for-product-manager/blob/main/top-skills/risk-and-edge-case-analyzer/risk-and-edge-case-analyzer.md
---
# Risk & Edge Case Analyzer

## Purpose
Surface material ways a product change can fail, harm users, create operational burden, or miss its intended outcome, then make the risks actionable.

## When to use
Use during discovery, requirements review, design review, release readiness, or post-incident learning. This Skill surveys broader risk. For exhaustive requirement-linked test scenario generation, hand off to an Edge Case Generator.

## Inputs
- Feature, system, workflow, or launch description.
- Requirements, user journey, architecture, dependencies, and constraints, if available.
- User segments, failure history, security/privacy context, scale assumptions, and operational processes.
- Release stage, risk tolerance, and desired level of detail.

## Process
1. **Define scope and context.** Identify what is changing, who may be affected, and the decisions the analysis should support. Ask only for material gaps.
2. **Map risk categories.** Consider user harm, functional failure, data integrity, security/privacy, accessibility, reliability/performance, abuse, compliance, support/operations, dependencies, rollout, and business impact where relevant.
3. **Find concrete failure modes.** Describe the condition, trigger, affected users or systems, and consequence. Avoid generic labels without a scenario.
4. **Rate risk transparently.** Use a simple likelihood/impact scale if useful, define the scale, and mark ratings as estimates when evidence is limited. Include detectability or reversibility when it materially changes priority.
5. **Propose mitigations and controls.** Identify prevention, detection, recovery, owner role, validation evidence, and rollback or escalation path where appropriate.
6. **Check edge conditions.** Consider empty/missing data, invalid inputs, permissions, retries, duplicate actions, partial failure, timeouts, concurrent updates, migrations, and unusual scale only where relevant to the product.
7. **Prioritize.** Separate launch blockers from issues that can be monitored or accepted with explicit rationale.
8. **Identify observability.** Recommend events, alerts, logs, support signals, or manual checks needed to detect failures. Do not claim those controls already exist unless confirmed.
9. **State residual risk.** List assumptions, unresolved decisions, and risks that remain after mitigation.

## Expected outputs
- Risk register: scenario, cause/trigger, impact, likelihood, severity, mitigation, detection, owner role, and status.
- Prioritized edge conditions and validation checks.
- Launch blockers, accepted risks, and rationale.
- Monitoring, recovery, rollback, and escalation recommendations.
- Assumptions and open questions.

## Quality checklist
- Risks are expressed as concrete scenarios with plausible consequences.
- Ratings have definitions and are not presented as objective fact without evidence.
- Mitigations include prevention and/or detection plus recovery where appropriate.
- Priority reflects severity and reversibility, not just frequency.
- Launch blockers and residual risks are explicit.

## Guardrails
- Do not invent compliance requirements, security guarantees, incident history, or existing controls.
- Do not assume every possible edge case has equal importance.
- Do not mark a risk "mitigated" without evidence that the control exists and works.
- Do not turn this broad risk review into a duplicate of detailed test-case generation.
- Escalate high-impact security, safety, privacy, or regulatory questions to qualified owners.

## Definition of done
The team has a prioritized and reviewable view of important failure scenarios, mitigation actions, detection needs, and remaining risk.
