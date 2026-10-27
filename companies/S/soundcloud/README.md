# Soundcloud

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 4 | 5 | 4 | 5 |
| Fullstack | 1 | 1 | 1 | 4 | 3 | 4 |
| DevOps | 0 | 0 | 2 | 3 | 1 | 3 |
| AIOps | 3 | 0 | 3 | 3 | 1 | 3 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the governance for backend-for-frontend (BFF) APIs so each client team can move fast without fragmenting the domain contract. Where's the line between BFF and core API ownership, and how do you stop BFF logic from becoming a second business-logic tier? | expertise | SDE-2/3, Architect/Principal | API Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-governance-for-backend-for-frontend-bff-apis-so-each-client-36447) |
| How does a CRDT let a system stay available and still converge to a consistent state? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-a-crdt-let-a-system-stay-available-and-still-converge-to-a-co-5289) |
| Explain what a CRDT is and why it enables conflict-free merges without coordination. Contrast a G-Counter, PN-Counter, and OR-Set, and name a case where CRDTs are the wrong tool. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-what-a-crdt-is-and-why-it-enables-conflict-free-merges-without-28477) |
| You want a fallback that returns cached or default data when a dependency fails. How do you keep the fallback from serving dangerously stale data during a long outage? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-a-fallback-that-returns-cached-or-default-data-when-a-depende-29876) |
| What does the ORDER BY ... LIMIT combination return and how does adding DESC change it? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-the-order-by-limit-combination-return-and-how-does-adding-de-11854) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the governance for backend-for-frontend (BFF) APIs so each client team can move fast without fragmenting the domain contract. Where's the line between BFF and core API ownership, and how do you stop BFF logic from becoming a second business-logic tier? | expertise | SDE-2/3, Architect/Principal | API Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-governance-for-backend-for-frontend-bff-apis-so-each-client-36447) |
| How would you architect a BFF (backend-for-frontend) layer so that web, iOS, Android, and TV clients each get tailored payloads without fragmenting the domain services behind them? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-bff-backend-for-frontend-layer-so-that-web-i-40030) |
| What does the ORDER BY ... LIMIT combination return and how does adding DESC change it? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-the-order-by-limit-combination-return-and-how-does-adding-de-11854) |
| How do you decide whether to make a bet on a BFF-per-experience pattern versus a single shared API layer, and how does that choice ripple into your team topology and roadmap? | deep understanding | SDE-2/3, Architect/Principal | Technical Strategy & Roadmapping | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-make-a-bet-on-a-bff-per-experience-patter-40666) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a Prometheus exporter in Go using the client_golang library. How do you implement a Collector versus registering static gauges, and why does the Collector interface matter for metrics that must be scraped fresh each time? | intermediate experience | SDE-1/2, SDE-2/3 | Go | Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-prometheus-exporter-in-go-using-the-client-golang-library-how-45222) |
| Explain how you'd build a multi-window multi-burn-rate SLO alerting standard as an org-wide paved road, and how you'd stop teams from silently widening windows to dodge pages. | deep understanding | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-build-a-multi-window-multi-burn-rate-slo-alerting-st-53129) |
| A Prometheus instance is using 40GB RAM and queries are slow. How do you profile whether the cost is series cardinality, scrape volume, or expensive recording rules, and how do you reduce it without losing incident-debugging signal? | deep understanding | SDE-1/2, SDE-2/3 | Performance Tuning & Profiling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-prometheus-instance-is-using-40gb-ram-and-queries-are-slow-how-do-yo-47030) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How is Grafana different from Prometheus and why are they usually used together? | basic concept | Fresher, SDE-1/2, SDE-2/3 | Grafana | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-is-grafana-different-from-prometheus-and-why-are-they-usually-used-91627) |
| What is PromQL and why do you need it when using Prometheus data in Grafana? | basic concept | Fresher, SDE-1/2, SDE-2/3 | Grafana | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-promql-and-why-do-you-need-it-when-using-prometheus-data-in-gr-91636) |
| What is a scrape in Prometheus, and roughly how often does a default setup scrape a target? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-scrape-in-prometheus-and-roughly-how-often-does-a-default-se-88329) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle the cold-start problem for a new model in an A/B test where the model needs warm-up data to perform well? | deep understanding | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-cold-start-problem-for-a-new-model-in-an-a-b-tes-67684) |
