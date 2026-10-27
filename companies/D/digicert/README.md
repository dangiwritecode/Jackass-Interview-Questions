# DigiCert

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 17

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 3 | 3 | 0 | 0 | 0 | 3 |
| Fullstack | 2 | 2 | 0 | 0 | 0 | 2 |
| DevOps | 1 | 0 | 2 | 12 | 11 | 12 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How does an SSL/TLS certificate prove a server's identity? | intermediate experience | Fresher, SDE-1 | Computer Networks | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-an-ssl-tls-certificate-prove-a-server-s-identity-575) |
| What is a certificate authority and what is the chain of trust? | deep understanding | Fresher, SDE-1 | Computer Networks | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-certificate-authority-and-what-is-the-chain-of-trust-576) |
| What is OCSP and how does a browser check whether a certificate has been revoked? | expertise | Fresher, SDE-1 | Computer Networks | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-ocsp-and-how-does-a-browser-check-whether-a-certificate-has-be-8669) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How does an SSL/TLS certificate prove a server's identity? | intermediate experience | Fresher, SDE-1 | Computer Networks | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-does-an-ssl-tls-certificate-prove-a-server-s-identity-575) |
| What is a certificate authority and what is the chain of trust? | deep understanding | Fresher, SDE-1 | Computer Networks | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-certificate-authority-and-what-is-the-chain-of-trust-576) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you design an org-wide TLS and certificate-management strategy on Azure so no service ever pages at 2am for an expired cert, spanning App Gateway, Front Door, and AKS ingress? | deep understanding | SDE-2/3, Architect/Principal | Azure | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-an-org-wide-tls-and-certificate-management-strategy--54589) |
| How do you ensure your BCP accounts for clock, time-zone, and certificate-expiry issues that quietly break failover, like an expired cert in the standby region nobody rotated? | deep understanding | SDE-2/3, Architect/Principal | Business Continuity Planning | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-ensure-your-bcp-accounts-for-clock-time-zone-and-certificat-57017) |
| How do you handle organization-wide certificate and TLS management (private CA, ACM) as a foundational service across accounts? | deep understanding | SDE-2/3, Architect/Principal | Landing Zones & Cloud Foundations | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-organization-wide-certificate-and-tls-management-pri-56108) |
| How do you handle certificate and DNS management when the same domain serves from two clouds behind different CDNs? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Cloud & Hybrid Cloud | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-certificate-and-dns-management-when-the-same-domain--51144) |
| How would you write a Python script that checks a certificate's expiry date and warns if it expires within 30 days? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | Python | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-write-a-python-script-that-checks-a-certificate-s-expiry-41898) |
| Design how Vault's PKI engine becomes the org-wide certificate authority for service-mesh mTLS across 50 clusters, including intermediate CA hierarchy, offline root custody, and cert-lifecycle automation. | expertise | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-vault-s-pki-engine-becomes-the-org-wide-certificate-authori-54954) |
| Your PKI engine is issuing 90-day certs, but a CA compromise scenario forces you to rotate the intermediate. Walk through the org-wide rotation without a mass outage, including CRL/OCSP scaling. | expertise | SDE-2/3, Architect/Principal | Secrets Management (Vault) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-pki-engine-is-issuing-90-day-certs-but-a-ca-compromise-scenario-f-54955) |
| Architect the governance for signing-key and trust-root rotation across the whole org so a compromised or expired root doesn't cause a fleet-wide deploy outage — what's your zero-downtime rotation design? | expertise | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=architect-the-governance-for-signing-key-and-trust-root-rotation-acros-55451) |
| Design a multi-region disaster-recovery plan for your Rekor transparency log and Fulcio CA — how do you guarantee no signing downtime and no loss of inclusion proofs during a region loss? | expertise | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-multi-region-disaster-recovery-plan-for-your-rekor-transparen-55435) |
| How do you architect the transition from a self-hosted signing PKI to keyless Sigstore (or vice versa) for an org already deeply invested in one — what's the dual-run and cutover strategy? | expertise | SDE-2/3, Architect/Principal | Software Supply Chain Security (SBOM/Sigstore) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-the-transition-from-a-self-hosted-signing-pki-to--55509) |
| How do you design the trust relationship between your mesh's CA and the org's enterprise PKI? What breaks if security wants to own the root while platform owns issuance velocity? | expertise | SDE-2/3, Architect/Principal | Zero Trust Network Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-design-the-trust-relationship-between-your-mesh-s-ca-and-th-56880) |
| How do you handle certificate rotation, revocation, and the CRL/OCSP problem at fleet scale? Why do many Zero Trust deployments avoid revocation entirely and what's the risk you accept? | expertise | SDE-2/3, Architect/Principal | Zero Trust Network Architecture | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-certificate-rotation-revocation-and-the-crl-ocsp-pro-56863) |
