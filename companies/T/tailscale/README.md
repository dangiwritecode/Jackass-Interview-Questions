# Tailscale

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 3 | 3 | 5 | 5 | 1 | 5 |
| Fullstack | 0 | 0 | 0 | 2 | 2 | 2 |
| DevOps | 0 | 0 | 0 | 4 | 4 | 4 |
| AI Engineer | 1 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You want to add 'trusted internal callers can skip MFA but external users can't', keyed off network origin. Why is network location a weak authorization signal and what do you use instead in a zero-trust model? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-want-to-add-trusted-internal-callers-can-skip-mfa-but-external-use-26165) |
| What is a container's MTU, and why can Docker networking break behind a VPN or in certain cloud VPCs with packet fragmentation? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-container-s-mtu-and-why-can-docker-networking-break-behind-a-14321) |
| What is a scratch base image, and what does a Go binary need to run in a FROM scratch container (CA certs, timezone data)? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-scratch-base-image-and-what-does-a-go-binary-need-to-run-in--14283) |
| Why might a statically linked binary work in scratch but a CGO-enabled Go binary fail with 'no such file or directory'? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3 | Docker | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=why-might-a-statically-linked-binary-work-in-scratch-but-a-cgo-enabled-14284) |
| Explain how path MTU discovery works and why a Linux service behind a tunnel/VPN can hang on large responses when ICMP is blocked. How would you confirm an MTU black hole and mitigate with MSS clamping? | expertise | SDE-1/2, SDE-2/3 | Linux | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-path-mtu-discovery-works-and-why-a-linux-service-behind-a--26686) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you threat-model the developer's laptop as part of the production trust boundary? Local secrets, kubeconfigs, and cloud creds all sit there. Design the architecture that keeps a compromised endpoint from becoming production access. | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-threat-model-the-developer-s-laptop-as-part-of-the-producti-41266) |
| You're asked whether to allow Access-Control-Allow-Private-Network for an internal tool that a browser on the corporate LAN must call. Explain the Private Network Access spec, the threat it addresses (drive-by attacks on internal services), and your rollout stance. | deep understanding | SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-whether-to-allow-access-control-allow-private-network-for-38954) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| An auditor accepts your evidence but your own principal-engineering judgment says a control is theater. How do you navigate the gap between 'audit-passing' and 'actually-secure' — and what's your architectural strategy to close controls that satisfy paperwork but not adversaries? | expertise | SDE-2/3, Architect/Principal | Compliance & Governance (GDPR/SOC2/PCI) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=an-auditor-accepts-your-evidence-but-your-own-principal-engineering-ju-54057) |
| How do you architect the network exposure of Vault so the API is reachable by Agent Injectors and ESO across clusters but never from the public internet or low-trust segments? Discuss private endpoints, mTLS, and zero-trust segmentation. | deep understanding | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-network-exposure-of-vault-so-the-api-is-reach-54974) |
| How do you architect Vault-issued SSH certificates to replace static keys and jump-host sprawl for a 2000-server fleet? Compare signed-cert vs OTP mode operationally and for audit. | deep understanding | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-vault-issued-ssh-certificates-to-replace-static-k-54956) |
| You're challenged on whether the mesh's per-hop mTLS is redundant with a WireGuard-encrypted CNI already encrypting all pod traffic. Adjudicate the double-encryption cost vs the identity-vs-transport distinction, and whether you'd run both, one, or neither. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-challenged-on-whether-the-mesh-s-per-hop-mtls-is-redundant-with-52714) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What is a bastion or session-manager approach and why avoid exposing your vector database directly to the internet? | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | Cloud Fundamentals | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-bastion-or-session-manager-approach-and-why-avoid-exposing-y-76561) |
