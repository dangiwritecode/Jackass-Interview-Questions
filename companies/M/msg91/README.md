# MSG91

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 8 | 9 | 8 | 9 |
| Fullstack | 1 | 1 | 2 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An attacker is draining your SMS OTP budget by triggering millions of sends to numbers they control. As architect, design the multi-layer economic defense so this is impossible to weaponize, spanning rate limits, cost caps, provider fallback, and pre-send risk scoring. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-attacker-is-draining-your-sms-otp-budget-by-triggering-millions-of--32780) |
| How would you architect a rate-limited third-party integration (say an SMS provider capped at 100/sec) so bursts of your traffic never breach their limit? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-rate-limited-third-party-integration-say-an--19855) |
| How would you protect a GraphQL mutation that triggers an email/SMS send from being abused as a spam amplifier? Consider rate limiting per recipient, per user, and per operation, and where each check lives. | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-protect-a-graphql-mutation-that-triggers-an-email-sms-se-24091) |
| Design an OTP-generation-and-verification service used across products — how do you rate-limit per number resend prevent enumeration and store OTPs securely with short TTL at scale? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-otp-generation-and-verification-service-used-across-products-28402) |
| Design the priority handling in a notification queue where OTP/transactional messages must never be delayed behind a bulk marketing blast — how do you isolate lanes and prevent priority inversion? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-priority-handling-in-a-notification-queue-where-otp-transac-28354) |
| Model a class design for rate-limited email/SMS sending with provider fallback and cost-aware routing; how do you keep per-provider limits, choose the cheapest healthy provider, and record delivery outcomes? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=model-a-class-design-for-rate-limited-email-sms-sending-with-provider--22392) |
| SMS-OTP sends cost real money and abuse can run up a huge bill. Design multi-dimensional limits (per phone, per IP, per account, global spend cap) and the alerting to catch a spend spike fast. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Rate Limiting | Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=sms-otp-sends-cost-real-money-and-abuse-can-run-up-a-huge-bill-design--25979) |
| Design a system to send SMS alerts when an order status changes. | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-system-to-send-sms-alerts-when-an-order-status-changes-8900) |
| Design an OTP send-and-verify system hardened against abuse: rate-limit generation per phone and per IP, prevent enumeration, and make verification safe against timing and brute-force attacks. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-otp-send-and-verify-system-hardened-against-abuse-rate-limit-22310) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An attacker is draining your OTP SMS budget by triggering millions of sends to numbers they control. Architect the multi-layer economic defense — per-number and per-account limits, pre-send risk scoring, cost caps, provider fallback — so weaponizing your send path is impossible. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-attacker-is-draining-your-otp-sms-budget-by-triggering-millions-of--38890) |
| How would you architect a rate-limited third-party integration (say an SMS provider capped at 100/sec) so bursts of your traffic never breach their limit? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-rate-limited-third-party-integration-say-an--19855) |
| Design a system to send SMS alerts when an order status changes. | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-system-to-send-sms-alerts-when-an-order-status-changes-8900) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you plan capacity for a system where the binding constraint is a downstream vendor's rate limit (payment processor, SMS gateway, external API) rather than your own compute? How does an externally-imposed ceiling reshape your scaling and cost story? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-capacity-for-a-system-where-the-binding-constraint-is--52988) |
