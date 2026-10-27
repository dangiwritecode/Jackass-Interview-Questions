# Worldpay

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 6 | 6 | 6 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're the architect for a merger of two payment platforms, each with a ledger making different CAP choices. How do you design the unified ledger's consistency model so historical guarantees on both sides remain valid post-merger? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-the-architect-for-a-merger-of-two-payment-platforms-each-with-a-32237) |
| Design a PCI-DSS cardholder-data environment (CDE) so that scope is minimized to the smallest possible surface — how do you use tokenization network segmentation and a payments vault so 90 percent of your services never touch PAN and stay out of audit scope? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-pci-dss-cardholder-data-environment-cde-so-that-scope-is-mini-37218) |
| How do you architect the boundary between a PCI Level-1 payments platform and the rest of the company so an SDE-2 building a feature literally cannot pull a PAN into a non-compliant service — what platform guardrails make the mistake impossible not just discouraged? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-boundary-between-a-pci-level-1-payments-platf-37244) |
| You are asked to reduce PCI audit scope and cost by 70 percent — as principal what architectural moves (P2PE hosted fields iframe/redirect network tokenization vault outsourcing) get you there and what capability do you give up in exchange? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-reduce-pci-audit-scope-and-cost-by-70-percent-as-prin-37264) |
| Design the reconciliation subsystem for a payments platform that matches internal ledger entries against daily PSP settlement files — how do you detect missing captured-but-not-settled and settled-but-not-recorded transactions and drive them to resolution? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-reconciliation-subsystem-for-a-payments-platform-that-match-28333) |
| Compliance requires that PCI-scoped code be isolated from the rest of the app. Argue how a modular monolith versus service extraction each satisfies (or fails) auditor expectations, and what you'd recommend. | expertise | SDE-2/3, Architect/Principal | Monolith vs Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compliance-requires-that-pci-scoped-code-be-isolated-from-the-rest-of--31714) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you strangle a monolith that must remain PCI-DSS compliant throughout, where the seam itself now touches cardholder data — does the facade fall in scope? | expertise | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-strangle-a-monolith-that-must-remain-pci-dss-compliant-t-40951) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the governance interface between engineering and an external QSA/auditor so evidence is self-serve and read-only — the auditor queries a curated attestation API rather than being handed prod access — and what are the risks of exposing that surface? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-governance-interface-between-engineering-and--54070) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a tokenization strategy for a lakehouse so PAN and PII are tokenized before landing yet analysts can still join and aggregate on customer identity — deterministic vs format-preserving tokens — without re-introducing the raw value into PCI scope anywhere in the pipeline. | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-tokenization-strategy-for-a-lakehouse-so-pan-and-pii-are-toke-126028) |
| Design the architecture to scope which pipelines and data stores are actually in PCI scope in a data platform that touches payment events — what tokenization network segmentation and derived-signal design shrinks the cardholder-data environment to the smallest possible surface? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-to-scope-which-pipelines-and-data-stores-are-a-126067) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| When would you choose format-preserving encryption over tokenization for card PAN in a PCI-plus-GDPR context — what does FPE break in your indexes and joins? | deep understanding | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-format-preserving-encryption-over-tokenization-f-115257) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you monitor feature importance stability over time and why might a sudden reshuffle be an early warning even when accuracy looks fine? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-monitor-feature-importance-stability-over-time-and-why-migh-65885) |
