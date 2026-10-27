# TigerBeetle

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 8

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 2 | 2 | 7 | 7 | 7 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design how you'd validate correctness of your conflict resolution before shipping: what property tests, simulations, or formal methods (TLA+/deterministic sim) would you use for a multi-region write model? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-d-validate-correctness-of-your-conflict-resolution-befo-36698) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What criteria would lead you to choose a specialized ledger database vendor over building double-entry accounting on a relational store? | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-criteria-would-lead-you-to-choose-a-specialized-ledger-database-v-115441) |
| Give an example where two transactions each read then write disjoint rows but the combined outcome violates a business invariant. Which level catches it? | deep understanding | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=give-an-example-where-two-transactions-each-read-then-write-disjoint-r-110268) |
| How do you architect isolation for a fintech ledger where double-entry invariants must hold, but the volume forbids serializing every entry through one lock? What's the partition key? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-isolation-for-a-fintech-ledger-where-double-entry-113721) |
| How does snapshot isolation choose which committed version a transaction sees? What role does the transaction's start timestamp play? | deep understanding | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-snapshot-isolation-choose-which-committed-version-a-transacti-110257) |
| How would you evaluate whether moving a hot aggregate (like a running balance) out of SQL into a single-writer partitioned log removes the isolation bottleneck entirely? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-whether-moving-a-hot-aggregate-like-a-running-b-113687) |
| You must certify a new datastore for tier-0 payments. What isolation-specific evidence (Jepsen-style, formal, or empirical) do you demand before sign-off? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-certify-a-new-datastore-for-tier-0-payments-what-isolation-sp-113653) |
| How would you architect a ledger-plus-projections design where an immutable financial ledger is the truth and everything else is a derived polyglot view? | expertise | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-ledger-plus-projections-design-where-an-immu-114635) |
