# ThoughtSpot

**Tier:** Tier 3  |  **Business domain:** SaaS/Analytics  |  **Questions:** 26

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 1 | 3 | 2 | 3 |
| AIOps | 0 | 0 | 0 | 7 | 7 | 7 |
| Data Engineer | 2 | 0 | 2 | 7 | 5 | 7 |
| Database Developer | 0 | 1 | 1 | 0 | 0 | 1 |
| AI Engineer | 0 | 0 | 1 | 2 | 1 | 2 |
| Data Structures & Algorithms (all profiles) | 5 | 5 | 5 | 5 | 5 | 5 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org wants to run WebAssembly (WASM/WASI) workloads on Kubernetes alongside containers via a runtime like SpinKube or runwasi. As principal, how would you frame where WASM's fast cold-start and sandboxing genuinely win over containers, and what maturity gaps would stop you from betting the platform on it? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-to-run-webassembly-wasm-wasi-workloads-on-kubernetes-al-39019) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you reconcile the SPACE framework and DORA metrics with the DevEx (Developer Experience) framework of feedback loops cognitive load and flow state at org scale? | expertise | SDE-2/3, Architect/Principal | Developer Experience (DevEx) Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reconcile-the-space-framework-and-dora-metrics-with-the-dev-56330) |
| How do you think about DevEx for data and ML engineers whose workflows differ sharply from application developers? | deep understanding | SDE-2/3, Architect/Principal | Developer Experience (DevEx) Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-think-about-devex-for-data-and-ml-engineers-whose-workflows-56384) |
| Your Kubernetes pods keep getting CPU-throttled despite node CPU being under 40% — how do you connect that to CFS quota (cpu.cfs_period_us and cfs_quota_us) and fix it? | deep understanding | SDE-1/2, SDE-2/3 | Operating Systems | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-kubernetes-pods-keep-getting-cpu-throttled-despite-node-cpu-being-44918) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect detection for silent ML-model incidents in production — drift, degraded inference quality, poisoned features — such that they page as first-class incidents alongside classic availability events? | expertise | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-detection-for-silent-ml-model-incidents-in-produc-99338) |
| How would you architect explainability into anomaly alerts so a responder gets a defensible starting point ('which metric, which dimension, versus what baseline') rather than an opaque 'anomaly detected'? | expertise | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-explainability-into-anomaly-alerts-so-a-respon-99409) |
| How would you architect verification of an AIOps causality chain (say a 6-service graph) so a responder can confirm it's real and not a spurious correlation the model invented, before acting on the named origin? | expertise | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-verification-of-an-aiops-causality-chain-say-a-99422) |
| How would you build the org's causality-inference approach so an auto-generated 'this service is the origin' claim is verifiable and doesn't send responders chasing a victim instead of the cause? | expertise | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-the-org-s-causality-inference-approach-so-an-auto--99357) |
| How would you design the org's telemetry-freshness checks so an upstream data-pipeline delay can't masquerade as a KPI-dip incident and page on-call for a problem that isn't there? | deep understanding | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-org-s-telemetry-freshness-checks-so-an-upstre-99377) |
| Your AIOps correlation depends on a service-dependency graph — architect how that graph is derived (traces / eBPF / CMDB / IaC) at org scale and how you keep it accurate enough that responders can trust auto-grouping. | expertise | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-aiops-correlation-depends-on-a-service-dependency-graph-architect-99329) |
| You're standing up a unified observability platform for a 500-service org with 12 autonomous teams — how do you set the standard for instrumentation without becoming the bottleneck every team routes tickets through? | expertise | SDE-2/3, Architect/Principal | Unified Observability (Logs/Metrics/Traces) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-standing-up-a-unified-observability-platform-for-a-500-service--101630) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a notebook / interactive-compute environment for analysts and data scientists (buy Hex/Deepnote/Databricks notebooks vs JupyterHub self-run) when practitioner productivity, governance, and idle-compute cost all matter at 200+ users? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-notebook-interactive-compute-envi-125853) |
| How do you decide build-vs-buy for a text-to-SQL / natural-language-analytics layer over your warehouse (buy a vendor NL-BI product vs build on your semantic model + LLM) when a hallucinated query against production financial data is the failure mode, not a UX quibble? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-text-to-sql-natural-language-anal-125885) |
| How do you govern access when your BI tool (Tableau/Power BI/Looker) has its own extract cache — do you enforce at the source or the tool, and what breaks when a dashboard caches data the viewer shouldn't see? | deep understanding | SDE-2/3, Architect/Principal | Data Security & Access Governance | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-govern-access-when-your-bi-tool-tableau-power-bi-looker-has-126669) |
| How would you design governance for a feature where end-users can run arbitrary SQL against a governed warehouse (an internal query tool) without letting them escalate to see data they lack rights to? | deep understanding | SDE-2/3, Architect/Principal | Data Security & Access Governance | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-governance-for-a-feature-where-end-users-can-run--126694) |
| A team wants to expose a Silver table directly to a BI dashboard to 'save a hop.' What's the trade-off and where do you draw the governance line? | deep understanding | SDE-2/3, Architect/Principal | Medallion Architecture (Bronze/Silver/Gold) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-team-wants-to-expose-a-silver-table-directly-to-a-bi-dashboard-to-sa-126219) |
| What does 'reporting' typically mean and why is it associated with OLAP? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-reporting-typically-mean-and-why-is-it-associated-with-olap-118820) |
| What is a 'measure' (like revenue or count) versus a 'dimension' (like date or region) in analytics terms? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-measure-like-revenue-or-count-versus-a-dimension-like-date-o-118802) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you read an actual execution plan and what warning signs (thick arrows implicit conversion residual predicates) you look for first. | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-read-an-actual-execution-plan-and-what-warning-signs-t-108545) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a text-to-SQL / natural-language-analytics layer over your warehouse (buy a vendor NL-BI product vs build on your semantic model + LLM) when hallucinated queries against production data are the failure mode? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-text-to-sql-natural-language-anal-83761) |
| Your NER model degrades badly on documents where entities span line breaks introduced by PDF extraction. How would you make preprocessing robust to layout noise? | intermediate experience | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-ner-model-degrades-badly-on-documents-where-entities-span-line-br-79408) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Count Node Pairs Whose Path Labels Can Be Rearranged Into a Palindrome | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Bit Manipulation, Bitmask, Breadth-First Search, Depth-First Search, Dynamic Programming, Hash Table, Prefix XOR, Tree | DSA/Coding Round, Onsite, Hiring Manager | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-node-pairs-whose-path-labels-can-be-rearranged-into-a-palindrome-d2596) |
| Counting Pairs Reachable Through Each Hub in a Weighted Tree | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Combinatorics, Counting, Depth-First Search, Graph, Tree | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=counting-pairs-reachable-through-each-hub-in-a-weighted-tree-d2798) |
| Is a String a Valid Interleaving of Two Others | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Dynamic Programming, Memoization, String, Two-Dimensional DP | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=is-a-string-a-valid-interleaving-of-two-others-d97) |
| Largest Axis-Aligned Rectangle Under a Bar Skyline | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Monotonic Stack, Stack | DSA/Coding Round, Onsite, Hiring Manager | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=largest-axis-aligned-rectangle-under-a-bar-skyline-d84) |
| Smallest Covering Window | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Frequency Counting, Hash Table, Sliding Window, String, Two Pointers | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=smallest-covering-window-d76) |
