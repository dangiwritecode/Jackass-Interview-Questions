# Gusto

**Tier:** Tier 3  |  **Business domain:** SaaS/Fintech  |  **Questions:** 18

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Fullstack | 3 | 3 | 4 | 8 | 5 | 8 |
| Database Developer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Structures & Algorithms (all profiles) | 4 | 4 | 4 | 4 | 4 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You inherited a monolith with auth logic scattered across 40 route handlers. How would you plan a migration to centralized auth middleware without breaking any endpoint mid-rollout? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherited-a-monolith-with-auth-logic-scattered-across-40-route-han-18912) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You inherited a monolith with auth logic scattered across 40 route handlers. How would you plan a migration to centralized auth middleware without breaking any endpoint mid-rollout? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherited-a-monolith-with-auth-logic-scattered-across-40-route-han-18912) |
| How do you decide whether to strangle the monolith into services or first refactor it into a well-modularized monolith and only then extract — what tips the decision either way? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-strangle-the-monolith-into-services-or-fi-41003) |
| How do you make a schema migration reversible during a strangler cutover using expand-contract, and what's your discipline for never doing the 'contract' step prematurely? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-make-a-schema-migration-reversible-during-a-strangler-cutov-40993) |
| What's your strategy for migrating a monolith where a single ORM entity maps to 40 tables — do you strangle at the aggregate boundary or the table boundary first? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-migrating-a-monolith-where-a-single-orm-entit-40974) |
| How would you manage a multi-step wizard/form with per-step validation and a shared data model? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-manage-a-multi-step-wizard-form-with-per-step-validation-10267) |
| What does the useId hook do and why is it safer than generating random ids for form labels? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-the-useid-hook-do-and-why-is-it-safer-than-generating-random-10240) |
| When would you reach for a form library like React Hook Form or Formik instead of raw useState-controlled inputs? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-reach-for-a-form-library-like-react-hook-form-or-formik-10268) |
| You must design authorization so a multi-tenant B2B customer can define their own roles and delegate admin to their users, while your platform's invariants (never cross tenant, never exceed plan) are unbreakable. How do you compose tenant policy over platform policy? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-authorization-so-a-multi-tenant-b2b-customer-can-defin-41259) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a per-tenant data-isolation strategy for a B2B SaaS on AWS databases offering both a cheap shared-pool tier and a compliance-driven dedicated-silo tier from one codebase — where do you draw the pool/bridge/silo line on cost, blast radius, and noisy-neighbor risk? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-per-tenant-data-isolation-strategy-for-a-b2b-sa-111880) |
| You're choosing between Aurora Serverless v2 auto-scaling ACUs and provisioned Aurora with capacity headroom for a spiky multi-tenant SaaS — how do you reason about the scaling-step granularity, cold-buffer-cache penalty on scale-up, and per-tenant cost fairness? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-choosing-between-aurora-serverless-v2-auto-scaling-acus-and-pro-111847) |
| How do you decide build-vs-buy for a schema-migration and change-management gate (self-run Liquibase/Flyway vs Bytebase vs bespoke) when every production DDL flows through it and a bad online migration can lock a hot table and take a service down? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-schema-migration-and-change-manag-112964) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect PII handling differently for internal-employee-data models (HR, productivity) vs customer-data models given works-council and labor laws? | deep understanding | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-pii-handling-differently-for-internal-employee-da-72639) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect the org so that the same fairness metric is computed the same way in every model rather than each team inventing its own definition? | deep understanding | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-org-so-that-the-same-fairness-metric-is-co-84347) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Maximum Recipients Receiving Exactly Eight Tokens | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Greedy, Math | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=maximum-recipients-receiving-exactly-eight-tokens-d2442) |
| Spell a Whole Number in English Words | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Lookup Table, Math, Number Formatting, Recursion, Simulation, String | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=spell-a-whole-number-in-english-words-d273) |
| Versioned Value Store with Point-in-Time Lookup | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Binary Search, Data Structure, Design, Hash Table, String | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=versioned-value-store-with-point-in-time-lookup-d966) |
| Wrap Keyword Occurrences with Merged Emphasis Tags | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Hash Table, Interval Merging, String, String Matching, Trie | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=wrap-keyword-occurrences-with-merged-emphasis-tags-d602) |
