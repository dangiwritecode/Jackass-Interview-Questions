# Reliance Retail

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| Data Engineer | 4 | 0 | 7 | 7 | 1 | 7 |
| Database Developer | 0 | 0 | 0 | 4 | 4 | 4 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org runs Kubernetes at the edge (thousands of retail/IoT sites) on K3s/KubeEdge with intermittent connectivity. How would you architect fleet management and GitOps to disconnected clusters, and preserve local autonomy when the control plane is unreachable for hours, given the standard reconcile model assumes a reachable API server? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-runs-kubernetes-at-the-edge-thousands-of-retail-iot-sites-on--52203) |
| How do you approach a landing zone that must span AWS + on-prem VMware + edge locations for a manufacturing/retail company? What's foundational vs location-specific? | deep understanding | SDE-2/3, Architect/Principal | Landing Zones & Cloud Foundations | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-a-landing-zone-that-must-span-aws-on-prem-vmware-e-56125) |
| How would you architect a hybrid edge-to-cloud topology (retail stores / factories) where thousands of edge sites must stay operational during a cloud disconnect? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud & Hybrid Cloud | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-hybrid-edge-to-cloud-topology-retail-stores--55298) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you model a Store dimension for a retail chain, and what attributes would you include? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Data Modeling (Star/Snowflake Schema) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-store-dimension-for-a-retail-chain-and-what-attr-117242) |
| How do you describe the difference between 'processing an order' and 'analyzing all orders' to explain OLTP vs OLAP? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-describe-the-difference-between-processing-an-order-and-ana-118789) |
| If a business asks 'which product sold best last quarter', why do you not query the live product-catalog OLTP table for the answer? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=if-a-business-asks-which-product-sold-best-last-quarter-why-do-you-not-118832) |
| What does 'aggregation' mean and why is it far more common in OLAP than OLTP? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-aggregation-mean-and-why-is-it-far-more-common-in-olap-than--118778) |
| Write a Flink SQL query that computes a 10-minute sliding sum of order value per store, and explain the windowing clause used. | intermediate experience | SDE-1/2, SDE-2/3 | Stream Processing (Apache Flink) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=write-a-flink-sql-query-that-computes-a-10-minute-sliding-sum-of-order-121282) |
| How would you compute a per-region cumulative share of company revenue in descending order in a single scan, and why is the ORDER BY direction inside OVER load-bearing here? | deep understanding | SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-compute-a-per-region-cumulative-share-of-company-revenue-123265) |
| How would you compute both a per-store daily rank and an all-time rank of sales in one pass and prove that the two OVER clauses can share a single sort? | deep understanding | SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-compute-both-a-per-store-daily-rank-and-an-all-time-rank-123217) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you reason about CAP for a database whose replication is over an unreliable satellite/last-mile link (retail POS, remote sites) where partitions are frequent and long, and why does that make an offline-first AP design with reconciliation the pragmatic default? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reason-about-cap-for-a-database-whose-replication-is-over-a-111604) |
| How do you architect a data platform where the same conformed dimension (say 'product') is authored once but physically replicated into every domain's data product in a mesh? What keeps the copies consistent, and how do you avoid the central-model chokepoint you were trying to escape? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-data-platform-where-the-same-conformed-dimensio-112665) |
| You're asked to eliminate a nightly 8-hour batch window that no longer fits the business's global operating hours. Walk me through converting a batch-dependent warehouse to continuously-loaded micro-batches or streaming, and where downstream consumers' assumptions about 'a complete day' break. | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-eliminate-a-nightly-8-hour-batch-window-that-no-longer-112717) |
| You're consolidating 6 regional warehouses with divergent conformed dimensions after years of local autonomy. As principal, design the master-data-management and identity-resolution layer that reconciles them, and decide where you accept permanent regional variance versus force conformance. | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-consolidating-6-regional-warehouses-with-divergent-conformed-di-112687) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you decide whether a drop in XGBoost model performance justifies a full retrain versus a warm-started incremental update? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-a-drop-in-xgboost-model-performance-justi-65917) |
