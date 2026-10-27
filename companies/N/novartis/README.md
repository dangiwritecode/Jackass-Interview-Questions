# Novartis

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| AI Engineer | 0 | 0 | 0 | 12 | 12 | 12 |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What is the difference between pseudonymization and anonymization under GDPR and why does that distinction change whether the data still falls in scope for your governance controls? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-the-difference-between-pseudonymization-and-anonymization-unde-127326) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you architect a data platform for a genomics/research org where individual datasets are terabyte-scale files (BAM/VCF) that don't fit a columnar table model? Where does object-storage-plus-metadata-index beat a warehouse, and how do you still provide catalog, lineage, and governance over opaque files? | deep understanding | SDE-2/3, Architect/Principal | Data Architecture (Lakes/Warehouses/Mesh) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-data-platform-for-a-genomics-research-org-where-112718) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An interviewer challenges your privacy design: pseudonymized training data can be re-identified by a model that learns spurious correlations. As principal how do you measure re-identification risk of a trained model and defend that residual risk to a skeptical DPO? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-interviewer-challenges-your-privacy-design-pseudonymized-training-d-70008) |
| Design governance for synthetic-data generation so synthetic training data provably doesn't leak real individuals (membership-inference resistance) and can be used to unblock GDPR-constrained ML use cases — how do you measure and attest the privacy of the synthetic set? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-governance-for-synthetic-data-generation-so-synthetic-training--69982) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you govern a clinical or diagnostic model so that model-lifecycle controls, SaMD validation, and post-market surveillance are a single coherent pipeline? | expertise | SDE-2/3, Architect/Principal | AI Governance & Responsible AI | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-govern-a-clinical-or-diagnostic-model-so-that-model-life-86076) |
| What's your strategy for evaluating models in a regulated domain where the eval itself must be validated and signed off by a compliance function? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-evaluating-models-in-a-regulated-domain-where-86914) |
| How do you architect a policy where 'answering when you shouldn't' is treated as a graver failure than over-refusal, and encode that asymmetry into every judge and guardrail across the org? | expertise | SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-policy-where-answering-when-you-shouldn-t-is-tr-84781) |
| How do you decide the org's stance on human-in-the-loop for high-stakes domains — which query classes must route to a human, and how do you evaluate that the routing guardrail itself is calibrated? | expertise | SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-org-s-stance-on-human-in-the-loop-for-high-stake-84780) |
| How do you design an eval governance model that satisfies EU AI Act high-risk obligations and produces the audit artifacts regulators expect, without grinding shipping velocity to a halt? | expertise | SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-eval-governance-model-that-satisfies-eu-ai-act-hi-84732) |
| How do you evaluate and guardrail against confident overclaiming — the model asserting certainty it shouldn't — and can you calibrate and gate on the model's expressed confidence at all? | expertise | SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-and-guardrail-against-confident-overclaiming-the-m-84817) |
| You need to prove to compliance and auditors that your guardrails enforce a fuzzy policy document — how do you turn policy into measurable, versioned, auditable eval cases at scale? | expertise | SDE-2/3, Architect/Principal | LLM Evaluation & Guardrails | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-prove-to-compliance-and-auditors-that-your-guardrails-enfo-84764) |
| As a principal, how do you architect the decision on whether a healthcare or fintech assistant needs full RLHF or whether SFT with strong guardrails suffices, given the liability profile? | deep understanding | SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=as-a-principal-how-do-you-architect-the-decision-on-whether-a-healthca-85824) |
| Design the architecture for a preference-elicitation UI and pipeline that lets non-ML domain experts (doctors, lawyers) contribute governed comparison data that feeds DPO safely. | expertise | SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-architecture-for-a-preference-elicitation-ui-and-pipeline-t-85768) |
| How do you architect a multi-region RLHF pipeline where preference data cannot leave its jurisdiction but the resulting reward model can — what does the federated boundary look like? | expertise | SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-multi-region-rlhf-pipeline-where-preference-dat-85747) |
| How do you architect a safety-evidence dossier that accumulates red-team results, eval scores, and data provenance automatically so any post-trained release can be signed off under the EU AI Act? | expertise | SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-safety-evidence-dossier-that-accumulates-red-te-85756) |
| How would you architect a post-training data plane where every SFT and preference example carries a consent, license, and jurisdiction tag that the training scheduler enforces as a hard filter per region? | expertise | SDE-2/3, Architect/Principal | Post-training (SFT/DPO/RLHF) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-post-training-data-plane-where-every-sft-and-85732) |
