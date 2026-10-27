# Tyk

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 5 | 5 | 1 | 5 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 2 | 4 | 4 | 4 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design how you'd verify a caller's identity at an API gateway once and forward a signed 'identity assertion' downstream, so backend services never re-run the full auth but still can't be spoofed. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-d-verify-a-caller-s-identity-at-an-api-gateway-once-and-26159) |
| Your rate limiter keys on (user, route) and the map of counters never shrinks; how would you design a segmented/expiring counter map so idle keys reclaim memory without a global sweep pause? | intermediate experience | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-rate-limiter-keys-on-user-route-and-the-map-of-counters-never-shr-21957) |
| Your service throttles per-tenant using a token bucket but tenants share a node and one bursts; how do you structure per-tenant buckets with fair refill and avoid one tenant's map churn starving the CPU? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-service-throttles-per-tenant-using-a-token-bucket-but-tenants-sha-21972) |
| Explain how you'd design a Node API gateway that authenticates, rate-limits, and routes to backends, and the trade-off of doing cross-cutting concerns at the gateway versus in each service. | deep understanding | SDE-1/2, SDE-2/3 | JavaScript | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-node-api-gateway-that-authenticates-rate-li-22921) |
| You must design a time-window rate limiter that's memory-efficient at scale; how do you reason about the space of a sliding-window log (O(requests)) versus a sliding-window counter (O(buckets)) and the accuracy trade-off? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-a-time-window-rate-limiter-that-s-memory-efficient-at--22102) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe a time you had to lead the org through a decision on whether to invest in a formal API gateway and traffic-management layer versus letting each service handle its own concerns. How did you weigh the centralization? | deep understanding | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-a-time-you-had-to-lead-the-org-through-a-decision-on-whether--40503) |
| A probe: your team migrated 90% of endpoints to a new API gateway and the remaining 10% are the most business-critical and the riskiest. How do you finish the tail without a catastrophic cutover, and who owns the risk? | expertise | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-probe-your-team-migrated-90-of-endpoints-to-a-new-api-gateway-and-th-41484) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A tradeoff point pits a centralized ingress/API-gateway tier (uniform auth, rate-limit, observability) against per-team ingress ownership (autonomy, no shared bottleneck). How do you scenario-test this against a fleet-wide outage scenario and a team-velocity scenario? | deep understanding | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-tradeoff-point-pits-a-centralized-ingress-api-gateway-tier-uniform-a-53303) |
| How do you decide build-vs-buy for an internal API gateway + rate-limiting + auth edge for hundreds of microservices (Kong/Apigee/Gravitee vs Envoy Gateway + custom filters) when multi-team policy governance beats raw throughput? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-internal-api-gateway-rate-limiti-53755) |
| You're paged for an incident where an API gateway's rate limits are being hit by one abusive client, degrading everyone — how do you identify and isolate the offending caller live? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-paged-for-an-incident-where-an-api-gateway-s-rate-limits-are-be-47458) |
| How would you configure rate limiting at the API gateway per client and per route so one abusive caller can't exhaust a shared backend service? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-configure-rate-limiting-at-the-api-gateway-per-client-an-45394) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design capability negotiation and version-compatibility for an internal MCP-based tool ecosystem where dozens of teams publish and consume tool servers on independent release cadences. How do you avoid a coordinated-deploy nightmare when a tool's schema evolves? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-capability-negotiation-and-version-compatibility-for-an-interna-83089) |
