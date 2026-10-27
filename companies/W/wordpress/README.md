# WordPress

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 2 | 2 | 2 | 2 |
| Fullstack | 1 | 1 | 3 | 8 | 8 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain surrogate keys (cache tags). How would you attach them at the origin so that editing one blog author purges every article by that author across the edge? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-surrogate-keys-cache-tags-how-would-you-attach-them-at-the-ori-20820) |
| How would you design the schema and API for a blogging platform? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-schema-and-api-for-a-blogging-platform-789) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must set the org policy on token lifetimes across products with wildly different risk (a blog CMS vs a wire-transfer app). Design a tiered token-lifetime framework tied to action risk rather than one global TTL, and how you keep teams from all defaulting to the longest tier. | deep understanding | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-set-the-org-policy-on-token-lifetimes-across-products-with-wi-38845) |
| Explain surrogate keys (cache tags). How would you attach them at the origin so that editing one blog author purges every article by that author across the edge? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-surrogate-keys-cache-tags-how-would-you-attach-them-at-the-ori-20820) |
| You want to preview draft CMS content without it being cached publicly. Describe a bypass-cache mechanism (preview cookie/header) that keeps prod caching intact for everyone else. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-preview-draft-cms-content-without-it-being-cached-publicly-20911) |
| How would you design a Template-Method-free plugin lifecycle (init, validate, execute, cleanup) so that third-party plugins can't leave the host in an inconsistent state if they throw between phases, and how do you make partial cleanup deterministic? | deep understanding | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-template-method-free-plugin-lifecycle-init-vali-38445) |
| How do you strangle a monolith that other teams extend via a plugin/hook system — do you have to migrate the plugin API before you can move the core? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-strangle-a-monolith-that-other-teams-extend-via-a-plugin-ho-41009) |
| How do you threat-model a headless CMS / content pipeline where marketers can inject HTML/JS that renders in customers' authenticated sessions? Design the trust boundary between content authors and the security context of the rendered page. | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-threat-model-a-headless-cms-content-pipeline-where-marketer-41239) |
| How would you design the schema and API for a blogging platform? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-schema-and-api-for-a-blogging-platform-789) |
| How do you quantify the debt of an over-abstracted plugin/extension architecture that made everything configurable, so now nobody can reason about what the system actually does at runtime? Design the simplification. | deep understanding | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-quantify-the-debt-of-an-over-abstracted-plugin-extension-ar-41498) |
