# LIC

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 7 | 7 | 7 |
| Database Developer | 0 | 0 | 0 | 5 | 5 | 5 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the gateway's strategy for a hybrid where 20% of traffic is legacy SOAP/XML and 80% is JSON/REST; adjudicate whether protocol translation lives at the gateway forever or you set a sunset for the legacy path, and how you measure whether translation is a bridge or a permanent liability. | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-gateway-s-strategy-for-a-hybrid-where-20-of-traffic-is-lega-39549) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you build a capacity model for a hybrid workload that must burst from on-prem into cloud (cloud-bursting) only at peak? How do you size the on-prem floor versus the cloud burst, and what makes the burst economics work or fail? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-capacity-model-for-a-hybrid-workload-that-must-b-52982) |
| How would you design a chaos program for a hybrid estate where 60% of workloads are still on legacy VMs and mainframe-adjacent systems that cannot tolerate pod-kill semantics? | deep understanding | SDE-2/3, Architect/Principal | Chaos Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-chaos-program-for-a-hybrid-estate-where-60-of-w-55139) |
| Walk me through how you would introduce chaos engineering into a strict change-freeze-heavy enterprise (banking/insurance) where any production experiment needs CAB approval. | deep understanding | SDE-2/3, Architect/Principal | Chaos Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-would-introduce-chaos-engineering-into-a-stric-55170) |
| How do you architect an anti-corruption boundary between a modern services estate and a legacy mainframe system-of-record that can't be retired for years, so mainframe semantics and its batch/latency profile don't leak org-wide? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-anti-corruption-boundary-between-a-modern-serv-51986) |
| Design the org strategy for handling components with no upstream fix (abandonware, EOL libs) that keep appearing in SBOMs — how do you formalize accepted-risk, backporting and replacement roadmaps? | deep understanding | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-org-strategy-for-handling-components-with-no-upstream-fix-a-55478) |
| How do you architect the retention, immutability and legal-hold requirements for transparency-log and attestation data so they survive as admissible audit evidence for a decade? | deep understanding | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-retention-immutability-and-legal-hold-require-55465) |
| How would you handle the org-scale problem of thousands of long-lived legacy artifacts that can never be rebuilt but must carry some trust signal — what compensating controls do you architect? | deep understanding | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-the-org-scale-problem-of-thousands-of-long-lived--55441) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd architect a bitemporal warehouse for a regulated insurance domain where policy state must be reconstructable as-of any valid-time and as-of any transaction-time. What indexing and SCD strategy keeps 'as-known-on' queries tractable at billions of rows? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-architect-a-bitemporal-warehouse-for-a-regulated-ins-112655) |
| How do you evaluate the residual risk and design compensating controls when a legacy system genuinely cannot support least-privilege or modern auth, and must stay in production? | deep understanding | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-the-residual-risk-and-design-compensating-controls-114139) |
| Describe how you would justify replacing a mature commercial database with an open-source alternative to a risk-averse executive committee. | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-would-justify-replacing-a-mature-commercial-database--115359) |
| How do you decide whether to keep a legacy database vendor for a system in maintenance mode versus forcing it into a modernization program? | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-keep-a-legacy-database-vendor-for-a-syste-115406) |
| How would you structure a multi-year exit plan from a legacy mainframe database vendor while keeping the business running the entire time? | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-structure-a-multi-year-exit-plan-from-a-legacy-mainframe-115362) |
