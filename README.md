# Steelcase (steelcase)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Steelcase is a global leader in the office furniture and workplace design industry, providing furniture, technology, and research-based insights to help organizations create effective work environments. Steelcase offers the RoomWizard API for integrating room scheduling and conference room reservation systems with enterprise calendaring platforms. The API enables developers to manage room bookings, retrieve availability, and synchronize reservations with Microsoft Exchange, Office 365, and Google Calendar.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/steelcase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Office Furniture
- Workplace
- Room Scheduling
- Facilities Management
- IoT
- Smart Office

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### Steelcase RoomWizard API

The Steelcase RoomWizard API provides programmatic access to conference room scheduling and reservation management. Using HTTP GET and POST requests, developers can retrieve room bookings, create reservations, check room availability, and synchronize with enterprise calendaring systems including Microsoft Exchange, Office 365, and Google Calendar. The API returns XML-structured responses and supports webhook-style synchronization for keeping room status current.

- **Human URL:** [https://www.steelcase.com/products/scheduling-systems/roomwizard/](https://www.steelcase.com/products/scheduling-systems/roomwizard/)
- **Base URL:** `https://roomwizard.local/api`

#### Tags

- Room Scheduling
- Conference Rooms
- Calendaring
- Facilities Management
- Workplace

#### Properties

- [Documentation](https://www.steelcase.com/techsupport/types/spec-guide/)
- [OpenAPI](openapi/steelcase-roomwizard-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/steelcase-roomwizard-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/steelcase-roomwizard-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/steelcase)
- [Website](https://www.steelcase.com)
- [Tech Support](https://www.steelcase.com/techsupport/)
- [Downloads](https://www.steelcase.com/techsupport/downloads/)
- [JSON Schema](json-schema/steelcase-booking-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/steelcase-room-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/steelcase-booking-structure.json)
- [JSON Structure](json-structure/steelcase-room-structure.json)
- [JSON-LD](json-ld/steelcase-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/steelcase-rules.yml)
- [Vocabulary](vocabulary/steelcase-vocabulary.yml)
- [Integrations](https://www.steelcase.com/marketplace/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
