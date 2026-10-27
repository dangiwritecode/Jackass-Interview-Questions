# Khan-Academy

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 4 | 4 | 4 | 4 |
| Fullstack | 0 | 0 | 5 | 7 | 7 | 7 |
| Data Engineer | 0 | 0 | 1 | 1 | 1 | 1 |
| ML Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| AI Engineer | 1 | 0 | 1 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A header value (User-Agent, Referer) is being logged into a system that later renders logs in a web UI and also builds a SQL query. Trace how one untrusted header becomes both a stored-XSS and a SQLi vector, and fix both. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-header-value-user-agent-referer-is-being-logged-into-a-system-that-l-19190) |
| A URL-preview/link-unfurl service fetches and renders remote HTML server-side. Enumerate the combined SSRF, stored-XSS, and CORS-bypass risks and design the sandboxing/network-isolation controls. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-url-preview-link-unfurl-service-fetches-and-renders-remote-html-serv-19168) |
| Compare a session-bound CSRF token vs a stateless HMAC-signed (double-submit) token for a horizontally-scaled service. Discuss token rotation, logout invalidation, and the security/operability trade-offs of each. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-a-session-bound-csrf-token-vs-a-stateless-hmac-signed-double-s-19202) |
| You must migrate a legacy monolith full of string-concatenated queries to parameterized queries while shipping features. Design the incremental strategy, the safety net, and how you prove coverage to security. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-migrate-a-legacy-monolith-full-of-string-concatenated-queries-19171) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design an EdTech live-class platform delivering interactive classes to 100K concurrent students with video quizzes and doubt-solving — how do you architect the low-latency AV interactivity and recording so a class survives a regional network blip? | deep understanding | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-edtech-live-class-platform-delivering-interactive-classes-to-39495) |
| How do you distinguish frontend accessibility debt that carries legal/compliance risk from cosmetic UI inconsistency, and how do you sequence remediation given both are lumped as 'UI polish' by product? | deep understanding | SDE-2/3, Architect/Principal | Tech Debt Management | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-distinguish-frontend-accessibility-debt-that-carries-legal--41437) |
| A header value (User-Agent, Referer) is being logged into a system that later renders logs in a web UI and also builds a SQL query. Trace how one untrusted header becomes both a stored-XSS and a SQLi vector, and fix both. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-header-value-user-agent-referer-is-being-logged-into-a-system-that-l-19190) |
| A URL-preview/link-unfurl service fetches and renders remote HTML server-side. Enumerate the combined SSRF, stored-XSS, and CORS-bypass risks and design the sandboxing/network-isolation controls. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-url-preview-link-unfurl-service-fetches-and-renders-remote-html-serv-19168) |
| Compare a session-bound CSRF token vs a stateless HMAC-signed (double-submit) token for a horizontally-scaled service. Discuss token rotation, logout invalidation, and the security/operability trade-offs of each. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-a-session-bound-csrf-token-vs-a-stateless-hmac-signed-double-s-19202) |
| You must migrate a legacy monolith full of string-concatenated queries to parameterized queries while shipping features. Design the incremental strategy, the safety net, and how you prove coverage to security. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-migrate-a-legacy-monolith-full-of-string-concatenated-queries-19171) |
| Your SPA reads location.hash to drive client-side routing and one route sinks it into .innerHTML. Trace the DOM-XSS source-to-sink, and explain why server-side defenses never see this payload. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-spa-reads-location-hash-to-drive-client-side-routing-and-one-rout-19152) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you model a factless fact table to track daily student attendance and answer who was absent efficiently, and why is coverage tricky there? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Data Modeling (Star/Snowflake Schema) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-factless-fact-table-to-track-daily-student-atten-121427) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect guardrails and safety governance for a fleet of LLM-powered features on AWS — where do Bedrock Guardrails, a central content-moderation service, and per-team policy overrides fit, and how do you enforce a baseline no team can weaken? | deep understanding | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-guardrails-and-safety-governance-for-a-fleet-o-68578) |
| How would you define and enforce an org-wide quality regression budget for inference optimizations so cumulative small degradations across many quarters don't erode the product? | expertise | SDE-2/3, Architect/Principal | Inference Optimization (vLLM/TensorRT) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-define-and-enforce-an-org-wide-quality-regression-budget-71197) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You want an agent for a students app that can look up a topic and generate a quiz. What two tools would you expose and their parameters? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-an-agent-for-a-students-app-that-can-look-up-a-topic-and-gene-73638) |
| What's your strategy for evaluating a model's behavior on ambiguous prompts where multiple answers are valid and a single reference answer is wrong to grade against? | deep understanding | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-strategy-for-evaluating-a-model-s-behavior-on-ambiguous-pr-86908) |
