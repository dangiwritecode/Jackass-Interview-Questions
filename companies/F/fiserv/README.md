# Fiserv

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 4 | 4 | 4 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 1 | 2 | 1 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're the architect for a merger of two payment platforms, each with a ledger making different CAP choices. How do you design the unified ledger's consistency model so historical guarantees on both sides remain valid post-merger? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-the-architect-for-a-merger-of-two-payment-platforms-each-with-a-32237) |
| Compliance-driven: auditors require that every money-moving saga be fully reconstructable and provably all-or-nothing at year-end. How do you architect saga event retention, immutability, and audit trails to satisfy SOX/PCI while keeping the hot path fast? | expertise | SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compliance-driven-auditors-require-that-every-money-moving-saga-be-ful-34128) |
| Design how a saga platform coexists with a legacy batch-settlement system that only reconciles nightly. How do you bridge real-time sagas with an end-of-day batch source of truth without letting the two drift into permanent disagreement? | expertise | SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-a-saga-platform-coexists-with-a-legacy-batch-settlement-sys-34164) |
| Migration at scale: you must move a 15-year-old mainframe-backed ACID settlement engine into event-driven sagas without a single lost or double settlement. Lay out the strangler-fig sequence, the dual-run/shadow strategy, and your go/no-go criteria at each phase. | expertise | SDE-2/3, Architect/Principal | Distributed Transactions & Saga Pattern | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=migration-at-scale-you-must-move-a-15-year-old-mainframe-backed-acid-s-34121) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you build the business case and phasing to strangle a mainframe when each MIPS reduction has real dollar savings but cutover risk is catastrophic? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-the-business-case-and-phasing-to-strangle-a-mainframe-40954) |
| How do you manage debt when two merged companies have overlapping full stacks (two auth systems, two payment stacks, two frontends) and leadership wants 'one platform' in 18 months? Sequence the consolidation. | expertise | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-manage-debt-when-two-merged-companies-have-overlapping-full-41475) |
| How do you manage the debt of a payments/billing subsystem where correctness is legally and financially non-negotiable, so 'refactor and hope the tests catch it' is unacceptable? What's your paydown methodology? | expertise | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-manage-the-debt-of-a-payments-billing-subsystem-where-corre-41488) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the governance interface between engineering and an external QSA/auditor so evidence is self-serve and read-only — the auditor queries a curated attestation API rather than being handed prod access — and what are the risks of exposing that surface? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-governance-interface-between-engineering-and--54070) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're the architect for a CBDC/central-bank-grade payment rail; regulators demand deterministic finality. Explain why this pushes you hard into CP and how you'd communicate the availability floor that finality mathematically imposes. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-the-architect-for-a-cbdc-central-bank-grade-payment-rail-regula-111556) |
| When would you choose format-preserving encryption over tokenization for card PAN in a PCI-plus-GDPR context — what does FPE break in your indexes and joins? | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-format-preserving-encryption-over-tokenization-f-115257) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Walk me through a phased migration from field-level encryption to format-preserving encryption for a 5PB feature store — what breaks and how do you keep training stable? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-a-phased-migration-from-field-level-encryption-to-form-72589) |
| How do you monitor feature importance stability over time and why might a sudden reshuffle be an early warning even when accuracy looks fine? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-monitor-feature-importance-stability-over-time-and-why-migh-65885) |
