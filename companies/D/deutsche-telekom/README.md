# Deutsche Telekom

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 5 | 5 | 5 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your platform serves 30 countries with data-residency laws. How do data-sovereignty constraints reshape the CAP calculus, given you can no longer freely place a majority quorum wherever latency is best? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-platform-serves-30-countries-with-data-residency-laws-how-do-data-32228) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A single etcd and control plane whose loss halts all deploys is a top risk. As principal, how would you architect control-plane resilience (HA quorum sizing, regional isolation, upgrade safety) and prove to leadership that running workloads keep serving user traffic through a full control-plane outage window? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-single-etcd-and-control-plane-whose-loss-halts-all-deploys-is-a-top--39084) |
| You must decide the org's node-image and OS strategy: general-purpose distro versus an immutable, minimal, container-optimized OS (Bottlerocket/Talos/Flatcar). Walk through the security, patch-cadence, and debuggability trade-offs, and how you'd migrate 80 clusters without losing the ability to break-glass onto a node. | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-the-org-s-node-image-and-os-strategy-general-purpose-d-39045) |
| You're deciding the org's CNI strategy fleet-wide including moving thousands of running workloads to eBPF-based networking (kube-proxy replacement, policy engine, observability). As principal, how would you evaluate the migration risk, run it without a fleet-wide network outage, and what would make you decide not to do it at all? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-the-org-s-cni-strategy-fleet-wide-including-moving-tho-39103) |
| You're deciding the org's stance on running the API server and etcd as a managed control plane (control-plane-as-a-service like Kamaji/Hosted Control Planes) to run many lightweight tenant clusters. Walk through the trade-offs versus full clusters, and the failure isolation you gain or lose. | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-the-org-s-stance-on-running-the-api-server-and-etcd-as-39054) |
| You're deciding whether to manage the fleet declaratively with Cluster API (CAPI) or stay on cloud-managed node groups. Walk through the build-vs-buy trade-off for CAPI at 80+ clusters across clouds, the lifecycle guarantees it buys, and the operational tax it adds. | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-whether-to-manage-the-fleet-declaratively-with-cluster-39025) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You are asked to set the governance strategy for a platform that must comply with sovereignty requirements demanding EU-national-only operators and EU-owned infrastructure (e.g. sovereign-cloud mandates) — how do you architect a sovereign enclave without forking your entire operations model? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-asked-to-set-the-governance-strategy-for-a-platform-that-must--54087) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you govern data residency and sovereignty for a global AIOps platform that must detect incidents in-region but present one unified reliability view to leadership? | expertise | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-govern-data-residency-and-sovereignty-for-a-global-aiops-pl-101385) |
| Your platform must scale to sovereign/regional isolation where each geography is a near-independent stack for data-residency and regulatory reasons. As a principal, design how you share tooling and models across sovereign boundaries without violating them, and where the isolation forces genuine duplication. | expertise | SDE-2/3, Architect/Principal | Scalable AI/ML Platform Architecture | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-platform-must-scale-to-sovereign-regional-isolation-where-each-ge-100680) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A GDPR DPIA flags that your read replicas in a third country hold decryptable PII — how do you redesign replication topology to keep decryption capability strictly in-region? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-gdpr-dpia-flags-that-your-read-replicas-in-a-third-country-hold-decr-115264) |
| Your firm is entering the EU and must comply with GDPR data-residency plus Schrems II — architect a database platform where EU personal data keys never leave the EU even during cross-region DR failover. | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-firm-is-entering-the-eu-and-must-comply-with-gdpr-data-residency--115248) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a data-residency-aware training architecture so an EU-only model trains exclusively on EU data in EU regions while a global model trains on a lawfully-aggregated superset — how do you avoid maintaining N forked pipelines per jurisdiction? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-data-residency-aware-training-architecture-so-an-eu-only-mode-69985) |
| Design governance for a model that must comply with data-sovereignty mandates requiring EU-national operators and EU-owned infrastructure (sovereign-cloud) for the whole training-to-serving pipeline — how do you build a sovereign ML enclave without forking all of MLOps? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-governance-for-a-model-that-must-comply-with-data-sovereignty-m-70027) |
| How do you architect a distributed training cluster so that PII in the training data never leaves an in-region compliant boundary even as gradients checkpoints and shuffled shards move across hundreds of GPU workers — where does cross-border leakage sneak in? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-distributed-training-cluster-so-that-pii-in-the-69973) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your strategy for cross-region data residency when a global GenAI product must retrieve region-local knowledge but serve a single conversational experience? | expertise | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-cross-region-data-residency-when-a-global-gen-86745) |
