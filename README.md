# Casdoor (casdoor)
Casdoor is an open-source, AI-first identity and access management (IAM) and MCP gateway authentication server with a web UI. Built in Go (Beego) with a React frontend, Casdoor supports OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP, Kerberos/SPNEGO, WebAuthn / Passkeys, TOTP / MFA, SCIM 2.0 provisioning, social login, multi-tenant organizations, role-based access control, and an MCP Gateway plus A2A Protocol for agent-to-agent communication. The platform exposes a RESTful API documented via Swagger and ships SDKs for Go, Java, Python, Node.js, C#, C++, PHP, Ruby, JavaScript, Lua, and Haskell. Released under the Apache License 2.0.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/casdoor/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Authentication, Authorization, IAM, Identity, OAuth, OIDC, SAML, LDAP, MFA, SCIM, SSO, WebAuthn, Passkeys, MCP, Open Source

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-23

## APIs

### Casdoor REST API
The Casdoor REST API provides programmatic access to the IAM platform's core resources including users, organizations, applications, roles, groups, permissions, identity providers, tokens, sessions, certificates, adapters, syncers, webhooks, products, payments, MFA enrollments, and enforcers.

**Human URL:** [https://casdoor.ai/docs/basic/api](https://casdoor.ai/docs/basic/api)

**Base URL:** `https://door.casdoor.com`

#### Tags
- IAM, REST, Users, Organizations, Applications, Roles, Tokens, Sessions

#### Properties
- [Documentation](https://casdoor.ai/docs/basic/api)
- [Swagger](https://door.casdoor.com/swagger/)
- [GitHub Repository](https://github.com/casdoor/casdoor)
- [Authentication](https://casdoor.ai/docs/basic/core-concepts)

### Casdoor OAuth 2.0 / OIDC Provider
OAuth 2.0 authorization server and OpenID Connect identity provider exposing standard authorization, token, userinfo, revocation, introspection, JWKS, and OIDC discovery endpoints.

**Human URL:** [https://casdoor.ai/docs/how-to-connect/oauth](https://casdoor.ai/docs/how-to-connect/oauth)

#### Tags
- OAuth, OIDC, JWT, SSO, Authentication, Tokens

#### Properties
- [Documentation](https://casdoor.ai/docs/how-to-connect/oauth)
- [Discovery](https://door.casdoor.com/.well-known/openid-configuration)
- [Specification](https://datatracker.ietf.org/doc/html/rfc6749)

### Casdoor SAML 2.0 Identity Provider
SAML 2.0 IdP for enterprise SSO scenarios with support for standard metadata, ACS, and SLO bindings.

**Human URL:** [https://casdoor.ai/docs/how-to-connect/saml](https://casdoor.ai/docs/how-to-connect/saml)

#### Tags
- SAML, Enterprise SSO, Federation, SSO

#### Properties
- [Documentation](https://casdoor.ai/docs/how-to-connect/saml)
- [Specification](http://docs.oasis-open.org/security/saml/v2.0/)

### Casdoor CAS Server
Central Authentication Service server compatible with CAS protocol versions 1.0, 2.0, and 3.0.

**Human URL:** [https://casdoor.ai/docs/how-to-connect/cas](https://casdoor.ai/docs/how-to-connect/cas)

#### Tags
- CAS, SSO, Authentication

#### Properties
- [Documentation](https://casdoor.ai/docs/how-to-connect/cas)

### Casdoor LDAP Server
LDAP server interface so legacy applications can bind against Casdoor users and groups, plus a sync engine that imports users from external LDAP directories.

**Human URL:** [https://casdoor.ai/docs/ldap/overview](https://casdoor.ai/docs/ldap/overview)

#### Tags
- LDAP, Directory, Sync

#### Properties
- [Documentation](https://casdoor.ai/docs/ldap/overview)

### Casdoor SCIM 2.0 API
SCIM 2.0 endpoints for automated user and group provisioning between Casdoor and downstream identity-aware systems.

**Human URL:** [https://casdoor.ai/docs/scim/overview](https://casdoor.ai/docs/scim/overview)

#### Tags
- SCIM, Provisioning, Identity

#### Properties
- [Documentation](https://casdoor.ai/docs/scim/overview)
- [Specification](https://datatracker.ietf.org/doc/html/rfc7644)

### Casdoor MCP Gateway
MCP (Model Context Protocol) gateway and A2A (Agent-to-Agent) protocol surface for brokering authentication and authorization for AI agents.

**Human URL:** [https://casdoor.ai/docs/mcp/overview](https://casdoor.ai/docs/mcp/overview)

#### Tags
- MCP, AI, Agents, A2A

#### Properties
- [Documentation](https://casdoor.ai/docs/mcp/overview)

### Casdoor Webhooks
Outbound webhook events for identity events such as signup, login, logout, profile changes, password resets, and MFA enrollments.

**Human URL:** [https://casdoor.ai/docs/integration/webhook](https://casdoor.ai/docs/integration/webhook)

#### Tags
- Webhooks, Events, Integration

#### Properties
- [Documentation](https://casdoor.ai/docs/integration/webhook)

## Common Properties

- [Website](https://casdoor.org)
- [Documentation](https://casdoor.ai/docs/overview)
- [GettingStarted](https://casdoor.ai/docs/basic/server-installation)
- [Swagger](https://door.casdoor.com/swagger/)
- [GitHub](https://github.com/casdoor/casdoor)
- [SourceCode](https://github.com/casdoor/casdoor)
- [IssueTracker](https://github.com/casdoor/casdoor/issues)
- [Blog](https://casdoor.org/blog)
- [Discord](https://discord.gg/5rPsrAzK7S)
- [License](https://github.com/casdoor/casdoor/blob/master/LICENSE)
- [DockerHub](https://hub.docker.com/r/casbin/casdoor)
- [Demo](https://door.casdoor.com)
- [Pricing](https://casdoor.com/pricing)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
