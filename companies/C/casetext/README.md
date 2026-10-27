# Casetext

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 8

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 2 | 3 | 1 | 3 |
| AI Engineer | 0 | 0 | 4 | 5 | 3 | 5 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You enabled Anthropic structured output and citations on the same document-extraction request and got a 400. You need machine-parseable results and source attribution. How do you architect around the incompatibility? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-enabled-anthropic-structured-output-and-citations-on-the-same-docu-64124) |
| You upload a corpus via the Files API and reference it by file_id across thousands of extraction requests. When is that better than base64-inlining, and how does it interact with prompt caching and cost? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-upload-a-corpus-via-the-files-api-and-reference-it-by-file-id-acro-64131) |
| How would you evaluate and bound the risk of hallucination in an LLM used for medical or legal summarization, and what's your acceptance threshold? | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-and-bound-the-risk-of-hallucination-in-an-llm-u-71826) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you would decide chunk boundaries for legal contracts where cutting mid-clause destroys meaning but clauses vary wildly in length. | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-decide-chunk-boundaries-for-legal-contracts-wher-79413) |
| You must support 'answer only from documents effective as of date D' for a legal RAG. How do you model temporal validity of chunks and filter on it in retrieval? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-support-answer-only-from-documents-effective-as-of-date-d-for-78195) |
| You need to decide between fixed 512-token chunks and semantic chunking for a corpus of legal contracts. What experiment settles it and what metric do you optimize? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-decide-between-fixed-512-token-chunks-and-semantic-chunkin-78107) |
| Describe how you'd construct hard negatives to fine-tune a domain-specific reranker for a legal-document RAG system. | expertise | SDE-1/2, SDE-2/3 | Reranking | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-construct-hard-negatives-to-fine-tune-a-domain-spec-80308) |
| Design a retrieval layer for an agent that must cite sources with legal-grade reproducibility years later, despite ANN non-determinism, nightly reindexes, and model upgrades. What must you persist, and what's the honest cost of true reproducibility at scale? | expertise | SDE-2/3, Architect/Principal | Vector Databases (Pinecone/pgvector) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-retrieval-layer-for-an-agent-that-must-cite-sources-with-lega-82456) |
