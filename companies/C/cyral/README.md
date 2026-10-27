# Cyral

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 5 | 5 | 5 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect a data-access broker/proxy that sits in front of all PII stores providing centralized authz masking purpose-checking and audit — what are the failure modes of routing all sensitive reads through one plane and how do you keep it from being a SPOF or latency tax? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-data-access-broker-proxy-that-sits-in-front-of-all-pii-sto-37257) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Contrast row-level/column-level access control enforced in the warehouse, in a policy engine (OPA/Immuta), and in the semantic layer for a 30-domain enterprise. Where does centralizing data-access policy help audit and consistency, and where does it add query latency and a critical single dependency? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-row-level-column-level-access-control-enforced-in-the-warehou-125636) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer probes: an engineer ran a mysqldump of a 2M-row PII table to a laptop. Lead the retro — what database egress controls (query-result-size limits export gating data-access broker JIT access) would have made it impossible, prioritized against DBA velocity and cost? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-an-engineer-ran-a-mysqldump-of-a-2m-row-pii-tabl-113073) |
| An interviewer probes: two teams disagree — platform wants every PII read to go through a central masking proxy, the latency-sensitive team wants native RLS local to their Postgres. As principal adjudicate the trade-off — what data compliance and performance evidence decides it and how do you land the decision? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-two-teams-disagree-platform-wants-every-pii-read-113107) |
| Design a build-vs-buy decision for a database-security-and-governance platform (Immuta/Cyral/Privacera) versus native RDBMS RLS+masking plus a home-grown proxy at a 2000-engineer org — make the architectural and economic case either way and describe the integration seams. | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-build-vs-buy-decision-for-a-database-security-and-governance--113085) |
| Design a database-access broker/proxy that fronts all PII stores providing centralized authz masking purpose-checking and query audit — what are the failure modes of routing every sensitive read through one plane and how do you keep it from being a SPOF or a latency tax? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-database-access-broker-proxy-that-fronts-all-pii-stores-provi-113071) |
| Defend a build-vs-buy decision for a centralized data-access proxy that mediates all production queries versus embedding controls in every datastore. What tips you either way at scale? | expertise | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=defend-a-build-vs-buy-decision-for-a-centralized-data-access-proxy-tha-114047) |
