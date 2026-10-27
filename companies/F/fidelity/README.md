# Fidelity

**Tier:** Tier 3  |  **Business domain:** Fintech  |  **Questions:** 27

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 5 | 5 | 5 |
| Data Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 1 | 13 | 12 | 13 |
| Data Structures & Algorithms (all profiles) | 4 | 4 | 4 | 4 | 4 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle the tension between GDPR erasure and legal-hold / regulatory-retention obligations that require you to KEEP the same data — architect a system that can both delete on request and preserve under hold without contradiction. | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-tension-between-gdpr-erasure-and-legal-hold-regu-37266) |
| Walk me through architecting for a US financial-services stack under SOX plus PCI plus GLBA — how do you layer these frameworks so controls compose rather than conflict and what's the shared evidence backbone across all three? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-architecting-for-a-us-financial-services-stack-under-s-37261) |
| Walk me through your strategy for making a legacy mainframe/COBOL core banking system GDPR and PCI compliant without rewriting it — what wrapping tokenization masking and access-mediation layers do you add and where does the risk remain? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-your-strategy-for-making-a-legacy-mainframe-cobol-core-37277) |
| Describe a governance model for reserved-capacity commitments across a portfolio of business units with different risk appetites. How do you decide the org-wide commitment coverage ratio and who bears the risk of unused commitments? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-a-governance-model-for-reserved-capacity-commitments-across-a-37058) |
| You want to centralize commitment purchasing so no single team over-commits, but teams complain the central pool 'steals' their savings. Design the internal RI/Savings-Plan sharing and rate-card model that keeps incentives aligned. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-centralize-commitment-purchasing-so-no-single-team-over-co-37020) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A team needs to restore 500TB from Deep Archive by tomorrow for a regulator. Walk me through cost, throughput, and how you'd sequence it under the deadline. | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-team-needs-to-restore-500tb-from-deep-archive-by-tomorrow-for-a-regu-126779) |
| How do you reconcile aggressive cold-tiering with SLA-bound restore latency for compliance queries, litigation holds, or audit requests? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reconcile-aggressive-cold-tiering-with-sla-bound-restore-la-126720) |
| How does S3 Object Lock (governance vs compliance mode) interact with lifecycle transitions and expirations, and how do you design around WORM requirements? | expertise | SDE-2/3, Architect/Principal | Storage Tiering & Lifecycle (Hot/Cold/Glacier) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-s3-object-lock-governance-vs-compliance-mode-interact-with-li-126741) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A regulator requires that during a partition, a specific dataset must NEVER serve a stale value even if that means an outage. Translate that into a testable database configuration and design the pre-audit evidence you'd produce to prove the CP behavior holds. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-regulator-requires-that-during-a-partition-a-specific-dataset-must-n-111570) |
| How do you set RTO/RPO per data class and translate those numbers directly into replication mode and quorum topology, so the DR conversation and the CAP conversation become the same review rather than two disconnected decisions? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-rto-rpo-per-data-class-and-translate-those-numbers-dire-111608) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your drift-monitoring agent calls a 'compute_psi' tool per feature. With 400 features the model issues 400 tool calls. How do you redesign the tool interface to avoid this? | deep understanding | SDE-1/2, SDE-2/3 | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-drift-monitoring-agent-calls-a-compute-psi-tool-per-feature-with--64175) |
| Design a model risk dashboard for the CRO. What signals go on it, at what granularity, and how do you avoid alert fatigue at the executive level? | deep understanding | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-model-risk-dashboard-for-the-cro-what-signals-go-on-it-at-wha-71801) |
| Design a risk-tiering rubric for GenAI use cases spanning internal productivity to customer-facing financial advice. What dimensions drive the tier? | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-risk-tiering-rubric-for-genai-use-cases-spanning-internal-pro-71813) |
| How do you manage model risk during a large-scale migration from legacy statistical models to deep learning across a regulated portfolio? | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-manage-model-risk-during-a-large-scale-migration-from-legac-71808) |
| How would you convince a regulator that your automated validation pipeline is as rigorous as manual expert review for a high-risk model? | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-convince-a-regulator-that-your-automated-validation-pipe-71860) |
| How would you quantify the financial impact of model risk to justify investment in a model risk management program to the board? | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-quantify-the-financial-impact-of-model-risk-to-justify-i-71818) |
| How would you structure model risk reporting differently for a regulator, the board, and engineering leadership, given each needs different granularity? | deep understanding | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-structure-model-risk-reporting-differently-for-a-regulat-71856) |
| Walk me through how you'd extend a classical SR 11-7 model risk framework to cover LLMs and generative systems where behavior is emergent and hard to specify. | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-extend-a-classical-sr-11-7-model-risk-framew-71769) |
| What metrics do you report to a model risk committee, and how do you avoid vanity metrics that mask real exposure? | deep understanding | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-metrics-do-you-report-to-a-model-risk-committee-and-how-do-you-av-71784) |
| Your validation team lacks capacity to review the model backlog. How do you decide which models to validate first and defend that prioritization to a regulator? | deep understanding | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-validation-team-lacks-capacity-to-review-the-model-backlog-how-do-71793) |
| How do you handle retraining when compliance requires model change notifications to customers before behavior shifts (regulated industries)? | expertise | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-retraining-when-compliance-requires-model-change-not-72439) |
| How would you architect audit trails for retraining so every promotion decision, who approved it and on what evidence, is queryable for compliance? | deep understanding | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-audit-trails-for-retraining-so-every-promotion-72463) |
| How would you architect retraining reproducibility so a model trained 18 months ago can be exactly rebuilt for an audit or regulator request? | expertise | SDE-2/3, Architect/Principal | Retraining & Lifecycle Strategy | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-retraining-reproducibility-so-a-model-trained--72377) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Case-Insensitive Alphanumeric Palindrome Check | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Character Classification, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=case-insensitive-alphanumeric-palindrome-check-d125) |
| Detect Whether Two Strings Are Letter Rearrangements | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Hash Table, Sorting, String | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=detect-whether-two-strings-are-letter-rearrangements-d242) |
| Fill Missing Grid Readings with Column Maximums | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Aggregation, Array, Matrix, Traversal | Online Assessment (OA), Phone Screen | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=fill-missing-grid-readings-with-column-maximums-d2780) |
| Index of the First Non-Repeating Character | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Frequency Array, Hash Table, Queue, String | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=index-of-the-first-non-repeating-character-d387) |
