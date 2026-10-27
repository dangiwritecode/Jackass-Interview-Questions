# Imbue

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| AI Engineer | 0 | 0 | 3 | 7 | 4 | 7 |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| At what recursion depth does agents-calling-agents-as-tools become a scaling and cost hazard? Design the architectural limit you impose, how you enforce it, and how you keep the depth cap from silently truncating legitimate delegation. | deep understanding | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=at-what-recursion-depth-does-agents-calling-agents-as-tools-become-a-s-83117) |
| Design a progressive-autonomy architecture: an agent starts suggest-only, graduates to auto-execute-with-undo, then full autonomy, gated by measured trust. What signals promote or demote autonomy automatically, and what stops gaming of those signals? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-progressive-autonomy-architecture-an-agent-starts-suggest-onl-83085) |
| You must find whether an agent's proposed action sequence revisits a previously explored world-state to prune redundant planning; what hashing of state gives you O(1) visited checks, and how do you handle near-equivalent states? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-find-whether-an-agent-s-proposed-action-sequence-revisits-a-p-76758) |
| Your agent maintains a plan tree that gets revised as tools return; when a subtask fails you must re-plan only the affected branch in O(depth), not rebuild the whole tree; what immutable-tree or path-update approach enables that? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-agent-maintains-a-plan-tree-that-gets-revised-as-tools-return-whe-76738) |
| Your agent must plan over a state graph where nodes are world-states and edges are tool actions; when is BFS the right search versus a cost-aware A*, and what makes an admissible heuristic for reaching a goal state? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-agent-must-plan-over-a-state-graph-where-nodes-are-world-states-a-76713) |
| How do you evaluate long-horizon agent tasks where a full trajectory takes minutes and running thousands for statistical power is infeasible? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-evaluate-long-horizon-agent-tasks-where-a-full-trajectory-t-86869) |
| How would you design eval to detect reward hacking in an RL-trained agent that games the metric without achieving the intended outcome? | expertise | SDE-2/3, Architect/Principal | Evaluation at Scale | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-eval-to-detect-reward-hacking-in-an-rl-trained-ag-86895) |
