---
name: ab-testing-expert
display_name: "A/B Testing Expert"
description: "Design interpretable product experiments with defensible metrics, sample-size assumptions, and decision rules."
category: experimentation
asset_type: skill
version: "1.1.0"
status: active
portability: portable
review_status: content-reviewed
tags: ["experimentation", "ab-testing", "statistics"]
source: https://github.com/imohammadfaraz/claude-skills-for-product-manager/blob/main/top-skills/ab-testing-expert/ab-testing-expert.md
---
# A/B Testing Expert

## Purpose
Create an experiment plan that helps a product team learn whether a defined change improves an outcome without unacceptable harm to guardrails.

## When to use
Use when comparing product variants or evaluating a causal product hypothesis. If traffic, instrumentation, or randomization is inadequate, recommend a safer learning method instead of forcing an A/B test.

## Inputs
- Product change, user problem, hypothesis, and decision the result will inform.
- Primary outcome, baseline rate or distribution, eligible traffic, and expected exposure.
- Meaningful minimum detectable effect (MDE), if known, and experiment constraints.
- Randomization unit, audience, platform, duration constraints, guardrails, and existing concurrent tests.
- Desired depth: concise plan or detailed design.

## Process
1. **Clarify material gaps only.** Ask for missing baseline, traffic, outcome, or constraints when necessary. If the user wants a draft and values are unavailable, provide a plan with labeled assumptions and explain what is needed before launch.
2. **State the hypothesis.** Use "If we change X for population Y, metric Z will change in direction D because reason R."
3. **Specify variants.** Describe control and treatment. Identify the main difference and avoid changing multiple unrelated factors unless the design explicitly tests a bundle.
4. **Define measurement.** Choose one primary metric, relevant secondary metrics, guardrails, eligibility, exposure, event definitions, and analysis unit.
5. **Plan sample size and runtime.** State baseline, MDE, significance level, power, allocation, and method. Calculate only when enough inputs and a suitable method are available. Otherwise mark estimates as pending rather than inventing sample counts.
6. **Pre-register the analysis.** Define exclusion rules, duration or stopping rule, handling of missing data, segment analyses, and decision criteria before observing results.
7. **Assess validity risks.** Consider sample-ratio mismatch, instrumentation errors, novelty, seasonality, interference, repeated peeking, multiple comparisons, and user exposure to multiple variants.
8. **Define decisions.** Specify what happens if the result is positive, negative, or inconclusive. Statistical significance alone does not establish practical value.
9. **Explain terms when useful.** Define statistical power, p-value, confidence interval, MDE, or randomization unit in plain language when they appear and may be unfamiliar.

## Expected outputs
- Objective, hypothesis, and variants.
- Primary, secondary, and guardrail metrics with definitions.
- Design and sample-size assumptions, method, and runtime estimate or explicit missing inputs.
- Analysis and stopping plan.
- Risks, instrumentation checks, and decision rules for positive, negative, and inconclusive results.

## Quality checklist
- The primary metric measures the intended effect and is defined before the test.
- MDE represents a practically meaningful effect, not just a convenient number.
- Sample size claims are supported by inputs and a stated method.
- Stopping and analysis rules avoid unplanned repeated significance checking.
- Guardrails and all decision outcomes are covered.
- Limitations and uncertainty are explicit.

## Guardrails
- Do not promise that p < 0.05 means a result is certainly real or important.
- Do not invent baseline rates, traffic, sample sizes, or expected lift.
- Do not recommend an A/B test when traffic or assignment integrity cannot support interpretable results.
- Do not recommend repeatedly checking results and stopping at the first favorable p-value.
- Consider ethical, privacy, and user-impact risks before experimentation.

## Definition of done
The plan is executable by a product and analytics team, with assumptions and decision rules documented before the experiment starts.
