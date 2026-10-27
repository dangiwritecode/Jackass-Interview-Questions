# Zee5

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 25

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 11 | 11 | 10 | 11 |
| Fullstack | 2 | 2 | 5 | 6 | 6 | 7 |
| Data Engineer | 2 | 0 | 3 | 3 | 0 | 3 |
| ML Engineer | 1 | 0 | 3 | 3 | 2 | 3 |
| AI Engineer | 0 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you implement 'concurrent session limit' (max 3 devices) enforcement, deciding which session to evict, and doing it correctly across a distributed session store under a race of two simultaneous logins? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-concurrent-session-limit-max-3-devices-enforce-26203) |
| Your refresh endpoint is being hammered because access tokens are too short and every client refreshes in lockstep. How do you smooth this thundering herd (jitter, staggered expiry) without weakening security? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-refresh-endpoint-is-being-hammered-because-access-tokens-are-too--26154) |
| Design a cross-region "max concurrent sessions per user = 1" enforcement. Explain why this needs a CP coordination point, what happens under partition, and the UX you'd choose when coordination is unavailable. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-cross-region-max-concurrent-sessions-per-user-1-enforcement-e-25722) |
| Estimate the CDN offload ratio needed to make a video-heavy site's origin bandwidth affordable, and describe how cache-hit-ratio drives both cost and origin capacity. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=estimate-the-cdn-offload-ratio-needed-to-make-a-video-heavy-site-s-ori-30114) |
| Estimate the compute and cost of re-encoding a 100k-hour video catalog into 5 renditions. How would you schedule it to minimize cost using Spot and off-peak capacity? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=estimate-the-compute-and-cost-of-re-encoding-a-100k-hour-video-catalog-30095) |
| Design a video streaming platform's upload-and-transcode pipeline — from raw upload to multiple bitrate renditions ready for adaptive streaming. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-platform-s-upload-and-transcode-pipeline-from-20641) |
| Design the video metadata and view-count service — how do you store and serve near-real-time view counts for billions of videos without a write hotspot on popular ones? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-video-metadata-and-view-count-service-how-do-you-store-and--20643) |
| How does adaptive bitrate streaming (HLS/DASH) work at the system level, and how do you design the CDN and origin so a live match with 25M concurrent viewers doesn't collapse? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-adaptive-bitrate-streaming-hls-dash-work-at-the-system-level--20642) |
| Design a video-streaming quality selector that adapts to bandwidth. Which pattern picks the bitrate? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-quality-selector-that-adapts-to-bandwidth-whi-9020) |
| You must produce a report of 'active subscriptions per day' from a table of (subscription_id, start_date, end_date) ranges. How do you expand ranges into a daily series efficiently without generating a row per subscription per day naively? | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-produce-a-report-of-active-subscriptions-per-day-from-a-table-22168) |
| Why is video usually served in small chunks rather than one big file? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-is-video-usually-served-in-small-chunks-rather-than-one-big-file-8908) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a video streaming/transcoding + delivery pipeline (Mux/AWS MediaConvert vs bespoke FFmpeg fleet) when both egress cost and playback quality at scale drive the economics? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-video-streaming-transcoding-deliv-41065) |
| How does adaptive bitrate streaming (HLS/DASH) use HTTP to adjust video quality to bandwidth? | deep understanding | Fresher, SDE-1 | Computer Networks | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-adaptive-bitrate-streaming-hls-dash-use-http-to-adjust-video--8715) |
| Design a video streaming platform's upload-and-transcode pipeline — from raw upload to multiple bitrate renditions ready for adaptive streaming. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-platform-s-upload-and-transcode-pipeline-from-20641) |
| Design the video metadata and view-count service — how do you store and serve near-real-time view counts for billions of videos without a write hotspot on popular ones? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-video-metadata-and-view-count-service-how-do-you-store-and--20643) |
| Design the video player web client: buffering strategy, quality switching, resume-from-position, and analytics beacons — how do you keep beacons reliable without hurting playback? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-video-player-web-client-buffering-strategy-quality-switchin-20644) |
| How does adaptive bitrate streaming (HLS/DASH) work at the system level, and how do you design the CDN and origin so a live match with 25M concurrent viewers doesn't collapse? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-adaptive-bitrate-streaming-hls-dash-work-at-the-system-level--20642) |
| Design a video-streaming quality selector that adapts to bandwidth. Which pattern picks the bitrate? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-streaming-quality-selector-that-adapts-to-bandwidth-whi-9020) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What does it mean for OLAP data to be 'historical' and why is that useful for a business? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-it-mean-for-olap-data-to-be-historical-and-why-is-that-usefu-118791) |
| Why do we say OLTP handles 'now' and OLAP handles 'over time'? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-do-we-say-oltp-handles-now-and-olap-handles-over-time-118839) |
| Describe how you'd implement a keyed timer to close a user's session and flush aggregates if no activity arrives for 30 minutes. | deep understanding | SDE-1/2, SDE-2/3 | Stream Processing (Apache Flink) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-implement-a-keyed-timer-to-close-a-user-s-session-a-121291) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you approach building a churn-prediction model for a subscription streaming service? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-building-a-churn-prediction-model-for-a-subscri-62109) |
| How would you design a churn-prediction system whose predictions feed automated retention campaigns without creating a self-fulfilling feedback loop? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-churn-prediction-system-whose-predictions-feed--66716) |
| How would you forecast concurrent viewers for a live-streamed cricket match with massive spike behavior? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-forecast-concurrent-viewers-for-a-live-streamed-cricket--66410) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd measure whether a prompt change actually improved quality or just shifted which inputs pass, avoiding the illusion of improvement. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-measure-whether-a-prompt-change-actually-improved-qu-77977) |
