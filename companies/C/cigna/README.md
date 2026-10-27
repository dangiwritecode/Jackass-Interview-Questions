# Cigna

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 29

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 20 | 20 | 1 | 1 | 21 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 5 | 5 | 5 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect governance for a platform that offers customers a choice of compliance 'tiers' (baseline SaaS vs PCI-in-scope vs HIPAA-in-scope) provisioned self-serve — how do you keep the higher tiers from contaminating the shared control plane's scope? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-for-a-platform-that-offers-customers-a-54026) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A factless fact table is proposed to model coverage/eligibility. When is that elegant versus a sign someone doesn't understand the actual event grain? | deep understanding | SDE-2/3, Architect/Principal | Data Modeling Judgment (Kimball/Inmon/Data Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-factless-fact-table-is-proposed-to-model-coverage-eligibility-when-i-127662) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Compare application-layer encryption versus database-native TDE for a HIPAA ePHI store — what threat model does each defeat and where does TDE give you a false sense of security? | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-application-layer-encryption-versus-database-native-tde-for-a--115246) |
| A junior wrote a cursor loop that runs for hours. How do you convert it to a set-based operation and quantify the gain? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-junior-wrote-a-cursor-loop-that-runs-for-hours-how-do-you-convert-it-108591) |
| Compare the four default transaction isolation levels in SQL Server and the concurrency phenomena each prevents. | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-the-four-default-transaction-isolation-levels-in-sql-server-an-108560) |
| Explain how a computed column can be PERSISTED and indexed, and give a case where it improved query performance. | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-a-computed-column-can-be-persisted-and-indexed-and-give-a--108621) |
| Explain how you would generate a numbers or calendar table and why it beats recursive CTEs for large ranges. | intermediate experience | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-generate-a-numbers-or-calendar-table-and-why-it--108601) |
| Explain how you would grant least-privilege access to a stored procedure using ownership chaining and EXECUTE AS. | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-grant-least-privilege-access-to-a-stored-procedu-108635) |
| Explain optimistic concurrency using a rowversion column and how the application detects a conflicting update. | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-optimistic-concurrency-using-a-rowversion-column-and-how-the-a-108606) |
| Explain what CXPACKET and CXCONSUMER waits indicate and how MAXDOP and cost threshold for parallelism relate to them. | expertise | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-what-cxpacket-and-cxconsumer-waits-indicate-and-how-maxdop-and-108571) |
| How do FIRST_VALUE LAST_VALUE and the framing default catch people out with LAST_VALUE returning the current row? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-first-value-last-value-and-the-framing-default-catch-people-out-108596) |
| How do you interpret and act on a high signal from sys.dm_db_index_usage_stats when deciding to drop an index? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-interpret-and-act-on-a-high-signal-from-sys-dm-db-index-usa-108549) |
| How do you write an idempotent deployment script so re-running a schema change does not error or corrupt data? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-write-an-idempotent-deployment-script-so-re-running-a-schem-108586) |
| How does an ONLINE index rebuild work, what are its limitations, and how does RESUMABLE help a long-running rebuild? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-an-online-index-rebuild-work-what-are-its-limitations-and-how-108581) |
| How does the transaction log work with checkpoints, and how do the FULL SIMPLE and BULK_LOGGED recovery models affect log growth? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-the-transaction-log-work-with-checkpoints-and-how-do-the-full-108610) |
| How would you detect and fix a query returning duplicated rows after adding a one-to-many join? | intermediate experience | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-detect-and-fix-a-query-returning-duplicated-rows-after-a-108631) |
| How would you troubleshoot a nightly ETL procedure that intermittently fails with a transaction log full error only under peak load? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-troubleshoot-a-nightly-etl-procedure-that-intermittently-108642) |
| Walk me through investigating a report where the same procedure sometimes returns in 200ms and sometimes in 20 seconds. | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-investigating-a-report-where-the-same-procedure-someti-108640) |
| What are In-Memory OLTP tables and natively compiled procedures, and what workloads justify them despite their restrictions? | expertise | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-are-in-memory-oltp-tables-and-natively-compiled-procedures-and-wh-108615) |
| What are the UPDLOCK HOLDLOCK and READPAST table hints and give a real scenario for each in a queue-processing pattern. | expertise | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-are-the-updlock-holdlock-and-readpast-table-hints-and-give-a-real-108566) |
| What does SET STATISTICS IO and SET STATISTICS TIME tell you, and how do you interpret logical reads versus physical reads? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-set-statistics-io-and-set-statistics-time-tell-you-and-how-d-108626) |
| What is the plan cache, how do you find the most expensive cached plans with sys.dm_exec_query_stats, and what does plan cache bloat look like? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-plan-cache-how-do-you-find-the-most-expensive-cached-plans-108576) |
| When would you use a filtered index and what pitfalls (parameterization query rewrite) prevent it from being used? | deep understanding | SDE-1, SDE-1/2 | T-SQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-use-a-filtered-index-and-what-pitfalls-parameterization-108554) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle retraining when compliance requires model change notifications to customers before behavior shifts (regulated industries)? | expertise | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-retraining-when-compliance-requires-model-change-not-72439) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a data-governance and lineage architecture where any tool an agent calls may touch regulated data: track what the model saw, prove compliance to auditors, and enforce purpose limitation across tool calls without storing raw prompts forever. | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-governance-and-lineage-architecture-where-any-tool-an-ag-83080) |
| What's your strategy for evaluating models in a regulated domain where the eval itself must be validated and signed off by a compliance function? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-evaluating-models-in-a-regulated-domain-where-86914) |
| How do you keep prompt caching effective when your compliance team requires per-request injection of dynamic legal disclaimers? | expertise | SDE-2/3, Architect/Principal | Prompt Caching Strategy | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-prompt-caching-effective-when-your-compliance-team-req-86579) |
| What are the security and privacy risks of a shared prompt cache in a regulated environment (PII, PHI), and how do you design guardrails around them? | expertise | SDE-2/3, Architect/Principal | Prompt Caching Strategy | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-are-the-security-and-privacy-risks-of-a-shared-prompt-cache-in-a--86535) |
| What's your approach to token budgeting for compliance-heavy domains where you must also pay for redaction, logging, and audit re-processing? | deep understanding | SDE-2/3, Architect/Principal | Token Budgeting & Throughput Estimation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-token-budgeting-for-compliance-heavy-domains-w-86413) |
