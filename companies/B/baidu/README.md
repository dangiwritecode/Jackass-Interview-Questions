# Baidu

**Tier:** Tier 2  |  **Business domain:** Search/AI  |  **Questions:** 20

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| ML Engineer | 0 | 0 | 4 | 7 | 6 | 7 |
| AI Engineer | 0 | 0 | 0 | 2 | 2 | 2 |
| Data Structures & Algorithms (all profiles) | 11 | 11 | 11 | 11 | 11 | 11 |

## ML Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Explain how a parameter server differs from all-reduce for distributed training. What are the bottleneck and single-point-of-failure concerns of the parameter-server pattern, and why did all-reduce win for dense deep-learning workloads? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-a-parameter-server-differs-from-all-reduce-for-distributed-64508) |
| Explain the difference between synchronous SGD and asynchronous SGD across many workers. What is the stale-gradient problem in async training, and why do most teams still default to synchronous with large batches? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-the-difference-between-synchronous-sgd-and-asynchronous-sgd-ac-64472) |
| You want to compress gradients (quantization / sparsification) to cut all-reduce bandwidth in distributed training. Explain the bandwidth-versus-accuracy trade-off and how error feedback keeps compressed SGD from degrading convergence. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-compress-gradients-quantization-sparsification-to-cut-all--64554) |
| Walk me through a multi-year migration from a parameter-server legacy stack to a collective-based FSDP platform without freezing model delivery for the teams that depend on it. | expertise | SDE-2/3, Architect/Principal | Distributed Training (Data/Model Parallelism) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-a-multi-year-migration-from-a-parameter-server-legacy--70671) |
| How would you mine hard negatives for training a retrieval model, and why do hard negatives risk introducing false negatives you have to filter? | deep understanding | SDE-1/2, SDE-2/3 | Embeddings & Vector Search | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-mine-hard-negatives-for-training-a-retrieval-model-and-w-64272) |
| When would you choose synchronous versus asynchronous distributed training for a large model and how does the choice interact with straggler nodes and network topology? | deep understanding | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-synchronous-versus-asynchronous-distributed-trai-70476) |
| Your org wants a single distributed training platform for Transformers from 1B to 500B parameters; how do you design the parallelism abstraction so teams do not hand-tune sharding? | expertise | SDE-2/3, Architect/Principal | Transformers & Attention | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-wants-a-single-distributed-training-platform-for-transformers-70378) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Walk me through serving a recommendation model whose embedding tables exceed single-host memory and must be sharded across a parameter-server tier. | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=walk-me-through-serving-a-recommendation-model-whose-embedding-tables--84359) |
| When would you choose synchronous versus asynchronous distributed training, and how does the choice interact with stragglers and network topology? | expertise | SDE-2/3, Architect/Principal | ML System Design | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=when-would-you-choose-synchronous-versus-asynchronous-distributed-trai-84416) |

## Data Structures & Algorithms

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Clear the Row of Colored Beads With the Fewest Inserts | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Backtracking, Depth-First Search, Dynamic Programming, Memoization, Recursion, String | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=clear-the-row-of-colored-beads-with-the-fewest-inserts-d488) |
| Count Arithmetic Progression Subsequences of Length Three or More | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Hash Table, Subsequence | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-arithmetic-progression-subsequences-of-length-three-or-more-d446) |
| Count Contiguous Constant-Step Segments | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Dynamic Programming, Prefix Counting, Running Counter, Sliding Window | Online Assessment (OA), DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=count-contiguous-constant-step-segments-d413) |
| Counting Ways to Step a Token Off a Board | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Breadth-First Search, Counting, Dynamic Programming, Grid Traversal, Memoization, Modular Arithmetic | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=counting-ways-to-step-a-token-off-a-board-d571) |
| In-Memory Hierarchical File System | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Design, Hash Table, Sorting, String, Tree, Trie | DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=in-memory-hierarchical-file-system-d580) |
| Largest Sum Along Any Path in a Binary Tree | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Binary Tree, Depth-First Search, Dynamic Programming, Post-order Traversal, Recursion, Tree | Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=largest-sum-along-any-path-in-a-binary-tree-d124) |
| Longest Additive Chain Hidden in a Sorted Array | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Dynamic Programming, Hash Table, Sequence, Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-additive-chain-hidden-in-a-sorted-array-d858) |
| Longest Substring Where Every Letter Meets a Minimum Count | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Counting, Divide and Conquer, Hash Table, Sliding Window, String, Two Pointers | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=longest-substring-where-every-letter-meets-a-minimum-count-d395) |
| Minimize the Largest Segment Sum When Partitioning an Array | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Binary Search on Answer, Dynamic Programming, Greedy, Prefix Sum | Online Assessment (OA), DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=minimize-the-largest-segment-sum-when-partitioning-an-array-d410) |
| Minimum Steps to Reduce a Number to One | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Bit Manipulation, Dynamic Programming, Greedy, Math, Memoization | Online Assessment (OA), Phone Screen, DSA/Coding Round | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=minimum-steps-to-reduce-a-number-to-one-d397) |
| Search a Value in a Row-and-Column Sorted Grid | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Array, Binary Search, Divide and Conquer, Matrix, Two Pointers | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | DSA | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=search-a-value-in-a-row-and-column-sorted-grid-d240) |
