# Liveblocks

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 2 | 1 | 2 |
| Fullstack | 0 | 0 | 1 | 3 | 2 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Build vs buy for a real-time collaboration/presence layer (Liveblocks/Ably vs building on your own WebSocket infra). Weigh scale economics, latency guarantees, and the depth of your differentiation. | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=build-vs-buy-for-a-real-time-collaboration-presence-layer-liveblocks-a-36997) |
| A CRDT-based collaborative counter shows drift under concurrent increments across regions; explain the state structure that makes merges commutative and idempotent and how you detect a broken merge. | expertise | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-crdt-based-collaborative-counter-shows-drift-under-concurrent-increm-21981) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you use ATAM to evaluate whether to build a real-time collaborative feature on CRDTs versus operational transforms versus a central-authority lock? Which scenarios expose the correctness-vs-latency-vs-complexity tradeoffs decisively? | expertise | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-atam-to-evaluate-whether-to-build-a-real-time-collab-40562) |
| Build vs buy for a real-time collaboration/presence layer (Liveblocks/Ably vs building on your own WebSocket infra). Weigh scale economics, latency guarantees, and the depth of your differentiation. | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=build-vs-buy-for-a-real-time-collaboration-presence-layer-liveblocks-a-36997) |
| How would you build a real-time collaborative cursor feature in a Next.js app — where does the WebSocket/SSE live given serverless constraints? | deep understanding | SDE-1/2, SDE-2/3 | Next.js | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-a-real-time-collaborative-cursor-feature-in-a-next-17242) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a collaborative editor for huge documents and huge concurrent sessions on flaky client networks, deciding between OT and CRDT, where the authoritative state lives, and how the server tier scales fan-out without a hot document toppling a shard? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-collaborative-editor-for-huge-documents-and--52118) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect caching for a collaborative-editing product (CRDT/OT) backed by a database so cached reads by non-editing viewers stay consistent with the convergent state without forcing every viewer onto the realtime channel? | expertise | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-caching-for-a-collaborative-editing-product-cr-111538) |
