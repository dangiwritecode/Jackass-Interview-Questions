# Todoist

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 3 | 3 | 3 | 3 |
| Fullstack | 1 | 1 | 5 | 5 | 2 | 5 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You need offline-first sync where queued user actions replay on reconnect. Which pattern models the queued actions, and how do you handle conflict resolution, ordering, and deduplication when the same action was partially applied server-side before disconnect? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-offline-first-sync-where-queued-user-actions-replay-on-reconn-22500) |
| Design a class model for optimistic mutation with rollback on the client (like a to-do reorder) that must survive a failed server sync and offline; what does the mutation queue and rollback stack look like? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-class-model-for-optimistic-mutation-with-rollback-on-the-clie-22405) |
| Design a reminder system that notifies users at a chosen date and time. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-reminder-system-that-notifies-users-at-a-chosen-date-and-time-8911) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a class model for optimistic mutation with rollback on the client (like a to-do reorder) that must survive a failed server sync and offline; what does the mutation queue and rollback stack look like? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-class-model-for-optimistic-mutation-with-rollback-on-the-clie-22405) |
| Mid-way through building a task manager, the interviewer says "now add recurring tasks." How do you extend your model without breaking existing one-off tasks, and where do you compute the next occurrence? | intermediate experience | SDE-1/2, SDE-2/3 | Machine Coding Round | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=mid-way-through-building-a-task-manager-the-interviewer-says-now-add-r-21518) |
| You built a task manager and now must add offline support. The interviewer asks how you queue mutations locally and sync on reconnect. Walk through conflict resolution and ordering guarantees. | expertise | SDE-1/2, SDE-2/3 | Machine Coding Round | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-built-a-task-manager-and-now-must-add-offline-support-the-intervie-21571) |
| You built a task manager and now must add sub-tasks and dependencies. The interviewer asks how you prevent circular dependencies when a user links task A to B to A. Walk through detection. | deep understanding | SDE-1/2, SDE-2/3 | Machine Coding Round | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-built-a-task-manager-and-now-must-add-sub-tasks-and-dependencies-t-21543) |
| Design a reminder system that notifies users at a chosen date and time. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-reminder-system-that-notifies-users-at-a-chosen-date-and-time-8911) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd reason about CAP for a 'local-first' mobile app where each device holds an authoritative replica that syncs opportunistically; why is such a system fundamentally AP, and how do you preserve business invariants across long device partitions? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-reason-about-cap-for-a-local-first-mobile-app-where--111560) |
