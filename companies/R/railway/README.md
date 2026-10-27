# Railway

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 25

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 3 | 3 | 2 | 3 |
| Fullstack | 0 | 0 | 2 | 3 | 1 | 3 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 1 | 2 | 1 | 2 |
| AI Engineer | 12 | 0 | 14 | 15 | 12 | 15 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design authentication for a CLI tool that developers install locally — how do you do the browser-based OAuth device/auth-code flow, store the resulting token securely on disk, and refresh it? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-authentication-for-a-cli-tool-that-developers-install-locally-h-26204) |
| An endpoint returns a paginated list plus a 'has_more' flag. Why is fetching limit+1 rows better than a separate COUNT query for that flag, and when does even that break down? | intermediate experience | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-endpoint-returns-a-paginated-list-plus-a-has-more-flag-why-is-fetch-22143) |
| How do you install and enable the pgvector extension in a fresh Postgres database? | basic concept | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Vector Databases (Pinecone/pgvector) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-install-and-enable-the-pgvector-extension-in-a-fresh-postgr-12247) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your Next.js server components hit Postgres directly per request and connections spike on serverless; explain why serverless kills connection pools and how a proxy or serverless driver fixes it. | deep understanding | SDE-1/2, SDE-2/3 | PostgreSQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-next-js-server-components-hit-postgres-directly-per-request-and-c-18178) |
| Walk me through threat-modeling a design where you expose a customer-facing 'run my code' or webhook-transform feature. Untrusted code executes in your infra. Compare gVisor, Firecracker microVMs, and Wasm for the isolation architecture. | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-threat-modeling-a-design-where-you-expose-a-customer-f-41303) |
| An endpoint returns a paginated list plus a 'has_more' flag. Why is fetching limit+1 rows better than a separate COUNT query for that flag, and when does even that break down? | intermediate experience | SDE-1/2, SDE-2/3 | SQL | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-endpoint-returns-a-paginated-list-plus-a-has-more-flag-why-is-fetch-22143) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design a compliance program for a platform that spins ephemeral preview environments per pull request — dozens created and destroyed hourly — so that transient infra doesn't create scope gaps or blind spots the auditor can exploit? | deep understanding | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-a-compliance-program-for-a-platform-that-spins-ephem-54040) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your rubric for when to trust a young database (< 3 years, small team) in production, and what mitigations do you put around that bet to make it reversible? | expertise | SDE-2/3, Architect/Principal | Database Selection Strategy (RDBMS/NoSQL/NewSQL) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-rubric-for-when-to-trust-a-young-database-3-years-small-te-114411) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you profile and reduce XGBoost inference latency when the bottleneck turns out to be feature preprocessing, not tree traversal? | deep understanding | SDE-1/2, SDE-2/3 | Ensemble Methods (Random Forest/XGBoost) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-profile-and-reduce-xgboost-inference-latency-when-the-bo-65935) |
| How would you architect the control plane for a self-serve inference platform where product teams request an endpoint and get quantization/parallelism/autoscaling chosen for them? | deep understanding | SDE-2/3, Architect/Principal | Inference Optimization (vLLM/TensorRT) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-control-plane-for-a-self-serve-inference-p-71185) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you build an ephemeral preview environment per PR for a RAG app, including a small seeded vector index, so reviewers can actually query the changed behavior? | deep understanding | SDE-1/2, SDE-2/3 | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-build-an-ephemeral-preview-environment-per-pr-for-a-rag--77648) |
| How would you decide the right chunk of your RAG pipeline to run serverless versus on a long-running instance? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-the-right-chunk-of-your-rag-pipeline-to-run-serve-76543) |
| How would you deploy a simple Python RAG API to the cloud so it is reachable over the internet? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-deploy-a-simple-python-rag-api-to-the-cloud-so-it-is-rea-76499) |
| How would you deploy a Streamlit or Gradio AI demo to the cloud so others can try it? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-deploy-a-streamlit-or-gradio-ai-demo-to-the-cloud-so-oth-76551) |
| How would you set up a staging environment in the cloud to test prompt changes before they reach real users? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-set-up-a-staging-environment-in-the-cloud-to-test-prompt-76564) |
| What is a CI/CD pipeline and how would you use one to deploy updates to your RAG service safely? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-ci-cd-pipeline-and-how-would-you-use-one-to-deploy-updates-t-76525) |
| What is a container and why would you package your AI service in one before deploying it to the cloud? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-container-and-why-would-you-package-your-ai-service-in-one-b-76500) |
| What is a managed Kubernetes cluster and why is it usually overkill for a fresher's first LLM chatbot? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-managed-kubernetes-cluster-and-why-is-it-usually-overkill-fo-76536) |
| What is horizontal scaling and how would it help your RAG API handle more concurrent chat requests? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-horizontal-scaling-and-how-would-it-help-your-rag-api-handle-m-76510) |
| What would you check first if your deployed AI app returns a 502 or 503 error right after a new release? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-would-you-check-first-if-your-deployed-ai-app-returns-a-502-or-50-76581) |
| Why should configuration like model names and API endpoints come from environment variables rather than being hardcoded? | basic concept | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-should-configuration-like-model-names-and-api-endpoints-come-from--76520) |
| Your streaming UI shows garbled partial JSON to users when the model streams a structured field. Explain why partial JSON can't be incrementally parsed and how you'd fix the UX. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | LLM Fundamentals | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-streaming-ui-shows-garbled-partial-json-to-users-when-the-model-s-77933) |
| How would you deploy your LLM app on a platform like Render, Railway, or Vercel and what are the trade-offs? | basic concept | Fresher, SDE-1/2, SDE-2/3 | Model Deployment & Serving | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-deploy-your-llm-app-on-a-platform-like-render-railway-or-74618) |
| How did you deploy your AI project, and where does the LLM API call actually happen in your architecture? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | Projects (Resume Deep-Dive) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-did-you-deploy-your-ai-project-and-where-does-the-llm-api-call-act-74036) |
| Design a self-serve platform contract so a product team can onboard a new corpus to agent-retrieval in a day without touching your team. What defaults, guardrails, and paved-road primitives must you expose, and where do you deliberately refuse to make it self-serve? | expertise | SDE-2/3, Architect/Principal | Vector Databases (Pinecone/pgvector) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-self-serve-platform-contract-so-a-product-team-can-onboard-a--82516) |
