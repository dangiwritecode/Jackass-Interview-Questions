# ArangoDB

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 11 | 11 | 11 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Tell me about a time you had to lead the org's decision on how much to invest in a graph/relationship data layer versus modeling relationships in existing stores. How did you evaluate whether the problem was truly graph-shaped? | deep understanding | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=tell-me-about-a-time-you-had-to-lead-the-org-s-decision-on-how-much-to-40510) |
| How do you migrate a monolith to a new datastore paradigm (relational to document, or SQL to graph) under strangler fig when the access patterns must change too? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-migrate-a-monolith-to-a-new-datastore-paradigm-relational-t-40972) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect caching for a multi-model database (document, graph, relational in one engine) so a read migrating from the relational to the graph model never gets served from a cache keyed on the old model? | deep understanding | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-caching-for-a-multi-model-database-document-gr-111466) |
| How do you decide when a workload should abandon relational entirely and move to Cosmos DB's document or graph API — and how do you migrate deeply relational joins into a denormalized model? | expertise | SDE-2/3, Architect/Principal | Cloud Database Strategy (RDS/Aurora/Cosmos) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-a-workload-should-abandon-relational-entirely-a-115227) |
| How do you architect HA for a graph database or a specialized store that lacks mature native replication? What compensating patterns (dual-write, CDC replay, rebuild-from-source) do you accept? | deep understanding | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-ha-for-a-graph-database-or-a-specialized-store-th-114711) |
| How do you architect access control for a multi-model database (document + relational + search) so one query interface can't be used to sidestep another's permissions? | expertise | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-access-control-for-a-multi-model-database-documen-114107) |
| How do you decide when a workload's relationships are complex enough that a native graph database beats both relational joins and a document model? Where do graph databases fail to scale? | deep understanding | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-a-workload-s-relationships-are-complex-enough-t-114429) |
| What is your strategy for evaluating multi-model databases versus best-of-breed specialized stores for a platform with document, graph, and relational needs? | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-strategy-for-evaluating-multi-model-databases-versus-best-115373) |
| Design DR for a graph database where value lives in the edges and losing a fraction of relationships silently corrupts the graph — how does that shift your RPO thinking from row-count to integrity? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-dr-for-a-graph-database-where-value-lives-in-the-edges-and-losi-112870) |
| How do you evaluate whether a multi-model database that claims to serve document graph and relational in one engine actually removes your polyglot complexity or just relocates it? | expertise | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-whether-a-multi-model-database-that-claims-to-serv-114552) |
| How do you weigh a graph database against modeling relationships in relational recursive CTEs or a document store's embedded refs for a deeply-connected domain? | deep understanding | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-weigh-a-graph-database-against-modeling-relationships-in-re-114597) |
| What's your strategy for keeping a graph store and a relational store in sync when relationships are derived from relational rows that change frequently? | expertise | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-keeping-a-graph-store-and-a-relational-store--114626) |
| How would you handle read/write splitting when a graph or recursive query on a replica sees a partially-replicated subtree, producing incorrect traversals? | expertise | SDE-2/3, Architect/Principal | Read/Write Splitting | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-read-write-splitting-when-a-graph-or-recursive-qu-115506) |
