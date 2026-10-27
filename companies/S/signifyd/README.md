# Signifyd

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 2 | 2 | 2 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 2 | 2 | 0 | 2 |
| AI Engineer | 0 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain the difference between fail-fast and fail-safe. For a fraud-check service in a payment flow, which do you pick and why? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-fail-fast-and-fail-safe-for-a-fraud-che-29903) |
| Design fraud-scoring in the payment authorization path that must add under 30ms of latency — how do you fetch features rules and velocity counters synchronously and fall back safely if the scorer times out? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-fraud-scoring-in-the-payment-authorization-path-that-must-add-u-28341) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a fraud/risk decisioning rules engine when you need to change rules hourly during an attack, and a vendor's change-deployment latency could cost you money in real time? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-fraud-risk-decisioning-rules-engi-41069) |
| How do you set reliability targets for a system where the SLI is fundamentally probabilistic — a fraud-detection model that must respond in 200ms but can't guarantee correctness — do you SLO latency separately from precision/recall? | expertise | SDE-2/3, Architect/Principal | Reliability Engineering (SLA/SLO/SLI) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-reliability-targets-for-a-system-where-the-sli-is-funda-41391) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd model the capacity and cost of a feature that adds a synchronous call to a third-party fraud/risk API on every transaction. How does a per-transaction external dependency change your throughput ceiling and your marginal cost per order? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-model-the-capacity-and-cost-of-a-feature-that-adds-a-53001) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your read replicas serve stale snapshots and a fraud check reads a replica while writing the primary. What isolation/consistency framing tells you this design is unsafe, and how do you fix it? | deep understanding | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-read-replicas-serve-stale-snapshots-and-a-fraud-check-reads-a-rep-113681) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you approach setting the decision threshold for an XGBoost classifier when it must balance operational capacity limits with model recall? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-setting-the-decision-threshold-for-an-xgboost-clas-65969) |
| How would you balance recall vs precision for an XGBoost fraud model when the cost of a false negative is 50x a false positive? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-balance-recall-vs-precision-for-an-xgboost-fraud-model-w-65933) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you explain why an LLM is a poor fit for a hard real-time low-latency decision (fraud block at checkout), and what pattern you'd use instead? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-explain-why-an-llm-is-a-poor-fit-for-a-hard-real-time-lo-77984) |
