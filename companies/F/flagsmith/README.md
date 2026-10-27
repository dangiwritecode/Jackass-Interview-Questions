# Flagsmith

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 4 | 1 | 4 |
| DevOps | 0 | 0 | 2 | 5 | 4 | 5 |
| AIOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 1 | 0 | 1 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're asked to design a global feature-flag/config plane that must be available on every request path yet must not let a bad flag persist after a partition heals. What's the architecture, and what's the exact CAP trade you accept on the write path? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-design-a-global-feature-flag-config-plane-that-must-be-32274) |
| A flag defaults to false in code but the SDK returns the control-plane default of true when config loads — during the cold-start window some requests get false, then true, causing a mixed rollout for a few seconds after each deploy; how do you eliminate this defaults-drift race? | deep understanding | SDE-1/2, SDE-2/3 | Feature Flags & Progressive Rollouts | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-flag-defaults-to-false-in-code-but-the-sdk-returns-the-control-plane-30477) |
| How would you structure a flag SDK so evaluation is fully in-process (no network on the request path) yet still gets rule updates within seconds — what does the control plane push, and how big can the payload get before you need deltas? | deep understanding | SDE-1/2, SDE-2/3 | Feature Flags & Progressive Rollouts | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-structure-a-flag-sdk-so-evaluation-is-fully-in-process-n-30456) |
| You're migrating off an expensive flag vendor to a self-hosted OpenFeature-based setup with hundreds of live flags across many services — design the zero-downtime cutover: dual-provider shim, per-flag migration, and parity verification. | expertise | SDE-1/2, SDE-2/3 | Feature Flags & Progressive Rollouts | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-migrating-off-an-expensive-flag-vendor-to-a-self-hosted-openfea-30532) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a globally-consistent feature-flag and dynamic-config system that propagates within seconds worldwide without redeploys — compare AppConfig with validators and gradual rollout against a DynamoDB-poll model on consistency-versus-blast-radius? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-globally-consistent-feature-flag-and-dynamic-52371) |
| How would you architect a progressive-delivery platform that gates promotion on shared SLO burn-rate signals uniformly across a CloudFront frontend, ECS backends, and Lambda functions — so every team gets automated canary analysis and rollback without reinventing it? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-progressive-delivery-platform-that-gates-pro-52343) |
| How do you handle feature flags in an air-gapped or on-prem deployment where you can't reach a SaaS flag vendor — what self-hosted approach keeps ramp control and kill switches? | deep understanding | SDE-1/2, SDE-2/3 | Feature Flags & Progressive Rollouts | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-feature-flags-in-an-air-gapped-or-on-prem-deployment-47412) |
| How would you build feature flags into the platform as a golden-path capability so teams get safe rollout and kill-switches by default? What's the failure mode if the flag service is down? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Platform Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-feature-flags-into-the-platform-as-a-golden-path-c-48201) |
| How do you handle the debt of a shared feature-flag / config service that has thousands of stale flags across every deploy that nobody dares remove because the blast radius is unknown? Design the cleanup and the guardrails so it doesn't re-accumulate. | deep understanding | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-the-debt-of-a-shared-feature-flag-config-service-tha-54414) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd govern feature-flag and progressive-delivery telemetry across clouds so your AIOps can auto-halt a bad rollout before it becomes a full incident. Who authorizes the auto-halt? | expertise | SDE-2/3, Architect/Principal | Multi-Cloud Governance Frameworks | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-feature-flag-and-progressive-delivery-telemet-100852) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle read/write splitting for feature flags or config data that is read on nearly every request but written rarely, where lag on a flag flip matters? | deep understanding | SDE-2/3, Architect/Principal | Read/Write Splitting | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-read-write-splitting-for-feature-flags-or-config-dat-115521) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect blue/green or canary rollout for a change that spans model version, system prompt, and multiple tool schemas at once, so you can attribute a regression to the right variable. How do you avoid confounding when everything moved together? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-blue-green-or-canary-rollout-for-a-change-that-spans-model-v-83074) |
| What is a feature flag and how could it help you roll out a new LLM model to only some users first? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-feature-flag-and-how-could-it-help-you-roll-out-a-new-llm-mo-76526) |
