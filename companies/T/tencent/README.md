# Tencent

**Tier:** Tier 1  |  **Business domain:** Social/Gaming  |  **Questions:** 27

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 4 | 4 | 4 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| Data Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 1 | 6 | 6 | 6 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| Data Structures & Algorithms (all profiles) | 4 | 4 | 4 | 4 | 4 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A principal-loop scenario: design the API gateway for a super-app with 50 product lines sharing one edge; how do you keep one product's traffic surge or bad deploy from degrading the others, and how do you allocate isolation vs sharing to control cost? | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-loop-scenario-design-the-api-gateway-for-a-super-app-with--34553) |
| Your platform serves 30 countries with data-residency laws. How do data-sovereignty constraints reshape the CAP calculus, given you can no longer freely place a majority quorum wherever latency is best? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-platform-serves-30-countries-with-data-residency-laws-how-do-data-32228) |
| You're the architect for a super-app with many products sharing infra. How do you contain blast radius so a failure in a non-critical product (e.g., games) can never degrade the critical one (e.g., payments) despite shared platforms? | expertise | SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-the-architect-for-a-super-app-with-many-products-sharing-infra--35270) |
| How do you evaluate Apache Pulsar versus Kafka as the backbone for a new streaming platform where you anticipate heavy multi-tenancy and geo-replication needs? What would make you bet against the market-default Kafka? | deep understanding | SDE-2/3, Architect/Principal | Real-time Streaming Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-apache-pulsar-versus-kafka-as-the-backbone-for-a-n-37880) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the gateway architecture for a super-app where one login must fan out to 40 product APIs owned by 40 teams; how do you prevent a slow or failing product from degrading the app shell, and how do you allocate the shared latency budget across independently-deployed teams? | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-gateway-architecture-for-a-super-app-where-one-login-must-f-39554) |
| Design the frontend architecture for a super-app with dozens of mini-apps (payments, food, travel) inside one shell — how do you sandbox, lazy-load, and share auth/session across mini-apps? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-frontend-architecture-for-a-super-app-with-dozens-of-mini-a-40079) |
| You are asked to unify authentication across a portfolio of consumer apps under one account system (a super-app move). Threat-model the aggregation risk: one account now unlocks payments, chat, and commerce. How does blast radius change and how do you contain it? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-unify-authentication-across-a-portfolio-of-consumer-a-41313) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd handle IAM for a company operating under both US and China cloud regions where identity federation, data sovereignty, and provider partitions differ. What's the identity-plane architecture that keeps them isolated yet governable? | expertise | SDE-2/3, Architect/Principal | Cloud IAM & Access Management | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-handle-iam-for-a-company-operating-under-both-us-and-54808) |
| How do you architect blast-radius containment for a super-app where many products share infra, so a failure in a non-critical product (games, rewards) can never degrade a critical one (payments)? Adjudicate shared-platform efficiency against hard product isolation. | expertise | SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-blast-radius-containment-for-a-super-app-where-ma-52896) |
| You're asked to design the trust boundary for a super-app move that unifies auth across payments, chat, and commerce under one account. Threat-model how blast radius changes when one credential now unlocks everything, and how you re-segment authority within a single identity. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-design-the-trust-boundary-for-a-super-app-move-that-un-54015) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A subsidiary in China must run on a local cloud with no cross-border transfer — how does that partition change your global catalog, lineage and metrics-layer design? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-subsidiary-in-china-must-run-on-a-local-cloud-with-no-cross-border-t-127253) |
| How would you approach compliance when the same platform serves multiple legal entities across jurisdictions with conflicting data laws — for example EU India and China? | expertise | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-compliance-when-the-same-platform-serves-multip-127396) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a globally distributed database so that data-residency law (which forbids placing a majority quorum in the fastest region) still yields an acceptable consistency/latency posture, and where do you accept a weaker guarantee as a legal necessity? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-globally-distributed-database-so-that-data-resi-111630) |
| You must serve a real-time leaderboard and historical analytics for a gaming platform with 50M concurrent players from the same event source. Architect the split between an in-memory/Redis serving tier, a real-time OLAP store, and the lakehouse, and where consistency between them is allowed to be loose. | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-serve-a-real-time-leaderboard-and-historical-analytics-for-a--112670) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a graph-neural-network / large-embedding-table serving system for recommendations (buy vs build on TorchRec/HugeCTR + your own parameter server) when trillion-parameter embedding tables blow past any vendor's abstractions? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-graph-neural-network-large-embedd-69858) |
| Walk me through a multi-year migration from a parameter-server legacy stack to a collective-based FSDP platform without freezing model delivery for the teams that depend on it. | expertise | SDE-2/3, Architect/Principal | Distributed Training (Data/Model Parallelism) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-a-multi-year-migration-from-a-parameter-server-legacy--70671) |
| How would you design a platform for continuous online learning at scale and what are the org-level safeguards you would insist on before allowing any team to update models in real time? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-platform-for-continuous-online-learning-at-scal-70527) |
| Walk me through designing a serving architecture for very large recommendation models whose embedding tables exceed single-host memory and must be sharded across a parameter-server tier. | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-designing-a-serving-architecture-for-very-large-recomm-70504) |
| Walk me through designing a system to serve a large recommendation model whose weights do not fit on a single machine. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-designing-a-system-to-serve-a-large-recommendation-mod-66731) |
| How would you architect a KV-cache-aware routing and paging layer shared across many Transformer models to maximize cluster-wide GPU utilization? | expertise | SDE-2/3, Architect/Principal | Transformers & Attention | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-kv-cache-aware-routing-and-paging-layer-shar-70371) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you govern the definition of 'harm' itself when different regions, cultures, and business units have materially different thresholds — do you centralize or federate the taxonomy? | expertise | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-govern-the-definition-of-harm-itself-when-different-regions-86060) |
| Walk me through serving a recommendation model whose embedding tables exceed single-host memory and must be sharded across a parameter-server tier. | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-serving-a-recommendation-model-whose-embedding-tables--84359) |
| When would you choose synchronous versus asynchronous distributed training, and how does the choice interact with stragglers and network topology? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-synchronous-versus-asynchronous-distributed-trai-84416) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Expand a Nested Repeat-Notation String | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Parsing, Recursion, Stack, String | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=expand-a-nested-repeat-notation-string-d394) |
| Maximum Score from Clearing a Row of Colored Stones | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Interval DP, Memoization, Recursion | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=maximum-score-from-clearing-a-row-of-colored-stones-d544) |
| Smallest Number Whose Digits Multiply to a Target | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Digit Manipulation, Greedy, Math, Number Theory | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=smallest-number-whose-digits-multiply-to-a-target-d610) |
| Top Earner in Every Team | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Aggregation, Array, Group-By-Max, Grouping, Hash Table | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=top-earner-in-every-team-d184) |
