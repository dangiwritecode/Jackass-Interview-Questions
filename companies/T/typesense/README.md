# Typesense

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 17

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 8 | 8 | 0 | 8 |
| Fullstack | 0 | 0 | 3 | 5 | 2 | 5 |
| Database Developer | 0 | 0 | 0 | 4 | 4 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A trie-backed autocomplete must return top-k weighted completions per prefix, not just any completions; how do you store aggregated weights on nodes and avoid a full subtree scan per keystroke? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-trie-backed-autocomplete-must-return-top-k-weighted-completions-per--21985) |
| You must implement fuzzy search tolerant of typos over a product catalog; compare a BK-tree on edit distance, an n-gram index, and a trie with error tolerance for latency and memory at catalog scale. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-implement-fuzzy-search-tolerant-of-typos-over-a-product-catal-22018) |
| Your search index rebuild takes hours and blocks queries; explain a segment-based inverted index with immutable segments and background merges, and how you keep query latency stable during a merge. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-search-index-rebuild-takes-hours-and-blocks-queries-explain-a-seg-21948) |
| A search-as-you-type feature does a fresh filter over the full dataset on each keystroke; analyze the complexity end to end (client and server) and describe how debounce, indexing, and pagination each attack a different term. | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-search-as-you-type-feature-does-a-fresh-filter-over-the-full-dataset-16127) |
| A search-suggest API returns top-k prefixes; how do you reason about the trie-based O(prefix-length + k) lookup versus a naive O(n) scan, and the space cost of precomputing top-k per node? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-search-suggest-api-returns-top-k-prefixes-how-do-you-reason-about-th-22075) |
| How do you estimate the complexity and cost of a full-text search feature and decide between a LIKE '%x%' scan (O(n)), a trigram index, and a dedicated search engine? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-estimate-the-complexity-and-cost-of-a-full-text-search-feat-16164) |
| How do you reason about the complexity of a fuzzy-search feature backed by Levenshtein distance, where per-candidate cost is O(m*k) and candidate count is huge, and how does an index prune the candidate set? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reason-about-the-complexity-of-a-fuzzy-search-feature-backe-22055) |
| How do you reason about the complexity of an inverted index build (O(total-tokens)) versus query-time scanning, and the space cost of postings lists you're choosing to store? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reason-about-the-complexity-of-an-inverted-index-build-o-to-22091) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must decide whether caching for a search platform invalidates on every index update or serves against index snapshots. Argue how continuous indexing forces you to choose between freshness and a stable, cacheable result set. | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-whether-caching-for-a-search-platform-invalidates-on-e-38597) |
| A principal trade-off: your org wants one Repository abstraction over SQL, a document store, and a search index for the same aggregate. When does that unification become a leaky lowest-common-denominator, and where do you deliberately let it fork? | expertise | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-trade-off-your-org-wants-one-repository-abstraction-over-s-38446) |
| A search-as-you-type feature does a fresh filter over the full dataset on each keystroke; analyze the complexity end to end (client and server) and describe how debounce, indexing, and pagination each attack a different term. | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-search-as-you-type-feature-does-a-fresh-filter-over-the-full-dataset-16127) |
| A search-suggest API returns top-k prefixes; how do you reason about the trie-based O(prefix-length + k) lookup versus a naive O(n) scan, and the space cost of precomputing top-k per node? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-search-suggest-api-returns-top-k-prefixes-how-do-you-reason-about-th-22075) |
| How do you estimate the complexity and cost of a full-text search feature and decide between a LIKE '%x%' scan (O(n)), a trigram index, and a dedicated search engine? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-estimate-the-complexity-and-cost-of-a-full-text-search-feat-16164) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must choose a search stack over your product data: self-managed Elasticsearch, Amazon OpenSearch Service, Algolia, or Typesense — walk the decision across relevance-tuning control, index-sync-from-DB complexity, cost-at-scale, and lock-in. | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-choose-a-search-stack-over-your-product-data-self-managed-ela-112968) |
| How would you architect caching so a database index rebuild on a search platform invalidates cached result sets against a moving index without a global flush on every rebuild? | deep understanding | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-caching-so-a-database-index-rebuild-on-a-searc-111536) |
| What's your decision process when the workload needs full-text search plus transactional integrity? Bolt-on search index, native search in Postgres, or a dedicated search engine as source of truth? | deep understanding | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-decision-process-when-the-workload-needs-full-text-search--114379) |
| How do you set the strategy for when read/write splitting should give way to a dedicated search/index tier (Elasticsearch/OpenSearch) instead of hammering replicas? | deep understanding | SDE-2/3, Architect/Principal | Read/Write Splitting | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-the-strategy-for-when-read-write-splitting-should-give--115538) |
