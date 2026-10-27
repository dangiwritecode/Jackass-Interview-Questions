# Deliveroo

**Tier:** Tier 2  |  **Business domain:** E-commerce  |  **Questions:** 24

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 5 | 5 | 5 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 1 | 4 | 3 | 4 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 2 | 2 | 0 | 2 |
| AI Engineer | 0 | 0 | 2 | 4 | 3 | 4 |
| Data Structures & Algorithms (all profiles) | 6 | 6 | 6 | 6 | 6 | 6 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A Facade over four downstream services returns partial data when one dependency times out, but callers can't tell which fields are stale. How do you evolve the Facade's contract to communicate partial success and per-source freshness without leaking every subsystem's shape? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-facade-over-four-downstream-services-returns-partial-data-when-one-d-22439) |
| Design the saga state machine for a food-delivery order (place, assign rider, pickup, deliver, settle). Which steps are compensatable and what are their compensations? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-saga-state-machine-for-a-food-delivery-order-place-assign-r-28778) |
| Describe how you'd use event storming with domain experts to discover aggregates and bounded contexts for a food-delivery platform. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Domain-Driven Design (DDD) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-use-event-storming-with-domain-experts-to-discover--28978) |
| Your unit-economics dashboard shows cost-per-order rising, but nobody knows if it's mix shift, inefficiency, or a pricing change from the cloud vendor. Design the attribution and decomposition analysis that isolates the true driver. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-unit-economics-dashboard-shows-cost-per-order-rising-but-nobody-k-37059) |
| How would you design the availability architecture of a food-delivery platform during peak dinner hours across many cities, where you have three coupled real-time systems (search, dispatch, tracking) and any one saturating cascades into the others? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-availability-architecture-of-a-food-delivery--32166) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a food-delivery platform's peak-hour availability across coupled real-time systems (search, dispatch, tracking) so that one saturating doesn't cascade into the others across many cities at once? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-food-delivery-platform-s-peak-hour-availabil-38782) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a food-delivery platform's peak-hour availability across coupled real-time systems (search, dispatch, tracking) so that one saturating subsystem doesn't cascade into the others across many cities at once, and how do you isolate a single city's meltdown? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-food-delivery-platform-s-peak-hour-availabil-52113) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your dbt slim-CI build relies on a production manifest.json artifact and it went stale after a hotfix ran outside CI; how would you keep the deferred state manifest trustworthy so the diff isn't wrong? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-dbt-slim-ci-build-relies-on-a-production-manifest-json-artifact-a-120368) |
| In a data mesh the legal entity is accountable to a regulator but data ownership is decentralized across domains — who is the single throat to choke for a GDPR violation, and how does the platform enforce accountability without recentralizing every data product? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-a-data-mesh-the-legal-entity-is-accountable-to-a-regulator-but-data-126017) |
| An analytics team complains that a monthly report suddenly takes 6 hours because its data aged into Glacier. How do you debug and prevent this class of problem systemically? | deep understanding | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-analytics-team-complains-that-a-monthly-report-suddenly-takes-6-hou-126719) |
| BigQuery auto-drops table partitions to long-term storage after 90 days of no edits. How do you exploit or work around that behavior in a partitioning + tiering design? | deep understanding | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=bigquery-auto-drops-table-partitions-to-long-term-storage-after-90-day-126786) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a provable right-to-be-forgotten across every datastore a customer's data touches — the OLTP row, Streams-derived read models, the search index, the Redshift warehouse, and backups under retention lock — reconciling GDPR erasure with immutability requirements? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-provable-right-to-be-forgotten-across-every--111892) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide the retraining cadence for an XGBoost model: fixed schedule, drift-triggered, or performance-triggered, and what are the trade-offs? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-retraining-cadence-for-an-xgboost-model-fixed-sc-65895) |
| Your model's F1 improved in CV but degraded on the holdout month — what evaluation-setup mistakes would you check first? | intermediate experience | SDE-1/2, SDE-2/3 | Model Evaluation Metrics | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-model-s-f1-improved-in-cv-but-degraded-on-the-holdout-month-what--65785) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a saga/compensation framework for multi-tool agent workflows where later steps can fail and earlier side effects must be undone, given the model's plan is not known upfront. Where do compensations get defined and who triggers them? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-saga-compensation-framework-for-multi-tool-agent-workflows-wh-83056) |
| How would you decide the safe timeout for an LLM call inside a synchronous request, given the SDK auto-retries and total wall time can multiply? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-the-safe-timeout-for-an-llm-call-inside-a-synchro-77972) |
| Why not just let every model pull features directly from the source systems at inference time instead of a feature store, and when is that actually the right call? | deep understanding | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-not-just-let-every-model-pull-features-directly-from-the-source-sy-84340) |
| Walk through how you would design an A/B test to compare a TF-IDF baseline against a transformer classifier when your online conversion metric is noisy and low-volume. | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-through-how-you-would-design-an-a-b-test-to-compare-a-tf-idf-base-79407) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Column-by-Column (Vertical) Traversal of a Binary Tree | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Binary Tree, Breadth-First Search, Depth-First Search, Hash Table, Sorting, Tree | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=column-by-column-vertical-traversal-of-a-binary-tree-d972) |
| Count Contiguous Subarrays Containing Exactly K Odd Numbers | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Hash Table, Math, Prefix Sum, Sliding Window | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-contiguous-subarrays-containing-exactly-k-odd-numbers-d1209) |
| Duplicate Alert Suppression Within a Cooldown Window | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Data Stream, Design, Hash Table, Rate Limiting | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=duplicate-alert-suppression-within-a-cooldown-window-d359) |
| Expiring Access Badge Registry | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design, Doubly Linked List, Hash Table, Lazy Expiry / TTL Cache, Linked List, Ordered Map, Simulation | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=expiring-access-badge-registry-d1710) |
| Fewest Bracket Removals to Make a String Balanced | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Backtracking, Breadth-First Search, Depth-First Search, Recursion, String | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=fewest-bracket-removals-to-make-a-string-balanced-d301) |
| Indices of Entries Containing a Given Letter | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, String, Traversal | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=indices-of-entries-containing-a-given-letter-d2712) |
