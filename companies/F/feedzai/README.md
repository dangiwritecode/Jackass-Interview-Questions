# Feedzai

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 0 | 7 | 7 | 7 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a real-time fraud/risk decisioning platform that must respond in under 50ms, combine dozens of features and rules, stay explainable for compliance, and let risk analysts change rules without a deploy? | expertise | SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-real-time-fraud-risk-decisioning-platform-that--31044) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a real-time fraud-detection platform that scores transactions inline (sub-50ms) using velocity features and a model while a separate async path does deeper investigation — how do you keep feature freshness and feed confirmed fraud back into the online path? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-real-time-fraud-detection-platform-that-scores-transactions-i-39505) |
| How do you set reliability targets for a system where the SLI is fundamentally probabilistic — a fraud-detection model that must respond in 200ms but can't guarantee correctness — do you SLO latency separately from precision/recall? | expertise | SDE-2/3, Architect/Principal | Reliability Engineering (SLA/SLO/SLI) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-reliability-targets-for-a-system-where-the-sli-is-funda-41391) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A bar-raiser asks you to defend running an AP store for a fraud-decisioning feature store where a stale feature could approve a fraudulent transaction; reconstruct the guardrails (bounded staleness, fail-closed on critical features) that make that bet defensible. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-asks-you-to-defend-running-an-ap-store-for-a-fraud-decisi-111589) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a fraud/risk ML decisioning platform (buy Sift/Feedzai/DataVisor vs build in-house on your proprietary signals) when your transaction data is a moat but time-to-market and model-explainability for regulators both matter? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-fraud-risk-ml-decisioning-platfor-69804) |
| How do you decide build-vs-buy for a knowledge-graph/entity-resolution ML capability central to a fraud or recommendation product (buy vs build on Neo4j/your own GNNs) — where does capability-fit to your proprietary graph override the vendor's cost advantage? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-knowledge-graph-entity-resolution-69833) |
| How do you decide build-vs-buy when a bought ML capability's per-inference cost scales with your product's success (per-prediction billing) such that winning punishes you financially — when does that dynamic alone justify insourcing the model? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-when-a-bought-ml-capability-s-per-infer-69828) |
| How do you evaluate build-vs-buy when the ML capability's value comes from network effects you can't replicate (e.g. a shared fraud-model consortium or a speech model trained on data volumes only a hyperscaler has) — how do you price the unreplicable-data gap? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-build-vs-buy-when-the-ml-capability-s-value-comes--69805) |
| How do you design an approval and exception workflow for legitimate PII-in-training use cases (fraud, safety) that would otherwise be blocked by policy? | deep understanding | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-approval-and-exception-workflow-for-legitimate-pi-72623) |
| How do you handle a scenario where masking PII destroys a critical signal (e.g. names correlate with fraud rings) — what privacy-preserving alternative preserves it? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-a-scenario-where-masking-pii-destroys-a-critical-sig-72654) |
| What's your reference design for privacy-preserving fraud/risk models shared across a consortium of banks that legally cannot pool raw data? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-reference-design-for-privacy-preserving-fraud-risk-models--72659) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a hybrid rules-plus-ML decision system so hand-authored rules can override the model in risky cases while you still measure the model's true incremental value? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-hybrid-rules-plus-ml-decision-system-so-hand-au-84395) |
