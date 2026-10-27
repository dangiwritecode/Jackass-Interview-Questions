# Decodable

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 0 | 1 |
| Data Engineer | 0 | 0 | 0 | 9 | 9 | 9 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A stream processor must join a fast event stream against a slowly-changing dimension table; what in-memory structure holds the dimension, and how do you handle updates without stalling the join? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-stream-processor-must-join-a-fast-event-stream-against-a-slowly-chan-21991) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a Kafka-to-lakehouse sink / ingestion path (buy Confluent's connectors/Tableflow vs build your own compaction-aware sink) when exactly-once semantics into Iceberg and small-file management determine both correctness and query cost downstream? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-kafka-to-lakehouse-sink-ingestion-125889) |
| How do you decide build-vs-buy for a real-time streaming-analytics/materialized-view engine (Flink/Spark Streaming self-run vs Materialize/RisingWave vs bespoke) when both correctness under late and out-of-order data and cost-per-event drive a platform bet that touches every real-time product? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-real-time-streaming-analytics-mat-125829) |
| How do you decide build-vs-buy for a streaming-ETL / stream-processing framework that your data-platform team owns operationally (self-run Flink vs Confluent/Decodable managed vs Databricks streaming) when the on-call for stateful streaming jobs lands on you, not on the app teams? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-streaming-etl-stream-processing-f-125859) |
| A bar-raiser probes your streaming design: 'what happens to a Flink job's exactly-once guarantee when you rescale parallelism, and how does that interact with your Kafka partition count and your sink's transaction support?' Walk through checkpoint/savepoint mechanics and where the guarantee silently degrades. | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-probes-your-streaming-design-what-happens-to-a-flink-job--125648) |
| Contrast a batch-first lakehouse with a streaming-first Kappa architecture as the enterprise default when 70% of workloads are daily reporting but the CDO wants 'real-time.' Defend where a unified batch-and-stream engine (Flink) genuinely reduces two-codebase drift versus adding operational surface nobody needed. | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-a-batch-first-lakehouse-with-a-streaming-first-kappa-architec-125620) |
| Contrast a Kafka-plus-stream-processor backbone with a streaming database (Materialize/RisingWave) for maintaining always-fresh enterprise materialized views. For which classes of view is each the right spine, and what operational and cost surprises appear when you push complex joins into the streaming tier? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-a-kafka-plus-stream-processor-backbone-with-a-streaming-datab-125649) |
| Design the enterprise pattern for handling late-arriving and out-of-order events in streaming aggregates so a metric doesn't flip-flop as stragglers land. Walk through watermark strategy, allowed-lateness, and how you make the freshness-vs-completeness trade-off a platform-level policy rather than each team's guess. | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-enterprise-pattern-for-handling-late-arriving-and-out-of-or-125665) |
| A principal-level scenario: your streaming pipeline runs 24/7 but carries meaningful volume only during a 4-hour daily peak. Architect a cost-adaptive streaming design — parallelism autoscaling, dynamic Kafka consumer scaling, off-peak checkpoint tuning — that scales down off-peak without dropping the SLA for the busy window. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-level-scenario-your-streaming-pipeline-runs-24-7-but-carri-125952) |
| Your streaming platform's consumer lag spiked during an incident and the auto-scaler spun up dozens of extra Flink task managers that never scaled back, quietly becoming permanent baseline cost. What signal distinguishes emergency stream-processing capacity that should sunset from capacity that legitimately became steady-state, and how do you enforce the paydown? | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-streaming-platform-s-consumer-lag-spiked-during-an-incident-and-t-125990) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect PII scrubbing in a streaming pipeline (Kafka/Flink) where you can't buffer whole records but must mask before anything lands downstream? | deep understanding | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-pii-scrubbing-in-a-streaming-pipeline-kafka-fl-72625) |
