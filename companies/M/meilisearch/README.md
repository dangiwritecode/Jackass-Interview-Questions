# Meilisearch

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 24

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 7 | 10 | 4 | 10 |
| Fullstack | 0 | 0 | 1 | 3 | 2 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 7 | 7 | 7 |
| AI Engineer | 0 | 0 | 1 | 3 | 2 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A trie-backed autocomplete must return top-k weighted completions per prefix, not just any completions; how do you store aggregated weights on nodes and avoid a full subtree scan per keystroke? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-trie-backed-autocomplete-must-return-top-k-weighted-completions-per--21985) |
| You must implement fuzzy search tolerant of typos over a product catalog; compare a BK-tree on edit distance, an n-gram index, and a trie with error tolerance for latency and memory at catalog scale. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-implement-fuzzy-search-tolerant-of-typos-over-a-product-catal-22018) |
| Your search index rebuild takes hours and blocks queries; explain a segment-based inverted index with immutable segments and background merges, and how you keep query latency stable during a merge. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-search-index-rebuild-takes-hours-and-blocks-queries-explain-a-seg-21948) |
| How would you handle typos and misspellings in a query for a vector search system? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Embeddings & Vector Search | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-typos-and-misspellings-in-a-query-for-a-vector-se-7770) |
| What is semantic search and how does it differ from traditional keyword (lexical) search? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Embeddings & Vector Search | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-semantic-search-and-how-does-it-differ-from-traditional-keywor-7696) |
| How would you architect exactly-once delivery from a Kafka topic into Elasticsearch given ES has no transactions? Discuss versioning and optimistic concurrency. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-exactly-once-delivery-from-a-kafka-topic-into--24872) |
| How do you handle a global secondary index or search index that must reflect writes across all regions? Walk through the freshness/consistency trade-offs and where you'd accept staleness. | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-a-global-secondary-index-or-search-index-that-must-r-36634) |
| How do you architect a search backend to keep results fresh within seconds while scaling to billions of documents and heavy query traffic, deciding how to split the indexing pipeline from the query pipeline so a reindex storm never degrades live search availability? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-search-backend-to-keep-results-fresh-within-sec-32167) |
| How do you estimate the complexity and cost of a full-text search feature and decide between a LIKE '%x%' scan (O(n)), a trigram index, and a dedicated search engine? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-estimate-the-complexity-and-cost-of-a-full-text-search-feat-16164) |
| A full-text search platform passes user queries to to_tsquery, where the tsquery grammar itself is an injection surface distinct from value binding. Architect a grammar-sanitizing / query-parsing layer as a shared capability across search consumers, and explain what you'd fuzz to prove it safe. | expertise | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-full-text-search-platform-passes-user-queries-to-to-tsquery-where-th-32901) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must decide whether caching for a search platform invalidates on every index update or serves against index snapshots. Argue how continuous indexing forces you to choose between freshness and a stable, cacheable result set. | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-whether-caching-for-a-search-platform-invalidates-on-e-38597) |
| A principal trade-off: your org wants one Repository abstraction over SQL, a document store, and a search index for the same aggregate. When does that unification become a leaky lowest-common-denominator, and where do you deliberately let it fork? | expertise | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-trade-off-your-org-wants-one-repository-abstraction-over-s-38446) |
| How do you estimate the complexity and cost of a full-text search feature and decide between a LIKE '%x%' scan (O(n)), a trigram index, and a dedicated search engine? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-estimate-the-complexity-and-cost-of-a-full-text-search-feat-16164) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org's largest single cost is an internally-built search/index platform that must hold the full corpus in memory for latency. How do you capacity-plan and cost-optimize a memory-bound system where you can't just add cheap disk or scale to zero? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-s-largest-single-cost-is-an-internally-built-search-index-pla-52945) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect caching so a database index rebuild on a search platform invalidates cached result sets against a moving index without a global flush on every rebuild? | deep understanding | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-caching-so-a-database-index-rebuild-on-a-searc-111536) |
| How would you architect the read strategy for a search-heavy product torn between Postgres full-text/trigram indexes and a dedicated search engine, where the deciding factor is a three-year org-capability bet rather than a feature checklist? Frame the reversible pilot. | expertise | SDE-2/3, Architect/Principal | Database Indexing & Query Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-read-strategy-for-a-search-heavy-product-t-111699) |
| What's your decision process when the workload needs full-text search plus transactional integrity? Bolt-on search index, native search in Postgres, or a dedicated search engine as source of truth? | deep understanding | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-decision-process-when-the-workload-needs-full-text-search--114379) |
| You run a search-index datastore (Elasticsearch/OpenSearch) whose recovery is a rebuild from the primary DB. Is index-rebuild time part of RTO, and how do you bound it against a multi-hour reindex? | deep understanding | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-run-a-search-index-datastore-elasticsearch-opensearch-whose-recove-112872) |
| How do you architect isolation across a read-through cache, primary, and async search index so a user's own write is reflected coherently in all three within their session? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-isolation-across-a-read-through-cache-primary-and-113716) |
| How would you design a data platform where the same logical entity is served serializably for writes but eventually-consistently for search? Where do you draw the boundary and how do you keep them coherent? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-data-platform-where-the-same-logical-entity-is--113682) |
| How do you set the strategy for when read/write splitting should give way to a dedicated search/index tier (Elasticsearch/OpenSearch) instead of hammering replicas? | deep understanding | SDE-2/3, Architect/Principal | Read/Write Splitting | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-the-strategy-for-when-read-write-splitting-should-give--115538) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for the ranking/retrieval stack of RAG when a vendor gets better with pooled cross-customer relevance data but you'd rather keep your query and click data proprietary — how do you value that data moat against time-to-value? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-ranking-retrieval-stack-of-rag--83770) |
| What's your strategy for evaluating retrieval quality at scale when you have no per-query relevance labels and can't afford to create them exhaustively? | deep understanding | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-evaluating-retrieval-quality-at-scale-when-yo-86850) |
| How do you decide whether to expand your embedding index in place or rebuild it when you switch to a new embedding model version? | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-expand-your-embedding-index-in-place-or-r-79417) |
