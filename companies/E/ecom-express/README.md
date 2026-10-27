# Ecom Express

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 4 | 4 | 3 | 4 |
| Fullstack | 0 | 0 | 1 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 2 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A batch that computes shortest paths between all warehouse pairs is too slow with repeated Dijkstra; when would you switch to Floyd-Warshall or Johnson's algorithm, and how does graph density drive the choice? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-batch-that-computes-shortest-paths-between-all-warehouse-pairs-is-to-21964) |
| You have an at-least-once event bus. A saga step's handler is not idempotent and got invoked twice, creating two shipments. How do you fix this without a full rewrite? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-have-an-at-least-once-event-bus-a-saga-step-s-handler-is-not-idemp-28764) |
| How do you prevent illegal transitions like delivered->placed in your order state machine? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-prevent-illegal-transitions-like-delivered-placed-in-your-o-8975) |
| Design an event-driven order-status system where a package moves through placed → picked → shipped → delivered across 3 services. How do you keep the status consistent and handle out-of-order events? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-event-driven-order-status-system-where-a-package-moves-throu-16405) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design an event-driven order-status system where a package moves through placed → picked → shipped → delivered across 3 services. How do you keep the status consistent and handle out-of-order events? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-event-driven-order-status-system-where-a-package-moves-throu-16405) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you allocate a shared measure like shipping cost across the line items of an order so it stays additive at both order and line grain? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Data Modeling (Star/Snowflake Schema) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-allocate-a-shared-measure-like-shipping-cost-across-the-lin-121443) |
| How do you build an accumulating snapshot fact for order-to-delivery, and how do you make the frequent milestone UPDATEs cheap on a warehouse that dislikes row-level updates? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Data Modeling (Star/Snowflake Schema) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-an-accumulating-snapshot-fact-for-order-to-delivery-a-121386) |
