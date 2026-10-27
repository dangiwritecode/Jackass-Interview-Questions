# Proton

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect data-minimization enforcement at collection time so services physically cannot collect fields they don't have a declared lawful basis for — describe schema governance a privacy-linter in CI and runtime rejection of over-collection. | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-data-minimization-enforcement-at-collection-ti-37253) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You are asked whether client-side encryption (E2E) is worth it for a product feature. Threat-model what it protects against, what it makes impossible (search, server-side processing, sharing), and where you'd draw the architectural line. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-whether-client-side-encryption-e2e-is-worth-it-for-a-pro-41301) |
| You must design so that even your own platform SREs cannot read customer plaintext, yet can operate and debug the system. Walk me through the operator-access architecture: encryption boundaries, ephemeral scoped access, and dual-control for the exceptions. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-so-that-even-your-own-platform-sres-cannot-read-custom-41271) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design encryption-as-a-service using Vault transit for 100 apps needing envelope encryption, with key rotation, keyring versioning, and a path to crypto-agility if an algorithm is deprecated. Where's the throughput ceiling? | expertise | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-encryption-as-a-service-using-vault-transit-for-100-apps-needin-54957) |
| How would you evaluate and plan for post-quantum readiness in your Vault-based crypto (transit, PKI)? What's your crypto-agility architecture so you can swap algorithms without re-encrypting the world overnight? | expertise | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-and-plan-for-post-quantum-readiness-in-your-vau-54990) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect a per-user encryption key model for a consumer app so that GDPR erasure = destroy one user's key — how do you handle shared/derived data that references multiple users? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-per-user-encryption-key-model-for-a-consumer-app-so-that-g-115290) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide whether an ML use case even needs PII at all, and enforce data minimization as an architectural default rather than an afterthought? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-an-ml-use-case-even-needs-pii-at-all-and-enf-72651) |
| Walk me through how you'd handle a court order / lawful-access request for training data or model outputs while respecting other users' privacy. | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-handle-a-court-order-lawful-access-request-f-72649) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you govern the tension between wanting rich audit logs and the fact that those logs may themselves contain the sensitive prompts and outputs you're liable for? | expertise | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-govern-the-tension-between-wanting-rich-audit-logs-and-the--86042) |
