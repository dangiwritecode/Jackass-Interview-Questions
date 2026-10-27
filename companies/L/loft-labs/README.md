# Loft-Labs

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 17

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 2 | 12 | 12 | 12 |
| AIOps | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must build a preview-environment-per-pull-request platform for hundreds of engineers on Kubernetes. As principal, how would you architect it for cost, isolation, fast spin-up, ephemeral secrets, and automatic teardown so it stays cheap and doesn't leave thousands of orphaned namespaces, and how would you measure whether it improved DX? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-build-a-preview-environment-per-pull-request-platform-for-hun-39113) |
| You must decide the org's stance on virtual clusters (vCluster) for tenant isolation versus namespaces versus real clusters. How would you map tenant classes to isolation models, what does vCluster genuinely buy for control-plane isolation, and where does its shared-node reality leak? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-the-org-s-stance-on-virtual-clusters-vcluster-for-tena-39029) |
| You're deciding the org's stance on running the API server and etcd as a managed control plane (control-plane-as-a-service like Kamaji/Hosted Control Planes) to run many lightweight tenant clusters. Walk through the trade-offs versus full clusters, and the failure isolation you gain or lose. | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-the-org-s-stance-on-running-the-api-server-and-etcd-as-39054) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A tradeoff point sits between namespace-based soft multi-tenancy (cheap, dense) and cluster-per-tenant hard isolation (blast-radius containment, noisy-neighbor immunity). How do you scenario-test both against a container-escape security scenario and a resource-contention scenario? | expertise | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-tradeoff-point-sits-between-namespace-based-soft-multi-tenancy-cheap-53252) |
| How do you decide build-vs-buy for a Kubernetes multi-tenancy + namespace-as-a-service isolation layer (buy a K8s platform with hard tenancy vs vcluster/Capsule/Kiosk + bespoke) when one bad tenant can starve a shared cluster? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-kubernetes-multi-tenancy-namespac-53758) |
| How do you decide build-vs-buy for a platform's tenant-isolation + resource-quota + fair-share layer when a bought K8s platform bundles it but a build lets you tune the exact noisy-neighbor controls your workloads need — where does fit override convenience? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-platform-s-tenant-isolation-resou-53806) |
| Your org standardized on Kubernetes but a large fraction of clusters run at low utilization due to per-cluster control-plane and system-daemon overhead. How would you drive cluster consolidation — fewer bigger clusters vs many small — from a cost and blast-radius view? | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-standardized-on-kubernetes-but-a-large-fraction-of-clusters-r-52975) |
| Architect the enterprise pattern for multi-tenancy isolation in a shared platform cluster (namespace vs vCluster vs dedicated-node vs separate-cluster per tenant). How do you offer isolation tiers by criticality without maintaining N separate architectures? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-the-enterprise-pattern-for-multi-tenancy-isolation-in-a-shar-53458) |
| How do you architect cost attribution for FinOps in a Kubernetes multi-tenancy model based on virtual clusters (vCluster) or hierarchical namespaces, where the control-plane overhead is shared but tenants believe they have a whole cluster? Split the shared control-plane cost fairly. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-cost-attribution-for-finops-in-a-kubernetes-multi-53831) |
| Explain how you'd add a self-service 'request a new environment' flow in Backstage that provisions a namespace with quotas and RBAC. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Internal Developer Platform (Backstage) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-add-a-self-service-request-a-new-environment-flow-in-51774) |
| A hosted-control-plane model (Kamaji/vcluster-style) would let you run hundreds of cheap tenant clusters sharing physical nodes. How would you decide which tenants get a real control plane versus a hosted one, and where does the shared-node reality break the isolation promise you sold to security? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-hosted-control-plane-model-kamaji-vcluster-style-would-let-you-run-h-52138) |
| You're deciding the org's stance on virtual clusters (vCluster) versus namespaces versus real clusters for tenant isolation. How would you map tenant classes to isolation models, what does vCluster genuinely buy for control-plane isolation, and where does its shared-node reality leak in a way you'd have to disclose? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-the-org-s-stance-on-virtual-clusters-vcluster-versus-n-52204) |
| Explain how you'd design multi-tenancy on a shared Kubernetes cluster so one noisy team can't starve others. Compare namespace isolation, virtual clusters, and separate clusters. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Platform Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-multi-tenancy-on-a-shared-kubernetes-cluster--48167) |
| How do you decide the platform's stance on Kubernetes cluster topology — many small single-tenant clusters, few large multi-tenant ones, or virtual clusters — as the org scales past a thousand teams? Walk through the operational-cost inflection points. | expertise | SDE-2/3, Architect/Principal | Platform Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-platform-s-stance-on-kubernetes-cluster-topology-54249) |
| Your org runs a service mesh and is adopting Kubernetes multi-tenancy via vClusters/hierarchical namespaces. Architect how mesh identity, policy, and telemetry stay coherent across virtual-cluster boundaries, and the isolation guarantees that hold vs those that only appear to. | deep understanding | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-runs-a-service-mesh-and-is-adopting-kubernetes-multi-tenancy--52653) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect the org's approach to Kubernetes multi-tenancy for the AIOps workloads, deciding between namespace isolation, virtual clusters, and dedicated clusters, given noisy-neighbor and blast-radius concerns? | deep understanding | SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-org-s-approach-to-kubernetes-multi-tenancy-98894) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must decide the tenancy model for the org's AI platform: shared multi-tenant cluster with namespaces, virtual clusters per team, or dedicated clusters for regulated GenAI workloads. Map tenant classes to isolation models and justify against GPU-cost efficiency and blast-radius for a compromised agent. | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-the-tenancy-model-for-the-org-s-ai-platform-shared-mul-82575) |
