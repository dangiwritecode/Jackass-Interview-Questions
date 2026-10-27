# Angel One

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 23

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 9 | 10 | 5 | 10 |
| Fullstack | 2 | 2 | 4 | 6 | 5 | 6 |
| DevOps | 0 | 0 | 1 | 2 | 1 | 2 |
| Database Developer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 1 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Given a stream of trades you must maintain a live order book with fast best-bid/best-ask and price-level aggregation; which combination of a tree map and intrusive lists would you use and where do naive approaches choke? | expertise | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=given-a-stream-of-trades-you-must-maintain-a-live-order-book-with-fast-21936) |
| How would you design a stock-price ticker that updates multiple UI widgets in real time? Which pattern fits? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-stock-price-ticker-that-updates-multiple-ui-wid-964) |
| Design a stock-trading order-matching engine's high-level architecture — how do you keep the matching deterministic, low-latency, and recoverable after a crash? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-stock-trading-order-matching-engine-s-high-level-architecture-20706) |
| Design a system to serve real-time stock price ticks to millions of concurrent web/mobile clients — how do you fan out updates efficiently without overwhelming clients? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-system-to-serve-real-time-stock-price-ticks-to-millions-of-co-20707) |
| A stock-trading API sees synchronized bursts at market open. Your fixed-window limiter creates a 2x-limit spike at the boundary. Explain the mechanism and how you'd redesign to avoid it. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Rate Limiting | Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-stock-trading-api-sees-synchronized-bursts-at-market-open-your-fixed-25967) |
| You need Redis to serve as the source of truth for real-time stock prices with sub-ms reads but also durably survive a crash — how do you reconcile the durability vs latency tension? | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-redis-to-serve-as-the-source-of-truth-for-real-time-stock-pri-24727) |
| How do you set an availability and capacity strategy for a stock-trading platform where the load is spiky at market open, the correctness bar is absolute, and even seconds of downtime during a crash cost customers real money and you regulatory scrutiny? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-an-availability-and-capacity-strategy-for-a-stock-tradi-32159) |
| A financial report must be reproducible: running it next month for last month must give identical numbers. What makes an aggregation non-reproducible (late-arriving data, mutable rows, NOW()), and how do you design snapshots or as-of queries to guarantee it? | expertise | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-financial-report-must-be-reproducible-running-it-next-month-for-last-22174) |
| A ledger stores debits and credits, and you must produce a statement with a running balance that resets each account. How do you partition and order the window, and why must you break ties deterministically to keep balances stable across reruns? | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-ledger-stores-debits-and-credits-and-you-must-produce-a-statement-wi-22157) |
| Describe how you'd model a bi-temporal table (both valid-time and transaction-time) so you can answer 'what did we believe on date X about the state at date Y'. What keys and range columns are required? | expertise | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-model-a-bi-temporal-table-both-valid-time-and-trans-22147) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a stock-price ticker that updates multiple UI widgets in real time? Which pattern fits? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-stock-price-ticker-that-updates-multiple-ui-wid-964) |
| Architect a real-time stock/crypto order-book streaming and matching system where market-data fan-out and order matching share infrastructure — how do you keep matching deterministic and low-latency while fanning out ticks to millions of retail clients? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-real-time-stock-crypto-order-book-streaming-and-matching-s-39440) |
| Design a stock-trading order-matching engine's high-level architecture — how do you keep the matching deterministic, low-latency, and recoverable after a crash? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-stock-trading-order-matching-engine-s-high-level-architecture-20706) |
| Design a system to serve real-time stock price ticks to millions of concurrent web/mobile clients — how do you fan out updates efficiently without overwhelming clients? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-system-to-serve-real-time-stock-price-ticks-to-millions-of-co-20707) |
| How would you implement real-time price updates (like a trading dashboard) without re-rendering the whole tree? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-real-time-price-updates-like-a-trading-dashboa-10279) |
| How would you set the availability and correctness strategy for a stock-trading platform where load spikes at market open, downtime during a crash costs customers real money, and regulators are watching? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-the-availability-and-correctness-strategy-for-a-stoc-38780) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Walk me through architecting a capacity plan for a system with a hard regulatory latency ceiling (e.g. exchange order-matching) where you cannot trade latency for cost. How do you still find savings when the usual lever — running hotter — is off the table? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-architecting-a-capacity-plan-for-a-system-with-a-hard--52947) |
| Describe how you'd size vCPU-to-pCPU ratios for a hypervisor cluster hosting latency-sensitive trading workloads. | expertise | SDE-1/2, SDE-2/3 | Virtualization | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-size-vcpu-to-pcpu-ratios-for-a-hypervisor-cluster-h-49534) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide RPO for a database write where losing the last N minutes is legally different from losing it operationally (a recorded trade vs a profile edit)? Walk the regulatory lens over the technical one. | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-rpo-for-a-database-write-where-losing-the-last-n-min-112937) |
| Your synchronous cross-region commit for RPO=0 on a write-heavy ledger pushes p99 write latency past the SLO. How do you adjudicate the RPO-versus-latency trade for a financial system that can't lose a recorded trade? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-synchronous-cross-region-commit-for-rpo-0-on-a-write-heavy-ledger-112855) |
| You're asked to reduce serialization-failure retries that are inflating tail latency in a trading system. Walk through the design levers, ordered by blast radius, that you'd pull. | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-reduce-serialization-failure-retries-that-are-inflatin-113660) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you set up a backtesting harness for an XGBoost time-aware model so evaluation respects temporal ordering and no lookahead bias? | expertise | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-a-backtesting-harness-for-an-xgboost-time-aware-m-65951) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You are asked to add a 'get_stock_quote' tool to a chatbot. Walk through the steps from writing the function to seeing the model call it. | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-add-a-get-stock-quote-tool-to-a-chatbot-walk-through--73664) |
