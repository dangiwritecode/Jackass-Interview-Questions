# NSE

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 1 | 4 | 4 | 4 |
| DevOps | 0 | 0 | 1 | 7 | 6 | 7 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a stock-trading order-matching engine's high-level architecture — how do you keep the matching deterministic, low-latency, and recoverable after a crash? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-stock-trading-order-matching-engine-s-high-level-architecture-20706) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org standardized on the gateway for auth but a domain with hard real-time constraints refuses the edge-auth latency; adjudicate whether you grant a per-service local-auth exception, add an auth fast-path, or push a signed-assertion model, and set the precedent this creates. | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-standardized-on-the-gateway-for-auth-but-a-domain-with-hard-r-39547) |
| Your org's gateway must front a new class of ultra-low-latency APIs (sub-5ms budget) alongside existing 200ms APIs; adjudicate whether the low-latency class gets a bypass path, a dedicated lightweight gateway, or a fast-path within the same plane, and defend the isolation cost. | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-s-gateway-must-front-a-new-class-of-ultra-low-latency-apis-su-39538) |
| Describe a time you had to lead the org through a decision on how much resilience to engineer for a scenario that had never happened and might never happen. How did you avoid both under- and over-investing? | expertise | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-a-time-you-had-to-lead-the-org-through-a-decision-on-how-much-40449) |
| Design a stock-trading order-matching engine's high-level architecture — how do you keep the matching deterministic, low-latency, and recoverable after a crash? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-stock-trading-order-matching-engine-s-high-level-architecture-20706) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle continuity for time-sensitive batch and financial-reconciliation jobs where missing a settlement window during an outage has legal and monetary consequences? | expertise | SDE-2/3, Architect/Principal | Business Continuity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-continuity-for-time-sensitive-batch-and-financial-re-57016) |
| How do you plan continuity for real-time and streaming systems (live video, trading, gaming) where even seconds of failover downtime are business-critical and buffering isn't an option? | expertise | SDE-2/3, Architect/Principal | Business Continuity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-continuity-for-real-time-and-streaming-systems-live-vi-57005) |
| Walk me through architecting a capacity plan for a system with a hard regulatory latency ceiling (e.g. exchange order-matching) where you cannot trade latency for cost. How do you still find savings when the usual lever — running hotter — is off the table? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-architecting-a-capacity-plan-for-a-system-with-a-hard--52947) |
| Your real-time trading path needs deterministic latency — how do CPU isolation, disabling deep C-states, and tuned profiles reduce OS jitter? | expertise | SDE-1/2, SDE-2/3 | Operating Systems | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-real-time-trading-path-needs-deterministic-latency-how-do-cpu-iso-44994) |
| How would you set the availability and correctness strategy for a stock-trading or exchange platform where load spikes at market open, downtime during a crash costs customers real money, and regulators are watching every second of an outage? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-the-availability-and-correctness-strategy-for-a-stoc-52111) |
| You must architect how the mesh handles a service that speaks a custom binary protocol over TCP (not HTTP/gRPC). Frame what the mesh can do at L4-only for such traffic, the loss of L7 features, and whether to invest in a custom Envoy protocol filter or leave it unmeshed. | deep understanding | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-how-the-mesh-handles-a-service-that-speaks-a-custom-52693) |
| Your mesh will front a service that must meet a hard 5ms p99 SLO for a trading system. Architect whether the mesh can live on this path at all, what you'd strip (mTLS offload, minimal filters, ambient L4-only), and where you'd draw the line and de-mesh entirely. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-mesh-will-front-a-service-that-must-meet-a-hard-5ms-p99-slo-for-a-52657) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Why not just use one cloud and accept the concentration risk — quantify for me what a full regional outage of your primary provider would cost the business versus your multi-cloud DR spend. | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-not-just-use-one-cloud-and-accept-the-concentration-risk-quantify--127222) |
