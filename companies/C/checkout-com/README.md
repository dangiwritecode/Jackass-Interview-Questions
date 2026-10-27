# Checkout.com

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 21

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 13 | 13 | 13 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 2 | 2 | 0 | 2 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you quantify a modifiability scenario so it can be measured — 'a new payment method can be added in under two sprints touching no more than three modules' — and what architectural approaches (ports/adapters, plugin) do you probe to satisfy it? | deep understanding | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-quantify-a-modifiability-scenario-so-it-can-be-measured-a-n-36120) |
| How do you architect for the case where your 'partition' is really a dependency on an external SaaS or payment gateway that has its own CAP choices you don't control? Design the boundary so their consistency posture doesn't dictate yours. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-for-the-case-where-your-partition-is-really-a-dep-32257) |
| How does the CAP posture of your platform change what 'idempotency' must mean org-wide? Design the standard so that AP-path retries after a partition, CP-path hard-error retries, and cross-service replays all use one coherent idempotency contract. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-the-cap-posture-of-your-platform-change-what-idempotency-must-32290) |
| You're the architect for a merger of two payment platforms, each with a ledger making different CAP choices. How do you design the unified ledger's consistency model so historical guarantees on both sides remain valid post-merger? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-the-architect-for-a-merger-of-two-payment-platforms-each-with-a-32237) |
| Design a PCI-DSS cardholder-data environment (CDE) so that scope is minimized to the smallest possible surface — how do you use tokenization network segmentation and a payments vault so 90 percent of your services never touch PAN and stay out of audit scope? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-pci-dss-cardholder-data-environment-cde-so-that-scope-is-mini-37218) |
| How do you architect the boundary between a PCI Level-1 payments platform and the rest of the company so an SDE-2 building a feature literally cannot pull a PAN into a non-compliant service — what platform guardrails make the mistake impossible not just discouraged? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-boundary-between-a-pci-level-1-payments-platf-37244) |
| How do you evolve a monolith into a compliance-scoped architecture where regulated workloads (PCI/HIPAA) live in a small hardened enclave and everything else stays fast-moving — what's the strangler-fig sequence and how do you keep the seam from leaking scope? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evolve-a-monolith-into-a-compliance-scoped-architecture-whe-37236) |
| Two teams disagree: platform wants a central tokenization service every payment must call; the payments team wants to keep PAN local for latency. As principal adjudicate the trade-off — what data compliance and performance evidence decides it and how do you land the decision? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=two-teams-disagree-platform-wants-a-central-tokenization-service-every-37258) |
| You are asked to reduce PCI audit scope and cost by 70 percent — as principal what architectural moves (P2PE hosted fields iframe/redirect network tokenization vault outsourcing) get you there and what capability do you give up in exchange? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-reduce-pci-audit-scope-and-cost-by-70-percent-as-prin-37264) |
| A Command handler is not idempotent, so a client retry after a timeout double-charged a customer. Where do you store the idempotency key and cached result, how long do you keep it, and how do you handle concurrent retries hitting simultaneously? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-command-handler-is-not-idempotent-so-a-client-retry-after-a-timeout--22450) |
| Walk me through how you'd define and instrument cost-per-transaction as a first-class SLO for a payments platform doing 5B transactions/month, and how that metric would change the way you make architecture decisions. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-define-and-instrument-cost-per-transaction-a-37015) |
| Design a payment orchestration layer that routes each transaction across multiple PSPs (gateways) based on cost success-rate and BIN — how do you model routing rules and fail over to a secondary PSP mid-transaction without double-charging? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-payment-orchestration-layer-that-routes-each-transaction-acro-28332) |
| How do you architect an idempotency and exactly-once-effects standard that every payments-adjacent service in the company must comply with? What shared library, storage, and audit would you mandate versus leave flexible? | expertise | SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-idempotency-and-exactly-once-effects-standard--31007) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Threat-model a payment-tokenization / vault-boundary design where card data must be isolated from the rest of the app for PCI scope reduction. How do you architect the trust boundary so the main app never touches PAN yet UX stays seamless? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=threat-model-a-payment-tokenization-vault-boundary-design-where-card-d-41251) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a compliance posture that can absorb a same-day emergency change to a control framework (e.g. a new PCI DSS 4.0 requirement becoming mandatory) across hundreds of services without a fire drill each time — what makes controls versionable and hot-swappable? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-compliance-posture-that-can-absorb-a-same-day-e-54030) |
| How do you architect a payment path to stay available and correct when the payment gateway is slow-but-not-erroring, so users don't abandon and you don't create duplicate charges — and how do you decide reconciliation windows and idempotency-key retention at scale? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-payment-path-to-stay-available-and-correct-when-52120) |
| You're asked whether the mesh should own retries for a system with strong exactly-once/idempotency-key semantics vs one without. Architect a fleet-wide retry policy keyed on idempotency guarantees, and how you'd enforce that non-idempotent routes carry zero retries. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-whether-the-mesh-should-own-retries-for-a-system-with-str-52682) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect an idempotency/dedup store that must itself survive partitions, and explain why making IT the AP component while the ledger is CP creates a subtle window where a retry during a partition can still double-apply — and how you close it. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-idempotency-dedup-store-that-must-itself-survi-111583) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you handle a scenario where XGBoost's built-in missing-value handling makes serving fragile because upstream stopped sending nulls and started sending zeros? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-a-scenario-where-xgboost-s-built-in-missing-value-65911) |
| How would you make a FastAPI model endpoint idempotent for a scoring request that a client may retry, so the same input never triggers duplicate downstream side effects like writing a decision to a ledger? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-make-a-fastapi-model-endpoint-idempotent-for-a-scoring-r-62916) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect exactly-once execution for money-moving tools across model retries, worker crashes, provider retries, and network partitions? Include the reconciliation job and what it does when the idempotency store itself is unavailable. | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-exactly-once-execution-for-money-moving-tools-acr-83055) |
