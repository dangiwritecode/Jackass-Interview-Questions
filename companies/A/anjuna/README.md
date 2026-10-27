# Anjuna

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 7 | 7 | 7 |
| AIOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Regulators require workloads processing PII to run in a confidential-computing enclave. How would you architect confidential containers (Kata + TEE / Confidential Containers project) on Kubernetes fleet-wide, what attestation flow would you require at admission, and where would you accept the performance and operability cost? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=regulators-require-workloads-processing-pii-to-run-in-a-confidential-c-39020) |
| You are told to adopt confidential computing for the most sensitive workload. Threat-model what a TEE actually protects against versus what remains exposed (side channels, the untrusted host, key provisioning). When is it worth the operational tax? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-told-to-adopt-confidential-computing-for-the-most-sensitive-wo-41245) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must architect a compliance approach for confidential-computing workloads (enclaves TEEs) that process PII/PAN where even your own operators can't see the data — how does this change your audit-evidence model when the trust root shifts to attestation hardware? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-a-compliance-approach-for-confidential-computing-wo-54075) |
| How do you architect confidential-computing / TEE workloads into the platform, and when is the operational and cost overhead actually justified? | expertise | SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-confidential-computing-tee-workloads-into-the-pla-55097) |
| How do you handle the compliance implications of adopting confidential computing / TEEs to reduce your PHI attack surface when the control catalog has no explicit mapping? | expertise | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-compliance-implications-of-adopting-confidential-56797) |
| How do you architect confidential computing (TEEs) into the highest-sensitivity path so it protects against a compromised host and hypervisor, and be honest with me about what it does not protect against and when the operational tax isn't worth it? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-confidential-computing-tees-into-the-highest-sens-53972) |
| How do you architect the trust relationship between your control plane and data plane so that if the control plane is fully compromised, the data plane still refuses to serve customer plaintext, and this separation is enforced by construction not by policy? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-trust-relationship-between-your-control-plane-53968) |
| A board initiative mandates FIPS-validated cryptography for all in-transit data. Architect how the mesh delivers FIPS-compliant mTLS across the fleet, the proxy-build implications (BoringCrypto/FIPS Envoy), and the operational cost of maintaining a compliant proxy. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-board-initiative-mandates-fips-validated-cryptography-for-all-in-tra-52638) |
| Your org runs a mesh and is adopting confidential computing (SEV-SNP/TDX enclaves) for sensitive workloads. Architect how mesh identity and mTLS interact with enclave attestation, and whether the sidecar can live outside the enclave without breaking the trust boundary. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-runs-a-mesh-and-is-adopting-confidential-computing-sev-snp-td-52716) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect governance for confidential-computing observability where telemetry is processed inside TEEs/enclaves so even your operators can't see raw PII in logs — how does shifting the trust root to attestation hardware change your audit-evidence model and what new failure modes appear for AIOps analytics? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-for-confidential-computing-observabili-100319) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you use confidential computing / TEEs (SGX Nitro Enclaves) to keep DEKs and PII off the DBA's reach — what's the residual trust and attestation burden? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-confidential-computing-tees-sgx-nitro-enclaves-to-ke-115263) |
| How would you architect confidential-computing or enclave-backed query processing so that even cloud operators cannot read sensitive columns, and when is the added complexity justified? | expertise | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-confidential-computing-or-enclave-backed-query-114065) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design governance for confidential-computing ML where training runs inside TEEs/enclaves so even your operators can't see the data — how does the shift of trust root to attestation hardware change your audit-evidence model and what new failure modes appear? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-governance-for-confidential-computing-ml-where-training-runs-in-70009) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect confidential inference so even the platform operator cannot read Transformer prompts or KV cache, and what TEE/enclave trade-offs hit attention throughput? | expertise | SDE-2/3, Architect/Principal | Transformers & Attention | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-confidential-inference-so-even-the-platform-opera-84294) |
