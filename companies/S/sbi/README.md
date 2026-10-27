# SBI

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 20

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 2 | 0 | 2 | 2 | 0 | 2 |
| Database Developer | 0 | 0 | 0 | 11 | 11 | 11 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 0 | 0 | 1 | 3 | 3 | 3 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you approach build-vs-buy for a capability that must work identically on-prem (for one regulated customer) and in cloud (for everyone else) — does the deployment-topology constraint force you to build for portability? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-build-vs-buy-for-a-capability-that-must-work-ident-41068) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you build a capacity model for a hybrid workload that must burst from on-prem into cloud (cloud-bursting) only at peak? How do you size the on-prem floor versus the cloud burst, and what makes the burst economics work or fail? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-capacity-model-for-a-hybrid-workload-that-must-b-52982) |
| How do you architect an anti-corruption boundary between a modern services estate and a legacy mainframe system-of-record that can't be retired for years, so mainframe semantics and its batch/latency profile don't leak org-wide? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-anti-corruption-boundary-between-a-modern-serv-51986) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What is a 'transaction' in OLTP and why is it usually all-or-nothing? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-transaction-in-oltp-and-why-is-it-usually-all-or-nothing-118810) |
| What kind of question would you route to OLAP: 'What is customer X's current balance?' or 'What is the average balance across all customers this year?' | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-kind-of-question-would-you-route-to-olap-what-is-customer-x-s-cur-118784) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the retention and rollup strategy for a warehouse where regulators require 7-year retention of granular financial transactions but 99% of queries only touch the last 90 days? Design the tiering so audits over 7-year-old data are possible without paying hot-storage rates continuously. | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-retention-and-rollup-strategy-for-a-warehouse-112710) |
| Describe how you would evaluate portability of stored procedures and vendor-specific logic when planning to keep a future migration option open. | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-would-evaluate-portability-of-stored-procedures-and-v-115426) |
| Describe how you would justify replacing a mature commercial database with an open-source alternative to a risk-averse executive committee. | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-would-justify-replacing-a-mature-commercial-database--115359) |
| Describe how you would run a total-cost-of-migration model that includes retraining, tooling rewrites, and dual-run periods across a vendor switch. | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-would-run-a-total-cost-of-migration-model-that-includ-115405) |
| How do you decide whether to keep a legacy database vendor for a system in maintenance mode versus forcing it into a modernization program? | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-keep-a-legacy-database-vendor-for-a-syste-115406) |
| How do you justify the migration cost and risk of moving off a working commercial database purely to reduce license spend? | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-justify-the-migration-cost-and-risk-of-moving-off-a-working-115395) |
| How would you approach evaluating a database vendor's disaster-recovery RPO and RTO guarantees against your regulatory recovery mandates? | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-evaluating-a-database-vendor-s-disaster-recover-115397) |
| How would you structure a multi-year exit plan from a legacy mainframe database vendor while keeping the business running the entire time? | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-structure-a-multi-year-exit-plan-from-a-legacy-mainframe-115362) |
| What is your strategy for evaluating a database vendor when the primary constraint is data-sovereignty across multiple countries? | expertise | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-strategy-for-evaluating-a-database-vendor-when-the-primar-115436) |
| You inherit a mainframe DB2/IMS core banking system that can't be replaced in under five years. Architect a strangler-fig data-modernization: how do you carve out data capabilities, keep the mainframe authoritative during transition, and manage dual-write consistency between DB2 and the new Postgres services? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherit-a-mainframe-db2-ims-core-banking-system-that-can-t-be-repl-112551) |
| Design the data-residency and sovereignty architecture for a bank that must keep Indian data in India but wants a single global CockroachDB schema; how do RBAC, super regions, and locality enforce compliance? | expertise | SDE-2/3, Architect/Principal | NewSQL (CockroachDB/Spanner) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-data-residency-and-sovereignty-architecture-for-a-bank-that-114517) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An XGBoost model trained with scale_pos_weight now outputs miscalibrated probabilities; how do you reconcile class weighting with calibrated scores? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-xgboost-model-trained-with-scale-pos-weight-now-outputs-miscalibrat-65934) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| For a regulated bank, design the compliance architecture covering explainability of tool decisions, immutable audit trails, model-change approvals, and proving a specific automated action to a regulator years later. What can't the agent be allowed to decide? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-a-regulated-bank-design-the-compliance-architecture-covering-expla-83081) |
| If you had to run an agent fully offline for a regulated bank with no external LLM API, which parts of your tool-calling and routing design change, and what capabilities do you consciously give up? How do you keep the tool layer unchanged? | deep understanding | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=if-you-had-to-run-an-agent-fully-offline-for-a-regulated-bank-with-no--83126) |
| How would you decide whether a hallucination is worth fixing with a verification pass versus tolerating it, given the feature's risk profile? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-a-hallucination-is-worth-fixing-with-a-ve-77962) |
