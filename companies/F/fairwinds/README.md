# Fairwinds

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 7

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 3 | 5 | 4 | 5 |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You must design how the org handles Kubernetes deprecated-API detection and remediation continuously so an upgrade never surprises anyone. How would you wire scanning (Pluto/kubent), admission-time blocking of deprecated APIs, and an org policy that keeps the long tail of manifests current across dozens of teams? | deep understanding | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-design-how-the-org-handles-kubernetes-deprecated-api-detectio-39059) |
| Your org's clusters have drifted to inconsistent kernel, CNI, and CSI versions, causing hard-to-reproduce incidents. As principal, how would you architect a golden-cluster-config and continuous-conformance program so drift is detected and remediated automatically, without freezing teams' ability to adopt new features? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-org-s-clusters-have-drifted-to-inconsistent-kernel-cni-and-csi-ve-39068) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| During a cluster upgrade, a deprecated API version broke controllers you didn't know depended on it. How do you make Kubernetes upgrades resilient by catching deprecated-API usage before the upgrade? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=during-a-cluster-upgrade-a-deprecated-api-version-broke-controllers-yo-47010) |
| A deprecated API is being removed cluster-wide and hundreds of manifests across dozens of teams still use it. As principal, how would you drive the org-wide remediation (Pluto/kubent scanning plus admission-time blocking of new usage) and avoid a coordinated break at upgrade time without stalling every team's roadmap? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-deprecated-api-is-being-removed-cluster-wide-and-hundreds-of-manifes-52216) |
| You inherit manifests using a Kubernetes API version that's removed in the next upgrade. How would you find every affected object across namespaces before the upgrade breaks them? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherit-manifests-using-a-kubernetes-api-version-that-s-removed-in-45958) |
| Describe how you'd design the platform's rollout of a Kubernetes version upgrade across hundreds of clusters and thousands of workloads, including handling deprecated APIs, so a version EOL never becomes a fire drill. What's automated versus gated? | deep understanding | SDE-2/3, Architect/Principal | Platform Engineering | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=describe-how-you-d-design-the-platform-s-rollout-of-a-kubernetes-versi-54250) |
| You want to fail CI when a Kubernetes YAML uses a deprecated API. What tools (kubeconform, pluto) do you wire in and how do they read the YAML kind/apiVersion to decide? | intermediate experience | SDE-1/2, SDE-2/3 | YAML | Online Assessment (OA), Phone Screen | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-fail-ci-when-a-kubernetes-yaml-uses-a-deprecated-api-what--48973) |
