# Astral

**Tier:** Tier 2  |  **Business domain:** —  |  **Questions:** 8

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 3 | 3 | 0 | 3 |
| ML Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| AI Engineer | 0 | 0 | 0 | 3 | 3 | 3 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you'd use uv or pip-tools in a Python project's Dockerfile to get fully reproducible, hash-locked builds, and why an unpinned pip install in a base image is a supply-chain risk. | deep understanding | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-use-uv-or-pip-tools-in-a-python-project-s-dockerfile-45177) |
| How would you package a Python CLI tool your platform team distributes internally so it's installable via pipx with pinned deps, and why does bundling with a lockfile or a zipapp/PEX beat a bare pip install? | intermediate experience | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-package-a-python-cli-tool-your-platform-team-distributes-45176) |
| How would you use pytest fixtures and parametrization to test a Python function that generates cloud resource names across dozens of naming conventions without writing dozens of near-identical test functions? | intermediate experience | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-pytest-fixtures-and-parametrization-to-test-a-python-45199) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you handle Python dependency and environment management at platform scale so that thousands of jobs are reproducible and you're not stuck in perpetual CUDA/driver/framework version wars? | deep understanding | SDE-2/3, Architect/Principal | ML Platform Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-python-dependency-and-environment-management-at-plat-72028) |
| Explain how you'd design a Python dependency-resolution and lock strategy that lets 50 teams share a common ML base image while still pinning team-specific extras reproducibly, avoiding a monolithic requirements file that no one can update. | deep understanding | SDE-2/3, Architect/Principal | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-design-a-python-dependency-resolution-and-lock-strat-68381) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Compare uv, Poetry and pip-tools for locking a large Python AI platform's dependencies. What criteria (resolution speed, reproducibility, CI cost, native-wheel handling for CUDA) drive your org-wide standard, and how do you migrate 100 repos? | deep understanding | SDE-2/3, Architect/Principal | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=compare-uv-poetry-and-pip-tools-for-locking-a-large-python-ai-platform-82341) |
| Explain how you'd offload CPU-heavy pre/post-processing (tokenization, image decode, JSON parsing) out of the Python event loop at scale: threadpool vs processpool vs Rust/PyO3 native extension, and how you decide. | deep understanding | SDE-2/3, Architect/Principal | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-offload-cpu-heavy-pre-post-processing-tokenization-i-82391) |
| How would you design an org-wide Python style/lint/type-check baseline (ruff, mypy, pyright) enforced in CI for 100+ AI repos, and how do you roll it out without blocking every team's PRs on day one? | deep understanding | SDE-2/3, Architect/Principal | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-an-org-wide-python-style-lint-type-check-baseline-82394) |
