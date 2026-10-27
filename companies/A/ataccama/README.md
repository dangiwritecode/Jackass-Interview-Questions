# Ataccama

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 10

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 0 | 10 | 10 | 10 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the audit and lineage layer for MDM so that for any golden attribute you can answer 'which source, which rule, which steward, at what time set this value' — how much history do you keep and why? | expertise | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-audit-and-lineage-layer-for-mdm-so-that-for-any-golden-attr-127742) |
| How do you avoid the classic MDM anti-pattern where the hub becomes a giant EAV / catch-all schema that no consumer can query performantly — what modeling discipline do you enforce? | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-avoid-the-classic-mdm-anti-pattern-where-the-hub-becomes-a--127784) |
| How do you decide between attribute-level trust scores propagated to consumers vs a single binary 'validated' flag on the golden record — what do downstream consumers actually need to act safely? | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-between-attribute-level-trust-scores-propagated-to-c-127808) |
| How do you design the steward workflow / UX at scale — task routing, prioritization, bulk actions, and feedback loops that improve match rules — so 5 stewards can cover millions of entities? | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-the-steward-workflow-ux-at-scale-task-routing-priori-127767) |
| How do you measure and defend MDM data quality — what metrics (match rate, false-merge rate, completeness, uniqueness, stewardship backlog) do you put on an exec dashboard and what SLAs do you commit? | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-measure-and-defend-mdm-data-quality-what-metrics-match-rate-127728) |
| Interviewer probe: 'Why did you choose survivorship at the attribute level instead of the record level?' Defend the added complexity and explain when record-level winner-takes-all is actually better. | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=interviewer-probe-why-did-you-choose-survivorship-at-the-attribute-lev-127772) |
| Interviewer probe: 'Your data steward team is drowning in a 200k-record match-review backlog.' What structural changes — not just more people — do you make to shrink the backlog permanently? | expertise | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=interviewer-probe-your-data-steward-team-is-drowning-in-a-200k-record--127805) |
| What is your model for the relationship between MDM, the data catalog, and lineage tooling — where does the system of record actually live and how do you avoid three overlapping sources of truth? | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-model-for-the-relationship-between-mdm-the-data-catalog-a-127731) |
| What is your survivorship and merge/unmerge strategy, and how do you make unmerge reversible and auditable years later when a false merge is discovered? | expertise | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-your-survivorship-and-merge-unmerge-strategy-and-how-do-you-ma-127718) |
| When you say 'golden record', what is the actual data model and lineage behind it — do you materialize one physical golden record, keep source-attributed survivorship, or expose a virtual golden view, and what drove that choice? | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-you-say-golden-record-what-is-the-actual-data-model-and-lineage-b-127716) |
