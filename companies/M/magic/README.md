# Magic

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 2 | 6 | 6 | 6 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Long-context frontier models can now hold whole corpora. Construct the principled decision boundary between RAG and pure long-context prompting for the org, and explain how you'd continuously re-evaluate that boundary as context windows and prices move. | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=long-context-frontier-models-can-now-hold-whole-corpora-construct-the--68892) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a policy for how the platform handles the KV-cache blowup of 1M-token context requests: dedicated fleet, streaming attention, or a hard cost-gated ceiling; how do you decide? | expertise | SDE-2/3, Architect/Principal | Inference Optimization (vLLM/TensorRT) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-policy-for-how-the-platform-handles-the-kv-cache-blowup-of-1m-85156) |
| Explain how you'd sanity-check whether a model actually supports the context length it advertises for your task, before relying on it in production. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-sanity-check-whether-a-model-actually-supports-the-c-77995) |
| Explain why a model with a 1M-token window can still fail a needle-in-haystack retrieval at 400k tokens, and how you'd measure your effective usable context. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-why-a-model-with-a-1m-token-window-can-still-fail-a-needle-in--77916) |
| Describe how you'd budget and throughput-plan for a long-context (1M-token) use case where a single request can monopolize a GPU. | expertise | SDE-2/3, Architect/Principal | Token Budgeting & Throughput Estimation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-budget-and-throughput-plan-for-a-long-context-1m-to-86366) |
| An interviewer challenges: your teams keep asking for 1M-token context; how do you push back architecturally with hierarchical/retrieval attention and prove it wins on cost per useful answer? | deep understanding | SDE-2/3, Architect/Principal | Transformers & Attention | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-teams-keep-asking-for-1m-token-context--84237) |
| A principal peer argues that with million-token context windows, RAG-and-vector-DB is obsolete and you should just stuff whole corpora into context. Steelman that, then define the corpus, cost, and latency conditions under which vector retrieval still wins decisively. | expertise | SDE-2/3, Architect/Principal | Vector Databases (Pinecone/pgvector) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-peer-argues-that-with-million-token-context-windows-rag-an-82437) |
