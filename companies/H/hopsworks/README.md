# Hopsworks

**Tier:** Tier 5  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 5 | 6 | 1 | 6 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the cost-attribution model for a shared machine-learning feature store used by 30 teams, where storage, serving, and training compute are jointly consumed. How do you fairly split cost and drive efficient feature reuse instead of duplication? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-cost-attribution-model-for-a-shared-machine-learning-featur-37082) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer asks how you'd govern data that flows into a real-time streaming ML feature store — where the same event is simultaneously a training signal a serving feature and a regulated personal record — how do you apply consent retention and erasure at streaming velocity? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-asks-how-you-d-govern-data-that-flows-into-a-real-time--54093) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A bar-raiser asks: 'your feature computed in the batch training pipeline uses a window that isn't available at serving time — how did point-in-time correctness leak?' Walk through time-travel/as-of-join correctness at the platform level and how you make it impossible for a team to build a leaky feature. | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-asks-your-feature-computed-in-the-batch-training-pipeline-125643) |
| Contrast serving ML features from a warehouse-derived offline store versus a low-latency online store, and reconcile the training-serving skew that appears when the two diverge. Architect the enterprise feature-platform boundary so 50 model teams share features without reimplementing them per model. | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-serving-ml-features-from-a-warehouse-derived-offline-store-ve-125642) |
| Explain how you'd govern the cost of a feature store shared across data-science teams, where offline materialization, online serving, and point-in-time joins are jointly consumed. How do you fairly split cost and drive feature reuse instead of every team recomputing the same features? | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-the-cost-of-a-feature-store-shared-across-dat-125951) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect caching for an ML feature store backed by a database so a model retrain invalidates cached features tied to the old model version and never serves features from a mismatched distribution? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-caching-for-an-ml-feature-store-backed-by-a-datab-111516) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your feature store has a real-time and offline half. How do you guarantee consistent PII masking/consent enforcement across both without training-serving skew? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-feature-store-has-a-real-time-and-offline-half-how-do-you-guarant-72609) |
| Describe how you'd wire an XGBoost training job into a feature store so features are read point-in-time-correct and no future leakage occurs. | expertise | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-wire-an-xgboost-training-job-into-a-feature-store-s-65916) |
| How do you architect a feature pipeline so that adding a new feature to XGBoost doesn't require redeploying the entire serving stack? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-feature-pipeline-so-that-adding-a-new-feature-t-65939) |
| How do you handle a feature that's available at training time from batch data but has high latency or is unavailable at serving time for XGBoost? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-a-feature-that-s-available-at-training-time-from-bat-65956) |
| How do you handle a FastAPI model endpoint whose feature preprocessing depends on a lookup table that itself changes over time, keeping the table version pinned to the model? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-a-fastapi-model-endpoint-whose-feature-preprocessing-62965) |
| How would you architect a FastAPI feature-transformation endpoint reused by both training data prep and online serving so the exact same code path guarantees no skew? | expertise | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-fastapi-feature-transformation-endpoint-reus-62976) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect schema evolution in a feature store so upgrading a feature definition never silently breaks a downstream training job months later? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-schema-evolution-in-a-feature-store-so-upgradi-84356) |
