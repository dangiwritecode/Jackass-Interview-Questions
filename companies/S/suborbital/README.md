# Suborbital

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 5

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 2 | 2 | 2 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you decide whether a plugin system should sandbox third-party Strategies via WASM, a separate process, or just a language interface, given hard requirements on CPU/memory isolation and a low-latency call budget? | expertise | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-a-plugin-system-should-sandbox-third-part-38497) |
| Design a WebAssembly-based plugin/extension architecture where third-party developers run untrusted code inside your product — how do you sandbox resource-limit and give plugins a capability-scoped API without letting one crash or exfiltrate host data? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-webassembly-based-plugin-extension-architecture-where-third-p-39430) |
| How do you design the trust boundary and threat model for a WebAssembly plugin runtime that executes partner code inside your service process? What isolation guarantees does Wasm give you, and what still leaks (timing, resource, capability)? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-the-trust-boundary-and-threat-model-for-a-webassembl-41278) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect the trust boundary and threat model for a WebAssembly plugin runtime executing partner code inside your service process? Be precise about what Wasm isolation guarantees and what still leaks (timing, resource exhaustion, capability confusion). | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-trust-boundary-and-threat-model-for-a-webasse-54008) |
| You inherit a mesh where WASM extension filters have proliferated across teams with no lifecycle management. Design the governance model for WASM plugins org-wide: a curated registry, versioning, resource limits, and a kill-switch, and how you retire the wild ones. | deep understanding | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherit-a-mesh-where-wasm-extension-filters-have-proliferated-acro-52640) |
