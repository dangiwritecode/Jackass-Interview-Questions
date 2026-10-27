# DuckDB

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 5 | 0 | 6 | 11 | 5 | 11 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design the security architecture for an in-browser SQL sandbox feature (users run SQL against their own data in the browser via WASM SQLite)? Where does the injection threat model change when the DB is client-side, and what server-side data can still leak? | expertise | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-the-security-architecture-for-an-in-browser-sql-s-39005) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for the data-warehouse compute layer specifically, decoupled from storage — buy Snowflake/BigQuery compute vs run Trino/DuckDB/Spark yourself over open Iceberg storage — and where does the compute-only crossover sit once storage is already open and portable? | expertise | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-data-warehouse-compute-layer-sp-125856) |
| How do you decide build-vs-buy for the query engine over your lakehouse — Trino/Presto self-run vs Athena/Starburst-managed vs Snowflake external tables vs DuckDB — when interactive concurrency, cost-per-query, and connector breadth pull in different directions across analyst and pipeline workloads? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-the-query-engine-over-your-lakehous-125839) |
| Can you query a Parquet file directly with SQL and what tools let you do that? | basic concept | Fresher, SDE-1/2, SDE-2/3 | Columnar File Formats (Parquet/ORC/Avro) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=can-you-query-a-parquet-file-directly-with-sql-and-what-tools-let-you--119218) |
| What tools can you use to view the contents of a Parquet file quickly? | basic concept | Fresher, SDE-1/2, SDE-2/3 | Columnar File Formats (Parquet/ORC/Avro) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-tools-can-you-use-to-view-the-contents-of-a-parquet-file-quickly-119254) |
| You're driving a decision where a benchmark says a new query engine is faster but production tail-latency and concurrency data say it degrades under real BI load, and reasonable engineers disagree on adopting it. How do you make a defensible call, document the reasoning, and set a review trigger to course-correct? | expertise | SDE-2/3, Architect/Principal | Cross-team Technical Leadership & Influence | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-driving-a-decision-where-a-benchmark-says-a-new-query-engine-is-126179) |
| What's your strategy for handling 'shadow data platforms' — teams spinning up their own BigQuery/DuckDB because central platform is too slow — do you absorb, ban, or federate them? | deep understanding | SDE-2/3, Architect/Principal | Data Platform Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-handling-shadow-data-platforms-teams-spinning-126461) |
| How would you decide the right --shm-size for a containerized Spark or DuckDB workload that uses shared memory, and how do you detect that /dev/shm exhaustion causes intermittent crashes? | deep understanding | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-the-right-shm-size-for-a-containerized-spark-or-d-120243) |
| How would a GitHub Actions job spin up a throwaway Postgres or DuckDB container and run your dbt models to verify they build cleanly on every PR? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-a-github-actions-job-spin-up-a-throwaway-postgres-or-duckdb--116088) |
| What entries would you add to a .gitignore in a Python data-engineering repo that uses a local DuckDB file, a .env for warehouse credentials, and generated Parquet outputs? | basic concept | Fresher, SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-entries-would-you-add-to-a-gitignore-in-a-python-data-engineering-116045) |
| Why is it a bad idea to commit a large local Parquet output or a DuckDB database file, and how would DVC or Git LFS help if you truly must track a sample? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-is-it-a-bad-idea-to-commit-a-large-local-parquet-output-or-a-duckd-116132) |
| You keep getting pitched streaming lakehouses, embedded OLAP engines, and vector-plus-relational hybrids, and being early can be an edge or a scar. Tell me about a time you jumped early and it paid off, and one where you should have waited — what was different about the signal you read, and what rule did you take away for the next frontier bet? | expertise | SDE-2/3, Architect/Principal | Technical Strategy & Roadmapping | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-keep-getting-pitched-streaming-lakehouses-embedded-olap-engines-an-125582) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| When would you choose an embedded/edge database (SQLite/RocksDB/DuckDB) as part of the architecture, and how does that change the central datastore selection? | deep understanding | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-an-embedded-edge-database-sqlite-rocksdb-duckdb--114381) |
| How would you evaluate whether to adopt an embedded analytics database like DuckDB for local processing versus a centralized warehouse? | deep understanding | SDE-2/3, Architect/Principal | Database Vendor & Tooling Strategy | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evaluate-whether-to-adopt-an-embedded-analytics-database-115432) |
