# Teladoc

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 4 | 4 | 4 |
| Database Developer | 0 | 0 | 0 | 6 | 6 | 6 |
| AI Engineer | 0 | 0 | 2 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design an event-driven architecture for a healthcare platform where HL7/FHIR clinical events carry PHI, must be auditable, and where a dropped or reordered event can be a patient-safety issue. What guarantees are non-negotiable and how does that constrain your broker choice? | expertise | SDE-2/3, Architect/Principal | Message Queues & Event-Driven Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-event-driven-architecture-for-a-healthcare-platform-where-hl-32663) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect a healthcare-records platform where patient data must be consented-access audited encrypted and shareable across providers — how do you model access grants keep an immutable access log and stay compliant while enabling emergency break-glass access? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-healthcare-records-platform-where-patient-data-must-be-con-39494) |
| How do you migrate a monolith serving a healthcare/regulated workload where every cutover needs a validated change-control artifact — how does that reshape your slice cadence? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-migrate-a-monolith-serving-a-healthcare-regulated-workload--40950) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd instrument the minimum-necessary principle of HIPAA at the query and API layer, not just at storage-level access control. | deep understanding | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-instrument-the-minimum-necessary-principle-of-hipaa--56773) |
| How do you architect a Business Associate Agreement flow-down so that every downstream subprocessor in your platform inherits HIPAA obligations without manual contract tracking? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-business-associate-agreement-flow-down-so-that--56742) |
| How do you design de-identification and safe-harbor pipelines so that data leaving the HIPAA boundary for analytics is provably no longer PHI? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-de-identification-and-safe-harbor-pipelines-so-that--56745) |
| What's your architecture for handling data-residency and sovereignty when a HIPAA workload also has state-level privacy (e.g. CCPA/CPRA) obligations layered on? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-architecture-for-handling-data-residency-and-sovereignty-w-56780) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer asks: why not just encrypt the whole disk and call it a day for HIPAA? Dismantle that reasoning from a threat-model and access-control standpoint. | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-asks-why-not-just-encrypt-the-whole-disk-and-call-it-a--115258) |
| Compare application-layer encryption versus database-native TDE for a HIPAA ePHI store — what threat model does each defeat and where does TDE give you a false sense of security? | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-application-layer-encryption-versus-database-native-tde-for-a--115246) |
| Design a break-glass access procedure for encrypted production PHI during an incident that is HIPAA-auditable and cannot be abused — who holds what and how is it evidenced? | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-break-glass-access-procedure-for-encrypted-production-phi-dur-115262) |
| Design encryption and key management for an edge/IoT healthcare deployment where devices sync ePHI intermittently to a central DB — how do you handle keys on constrained untrusted devices? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-encryption-and-key-management-for-an-edge-iot-healthcare-deploy-115294) |
| How do you architect a Business Associate Agreement-compliant multi-tenant HIPAA database offering — what technical isolation must back the contractual BAA? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-business-associate-agreement-compliant-multi-te-115278) |
| How do you enforce minimum-necessary access (HIPAA) at the row and column level in a shared clinical database — ABAC/RBAC design and how it composes with encryption grants? | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-enforce-minimum-necessary-access-hipaa-at-the-row-and-colum-115331) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you build a guardrail that lets high-stakes financial or medical queries through to a human while still auto-handling the rest? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-a-guardrail-that-lets-high-stakes-financial-or-medica-80780) |
| Your over-refusal rate on legitimate medical queries jumped after a guardrail update — how do you diagnose and fix it without reopening the safety hole? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-over-refusal-rate-on-legitimate-medical-queries-jumped-after-a-gu-80720) |
