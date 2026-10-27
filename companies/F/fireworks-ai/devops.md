# Fireworks AI — DevOps

[← back to Fireworks AI](README.md)

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your inference platform must serve a large LLM with strict p99 latency; batching improves throughput/cost but hurts tail latency. How do you architect the capacity-and-batching policy to hit both a cost-per-token target and an SLA at org scale? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-inference-platform-must-serve-a-large-llm-with-strict-p99-latency-52959) |
| How would you architect a multi-provider LLM-inference fallback and capacity strategy so that when your primary model endpoint is rate-limited or degraded, traffic degrades to a smaller/cheaper model or a queue, without a jarring quality cliff and without unbounded per-token cost? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-multi-provider-llm-inference-fallback-and-ca-52105) |
| How would you design a capacity strategy for a bursty inference workload on scarce accelerators where cold-start of a model can take minutes — deciding between keeping expensive replicas warm, a request queue with an SLA, and a smaller-model fallback — and how do you make that decision per-tenant? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-capacity-strategy-for-a-bursty-inference-worklo-52040) |
