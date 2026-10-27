# Stack Overflow

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 27

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 4 | 4 | 15 | 17 | 10 | 18 |
| Fullstack | 2 | 2 | 3 | 3 | 2 | 4 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 1 | 0 | 1 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design authorization for a public-facing 'read' path that must be extremely fast and mostly anonymous, while the same objects have a strict 'write' path — without duplicating the permission model? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-authorization-for-a-public-facing-read-path-that--26175) |
| What is Dapper and when would you choose a micro-ORM over EF Core for a data-access layer? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | C++ | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-dapper-and-when-would-you-choose-a-micro-orm-over-ef-core-for--9822) |
| When would you drop EF Core for Dapper on a specific read path? Walk through a concrete case where the ORM overhead or query shape justifies raw SQL, and how you keep it maintainable. | intermediate experience | SDE-1/2, SDE-2/3 | C++ | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-drop-ef-core-for-dapper-on-a-specific-read-path-walk-th-23178) |
| A many-to-many tag search 'posts having all of tags A, B, C' is slow. Compare a GIN index on a tag array, a normalized join with grouping, and an inverted-index table. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Database Indexing & Query Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-many-to-many-tag-search-posts-having-all-of-tags-a-b-c-is-slow-compa-25815) |
| How would you design a tagging system where items can have many tags and tags apply to many items? | intermediate experience | Fresher, SDE-1 | DBMS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-tagging-system-where-items-can-have-many-tags-a-8386) |
| You render a deeply nested category/comment tree with the Composite pattern, and recursion blows the stack on a pathological thread depth. How do you keep the Composite model but traverse iteratively, and how do you bound depth at ingestion? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-render-a-deeply-nested-category-comment-tree-with-the-composite-pa-22482) |
| Design a class model for a hierarchical/threaded comment store that must return an entire subtree in one query; compare adjacency list, materialized path, and nested set — which do you pick for heavy writes and why? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-class-model-for-a-hierarchical-threaded-comment-store-that-mu-22379) |
| Design a Stack Overflow style Q&A system. What are the core entities and their relations? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-stack-overflow-style-q-and-a-system-what-are-the-core-entitie-8962) |
| In a Q&A system how would you model voting and compute a user's reputation? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-a-q-and-a-system-how-would-you-model-voting-and-compute-a-user-s-re-8963) |
| Your Q&A reputation computation is recalculated on every page load and is now the slowest query; how do you redesign so reputation is maintained incrementally and stays consistent after a vote is retracted? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-q-and-a-reputation-computation-is-recalculated-on-every-page-load-16470) |
| You're presenting to an architecture review board: justify a decision to NOT split a high-revenue monolith despite executive pressure. What evidence and risk framing wins the room? | expertise | SDE-2/3, Architect/Principal | Monolith vs Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-presenting-to-an-architecture-review-board-justify-a-decision-t-31722) |
| Your interviewer says a monolith 'can't scale.' Give a concrete counterexample of a monolith scaling to millions of RPS and explain what made it possible. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Monolith vs Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-interviewer-says-a-monolith-can-t-scale-give-a-concrete-counterex-25152) |
| Explain how you'd design a schema to store and query many-to-many tags with counts, and keep tag-cloud queries fast without a full aggregation each time. | intermediate experience | SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-schema-to-store-and-query-many-to-many-tags-24399) |
| Explain how you'd model and query a hierarchical categories/comments tree at scale; compare recursive CTE, adjacency list, materialized path, and ltree with their query trade-offs. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-model-and-query-a-hierarchical-categories-comments-t-18149) |
| How would you design a comments feed that supports 'load more replies' lazily for deeply nested threads without a recursive CTE per request; compare materialized path with LIKE prefix scans against pre-fetching by depth. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-comments-feed-that-supports-load-more-replies-l-24521) |
| How would you design and query a tagging system where posts have many tags and you need to find posts matching ALL of a set of tags efficiently; compare a join table with GROUP BY HAVING against an array column with GIN. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-and-query-a-tagging-system-where-posts-have-many--24493) |
| How do you decide when horizontal scale-out has stopped paying off — when the coordination, cross-node chatter, or shared-bottleneck overhead means adding nodes barely helps — and a vertically scaled, simpler design would be more available and cheaper? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-horizontal-scale-out-has-stopped-paying-off-whe-32199) |
| Explain how you'd store hierarchical comments (threaded replies to arbitrary depth) using a materialized-path (ltree) column, and how you'd query an entire subtree and reparent a node atomically. | expertise | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-store-hierarchical-comments-threaded-replies-to-arbi-22173) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a tagging system where items can have many tags and tags apply to many items? | intermediate experience | Fresher, SDE-1 | DBMS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-tagging-system-where-items-can-have-many-tags-a-8386) |
| Design a Stack Overflow style Q&A system. What are the core entities and their relations? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-stack-overflow-style-q-and-a-system-what-are-the-core-entitie-8962) |
| Your Q&A reputation computation is recalculated on every page load and is now the slowest query; how do you redesign so reputation is maintained incrementally and stays consistent after a vote is retracted? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-q-and-a-reputation-computation-is-recalculated-on-every-page-load-16470) |
| Explain how you'd model and query a hierarchical categories/comments tree at scale; compare recursive CTE, adjacency list, materialized path, and ltree with their query trade-offs. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-model-and-query-a-hierarchical-categories-comments-t-18149) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide when horizontal scale-out has stopped paying off — coordination overhead, cross-node chatter, or a shared bottleneck means new nodes barely help — and a simpler vertically-scaled design would be more available, cheaper, and easier to reason about? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-horizontal-scale-out-has-stopped-paying-off-coo-52085) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a duplicate or near-duplicate question detection system for a Q&A platform? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-duplicate-or-near-duplicate-question-detection--62153) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a platform strategy for handling documents that are themselves LLM-generated (summaries, drafts) entering the corpus, so RAG doesn't spiral into a model-feeding-on-model-output degradation loop. How do you detect and gate synthetic content? | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-platform-strategy-for-handling-documents-that-are-themselves--83014) |
| How would you architect an org-wide 'ground-truth harvesting' loop where verified expert answers (from support agents, analysts) are captured and promoted into the corpus as authoritative, closing the gap between what humans know and what RAG retrieves? | deep understanding | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-an-org-wide-ground-truth-harvesting-loop-where-82981) |
| Present the strategic argument for whether the org should treat its curated, cleaned, well-chunked corpus as a competitive asset worth protecting and investing in independent of any model, and how you'd quantify that asset's value to leadership. | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=present-the-strategic-argument-for-whether-the-org-should-treat-its-cu-83026) |
