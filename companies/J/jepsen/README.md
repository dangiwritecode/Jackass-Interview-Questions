# Jepsen

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 4 | 4 | 4 | 4 |
| Database Developer | 0 | 1 | 1 | 6 | 6 | 6 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you write a Jepsen-style test to prove your service is actually linearizable (or actually eventually consistent) rather than trusting its CAP label from the docs? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-write-a-jepsen-style-test-to-prove-your-service-is-actua-25687) |
| Explain how you'd test that your automatic failover actually promotes a replica within SLO under a real primary crash, including how you inject the failure and what you assert. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Sharding & Replication | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-test-that-your-automatic-failover-actually-promotes--25877) |
| How would you test a sharded, replicated system's failover behavior before it hits production? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Sharding & Replication | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-test-a-sharded-replicated-system-s-failover-behavior-bef-13464) |
| What kinds of bugs does Jepsen-style testing reveal in replicated databases, and why does it matter? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Sharding & Replication | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-kinds-of-bugs-does-jepsen-style-testing-reveal-in-replicated-data-13465) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Jepsen has found consistency bugs in databases that claimed strong guarantees. As a DB developer, how do you verify your store's CAP label instead of trusting the docs? | deep understanding | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=jepsen-has-found-consistency-bugs-in-databases-that-claimed-strong-gua-107515) |
| You're asked to certify in production that your database is actually serializable, not just configured to be. Design the continuous Elle/Jepsen-style verification harness that runs against live-like traffic, the invariants you assert, and how you feed findings into the release gate. | expertise | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-certify-in-production-that-your-database-is-actually-s-112209) |
| A JEPSEN-style report finds your candidate database violates its claimed serializable guarantee under partition. Walk me through how you'd interpret it and whether it's a blocker. | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-jepsen-style-report-finds-your-candidate-database-violates-its-claim-113696) |
| You must certify a new datastore for tier-0 payments. What isolation-specific evidence (Jepsen-style, formal, or empirical) do you demand before sign-off? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-certify-a-new-datastore-for-tier-0-payments-what-isolation-sp-113653) |
| Explain how you'd verify, as a continuous property test, that your geo-replicated database never violates a business invariant (e.g. account balance never negative) under injected partitions and reordered replication. What role do TLA+, Jepsen-style tests, or deterministic sim play? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-verify-as-a-continuous-property-test-that-your-geo-r-112823) |
| How do you approach testing a NewSQL system for correctness under partition/failure — Jepsen-style testing, chaos engineering, and clock-skew injection — and what would convince you it's production-ready? | expertise | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-testing-a-newsql-system-for-correctness-under-part-114505) |
