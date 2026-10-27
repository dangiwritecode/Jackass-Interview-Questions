# Logz.io

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 1 | 1 | 1 |
| AIOps | 0 | 0 | 5 | 5 | 3 | 5 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your company forked OpenSearch off Elasticsearch after the license change. Three years later you're carrying significant maintenance burden. Walk me through how you'd reassess: stay forked, migrate back to Elastic, or move to a managed service, and how you'd de-risk each path. | expertise | SDE-2/3, Architect/Principal | Elasticsearch & Search Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-company-forked-opensearch-off-elasticsearch-after-the-license-cha-34914) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A dedup rule in your log pipeline keys on the exact message string, but a stack trace with varying line numbers explodes cardinality. How would you normalize/template Linux log lines (regex, drain-style) before dedup on the collector? | deep understanding | SDE-1/2, SDE-2/3 | Linux | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-dedup-rule-in-your-log-pipeline-keys-on-the-exact-message-string-but-92232) |
| Explain how you'd measure the end-to-end lag between a log line being written on a Linux host and it becoming queryable in your backend, and where you'd add timestamps to attribute the delay to the agent, network, or index. | deep understanding | SDE-1/2, SDE-2/3 | Linux | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-measure-the-end-to-end-lag-between-a-log-line-being--92265) |
| How do you monitor a model that scores log lines for anomalies at millions of lines per minute without making drift computation a bottleneck? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-monitor-a-model-that-scores-log-lines-for-anomalies-at-mill-95376) |
| How would you monitor for training-serving skew where log features are enriched with GeoIP/asset data offline but that enrichment lags in the live path? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-monitor-for-training-serving-skew-where-log-features-are-95409) |
| Your log-parsing model that extracts templates from unstructured logs is missing new patterns. How do you monitor its coverage drift in production? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-log-parsing-model-that-extracts-templates-from-unstructured-logs--95342) |
