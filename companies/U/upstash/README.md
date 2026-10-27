# Upstash

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 27

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 2 | 2 | 2 |
| Fullstack | 0 | 0 | 6 | 8 | 3 | 8 |
| DevOps | 0 | 0 | 2 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 7 | 0 | 12 | 14 | 14 | 14 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain the difference between edge caching and edge compute state. Why is durable state (KV, Durable Objects, edge DB) hard to keep consistent across POPs, and when would you use it? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-edge-caching-and-edge-compute-state-why-20876) |
| Design a de-duplication strategy for a consumer that must be exactly-once into Redis, where Redis has no transactions spanning your Kafka commit. Where do you store the dedupe state? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-de-duplication-strategy-for-a-consumer-that-must-be-exactly-o-24841) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You are asked to make the tie-breaking call between adopting a managed serverless cache (pay-per-request) versus a provisioned cluster for a spiky workload. How do you model the cost crossover and the operational trade-off at org scale? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-make-the-tie-breaking-call-between-adopting-a-managed-38612) |
| You must decide the org's stance on caching in serverless functions where there is no durable local memory between invocations. Argue how the statelessness reshapes your caching architecture and where an external cache becomes mandatory. | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-the-org-s-stance-on-caching-in-serverless-functions-wh-38609) |
| Explain the difference between edge caching and edge compute state. Why is durable state (KV, Durable Objects, edge DB) hard to keep consistent across POPs, and when would you use it? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-edge-caching-and-edge-compute-state-why-20876) |
| A third-party API you fetch in Server Components has strict rate limits — how do you dedupe, cache, and coalesce requests across concurrent renders and users? | deep understanding | SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-third-party-api-you-fetch-in-server-components-has-strict-rate-limit-17259) |
| Describe how you'd add per-tenant rate limiting and quota enforcement in Middleware while keeping it under the Edge Runtime's CPU/time budget. | deep understanding | SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-add-per-tenant-rate-limiting-and-quota-enforcement--17273) |
| Design a background job trigger from a Server Action (e.g. send email, resize image) that doesn't block the response and survives the serverless function ending. | deep understanding | SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-background-job-trigger-from-a-server-action-e-g-send-email-re-17225) |
| Design a per-user rate limiter for Server Actions and Route Handlers that works across serverless instances — where does state live and how do you avoid a hot key? | deep understanding | SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-per-user-rate-limiter-for-server-actions-and-route-handlers-t-17213) |
| You need to run a scheduled job (cron) tied to your Next.js deployment to warm ISR pages — how do you set it up and make it idempotent? | intermediate experience | SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-run-a-scheduled-job-cron-tied-to-your-next-js-deployment-t-17283) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you implement a distributed rate limiter shared across many app instances on AWS that survives an ElastiCache node failure — what data structure and fallback behavior keep it accurate without failing open dangerously? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-implement-a-distributed-rate-limiter-shared-across-many-app-46209) |
| Your Redis is used for both caching and as a rate-limiter store, and when it failed both broke. How would you decouple these so a cache-store outage doesn't take down rate limiting or vice versa? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-redis-is-used-for-both-caching-and-as-a-rate-limiter-store-and-wh-46955) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you size a Redis-based rate-limiter/counter store for 130k QPS of sliding-window writes, estimate the memory for the counters and TTLs, and describe the failure mode and cost of undersizing versus over-provisioning it? | intermediate experience | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-size-a-redis-based-rate-limiter-counter-store-for-130k-q-112270) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a prompt-caching strategy for large shared tool blocks and system prompts across many tenants and roles that maximizes hit rate while preventing cross-tenant leakage and prompt-cache poisoning. What's your cache-key and prefix-ordering design? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-prompt-caching-strategy-for-large-shared-tool-blocks-and-syst-83069) |
| How do you decide build-vs-buy for a semantic/response caching layer in front of your LLMs when a cache hit could cut inference spend 40% but a wrong-hit answer is a correctness incident — buy vs build on Redis/GPTCache? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-semantic-response-caching-layer-i-83747) |
| How would you cache LLM responses in the cloud so identical questions do not incur repeat API charges? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-cache-llm-responses-in-the-cloud-so-identical-questions--76545) |
| How would you store conversation history so an AI chat app remembers context across sessions in the cloud? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-store-conversation-history-so-an-ai-chat-app-remembers-c-76555) |
| How would you use a queue and workers to process a large batch of documents for embedding without timing out an HTTP request? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-a-queue-and-workers-to-process-a-large-batch-of-docu-76557) |
| What is a dead-letter queue and when would a document that repeatedly fails embedding land in one? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-dead-letter-queue-and-when-would-a-document-that-repeatedly--76558) |
| What is caching and where would you add a cache in a RAG app to avoid re-calling the LLM for the same question? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-caching-and-where-would-you-add-a-cache-in-a-rag-app-to-avoid--76495) |
| What is rate limiting and how would you cap how many LLM requests a single user can make per minute? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-rate-limiting-and-how-would-you-cap-how-many-llm-requests-a-si-76550) |
| Why might you put a message queue between your web app and a slow LLM-processing worker in the cloud? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-you-put-a-message-queue-between-your-web-app-and-a-slow-llm--76497) |
| Design a per-user token accounting subsystem so you can throttle heavy users; where does the counter live and how does it stay accurate across pods? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-per-user-token-accounting-subsystem-so-you-can-throttle-heavy-78434) |
| How would you decide whether to cache an LLM response, given the same question may need a different answer as underlying data changes? Design the key and TTL reasoning. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-to-cache-an-llm-response-given-the-same-q-77986) |
| How would you design a semantic cache in front of an LLM so repeated or similar queries avoid a full inference call and how do you decide the similarity threshold? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-semantic-cache-in-front-of-an-llm-so-repeated-o-79516) |
| Explain how you'd instrument a semantic cache for LLM responses where cache hits depend on an embedding-similarity threshold. Which metrics reveal the threshold is too loose (serving wrong cached answers) versus too tight (low hit ratio)? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-instrument-a-semantic-cache-for-llm-responses-where--78822) |
| How do you monitor a prediction/response cache in front of an LLM so a falling hit ratio manifests as increased provider spend and latency before an aggregate dashboard notices? What per-request view helps you catch it early? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-monitor-a-prediction-response-cache-in-front-of-an-llm-so-a-78853) |
