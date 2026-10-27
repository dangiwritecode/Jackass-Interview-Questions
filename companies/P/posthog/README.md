# PostHog

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 5 | 5 | 1 | 5 |
| Fullstack | 0 | 0 | 4 | 5 | 1 | 5 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design an authorization approach for an analytics dashboard where a manager can see aggregate metrics across their team but not individual PII rows. How do you enforce 'aggregate-only' access at the query layer? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-authorization-approach-for-an-analytics-dashboard-where-a-ma-26222) |
| How do you design a schema for storing feature flags and A/B experiment assignments so lookups are O(1)-ish per request and rollouts are safe to change live? | intermediate experience | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-schema-for-storing-feature-flags-and-a-b-experimen-18164) |
| How would you compute per-day active users and retention cohorts efficiently, and when do you precompute with a rollup table versus query live with window functions? | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-compute-per-day-active-users-and-retention-cohorts-effic-18181) |
| You need near-real-time counts on a dashboard but exact COUNT(*) over a huge table is too slow; walk through summary tables, triggers, and approximate counting trade-offs. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-near-real-time-counts-on-a-dashboard-but-exact-count-over-a-h-18133) |
| Your time-series events table is 2TB and queries only touch recent data; walk through declarative range partitioning by time, partition pruning, and dropping old partitions for retention. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-time-series-events-table-is-2tb-and-queries-only-touch-recent-dat-18140) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a session-recording / product-analytics layer (FullStory/PostHog/Amplitude vs bespoke) where you must balance product insight against privacy exposure of recording real user sessions? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-session-recording-product-analyti-41075) |
| How do you design a schema for storing feature flags and A/B experiment assignments so lookups are O(1)-ish per request and rollouts are safe to change live? | intermediate experience | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-schema-for-storing-feature-flags-and-a-b-experimen-18164) |
| How would you compute per-day active users and retention cohorts efficiently, and when do you precompute with a rollup table versus query live with window functions? | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-compute-per-day-active-users-and-retention-cohorts-effic-18181) |
| You need near-real-time counts on a dashboard but exact COUNT(*) over a huge table is too slow; walk through summary tables, triggers, and approximate counting trade-offs. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-near-real-time-counts-on-a-dashboard-but-exact-count-over-a-h-18133) |
| Your time-series events table is 2TB and queries only touch recent data; walk through declarative range partitioning by time, partition pruning, and dropping old partitions for retention. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-time-series-events-table-is-2tb-and-queries-only-touch-recent-dat-18140) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a capacity-planning practice for a company where infra is a cost of goods sold that directly gates gross margin (a usage-priced SaaS)? How does every efficiency win map to margin, and how do you make engineers feel that connection? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-capacity-planning-practice-for-a-company-whe-53014) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a system that automatically bisects and attributes a schema-change-induced performance regression when plans shift after a migration adds or drops an index. | expertise | SDE-2/3, Architect/Principal | Database Migrations & Versioning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-system-that-automatically-bisects-and-attributes-a-schema-cha-114310) |
