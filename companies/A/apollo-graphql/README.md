# Apollo GraphQL

**Tier:** Tier 3  |  **Business domain:** SaaS  |  **Questions:** 25

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 11 | 13 | 3 | 13 |
| Fullstack | 1 | 1 | 1 | 5 | 5 | 5 |
| DevOps | 0 | 0 | 2 | 3 | 3 | 3 |
| Data Engineer | 0 | 0 | 0 | 1 | 1 | 1 |
| Database Developer | 0 | 0 | 0 | 1 | 1 | 1 |
| AI Engineer | 0 | 0 | 0 | 2 | 2 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you cache GraphQL query results and why is it trickier than caching REST? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-cache-graphql-query-results-and-why-is-it-trickier-than--5015) |
| How do you architect an org-wide 'consistency contract registry' where every inter-service dependency declares the consistency it provides and requires, so a partition's blast radius is computable before it happens rather than discovered in an incident? | expertise | SDE-2/3, Architect/Principal | CAP Theorem | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-architect-an-org-wide-consistency-contract-registry-where-e-32224) |
| Contrast enterprise integration via a GraphQL federation layer versus REST/BFF versus event streams for aggregating data from many backend domains. When does federation reduce client-team friction, and when does it centralize a new bottleneck and ownership headache? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-enterprise-integration-via-a-graphql-federation-layer-versus--36386) |
| A federated entity's @key is a composite of two fields and the gateway keeps sending malformed representations. How would you debug the entity-resolution contract between subgraph and gateway to find the mismatch? | expertise | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-federated-entity-s-key-is-a-composite-of-two-fields-and-the-gateway--24121) |
| A federated subgraph owns Order and another owns Payment, and a query needs Order.payment.status. Trace the exact fan-out the gateway does and where you'd add caching to avoid a chatty N+1 across subgraphs. | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-federated-subgraph-owns-order-and-another-owns-payment-and-a-query-n-24047) |
| A GraphQL query joins data across two services with different latency profiles, and the slow one dominates. How would you use partial responses (@defer or field-level nullability) to return the fast data first? | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-graphql-query-joins-data-across-two-services-with-different-latency--24093) |
| A GraphQL query with @defer streams over HTTP chunked encoding but your reverse proxy buffers it, killing the benefit. How would you diagnose where buffering happens across proxy, framework, and client? | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-graphql-query-with-defer-streams-over-http-chunked-encoding-but-your-24074) |
| How would you design GraphQL persisted queries so the same query hash is stable across client builds, and explain what happens to the APQ negotiation when a CDN caches the 'PersistedQueryNotFound' response by mistake. | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-graphql-persisted-queries-so-the-same-query-hash--24106) |
| How would you evolve a GraphQL API from a single monolithic schema to federation without a big-bang migration? What's the first subgraph you'd carve out and how do you keep the gateway backward-compatible? | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-evolve-a-graphql-api-from-a-single-monolithic-schema-to--24111) |
| How would you handle partial failure in a federated query where one subgraph is down but the client can still use the rest? What does the gateway return, and how do you design nullability so the outage is contained? | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-handle-partial-failure-in-a-federated-query-where-one-su-24055) |
| How would you implement GraphQL query allowlisting where the allowlist itself must be updated safely across a fleet of gateway instances? What's the propagation delay problem and how do you avoid split-brain rejections? | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-implement-graphql-query-allowlisting-where-the-allowlist-24117) |
| Your GraphQL schema is registered in Apollo Studio and you want to block deploys that remove a field still queried by mobile clients (which can't force-upgrade). How do usage windows and client version tracking gate the removal? | deep understanding | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-graphql-schema-is-registered-in-apollo-studio-and-you-want-to-blo-24099) |
| Your GraphQL server's introspection is disabled in prod, but internal dashboards break. How would you securely expose the schema to trusted internal tools (auth'd introspection, published SDL artifact) without opening it publicly? | intermediate experience | SDE-1/2, SDE-2/3 | GraphQL | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-graphql-server-s-introspection-is-disabled-in-prod-but-internal-d-24095) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Adjudicate a proposal to make the gateway the org's canonical API changelog/diff engine (auto-detecting breaking changes from traffic and specs); what's the architecture, where does it get false positives, and is this a gateway responsibility or a separate platform capability? | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=adjudicate-a-proposal-to-make-the-gateway-the-org-s-canonical-api-chan-39553) |
| You must decide whether the gateway enforces schema compatibility (backward/forward) as a hard gate or a soft warning during an org-wide push to spec-first; adjudicate the velocity-versus-safety tension and design the escape hatch that doesn't become the default. | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-whether-the-gateway-enforces-schema-compatibility-back-39540) |
| You're deciding the gateway's stance on GraphQL: front it as an opaque POST endpoint, or teach the gateway to parse operations for rate-limiting/caching/authz; adjudicate the coupling of gateway-into-query-semantics versus a dedicated GraphQL gateway, at org scale. | deep understanding | SDE-2/3, Architect/Principal | API Gateway | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-re-deciding-the-gateway-s-stance-on-graphql-front-it-as-an-opaque--39570) |
| How would you cache GraphQL query results and why is it trickier than caching REST? | expertise | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-cache-graphql-query-results-and-why-is-it-trickier-than--5015) |
| Contrast an enterprise-wide GraphQL gateway (single graph, schema stitching/federation) with each team owning REST APIs plus a thin aggregation BFF. Where does one graph reduce client friction, and where does it centralize ownership pain and coupling you'll regret? | expertise | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-an-enterprise-wide-graphql-gateway-single-graph-schema-stitch-40744) |

