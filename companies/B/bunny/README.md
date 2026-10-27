# Bunny

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 2 | 2 | 2 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 1 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your CDN caches API responses to improve latency, but some responses are user-specific and must never be cross-served. How do you make caching and authorization coexist safely with Vary and cache keys? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-cdn-caches-api-responses-to-improve-latency-but-some-responses-ar-26188) |
| Design a CDN's origin-shield and cache-fill layer so a cache miss on a hot object doesn't stampede the origin — how do you coalesce fills tier the cache and handle cache-key normalization? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-cdn-s-origin-shield-and-cache-fill-layer-so-a-cache-miss-on-a-28418) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle SLIs for a system behind a global anycast edge where the same request can be served by different POPs with different health — do you set per-POP SLOs or a single edge SLO and why? | deep understanding | SDE-2/3, Architect/Principal | Reliability Engineering (SLA/SLO/SLI) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-slis-for-a-system-behind-a-global-anycast-edge-where-41346) |
| How do you reason about the SLO of a system that's mostly cached at the CDN so origin traffic is tiny and unrepresentative — a small origin blip barely moves the ratio but breaks the uncached long tail. How do you weight it? | deep understanding | SDE-2/3, Architect/Principal | Reliability Engineering (SLA/SLO/SLI) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reason-about-the-slo-of-a-system-that-s-mostly-cached-at-th-41406) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your CDN caches at the edge but origin is single-region. How do you architect multi-origin failover in the CDN config so an origin-region outage doesn't cause cache-miss errors? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-cdn-caches-at-the-edge-but-origin-is-single-region-how-do-you-arc-47558) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| CDNs and edge caches may hold personal data outside your governed region; how do you bring edge into your compliance boundary? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=cdns-and-edge-caches-may-hold-personal-data-outside-your-governed-regi-127360) |
