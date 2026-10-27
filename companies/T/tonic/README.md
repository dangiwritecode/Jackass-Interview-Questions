# Tonic

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 21

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 1 | 4 | 4 | 4 |
| Data Engineer | 0 | 0 | 0 | 5 | 5 | 5 |
| Database Developer | 0 | 0 | 0 | 7 | 7 | 7 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A director proposes copying prod PII into staging so QA is realistic. As the principal reject or reshape this — architect a data-provisioning approach (synthetic data subsetting masking) that gives realistic test data with zero compliance exposure and quantify the trade-offs. | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-director-proposes-copying-prod-pii-into-staging-so-qa-is-realistic-a-37279) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data anonymization / synthetic-data platform needed to unblock analytics on regulated data — where does the compliance risk of building your own de-identification tip the scale? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-anonymization-synthetic-data-41027) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-masking / synthetic-test-data pipeline for lower environments when a vendor gives you turnkey de-identification but building lets you prove your PII-scrubbing to auditors line-by-line — where does the compliance risk tip it? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-masking-synthetic-test-data--53798) |
| How do you decide build-vs-buy for a self-service database-branching / data-provisioning capability for test envs (buy vs build snapshot/anonymization pipeline) when refresh-from-prod latency and PII scrubbing both gate release quality? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-self-service-database-branching-d-53748) |
| How would you architect a data strategy for CI that gives realistic test fidelity without ever moving regulated PII into build environments, given today's pipelines seed test databases directly from production snapshots; cover synthetic generation, masking, and subsetting and their fidelity limits. | expertise | SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-data-strategy-for-ci-that-gives-realistic-te-52287) |
| Your pipeline seeds test databases from production snapshots, creating a PII compliance exposure; how would you get realistic test fidelity without ever moving regulated PII into build environments? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-pipeline-seeds-test-databases-from-production-snapshots-creating--46117) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-masking / synthetic-test-data pipeline for lower environments — buy Gretel/Tonic vs build your own de-identification — when a vendor gives turnkey masking but building lets you prove your PII-scrubbing line-by-line to auditors? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-masking-synthetic-test-data--125842) |
| How do you decide build-vs-buy for a self-service data-provisioning / dataset-branching capability for dev-and-test environments (buy vs build snapshot + PII-scrub + refresh pipelines) when refresh-from-prod latency and scrubbing correctness both gate release quality for data-consuming teams? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-self-service-data-provisioning-da-125879) |
| An interviewer probes: your team copies prod PII into a staging lake so pipeline development is realistic. As principal reject or reshape this — architect a synthetic-data and subsetting-plus-masking approach that gives realistic test data with zero compliance exposure, and quantify the trade-offs. | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-your-team-copies-prod-pii-into-a-staging-lake-so-126059) |
| Explain how you'd give data scientists sandbox access to sensitive production data using differential privacy or synthetic data, and where each technique fails to preserve analytic utility. | deep understanding | SDE-2/3, Architect/Principal | Data Security & Access Governance | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-give-data-scientists-sandbox-access-to-sensitive-pro-126634) |
| How do you keep test staging and lower environments compliant when engineers want realistic data — synthetic data masking or subsetting and what are the trade-offs? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-test-staging-and-lower-environments-compliant-when-eng-127373) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a database-branching / test-data-provisioning capability for lower environments (managed branching like Neon/PlanetScale vs a self-built snapshot + PII-scrub pipeline) when refresh-from-prod latency and masking both gate release quality? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-database-branching-test-data-prov-113017) |
| Design how you would provision realistic non-prod databases without copying prod PII — subsetting deterministic masking and synthetic generation that preserve referential integrity and cardinality so QA is realistic yet zero compliance exposure. Quantify the trade-offs. | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-would-provision-realistic-non-prod-databases-without-co-113059) |
| Architect a compliant test-data-management pipeline that produces realistic non-production datasets from PHI/PII without exposing real data — synthetic vs masked vs subsetted, and the fidelity trade-off. | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-compliant-test-data-management-pipeline-that-produces-real-115324) |
| What governance would you build around synthetic data generation so that generated data doesn't inadvertently reproduce or leak real records? | deep understanding | SDE-2/3, Architect/Principal | Data Governance & Stewardship | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-governance-would-you-build-around-synthetic-data-generation-so-th-114823) |
| What is your approach to governing test data management so non-prod environments get realistic data without leaking real PII? | deep understanding | SDE-2/3, Architect/Principal | Data Governance & Stewardship | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-approach-to-governing-test-data-management-so-non-prod-en-114781) |
| What's your approach to anonymizing or masking production data when cloning it into a shadow database for realistic migration dry-runs, at fleet scale? | deep understanding | SDE-2/3, Architect/Principal | Database Migrations & Versioning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-anonymizing-or-masking-production-data-when-cl-114290) |
| How would you architect a policy where developers get realistic test data that is provably free of production PII, at the scale of hundreds of teams cloning databases weekly? | deep understanding | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-policy-where-developers-get-realistic-test-d-114097) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you govern synthetic-data generation so downstream teams can rely on the synthetic set's fidelity and privacy claims without re-validating them each time? | deep understanding | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-synthetic-data-generation-so-downstream-teams-can-86091) |
| How do you decide build-vs-buy for a synthetic-data-generation pipeline to unblock training/eval on regulated data (buy Gretel/Mostly AI vs build your own generative + differential-privacy pipeline) when the compliance risk of your own de-identification is the crux? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-synthetic-data-generation-pipelin-83772) |
| What's your strategy for building eval on differentially-private or synthetic traffic when raw production data can't leave a secure enclave? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-building-eval-on-differentially-private-or-sy-86868) |
