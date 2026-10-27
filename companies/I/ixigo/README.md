# ixigo

**Tier:** Tier 3  |  **Business domain:** E-commerce  |  **Questions:** 31

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 8 | 8 | 12 | 12 | 8 | 16 |
| Fullstack | 4 | 4 | 3 | 4 | 3 | 8 |
| Data Engineer | 1 | 0 | 1 | 1 | 0 | 1 |
| Database Developer | 3 | 5 | 5 | 0 | 0 | 5 |
| ML Engineer | 1 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A person travels from A to B at 30 km/h and returns at 20 km/h. If the total time is 5 hours find the distance between A and B. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-person-travels-from-a-to-b-at-30-km-h-and-returns-at-20-km-h-if-the--15789) |
| A train 150 m long crosses a bridge 350 m long in 25 seconds. Find its speed in km/h. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-150-m-long-crosses-a-bridge-350-m-long-in-25-seconds-find-its--15813) |
| A train travelling at 54 km/h crosses a man running at 9 km/h in the opposite direction in 4 seconds. Find the length of the train. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-travelling-at-54-km-h-crosses-a-man-running-at-9-km-h-in-the-o-15862) |
| Two trains of length 100 m and 150 m run on parallel tracks in the same direction at 50 and 40 km/h. How long does the faster take to overtake the slower? | deep understanding | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=two-trains-of-length-100-m-and-150-m-run-on-parallel-tracks-in-the-sam-15829) |
| During an interview you're asked to make a "seat hold" survive partitions without double-booking. Contrast a CP reservation (etcd/ZK lease) vs an AP optimistic-hold-with-reconciliation and give the trade-off table. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-an-interview-you-re-asked-to-make-a-seat-hold-survive-partition-25661) |
| For a seat-booking system (movies/flights), why does double-booking make CP almost mandatory during a partition? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-a-seat-booking-system-movies-flights-why-does-double-booking-make--13218) |
| How would you let a booking system stay 'partially available' — browse-yes, book-no — during a partition, in CAP terms? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-let-a-booking-system-stay-partially-available-browse-yes-13219) |
| A booking system must answer 'is any sub-range of this resource free' under heavy concurrent booking; how do you prevent double-booking races algorithmically and what structure supports fast free-range queries? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-booking-system-must-answer-is-any-sub-range-of-this-resource-free-un-22010) |
| Design a hotel/flight booking system that prevents double-booking a seat under high concurrency — how do you hold inventory during the payment window and release on timeout? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-flight-booking-system-that-prevents-double-booking-a-se-20702) |
| Design a seat/slot booking backend (concerts/flights) that holds a seat during the payment window and releases it on timeout at high contention — how do you avoid overbooking and hold leaks? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-seat-slot-booking-backend-concerts-flights-that-holds-a-seat--28401) |
| Probe: how does your booking design behave if the same request is retried by the client twice? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=probe-how-does-your-booking-design-behave-if-the-same-request-is-retri-9035) |
| How would you design a booking system that must never double-book a resource; contrast a unique constraint, an exclusion constraint with tstzrange, and app-level locking including edge cases. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-that-must-never-double-book-a-re-18127) |
| A REST endpoint accepts user-supplied timezone and date-range filters, and you keep getting off-by-one-day bugs at DST boundaries. How do you design the contract and server logic to make date handling unambiguous? | intermediate experience | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-rest-endpoint-accepts-user-supplied-timezone-and-date-range-filters--24018) |
| How would you design a booking system (seats, slots) that stays consistent under high concurrency? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-seats-slots-that-stays-consisten-13089) |
| You're asked to implement a 'reserve then confirm' seat-hold that auto-expires in 5 minutes. Would you store an expiry timestamp and filter, use a TTL job, or use FOR UPDATE SKIP LOCKED reclamation? Compare correctness under concurrent reservations. | expertise | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-implement-a-reserve-then-confirm-seat-hold-that-auto-e-22139) |
| How would you design a two-phase commit alternative (saga) for a multi-service booking that reserves a flight, a hotel, and a car — and what are your compensating actions when step 2 fails? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-two-phase-commit-alternative-saga-for-a-multi-s-16328) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A person travels from A to B at 30 km/h and returns at 20 km/h. If the total time is 5 hours find the distance between A and B. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-person-travels-from-a-to-b-at-30-km-h-and-returns-at-20-km-h-if-the--15789) |
| A train 150 m long crosses a bridge 350 m long in 25 seconds. Find its speed in km/h. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-150-m-long-crosses-a-bridge-350-m-long-in-25-seconds-find-its--15813) |
| A train travelling at 54 km/h crosses a man running at 9 km/h in the opposite direction in 4 seconds. Find the length of the train. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-travelling-at-54-km-h-crosses-a-man-running-at-9-km-h-in-the-o-15862) |
| Two trains of length 100 m and 150 m run on parallel tracks in the same direction at 50 and 40 km/h. How long does the faster take to overtake the slower? | deep understanding | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=two-trains-of-length-100-m-and-150-m-run-on-parallel-tracks-in-the-sam-15829) |
| Design a hotel/flight booking system that prevents double-booking a seat under high concurrency — how do you hold inventory during the payment window and release on timeout? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-flight-booking-system-that-prevents-double-booking-a-se-20702) |
| How would you design a booking system that must never double-book a resource; contrast a unique constraint, an exclusion constraint with tstzrange, and app-level locking including edge cases. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-that-must-never-double-book-a-re-18127) |
| How would you design a two-phase commit alternative (saga) for a multi-service booking that reserves a flight, a hotel, and a car — and what are your compensating actions when step 2 fails? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-two-phase-commit-alternative-saga-for-a-multi-s-16328) |
| A bar-raiser probe: your team celebrates a green Lighthouse score but retention hasn't moved. Convince me performance work was worth the headcount, or tell me honestly it wasn't. How do you separate perf theater from perf that matters? | expertise | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-probe-your-team-celebrates-a-green-lighthouse-score-but-r-40239) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What does NTILE(4) do and what would each row's value look like for 8 rows? | basic concept | Fresher, SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-ntile-4-do-and-what-would-each-row-s-value-look-like-for-8-r-118994) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| When booking the last available seat or ticket why is a transaction with locking important? | intermediate experience | Fresher, SDE-1, SDE-1/2 | ACID & Transactions | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-booking-the-last-available-seat-or-ticket-why-is-a-transaction-wi-106119) |
| Write a CHECK constraint ensuring end_date is greater than or equal to start_date in a bookings table. | intermediate experience | Fresher, SDE-1, SDE-1/2 | Constraints & Keys (PK/FK) | Online Assessment (OA), Phone Screen | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=write-a-check-constraint-ensuring-end-date-is-greater-than-or-equal-to-105899) |
| Given a Bookings table write a subquery-based query to find the customer who made the most bookings. | deep understanding | Fresher, SDE-1, SDE-1/2 | Joins & Subqueries | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=given-a-bookings-table-write-a-subquery-based-query-to-find-the-custom-105722) |
| Explain the 'reserve then confirm' seat-hold that auto-expires in 5 minutes. Compare an expiry-timestamp filter, a TTL sweeper job, and FOR UPDATE SKIP LOCKED reclamation under concurrent reservations. | deep understanding | SDE-1, SDE-1/2 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-reserve-then-confirm-seat-hold-that-auto-expires-in-5-minu-107023) |
| How would you choose an isolation level for a seat-booking system where double-booking must be impossible? Compare SERIALIZABLE, SELECT FOR UPDATE, and a unique constraint on (resource, slot). | deep understanding | SDE-1, SDE-1/2 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-choose-an-isolation-level-for-a-seat-booking-system-wher-107000) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you explain why an agent might need both a 'search flights' and a 'book flight' tool, and why the second is riskier? | basic concept | Fresher, SDE-1/2, SDE-2/3 | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-explain-why-an-agent-might-need-both-a-search-flights-an-58724) |
