# N26

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 1 | 3 | 2 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a login system that must work across three regions with data residency rules (EU users' credentials never leave the EU). How does this constrain your token issuance and session store? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-login-system-that-must-work-across-three-regions-with-data-re-26163) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A new regulation requires you to attest that no telemetry from EU users is processed outside the EU. Architect a region-pinned observability pipeline, and explain how global querying and cross-region incident correlation still work under that constraint. | expertise | SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-new-regulation-requires-you-to-attest-that-no-telemetry-from-eu-user-39722) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must set a multi-region data residency strategy for a fintech operating in the EU and India on Azure; how do sovereignty, latency, and DR requirements shape your region and replication design? | expertise | SDE-2/3, Architect/Principal | Azure | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-set-a-multi-region-data-residency-strategy-for-a-fintech-oper-54537) |
| A regulator's enforcement action against a competitor just made a previously 'recommended' practice effectively mandatory — as principal how do you architect a horizon-scanning process that turns regulatory signals into prioritized platform work before it becomes an audit finding? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-regulator-s-enforcement-action-against-a-competitor-just-made-a-prev-54037) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your firm is entering the EU and must comply with GDPR data-residency plus Schrems II — architect a database platform where EU personal data keys never leave the EU even during cross-region DR failover. | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-firm-is-entering-the-eu-and-must-comply-with-gdpr-data-residency--115248) |
| A GDPR right-to-erasure request requires deleting a field's data across a table that's mid-migration to a new encrypted column. How do you reconcile the two workflows? | deep understanding | SDE-2/3, Architect/Principal | Database Migrations & Versioning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-gdpr-right-to-erasure-request-requires-deleting-a-field-s-data-acros-114260) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A compliance mandate says EU customer data used for ML training must never leave eu-central and models trained on it can't be served from other regions — how do you enforce this provably at the account, S3-routing, training-job, and serving layers? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-compliance-mandate-says-eu-customer-data-used-for-ml-training-must-n-68604) |
| What's the trade-off between using SHAP for per-prediction explanations in real time versus precomputing global importances, given latency constraints? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-the-trade-off-between-using-shap-for-per-prediction-explanation-65900) |
| How would you architect retraining to respect data residency so an EU model never trains on data that left the region? | expertise | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-retraining-to-respect-data-residency-so-an-eu--72456) |
