# Kimball Group

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 7 | 9 | 2 | 9 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide whether to model conformed dimensions once in Silver and share, versus letting each Gold mart build its own? What's the coupling trade-off? | deep understanding | SDE-2/3, Architect/Principal | Medallion Architecture (Bronze/Silver/Gold) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-model-conformed-dimensions-once-in-silver-126305) |
| How do you manage SCD Type 2 history across Silver and Gold so that point-in-time restatements are consistent and auditable years later? | deep understanding | SDE-2/3, Architect/Principal | Medallion Architecture (Bronze/Silver/Gold) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-manage-scd-type-2-history-across-silver-and-gold-so-that-po-126233) |
| Explain a factless fact table and give a warehouse case (e.g. student-course enrollment or promotion coverage) where you'd model events with no measures, and how you query coverage gaps. | intermediate experience | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-a-factless-fact-table-and-give-a-warehouse-case-e-g-student-co-119401) |
| Explain how you'd build a bridge/junction table to resolve a many-to-many between accounts and products in a warehouse, and how an allocation factor prevents double-counting revenue across the many side. | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-build-a-bridge-junction-table-to-resolve-a-many-to-m-119460) |
| Explain how you'd generate and use a date/calendar dimension with fiscal-quarter and holiday flags, and why joining facts to a calendar table beats computing fiscal periods inline on every query. | intermediate experience | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-generate-and-use-a-date-calendar-dimension-with-fisc-119462) |
| How would you implement a late-arriving-dimension pattern where a fact row references a dimension member that hasn't loaded yet? Compare inferred-member insertion versus deferred re-processing. | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-a-late-arriving-dimension-pattern-where-a-fact-119400) |
| How would you implement a Type-6 hybrid SCD (current + historical attributes on the same row) and query it, and why do reporting teams sometimes prefer it over pure Type-2? | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-a-type-6-hybrid-scd-current-historical-attribu-119414) |
| How would you write a query to find the effective Type-2 dimension row for each fact using a range containment join on valid_from/valid_to, and why can an open-ended NULL valid_to break the BETWEEN? | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-write-a-query-to-find-the-effective-type-2-dimension-row-119463) |
| Your fact-to-dimension SUM double-counts because the dimension is Type-2 and matches multiple versions per fact. How would you constrain the join to the version effective at the fact's event date? | deep understanding | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-fact-to-dimension-sum-double-counts-because-the-dimension-is-type-119412) |
