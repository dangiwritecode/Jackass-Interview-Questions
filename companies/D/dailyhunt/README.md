# Dailyhunt

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 23

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 5 | 5 | 5 | 5 | 3 | 5 |
| Fullstack | 1 | 1 | 14 | 14 | 13 | 14 |
| Data Engineer | 1 | 0 | 1 | 1 | 0 | 1 |
| ML Engineer | 0 | 0 | 2 | 2 | 0 | 2 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you implement a like or upvote counter that must never go below zero in Redis? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-a-like-or-upvote-counter-that-must-never-go-be-12157) |
| How would you use SETBIT and BITCOUNT to track daily active users across a 30-day window? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-setbit-and-bitcount-to-track-daily-active-users-acro-12214) |
| How would you decide between a pull-based and a push-based fan-out for a social feed? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-between-a-pull-based-and-a-push-based-fan-out-for-13049) |
| How would you design a counter (likes, views) that scales to very high write rates while staying reasonably accurate? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-counter-likes-views-that-scales-to-very-high-wr-13128) |
| How would you handle a celebrity user whose activity overwhelms a single partition? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-a-celebrity-user-whose-activity-overwhelms-a-sing-13071) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a data model on the client for threaded comments (nested replies) that renders efficiently and loads deeper levels on demand. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-model-on-the-client-for-threaded-comments-nested-replies-21275) |
| Design a feed that supports pull-to-refresh and background refresh — how do you merge new data with what's already displayed without losing position? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-feed-that-supports-pull-to-refresh-and-background-refresh-how-21263) |
| Design a feed's client-side ranking/deduplication so items already seen aren't reshown and personalization signals are respected. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-feed-s-client-side-ranking-deduplication-so-items-already-see-21305) |
| Design a feed's read/unread and view-tracking system that batches impression events without hurting scroll performance. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-feed-s-read-unread-and-view-tracking-system-that-batches-impr-21249) |
| Design a news feed that mixes ads, recommendations, and organic posts — how do you keep the UI simple while sources have different shapes and cadences? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-news-feed-that-mixes-ads-recommendations-and-organic-posts-ho-21240) |
| Design a video/media feed (like Reels) — how do you manage preloading, playback lifecycle, and only one item playing at a time? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-video-media-feed-like-reels-how-do-you-manage-preloading-play-21293) |
| Design the data-fetching layer for a feed so a user scrolling fast never sees duplicate or missing items across page boundaries. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-data-fetching-layer-for-a-feed-so-a-user-scrolling-fast-nev-21231) |
| How do you handle a feed request that partially fails (some items error) — do you show partial data, retry, or skeleton, and how do you decide? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-a-feed-request-that-partially-fails-some-items-error-21300) |
| How do you prevent layout shift (CLS) in a feed where images, ads, and dynamic content load at different times? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-prevent-layout-shift-cls-in-a-feed-where-images-ads-and-dyn-21272) |
| How would you design the component architecture for an infinite-scrolling news feed so that appending thousands of items doesn't degrade scroll performance? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-component-architecture-for-an-infinite-scroll-21212) |
| How would you handle pagination + real-time inserts together in a feed (new posts arrive while the user is on page 3) without jarring the layout? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-pagination-real-time-inserts-together-in-a-feed-n-21254) |
| How would you implement infinite scroll while keeping deep links and browser back-button restoring the exact scroll position and loaded pages? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-infinite-scroll-while-keeping-deep-links-and-b-21227) |
| Your infinite scroll feed leaks memory as users scroll for a long session — how do you diagnose and fix it while keeping scroll position stable? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-infinite-scroll-feed-leaks-memory-as-users-scroll-for-a-long-sess-21220) |
| How would you implement a like or upvote counter that must never go below zero in Redis? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-a-like-or-upvote-counter-that-must-never-go-be-12157) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| If your task is to build a 'weekly signups' report, which system do you pull from and why? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=if-your-task-is-to-build-a-weekly-signups-report-which-system-do-you-p-118798) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd handle multi-language content in a recommender when embeddings for low-resource languages are much weaker. | deep understanding | SDE-1/2, SDE-2/3 | Recommendation Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-handle-multi-language-content-in-a-recommender-when--66552) |
| How would you handle recommendation freshness for a news or short-video app where item value decays within hours? | deep understanding | SDE-1/2, SDE-2/3 | Recommendation Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-recommendation-freshness-for-a-news-or-short-vide-66537) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you evaluate cross-lingual quality parity so an English-first model isn't shipped with a silent 30% quality gap in Hindi or Tamil? | deep understanding | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-cross-lingual-quality-parity-so-an-english-first-m-86877) |
