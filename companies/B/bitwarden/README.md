# Bitwarden

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 7 | 10 | 9 | 10 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a 'sudo mode' where sensitive settings pages require a fresh re-auth within the last 5 minutes. Where do you track this freshness, and how do you avoid re-prompting the user on every field save? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-sudo-mode-where-sensitive-settings-pages-require-a-fresh-re-a-26180) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An auditor accepts your evidence but your own principal-engineering judgment says a control is theater. How do you navigate the gap between 'audit-passing' and 'actually-secure' — and what's your architectural strategy to close controls that satisfy paperwork but not adversaries? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-auditor-accepts-your-evidence-but-your-own-principal-engineering-ju-54057) |
| How do you manage secrets for a Kubernetes workload without storing them in plaintext — compare the approaches you've actually used and their trade-offs. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-manage-secrets-for-a-kubernetes-workload-without-storing-th-50635) |
| A large secret synced via External Secrets exceeded etcd's object size and reconciliation failed silently — how do you catch resource-limit failures in GitOps? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GitOps | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-large-secret-synced-via-external-secrets-exceeded-etcd-s-object-size-50102) |
| Define your org's secrets-in-GitOps strategy at fleet scale — Sealed Secrets vs External Secrets vs Vault-injected — and how you handle key rotation without a fleet-wide outage. | expertise | SDE-2/3, Architect/Principal | GitOps | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=define-your-org-s-secrets-in-gitops-strategy-at-fleet-scale-sealed-sec-54834) |
| Explain how you'd prevent secret values from ever landing in git history even accidentally — pre-commit hooks, admission control, and repo scanning all have gaps. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GitOps | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-prevent-secret-values-from-ever-landing-in-git-histo-50049) |
| How do you handle secrets rotation in a GitOps world where the secret itself lives in Vault but the reference lives in git — what triggers the pod to pick up the new value? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GitOps | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-secrets-rotation-in-a-gitops-world-where-the-secret--50088) |
| You need audit-grade change tracking for SOC2 — how does GitOps satisfy it and where are the gaps (out-of-band kubectl, controller service accounts)? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GitOps | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-audit-grade-change-tracking-for-soc2-how-does-gitops-satisfy--50073) |
| You're setting a fleet-wide standard for secret rotation where the value lives in Vault and the reference lives in git — architect what triggers pods to pick up rotated values without manual intervention. | expertise | SDE-2/3, Architect/Principal | GitOps | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-setting-a-fleet-wide-standard-for-secret-rotation-where-the-val-54892) |
| Your Sealed Secrets controller's key was rotated and all sealed secrets across the fleet failed to decrypt — how do you recover, and how do you avoid this single point of failure? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GitOps | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-sealed-secrets-controller-s-key-was-rotated-and-all-sealed-secret-50036) |
| A teammate wants to store a private TLS key inside a YAML Secret manifest. Walk through why base64 in YAML is not encryption and how sealed-secrets or SOPS keeps the encrypted blob valid YAML. | deep understanding | SDE-1/2, SDE-2/3 | YAML | Online Assessment (OA), Phone Screen | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-teammate-wants-to-store-a-private-tls-key-inside-a-yaml-secret-manif-48947) |
