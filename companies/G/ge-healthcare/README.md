# GE HealthCare

**Tier:** Tier 2  |  **Business domain:** Healthcare/Hardware  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 3 | 4 | 1 | 4 |
| AI Engineer | 0 | 0 | 0 | 4 | 4 | 4 |
| Data Structures & Algorithms (all profiles) | 3 | 3 | 3 | 3 | 3 | 3 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a data strategy for CI that gives realistic test fidelity without ever moving regulated PII into build environments, given today's pipelines seed test databases directly from production snapshots; cover synthetic generation, masking, and subsetting and their fidelity limits. | expertise | SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-data-strategy-for-ci-that-gives-realistic-te-52287) |
| How would you architect delivery for a product that ships continuously to your own cloud and periodically to air-gapped customer environments you don't control, so a single pipeline produces and promotes artifacts destined for both, and updates to the air-gapped install remain verifiable and rollback-capable remotely? | expertise | SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-delivery-for-a-product-that-ships-continuously-52321) |
| Your delivery platform must ship the same product to your managed cloud and to sovereign/on-prem installations your customers self-operate on air-gapped networks; how do you architect artifact packaging, promotion, and update delivery so one pipeline produces something you can ship where you have no runtime access? | expertise | SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-delivery-platform-must-ship-the-same-product-to-your-managed-clou-52232) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design encryption and key management for an edge/IoT healthcare deployment where devices sync ePHI intermittently to a central DB — how do you handle keys on constrained untrusted devices? | expertise | SDE-2/3, Architect/Principal | Data Encryption & Compliance (GDPR/HIPAA) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-encryption-and-key-management-for-an-edge-iot-healthcare-deploy-115294) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect governance for models in healthcare where you must handle SaMD/FDA-style validation plus HIPAA on top of ML lifecycle controls? | expertise | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-governance-for-models-in-healthcare-where-you-mus-71752) |
| You get a request to explain why a CNN misclassified a specific medical image; what interpretability tools (Grad-CAM, saliency, occlusion) would you use and what are their limits? | deep understanding | SDE-1/2, SDE-2/3 | Deep Learning (Neural Networks/CNN/RNN) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-get-a-request-to-explain-why-a-cnn-misclassified-a-specific-medica-65090) |
| How do you handle tuning a model where the validation metric has high variance run-to-run because of small data? | deep understanding | SDE-1/2, SDE-2/3 | Hyperparameter Tuning | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-tuning-a-model-where-the-validation-metric-has-high--65981) |
| How would you approach fine-tuning a multimodal model for a medical imaging plus report-generation task with very limited labeled data? | deep understanding | SDE-1/2, SDE-2/3 | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-fine-tuning-a-multimodal-model-for-a-medical-im-67130) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you govern a clinical or diagnostic model so that model-lifecycle controls, SaMD validation, and post-market surveillance are a single coherent pipeline? | expertise | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-a-clinical-or-diagnostic-model-so-that-model-life-86076) |
| How would you build an eval that quantifies the tail risk of a rare catastrophic output when its base rate is too low to observe in normal sampling? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-an-eval-that-quantifies-the-tail-risk-of-a-rare-ca-86911) |
| How would you architect eval for an assistant embedded in a safety-critical workflow (medical triage, industrial control) where a single missed failure is catastrophic? What changes versus a consumer chatbot? | expertise | SDE-2/3, Architect/Principal | Evaluation Frameworks (LLM-as-Judge) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-eval-for-an-assistant-embedded-in-a-safety-cri-85524) |
| Interviewer probe: your org wants to enter a regulated healthcare imaging market with a multimodal model. As architect what data safety validation and liability guardrails would you demand before greenlighting a single deployment? | expertise | SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=interviewer-probe-your-org-wants-to-enter-a-regulated-healthcare-imagi-84720) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Duplicate a Sequence by Self-Concatenation | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Simulation | Online Assessment (OA), Phone Screen | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=duplicate-a-sequence-by-self-concatenation-d1828) |
| Median of Two Sorted Sequences in Logarithmic Time | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Divide and Conquer, Two Pointers | Phone Screen, DSA/Coding Round, Onsite, Hiring Manager | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=median-of-two-sorted-sequences-in-logarithmic-time-d4) |
| Resolve Ratio Queries Over a Web of Known Proportions | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Breadth-First Search, Depth-First Search, Graph, Hash Table, Shortest Path, String, Union Find | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=resolve-ratio-queries-over-a-web-of-known-proportions-d399) |
