# Ambassador Labs

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 11

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 1 | 1 | 1 |
| DevOps | 0 | 0 | 8 | 9 | 7 | 9 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design how you'd verify a caller's identity at an API gateway once and forward a signed 'identity assertion' downstream, so backend services never re-run the full auth but still can't be spoofed. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-you-d-verify-a-caller-s-identity-at-an-api-gateway-once-and-26159) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You own developer experience for shipping to Kubernetes and the inner loop (build, deploy, test) is painfully slow across the org. As principal, how would you architect the local/remote dev experience (Tilt/Skaffold/Telepresence-class), measure DX quantitatively, and defend faster iteration as an investment rather than a vanity metric? | expertise | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-own-developer-experience-for-shipping-to-kubernetes-and-the-inner--39114) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You own developer experience for shipping to Kubernetes and the inner loop is painfully slow across the org. How would you architect the local/remote dev experience (Tilt/Skaffold/Telepresence-class), measure DX quantitatively, and defend faster iteration as an investment rather than a vanity metric to a skeptical CFO? | deep understanding | SDE-2/3, Architect/Principal | Kubernetes | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-own-developer-experience-for-shipping-to-kubernetes-and-the-inner--52202) |
| You need to parse and mutate thousands of Kubernetes YAML manifests programmatically while preserving comments and key order. Why does PyYAML lose comments, and how does ruamel.yaml solve it? | intermediate experience | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-parse-and-mutate-thousands-of-kubernetes-yaml-manifests-pr-45125) |
| You want a Python admission-webhook server for Kubernetes that rejects Pods without resource limits. How would you implement the TLS-served endpoint, parse the AdmissionReview, and keep latency low enough to not stall the API server? | expertise | SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-a-python-admission-webhook-server-for-kubernetes-that-rejects-45162) |
| A gRPC streaming call gets cut off at 15 minutes even though it should run longer. Explain how mesh route timeouts treat long-lived streams and how you'd exempt streaming routes. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-grpc-streaming-call-gets-cut-off-at-15-minutes-even-though-it-should-46626) |
| A meshed service behind an ingress gateway returns 404 for a path that works when called in-cluster. Walk through debugging Gateway host matching, VirtualService gateway binding, and route ordering. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-meshed-service-behind-an-ingress-gateway-returns-404-for-a-path-that-46662) |
| A service behind the mesh needs to accept both HTTP/1.1 and HTTP/2 (h2c) on the same port. Explain how Envoy does protocol detection and the failure mode when auto-detection guesses wrong. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-service-behind-the-mesh-needs-to-accept-both-http-1-1-and-http-2-h2c-46649) |
| You need to migrate an ingress from HTTP to HTTPS with automatic redirect, but health-check probes must stay HTTP. Design the Gateway config for the redirect and the carve-out for probes. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-migrate-an-ingress-from-http-to-https-with-automatic-redir-46669) |
| Your ingress gateway is a single deployment and it's saturated at peak. Explain how you'd horizontally scale the gateway, use HPA on it, and the connection-draining concern when gateway pods scale down. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-ingress-gateway-is-a-single-deployment-and-it-s-saturated-at-peak-46684) |
| Your ingress gateway terminates TLS but you need SNI-based routing to different backends by hostname. Explain how the Gateway TLS config and SNI matching route traffic and where a wildcard cert helps or hurts. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-ingress-gateway-terminates-tls-but-you-need-sni-based-routing-to--46639) |
