# Entrust

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 7 | 7 | 7 |
| Database Developer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect governance for the moment a critical vendor (say your tokenization or KMS provider) announces end-of-life or a breach — what's your compliance-preserving exit and failover design so you're never one vendor away from a violation you can't remediate in time? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-for-the-moment-a-critical-vendor-say-y-54088) |
| How do you architect governance to handle the compliance implications of quantum-readiness — post-quantum cryptography migration for long-lived encrypted PII/PAN where 'harvest-now-decrypt-later' means today's ciphertext is a future liability? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-to-handle-the-compliance-implications--54110) |
| How do you architect the governance of secrets and encryption keys so that key custody itself satisfies separation-of-duties — no single admin can both access ciphertext and unwrap the key — at the scale of thousands of per-tenant keys across regions? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-governance-of-secrets-and-encryption-keys-so--54100) |
| Walk me through your encryption-at-rest and in-transit key management architecture such that it satisfies both FIPS 140-3 validation and HIPAA's addressable encryption requirement. | expertise | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-your-encryption-at-rest-and-in-transit-key-management--56737) |
| How do you decide between cloud-KMS auto-unseal and HSM-backed seal for a regulated workload, and what's the recovery and key-custody story you present to a security board for each? | expertise | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-between-cloud-kms-auto-unseal-and-hsm-backed-seal-fo-54943) |
| Your PKI engine is issuing 90-day certs, but a CA compromise scenario forces you to rotate the intermediate. Walk through the org-wide rotation without a mass outage, including CRL/OCSP scaling. | expertise | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-pki-engine-is-issuing-90-day-certs-but-a-ca-compromise-scenario-f-54955) |
| How do you approach quantum-readiness of your signing infrastructure — would you plan a migration to post-quantum signature algorithms in Sigstore/cosign now, and what's the phased strategy? | deep understanding | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-quantum-readiness-of-your-signing-infrastructure-w-55432) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An auditor asks you to prove encryption keys were never accessible to your cloud provider — how do you evidence that with External Key Store / Hold-Your-Own-Key and what's the operational cost? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-auditor-asks-you-to-prove-encryption-keys-were-never-accessible-to--115274) |
| Design HSM integration for a database fleet — network HSM vs cloud HSM vs KMS-backed — and defend your choice on latency availability and FIPS 140-3 posture. | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-hsm-integration-for-a-database-fleet-network-hsm-vs-cloud-hsm-v-115270) |
| How do you decide build-vs-buy for a key-management and data-protection platform across the org — evaluate KMS+Vault vs Thales/Fortanix/Protegrity against your compliance and TCO? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-key-management-and-data-protectio-115317) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect key management (HSM, KMS, envelope encryption, rotation) so that revoking a key effectively renders a class of training data unusable? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-key-management-hsm-kms-envelope-encryption-rotati-72628) |
