# Oso

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 6 | 7 | 3 | 7 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 3 | 3 | 3 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design authorization caching where the cache key must include user, resource, action, AND the policy version — so a policy change invalidates only affected entries? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-authorization-caching-where-the-cache-key-must-in-26155) |
| Your access-control list for a resource can grow to thousands of entries (per-user shares). How do you keep the 'can X read this' check fast without scanning the whole ACL, and how does this compare to a Zanzibar tuple store? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-access-control-list-for-a-resource-can-grow-to-thousands-of-entri-26196) |
| How do you architect a globally distributed authorization/entitlements service such that a partition can never grant an entitlement that was just revoked, while still staying available for the far more common allow-decisions? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-globally-distributed-authorization-entitlements-32260) |
| A recursive tree-walk builds a permission decision by merging inherited grants; it re-visits shared subtrees repeatedly; how do you add memoization keyed on subtree identity and prove it stays correct with cycles? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-recursive-tree-walk-builds-a-permission-decision-by-merging-inherite-21956) |
| On this project, tell me about a query that let a user access data they shouldn't have, and how you closed the authorization gap. | expertise | SDE-1/2, SDE-2/3 | Projects (Resume Deep-Dive) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=on-this-project-tell-me-about-a-query-that-let-a-user-access-data-they-28287) |
| A backtracking rule/permission solver has a large branching factor; how do you reason about its O(b^d) worst case, where pruning and constraint propagation cut the effective base, and how to bound it in prod? | expertise | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-backtracking-rule-permission-solver-has-a-large-branching-factor-how-22115) |
| How do you reason about the complexity of a permission check cached per (user, resource) pair, where the cache is O(users x resources) in the worst case, and how you'd bound it with scoping and TTL? | deep understanding | SDE-1/2, SDE-2/3 | Time & Space Complexity | Online Assessment (OA), Phone Screen, DSA/Coding Round | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-reason-about-the-complexity-of-a-permission-check-cached-pe-22107) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you decide whether to standardize authorization on the Specification pattern in-code versus an external policy engine, framing the build-vs-buy over five years including audit, compliance, and policy-author ergonomics for non-engineers? | expertise | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-whether-to-standardize-authorization-on-the-specific-38507) |
| You're deciding whether authorization should be a Specification-pattern policy library embedded per service or an external decision point (PDP) queried at request time. What are the latency, staleness, and blast-radius trade-offs at fleet scale? | expertise | SDE-2/3, Architect/Principal | Design Patterns | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-whether-authorization-should-be-a-specification-patter-38440) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect a fine-grained authorization system for a deep resource hierarchy (org to team to project to resource) that must be sub-millisecond per request and centrally auditable — where do JWT claims, a policy engine like Cedar/OPA, and DynamoDB each fit? | expertise | SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-fine-grained-authorization-system-for-a-deep-52415) |
| How do you architect a policy-decision-point for authorization at fleet scale (Zanzibar-style relationship-based access) so 500 services enforce consistent fine-grained authz without each embedding brittle if-checks, and what's the caching/consistency trade-off? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-a-policy-decision-point-for-authorization-at-flee-51974) |
| You're designing least-privilege authorization propagation (user identity + delegated service identity + resource scopes) across a deep call chain. How do you prevent confused-deputy at scale and decide between token exchange, macaroons, and a central PDP? | expertise | SDE-2/3, Architect/Principal | Microservices | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-designing-least-privilege-authorization-propagation-user-identi-51973) |
