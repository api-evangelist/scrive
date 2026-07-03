# Scrive (scrive)

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
