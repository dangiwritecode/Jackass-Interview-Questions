# Turso

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 8

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 7 | 7 | 7 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You are asked to evaluate whether to adopt an edge-database (data replicated to the edge) instead of an edge cache. Argue how the correctness and invalidation stories differ, and when a replicated edge store beats a cache at the edge. | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-evaluate-whether-to-adopt-an-edge-database-data-repli-38582) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect an edge-database tier (Cloudflare D1 / Turso / regional SQLite replicas) so thousands of edge locations serve fast local reads yet a write invariant remains globally CP, and where does the write path become the availability bottleneck? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-edge-database-tier-cloudflare-d1-turso-regiona-111559) |
| Explain how you'd design the durability + consistency contract for a database on cloud object storage (disaggregated storage, e.g., Neon/Aurora-style) where the compute is stateless. Where does consensus or quorum now live, and how does a compute restart get a consistent view? | expertise | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-the-durability-consistency-contract-for-a-dat-112226) |
| Explain how you'd design HA for a serverless/autoscaling database where compute nodes come and go. How does elastic compute interact with quorum, leader election, and connection stability? | deep understanding | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-ha-for-a-serverless-autoscaling-database-wher-114726) |
| Explain how you'd handle HA for a database at the edge (hundreds of PoPs) where full quorum is impractical. What consistency and failover model works for edge-replicated data? | expertise | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-handle-ha-for-a-database-at-the-edge-hundreds-of-pop-114735) |
| What's your rubric for when to trust a young database (< 3 years, small team) in production, and what mitigations do you put around that bet to make it reversible? | expertise | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-rubric-for-when-to-trust-a-young-database-3-years-small-te-114411) |
| When would you choose an embedded/edge database (SQLite/RocksDB/DuckDB) as part of the architecture, and how does that change the central datastore selection? | deep understanding | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-an-embedded-edge-database-sqlite-rocksdb-duckdb--114381) |
| How do you evaluate whether your team's move to a serverless database (Neon/Aurora Serverless) changes the isolation and connection-scaling assumptions your transactions were built on? | deep understanding | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-whether-your-team-s-move-to-a-serverless-database--113731) |
