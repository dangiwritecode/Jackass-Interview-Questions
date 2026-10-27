# Zoox

**Tier:** Tier 2  |  **Business domain:** Autonomous  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 6 | 8 | 3 | 8 |
| Data Structures & Algorithms (all profiles) | 6 | 6 | 6 | 6 | 6 | 6 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a computer-vision annotation + active-learning loop for an autonomy stack (buy Scale/Encord vs build in-house tooling + labeler ops) when the labeling flywheel is the core moat and per-frame cost scales with fleet miles? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-computer-vision-annotation-active-69799) |
| How would you design a C++ perception inference pipeline for an AV with a hard per-frame deadline? How do you bound worst-case latency, avoid GC-free stalls (page faults, allocations), and detect when you miss the deadline? | expertise | SDE-1/2, SDE-2/3 | C++ | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-c-perception-inference-pipeline-for-an-av-with--62847) |
| You must guarantee no dynamic allocation on a real-time inference path (e.g., an autonomous-vehicle perception loop). How do you enforce and verify it — preallocated pools, an aborting operator new, static analysis — and what STL usage silently allocates? | expertise | SDE-1/2, SDE-2/3 | C++ | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-guarantee-no-dynamic-allocation-on-a-real-time-inference-path-62846) |
| An interviewer probes your active-learning loop: the system selects uncertain live samples containing PII for re-labeling and retraining. How do you govern consent and minimization when the model itself chooses which personal data gets collected and re-processed? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-probes-your-active-learning-loop-the-system-selects-unc-70041) |
| How would you set up guardrails so an automated XGBoost retraining loop can't silently ship a model trained on corrupted labels? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-guardrails-so-an-automated-xgboost-retraining-loo-65908) |
| How do you detect and handle out-of-distribution inputs at the FastAPI serving layer before they reach the model, and what do you return when an input is flagged as OOD? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-detect-and-handle-out-of-distribution-inputs-at-the-fastapi-62898) |
| You must add GPU inference for a vision model; how do you decide between batching requests dynamic batching and per-request serving under a latency SLA? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-add-gpu-inference-for-a-vision-model-how-do-you-decide-betwee-66681) |
| How do you evaluate an object-detection model beyond mAP when small-object recall is the business-critical metric? | deep understanding | SDE-1/2, SDE-2/3 | Model Evaluation Metrics | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-an-object-detection-model-beyond-map-when-small-ob-65807) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Evaluate a Flat Arithmetic Expression String | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Math, Parsing, Simulation, Stack, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=evaluate-a-flat-arithmetic-expression-string-d227) |
| Fewest Birds Needed to Produce a Chirp Stream | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Greedy, Simulation, String | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=fewest-birds-needed-to-produce-a-chirp-stream-d1364) |
| In-Place Run-Length Compression of a Character Array | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, In-place Modification, Run-Length Encoding, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-place-run-length-compression-of-a-character-array-d443) |
| Largest Set of Collinear Points | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, GCD, Geometry, Hash Table, Math, Number Theory | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=largest-set-of-collinear-points-d149) |
| Maximum Gain from a Single Buy and Later Sell | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Greedy, Prefix Minimum, Single Pass | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=maximum-gain-from-a-single-buy-and-later-sell-d121) |
| Spreading Compromise Across a Server Grid | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Breadth-First Search, Flood Fill, Graph, Matrix, Queue | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=spreading-compromise-across-a-server-grid-d979) |
