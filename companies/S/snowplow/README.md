# Snowplow

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 8

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 2 | 0 | 2 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 3 | 4 | 1 | 4 |
| AI Engineer | 0 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must dedupe an at-least-once event stream over a 24h window with strict memory; compare a rotating set of Bloom filters versus a cuckoo filter for supporting deletes and bounding false positives. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-dedupe-an-at-least-once-event-stream-over-a-24h-window-with-s-21955) |
| You must dedup a huge event stream with limited memory; how do you compare exact O(n)-space hash dedup versus a rotating Bloom filter, and defend the false-positive trade-off you'd ship? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-dedup-a-huge-event-stream-with-limited-memory-how-do-you-comp-22113) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the governance of consent and lawful-basis for server-side and clickstream data that increasingly bypasses the browser (server-side tagging conversion APIs) — where the old cookie-banner model no longer sees the data flow? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-governance-of-consent-and-lawful-basis-for-se-54074) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design quality checks that are resilient to schema drift from upstream event producers who add and remove fields without coordination? | deep understanding | SDE-2/3, Architect/Principal | Data Quality Framework & SLAs | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-quality-checks-that-are-resilient-to-schema-drift-fr-126986) |
| How do you sessionize clickstream events into sessions with a 30-minute inactivity gap using LAG and a cumulative SUM of a break flag, and how do you make it scale across billions of events? | deep understanding | SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-sessionize-clickstream-events-into-sessions-with-a-30-minut-123191) |
| How would you compute a 'first-seen vs last-seen' timestamp per entity across an event stream efficiently, and why is MIN/MAX aggregation usually better than FIRST_VALUE/LAST_VALUE windows here? | deep understanding | SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-compute-a-first-seen-vs-last-seen-timestamp-per-entity-a-123260) |
| How would you compute per-customer attribution (first-touch and last-touch channel) over a journey and materialize it, and why is nesting FIRST_VALUE/LAST_VALUE inside an aggregate not allowed? | deep understanding | SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-compute-per-customer-attribution-first-touch-and-last-to-123209) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you explain to a skeptical engineer why 'just ask the model to return JSON' is unreliable and when constrained decoding is worth the quality hit? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-explain-to-a-skeptical-engineer-why-just-ask-the-model-t-77932) |
