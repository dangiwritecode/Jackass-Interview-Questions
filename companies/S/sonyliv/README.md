# SonyLiv

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 33

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 3 | 3 | 13 | 15 | 13 | 15 |
| Fullstack | 2 | 2 | 7 | 9 | 8 | 9 |
| Data Engineer | 2 | 0 | 3 | 3 | 0 | 3 |
| Database Developer | 0 | 1 | 1 | 0 | 0 | 1 |
| ML Engineer | 1 | 0 | 4 | 4 | 1 | 4 |
| AI Engineer | 0 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you implement 'concurrent session limit' (max 3 devices) enforcement, deciding which session to evict, and doing it correctly across a distributed session store under a race of two simultaneous logins? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-concurrent-session-limit-max-3-devices-enforce-26203) |
| Your refresh endpoint is being hammered because access tokens are too short and every client refreshes in lockstep. How do you smooth this thundering herd (jitter, staggered expiry) without weakening security? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-refresh-endpoint-is-being-hammered-because-access-tokens-are-too--26154) |
| Design a cross-region "max concurrent sessions per user = 1" enforcement. Explain why this needs a CP coordination point, what happens under partition, and the UX you'd choose when coordination is unavailable. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-cross-region-max-concurrent-sessions-per-user-1-enforcement-e-25722) |
| You need a monotonically increasing, roughly time-ordered ID generator across many hosts (Snowflake-style). Walk through the bit layout, the clock-skew failure mode, and how you handle a backwards clock jump. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-a-monotonically-increasing-roughly-time-ordered-id-generator--28438) |
| Explain, at principal level, when to model cross-service consistency as a saga versus as a 'unit of work' that is deliberately allowed to be non-atomic because the business can tolerate and cheaply reconcile partial completion. Where's that line for a media-streaming entitlement flow? | expertise | SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-at-principal-level-when-to-model-cross-service-consistency-as--34187) |
| Design a video streaming platform's upload-and-transcode pipeline — from raw upload to multiple bitrate renditions ready for adaptive streaming. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-platform-s-upload-and-transcode-pipeline-from-20641) |
| Design the video metadata and view-count service — how do you store and serve near-real-time view counts for billions of videos without a write hotspot on popular ones? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-video-metadata-and-view-count-service-how-do-you-store-and--20643) |
| How does adaptive bitrate streaming (HLS/DASH) work at the system level, and how do you design the CDN and origin so a live match with 25M concurrent viewers doesn't collapse? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-adaptive-bitrate-streaming-hls-dash-work-at-the-system-level--20642) |
| Design a video-streaming quality selector that adapts to bandwidth. Which pattern picks the bitrate? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-quality-selector-that-adapts-to-bandwidth-whi-9020) |
| Your streaming platform must serve a live sports final to 50 million concurrent viewers with a hard, immovable start time. Walk me through the capacity, CDN, origin-shielding, and failover architecture, and how you rehearse it so there's no second chance to get it right. | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-streaming-platform-must-serve-a-live-sports-final-to-50-million-c-32156) |
| During a live event you expect 50x traffic on a serverless API — how do you pre-warm, raise concurrency limits, and load-test so the first users don't hit cold-start cascades? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Serverless | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-a-live-event-you-expect-50x-traffic-on-a-serverless-api-how-do--18450) |
| You must produce a report of 'active subscriptions per day' from a table of (subscription_id, start_date, end_date) ranges. How do you expand ranges into a daily series efficiently without generating a row per subscription per day naively? | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-produce-a-report-of-active-subscriptions-per-day-from-a-table-22168) |
| Compare WebSockets, SSE, and long-polling for pushing live scores to 500k viewers. What breaks first at scale for each, and how do you scale the fan-out layer horizontally? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-websockets-sse-and-long-polling-for-pushing-live-scores-to-500-22285) |
| Why is video usually served in small chunks rather than one big file? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-is-video-usually-served-in-small-chunks-rather-than-one-big-file-8908) |
| How would you build a live sports score or cricket scoreboard that updates in real time? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | WebSockets | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-live-sports-score-or-cricket-scoreboard-that-upd-3752) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're accountable for a live cricket final with tens of millions of concurrent viewers. Design the multi-CDN capacity, manifest-caching, and failover so a single provider saturating doesn't blackout the stream, and explain how you rehearse this before the actual event. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-accountable-for-a-live-cricket-final-with-tens-of-millions-of-c-39645) |
| You're accountable for a video platform where 90% of egress is a long tail of rarely-watched content. Design the tiered hot-edge / warm-regional / cold-origin storage-plus-CDN strategy that minimizes cost while keeping start latency acceptable, and quantify where each tier pays off. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-accountable-for-a-video-platform-where-90-of-egress-is-a-long-t-39662) |
| Design a video streaming platform's upload-and-transcode pipeline — from raw upload to multiple bitrate renditions ready for adaptive streaming. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-platform-s-upload-and-transcode-pipeline-from-20641) |
| Design the video metadata and view-count service — how do you store and serve near-real-time view counts for billions of videos without a write hotspot on popular ones? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-video-metadata-and-view-count-service-how-do-you-store-and--20643) |
| Design the video player web client: buffering strategy, quality switching, resume-from-position, and analytics beacons — how do you keep beacons reliable without hurting playback? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-video-player-web-client-buffering-strategy-quality-switchin-20644) |
| How does adaptive bitrate streaming (HLS/DASH) work at the system level, and how do you design the CDN and origin so a live match with 25M concurrent viewers doesn't collapse? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-adaptive-bitrate-streaming-hls-dash-work-at-the-system-level--20642) |
| Design a video-streaming quality selector that adapts to bandwidth. Which pattern picks the bitrate? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-quality-selector-that-adapts-to-bandwidth-whi-9020) |
| During a live event you expect 50x traffic on a serverless API — how do you pre-warm, raise concurrency limits, and load-test so the first users don't hit cold-start cascades? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Serverless | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-a-live-event-you-expect-50x-traffic-on-a-serverless-api-how-do--18450) |
| How would you build a live sports score or cricket scoreboard that updates in real time? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | WebSockets | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-live-sports-score-or-cricket-scoreboard-that-upd-3752) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What does it mean for OLAP data to be 'historical' and why is that useful for a business? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-it-mean-for-olap-data-to-be-historical-and-why-is-that-usefu-118791) |
| Why do we say OLTP handles 'now' and OLAP handles 'over time'? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-do-we-say-oltp-handles-now-and-olap-handles-over-time-118839) |
| Describe how you'd implement a keyed timer to close a user's session and flush aggregates if no activity arrives for 30 minutes. | deep understanding | SDE-1/2, SDE-2/3 | Stream Processing (Apache Flink) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-implement-a-keyed-timer-to-close-a-user-s-session-a-121291) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd expand (subscription_id, start_date, end_date) ranges into a daily 'active subscriptions per day' series without naively generating a row per subscription per day. | deep understanding | SDE-1, SDE-1/2 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-expand-subscription-id-start-date-end-date-ranges-in-107006) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you choose between a guardrail metric and a primary metric when evaluating a new model in an experiment? | deep understanding | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-choose-between-a-guardrail-metric-and-a-primary-metric-when-67679) |
| How would you approach building a churn-prediction model for a subscription streaming service? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-building-a-churn-prediction-model-for-a-subscri-62109) |
| How would you forecast concurrent viewers for a live-streamed cricket match with massive spike behavior? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-forecast-concurrent-viewers-for-a-live-streamed-cricket--66410) |
| What's your approach to forecasting a metric that has both weekly and yearly seasonality plus irregular holiday spikes? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-forecasting-a-metric-that-has-both-weekly-and--66394) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd measure whether a prompt change actually improved quality or just shifted which inputs pass, avoiding the illusion of improvement. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-measure-whether-a-prompt-change-actually-improved-qu-77977) |
