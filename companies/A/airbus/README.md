# Airbus

**Tier:** Tier 2  |  **Business domain:** Aerospace  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| AI Engineer | 0 | 0 | 0 | 6 | 6 | 6 |
| Data Structures & Algorithms (all profiles) | 3 | 3 | 3 | 3 | 3 | 3 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer probes: two jurisdictions' laws conflict — the EU AI Act demands you log all high-risk model decisions while GDPR data-minimization pushes to log less. As principal how do you architect the ML audit-log design that satisfies both without contradiction? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-two-jurisdictions-laws-conflict-the-eu-ai-act-de-70017) |
| Design an EU-AI-Act risk-classification workflow so every new model is tagged (minimal limited high-risk prohibited) and high-risk models automatically inherit the conformity-assessment logging and human-oversight controls — how do you keep the classification from being gamed to avoid obligations? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-eu-ai-act-risk-classification-workflow-so-every-new-model-is-69979) |
| Design governance for a model that must comply with data-sovereignty mandates requiring EU-national operators and EU-owned infrastructure (sovereign-cloud) for the whole training-to-serving pipeline — how do you build a sovereign ML enclave without forking all of MLOps? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-governance-for-a-model-that-must-comply-with-data-sovereignty-m-70027) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your reference architecture for a 'safety case' — a structured, auditable argument that a given AI system is acceptably safe for its deployment context? | expertise | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-reference-architecture-for-a-safety-case-a-structured-audi-86053) |
| Argue the organizational trade-off between a single global corpus with fine-grained ACLs versus federated per-department corpora that never physically merge. At what compliance and blast-radius threshold do you mandate federation? | deep understanding | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=argue-the-organizational-trade-off-between-a-single-global-corpus-with-82950) |
| Design the platform's handling of extremely long documents (a 2000-page manual) so that hierarchical retrieval (section then passage) works correctly and citations resolve to the right nested location, at scale across thousands of such documents. | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-platform-s-handling-of-extremely-long-documents-a-2000-page-83006) |
| How do you architect the platform so the org can prove, for an AI-Act-style conformity assessment, that its high-risk RAG system meets logging, human-oversight, and accuracy obligations — turning regulatory requirements into concrete architectural components? | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-platform-so-the-org-can-prove-for-an-ai-act-s-83015) |
| You must design how the platform handles a corpus that legally must be sharded by geography (data residency) but where a single answer may need evidence from multiple regions. How do you compose a cross-region answer without moving the data? | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-how-the-platform-handles-a-corpus-that-legally-must-be-82996) |
| You must design the org's response to a novel failure: retrieval works and citations are valid, but the generator subtly misreads a table's units and gives dangerous numeric answers. How do you build systemic defenses for grounded-but-misinterpreted evidence? | expertise | SDE-2/3, Architect/Principal | RAG (Retrieval-Augmented Generation) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-the-org-s-response-to-a-novel-failure-retrieval-works--83020) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Count Divisible Cross Pairs | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Enumeration, Hash Table, Math, Number Theory | Online Assessment (OA), Phone Screen | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-divisible-cross-pairs-d2872) |
| Counting Divisibility Pairs Across Two Arrays | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Counting, Divisor Sieve, Harmonic Sum, Hash Table, Math, Number Theory | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=counting-divisibility-pairs-across-two-arrays-d2874) |
| Fewest Overwrites to Equalize Mirror-Pair Gaps | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Difference Array, Greedy, Hash Table, Line Sweep, Prefix Sum, Two Pointers | Online Assessment (OA), DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=fewest-overwrites-to-equalize-mirror-pair-gaps-d2919) |
