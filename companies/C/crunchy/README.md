# Crunchy

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 4 | 4 | 6 | 6 | 6 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect the platform to make stateful data infrastructure (databases, streaming, caches) a paved-road capability with backup, failover, and schema governance built in, without the platform team becoming an accidental DBA org for the whole company? | deep understanding | SDE-2/3, Architect/Principal | Platform Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-platform-to-make-stateful-data-infrastruct-54264) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A cross-team data platform you sponsored — a self-service database-provisioning portal — is failing to gain adoption and sunk-cost pressure is real. How do you decide whether to double down, pivot, or kill it, and how do you communicate that across the teams involved? | deep understanding | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-cross-team-data-platform-you-sponsored-a-self-service-database-provi-113210) |
| Explain how PostgreSQL streaming replication works using WAL shipping and the walsender/walreceiver processes. | deep understanding | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Database Replication (Master-Slave) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-postgresql-streaming-replication-works-using-wal-shipping--110457) |
| How do PostgreSQL replication slots prevent WAL removal, and what is the risk of an inactive slot filling the master's disk? | deep understanding | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Database Replication (Master-Slave) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-postgresql-replication-slots-prevent-wal-removal-and-what-is-th-110479) |
| What are hot standby conflicts (query cancellation due to vacuum) on a PostgreSQL replica, and how do hot_standby_feedback and max_standby_streaming_delay address them? | expertise | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Database Replication (Master-Slave) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-are-hot-standby-conflicts-query-cancellation-due-to-vacuum-on-a-p-110481) |
| A Patroni-managed Postgres cluster failed over and lost a few committed-looking writes. Explain how synchronous_commit and synchronous_standby_names settings determine whether a promoted replica can lose data, and how you'd tune for zero-RPO. | expertise | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-patroni-managed-postgres-cluster-failed-over-and-lost-a-few-committe-107903) |
| Explain how a Patroni/etcd-managed Postgres HA cluster prevents split-brain during a leader promotion, exactly what role the DCS plays, and the failure mode when the DCS itself partitions. What fencing keeps a demoted old primary from accepting writes? | deep understanding | SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-a-patroni-etcd-managed-postgres-ha-cluster-prevents-split--112066) |
