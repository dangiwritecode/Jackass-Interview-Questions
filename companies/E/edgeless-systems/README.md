# Edgeless Systems

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 2 | 2 | 2 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Regulators require workloads processing PII to run in a confidential-computing enclave. How would you architect confidential containers (Kata + TEE / Confidential Containers project) on Kubernetes fleet-wide, what attestation flow would you require at admission, and where would you accept the performance and operability cost? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=regulators-require-workloads-processing-pii-to-run-in-a-confidential-c-39020) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must architect a compliance approach for confidential-computing workloads (enclaves TEEs) that process PII/PAN where even your own operators can't see the data — how does this change your audit-evidence model when the trust root shifts to attestation hardware? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-a-compliance-approach-for-confidential-computing-wo-54075) |
| You're establishing how the org runs confidential workloads that must attest before receiving decryption keys. How would you architect the attestation-to-KMS flow with Confidential Containers so a node that fails attestation can never obtain the data key, and what's the operability cost you'd defend? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-establishing-how-the-org-runs-confidential-workloads-that-must--52144) |
| Your org runs a mesh and is adopting confidential computing (SEV-SNP/TDX enclaves) for sensitive workloads. Architect how mesh identity and mTLS interact with enclave attestation, and whether the sidecar can live outside the enclave without breaking the trust boundary. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-runs-a-mesh-and-is-adopting-confidential-computing-sev-snp-td-52716) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design governance for confidential-computing ML where training runs inside TEEs/enclaves so even your operators can't see the data — how does the shift of trust root to attestation hardware change your audit-evidence model and what new failure modes appear? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-governance-for-confidential-computing-ml-where-training-runs-in-70009) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design how the org runs confidential inference for a regulated customer whose prompts must be processed in a TEE. How would you architect confidential containers (Kata + TEE / Confidential Containers) for GPU inference on Kubernetes, what attestation flow would you require at admission, and where would you accept the performance cost? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-the-org-runs-confidential-inference-for-a-regulated-custome-82602) |
| How do you architect confidential inference so even the platform operator cannot read Transformer prompts or KV cache, and what TEE/enclave trade-offs hit attention throughput? | expertise | SDE-2/3, Architect/Principal | Transformers & Attention | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-confidential-inference-so-even-the-platform-opera-84294) |
