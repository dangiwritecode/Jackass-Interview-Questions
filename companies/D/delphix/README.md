# Delphix

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 1 | 3 | 3 | 3 |
| Data Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| Database Developer | 0 | 0 | 0 | 8 | 8 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A director proposes copying prod PII into staging so QA is realistic. As the principal reject or reshape this — architect a data-provisioning approach (synthetic data subsetting masking) that gives realistic test data with zero compliance exposure and quantify the trade-offs. | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-director-proposes-copying-prod-pii-into-staging-so-qa-is-realistic-a-37279) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-masking / synthetic-test-data pipeline for lower environments when a vendor gives you turnkey de-identification but building lets you prove your PII-scrubbing to auditors line-by-line — where does the compliance risk tip it? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-masking-synthetic-test-data--53798) |
| How do you decide build-vs-buy for a self-service database-branching / data-provisioning capability for test envs (buy vs build snapshot/anonymization pipeline) when refresh-from-prod latency and PII scrubbing both gate release quality? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-self-service-database-branching-d-53748) |
| A developer wants prod data copied into staging to reproduce a bug — why is that a compliance risk and what data-masking or subsetting approach would you offer instead? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-developer-wants-prod-data-copied-into-staging-to-reproduce-a-bug-why-47951) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-masking / synthetic-test-data pipeline for lower environments — buy Gretel/Tonic vs build your own de-identification — when a vendor gives turnkey masking but building lets you prove your PII-scrubbing line-by-line to auditors? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-masking-synthetic-test-data--125842) |
| How do you decide build-vs-buy for a self-service data-provisioning / dataset-branching capability for dev-and-test environments (buy vs build snapshot + PII-scrub + refresh pipelines) when refresh-from-prod latency and scrubbing correctness both gate release quality for data-consuming teams? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-self-service-data-provisioning-da-125879) |
| How do you keep test staging and lower environments compliant when engineers want realistic data — synthetic data masking or subsetting and what are the trade-offs? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-test-staging-and-lower-environments-compliant-when-eng-127373) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect and enforce a company standard for masking or synthesizing PII when backups are restored into lower environments for testing? | expertise | SDE-2/3, Architect/Principal | Backup & Recovery | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-and-enforce-a-company-standard-for-masking-or-syn-114183) |
| Make the build-versus-buy case for adopting a managed backup product like Rubrik or a cloud-native service versus building recovery orchestration in-house across your fleet. | expertise | SDE-2/3, Architect/Principal | Backup & Recovery | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=make-the-build-versus-buy-case-for-adopting-a-managed-backup-product-l-114143) |
| Design how you would provision realistic non-prod databases without copying prod PII — subsetting deterministic masking and synthetic generation that preserve referential integrity and cardinality so QA is realistic yet zero compliance exposure. Quantify the trade-offs. | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-would-provision-realistic-non-prod-databases-without-co-113059) |
| Architect a compliant test-data-management pipeline that produces realistic non-production datasets from PHI/PII without exposing real data — synthetic vs masked vs subsetted, and the fidelity trade-off. | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-compliant-test-data-management-pipeline-that-produces-real-115324) |
| What is your approach to governing test data management so non-prod environments get realistic data without leaking real PII? | deep understanding | SDE-2/3, Architect/Principal | Data Governance & Stewardship | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-approach-to-governing-test-data-management-so-non-prod-en-114781) |
| What's your approach to anonymizing or masking production data when cloning it into a shadow database for realistic migration dry-runs, at fleet scale? | deep understanding | SDE-2/3, Architect/Principal | Database Migrations & Versioning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-anonymizing-or-masking-production-data-when-cl-114290) |
| How would you architect a policy where developers get realistic test data that is provably free of production PII, at the scale of hundreds of teams cloning databases weekly? | deep understanding | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-policy-where-developers-get-realistic-test-d-114097) |
| How do you decide whether to invest in a commercial data-masking and test-data-management tool across all database vendors? | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-invest-in-a-commercial-data-masking-and-t-115430) |
