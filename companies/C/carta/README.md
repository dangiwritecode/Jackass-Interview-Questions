# Carta

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 5

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your access-control list for a resource can grow to thousands of entries (per-user shares). How do you keep the 'can X read this' check fast without scanning the whole ACL, and how does this compare to a Zanzibar tuple store? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-access-control-list-for-a-resource-can-grow-to-thousands-of-entri-26196) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for an authorization/policy engine (OPA/Cerbos OSS vs a managed authz SaaS vs bespoke RBAC/ReBAC) that will sit inline on every request and encode your entire permission model? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-authorization-policy-engine-opa--41023) |
| You must architect a graph-database-backed access-control (relationship-based / Zanzibar-style) system answering millions of 'can X view Y' checks — how do you model relation tuples cache the check and propagate a shared-document revoke consistently? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-a-graph-database-backed-access-control-relationship-39452) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a policy-decision-point for authorization at fleet scale (Zanzibar-style relationship-based access) so 500 services enforce consistent fine-grained authz without each embedding brittle if-checks, and what's the caching/consistency trade-off? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-policy-decision-point-for-authorization-at-flee-51974) |
| A principal peer wants to standardize on ABAC everywhere; another wants ReBAC (Zanzibar-style). As the deciding architect for a 10-year horizon, how do you evaluate which failure modes each hides at scale and what the migration cost is if you pick wrong? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-peer-wants-to-standardize-on-abac-everywhere-another-wants-53935) |
