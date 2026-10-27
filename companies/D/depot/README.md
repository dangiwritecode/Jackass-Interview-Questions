# Depot

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 3 | 3 | 3 | 3 | 0 | 3 |
| DevOps | 0 | 0 | 8 | 8 | 2 | 8 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do BuildKit cache mounts (RUN --mount=type=cache) speed up dependency installs, and when would you use them? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-buildkit-cache-mounts-run-mount-type-cache-speed-up-dependency--14278) |
| How does Docker layer caching work in GitHub Actions, and how do gha cache or registry cache backends speed up buildx builds? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-docker-layer-caching-work-in-github-actions-and-how-do-gha-ca-14338) |
| Your build cache keeps growing on a CI runner and fills the disk. How do you prune build cache selectively while keeping recent layers? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-build-cache-keeps-growing-on-a-ci-runner-and-fills-the-disk-how-d-14360) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you architect ephemeral CI runners on ECS Fargate so each build gets a clean isolated environment with no state leakage, and how do you cache dependencies to keep builds fast without persistent runners? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-ephemeral-ci-runners-on-ecs-fargate-so-each-bu-46203) |
| Your team wants to move build artifacts and Docker layer caching off the build machine's local disk — how would you use S3-backed cache and ECR pull-through cache to speed cold builds across an ephemeral runner fleet? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | AWS | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-team-wants-to-move-build-artifacts-and-docker-layer-caching-off-t-46210) |
| A build with BuildKit caches inconsistently because a RUN pulls the current date into a layer; how do you find and eliminate such cache-busting non-determinism? | deep understanding | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-build-with-buildkit-caches-inconsistently-because-a-run-pulls-the-cu-45859) |
| How would you architect a Docker build cache that is shared across a fleet of ephemeral CI runners without one runner poisoning another's cache? | expertise | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-a-docker-build-cache-that-is-shared-across-a-f-45826) |
| How would you design build and cache so an urgent security-patch rebuild of all services completes in minutes rather than serially over hours? | expertise | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-build-and-cache-so-an-urgent-security-patch-rebui-45910) |
| How would you make a multi-stage build cache the expensive compile stage in a shared remote cache while keeping the fast final assembly per-build? | expertise | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-make-a-multi-stage-build-cache-the-expensive-compile-sta-45879) |
| How would you profile which Dockerfile instructions dominate build wall-clock time and reorder or parallelize them with BuildKit? | intermediate experience | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-profile-which-dockerfile-instructions-dominate-build-wal-45830) |
| Your build's final image differs between local Docker and CI buildx; how would you reconcile builder-driver differences to get consistent output? | deep understanding | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-build-s-final-image-differs-between-local-docker-and-ci-buildx-ho-45899) |
