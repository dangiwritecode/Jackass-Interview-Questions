# Nirmata

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 1 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 4 | 10 | 9 | 10 |
| AI Engineer | 0 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What is OPA Gatekeeper or Kyverno, and how would you use it to enforce that all Pods have resource limits? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-opa-gatekeeper-or-kyverno-and-how-would-you-use-it-to-enforce--14408) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the org's compliance-and-cost policy-as-code strategy enforced at admission uniformly across the fleet (resource limits, non-root, pinned digests, labels for chargeback). As principal, how would you compare owning Gatekeeper versus Kyverno versus in-tree CEL policies at org scale, and how would you roll out a new policy without breaking existing workloads? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-org-s-compliance-and-cost-policy-as-code-strategy-enforced--39116) |
| You're evaluating ValidatingAdmissionPolicy (CEL-based, in-tree) to replace external policy webhooks for a class of guardrails. How would you decide what moves to in-tree CEL versus stays on Gatekeeper/Kyverno, and what does removing the webhook hop buy you in reliability and latency at fleet scale? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-evaluating-validatingadmissionpolicy-cel-based-in-tree-to-repla-39057) |
| Your fleet's admission-webhook layer (policy, mutation, injection) has grown to add tens of milliseconds to every object create and is now on the critical path for scheduling latency. As principal, how would you architect the policy layer for performance, ordering, and failure isolation so it's fast and can never brick creates? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-fleet-s-admission-webhook-layer-policy-mutation-injection-has-gro-39056) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A scenario tests whether the platform can enforce that every workload has resource requests/limits and a PodDisruptionBudget. During analysis you find enforcement is advisory, not blocking. How significant is this finding and how do you drive it to closure? | intermediate experience | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-scenario-tests-whether-the-platform-can-enforce-that-every-workload--53305) |
| How do you encode a subset of ATAM sensitivity points as automated fitness functions (e.g. an OPA rule or a Conftest check) so the platform stays continuously evaluated between formal reviews? Which findings translate cleanly and which resist automation? | deep understanding | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-encode-a-subset-of-atam-sensitivity-points-as-automated-fit-53265) |
| How do you use ATAM to decide whether to adopt a platform-wide policy engine (OPA/Gatekeeper or Kyverno) versus embedding controls in CI? Which scenarios expose whether admission-time enforcement buys real security-vs-developer-friction gains? | deep understanding | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-use-atam-to-decide-whether-to-adopt-a-platform-wide-policy--53253) |
| A validating webhook you deployed started blocking all pod creation when its own pod went down. How does failurePolicy cause this, and how would you design webhooks so they can't brick scheduling? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-validating-webhook-you-deployed-started-blocking-all-pod-creation-wh-45981) |
| You're asked to enforce that no Deployment can ship without CPU/memory requests. How would you weigh a Kyverno policy versus a CI lint gate, and what does each miss that the other catches? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-enforce-that-no-deployment-can-ship-without-cpu-memory-45947) |
| You're deciding whether to move a class of security guardrails from Kyverno webhooks to in-tree ValidatingAdmissionPolicy CEL. How would you decide which policies are worth the webhook-hop removal, and how do you keep two policy engines from silently disagreeing during the transition? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-whether-to-move-a-class-of-security-guardrails-from-ky-52142) |
| How do you govern Kubernetes admission control fleet-wide (Kyverno/Gatekeeper) while letting each team's namespace have legitimately different needs? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Governance Frameworks | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-govern-kubernetes-admission-control-fleet-wide-kyverno-gate-55983) |
| How do you build a policy-as-code framework (OPA/Kyverno) that expresses NIST controls as enforceable gates without creating so much friction that teams route around it? | expertise | SDE-2/3, Architect/Principal | Regulatory Compliance Architecture (HIPAA/FedRAMP) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-build-a-policy-as-code-framework-opa-kyverno-that-expresses-56748) |
| Explain how you'd enforce that no pod runs as root or with privileged capabilities across the cluster. Compare Pod Security Admission with a policy engine like Kyverno or OPA Gatekeeper, and when the built-in standard isn't enough. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-enforce-that-no-pod-runs-as-root-or-with-privileged--47838) |
| An OPA/Gatekeeper or Kyverno policy is failing your Deployment YAML for a label you swear is present. How do you debug whether the policy reads the field path differently than you expect? | deep understanding | SDE-1/2, SDE-2/3 | YAML | Online Assessment (OA), Phone Screen | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-opa-gatekeeper-or-kyverno-policy-is-failing-your-deployment-yaml-fo-48957) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you enforce, at admission time, that every model-serving Deployment declares GPU limits, a non-root user, and a pinned image digest? Compare doing this with Kyverno versus a ValidatingAdmissionPolicy. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-enforce-at-admission-time-that-every-model-serving-deplo-77567) |
