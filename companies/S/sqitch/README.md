# Sqitch

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 5

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Database Developer | 0 | 5 | 5 | 0 | 0 | 5 |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A revert of a bad migration merge to main is blocking the later re-merge of the corrected feature because Git thinks the changes are already applied. Explain the DAG mechanism and the exact sequence to cleanly re-introduce the migration. | deep understanding | SDE-1, SDE-1/2 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-revert-of-a-bad-migration-merge-to-main-is-blocking-the-later-re-mer-107776) |
| You inherited a repo where a single evolving schema.sql is edited in place with no migration history, and you can't reproduce past production schema states. Lay out a migration to an append-only, Git-tracked migration workflow without a risky big-bang cutover. | expertise | SDE-1, SDE-1/2 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherited-a-repo-where-a-single-evolving-schema-sql-is-edited-in-p-107833) |
| You need to split a giant already-merged 'add whole schema' commit into per-table logical commits for a clean future revert story. Walk through interactive rebase 'edit' plus reset, and the exact risks if the commit is already public and branched from. | deep understanding | SDE-1, SDE-1/2 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-split-a-giant-already-merged-add-whole-schema-commit-into--107807) |
| Your CODEOWNERS forces DBA review on the migrations folder, but a PR bundled a migration inside the application source directory and skipped DBA review. How would you structure path rules and repo layout so schema-affecting changes always route to the DBA team? | intermediate experience | SDE-1, SDE-1/2 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-codeowners-forces-dba-review-on-the-migrations-folder-but-a-pr-bu-107759) |
| Your team keeps DDL in one directory and DML/data-fix scripts in another. A reviewer approved a data-fix DML that should have been a reversible migration. How would you structure the repo and CI so data-fix scripts get the same rigor as schema migrations? | intermediate experience | SDE-1, SDE-1/2 | Git & GitHub | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-team-keeps-ddl-in-one-directory-and-dml-data-fix-scripts-in-anoth-107796) |
