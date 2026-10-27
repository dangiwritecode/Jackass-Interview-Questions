# Momento

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 4 | 4 | 4 |
| AIOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 7 | 8 | 8 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a caching platform's API so that migrating from one backing store to another (Redis to a newer engine) is invisible to tenants? What abstraction do you commit to and what leaks through anyway? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-caching-platform-s-api-so-that-migrating-from-o-31957) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer asks you to justify the memory-versus-latency curve for your cache: at what point does adding memory stop improving hit ratio, and how would you find that knee empirically across the fleet? | deep understanding | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-asks-you-to-justify-the-memory-versus-latency-curve-for-38533) |
| How would you architect a caching platform's capacity model so that a tenant's traffic spike triggers automatic memory reallocation without evicting another tenant's committed working set, and prove isolation to a skeptical tenant? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-caching-platform-s-capacity-model-so-that-a--38560) |
| You are asked to make the tie-breaking call between adopting a managed serverless cache (pay-per-request) versus a provisioned cluster for a spiky workload. How do you model the cost crossover and the operational trade-off at org scale? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-make-the-tie-breaking-call-between-adopting-a-managed-38612) |
| You must decide the org's stance on caching in serverless functions where there is no durable local memory between invocations. Argue how the statelessness reshapes your caching architecture and where an external cache becomes mandatory. | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-the-org-s-stance-on-caching-in-serverless-functions-wh-38609) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect the platform so scaling the shared inference cache (semantic/embedding cache) stays coherent and cheap: at high hit-rate a stale-but-cached answer can subtly corrupt many downstream features. As a principal, what invalidation and consistency architecture bounds staleness without gutting the hit rate? | deep understanding | SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-platform-so-scaling-the-shared-inference-c-100727) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Argue build-versus-buy for standing up a managed database read-through cache (like DAX for DynamoDB or Momento) versus a self-run Redis fleet across a 200-service org, on TCO, operability, and lock-in. | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=argue-build-versus-buy-for-standing-up-a-managed-database-read-through-111461) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a semantic/response caching layer in front of your LLMs when a cache hit could cut inference spend 40% but a wrong-hit answer is a correctness incident — buy vs build on Redis/GPTCache? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-semantic-response-caching-layer-i-83747) |
| Design a semantic cache that keys on meaning but stays user-scoped so one user's answer never leaks to another when the answer is personalized. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-semantic-cache-that-keys-on-meaning-but-stays-user-scoped-so--78486) |
| Design a two-tier cache with exact-match in front of semantic; how do you order the lookups and set the similarity threshold to avoid serving a wrong answer? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-two-tier-cache-with-exact-match-in-front-of-semantic-how-do-y-78448) |
| How would you separate the 'safe to cache' path from the 'must be fresh' path in a design where some answers are generic and some are user-specific? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-separate-the-safe-to-cache-path-from-the-must-be-fresh-p-78420) |
| How would you decide whether to cache an LLM response, given the same question may need a different answer as underlying data changes? Design the key and TTL reasoning. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-to-cache-an-llm-response-given-the-same-q-77986) |
| How do you monitor a prediction/response cache in front of an LLM so a falling hit ratio manifests as increased provider spend and latency before an aggregate dashboard notices? What per-request view helps you catch it early? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-monitor-a-prediction-response-cache-in-front-of-an-llm-so-a-78853) |
| A junior on your team wants to cache LLM responses by exact prompt string. Why is that mostly useless for your chat product, and what caching layer would actually cut cost and latency here? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-junior-on-your-team-wants-to-cache-llm-responses-by-exact-prompt-str-79005) |
| How would you architect a semantic cache for LLM responses so near-duplicate queries hit cache, and what's the risk of serving a cached answer that's subtly wrong for the new query? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-semantic-cache-for-llm-responses-so-near-dup-79035) |
