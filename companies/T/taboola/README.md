# Taboola

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 2 | 1 | 2 |
| ML Engineer | 0 | 0 | 9 | 9 | 2 | 9 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design multi-region for a low-latency real-time bidding / ad-serving system where a 50ms cross-region hop kills the business. How do you get correctness and freshness without paying that latency? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-multi-region-for-a-low-latency-real-time-bidding-ad-serving-sys-36701) |
| You need to atomically reserve budget from a shared pool across many ad-serving nodes so you never overspend a campaign — design the Redis operation and the reconciliation. | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-atomically-reserve-budget-from-a-shared-pool-across-many-a-24690) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how a bandit approach differs from a fixed A/B test for model rollout and when you'd prefer each. | deep understanding | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-a-bandit-approach-differs-from-a-fixed-a-b-test-for-model--67689) |
| Explain how you'd measure the business impact of a model that improves an intermediate metric (e.g., click prediction) but the goal is downstream revenue. | deep understanding | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-measure-the-business-impact-of-a-model-that-improves-67698) |
| How would you design an experiment to compare online-learning updates versus periodic batch retraining for the same model? | deep understanding | SDE-1/2, SDE-2/3 | A/B Testing & Experimentation | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-experiment-to-compare-online-learning-updates--67759) |
| How do you decide the max_depth and num_boost_round budget for XGBoost when serving cost scales roughly with tree count and depth? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-max-depth-and-num-boost-round-budget-for-xgboost-65919) |
| How do you handle categorical features with thousands of levels in XGBoost without blowing up memory or leaking target information? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-categorical-features-with-thousands-of-levels-in-xgb-65883) |
| What's the trade-off between DART booster and standard gbtree in XGBoost, and when would production constraints push you to pick one? | expertise | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-the-trade-off-between-dart-booster-and-standard-gbtree-in-xgboo-65945) |
| How would you build a FastAPI service that supports online learning, applying incremental model updates from streamed feedback without downtime? | expertise | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-fastapi-service-that-supports-online-learning-ap-62950) |
| Walk me through designing a real-time bidding predictor that must return a bid within a few milliseconds under strict budget constraints. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-designing-a-real-time-bidding-predictor-that-must-retu-66721) |
| Your CTR model's offline AUC improved but online CTR dropped after launch; how do you debug this offline-online disagreement? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-ctr-model-s-offline-auc-improved-but-online-ctr-dropped-after-lau-66677) |
