# The New York Times

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 3 | 3 | 3 |
| Fullstack | 0 | 0 | 0 | 11 | 11 | 11 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how conditional requests (If-None-Match) flow through a CDN to your origin during revalidation, and how you'd make your origin cheaply answer 304s without fully rendering the resource. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-conditional-requests-if-none-match-flow-through-a-cdn-to-y-29680) |
| Explain how Surrogate-Control and Surrogate-Capability let your origin instruct the CDN differently from the browser. Give a scenario where you cache aggressively at the edge but tell the browser not to cache at all. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-surrogate-control-and-surrogate-capability-let-your-origin-29665) |
| Explain how you'd design a soft-purge (mark-stale) flow at the origin so hot content is revalidated in the background rather than hard-evicted, preventing a stampede the instant you invalidate a breaking-news article. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-soft-purge-mark-stale-flow-at-the-origin-so-29744) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect caching to support incremental static regeneration at global scale, so a content update revalidates only affected pages at every edge POP within an SLA without a synchronized global purge storm? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-caching-to-support-incremental-static-regenera-38614) |
| How would you decide whether to cache at compile/build time (SSG), request time (SSR/edge), or client time for a large content platform, and how do you keep the three from producing three different truths on the same page? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-to-cache-at-compile-build-time-ssg-reques-38530) |
| You must decide whether the org standardizes on HTTP caching semantics end to end (surrogate keys, Cache-Control) or on an application-level cache API. Argue how each choice constrains your CDN, edge, and future architecture. | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-whether-the-org-standardizes-on-http-caching-semantics-38591) |
| Design a frontend architecture for extreme SEO-sensitive content (marketplace, publisher) at scale — how do you balance SSR/ISR, crawl budget, Core Web Vitals, and dynamic personalization? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-frontend-architecture-for-extreme-seo-sensitive-content-marke-40073) |
| How do you decide whether to pay down debt by migrating a legacy server-rendered app to a modern SSR/streaming framework versus wrapping it behind an edge layer, given both SEO and time-to-interactive are degrading? | deep understanding | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-pay-down-debt-by-migrating-a-legacy-serve-41425) |
| How do you handle the debt of an SEO/rendering strategy where a rewrite to a SPA silently tanked organic traffic years ago, and the business only now connects revenue loss to the technical decision? | deep understanding | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-debt-of-an-seo-rendering-strategy-where-a-rewrit-41478) |
| Design the decision framework a platform team should publish so product teams can self-serve the choice between SSG, ISR, SSR, streaming SSR, and CSR per route — without a principal engineer in every review. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-decision-framework-a-platform-team-should-publish-so-produc-40238) |
| Design the observability so a spike in field CLS can be traced to the exact ad slot, embed, or late-injected element and its owning team, at billions of impressions, without shipping a heavy client agent. | expertise | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-observability-so-a-spike-in-field-cls-can-be-traced-to-the--40265) |
| Explain how you'd govern the perpetual tension between marketing's desire for rich media / interactive hero experiences and the LCP/CLS cost, including the guardrails you'd embed in the CMS so bad choices are hard to make. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-the-perpetual-tension-between-marketing-s-des-40302) |
| Explain how you'd measure and defend a decision to serve differentiated experiences to bots/crawlers vs users for performance and SEO, and where that crosses into cloaking risk you must avoid. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-measure-and-defend-a-decision-to-serve-differentiate-40298) |
| You inherit a codebase where every team ships its own analytics beacon and the cumulative third-party weight is 1.2MB. Design an org-wide tag-governance and consent-aware loading architecture that reclaims performance without a data revolt. | expertise | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherit-a-codebase-where-every-team-ships-its-own-analytics-beacon-40225) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you handle Global Privacy Control and browser-signal opt-outs so they flow from the edge all the way into your analytics and adtech data flows automatically? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-global-privacy-control-and-browser-signal-opt-out-127374) |
