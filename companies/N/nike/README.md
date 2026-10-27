# Nike

**Tier:** Tier 2  |  **Business domain:** Retail  |  **Questions:** 40

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 2 | 2 | 2 |
| Fullstack | 0 | 0 | 0 | 9 | 9 | 9 |
| DevOps | 0 | 0 | 2 | 4 | 4 | 4 |
| AIOps | 0 | 0 | 1 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 2 | 10 | 10 | 10 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Structures & Algorithms (all profiles) | 11 | 11 | 11 | 11 | 11 | 11 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a globally-consistent inventory-reservation platform for a company selling across regions where the same SKU pool is shared globally and oversell is unacceptable. Reconcile the single-source-of-truth requirement with the multi-region low-latency demand. | expertise | SDE-2/3, Architect/Principal | Cassandra/DynamoDB (Wide-Column NoSQL) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-globally-consistent-inventory-reservation-platform-for-a-comp-34890) |
| Explain how you'd retrofit cost tagging and allocation onto a legacy estate with 200000 untagged resources across 40 AWS accounts. What's your sequencing, automation, and enforcement plan so you don't spend a year tagging manually? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-retrofit-cost-tagging-and-allocation-onto-a-legacy-e-37067) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the frontend caching topology across browser cache, service worker, CDN, and origin so a single invalidation event (e.g. price change) propagates correctly and quickly across all layers. | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-frontend-caching-topology-across-browser-cache-service-work-40051) |
| How do you architect a frontend so a single vendor SDK (analytics, chat, tag manager) can never block first paint or exfiltrate PII, while product teams still self-serve adding tags? | deep understanding | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-frontend-so-a-single-vendor-sdk-analytics-chat--40040) |
| How do you architect a shared rendering platform that lets teams choose CSR, SSR, or static per route without every team re-solving hydration, caching, and edge deployment? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-shared-rendering-platform-that-lets-teams-choos-40023) |
| How do you architect personalization on an SSR/edge-cached page so each user sees tailored content without destroying cache hit-rate or leaking one user's data into another's cached response? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-personalization-on-an-ssr-edge-cached-page-so-eac-40074) |
| How do you architect SSR compute so a traffic spike (flash sale, live event) doesn't blow the render tier's cost or latency — where do you push work to the edge, cache, or the client? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-ssr-compute-so-a-traffic-spike-flash-sale-live-ev-40050) |
| How would you architect frontend consent management and privacy controls so cookie/consent state deterministically gates every tracker, pixel, and third-party SDK across all product surfaces? | deep understanding | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-frontend-consent-management-and-privacy-contro-40084) |
| Architect an inventory-availability system across 5000 physical stores plus warehouses where stock must be near-real-time accurate for online buyers — how do you reconcile in-store POS events with online reservations and avoid overselling a store's last unit? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-an-inventory-availability-system-across-5000-physical-stores-39485) |
| Your org wants to adopt Crossplane so infrastructure (databases, buckets, queues) is provisioned as Kubernetes resources. As principal, how would you weigh Crossplane against Terraform for the whole estate, where does the everything-is-a-CRD model break down, and how would you avoid a control-plane that becomes a giant blast radius? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-to-adopt-crossplane-so-infrastructure-databases-buckets-39026) |
| Design the architecture for handling a flash-sale where the frontend, CDN, edge, and backend must together survive 100x traffic: static-first rendering, a virtual waiting room, and a thin write path. How do you keep the browser experience trustworthy while shedding load? | expertise | SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-for-handling-a-flash-sale-where-the-frontend-c-38274) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a Control Tower landing zone with Account Factory so cost-attribution, security baseline, and network baseline are guaranteed the instant a team vends a new account — and where do you draw the shared-services versus per-team account boundary? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-control-tower-landing-zone-with-account-fact-52358) |
| How would you architect a globally-consistent inventory/quota counter that must never oversell during a flash sale at millions of concurrent requests — how do you reconcile strong consistency with throughput, and where do sharded counters, DynamoDB conditional writes, or a reservation ledger fit? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-globally-consistent-inventory-quota-counter--52364) |
| Walk me through configuring DynamoDB Global Tables and how you'd handle the last-writer-wins conflict semantics operationally when two regions update the same item. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-configuring-dynamodb-global-tables-and-how-you-d-handl-47534) |
| Your active-active setup routes by latency but you need session affinity for a stateful checkout flow. How do you reconcile latency routing with keeping a user pinned to one region mid-flow? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-active-active-setup-routes-by-latency-but-you-need-session-affini-47599) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your KPI-anomaly model watches business metrics (checkout rate). During a flash sale it screams anomaly. How do you monitor without alerting on planned events? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-kpi-anomaly-model-watches-business-metrics-checkout-rate-during-a-95348) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer asks: your nightly Glue job intermittently fails with an S3 SlowDown 503. What is actually happening at the storage layer and how would you make the writer resilient to it? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-asks-your-nightly-glue-job-intermittently-fails-with-an-120570) |
| When would you pick Redshift's provisioned clusters over serverless, and how would you reason about the concurrency-scaling and RA3 storage-compute split for a bursty BI workload? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-pick-redshift-s-provisioned-clusters-over-serverless-an-120582) |
| Describe how you would run a discovery process to identify the first three data products worth investing in when an organization has hundreds of tables and no clear ownership. | deep understanding | SDE-2/3, Architect/Principal | Data Product Thinking | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-would-run-a-discovery-process-to-identify-the-first-t-127119) |
| How do you handle product master data (PIM) where the same SKU has different attributes per channel/region — is that one master with variants, many masters, or a different pattern entirely? | expertise | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-product-master-data-pim-where-the-same-sku-has-diffe-127755) |
| A subsidiary in China must run on a local cloud with no cross-border transfer — how does that partition change your global catalog, lineage and metrics-layer design? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-subsidiary-in-china-must-run-on-a-local-cloud-with-no-cross-border-t-127253) |
| Design cross-cloud data sharing with a partner org where neither side trusts the other's cloud — how do you use clean rooms / Delta Sharing to expose only aggregates? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-cross-cloud-data-sharing-with-a-partner-org-where-neither-side--127290) |
| How do you architect a single semantic/metrics layer that serves BI tools connected to warehouses in different clouds without recomputing definitions three times? | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-single-semantic-metrics-layer-that-serves-bi-to-127237) |
| How do you handle master data management for a customer entity that's created and updated in systems living on different clouds — where does the golden record live and how is it reconciled? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-master-data-management-for-a-customer-entity-that-s--127299) |
| Your leadership wants to avoid lock-in but your fastest path uses Snowflake's proprietary features — how do you frame the lock-in-vs-velocity tradeoff as a reversible-vs-irreversible-decisions problem? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leadership-wants-to-avoid-lock-in-but-your-fastest-path-uses-snow-127249) |
| Snowflake charges for time-travel and fail-safe storage on cold tables you never query. How do you design retention and cloning to avoid paying for cold history you don't need? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=snowflake-charges-for-time-travel-and-fail-safe-storage-on-cold-tables-126787) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a DynamoDB single-table data model for a domain with a dozen access patterns while keeping GSI count bounded — walk me through the write-sharding, GSI-overloading, and sparse-index techniques and where each starts to hurt at scale. | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-dynamodb-single-table-data-model-for-a-domain-w-111848) |
| How do you architect a data platform where the same conformed dimension (say 'product') is authored once but physically replicated into every domain's data product in a mesh? What keeps the copies consistent, and how do you avoid the central-model chokepoint you were trying to escape? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-data-platform-where-the-same-conformed-dimensio-112665) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect brand-voice and tone compliance as an eval so a regulated brand's assistant is never flippant or off-brand — and how do you keep that judge aligned with the brand team's intent? | deep understanding | SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-brand-voice-and-tone-compliance-as-an-eval-so-a-r-84813) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Dynamic Weighted Digraph With On-Demand Shortest Path | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Adjacency List, Design, Dijkstra's Algorithm, Graph, Heap (Priority Queue), Shortest Path | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=dynamic-weighted-digraph-with-on-demand-shortest-path-d2487) |
| Installing Chargers Without Adjacent Conflicts | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Simulation | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=installing-chargers-without-adjacent-conflicts-d595) |
| Largest Sum of a Contiguous Block | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Divide and Conquer, Dynamic Programming, Kadane's Algorithm | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=largest-sum-of-a-contiguous-block-d53) |
| Locate the Repeated Label in a Bounded Sequence | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Bit Manipulation, Floyd's Cycle Detection, Linked List (implicit), Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=locate-the-repeated-label-in-a-bounded-sequence-d287) |
| Longest Well-Formed Bracket Run | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Dynamic Programming, Stack, String, Two Pointers | DSA/Coding Round, Onsite, Hiring Manager | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-well-formed-bracket-run-d32) |
| Maximum Total Gain with Unlimited Buy-Sell Transactions | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Greedy, Peak-Valley, Single Pass | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=maximum-total-gain-with-unlimited-buy-sell-transactions-d122) |
| Reaching the Final Cell With Forward Hops | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Greedy | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=reaching-the-final-cell-with-forward-hops-d55) |
| Rearrange a Sequence Into Its Next Greater Ordering | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, In-place Modification, Permutations, Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=rearrange-a-sequence-into-its-next-greater-ordering-d31) |
| Repeated Digit-Square Sum Reaches One | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Cycle Detection, Floyd's Tortoise and Hare, Hash Table, Math, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=repeated-digit-square-sum-reaches-one-d202) |
| Stack With Constant-Time Minimum Lookup | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Amortized Analysis, Auxiliary State, Design, Stack | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=stack-with-constant-time-minimum-lookup-d155) |
| Zigzag Diagonal Sweep of a Grid | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Matrix, Simulation, Two-Dimensional Traversal | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=zigzag-diagonal-sweep-of-a-grid-d498) |
