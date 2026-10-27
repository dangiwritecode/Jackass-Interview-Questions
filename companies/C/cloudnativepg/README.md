# CloudNativePG

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Database Developer | 0 | 0 | 0 | 6 | 6 | 6 |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a backup + point-in-time-recovery + DR-orchestration layer for stateful databases (self-run pgBackRest/wal-g + scripts vs managed backup vs Kasten/Portworx on K8s) when RPO/RTO guarantees and restore-test automation are the real deliverable? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-backup-point-in-time-recovery-dr--113015) |
| How do you weigh multi-cloud portability against best-of-breed managed databases when a build-vs-buy choice would deepen single-cloud lock-in (Aurora/Spanner/Cosmos are not portable) — and is a self-hosted-on-K8s Postgres worth the portability tax? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-weigh-multi-cloud-portability-against-best-of-breed-managed-112986) |
| Explain how you'd set up automatic re-provisioning of a failed node back into the cluster (rebuild/reseed) without manual intervention, and the guardrails against reseeding from a corrupt source. | deep understanding | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-set-up-automatic-re-provisioning-of-a-failed-node-ba-114714) |
| How do you decide between database-native HA (e.g. Aurora multi-AZ), operator-managed HA on Kubernetes, and self-managed VMs? What governs that build-vs-buy call across a portfolio? | expertise | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-between-database-native-ha-e-g-aurora-multi-az-opera-114655) |
| How do you keep the failover automation's config (topology, priorities, thresholds) in sync with reality when teams routinely add/remove replicas? Describe the GitOps/reconciliation approach. | deep understanding | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-the-failover-automation-s-config-topology-priorities-t-114730) |
| Walk through the failover sequence for a Kubernetes-hosted Postgres cluster using an operator. What are the failure modes of running stateful HA databases on K8s that people underestimate? | deep understanding | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-through-the-failover-sequence-for-a-kubernetes-hosted-postgres-cl-114656) |
