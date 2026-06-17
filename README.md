# 🛡️ Awesome Customer IAM [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated, vendor-neutral list of the best resources, tools, platforms, protocols, and practitioner knowledge for building and scaling **Customer Identity and Access Management (CIAM)** systems.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](#-contributing)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](#-contributing)

---

## 📘 What is CIAM?

**Customer Identity and Access Management (CIAM)** is the layer of platforms, protocols, and policies that lets organizations register, authenticate, authorize, and manage the identities of the **external users** of their products: consumers, businesses, partners, and increasingly machines and AI agents.

Unlike workforce IAM, which secures a known and finite population of employees, CIAM has to serve **millions of unknown, unmanaged users** while balancing three forces that constantly pull against each other:

- **Security:** stopping account takeover, credential stuffing, fraud, and bots.
- **Experience:** frictionless signup, login, and recovery that protect conversion and retention.
- **Privacy and compliance:** consent, data residency, and regulations like GDPR, CCPA, and HIPAA.

CIAM is a foundational layer of modern consumer apps, SaaS products, e-commerce, fintech, healthcare portals, and gaming. In short, any business where the login box is the front door to revenue.

### CIAM vs. IAM vs. IDaaS

| | **Workforce IAM** | **CIAM** | **IDaaS** |
|---|---|---|---|
| **Users** | Employees, contractors | Customers, consumers, businesses | Either (a delivery model, not a category) |
| **Scale** | Thousands | Millions+ | Varies |
| **Primary goal** | Governance, least privilege, provisioning | Conversion, retention, trust, privacy | Outsourced identity run as a cloud service |
| **Optimized for** | Control and audit | Frictionless UX and growth | Operational simplicity |
| **Typical flows** | Joiner-Mover-Leaver, SSO, SCIM | Self-service signup, social login, progressive profiling | Both |

