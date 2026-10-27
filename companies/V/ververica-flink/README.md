# Ververica-Flink

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 5

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 1 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd load balance a fleet of stateful stream processors (e.g. Flink task managers) where key-group assignment must stay stable across rescales, so the 'balancer' is really the state-assignment planner. What are the rebalance-cost trade-offs? | expertise | SDE-2/3, Architect/Principal | Load Balancing | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-load-balance-a-fleet-of-stateful-stream-processors-e-38651) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your streaming anomaly detector computes a 5-minute sliding-window rate served to alerting, and a task-manager crash mid-window lost state. Explain what checkpointing and exactly-once state give you and the recovery-time-versus-freshness trade-off of checkpoint frequency. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-streaming-anomaly-detector-computes-a-5-minute-sliding-window-rat-92949) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A well-liked team wants to adopt a shiny new stream-processing engine you believe adds long-term operational burden the data platform can't sustain org-wide. How do you say no while keeping their trust intact? | deep understanding | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-well-liked-team-wants-to-adopt-a-shiny-new-stream-processing-engine--126145) |
| You're asked to weigh in on an already-shipped decision — a team wired a high-fan-out streaming job with no backpressure or checkpointing straight into the shared Kafka cluster — and you think it's a ticking bomb. Do you say anything? When is re-opening a shipped data-pipeline decision worth the disruption? | expertise | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-weigh-in-on-an-already-shipped-decision-a-team-wired-a-126174) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect DR for a stateful stream-processing store (Flink/Kafka Streams state) so on failover you resume from consistent checkpoints without reprocessing or dropping events past your RPO? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-dr-for-a-stateful-stream-processing-store-flink-k-112912) |
