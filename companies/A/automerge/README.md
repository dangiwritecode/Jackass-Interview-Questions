# Automerge

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 13

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 5 | 8 | 7 | 8 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're presenting a tech-radar recommendation: adopt, trial, or hold on CRDTs as a platform-wide answer to AP conflict resolution. Make the principal-level case, including where CRDTs are a footgun that hides real consistency requirements. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-presenting-a-tech-radar-recommendation-adopt-trial-or-hold-on-c-32250) |
| A CRDT-based collaborative counter shows drift under concurrent increments across regions; explain the state structure that makes merges commutative and idempotent and how you detect a broken merge. | expertise | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-crdt-based-collaborative-counter-shows-drift-under-concurrent-increm-21981) |
| Explain the difference between eventual consistency and strong eventual consistency. Which do CRDTs provide, and why is 'eventual' insufficient to reason about correctness on its own? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-eventual-consistency-and-strong-eventua-28520) |
| Explain what a CRDT is and why it enables conflict-free merges without coordination. Contrast a G-Counter, PN-Counter, and OR-Set, and name a case where CRDTs are the wrong tool. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-what-a-crdt-is-and-why-it-enables-conflict-free-merges-without-28477) |
| You're building a collaborative editor. Compare Operational Transform and CRDTs for this. What are the correctness and engineering trade-offs, and what happens to tombstone growth over time? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-building-a-collaborative-editor-compare-operational-transform-a-28478) |
| Design multi-region for a real-time collaborative product (docs/whiteboard) where users in different regions edit the same document. How do you keep latency low and merges correct? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-multi-region-for-a-real-time-collaborative-product-docs-whitebo-36658) |
| Your team proposes CRDTs to eliminate conflict resolution entirely. Where do CRDTs genuinely fit in a multi-region system, and where do they quietly fail to model your business semantics? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-team-proposes-crdts-to-eliminate-conflict-resolution-entirely-whe-36623) |
| How do CRDTs help multi-leader/leaderless systems converge without central coordination? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Sharding & Replication | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-crdts-help-multi-leader-leaderless-systems-converge-without-cen-13398) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you would run an ATAM on an offline-first mobile+web architecture where sync-conflict resolution is the dominant quality attribute. What scenarios expose whether the conflict strategy actually preserves the business's correctness guarantees? | expertise | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-run-an-atam-on-an-offline-first-mobile-web-archi-40533) |
| How would you use ATAM to evaluate whether to build a real-time collaborative feature on CRDTs versus operational transforms versus a central-authority lock? Which scenarios expose the correctness-vs-latency-vs-complexity tradeoffs decisively? | expertise | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-atam-to-evaluate-whether-to-build-a-real-time-collab-40562) |
| Architect an offline-first collaborative mobile app where edits sync when connectivity returns — how do you draw the boundary between CRDT-merged fields last-writer-wins fields and server-authoritative fields and defend that split to a skeptical reviewer? | deep understanding | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-an-offline-first-collaborative-mobile-app-where-edits-sync-w-39422) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain when CRDTs are the right org-wide bet versus a coordination-based approach, and the operational tail you sign up for (tombstone/metadata growth, GC, merge semantics teams misunderstand). Where have you seen CRDTs be the wrong tool that looked right on paper? | deep understanding | SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-when-crdts-are-the-right-org-wide-bet-versus-a-coordination-ba-52548) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide, when modeling a new aggregate, whether it should live as a single consensus-replicated entity (linearizable) or as a set of CRDT-mergeable fields (eventual)? Give the modeling heuristic and a concrete case where you split one entity across both. | deep understanding | SDE-2/3, Architect/Principal | Consistency Models & Consensus (Raft/Paxos) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-when-modeling-a-new-aggregate-whether-it-should-live-112149) |
