# Claude Skills for Product Managers

A structured library of **150 Product Management skills** for Claude and compatible AI assistants, covering discovery, strategy, execution, analytics, UX, AI product management, product building, leadership, and PM careers.

All **150 individual skills are linked below**. Each skill is stored at `skills/<category>/<skill-name>/SKILL.md`, with a dedicated folder and consistent filename. The canonical layout has no `top-skills/` directory.

## Quick navigation

- [All 150 skills](#all-150-skills)
- [Recommended starting points](#recommended-starting-points)
- [How to use a skill](#how-to-use-a-skill)
- [Repository structure](#repository-structure)
- [Skill catalog](catalog/skills.yaml)
- [Skill authoring standard](docs/skill-standard.md)
- [Skill audit and review status](docs/skill-audit.md)
- [Source toolkit](https://github.com/imohammadfaraz/product-manager-toolkit)

## Repository structure

```text
skills/
├── ai-product/
├── analytics/
├── career/
├── design/
├── discovery/
├── execution/
├── experimentation/
├── growth/
├── launch/
├── leadership/
├── product-builder/
├── quality/
├── requirements/
└── strategy/
catalog/
docs/
README.md
```

The category folders are directly under `skills/`. Each one contains a `SKILL.md` per skill. The machine-readable catalog holds each skill's stable ID, title, path, version, and review status.

## All 150 skills

### AI Product Management (22)

- [Agent Workflow Designer](skills/ai-product/agent-workflow-designer/SKILL.md)
- [Ai Feature Launch Reviewer](skills/ai-product/ai-feature-launch-reviewer/SKILL.md)
- [Ai Human Handoff Designer](skills/ai-product/ai-human-handoff-designer/SKILL.md)
- [Ai Incident Reviewer](skills/ai-product/ai-incident-reviewer/SKILL.md)
- [Ai Latency Cost Optimizer](skills/ai-product/ai-latency-cost-optimizer/SKILL.md)
- [Ai Observability Planner](skills/ai-product/ai-observability-planner/SKILL.md)
- [Ai Opportunity Assessor](skills/ai-product/ai-opportunity-assessor/SKILL.md)
- [Ai Product Feasibility Reviewer](skills/ai-product/ai-product-feasibility-reviewer/SKILL.md)
- [Ai Product Requirements Writer](skills/ai-product/ai-product-requirements-writer/SKILL.md)
- [Ai Quality Error Taxonomy Builder](skills/ai-product/ai-quality-error-taxonomy-builder/SKILL.md)
- [Ai Vs Rules Vs Human Decision Maker](skills/ai-product/ai-vs-rules-vs-human-decision-maker/SKILL.md)
- [Golden Dataset Builder](skills/ai-product/golden-dataset-builder/SKILL.md)
- [Hallucination Risk Reviewer](skills/ai-product/hallucination-risk-reviewer/SKILL.md)
- [Llm Evaluation Planner](skills/ai-product/llm-evaluation-planner/SKILL.md)
- [Llm Evaluation Rubric Builder](skills/ai-product/llm-evaluation-rubric-builder/SKILL.md)
- [Llm Use Case Risk Assessor](skills/ai-product/llm-use-case-risk-assessor/SKILL.md)
- [Model Selection Tradeoff Analyzer](skills/ai-product/model-selection-tradeoff-analyzer/SKILL.md)
- [Prompt Regression Test Planner](skills/ai-product/prompt-regression-test-planner/SKILL.md)
- [Rag Product Spec Builder](skills/ai-product/rag-product-spec-builder/SKILL.md)
- [Rag Retrieval Quality Reviewer](skills/ai-product/rag-retrieval-quality-reviewer/SKILL.md)
- [Responsible Ai Reviewer](skills/ai-product/responsible-ai-reviewer/SKILL.md)
- [Tool Calling Requirements Designer](skills/ai-product/tool-calling-requirements-designer/SKILL.md)

### Product Analytics & Metrics (15)

- [Ab Test Results Interpreter](skills/analytics/ab-test-results-interpreter/SKILL.md)
- [Activation Analysis](skills/analytics/activation-analysis/SKILL.md)
- [Analytics Instrumentation Planner](skills/analytics/analytics-instrumentation-planner/SKILL.md)
- [Churn Diagnostic](skills/analytics/churn-diagnostic/SKILL.md)
- [Cohort Retention Analyzer](skills/analytics/cohort-retention-analyzer/SKILL.md)
- [Dashboard Requirements Writer](skills/analytics/dashboard-requirements-writer/SKILL.md)
- [Event Taxonomy Designer](skills/analytics/event-taxonomy-designer/SKILL.md)
- [Experiment Design Reviewer](skills/analytics/experiment-design-reviewer/SKILL.md)
- [Funnel Diagnostic](skills/analytics/funnel-diagnostic/SKILL.md)
- [Growth Opportunity Diagnostic](skills/analytics/growth-opportunity-diagnostic/SKILL.md)
- [Metric Tree Builder](skills/analytics/metric-tree-builder/SKILL.md)
- [Metrics Analytics Designer](skills/analytics/metrics-analytics-designer/SKILL.md)
- [North Star Metric Builder](skills/analytics/north-star-metric-builder/SKILL.md)
- [Product Metric Anomaly Investigator](skills/analytics/product-metric-anomaly-investigator/SKILL.md)
- [Sql For Product Analytics](skills/analytics/sql-for-product-analytics/SKILL.md)

### PM Career & Learning (12)

- [Metrics Interview Coach](skills/career/metrics-interview-coach/SKILL.md)
- [Mock Interview Evaluator](skills/career/mock-interview-evaluator/SKILL.md)
- [Pm Achievement Quantifier](skills/career/pm-achievement-quantifier/SKILL.md)
- [Pm Career Transition Planner](skills/career/pm-career-transition-planner/SKILL.md)
- [Pm Learning Roadmap Builder](skills/career/pm-learning-roadmap-builder/SKILL.md)
- [Pm Portfolio Project Planner](skills/career/pm-portfolio-project-planner/SKILL.md)
- [Pm Skill Gap Assessor](skills/career/pm-skill-gap-assessor/SKILL.md)
- [Portfolio Case Study Reviewer](skills/career/portfolio-case-study-reviewer/SKILL.md)
- [Product Case Interview Coach](skills/career/product-case-interview-coach/SKILL.md)
- [Product Sense Interview Practice](skills/career/product-sense-interview-practice/SKILL.md)
- [Product Strategy Interview Coach](skills/career/product-strategy-interview-coach/SKILL.md)
- [Resume Impact Bullet Reviewer](skills/career/resume-impact-bullet-reviewer/SKILL.md)

### UX, Design & Product Quality (13)

- [Accessibility Reviewer](skills/design/accessibility-reviewer/SKILL.md)
- [Design System Consistency Reviewer](skills/design/design-system-consistency-reviewer/SKILL.md)
- [Empty Error Loading State Reviewer](skills/design/empty-error-loading-state-reviewer/SKILL.md)
- [Feature Acceptance Reviewer](skills/design/feature-acceptance-reviewer/SKILL.md)
- [Heuristic Ux Auditor](skills/design/heuristic-ux-auditor/SKILL.md)
- [Information Architecture Reviewer](skills/design/information-architecture-reviewer/SKILL.md)
- [Mobile Experience Reviewer](skills/design/mobile-experience-reviewer/SKILL.md)
- [Onboarding Flow Reviewer](skills/design/onboarding-flow-reviewer/SKILL.md)
- [Pre Release Product Auditor](skills/design/pre-release-product-auditor/SKILL.md)
- [Product Copy Reviewer](skills/design/product-copy-reviewer/SKILL.md)
- [Usability Findings Synthesizer](skills/design/usability-findings-synthesizer/SKILL.md)
- [Usability Test Planner](skills/design/usability-test-planner/SKILL.md)
- [Ux Reviewer](skills/design/ux-reviewer/SKILL.md)

### Product Discovery & Research (13)

- [Assumption Mapper](skills/discovery/assumption-mapper/SKILL.md)
- [Customer Feedback Analyzer](skills/discovery/customer-feedback-analyzer/SKILL.md)
- [Customer Interview Planner](skills/discovery/customer-interview-planner/SKILL.md)
- [Customer Journey Mapper](skills/discovery/customer-journey-mapper/SKILL.md)
- [Interview Question Builder](skills/discovery/interview-question-builder/SKILL.md)
- [Interview Synthesis](skills/discovery/interview-synthesis/SKILL.md)
- [Jobs To Be Done Analyzer](skills/discovery/jobs-to-be-done-analyzer/SKILL.md)
- [Opportunity Solution Tree Builder](skills/discovery/opportunity-solution-tree-builder/SKILL.md)
- [Persona Builder](skills/discovery/persona-builder/SKILL.md)
- [Problem Definition Expert](skills/discovery/problem-definition-expert/SKILL.md)
- [Problem Validation Planner](skills/discovery/problem-validation-planner/SKILL.md)
- [Research Insight Prioritizer](skills/discovery/research-insight-prioritizer/SKILL.md)
- [Survey Designer](skills/discovery/survey-designer/SKILL.md)

### Product Execution (14)

- [Backlog Health Reviewer](skills/execution/backlog-health-reviewer/SKILL.md)
- [Decision Memo Writer](skills/execution/decision-memo-writer/SKILL.md)
- [Delivery Risk Analyzer](skills/execution/delivery-risk-analyzer/SKILL.md)
- [Dependency Mapper](skills/execution/dependency-mapper/SKILL.md)
- [Feature Prioritizer](skills/execution/feature-prioritizer/SKILL.md)
- [Meeting Decision Extractor](skills/execution/meeting-decision-extractor/SKILL.md)
- [Okrs And Krs Builder](skills/execution/okrs-and-krs-builder/SKILL.md)
- [Post Launch Reviewer](skills/execution/post-launch-reviewer/SKILL.md)
- [Release Notes Writer](skills/execution/release-notes-writer/SKILL.md)
- [Rice Prioritization](skills/execution/rice-prioritization/SKILL.md)
- [Roadmap Builder](skills/execution/roadmap-builder/SKILL.md)
- [Roadmap Challenge Reviewer](skills/execution/roadmap-challenge-reviewer/SKILL.md)
- [Sprint Planning Assistant](skills/execution/sprint-planning-assistant/SKILL.md)
- [Stakeholder Update Writer](skills/execution/stakeholder-update-writer/SKILL.md)

### Experimentation (1)

- [Ab Testing Expert](skills/experimentation/ab-testing-expert/SKILL.md)

### Growth & Monetization (1)

- [Monetization Strategist](skills/growth/monetization-strategist/SKILL.md)

### Launch & Go-to-Market (1)

- [Gtm Planner](skills/launch/gtm-planner/SKILL.md)

### Product Leadership (10)

- [Conflict Resolution Preparation](skills/leadership/conflict-resolution-preparation/SKILL.md)
- [Cross Functional Dependency Reviewer](skills/leadership/cross-functional-dependency-reviewer/SKILL.md)
- [Executive Product Brief Writer](skills/leadership/executive-product-brief-writer/SKILL.md)
- [Product Decision Challenger](skills/leadership/product-decision-challenger/SKILL.md)
- [Product Leadership Coaching Guide](skills/leadership/product-leadership-coaching-guide/SKILL.md)
- [Product Org Maturity Assessor](skills/leadership/product-org-maturity-assessor/SKILL.md)
- [Product Review Facilitator](skills/leadership/product-review-facilitator/SKILL.md)
- [Product Team Retrospective](skills/leadership/product-team-retrospective/SKILL.md)
- [Stakeholder Alignment Planner](skills/leadership/stakeholder-alignment-planner/SKILL.md)
- [Tradeoff Analysis Builder](skills/leadership/tradeoff-analysis-builder/SKILL.md)

### AI Product Builder & Technical PM (14)

- [Ai App Builder Prompt Generator](skills/product-builder/ai-app-builder-prompt-generator/SKILL.md)
- [Api Integration Planner](skills/product-builder/api-integration-planner/SKILL.md)
- [Automated Test Planner](skills/product-builder/automated-test-planner/SKILL.md)
- [Backend Architecture Reviewer](skills/product-builder/backend-architecture-reviewer/SKILL.md)
- [Code Change Impact Analyzer](skills/product-builder/code-change-impact-analyzer/SKILL.md)
- [Database Schema Reviewer](skills/product-builder/database-schema-reviewer/SKILL.md)
- [Deployment Readiness Reviewer](skills/product-builder/deployment-readiness-reviewer/SKILL.md)
- [Frontend Ux Code Reviewer](skills/product-builder/frontend-ux-code-reviewer/SKILL.md)
- [Idea To Prototype Planner](skills/product-builder/idea-to-prototype-planner/SKILL.md)
- [Prototype Requirements Writer](skills/product-builder/prototype-requirements-writer/SKILL.md)
- [Prototype To Production Gap Analyzer](skills/product-builder/prototype-to-production-gap-analyzer/SKILL.md)
- [Prototype Usability Test Planner](skills/product-builder/prototype-usability-test-planner/SKILL.md)
- [Security And Privacy Reviewer](skills/product-builder/security-and-privacy-reviewer/SKILL.md)
- [Technical Feasibility Reviewer](skills/product-builder/technical-feasibility-reviewer/SKILL.md)

### Quality & Risk (1)

- [Risk And Edge Case Analyzer](skills/quality/risk-and-edge-case-analyzer/SKILL.md)

### Requirements & Acceptance Criteria (19)

- [Acceptance Criteria Generator](skills/requirements/acceptance-criteria-generator/SKILL.md)
- [Business Rule Builder](skills/requirements/business-rule-builder/SKILL.md)
- [Change Impact Analyzer](skills/requirements/change-impact-analyzer/SKILL.md)
- [Clarification Builder](skills/requirements/clarification-builder/SKILL.md)
- [Coverage Gap Analyzer](skills/requirements/coverage-gap-analyzer/SKILL.md)
- [Edge Case Generator](skills/requirements/edge-case-generator/SKILL.md)
- [Gherkin Quality Reviewer](skills/requirements/gherkin-quality-reviewer/SKILL.md)
- [Non Functional Reviewer](skills/requirements/non-functional-reviewer/SKILL.md)
- [Prd Analyzer](skills/requirements/prd-analyzer/SKILL.md)
- [Prd Generator](skills/requirements/prd-generator/SKILL.md)
- [Prd Intake](skills/requirements/prd-intake/SKILL.md)
- [Prd To Gherkin](skills/requirements/prd-to-gherkin/SKILL.md)
- [Qa Handoff](skills/requirements/qa-handoff/SKILL.md)
- [Requirement Decomposer](skills/requirements/requirement-decomposer/SKILL.md)
- [Scenario Coverage Planner](skills/requirements/scenario-coverage-planner/SKILL.md)
- [Test Data Builder](skills/requirements/test-data-builder/SKILL.md)
- [Traceability Matrix](skills/requirements/traceability-matrix/SKILL.md)
- [User Story Generator](skills/requirements/user-story-generator/SKILL.md)
- [Workflow Orchestrator](skills/requirements/workflow-orchestrator/SKILL.md)

### Product Strategy & Market Intelligence (14)

- [Build Buy Partner Analyzer](skills/strategy/build-buy-partner-analyzer/SKILL.md)
- [Business Model Canvas Builder](skills/strategy/business-model-canvas-builder/SKILL.md)
- [Competitive Analysis Expert](skills/strategy/competitive-analysis-expert/SKILL.md)
- [Competitive Positioning Analyzer](skills/strategy/competitive-positioning-analyzer/SKILL.md)
- [Competitor Feature Matrix](skills/strategy/competitor-feature-matrix/SKILL.md)
- [Icp And Segmentation Builder](skills/strategy/icp-and-segmentation-builder/SKILL.md)
- [Market Research Planner](skills/strategy/market-research-planner/SKILL.md)
- [Product Portfolio Prioritizer](skills/strategy/product-portfolio-prioritizer/SKILL.md)
- [Product Strategy Builder](skills/strategy/product-strategy-builder/SKILL.md)
- [Product Vision Builder](skills/strategy/product-vision-builder/SKILL.md)
- [Strategic Options Analyzer](skills/strategy/strategic-options-analyzer/SKILL.md)
- [Strategy Assumption Reviewer](skills/strategy/strategy-assumption-reviewer/SKILL.md)
- [Tam Sam Som Estimator](skills/strategy/tam-sam-som-estimator/SKILL.md)
- [Value Proposition Designer](skills/strategy/value-proposition-designer/SKILL.md)

## Recommended starting points

| Need | Skill |
|---|---|
| Define a problem | [Problem Definition Expert](skills/discovery/problem-definition-expert/SKILL.md) |
| Plan customer interviews | [Customer Interview Planner](skills/discovery/customer-interview-planner/SKILL.md) |
| Synthesize user interviews | [Interview Synthesis](skills/discovery/interview-synthesis/SKILL.md) |
| Analyze competitors | [Competitive Analysis Expert](skills/strategy/competitive-analysis-expert/SKILL.md) |
| Develop product strategy | [Product Strategy Builder](skills/strategy/product-strategy-builder/SKILL.md) |
| Generate a PRD | [PRD Generator](skills/requirements/prd-generator/SKILL.md) |
| Review PRD gaps | [PRD Analyzer](skills/requirements/prd-analyzer/SKILL.md) |
| Generate acceptance criteria | [Acceptance Criteria Generator](skills/requirements/acceptance-criteria-generator/SKILL.md) |
| Convert a PRD to Gherkin | [PRD-to-Gherkin Converter](skills/requirements/prd-to-gherkin/SKILL.md) |
| Prioritize features | [Feature Prioritizer](skills/execution/feature-prioritizer/SKILL.md) |
| Build a roadmap | [Roadmap Builder](skills/execution/roadmap-builder/SKILL.md) |
| Design product metrics | [Metrics & Analytics Designer](skills/analytics/metrics-analytics-designer/SKILL.md) |
| Plan an experiment | [A/B Testing Expert](skills/experimentation/ab-testing-expert/SKILL.md) |
| Design agent workflows | [Agent Workflow Designer](skills/ai-product/agent-workflow-designer/SKILL.md) |
| Review responsible AI risks | [Responsible AI Reviewer](skills/ai-product/responsible-ai-reviewer/SKILL.md) |
| Plan a prototype | [Idea to Prototype Planner](skills/product-builder/idea-to-prototype-planner/SKILL.md) |
| Review user experience | [UX Reviewer](skills/design/ux-reviewer/SKILL.md) |
| Practice PM interviews | [Product Case Interview Coach](skills/career/product-case-interview-coach/SKILL.md) |

## How to use a skill

1. Open a skill from the index.
2. Provide relevant product context, constraints, goals, and source evidence.
3. Follow the instructions with Claude or another compatible assistant.
4. Review the output for unsupported assumptions, missing evidence, and applicability before use.

These are portable instruction assets. They are not automatically runtime-installed, orchestrated, or behaviorally evaluated across all hosts. Structural consistency is not the same as full editorial review or runtime evaluation.

## Formatting and contribution guidelines

- Use kebab-case for folder names.
- Use `skills/<category>/<skill-name>/SKILL.md` for every skill.
- Preserve front matter and required sections in the [skill authoring standard](docs/skill-standard.md).
- Update `catalog/skills.yaml` whenever a skill is added, renamed, moved, or retired.
- Keep tool-specific configuration and credentials outside reusable skill instructions.
- Do not claim testing or evaluation unless it actually occurred.

## Source and licensing

The canonical files are sourced from [Product Manager Toolkit](https://github.com/imohammadfaraz/product-manager-toolkit). The source repository has not selected a license, so this repository does not add reuse or redistribution permissions.
