# FoundationDB

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 7 | 4 | 7 |
| Database Developer | 0 | 0 | 0 | 6 | 6 | 6 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design a C++ service to be testable for concurrency bugs? Discuss injecting a controllable clock and scheduler, deterministic simulation testing, and running under TSan/ASan in CI. | expertise | SDE-1/2, SDE-2/3 | C++ | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-c-service-to-be-testable-for-concurrency-bugs-disc-22790) |
| You must support 'give me a consistent snapshot of this counter map while writers keep updating'; how do copy-on-write structures or MVCC versions give readers isolation without blocking writers? | expertise | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-support-give-me-a-consistent-snapshot-of-this-counter-map-whi-21970) |
| You must support 'range delete' of millions of keys in a KV store without a long stop-the-world scan; how does a tombstone-and-compaction design differ algorithmically from deleting one node at a time? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-support-range-delete-of-millions-of-keys-in-a-kv-store-withou-21938) |
| Design how you'd validate correctness of your conflict resolution before shipping: what property tests, simulations, or formal methods (TLA+/deterministic sim) would you use for a multi-region write model? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-d-validate-correctness-of-your-conflict-resolution-befo-36698) |
| Design multi-region for a system where writes must be totally ordered globally (e.g. an append-only audit log or ledger). What coordination is unavoidable and how do you minimize its latency impact? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-multi-region-for-a-system-where-writes-must-be-totally-ordered--36695) |
| Explain the difference between synchronous quorum replication across 3 regions vs 2-region sync + async DR. What do the extra region and the extra hop buy or cost you at scale? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-synchronous-quorum-replication-across-3-36637) |
| How do you handle clock skew and ordering across regions when your conflict resolution or causality tracking depends on time? Compare NTP, TrueTime-style, and logical/hybrid clocks for your use case. | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-clock-skew-and-ordering-across-regions-when-your-con-36654) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you incorporate the capacity impact of moving to strong consistency or serializable isolation from read-committed — the correctness upgrade that quietly cuts throughput? | expertise | SDE-2/3, Architect/Principal | Database Capacity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-incorporate-the-capacity-impact-of-moving-to-strong-consist-115041) |
| During a partition, your Raft cluster loses quorum and goes read-only. Product demands writes continue. How do you explain the safety-vs-availability choice and what escape hatches (if any) are acceptable? | expertise | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-a-partition-your-raft-cluster-loses-quorum-and-goes-read-only-p-114737) |
| Explain how leader leases work in Raft-based databases and what happens to availability if clock skew makes a lease expire prematurely. How do you defend against clock issues? | expertise | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-leader-leases-work-in-raft-based-databases-and-what-happen-114701) |
| How do you decide when a workload should use a key-value store with secondary indexes versus a document database, given how much their capabilities have converged? | deep understanding | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-a-workload-should-use-a-key-value-store-with-se-114418) |
| You must certify a new datastore for tier-0 payments. What isolation-specific evidence (Jepsen-style, formal, or empirical) do you demand before sign-off? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-certify-a-new-datastore-for-tier-0-payments-what-isolation-sp-113653) |
| How do you evaluate whether a multi-model database that claims to serve document graph and relational in one engine actually removes your polyglot complexity or just relocates it? | expertise | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-whether-a-multi-model-database-that-claims-to-serv-114552) |
