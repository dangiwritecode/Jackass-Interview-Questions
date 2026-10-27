# StormForge

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| AIOps | 0 | 0 | 6 | 6 | 6 | 6 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd design the org's approach to 'right-sizing at rollout' versus 'right-sizing continuously'. Continuous automated resizing saves more but erodes trust and can destabilize prod. Where do you land the policy and what safety envelope do you enforce? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-the-org-s-approach-to-right-sizing-at-rollout-52969) |
| Your org is deciding whether to invest in an internal autoscaling/bin-packing platform or adopt a commercial one (Karpenter-based product, Cast AI, etc.). Walk me through the build-vs-buy analysis at fleet scale — where the vendor's economics and your control needs collide. | expertise | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-is-deciding-whether-to-invest-in-an-internal-autoscaling-bin--53007) |
| Your right-sizing program stalled because one automated VPA resize caused an incident and teams revoked trust. How would you rebuild a safe continuous right-sizing loop with in-place resize, staged recommendations, and a quota-price incentive, and win back the credibility to run it unattended? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-right-sizing-program-stalled-because-one-automated-vpa-resize-cau-52161) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd build a remediation that automatically increases a Deployment's memory limit when your detector confirms repeated OOMKills, while capping the total and requiring approval past a threshold to avoid runaway cost. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-build-a-remediation-that-automatically-increases-a-d-92512) |
| You built a model that predicts OOMKills 10 minutes ahead from working-set-bytes trends. How would you close the loop to auto-adjust memory requests via VPA recommendations, and why must you not let it fight the HPA? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-built-a-model-that-predicts-oomkills-10-minutes-ahead-from-working-92438) |
| You feed HPA scaling events into an anomaly model to catch autoscaler misbehavior. What does a healthy scale pattern look like versus flapping, and which HPA metrics (desiredReplicas vs currentReplicas oscillation) reveal instability? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-feed-hpa-scaling-events-into-an-anomaly-model-to-catch-autoscaler--92471) |
| You want a model to distinguish a real traffic-driven scale-up from a runaway crash-and-restart loop that inflates request counts. What features from HPA events and Pod lifecycle would separate these two patterns? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-a-model-to-distinguish-a-real-traffic-driven-scale-up-from-a--92453) |
| You want an operator to auto-tune HPA target utilization based on observed latency-vs-utilization curves. How would you close this loop safely, and what prevents it from oscillating with the HPA it's tuning? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-an-operator-to-auto-tune-hpa-target-utilization-based-on-obse-92505) |
| You want to predict node-level saturation to pre-scale the cluster autoscaler ahead of a known 9am spike. What historical signals would you forecast on, and why is reactive cluster-autoscaling too slow for cold-start-sensitive workloads? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-predict-node-level-saturation-to-pre-scale-the-cluster-aut-92508) |
