# Casdoor

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Casdoor is an open-source, AI-first identity and access management (IAM) and MCP gateway authentication server with a web UI. Built in Go (Beego) with a React frontend, Casdoor supports OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP, Kerberos/SPNEGO, WebAuthn / Passkeys, TOTP / MFA, SCIM 2.0 provisioning, social login, multi-tenant organizations, role-based access control, and an MCP Gateway plus A2A Protocol for agent-to-agent communication. The platform exposes a RESTful API documented via Swagger and ships SDKs for Go, Java, Python, Node.js, C#, C++, PHP, Ruby, JavaScript, Lua, and Haskell. Released under the Apache License 2.0.

**Areas:** Authentication · Authorization · Identity and Access Management · Identity · LDAP · MCP · MFA · OpenID Connect · Open Source · Passkeys · SAML · SCIM

## Casdoor on APIs.io

Everything profiled for Casdoor is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/casdoor/](https://apis.io/providers/casdoor/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Casdoor REST API](https://apis.io/apis/casdoor/casdoor-rest-api/) — The Casdoor REST API provides programmatic access to the IAM platform's core resources including users, organizations, applications, roles, groups,…
- [Casdoor OAuth 2.0 / OIDC Provider](https://apis.io/apis/casdoor/casdoor-oauth-oidc/) — Casdoor implements an OAuth 2.0 authorization server and OpenID Connect identity provider, exposing the standard authorization, token, userinfo, revocation,…
- [Casdoor SAML 2.0 Identity Provider](https://apis.io/apis/casdoor/casdoor-saml/) — SAML 2.0 identity provider endpoints in Casdoor that issue SAML assertions to enterprise service providers, supporting SSO scenarios for legacy and…
- [Casdoor CAS Server](https://apis.io/apis/casdoor/casdoor-cas/) — Casdoor exposes a CAS (Central Authentication Service) server compatible with CAS protocol versions 1.0, 2.0, and 3.0, providing single sign-on to…
- [Casdoor LDAP Server](https://apis.io/apis/casdoor/casdoor-ldap/) — Casdoor provides an LDAP server interface so that legacy applications and infrastructure components requiring LDAP authentication can bind against Casdoor…
- [Casdoor SCIM 2.0 API](https://apis.io/apis/casdoor/casdoor-scim/) — SCIM 2.0 (System for Cross-domain Identity Management) endpoints for automated user and group provisioning between Casdoor and downstream identity-aware…
- [Casdoor MCP Gateway](https://apis.io/apis/casdoor/casdoor-mcp-gateway/) — Casdoor's MCP (Model Context Protocol) gateway and A2A (Agent-to-Agent) protocol surface, designed to broker authentication and authorization for AI agents…
- [Casdoor Webhooks](https://apis.io/apis/casdoor/casdoor-webhooks/) — Outbound webhook events that notify external systems of identity events such as user signup, login, logout, profile changes, password resets, and MFA…
- [Casdoor Applications API](https://apis.io/apis/casdoor/casdoor-applications-api/) — OAuth/OIDC client applications
- [Casdoor Authentication API](https://apis.io/apis/casdoor/casdoor-authentication-api/) — Login, callback, and device authorization
- [Casdoor OIDC API](https://apis.io/apis/casdoor/casdoor-oidc-api/) — OpenID Connect discovery and JWKS endpoints
- [Casdoor Organizations API](https://apis.io/apis/casdoor/casdoor-organizations-api/) — Multi-tenant organization management
- [Casdoor Permissions API](https://apis.io/apis/casdoor/casdoor-permissions-api/) — Casbin policy enforcement
- [Casdoor Roles API](https://apis.io/apis/casdoor/casdoor-roles-api/) — Role-based access control
- [Casdoor Users API](https://apis.io/apis/casdoor/casdoor-users-api/) — User CRUD and credential operations

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [MCP Server](https://apis.io/servers/casdoor/mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Casdoor Agentic Access](https://apis.io/agentic-access/casdoor/casdoor-agentic-access/)

#### Collections (8)

Postman and Open Collection request collections.

- [Casdoor REST API](https://apis.io/collections/casdoor/open-casdoor/)
- [Casdoor REST Applications API](https://apis.io/collections/casdoor/open-casdoor-applications-api/)
- [Casdoor REST Applications Authentication API](https://apis.io/collections/casdoor/open-casdoor-authentication-api/)
- [Casdoor REST Applications OIDC API](https://apis.io/collections/casdoor/open-casdoor-oidc-api/)
- [Casdoor REST Applications Organizations API](https://apis.io/collections/casdoor/open-casdoor-organizations-api/)
- [Casdoor REST Applications Permissions API](https://apis.io/collections/casdoor/open-casdoor-permissions-api/)
- [Casdoor REST Applications Roles API](https://apis.io/collections/casdoor/open-casdoor-roles-api/)
- [Casdoor REST Applications Users API](https://apis.io/collections/casdoor/open-casdoor-users-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Casdoor Authentication](https://apis.io/security/casdoor/casdoor-authentication/)
- [Casdoor Domain Security](https://apis.io/security/casdoor/casdoor-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Casdoor Plans Pricing](https://apis.io/plans/casdoor/casdoor-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Casdoor Rate Limits](https://apis.io/rate-limits/casdoor/casdoor-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Casdoor Finops](https://apis.io/finops/casdoor/casdoor-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://casdoor.org)
- [Documentation](https://casdoor.ai/docs/overview)
- [Getting started](https://casdoor.ai/docs/basic/server-installation)
- [Pricing](https://casdoor.com/pricing)
- [Blog](https://casdoor.org/blog)
- [Privacy policy](https://casdoor.org/privacy)
- [GitHub](https://github.com/casdoor)

## API Evangelist rating

**Kin Score 22.5** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 56.7 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 36.8 |
| Developer ergonomics | 38.1 |
| Access clarity | 7.9 |

**Agent readiness 21.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/casdoor/](https://apis.io/providers/casdoor/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Casdoor: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/casdoor/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
