# Scrive (scrive)

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

Scrive is a Nordic e-signature and digital identity (e-ID) platform for agreeing, signing, and verifying documents online. The Scrive Document API (eSign Online, Version 2) is a RESTful, JSON-over-HTTPS interface that creates, prepares, sends, and manages the full lifecycle of documents for electronic signing, with identity verification through Nordic and European e-ID methods including Swedish, Norwegian, and Finnish BankID, Danish MitID, Freja, and Smart-ID. Authentication uses OAuth2, OAuth 1.0, or personal access credentials; document status changes are delivered to consumers via HTTP callback (webhook) URLs. A separate Scrive eID Hub provides standalone identity authentication and signing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scrive/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scrive/refs/heads/main/apis.yml)

## Tags

- E-Signature
- Electronic Signing
- Digital Identity
- e-ID
- BankID
- MitID
- Nordic
- Document Workflow

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Scrive Documents API

Create, prepare, update, and drive the full lifecycle of documents for electronic signing - new documents, set/append files, start the signing process, retrieve, list, remind, prolong, cancel, trash, and delete. The core of Scrive eSign Online (Document API Version 2).

- **Human URL:** [https://apidocs.scrive.com/](https://apidocs.scrive.com/)
- **Base URL:** `https://scrive.com/api/v2`

#### Tags

- Documents
- eSign
- Lifecycle

#### Properties

- [Documentation](https://apidocs.scrive.com/)
- [API Reference](https://apidocs.scrive.com/)
- [OpenAPI](openapi/scrive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrive Templates API

Reuse saved documents as templates - create new documents from a template, clone existing documents, and drive repeatable signing workflows and bulk sends from a single reusable definition.

- **Human URL:** [https://apidocs.scrive.com/](https://apidocs.scrive.com/)
- **Base URL:** `https://scrive.com/api/v2`

#### Tags

- Templates
- Reuse
- Documents

#### Properties

- [Documentation](https://apidocs.scrive.com/)
- [OpenAPI](openapi/scrive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrive Signing API

Manage the signatory-facing signing process - retrieve signing data and sign-link QR codes, remind and resend to signatories, forward and restart documents, change signatory contact details, and run bulk sends.

- **Human URL:** [https://apidocs.scrive.com/](https://apidocs.scrive.com/)
- **Base URL:** `https://scrive.com/api/v2`

#### Tags

- Signing
- Signatories
- QR Code

#### Properties

- [Documentation](https://apidocs.scrive.com/)
- [OpenAPI](openapi/scrive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrive e-ID Authentication API

Configure electronic identity verification for signatories - set the authentication method required to view, to sign, and to view archived documents (Swedish/Norwegian/Finnish BankID, Danish MitID, Freja, Smart-ID, SMS PIN, Onfido, and more). A standalone Scrive eID Hub also provides direct e-ID authentication.

- **Human URL:** [https://eid.scrive.com/documentation/api/v1/](https://eid.scrive.com/documentation/api/v1/)
- **Base URL:** `https://scrive.com/api/v2`

#### Tags

- e-ID
- BankID
- MitID
- Authentication

#### Properties

- [Documentation](https://eid.scrive.com/documentation/api/v1/)
- [OpenAPI](openapi/scrive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrive Attachments API

Manage author and signatory attachments and document files - list, create, download, share, and delete reusable attachments; set author attachments on a document; request and attach files from signatories; and download main files and ZIP archives.

- **Human URL:** [https://apidocs.scrive.com/](https://apidocs.scrive.com/)
- **Base URL:** `https://scrive.com/api/v2`

#### Tags

- Attachments
- Files
- Documents

#### Properties

- [Documentation](https://apidocs.scrive.com/)
- [OpenAPI](openapi/scrive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrive Callbacks API

Receive document status changes as HTTP POST callbacks (webhooks) to a configured `api_callback_url` when a document becomes pending, closed, canceled, timedout, or rejected, with automatic retries; trigger a manual callback on demand.

- **Human URL:** [https://apidocs.scrive.com/](https://apidocs.scrive.com/)
- **Base URL:** `https://scrive.com/api/v2`

#### Tags

- Callbacks
- Webhooks
- Notifications

#### Properties

- [Documentation](https://apidocs.scrive.com/)
- [OpenAPI](openapi/scrive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrive Access Control API

Administer organizational access - manage user groups and their settings and contact details, grant and revoke access roles for users, and organize documents into folders.

- **Human URL:** [https://apidocs.scrive.com/](https://apidocs.scrive.com/)
- **Base URL:** `https://scrive.com/api/v2`

#### Tags

- Access Control
- User Groups
- Folders

#### Properties

- [Documentation](https://apidocs.scrive.com/)
- [OpenAPI](openapi/scrive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scrive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/scrive)
- [LinkedIn](https://www.linkedin.com/company/scrive)
- [Website](https://www.scrive.com)
- [Documentation](https://apidocs.scrive.com/)
- [Plans](plans/scrive-plans-pricing.yml)
- [Rate Limits](rate-limits/scrive-rate-limits.yml)
- [Fin Ops](finops/scrive-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
