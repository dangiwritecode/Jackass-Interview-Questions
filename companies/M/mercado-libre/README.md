# Mercado Libre

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 3 | 3 | 3 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 0 | 0 | 1 | 3 | 2 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the reference architecture for a global inventory platform that must never oversell high-value SKUs but can tolerate soft counts on low-value ones. How do you make CAP posture a per-SKU-class attribute rather than a system-wide switch? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-reference-architecture-for-a-global-inventory-platform-that-32243) |
| You're evolving a decade-old CP monolith datastore into domain-oriented services over three years using the strangler-fig pattern. Sequence the extraction so that at no cutover step do you accidentally weaken a consistency guarantee users depend on. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-evolving-a-decade-old-cp-monolith-datastore-into-domain-oriente-32222) |
| Design the cross-domain order-to-cash workflow for a global marketplace spanning ordering, inventory, payments, tax, fraud, and fulfillment — each a separate domain in a different region. How do you decompose it into sagas and where do you deliberately keep strong consistency? | expertise | SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-cross-domain-order-to-cash-workflow-for-a-global-marketplac-34114) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your company runs 12 country sites off one platform with wildly different network conditions and regulatory constraints. Design the per-region performance strategy and the single control plane that manages it without 12 forks. | expertise | SDE-2/3, Architect/Principal | Web Performance Optimization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-company-runs-12-country-sites-off-one-platform-with-wildly-differ-40235) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle Brazil's LGPD and other emerging privacy laws so the platform is regime-agnostic and a new law becomes a config change not a re-architecture? | expertise | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-brazil-s-lgpd-and-other-emerging-privacy-laws-so-the-127398) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd choose between one big XGBoost model and many per-segment models for a multi-country product, considering ops overhead. | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-choose-between-one-big-xgboost-model-and-many-per-se-65903) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you govern the definition of 'harm' itself when different regions, cultures, and business units have materially different thresholds — do you centralize or federate the taxonomy? | expertise | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-govern-the-definition-of-harm-itself-when-different-regions-86060) |
| How do you design the migration from batch scoring to real-time inference across dozens of consuming products so no consumer even notices the cutover? | deep understanding | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-the-migration-from-batch-scoring-to-real-time-infere-84351) |
| Your classifier accuracy dropped only in one region. How would you trace whether it is data, language, or feature-availability driven? | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-classifier-accuracy-dropped-only-in-one-region-how-would-you-trac-79457) |
