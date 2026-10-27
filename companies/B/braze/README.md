# Braze

**Tier:** Tier 2  |  **Business domain:** SaaS  |  **Questions:** 25

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 8 | 10 | 10 | 10 |
| Fullstack | 0 | 0 | 0 | 4 | 4 | 4 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 5 | 5 | 5 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| Data Structures & Algorithms (all profiles) | 1 | 1 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the strategy for exposing bulk/batch and export APIs alongside your transactional API. How do you keep heavy bulk consumers from starving real-time traffic, govern which is the "right" API for a use case, and price bulk differently? | expertise | SDE-2/3, Architect/Principal | API Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-strategy-for-exposing-bulk-batch-and-export-apis-alongside--36480) |
| A background job impersonates users to send reminders and one bug caused it to act as the wrong user. How do you design 'act-as' in async jobs so the intended subject is unambiguous and validated at execution time, not enqueue time? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-background-job-impersonates-users-to-send-reminders-and-one-bug-caus-26226) |
| Your Bridge design separates a Notification abstraction from delivery implementations, but a new requirement crosses a third dimension (priority tier). Is Bridge still right, or are you heading for combinatorial explosion, and how do you restructure? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-bridge-design-separates-a-notification-abstraction-from-delivery--22486) |
| A notification campaign to 40M users must respect a per-provider send rate and complete within a 2-hour window — how do you design the pacing/throttle scheduler so you neither burst-limit the provider nor miss the window? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-notification-campaign-to-40m-users-must-respect-a-per-provider-send--28351) |
| Design a scheduled/delayed notification system where a user schedules a reminder for a specific future timestamp across timezones — how do you store and efficiently query billions of pending timed notifications due in the next minute? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-scheduled-delayed-notification-system-where-a-user-schedules--28350) |
| Design idempotent notification dispatch so that when the fanout worker crashes and its message is redelivered the user does not receive a duplicate push — where do you place the dedup key and what's its TTL? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-idempotent-notification-dispatch-so-that-when-the-fanout-worker-28353) |
| Design the delivery-status tracking of a notification service that ingests async delivery receipts from APNs FCM and SMTP — how do you correlate a receipt back to the original send and expose per-campaign delivery funnels? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-delivery-status-tracking-of-a-notification-service-that-ing-28352) |
| Design the template-rendering and localization layer of a notification service supporting 30 languages and A/B content variants — how do you version templates and roll back a bad template without redeploying? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-template-rendering-and-localization-layer-of-a-notification-28349) |
| How would you design an event-driven system that must guarantee a customer only receives one marketing push per day across three independent services that all emit send events? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Message Queues & Event-Driven Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-event-driven-system-that-must-guarantee-a-cust-26035) |
| Design the architecture for a company-wide idempotent bulk-notification platform that other teams call to send billions of messages/day across channels while respecting global user preferences, quiet hours, and provider quotas. What's the ownership boundary? | expertise | SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-for-a-company-wide-idempotent-bulk-notificatio-31012) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the strategy for exposing bulk/batch and export APIs alongside your transactional API. How do you keep heavy bulk consumers from starving real-time traffic, govern which is the "right" API for a use case, and price bulk differently? | expertise | SDE-2/3, Architect/Principal | API Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-strategy-for-exposing-bulk-batch-and-export-apis-alongside--36480) |
| How do you architect a Bridge between a stable notification abstraction and a growing set of channels (email, SMS, push, WhatsApp, in-app) so adding a channel is additive, while per-channel delivery guarantees and retries still differ legitimately? | deep understanding | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-bridge-between-a-stable-notification-abstractio-38439) |
| An interviewer challenges: "you propose a shared 'notifications platform' (email/SMS/push/in-app) as an enterprise capability — why won't it become a bottleneck and a single point of failure for every product launch?" Design it to avoid exactly that. | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-you-propose-a-shared-notifications-platform--40750) |
| Describe strangling a monolith's messaging/notification pipeline (email, SMS, push) without double-sending during the dual-run — what dedupe key survives the cutover? | deep understanding | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-strangling-a-monolith-s-messaging-notification-pipeline-email-40964) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You need to architect governance for browser-side and mobile-SDK data collection where the code runs on devices you don't control — how do you prove to an auditor what a shipped mobile app actually does with PII when you can't inspect every user's runtime? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-architect-governance-for-browser-side-and-mobile-sdk-data--54099) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect capacity planning for a reverse-ETL / data-activation layer that syncs warehouse tables back into hundreds of SaaS destinations, where per-row sync cost and destination rate limits, not your own compute, become the binding constraint and cost driver? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-capacity-planning-for-a-reverse-etl-data-activ-125410) |
| Design the enterprise reverse-ETL architecture that syncs warehouse-derived audiences and scores back into 20 SaaS operational tools. How do you prevent the warehouse becoming an accidental system-of-record, handle each SaaS API's rate limits and eventual consistency, and govern which data may flow out? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-enterprise-reverse-etl-architecture-that-syncs-warehouse-de-125646) |
| How do you architect the medallion to support both the analytical (OLAP) and the operational/reverse-ETL use case where Gold data must flow back into SaaS tools? | deep understanding | SDE-2/3, Architect/Principal | Medallion Architecture (Bronze/Silver/Gold) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-medallion-to-support-both-the-analytical-olap-126263) |
| How would you build compliance instrumentation into a reverse-ETL flow that pushes warehouse data back into operational SaaS tools where it becomes harder to track? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-compliance-instrumentation-into-a-reverse-etl-flow-127404) |
| How would you propagate deletion and consent changes to sub-processors and third parties who received data exports so the erasure is genuinely end-to-end? | expertise | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-propagate-deletion-and-consent-changes-to-sub-processors-127346) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a 'reverse-ETL' loop where OLAP-computed segments must flow back into the OLTP application safely — what consistency and blast-radius controls do you enforce? | expertise | SDE-2/3, Architect/Principal | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-reverse-etl-loop-where-olap-computed-segment-113475) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you approach a build-vs-buy for a consent management platform that must integrate with your ML feature lineage — what integration points are non-negotiable? | deep understanding | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-a-build-vs-buy-for-a-consent-management-platform-t-72610) |
| How do you decide the right unit of retraining: one global model, per-segment models, or per-tenant models, given the operational cost of maintaining thousands of lifecycles? | expertise | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-right-unit-of-retraining-one-global-model-per-se-72390) |
| What's your strategy for lifecycle-managing thousands of tiny per-customer models in a B2B SaaS product without an unmanageable ops burden? | expertise | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-lifecycle-managing-thousands-of-tiny-per-cust-72441) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Stabilize a Collapsing Token Grid | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, In-place Modification, Matrix, Simulation, Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=stabilize-a-collapsing-token-grid-d708) |
