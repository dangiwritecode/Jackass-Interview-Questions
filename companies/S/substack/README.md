# Substack

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 4 | 4 | 1 | 4 |
| Fullstack | 4 | 4 | 6 | 8 | 3 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design authorization for a public-facing 'read' path that must be extremely fast and mostly anonymous, while the same objects have a strict 'write' path — without duplicating the permission model? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-authorization-for-a-public-facing-read-path-that--26175) |
| A notification digest job scans every user's followed entities nightly and takes 12 hours; how would you invert it with a per-entity subscriber index so work scales with what actually changed? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-notification-digest-job-scans-every-user-s-followed-entities-nightly-21983) |
| How would you design a structure to track which of a user's followed entities have new content since last visit, efficiently, without scanning every entity per user? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-structure-to-track-which-of-a-user-s-followed-e-16101) |
| What is the difference between TEXT, MEDIUMTEXT, and LONGTEXT and when would you use each? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-difference-between-text-mediumtext-and-longtext-and-when-w-11851) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A team wants to cache authorization decisions at the CDN edge for a mostly-public product to cut latency, but some objects flip to private. Architect edge authorization so a permission change is reflected within seconds and a private object can never be served from a public edge cache. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-team-wants-to-cache-authorization-decisions-at-the-cdn-edge-for-a-mo-38834) |
| How would you design a structure to track which of a user's followed entities have new content since last visit, efficiently, without scanning every entity per user? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-structure-to-track-which-of-a-user-s-followed-e-16101) |
| Design resolvers for a blog where Post.author and User.posts both exist — how do you avoid an infinite/N+1 loop? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-resolvers-for-a-blog-where-post-author-and-user-posts-both-exis-11591) |
| What is the difference between TEXT, MEDIUMTEXT, and LONGTEXT and when would you use each? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-difference-between-text-mediumtext-and-longtext-and-when-w-11851) |
| How do you generate a dynamic Open Graph image per blog post using the ImageResponse API? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-generate-a-dynamic-open-graph-image-per-blog-post-using-the-10414) |
| How would you architect a blog with thousands of markdown posts in Next.js — rendering strategy, build time, and revalidation plan? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-blog-with-thousands-of-markdown-posts-in-nex-10439) |
| Design the decision framework a platform team should publish so product teams can self-serve the choice between SSG, ISR, SSR, streaming SSR, and CSR per route — without a principal engineer in every review. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-decision-framework-a-platform-team-should-publish-so-produc-40238) |
| You're designing a comment-rendering pipeline that must preserve some formatting, links, and mentions across web, email, and RSS. Where do you sanitize/encode for each surface and how do you avoid a single sanitizer becoming a false sense of safety? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-designing-a-comment-rendering-pipeline-that-must-preserve-some--19155) |
