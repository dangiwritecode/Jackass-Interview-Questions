# Fishtown

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 5 | 7 | 3 | 7 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your dbt project runs 4000 models and warehouse credits scale with every full-refresh. How do you decide the org-wide policy on incremental vs full-refresh materialization, and quantify the credit saving of incrementalizing the top-cost models before touching the long tail? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-dbt-project-runs-4000-models-and-warehouse-credits-scale-with-eve-125318) |
| Walk me through how you'd design incremental materialization in dbt for a huge fact table to avoid full rebuilds. | deep understanding | SDE-1/2, SDE-2/3 | Data Pipeline Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-how-you-d-design-incremental-materialization-in-dbt-fo-122640) |
| What trade-offs did you weigh when choosing between orchestrating transformations in dbt versus in Airflow-managed Spark jobs? | deep understanding | SDE-1/2, SDE-2/3 | Data Pipeline Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-trade-offs-did-you-weigh-when-choosing-between-orchestrating-tran-122576) |
| How would you Dockerize dbt so the same image runs dbt build in CI and in production orchestration, and where do you inject the profiles.yml and warehouse credentials? | intermediate experience | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-dockerize-dbt-so-the-same-image-runs-dbt-build-in-ci-and-120176) |
| An analyst's careless dbt model change rebuilds a full downstream lineage graph incrementally-materialized tables and 10x's the daily warehouse cost overnight. Design the pre-merge cost-preview gate for warehouse workloads — what you can estimate from the compiled SQL and table stats before the query ever runs. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-analyst-s-careless-dbt-model-change-rebuilds-a-full-downstream-line-125922) |
| Your dbt runs are monitored only by 'did dbt run exit 0'. How would you convert dbt's run_results.json and manifest into Prometheus metrics so per-model timing, row counts, and test pass rates become graphable, and what would you emit for a skipped model? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-dbt-runs-are-monitored-only-by-did-dbt-run-exit-0-how-would-you-c-120870) |
| In dbt, how would you build an incremental model that uses a window function only over the newly loaded slice without recomputing historical running totals? | deep understanding | SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-dbt-how-would-you-build-an-incremental-model-that-uses-a-window-fun-123181) |
