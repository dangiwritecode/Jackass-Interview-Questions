# Camunda

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 20

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 5 | 9 | 7 | 10 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 1 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A Saga compensation ran twice on retry and refunded a customer twice. How do you make saga steps and their compensations idempotent, and where do you store the per-step completion markers so a crash mid-compensation is recoverable? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-saga-compensation-ran-twice-on-retry-and-refunded-a-customer-twice-h-22469) |
| You must choose between State-pattern classes and a typed/config-driven state-machine library for a workflow that grows steps monthly. What signals push you from one to the other, and how do you migrate a live workflow without dropping in-flight instances? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-choose-between-state-pattern-classes-and-a-typed-config-drive-22456) |
| A senior engineer proposes putting all cross-team communication through a single 'god' orchestration service to 'centralize business logic.' As principal, dismantle or defend this. What's the failure mode at scale, and what's the legitimate kernel of their concern? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-senior-engineer-proposes-putting-all-cross-team-communication-throug-36398) |
| Contrast a message-broker-centric integration (Kafka/Pulsar/RabbitMQ) with a durable-execution/workflow-centric integration (Temporal/Step Functions) as the enterprise backbone. For which classes of enterprise process is each the right spine, and what breaks if you pick wrong? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-a-message-broker-centric-integration-kafka-pulsar-rabbitmq-wi-36374) |
| Design the pattern for handling long-running human-in-the-loop business processes (approvals that take days) in an event-driven enterprise. How do you model wait states, timeouts, and escalations without holding threads/connections open, and where does a workflow engine belong? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-pattern-for-handling-long-running-human-in-the-loop-busines-36362) |
| Explain the trade-offs between orchestration (a central saga coordinator) and choreography (event-driven, no coordinator) for a multi-step cross-department business process spanning 6 systems. How do you keep observability and error recovery sane in the choreographed version? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-trade-offs-between-orchestration-a-central-saga-coordinato-36318) |
| You're modeling a workflow engine where steps form a DAG with conditional branches and retries; how do you represent the graph and execution state so a resumed run continues from the exact failed node? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-modeling-a-workflow-engine-where-steps-form-a-dag-with-conditio-22374) |
| How would you model a workflow engine where each step is an object and steps can be composed dynamically? | deep understanding | Fresher, SDE-1 | OOPS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-workflow-engine-where-each-step-is-an-object-and-8771) |
| On this project, how did you handle a compensating action when the second step of a multi-step operation failed after the first succeeded? | deep understanding | SDE-1/2, SDE-2/3 | Projects (Resume Deep-Dive) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=on-this-project-how-did-you-handle-a-compensating-action-when-the-seco-28265) |
| On this project, walk me through a distributed transaction across two systems and whether you used a saga, two-phase commit, or accepted eventual consistency. | expertise | SDE-1/2, SDE-2/3 | Projects (Resume Deep-Dive) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=on-this-project-walk-me-through-a-distributed-transaction-across-two-s-28264) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you would evaluate, via ATAM, whether to move a synchronous saga to an orchestrated workflow engine versus a choreographed event chain. Which scenarios expose the observability, failure-recovery, and coupling tradeoffs? | expertise | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-evaluate-via-atam-whether-to-move-a-synchronous--40611) |
| You're evaluating whether a workflow with heavy branching is clearer as a State machine or a rules-driven Chain of Responsibility. What complexity signals (transition density, branch depth, testability) push you decisively toward one? | deep understanding | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-evaluating-whether-a-workflow-with-heavy-branching-is-clearer-a-38488) |
| You must architect a workflow/approval engine where business users configure multi-step approval flows without code — how do you model the flow-definition versioning in-flight instances during a definition change and long-running human waits? | deep understanding | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-a-workflow-approval-engine-where-business-users-con-39465) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you plan continuity for long-running stateful workflows and sagas that were mid-execution when a region failed, so business processes don't get stuck in limbo? | deep understanding | SDE-2/3, Architect/Principal | Business Continuity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-continuity-for-long-running-stateful-workflows-and-sag-56972) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your incident-automation workflow spans five steps across services (diagnose, drain, scale, notify, verify) and a worker crashed after draining but before scaling. Explain how you'd make the workflow durable so it resumes from the drain step rather than re-draining, and the determinism constraints on the notify step. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-incident-automation-workflow-spans-five-steps-across-services-dia-92933) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle in-flight distributed transactions and sagas across a database failover so a cut-over mid-workflow leaves no partial or duplicated business state? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-in-flight-distributed-transactions-and-sagas-across--112874) |
| Design the pattern for long-running human-in-the-loop data workflows (a data-correction approval that waits days before writing to the system-of-record) in an event-driven enterprise. How do you model wait states and timeouts without holding a transaction open, and where does a workflow engine belong versus the database? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-pattern-for-long-running-human-in-the-loop-data-workflows-a-112597) |
| How do you design a saga or process-manager that coordinates state changes across payment relational store inventory key-value and notification queue with compensations? | expertise | SDE-2/3, Architect/Principal | Polyglot Persistence | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-saga-or-process-manager-that-coordinates-state-cha-114581) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Steelman the position that your org should NOT build an agent framework and should compose stateless LLM calls with a workflow engine instead; then present when you'd override that and adopt a real agent runtime. | expertise | SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=steelman-the-position-that-your-org-should-not-build-an-agent-framewor-68982) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Walk me through your reference architecture for durable long-horizon agents that span days, integrating human approvals, event-driven wakeups, and idempotent tool replay. What engine and state model underpin it? | expertise | SDE-2/3, Architect/Principal | Agentic Workflows | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-your-reference-architecture-for-durable-long-horizon-a-84548) |
