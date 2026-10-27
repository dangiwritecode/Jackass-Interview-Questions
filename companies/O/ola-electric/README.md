# Ola Electric

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 14

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 2 | 3 | 2 | 3 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| AIOps | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Engineer | 0 | 0 | 2 | 2 | 1 | 2 |
| Database Developer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must authenticate requests from an IoT/device fleet with no user interaction and intermittent connectivity. Compare pre-provisioned device certs vs a device-registration token exchange, and how you revoke a stolen device. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-authenticate-requests-from-an-iot-device-fleet-with-no-user-i-26178) |
| How do you design an endpoint that must return within a fixed byte budget for constrained IoT clients, dynamically trimming the representation and signaling truncation without breaking parsers? | deep understanding | SDE-1/2, SDE-2/3 | REST API | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-endpoint-that-must-return-within-a-fixed-byte-bud-23973) |
| How do you architect an IoT/telemetry ingestion platform for tens of millions of devices phoning home, where a firmware bug can cause synchronized thundering-herd reconnects, and where write scaling and cost dominate over read latency? | expertise | SDE-2/3, Architect/Principal | Scalability & Availability | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-iot-telemetry-ingestion-platform-for-tens-of-m-32165) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're architecting an IoT-scale telemetry platform ingesting from 10M devices sending every few seconds — how do you design device-connection management (MQTT) ingestion downsampling and command-and-control back to devices under intermittent connectivity? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-architecting-an-iot-scale-telemetry-platform-ingesting-from-10m-39496) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect SLOs for an IoT/edge fleet of millions of devices with intermittent connectivity where most "failures" are the device's network — what SLI fairly separates device-side from platform-side reliability? | deep understanding | SDE-2/3, Architect/Principal | Reliability Engineering (SLA/SLO/SLI) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-slos-for-an-iot-edge-fleet-of-millions-of-devices-54206) |
| How do you architect a zero-trust posture for an IoT/edge fleet shipped to customer premises, physically accessible and rarely updated? Design the identity bootstrap, key rotation, and clone-detection so a cloned device can be revoked at scale. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-zero-trust-posture-for-an-iot-edge-fleet-shippe-53986) |
| Architect how you'd bring firmware, IoT and edge-device software under the same supply chain umbrella as your cloud workloads — what changes when the endpoint can't verify signatures at runtime? | expertise | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-how-you-d-bring-firmware-iot-and-edge-device-software-under--55490) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect telemetry for edge/IoT fleets (thousands of intermittently connected devices) so metrics survive disconnection, back-fill on reconnect, and don't drown the central Prometheus in a thundering-herd re-sync after a network recovery? | expertise | SDE-2/3, Architect/Principal | Observability & Monitoring (Prometheus/Grafana/OpenTelemetry) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-telemetry-for-edge-iot-fleets-thousands-of-interm-99059) |
| How do you architect telemetry for edge and IoT fleets where connectivity is intermittent and you can't stream everything back — what do you compute at the edge? | deep understanding | SDE-2/3, Architect/Principal | Unified Observability (Logs/Metrics/Traces) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-telemetry-for-edge-and-iot-fleets-where-connectiv-101695) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design a pipeline for slowly-arriving IoT sensor data with clock drift; how do you assign event time and handle out-of-order batches? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Data Pipeline System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-pipeline-for-slowly-arriving-iot-sensor-data-with-clock-drift-124723) |
| How would you forward-fill sensor readings (carry last non-null) across millions of device partitions efficiently, and what frame or IGNORE NULLS pattern scales best? | deep understanding | SDE-1/2, SDE-2/3 | Window Functions (SQL) | Online Assessment (OA), DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-forward-fill-sensor-readings-carry-last-non-null-across--123211) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a time-series data platform on Amazon Timestream (or a self-managed alternative) for high-ingest IoT/telemetry — reason about the memory-store versus magnetic-store tiering, retention policy design, and query-cost model at billions of points/day. | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-time-series-data-platform-on-amazon-timestream--111858) |
| How would you architect denormalization for an IoT or telemetry system ingesting millions of events per second into time-series storage? | deep understanding | SDE-2/3, Architect/Principal | Normalization & Denormalization | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-denormalization-for-an-iot-or-telemetry-system-113419) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you set up guardrails so an automated XGBoost retraining loop can't silently ship a model trained on corrupted labels? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-guardrails-so-an-automated-xgboost-retraining-loo-65908) |
