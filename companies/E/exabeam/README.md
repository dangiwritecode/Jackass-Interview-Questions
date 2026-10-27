# Exabeam

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 4 | 4 | 4 |
| AIOps | 0 | 0 | 0 | 3 | 3 | 3 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect governance so a security incident's forensic timeline is provably complete across the seam between your identity provider your cloud audit log and your application logs — where clock skew and log gaps between systems could hide the attacker's path? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-so-a-security-incident-s-forensic-time-54076) |
| How do you architect ongoing insider-threat detection (audit review, UEBA) for privileged platform engineers with legitimate broad access to PHI systems? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-ongoing-insider-threat-detection-audit-review-ueb-56807) |
| Design an anomaly-detection layer over Vault audit logs to catch a service reading 10x its baseline or a human enumerating paths. What signals matter, and how do you keep false positives from causing alert fatigue? | deep understanding | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-anomaly-detection-layer-over-vault-audit-logs-to-catch-a-ser-54972) |
| How do you architect the audit-log HMAC-key management so you can still correlate logged values back to real secrets during a forensic investigation, while keeping the raw logs privacy-safe day-to-day? | deep understanding | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-audit-log-hmac-key-management-so-you-can-stil-54997) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect DR for a platform serving both real-time operational monitoring (needs low RTO, tolerates data gaps) and forensic security investigation (tolerates higher RTO, needs zero data loss)? These pull RPO/RTO in opposite directions on one platform — how do you split them? | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-dr-for-a-platform-serving-both-real-time-operatio-99988) |
| How do you architect DR so a security incident-response 'freeze everything, preserve forensics' directive doesn't conflict with the need to fail over the observability platform fast — the platform holds the forensic evidence and is also needed live. Reconcile the two imperatives. | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-dr-so-a-security-incident-response-freeze-everyth-100007) |
| How do you architect DR so that the SIEM/security-observability half of your platform preserves an immutable, tamper-evident audit trail through a disaster, even when the attacker's goal may be to destroy that trail? Reconcile RPO with anti-tampering. | expertise | SDE-2/3, Architect/Principal | Disaster Recovery (RTO/RPO) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-dr-so-that-the-siem-security-observability-half-o-99950) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd design controls and drills to detect and respond to a slow, low-volume data-exfiltration campaign that stays under per-query rate thresholds for months. | expertise | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-controls-and-drills-to-detect-and-respond-to--114130) |
| How do you architect anomaly detection over database access that distinguishes a legitimate new analytics workload from an insider exfiltration campaign at scale? | expertise | SDE-2/3, Architect/Principal | Database Security & Access Control | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-anomaly-detection-over-database-access-that-disti-114071) |
