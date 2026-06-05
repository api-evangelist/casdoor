# Casdoor (casdoor)

Casdoor is an open-source, AI-first identity and access management (IAM) and MCP gateway authentication server with a web UI. Built in Go (Beego) with a React frontend, Casdoor supports OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP, Kerberos/SPNEGO, WebAuthn / Passkeys, TOTP / MFA, SCIM 2.0 provisioning, social login, multi-tenant organizations, role-based access control, and an MCP Gateway plus A2A Protocol for agent-to-agent communication. The platform exposes a RESTful API documented via Swagger and ships SDKs for Go, Java, Python, Node.js, C#, C++, PHP, Ruby, JavaScript, Lua, and Haskell. Released under the Apache License 2.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/casdoor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/casdoor/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Authentication
- Authorization
- IAM
- Identity
- LDAP
- MCP
- MFA
- OAuth
- OIDC
- Open Source
- Passkeys
- SAML
- SCIM
- Single Sign-On
- SSO
- WebAuthn

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-19

## APIs

### Casdoor REST API

The Casdoor REST API provides programmatic access to the IAM platform's core resources including users, organizations, applications, roles, groups, permissions, identity providers, tokens, sessions, certificates, adapters, syncers, webhooks, products, payments, MFA enrollments, and enforcers. The API follows RESTful conventions with JSON payloads and is documented via a hosted Swagger UI.

- **Human URL:** [https://casdoor.ai/docs/basic/api](https://casdoor.ai/docs/basic/api)
- **Base URL:** `https://door.casdoor.com`

#### Tags

- Applications
- IAM
- Organizations
- REST
- Roles
- Sessions
- Tokens
- Users

#### Properties

- [Documentation](https://casdoor.ai/docs/basic/api)
- [Swagger](https://door.casdoor.com/swagger/)
- [GitHub Repository](https://github.com/casdoor/casdoor)
- [Authentication](https://casdoor.ai/docs/basic/core-concepts)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Casdoor OAuth 2.0 / OIDC Provider

Casdoor implements an OAuth 2.0 authorization server and OpenID Connect identity provider, exposing the standard authorization, token, userinfo, revocation, introspection, JWKS, and OIDC discovery endpoints used by web, mobile, native, and machine-to-machine clients to obtain ID tokens and access tokens.

- **Human URL:** [https://casdoor.ai/docs/how-to-connect/oauth](https://casdoor.ai/docs/how-to-connect/oauth)

#### Tags

- Authentication
- JWT
- OAuth
- OIDC
- SSO
- Tokens

#### Properties

- [Documentation](https://casdoor.ai/docs/how-to-connect/oauth)
- [Discovery](https://door.casdoor.com/.well-known/openid-configuration)
- [Specification](https://datatracker.ietf.org/doc/html/rfc6749)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Casdoor SAML 2.0 Identity Provider

SAML 2.0 identity provider endpoints in Casdoor that issue SAML assertions to enterprise service providers, supporting SSO scenarios for legacy and enterprise SaaS applications via standard SAML metadata, ACS, and SLO bindings.

- **Human URL:** [https://casdoor.ai/docs/how-to-connect/saml](https://casdoor.ai/docs/how-to-connect/saml)

#### Tags

- Enterprise SSO
- Federation
- SAML
- SSO

#### Properties

- [Documentation](https://casdoor.ai/docs/how-to-connect/saml)
- [Specification](http://docs.oasis-open.org/security/saml/v2.0/)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Casdoor CAS Server

Casdoor exposes a CAS (Central Authentication Service) server compatible with CAS protocol versions 1.0, 2.0, and 3.0, providing single sign-on to applications that integrate via the CAS ticket-validation flow.

- **Human URL:** [https://casdoor.ai/docs/how-to-connect/cas](https://casdoor.ai/docs/how-to-connect/cas)

#### Tags

- Authentication
- CAS
- SSO

#### Properties

- [Documentation](https://casdoor.ai/docs/how-to-connect/cas)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Casdoor LDAP Server

Casdoor provides an LDAP server interface so that legacy applications and infrastructure components requiring LDAP authentication can bind against Casdoor users and groups, and a sync engine that imports users from external LDAP directories.

- **Human URL:** [https://casdoor.ai/docs/ldap/overview](https://casdoor.ai/docs/ldap/overview)

#### Tags

- Directory
- LDAP
- Sync

#### Properties

- [Documentation](https://casdoor.ai/docs/ldap/overview)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Casdoor SCIM 2.0 API

SCIM 2.0 (System for Cross-domain Identity Management) endpoints for automated user and group provisioning between Casdoor and downstream identity-aware systems.

- **Human URL:** [https://casdoor.ai/docs/scim/overview](https://casdoor.ai/docs/scim/overview)

#### Tags

- Identity
- Provisioning
- SCIM

#### Properties

- [Documentation](https://casdoor.ai/docs/scim/overview)
- [Specification](https://datatracker.ietf.org/doc/html/rfc7644)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Casdoor MCP Gateway

Casdoor's MCP (Model Context Protocol) gateway and A2A (Agent-to-Agent) protocol surface, designed to broker authentication and authorization for AI agents and MCP-aware tooling using Casdoor as the identity provider.

- **Human URL:** [https://casdoor.ai/docs/mcp/overview](https://casdoor.ai/docs/mcp/overview)

#### Tags

- A2A
- Agents
- AI
- MCP

#### Properties

- [Documentation](https://casdoor.ai/docs/mcp/overview)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Casdoor Webhooks

Outbound webhook events that notify external systems of identity events such as user signup, login, logout, profile changes, password resets, and MFA enrollments.

- **Human URL:** [https://casdoor.ai/docs/integration/webhook](https://casdoor.ai/docs/integration/webhook)

#### Tags

- Events
- Integration
- Webhooks

#### Properties

- [Documentation](https://casdoor.ai/docs/integration/webhook)
- [Postman Collection](collections/casdoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/casdoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://casdoor.org)
- [Documentation](https://casdoor.ai/docs/overview)
- [Getting Started](https://casdoor.ai/docs/basic/server-installation)
- [Authentication](https://casdoor.ai/docs/basic/core-concepts)
- [Swagger](https://door.casdoor.com/swagger/)
- [Git Hub](https://github.com/casdoor/casdoor)
- [GitHub Organization](https://github.com/casdoor)
- [Source Code](https://github.com/casdoor/casdoor)
- [Issue Tracker](https://github.com/casdoor/casdoor/issues)
- [Blog](https://casdoor.org/blog)
- [Community](https://casdoor.ai/docs/community/forum)
- [Discord](https://discord.gg/5rPsrAzK7S)
- [License](https://github.com/casdoor/casdoor/blob/master/LICENSE)
- [Docker Hub](https://hub.docker.com/r/casbin/casdoor)
- [Demo](https://door.casdoor.com)
- [Privacy Policy](https://casdoor.org/privacy)
- [Pricing](https://casdoor.com/pricing)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/casdoor/public-mcp-server-registry)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
