# Graphcore

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 2 | 9 | 8 | 9 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how overlapping computation with communication (e.g. computation-communication overlap in the backward pass) hides all-reduce cost, and what breaks the overlap at scale. As principal, how do you make this a platform-level guarantee rather than something each team hand-tunes? | deep understanding | SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-overlapping-computation-with-communication-e-g-computation-69075) |
| Explain pipeline parallelism's bubble problem. How do micro-batching and schedules like GPipe or 1F1B reduce the bubble, and what's the memory-versus-throughput trade-off you're making? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-pipeline-parallelism-s-bubble-problem-how-do-micro-batching-an-64474) |
| Your largest run trains across 4096 GPUs and silent data corruption from a single flaky NIC costs a week of compute. How do you architect corruption detection into the training loop itself? | expertise | SDE-2/3, Architect/Principal | Distributed Training (Data/Model Parallelism) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-largest-run-trains-across-4096-gpus-and-silent-data-corruption-fr-70677) |
| Your org is evaluating custom silicon (TPU/Trainium/Gaudi) versus staying on NVIDIA. How does the choice of parallelism framework and portability risk factor into that platform bet? | expertise | SDE-2/3, Architect/Principal | Distributed Training (Data/Model Parallelism) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-is-evaluating-custom-silicon-tpu-trainium-gaudi-versus-stayin-70694) |
| Explain how you'd set a cost SLO for an ML platform's training throughput expressed as dollars-per-effective-FLOP or MFU-adjusted cost, and how that SLO changes the way teams choose model architectures, batch sizes, and hardware. What breaks when you make MFU a governed target? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-set-a-cost-slo-for-an-ml-platform-s-training-through-69881) |
| A vendor pitches a new accelerator with 2x claimed perf-per-dollar but an immature software stack. How do you run a de-risked pilot and set the bar for org-wide adoption? | deep understanding | SDE-2/3, Architect/Principal | GPU & Accelerator Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-vendor-pitches-a-new-accelerator-with-2x-claimed-perf-per-dollar-but-71127) |
| Your leadership asks whether to co-design workloads around a custom accelerator (Trainium/TPU/Inferentia) to cut cost. How do you evaluate the total cost of that portability loss? | expertise | SDE-2/3, Architect/Principal | GPU & Accelerator Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leadership-asks-whether-to-co-design-workloads-around-a-custom-ac-71080) |
| Your tuning job's trials show non-reproducible scores despite fixed seeds; what non-determinism sources on GPU would you check? | deep understanding | SDE-1/2, SDE-2/3 | Hyperparameter Tuning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-tuning-job-s-trials-show-non-reproducible-scores-despite-fixed-se-65983) |
| Your org wants a single distributed training platform for Transformers from 1B to 500B parameters; how do you design the parallelism abstraction so teams do not hand-tune sharding? | expertise | SDE-2/3, Architect/Principal | Transformers & Attention | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-a-single-distributed-training-platform-for-transformers-70378) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A vendor pitches a new accelerator claiming 2x perf-per-dollar but an immature compiler stack. How do you structure a de-risked pilot and set the bar that gates org-wide adoption? | expertise | SDE-2/3, Architect/Principal | GPU & Accelerator Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-vendor-pitches-a-new-accelerator-claiming-2x-perf-per-dollar-but-an--85047) |
