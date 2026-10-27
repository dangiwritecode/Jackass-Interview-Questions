# Excalidraw

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 2 | 2 | 2 |
| Fullstack | 1 | 1 | 5 | 8 | 7 | 8 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design a Flyweight-based rendering model for a canvas with 100k identical icons so memory stays flat, and what breaks if some 'identical' objects later need per-instance mutable state? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-flyweight-based-rendering-model-for-a-canvas-with--16494) |
| Design multi-region for a real-time collaborative product (docs/whiteboard) where users in different regions edit the same document. How do you keep latency low and merges correct? | expertise | SDE-2/3, Architect/Principal | Multi-Region & Geo-Replication | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-multi-region-for-a-real-time-collaborative-product-docs-whitebo-36658) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A canvas-based diagram editor slows down as nodes grow; what spatial index would you use for hit-testing and viewport culling so pan/zoom stays smooth at thousands of shapes? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-canvas-based-diagram-editor-slows-down-as-nodes-grow-what-spatial-in-16070) |
| How would you architect a Flyweight-style shared-model layer for a real-time collaborative canvas so millions of nodes share style/geometry intrinsics across clients, and where does the extrinsic per-user cursor/selection state live to keep sync cheap? | deep understanding | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-flyweight-style-shared-model-layer-for-a-rea-38437) |
| Design a real-time collaborative whiteboard (Figma/Miro-style) — how do you sync shapes across clients, handle large canvases, and keep rendering at 60fps? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-real-time-collaborative-whiteboard-figma-miro-style-how-do-yo-20689) |
| Design the architecture for a design-collaboration canvas (Figma-scale) that must render a 100K-object document at 60fps in the browser and sync multiplayer edits — how do you split the rendering engine (WebGL/WASM) from the sync layer and keep memory bounded? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-for-a-design-collaboration-canvas-figma-scale--39444) |
| Design a client-side undo/redo for a drawing app. What does each command capture and how do you replay? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-client-side-undo-redo-for-a-drawing-app-what-does-each-comman-9006) |
| Design client-side undo/redo for a drawing app where operations can be large (freehand paths); how do you keep the command history memory-bounded and support collaborative edits interleaving later? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-client-side-undo-redo-for-a-drawing-app-where-operations-can-be-16480) |
| How do you design a Flyweight-based rendering model for a canvas with 100k identical icons so memory stays flat, and what breaks if some 'identical' objects later need per-instance mutable state? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-flyweight-based-rendering-model-for-a-canvas-with--16494) |
| You must set the org policy for Cross-Origin-Resource-Policy, COEP and COOP now that some products need cross-origin isolation for SharedArrayBuffer. Explain how these headers interact with your existing CORS/CSP posture and where enabling isolation breaks embeds. | expertise | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-set-the-org-policy-for-cross-origin-resource-policy-coep-and--38936) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you plan capacity for a real-time collaborative product (docs, whiteboards) where cost scales with concurrent active sessions and fan-out of edits, not with total users? How do you model concurrency-driven cost and where does it break down? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-capacity-for-a-real-time-collaborative-product-docs-wh-53020) |
