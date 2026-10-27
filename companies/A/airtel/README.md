# Airtel

**Tier:** Tier 3  |  **Business domain:** Telecom  |  **Questions:** 41

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 4 | 7 | 4 | 7 |
| Fullstack | 0 | 0 | 0 | 4 | 4 | 4 |
| DevOps | 0 | 0 | 0 | 5 | 5 | 5 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 7 | 7 | 7 |
| ML Engineer | 0 | 0 | 2 | 4 | 3 | 4 |
| AI Engineer | 0 | 0 | 0 | 7 | 7 | 7 |
| Data Structures & Algorithms (all profiles) | 4 | 4 | 4 | 4 | 4 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| When would you reach for S3 Transfer Acceleration, and how does it actually speed uploads? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-reach-for-s3-transfer-acceleration-and-how-does-it-actu-14570) |
| Argue for or against building your own POP presence in a strategic market versus relying on a CDN there. What traffic volume, regulatory pressure, and peering economics justify owning infrastructure in-region? | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=argue-for-or-against-building-your-own-pop-presence-in-a-strategic-mar-35072) |
| Design the strategy for delivering to markets with poor last-mile connectivity (tier-2/3 India, emerging markets) as a first-class concern in your edge platform: compression, protocol choice, adaptive delivery, and how you'd measure real-world gains. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-strategy-for-delivering-to-markets-with-poor-last-mile-conn-35103) |
| Your company operates in regions where the primary CDN has weak coverage (e.g., specific parts of India/Africa/SEA). Design a regional multi-CDN strategy that optimizes local performance without fragmenting global operations and cost control. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-company-operates-in-regions-where-the-primary-cdn-has-weak-covera-35032) |
| How would you diagnose asymmetric routing or a black-holed subnet from a Linux backend box, using ip route, traceroute, mtr, and ip rule, when only some destinations are unreachable? | deep understanding | SDE-1/2, SDE-2/3 | Linux | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-diagnose-asymmetric-routing-or-a-black-holed-subnet-from-26685) |
| You expose GET /accounts/:id/balance and it must reflect writes made microseconds earlier from the same client but tolerate replica lag for everyone else. How do you route reads to satisfy both without a strong-read for all? | expertise | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-expose-get-accounts-id-balance-and-it-must-reflect-writes-made-mic-23933) |
| Your API gateway terminates TLS and re-encrypts to backends. A subtle bug drops the client IP so rate limiting keys on the gateway IP and limits everyone together. How do you propagate and trust the real client IP? | deep understanding | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-api-gateway-terminates-tls-and-re-encrypts-to-backends-a-subtle-b-23948) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org wants the gateway to enforce a company-wide caching policy but every team has different freshness needs; design a declarative caching-contract layer where teams express intent (TTL/staleness tolerance/invalidation triggers) and the gateway enforces it uniformly, and adjudicate what you refuse to let teams override. | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-the-gateway-to-enforce-a-company-wide-caching-policy-bu-39525) |
| Argue for or against building your own POP presence in a strategic market (say a specific region of India or Africa) versus relying on the CDN there. What traffic volume, regulatory pressure, and peering economics justify owning in-region infrastructure? | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=argue-for-or-against-building-your-own-pop-presence-in-a-strategic-mar-39664) |
| Argue when a CDN is the wrong primary tool and a different architecture (regional replication, P2P delivery, client-side caching, ISP peering/PNI) is the right choice. Give a concrete workload where you'd deliberately minimize CDN reliance and defend it at portfolio level. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=argue-when-a-cdn-is-the-wrong-primary-tool-and-a-different-architectur-39685) |
| Design the strategy for delivering to markets with poor last-mile connectivity (tier-2/3 India, emerging markets) as a first-class concern in your edge platform: compression, protocol choice, adaptive delivery, and how you'd measure real-world gains. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-strategy-for-delivering-to-markets-with-poor-last-mile-conn-35103) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide between a hub-and-spoke topology and Azure Virtual WAN for a global enterprise with 15 regions and on-prem MPLS; what's the inflection point that changes the answer? | deep understanding | SDE-2/3, Architect/Principal | Azure | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-between-a-hub-and-spoke-topology-and-azure-virtual-w-54527) |
| How would you architect the org's stance on multi-network Pods now that the multi-network and DRA-for-networking KEPs are landing, for a workload that needs a fast data-plane NIC separate from the pod-network NIC, and what governance keeps this from becoming a per-team snowflake? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-org-s-stance-on-multi-network-pods-now-tha-52131) |
| How do you approach governance for edge and hybrid deployments (on-prem + cloud) where the same policy engine can't run everywhere? What's the consistency story? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Governance Frameworks | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-governance-for-edge-and-hybrid-deployments-on-prem-55974) |
| Architect how you'd federate signing identity across a partner ecosystem so that vendors can sign artifacts you consume, and you can verify them, without sharing keys or trust roots. | expertise | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-how-you-d-federate-signing-identity-across-a-partner-ecosyst-55442) |
| How do you approach a negotiation where regulatory data-residency requirements limit which regions/vendors you can use — shrinking your leverage? | deep understanding | SDE-2/3, Architect/Principal | Vendor & Cloud Cost Negotiation | Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-a-negotiation-where-regulatory-data-residency-requ-56689) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a mobile/edge/IoT telemetry-collection tier feeding AIOps where you can't assume connectivity to a vendor's cloud — does the disconnected/intermittent-operation constraint force building your own store-and-forward collector? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-mobile-edge-iot-telemetry-collect-100106) |
| How do you decide build-vs-buy for network-performance AIOps specifically (buy ThousandEyes/Kentik vs build on flow logs + your ML) when cross-cloud and last-mile latency diagnosis needs vantage points you can't replicate in-house? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-network-performance-aiops-specifica-100062) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| When you present multi-cloud strategy to the board, how do you separate genuine sovereignty/resilience drivers from procurement leverage against a single vendor — and does it change the architecture? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-you-present-multi-cloud-strategy-to-the-board-how-do-you-separate-127251) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the primary-key and merge-on-read strategy for a lakehouse table fed by CDC upserts from a sharded OLTP source with 500M mutations/day? Where does merge-on-read's read amplification force you back to copy-on-write, and what's the compaction cadence? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-primary-key-and-merge-on-read-strategy-for-a--112644) |
| How do you decide between a shared-nothing MPP warehouse (Redshift classic/Teradata) and a decoupled storage-compute warehouse (Snowflake/BigQuery/Redshift RA3) for a workload with wildly spiky concurrency? Where does the shared-nothing data-redistribution cost dominate and force the migration? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-between-a-shared-nothing-mpp-warehouse-redshift-clas-112668) |
| You must migrate a 10PB Hadoop/Hive estate to Iceberg-on-object-storage. Sequence the migration so queries keep working across both formats during transition, table by table, and describe how you handle in-place metadata migration versus full rewrite and the correctness checks at cut-over. | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-migrate-a-10pb-hadoop-hive-estate-to-iceberg-on-object-storag-112724) |
| You're asked whether to run your lake on HDFS versus object storage (S3/GCS/ADLS) for a rebuild. Beyond cost, what consistency-model, rename-atomicity, and throughput differences actually change your table-format and compaction design on object storage? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-whether-to-run-your-lake-on-hdfs-versus-object-storage-s3-112682) |
| How do you build a capacity plan that accounts for on-prem vs cloud economics when parts of the estate are hybrid, and the cost curves cross at different scales? | expertise | SDE-2/3, Architect/Principal | Database Capacity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-a-capacity-plan-that-accounts-for-on-prem-vs-cloud-ec-115016) |
| What's your approach when the 'right' datastore for a workload isn't available in your cloud region or has weak managed support there? How does cloud-provider reality constrain ideal selection? | deep understanding | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-when-the-right-datastore-for-a-workload-isn-t-ava-114395) |
| When a preferred managed database service is not available in a required region or sovereign cloud, how do you adjust your vendor strategy without fragmenting the platform? | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-a-preferred-managed-database-service-is-not-available-in-a-requir-115350) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle concept drift for an XGBoost churn model when labels only arrive 60 days after prediction? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-concept-drift-for-an-xgboost-churn-model-when-labels-65889) |
| Your largest customer demands in-region data residency with no data leaving to any US API. How does that single requirement reshape your whole model-deployment architecture, vendor strategy, and roadmap? | expertise | SDE-2/3, Architect/Principal | LLMOps & Model Deployment | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-largest-customer-demands-in-region-data-residency-with-no-data-le-69456) |
| How would you design a churn-prediction system whose predictions feed automated retention campaigns without creating a self-fulfilling feedback loop? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-churn-prediction-system-whose-predictions-feed--66716) |
| What is your multi-region and DR strategy for a post-training platform when a single RLHF run can span weeks and consume a datacenter's worth of GPUs? | expertise | SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-multi-region-and-dr-strategy-for-a-post-training-platform-71276) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your strategy for cross-region data residency when a global GenAI product must retrieve region-local knowledge but serve a single conversational experience? | expertise | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-cross-region-data-residency-when-a-global-gen-86745) |
| Data-residency and sovereign-AI rules force you to serve some regions on in-region (pricier) model deployments while others use a cheaper central endpoint. Design the cost-governance and placement engine that respects sovereignty without letting compliance cost balloon unmeasured. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=data-residency-and-sovereign-ai-rules-force-you-to-serve-some-regions--83845) |
| Design the capacity-planning and GPU-procurement model you'd bring to a yearly hardware budgeting cycle, translating token forecasts and KV-cache footprints into committed spend and headroom. | expertise | SDE-2/3, Architect/Principal | LLM Serving & KV Cache | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-capacity-planning-and-gpu-procurement-model-you-d-bring-to--85340) |
| How would you approach standing up serving in a data-residency-restricted region with limited GPU supply, and what KV-cache and model choices flow from that constraint? | expertise | SDE-2/3, Architect/Principal | LLM Serving & KV Cache | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-standing-up-serving-in-a-data-residency-restric-85402) |
| How would you architect a serving platform that spans on-prem GPUs and multiple clouds, keeping KV-cache-aware routing and prefix reuse coherent across environments? | expertise | SDE-2/3, Architect/Principal | LLM Serving & KV Cache | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-serving-platform-that-spans-on-prem-gpus-and-85358) |
| How would you architect federated RAG that queries multiple isolated indexes owned by different business units (or partner companies) and merges results without any unit shipping its raw documents or embeddings to a central place? | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-federated-rag-that-queries-multiple-isolated-i-82951) |
| You're deciding how much retrieval intelligence lives in an on-device/edge model versus the cloud platform for a mobile-first product in low-connectivity markets. Where do you split the index and how do you reconcile edge and cloud answers? | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-how-much-retrieval-intelligence-lives-in-an-on-device--82968) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Answer Range XOR Queries on an Array | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Bit Manipulation, Prefix Sum, Prefix XOR | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=answer-range-xor-queries-on-an-array-d1264) |
| First and Last Occurrence in a Sorted Array | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=first-and-last-occurrence-in-a-sorted-array-d34) |
| Maximum Perimeter of a Closable Rod Loop | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Prefix Sum, Sorting | Online Assessment (OA), DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=maximum-perimeter-of-a-closable-rod-loop-d2737) |
| Rearrange a Sequence Into Its Next Greater Ordering | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, In-place Modification, Permutations, Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=rearrange-a-sequence-into-its-next-greater-ordering-d31) |
