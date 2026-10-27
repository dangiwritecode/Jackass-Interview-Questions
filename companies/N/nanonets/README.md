# Nanonets

**Tier:** Tier 4  |  **Business domain:** AI  |  **Questions:** 17

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 3 | 4 | 1 | 4 |
| AI Engineer | 0 | 0 | 11 | 12 | 9 | 12 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Architect a document-processing pipeline that OCRs classifies and extracts structured data from millions of uploaded PDFs/images with an LLM step — how do you handle the async long-running jobs cost control and human-in-the-loop correction at scale? | deep understanding | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-document-processing-pipeline-that-ocrs-classifies-and-extr-39497) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a document-AI/IDP pipeline (buy Textract/Document AI/Azure DI vs build on open OCR + your own layout models) when accuracy on your domain forms and per-page pricing at millions of docs define the crossover? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-document-ai-idp-pipeline-buy-text-69803) |
| How would you approach building an OCR pipeline for noisy real-world documents, and where do most failures occur (detection, recognition, layout)? | deep understanding | SDE-1/2, SDE-2/3 | Computer Vision Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-approach-building-an-ocr-pipeline-for-noisy-real-world-d-66305) |
| For a vision extraction request, does content-block ordering of image vs text matter, and how do you choose between a base64 image and an image URL for user-uploaded documents in a pipeline? | intermediate experience | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=for-a-vision-extraction-request-does-content-block-ordering-of-image-v-64134) |
| You feed vision-capable models scanned documents. High-res images cost far more image tokens. How do you decide whether to downsample client-side, and how do you measure the cost to justify it? | deep understanding | SDE-1/2, SDE-2/3 | LLM API Integration (OpenAI/Anthropic) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-feed-vision-capable-models-scanned-documents-high-res-images-cost--64133) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide build-vs-buy for a document-AI/IDP extraction pipeline feeding your RAG (Textract/Document AI/Reducto vs open OCR + your own layout models) when domain-form accuracy and per-page pricing at millions of docs define the crossover? | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-build-vs-buy-for-a-document-ai-idp-extraction-pipeli-83749) |
| Design a feature that extracts structured fields from uploaded invoices; how do you place validation and repair so a bad extraction never silently persists? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | GenAI System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-feature-that-extracts-structured-fields-from-uploaded-invoice-78437) |
| How would you monitor for drift in an OCR + extraction pipeline where document templates from a vendor change without notice? | deep understanding | SDE-1/2, SDE-2/3 | Model Monitoring & Drift Detection | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-monitor-for-drift-in-an-ocr-extraction-pipeline-where-do-81189) |
| How would you architect a multimodal RAG system where the retriever returns document-page images and the VLM must answer citing specific regions of those pages? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-multimodal-rag-system-where-the-retriever-re-80648) |
| How would you fine-tune a vision-language model to output structured JSON reliably from receipts, and what training data and loss shaping reduce schema-invalid outputs? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-fine-tune-a-vision-language-model-to-output-structured-j-80615) |
| How would you set up an offline eval harness for a multimodal assistant that must handle screenshots, scanned documents, and natural photos with a different scoring rubric per input type? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-an-offline-eval-harness-for-a-multimodal-assistan-80701) |
| Interviewer probe: you're asked to justify fine-tuning a VLM versus few-shot prompting a hosted one for a document-extraction product. Walk me through the cost, quality, and ops trade-offs. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=interviewer-probe-you-re-asked-to-justify-fine-tuning-a-vlm-versus-few-80655) |
| You need to evaluate a document-understanding model across invoices, forms, and handwritten notes. How would you stratify the eval set and set per-slice acceptance gates in CI? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-evaluate-a-document-understanding-model-across-invoices-fo-80613) |
| Your team must choose between building a document-understanding VLM in-house versus a hosted API. Walk me through the build-vs-buy factors specific to multimodal (data, latency, compliance, cost). | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-team-must-choose-between-building-a-document-understanding-vlm-in-80687) |
| Your VLM confidently mis-reads decimal points on financial documents, causing downstream errors. How would you separate the perception failure from the reasoning failure and fix each? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multimodal AI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-vlm-confidently-mis-reads-decimal-points-on-financial-documents-c-80667) |
| How would you decide whether a rule-based regex extractor beats a learned NER model for a highly structured field like invoice numbers? | intermediate experience | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-whether-a-rule-based-regex-extractor-beats-a-lear-79481) |
| Your OCR-fed classifier sees character-level noise. How would you make token representations robust to that noise without retraining from scratch? | deep understanding | SDE-1/2, SDE-2/3 | NLP Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-ocr-fed-classifier-sees-character-level-noise-how-would-you-make--79450) |
