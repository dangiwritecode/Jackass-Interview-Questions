# Imply

**Tier:** Tier 5  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 0 | 0 | 1 | 6 | 5 | 6 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your data platform's storage cost is growing 15%/month because nobody deletes anything and lifecycle policies are inconsistent. Architect a data-tiering and retention governance system that reduces spend without violating compliance or breaking analytics. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-data-platform-s-storage-cost-is-growing-15-month-because-nobody-d-37028) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must design the data plane for a real-time analytics product that ingests events and lets users query them with sub-second latency — how do you decide between a streaming OLAP store (Druid/ClickHouse/Pinot) and a warehouse+cache and what does that lock you into? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-the-data-plane-for-a-real-time-analytics-product-that--39427) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide when it is finally worth investing in a real-time OLAP tier over the lake versus telling AIOps to tolerate 30-second query latency for another year? | deep understanding | SDE-2/3, Architect/Principal | Observability Data Lake | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-it-is-finally-worth-investing-in-a-real-time-ol-102361) |
| How would you run a proof-of-concept bake-off to choose the lake's serving engine and what objective criteria stop it from devolving into a vendor beauty contest? | deep understanding | SDE-2/3, Architect/Principal | Observability Data Lake | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-run-a-proof-of-concept-bake-off-to-choose-the-lake-s-ser-102435) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a real-time OLAP serving engine powering customer-facing analytics (buy Pinot/Druid-managed like StarTree/Imply vs self-run vs ClickHouse Cloud) when sub-second latency at high ingest and high concurrency define the whole product, not the tool? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-real-time-olap-serving-engine-pow-125845) |
| How do you capacity-plan a large stateful analytical store (Druid, Pinot, ClickHouse) whose capacity is dominated by keeping recent segments in memory for sub-second queries? Where does the memory footprint cap concurrency, and where can you tier to disk without breaking the SLA? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-capacity-plan-a-large-stateful-analytical-store-druid-pinot-125391) |
| Explain how a Druid bitmap index on a dimension speeds up high-cardinality filters and how roll-up reduces the rows an index must cover. | deep understanding | SDE-1/2, SDE-2/3 | Database Indexing & Query Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-a-druid-bitmap-index-on-a-dimension-speeds-up-high-cardina-119819) |
| Architect the enterprise real-time OLAP tier (Druid/Pinot/ClickHouse/StarRocks) serving user-facing sub-second analytics dashboards for 30 product teams. When is this warranted versus pushing product analytics onto the warehouse, and how do you stop 30 teams each standing up a snowflake cluster? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-the-enterprise-real-time-olap-tier-druid-pinot-clickhouse-st-125641) |
| Explain how you'd govern the cost of a real-time analytics store (Pinot, Druid, ClickHouse) where segment replication, retention, and always-hot memory drive spend, versus serving the same queries from a cheaper batch warehouse with higher latency. Where do you draw the freshness-versus-cost line per query class? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-the-cost-of-a-real-time-analytics-store-pinot-125939) |
| How do you decide between compute-local NVMe cache tiers, object-store hot tier, and archive for a query engine, and how does the cache-vs-tier boundary shift the economics? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-between-compute-local-nvme-cache-tiers-object-store--126733) |
