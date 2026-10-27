# SPIRL

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 5

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 5 | 5 | 5 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the identity story for a hybrid estate where some workloads can be attested by hardware TPM, some by cloud instance identity, and some not at all? Define your tiered-assurance model and how policy consumes the assurance level. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-identity-story-for-a-hybrid-estate-where-some-53950) |
| How do you decide the granularity of your workload identity: one identity per service, per version, per replica, or per request? Tie the choice explicitly to revocation speed, attestation cost, and blast radius, and defend where you'd stop. | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-granularity-of-your-workload-identity-one-identi-53958) |
| Walk me through architecting attestation so a workload only receives an identity if it can prove it is running expected code on expected hardware. What does this buy you against a pod-spoofing attacker, and what is the operational cost at 100k workloads? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-architecting-attestation-so-a-workload-only-receives-a-53991) |
| You are choosing the org-wide standard for how services prove identity: SPIFFE SVIDs, cloud IAM roles, or a shared internal JWT issuer, across a hybrid multi-cloud estate. Compare them at scale and defend the one you'd mandate and the migration path off the others. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-choosing-the-org-wide-standard-for-how-services-prove-identity-54001) |
| You must choose a trust-domain architecture: one org-wide SPIFFE trust domain vs per-business-unit trust domains with federation. Walk through the blast-radius, delegation, and M&A-flexibility trade-offs, and defend the model you'd commit to for a decade. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-choose-a-trust-domain-architecture-one-org-wide-spiffe-trust--52630) |
