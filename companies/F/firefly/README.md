# Firefly

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 8

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 2 | 8 | 7 | 8 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a Terraform state + policy + drift orchestration layer (Spacelift/env0/Terraform Cloud vs self-hosted Atlantis + OPA) when GitOps for infra becomes the single gate on all cloud changes? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-terraform-state-policy-drift-orch-53731) |
| Your org wants to adopt a 'FinOps-as-code' model where budgets, quotas, and commitment strategy are declared in the same IaC as infrastructure. As architect, how would you design that so cost policy is version-controlled, reviewed, and enforced at plan time? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-to-adopt-a-finops-as-code-model-where-budgets-quotas-an-52991) |
| An interviewer challenges your reliance on tags for governance: 'tags are advisory and teams forget them.' Defend or replace tag-based governance with something stronger — how do you make classification a non-optional property of the resource rather than an afterthought label? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-reliance-on-tags-for-governance-tags-ar-54073) |
| How do you influence teams to pay down cross-cutting infra debt — expired IAM roles, orphaned resources, drifted Terraform — that no single team owns and everyone benefits from ignoring? What structural mechanism, not just persuasion, do you install? | deep understanding | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-influence-teams-to-pay-down-cross-cutting-infra-debt-expire-54464) |
| Explain how you'd govern the reconciliation between desired state (IaC) and actual cloud state at scale. What happens when someone clicks in the console and how do you close the loop? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Governance Frameworks | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-the-reconciliation-between-desired-state-iac--56007) |
| Your standby region's Terraform state has drifted because someone made manual changes there. How do you reconcile it, and what guardrails (drift detection, SCPs) prevent the standby from rotting? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-standby-region-s-terraform-state-has-drifted-because-someone-made-47570) |
| You need to detect config drift by comparing live AWS resource state (via boto3) against Terraform state. How would you structure the diff and decide what counts as a meaningful drift versus noise? | expertise | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-detect-config-drift-by-comparing-live-aws-resource-state-v-45139) |
| How do you architect drift detection so that any out-of-band change to a FedRAMP-boundary resource is auto-detected, alerted, and evidenced as a control violation? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-drift-detection-so-that-any-out-of-band-change-to-56783) |
