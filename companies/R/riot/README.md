# Riot

**Tier:** Tier 1  |  **Business domain:** —  |  **Questions:** 20

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 10 | 11 | 7 | 11 |
| Fullstack | 0 | 0 | 7 | 7 | 4 | 7 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you model a leaderboard that needs top-N-by-score plus point lookups in DynamoDB, and why might you push the ranked reads to ElastiCache sorted sets instead? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-leaderboard-that-needs-top-n-by-score-plus-point-27039) |
| A leaderboard table needs both 'top 100 globally' and 'rank of arbitrary user' cheaply. Discuss a covering index versus a Redis sorted set as the source of truth. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Database Indexing & Query Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-leaderboard-table-needs-both-top-100-globally-and-rank-of-arbitrary--25747) |
| Design a leaderboard service for a game with 50M players and live rank updates — how do you compute and serve a user's rank and the top-N in real time? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-service-for-a-game-with-50m-players-and-live-rank-20661) |
| Your leaderboard uses a sorted set in Redis but a single game has 50M entries — how do you shard it, compute global rank across shards, and cap memory? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-uses-a-sorted-set-in-redis-but-a-single-game-has-50m--20662) |
| How do you design a Memento-based game-save so that a save from an old version can still be loaded after you ship new features; what does forward/backward compatibility require of the memento format? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-memento-based-game-save-so-that-a-save-from-an-old-16481) |
| Your leaderboard gives correct top-K but rank queries for arbitrary users are slow at 10M players; how would you redesign the structure so both top-K and 'my rank' are fast, and what do you trade? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-gives-correct-top-k-but-rank-queries-for-arbitrary-us-16464) |
| How would you architect the concurrency for a stateful in-memory service (session store, matchmaking, live leaderboard) that must be highly available; how do you handle concurrent read-modify-write during failover and replica catch-up without corruption? | expertise | SDE-2/3, Architect/Principal | Multithreading & Concurrency | Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-concurrency-for-a-stateful-in-memory-servi-32991) |
| A leaderboard must return a specific user's rank and a page around them for millions of users in low latency; design the schema, index, and query and discuss recompute vs live rank. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-leaderboard-must-return-a-specific-user-s-rank-and-a-page-around-the-18136) |
| Your API must return a consistent ordering for a leaderboard endpoint under heavy concurrent score updates. How do you design pagination and tie-breaking so a client scrolling doesn't see items jump around? | deep understanding | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-api-must-return-a-consistent-ordering-for-a-leaderboard-endpoint--23954) |
| How would you design leaderboard queries that must return a user's exact rank among millions in real time? Compare window-function ranking, a maintained rank column, and Redis sorted sets. | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-leaderboard-queries-that-must-return-a-user-s-exa-16282) |
| For a multiplayer game needing unreliable-but-fast state sync, why might WebSockets (TCP) be the wrong transport, and what would you use instead? | deep understanding | SDE-1/2, SDE-2/3 | WebSockets | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-a-multiplayer-game-needing-unreliable-but-fast-state-sync-why-migh-17989) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a leaderboard service for a game with 50M players and live rank updates — how do you compute and serve a user's rank and the top-N in real time? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-service-for-a-game-with-50m-players-and-live-rank-20661) |
| Your leaderboard uses a sorted set in Redis but a single game has 50M entries — how do you shard it, compute global rank across shards, and cap memory? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-uses-a-sorted-set-in-redis-but-a-single-game-has-50m--20662) |
| How do you design a Memento-based game-save so that a save from an old version can still be loaded after you ship new features; what does forward/backward compatibility require of the memento format? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-memento-based-game-save-so-that-a-save-from-an-old-16481) |
| Your leaderboard gives correct top-K but rank queries for arbitrary users are slow at 10M players; how would you redesign the structure so both top-K and 'my rank' are fast, and what do you trade? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-gives-correct-top-k-but-rank-queries-for-arbitrary-us-16464) |
| A leaderboard must return a specific user's rank and a page around them for millions of users in low latency; design the schema, index, and query and discuss recompute vs live rank. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-leaderboard-must-return-a-specific-user-s-rank-and-a-page-around-the-18136) |
| How would you design leaderboard queries that must return a user's exact rank among millions in real time? Compare window-function ranking, a maintained rank column, and Redis sorted sets. | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-leaderboard-queries-that-must-return-a-user-s-exa-16282) |
| For a multiplayer game needing unreliable-but-fast state sync, why might WebSockets (TCP) be the wrong transport, and what would you use instead? | deep understanding | SDE-1/2, SDE-2/3 | WebSockets | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-a-multiplayer-game-needing-unreliable-but-fast-state-sync-why-migh-17989) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a global traffic-steering strategy layering AWS Global Accelerator anycast over Route 53 latency routing and CloudFront — how do you decide which layer owns steering, and what's your story for a partial regional brownout that health checks don't catch? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-global-traffic-steering-strategy-layering-aws-g-52345) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a restore-orchestration layer so that thousands of Glacier restore requests don't collide, exceed retrieval throughput limits, or blow the retrieval budget? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-restore-orchestration-layer-so-that-thousands-o-126728) |
