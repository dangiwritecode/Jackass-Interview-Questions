# Goibibo

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 5 | 5 | 11 | 10 | 8 | 11 |
| Fullstack | 1 | 1 | 2 | 2 | 2 | 2 |
| Database Developer | 1 | 2 | 2 | 1 | 1 | 2 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| During an interview you're asked to make a "seat hold" survive partitions without double-booking. Contrast a CP reservation (etcd/ZK lease) vs an AP optimistic-hold-with-reconciliation and give the trade-off table. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-an-interview-you-re-asked-to-make-a-seat-hold-survive-partition-25661) |
| For a seat-booking system (movies/flights), why does double-booking make CP almost mandatory during a partition? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-a-seat-booking-system-movies-flights-why-does-double-booking-make--13218) |
| A booking system must answer 'is any sub-range of this resource free' under heavy concurrent booking; how do you prevent double-booking races algorithmically and what structure supports fast free-range queries? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-booking-system-must-answer-is-any-sub-range-of-this-resource-free-un-22010) |
| Design a schema for a hotel/flight booking system that prevents double-booking the same seat. | deep understanding | Fresher, SDE-1, SDE-1/2 | DBMS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-schema-for-a-hotel-flight-booking-system-that-prevents-double-8384) |
| Design a saga for booking a trip: flight + hotel + car, each a separate provider with its own failure modes. Which fails often, and how does that shape your step ordering? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-saga-for-booking-a-trip-flight-hotel-car-each-a-separate-prov-28790) |
| Design a hotel/flight booking system that prevents double-booking a seat under high concurrency — how do you hold inventory during the payment window and release on timeout? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-flight-booking-system-that-prevents-double-booking-a-se-20702) |
| Design a seat/slot booking backend (concerts/flights) that holds a seat during the payment window and releases it on timeout at high contention — how do you avoid overbooking and hold leaks? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-seat-slot-booking-backend-concerts-flights-that-holds-a-seat--28401) |
| How would you design a Kafka-based saga orchestration for a multi-step booking flow, ensuring compensating actions run if a later step fails? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-kafka-based-saga-orchestration-for-a-multi-step-24863) |
| Design a hotel or a meeting-room booking system. Model rooms slots and bookings. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-or-a-meeting-room-booking-system-model-rooms-slots-and--927) |
| Probe: how does your booking design behave if the same request is retried by the client twice? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=probe-how-does-your-booking-design-behave-if-the-same-request-is-retri-9035) |
| How does TIMESTAMP's automatic timezone conversion differ from DATETIME, and how can it bite you across regions? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-timestamp-s-automatic-timezone-conversion-differ-from-datetim-11875) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a hotel/flight booking system that prevents double-booking a seat under high concurrency — how do you hold inventory during the payment window and release on timeout? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-flight-booking-system-that-prevents-double-booking-a-se-20702) |
| Design a hotel or a meeting-room booking system. Model rooms slots and bookings. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-or-a-meeting-room-booking-system-model-rooms-slots-and--927) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you model a seat-booking system (movies/flights) so two users can't book the same seat, and where does the constraint live in the ER design? | deep understanding | SDE-1, SDE-1/2 | ER Diagrams & Schema Design | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-seat-booking-system-movies-flights-so-two-users--109505) |
| In a hotel booking system, which parts are OLTP and which reporting parts would be OLAP? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-a-hotel-booking-system-which-parts-are-oltp-and-which-reporting-par-105043) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you A/B test replacing a logistic regression scoring model with XGBoost when the business cares mostly about downstream conversion, not AUC? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-a-b-test-replacing-a-logistic-regression-scoring-model-w-65879) |
