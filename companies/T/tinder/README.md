# Tinder

**Tier:** Tier 1  |  **Business domain:** Social  |  **Questions:** 8

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 4 | 4 | 4 |
| Data Structures & Algorithms (all profiles) | 3 | 3 | 3 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your DynamoDB table has a celebrity partition (one user is 90% of traffic) and you're getting throttled while overall consumed capacity is low. Explain what's happening and three concrete ways to fix it. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Cassandra/DynamoDB (Wide-Column NoSQL) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-dynamodb-table-has-a-celebrity-partition-one-user-is-90-of-traffi-29440) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a DynamoDB single-table data model for a domain with a dozen access patterns while keeping GSI count bounded — walk me through the write-sharding, GSI-overloading, and sparse-index techniques and where each starts to hurt at scale. | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-dynamodb-single-table-data-model-for-a-domain-w-111848) |
| How do you decide between DynamoDB on-demand and provisioned-with-auto-scaling for a new workload, and how do you continuously reason about the cost-crossover point as traffic patterns mature — what evidence would flip an established table from one mode to the other? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-between-dynamodb-on-demand-and-provisioned-with-auto-111901) |
| How do you diagnose intermittent DynamoDB ProvisionedThroughputExceeded or throttling when average consumed capacity is well below provisioned — walk me through confirming a hot key with CloudWatch Contributor Insights and redesigning the key schema without downtime. | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-diagnose-intermittent-dynamodb-provisionedthroughputexceede-111918) |
| How would you architect the caching tier for a read-heavy DynamoDB workload — compare DAX's write-through/item-cache model against ElastiCache cache-aside, and explain where DAX's consistency window and node-failure behavior bite you. | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-caching-tier-for-a-read-heavy-dynamodb-wor-111855) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Full Line-Width Text Justification | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Simulation, String | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=full-line-width-text-justification-d68) |
| Live Tracker for the K-th Largest Value in a Stream | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Data Stream, Design, Heap (Priority Queue), Sorting | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=live-tracker-for-the-k-th-largest-value-in-a-stream-d688) |
| Running Median of a Number Stream | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Data Stream, Design, Heap (Priority Queue), Sorting, Two Heaps | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=running-median-of-a-number-stream-d295) |
