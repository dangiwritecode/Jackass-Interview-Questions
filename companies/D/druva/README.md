# Druva

**Tier:** Tier 3  |  **Business domain:** SaaS/Cloud  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 3 | 3 | 4 | 4 | 4 | 4 |
| Fullstack | 1 | 1 | 1 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 4 | 4 | 4 | 4 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Structures & Algorithms (all profiles) | 1 | 1 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how S3 server-side encryption with SSE-S3, SSE-KMS, and SSE-C differ. | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-s3-server-side-encryption-with-sse-s3-sse-kms-and-sse-c-di-14576) |
| What is IMDSv2 and why did AWS introduce it over IMDSv1? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-imdsv2-and-why-did-aws-introduce-it-over-imdsv1-14574) |
| Design a data-deduplication layer for a backup/storage service so identical file chunks are stored once — how do you chunk hash and index at scale and handle hash-collision and reference counting for deletes? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-deduplication-layer-for-a-backup-storage-service-so-iden-28417) |
| Design a file system abstraction with directories and files. How do you compute total size? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-file-system-abstraction-with-directories-and-files-how-do-you-8958) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a file system abstraction with directories and files. How do you compute total size? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-file-system-abstraction-with-directories-and-files-how-do-you-8958) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you continuously verify that backups are encrypted and restorable in a way that satisfies both your DR requirement and a SOC2 availability control? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-continuously-verify-that-backups-are-encrypted-and-restorab-47952) |
| How do you handle DR replication of PII to a second region when that region is a different legal jurisdiction — how do you keep RTO/RPO targets while staying residency-compliant? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-dr-replication-of-pii-to-a-second-region-when-that-r-47992) |
| Walk me through how you'd prove backups are actually restorable within RTO for a SOC2 availability control — what test cadence and evidence would satisfy an auditor? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-prove-backups-are-actually-restorable-within-47999) |
| Your GDPR data-residency requirement says EU customer data cannot leave the EU — how do you enforce that at the AWS account/region level so a misconfigured cross-region replication can't leak it? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-gdpr-data-residency-requirement-says-eu-customer-data-cannot-leav-47942) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do backup/snapshot lifecycle policies (RDS/EBS/Dynamo backups, Iceberg time-travel) intersect with data tiering, and where does one undo the other's savings? | deep understanding | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-backup-snapshot-lifecycle-policies-rds-ebs-dynamo-backups-icebe-126767) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You inherited a database platform where each shard runs an independent Raft group but backups are taken per-node. Explain why that produces an inconsistent restore across shards and design a consensus-aware, transactionally-consistent distributed backup. | expertise | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherited-a-database-platform-where-each-shard-runs-an-independent-112155) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Largest Array Sum After Exactly K Sign Flips | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Priority Queue, Sorting | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=largest-array-sum-after-exactly-k-sign-flips-d990) |
