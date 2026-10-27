# StarTree

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 4 | 9 | 5 | 9 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must design the data plane for a real-time analytics product that ingests events and lets users query them with sub-second latency — how do you decide between a streaming OLAP store (Druid/ClickHouse/Pinot) and a warehouse+cache and what does that lock you into? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-the-data-plane-for-a-real-time-analytics-product-that--39427) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you govern the trade-off between real-time streaming analytics and cheaper batch analysis of telemetry across clouds so critical detection stays fast without runaway compute cost? | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud Governance Frameworks | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-the-trade-off-between-real-time-streaming-analyti-100881) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a real-time OLAP serving engine powering customer-facing analytics (buy Pinot/Druid-managed like StarTree/Imply vs self-run vs ClickHouse Cloud) when sub-second latency at high ingest and high concurrency define the whole product, not the tool? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-real-time-olap-serving-engine-pow-125845) |
| In Apache Pinot, how do you choose among sorted, inverted, star-tree, and range indexes for a given query pattern in a real-time analytics table? | expertise | SDE-1/2, SDE-2/3 | Database Indexing & Query Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-apache-pinot-how-do-you-choose-among-sorted-inverted-star-tree-and--119818) |
| Architect the enterprise real-time OLAP tier (Druid/Pinot/ClickHouse/StarRocks) serving user-facing sub-second analytics dashboards for 30 product teams. When is this warranted versus pushing product analytics onto the warehouse, and how do you stop 30 teams each standing up a snowflake cluster? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-the-enterprise-real-time-olap-tier-druid-pinot-clickhouse-st-125641) |
| Explain how you'd govern the cost of a real-time analytics store (Pinot, Druid, ClickHouse) where segment replication, retention, and always-hot memory drive spend, versus serving the same queries from a cheaper batch warehouse with higher latency. Where do you draw the freshness-versus-cost line per query class? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-the-cost-of-a-real-time-analytics-store-pinot-125939) |
| A near-real-time OLAP store (Pinot/Druid) is fed from the same Kafka topic as the OLTP consumer — how do you keep the two views consistent enough that users don't see contradictions? | expertise | SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-near-real-time-olap-store-pinot-druid-is-fed-from-the-same-kafka-top-123007) |
| A stakeholder wants sub-second p99 on a warehouse aggregation over 10B rows — explain why that's fundamentally an OLTP-shaped ask and what serving layer (Druid/Pinot/pre-agg cube) you'd introduce. | expertise | SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-stakeholder-wants-sub-second-p99-on-a-warehouse-aggregation-over-10b-122974) |
| Explain when a lambda-style architecture (batch OLAP + speed layer) is justified over just streaming everything into a real-time OLAP store, given operational cost. | expertise | SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-when-a-lambda-style-architecture-batch-olap-speed-layer-is-jus-122981) |
| How do you decide where compute-storage separation helps versus hurts in a real-time OLAP store, given the latency cost of pulling cold data from object storage? | expertise | SDE-2/3, Architect/Principal | Real-time Analytics Architecture | Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-where-compute-storage-separation-helps-versus-hurts--127604) |
| When would you choose ClickHouse over Apache Pinot over Apache Druid for a real-time OLAP serving layer, and what query patterns break each of them? | expertise | SDE-2/3, Architect/Principal | Real-time Analytics Architecture | Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-clickhouse-over-apache-pinot-over-apache-druid-f-127518) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide the cost-optimal storage engine and compression codec for a column-store analytical table — dictionary vs run-length vs delta encoding — where aggressive compression cuts scan cost but raises CPU on write? Where's the break-even? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-cost-optimal-storage-engine-and-compression-code-112303) |
| How do you decide when to precompute and materialize aggregations/rollups versus computing them on demand, at 10k analytical queries/day each scanning 2TB? When does the storage-and-refresh cost of a materialized view beat repeated scan cost? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-to-precompute-and-materialize-aggregations-roll-112305) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the boundary between the feature store's online serving layer and a purpose-built OLAP store (Pinot/Druid) when some ML features are also real-time analytics aggregates? When do you refuse to run both? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-boundary-between-the-feature-store-s-online-s-69678) |
