# SAS

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| AIOps | 0 | 0 | 0 | 9 | 9 | 9 |
| ML Engineer | 0 | 0 | 2 | 4 | 2 | 4 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect handling for a model whose label definition legitimately changed (e.g., fraud criteria updated), platform-wide, without corrupting drift history? | deep understanding | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-handling-for-a-model-whose-label-definition-legit-101227) |
| How do you set the org's position on statistical significance vs effect size for drift thresholds so large-N models don't page on trivially-detectable shifts? | deep understanding | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-the-org-s-position-on-statistical-significance-vs-effec-101198) |
| How would you architect a policy engine that reconciles disagreeing drift signals (PSI vs KS vs performance-estimation) into one verdict, not ad hoc per team? | expertise | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-policy-engine-that-reconciles-disagreeing-dr-101218) |
| How would you architect calibration-drift monitoring as an org default, given calibration can rot while accuracy holds and auto-remediation triggers depend on score thresholds? | expertise | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-calibration-drift-monitoring-as-an-org-default-101169) |
| How would you architect drift monitoring for time-series/forecasting models whose inputs are inherently non-stationary, so expected trend and seasonality don't trigger alerts? | deep understanding | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-drift-monitoring-for-time-series-forecasting-m-101183) |
| How would you govern the boundary between drift monitoring and model risk management for regulated models so the two don't produce contradictory verdicts to auditors? | expertise | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-the-boundary-between-drift-monitoring-and-model-r-101140) |
| How would you set an org policy for the statistical-test toolbox (PSI/KL/JS/Wasserstein/MMD/adversarial) so teams pick correctly by feature type without a central bottleneck approving each choice? | deep understanding | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-an-org-policy-for-the-statistical-test-toolbox-psi-k-101150) |
| When would you standardize sequential detectors (DDM/EDDM/ADWIN/Page-Hinkley/CUSUM) versus distributional tests as the org's drift primitive, and what drives the choice? | deep understanding | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-standardize-sequential-detectors-ddm-eddm-adwin-page-hi-101196) |
| Would you standardize drift-on-raw-features or drift-on-model-attributions (SHAP) as the platform default? Defend the trade-off in cost, interpretability, and blind spots. | deep understanding | SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=would-you-standardize-drift-on-raw-features-or-drift-on-model-attribut-101191) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a bias/fairness-testing and model-validation harness for regulated ML (buy vs build) when a fairness violation is a regulatory fine and off-the-shelf metrics don't map to your protected-attribute definitions? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-bias-fairness-testing-and-model-v-69827) |
| How do you decide build-vs-buy for a model-governance + lineage + audit layer (buy a model-governance product vs build on your registry) when regulators demand model cards, approval trails, and explainability for every deployed model? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-model-governance-lineage-audit-la-69790) |
| How would you reduce the training cost of a Random Forest that uses 2000 deep trees without meaningfully hurting accuracy? | intermediate experience | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-reduce-the-training-cost-of-a-random-forest-that-uses-20-65914) |
| How would you expose a model-explainability endpoint in FastAPI that is heavier than the prediction path, and how do you keep it from starving the primary inference traffic? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-expose-a-model-explainability-endpoint-in-fastapi-that-i-62938) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a bias/fairness-testing harness for LLM outputs in regulated use (buy vs build) when a fairness violation is a regulatory fine and off-the-shelf metrics don't map to your protected-attribute definitions? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-bias-fairness-testing-harness-for-83787) |
| How do you decide build-vs-buy for an AI-governance/model-risk layer (model cards, approval trails, EU AI Act conformity docs) — buy a governance product vs build on your registry — when regulators demand per-deployment audit artifacts? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-an-ai-governance-model-risk-layer-m-83755) |
| How would you set up a mechanism to detect when the population a model scores has drifted so far that its original validation is no longer applicable and re-validation is legally required? | deep understanding | SDE-2/3, Architect/Principal | Model Risk Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-a-mechanism-to-detect-when-the-population-a-model-86131) |
