# Decagon

**Tier:** Tier 3  |  **Business domain:** AI  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 4 | 5 | 1 | 5 |
| AI Engineer | 0 | 0 | 5 | 9 | 4 | 9 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for an agent/tool-orchestration framework (buy an agent platform vs build on LangGraph/OpenAI Agents SDK/bespoke) when the differentiator is your tools and business logic, not the orchestration loop? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-agent-tool-orchestration-framewo-69792) |
| A 400 says roles must alternate or the first message must be user. What in your history-reconstruction code (feed rebuild, dropped turns) most often produces this in a serving loop, and how do you defend against it? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-400-says-roles-must-alternate-or-the-first-message-must-be-user-what-64159) |
| How would you write a tool description so the model reliably calls it at the right time in an agentic pipeline? Why is stating when to call it as important as what it does on models that reach for tools conservatively? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-write-a-tool-description-so-the-model-reliably-calls-it--64127) |
| You attach adaptive thinking to a reasoning-heavy extraction feature and p99 latency spikes because the model reasons far more than budgeted. What levers bound reasoning depth without switching models? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-attach-adaptive-thinking-to-a-reasoning-heavy-extraction-feature-a-64102) |
| You use Anthropic Task Budgets to cap tokens for a whole agentic extraction loop distinct from max_tokens. When would you use each, and can you use both in one serving request? | expertise | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-use-anthropic-task-budgets-to-cap-tokens-for-a-whole-agentic-extra-64120) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a progressive-autonomy architecture: an agent starts suggest-only, graduates to auto-execute-with-undo, then full autonomy, gated by measured trust. What signals promote or demote autonomy automatically, and what stops gaming of those signals? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-progressive-autonomy-architecture-an-agent-starts-suggest-onl-83085) |
| For an agentic customer-support system, how do you decide between buying a turnkey agent platform (e.g. an off-the-shelf AI agent suite) versus building agents on your own orchestration when the differentiator is your tool integrations and escalation logic, not the reasoning loop? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-an-agentic-customer-support-system-how-do-you-decide-between-buyin-83732) |
| How do you evaluate whether an agent knows when to stop or escalate to a human, rather than persisting in a failing loop, at production scale? | deep understanding | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-whether-an-agent-knows-when-to-stop-or-escalate-to-86865) |
| On this project, how did you decide when your agent should hand off to a human, and how did you tune that confidence threshold without over-escalating? | deep understanding | SDE-1/2, SDE-2/3 | Projects (Resume Deep-Dive) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=on-this-project-how-did-you-decide-when-your-agent-should-hand-off-to--78667) |
| You want the assistant to ask at most one follow-up per turn and never on clear requests. How do you encode this control flow in the prompt and verify it holds across an eval set? | intermediate experience | SDE-1/2, SDE-2/3 | Prompt Engineering | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-the-assistant-to-ask-at-most-one-follow-up-per-turn-and-never-78094) |
| You want the model to emit a tool call only when a precondition holds, otherwise ask a clarifying question. How do you word the decision boundary in the prompt so it neither over-asks nor calls tools prematurely? | intermediate experience | SDE-1/2, SDE-2/3 | Prompt Engineering | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-the-model-to-emit-a-tool-call-only-when-a-precondition-holds--78007) |
| Your prompt asks the model to output a confidence tier so you can gate on it, but the tiers cluster at 'high'. How do you re-anchor the rubric with explicit criteria per tier so the distribution spreads out usefully? | intermediate experience | SDE-1/2, SDE-2/3 | Prompt Engineering | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-prompt-asks-the-model-to-output-a-confidence-tier-so-you-can-gate-78014) |
| Your uncertainty-based escalation to a human fires too rarely because the model rarely admits doubt. How do you extract a better-calibrated uncertainty signal to drive escalation instead of the model's self-report? | deep understanding | SDE-1/2, SDE-2/3 | Prompt Engineering | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-uncertainty-based-escalation-to-a-human-fires-too-rarely-because--78061) |
| How do you translate a business KPI like 'resolve tickets under $0.12 each' into a per-turn token budget and model-selection policy? | expertise | SDE-2/3, Architect/Principal | Token Budgeting & Throughput Estimation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-translate-a-business-kpi-like-resolve-tickets-under-0-12-ea-86359) |
