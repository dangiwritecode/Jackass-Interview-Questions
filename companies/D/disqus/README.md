# Disqus

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 7 | 7 | 5 | 7 |
| Fullstack | 1 | 1 | 5 | 6 | 5 | 6 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You run a write-heavy comment service where reads are cached at the edge. Explain how you'd choose between purge-on-write and short-TTL-plus-revalidate given a 10:1 read:write ratio versus a 1:1 ratio, and how the answer flips. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-run-a-write-heavy-comment-service-where-reads-are-cached-at-the-ed-29685) |
| Design a comment system for a high-traffic site supporting nested threads, sorting by top/new, and live updates — how do you model and paginate deep threads efficiently? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-comment-system-for-a-high-traffic-site-supporting-nested-thre-20668) |
| Design a comment system that supports nested/threaded replies. How do you model the tree? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-comment-system-that-supports-nested-threaded-replies-how-do-y-8964) |
| How would you design the class model for a comment system that must support threaded replies AND efficient 'load more' pagination at any depth without N+1 queries; where does the tree vs flat trade-off bite? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-class-model-for-a-comment-system-that-must-su-16469) |
| How do you design an API + query so a "load more comments" nested-thread view stays fast and consistent while new comments are being inserted concurrently? | intermediate experience | SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-api-query-so-a-load-more-comments-nested-thread-v-24345) |
| How would you design a comments feed that supports 'load more replies' lazily for deeply nested threads without a recursive CTE per request; compare materialized path with LIKE prefix scans against pre-fetching by depth. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-comments-feed-that-supports-load-more-replies-l-24521) |
| Design a threat model and mitigations for a comment feature: users post text and links visible to others. Cover XSS, CSRF, and injection. | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-threat-model-and-mitigations-for-a-comment-feature-users-post-13968) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the frontend architecture for an embeddable widget (payments/chat/reviews) that must run safely inside any third-party site — isolation, CSP compatibility, versioning, and size budget. | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-frontend-architecture-for-an-embeddable-widget-payments-cha-40057) |
| Design a comment system for a high-traffic site supporting nested threads, sorting by top/new, and live updates — how do you model and paginate deep threads efficiently? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-comment-system-for-a-high-traffic-site-supporting-nested-thre-20668) |
| How would you design the class model for a comment system that must support threaded replies AND efficient 'load more' pagination at any depth without N+1 queries; where does the tree vs flat trade-off bite? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-class-model-for-a-comment-system-that-must-su-16469) |
| How do you design an API + query so a "load more comments" nested-thread view stays fast and consistent while new comments are being inserted concurrently? | intermediate experience | SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-api-query-so-a-load-more-comments-nested-thread-v-24345) |
| Design a threat model and mitigations for a comment feature: users post text and links visible to others. Cover XSS, CSRF, and injection. | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-threat-model-and-mitigations-for-a-comment-feature-users-post-13968) |
| You're designing a comment-rendering pipeline that must preserve some formatting, links, and mentions across web, email, and RSS. Where do you sanitize/encode for each surface and how do you avoid a single sanitizer becoming a false sense of safety? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-designing-a-comment-rendering-pipeline-that-must-preserve-some--19155) |
