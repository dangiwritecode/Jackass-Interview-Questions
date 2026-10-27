# Instaclustr

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 7 | 7 | 7 | 7 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 1 | 1 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A broker's disk hit 95% and it started throttling. Walk through your immediate mitigation and the longer-term retention or tiered-storage change you'd make. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-broker-s-disk-hit-95-and-it-started-throttling-walk-through-your-imm-24857) |
| A partition reassignment during a broker addition saturated replication traffic and starved live producers. How do you throttle and stage such a move safely? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-partition-reassignment-during-a-broker-addition-saturated-replicatio-24921) |
| A partition's leader keeps flapping between two brokers under load. How would you diagnose whether it's ISR churn, GC pauses, or network, and what's your fix? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-partition-s-leader-keeps-flapping-between-two-brokers-under-load-how-24899) |
| Explain how KRaft changes your operational runbook for controller failover, and what new failure modes the metadata quorum introduces versus ZooKeeper. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-kraft-changes-your-operational-runbook-for-controller-fail-24915) |
| How do you reason about the memory footprint of a broker under a high partition count, and what happens to failover time as partitions grow into the hundreds of thousands? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reason-about-the-memory-footprint-of-a-broker-under-a-high--24840) |
| How would you throttle a single misbehaving client that is saturating broker network and causing latency for everyone else, without redeploying that client? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-throttle-a-single-misbehaving-client-that-is-saturating--24888) |
| Your compacted topic keeps growing despite compaction being enabled. What operational reasons prevent compaction from reclaiming space and how do you fix each? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-compacted-topic-keeps-growing-despite-compaction-being-enabled-wh-24871) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org is deciding whether to run its search/analytics stack (Elasticsearch/OpenSearch) on Kubernetes operators versus managed services. As principal, walk through the framework: shard-rebalance-during-node-loss risk, storage guarantees, upgrade pain, and the failure mode that would flip your recommendation, plus how you'd pilot it. | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-is-deciding-whether-to-run-its-search-analytics-stack-elastic-39086) |
| Your org wants to run Kafka/Cassandra on Kubernetes via operators, and a staff engineer warns it'll be a snowflake per team. As principal, how would you set a fleet standard for stateful clustering systems (which operators, storage guarantees, failover SLAs) and stop each team operating a bespoke stateful stack? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-to-run-kafka-cassandra-on-kubernetes-via-operators-and--39046) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Kafka now supports tiered storage to object stores. Walk me through how you'd design retention and tiering so brokers offload cold segments without hurting consumer catch-up throughput. | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=kafka-now-supports-tiered-storage-to-object-stores-walk-me-through-how-126732) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You run a Postgres primary with a synchronous standby using synchronous_commit=remote_apply; a partition isolates the standby. Explain why writes stall and how that maps you into the CP corner. | deep understanding | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-run-a-postgres-primary-with-a-synchronous-standby-using-synchronou-107432) |
| Explain the read-consistency guarantees of PostgreSQL synchronous replication with quorum_commit vs. Patroni-orchestrated failover via etcd. Where can a promoted standby lose an acked write, and how do you configure to eliminate that at a modeling level? | deep understanding | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-read-consistency-guarantees-of-postgresql-synchronous-repl-112162) |
