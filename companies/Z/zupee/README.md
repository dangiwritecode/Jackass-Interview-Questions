# Zupee

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 6 | 6 | 5 | 6 |
| Fullstack | 0 | 0 | 3 | 3 | 3 | 3 |
| Data Engineer | 1 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your leaderboard must be highly available and roughly right during partitions but exact at settlement time (e.g., prize payout). Design the two-mode system: AP live view + CP reconciliation, and how they hand off. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-must-be-highly-available-and-roughly-right-during-par-25730) |
| Design the class model for a leaderboard that must support seasonal resets, ties broken by earliest-achieved, and 'friends-only' views; how do you structure storage so all three queries stay fast? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-class-model-for-a-leaderboard-that-must-support-seasonal-re-22403) |
| How do you design a Memento-based game-save so that a save from an old version can still be loaded after you ship new features; what does forward/backward compatibility require of the memento format? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-memento-based-game-save-so-that-a-save-from-an-old-16481) |
| Your leaderboard gives correct top-K but rank queries for arbitrary users are slow at 10M players; how would you redesign the structure so both top-K and 'my rank' are fast, and what do you trade? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-gives-correct-top-k-but-rank-queries-for-arbitrary-us-16464) |
| How would you find a player's rank using ZRANK and ZREVRANK in a leaderboard? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-find-a-player-s-rank-using-zrank-and-zrevrank-in-a-leade-12167) |
| Design a leaderboard for a fantasy game showing live ranks for 10M users during a match. How do you compute and serve top-N plus a given user's rank efficiently under a huge write burst? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-for-a-fantasy-game-showing-live-ranks-for-10m-use-16397) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design a Memento-based game-save so that a save from an old version can still be loaded after you ship new features; what does forward/backward compatibility require of the memento format? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-memento-based-game-save-so-that-a-save-from-an-old-16481) |
| Your leaderboard gives correct top-K but rank queries for arbitrary users are slow at 10M players; how would you redesign the structure so both top-K and 'my rank' are fast, and what do you trade? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leaderboard-gives-correct-top-k-but-rank-queries-for-arbitrary-us-16464) |
| Design a leaderboard for a fantasy game showing live ranks for 10M users during a match. How do you compute and serve top-N plus a given user's rank efficiently under a huge write burst? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-leaderboard-for-a-fantasy-game-showing-live-ranks-for-10m-use-16397) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Why might a gaming company keep 'live match state' in OLTP but 'player retention trends' in OLAP? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-a-gaming-company-keep-live-match-state-in-oltp-but-player-re-118856) |
