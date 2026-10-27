# Palo

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 7 | 7 | 7 | 7 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must provision cross-account infra where the prod-account role can only be assumed after MFA, but CI has no human to enter MFA. How do you architect the assume-role chain and session policies so automated applies work without weakening the human MFA requirement? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-provision-cross-account-infra-where-the-prod-account-role-can-30213) |
| You need to run terraform in an air-gapped environment where the public registry is blocked. Walk me through hosting a private provider mirror, pinning the lock file's hashes, and keeping the mirror in sync as you upgrade providers. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-run-terraform-in-an-air-gapped-environment-where-the-publi-30184) |
| You want a break-glass path to apply an emergency infra fix when CI is down, but without permanently handing engineers prod apply rights. Design a time-boxed, audited emergency-access flow that reconciles state afterward so the manual fix doesn't drift. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-a-break-glass-path-to-apply-an-emergency-infra-fix-when-ci-is-30970) |
| You want to detect and alert when someone bypasses Terraform and changes infra directly in the console. Beyond nightly plans, how would you use CloudTrail and config rules to catch out-of-band changes in near-real-time and route them to the owning team? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-detect-and-alert-when-someone-bypasses-terraform-and-chang-30207) |
| You want to enforce that no PR can add a security group rule opening 0.0.0.0/0 on port 22, but engineers keep finding creative encodings (variables, dynamic blocks) to sneak it past a naive regex check. How do you make the policy robust against evasion by evaluating the resolved plan? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-enforce-that-no-pr-can-add-a-security-group-rule-opening-0-30231) |
| Your CI applies from an OIDC-federated role, but a compromised PR could exfiltrate the role by printing aws sts get-caller-identity" and abusing session tokens in a build step. How do you harden the apply pipeline so a malicious PR can't escalate to prod credentials?" | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-ci-applies-from-an-oidc-federated-role-but-a-compromised-pr-could-30178) |
| Your org enforces no public S3 buckets via OPA, but a team bypassed it by creating the bucket private and adding a public policy in a separate resource in another PR. How do you close policy-evasion gaps where the violating state emerges from a combination of resources? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Infrastructure as Code (Terraform) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-enforces-no-public-s3-buckets-via-opa-but-a-team-bypassed-it--30950) |
