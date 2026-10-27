# StreamNative

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 4 | 4 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must design an eventing backbone that every team in the org will build on for the next five years. Kafka vs Pulsar vs a managed queue vs a log-per-cell design: make the call as a platform bet, and describe the multi-tenancy, ordering, retention, and schema-governance guarantees you commit to. | expertise | SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-an-eventing-backbone-that-every-team-in-the-org-will-b-33850) |
| You want per-message ack semantics AND the replay/retention of a log. How does Apache Pulsar's model differ from Kafka here, and when would that difference change your choice? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Message Queues & Event-Driven Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-per-message-ack-semantics-and-the-replay-retention-of-a-log-h-26075) |
| How do you evaluate Apache Pulsar versus Kafka as the backbone for a new streaming platform where you anticipate heavy multi-tenancy and geo-replication needs? What would make you bet against the market-default Kafka? | deep understanding | SDE-2/3, Architect/Principal | Real-time Streaming Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-apache-pulsar-versus-kafka-as-the-backbone-for-a-n-37880) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a message-broker platform at scale (self-run Kafka/Pulsar vs MSK/Confluent Cloud vs cloud-native SNS/SQS/PubSub) when partition rebalancing toil vs managed premium drives a $2M/yr decision? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-message-broker-platform-at-scale--53756) |
| How would you architect an event backbone (Kafka/Pulsar) spanning clouds so producers and consumers in different providers get ordered, exactly-once semantics you can defend? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud & Hybrid Cloud | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-an-event-backbone-kafka-pulsar-spanning-clouds-55289) |
| You must decide how the mesh interoperates with a large event-driven backbone (Kafka/Pulsar) that carries most inter-service traffic. Frame where a request-response mesh adds value in an async-first architecture, and whether to invest in mesh at all for such an org. | deep understanding | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-how-the-mesh-interoperates-with-a-large-event-driven-b-52658) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect DR for the streaming ingestion tier (Kafka/Kinesis/Pulsar) that fans telemetry into your platform, so that consumer offsets and in-flight events don't produce gaps or duplicate anomalies past your RPO on failover? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-dr-for-the-streaming-ingestion-tier-kafka-kinesis-99938) |
| The platform's shared message bus (Kafka/Pulsar) carrying feature events is now the throughput ceiling for every real-time model. Design how you scale ingestion past a single bus's limits without teams having to reason about partitions, ordering, or rebalancing. | deep understanding | SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=the-platform-s-shared-message-bus-kafka-pulsar-carrying-feature-events-100640) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for the streaming-ingestion backbone — self-run Kafka/Pulsar vs MSK/Confluent Cloud vs cloud-native Kinesis/PubSub — when partition-rebalance toil and broker on-call land on your data-platform team while the managed premium is a seven-figure line item? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-streaming-ingestion-backbone-se-125820) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide when a message queue or event log (Kafka/Pulsar) becomes the de facto source of truth versus staying a transport, and what does that imply for your database choices downstream? | expertise | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-a-message-queue-or-event-log-kafka-pulsar-becom-114366) |
| A bar-raiser probes your event-driven data design: 'what happens to event ordering when you scale Kafka partitions off a database's change log, and how does that break your read-model invariants?' Walk through partition-key selection, per-key ordering guarantees, and the projections that silently assume global order. | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-probes-your-event-driven-data-design-what-happens-to-even-112617) |
| Contrast a message-broker-centric data backbone (Kafka/Pulsar for CDC and events) with a durable-execution/workflow-centric one (Temporal/Step Functions coordinating multi-database writes) as the enterprise spine. For which classes of data process is each right, and what breaks if you pick wrong? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-a-message-broker-centric-data-backbone-kafka-pulsar-for-cdc-a-112609) |
| Explain the pattern trade-offs between a shared enterprise change-event bus with topic-per-table routing versus point-to-point CDC pipelines per integration. At what number of integrations does the bus's operational leverage outweigh its coupling and noisy-neighbor throughput risks? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-pattern-trade-offs-between-a-shared-enterprise-change-even-112592) |
