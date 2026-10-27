# Rappi

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 27

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 5 | 5 | 5 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 2 | 2 | 0 | 2 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 9 | 11 | 2 | 11 |
| AI Engineer | 0 | 0 | 2 | 3 | 1 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Two staff engineers deadlock in a design review: one insists the new order service must be CP, the other AP. As the deciding architect, how do you run the arbitration so the outcome is principled and both sides feel heard? | deep understanding | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=two-staff-engineers-deadlock-in-a-design-review-one-insists-the-new-or-32208) |
| A Facade over four downstream services returns partial data when one dependency times out, but callers can't tell which fields are stale. How do you evolve the Facade's contract to communicate partial success and per-source freshness without leaking every subsystem's shape? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-facade-over-four-downstream-services-returns-partial-data-when-one-d-22439) |
| A State-pattern order machine must persist state across service restarts, but a crash between a side effect and the state write left the DB out of sync with reality. How do you make state transitions durable and recoverable without double-executing side effects? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-state-pattern-order-machine-must-persist-state-across-service-restar-22455) |
| A downstream sink can only handle 5000 writes/sec but the topic bursts to 50000/sec. Design the consumer flow-control so you neither drop data nor OOM. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-downstream-sink-can-only-handle-5000-writes-sec-but-the-topic-bursts-24838) |
| How would you design the availability architecture of a food-delivery platform during peak dinner hours across many cities, where you have three coupled real-time systems (search, dispatch, tracking) and any one saturating cascades into the others? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-availability-architecture-of-a-food-delivery--32166) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the frontend architecture for a super-app with dozens of mini-apps (payments, food, travel) inside one shell — how do you sandbox, lazy-load, and share auth/session across mini-apps? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-frontend-architecture-for-a-super-app-with-dozens-of-mini-a-40079) |
| How do you decide the migration order between the data tier and the API tier when the frontend team wants new APIs now but the DB split will take a year? | deep understanding | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-migration-order-between-the-data-tier-and-the-ap-40928) |
| You are asked to unify authentication across a portfolio of consumer apps under one account system (a super-app move). Threat-model the aggregation risk: one account now unlocks payments, chat, and commerce. How does blast radius change and how do you contain it? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-unify-authentication-across-a-portfolio-of-consumer-a-41313) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a food-delivery platform's peak-hour availability across coupled real-time systems (search, dispatch, tracking) so that one saturating subsystem doesn't cascade into the others across many cities at once, and how do you isolate a single city's meltdown? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-food-delivery-platform-s-peak-hour-availabil-52113) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do processing-time and event-time windows differ when computing daily revenue totals across timezones, and which do you pick? | intermediate experience | SDE-1/2, SDE-2/3 | Stream Processing (Apache Flink) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-processing-time-and-event-time-windows-differ-when-computing-da-121270) |
| How do you keep event-time watermarks advancing when one Kafka partition goes idle in a low-traffic region? | deep understanding | SDE-1/2, SDE-2/3 | Stream Processing (Apache Flink) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-event-time-watermarks-advancing-when-one-kafka-partiti-121303) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain the CAP nuance where a database offers 'strong consistency within a region, eventual across regions'; how do you prevent an application from unknowingly reading cross-region and assuming the strong guarantee, and how do you enforce region-affinity in the data layer? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-cap-nuance-where-a-database-offers-strong-consistency-with-111603) |
| How would you architect the data layer for a global ride/food/payments super-app where each subdomain genuinely needs a different store but they share identity and money? | expertise | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-data-layer-for-a-global-ride-food-payments-114621) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide the retraining cadence for an XGBoost model: fixed schedule, drift-triggered, or performance-triggered, and what are the trade-offs? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-retraining-cadence-for-an-xgboost-model-fixed-sc-65895) |
| When would you prefer quantile regression with XGBoost over point prediction, and how does that change your serving and monitoring? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-prefer-quantile-regression-with-xgboost-over-point-pred-65913) |
| Describe how you'd tune under data imbalance across regions so no single geography's metric dominates the objective. | deep understanding | SDE-1/2, SDE-2/3 | Hyperparameter Tuning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-tune-under-data-imbalance-across-regions-so-no-sing-66053) |
| Your model's F1 improved in CV but degraded on the holdout month — what evaluation-setup mistakes would you check first? | intermediate experience | SDE-1/2, SDE-2/3 | Model Evaluation Metrics | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-model-s-f1-improved-in-cv-but-degraded-on-the-holdout-month-what--65785) |
| How do you design a rollback strategy when a freshly retrained model degrades a metric that only surfaces days after deployment? | deep understanding | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-rollback-strategy-when-a-freshly-retrained-model-d-72383) |
| How would you decide whether to retrain versus adapt via domain adaptation when entering a new geography or market segment? | deep understanding | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-to-retrain-versus-adapt-via-domain-adapta-72401) |
| How do you evaluate whether adding exogenous weather data actually improves forecasts or just overfits noise? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-whether-adding-exogenous-weather-data-actually-imp-66414) |
| How do you serve pre-computed forecasts vs on-demand forecasts, and when is each the right architectural choice? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-serve-pre-computed-forecasts-vs-on-demand-forecasts-and-whe-66380) |
| How would you design a forecasting system that must produce forecasts for new regions launched weekly, with no code changes per region? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-forecasting-system-that-must-produce-forecasts--66400) |
| Why did you choose a global gradient-boosted model over per-series ARIMA for your forecasting fleet — what trade-offs did that involve? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-did-you-choose-a-global-gradient-boosted-model-over-per-series-ari-66373) |
| You need forecasts at both 1-hour and 1-day horizons from the same data — do you build one model or two, and why? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-forecasts-at-both-1-hour-and-1-day-horizons-from-the-same-dat-66459) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Why not just let every model pull features directly from the source systems at inference time instead of a feature store, and when is that actually the right call? | deep understanding | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-not-just-let-every-model-pull-features-directly-from-the-source-sy-84340) |
| Walk through how you would design an A/B test to compare a TF-IDF baseline against a transformer classifier when your online conversion metric is noisy and low-volume. | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-through-how-you-would-design-an-a-b-test-to-compare-a-tf-idf-base-79407) |
| Your classifier accuracy dropped only in one region. How would you trace whether it is data, language, or feature-availability driven? | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-classifier-accuracy-dropped-only-in-one-region-how-would-you-trac-79457) |
