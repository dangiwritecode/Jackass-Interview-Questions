# Anthem

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 0 | 4 | 4 | 4 |
| ML Engineer | 0 | 0 | 0 | 6 | 6 | 6 |
| AI Engineer | 0 | 0 | 0 | 2 | 2 | 2 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you enforce a consistent data-classification and tagging taxonomy across clouds so that PII controls apply identically whether data sits in S3, GCS or ADLS? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-enforce-a-consistent-data-classification-and-tagging-taxono-127234) |
| How do you prevent a multi-cloud strategy from doubling your compliance-audit burden — can you make controls provably equivalent across clouds so auditors sign off once? | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-prevent-a-multi-cloud-strategy-from-doubling-your-complianc-127273) |
| You need to give a data-science team read access to production data that spans two clouds without copying it into notebooks — design the governed access pattern and its audit trail. | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-give-a-data-science-team-read-access-to-production-data-th-127258) |
| A dataset is under legal hold but your lifecycle rule tried to expire it. How do you architect lifecycle so legal holds and retention locks always win over cost policies? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-dataset-is-under-legal-hold-but-your-lifecycle-rule-tried-to-expire--126740) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a bias/fairness-testing and model-validation harness for regulated ML (buy vs build) when a fairness violation is a regulatory fine and off-the-shelf metrics don't map to your protected-attribute definitions? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-bias-fairness-testing-and-model-v-69827) |
| How do you decide build-vs-buy for a model-explainability/interpretability layer for regulated lending or healthcare (buy Fiddler/Arthur vs build on SHAP/LIME + your own reports) when adverse-action explanations are legally mandated per decision? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-model-explainability-interpretabi-69813) |
| How do you decide build-vs-buy for a model-governance + lineage + audit layer (buy a model-governance product vs build on your registry) when regulators demand model cards, approval trails, and explainability for every deployed model? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-model-governance-lineage-audit-la-69790) |
| How do you decide build-vs-buy for a synthetic-data-generation platform to unblock training on regulated data (buy Gretel/Mostly AI vs build your own generative + differential-privacy pipeline) when the compliance risk of your own de-identification is the crux? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-synthetic-data-generation-platfor-69784) |
| Present how you'd architect an audit and compliance trail for every PyTorch model decision in a high-stakes domain so you can defend it in a regulatory review. | expertise | SDE-2/3, Architect/Principal | PyTorch | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=present-how-you-d-architect-an-audit-and-compliance-trail-for-every-py-70352) |
| How do you handle retraining when compliance requires model change notifications to customers before behavior shifts (regulated industries)? | expertise | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-retraining-when-compliance-requires-model-change-not-72439) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a data-governance and lineage architecture where any tool an agent calls may touch regulated data: track what the model saw, prove compliance to auditors, and enforce purpose limitation across tool calls without storing raw prompts forever. | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-governance-and-lineage-architecture-where-any-tool-an-ag-83080) |
| What's your approach to token budgeting for compliance-heavy domains where you must also pay for redaction, logging, and audit re-processing? | deep understanding | SDE-2/3, Architect/Principal | Token Budgeting & Throughput Estimation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-token-budgeting-for-compliance-heavy-domains-w-86413) |
