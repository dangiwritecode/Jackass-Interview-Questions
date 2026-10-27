# Mixedbread

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 2 | 0 | 8 | 9 | 7 | 9 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for an embedding model itself (buy OpenAI/Cohere embeddings API vs self-host open embeddings vs fine-tune your own) when retrieval quality, per-embedding cost at billions of docs, and re-embedding-on-model-change all interact? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-embedding-model-itself-buy-opena-69815) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide whether to buy a reranker (Cohere/Voyage rerank API) or fine-tune your own cross-encoder, when reranking lifts RAG accuracy but adds per-query latency and cost you own end-to-end at high QPS? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-buy-a-reranker-cohere-voyage-rerank-api-o-83745) |
| How would you decide between a hosted embedding API and running your own embedding model on a cloud GPU for a small project? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-between-a-hosted-embedding-api-and-running-your-o-76522) |
| Why might you batch multiple embedding requests together before sending them to an embedding API in the cloud? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-you-batch-multiple-embedding-requests-together-before-sendin-76531) |
| Explain the difference between an embedding model and a chat model's internal representations, and why you can't use a chat model's hidden states as embeddings casually. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-an-embedding-model-and-a-chat-model-s-i-77975) |
| Walk me through how you would evaluate whether upgrading your embedding model is worth the cost of re-embedding your entire corpus. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-would-evaluate-whether-upgrading-your-embeddin-79521) |
| How do you decide the number and sampling strategy for negatives when training a sentence-embedding model with contrastive loss? | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-number-and-sampling-strategy-for-negatives-when--79456) |
| How do you decide the pooling and normalization strategy when you must reuse one encoder for both classification and retrieval? | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-pooling-and-normalization-strategy-when-you-must-79428) |
| Explain how you'd monitor an LLM app's dependency on an external embedding or reranker API you don't control, and architect your SLO so their outages are visible but don't unfairly burn your own error budget. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-monitor-an-llm-app-s-dependency-on-an-external-embed-78883) |
| Your reranker sits between vector search and the LLM. How would you monitor whether the reranker is actually improving retrieval versus adding pure latency, and what signal tells you it's reordering results meaningfully rather than passing them through? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-reranker-sits-between-vector-search-and-the-llm-how-would-you-mon-78814) |
