# Winzo

**Tier:** Tier 4  |  **Business domain:** Gaming  |  **Questions:** 21

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 3 | 3 | 12 | 12 | 5 | 12 |
| Fullstack | 0 | 0 | 4 | 5 | 4 | 5 |
| Data Engineer | 1 | 0 | 1 | 1 | 0 | 1 |
| Database Developer | 0 | 1 | 1 | 1 | 1 | 2 |
| Data Structures & Algorithms (all profiles) | 1 | 1 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your leaderboard must be highly available and roughly right during partitions but exact at settlement time (e.g., prize payout). Design the two-mode system: AP live view + CP reconciliation, and how they hand off. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-must-be-highly-available-and-roughly-right-during-par-25730) |
| You maintain a leaderboard where scores decay over time; how do you avoid recomputing every entry on each read, and what structure lets you apply a lazy decay factor at query time? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-maintain-a-leaderboard-where-scores-decay-over-time-how-do-you-avo-21975) |
| Design a leaderboard service for a game with 50M players and live rank updates — how do you compute and serve a user's rank and the top-N in real time? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-service-for-a-game-with-50m-players-and-live-rank-20661) |
| Your leaderboard uses a sorted set in Redis but a single game has 50M entries — how do you shard it, compute global rank across shards, and cap memory? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-uses-a-sorted-set-in-redis-but-a-single-game-has-50m--20662) |
| Design the class model for a leaderboard that must support seasonal resets, ties broken by earliest-achieved, and 'friends-only' views; how do you structure storage so all three queries stay fast? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-class-model-for-a-leaderboard-that-must-support-seasonal-re-22403) |
| A leaderboard must return a specific user's rank and a page around them for millions of users in low latency; design the schema, index, and query and discuss recompute vs live rank. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-leaderboard-must-return-a-specific-user-s-rank-and-a-page-around-the-18136) |
| Design a Redis-backed sliding leaderboard that only counts activity in the trailing 24 hours, so scores decay automatically without a cron sweep. | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-redis-backed-sliding-leaderboard-that-only-counts-activity-in-24689) |
| How do ZINCRBY and ZSCORE help you update and read a single player's leaderboard score? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-zincrby-and-zscore-help-you-update-and-read-a-single-player-s-l-12166) |
| How does ZREMRANGEBYRANK help you trim a leaderboard to only the top scores? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-zremrangebyrank-help-you-trim-a-leaderboard-to-only-the-top-s-12170) |
| How would you find a player's rank using ZRANK and ZREVRANK in a leaderboard? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-find-a-player-s-rank-using-zrank-and-zrevrank-in-a-leade-12167) |
| Your Redis Sorted Set leaderboard needs ties broken deterministically by earliest-achieved time — how do you encode two dimensions into one score without losing precision? | deep understanding | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-redis-sorted-set-leaderboard-needs-ties-broken-deterministically--24731) |
| Design a leaderboard for a fantasy game showing live ranks for 10M users during a match. How do you compute and serve top-N plus a given user's rank efficiently under a huge write burst? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-for-a-fantasy-game-showing-live-ranks-for-10m-use-16397) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a leaderboard service for a game with 50M players and live rank updates — how do you compute and serve a user's rank and the top-N in real time? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-service-for-a-game-with-50m-players-and-live-rank-20661) |
| You must architect a fantasy-sports contest platform that locks lineups at match start scores millions of teams live and pays winners atomically — how do you compute live leaderboards handle a mid-match data correction and settle prize money correctly? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-a-fantasy-sports-contest-platform-that-locks-lineup-39493) |
| Your leaderboard uses a sorted set in Redis but a single game has 50M entries — how do you shard it, compute global rank across shards, and cap memory? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-uses-a-sorted-set-in-redis-but-a-single-game-has-50m--20662) |
| A leaderboard must return a specific user's rank and a page around them for millions of users in low latency; design the schema, index, and query and discuss recompute vs live rank. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-leaderboard-must-return-a-specific-user-s-rank-and-a-page-around-the-18136) |
| Design a leaderboard for a fantasy game showing live ranks for 10M users during a match. How do you compute and serve top-N plus a given user's rank efficiently under a huge write burst? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-for-a-fantasy-game-showing-live-ranks-for-10m-use-16397) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Why might a gaming company keep 'live match state' in OLTP but 'player retention trends' in OLAP? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-a-gaming-company-keep-live-match-state-in-oltp-but-player-re-118856) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect the 'settlement vs live' reconciliation for a real-money leaderboard/tournament so the live view is AP and roughly-right but the payout uses a CP snapshot, and prove a mid-window partition can't cause a payout the settlement wouldn't allow? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-settlement-vs-live-reconciliation-for-a-re-111610) |
| How would you build leaderboard queries returning a user's exact rank among millions in real time? Compare window-function ranking, a maintained rank column, and Redis sorted sets. | deep understanding | SDE-1, SDE-1/2 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-leaderboard-queries-returning-a-user-s-exact-rank--107013) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Tightest Interval Touching Every Sorted Group | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Hash Table, Heap (Priority Queue), K-way Merge, Sliding Window, Sorting, Two Pointers | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=tightest-interval-touching-every-sorted-group-d617) |
