# Gretel

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 29

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 5 | 5 | 5 |
| Database Developer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 1 | 10 | 9 | 10 |
| AI Engineer | 0 | 0 | 1 | 9 | 9 | 9 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A director proposes copying prod PII into staging so QA is realistic. As the principal reject or reshape this — architect a data-provisioning approach (synthetic data subsetting masking) that gives realistic test data with zero compliance exposure and quantify the trade-offs. | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-director-proposes-copying-prod-pii-into-staging-so-qa-is-realistic-a-37279) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data anonymization / synthetic-data platform needed to unblock analytics on regulated data — where does the compliance risk of building your own de-identification tip the scale? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-anonymization-synthetic-data-41027) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a data-anonymization / differential-privacy platform to unblock analytics on regulated data — where does the compliance risk of building your own de-identification (and being wrong) tip the scale toward buying a certified vendor's guarantees? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-anonymization-differential-p-125877) |
| How do you decide build-vs-buy for a data-masking / synthetic-test-data pipeline for lower environments — buy Gretel/Tonic vs build your own de-identification — when a vendor gives turnkey masking but building lets you prove your PII-scrubbing line-by-line to auditors? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-data-masking-synthetic-test-data--125842) |
| An interviewer probes: your team copies prod PII into a staging lake so pipeline development is realistic. As principal reject or reshape this — architect a synthetic-data and subsetting-plus-masking approach that gives realistic test data with zero compliance exposure, and quantify the trade-offs. | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-your-team-copies-prod-pii-into-a-staging-lake-so-126059) |
| Explain how you'd give data scientists sandbox access to sensitive production data using differential privacy or synthetic data, and where each technique fails to preserve analytic utility. | deep understanding | SDE-2/3, Architect/Principal | Data Security & Access Governance | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-give-data-scientists-sandbox-access-to-sensitive-pro-126634) |
| How do you keep test staging and lower environments compliant when engineers want realistic data — synthetic data masking or subsetting and what are the trade-offs? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-keep-test-staging-and-lower-environments-compliant-when-eng-127373) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect a compliant test-data-management pipeline that produces realistic non-production datasets from PHI/PII without exposing real data — synthetic vs masked vs subsetted, and the fidelity trade-off. | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-compliant-test-data-management-pipeline-that-produces-real-115324) |
| What governance would you build around synthetic data generation so that generated data doesn't inadvertently reproduce or leak real records? | deep understanding | SDE-2/3, Architect/Principal | Data Governance & Stewardship | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-governance-would-you-build-around-synthetic-data-generation-so-th-114823) |
| How would you architect a policy where developers get realistic test data that is provably free of production PII, at the scale of hundreds of teams cloning databases weekly? | deep understanding | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-policy-where-developers-get-realistic-test-d-114097) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What governance controls do you put around synthetic data generation to prevent leakage of the real data it was derived from and to prevent bias amplification? | deep understanding | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-governance-controls-do-you-put-around-synthetic-data-generation-t-71706) |
| How do you decide build-vs-buy for a synthetic-data-generation platform to unblock training on regulated data (buy Gretel/Mostly AI vs build your own generative + differential-privacy pipeline) when the compliance risk of your own de-identification is the crux? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-synthetic-data-generation-platfor-69784) |
| Design governance for synthetic-data generation so synthetic training data provably doesn't leak real individuals (membership-inference resistance) and can be used to unblock GDPR-constrained ML use cases — how do you measure and attest the privacy of the synthetic set? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-governance-for-synthetic-data-generation-so-synthetic-training--69982) |
| How do you evaluate whether synthetic data generation actually protects privacy versus creating a false sense of safety through memorized real records? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-whether-synthetic-data-generation-actually-protect-72577) |
| How would you govern synthetic data generation so teams don't inadvertently leak the very PII the synthetic data was meant to protect? | deep understanding | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-synthetic-data-generation-so-teams-don-t-inadvert-72084) |
| What criteria would push you to invest in a synthetic-data generation pipeline to bootstrap fine-tuning data, and what quality risks must you guard against? | deep understanding | SDE-2/3, Architect/Principal | Foundation Model Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-criteria-would-push-you-to-invest-in-a-synthetic-data-generation--72311) |
| Explain how you'd design the platform's approach to synthetic data and data augmentation pipelines as reusable services, and the governance risks that introduces for downstream models. | deep understanding | SDE-2/3, Architect/Principal | ML Platform Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-the-platform-s-approach-to-synthetic-data-and-72058) |
| How do you quantify the risk of using synthetic or augmented training data, and what controls prevent synthetic-data feedback loops from degrading models? | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-quantify-the-risk-of-using-synthetic-or-augmented-training--71800) |
| Describe how you'd design a synthetic-data generation platform for SFT/preference data at scale while controlling for distillation bias and model collapse. | expertise | SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-design-a-synthetic-data-generation-platform-for-sft-71303) |
| How would you use a chi-square goodness-of-fit test to verify that a synthetic data generator matches the real categorical distribution? | deep understanding | SDE-1/2, SDE-2/3 | Probability & Statistics | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-a-chi-square-goodness-of-fit-test-to-verify-that-a-s-65247) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you govern synthetic-data generation so downstream teams can rely on the synthetic set's fidelity and privacy claims without re-validating them each time? | deep understanding | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-synthetic-data-generation-so-downstream-teams-can-86091) |
| How do you decide build-vs-buy for a synthetic-data-generation pipeline to unblock training/eval on regulated data (buy Gretel/Mostly AI vs build your own generative + differential-privacy pipeline) when the compliance risk of your own de-identification is the crux? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-synthetic-data-generation-pipelin-83772) |
| An auditor asks you to prove your synthetic-data pipeline is actually differentially private end-to-end, not just the final release step. How do you evidence the whole chain? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-auditor-asks-you-to-prove-your-synthetic-data-pipeline-is-actually--87306) |
| An interviewer follow-up: you said synthetic data solves the sharing problem — so how do you bound the synthesizer itself from memorizing and leaking outlier real individuals? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-follow-up-you-said-synthetic-data-solves-the-sharing-pr-87241) |
| How would you architect governance for synthetic data used to fine-tune LLMs, so generation prompts don't inadvertently regurgitate the sensitive source they abstract? | deep understanding | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-governance-for-synthetic-data-used-to-fine-tun-86754) |
| What's your strategy for building eval on differentially-private or synthetic traffic when raw production data can't leave a secure enclave? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-building-eval-on-differentially-private-or-sy-86868) |
| How does the availability of high-quality synthetic data change the build case — can you now justify fine-tuning where labeling cost previously killed it? | deep understanding | SDE-2/3, Architect/Principal | LLM Architecture Selection (Build vs Buy vs Fine-tune) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-the-availability-of-high-quality-synthetic-data-change-the-bu-86281) |
| How do you architect synthetic eval-data generation with an LLM so it scales coverage without baking in the generator's blind spots or contaminating your test set — what's the validation loop? | expertise | SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-synthetic-eval-data-generation-with-an-llm-so-it--84769) |
| How would you design a system that generates and continually refreshes synthetic training data to fine-tune a smaller model from a larger one? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-system-that-generates-and-continually-refreshes-79562) |
