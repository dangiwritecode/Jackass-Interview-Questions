# Infracost

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 3 | 3 | 3 |
| Fullstack | 0 | 0 | 1 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 2 | 8 | 7 | 8 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe how you'd embed FinOps into the CI/CD and IaC pipeline so cost impact is visible at PR time. What do you show the engineer, what do you block on, and how do you avoid alert fatigue? | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-embed-finops-into-the-ci-cd-and-iac-pipeline-so-cos-37031) |
| You need to detect that a costly change (e.g., switching to a bigger instance fleet) merged and correlate it to the bill spike a week later. How do you wire Infracost into the pipeline AND retain plan cost estimates so you can attribute a spend change to a specific PR? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-detect-that-a-costly-change-e-g-switching-to-a-bigger-inst-30228) |
| Your monthly cloud bill spiked after a Terraform change. How do you use plan output, cost-estimation tools (Infracost), and tagging to catch expensive changes before they merge? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-monthly-cloud-bill-spiked-after-a-terraform-change-how-do-you-use-21137) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your monthly cloud bill spiked after a Terraform change. How do you use plan output, cost-estimation tools (Infracost), and tagging to catch expensive changes before they merge? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-monthly-cloud-bill-spiked-after-a-terraform-change-how-do-you-use-21137) |
| Leadership wants a carbon-aware and cost-aware scheduling strategy so batch runs when grid intensity and spot prices are low. How would you architect carbon-aware placement across regions and time, what SLO and data-locality constraints bound it, and how would you report the emissions and dollar savings credibly? | deep understanding | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=leadership-wants-a-carbon-aware-and-cost-aware-scheduling-strategy-so--39024) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect capacity governance for a platform where a single misconfigured GitOps commit can provision or destroy huge capacity fleet-wide? What plan-time cost estimation and approval gates prevent a cost-catastrophe from a merged PR? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-capacity-governance-for-a-platform-where-a-single-52996) |
| Your org wants to adopt a 'FinOps-as-code' model where budgets, quotas, and commitment strategy are declared in the same IaC as infrastructure. As architect, how would you design that so cost policy is version-controlled, reviewed, and enforced at plan time? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-to-adopt-a-finops-as-code-model-where-budgets-quotas-an-52991) |
| A principal-level probe: your IaC is split across Terraform, Pulumi, and CDK owned by different teams, and cost-preview tooling only integrates cleanly with one. How do you deliver a consistent pre-merge cost-gate across heterogeneous IaC without mandating everyone converge on a single tool? | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-level-probe-your-iac-is-split-across-terraform-pulumi-and--53849) |
| Walk me through adding a cost estimate to a Terraform pull request with Infracost. What do you show the reviewer, and would you ever block a merge on it? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-adding-a-cost-estimate-to-a-terraform-pull-request-wit-47752) |
| A cost spike traced to a Terraform change that resized instances 10x, and the PR was approved by someone who didn't understand the cost impact. How would you surface estimated cost delta on every infra PR so approvers see the FinOps impact before merging? | deep understanding | SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-cost-spike-traced-to-a-terraform-change-that-resized-instances-10x-a-45713) |
| A cross-team dispute: the FinOps team wants Terraform to enforce a hard per-resource cost ceiling at plan time, but engineers argue it blocks legitimate scale-ups during incidents. As principal, design a cost-guardrail that hard-fails runaway provisioning yet has an audited, time-boxed break-glass override for genuine capacity emergencies. | deep understanding | SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-cross-team-dispute-the-finops-team-wants-terraform-to-enforce-a-hard-53077) |
| You're deciding whether to adopt Terraform run tasks (pre-plan / post-plan webhooks) for policy and cost checks versus baking them into CI steps. As principal, weigh the coupling to a specific run environment (TFC/TFE) against the portability of CI-native checks, and where run tasks give you an enforcement guarantee CI can't. | deep understanding | SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-whether-to-adopt-terraform-run-tasks-pre-plan-post-pla-53049) |
| You're setting the org's stance on 'infrastructure diff review' UX: raw HCL plans are unreadable to reviewers, so some teams built plan-to-English bots and others use TFC's visual plan. As principal, define what a trustworthy plan-review artifact must show (replacements, blast radius, cost, policy result) and where a summarized diff dangerously hides a critical change. | deep understanding | SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-setting-the-org-s-stance-on-infrastructure-diff-review-ux-raw-h-53085) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You want engineers to see the projected scan-bytes and dollar cost of a SQL or Spark job change at pull-request time. What can you realistically estimate pre-merge from the compiled plan, table statistics, and partition layout, what do you block on, and how do you avoid alert fatigue? | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-engineers-to-see-the-projected-scan-bytes-and-dollar-cost-of--125979) |
