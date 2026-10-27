# Truecaller

**Tier:** Tier 2  |  **Business domain:** SaaS  |  **Questions:** 16

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 2 | 2 | 5 | 5 | 2 | 5 |
| Fullstack | 2 | 2 | 2 | 7 | 6 | 7 |
| ML Engineer | 3 | 0 | 4 | 4 | 3 | 4 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design how you'd support 'login with phone number' with number portability and reassignment — a recycled phone number must not grant access to the previous owner's account. What checks close this gap? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-d-support-login-with-phone-number-with-number-portabili-26218) |
| Solve the classic backtracking problem of placing letters to form all valid phone-keypad words. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=solve-the-classic-backtracking-problem-of-placing-letters-to-form-all--8198) |
| Design a Trie-backed contact/phone-book search. What classes and how does prefix search work? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-trie-backed-contact-phone-book-search-what-classes-and-how-do-8948) |
| How would you design Redis-backed short-lived OTP storage that resists brute force, enforces attempt limits, and cleans up on success — atomically checking and burning the code? | deep understanding | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-redis-backed-short-lived-otp-storage-that-resists-24686) |
| How would you use Redis to enforce a global unique-constraint (e.g. one active phone number per account) that must be immediately consistent even before the DB commits? | expertise | SDE-1/2, SDE-2/3 | Redis | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-redis-to-enforce-a-global-unique-constraint-e-g-one--24708) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how you would treat 'privacy' (data minimization, consent enforcement, right-to-erasure latency) as a first-class quality attribute in the utility tree, and give a scenario that turns GDPR/DPDP compliance into a measurable tradeoff. | deep understanding | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-would-treat-privacy-data-minimization-consent-enforcem-40526) |
| How would you model a friend-suggestion feature as a graph problem and which traversal fits? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-model-a-friend-suggestion-feature-as-a-graph-problem-and-8220) |
| Design a frontend platform that must serve the next billion users on low-end Android and 2G/3G — how do you architect for constrained CPU, memory, and bandwidth without abandoning rich features? | expertise | SDE-2/3, Architect/Principal | Frontend System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-frontend-platform-that-must-serve-the-next-billion-users-on-l-40077) |
| Architect a consent-and-privacy platform that gates every data access across the company by user consent state — how do you make the consent check fast propagate a withdrawal within seconds and prove to auditors no code path bypassed it? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-a-consent-and-privacy-platform-that-gates-every-data-access--39436) |
| Design a right-to-be-forgotten deletion architecture that must purge a user across 60 services CDC streams backups and a warehouse within a legal deadline — how do you orchestrate the fan-out prove completeness and handle backups you can't selectively edit? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-right-to-be-forgotten-deletion-architecture-that-must-purge-a-39473) |
| Design a Trie-backed contact/phone-book search. What classes and how does prefix search work? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-trie-backed-contact-phone-book-search-what-classes-and-how-do-8948) |
| You must design the org's canonical 'phone number / email / address' value objects with parsing, normalization, and equality so 'the same number in two formats' compares equal; how do you handle locale-specific rules without the type becoming a giant validation monolith? | deep understanding | SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-the-org-s-canonical-phone-number-email-address-value-o-38361) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a lightweight offline-capable prediction feature for an app used in low-connectivity areas? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-lightweight-offline-capable-prediction-feature--62155) |
| How would you design a system to flag potentially fake or bot accounts on a platform? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-system-to-flag-potentially-fake-or-bot-accounts-62139) |
| What considerations would you have when serving an ML model on a mobile device instead of a server? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-considerations-would-you-have-when-serving-an-ml-model-on-a-mobil-62116) |
| How would you serve a model at the edge on mobile while keeping the ability to hot-swap the model without an app store release? | deep understanding | SDE-1/2, SDE-2/3 | Model Deployment & Serving | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-serve-a-model-at-the-edge-on-mobile-while-keeping-the-ab-66797) |
