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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[DocuSign](https://www.docusign.com/)**  
  **The industry standard for e-signature.** Envelopes, templates, and certificate of completion on every agreement. **Per-user seat pricing with envelope caps** on lower tiers; overages billed per envelope ($3.60–$7.80) or pre-purchased ($3.00–$6.50). SMS delivery and ID verification are paid add-ons. Best for enterprises needing the broadest integration ecosystem and legal recognition.

- **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)**  
  **E-signature bundled into Acrobat plans.** **Per-license billing** with seat subscriptions. **Free Developer Edition with full REST API access and sandbox** for testing. Deep integration if your workflows are PDF-native. Best for organizations already standardized on Adobe's PDF ecosystem.

- **[Dropbox Sign](https://sign.dropbox.com/)**  
  **E-signature with unlimited signature requests on paid plans**—no envelope caps. **Free tier: 3 signature requests per month**. Official SDKs for Python, Node, Java, C#, PHP, Ruby, Go. Best for teams wanting predictable unlimited sending without per-envelope anxiety.

- **[OneSpan Sign](https://www.onespan.com/)**  
  **Enterprise e-signature focused on complex authentication and audit requirements.** Certificate-based signing, policy controls, and audit-oriented message handling. SaaS and on-premises deployment options available. Best for regulated industries needing deep audit and authentication controls.

- **[PandaDoc](https://www.pandadoc.com/)**  
  **Document workflow platform combining e-signature, proposals, and CPQ.** Free eSign plan: **5 documents/month, 2 recipients/document**. Paid plans add unlimited documents and templates. Best for sales teams wanting signing integrated with proposal creation.

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
