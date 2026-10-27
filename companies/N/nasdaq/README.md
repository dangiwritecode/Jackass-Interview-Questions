# Nasdaq

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 6 | 6 | 6 |
| Database Developer | 0 | 0 | 0 | 5 | 5 | 5 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you set an availability and capacity strategy for a stock-trading platform where the load is spiky at market open, the correctness bar is absolute, and even seconds of downtime during a crash cost customers real money and you regulatory scrutiny? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-an-availability-and-capacity-strategy-for-a-stock-tradi-32159) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you set the availability and correctness strategy for a stock-trading platform where load spikes at market open, downtime during a crash costs customers real money, and regulators are watching? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-the-availability-and-correctness-strategy-for-a-stoc-38780) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you set the availability and correctness strategy for a stock-trading or exchange platform where load spikes at market open, downtime during a crash costs customers real money, and regulators are watching every second of an outage? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-the-availability-and-correctness-strategy-for-a-stoc-52111) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A team needs to restore 500TB from Deep Archive by tomorrow for a regulator. Walk me through cost, throughput, and how you'd sequence it under the deadline. | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-team-needs-to-restore-500tb-from-deep-archive-by-tomorrow-for-a-regu-126779) |
| Explain provisioned-capacity vs expedited vs bulk Glacier retrieval and when you'd pay for provisioned capacity to guarantee restore throughput. | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-provisioned-capacity-vs-expedited-vs-bulk-glacier-retrieval-an-126781) |
| How do you handle the operational risk that a format or codec used in archived data may be unreadable years later? What's your long-term-archival readability strategy? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-operational-risk-that-a-format-or-codec-used-in--126773) |
| How do you reconcile aggressive cold-tiering with SLA-bound restore latency for compliance queries, litigation holds, or audit requests? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reconcile-aggressive-cold-tiering-with-sla-bound-restore-la-126720) |
| How does S3 Object Lock (governance vs compliance mode) interact with lifecycle transitions and expirations, and how do you design around WORM requirements? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-s3-object-lock-governance-vs-compliance-mode-interact-with-li-126741) |
| When is tape (physical or virtual) still the right cold tier over Glacier Deep Archive, and how would you defend that to a cloud-first executive? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-is-tape-physical-or-virtual-still-the-right-cold-tier-over-glacie-126798) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A regulator requires proof that once a trade is confirmed it is immutable and totally ordered with all prior trades. Explain how you architect an append-only consensus log as the system of record, and what caveats (leader-term boundaries, uncommitted tail) you must disclose. | expertise | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-regulator-requires-proof-that-once-a-trade-is-confirmed-it-is-immuta-112203) |
| How do you decide RPO for a database write where losing the last N minutes is legally different from losing it operationally (a recorded trade vs a profile edit)? Walk the regulatory lens over the technical one. | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-rpo-for-a-database-write-where-losing-the-last-n-min-112937) |
| Your synchronous cross-region commit for RPO=0 on a write-heavy ledger pushes p99 write latency past the SLO. How do you adjudicate the RPO-versus-latency trade for a financial system that can't lose a recorded trade? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-synchronous-cross-region-commit-for-rpo-0-on-a-write-heavy-ledger-112855) |
| You lead a migration off a legacy system that relied on dirty reads for a real-time dashboard. How do you deliver the same freshness without READ UNCOMMITTED's hazards? | deep understanding | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-lead-a-migration-off-a-legacy-system-that-relied-on-dirty-reads-fo-113668) |
| You're asked to reduce serialization-failure retries that are inflating tail latency in a trading system. Walk through the design levers, ordered by blast radius, that you'd pull. | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-reduce-serialization-failure-retries-that-are-inflatin-113660) |
