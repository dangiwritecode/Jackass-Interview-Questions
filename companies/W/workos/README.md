# WorkOS

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 5 | 3 | 5 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A major enterprise customer demands SCIM so deprovisioned employees lose all access within seconds. How does SCIM interplay with your session/token lifetimes, and how do you architect near-instant revocation without polling every IdP constantly? | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-major-enterprise-customer-demands-scim-so-deprovisioned-employees-lo-32761) |
| You're the principal on a B2B SaaS that must support per-tenant IdPs (SAML and OIDC), tenant-defined custom roles, SCIM provisioning, and just-in-time provisioning — all behind one login endpoint. Architect the tenant-routing and enforcement uniformity. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-the-principal-on-a-b2b-saas-that-must-support-per-tenant-idps-s-32760) |
| How do you architect immutable customer-facing audit logs as a product feature (like tenant-visible access history) that is also your internal SOC2 evidence — one system serving both without leaking one tenant's activity to another or slowing the hot path? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-immutable-customer-facing-audit-logs-as-a-product-37293) |
| Compare SAML and OIDC when you must support both for enterprise SSO — what abstraction do you build so downstream code doesn't care which protocol authenticated the user? | deep understanding | SDE-1/2, SDE-2/3 | JWT/OAuth/Sessions | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-saml-and-oidc-when-you-must-support-both-for-enterprise-sso-wh-26299) |
| How would you add pluggable SSO (some tenants on SAML, some on OIDC) to an app that only has email/password today, without forking your login code per customer? | deep understanding | SDE-1/2, SDE-2/3 | JWT/OAuth/Sessions | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-add-pluggable-sso-some-tenants-on-saml-some-on-oidc-to-a-26298) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A large customer demands SCIM so deprovisioned employees lose access within seconds, but your tokens live an hour. As architect, reconcile SCIM's deprovision event with your token/session model to guarantee near-instant revocation without polling every tenant IdP. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-large-customer-demands-scim-so-deprovisioned-employees-lose-access-w-38875) |
| Your enterprise B2B product must support each tenant bringing SAML or OIDC, custom roles, SCIM, and JIT provisioning behind one login endpoint. Architect tenant-routing (how you resolve which IdP before knowing the user) and keep enforcement uniform across the tenant zoo. | deep understanding | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-enterprise-b2b-product-must-support-each-tenant-bringing-saml-or--38874) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A principal peer wants to standardize on ABAC everywhere; another wants ReBAC (Zanzibar-style). As the deciding architect for a 10-year horizon, how do you evaluate which failure modes each hides at scale and what the migration cost is if you pick wrong? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-peer-wants-to-standardize-on-abac-everywhere-another-wants-53935) |
| Walk me through architecting per-tenant policy composition for a multi-tenant B2B platform where each customer defines their own roles, yet your platform invariants (never cross tenant, never exceed plan) are unbreakable regardless of what a tenant configures. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-architecting-per-tenant-policy-composition-for-a-multi-53969) |
| Walk me through how you'd architect the trust model for federating identity with hundreds of enterprise customers via SAML/OIDC, where each customer IdP is a trust anchor you don't control, so one customer's IdP breach cannot spill into shared infrastructure. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-architect-the-trust-model-for-federating-ide-53973) |
