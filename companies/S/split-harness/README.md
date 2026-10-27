# Split-Harness

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 3 | 4 | 1 | 4 |
| AI Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must decide whether to build a homegrown feature-flag/config service on DynamoDB or adopt AppConfig for org-wide dynamic config — how do you weigh propagation latency, blast-radius of a bad flag, and the operational cost of owning it? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-whether-to-build-a-homegrown-feature-flag-config-servi-39312) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd architect a resilient global-config/feature-flag control plane that hundreds of services depend on, so that if it's unreachable, every service still starts and runs on safe local defaults, and a bad global flag can't fan out to the whole fleet. | expertise | SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-architect-a-resilient-global-config-feature-flag-con-52895) |
| How would you use OpenFeature as a vendor-agnostic abstraction so you can swap flag providers without touching app code, and what does that buy an SRE team operationally? | deep understanding | SDE-1/2, SDE-2/3 | Feature Flags & Progressive Rollouts | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-openfeature-as-a-vendor-agnostic-abstraction-so-you--47339) |
| Your flag service is a SaaS vendor and it went down during a regional outage — how do you architect the SDK caching and fallback so your app keeps serving sane defaults? | deep understanding | SDE-1/2, SDE-2/3 | Feature Flags & Progressive Rollouts | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-flag-service-is-a-saas-vendor-and-it-went-down-during-a-regional--47363) |
| Your org wants flags to be self-service for developers but SRE-governed for anything touching prod capacity — how do you split permissions and approval flows to balance speed and safety? | deep understanding | SDE-1/2, SDE-2/3 | Feature Flags & Progressive Rollouts | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-flags-to-be-self-service-for-developers-but-sre-governe-47395) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you would expose a feature-flag or config resource via MCP so agent behavior can be tuned without redeploys. | intermediate experience | SDE-1/2, SDE-2/3 | Model Context Protocol (MCP) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-expose-a-feature-flag-or-config-resource-via-mcp-80985) |
