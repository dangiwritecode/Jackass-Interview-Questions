# Commvault

**Tier:** Tier 2  |  **Business domain:** SaaS/Data  |  **Questions:** 25

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 5 | 5 | 5 |
| Data Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 8 | 8 | 8 |
| Data Structures & Algorithms (all profiles) | 10 | 10 | 10 | 10 | 10 | 10 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design an org-wide backup, retention, and immutability strategy on Azure that survives a ransomware event, and how do you prove recoverability to auditors? | expertise | SDE-2/3, Architect/Principal | Azure | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-org-wide-backup-retention-and-immutability-strate-54597) |
| How do you keep backups themselves resilient against ransomware and insider threats, and what does a defensible immutable-backup and 3-2-1-1-0 strategy look like at enterprise scale? | expertise | SDE-2/3, Architect/Principal | Business Continuity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-backups-themselves-resilient-against-ransomware-and-in-56950) |
| How would you prove that your backups are actually restorable, and what continuous restore-verification would you build so you never discover a bad backup mid-disaster? | deep understanding | SDE-2/3, Architect/Principal | Business Continuity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-prove-that-your-backups-are-actually-restorable-and-what-56951) |
| What's your approach to migrating disaster recovery and backup workloads themselves, given they must remain functional throughout the migration? | deep understanding | SDE-2/3, Architect/Principal | Cloud Migration Strategy (6 Rs) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-migrating-disaster-recovery-and-backup-workloa-56573) |
| You must make backups verifiable across many teams so 'we have Velero' actually means 'we can recover'. How would you architect a regularly-test-restored backup program, assign ownership of proving each service is recoverable, and surface a service whose last test-restore silently failed? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-make-backups-verifiable-across-many-teams-so-we-have-velero-a-52178) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Backups and disaster-recovery copies also contain a subject's data; how do you reconcile immutable backup retention with an erasure obligation? | expertise | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=backups-and-disaster-recovery-copies-also-contain-a-subject-s-data-how-127341) |
| How do backup/snapshot lifecycle policies (RDS/EBS/Dynamo backups, Iceberg time-travel) intersect with data tiering, and where does one undo the other's savings? | deep understanding | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-backup-snapshot-lifecycle-policies-rds-ebs-dynamo-backups-icebe-126767) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the handling of backup catalog metadata itself, given that if you lose the catalog you may have valid backups you can no longer find or interpret? | deep understanding | SDE-2/3, Architect/Principal | Backup & Recovery | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-handling-of-backup-catalog-metadata-itself-gi-114196) |
| How do you architect the trade-off between deduplicated backup storage that saves cost and the risk that a single corrupted dedup block can damage many restore points at once? | deep understanding | SDE-2/3, Architect/Principal | Backup & Recovery | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-trade-off-between-deduplicated-backup-storage-114228) |
| How does the CAP posture of a database change your backup/PITR strategy — specifically why an AP store's 'point in time' is ambiguous across divergent replicas, and how you define a recoverable, consistent snapshot despite that ambiguity? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-the-cap-posture-of-a-database-change-your-backup-pitr-strateg-111597) |
| How do you validate that a restored backup is still decryptable years later — design key-lifecycle governance so retired keys needed for old backups aren't destroyed prematurely? | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-validate-that-a-restored-backup-is-still-decryptable-years--115295) |
| How would you architect protection so a compromised backup-and-restore pipeline (a common ransomware and exfil vector) cannot become the weakest link in your data security? | expertise | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-protection-so-a-compromised-backup-and-restore-114121) |
| Design a ransomware-recovery architecture for a database where you must assume backups themselves may be encrypted or deleted — what does immutable, air-gapped, verifiable recovery look like at petabyte scale? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-ransomware-recovery-architecture-for-a-database-where-you-mus-112886) |
| How do you protect database backups from a compromised credential or attacker who tries to delete them — walk me through immutable object lock, separate-account custody, and air-gapped copies for a petabyte estate. | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-protect-database-backups-from-a-compromised-credential-or-a-112858) |
| How do you validate a database ransomware-recovery path when you can't safely detonate real ransomware in prod — what's the test harness that proves the air-gapped copy restores without breaking the air gap? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-validate-a-database-ransomware-recovery-path-when-you-can-t-112887) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Add Two Numbers Stored as Reversed Digit Linked Lists | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Linked List, Math, Simulation, Two Pointers | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=add-two-numbers-stored-as-reversed-digit-linked-lists-d2) |
| Count of Longest Strictly Increasing Subsequences | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Indexed Tree, Counting, Dynamic Programming, Longest Increasing Subsequence, Segment Tree | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-of-longest-strictly-increasing-subsequences-d658) |
| Count Substrings That Contain Every Vowel and Nothing Else | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Hash Table, Sliding Window, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-substrings-that-contain-every-vowel-and-nothing-else-d1948) |
| Counting Mutually Unreachable Vertex Pairs | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Breadth-First Search, Combinatorics, Connected Components, Depth-First Search, Disjoint Set Union, Graph, Union Find | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=counting-mutually-unreachable-vertex-pairs-d2180) |
| Counting Ways to Decode a Numeric Message | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | 1-D DP, Dynamic Programming, Recursion with Memoization, String | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=counting-ways-to-decode-a-numeric-message-d91) |
| Fewest Growing Jumps to Land Exactly on a Marker | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Binary Search, Greedy, Math, Number Theory, Parity | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=fewest-growing-jumps-to-land-exactly-on-a-marker-d739) |
| Length of the Longest Strictly Increasing Subsequence | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Dynamic Programming, Greedy, Patience Sorting | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=length-of-the-longest-strictly-increasing-subsequence-d300) |
| Locate Any Peak Index in an Array | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Divide and Conquer | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=locate-any-peak-index-in-an-array-d162) |
| Reverse a Singly Linked List in Consecutive Blocks of Size K | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | In-place Reversal, Linked List, Recursion, Two Pointers | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=reverse-a-singly-linked-list-in-consecutive-blocks-of-size-k-d25) |
| Settling Pebbles in a Rotated Cabinet | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Gravity Simulation, Matrix, Simulation, Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=settling-pebbles-in-a-rotated-cabinet-d1766) |
