# IRCTC

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 21

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 5 | 5 | 5 | 5 | 4 | 8 |
| Fullstack | 3 | 3 | 0 | 2 | 2 | 5 |
| Database Developer | 1 | 4 | 4 | 2 | 2 | 5 |
| ML Engineer | 0 | 0 | 3 | 3 | 0 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A train 150 m long crosses a bridge 350 m long in 25 seconds. Find its speed in km/h. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-150-m-long-crosses-a-bridge-350-m-long-in-25-seconds-find-its--15813) |
| A train travelling at 54 km/h crosses a man running at 9 km/h in the opposite direction in 4 seconds. Find the length of the train. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-travelling-at-54-km-h-crosses-a-man-running-at-9-km-h-in-the-o-15862) |
| Two trains of length 100 m and 150 m run on parallel tracks in the same direction at 50 and 40 km/h. How long does the faster take to overtake the slower? | deep understanding | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=two-trains-of-length-100-m-and-150-m-run-on-parallel-tracks-in-the-sam-15829) |
| During an interview you're asked to make a "seat hold" survive partitions without double-booking. Contrast a CP reservation (etcd/ZK lease) vs an AP optimistic-hold-with-reconciliation and give the trade-off table. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-an-interview-you-re-asked-to-make-a-seat-hold-survive-partition-25661) |
| Design a seat/slot booking backend (concerts/flights) that holds a seat during the payment window and releases it on timeout at high contention — how do you avoid overbooking and hold leaks? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-seat-slot-booking-backend-concerts-flights-that-holds-a-seat--28401) |
| Design a real-time seat-inventory system for concert bookings on Redis where holds expire automatically and confirmed seats are never double-sold under a flash sale. | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-real-time-seat-inventory-system-for-concert-bookings-on-redis-24652) |
| How would you design a booking system (seats, slots) that stays consistent under high concurrency? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-seats-slots-that-stays-consisten-13089) |
| What is the difference between scaling capacity for peak load vs provisioning for average load with a queue? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-difference-between-scaling-capacity-for-peak-load-vs-provi-13050) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A train 150 m long crosses a bridge 350 m long in 25 seconds. Find its speed in km/h. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-150-m-long-crosses-a-bridge-350-m-long-in-25-seconds-find-its--15813) |
| A train travelling at 54 km/h crosses a man running at 9 km/h in the opposite direction in 4 seconds. Find the length of the train. | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-train-travelling-at-54-km-h-crosses-a-man-running-at-9-km-h-in-the-o-15862) |
| Two trains of length 100 m and 150 m run on parallel tracks in the same direction at 50 and 40 km/h. How long does the faster take to overtake the slower? | deep understanding | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=two-trains-of-length-100-m-and-150-m-run-on-parallel-tracks-in-the-sam-15829) |
| Architect a ticket-booking system for a mega-event (concert/IPL/exam-result) where 10M users hit at the exact drop time — how do you design a virtual waiting room seat-hold inventory and payment window so you neither oversell nor melt the DB? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-ticket-booking-system-for-a-mega-event-concert-ipl-exam-re-39516) |
| You must architect the capacity and autoscaling for a bursty workload that idles most of the day then spikes 100x for a scheduled event — how do you decide serverless vs provisioned pre-warm the fleet and avoid paying for peak capacity year-round? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-the-capacity-and-autoscaling-for-a-bursty-workload--39515) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you keep a seat/ticket booking correct when thousands of users hit the last unit simultaneously? | deep understanding | SDE-1, SDE-1/2 | ACID & Transactions | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-a-seat-ticket-booking-correct-when-thousands-of-users--109400) |
| When booking the last available seat or ticket why is a transaction with locking important? | intermediate experience | Fresher, SDE-1, SDE-1/2 | ACID & Transactions | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-booking-the-last-available-seat-or-ticket-why-is-a-transaction-wi-106119) |
| How would you model a seat-booking system (movies/flights) so two users can't book the same seat, and where does the constraint live in the ER design? | deep understanding | SDE-1, SDE-1/2 | ER Diagrams & Schema Design | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-seat-booking-system-movies-flights-so-two-users--109505) |
| A ticket-booking system double-books a seat under READ COMMITTED. Debug it: what concurrency anomaly is this and what's the minimal isolation change that fixes it? | intermediate experience | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-ticket-booking-system-double-books-a-seat-under-read-committed-debug-110280) |
| Explain how you'd handle read/write splitting for time-sensitive reads like inventory or seat availability where even 200ms of lag oversells. | expertise | SDE-2/3, Architect/Principal | Read/Write Splitting | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-handle-read-write-splitting-for-time-sensitive-reads-115493) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design an experiment for a model change whose benefit only shows up under high-load or peak-traffic conditions? | deep understanding | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-experiment-for-a-model-change-whose-benefit-on-67768) |
| How would you set up an experiment for a dynamic-pricing model while keeping fairness and avoiding user-visible price discrimination complaints? | expertise | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-an-experiment-for-a-dynamic-pricing-model-while-k-67740) |
| An interviewer probes: what breaks in your XGBoost pipeline first if traffic 10x's overnight, and how would you pre-empt it? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-what-breaks-in-your-xgboost-pipeline-first-if-tr-65949) |
