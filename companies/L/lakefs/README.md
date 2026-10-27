# lakeFS

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 30

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 1 | 4 | 4 | 4 |
| Data Engineer | 0 | 0 | 1 | 5 | 4 | 5 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 9 | 16 | 12 | 16 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect for reproducibility — 'give me exactly the dataset as it was on 2024-11-01 for this ML model'? What does time-travel/snapshotting cost you in storage and metadata, and where do you cap retention? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-for-reproducibility-give-me-exactly-the-dataset-a-36584) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What governance controls ensure reproducibility — that an incident's model decision can be re-derived from the exact telemetry snapshot months later? | expertise | SDE-2/3, Architect/Principal | AIOps Data Governance & Standardization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-governance-controls-ensure-reproducibility-that-an-incident-s-mod-103126) |
| What's your strategy for governing dataset versioning of the telemetry corpus so a regulated incident-prediction model can be re-trained on its exact original snapshot years later? | expertise | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-governing-dataset-versioning-of-the-telemetry-101392) |
| Explain how you'd version telemetry datasets in the lake so an anomaly model can be reproducibly retrained on the exact data it saw. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability Data Lake | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-version-telemetry-datasets-in-the-lake-so-an-anomaly-98071) |
| How would you architect a reproducibility guarantee so any AIOps model retrained six months from now sees the byte-identical lake snapshot it originally trained on? | expertise | SDE-2/3, Architect/Principal | Observability Data Lake | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-reproducibility-guarantee-so-any-aiops-model-102395) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-versioning / lakehouse branching capability (buy lakeFS-managed / Nessie vs build snapshot-based branching on Iceberg) when 'reproduce exactly what this pipeline saw on this date' must be a true statement years later for a financial audit? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-versioning-lakehouse-branchi-125880) |
| How do you decide build-vs-buy for a self-service data-provisioning / dataset-branching capability for dev-and-test environments (buy vs build snapshot + PII-scrub + refresh pipelines) when refresh-from-prod latency and scrubbing correctness both gate release quality for data-consuming teams? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-self-service-data-provisioning-da-125879) |
| Describe how you'd version datasets so consumers can pin to a stable version while you iterate on the pipeline. | deep understanding | SDE-1/2, SDE-2/3 | Data Pipeline Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-version-datasets-so-consumers-can-pin-to-a-stable-v-122610) |
| How do you build a platform strategy that treats reproducibility and time-travel as first-class — for audit, backfills, and ML — and what storage/compute cost does that impose that you must budget for? | deep understanding | SDE-2/3, Architect/Principal | Data Platform Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-a-platform-strategy-that-treats-reproducibility-and-t-126460) |
| What's your strategy for platform-level testing and CI/CD of data pipelines so a bad merge can't corrupt production tables — how do you build a staging tier for stateful data without duplicating petabytes? | deep understanding | SDE-2/3, Architect/Principal | Data Platform Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-platform-level-testing-and-ci-cd-of-data-pipe-126493) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you govern the versioning and reproducibility of datasets so a model or report can be regenerated exactly from the data as it existed at a past date? | expertise | SDE-2/3, Architect/Principal | Data Governance & Stewardship | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-the-versioning-and-reproducibility-of-datasets-so-114838) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect immutable, versioned dataset snapshots on AWS so a training job pins an exact, reproducible view of the data — comparing S3 versioning, dated prefixes, and Iceberg time-travel on reproducibility, cost, and how they interact with a right-to-be-forgotten deletion? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-immutable-versioned-dataset-snapshots-on-aws-so-a-68652) |
| How do you decide build-vs-buy for a data-versioning/dataset-management layer for training reproducibility (buy Pachyderm/managed vs DVC/lakeFS/OSS vs bespoke) when 'reproduce this model exactly' must be a true statement years later for audits? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-versioning-dataset-managemen-69795) |
| How do you version datasets so a CI pipeline can pin the exact training data and reproduce a model months later, and what tooling would you use? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-version-datasets-so-a-ci-pipeline-can-pin-the-exact-trainin-63507) |
| Explain how you'd version and manage a growing labeled image dataset so training runs are reproducible as new labels stream in. | intermediate experience | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-version-and-manage-a-growing-labeled-image-dataset-s-66282) |
| You must make training data reproducible and dataset-versioned alongside model versions across the whole org. Compare table-format time-travel, a data-version-control tool (lakeFS/DVC), and snapshot copies. What do you standardize on and why? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-make-training-data-reproducible-and-dataset-versioned-alongsi-69690) |
| How would you design a rollback strategy when a bad feature-pipeline deploy has already written corrupt features consumed by production models? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Data Pipelines (Airflow/Spark) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-rollback-strategy-when-a-bad-feature-pipeline-d-68334) |
| How would you version and reproduce a feature pipeline run so a model can be retrained on the exact data snapshot months later? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Data Pipelines (Airflow/Spark) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-version-and-reproduce-a-feature-pipeline-run-so-a-model--68310) |
| What's your strategy for versioning datasets so that a model can always be re-trained on exactly the data snapshot it originally used, even years later? | deep understanding | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-versioning-datasets-so-that-a-model-can-alway-72104) |
| A model config store must serve 'the version of these features as of timestamp T' for reproducible training; compare full snapshots, deltas, and a persistent (immutable) tree for storage and read cost. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-model-config-store-must-serve-the-version-of-these-features-as-of-ti-62535) |
| Explain how you'd make a training dataset immutable and versioned so an experiment is exactly reproducible six months later. What does data lineage give you when a model in production is found to have trained on corrupted data? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-make-a-training-dataset-immutable-and-versioned-so-a-64529) |
| Your distributed training reads training data from a data warehouse via a query that occasionally returns slightly different rows run-to-run, hurting reproducibility. Explain how snapshot isolation or dataset versioning (e.g. Delta/Iceberg time-travel) fixes this. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-distributed-training-reads-training-data-from-a-data-warehouse-vi-64528) |
| How do you version the training data alongside the XGBoost model so a regression can be reproduced three months later? | intermediate experience | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-version-the-training-data-alongside-the-xgboost-model-so-a--65881) |
| How would you design a data-versioning and lineage backbone that ties datasets features model artifacts and evaluations together for the whole organization? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-data-versioning-and-lineage-backbone-that-ties--70514) |
| What data versioning and lineage practices do you put in place so a post-trained model's training data is fully auditable? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-data-versioning-and-lineage-practices-do-you-put-in-place-so-a-po-68126) |
| How do you architect a data-versioning and snapshotting layer so every PyTorch training run is tied to an immutable, reproducible dataset without exploding storage cost? | deep understanding | SDE-2/3, Architect/Principal | PyTorch | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-data-versioning-and-snapshotting-layer-so-every-70315) |
| Design the platform's data-versioning so that a training dataset is an immutable, addressable snapshot, and any experiment records exactly which snapshot it used, enabling true reproducibility. What's the storage-cost strategy so you don't keep infinite copies of everything? | deep understanding | SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-platform-s-data-versioning-so-that-a-training-dataset-is-an-70142) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-versioning/lineage layer for training and RAG corpora (buy vs DVC/lakeFS/OpenLineage) when 'reproduce this fine-tune and this retrieval index exactly' must be a true statement years later for an audit? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-versioning-lineage-layer-for-83824) |
| What's your framework for governing dataset versioning so a regulated model can be re-trained on the exact corpus snapshot it originally used, years later? | expertise | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-framework-for-governing-dataset-versioning-so-a-regulated--86791) |
| How would you design a data-versioning and lineage backbone that ties datasets, features, model artifacts, and evaluations together for the whole company? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-data-versioning-and-lineage-backbone-that-ties--84366) |
