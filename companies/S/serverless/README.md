# Serverless

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 2 | 1 | 2 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 6 | 7 | 4 | 7 |
| AIOps | 0 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect cost visibility for a serverless-heavy estate (Lambda, DynamoDB on-demand, API Gateway, Step Functions) where per-invocation costs are tiny but aggregate is huge and hard to attribute? What's uniquely hard versus VM-based cost tracking? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-cost-visibility-for-a-serverless-heavy-estate-lam-37062) |
| Your team runs GraphQL on serverless (Lambda) and cold starts plus per-request DataLoader setup hurt p99. How would you weigh provisioned concurrency, connection reuse, and schema-build caching to fix it? | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-team-runs-graphql-on-serverless-lambda-and-cold-starts-plus-per-r-24088) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Describe a time you had to lead the org's decision on whether to adopt a serverless-first strategy across product teams, knowing it would trade operational simplicity for cold-starts and vendor coupling. How did you decide? | deep understanding | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-a-time-you-had-to-lead-the-org-s-decision-on-whether-to-adopt-40491) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect identity for a serverless-heavy estate with tens of thousands of Lambda functions so that per-function least-privilege is enforced by construction rather than by review discipline? | deep understanding | SDE-2/3, Architect/Principal | Cloud IAM & Access Management | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-identity-for-a-serverless-heavy-estate-with-te-54763) |
| How would you monitor a serverless Lambda backend where the pull model fails? Explain how the OTel Lambda extension exports telemetry and how you separately track cold-start latency. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-monitor-a-serverless-lambda-backend-where-the-pull-model-46889) |
| You need to trace a request that crosses an SQS queue and a Lambda consumer minutes later. How do you propagate context through SQS message attributes and preserve the link? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-trace-a-request-that-crosses-an-sqs-queue-and-a-lambda-con-46842) |
| A Lambda function's p99 is dominated by cold starts under bursty traffic. How do you profile init duration vs execution duration in CloudWatch, and decide between provisioned concurrency, SnapStart, or reducing the deployment package? | deep understanding | SDE-1/2, SDE-2/3 | Performance Tuning & Profiling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-lambda-function-s-p99-is-dominated-by-cold-starts-under-bursty-traff-47037) |
| How would you reduce cold-start time and package size of a Python AWS Lambda that depends on boto3 and a few heavy libraries, and when is a Lambda layer or container image the better choice? | intermediate experience | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-reduce-cold-start-time-and-package-size-of-a-python-aws--45144) |
| Your Python Lambda that processes S3 events occasionally times out and the event gets retried, causing duplicate processing. How do you make the handler idempotent using an S3 object key or a DynamoDB dedup marker? | deep understanding | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-python-lambda-that-processes-s3-events-occasionally-times-out-and-45143) |
| Your Lambda-backed API throttles downstream because reserved concurrency wasn't set and one function starved the account pool. How would you isolate functions so one can't exhaust the rest? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-lambda-backed-api-throttles-downstream-because-reserved-concurren-45567) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're asked to map dependencies for a serverless (Lambda/Functions) architecture. Why is traditional discovery harder here and what do you rely on instead? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Topology & Dependency Mapping | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-map-dependencies-for-a-serverless-lambda-functions-arc-97654) |
