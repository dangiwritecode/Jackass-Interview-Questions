# Brex

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 22

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 3 | 2 | 3 |
| Fullstack | 0 | 0 | 0 | 4 | 4 | 4 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 2 | 4 | 2 | 4 |
| AI Engineer | 0 | 0 | 2 | 9 | 9 | 9 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design authorization for a 'workflow approval' system where step 3 can only be done by someone who did NOT do step 2 (separation of duties)? Where do you store and enforce this history? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-authorization-for-a-workflow-approval-system-wher-26182) |
| Explain how idempotency keys interact with retries and timeouts. What happens when the client times out but the server actually succeeded? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-idempotency-keys-interact-with-retries-and-timeouts-what-h-29889) |
| How would you design a schema and query to enforce hierarchical spending limits (org > department > team > user) checked atomically on every transaction? | deep understanding | SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-schema-and-query-to-enforce-hierarchical-spendi-24388) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe a time you had to lead the org in balancing the desire for a beautiful, correct architecture against the reality that the business needed to validate the idea cheaply first. How did you decide how much to build? | deep understanding | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-a-time-you-had-to-lead-the-org-in-balancing-the-desire-for-a--40495) |
| Tell me about a time you had to make a call on how much to formalize architecture ownership across an org that had grown from a startup with no titles. How did you introduce structure without alienating the founding engineers? | deep understanding | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=tell-me-about-a-time-you-had-to-make-a-call-on-how-much-to-formalize-a-40458) |
| Tell me about a time you had to persuade the org to invest in a capability whose value would only be visible three or four leadership changes from now. How did you make it survive a change of sponsor? | deep understanding | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=tell-me-about-a-time-you-had-to-persuade-the-org-to-invest-in-a-capabi-40428) |
| Architect a document-processing pipeline that OCRs classifies and extracts structured data from millions of uploaded PDFs/images with an LLM step — how do you handle the async long-running jobs cost control and human-in-the-loop correction at scale? | deep understanding | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-document-processing-pipeline-that-ocrs-classifies-and-extr-39497) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer probes your migration plan: you propose moving 300 services behind a data-access broker over 3 years — what is the risk that the broker becomes an ossified chokepoint that no one can evolve, and how do you architect for its own eventual replacement? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-your-migration-plan-you-propose-moving-300-servi-54053) |
| You're asked to build a compliance program that a Series-B startup can grow into without re-platforming at Series-D — what minimal governance primitives do you architect on day one so that scaling from 50 to 2000 engineers doesn't force a rip-and-replace of the control plane? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-build-a-compliance-program-that-a-series-b-startup-can-54067) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a document-AI/IDP pipeline (buy Textract/Document AI/Azure DI vs build on open OCR + your own layout models) when accuracy on your domain forms and per-page pricing at millions of docs define the crossover? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-document-ai-idp-pipeline-buy-text-69803) |
| How would you design an offline/online consistency test that runs on every XGBoost deploy to catch scoring divergence early? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-offline-online-consistency-test-that-runs-on-e-65923) |
| How would you implement canary rollout of a new model version in FastAPI where 5% of traffic is scored by the candidate and you auto-roll-back on a live-accuracy or latency regression? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-canary-rollout-of-a-new-model-version-in-fasta-62893) |
| Design a model risk framework that accommodates rapid experimentation velocity for a startup while still passing a future SOC2/regulatory audit. | expertise | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-model-risk-framework-that-accommodates-rapid-experimentation--71825) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect an agent 'capability tier' model where an agent earns access to riskier tools (money, deletes, prod mutations) by accumulating measured reliability, and how does demotion work when reliability regresses? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-an-agent-capability-tier-model-where-an-agent--83035) |
| How would you build a continuous eval that catches a silent quality regression introduced by a provider's model update you didn't control? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-continuous-eval-that-catches-a-silent-quality-re-86853) |
| How would you decide the boundary between what an agent does autonomously versus what it drafts for human approval in a financial-operations workflow, and defend encoding that boundary as a risk-scored policy rather than a static allow-list? | expertise | SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-the-boundary-between-what-an-agent-does-autonomou-83179) |
| Your extraction feature worked on the old model but degraded after a silent provider update. Walk through isolating whether the tokenizer, alignment, or default sampling changed. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-extraction-feature-worked-on-the-old-model-but-degraded-after-a-s-77915) |
| Your feature must extract a bounded numeric field the JSON schema can't constrain to a range. Explain where schema enforcement ends and your validation must begin. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-feature-must-extract-a-bounded-numeric-field-the-json-schema-can--77958) |
| How do you measure the true blended cost per request with caching, accounting for write premiums, read discounts, and miss penalties? | deep understanding | SDE-2/3, Architect/Principal | Prompt Caching Strategy | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-measure-the-true-blended-cost-per-request-with-caching-acco-86544) |
| How would you design a chargeback model that fairly attributes cache-write costs to the team that populated the shared prefix? | expertise | SDE-2/3, Architect/Principal | Prompt Caching Strategy | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-chargeback-model-that-fairly-attributes-cache-w-86595) |
| How would you set a cache-effectiveness SLI and wire it into your FinOps dashboards for LLM spend? | deep understanding | SDE-2/3, Architect/Principal | Prompt Caching Strategy | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-a-cache-effectiveness-sli-and-wire-it-into-your-fino-86557) |
| Walk me through a cost model that shows the break-even reuse count above which enabling caching pays for its write premium. | deep understanding | SDE-2/3, Architect/Principal | Prompt Caching Strategy | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-a-cost-model-that-shows-the-break-even-reuse-count-abo-86574) |
