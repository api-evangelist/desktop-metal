# Desktop Metal (desktop-metal)

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

Desktop Metal designs and manufactures additive manufacturing (3D printing) hardware and software for metal and polymer parts, including binder jet and Bound Metal Deposition printers, sintering furnaces, materials, and the cloud/desktop Live Suite software (Live Platform, Live Studio, Live Build, Live Sinter, Live Monitor) that replaced the legacy Fabricate applications. As of April 2025 Desktop Metal is a subsidiary of Nano Dimension. No public or partner developer API is documented; the surfaces below are product features rather than published HTTP APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/desktop-metal/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/desktop-metal/refs/heads/main/apis.yml)

## Tags

- 3D Printing
- Additive Manufacturing
- Metal
- Hardware
- Manufacturing Software

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Printer Fleet & Live Suite

Live Platform provisions and manages Desktop Metal AM systems and users, and Live Monitor surfaces real-time fleet, printer, and furnace data (job/event status, time reporting, consumable usage, OEE) in a web browser with 30-day exportable history for trend analysis and Industry 4.0 integration. This is delivered as a product UI and data export, not as a documented public REST/HTTP API.

- **Human URL:** [https://www.desktopmetal.com/products/live-suite](https://www.desktopmetal.com/products/live-suite)

#### Tags

- Fleet Management
- Live Suite
- Live Monitor
- Product Feature

#### Properties

- [Documentation](https://www.desktopmetal.com/products/live-suite)
- [Documentation](https://www.desktopmetal.com/products/live-monitor)
- [OpenAPI](openapi/desktop-metal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/desktop-metal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/desktop-metal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fabricate Software

Build preparation and slicing software for Desktop Metal printers. The legacy Fabricate and Fabricate MFG desktop applications have been replaced and upgraded by Live Studio (cloud build preparation for Bound Metal Deposition / Studio System) and Live Build MFG/DLP (binder jet and DLP build preparation). Distributed as installable/cloud applications; no documented public API surface.

- **Human URL:** [https://www.desktopmetal.com/products/live-suite](https://www.desktopmetal.com/products/live-suite)

#### Tags

- Build Preparation
- Slicing
- Live Studio
- Live Build
- Product Feature

#### Properties

- [Documentation](https://www.desktopmetal.com/products/live-suite)
- [OpenAPI](openapi/desktop-metal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/desktop-metal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/desktop-metal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Materials

Qualified metal, polymer, composite, ceramic, sand, and wood material portfolio for Desktop Metal's binder jet, Bound Metal Deposition, and DLP/polymer systems, with associated material parameters and process profiles. Presented as a product catalog; no documented public API for material data.

- **Human URL:** [https://www.desktopmetal.com/materials](https://www.desktopmetal.com/materials)

#### Tags

- Materials
- Metal
- Polymer
- Product Feature

#### Properties

- [Documentation](https://www.desktopmetal.com/materials)
- [OpenAPI](openapi/desktop-metal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/desktop-metal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/desktop-metal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/desktop-metal)
- [Website](https://www.desktopmetal.com)
- [Documentation](https://www.desktopmetal.com/products/live-suite)
- [Plans](plans/desktop-metal-plans-pricing.yml)
- [Rate Limits](rate-limits/desktop-metal-rate-limits.yml)
- [Fin Ops](finops/desktop-metal-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
