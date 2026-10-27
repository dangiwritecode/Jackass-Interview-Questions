# Semgrep

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 4 | 5 | 5 | 5 |
| Fullstack | 0 | 0 | 0 | 3 | 3 | 3 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design an authorization policy test harness that generates adversarial requests (wrong tenant, missing scope, tampered id) and asserts every one is denied, integrated into CI as a gate. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-authorization-policy-test-harness-that-generates-adversarial-26166) |
| Your team keeps shipping IDOR bugs. Beyond code review, how would you design a framework-level default (deny-by-default resource loading that requires an explicit ownership check) so new endpoints can't forget authz? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-team-keeps-shipping-idor-bugs-beyond-code-review-how-would-you-de-26228) |
| How would you design CI to fail when a new endpoint is added without a corresponding authorization check or rate limit, using static analysis rather than relying on reviewer vigilance? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-ci-to-fail-when-a-new-endpoint-is-added-without-a-26986) |
| Design the CI/build architecture that structurally prevents anyone from concatenating a variable into SQL across a polyglot codebase mixing ORM, raw queries, and stored procs. Discuss the static-analysis approach, false-positive management, and how you make the gate non-bypassable without blocking legit dynamic SQL. | expertise | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-the-ci-build-architecture-that-structurally-prevents-anyone-fro-32871) |
| Your service builds queries via a string-templating helper that everyone thinks is safe because it 'has placeholders'; describe how you'd write a static-analysis rule to distinguish real bind placeholders from format-string interpolation. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-service-builds-queries-via-a-string-templating-helper-that-everyo-26392) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a fitness-function suite that enforces, in CI across a polyglot fleet, that no cross-context call bypasses the anti-corruption layer and no service opens more than its allotted Object-Pool of connections? | deep understanding | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-fitness-function-suite-that-enforces-in-ci-a-38517) |
| How would you architect a Visitor-based static-analysis pass over a large polyglot monorepo to detect anti-pattern usage (god objects, cyclic deps), and why does the 'hard to add node types' Visitor weakness actually not bite you here? | deep understanding | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-visitor-based-static-analysis-pass-over-a-la-38477) |
| How would you architect a CI gate that fails builds on new unsafe query construction across an ORM+raw+stored-proc polyglot without drowning teams in false positives on legitimate dynamic SQL? Describe the taint-analysis approach and the appeal/suppression workflow. | expertise | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-ci-gate-that-fails-builds-on-new-unsafe-quer-38985) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide governance for AI-assisted coding tools org-wide — what DevSecOps controls do you add when developers ship large volumes of LLM-generated code? | expertise | SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-governance-for-ai-assisted-coding-tools-org-wide-wha-55057) |
| How do you set the org standard for handling a deeply-embedded dependency with a known CVE and no fix — architecturally isolate, vendor, or accept the risk? | deep understanding | SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-set-the-org-standard-for-handling-a-deeply-embedded-depende-55099) |
| Present a strategy for reachability-based vulnerability prioritization at fleet scale — how do you fund the tooling and change developer behavior around it? | expertise | SDE-2/3, Architect/Principal | DevSecOps | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=present-a-strategy-for-reachability-based-vulnerability-prioritization-55056) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you audit a large existing codebase to find every transaction whose correctness silently depends on the current default isolation level? What tooling would you build? | expertise | SDE-2/3, Architect/Principal | Isolation Levels (RU/RC/RR/Serializable) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-audit-a-large-existing-codebase-to-find-every-transaction-w-113676) |