## DevOps

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you expose an API catalog (OpenAPI/gRPC/AsyncAPI specs) in Backstage and keep the specs in sync with running services? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | Internal Developer Platform (Backstage) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-expose-an-api-catalog-openapi-grpc-asyncapi-specs-in-bac-51763) |
| How would you present cross-team dependencies and 'who consumes my API' in Backstage to help with change communication? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Internal Developer Platform (Backstage) | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-present-cross-team-dependencies-and-who-consumes-my-api--51810) |
| A principal argues the mesh should enforce schema/contract validation (protobuf/JSON) at the proxy so bad payloads never reach services. Adjudicate whether contract enforcement belongs in the mesh vs the app vs an API gateway, and the operational cost of proxy-side validation at scale. | deep understanding | SDE-2/3, Architect/Principal | Service Mesh | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-principal-argues-the-mesh-should-enforce-schema-contract-validation--52642) |

## Data Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What's your view on serving master data via an API/GraphQL 'entity service' vs publishing to a shared data product in the lakehouse — when is each the right consumption pattern? | deep understanding | SDE-2/3, Architect/Principal | Master Data Management (MDM) | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-s-your-view-on-serving-master-data-via-an-api-graphql-entity-serv-127788) |

## Database Developer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Contrast aggregating cross-domain data via a GraphQL federation layer over service databases versus a BFF versus streaming into one query store. When does federation reduce client-team friction against many backend databases, and when does it centralize a new query-performance bottleneck and ownership headache? | deep understanding | SDE-2/3, Architect/Principal | Enterprise Architecture Patterns | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=contrast-aggregating-cross-domain-data-via-a-graphql-federation-layer--112620) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| Design capability negotiation and version-compatibility for an internal MCP-based tool ecosystem where dozens of teams publish and consume tool servers on independent release cadences. How do you avoid a coordinated-deploy nightmare when a tool's schema evolves? | expertise | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-capability-negotiation-and-version-compatibility-for-an-interna-83089) |
| You centralized all tool definitions in one registry service. A reviewer calls it a single point of failure and a coupling magnet. Defend the decision or propose an alternative that keeps a single source of truth without the SPOF. | deep understanding | SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-centralized-all-tool-definitions-in-one-registry-service-a-reviewe-83123) |
