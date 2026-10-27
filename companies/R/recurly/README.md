# Recurly

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 5 | 5 | 3 | 5 |
| Fullstack | 0 | 0 | 2 | 4 | 4 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design authorization for feature entitlements (billing plan gates what you can do) separately from RBAC (org roles), and combine them so a check is 'has-role AND plan-allows'? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-authorization-for-feature-entitlements-billing-pl-26191) |
| Design a subscription-billing engine that computes prorated charges on mid-cycle plan changes and handles dunning for failed renewals — how do you model billing periods invoices and retry schedules? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-subscription-billing-engine-that-computes-prorated-charges-on-28337) |
| You have to design a subscription-billing engine that supports mid-cycle plan changes with proration; where do you put the proration logic, and how do you keep it unit-testable across timezones and leap days? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-have-to-design-a-subscription-billing-engine-that-supports-mid-cyc-16441) |
| How would you model a subscription-billing schema (plans, subscriptions, invoices, proration) so mid-cycle upgrades and refunds stay auditable and idempotent? | deep understanding | SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-subscription-billing-schema-plans-subscriptions--24367) |
| A pricing engine evaluates n rules against m line items per request as O(n*m); how do you reason about indexing rules by applicability to reduce the effective work, and when is caching per-item results worth the space? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-pricing-engine-evaluates-n-rules-against-m-line-items-per-request-as-22060) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a subscription-billing engine that computes prorated charges on mid-cycle plan changes and handles dunning for failed renewals — how do you model billing periods invoices and retry schedules? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-subscription-billing-engine-that-computes-prorated-charges-on-28337) |
| You have to design a subscription-billing engine that supports mid-cycle plan changes with proration; where do you put the proration logic, and how do you keep it unit-testable across timezones and leap days? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-have-to-design-a-subscription-billing-engine-that-supports-mid-cyc-16441) |
| How do you architect an authorization model that spans your product plane and a separately-owned billing platform, so a compromised billing service can never mint entitlements it was not granted? Name the confused-deputy control. | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-authorization-model-that-spans-your-product-pl-41227) |
| How do you decide when the right move is to buy your way out of debt — replacing a homegrown auth/search/billing subsystem with a SaaS — versus the strategic cost of ceding that capability to a vendor? | deep understanding | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-the-right-move-is-to-buy-your-way-out-of-debt-r-41462) |
