# GitGuardian

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 5 | 5 | 0 | 5 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 4 | 5 | 5 | 5 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A leaked database password was committed and pushed to an internal repo, then removed in a follow-up commit. Explain why deleting it in a new commit is useless, and the correct order of rotate, purge history, and notify. | deep understanding | SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-leaked-database-password-was-committed-and-pushed-to-an-internal-rep-26547) |
| Explain how author and committer diverge on a commit, why the Verified badge attests to the committer's signature not code safety, and how a malicious PR could show a spoofed author name. | deep understanding | SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-author-and-committer-diverge-on-a-commit-why-the-verified--26601) |
| You must audit your org's GitHub security posture. Which settings (2FA enforcement, secret scanning, required reviews, default GITHUB_TOKEN perms, third-party OAuth app access, SSO) do you check, and how do you prioritize fixes? | expertise | SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-audit-your-org-s-github-security-posture-which-settings-2fa-e-26602) |
| You want to speed up dependency-vulnerability response across 30 backend repos. How does Dependabot fit in, how do you avoid PR spam, and how would you auto-merge only safe patch bumps that pass CI? | deep understanding | SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-speed-up-dependency-vulnerability-response-across-30-backe-26620) |
| Your team enforces server-side push protection, but a determined dev could still commit a secret locally. Compare a pre-receive hook, GitHub push protection, and client-side hooks for blocking an AWS key, including the gap each leaves. | deep understanding | SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-team-enforces-server-side-push-protection-but-a-determined-dev-co-26549) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A secret was pushed to a public repo and possibly used. As principal, design the org-wide structural prevention (pre-commit and CI secret scanning, short-lived dynamic credentials, no-standing-secrets, auto-revoke on detection) so a leaked secret is worthless — not just the point fix for this leak. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-secret-was-pushed-to-a-public-repo-and-possibly-used-as-principal-de-38905) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd stop secrets from leaking into git and CI logs — what layered controls do you put in place, and how do you catch what still slips through? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-stop-secrets-from-leaking-into-git-and-ci-logs-what--50633) |
| Explain your approach to secrets scanning in CI — pre-commit hooks versus server-side, and why you'd want both. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-your-approach-to-secrets-scanning-in-ci-pre-commit-hooks-versu-50682) |
| You discover an AWS access key was committed to a public repo three days ago — what's your incident response, in order? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-discover-an-aws-access-key-was-committed-to-a-public-repo-three-da-50634) |
| How would you design a secrets-detection and prevention layer (pre-commit, CI scanning, and Vault as the sanctioned store) so that leaked secrets in git become rare and quickly revoked? What's the closed loop? | deep understanding | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-secrets-detection-and-prevention-layer-pre-comm-55003) |
| A developer commits an AWS key to a public repo and it's exploited within minutes. Walk me through prevention (pre-commit hooks, secret scanning), detection (GitHub push protection, credential monitoring), and the automated revocation you'd wire up. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-developer-commits-an-aws-key-to-a-public-repo-and-it-s-exploited-wit-47868) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you govern the tension where security wants maximum log redaction and ML wants maximum detail — what standardized redaction/tokenization contract do you set? | expertise | SDE-2/3, Architect/Principal | AIOps Data Governance & Standardization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-govern-the-tension-where-security-wants-maximum-log-redacti-103137) |
| What governance do you need so that a security team can quarantine or scrub telemetry (e.g. leaked secrets in logs) without breaking the ML pipelines depending on it? | expertise | SDE-2/3, Architect/Principal | AIOps Data Governance & Standardization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-governance-do-you-need-so-that-a-security-team-can-quarantine-or--103109) |
