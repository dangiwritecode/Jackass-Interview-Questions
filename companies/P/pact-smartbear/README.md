# Pact-SmartBear

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 4 | 5 | 2 | 5 |
| Fullstack | 0 | 0 | 1 | 5 | 4 | 5 |
| DevOps | 0 | 0 | 2 | 3 | 1 | 3 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect the enterprise pattern for schema/contract testing across producer-consumer team boundaries (consumer-driven contracts, contract registries). How do you make a breaking-change fail in CI at the producer rather than in production at the consumer? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-the-enterprise-pattern-for-schema-contract-testing-across-pr-36368) |
| A contract test passed in CI but the real integration failed in prod because the mock drifted from the provider. How do you keep contracts honest? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-contract-test-passed-in-ci-but-the-real-integration-failed-in-prod-b-25094) |
| A downstream migration changes an API's response shape and your Node.js clients break silently. How would you have caught this earlier with contract testing? | deep understanding | SDE-1/2, SDE-2/3 | Node.js | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-downstream-migration-changes-an-api-s-response-shape-and-your-node-j-17562) |
| Explain how you'd design a 'prompt contract test' that a downstream team can run against your LLM service so they're alerted before you ship a change that breaks their parsing assumptions. | deep understanding | SDE-1/2, SDE-2/3 | Prompt Engineering | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-prompt-contract-test-that-a-downstream-team-27586) |
| How do you design a REST API contract test suite that a consumer team runs in their CI against a provider mock, so a provider change breaks the consumer build before the provider deploys? | deep understanding | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-rest-api-contract-test-suite-that-a-consumer-team--23977) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org wants the gateway to enforce a mandatory 'consumer contract' registration so no team can call another team's API without a declared, reviewed dependency; design this dependency-governance layer and adjudicate the friction it adds versus the coupling it prevents. | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-the-gateway-to-enforce-a-mandatory-consumer-contract-re-39567) |
| How do you architect a schema-and-contract-testing regime across an org so a producer team deploying an EventBridge/API change can't break downstream consumers, and defend where you draw the line between consumer-driven contracts and a central registry? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-schema-and-contract-testing-regime-across-an-or-39253) |
| Architect the enterprise approach to API mocking, service virtualization, and contract stubs so 40 frontend and backend teams can develop in parallel against not-yet-built services. How do you keep the mocks honest so integration doesn't blow up at merge time? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-the-enterprise-approach-to-api-mocking-service-virtualizatio-40765) |
| How do you validate the migration end-to-end when consumer-driven contract tests between the facade and services must cover behaviors nobody has documented? | deep understanding | SDE-2/3, Architect/Principal | Migration Strategy (Strangler Fig) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-validate-the-migration-end-to-end-when-consumer-driven-cont-40988) |
| A downstream migration changes an API's response shape and your Node.js clients break silently. How would you have caught this earlier with contract testing? | deep understanding | SDE-1/2, SDE-2/3 | Node.js | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-downstream-migration-changes-an-api-s-response-shape-and-your-node-j-17562) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you handle a sprint where a critical dependency team promised an API but delivered only a mock; how do you contract-test and structure your stories so integration surprises don't leak into the next sprint? | intermediate experience | SDE-1/2, SDE-2/3 | Agile/Scrum | Phone Screen, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-a-sprint-where-a-critical-dependency-team-promise-46399) |
| How would you introduce consumer-driven contract testing between services as a phased backlog initiative, and prove sprint over sprint that it's reducing integration breakage? | deep understanding | SDE-1/2, SDE-2/3 | Agile/Scrum | Phone Screen, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-introduce-consumer-driven-contract-testing-between-servi-46362) |
| You're accountable for making cross-service API evolution safe on Kubernetes when you can't coordinate simultaneous releases. How would you standardize contract versioning, consumer-driven contracts, and rollout gating so old and new callers always interoperate during any single team's deploy, and enforce it at CI? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-accountable-for-making-cross-service-api-evolution-safe-on-kube-52221) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd build an "agent contract test" so a tool team can change their tool and immediately know which agents' behaviors regress, before deploy. | deep understanding | SDE-2/3, Architect/Principal | Agentic System Architecture | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-build-an-agent-contract-test-so-a-tool-team-can-chan-87005) |
