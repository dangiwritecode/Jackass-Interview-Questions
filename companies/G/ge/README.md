# GE

**Tier:** Tier 3  |  **Business domain:** Industrial-IoT  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 0 | 2 | 2 | 3 |
| Fullstack | 1 | 1 | 0 | 1 | 1 | 2 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 3 | 3 | 0 | 3 |
| Data Structures & Algorithms (all profiles) | 3 | 3 | 3 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A machine's output increases by 20 percent each year. If it produces 8640 units after 2 years what did it produce initially? | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-machine-s-output-increases-by-20-percent-each-year-if-it-produces-86-15850) |
| Design a globally-distributed IoT ingestion platform: 50M devices across regions writing telemetry, with each region owning its devices but needing global aggregate queries. Lay out the wide-column topology, regional partitioning, and how you reconcile global rollups. | expertise | SDE-2/3, Architect/Principal | Cassandra/DynamoDB (Wide-Column NoSQL) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-globally-distributed-iot-ingestion-platform-50m-devices-acros-34847) |
| Explain how you'd retrofit cost tagging and allocation onto a legacy estate with 200000 untagged resources across 40 AWS accounts. What's your sequencing, automation, and enforcement plan so you don't spend a year tagging manually? | expertise | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-retrofit-cost-tagging-and-allocation-onto-a-legacy-e-37067) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the architecture for a gateway that must serve both a public-cloud tenant and an air-gapped on-prem tenant from one codebase; how do you keep feature parity, ship config to the disconnected estate, and prevent the cloud-first assumptions from leaking into the air-gapped build? | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-for-a-gateway-that-must-serve-both-a-public-cl-39519) |
| A machine's output increases by 20 percent each year. If it produces 8640 units after 2 years what did it produce initially? | intermediate experience | Fresher, SDE-1 | Aptitude & Logical Reasoning | Online Assessment (OA) | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-machine-s-output-increases-by-20-percent-each-year-if-it-produces-86-15850) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you use Azure Arc to bring governance, policy, and observability to a fleet of on-prem and multi-cloud Kubernetes clusters, and where does that abstraction leak? | expertise | SDE-2/3, Architect/Principal | Azure | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-azure-arc-to-bring-governance-policy-and-observabili-54559) |
| Your Retire disposition depends on someone confirming an app is truly unused; describe how you'd build evidence-based decommissioning at scale without breaking a silent downstream consumer. | deep understanding | SDE-2/3, Architect/Principal | Cloud Migration Strategy (6 Rs) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-retire-disposition-depends-on-someone-confirming-an-app-is-truly--56532) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a time-series data platform on Amazon Timestream (or a self-managed alternative) for high-ingest IoT/telemetry — reason about the memory-store versus magnetic-store tiering, retention policy design, and query-cost model at billions of points/day. | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-time-series-data-platform-on-amazon-timestream--111858) |
| How do you architect the split between a time-series database (InfluxDB/TimescaleDB/Prometheus) and your general lakehouse for a manufacturing sensor estate? Where does downsampling and continuous-aggregate rollup belong, and when do you refuse to store raw high-frequency data in the lake at all? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-split-between-a-time-series-database-influxdb-112684) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A defect-detection model must never miss a critical defect. How would you tune the classification threshold and design the precision/recall trade-off for that business constraint? | deep understanding | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-defect-detection-model-must-never-miss-a-critical-defect-how-would-y-66281) |
| How do you handle intermittent (mostly-zero) demand series like spare parts in a forecasting fleet — what does Croston miss? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-intermittent-mostly-zero-demand-series-like-spare-pa-66399) |
| How would you forecast electricity/energy load with strong temperature dependence and evaluate marginal value of weather features? | deep understanding | SDE-1/2, SDE-2/3 | Time Series Analysis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-forecast-electricity-energy-load-with-strong-temperature-66442) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Cheapest Keystrokes to Program a Countdown Timer | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Enumeration, Greedy, Math, Simulation, String | Online Assessment (OA), DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=cheapest-keystrokes-to-program-a-countdown-timer-d2039) |
| Delete Fewest Parentheses to Make a String Valid | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Greedy, Stack, String | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=delete-fewest-parentheses-to-make-a-string-valid-d1210) |
| Shortest Subarray Preserving the Peak Frequency | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Counting, First/Last Occurrence Tracking, Hash Table | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=shortest-subarray-preserving-the-peak-frequency-d682) |
