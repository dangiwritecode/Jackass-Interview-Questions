# PayU

**Tier:** Tier 3  |  **Business domain:** Fintech  |  **Questions:** 21

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 13 | 13 | 7 | 13 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 1 | 1 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 1 | 1 | 1 | 1 |
| Data Structures & Algorithms (all profiles) | 2 | 2 | 2 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A dedup service must decide 'have we processed this idempotency key' with a strict TTL; how do you design the key store so expiries are cheap and you never double-execute a payment on retry? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-dedup-service-must-decide-have-we-processed-this-idempotency-key-wit-21974) |
| A payment reconciliation job must match millions of ledger entries to bank statements with fuzzy amount/time keys; how do you structure the matching to avoid O(n*m) and still catch near-matches? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-payment-reconciliation-job-must-match-millions-of-ledger-entries-to--21949) |
| A payment webhook from the PSP arrives before your own synchronous API response has committed the order — how do you design the ordering so the out-of-order webhook doesn't create a phantom or orphaned order? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-payment-webhook-from-the-psp-arrives-before-your-own-synchronous-api-28338) |
| Design a payment orchestration layer that routes each transaction across multiple PSPs (gateways) based on cost success-rate and BIN — how do you model routing rules and fail over to a secondary PSP mid-transaction without double-charging? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-payment-orchestration-layer-that-routes-each-transaction-acro-28332) |
| Design a UPI/wallet payments backend that must hold funds in escrow between debit and credit legs — how do you model the pending state and guarantee no money is lost if the credit leg fails after the debit succeeds? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-upi-wallet-payments-backend-that-must-hold-funds-in-escrow-be-28336) |
| Design refund and partial-refund handling in a payment system where the original charge may have been split across multiple settlements — how do you keep the ledger balanced and prevent refunding more than was captured? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-refund-and-partial-refund-handling-in-a-payment-system-where-th-28335) |
| Your payment capture service must guarantee a card is authorized then captured exactly once even if the auth response is lost on the network — walk through the state machine reconciliation query and timeout handling you'd build. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-payment-capture-service-must-guarantee-a-card-is-authorized-then--28334) |
| Your payments DB has a hot row on the merchant's balance account during peak sale hours causing lock contention — how do you redesign the balance update to remove the hotspot while keeping the running balance queryable? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-payments-db-has-a-hot-row-on-the-merchant-s-balance-account-durin-28340) |
| How would you design an endpoint for a checkout that must complete a payment authorization within 3 seconds or fail cleanly, coordinating a downstream call with a strict deadline and propagating that deadline downstream? | expertise | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-endpoint-for-a-checkout-that-must-complete-a-p-23961) |
| You must guarantee at-most-once processing for a webhook that triggers money movement. Walk through dedupe storage, the race between two concurrent deliveries of the same event, and what you persist transactionally. | expertise | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-guarantee-at-most-once-processing-for-a-webhook-that-triggers-23941) |
| Your API must support 'test mode' and 'live mode' like a payments provider. How do you isolate data, keys, and side effects between modes while sharing one codebase and endpoint surface? | deep understanding | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-api-must-support-test-mode-and-live-mode-like-a-payments-provider-24012) |
| Your REST service must call a third-party API that has no idempotency support and occasionally times out after actually succeeding. How do you build a reconciliation loop to detect and heal these ambiguous outcomes? | expertise | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-rest-service-must-call-a-third-party-api-that-has-no-idempotency--23988) |
| How does using an idempotency key on a payment endpoint help you scale safely with retries? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-using-an-idempotency-key-on-a-payment-endpoint-help-you-scale-13086) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A regulator requires that your CDN/edge cannot read customer PII in transit even though it terminates TLS. Design the architecture: field-level encryption, edge-to-origin re-encryption, or tokenization? Defend the choice against latency and key-management cost. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-regulator-requires-that-your-cdn-edge-cannot-read-customer-pii-in-tr-41234) |
| Threat-model a payment-tokenization / vault-boundary design where card data must be isolated from the rest of the app for PCI scope reduction. How do you architect the trust boundary so the main app never touches PAN yet UX stays seamless? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=threat-model-a-payment-tokenization-vault-boundary-design-where-card-d-41251) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a payment path to stay available and correct when the payment gateway is slow-but-not-erroring, so users don't abandon and you don't create duplicate charges — and how do you decide reconciliation windows and idempotency-key retention at scale? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-payment-path-to-stay-available-and-correct-when-52120) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your BigQuery estate mixes on-demand per-TB-scanned pricing with flat-rate slot reservations, and neither model is obviously cheaper as workloads shift. Walk me through the slot-utilization and query-volatility analysis that decides how many slots to commit and how much to leave on on-demand, plus the regret risk of over-committing. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-bigquery-estate-mixes-on-demand-per-tb-scanned-pricing-with-flat--125921) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must guarantee idempotent processing of a payment webhook. How do isolation level plus a unique constraint together give you exactly-once effect? | deep understanding | SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-guarantee-idempotent-processing-of-a-payment-webhook-how-do-i-110272) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you decide whether a failure is a tokenization problem, a context-window problem, or a prompt problem when a model mishandles a long product SKU string? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-a-failure-is-a-tokenization-problem-a-con-77910) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Count Repeated Subtractions Until One Value Hits Zero | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Euclidean Algorithm, Greatest Common Divisor, Math, Number Theory, Simulation | Online Assessment (OA), Phone Screen | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-repeated-subtractions-until-one-value-hits-zero-d2046) |
| Longest Uniform Block After Limited Repaints | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Hash Table, Sliding Window, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-uniform-block-after-limited-repaints-d424) |
