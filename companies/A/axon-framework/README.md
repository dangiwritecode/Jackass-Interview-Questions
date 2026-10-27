# Axon-Framework

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 5 | 5 | 5 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect resilience for an event-sourced platform so you can recover from a corrupted projection without downtime across many consumers? Discuss rebuilds, snapshots, dual-read cutover, and how you bound the rebuild's load impact on the live system. | expertise | SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-resilience-for-an-event-sourced-platform-so-you-c-52910) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide whether caching belongs at the CQRS read model or in a separate cache in front of it, and when is a cache redundant with a well-designed, already-denormalized read model? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-caching-belongs-at-the-cqrs-read-model-or-in-111506) |
| For a database whose recovery requires replaying months of events or CDC to rebuild state, RTO is dominated by replay throughput. How do you architect snapshots plus incremental replay to bound the RTO? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-a-database-whose-recovery-requires-replaying-months-of-events-or-c-112914) |
| How do you define RPO for an event-sourced datastore where state is a fold over an immutable log — is RPO simply the log's durability, and where does that reasoning quietly break for downstream projections? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-define-rpo-for-an-event-sourced-datastore-where-state-is-a--112862) |
| How do you handle in-flight distributed transactions and sagas across a database failover so a cut-over mid-workflow leaves no partial or duplicated business state? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-in-flight-distributed-transactions-and-sagas-across--112874) |
| How do you set differentiated RTO/RPO for the read path versus the write path of a CQRS database system, and how do you communicate that asymmetry so product owners don't assume symmetric protection? | deep understanding | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-differentiated-rto-rpo-for-the-read-path-versus-the-wri-112883) |
