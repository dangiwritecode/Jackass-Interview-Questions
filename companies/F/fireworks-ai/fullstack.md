# Fireworks AI — Fullstack

[← back to Fireworks AI](README.md)

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must architect an LLM-inference gateway that batches requests across users applies per-key rate limits streams tokens and fairly schedules under GPU scarcity — how do you handle request queuing prompt-cache reuse and priority tiers without starving anyone? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-an-llm-inference-gateway-that-batches-requests-acro-39499) |
| Your inference services have p99 latency SLOs but GPU autoscaling on utilization reacts far too slowly during traffic spikes. How would you design a scaling signal (queue depth, batch-fill, KV-cache pressure) and pre-warm strategy specific to LLM serving that reactive HPA can't provide? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-inference-services-have-p99-latency-slos-but-gpu-autoscaling-on-u-39028) |
| Explain how you'd design load balancing for a batch-inference pipeline where throughput matters more than latency, so the balancer packs work to maximize GPU utilization (bin-packing) rather than spreading it. When does this conflict with the online path sharing the fleet? | expertise | SDE-2/3, Architect/Principal | Load Balancing | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-load-balancing-for-a-batch-inference-pipeline-38685) |
