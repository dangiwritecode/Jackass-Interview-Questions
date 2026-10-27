# Adevinta

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 3 | 3 | 3 |
| Data Engineer | 0 | 0 | 0 | 8 | 8 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Conway's law is pushing your teams toward per-team datastores that each make their own CAP choice, producing a patchwork of consistency guarantees at the seams. How do you re-shape team topologies so the CAP boundaries land where they belong? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=conway-s-law-is-pushing-your-teams-toward-per-team-datastores-that-eac-32209) |
| How do you operationalize 'data as a product' so it isn't just a slide? Define the SLAs, ownership, discoverability, and lifecycle contract a domain team must sign up to before a dataset is 'published'. | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-operationalize-data-as-a-product-so-it-isn-t-just-a-slide-d-36511) |
| You're evaluating whether to adopt a data-mesh product-catalog layer on top of an existing centralized platform (a 'mesh-lite'). Is this a pragmatic hybrid or a worst-of-both? Where does it break down at scale? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-evaluating-whether-to-adopt-a-data-mesh-product-catalog-layer-o-36563) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a data-mesh cost model where each domain team owns and pays for its own data products but shares a central platform (catalog, storage, compute pools)? How do you allocate the truly-shared tier so a domain internalizes its footprint without endless allocation disputes? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-data-mesh-cost-model-where-each-domain-team-own-125315) |
| How do you decide whether to run a central data-platform team that owns all warehouse/cluster provisioning and cost, or let domain teams self-serve within budgets? Argue the efficiency-vs-velocity trade-off and where you'd centralize the commitment buying in a data-mesh org. | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-run-a-central-data-platform-team-that-own-125376) |
| How do you handle the org-political problem where a central data-platform team is measured on cost savings while domain teams are measured on data-product delivery speed, creating opposed incentives? Design the incentive structure so both win rather than fight over the warehouse budget. | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-org-political-problem-where-a-central-data-platf-125405) |
| How would you design an internal 'data marketplace' where domain teams pay realistic per-GB-stored and per-compute-second prices reflecting true marginal cost, so they self-optimize their data products — while avoiding the failure where teams under-invest in critical shared datasets to dodge the bill? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-internal-data-marketplace-where-domain-teams-p-125412) |
| Your lake's data-transfer/egress cost is a fast-growing line as domains read each other's data cross-region and cross-account. How do you find the chatty cross-domain read paths and redesign data placement and replication to cut egress without breaking mesh autonomy? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-lake-s-data-transfer-egress-cost-is-a-fast-growing-line-as-domain-125335) |
| When you say you have a data mesh across clouds, how do the domain teams actually publish products that a consumer in another cloud can discover and query without a central copy? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Data Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-you-say-you-have-a-data-mesh-across-clouds-how-do-the-domain-team-127226) |
| In a data mesh where each domain owns its products independently how do you enforce a single consistent DSAR fulfillment SLA without recentralizing ownership? | expertise | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-a-data-mesh-where-each-domain-owns-its-products-independently-how-d-127317) |
| What's your framework for deciding whether tiering should be driven by age, by access frequency, by business classification, or by a blend, across a data mesh with many domain owners? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-framework-for-deciding-whether-tiering-should-be-driven-by-126723) |
