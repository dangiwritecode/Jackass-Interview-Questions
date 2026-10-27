# Gable

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 3 | 11 | 9 | 11 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a schema-evolution + backward-compatibility governance layer across your lakehouse tables (buy vs build compatibility checks in CI on Iceberg schema changes) when a non-additive schema change on a shared table can break every downstream job silently at read time? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-schema-evolution-backward-compati-125906) |
| How do you decide build-vs-buy for a schema-registry / data-contract enforcement system that sits on the critical path of every producer and consumer — buy vs build on Confluent Schema Registry/Buf — when a bad bet ossifies your whole data plane and blocks safe schema evolution? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-schema-registry-data-contract-enf-125827) |
| How do you decide build-vs-buy for the data-contract enforcement + producer-side testing capability (buy Gable/build on schema-registry + CI checks) when the goal is that a producer can't ship a breaking schema change that silently corrupts fifty downstream consumers? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-data-contract-enforcement-produ-125855) |
| How would you build a data-contract test into CI so a producer team can't merge a change that violates the schema a downstream consumer team depends on? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-data-contract-test-into-ci-so-a-producer-team-ca-120385) |
| How would you make CI validate that a new pipeline's output schema matches a registered downstream contract (column names, types, nullability) before allowing the deploy? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-make-ci-validate-that-a-new-pipeline-s-output-schema-mat-120462) |
| An interviewer challenges your 'design the data contract before the pipeline' mandate: 'for an internal exploratory dataset that changes weekly, contract-first just slows us down.' Defend precisely where contract-first pays off and where it's ceremony, and how you tier rigor by dataset criticality. | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-design-the-data-contract-before-the-pip-125690) |
| Design the enterprise data-contract architecture where a producer's schema change can break 200 downstream pipelines. How do you shift enforcement left so a breaking change fails in the producer's CI, and where do the contract, its SLAs, and its owner physically live in your platform? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-enterprise-data-contract-architecture-where-a-producer-s-sc-125622) |
| You're defining the enterprise 'data contract' every producing team signs: schema-evolution rules, freshness SLA, PII classification, retention, and dead-letter behavior. What goes in it, how is it enforced technically at the pipeline gate, and how do you evolve the contract without renegotiating with 50 teams each time? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-defining-the-enterprise-data-contract-every-producing-team-sign-125689) |
| How would you enforce a data contract on a Kafka topic so a producer team can't ship an event shape that silently breaks your dbt/warehouse models downstream? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kafka | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-enforce-a-data-contract-on-a-kafka-topic-so-a-producer-t-119580) |
| Teams routinely ship column renames and drops straight to shared tables and discover downstream breakage in production. How do you make expand-and-contract the default without a heavy gatekeeper, and how do you retrofit that discipline onto legacy producers who've never versioned a schema in their lives? | deep understanding | SDE-2/3, Architect/Principal | Technical Strategy & Roadmapping | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=teams-routinely-ship-column-renames-and-drops-straight-to-shared-table-125597) |
| Walk me through how you'd sequence adopting a data-contract strategy — moving the org from ad-hoc events to producer-owned versioned schemas with enforcement in CI — as a multi-quarter program with clear off-ramps if it stalls. | deep understanding | SDE-2/3, Architect/Principal | Technical Strategy & Roadmapping | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-sequence-adopting-a-data-contract-strategy-m-125549) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your approach to defining and enforcing data contracts between the producing store and every downstream consumer store to prevent breaking changes? | expertise | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-defining-and-enforcing-data-contracts-between--114624) |
