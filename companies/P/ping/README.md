# Ping

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 12

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 1 | 1 | 1 | 1 |
| Fullstack | 0 | 0 | 0 | 9 | 9 | 9 |
| DevOps | 0 | 0 | 1 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you make an authentication service extremely fault tolerant given that if it's down, everything is down? Discuss caching tokens, degradation modes, and read paths. | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Fault Tolerance & Resiliency | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-make-an-authentication-service-extremely-fault-tolerant-giv-29952) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design how the gateway supports gradual rollout of a new auth scheme (say moving from opaque tokens to JWT, or from OAuth2 to OAuth2.1/DPoP) across hundreds of consumers over a year, running both schemes at once, tracking migration, and setting a defensible sunset. | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-how-the-gateway-supports-gradual-rollout-of-a-new-auth-scheme-s-39578) |
| Frame the org decision on whether the gateway should terminate and re-issue tokens (token exchange at the edge) or pass client tokens straight through to services; what are the security, auditability, and blast-radius implications of each at 100+ services, and which do you standardize on? | expertise | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=frame-the-org-decision-on-whether-the-gateway-should-terminate-and-re--39526) |
| You must decide whether the gateway or a dedicated identity broker owns the mapping from external identities (multiple IdPs, social, partner SSO) to internal principals; adjudicate the coupling, and design how a new IdP is onboarded without re-plumbing every downstream service. | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-whether-the-gateway-or-a-dedicated-identity-broker-own-39599) |
| Tell me about a time you led the org through a decision on how much to centralize identity, auth, and access control versus letting product teams own their own. How did you weigh security posture against team velocity at scale? | expertise | SDE-2/3, Architect/Principal | Behavioral & Leadership Principles (STAR) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=tell-me-about-a-time-you-led-the-org-through-a-decision-on-how-much-to-40426) |
| How do you architect token exchange (RFC 8693) across a request that crosses three trust domains so each hop gets a fresh audience-scoped token, and what breaks operationally when the token-exchange service itself degrades? | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-token-exchange-rfc-8693-across-a-request-that-cro-41221) |
| Threat-model a design where you federate identity with dozens of enterprise customers via SAML/OIDC. Each customer's IdP is a trust anchor you don't control. How do you contain a customer IdP breach and stop it from spilling into shared infrastructure? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=threat-model-a-design-where-you-federate-identity-with-dozens-of-enter-41299) |
| Threat-model an OAuth authorization-code flow across a first-party web app, a mobile app, and a partner integration. Where do PKCE, redirect-URI validation, and refresh-token rotation each fail, and how do you architect the shared IdP to enforce them uniformly? | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=threat-model-an-oauth-authorization-code-flow-across-a-first-party-web-41269) |
| You are consolidating five acquired products onto one identity fabric. How do you sequence the SSO and workload-identity unification so that during the multi-quarter overlap you never have two roots of trust silently accepting each other's tokens? | expertise | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-consolidating-five-acquired-products-onto-one-identity-fabric--41220) |
| You inherit a design where JWTs carry all the permissions as claims, and tokens live an hour. A permission is revoked mid-session but the token still says allow. How do you architect near-real-time revocation without abandoning stateless verification entirely? | deep understanding | SDE-2/3, Architect/Principal | Security Architecture & Threat Modeling (Zero Trust) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-inherit-a-design-where-jwts-carry-all-the-permissions-as-claims-an-41293) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you sequence identity provider migration so that neither on-prem nor migrated apps lose authentication during the transition? | deep understanding | SDE-2/3, Architect/Principal | Cloud Migration Strategy (6 Rs) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-sequence-identity-provider-migration-so-that-neither-on-pre-56616) |
| Your on-prem identity provider (AD) must authorize cloud console access; how do you design that federation to fail safely if AD is down? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Multi-Cloud & Hybrid Cloud | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-on-prem-identity-provider-ad-must-authorize-cloud-console-access--51190) |
