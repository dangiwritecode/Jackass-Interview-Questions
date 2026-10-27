# BharatPe

**Tier:** Tier 3  |  **Business domain:** Fintech/Banking  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 5 | 5 | 3 | 5 |
| Fullstack | 2 | 2 | 2 | 2 | 2 | 2 |
| Data Engineer | 1 | 0 | 1 | 1 | 0 | 1 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a 'trusted device + PIN' scheme for a payments app where the PIN never leaves the device but a signed proof does. How does the server verify the PIN attempt without knowing the PIN, and how do you rate-limit it? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-trusted-device-pin-scheme-for-a-payments-app-where-the-pin-ne-26212) |
| How would you design a payment system that supports multiple payment methods interchangeably? Which pattern? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-payment-system-that-supports-multiple-payment-m-967) |
| You need to integrate a third-party payment gateway with a different interface than your app expects. Which pattern helps? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-integrate-a-third-party-payment-gateway-with-a-different-i-955) |
| Design a Redis-backed dedup store for a payments webhook receiver that must retain dedup keys long enough to catch late retries but not grow unbounded — how do you size the TTL? | deep understanding | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-redis-backed-dedup-store-for-a-payments-webhook-receiver-that-24679) |
| Your Redis-backed idempotency layer stores 'in-progress' markers, but a client that times out and retries sees the marker and gets stuck — how do you design the state transitions and timeouts to avoid deadlocking legitimate retries? | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-redis-backed-idempotency-layer-stores-in-progress-markers-but-a-c-24639) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a payment system that supports multiple payment methods interchangeably? Which pattern? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-payment-system-that-supports-multiple-payment-m-967) |
| You need to integrate a third-party payment gateway with a different interface than your app expects. Which pattern helps? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-integrate-a-third-party-payment-gateway-with-a-different-i-955) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| If a table gets thousands of small INSERTs per second, which category of system is it most likely part of? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=if-a-table-gets-thousands-of-small-inserts-per-second-which-category-o-118779) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe a production incident you'd expect when an XGBoost model is served with a feature that silently changed units upstream, and how monitoring should catch it. | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-a-production-incident-you-d-expect-when-an-xgboost-model-is-s-65880) |
