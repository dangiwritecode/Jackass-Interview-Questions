# Pure Storage

**Tier:** Tier 2  |  **Business domain:** Storage  |  **Questions:** 19

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 0 | 1 |
| DevOps | 0 | 0 | 6 | 7 | 3 | 7 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Structures & Algorithms (all profiles) | 7 | 7 | 7 | 7 | 7 | 7 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you use fallocate and sparse files to pre-allocate space for a large database file on Linux, and what's the risk of thin-provisioned storage lying to you about available space? | deep understanding | SDE-1/2, SDE-2/3 | Linux | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-fallocate-and-sparse-files-to-pre-allocate-space-for-26640) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd decide the org-wide policy on committed vs on-demand for storage (not compute) — reserved capacity, provisioned IOPS commitments, minimum-retention tiers. Storage commitments are stickier than compute; how does that change your risk posture? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-decide-the-org-wide-policy-on-committed-vs-on-demand-52957) |
| A PVC using a network-attached volume shows 5x the IOPS latency of the same volume mounted on a bare VM. How would you isolate whether it's the CSI driver, the StorageClass parameters, or node attach limits? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-pvc-using-a-network-attached-volume-shows-5x-the-iops-latency-of-the-45923) |
| Your cluster's default StorageClass provisions Delete-reclaim volumes and a deleted PVC took real data with it. How would you set reclaim policy and PVC retention so an accidental delete is recoverable? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-cluster-s-default-storageclass-provisions-delete-reclaim-volumes--45975) |
| During an incident you find a process stuck in D state blocked on NFS — why is it uninterruptible, why won't kill -9 work, and what are your options? | deep understanding | SDE-1/2, SDE-2/3 | Operating Systems | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-an-incident-you-find-a-process-stuck-in-d-state-blocked-on-nfs--44936) |
| A datastore latency spike is causing VM I/O timeouts. Walk through diagnosing whether it's the storage array, the vSwitch, or overcommitted queues. | deep understanding | SDE-1/2, SDE-2/3 | Virtualization | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-datastore-latency-spike-is-causing-vm-i-o-timeouts-walk-through-diag-49572) |
| How do you decide thin versus thick provisioning for virtual disks in a storage cluster and what's the failure mode of over-thin-provisioning? | intermediate experience | SDE-1/2, SDE-2/3 | Virtualization | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-thin-versus-thick-provisioning-for-virtual-disks-in--49541) |
| Your VMs report high I/O wait but the SAN looks fine. How could the virtual disk queue depth or adapter settings be the bottleneck? | deep understanding | SDE-1/2, SDE-2/3 | Virtualization | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-vms-report-high-i-o-wait-but-the-san-looks-fine-how-could-the-vir-49616) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the trade-off between deduplicated backup storage that saves cost and the risk that a single corrupted dedup block can damage many restore points at once? | deep understanding | SDE-2/3, Architect/Principal | Backup & Recovery | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-trade-off-between-deduplicated-backup-storage-114228) |
| How would you decide whether to invest in near-instant recovery via storage-array snapshots and clones versus classic restore, for your highest-value databases? | deep understanding | SDE-2/3, Architect/Principal | Backup & Recovery | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-to-invest-in-near-instant-recovery-via-st-114236) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a checkpoint storage and retrieval subsystem for multi-terabyte sharded checkpoints so that checkpoint I/O never becomes the throughput ceiling for a 2000-GPU job? | expertise | SDE-2/3, Architect/Principal | Distributed Training (Data/Model Parallelism) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-checkpoint-storage-and-retrieval-subsystem-for--70687) |
| How do you plan storage and data-pipeline capacity so GPUs aren't starved waiting on I/O during training? | expertise | SDE-2/3, Architect/Principal | GPU Fleet & Capacity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-storage-and-data-pipeline-capacity-so-gpus-aren-t-star-71950) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Constant-Time Set with Uniform Random Sampling | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Design, Hash Table, Randomized, Swap-Remove | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=constant-time-set-with-uniform-random-sampling-d380) |
| Counting Axis-Aligned Squares from a Point Stream | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Counting, Design, Geometry, Hash Table, Streaming | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=counting-axis-aligned-squares-from-a-point-stream-d1903) |
| Counting Palindromic Substrings | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Dynamic Programming, Expand Around Center, Palindrome, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=counting-palindromic-substrings-d632) |
| Design a Fast Ordered Multiset with Add, Remove, and Contains | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design, Linked List, Ordered Set, Probabilistic Balancing, Randomized Data Structures, Skip List | DSA/Coding Round, Onsite, Hiring Manager | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-fast-ordered-multiset-with-add-remove-and-contains-d1171) |
| Do Four Corners Form a Square | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Combinatorics, Geometry, Hash Table, Math | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=do-four-corners-form-a-square-d585) |
| Highest Repetition Count of a Repeated Block | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Enumeration, Greedy, String, String Matching | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=highest-repetition-count-of-a-repeated-block-d1589) |
| Locate a Value in a Sorted Array of Distinct Integers | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Divide and Conquer | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=locate-a-value-in-a-sorted-array-of-distinct-integers-d689) |
