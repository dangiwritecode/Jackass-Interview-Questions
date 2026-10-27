# Smallstep

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 4

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 2 | 4 | 4 | 4 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for an internal PKI + certificate lifecycle automation (cert-manager + private CA vs buy a managed PKI/ACM Private CA) when mTLS everywhere means a cert-rotation failure can black-hole the whole mesh? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-internal-pki-certificate-lifecyc-53752) |
| Explain the resiliency trade-offs of a service mesh's automatic mTLS and cert rotation at fleet scale. How do you keep a cert-authority outage or a mass cert-expiry event from becoming a total-fleet mutual-TLS outage? | expertise | SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-resiliency-trade-offs-of-a-service-mesh-s-automatic-mtls-a-52831) |
| Your organization uses a bastion host that everyone SSHes through with a shared key. Walk me through replacing it with per-user short-lived SSH certificates from a CA, and what you gain in revocation and audit. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-organization-uses-a-bastion-host-that-everyone-sshes-through-with-47914) |
| Your organization wants short-lived certificates everywhere but worries about the CA becoming a bottleneck at high request rates. Explain how issuance caching, intermediate CAs, and per-node agents keep a cert authority from being on the hot path. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-organization-wants-short-lived-certificates-everywhere-but-worrie-47848) |
