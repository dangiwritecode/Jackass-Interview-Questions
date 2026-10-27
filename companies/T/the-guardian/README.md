# The Guardian

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 3 | 3 | 3 |
| Fullstack | 0 | 0 | 0 | 7 | 7 | 7 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd design a soft-purge (mark-stale) flow at the origin so hot content is revalidated in the background rather than hard-evicted, preventing a stampede the instant you invalidate a breaking-news article. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-soft-purge-mark-stale-flow-at-the-origin-so-29744) |
| Explain how you'd serve draft/preview CMS content past the CDN without leaking it publicly: a preview cookie/header that bypasses cache for editors while production caching stays fully intact for everyone else. Where can this bypass accidentally poison the public cache? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-serve-draft-preview-cms-content-past-the-cdn-without-29749) |
| You attach surrogate keys at the origin from a service that assembles a page from 6 upstream calls. Explain how you'd compute the union of cache tags for a composite response so a change in any upstream correctly invalidates the composite. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-attach-surrogate-keys-at-the-origin-from-a-service-that-assembles--29671) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the frontend architecture for a product that must degrade to a text-only/low-JS mode on demand (accessibility, low-power, emergency) — how do you build two fidelity tiers from one source? | deep understanding | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-frontend-architecture-for-a-product-that-must-degrade-to-a--40112) |
| How do you make the trade-off between shipping a single large SPA versus an MPA/islands architecture for a content-plus-app product — what evidence drives that architectural fork? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-make-the-trade-off-between-shipping-a-single-large-spa-vers-40086) |
| Architect how you'd guarantee bfcache eligibility across the app fleet (no unload handlers, cache-control correctness) so instant back/forward works, and how you'd detect the day a team's code silently disqualifies a page. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-how-you-d-guarantee-bfcache-eligibility-across-the-app-fleet-40315) |
| How would you architect the rollout of content-visibility and container queries across a large app to reduce rendering/layout cost, and what are the correctness and a11y traps that make a naive fleet-wide rollout dangerous? | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-rollout-of-content-visibility-and-containe-40309) |
| You need to justify keeping a legacy MPA architecture instead of migrating to an SPA because bfcache and instant back/forward navigation give you a CWV edge. Make the contrarian architectural case and its limits. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-justify-keeping-a-legacy-mpa-architecture-instead-of-migra-40281) |
| You're setting the standard for how the whole org handles web fonts across 30 locales and RTL scripts. Design the font strategy, the subsetting pipeline, and the guardrail that stops a designer from adding a 400KB font in a PR. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-setting-the-standard-for-how-the-whole-org-handles-web-fonts-ac-40241) |
| You've been asked to set a five-year rendering strategy that survives framework churn. How do you make the architecture resilient to the next React/Next paradigm shift without betting the company on today's RSC model? | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-ve-been-asked-to-set-a-five-year-rendering-strategy-that-survives--40231) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A staff engineer wants GraphQL federation as the universal integration layer across 15+ subgraphs. Where do you agree, where do you push back on N+1 fan-out, subgraph-ownership, and operational risk, and what conditions would make you approve it? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-staff-engineer-wants-graphql-federation-as-the-universal-integration-51981) |
