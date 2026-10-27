# Temporal Technologies — Data Engineer

[← back to Temporal Technologies](README.md)

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A retried orchestration step re-ran an expensive Spark job that had already succeeded because the success signal was lost. Explain how you'd make the trigger idempotent with a run-id and dedup so an at-least-once orchestrator can't double-launch. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-retried-orchestration-step-re-ran-an-expensive-spark-job-that-had-al-120839) |
| Explain how you'd design a distributed job scheduler that runs each pipeline exactly once at its scheduled time across a fleet tolerating a worker crash without duplicate or missed runs. What leader election and lease do you use? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-distributed-job-scheduler-that-runs-each-pi-120838) |
| Explain how you'd use a distributed lock or lease so exactly one worker runs a nightly compaction on a shared table even if the holder GC-pauses. Why is a lease with a fencing token safer than a plain lock here? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-use-a-distributed-lock-or-lease-so-exactly-one-worke-120840) |
