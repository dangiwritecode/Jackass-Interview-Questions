# PubMatic

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 4 | 5 | 4 | 5 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 3 | 3 | 1 | 3 |
| Data Structures & Algorithms (all profiles) | 3 | 3 | 3 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Adjudicate the trade-off: buffering absorbs bursts but adds latency and hides overload; shedding preserves latency but loses work. For a real-time bidding system defend where you draw the line and how you tune it. | expertise | SDE-2/3, Architect/Principal | Backpressure & Flow Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=adjudicate-the-trade-off-buffering-absorbs-bursts-but-adds-latency-and-37740) |
| Design budget pacing for an ad campaign so a daily budget is spent smoothly across the day without overspend — how do you distribute the budget across serving nodes and reconcile spend in near-real-time? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-budget-pacing-for-an-ad-campaign-so-a-daily-budget-is-spent-smo-28376) |
| Design frequency capping in ad serving so a user isn't shown the same ad more than N times in 24h across devices — where do you store the per-user counters and how do you keep the check under a few ms? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-frequency-capping-in-ad-serving-so-a-user-isn-t-shown-the-same--28379) |
| Design the real-time bidding (RTB) path for an ad exchange that must respond to bid requests in under 80ms at millions of QPS — how do you keep the candidate lookup and scoring hot and handle timeouts gracefully? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-real-time-bidding-rtb-path-for-an-ad-exchange-that-must-res-28377) |
| You need to atomically reserve budget from a shared pool across many ad-serving nodes so you never overspend a campaign — design the Redis operation and the reconciliation. | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-atomically-reserve-budget-from-a-shared-pool-across-many-a-24690) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design caching for a real-time bidding or ad-serving path where a cached decision that is milliseconds stale still costs money, so you must reconcile sub-millisecond latency with near-zero staleness tolerance? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-caching-for-a-real-time-bidding-or-ad-serving-pat-38562) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect an ad-serving or real-time-bidding backend that must answer within a tens-of-milliseconds budget at millions of QPS, staying available even when a fraction of scoring nodes are slow, and where you deliberately trade completeness for latency? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-an-ad-serving-or-real-time-bidding-backend-tha-52116) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the ingestion and storage architecture for an adtech firm processing 10M bid requests/second where 99% of data is discarded within seconds but the 1% kept must be joinable to conversions weeks later. Where does the streaming-hot path diverge from the lake-cold path, and how do you stitch them? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-ingestion-and-storage-architecture-for-an-adtech-firm-proce-112698) |
| You're standardizing the org on either Parquet or ORC as the physical file format under your table format. Beyond 'both are columnar,' what specific encoding, predicate-pushdown, and nested-type differences would actually change your recommendation for a nested-heavy adtech workload? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-standardizing-the-org-on-either-parquet-or-orc-as-the-physical--112654) |
| How would you capacity-plan for a database backing a real-time bidding or matching engine where sub-millisecond p99 caps effective throughput far below raw limits? | expertise | SDE-2/3, Architect/Principal | Database Capacity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-capacity-plan-for-a-database-backing-a-real-time-bidding-114995) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle categorical features with thousands of levels in XGBoost without blowing up memory or leaking target information? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-categorical-features-with-thousands-of-levels-in-xgb-65883) |
| What's the trade-off between DART booster and standard gbtree in XGBoost, and when would production constraints push you to pick one? | expertise | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-the-trade-off-between-dart-booster-and-standard-gbtree-in-xgboo-65945) |
| Walk me through designing a real-time bidding predictor that must return a bid within a few milliseconds under strict budget constraints. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-designing-a-real-time-bidding-predictor-that-must-retu-66721) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Longest Shared Starting Segment of a Group of Words | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | String, Trie, Vertical Scanning | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-shared-starting-segment-of-a-group-of-words-d14) |
| Minimum Concurrent Rooms for Overlapping Bookings | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Heap (Priority Queue), Intervals, Prefix Sum, Sorting, Sweep Line, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=minimum-concurrent-rooms-for-overlapping-bookings-d253) |
| Water Trapped Between Walls | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Monotonic Stack, Prefix/Suffix Maximum, Stack, Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite, Hiring Manager | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=water-trapped-between-walls-d42) |
