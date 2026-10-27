# Ticketmaster

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 10 | 9 | 10 |
| Fullstack | 0 | 0 | 1 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect a globally-consistent inventory/quota counter that must never oversell during a flash sale at millions of concurrent requests — how do you reconcile strong consistency with the throughput demands and where does DynamoDB conditional writes or a sharded counter fit? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-globally-consistent-inventory-quota-counter-that-must-neve-33251) |
| Design capacity and architecture for a flash-sale / IPO-open event where load goes from baseline to 50x in seconds — Auto Scaling is too slow so what pre-warming queueing and admission-control strategy do you use and how do you test it? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-capacity-and-architecture-for-a-flash-sale-ipo-open-event-where-33252) |
| How do you decide the org's default answer to 'browse-yes, act-no' partial-availability design, so that during any partition the read/browse surface stays up while only the mutating/committing surface degrades, and this is a reusable platform pattern rather than per-team improvisation? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-org-s-default-answer-to-browse-yes-act-no-partia-32295) |
| You're asked to architect a cross-region uniqueness guarantee (usernames, promo codes, seat IDs) at planet scale. Compare a single CP registry versus region-sharded namespaces versus a reservation-then-confirm scheme, and pick a default with its CAP costs. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-architect-a-cross-region-uniqueness-guarantee-username-32281) |
| Explain how a virtual waiting room protects downstream systems during a demand spike, and the subtle ways it can itself become the correlated single point of failure. How do you size and shard it, and what happens if the waiting-room service is exactly what fails under the surge? | expertise | SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-a-virtual-waiting-room-protects-downstream-systems-during--33889) |
| You're designing a flash-sale/ticketing system that will get 100x normal load in a 3-second window with a limited inventory. Walk through the full architecture: admission control, virtual waiting room, inventory reservation, idempotent checkout, and how you keep the correlated demand spike from cratering shared dependencies. | expertise | SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-designing-a-flash-sale-ticketing-system-that-will-get-100x-norm-33888) |
| Architect the boundary between a strongly-consistent inventory-reservation core and eventually-consistent order sagas so you never oversell during a flash sale, without making inventory a global bottleneck. Where does the transaction live and how does the saga interact with it? | expertise | SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-the-boundary-between-a-strongly-consistent-inventory-reserva-34156) |
| Design a seat/slot booking backend (concerts/flights) that holds a seat during the payment window and releases it on timeout at high contention — how do you avoid overbooking and hold leaks? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-seat-slot-booking-backend-concerts-flights-that-holds-a-seat--28401) |
| Design a real-time seat-inventory system for concert bookings on Redis where holds expire automatically and confirmed seats are never double-sold under a flash sale. | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-real-time-seat-inventory-system-for-concert-bookings-on-redis-24652) |
| Design a seat-booking system for a 100k-seat concert on-sale where inventory is finite and demand is 50x supply in the first second. How do you prevent oversell and keep the queue fair? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-seat-booking-system-for-a-100k-seat-concert-on-sale-where-inv-16324) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect a ticket-booking system for a mega-event (concert/IPL/exam-result) where 10M users hit at the exact drop time — how do you design a virtual waiting room seat-hold inventory and payment window so you neither oversell nor melt the DB? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-ticket-booking-system-for-a-mega-event-concert-ipl-exam-re-39516) |
| Design a seat-booking system for a 100k-seat concert on-sale where inventory is finite and demand is 50x supply in the first second. How do you prevent oversell and keep the queue fair? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-seat-booking-system-for-a-100k-seat-concert-on-sale-where-inv-16324) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect capacity and admission control for an IPO-open or ticket-drop event where load spikes 50x in seconds and Auto Scaling can't react in time — walk me through pre-warming, a virtual waiting room, and load-testing the entire chain including the DB? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-capacity-and-admission-control-for-an-ipo-open-or-52385) |
| How would you architect a globally-consistent inventory/quota counter that must never oversell during a flash sale at millions of concurrent requests — how do you reconcile strong consistency with throughput, and where do sharded counters, DynamoDB conditional writes, or a reservation ledger fit? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-globally-consistent-inventory-quota-counter--52364) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd handle read/write splitting for time-sensitive reads like inventory or seat availability where even 200ms of lag oversells. | expertise | SDE-2/3, Architect/Principal | Read/Write Splitting | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-handle-read-write-splitting-for-time-sensitive-reads-115493) |
