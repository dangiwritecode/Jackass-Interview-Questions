# Inngest

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 7 | 0 | 11 | 13 | 12 | 13 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a background job trigger from a Server Action (e.g. send email, resize image) that doesn't block the response and survives the serverless function ending. | deep understanding | SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-background-job-trigger-from-a-server-action-e-g-send-email-re-17225) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe how you'd checkpoint and resume a long-running agent so an infra restart doesn't force it to redo expensive completed steps. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Agentic Workflows | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-checkpoint-and-resume-a-long-running-agent-so-an-in-80517) |
| Your agent needs to coordinate with a human across hours (waiting for approvals). How do you architect durable, event-driven pausing and resumption? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Agentic Workflows | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-agent-needs-to-coordinate-with-a-human-across-hours-waiting-for-a-80571) |
| You picked a durable workflow engine for agent orchestration. What did you give up in latency and operational complexity, when would you regret it, and how do you keep interactive agents fast on top of it? | deep understanding | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-picked-a-durable-workflow-engine-for-agent-orchestration-what-did--83124) |
| When your agentic workflow needs durable, resumable long-running execution with retries and human-in-the-loop pauses, how do you decide between buying a managed agent-runtime and building on a workflow engine like Temporal — where does execution-substrate control tip it? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-your-agentic-workflow-needs-durable-resumable-long-running-execut-83742) |
| How would you make sure your embedding job that failed halfway does not double-charge you when you rerun it? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-make-sure-your-embedding-job-that-failed-halfway-does-no-76570) |
| How would you run a nightly job in the cloud to refresh your vector index without keeping a server on all day? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-run-a-nightly-job-in-the-cloud-to-refresh-your-vector-in-76533) |
| How would you use a queue and workers to process a large batch of documents for embedding without timing out an HTTP request? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-a-queue-and-workers-to-process-a-large-batch-of-docu-76557) |
| What is a dead-letter queue and when would a document that repeatedly fails embedding land in one? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-dead-letter-queue-and-when-would-a-document-that-repeatedly--76558) |
| What is idempotency and why does it matter if a client retries a request that already triggered an expensive LLM call? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-idempotency-and-why-does-it-matter-if-a-client-retries-a-reque-76521) |
| What is the difference between synchronous and asynchronous handling when an LLM call might take ten seconds to respond? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-difference-between-synchronous-and-asynchronous-handling-w-76498) |
| Why might you put a message queue between your web app and a slow LLM-processing worker in the cloud? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-you-put-a-message-queue-between-your-web-app-and-a-slow-llm--76497) |
| Your agent framework must resume a long trajectory from where it crashed; what append-only log plus checkpoint structure lets you replay to the last consistent step without re-running expensive tool calls? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-agent-framework-must-resume-a-long-trajectory-from-where-it-crash-76745) |
| How would you design the boundary so an agent's intermediate state persists between tool calls, letting it resume after a worker crash mid-workflow? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-boundary-so-an-agent-s-intermediate-state-per-78468) |
