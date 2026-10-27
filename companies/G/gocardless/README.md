# GoCardless

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 0 | 0 | 2 | 8 | 7 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Define a data contract precisely. What does it cover beyond schema, how is it enforced in CI/CD, and what happens at runtime when a producer breaks it? Who is paged? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=define-a-data-contract-precisely-what-does-it-cover-beyond-schema-how--36516) |
| You're asked whether to adopt an open standard like Open Data Product Specification / data contracts spec across the org. What does standardizing the interface buy you at scale, and what's the risk of premature standardization? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-whether-to-adopt-an-open-standard-like-open-data-product--36609) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you treat data-contract governance (producer-consumer contracts, backward-compatibility rules, breaking-change review) as a first-class quality attribute in the utility tree for a mesh of hundreds of data products, and where does it most often become a tradeoff point against domain-team velocity? | deep understanding | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-treat-data-contract-governance-producer-consumer-contracts--125430) |
| How would you set up CI for a dbt project so that only the models changed in a PR (and their downstream children) are built and tested via a state-deferred slim run? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-ci-for-a-dbt-project-so-that-only-the-models-chan-120367) |
| How do you observe and enforce data contracts between a producing microservice and your ingestion pipeline? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Data Observability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-observe-and-enforce-data-contracts-between-a-producing-micr-124480) |
| What is your approach to embedding data contracts into the definition of a data product so that producers and consumers agree on semantics before anything is built? | expertise | SDE-2/3, Architect/Principal | Data Product Thinking | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-approach-to-embedding-data-contracts-into-the-definition--127132) |
| How would you design data contracts as the enforcement boundary for quality, and what belongs in a contract versus what belongs in a runtime check? | expertise | SDE-2/3, Architect/Principal | Data Quality Framework & SLAs | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-data-contracts-as-the-enforcement-boundary-for-qu-126923) |
| What governance model do you use for 'data contracts' at the access layer — how does a producer encode who may consume each field and how is that enforced when the contract is versioned and evolves? | deep understanding | SDE-2/3, Architect/Principal | Data Security & Access Governance | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-governance-model-do-you-use-for-data-contracts-at-the-access-laye-126662) |
| How do you migrate and preserve data contracts between producers and consumers so producers can't break the lakehouse tables downstream teams now depend on? | deep understanding | SDE-2/3, Architect/Principal | Lakehouse Migration Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-migrate-and-preserve-data-contracts-between-producers-and-c-126895) |
| Explain how a data contract enforced at ingestion prevents a cross-cloud consumer from silently breaking when a producer in another cloud changes a field — what tooling enforces it and where does it leak? | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-a-data-contract-enforced-at-ingestion-prevents-a-cross-clo-127255) |
