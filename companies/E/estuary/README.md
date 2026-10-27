# Estuary

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 17

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| Data Engineer | 0 | 0 | 0 | 10 | 10 | 10 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you approach capacity planning for a data-pipeline SLA measured in freshness (data must be no older than X minutes) rather than latency? How does a freshness SLA change how you size stream vs batch and where you spend to keep the pipeline warm? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-capacity-planning-for-a-data-pipeline-sla-measured-52980) |
| You're asked to justify why your governance architecture stores classification and consent as immutable event history rather than mutable current-state — what compliance queries does the temporal model unlock and what's the cost you pay in complexity and storage? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-justify-why-your-governance-architecture-stores-classi-54079) |
| How do you architect the availability of a change-data-capture backbone that feeds dozens of downstream read systems, so that a CDC lag spike during a bulk write doesn't leave every search index and cache hours stale at once — and where do you cap the fan-out? | deep understanding | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-availability-of-a-change-data-capture-backbon-52064) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A vendor SaaS is 30% cheaper than building your ingestion layer but locks your pipeline metadata and connector configs into their proprietary format — how do you quantify that data/config lock-in as a first-class risk and fold it into the decision rather than treating it as a footnote? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-vendor-saas-is-30-cheaper-than-building-your-ingestion-layer-but-loc-125835) |
| How do you decide build-vs-buy for a data-pipeline where the vendor's roadmap diverges from yours — they won't ship the connector or streaming-semantics feature you need for 18 months — do you fork the OSS, pay for a custom build, wait, or leave, and how do you make that call reversible? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-pipeline-where-the-vendor-s--125912) |
| How do you decide build-vs-buy for the ingestion/ELT connector layer — Fivetran/Airbyte-managed vs Airbyte-OSS vs hand-rolled connectors — when connector breakage during upstream SaaS API changes becomes a recurring reliability tax you pay in on-call, not license fees? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-ingestion-elt-connector-layer-f-125817) |
| How do you structure the build-vs-buy decision for a change-data-capture layer feeding your lakehouse — Debezium OSS vs Fivetran/managed CDC vs bespoke log-mining — given CDC becomes the nervous system between every OLTP source and downstream consumer and reliability tax dominates? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-structure-the-build-vs-buy-decision-for-a-change-data-captu-125823) |
| You championed a shared ingestion framework three teams now depend on, and it's become a maintenance burden your team resents as connectors and source APIs evolve. How do you renegotiate ownership and funding across the teams that benefit? | deep understanding | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-championed-a-shared-ingestion-framework-three-teams-now-depend-on--126160) |
| You've been asked to align eight teams on a single ingestion-and-CDC tooling standard so pipelines never diverge. Half already have working homegrown Kafka Connect and Debezium setups. How do you drive convergence without forcing expensive rewrites on teams that already work? | deep understanding | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-ve-been-asked-to-align-eight-teams-on-a-single-ingestion-and-cdc-t-126139) |
| Design the enterprise CDC-to-lakehouse architecture that turns 40 operational database change logs into queryable tables with correct merge semantics. Discuss handling out-of-order events, deletes, schema DDL propagation, and the initial-snapshot-at-scale problem without app-team rewrites. | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-enterprise-cdc-to-lakehouse-architecture-that-turns-40-oper-125638) |
| You're deciding whether to build the enterprise ingestion on managed connectors (Fivetran/Airbyte) or a self-operated CDC stack for 500 sources. Frame the build-vs-buy around per-row pricing at scale, connector coverage, exit cost, and who's on call at 2am when a connector silently drops rows. | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-whether-to-build-the-enterprise-ingestion-on-managed-c-125640) |
| Your CDC pipeline from a high-write OLTP database generates enormous changelog volume during batch jobs on the source, flooding Kafka and the sink warehouse with churn. How do you govern CDC cost — snapshotting strategy, filtering, debounce/compaction — so a source-side batch doesn't 10x your downstream data-platform cost? | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-cdc-pipeline-from-a-high-write-oltp-database-generates-enormous-c-125961) |
| Your data platform's ingestion tool (Fivetran/Airbyte) charges per monthly-active-row, and a chatty source with high-churn tables balloons the connector bill independent of value. How do you govern SaaS-ingestion cost — sync frequency, column pruning, source selection — and decide when self-managed CDC beats the managed connector? | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-data-platform-s-ingestion-tool-fivetran-airbyte-charges-per-month-125949) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a change-data-capture layer off your OLTP (self-run Debezium vs Fivetran vs a managed CDC) when it becomes the nervous system between your system-of-record and every downstream store? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-change-data-capture-layer-off-you-112957) |
| How do you decide build-vs-buy for an ELT/ingestion layer feeding your warehouse (Fivetran/Airbyte-managed vs self-run Airbyte vs custom connectors) when connector breakage during source-API changes is a recurring reliability tax on your data models? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-elt-ingestion-layer-feeding-your-113010) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you handle a FastAPI batch scoring endpoint that must process a 2GB uploaded file of records without loading it all into memory and while streaming partial progress back? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-a-fastapi-batch-scoring-endpoint-that-must-proces-62934) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your agent writes to a system of record and an event stream, and the two can diverge if one succeeds and the other fails mid-loop. Design the architecture that guarantees they stay consistent, and the reconciliation when they don't. | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-agent-writes-to-a-system-of-record-and-an-event-stream-and-the-tw-83130) |
