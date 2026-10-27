# AtScale

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 0 | 10 | 10 | 10 |
| Database Developer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for the semantic/metrics layer that defines 'what revenue means' across the org — buy a headless BI product (Cube/AtScale/dbt Semantic Layer) vs build governed metric definitions yourself — when inconsistent metric logic across tools is the actual pain? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-semantic-metrics-layer-that-def-125822) |
| How do you build a coalition of allies across teams before proposing a controversial change — say deprecating all direct warehouse reads in favor of a governed semantic layer — versus dropping it cold in a big meeting? Walk me through the pre-wiring you do. | deep understanding | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-a-coalition-of-allies-across-teams-before-proposing-a-126180) |
| How would you evaluate moving from a warehouse-centric BI stack to a headless BI / semantic-layer-first architecture across the org — what's the migration risk and who resists it? | deep understanding | SDE-2/3, Architect/Principal | Data Platform Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-moving-from-a-warehouse-centric-bi-stack-to-a-h-126470) |
| What is the interplay between a data product and a semantic layer — should the metric definitions live inside the product or in a shared layer above it? | expertise | SDE-2/3, Architect/Principal | Data Product Thinking | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-interplay-between-a-data-product-and-a-semantic-layer-shou-127157) |
| You're deciding whether the enterprise semantic/metrics layer lives in the BI tool, in a headless dedicated layer, or pushed into the warehouse as views. Frame the trade-off for 30 consuming tools (BI, notebooks, reverse-ETL, LLM apps) and defend where a headless layer earns its operational cost. | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-whether-the-enterprise-semantic-metrics-layer-lives-in-125619) |
| A bar-raiser asks: you cut warehouse cost by pushing aggregations into pre-computed cubes, but now every schema change forces expensive cube rebuilds and the storage grows. Walk me through the point where pre-aggregation stops paying for itself against just scanning on demand with a bigger warehouse. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-asks-you-cut-warehouse-cost-by-pushing-aggregations-into--125942) |
| Why might you introduce a 'Platinum' or curated-semantic layer above Gold, and where does a semantic layer / metrics store fit relative to the medallion? | deep understanding | SDE-2/3, Architect/Principal | Medallion Architecture (Bronze/Silver/Gold) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-you-introduce-a-platinum-or-curated-semantic-layer-above-gol-126260) |
| How do you use a stable-contract semantic layer as the strangler facade so consumers don't see whether a metric is served by the old warehouse or the new lakehouse? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-use-a-stable-contract-semantic-layer-as-the-strangler-facad-125732) |
| How do you architect a single semantic/metrics layer that serves BI tools connected to warehouses in different clouds without recomputing definitions three times? | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-single-semantic-metrics-layer-that-serves-bi-to-127237) |
| How would you architect a unified real-time and batch semantic layer so business metrics are defined once and computed consistently in both paths? | expertise | SDE-2/3, Architect/Principal | Real-time Analytics Architecture | Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-unified-real-time-and-batch-semantic-layer-s-127574) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd architect query result caching and materialized-cube pre-aggregation for a BI layer serving 10k dashboards, so 90% of dashboard loads never touch the warehouse. Where does cube maintenance cost exceed the query savings, and how do you decide what to pre-aggregate? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-architect-query-result-caching-and-materialized-cube-112723) |
| How would you design a semantic layer and metric store governance so a metric has a single owned definition that BI, notebooks, and APIs all share? | expertise | SDE-2/3, Architect/Principal | Data Governance & Stewardship | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-semantic-layer-and-metric-store-governance-so-a-114797) |
| Walk me through how you'd design an org-wide 'semantic layer' so business definitions (revenue, active user) are computed identically whether a query hits an OLTP operational report or the OLAP warehouse. | expertise | SDE-2/3, Architect/Principal | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-design-an-org-wide-semantic-layer-so-busines-113453) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your approach to establishing an enterprise-wide semantic layer so ML features and BI metrics share one governed source of truth? | deep understanding | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-establishing-an-enterprise-wide-semantic-layer-72121) |
