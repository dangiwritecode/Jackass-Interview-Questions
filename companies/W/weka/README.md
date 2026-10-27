# Weka

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 1 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 0 | 4 | 4 | 4 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A team asks for a shared PVC mounted read-write across 8 replicas of a reporting service. How would you evaluate ReadWriteMany options versus redesigning to avoid shared writable state? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-team-asks-for-a-shared-pvc-mounted-read-write-across-8-replicas-of-a-45926) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the platform's approach to scaling checkpointing for very large models so that writing terabyte-scale checkpoints doesn't stall the whole training cluster on I/O. What sharded, asynchronous, or incremental checkpoint architecture keeps overhead flat as model and cluster size grow? | expertise | SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-platform-s-approach-to-scaling-checkpointing-for-very-large-100683) |
| Design the platform's storage tier for training data at exabyte scale so throughput to a thousand concurrent readers doesn't collapse. Contrast object-store-plus-cache, parallel filesystems, and a data-loading service, and pick one with a concrete bandwidth argument. | expertise | SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-platform-s-storage-tier-for-training-data-at-exabyte-scale--100647) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a high-throughput training-data storage + streaming loader tier (buy a managed data lake + loader vs build on object storage + WebDataset/MosaicML StreamingDataset) when GPU-idle-waiting-on-data is your dominant training inefficiency? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-high-throughput-training-data-sto-69822) |
| How do you architect a checkpoint storage and retrieval subsystem for multi-terabyte sharded checkpoints so that checkpoint I/O never becomes the throughput ceiling for a 2000-GPU job? | expertise | SDE-2/3, Architect/Principal | Distributed Training (Data/Model Parallelism) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-checkpoint-storage-and-retrieval-subsystem-for--70687) |
| How do you plan storage and data-pipeline capacity so GPUs aren't starved waiting on I/O during training? | expertise | SDE-2/3, Architect/Principal | GPU Fleet & Capacity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-storage-and-data-pipeline-capacity-so-gpus-aren-t-star-71950) |
| How would you architect a KV-cache tiering strategy (HBM to CPU to NVMe to remote store) for a platform serving very long shared contexts across thousands of sessions? | expertise | SDE-2/3, Architect/Principal | Inference Optimization (vLLM/TensorRT) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-kv-cache-tiering-strategy-hbm-to-cpu-to-nvme-71177) |
