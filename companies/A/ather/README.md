# Ather

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 0 | 1 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 6 | 6 | 0 | 6 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design an endpoint that must return within a fixed byte budget for constrained IoT clients, dynamically trimming the representation and signaling truncation without breaking parsers? | deep understanding | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-endpoint-that-must-return-within-a-fixed-byte-bud-23973) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're architecting an IoT-scale telemetry platform ingesting from 10M devices sending every few seconds — how do you design device-connection management (MQTT) ingestion downsampling and command-and-control back to devices under intermittent connectivity? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-architecting-an-iot-scale-telemetry-platform-ingesting-from-10m-39496) |
| Design a zero-trust posture for an IoT/edge fleet of devices you ship to customer premises. They're physically accessible to attackers and rarely updated. How do you bootstrap identity, rotate keys, and revoke a cloned device at scale? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-zero-trust-posture-for-an-iot-edge-fleet-of-devices-you-ship--41307) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you plan capacity for a workload with extreme write bursts followed by long idle periods (e.g. IoT sensors reporting on schedule)? How do you avoid provisioning for the burst peak while meeting ingest guarantees, and where does buffering pay off? | deep understanding | SDE-2/3, Architect/Principal | Capacity Planning & Cost Optimization | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-plan-capacity-for-a-workload-with-extreme-write-bursts-foll-53004) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design the ingestion architecture for 2M IoT device events/second with intermittent connectivity, where devices batch-flush hours of buffered readings on reconnect. How do you keep the lake's event-time partitioning and late-data handling correct without a re-partition storm? | expertise | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-ingestion-architecture-for-2m-iot-device-events-second-with-112652) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you decide the number and size of convolutional filters when designing a custom lightweight CNN for a constrained device? | intermediate experience | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-the-number-and-size-of-convolutional-filters-when-66349) |
| How would you validate that a quantized model's accuracy loss is acceptable, and what representative dataset would you calibrate on? | deep understanding | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-validate-that-a-quantized-model-s-accuracy-loss-is-accep-66360) |
| You're asked to reduce a MobileNet's size by 4x for an edge device without much accuracy loss. Compare quantization-aware training vs post-training quantization for this. | deep understanding | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-reduce-a-mobilenet-s-size-by-4x-for-an-edge-device-wit-66292) |
| Your model needs to run at 30 FPS on an embedded camera. Walk me through choosing an architecture and the accuracy/latency negotiation with stakeholders. | deep understanding | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-model-needs-to-run-at-30-fps-on-an-embedded-camera-walk-me-throug-66335) |
| Your object detector's mAP looks fine but customers complain about missed small objects. How would you break down mAP by object size to confirm and then fix it? | deep understanding | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-object-detector-s-map-looks-fine-but-customers-complain-about-mis-66275) |
| How would you set up guardrails so an automated XGBoost retraining loop can't silently ship a model trained on corrupted labels? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-guardrails-so-an-automated-xgboost-retraining-loo-65908) |