> 📖 Go deeper: [CIAM vs IAM vs IDaaS](https://guptadeepak.com/ciam-compass/guides/ciam-vs-iam-vs-idaas/) and [What is CIAM? The complete guide](https://guptadeepak.com/ciam-compass/guides/what-is-ciam/).

---

## 🎯 Why This Repo?

This repository helps **developers, architects, security engineers, and identity buyers**:

- Navigate the full CIAM vendor and protocol ecosystem
- Compare platforms with a consistent, vendor-neutral lens
- Apply battle-tested security, privacy, and UX best practices
- Make sound build-vs-buy and migration decisions
- Stay current with emerging areas like passkeys, fine-grained authorization, and AI agent (non-human) identity

### 🌟 Featured Knowledge Hubs

Two open, vendor-neutral resources anchor this list and are referenced throughout:

- **[CIAM Compass](https://guptadeepak.com/ciam-compass/)** is a vendor-neutral knowledge portal that evaluates **48 CIAM platforms** against the same 30+ capability matrix, with TCO bands across four MAU tiers, **118 head-to-head comparisons**, **68 practitioner guides**, 19 vertical guides, and free decision tools. No sponsored placements and no affiliate links. Every claim is sourced, and every page is dated and signed.
- **[Start With Identity](https://startwithidentity.com/)** is a practitioner library of **100+ identity glossary terms** and **50+ guides** spanning the six pillars of identity (Workforce, Customer, Privileged and Governance, Machine/Workload, Authorization, and Emerging), with deep coverage of CIAM, passwordless, and identity UX.

---

## 📂 Table of Contents

- [💡 CIAM Fundamentals](#-ciam-fundamentals)
- [🧭 Decision Frameworks & Buyer Guides](#-decision-frameworks--buyer-guides)
- [🛠️ CIAM Tools & Platforms](#️-ciam-tools--platforms)
- [🟢 Open Source CIAM](#-open-source-ciam)
- [🧪 Protocols & Standards](#-protocols--standards)
- [🔑 Authentication Methods](#-authentication-methods)
- [🧱 Authorization Models](#-authorization-models)
- [🔐 Security & Threat Defense](#-security--threat-defense)
- [⚖️ Privacy, Consent & Compliance](#️-privacy-consent--compliance)
- [🤖 Agentic & Non-Human Identity](#-agentic--non-human-identity)
- [🏢 B2B & Multi-Tenant Identity](#-b2b--multi-tenant-identity)
- [👨‍💻 Developer SDKs & APIs](#-developer-sdks--apis)
- [🧩 Integration Examples & Starters](#-integration-examples--starters)
- [🧠 Identity UX / CX](#-identity-ux--cx)
- [🏭 Industry & Vertical Guides](#-industry--vertical-guides)
- [📈 Analytics & Identity Intelligence](#-analytics--identity-intelligence)
- [🎓 Learning, Glossaries & Certifications](#-learning-glossaries--certifications)
- [🌐 Communities & Conferences](#-communities--conferences)
- [📑 Reference Frameworks](#-reference-frameworks)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 💡 CIAM Fundamentals

Core concepts every CIAM practitioner should know: identity lifecycle, authentication vs. authorization, consent, MFA, federation, progressive profiling, and session management.

- [What is CIAM? The complete guide](https://guptadeepak.com/ciam-compass/guides/what-is-ciam/)
- [Authentication vs. Authorization, explained properly](https://guptadeepak.com/ciam-compass/guides/authentication-vs-authorization/)
- [CIAM vs IAM vs IDaaS](https://guptadeepak.com/ciam-compass/guides/ciam-vs-iam-vs-idaas/)
- [CIAM Reference Architectures: four patterns and the vendors that fit](https://guptadeepak.com/ciam-compass/guides/ciam-reference-architectures/)
- [Session Management: JWTs vs. opaque tokens](https://guptadeepak.com/ciam-compass/guides/session-management-jwts-vs-opaque-tokens/)
- [Customer Onboarding and Progressive Profiling](https://guptadeepak.com/ciam-compass/guides/customer-onboarding-progressive-profiling/)
- [Auth0 CIAM Overview](https://auth0.com/learn/ciam/), [Okta CIAM](https://www.okta.com/customer-identity/), and [Ping Identity CIAM Go-to Guide](https://www.pingidentity.com/en/resources/blog/post/what-is-customer-identity-and-access-management-ciam.html)
- [IAM vs CIAM](https://guptadeepak.com/customer-identity-hub/ciam-vs-iam-understanding-the-critical-differences)

Key concepts: identity lifecycle, authentication, authorization, consent and privacy, MFA, SSO and federation, progressive profiling, session management, and risk-based or adaptive auth.

---

## 🧭 Decision Frameworks & Buyer Guides

Choosing, pricing, and migrating between CIAM platforms.

- [Start Here: How to choose a CIAM platform (a guided path)](https://guptadeepak.com/ciam-compass/guides/start-here-choosing-ciam/)
- [Build vs. Buy CIAM: a 2026 framework](https://guptadeepak.com/ciam-compass/guides/build-vs-buy-ciam/)
- [How to evaluate a CIAM vendor without falling for the demo](https://startwithidentity.com/)
- [CIAM Pricing Models: MAU, MTU, and the cost traps that bite at renewal](https://guptadeepak.com/ciam-compass/guides/ciam-pricing-models/)
- [The ROI of Passwordless Authentication: a CFO-ready business case](https://guptadeepak.com/ciam-compass/guides/roi-of-passwordless/)
- [The True Cost of a CIAM Breach: downside modeling](https://guptadeepak.com/ciam-compass/guides/true-cost-of-ciam-breach/)
- [How to Migrate Between CIAM Platforms: a vendor-agnostic framework](https://guptadeepak.com/ciam-compass/guides/ciam-migration-framework/)
- [Migrating off Auth0](https://guptadeepak.com/ciam-compass/guides/migrating-from-auth0/) and [Migrating from AWS Cognito](https://guptadeepak.com/ciam-compass/guides/migrating-from-cognito/)

Free decision tools on [CIAM Compass](https://guptadeepak.com/ciam-compass/): Vendor Selector, TCO Calculator, Build-vs-Buy Worksheet, and RFP Builder.

---

## 🛠️ CIAM Tools & Platforms

> 💡 For vendor-neutral, side-by-side profiles scored on the same 30+ capability matrix with TCO bands and editorial verdicts, see the **[CIAM Compass Vendor Directory](https://guptadeepak.com/ciam-compass/vendors/)** (48 platforms) and its **[118 head-to-head comparisons](https://guptadeepak.com/ciam-compass/)**.

### 🟣 Developer-First / API-First

[Auth0](https://auth0.com/) (Okta), [Clerk](https://clerk.com/), [Stytch](https://stytch.com/), [Descope](https://www.descope.com/), [Kinde](https://kinde.com/), [WorkOS](https://workos.com/), [Frontegg](https://frontegg.com/), [PropelAuth](https://www.propelauth.com/), [Scalekit](https://www.scalekit.com/), [SSOJet](https://ssojet.com/)

### 🔵 Enterprise CIAM

[Okta Customer Identity](https://www.okta.com/customer-identity/), [Microsoft Entra External ID](https://learn.microsoft.com/en-us/entra/external-id/), [Ping Identity](https://www.pingidentity.com/), [ForgeRock](https://www.forgerock.com/), [IBM Verify](https://www.ibm.com/products/verify), [CyberArk Identity](https://www.cyberark.com/), [Oracle IAM](https://www.oracle.com/security/identity-management/), [SAP Customer Data Cloud](https://www.sap.com/products/crm/customer-data-cloud.html), [Transmit Security](https://www.transmitsecurity.com/), [Strivacity](https://www.strivacity.com/), [Curity](https://curity.io/)

### ☁️ Cloud-Native / Platform

[AWS Cognito](https://aws.amazon.com/cognito/), [Firebase Authentication](https://firebase.google.com/products/auth), [Supabase Auth](https://supabase.com/auth)

### 🔓 Passwordless & Orchestration Specialists

[Beyond Identity](https://www.beyondidentity.com/), [Hanko](https://www.hanko.io/), [Corbado](https://www.corbado.com/), [MojoAuth](https://mojoauth.com/), [Authsignal](https://www.authsignal.com/), [Stytch](https://stytch.com/)

### 🟠 B2B / Multi-Tenant Specialists

[WorkOS](https://workos.com/), [Frontegg](https://frontegg.com/), [PropelAuth](https://www.propelauth.com/), [Tesseral](https://tesseral.com/), [Wristband](https://www.wristband.dev/), [SlashID](https://www.slashid.dev/), [Authress](https://authress.io/)

---

## 🟢 Open Source CIAM

Self-hostable identity platforms with public source code. Useful when data residency, deep customization, air-gapping, or cost-at-scale matter more than a fully managed service.

| Project | Description | Source |
|---|---|---|
| **Keycloak** | Red Hat-backed IAM with SSO, federation, and FGA | [keycloak/keycloak](https://github.com/keycloak/keycloak) |
| **Ory** | Composable identity (Kratos, Hydra, Keto, Oathkeeper) | [ory/kratos](https://github.com/ory/kratos) |
| **Zitadel** | Cloud-native IAM with multi-tenancy and audit trail | [zitadel/zitadel](https://github.com/zitadel/zitadel) |
| **FusionAuth** | Highly customizable, downloadable CIAM | [FusionAuth/fusionauth-containers](https://github.com/FusionAuth/fusionauth-containers) |
| **Authentik** | Flexible IdP with flows and outposts | [goauthentik/authentik](https://github.com/goauthentik/authentik) |
| **Authelia** | Authentication and 2FA portal for reverse proxies | [authelia/authelia](https://github.com/authelia/authelia) |
| **SuperTokens** | Open-source auth with prebuilt and custom UI | [supertokens/supertokens-core](https://github.com/supertokens/supertokens-core) |
| **Logto** | Modern, developer-focused identity for apps and APIs | [logto-io/logto](https://github.com/logto-io/logto) |
| **Better Auth** | Framework-agnostic auth for TypeScript | [better-auth/better-auth](https://github.com/better-auth/better-auth) |
| **Stack Auth** | Open-source Clerk/Auth0 alternative | [stack-auth/stack-auth](https://github.com/stack-auth/stack-auth) |
| **Casdoor** | UI-first IdP supporting OIDC, OAuth, SAML, CAS | [casdoor/casdoor](https://github.com/casdoor/casdoor) |
| **WSO2 Identity Server** | Enterprise-grade open-source IAM | [wso2/product-is](https://github.com/wso2/product-is) |
| **Supabase Auth** | Auth (GoTrue) within the Supabase platform | [supabase/auth](https://github.com/supabase/auth) |

---

## 🧪 Protocols & Standards

| Standard | Purpose | Reference |
|---|---|---|
| **OAuth 2.0 / 2.1** | Delegated authorization | [RFC 6749](https://datatracker.ietf.org/doc/html/rfc6749), [OAuth 2.1 explained](https://guptadeepak.com/ciam-compass/guides/oauth-2-1-explained/) |
| **OpenID Connect (OIDC)** | Identity layer on OAuth 2.0 | [openid.net](https://openid.net/connect/), [OIDC explained](https://guptadeepak.com/ciam-compass/guides/oidc-explained/) |
| **SAML 2.0** | Enterprise SSO federation | [OASIS](https://docs.oasis-open.org/security/saml/v2.0/), [SAML 2.0 explained](https://guptadeepak.com/ciam-compass/guides/saml-2-0-explained/) |
| **SCIM 2.0** | Cross-domain user provisioning | [RFC 7644](https://datatracker.ietf.org/doc/html/rfc7644), [SCIM provisioning guide](https://guptadeepak.com/ciam-compass/guides/scim-provisioning/) |
| **JWT** | Signed or encrypted tokens | [RFC 7519](https://datatracker.ietf.org/doc/html/rfc7519), [JWT explained and pitfalls](https://guptadeepak.com/ciam-compass/guides/jwt-explained/) |
| **PASETO** | JWT alternative without the footguns | [PASETO explained](https://guptadeepak.com/ciam-compass/guides/paseto-explained/) |
| **WebAuthn / FIDO2** | Phishing-resistant passwordless | [webauthn.io](https://webauthn.io/), [WebAuthn](https://guptadeepak.com/ciam-compass/guides/webauthn-explained/), [FIDO2/CTAP2](https://guptadeepak.com/ciam-compass/guides/fido2-explained/) |
| **PKCE** | Auth-code protection for public clients | [RFC 7636](https://datatracker.ietf.org/doc/html/rfc7636) |
| **mTLS** | Mutual TLS for service and API identity | [mTLS explained](https://guptadeepak.com/ciam-compass/guides/mtls-explained/) |
| **DPoP, PAR, CIBA, Token Exchange, Device Grant** | Advanced OAuth profiles | [Start With Identity glossary](https://startwithidentity.com/glossary) |

---

## 🔑 Authentication Methods

- [Passwordless Authentication: a 2026 practitioner's guide](https://guptadeepak.com/ciam-compass/guides/passwordless-authentication/)
- [Passkeys explained: how synced credentials replace passwords](https://guptadeepak.com/ciam-compass/guides/passkeys-explained/) and [Passkeys vs Passwords](https://guptadeepak.com/ciam-compass/guides/passkeys-vs-passwords/)
- [Multi-Factor Authentication (MFA): a 2026 guide](https://guptadeepak.com/ciam-compass/guides/multi-factor-authentication-mfa/) and [MFA vs 2FA](https://guptadeepak.com/ciam-compass/guides/mfa-vs-2fa/)
- [TOTP vs SMS OTP](https://guptadeepak.com/ciam-compass/guides/totp-vs-sms-otp/) and [Deprecating SMS OTP in 2026](https://guptadeepak.com/ciam-compass/guides/sms-otp-deprecation-2026/)
- [Magic Links vs OTP: picking the passwordless fallback](https://guptadeepak.com/ciam-compass/guides/magic-links-vs-otp/)
- [Biometric Authentication: fingerprint, face, and beyond](https://guptadeepak.com/ciam-compass/guides/biometric-authentication-guide/)
- [Social Login: implementation, trade-offs, and the privacy cost](https://guptadeepak.com/ciam-compass/guides/social-login/)
- [Password Manager vs Passwordless](https://guptadeepak.com/ciam-compass/guides/password-manager-vs-passwordless/)

---

## 🧱 Authorization Models

- [RBAC vs ABAC vs ReBAC: choosing an authorization model](https://guptadeepak.com/ciam-compass/guides/rbac-vs-abac-vs-rebac/)
- [Fine-Grained Authorization (FGA): a 2026 implementation guide](https://guptadeepak.com/ciam-compass/guides/fine-grained-authorization-fga/)
- [Google Zanzibar explained: the model behind modern FGA](https://guptadeepak.com/ciam-compass/guides/zanzibar-explained/)
- [API Authorization Patterns](https://guptadeepak.com/ciam-compass/guides/api-authorization-patterns/)
- Open standards and engines: [OpenFGA](https://openfga.dev/), [Oso](https://www.osohq.com/), [Cerbos](https://www.cerbos.dev/), [SpiceDB](https://authzed.com/spicedb), [OPA / Rego](https://www.openpolicyagent.org/)

---

## 🔐 Security & Threat Defense

- [Account Takeover Defense: a layered approach for 2026](https://guptadeepak.com/ciam-compass/guides/account-takeover-defense/)
- [Account Recovery Design: the most-attacked flow in CIAM](https://guptadeepak.com/ciam-compass/guides/account-recovery-design/)
- [Adaptive Risk-Based Authentication: decisioning at login](https://guptadeepak.com/ciam-compass/guides/adaptive-risk-based-authentication/)
- [Bot Defense and Fraud Detection for auth endpoints](https://guptadeepak.com/ciam-compass/guides/bot-defense/)
- [DDoS and Rate-Limiting for auth endpoints](https://guptadeepak.com/ciam-compass/guides/ddos-rate-limiting-auth/)
- [ITDR: Identity Threat Detection and Response in CIAM](https://guptadeepak.com/ciam-compass/guides/itdr-identity-threat-detection-response/)
- [Password Security and Storage: hashing, salting, what works in 2026](https://guptadeepak.com/ciam-compass/guides/password-security-and-storage/)
- [Token Lifetime Best Practices](https://guptadeepak.com/ciam-compass/guides/token-lifetime-best-practices/)
- [Symmetric vs Asymmetric Encryption](https://guptadeepak.com/ciam-compass/guides/symmetric-vs-asymmetric-encryption/) and [Post-Quantum Cryptography for Auth](https://guptadeepak.com/ciam-compass/guides/post-quantum-cryptography-for-auth/)

Common threats to design against: account takeover, credential stuffing, password spraying, session hijacking, token theft, MFA fatigue, infostealers, and bot-driven fake signups.

---

## ⚖️ Privacy, Consent & Compliance

- [GDPR and CIAM: a practical compliance guide](https://guptadeepak.com/ciam-compass/guides/gdpr-and-ciam/)
- [CCPA and CIAM: California privacy for consumer apps](https://guptadeepak.com/ciam-compass/guides/ccpa-and-ciam/)
- [HIPAA and CIAM: the healthcare identity checklist](https://guptadeepak.com/ciam-compass/guides/hipaa-and-ciam/)
- [PCI DSS 4.0 and CIAM: identity for payment workloads](https://guptadeepak.com/ciam-compass/guides/pci-dss-and-ciam/)
- [SOC 2 and CIAM: what auditors actually look at](https://guptadeepak.com/ciam-compass/guides/soc2-and-ciam/)
- [Identity Verification and Proofing (IDV/KYC)](https://guptadeepak.com/ciam-compass/guides/identity-verification-kyc/)
- [Data Residency and Sovereignty: where your auth data lives](https://guptadeepak.com/ciam-compass/guides/data-residency-and-sovereignty/)
- [Consent Management Platforms (CMPs) and CIAM](https://guptadeepak.com/ciam-compass/guides/consent-management-cmps/)
- Standards: [NIST SP 800-63](https://pages.nist.gov/800-63-3/), [eIDAS](https://digital-strategy.ec.europa.eu/en/policies/eidas-regulation), PSD2, FedRAMP

---

## 🤖 Agentic & Non-Human Identity

The fastest-growing frontier in CIAM is authenticating and authorizing AI agents, machines, workloads, and service accounts.

- [AI Agent Identity and MCP: authenticating non-human identities](https://guptadeepak.com/ciam-compass/guides/ai-agent-identity-mcp/)
- [Authentication for AI Agents: OAuth patterns for NHI](https://guptadeepak.com/ciam-compass/guides/authentication-for-ai-agents/)
- [Authorization Patterns for Agentic Workflows: delegation, constraints, JIT permissions](https://guptadeepak.com/ciam-compass/guides/authorization-patterns-for-agentic-workflows/)
- [MCP Server Identity Model: auth and trust for the Model Context Protocol](https://guptadeepak.com/ciam-compass/guides/mcp-server-identity-model/)
- [Token Management for AI Agents: lifetimes, rotation, revocation at machine speed](https://guptadeepak.com/ciam-compass/guides/token-management-for-ai-agents/)
- Related: [SPIFFE/SPIRE](https://spiffe.io/) for workload identity, and [What is a Non-Human Identity (NHI)?](https://startwithidentity.com/)

---

## 🏢 B2B & Multi-Tenant Identity

- [B2B SaaS Identity: organizations, SSO, SCIM, and the enterprise sales checklist](https://guptadeepak.com/ciam-compass/guides/b2b-saas-identity/)
- [Organizations and Tenants in B2B CIAM: modeling customer boundaries](https://guptadeepak.com/ciam-compass/guides/organizations-and-tenants/)
- [Multi-Tenant Architecture for CIAM: patterns and trade-offs](https://guptadeepak.com/ciam-compass/guides/multi-tenant-architecture/)
- [Enterprise SSO: SAML vs OIDC, and how to pick](https://guptadeepak.com/ciam-compass/guides/enterprise-sso-saml-vs-oidc/)
- [SCIM vs SAML: provisioning vs authentication, and why you need both](https://guptadeepak.com/ciam-compass/guides/scim-vs-saml/)
- [SSO vs Federation](https://guptadeepak.com/ciam-compass/guides/sso-vs-federation/)

---

## 👨‍💻 Developer SDKs & APIs

- **JavaScript / TypeScript:** [Auth.js / NextAuth](https://authjs.dev/), [Auth0.js](https://github.com/auth0/auth0.js), [Better Auth](https://www.better-auth.com/), [Lucia](https://lucia-auth.com/)
- **Python:** [Authlib](https://docs.authlib.org/), [python-jose](https://github.com/mpdavis/python-jose), Flask-OIDC
- **Java:** [Spring Security OAuth](https://spring.io/projects/spring-security), Keycloak adapters
- **Go:** [go-oidc](https://github.com/coreos/go-oidc), [Ory Hydra](https://www.ory.sh/hydra/), [zitadel/oidc](https://github.com/zitadel/oidc)
- **Node.js:** [Passport.js](https://www.passportjs.org/), [FusionAuth Node client](https://github.com/FusionAuth/fusionauth-node-client)
- **Mobile:** Auth0 SDKs (iOS/Android), [Firebase Authentication](https://firebase.google.com/products/auth), [AWS Amplify Auth](https://docs.amplify.aws/)
- **WebAuthn / Passkeys:** [SimpleWebAuthn](https://simplewebauthn.dev/), [Hanko Elements](https://www.hanko.io/), [passkeys.dev](https://passkeys.dev/)

---

## 🧩 Integration Examples & Starters

- [Auth0 (GitHub org)](https://github.com/auth0) with the [Next.js + Auth0 starter](https://github.com/auth0/nextjs-auth0) and [React samples](https://github.com/auth0-samples/auth0-react-samples)
- [MojoAuth (GitHub org)](https://github.com/mojoauth) for passwordless and passkey demos
- [WorkOS (GitHub org)](https://github.com/workos) with the [Next.js AuthKit starter](https://github.com/workos/authkit-nextjs)
- [SSOJet (GitHub org)](https://github.com/ssojet) for enterprise SSO and SCIM examples
- [Ory Kratos reference](https://github.com/ory/kratos)
- [Keycloak quickstarts](https://github.com/keycloak/keycloak-quickstarts)
- [SuperTokens example apps](https://github.com/supertokens/supertokens-core)
- [SimpleWebAuthn passkey demos](https://github.com/MasterKale/SimpleWebAuthn)

---

## 🧠 Identity UX / CX

The login box is a conversion surface, so design it accordingly.

- IAM/CIAM UX design principles for frictionless, accessible identity systems ([Start With Identity](https://startwithidentity.com/))
- Signup and onboarding flow best practices, plus [progressive profiling](https://guptadeepak.com/ciam-compass/guides/customer-onboarding-progressive-profiling/)
- Consent UX patterns and accessibility (WCAG) in login forms
- Social login design do's and don'ts, and passwordless-first UX
- Continuous and invisible authentication beyond passwords ([Start With Identity](https://startwithidentity.com/))

---

## 🏭 Industry & Vertical Guides

CIAM requirements shift dramatically by industry. The [CIAM Compass vertical guides](https://guptadeepak.com/ciam-compass/) cover **19 sectors**, each with use cases, vendor fit, and a 2027-2030 outlook:

Financial services, insurance, healthcare and life sciences, retail and e-commerce, D2C brands, consumer apps and marketplaces, B2B SaaS, gaming, iGaming and gambling, media and streaming, travel and hospitality, automotive and connected vehicles, energy and utilities, education and EdTech, government and cities, real estate and proptech, crypto and Web3, and non-profit and civic.

> Examples: [Healthcare and life sciences](https://guptadeepak.com/ciam-compass/verticals/healthcare/) (HIPAA, NIST 800-63 proofing) and [Media and streaming](https://guptadeepak.com/ciam-compass/verticals/media-streaming/) (household identity, password-sharing enforcement).

---

## 📈 Analytics & Identity Intelligence

- CIAM and CDP integration (Segment, Amplitude, mParticle)
- Identity as a personalization layer
- Real-time login and auth event tracking
- Behavior-based fraud and anomaly detection
- Funnel analytics for signup and login conversion

---

## 🎓 Learning, Glossaries & Certifications

- [Start With Identity Glossary](https://startwithidentity.com/glossary) with 100+ identity and CIAM terms (protocols, concepts, threats, compliance, emerging tech)
- [Start With Identity Guides](https://startwithidentity.com/) with 50+ practitioner guides across all six identity pillars
- [CIAM Compass Guides](https://guptadeepak.com/ciam-compass/) with 68 deep-dive practitioner guides
- [IDPro Body of Knowledge](https://bok.idpro.org/)
- [Auth0 Learning Center](https://auth0.com/learn/), [Okta Developer Docs](https://developer.okta.com/)
- [OpenID Foundation](https://openid.net/foundation/) and [FIDO Alliance resources](https://fidoalliance.org/)

---

## 🌐 Communities & Conferences

- [Identiverse](https://identiverse.com/), [Gartner IAM Summit](https://www.gartner.com/en/conferences/calendar/iam), [KuppingerCole / EIC](https://www.kuppingercole.com/events), and [FIDO Authenticate](https://authenticatecon.com/)
- [IDPro](https://idpro.org/), the professional association for identity practitioners
- [OpenID Foundation](https://openid.net/) and [FIDO Alliance](https://fidoalliance.org/)
- [r/IdentityManagement](https://www.reddit.com/r/IdentityManagement/) and Stack Overflow tags `oauth-2.0`, `openid-connect`, `saml`, `webauthn`

---

## 📑 Reference Frameworks

### CIAM Capability Matrix (8 evaluation groups)

A vendor-neutral way to compare platforms, from the [CIAM Compass methodology](https://guptadeepak.com/ciam-compass/methodology/):

1. **Authentication:** methods, passwordless, passkey orchestration
2. **Authorization:** RBAC/ABAC/ReBAC, FGA, API authz
3. **User Management:** lifecycle, profiles, directory, migration
4. **Developer Experience:** SDKs, docs, time-to-first-login
5. **Security:** threat defense, token handling, anomaly detection
6. **Agentic Identity:** AI agent and non-human identity support
7. **Compliance:** certifications, data residency, audit
8. **Consent / Privacy:** consent capture, preference management

Capabilities are rated `true`, `partial`, or `false`. Five dimensions (DX, docs quality, passkey orchestration, pricing transparency, migration difficulty) use a 1 to 5 scale. No aggregate score is published, because aggregate scores obscure trade-offs.

### TCO / Pricing Bands

CIAM cost is usually driven by Monthly Active Users (MAU). Compare vendors at consistent tiers (10K, 100K, 500K, and 1M MAU) with standard assumptions: roughly 60% activity rate, one MFA factor, standard support, US data residency, and no add-ons. Watch for renewal cost traps such as MAU vs MTU billing, an SSO tax, and add-on modules. See [CIAM Pricing Models](https://guptadeepak.com/ciam-compass/guides/ciam-pricing-models/).

### Hosted vs. Self-Hosted heuristic

| Choose **SaaS / hosted** when... | Choose **self-hosted / open-source** when... |
|---|---|
| Speed-to-market matters most | Data residency or sovereignty is mandatory |
| You have a small identity or platform team | You need deep customization or air-gapping |
| You want predictable, managed compliance | Cost at very high MAU must be controlled |
| Your auth requirements are standard | You have identity engineering capacity |

---

## 🤝 Contributing

Contributions are welcome. Help grow this resource by adding quality tools, guides, standards, or examples.

1. Fork this repo
2. Add your link in the appropriate section (keep entries vendor-neutral and high-signal)
3. Open a pull request describing what you added and why

Please prefer authoritative, durable sources over marketing pages, and keep formatting consistent with existing entries.

---

## 📄 License

This project is licensed under the **[Creative Commons CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)**.
You are free to share and adapt this material with attribution.

---

## ⭐ Star This Repo

If you found this useful, please star [the repo](https://github.com/guptadeepak/awesome-customer-iam) to help others discover it.

## 💬 Feedback & Ideas

Have suggestions or topics you'd like to see added? Open an [Issue](https://github.com/guptadeepak/awesome-customer-iam/issues) or start a [Discussion](https://github.com/guptadeepak/awesome-customer-iam/discussions).
