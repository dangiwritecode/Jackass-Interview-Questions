# CouchDB

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 5 | 5 | 5 | 5 | 5 | 5 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain why a multi-leader (multi-master) setup complicates the consistency guarantee under CAP. | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-why-a-multi-leader-multi-master-setup-complicates-the-consiste-5317) |
| Suppose your write succeeds on one replica but the partition heals later — how are conflicts resolved? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=suppose-your-write-succeeds-on-one-replica-but-the-partition-heals-lat-5286) |
| What are vector clocks and how do they help AP systems handle concurrent writes? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-are-vector-clocks-and-how-do-they-help-ap-systems-handle-concurre-5288) |
| When a partition heals, how does an AP system 'catch up' the divergent replicas? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-a-partition-heals-how-does-an-ap-system-catch-up-the-divergent-re-5311) |
| In multi-leader replication, what strategies exist to resolve write-write conflicts? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Sharding & Replication | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-multi-leader-replication-what-strategies-exist-to-resolve-write-wri-13399) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're setting policy for how teams handle write conflicts in a multi-master/active-active database. Compare last-write-wins, application-defined merge, and reject-and-retry, and mandate which is allowed for which data class. Where does LWW silently destroy data? | deep understanding | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-setting-policy-for-how-teams-handle-write-conflicts-in-a-multi--112190) |
