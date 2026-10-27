# PolicyBazaar

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 20

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 3 | 11 | 11 | 11 |
| Data Engineer | 0 | 0 | 1 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 2 | 6 | 4 | 6 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You need to support a genuine dynamic filter object from the client mapping to WHERE clauses. Design a query builder that binds values and allowlists fields/operators, and explain how you unit-test it against injection. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-support-a-genuine-dynamic-filter-object-from-the-client-ma-19160) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A principal loop asks how you'd design a 'process manager' (long-running stateful coordinator) versus a stateless saga orchestrator for a multi-day flow (KYC, onboarding); what state does the process manager own, how does it wake on external events, and when do you pick which? | deep understanding | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-loop-asks-how-you-d-design-a-process-manager-long-running--38362) |
| A principal loop: design the class model for 'a policy that must be evaluated identically today and reconstructed for an audit six months later' (regulatory replay); how do you version the policy and pin the inputs so a past decision is bit-reproducible even after the rules changed? | expertise | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-loop-design-the-class-model-for-a-policy-that-must-be-eval-38402) |
| A principal round: design the class model for a 'form engine' where the same declarative schema drives client rendering, client validation, server validation, and DB constraints; how do you keep four layers from drifting and where does the single source of truth live in a fullstack org? | expertise | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-round-design-the-class-model-for-a-form-engine-where-the-s-38369) |
| A principal round: design the org-standard for representing 'quantized decisions' (a scoring/tiering function mapping a continuous input to a discrete band) so product can retune bands as data without a deploy, and the mapping stays monotonic and gap-free by construction. | deep understanding | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-round-design-the-org-standard-for-representing-quantized-d-38355) |
| An interviewer asks how you'd model 'effective dating' (a price/policy that has different values over time and you must query 'what was true on date D') as a first-class org pattern; what does the temporal value object and repository look like, and how do you avoid off-by-one boundary bugs? | deep understanding | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-asks-how-you-d-model-effective-dating-a-price-policy-th-38339) |
| An interviewer challenges your 'shared validation library': one team needs a rule relaxed and forks the whole library; how do you design validation rules as composable, parameterizable units so a team overrides one rule without forking, and the base set stays governed centrally? | deep understanding | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-shared-validation-library-one-team-need-38415) |
| You're deciding how the org models 'a rule that must be explainable' (why was this user denied a loan/rejected at checkout) so the decision object carries its reasoning trace; how do you design the class so explainability is a byproduct of evaluation, not a separate re-run that can diverge? | expertise | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-how-the-org-models-a-rule-that-must-be-explainable-why-38389) |
| You're setting the org standard for how a fullstack team models 'a wizard/multi-step flow' whose steps have server-side validation and can be resumed on another device; where does the source of truth live (client, server-session, or persisted draft) and how do you type each step's precondition? | deep understanding | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-setting-the-org-standard-for-how-a-fullstack-team-models-a-wiza-38378) |
| You need to support a genuine dynamic filter object from the client mapping to WHERE clauses. Design a query builder that binds values and allowlists fields/operators, and explain how you unit-test it against injection. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-support-a-genuine-dynamic-filter-object-from-the-client-ma-19160) |
| You're designing a comment-rendering pipeline that must preserve some formatting, links, and mentions across web, email, and RSS. Where do you sanitize/encode for each surface and how do you avoid a single sanitizer becoming a false sense of safety? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-designing-a-comment-rendering-pipeline-that-must-preserve-some--19155) |
| Your React app safely renders {userInput} but passes user data into style={{ background: `url(${userInput})` }}. Explain why this isn't classic XSS, what injection class it is, and how you'd validate the URL. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-react-app-safely-renders-userinput-but-passes-user-data-into-styl-19203) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you model an insurance policy-claim scenario where a claim's dimensional context evolves through a long lifecycle with reopenings, without losing history? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Data Modeling (Star/Snowflake Schema) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-an-insurance-policy-claim-scenario-where-a-claim-s-121462) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd architect a bitemporal warehouse for a regulated insurance domain where policy state must be reconstructable as-of any valid-time and as-of any transaction-time. What indexing and SCD strategy keeps 'as-known-on' queries tractable at billions of rows? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-architect-a-bitemporal-warehouse-for-a-regulated-ins-112655) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe how you'd calibrate XGBoost output probabilities for a pricing model where the raw scores feed directly into a revenue calculation. | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-calibrate-xgboost-output-probabilities-for-a-pricin-65892) |
| A regulator asks you to demonstrate, for a specific past LLM decision, exactly which model version, prompt, retrieved context, and safety checks produced it. What lineage and reproducibility architecture must have been in place, and where do teams usually fail this? | expertise | SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-regulator-asks-you-to-demonstrate-for-a-specific-past-llm-decision-e-68786) |
| How would you design the org policy for handling knowledge cutoff and freshness across all LLM products, deciding centrally where RAG, tools, or scheduled fine-tunes are mandated, versus leaving it to each team? | deep understanding | SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-org-policy-for-handling-knowledge-cutoff-and--68798) |
| How would you set org guidance on when a feature must keep a human in the loop versus full automation, grounding it in the model's non-determinism and hallucination properties rather than in gut feel, and how do you audit compliance? | expertise | SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-org-guidance-on-when-a-feature-must-keep-a-human-in--68837) |
| How would you set org policy on where classical retrieval and rules must remain authoritative and the LLM only phrases the answer, so that in regulated or high-stakes flows the model can never be the source of a factual decision? | expertise | SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-org-policy-on-where-classical-retrieval-and-rules-mu-68849) |
| How would you evaluate whether a probability output can safely be shown as a percentage to end users? | intermediate experience | SDE-1/2, SDE-2/3 | Model Evaluation Metrics | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-whether-a-probability-output-can-safely-be-show-65821) |
