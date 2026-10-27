# Inflection

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 4 | 4 | 4 | 4 |
| AI Engineer | 0 | 0 | 3 | 9 | 8 | 9 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you would evaluate a post-trained model on multi-turn dialogue coherence rather than single-turn quality. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-evaluate-a-post-trained-model-on-multi-turn-dial-68163) |
| Your DPO model's win rate improves on the judge LLM but users complain quality dropped — how do you reconcile the eval and reality? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-dpo-model-s-win-rate-improves-on-the-judge-llm-but-users-complain-68112) |
| Your model after RLHF becomes overly cautious and refuses benign requests — how do you diagnose over-refusal and rebalance it? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-model-after-rlhf-becomes-overly-cautious-and-refuses-benign-reque-68098) |
| Your reward model gives high scores to long, verbose answers regardless of quality — how do you detect and correct this length bias? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-reward-model-gives-high-scores-to-long-verbose-answers-regardless-68077) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A frontier model upgrade improves reasoning but changes tool-call behavior and doubles per-token cost. Walk a bar-raiser through your adopt/defer decision and the org-wide rollout that won't silently break 200 tools. | deep understanding | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-frontier-model-upgrade-improves-reasoning-but-changes-tool-call-beha-83047) |
| How would you govern the retention and deletion of conversational memory in a long-running agent so personal data doesn't accumulate indefinitely? | deep understanding | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-the-retention-and-deletion-of-conversational-memo-86766) |
| You have a fixed embedding budget per user session in a chat agent. How would you decide between embedding every turn versus embedding a rolling summary? | intermediate experience | SDE-1/2, SDE-2/3 | Embeddings & Vector Search | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-have-a-fixed-embedding-budget-per-user-session-in-a-chat-agent-how-78508) |
| How would you design an eval program that measures whether safety guardrails are over-refusing benign requests, not just under-blocking harmful ones? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-eval-program-that-measures-whether-safety-guar-86856) |
| How would you design an eval to measure a model's refusal-versus-answer boundary consistency so it doesn't refuse the same request it answered yesterday? | deep understanding | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-eval-to-measure-a-model-s-refusal-versus-answe-86871) |
| What's your approach to evaluating a model's steerability — that it reliably follows a persona or format instruction — separately from its raw task quality? | deep understanding | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-evaluating-a-model-s-steerability-that-it-reli-86910) |
| Explain the difference between the model 'attending' to a token and that token 'influencing' the output, and why this matters when debugging why an instruction was ignored. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-the-model-attending-to-a-token-and-that-77912) |
| Explain why a chat model 'forgets' context in a way that is really a context-window eviction, and how you'd distinguish it from a genuine reasoning failure. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-why-a-chat-model-forgets-context-in-a-way-that-is-really-a-con-77936) |
| As principal you must decide whether the agent's episodic memory is compacted (summarized then re-embedded) over time to control index growth. What's lost when you compact memory into summary vectors, and how do you make the trade-off tunable per agent? | expertise | SDE-2/3, Architect/Principal | Vector Databases (Pinecone/pgvector) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=as-principal-you-must-decide-whether-the-agent-s-episodic-memory-is-co-82485) |
