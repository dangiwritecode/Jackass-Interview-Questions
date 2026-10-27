# BuildBuddy

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 4

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 0 | 4 | 4 | 4 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A principal probe on cost: you claim aggressive caching cut CI cost dramatically. Prove the cache isn't silently masking real failures or shipping stale artifacts; what correctness invariants must the cache-key derivation guarantee at fleet scale, and how do you continuously audit for cache poisoning without disabling the cache? | expertise | SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-probe-on-cost-you-claim-aggressive-caching-cut-ci-cost-dra-52324) |
| A principal probe on cost: you claim aggressive distributed caching cut CI spend by millions. Prove the cache can't silently poison builds or mask real failures; what correctness invariants must the cache-key derivation guarantee, and how do you continuously verify cache integrity at fleet scale? | expertise | SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-probe-on-cost-you-claim-aggressive-distributed-caching-cut-52275) |
| You're asked to justify keeping build and test on a dedicated remote-execution cluster (Bazel RBE / BuildBuddy-style) versus commodity CI runners at 3000 engineers; quantify the caching and parallelism payoff against the operational burden and who pays the BUILD-file maintenance tax. | deep understanding | SDE-2/3, Architect/Principal | CI/CD | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-justify-keeping-build-and-test-on-a-dedicated-remote-e-52241) |
| How would you architect the platform's approach to build-cache and CI at org scale (remote caching, build farms, monorepo versus polyrepo tooling) so build time doesn't linearly degrade as the codebase and team count grow tenfold? | deep understanding | SDE-2/3, Architect/Principal | Platform Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-the-platform-s-approach-to-build-cache-and-ci--54278) |
