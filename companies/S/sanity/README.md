# Sanity

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 2 | 2 | 2 |
| Fullstack | 3 | 3 | 4 | 9 | 6 | 9 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your cache stores objects that reference each other, and invalidating one should sometimes cascade. How do you model dependency-aware invalidation without creating an invalidation storm? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-cache-stores-objects-that-reference-each-other-and-invalidating-o-25343) |
| Explain how you'd serve draft/preview CMS content past the CDN without leaking it publicly: a preview cookie/header that bypasses cache for editors while production caching stays fully intact for everyone else. Where can this bypass accidentally poison the public cache? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-serve-draft-preview-cms-content-past-the-cdn-without-29749) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd design a company-wide 'preview/draft' bypass so editors can see uncached CMS content while production caching stays fully intact, and enumerate every way that bypass could accidentally poison the public cache and how your design forecloses each. | deep understanding | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-company-wide-preview-draft-bypass-so-editor-39649) |
| You want to preview draft CMS content without it being cached publicly. Describe a bypass-cache mechanism (preview cookie/header) that keeps prod caching intact for everyone else. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-preview-draft-cms-content-without-it-being-cached-publicly-20911) |
| Explain how nested fragments compose, and whether a fragment can spread another fragment. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-nested-fragments-compose-and-whether-a-fragment-can-spread-11556) |
| How would you model a field that can accept either an id or a slug — can GraphQL input unions help, and what's the current status of that feature? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-field-that-can-accept-either-an-id-or-a-slug-can-11561) |
| What is a description string in a GraphQL schema (triple-quoted) and where does it show up for consumers? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-description-string-in-a-graphql-schema-triple-quoted-and-whe-11550) |
| How do you threat-model a headless CMS / content pipeline where marketers can inject HTML/JS that renders in customers' authenticated sessions? Design the trust boundary between content authors and the security context of the rendered page. | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-threat-model-a-headless-cms-content-pipeline-where-marketer-41239) |
| Design the decision framework a platform team should publish so product teams can self-serve the choice between SSG, ISR, SSR, streaming SSR, and CSR per route — without a principal engineer in every review. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-decision-framework-a-platform-team-should-publish-so-produc-40238) |
| Explain how you'd govern the perpetual tension between marketing's desire for rich media / interactive hero experiences and the LCP/CLS cost, including the guardrails you'd embed in the CMS so bad choices are hard to make. | deep understanding | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-the-perpetual-tension-between-marketing-s-des-40302) |
| You're setting the org contract for how untrusted data crosses the SSR-to-client hydration boundary in an islands-architecture framework. Where can a partially-hydrated island reintroduce DOM-XSS that server encoding never covered, and how do you enforce a safe boundary? | expertise | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-setting-the-org-contract-for-how-untrusted-data-crosses-the-ssr-38924) |
