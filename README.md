# Awesome-Document-Verification-Digital-Attestation

## Top Document Verification & Digital Attestation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on E-Signature Workflows, Cryptographic Sealing & Self-Hosted Attestation Engines*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Verification & Digital Attestation**. These tools help organizations execute agreements with legal validity and prove document integrity—covering everything from commercial e-signature platforms with audit trails to open-source engines that cryptographically seal PDFs and self-hosted workflow tools that keep signing evidence on your own infrastructure.

**Examples** include DocuSign, Adobe Acrobat Sign, Dropbox Sign, OneSpan Sign, DocuSeal, OpenSign, and SignFuz (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted e-signature, open-source PDF signing, and community-driven attestation—ideal for teams seeking data sovereignty, avoiding per-envelope SaaS fees, and maintaining full control over signing evidence. The open-source landscape is genuinely functional: **DocuSeal** leads as the most mature DocuSign alternative with AI-powered field detection , **Documenso** offers a modern TypeScript stack with MIT licensing , and **SignFuz** brings native signing workflows directly into WordPress .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global document verification, digital attestation, and e-signature market is valued at approximately **$14B–$17B in 2025–2026**, on track to surpass **$65B+ by the early 2030s** at a ~25–35% CAGR driven by regulatory compliance mandates (such as eIDAS 2.0 and KYC/AML) and escalating anti-fraud requirements against AI-generated forgery. The sector displays a **moderately concentrated, winner-take-most structure at the enterprise layer**—where tech giants and dedicated incumbents (Adobe, DocuSign) dominate enterprise legal agreements—while remaining **moderately fragmented across mid-market, SMB, and developer niches** through specialized workflow automation, cost-effective API services, and self-hosted open-source alternatives.

## SaaS/Hosted Platforms

| Platform | Company Scale (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier Limits / Trial | Key Features & Target Use Case |
| :--- | :--- | :--- | :--- | :--- |
| **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)** | **~$26.5B revenue** / **~$85B–$90B market cap** *(Adobe Inc., NASDAQ: ADBE)* | **$12.99–$14.99/mo** (Acrobat Standard, billed annually) or **$23.99/mo** (Acrobat Pro, billed annually); Team plans start at **$16.99/user/mo** | **No permanent free sending tier**; offers a **7-day free trial** for individuals/teams (or **30-day free trial** for enterprise Acrobat Sign Solutions with full API and sandbox testing). Free signers can review and sign without limit. | Deep PDF-native document workflows and enterprise e-signatures bundled into the Acrobat ecosystem. Ideal for organizations standardized on Adobe Acrobat and Microsoft 365. |
| **[DocuSign](https://www.docusign.com/)** | **~$3.36B TTM revenue** / **~$14B–$15B market cap** *(NASDAQ: DOCU)* | **$10.00/mo** (Personal plan, billed annually at $120/yr) or **$15/mo** monthly; Standard plan starts at **$25/user/mo** | **No permanent free sending tier**; offers a **30-day free trial** with full Business Pro features and sending capabilities (no credit card required). Includes a **Free Signer Account** allowing unlimited signing and storage of incoming documents. | The global enterprise category standard for e-signatures and Intelligent Agreement Management (IAM), offering complete audit trails, certificates of completion, and comprehensive CRM/ERP integrations. |
| **[Dropbox Sign](https://sign.dropbox.com/)** | **~$2.53B TTM revenue** / **~$7.5B–$8.0B market cap** *(Parent: Dropbox Inc., NASDAQ: DBX; acquired for $230M)* | **$15.00/mo** (Essentials plan, billed annually at $180/yr) or **$20/mo** monthly; Standard team plan starts at **$25/user/mo** (min. 2 seats) | **Free forever plan available: 3 signature requests per 30 days**, basic audit trails, and status notifications (templates excluded). Also provides a **30-day free trial** for paid plans. | High-usability e-signature platform offering unlimited document requests on all paid plans, turnkey cloud integrations, and developer SDKs for Node, Python, Java, and Go. |
| **[PandaDoc](https://www.pandadoc.com/)** | **~$100M+ ARR** / **$1.0B valuation** *(Series C Unicorn)* | **$19.00/user/mo** (Starter plan, billed annually at $228/yr) or **$35/user/mo** monthly; Business tier at **$49/user/mo** | **Free forever plan available (*Free eSign*)**: **5 documents per month**, up to 2 signers per document, unlimited signatures, payment collection, and mobile app access. Also offers a **14-day free trial** of paid plans. | End-to-end proposal, contract generation, CPQ (Configure, Price, Quote), and document workflow automation with rich drag-and-drop document design tools. |
| **[OneSpan Sign](https://www.onespan.com/)** | **~$253M TTM revenue** / **~$800M market cap** *(OneSpan Inc., NASDAQ: OSPN)* | **$22.00/user/mo** (Professional plan, billed annually) | **No permanent free sending tier**; offers a **30-day free trial** (unrestricted testing with no credit card required; data kept for 120 days post-trial). | Bank-grade security and authentication, digital identity verification, tamper-evident sealing, and strict audit compliance designed for regulated financial services and healthcare. |

## Open-Source GitHub Projects

- **[DocuSeal](https://github.com/docusealco/docuseal)**  
  **The most mature open-source DocuSign alternative with AI-powered field detection.** **AGPL-3.0**, Ruby on Rails + PostgreSQL/SQLite. **Free Community Edition: unlimited envelopes and seats**. **AI-powered field detection** (v2.3.0+) automatically identifies form fields in PDF documents . **WYSIWYG PDF form editor** with 12 field types, multiple signatories, and **tamper-evident audit certificate**. **Docker runs as non-root** since v2.3.0 for improved security . Pro adds white-labeling, SSO/SAML, SMS verification, and embedded signing. **SOC-2 and ISO-27001 certified** . **Best for teams wanting a mature, feature-complete self-hosted signing platform** with the simplest Docker deployment path.

- **[Documenso](https://github.com/documenso/documenso)**  
  **The modern TypeScript/Next.js e-signature platform with MIT licensing.** **AGPL-3.0 Community Edition**, TypeScript/React/Next.js. **Free self-host of Community Edition** . **Advanced multi-party signing order, passkey signing authentication, SHA-256 hash + audit log, and cryptographic PDF signing** with optional timestamp authority (RFC 3161). **Full REST API with webhooks** for integration. Docker/Kubernetes/Railway deployment. **Best for developer platforms wanting a modern stack with strong API and passkey support**—and the most permissive licensing among leading open-source options.

- **[OpenSign](https://github.com/OpenSignLabs/OpenSign)**  
  **Node.js/MongoDB e-signature with full document lifecycle management.** **AGPL-3.0 with directory exceptions** (check LICENSE). **Cryptographic signing, detailed audit trails with IP tracking**, completion certificates, reusable templates, signing order, guest email verification codes, and REST API. Freemium model. Docker deployment with MongoDB, SMTP/Mailgun, and signature certificates. **Best for teams wanting a Node.js-based platform** with customizable PDF generation templates.

- **[SignFuz](https://wordpress.org/plugins/sign-fuz/)**  
  **Self-hosted e-signature engine for WordPress with zero mandatory SaaS fees.** **GPLv2 licensed** . **Pixel-perfect PDF field placement** (signature, name, date, text), **multi-party signing with parallel or sequential workflows**, Tailwind/React UI, **cryptographic evidence trail** (signer consent, timestamps, SHA-256 event chains), automated Certificate of Completion, and private storage vault. REST API endpoints for document and envelope management . **Best for WordPress sites needing native e-signature** without external services.

- **[LibreSign](https://github.com/LibreSign/libresign)**  
  **Nextcloud-integrated e-signature.** **AGPL-3.0**, PHP/JavaScript. Sign documents directly within your Nextcloud instance. **Best for organizations already on Nextcloud** wanting native signing without a separate platform.

### Additional Strong Open-Source Options

- **[Lifted Sign](https://github.com/topics/document-verification)** — **Self-hostable, ESIGN/UETA-compliant e-signature server** producing PAdES/PKCS#7-sealed PDFs with audit-trail certificates. Python, AGPL-3.0 . Best for developers building signing workflows into legal apps with standards-based sealing.
- **[Attestto Verify](https://verify.attestto.com)** — **Client-side, zero-upload browser library for verifying PDF digital signatures** under PAdES, CAdES, PKCS#7, and X.509 PKI standards including eIDAS. TypeScript, Apache-2.0 . Best for verifying signatures without uploading documents to a third party.
- **[sealed-pdf-verify](https://github.com/topics/document-verification)** — **Offline verifier for sealed PDFs** (detached ECDSA P-256 signature, RFC 3161 timestamp, hash-chain ledger) as library, CLI, and browser page. TypeScript, MIT . Best for legal intake teams confirming a document has not changed since sealing.

**Frameworks for building custom systems**: Choose **DocuSeal** for the most mature self-hosted signing platform with AI field detection , **Documenso** for MIT licensing and passkey support , or **SignFuz** for native WordPress integration . For standards-based sealing, pair **Lifted Sign** for PAdES/PKCS#7 production with **Attestto Verify** or **sealed-pdf-verify** for independent verification.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Document signing platforms handle legally binding agreements and signer PII; ensure compliance with ESIGN, UETA, eIDAS, and applicable data protection regulations. **Audit trails and certificate integrity are legally critical**—do not deploy open-source signing without validating the tamper-evidence of completed PDFs.
- **Open-source e-signature licensing is almost exclusively copyleft.** Every actively maintained project is AGPL-3.0, GPL, or similar—**only Documenso offers a path to permissive use** through its Community Edition . If your organization restricts copyleft software, review licenses carefully. **Self-hosting an e-signature API has hidden costs**: compute (~$20–60/month), **5–10 hours/month of engineering time** for operations, and certificate infrastructure for PAdES/CAdES sealing . **Qualified electronic signatures (QES) under eIDAS require a Qualified Trust Service Provider (QTSP)**—no open-source project issues qualified certificates; you must integrate with a QTSP regardless of platform . **Validate whether you need managed convenience (DocuSign, Dropbox Sign) or self-hosted control (DocuSeal, Documenso)** before committing.

---

**Made for legal ops teams, developers, and organizations building document execution infrastructure.**  
Let's make document verification and digital attestation more open, verifiable, and accessible.
