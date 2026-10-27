# Netdata

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 15

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| DevOps | 0 | 0 | 13 | 13 | 0 | 13 |
| AIOps | 1 | 0 | 1 | 1 | 0 | 2 |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A Cilium eBPF program is dropping packets intermittently under load. How would you use bpftool and the verifier logs to figure out where in the datapath the drop happens? | expertise | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-cilium-ebpf-program-is-dropping-packets-intermittently-under-load-ho-51828) |
| An eBPF map is filling up and evicting entries you care about. Walk me through LRU vs non-LRU maps and how you'd size the map for your workload's connection churn. | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-ebpf-map-is-filling-up-and-evicting-entries-you-care-about-walk-me--51862) |
| An eBPF program fails to load with 'invalid mem access' from the verifier. What does that error usually mean and how do you fix it without disabling verification? | expertise | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-ebpf-program-fails-to-load-with-invalid-mem-access-from-the-verifie-51836) |
| Explain how you'd use eBPF to detect noisy-neighbor CPU steal or memory pressure affecting a specific workload on a shared node. | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-use-ebpf-to-detect-noisy-neighbor-cpu-steal-or-memor-51910) |
| How do you approach capacity planning for eBPF map memory across a node fleet, given maps are locked (non-swappable) kernel memory? | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-approach-capacity-planning-for-ebpf-map-memory-across-a-nod-51898) |
| How do you decide the right ring-buffer size for an eBPF event pipeline, and what symptoms tell you it's too small versus wasting memory when too big? | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-decide-the-right-ring-buffer-size-for-an-ebpf-event-pipelin-51883) |
| How do you safely roll back a bad eBPF program that's already loaded and pinned in the BPF filesystem across hundreds of nodes? | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-safely-roll-back-a-bad-ebpf-program-that-s-already-loaded-a-51843) |
| You need to measure syscall latency for a specific process to debug a slow container startup. Which eBPF tools (execsnoop, syscount, funclatency) do you reach for and why? | intermediate experience | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-measure-syscall-latency-for-a-specific-process-to-debug-a--51869) |
| You want per-container disk IO latency without app changes. Which block-layer tracepoints would you attach and how do you map the request back to a container? | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-per-container-disk-io-latency-without-app-changes-which-block-51880) |
| You want to measure real TCP retransmits per service to catch a flaky node. Which tracepoints or kprobes would you attach and how do you aggregate the data cheaply? | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-measure-real-tcp-retransmits-per-service-to-catch-a-flaky--51847) |
| You want to trace which pod is exhausting a shared node's file-descriptor limit. Which eBPF hooks give you per-pod FD accounting and how do you aggregate it? | deep understanding | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-trace-which-pod-is-exhausting-a-shared-node-s-file-descrip-51917) |
| You're seeing 'BPF program too large' at load time. What are your options to shrink it, and how does the 1-million-instruction verifier limit constrain complex logic? | expertise | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-seeing-bpf-program-too-large-at-load-time-what-are-your-options-51858) |
| Your CI builds eBPF objects but they fail to load on production nodes with a relocation error. How does a mismatch between build-time and runtime BTF cause this and how do you fix it? | expertise | SDE-1/2, SDE-2/3 | eBPF | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-ci-builds-ebpf-objects-but-they-fail-to-load-on-production-nodes--51878) |

## AIOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you overlay a static alert threshold line on a metrics chart using axhline? | basic concept | Fresher | Data Visualization (Matplotlib/Seaborn) | Online Assessment (OA), Phone Screen | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-overlay-a-static-alert-threshold-line-on-a-metrics-chart-89829) |
| You containerize an anomaly-detection service that scores a per-service metric stream, but during a metrics storm it falls behind and starts flagging stale windows. How would you design the container's concurrency, buffering, and readiness so it sheds load rather than emitting false anomalies? | deep understanding | SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-containerize-an-anomaly-detection-service-that-scores-a-per-servic-92327) |
