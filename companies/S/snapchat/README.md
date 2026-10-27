# Snapchat

**Tier:** Tier 1  |  **Business domain:** —  |  **Questions:** 28

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 9 | 8 | 9 |
| Fullstack | 0 | 0 | 3 | 3 | 1 | 3 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 11 | 11 | 11 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Sketch a consistency architecture for a chat/messaging platform at billions of messages/day: which guarantees per message ordering, delivery, and read receipts, and where do you deliberately use causal (not total) order to scale? Defend the boundaries. | deep understanding | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=sketch-a-consistency-architecture-for-a-chat-messaging-platform-at-bil-33952) |
| How would you implement approximate top-k trending hashtags over a firehose stream with limited memory, and what guarantees does the Count-Min or Space-Saving approach give you? | expertise | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-approximate-top-k-trending-hashtags-over-a-fir-16044) |
| Design a photo-sharing service (Instagram-like) — how do you store and serve billions of images with thumbnails at multiple resolutions and a global CDN? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-photo-sharing-service-instagram-like-how-do-you-store-and-ser-20658) |
| Design a rate limiter for a graph/social API where a single request can traverse and cost against multiple users' quotas (e.g., a fan-out post to millions of followers). How do you account cost fairly and prevent one influential user's action from exhausting a shared write budget? | expertise | SDE-2/3, Architect/Principal | Rate Limiting | Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-rate-limiter-for-a-graph-social-api-where-a-single-request-ca-32596) |
| An interviewer challenges your session-window design: 'What happens when a user's session gap threshold is wrong for 5% of users?' Reason about the sensitivity of session windows to the gap parameter and how you'd make it adaptive or per-cohort. | deep understanding | SDE-2/3, Architect/Principal | Real-time Streaming Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-session-window-design-what-happens-when-37878) |
| Design event-time watermarking for a pipeline that ingests from mobile clients that can be offline for days. How do you balance allowed-lateness against unbounded state, and what product compromises do you negotiate? | expertise | SDE-2/3, Architect/Principal | Real-time Streaming Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-event-time-watermarking-for-a-pipeline-that-ingests-from-mobile-37843) |
| Design for correctness under clock skew and clock changes: your event timestamps come from thousands of client devices with unreliable clocks. How do you keep event-time processing sane, and when do you override client time with server time? | expertise | SDE-2/3, Architect/Principal | Real-time Streaming Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-for-correctness-under-clock-skew-and-clock-changes-your-event-t-37897) |
| How do you architect for correct results when the same logical event arrives on two independent ingestion paths (mobile SDK retry plus server-side log)? Design cross-source deduplication at scale and its state-cost trade-offs. | expertise | SDE-2/3, Architect/Principal | Real-time Streaming Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-for-correct-results-when-the-same-logical-event-a-37868) |
| How would you architect a globally-distributed chat/messaging backend (billions of messages, presence, ordering per conversation) to scale writes and fan-out while keeping availability high, and where do you accept eventual consistency versus enforce ordering? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-globally-distributed-chat-messaging-backend--32162) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you implement approximate top-k trending hashtags over a firehose stream with limited memory, and what guarantees does the Count-Min or Space-Saving approach give you? | expertise | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-approximate-top-k-trending-hashtags-over-a-fir-16044) |
| Your infinite-scroll feed accumulates DOM nodes and memory until the tab crashes; what windowing data structure recycles nodes and how do you keep scroll position stable during recycling? | intermediate experience | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-infinite-scroll-feed-accumulates-dom-nodes-and-memory-until-the-t-16079) |
| Design a photo-sharing service (Instagram-like) — how do you store and serve billions of images with thumbnails at multiple resolutions and a global CDN? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-photo-sharing-service-instagram-like-how-do-you-store-and-ser-20658) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your approach to handling hot keys in a real-time aggregation, like one celebrity account generating 40% of the traffic in a social feed analytics pipeline? | expertise | SDE-2/3, Architect/Principal | Real-time Analytics Architecture | Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-handling-hot-keys-in-a-real-time-aggregation-l-127555) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A DynamoDB GSI is throttling and backpressuring writes to the base table — explain precisely why a GSI's under-provisioned capacity throttles the base table, and how you'd fix the capacity mismatch, projection, or sparse-index design without downtime. | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-dynamodb-gsi-is-throttling-and-backpressuring-writes-to-the-base-tab-111919) |
| Explain how DynamoDB adaptive capacity and instant-split-on-throttle actually work under the hood, and how you'd design a partition-key strategy that keeps per-partition throughput below the physical 3000 RCU / 1000 WCU ceiling for a high-cardinality write workload. | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-dynamodb-adaptive-capacity-and-instant-split-on-throttle-a-111849) |
| How do you architect a globally-unique-username registration at planet scale so it's usable worldwide yet never allows a duplicate; compare a single CP registry, region-sharded namespaces, and a reserve-then-confirm scheme, and justify a default with its partition costs. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-globally-unique-username-registration-at-planet-111602) |
| How do you decide replication factor and consistency level for a globally-replicated NoSQL store balancing HA, latency, and storage cost across regions? Walk through a concrete tuning example. | deep understanding | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-replication-factor-and-consistency-level-for-a-globa-114732) |
| How does Redis Sentinel differ from Redis Cluster for HA, and when does an HA cache failover actually threaten data correctness in the primary datastore behind it? | deep understanding | SDE-2/3, Architect/Principal | Database HA Architecture (Failover/Clustering) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-redis-sentinel-differ-from-redis-cluster-for-ha-and-when-does-114688) |
| A senior engineer proposes putting all foreign-key-related tables into one Spanner interleave hierarchy for locality; what are the second-order risks (split limits, hierarchy rigidity, hotspot concentration) you'd raise? | expertise | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-senior-engineer-proposes-putting-all-foreign-key-related-tables-into-114485) |
| Describe how you'd architect multi-region write locality for a social feed where a user's data should be pinned to their home region but occasionally read globally; which locality primitive fits and why. | deep understanding | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-architect-multi-region-write-locality-for-a-social--114514) |
| Explain how Spanner's split points and load-based splitting work, why monotonically increasing keys cause hotspots, and the bit-reversed/UUID mitigations you'd recommend for a high-ingest table. | deep understanding | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-spanner-s-split-points-and-load-based-splitting-work-why-m-114475) |
| Explain how you'd model time-to-live and data-expiry at scale on CockroachDB (row-level TTL) versus Spanner, and the storage/GC implications of large expiring datasets. | deep understanding | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-model-time-to-live-and-data-expiry-at-scale-on-cockr-114507) |
| Explain Spanner's interleaved tables and how they physically co-locate child rows with parents; when does interleaving materially improve latency, and what are the migration hazards if hierarchy changes later? | deep understanding | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-spanner-s-interleaved-tables-and-how-they-physically-co-locate-114452) |
| How would you evaluate Spanner's dual PostgreSQL and GoogleSQL dialects for a new build, and what long-term portability and tooling trade-offs would you weigh in the interface choice? | deep understanding | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-spanner-s-dual-postgresql-and-googlesql-dialect-114513) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a shadow-deployment for a new XGBoost ranking model to measure real traffic behavior before switching over? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-shadow-deployment-for-a-new-xgboost-ranking-mod-65899) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe how you'd set the org's strategy for on-device versus cloud multimodal inference for a consumer app weighing privacy latency cost and model-freshness across a device fleet. | expertise | SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-set-the-org-s-strategy-for-on-device-versus-cloud-m-84674) |
| How would you architect a multimodal moderation platform that must catch joint-signal harmful memes at social-network scale with millions of items per minute while bounding false-positive impact on creators? | expertise | SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-multimodal-moderation-platform-that-must-cat-84698) |
| Interviewer probe: your VP wants a real-time multimodal avatar with speech and lip-sync. As principal how do you assess whether the latency and cost make it viable at your scale before committing a team? | deep understanding | SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=interviewer-probe-your-vp-wants-a-real-time-multimodal-avatar-with-spe-84697) |
