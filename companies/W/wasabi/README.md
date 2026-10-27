# Wasabi

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 25

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 8 | 9 | 8 | 9 |
| Fullstack | 0 | 0 | 1 | 3 | 3 | 3 |
| DevOps | 1 | 0 | 4 | 6 | 6 | 6 |
| Data Engineer | 0 | 0 | 0 | 4 | 4 | 4 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 2 | 0 | 2 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A pentester chains a low-privilege API that returns a signed URL with an admin-only download. Explain how signed-URL misuse becomes an authorization bypass and how you'd scope and expire them correctly. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-pentester-chains-a-low-privilege-api-that-returns-a-signed-url-with--26160) |
| How would you architect cross-region asynchronous replication for object storage so a regional outage loses at most a few minutes of uploads, and what does that cost in egress? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-cross-region-asynchronous-replication-for-obje-27140) |
| How would you decide the right storage class and access pattern for a growing archive of audit logs that must be queryable within hours but kept for seven years cheaply? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-the-right-storage-class-and-access-pattern-for-a--27135) |
| How would you design object-storage lifecycle rules and intelligent tiering for a media library and what retrieval-latency surprises must you warn product about? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-object-storage-lifecycle-rules-and-intelligent-ti-27183) |
| Design a data-deduplication layer for a backup/storage service so identical file chunks are stored once — how do you chunk hash and index at scale and handle hash-collision and reference counting for deletes? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-deduplication-layer-for-a-backup-storage-service-so-iden-28417) |
| Design an object-storage/blob service backend (S3-like) that stores exabytes durably — how do you shard metadata handle erasure coding for durability and serve presigned time-limited uploads/downloads? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-object-storage-blob-service-backend-s3-like-that-stores-exab-28415) |
| Design the metadata service for a blob store that must answer list/head for billions of objects with prefix queries — how do you shard the key space and keep listing consistent as objects are added/deleted? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-metadata-service-for-a-blob-store-that-must-answer-list-hea-28416) |
| Design geo-replication for user-generated media (large blobs) vs transactional metadata. Why do the replication strategies for these two data classes diverge, and how do you keep them coherent? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-geo-replication-for-user-generated-media-large-blobs-vs-transac-36644) |
| Why is storing large BLOBs directly in MySQL often discouraged and what is the common alternative? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-is-storing-large-blobs-directly-in-mysql-often-discouraged-and-wha-11852) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you decide the right storage class and access pattern for a growing archive of audit logs that must be queryable within hours but kept for seven years cheaply? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-the-right-storage-class-and-access-pattern-for-a--27135) |
| How do you handle the FinOps of a data-egress-heavy product (video, backups, large downloads) where egress fees dwarf compute? Design the architecture — CDN, peering, egress-free providers — and quantify the savings ceiling. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-finops-of-a-data-egress-heavy-product-video-back-41165) |
| You're accountable for whether the org runs its own object-storage-backed data platform (Ceph/Rook, MinIO) on Kubernetes or stays on cloud-native storage. Lay out the decision framework, the operational failure modes of self-hosted storage on K8s, and how you'd pilot before betting production data on it. | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-accountable-for-whether-the-org-runs-its-own-object-storage-bac-39043) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you diagnose an S3 request that's slow only for large objects — walk me through whether it's transfer bandwidth, missing multipart, wrong region, or a CloudFront misconfig, and what you'd measure? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-diagnose-an-s3-request-that-s-slow-only-for-large-object-46164) |
| Explain how you'd decide the org-wide policy on committed vs on-demand for storage (not compute) — reserved capacity, provisioned IOPS commitments, minimum-retention tiers. Storage commitments are stickier than compute; how does that change your risk posture? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-decide-the-org-wide-policy-on-committed-vs-on-demand-52957) |
| What is a storage class in object storage and give an example of when you would use a cheaper class. | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-storage-class-in-object-storage-and-give-an-example-of-when--42629) |
| Your S3-backed feature depends on a bucket in one region; a regional S3 event made the feature error out. How do you add cross-region replication and a fallback so object-store dependency doesn't hard-fail the app? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-s3-backed-feature-depends-on-a-bucket-in-one-region-a-regional-s3-46977) |
| Walk me through setting up cross-region replication for an S3 bucket with versioning, and how you'd verify replication completeness and monitor the ReplicationLatency metric. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-setting-up-cross-region-replication-for-an-s3-bucket-w-47527) |
| How do you approach negotiating data-transfer and storage-retrieval pricing for a cold/archive tier where retrieval costs can dwarf storage savings during an incident? | deep understanding | SDE-2/3, Architect/Principal | Vendor & Cloud Cost Negotiation | Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-negotiating-data-transfer-and-storage-retrieval-pr-56725) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your object-storage bill is dominated by GET/LIST request charges from millions of small-file scans, not by stored bytes. How would you estimate the request cost and redesign file layout, manifests, and caching to cut request charges rather than storage? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-object-storage-bill-is-dominated-by-get-list-request-charges-from-125337) |
| How do you design retention enforcement so that time-based deletion policies actually execute on cold object storage tiers and don't quietly fail forever? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-retention-enforcement-so-that-time-based-deletion-po-127340) |
| Compare Glacier Instant Retrieval, Flexible Retrieval, and Deep Archive on cost, latency, and minimum-storage duration, and where each fits in a real archival tier ladder. | deep understanding | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-glacier-instant-retrieval-flexible-retrieval-and-deep-archive--126729) |
| What signals do you feed into an automated tiering-decision engine, and how do you avoid it thrashing datasets between hot and cold repeatedly? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-signals-do-you-feed-into-an-automated-tiering-decision-engine-and-126716) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you reason about the durability math of your backup storage, and at what point do stated eleven-nines object-storage guarantees stop being sufficient for your risk model? | deep understanding | SDE-2/3, Architect/Principal | Backup & Recovery | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reason-about-the-durability-math-of-your-backup-storage-and-114179) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you store the documents that feed a RAG pipeline in the cloud before they are chunked and embedded? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-store-the-documents-that-feed-a-rag-pipeline-in-the-clou-76487) |
| Why does data egress from your cloud provider sometimes cost money when you pull embeddings or documents out? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-does-data-egress-from-your-cloud-provider-sometimes-cost-money-whe-76539) |
