# Acryl

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 1 | 12 | 12 | 12 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Defend a build-vs-buy decision for the data catalog: an open-source stack (DataHub/OpenMetadata) vs a commercial platform (Collibra/Alation) vs building your own. What tips it for a 2000-engineer org? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=defend-a-build-vs-buy-decision-for-the-data-catalog-an-open-source-sta-36553) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| For the data catalog + lineage + governance layer, how do you weigh buying Collibra/Alation against adopting OpenMetadata/DataHub OSS versus building bespoke — when the whole investment only pays off if adoption approaches universal across every producing and consuming team? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-the-data-catalog-lineage-governance-layer-how-do-you-weigh-buying--125816) |
| How do you decide build-vs-buy for a data-catalog-driven discovery + search experience thousands of analysts live in daily (buy Atlan/Select Star vs DataHub OSS vs bespoke) when the value is time-to-find-trusted-data and switching cost dominates once adoption is deep? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-catalog-driven-discovery-sea-125858) |
| How do you fold the cost of lineage and metadata capture into the data-platform capacity plan, given column-level lineage across thousands of tables generates its own high-volume metadata store? When does end-to-end lineage become a top cost line worth governing? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-fold-the-cost-of-lineage-and-metadata-capture-into-the-data-125396) |
| Your data catalog, lineage, and data-quality tooling has quietly become a top cost line as it scans and profiles every table on a schedule. How would you govern profiling frequency and column-level lineage depth as a cost lever without going blind on data quality? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-data-catalog-lineage-and-data-quality-tooling-has-quietly-become--125329) |
| An interviewer probes: your lineage is column-level for SQL transforms but goes dark inside a Spark UDF or a Python pandas step where PII gets copied into a new column. How do you architect lineage capture that survives opaque code transforms so classification propagates to derived columns? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-your-lineage-is-column-level-for-sql-transforms--126022) |
| How do you architect a data catalog (Unity Catalog/Glue/DataHub/Collibra) so that classification tags and access policies attached at the catalog are actually enforced at the compute engine — not just documentation — across Spark Trino and warehouse query paths simultaneously? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-data-catalog-unity-catalog-glue-datahub-collibr-126018) |
| Build-vs-buy: make the case for and against adopting a managed catalog (Unity Catalog / Purview / DataHub Cloud) versus building an internal metadata service. What tips your decision at a 5000-person data org? | expertise | SDE-2/3, Architect/Principal | Data Catalog & Metadata Engineering | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=build-vs-buy-make-the-case-for-and-against-adopting-a-managed-catalog--126516) |
| Compare OpenMetadata, DataHub, Amundsen, and a commercial catalog on their metadata models and extensibility. If you were standardizing across an org, which would you pick and why — or would you build? | expertise | SDE-2/3, Architect/Principal | Data Catalog & Metadata Engineering | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-openmetadata-datahub-amundsen-and-a-commercial-catalog-on-thei-126536) |
| Describe how you'd design the metadata ingestion pipeline itself so that adding a new source (a new warehouse, BI tool, or ML feature store) is a config change, not a code project. | expertise | SDE-2/3, Architect/Principal | Data Catalog & Metadata Engineering | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-design-the-metadata-ingestion-pipeline-itself-so-th-126520) |
| Compare push-based versus pull-based metadata ingestion into a catalog like DataHub. Which did you pick and why? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Data Governance & Lineage | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-push-based-versus-pull-based-metadata-ingestion-into-a-catalog-124577) |
| An interviewer probes: 'your data catalog is comprehensive but nobody trusts the freshness or lineage because it's populated by nightly crawls that lag reality.' Architect active/push metadata so lineage and freshness are emitted by the pipelines themselves at run time, and what makes engineers actually keep it accurate. | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-your-data-catalog-is-comprehensive-but-nobody-tr-125706) |
| You're choosing between a build-your-own DataHub/OpenMetadata catalog and a commercial one (Alation/Collibra/Atlan) for a 60-team enterprise. Frame the build-vs-buy around active-metadata push, lineage accuracy, and the catalog-goes-stale problem, and defend what makes a catalog actually get used versus ignored. | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-choosing-between-a-build-your-own-datahub-openmetadata-catalog--125632) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data catalog / lineage / governance layer (Collibra/Alation vs OpenMetadata/DataHub OSS vs bespoke) that only pays off if adoption is near-universal across every schema and pipeline team? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-catalog-lineage-governance-l-113011) |
