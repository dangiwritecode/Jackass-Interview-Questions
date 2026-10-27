# Lacework

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 4 | 6 | 6 | 6 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a cloud security posture management (CSPM) + CNAPP platform (Wiz/Orca/Prisma vs OSS Cloud Custodian/Steampipe + bespoke) across multi-account, multi-cloud, when the vendor sees all your config? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-cloud-security-posture-management-53742) |
| An interviewer challenges: 'your continuous-control-monitoring dashboard is green but you just had a breach.' Diagnose the class of failure where CCM gives false assurance and how you'd architect controls whose green truly implies safe. | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-continuous-control-monitoring-dashboard-54047) |
| A security review flags that your S3 buckets are 'private' but accessible from any principal in the account. Explain the difference between bucket ACLs, bucket policies, and IAM policies, and how you'd enforce least-privilege so only the ingestion service reads a given bucket. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-security-review-flags-that-your-s3-buckets-are-private-but-accessibl-47840) |
| Explain how you'd build a live query that answers 'what could an attacker reach right now if they compromised service X?' rather than a stale spreadsheet. What graph of identities, network policy, and IAM do you maintain and how do you keep it accurate? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-build-a-live-query-that-answers-what-could-an-attack-47913) |
| Walk me through why enabling IMDSv2 and setting the hop limit to 1 on your EC2 instances matters for zero trust, and what class of container-escape-to-cloud-credential attacks it prevents. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-why-enabling-imdsv2-and-setting-the-hop-limit-to-1-on--47871) |
| Your leadership wants a single 'security posture score' per team. Design the scoring inputs, then tell me the perverse incentives it creates and the concrete ways teams will game it, and how you'd defend against that. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-leadership-wants-a-single-security-posture-score-per-team-design--47896) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a continuous red-team pipeline for agents (injection fuzzing, tool-abuse fuzzing, jailbreak regression) that gates every release, and how do you keep it from becoming a flaky, ignored CI stage? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-continuous-red-team-pipeline-for-agents-injecti-83051) |
