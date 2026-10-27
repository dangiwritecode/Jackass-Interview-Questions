# Pachyderm

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 5 | 10 | 6 | 10 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you govern the versioning and reproducibility of datasets so a model or report can be regenerated exactly from the data as it existed at a past date? | expertise | SDE-2/3, Architect/Principal | Data Governance & Stewardship | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-the-versioning-and-reproducibility-of-datasets-so-114838) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-versioning/dataset-management layer for training reproducibility (buy Pachyderm/managed vs DVC/lakeFS/OSS vs bespoke) when 'reproduce this model exactly' must be a true statement years later for audits? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-versioning-dataset-managemen-69795) |
| An interviewer asks how you'd govern the reproducibility-vs-erasure tension: reproducible ML requires pinning exact training data but GDPR erasure requires removing individuals from it. How do you architect a training pipeline that is both reproducible and erasable? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-asks-how-you-d-govern-the-reproducibility-vs-erasure-te-70020) |
| What's your strategy for versioning datasets so that a model can always be re-trained on exactly the data snapshot it originally used, even years later? | deep understanding | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-versioning-datasets-so-that-a-model-can-alway-72104) |
| A model config store must serve 'the version of these features as of timestamp T' for reproducible training; compare full snapshots, deltas, and a persistent (immutable) tree for storage and read cost. | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-model-config-store-must-serve-the-version-of-these-features-as-of-ti-62535) |
| A model retraining triggers on data changes and you must diff two large feature-config trees efficiently; how would a Merkle-tree hash let you skip unchanged subtrees, and where does the hashing cost pay off? | expertise | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-model-retraining-triggers-on-data-changes-and-you-must-diff-two-larg-62508) |
| How do you version the training data alongside the XGBoost model so a regression can be reproduced three months later? | intermediate experience | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-version-the-training-data-alongside-the-xgboost-model-so-a--65881) |
| How would you make a FastAPI model service reproducible so a prediction from six months ago can be regenerated exactly, given model, code, and dependency versions? | expertise | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-make-a-fastapi-model-service-reproducible-so-a-predictio-62940) |
| Explain how you'd design the platform's approach to model and data versioning together, so a rollback restores a consistent (code, data, model, feature) state and not a Frankenstein. | deep understanding | SDE-2/3, Architect/Principal | ML Platform Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-the-platform-s-approach-to-model-and-data-ver-72011) |
| What data versioning and lineage practices do you put in place so a post-trained model's training data is fully auditable? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-data-versioning-and-lineage-practices-do-you-put-in-place-so-a-po-68126) |
| How do you architect a data-versioning and snapshotting layer so every PyTorch training run is tied to an immutable, reproducible dataset without exploding storage cost? | deep understanding | SDE-2/3, Architect/Principal | PyTorch | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-data-versioning-and-snapshotting-layer-so-every-70315) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-versioning/lineage layer for training and RAG corpora (buy vs DVC/lakeFS/OpenLineage) when 'reproduce this fine-tune and this retrieval index exactly' must be a true statement years later for an audit? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-versioning-lineage-layer-for-83824) |
| What's your framework for governing dataset versioning so a regulated model can be re-trained on the exact corpus snapshot it originally used, years later? | expertise | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-framework-for-governing-dataset-versioning-so-a-regulated--86791) |
| How would you design a data-versioning and lineage backbone that ties datasets, features, model artifacts, and evaluations together for the whole company? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-data-versioning-and-lineage-backbone-that-ties--84366) |
