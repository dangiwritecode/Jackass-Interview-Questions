# Very Good Security

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 4 | 4 | 4 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 2 | 3 | 1 | 3 |
| AI Engineer | 0 | 0 | 1 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're asked to add 'field-level encryption' for PII so even authenticated employees only see decrypted values if authorized. Where do the keys live, and how do authorization and decryption interact per request? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-add-field-level-encryption-for-pii-so-even-authenticat-26219) |
| Architect a PII tokenization/vault service that serves 500k tokenize/detokenize ops per second across regions — how do you meet latency SLOs while keeping the token vault as the only PCI/PII-in-scope component and surviving its failure? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-pii-tokenization-vault-service-that-serves-500k-tokenize-d-37223) |
| Design how tokenization interacts with analytics and joins — if PAN and PII are tokenized how do downstream systems still join and aggregate on those identities (deterministic vs format-preserving tokens) without re-introducing the raw value into scope? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-tokenization-interacts-with-analytics-and-joins-if-pan-and--37305) |
| What breaks at 100x in a centralized tokenization vault — throughput ceiling detokenization latency the blast radius of a vault outage or the key-management scaling? Redesign the vault topology (regional shards caching HSM fleet) to hold your SLOs at scale. | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-breaks-at-100x-in-a-centralized-tokenization-vault-throughput-cei-37296) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer probes: your design assumes you can enumerate all PII, but a free-text field or an uploaded document may contain anything. How do you architect governance for unstructured and user-generated content where you can't schema-enforce classification? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-your-design-assumes-you-can-enumerate-all-pii-bu-54081) |
| How do you architect governance for the moment a critical vendor (say your tokenization or KMS provider) announces end-of-life or a breach — what's your compliance-preserving exit and failover design so you're never one vendor away from a violation you can't remediate in time? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-for-the-moment-a-critical-vendor-say-y-54088) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your strategy for tokenization vault scaling and availability when every online feature lookup needs a detokenization call in the critical inference path? | expertise | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-tokenization-vault-scaling-and-availability-w-72599) |
| You must never store PII in prompts because it persists in event history and compaction summaries. How do you architect a labeling pipeline that needs sensitive fields without durably persisting them? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-never-store-pii-in-prompts-because-it-persists-in-event-histo-64137) |
| You must redact PII from prompts before they reach the provider but redaction is imperfect. How do you layer detection, tokenized placeholders, and re-hydration so the model still produces useful output? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-redact-pii-from-prompts-before-they-reach-the-provider-but-re-64160) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect PII redaction in the LLM request/response path on AWS so no customer identifier lands in prompt logs the vector store or a fine-tuning dataset — where does detection happen and what's the trade-off between redacting pre-model and post-model? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-pii-redaction-in-the-llm-request-response-path-on-82653) |
| A user's prompt may contain PII that flows into your traces. Compare redacting it in the app SDK (before the span is created) versus in the OTel Collector for an LLM pipeline. What does each protect against and miss? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-user-s-prompt-may-contain-pii-that-flows-into-your-traces-compare-re-78829) |
