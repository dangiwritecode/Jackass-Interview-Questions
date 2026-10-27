# Bolt

**Tier:** Tier 2  |  **Business domain:** Payments  |  **Questions:** 17

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 4 | 4 | 4 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 4 | 4 | 0 | 4 |
| Data Structures & Algorithms (all profiles) | 5 | 5 | 5 | 5 | 5 | 5 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A Facade over four downstream services returns partial data when one dependency times out, but callers can't tell which fields are stale. How do you evolve the Facade's contract to communicate partial success and per-source freshness without leaking every subsystem's shape? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-facade-over-four-downstream-services-returns-partial-data-when-one-d-22439) |
| You must choose consistency boundaries for a real-time ride-matching + pricing + payment flow where matching must be low-latency-eventual but payment must be strongly-consistent. Walk me through where the transactional seam goes and why matching can't be a saga step. | expertise | SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-choose-consistency-boundaries-for-a-real-time-ride-matching-p-34147) |
| Design an event backbone for a global ride-hailing platform where per-driver ordering, sub-second matching latency, and multi-region resilience all matter at once. Where do these three goals conflict and how do you adjudicate the trade-off per data type? | expertise | SDE-2/3, Architect/Principal | Message Queues & Event-Driven Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-event-backbone-for-a-global-ride-hailing-platform-where-per--32656) |
| How would you architect a ride-hailing dispatch system to stay available and correct during a city-wide surge (concert lets out, storm hits), where matching must be near-real-time and geographically hot, without a single hot region toppling the service? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-ride-hailing-dispatch-system-to-stay-availab-32160) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a ride-hailing dispatch system to stay available and geographically correct during a city-wide surge, so a single hot region can't topple the matching engine and matching stays near-real-time? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-ride-hailing-dispatch-system-to-stay-available--38781) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a ride-hailing dispatch system to stay available and geographically correct during a city-wide surge (concert lets out, storm hits), so a single hot geo-region can't topple the matching engine while matching stays near-real-time? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-ride-hailing-dispatch-system-to-stay-available--52112) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What is withIdleness / idle-source handling, and why is it essential for sparse per-region order streams? | deep understanding | SDE-1/2, SDE-2/3 | Stream Processing (Apache Flink) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-withidleness-idle-source-handling-and-why-is-it-essential-for--121304) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You run a multi-active CockroachDB deployment. How do online schema changes work there under the hood and what constraints does that place on your migration policy? | expertise | SDE-2/3, Architect/Principal | Database Migrations & Versioning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-run-a-multi-active-cockroachdb-deployment-how-do-online-schema-cha-114250) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| When would you prefer quantile regression with XGBoost over point prediction, and how does that change your serving and monitoring? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-prefer-quantile-regression-with-xgboost-over-point-pred-65913) |
| How would you design a forecasting system that must produce forecasts for new regions launched weekly, with no code changes per region? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-forecasting-system-that-must-produce-forecasts--66400) |
| Why did you choose a global gradient-boosted model over per-series ARIMA for your forecasting fleet — what trade-offs did that involve? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-did-you-choose-a-global-gradient-boosted-model-over-per-series-ari-66373) |
| You must forecast at 15-minute granularity for ride demand — what changes vs daily forecasting in features, models, and infra? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-forecast-at-15-minute-granularity-for-ride-demand-what-change-66421) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Books Read by Members at an Exact Network Distance | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Breadth-First Search, Graph, Hash Table, Sorting | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=books-read-by-members-at-an-exact-network-distance-d1265) |
| Count Contiguous Subarrays With a Given Sum | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Hash Table, Prefix Sum | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-contiguous-subarrays-with-a-given-sum-d558) |
| Maximum Gain from a Single Buy and Later Sell | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Greedy, Prefix Minimum, Single Pass | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=maximum-gain-from-a-single-buy-and-later-sell-d121) |
| Minimum Remaining Length After Cancelling Reactive Pairs | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Greedy, Simulation, Stack, String | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=minimum-remaining-length-after-cancelling-reactive-pairs-d2526) |
| Uniform Letter Frequency Check | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Frequency Array, Hash Table, String | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=uniform-letter-frequency-check-d1838) |
