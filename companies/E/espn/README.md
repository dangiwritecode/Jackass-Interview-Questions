# ESPN

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 5 | 5 | 4 | 5 |
| Fullstack | 1 | 1 | 2 | 4 | 3 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you cache a value whose freshness requirement changes over its lifetime — fresh when an event is live, stale-tolerant once it ends — and encode that in the caching layer itself? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-cache-a-value-whose-freshness-requirement-changes-over-i-25427) |
| Explain how you'd cache and serve a real-time-ish scoreboard (updates every few seconds) to millions without hitting origin per request. Compare short-TTL micro-caching with jitter, edge push/purge, and an edge-KV write-through approach. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-cache-and-serve-a-real-time-ish-scoreboard-updates-e-29742) |
| How would you cache and serve a real-time-ish feed (e.g., cricket scores) where users want freshness but you can't hit origin per request? Discuss micro-caching, TTL jitter, and edge push. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-cache-and-serve-a-real-time-ish-feed-e-g-cricket-scores--20907) |
| Compare WebSockets, SSE, and long-polling for pushing live scores to 500k viewers. What breaks first at scale for each, and how do you scale the fan-out layer horizontally? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-websockets-sse-and-long-polling-for-pushing-live-scores-to-500-22285) |
| How would you build a live sports score or cricket scoreboard that updates in real time? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | WebSockets | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-live-sports-score-or-cricket-scoreboard-that-upd-3752) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you cache and serve a real-time-ish feed (e.g., cricket scores) where users want freshness but you can't hit origin per request? Discuss micro-caching, TTL jitter, and edge push. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-cache-and-serve-a-real-time-ish-feed-e-g-cricket-scores--20907) |
| How do you architect the client for a product that must scale a single websocket/SSE fan-out to millions of concurrent viewers (live sports, elections) without the browser or the edge melting? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-client-for-a-product-that-must-scale-a-single-40054) |
| Design the architecture for a live-sports second-screen experience (live scores commentary polls) for 50M concurrent viewers during a final — how do you fan out state updates run interactive polls and degrade gracefully when a wicket falls and everyone refreshes at once? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-for-a-live-sports-second-screen-experience-liv-39432) |
| How would you build a live sports score or cricket scoreboard that updates in real time? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | WebSockets | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-live-sports-score-or-cricket-scoreboard-that-upd-3752) |
