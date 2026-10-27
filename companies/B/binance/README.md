# Binance

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 0 | 1 |
| Fullstack | 2 | 2 | 5 | 9 | 6 | 9 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You need Redis to serve as the source of truth for real-time stock prices with sub-ms reads but also durably survive a crash — how do you reconcile the durability vs latency tension? | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-redis-to-serve-as-the-source-of-truth-for-real-time-stock-pri-24727) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the governance for how you expose a 'firehose' streaming API (WebSocket/SSE/gRPC-stream) alongside request-response, when partners want real-time updates. Cover backpressure, reconnection/resume semantics, ordering guarantees, and how you version a long-lived stream contract without dropping connections. | expertise | SDE-2/3, Architect/Principal | API Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-governance-for-how-you-expose-a-firehose-streaming-api-webs-40886) |
| Design a live-updating dashboard fed by websockets: how do you throttle high-frequency updates so the UI stays at 60fps? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-live-updating-dashboard-fed-by-websockets-how-do-you-throttle-21224) |
| Design how you handle very large websocket message volume on a live dashboard so the UI stays responsive — batching, coalescing, and backpressure. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-handle-very-large-websocket-message-volume-on-a-live-da-21287) |
| Architect a real-time stock/crypto order-book streaming and matching system where market-data fan-out and order matching share infrastructure — how do you keep matching deterministic and low-latency while fanning out ticks to millions of retail clients? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-real-time-stock-crypto-order-book-streaming-and-matching-s-39440) |
| How do you strangle a real-time WebSocket/push subsystem out of a monolith without dropping live connections at cutover — what's your connection-drain and reconnect design? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-strangle-a-real-time-websocket-push-subsystem-out-of-a-mono-40926) |
| How do you share a single WebSocket connection across many components and update them as messages arrive? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-share-a-single-websocket-connection-across-many-components--10278) |
| How would you design a live dashboard receiving 100 WebSocket updates per second so React stays responsive and doesn't drop frames? | expertise | SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-live-dashboard-receiving-100-websocket-updates--17163) |
| How would you implement real-time price updates (like a trading dashboard) without re-rendering the whole tree? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | React | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-real-time-price-updates-like-a-trading-dashboa-10279) |
| Design an architecture where the authorization policy for a critical resource requires two independent approvals (four-eyes) that cannot be forged by a single compromised identity or a single compromised service. Where does the split-trust primitive live? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-architecture-where-the-authorization-policy-for-a-critical-r-41273) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A regulator's enforcement action against a competitor just made a previously 'recommended' practice effectively mandatory — as principal how do you architect a horizon-scanning process that turns regulatory signals into prioritized platform work before it becomes an audit finding? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-regulator-s-enforcement-action-against-a-competitor-just-made-a-prev-54037) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must design the analytical architecture for a crypto exchange where every trade is immutable and auditable, order books mutate at microsecond scale, and regulators demand full reconstruction. Where do you draw the line between the matching-engine event log, the lake, and the warehouse, and what consistency do you promise each consumer? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-the-analytical-architecture-for-a-crypto-exchange-wher-112707) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you set up a backtesting harness for an XGBoost time-aware model so evaluation respects temporal ordering and no lookahead bias? | expertise | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-a-backtesting-harness-for-an-xgboost-time-aware-m-65951) |
