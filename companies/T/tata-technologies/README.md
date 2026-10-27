# Tata Technologies

**Tier:** Tier 4  |  **Business domain:** Engineering-Services  |  **Questions:** 24

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 3 | 3 | 3 |
| Fullstack | 0 | 0 | 1 | 5 | 5 | 5 |
| DevOps | 1 | 0 | 1 | 7 | 6 | 7 |
| AIOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 3 | 0 | 3 | 3 | 0 | 3 |
| ML Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You need to move 50TB from on-prem to S3 within a week — walk me through evaluating Snowball, DataSync, and Transfer Acceleration and the bandwidth/cost math behind the choice. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-move-50tb-from-on-prem-to-s3-within-a-week-walk-me-through-19763) |
| Compare a hub-and-spoke warehouse topology (central + domain marts) vs a full mesh vs a single monolithic warehouse for a 10-BU conglomerate. Which fits which org shape, and how do you evolve between them? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-a-hub-and-spoke-warehouse-topology-central-domain-marts-vs-a-f-36593) |
| Your org spans 4 business lines that each think they own the 'core domain.' As chief architect, how do you facilitate a domain-vision workshop to agree on the true core, and what do you do when leadership can't agree? | expertise | SDE-2/3, Architect/Principal | Domain-Driven Design (DDD) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-spans-4-business-lines-that-each-think-they-own-the-core-doma-34351) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the gateway architecture for a multi-brand company where one platform serves several consumer brands on separate domains with separate auth, theming of error contracts, and isolation, but shares the backend fleet; how do you keep brand isolation without duplicating the whole edge? | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-gateway-architecture-for-a-multi-brand-company-where-one-pl-39603) |
| Design the gateway architecture for a super-app where one login must fan out to 40 product APIs owned by 40 teams; how do you prevent a slow or failing product from degrading the app shell, and how do you allocate the shared latency budget across independently-deployed teams? | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-gateway-architecture-for-a-super-app-where-one-login-must-f-39554) |
| How do you architect the gateway so a new acquisition's APIs can be exposed under your brand's domain within a week (proxy + rewrite + auth-bridge) while a proper long-term integration happens over quarters; what technical debt does the fast path create and how do you schedule paying it down? | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-gateway-so-a-new-acquisition-s-apis-can-be-ex-39548) |
| You're setting a 3-year plan to make the gateway multi-protocol (REST, gRPC, GraphQL, WebSocket, MQTT for IoT); how do you decide whether one gateway spans all protocols or you run protocol-specialized planes, and what does that mean for the shared control plane and policy engine? | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-setting-a-3-year-plan-to-make-the-gateway-multi-protocol-rest-g-39527) |
| You need to move 50TB from on-prem to S3 within a week — walk me through evaluating Snowball, DataSync, and Transfer Acceleration and the bandwidth/cost math behind the choice. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-move-50tb-from-on-prem-to-s3-within-a-week-walk-me-through-19763) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a config-management / fleet-provisioning tool for VMs and hybrid nodes (Ansible/Chef/Puppet self-run vs managed vs immutable-image-only) when config drift across thousands of hosts is your reliability tax? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-config-management-fleet-provision-53774) |
| How do you decide build-vs-buy for a hybrid/on-prem control plane when one large regulated customer demands self-hosted deployment but the rest run in your cloud — does the deployment-topology split justify building for portability across the board? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-hybrid-on-prem-control-plane-when-53795) |
| How do you decide build-vs-buy for a secrets-and-config distribution to edge/IoT/on-prem agents where you cannot assume vendor connectivity — does the disconnected-operation constraint force a build regardless of vendor quality? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-secrets-and-config-distribution-t-53754) |
| How do you plan capacity for a workload with extreme write bursts followed by long idle periods (e.g. IoT sensors reporting on schedule)? How do you avoid provisioning for the burst peak while meeting ingest guarantees, and where does buffering pay off? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-capacity-for-a-workload-with-extreme-write-bursts-foll-53004) |
| Why might a DevOps engineer host an internal Git server (like GitLab or Gitea) instead of relying solely on public GitHub? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-a-devops-engineer-host-an-internal-git-server-like-gitlab-or-42024) |
| How do you decide what state and logic must run at the edge versus centrally in cloud for a hybrid architecture spanning intermittent-connectivity sites? | deep understanding | SDE-2/3, Architect/Principal | Multi-Cloud & Hybrid Cloud | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-what-state-and-logic-must-run-at-the-edge-versus-cen-55299) |
| How would you architect a hybrid edge-to-cloud topology (retail stores / factories) where thousands of edge sites must stay operational during a cloud disconnect? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud & Hybrid Cloud | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-hybrid-edge-to-cloud-topology-retail-stores--55298) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Contrast a hub-and-spoke observability architecture (central data lake all telemetry flows into) with a decentralized observability mesh for a conglomerate with 15 regional units. Under what org and failure-domain conditions does hub-and-spoke actually win despite the central bottleneck critique? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-a-hub-and-spoke-observability-architecture-central-data-lake--99731) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you describe the difference between 'processing an order' and 'analyzing all orders' to explain OLTP vs OLAP? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-describe-the-difference-between-processing-an-order-and-ana-118789) |
| If a business asks 'which product sold best last quarter', why do you not query the live product-catalog OLTP table for the answer? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=if-a-business-asks-which-product-sold-best-last-quarter-why-do-you-not-118832) |
| What does 'aggregation' mean and why is it far more common in OLAP than OLTP? | basic concept | Fresher, SDE-1/2, SDE-2/3 | OLTP vs OLAP | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-does-aggregation-mean-and-why-is-it-far-more-common-in-olap-than--118778) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you reconcile the AI roadmap with an org that has multiple P&Ls, each wanting AI investment prioritized for their own outcomes? | deep understanding | SDE-2/3, Architect/Principal | AI Strategy & Roadmap | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reconcile-the-ai-roadmap-with-an-org-that-has-multiple-p-an-71659) |
| How would you approach setting the strategy and roadmap for AI in a joint venture or coalition where governance and data are shared across companies? | expertise | SDE-2/3, Architect/Principal | AI Strategy & Roadmap | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-setting-the-strategy-and-roadmap-for-ai-in-a-jo-71664) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you build a strategy that keeps the AI roadmap coherent when different business units are at wildly different AI maturity levels? | deep understanding | SDE-2/3, Architect/Principal | AI Strategy & Roadmap | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-strategy-that-keeps-the-ai-roadmap-coherent-when-85992) |
| How would you plan capacity for an Indian-market AI product where GPU availability and data-residency laws push you to local providers? | expertise | SDE-2/3, Architect/Principal | GPU Fleet & Capacity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-plan-capacity-for-an-indian-market-ai-product-where-gpu--86697) |
| Argue whether the org should own its embedding space (train/host its own encoder) purely to avoid the strategic risk that a third-party provider can invalidate a billion-vector index with a silent model change. What tips build-your-own? | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=argue-whether-the-org-should-own-its-embedding-space-train-host-its-ow-82937) |
