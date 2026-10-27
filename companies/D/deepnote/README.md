# DeepNote

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| ML Engineer | 2 | 0 | 2 | 8 | 8 | 8 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a notebook / interactive-compute environment for analysts and data scientists (buy Hex/Deepnote/Databricks notebooks vs JupyterHub self-run) when practitioner productivity, governance, and idle-compute cost all matter at 200+ users? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-notebook-interactive-compute-envi-125853) |
| Explain how you'd govern the cost of experiment and backtest environments where data scientists spin up full dataset clones, throwaway warehouses, and long-running notebooks against production data. Design the TTL, quota, and self-destruct governance that keeps exploratory velocity without permanent clone-and-compute leak. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-govern-the-cost-of-experiment-and-backtest-environme-125999) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a notebook/interactive-compute environment for data scientists (buy SageMaker Studio/Deepnote/Hex vs build on JupyterHub + your infra) when researcher productivity vs governance and idle-GPU cost both matter at 200 practitioners? | intermediate experience | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-notebook-interactive-compute-envi-69844) |
| What is a managed notebook service in the cloud and why is it convenient for early ML experimentation? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-managed-notebook-service-in-the-cloud-and-why-is-it-convenie-58131) |
| Why might a cloud notebook running for days quietly cost more than the compute you actually used for a few hours? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-a-cloud-notebook-running-for-days-quietly-cost-more-than-the-58207) |
| An interviewer challenges: your data scientists pull prod data into notebooks freely. As principal how do you architect a governed notebook/experimentation environment where PII access is brokered masked and audited without killing exploratory ML work? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-data-scientists-pull-prod-data-into-not-69981) |
| Design the controls that prevent a data scientist from downloading a raw PII sample to a laptop for 'quick exploration' — technical and cultural. | deep understanding | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-controls-that-prevent-a-data-scientist-from-downloading-a-r-72634) |
| How do you architect PII controls that survive the notebook/experimentation phase, not just the productionized pipeline where most tooling focuses? | deep understanding | SDE-2/3, Architect/Principal | Data Privacy & PII Handling in AI | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-pii-controls-that-survive-the-notebook-experiment-72650) |
| A principal probe: your data-scientists run notebooks on always-on GPU instances that idle 80% of the time between cells. Design the org-wide interactive-compute governance — auto-suspend, scale-to-zero notebooks, shared burst pools — that cuts idle GPU cost without hurting exploratory workflow. | deep understanding | SDE-2/3, Architect/Principal | FinOps & Cloud Cost Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-probe-your-data-scientists-run-notebooks-on-always-on-gpu--69920) |
| What's your position on notebooks in production? How does the platform give data scientists notebook ergonomics while preventing notebook-quality code from reaching prod? | deep understanding | SDE-2/3, Architect/Principal | ML Platform Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-position-on-notebooks-in-production-how-does-the-platform--72013) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your approach to governing golden-path vs. escape-hatch data access for data scientists so experimentation is fast but nothing sensitive leaks to notebooks? | deep understanding | SDE-2/3, Architect/Principal | Data Strategy & Governance | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-approach-to-governing-golden-path-vs-escape-hatch-data-acc-86777) |
