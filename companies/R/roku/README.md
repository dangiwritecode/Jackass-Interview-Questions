# Roku

**Tier:** Tier 3  |  **Business domain:** Streaming  |  **Questions:** 27

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 0 | 3 | 3 | 3 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Engineer | 0 | 0 | 0 | 3 | 3 | 3 |
| ML Engineer | 0 | 0 | 1 | 1 | 0 | 1 |
| AI Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Data Structures & Algorithms (all profiles) | 18 | 18 | 18 | 18 | 18 | 18 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your org runs both a strongly consistent core and a constellation of eventually consistent edge services. Define the architectural contract at the boundary so the edge can never leak an unsafe stale value back into a decision the core treats as authoritative. | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-runs-both-a-strongly-consistent-core-and-a-constellation-of-e-32211) |
| You're accountable for cost of a video platform where 90% of egress is a long tail of rarely-watched content. Design the tiered-storage + CDN strategy (hot edge, warm regional, cold origin) that minimizes cost while keeping start latency acceptable. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-accountable-for-cost-of-a-video-platform-where-90-of-egress-is--35070) |
| Your product spans web, mobile, and TV apps that all hit the same edge. Design a delivery strategy that serves each client optimally (bundle strategy, HTTP/3, adaptive media) while keeping a single coherent, cost-governed edge platform. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-product-spans-web-mobile-and-tv-apps-that-all-hit-the-same-edge-d-35049) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Your product spans web, mobile, and TV apps that all hit the same edge. Design a delivery strategy that serves each client optimally (bundle strategy, HTTP/3, adaptive media) while keeping a single coherent, cost-governed edge platform. | expertise | SDE-2/3, Architect/Principal | CDN | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-product-spans-web-mobile-and-tv-apps-that-all-hit-the-same-edge-d-35049) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| CCPA gives consumers a right to opt out of the sale or sharing of personal information; how do you engineer that opt-out to actually gate data leaving your platform to third-party adtech partners? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=ccpa-gives-consumers-a-right-to-opt-out-of-the-sale-or-sharing-of-pers-127320) |
| CCPA's definition of personal information is broader than PII including household and device data; how does that broader scope change your classification model and tagging taxonomy? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=ccpa-s-definition-of-personal-information-is-broader-than-pii-includin-127350) |
| How do you architect for cross-device and probabilistic identity matching in a way you can actually defend to a regulator on accuracy and consent? | deep understanding | SDE-2/3, Architect/Principal | Regulatory Data Compliance (GDPR/CCPA) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-for-cross-device-and-probabilistic-identity-match-127376) |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you enforce a per-request inference latency budget in FastAPI so a slow model call is cancelled and a cheaper fallback model or cached prediction is returned instead? | deep understanding | SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-enforce-a-per-request-inference-latency-budget-in-fastap-62895) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You inherit five product agents each with a divergent tool-calling adapter. Sketch the strangler-fig migration to one adapter standard that never freezes feature delivery for a quarter, and name the irreversible step. | deep understanding | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherit-five-product-agents-each-with-a-divergent-tool-calling-ada-83044) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Almost a Palindrome: Remove at Most One Character | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Greedy, Palindrome, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=almost-a-palindrome-remove-at-most-one-character-d665) |
| Colliding Blocks on a Frictionless Rail | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Monotonic Stack, Simulation, Stack | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=colliding-blocks-on-a-frictionless-rail-d720) |
| Column-by-Column (Vertical) Traversal of a Binary Tree | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Binary Tree, Breadth-First Search, Depth-First Search, Hash Table, Sorting, Tree | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=column-by-column-vertical-traversal-of-a-binary-tree-d972) |
| Expand a Nested Repeat-Notation String | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Parsing, Recursion, Stack, String | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=expand-a-nested-repeat-notation-string-d394) |
| Fewest Moves for a Robot to Collect Every Keycard in a Facility | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Bit Manipulation, Bitmask, Breadth-First Search, Grid, Matrix, Shortest Path, State-space Search | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=fewest-moves-for-a-robot-to-collect-every-keycard-in-a-facility-d849) |
| Largest Connected Block of Land in a Binary Grid | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Breadth-First Search, Connected Components, Depth-First Search, Flood Fill, Matrix, Union Find | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=largest-connected-block-of-land-in-a-binary-grid-d680) |
| Largest Product of Any Three Elements | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Math, Running Extremes, Sorting | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=largest-product-of-any-three-elements-d613) |
| Longest Run of Passing Readings With Limited Overrides | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Prefix Sum, Sliding Window, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-run-of-passing-readings-with-limited-overrides-d989) |
| Longest Well-Formed Bracket Run | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Dynamic Programming, Stack, String, Two Pointers | DSA/Coding Round, Onsite, Hiring Manager | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-well-formed-bracket-run-d32) |
| Minimum Reward Tokens for a Row of Workers | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Greedy, Prefix/Suffix Aggregation, Two-Pass Scan | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=minimum-reward-tokens-for-a-row-of-workers-d135) |
| Minimum Spend to Cover All Visit Days | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Bottom-up DP, Dynamic Programming, Interval Covering | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=minimum-spend-to-cover-all-visit-days-d968) |
| Product of Two Large Numbers Given as Digit Strings | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Arrays, Math, Number Theory, Simulation, String | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=product-of-two-large-numbers-given-as-digit-strings-d43) |
| Reach the Target of Twenty-Four | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Backtracking, Floating-Point Comparison, Math, Recursion | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=reach-the-target-of-twenty-four-d664) |
| Split A Bit Array Into Three Equal-Value Blocks | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Bit Manipulation, Greedy, Math, Two Pointers | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=split-a-bit-array-into-three-equal-value-blocks-d912) |
| The K Most Frequently Occurring Values in an Array | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Bucket Sort, Counting, Divide and Conquer, Hash Table, Heap (Priority Queue), Quickselect, Sorting | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=the-k-most-frequently-occurring-values-in-an-array-d347) |
| Triplets That Sum to Zero | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Sorting, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=triplets-that-sum-to-zero-d15) |
| Typed Text Equivalence with a Delete Key | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Simulation, Stack, String, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=typed-text-equivalence-with-a-delete-key-d829) |
| Wildcard Bracket Balance Check | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Dynamic Programming, Greedy, Stack, String, Two Counters / Balance Range | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=wildcard-bracket-balance-check-d663) |
