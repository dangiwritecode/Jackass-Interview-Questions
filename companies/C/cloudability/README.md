# Cloudability

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 8 | 8 | 8 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You are evaluating build-vs-buy for a FinOps platform: native cloud tools, a third-party SaaS (Apptio/Cloudability/Vantage), or an in-house build. Walk me through the decision framework and when the in-house build is actually justified at your scale. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-evaluating-build-vs-buy-for-a-finops-platform-native-cloud-too-37052) |
| Your amortized-versus-blended cost views tell two different stories and executives lose trust in FinOps numbers. Explain when to use amortized versus blended versus unblended cost, and how you'd standardize the 'source of truth' across finance and engineering. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-amortized-versus-blended-cost-views-tell-two-different-stories-an-37048) |
| Your company runs on 3 clouds after two acquisitions. Design a unified cost-visibility and governance layer across AWS, GCP, and Azure — normalization, tagging reconciliation, and cross-cloud commitment strategy — and tell me what you'd deliberately NOT unify. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-company-runs-on-3-clouds-after-two-acquisitions-design-a-unified--37040) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you build a chargeback-aware Composition that tags every provisioned resource for cost allocation automatically? | deep understanding | SDE-2/3, Architect/Principal | Crossplane & Control Plane Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-chargeback-aware-composition-that-tags-every-pro-56268) |
| How would you design guardrails so a Claim can't accidentally provision a 96xlarge or an unbounded autoscaling group and blow the budget? | deep understanding | SDE-2/3, Architect/Principal | Crossplane & Control Plane Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-guardrails-so-a-claim-can-t-accidentally-provisio-56300) |
| Interviewer probe: you decoupled infra API from implementation — how do you stop that indirection from hiding real cost and latency from teams? | expertise | SDE-2/3, Architect/Principal | Crossplane & Control Plane Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=interviewer-probe-you-decoupled-infra-api-from-implementation-how-do-y-56309) |
| What is your FinOps strategy for attributing cloud cost to teams when everything is provisioned through a shared Crossplane control plane? | expertise | SDE-2/3, Architect/Principal | Crossplane & Control Plane Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-finops-strategy-for-attributing-cloud-cost-to-teams-when--56252) |
| A bar-raiser asks you to reason about the limits of tagging: you've said allocation degrades gracefully below 100% tag coverage. Formalize that — what's the minimum tag coverage below which your allocation number becomes indefensible, and how do you attribute the untaggable remainder without picking arbitrary winners? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-bar-raiser-asks-you-to-reason-about-the-limits-of-tagging-you-ve-sai-53911) |
| A principal probe on build-vs-buy: leadership wants to replace your homegrown cost-allocation pipeline with a commercial FinOps SaaS. You built the internal one because commercial tools couldn't attribute your bespoke k8s multi-tenancy. Defend keeping the build, or make the case to migrate — and set the switching criteria. | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-probe-on-build-vs-buy-leadership-wants-to-replace-your-hom-53844) |
| A principal-level scenario: your org's cost data reconciles three ways — the raw billing export, the k8s allocator, and SaaS vendor invoices — and they never agree, eroding leadership trust. Design the single-source-of-truth reconciliation pipeline and explain how you'd communicate and bound the irreducible residual variance. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-level-scenario-your-org-s-cost-data-reconciles-three-ways--53881) |
| Walk me through architecting a FinOps data platform that ingests FOCUS-format billing exports across AWS, Azure, and GCP into one schema. What does adopting the FOCUS spec actually buy you at org scale, and where does it still leak provider-specific complexity you have to special-case? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-architecting-a-finops-data-platform-that-ingests-focus-53837) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a cost-attribution system that charges each team back for their share of telemetry ingest and AIOps inference, and why does chargeback change behavior more than dashboards? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-cost-attribution-system-that-charges-each-te-98761) |
| How do you incorporate FinOps practices into observability so every dashboard and alert has a visible cost attached to inform trade-offs? | deep understanding | SDE-2/3, Architect/Principal | Observability Platform Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-incorporate-finops-practices-into-observability-so-every-da-103041) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you build a system to forecast cloud spend per team and alert when actuals deviate from forecast, enabling FinOps? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-system-to-forecast-cloud-spend-per-team-and-aler-66464) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you build a cost-per-token attribution pipeline that maps third-party API spend back to the exact feature, team, and end-user, when the provider's invoice is a single opaque monthly number? What tagging and metering architecture makes this work? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-a-cost-per-token-attribution-pipeline-that-maps-third-83355) |
