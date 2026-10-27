# OYO

**Tier:** Tier 3  |  **Business domain:** Travel/Hospitality  |  **Questions:** 28

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 8 | 8 | 2 | 8 |
| Fullstack | 2 | 2 | 5 | 5 | 2 | 5 |
| Database Developer | 2 | 5 | 5 | 2 | 2 | 6 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| Data Structures & Algorithms (all profiles) | 8 | 8 | 8 | 8 | 8 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A booking system must answer 'is any sub-range of this resource free' under heavy concurrent booking; how do you prevent double-booking races algorithmically and what structure supports fast free-range queries? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-booking-system-must-answer-is-any-sub-range-of-this-resource-free-un-22010) |
| A geospatial 'products within X km' query over millions of listings is slow; compare a geohash grid, a quadtree, and an R-tree for your update-heavy write mix and skewed density. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-geospatial-products-within-x-km-query-over-millions-of-listings-is-s-22004) |
| Design a data structure that answers 'is any of these ranges free to book' for a resource under heavy concurrent booking; how do you prevent double-booking races algorithmically? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-structure-that-answers-is-any-of-these-ranges-free-to-bo-16087) |
| Design a hotel or a meeting-room booking system. Model rooms slots and bookings. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-or-a-meeting-room-booking-system-model-rooms-slots-and--927) |
| How do you avoid double-booking a room in overlapping time ranges in your design? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-avoid-double-booking-a-room-in-overlapping-time-ranges-in-y-928) |
| How would you design a schema and query strategy for a booking calendar that must prevent double-booking a resource across overlapping time ranges? | deep understanding | SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-schema-and-query-strategy-for-a-booking-calenda-24404) |
| How would you design a booking system that must never double-book a resource; contrast a unique constraint, an exclusion constraint with tstzrange, and app-level locking including edge cases. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-that-must-never-double-book-a-re-18127) |
| You need to enforce that overlapping bookings for the same room cannot exist. Explain exclusion constraints (GiST with range types) versus application-level checks and their concurrency guarantees. | expertise | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-enforce-that-overlapping-bookings-for-the-same-room-cannot-16303) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a data structure that answers 'is any of these ranges free to book' for a resource under heavy concurrent booking; how do you prevent double-booking races algorithmically? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-structure-that-answers-is-any-of-these-ranges-free-to-bo-16087) |
| Design a hotel or a meeting-room booking system. Model rooms slots and bookings. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-hotel-or-a-meeting-room-booking-system-model-rooms-slots-and--927) |
| How do you avoid double-booking a room in overlapping time ranges in your design? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-avoid-double-booking-a-room-in-overlapping-time-ranges-in-y-928) |
| How would you design a booking system that must never double-book a resource; contrast a unique constraint, an exclusion constraint with tstzrange, and app-level locking including edge cases. | expertise | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-booking-system-that-must-never-double-book-a-re-18127) |
| You need to enforce that overlapping bookings for the same room cannot exist. Explain exclusion constraints (GiST with range types) versus application-level checks and their concurrency guarantees. | expertise | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-enforce-that-overlapping-bookings-for-the-same-room-cannot-16303) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect isolation for a booking system spanning inventory, pricing, and payment services so a user never sees a confirmed booking that later evaporates? What's the guarantee boundary? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-isolation-for-a-booking-system-spanning-inventory-113737) |
| Given a Bookings table write a subquery-based query to find the customer who made the most bookings. | deep understanding | Fresher, SDE-1, SDE-1/2 | Joins & Subqueries | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=given-a-bookings-table-write-a-subquery-based-query-to-find-the-custom-105722) |
| In a hotel booking system, which parts are OLTP and which reporting parts would be OLAP? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-a-hotel-booking-system-which-parts-are-oltp-and-which-reporting-par-105043) |
| Explain the 'reserve then confirm' seat-hold that auto-expires in 5 minutes. Compare an expiry-timestamp filter, a TTL sweeper job, and FOR UPDATE SKIP LOCKED reclamation under concurrent reservations. | deep understanding | SDE-1, SDE-1/2 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-reserve-then-confirm-seat-hold-that-auto-expires-in-5-minu-107023) |
| How would you choose an isolation level for a seat-booking system where double-booking must be impossible? Compare SERIALIZABLE, SELECT FOR UPDATE, and a unique constraint on (resource, slot). | deep understanding | SDE-1, SDE-1/2 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-choose-an-isolation-level-for-a-seat-booking-system-wher-107000) |
| How would you enforce that overlapping room bookings cannot exist? Compare a GiST exclusion constraint over a tstrange against application-level checks under concurrency. | deep understanding | SDE-1, SDE-1/2 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-enforce-that-overlapping-room-bookings-cannot-exist-comp-106965) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you A/B test replacing a logistic regression scoring model with XGBoost when the business cares mostly about downstream conversion, not AUC? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-a-b-test-replacing-a-logistic-regression-scoring-model-w-65879) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Deep Copy a Linked List With Arbitrary Cross-Links | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Hash Table, In-place Manipulation, Linked List, Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=deep-copy-a-linked-list-with-arbitrary-cross-links-d138) |
| Furthest Pillar You Can Reach with Blocks and Hooks | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Greedy, Heap (Priority Queue) | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=furthest-pillar-you-can-reach-with-blocks-and-hooks-d1565) |
| Longest Shared Starting Segment of a Group of Words | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | String, Trie, Vertical Scanning | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-shared-starting-segment-of-a-group-of-words-d14) |
| Maximum Non-Adjacent Node Sum in a Binary Tree | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Binary Tree, Depth-First Search, Dynamic Programming, Maximum Independent Set, Recursion, Tree | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=maximum-non-adjacent-node-sum-in-a-binary-tree-d337) |
| Merge Multiple Sorted Linked Chains into One | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Divide and Conquer, Heap (Priority Queue), K-way Merge, Linked List, Merge Sort | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=merge-multiple-sorted-linked-chains-into-one-d23) |
| Minimum Hourly Clearing Rate to Empty Every Stack in Time | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Binary Search on Answer, Monotonic Predicate | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=minimum-hourly-clearing-rate-to-empty-every-stack-in-time-d860) |
| Total Pairwise Separation of Moving Particles | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Brainteaser, Modular Arithmetic, Prefix Sum, Sorting | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=total-pairwise-separation-of-moving-particles-d2555) |
| Triplets That Sum to Zero | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Sorting, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=triplets-that-sum-to-zero-d15) |
