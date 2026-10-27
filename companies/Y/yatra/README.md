# Yatra

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 10 | 10 | 6 | 10 |
| Fullstack | 0 | 0 | 3 | 4 | 3 | 4 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| During an interview you're asked to make a "seat hold" survive partitions without double-booking. Contrast a CP reservation (etcd/ZK lease) vs an AP optimistic-hold-with-reconciliation and give the trade-off table. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-an-interview-you-re-asked-to-make-a-seat-hold-survive-partition-25661) |
| A booking system must answer 'is any sub-range of this resource free' under heavy concurrent booking; how do you prevent double-booking races algorithmically and what structure supports fast free-range queries? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-booking-system-must-answer-is-any-sub-range-of-this-resource-free-un-22010) |
| Design a saga for booking a trip: flight + hotel + car, each a separate provider with its own failure modes. Which fails often, and how does that shape your step ordering? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-saga-for-booking-a-trip-flight-hotel-car-each-a-separate-prov-28790) |
| Design a hotel/flight booking system that prevents double-booking a seat under high concurrency — how do you hold inventory during the payment window and release on timeout? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-flight-booking-system-that-prevents-double-booking-a-se-20702) |
| Design a seat/slot booking backend (concerts/flights) that holds a seat during the payment window and releases it on timeout at high contention — how do you avoid overbooking and hold leaks? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-seat-slot-booking-backend-concerts-flights-that-holds-a-seat--28401) |
| How would you design a Kafka-based saga orchestration for a multi-step booking flow, ensuring compensating actions run if a later step fails? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-kafka-based-saga-orchestration-for-a-multi-step-24863) |
| How does TIMESTAMP's automatic timezone conversion differ from DATETIME, and how can it bite you across regions? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-timestamp-s-automatic-timezone-conversion-differ-from-datetim-11875) |
| How would you design a booking system that must never double-book a resource; contrast a unique constraint, an exclusion constraint with tstzrange, and app-level locking including edge cases. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-that-must-never-double-book-a-re-18127) |
| How would you design a two-phase commit alternative (saga) for a multi-service booking that reserves a flight, a hotel, and a car — and what are your compensating actions when step 2 fails? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-two-phase-commit-alternative-saga-for-a-multi-s-16328) |
| You must design an endpoint that returns whether any of n items conflicts with any of m existing bookings; how do you avoid the O(n*m) overlap check with interval trees or sorted sweep, and what's the space cost? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-an-endpoint-that-returns-whether-any-of-n-items-confli-22065) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a hotel/flight booking system that prevents double-booking a seat under high concurrency — how do you hold inventory during the payment window and release on timeout? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-flight-booking-system-that-prevents-double-booking-a-se-20702) |
| How would you design a booking system that must never double-book a resource; contrast a unique constraint, an exclusion constraint with tstzrange, and app-level locking including edge cases. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-that-must-never-double-book-a-re-18127) |
| How would you design a two-phase commit alternative (saga) for a multi-service booking that reserves a flight, a hotel, and a car — and what are your compensating actions when step 2 fails? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-two-phase-commit-alternative-saga-for-a-multi-s-16328) |
| A bar-raiser probe: your team celebrates a green Lighthouse score but retention hasn't moved. Convince me performance work was worth the headcount, or tell me honestly it wasn't. How do you separate perf theater from perf that matters? | expertise | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-probe-your-team-celebrates-a-green-lighthouse-score-but-r-40239) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you A/B test replacing a logistic regression scoring model with XGBoost when the business cares mostly about downstream conversion, not AUC? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-a-b-test-replacing-a-logistic-regression-scoring-model-w-65879) |
