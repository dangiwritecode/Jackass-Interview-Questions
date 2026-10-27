# Gaana

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 22

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 3 | 2 | 10 | 10 | 6 | 10 |
| Fullstack | 4 | 4 | 3 | 4 | 3 | 6 |
| Data Engineer | 2 | 0 | 2 | 2 | 0 | 2 |
| Database Developer | 0 | 1 | 1 | 0 | 0 | 1 |
| ML Engineer | 1 | 0 | 3 | 3 | 1 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you implement 'concurrent session limit' (max 3 devices) enforcement, deciding which session to evict, and doing it correctly across a distributed session store under a race of two simultaneous logins? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-concurrent-session-limit-max-3-devices-enforce-26203) |
| Design a cross-region "max concurrent sessions per user = 1" enforcement. Explain why this needs a CP coordination point, what happens under partition, and the UX you'd choose when coordination is unavailable. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-cross-region-max-concurrent-sessions-per-user-1-enforcement-e-25722) |
| A recommendation service recomputes a sorted candidate set on every request; how would you incrementally maintain a heap of candidates as signals stream in, and what breaks when a score is updated in place? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-recommendation-service-recomputes-a-sorted-candidate-set-on-every-re-21937) |
| You want a fallback that returns cached or default data when a dependency fails. How do you keep the fallback from serving dangerously stale data during a long outage? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-a-fallback-that-returns-cached-or-default-data-when-a-depende-29876) |
| Design a music-player playlist supporting shuffle, repeat-one, and repeat-all where switching modes mid-song behaves predictably; which pattern owns 'what plays next' and how do you unit-test shuffle fairness? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-music-player-playlist-supporting-shuffle-repeat-one-and-repea-16486) |
| Design a music-player playlist with shuffle and repeat modes. Which pattern captures the play strategy? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-music-player-playlist-with-shuffle-and-repeat-modes-which-pat-9019) |
| How would you design a system to recommend songs or playlists to a music-streaming user? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | DSA/Coding Round, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-system-to-recommend-songs-or-playlists-to-a-mus-62135) |
| What does the ORDER BY ... LIMIT combination return and how does adding DESC change it? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-the-order-by-limit-combination-return-and-how-does-adding-de-11854) |
| How would you enforce a maximum of N active sessions per user at the database level to prevent runaway concurrency, and what are the pitfalls of enforcing this with a trigger versus in the app? | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-enforce-a-maximum-of-n-active-sessions-per-user-at-the-d-24469) |
| You need to store an ordered playlist where users reorder items frequently; compare an integer position column with gap-based ordering, a float position, and an ltree/fractional index, and their reorder costs. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-store-an-ordered-playlist-where-users-reorder-items-freque-24454) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a frontend architecture that supports real-time multi-device continuity (start on phone, continue on TV/web) — how do you sync session, playback position, and UI state across devices? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-frontend-architecture-that-supports-real-time-multi-device-co-40087) |
| How do you embed audio and video with native controls in HTML5? | basic concept | Fresher, SDE-1 | HTML | Online Assessment (OA), Phone Screen | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-embed-audio-and-video-with-native-controls-in-html5-1997) |
| What is the difference between the <source> element and the src attribute inside <video>? | intermediate experience | Fresher, SDE-1 | HTML | Online Assessment (OA), Phone Screen | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-difference-between-the-source-element-and-the-src-attribut-1998) |
| Design a music-player playlist supporting shuffle, repeat-one, and repeat-all where switching modes mid-song behaves predictably; which pattern owns 'what plays next' and how do you unit-test shuffle fairness? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-music-player-playlist-supporting-shuffle-repeat-one-and-repea-16486) |
| Design a music-player playlist with shuffle and repeat modes. Which pattern captures the play strategy? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-music-player-playlist-with-shuffle-and-repeat-modes-which-pat-9019) |
| What does the ORDER BY ... LIMIT combination return and how does adding DESC change it? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-the-order-by-limit-combination-return-and-how-does-adding-de-11854) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What does it mean for OLAP data to be 'historical' and why is that useful for a business? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-it-mean-for-olap-data-to-be-historical-and-why-is-that-usefu-118791) |
| Why do we say OLTP handles 'now' and OLAP handles 'over time'? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-do-we-say-oltp-handles-now-and-olap-handles-over-time-118839) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you model a many-to-many relationship that also needs an ordering (e.g., playlist tracks in sequence) while keeping reorders cheap? | deep understanding | SDE-1, SDE-1/2 | ER Diagrams & Schema Design | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-many-to-many-relationship-that-also-needs-an-ord-109482) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle the cold-start problem for a new model in an A/B test where the model needs warm-up data to perform well? | deep understanding | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-cold-start-problem-for-a-new-model-in-an-a-b-tes-67684) |
| How do you design offline evaluation for an XGBoost recommender that matches the online metric you actually care about? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-offline-evaluation-for-an-xgboost-recommender-that-m-65912) |
| How would you design a system to recommend songs or playlists to a music-streaming user? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | DSA/Coding Round, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-system-to-recommend-songs-or-playlists-to-a-mus-62135) |
