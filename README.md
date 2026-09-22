# Awesome-Identity-Management

## Top Identity Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on SSO, MFA, Identity Providers, Workforce & Customer IAM, Federation & Access Management*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Management (IAM)**. These systems provide authentication, single sign-on (SSO), multi-factor authentication (MFA), user lifecycle, federation, and access control for workforce and customer identities.



**Examples** include Okta, Microsoft Entra ID, Ping Identity, ForgeRock, OneLogin, JumpCloud, IBM Security Verify, Auth0, CyberArk Identity, and SailPoint (the category leaders).



**Open-source emphasis**: Identity management has excellent open-source options. **Keycloak**, **Authentik**, **FreeIPA**, **Ory**, **Zitadel**, and related projects enable full self-hosted IdP and SSO capabilities. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Okta](https://www.okta.com/)**  

  Leading cloud identity platform for workforce and customer IAM, with extensive app integrations, SSO, MFA, and lifecycle management.



- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  

  Microsoft’s cloud identity and access management service (formerly Azure AD), tightly integrated with Microsoft 365 and Azure environments.



- **[Ping Identity](https://www.pingidentity.com/)**  

  Enterprise identity platform strong in hybrid deployments, federation, and large-scale consumer (CIAM) use cases (includes ForgeRock capabilities post-merger).



- **[ForgeRock (now part of Ping Identity)](https://www.pingidentity.com/)**  

  Historically a major identity platform for complex, high-scale, and highly customized IAM and CIAM scenarios.



- **[OneLogin (One Identity)](https://www.onelogin.com/)**  

  Cloud IAM platform focused on SSO, MFA, and directory integration for mid-market and enterprise organizations.



- **[JumpCloud](https://jumpcloud.com/)**  

  Cloud directory and identity platform combining device management, SSO, and user lifecycle for modern IT environments.



- **[IBM Security Verify](https://www.ibm.com/products/verify-identity)**  

  IBM’s identity and access management suite supporting workforce and consumer identity, MFA, and risk-based access.



- **[Auth0 (Okta)](https://auth0.com/)**  

  Developer-focused identity platform for application authentication, widely used for CIAM and custom login experiences.



- **[CyberArk Identity](https://www.cyberark.com/)**  

  Identity security platform emphasizing privileged and workforce identity, SSO, and adaptive MFA within the CyberArk portfolio.



- **[SailPoint](https://www.sailpoint.com/)**  

  Identity governance and administration (IGA) leader focused on access certification, provisioning, and compliance—often paired with access management platforms.



## Open-Source GitHub Projects

- **[Keycloak](https://github.com/keycloak/keycloak)**  

  Leading open-source identity and access management solution supporting SSO, OIDC, SAML, identity brokering, user federation, and fine-grained authorization (Apache 2.0).



- **[Authentik](https://github.com/goauthentik/authentik)**  

  Modern open-source identity provider with a strong admin UI, flexible authentication flows, SAML, OIDC, LDAP, RADIUS, and reverse-proxy capabilities (MIT core).



- **[FreeIPA](https://github.com/freeipa/freeipa)**  

  Open-source integrated identity management system combining LDAP, Kerberos, DNS, certificate authority, and policy for Linux/Unix environments.



- **[Ory (Kratos, Hydra, Oathkeeper, Keto)](https://github.com/ory)**  

  Modular open-source identity stack for authentication, OAuth2/OIDC, access control, and zero-trust style gateways—popular for cloud-native and multi-tenant apps.



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  Open-source identity and access management platform focused on modern multi-tenant and cloud-native use cases with strong developer experience.



- **[Casdoor](https://github.com/casdoor/casdoor)**  

  Open-source UI-first identity and access management platform supporting OAuth 2.0, OIDC, SAML, and multiple identity providers.



- **[Authelia](https://github.com/authelia/authelia)**  

  Open-source authentication and authorization server providing 2FA and single sign-on for reverse proxies and self-hosted applications.



- **[Gluu / Janssen Project](https://github.com/JanssenProject)**  

  Open-source identity platform lineage focused on large-scale and enterprise IAM capabilities.



- **[SuperTokens / Logto / similar developer IdPs](https://github.com/)**  

  Open-source authentication solutions aimed at application developers who want to own login without heavy IdP operations.



- **[LDAP, SAML, and federation open libraries](https://github.com/)**  

  Foundational open components used to build custom identity and federation stacks.



### Additional Strong Open-Source Options

- Deploying **Keycloak** as the default full-featured self-hosted IdP for workforce and moderate-scale CIAM.

- Choosing **Authentik** for a modern UI, flexible flows, and broader protocol support out of the box.

- Using **FreeIPA** when deep Linux/Unix directory, Kerberos, and policy integration is required.

- Building cloud-native identity with **Ory** or **Zitadel** for multi-tenant SaaS and microservices.

- Combining open IdPs with commercial IGA (e.g., SailPoint) for governance while keeping authentication open.

- Accepting that massive app catalogs, global SLA, advanced adaptive MFA analytics, and turnkey enterprise support still favor commercial platforms (Okta, Entra ID, Ping, Auth0, etc.).

- Focusing open-source efforts on data residency, cost control, and full ownership of identity infrastructure.



**Frameworks for building custom systems**: Run Keycloak or Authentik as the IdP → federate directories and applications via OIDC/SAML → enforce MFA and policies → integrate with open or commercial directories → add governance workflows as needed. Suitable for organizations with identity operations capacity. Most large enterprises adopt commercial IAM platforms for scale and support while many mid-market and self-hosted environments run open IdPs successfully.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity systems are security-critical. Misconfiguration can lead to unauthorized access. Open-source or self-hosted IdPs require hardened deployment, monitoring, backup, and expertise. This list is not security advice.



---

**Made for identity architects, security teams, and platform engineers managing access at scale.**

Let's keep identity standards-based, resilient, and as open as practical.
