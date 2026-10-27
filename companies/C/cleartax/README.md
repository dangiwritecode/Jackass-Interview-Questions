# ClearTax

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 6 | 6 | 3 | 6 |
| Fullstack | 1 | 1 | 2 | 3 | 2 | 3 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a service that assigns strictly-monotonic per-tenant sequence numbers (invoice numbers) at high throughput — how do you avoid gaps guarantee no duplicates and not serialize on a single row? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-service-that-assigns-strictly-monotonic-per-tenant-sequence-n-28390) |
| Design a rate-card or a tax calculation module that varies by region. Which pattern? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-rate-card-or-a-tax-calculation-module-that-varies-by-region-w-934) |
| How would you find gaps in a sequence of numeric IDs, such as missing invoice numbers? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-find-gaps-in-a-sequence-of-numeric-ids-such-as-missing-i-11868) |
| How would you design serverless capacity planning for a predictable annual event (like tax filing day) where load is 100x normal for 6 hours — what do you pre-provision and what do you let scale? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Serverless | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-serverless-capacity-planning-for-a-predictable-an-25323) |
| Explain how you'd guarantee monotonic, gapless per-tenant document numbers under concurrency without a global lock bottleneck, and why a single shared sequence both leaks gaps and becomes a hotspot. | expertise | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-guarantee-monotonic-gapless-per-tenant-document-numb-22202) |
| Your form saves a parent and its child rows (invoice + line items) in one request. How do you make the multi-statement write atomic, return the generated ids to the client, and handle a partial validation failure cleanly? | intermediate experience | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-form-saves-a-parent-and-its-child-rows-invoice-line-items-in-one--22228) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a rate-card or a tax calculation module that varies by region. Which pattern? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-rate-card-or-a-tax-calculation-module-that-varies-by-region-w-934) |
| Your form saves a parent and its child rows (invoice + line items) in one request. How do you make the multi-statement write atomic, return the generated ids to the client, and handle a partial validation failure cleanly? | intermediate experience | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-form-saves-a-parent-and-its-child-rows-invoice-line-items-in-one--22228) |
| You must design how the org handles a global config change (say, a new tax rule) that must take effect atomically across the frontend display, the backend calculation, and historical report regeneration. What's your rollout so no user ever sees an inconsistent number? | expertise | SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-how-the-org-handles-a-global-config-change-say-a-new-t-38266) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must design a distributed sequence generator that is gap-free AND ordered (e.g., invoice numbers for tax compliance). Explain why gap-free forces serialization through a single consensus group and where you'd relax to gapful-but-monotonic to regain throughput. | deep understanding | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-a-distributed-sequence-generator-that-is-gap-free-and--112187) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain why an LLM's answer to '2+2' can differ across calls, and use that to argue where an LLM must never be the arithmetic authority. | basic concept | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-why-an-llm-s-answer-to-2-2-can-differ-across-calls-and-use-tha-77997) |
