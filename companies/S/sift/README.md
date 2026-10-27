# Sift

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 17

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 2 | 2 | 2 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 2 | 8 | 6 | 8 |
| AI Engineer | 0 | 0 | 0 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your payments team wants to build an in-house fraud engine instead of buying Sift/Signifyd. How do you weigh proprietary data advantage against time-to-market and regulatory model-explainability? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-payments-team-wants-to-build-an-in-house-fraud-engine-instead-of--36937) |
| Explain the difference between fail-fast and fail-safe. For a fraud-check service in a payment flow, which do you pick and why? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-fail-fast-and-fail-safe-for-a-fraud-che-29903) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a fraud/risk decisioning rules engine when you need to change rules hourly during an attack, and a vendor's change-deployment latency could cost you money in real time? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-fraud-risk-decisioning-rules-engi-41069) |
| What's your framework for build-vs-buy when the capability's value comes almost entirely from network effects the vendor already has (e.g. a fraud consortium sharing signals) that you could never replicate in-house? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-framework-for-build-vs-buy-when-the-capability-s-value-com-41026) |
| Design a real-time fraud-detection platform that scores transactions inline (sub-50ms) using velocity features and a model while a separate async path does deeper investigation — how do you keep feature freshness and feed confirmed fraud back into the online path? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-real-time-fraud-detection-platform-that-scores-transactions-i-39505) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd model the capacity and cost of a feature that adds a synchronous call to a third-party fraud/risk API on every transaction. How does a per-transaction external dependency change your throughput ceiling and your marginal cost per order? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-model-the-capacity-and-cost-of-a-feature-that-adds-a-53001) |

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
| How do you approach setting the decision threshold for an XGBoost classifier when it must balance operational capacity limits with model recall? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-setting-the-decision-threshold-for-an-xgboost-clas-65969) |
| How would you balance recall vs precision for an XGBoost fraud model when the cost of a false negative is 50x a false positive? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-balance-recall-vs-precision-for-an-xgboost-fraud-model-w-65933) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the reference architecture for a human-in-the-loop approval system scaling to thousands of pending high-risk tool actions with SLA-bound reviewer response, escalation, timeout defaults, and full auditability of who approved what and why. | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-reference-architecture-for-a-human-in-the-loop-approval-sys-83112) |
| How do you architect a hybrid rules-plus-ML decision system so hand-authored rules can override the model in risky cases while you still measure the model's true incremental value? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-hybrid-rules-plus-ml-decision-system-so-hand-au-84395) |
