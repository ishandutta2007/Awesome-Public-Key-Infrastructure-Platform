# Awesome-Public-Key-Infrastructure-Platform

## Top Public Key Infrastructure (PKI) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Certificate Authorities, Certificate Lifecycle Management, Machine Identity, Automation & Trust Services*

**Last updated: September 2026**



This repository tracks notable **SaaS/enterprise platforms** and **open-source projects** for **Public Key Infrastructure (PKI)**. These systems issue, renew, revoke, and govern digital certificates for machines, users, devices, and workloads across enterprise and cloud environments.



**Examples** include Keyfactor, Venafi, Entrust, DigiCert, PrimeKey EJBCA, Microsoft Active Directory Certificate Services, KeyTalk, AppViewX, GlobalSign, and Sectigo (the category leaders).



**Open-source emphasis**: PKI has a mature and strong open-source ecosystem. **EJBCA Community**, **step-ca**, **OpenXPKI**, **Dogtag**, **CFSSL**, **cert-manager**, and related projects are widely used in production. This section is heavily expanded with these tools.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Keyfactor](https://www.keyfactor.com/)** | Certificate lifecycle management and PKI platform that combines CLM capabilities with EJBCA as its open-source CA engine; available in SaaS and self-hosted forms. | Est. starting at ~£40,250/yr (~$52,000/yr benchmark via G-Cloud listing; enterprise tiers ~$2,000–$10,000/mo) | 30-day free trial ("Test Drive" on AWS/Azure Marketplace) |
| **[Venafi (CyberArk Certificate Manager)](https://www.venafi.com/)** | Leading machine identity and certificate lifecycle management platform (now part of CyberArk) for discovering, protecting, and automating certificates at scale. | Enterprise tiers starting at ~$1,500–$5,000/mo (~$18,000+/yr benchmark based on deployment volume) | 30-day free trial (Venafi TLS Protect Cloud / CyberArk Certificate Manager SaaS) |
| **[Entrust PKI](https://www.entrust.com/)** | Enterprise PKI and certificate management solutions for issuing and governing digital certificates and identities. | Managed PKI starting at ~$4,000/yr (test/small envs) up to ~$50,000+/yr for enterprise production | 60-day free trial (Managed PKI 60-day evaluation) |
| **[DigiCert](https://www.digicert.com/)** | Public and private PKI plus Trust Lifecycle Manager for enterprise digital trust and certificate automation. | Direct OV TLS certs starting at $24–$26/mo ($288/yr); reseller tiers from ~$12.50/mo ($150/yr) | No free-forever plan (30-day money-back guarantee; Test Drive account for PKI testing) |
| **[PrimeKey EJBCA Enterprise](https://www.keyfactor.com/)** | Enterprise edition of the widely deployed EJBCA certificate authority (now part of the Keyfactor ecosystem). | AWS EC2 hourly pay-as-you-go starting at ~$0.50–$3.00/hr (~$360–$2,160/mo based on instance size) | 30-day free trial (EJBCA Enterprise Cloud 30-day trial on AWS Marketplace) |
| **[Microsoft Active Directory Certificate Services (AD CS)](https://learn.microsoft.com/en-us/windows-server/identity/ad-cs/)** | Microsoft’s on-premises enterprise CA and certificate services tightly integrated with Active Directory environments (plus Cloud PKI). | Included with Windows Server license (Essentials $501, Standard $1,069); Cloud PKI add-on at $2.00/user/mo | 180-day free trial (Windows Server Evaluation Edition valid for 180 days) / 30-day Intune trial for Cloud PKI |
| **[KeyTalk](https://www.keytalk.com/)** | Certificate and PKI-related solutions focused on automated certificate management and delivery. | Enterprise starting tier benchmark at ~€10,000/yr (~$11,000/yr for ~1,000 users base deployment) | Custom evaluation / trial license available upon request for Proof of Concept (PoC) |
| **[AppViewX](https://www.appviewx.com/)** | Certificate lifecycle and PKI automation platform focused on visibility, orchestration, and policy-driven management. | Enterprise tiers starting at ~$1,000–$3,000/mo (~$12,000+/yr base tier) | 30-day free trial (extendable up to 90 days upon request) |
| **[GlobalSign](https://www.globalsign.com/)** | Public CA and PKI services providing trusted certificates and related identity solutions. | AlphaSSL starting at $12–$49/yr; direct DomainSSL starting at $99–$249/yr | No free-forever plan (7 to 30-day money-back guarantee depending on reseller/product) |
| **[Sectigo](https://www.sectigo.com/)** | Public and private PKI services along with certificate management offerings for organizations of various sizes. | DV SSL starting at $96–$99/yr direct (~$12/yr via reseller); Sectigo Certificate Manager starting at ~$2,500/yr | 30-day free trial (Sectigo Certificate Manager 30-day evaluation trial) |



## Open-Source GitHub Projects

- **[EJBCA Community](https://github.com/Keyfactor/ejbca-ce)**  

  The leading open-source enterprise Certificate Authority. Supports complex hierarchies, SCEP, CMP, ACME, and a wide range of protocols. Widely used as the foundation for many commercial PKI offerings.



- **[step-ca (Smallstep)](https://github.com/smallstep/certificates)**  

  Modern, lightweight open-source online Certificate Authority focused on automated, short-lived certificates, ACME, and easy internal PKI.



- **[OpenXPKI](https://github.com/openxpki/openxpki)**  

  Full-featured open-source trustcenter/PKI software with workflow engine, SCEP/EST support, multi-CA capabilities, and enterprise-oriented features.



- **[Dogtag Certificate System](https://github.com/dogtagpki/pki)**  

  Enterprise-class open-source CA from the Dogtag project (used in FreeIPA/Red Hat environments) supporting full certificate lifecycle, OCSP, KRA, and related subsystems.



- **[CFSSL (Cloudflare)](https://github.com/cloudflare/cfssl)**  

  Cloudflare’s open-source PKI and TLS toolkit for building custom CAs, signing certificates, and handling related cryptographic operations.



- **[cert-manager](https://github.com/cert-manager/cert-manager)**  

  Kubernetes-native open-source certificate management controller that automates issuance and renewal (commonly used with ACME or internal CAs).



- **[HashiCorp Vault (PKI secrets engine)](https://github.com/hashicorp/vault)**  

  Open-source secrets management platform whose PKI secrets engine can act as a dynamic certificate authority for short-lived certificates.



- **[Boulder (Let's Encrypt)](https://github.com/letsencrypt/boulder)**  

  Open-source ACME CA software that powers Let’s Encrypt; useful as a reference or for private ACME-based deployments.



- **[Easy-RSA and OpenSSL-based PKI toolkits](https://github.com/)**  

  Classic open tools and scripts for building simple internal PKIs with OpenSSL.



- **[Additional ACME clients and automation projects](https://github.com/)**  

  Certbot, lego, and other open clients that automate certificate issuance and renewal against ACME-compatible CAs.



### Additional Strong Open-Source Options

- Using **EJBCA Community** or **OpenXPKI** for full enterprise-style internal CAs with protocol support (SCEP, CMP, etc.).

- Deploying **step-ca** for modern, automated internal PKI with short-lived certificates.

- Running **cert-manager** in Kubernetes environments for workload certificate automation.

- Leveraging **Vault’s PKI engine** when already using HashiCorp Vault for secrets.

- Accepting that large-scale discovery, multi-CA orchestration, advanced policy engines, and enterprise support still favor commercial CLM platforms (Venafi/CyberArk, Keyfactor, DigiCert, AppViewX, etc.).



**Frameworks for building custom systems**: Deploy an open CA (EJBCA, step-ca, OpenXPKI, or Dogtag) → issue and renew certificates via ACME/SCEP/API → automate with cert-manager or custom workflows → store roots and intermediates securely (HSM where required) → monitor expiration and revocation. This stack is fully open and production-proven for many organizations. Commercial platforms remain the practical choice when deep discovery, cross-platform orchestration, and enterprise governance are required.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- PKI underpins trust for TLS, code signing, authentication, and machine identity. Misconfigured CAs, weak key protection, or poor lifecycle practices can create severe security risks. Open-source PKI must be operated with strong operational security, proper HSMs where appropriate, and clear certificate policies. This list is not security or compliance advice.



---

**Made for security, platform, and infrastructure teams who need reliable certificate and machine identity management.**

Let's keep PKI automated, transparent, and as open as practical.
