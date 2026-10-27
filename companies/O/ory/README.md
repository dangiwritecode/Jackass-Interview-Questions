# Ory

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 9

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 0 | 0 | 3 | 3 | 3 | 3 |
| Fullstack | 0 | 0 | 0 | 5 | 5 | 5 |
| DevOps | 0 | 0 | 0 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design token issuance so an attacker who steals your database of hashed refresh tokens still cannot forge a valid access token? What must be kept out of the DB entirely? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-token-issuance-so-an-attacker-who-steals-your-dat-26217) |
| Your access-control list for a resource can grow to thousands of entries (per-user shares). How do you keep the 'can X read this' check fast without scanning the whole ACL, and how does this compare to a Zanzibar tuple store? | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-access-control-list-for-a-resource-can-grow-to-thousands-of-entri-26196) |
| Your OAuth token endpoint is being probed with a stolen client_id trying many redirect_uris. How do you detect this attack pattern in logs, and what server-side controls make an exact redirect_uri match non-negotiable? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-oauth-token-endpoint-is-being-probed-with-a-stolen-client-id-tryi-26223) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A tradeoff exists between building a bespoke internal auth/authz system (fit, control) and adopting a managed identity provider (speed, security maturity). How do you scenario-test this build-vs-buy decision on security, extensibility, and lock-in? | expertise | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-tradeoff-exists-between-building-a-bespoke-internal-auth-authz-syste-40599) |
| You are evaluating a proposal to move authentication from a shared session store to stateless JWTs. Walk through the ATAM analysis of this decision across security, scalability, and revocation-latency, and identify where the tradeoff point sits. | expertise | SDE-2/3, Architect/Principal | Architectural Trade-off Analysis (ATAM) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-are-evaluating-a-proposal-to-move-authentication-from-a-shared-ses-40535) |
| You're consolidating five acquired products onto one CIAM. Leadership wants Auth0 vs Cognito vs a self-hosted Keycloak/Ory stack. Frame the decision on total cost at 100M MAU, lock-in, extensibility of the login flow, and data-residency, and name the evidence that would flip your recommendation. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-consolidating-five-acquired-products-onto-one-ciam-leadership-w-38818) |
| Your OpenFGA/Zanzibar authorization store needs a 'read-your-writes' guarantee for the UI right after a share, but strong global consistency is too slow. Walk me through how consistency tokens let you offer per-request freshness selectively, and how you'd document the guarantee to app teams. | expertise | SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-openfga-zanzibar-authorization-store-needs-a-read-your-writes-gua-38826) |
| You must architect a graph-database-backed access-control (relationship-based / Zanzibar-style) system answering millions of 'can X view Y' checks — how do you model relation tuples cache the check and propagate a shared-document revoke consistently? | expertise | SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-architect-a-graph-database-backed-access-control-relationship-39452) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| You're asked to justify whether the mesh should be in the critical path of your authentication service itself (the thing that issues tokens). Frame the circular-dependency risk (mesh needs identity, identity needs mesh) and how you'd bootstrap trust to avoid a deadlock. | expertise | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-asked-to-justify-whether-the-mesh-should-be-in-the-critical-pat-52702) |
