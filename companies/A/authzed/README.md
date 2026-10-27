# Authzed

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a graph-based access-control / entitlements service (Google Zanzibar-style: buy a ReBAC SaaS vs build Zanzibar-inspired vs OSS SpiceDB) that will gate every read in a large product? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-graph-based-access-control-entitl-41099) |
| You must architect a graph-database-backed access-control (relationship-based / Zanzibar-style) system answering millions of 'can X view Y' checks — how do you model relation tuples cache the check and propagate a shared-document revoke consistently? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-a-graph-database-backed-access-control-relationship-39452) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a policy-decision-point for authorization at fleet scale (Zanzibar-style relationship-based access) so 500 services enforce consistent fine-grained authz without each embedding brittle if-checks, and what's the caching/consistency trade-off? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-policy-decision-point-for-authorization-at-flee-51974) |
| Design the authorization model itself: RBAC, ABAC, or ReBAC (relationship-based, Zanzibar-style) for a Zero Trust platform. When does each scale and when does policy complexity explode? | expertise | SDE-2/3, Architect/Principal | Zero Trust Network Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-authorization-model-itself-rbac-abac-or-rebac-relationship--56861) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect an entitlement service that answers 'can user U do action A on resource R' in under 10ms p99 at 200k QPS while keeping policy evaluation auditable and centrally managed? | expertise | SDE-2/3, Architect/Principal | Data Security & Access Governance | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-an-entitlement-service-that-answers-can-user-u-126658) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for an authorization/entitlements datastore inline on every read (Google Zanzibar-style: SpiceDB/OpenFGA self-run vs a managed ReBAC vs bespoke tables) that will encode your entire permission model and gate every query? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-authorization-entitlements-datas-113023) |
