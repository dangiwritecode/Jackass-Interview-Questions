# LiteLLM/BerriAI

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 5

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 3 | 3 | 3 | 3 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a multi-provider LLM-inference fallback and capacity strategy so that when your primary model endpoint is rate-limited or degraded, traffic degrades to a smaller/cheaper model or a queue, without a jarring quality cliff and without unbounded per-token cost? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-multi-provider-llm-inference-fallback-and-ca-52105) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd build a fallback chain across two providers so a refusal or 5xx transparently retries elsewhere without duplicating side effects. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-build-a-fallback-chain-across-two-providers-so-a-ref-63856) |
| Explain how you'd normalize responses across providers so callers don't couple to one provider's usage/stop-reason/tool-call shape. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-normalize-responses-across-providers-so-callers-don--63858) |
| What is an LLM gateway/proxy (e.g. LiteLLM, Portkey) and what cross-cutting concerns does it centralize versus calling providers directly? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-an-llm-gateway-proxy-e-g-litellm-portkey-and-what-cross-cuttin-63857) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a multi-model router that trades quality against attention/serving cost per request, and prove to leadership the cascade never regresses the p99 worst-case answer? | expertise | SDE-2/3, Architect/Principal | Transformers & Attention | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-multi-model-router-that-trades-quality-again-84245) |
