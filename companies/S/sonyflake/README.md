# Sonyflake

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 4

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 2 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a globally-unique, roughly-ordered ID service. Compare a CP ticket-server (ZK/etcd) vs an AP Snowflake-style scheme and explain what each gives up in the CAP trade and under what failure IDs can collide or reorder. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-globally-unique-roughly-ordered-id-service-compare-a-cp-ticke-25680) |
| Walk me through designing a globally-distributed ID generation scheme that avoids cross-region coordination on the hot path while preventing collisions and preserving rough time ordering. | deep understanding | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-designing-a-globally-distributed-id-generation-scheme--36627) |
| What is a Snowflake-style ID and why is it good for sharded systems? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Sharding & Replication | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-snowflake-style-id-and-why-is-it-good-for-sharded-systems-5454) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a global unique-ID and clock strategy across regions where wall-clock skew causes ordering bugs, adjudicating between hybrid logical clocks, Snowflake-style IDs, and TrueTime-style approaches for your specific consistency needs? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-global-unique-id-and-clock-strategy-across-regi-52024) |
