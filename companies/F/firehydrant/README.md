# FireHydrant

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 2 | 9 | 9 | 9 |
| AIOps | 0 | 0 | 6 | 6 | 1 | 6 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe how you would architect a chaos strategy that treats human/process failures (wrong runbook, missing access, key person out) as injectable faults during GameDays. | expertise | SDE-2/3, Architect/Principal | Chaos Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-would-architect-a-chaos-strategy-that-treats-human-pr-55218) |
| Describe how you would design chaos experiments that specifically exercise your incident-command process, comms, and paging at org scale, not just the technical failure. | deep understanding | SDE-2/3, Architect/Principal | Chaos Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-would-design-chaos-experiments-that-specifically-exer-55158) |
| How do you architect governance so an incident's regulatory-notification decision (is this reportable within 72 hours) is driven by a defensible pre-agreed severity rubric rather than a panicked judgment call at 3am — and how do you rehearse that decision path? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-so-an-incident-s-regulatory-notificati-54106) |
| How do you architect a company-wide incident-response platform as a paved-road internal product — declare, page, coordinate, communicate, retro — and get 50 autonomous teams to adopt it without a top-down mandate? | expertise | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-company-wide-incident-response-platform-as-a-pa-53220) |
| How do you decide build-vs-buy for the whole incident stack (paging, orchestration, status page, retro tooling), and how does that calculus shift as you scale from 50 to 5000 engineers and integration depth grows? | expertise | SDE-2/3, Architect/Principal | Incident Management & On-call | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-whole-incident-stack-paging-orc-53164) |
| How would you design so your incident tooling and status page aren't hosted in the same region as the workload, so you can still communicate and coordinate during a full-region outage? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-so-your-incident-tooling-and-status-page-aren-t-h-47598) |
| Walk me through writing a failover runbook precise enough that an on-call engineer with 6 months tenure can execute a region cutover at 3am, and what you automate to reduce manual steps. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-writing-a-failover-runbook-precise-enough-that-an-on-c-47565) |
| How do you handle the strategic decision of whether the platform team should absorb the org's incident-management and reliability practice, or stay a capability provider that reliability teams consume? Where does that ownership line create the healthiest incentives? | deep understanding | SDE-2/3, Architect/Principal | Platform Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-strategic-decision-of-whether-the-platform-team--54301) |
| How would you architect an incident-response structure for a system-of-systems so a cross-team cascading outage has a clear incident commander, blast-radius containment playbooks, and pre-approved 'break-glass' degradations, so the org stops the bleeding in minutes rather than debating ownership? | deep understanding | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-an-incident-response-structure-for-a-system-of-52086) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Why is streaming the LLM's incident narrative useful in a war-room chat even if total time is unchanged, and how would you implement it into the incident channel? | intermediate experience | SDE-1/2, SDE-2/3 | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-is-streaming-the-llm-s-incident-narrative-useful-in-a-war-room-cha-92870) |
| You maintain a running incident conversation across many services calling the model statelessly. How do you store per-incident history so you don't resend the whole timeline each turn but the model keeps needed context? | deep understanding | SDE-1/2, SDE-2/3 | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-maintain-a-running-incident-conversation-across-many-services-call-92881) |
| You summarize a growing incident thread with rolling summarization. What load-bearing detail (timestamps, who ran what) tends to get dropped, and how do you preserve it across the summary? | intermediate experience | SDE-1/2, SDE-2/3 | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-summarize-a-growing-incident-thread-with-rolling-summarization-wha-92839) |
| You want an LLM to generate a first-draft postmortem from the incident timeline. How do you evaluate quality when there's no single correct postmortem, and what approaches balance faithfulness against readability? | deep understanding | SDE-1/2, SDE-2/3 | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-an-llm-to-generate-a-first-draft-postmortem-from-the-incident-92909) |
| Your observability copilot's context window fills up as an incident channel grows. How do you manage the running incident timeline so the model keeps the key facts without blowing the window? | deep understanding | SDE-1/2, SDE-2/3 | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-observability-copilot-s-context-window-fills-up-as-an-incident-ch-92838) |
| How would you present a post-incident timeline for a drift outage to a review board, tying telemetry to the change that caused it? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Observability (Prompt/Retrieval Drift) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-present-a-post-incident-timeline-for-a-drift-outage-to-a-97913) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the incident-response runbook and on-call model specifically for agent failures where the root cause could be a model regression, tool outage, prompt change, or injection attack. How do you triage fast when the failure itself is probabilistic and intermittent? | deep understanding | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-incident-response-runbook-and-on-call-model-specifically-fo-83109) |
