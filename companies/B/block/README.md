# Block

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 2 | 2 | 1 | 2 |
| AI Engineer | 1 | 0 | 4 | 9 | 7 | 9 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Walk me through how you'd define and instrument cost-per-transaction as a first-class SLO for a payments platform doing 5B transactions/month, and how that metric would change the way you make architecture decisions. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-define-and-instrument-cost-per-transaction-a-37015) |
| Walk me through how you'd decide between active-active and active-passive multi-region topologies for a global payments ledger, and what specific failure and correctness properties push you toward one over the other. | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-decide-between-active-active-and-active-pass-36614) |
| Your active-active writes are eventually consistent but a fraud-check service needs a global view of recent transactions to catch cross-region abuse. How do you reconcile local writes with global fraud detection? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-active-active-writes-are-eventually-consistent-but-a-fraud-check--36669) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You expose your model's endpoint over MCP so multiple internal agents can call it. How do you version the tool schema so an older agent client keeps working when you add a parameter? | deep understanding | SDE-1/2, SDE-2/3 | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-expose-your-model-s-endpoint-over-mcp-so-multiple-internal-agents--64190) |
| What is the difference between an in-process function tool and an MCP server tool, and where do the server's credentials live so they never enter the prompt? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-difference-between-an-in-process-function-tool-and-an-mcp--63875) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you integrate an MCP server into your existing agent stack, and what security review would you run before trusting a third-party MCP server? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Agentic Workflows | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-integrate-an-mcp-server-into-your-existing-agent-stack-a-80526) |
| You're the principal advising the CTO on whether to standardize on MCP as the org's tool-interoperability standard. What's your recommendation, the risks, and the migration path from bespoke tool adapters? | expertise | SDE-2/3, Architect/Principal | Agentic Workflows | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-the-principal-advising-the-cto-on-whether-to-standardize-on-mcp-84544) |
| What is the Model Context Protocol (MCP) in one or two beginner sentences, and what problem does it solve for connecting agents to tools? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-model-context-protocol-mcp-in-one-or-two-beginner-sentence-73616) |
| How would you build a CI check that a new tool added to your agent has appropriate rate limits and auth wired in, so an agent can't be tricked into abusing a powerful tool? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-ci-check-that-a-new-tool-added-to-your-agent-has-77680) |
| How would you run integration tests for an MCP-based tool server in CI so a change to a tool's interface is validated against the way the model actually invokes it? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-run-integration-tests-for-an-mcp-based-tool-server-in-ci-77652) |
| How would you design a cross-team contract for feature freshness so a consumer knows exactly how stale a feature can be and is alerted before an SLA is silently broken? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-cross-team-contract-for-feature-freshness-so-a--84339) |
| How would you design multi-region active-active serving for a payments risk model so a regional outage cannot stop transaction scoring? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-multi-region-active-active-serving-for-a-payments-84422) |
| Architect injection defense for an agent that composes many untrusted MCP servers dynamically at runtime. How do you sandbox, attest, and authorize tools you didn't ship, and what's your trust-on-first-use policy? | expertise | SDE-2/3, Architect/Principal | Prompt Injection & Jailbreak Defense | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-injection-defense-for-an-agent-that-composes-many-untrusted--85657) |
| How do you account for retries, timeouts, and guardrail re-runs in a token budget so the 'wasted' tokens don't silently blow the forecast? | deep understanding | SDE-2/3, Architect/Principal | Token Budgeting & Throughput Estimation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-account-for-retries-timeouts-and-guardrail-re-runs-in-a-tok-86352) |
