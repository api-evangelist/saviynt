# Saviynt (saviynt)

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

Saviynt is an identity governance and administration (IGA) platform providing REST APIs for managing user identities, access requests, SOD violations, certifications, and privileged access controls across enterprise environments. The Saviynt Enterprise Identity Cloud API enables CRUD operations on user, account, and entitlement records; access request and approval workflows; rule engineering; segregation of duties policy management; and identity analytics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/saviynt/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/saviynt/refs/heads/main/apis.yml)

## Tags

- Identity Governance
- Identity Administration
- Access Management
- Privileged Access Management
- Segregation of Duties
- IGA
- Security

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Saviynt Enterprise Identity Cloud API

REST API for the Saviynt Enterprise Identity Cloud (EIC) platform, providing endpoints for identity administration, access requests, SOD policy management, identity analytics, rule engineering, delegated administration, and common IGA utilities. Authentication uses OAuth 2.0 bearer tokens (JWT) obtained via the login endpoint.

- **Human URL:** [https://developers.saviynt.com/apis/rest/](https://developers.saviynt.com/apis/rest/)
- **Base URL:** `https://{tenant}.saviyntcloud.com/ECM/api`

#### Tags

- Identity Governance
- Access Requests
- User Management
- Entitlements
- SOD
- Certifications
- Privileged Access

#### Properties

- [Documentation](https://developers.saviynt.com/apis/rest/)
- [OpenAPI](https://github.com/vivek9237/saviynt-api-reference/blob/main/docs/saviynt-eic-api_openapi3.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developers.saviynt.com/apis/rest/getting-started/)
- [Authentication](https://developers.saviynt.com/apis/rest/reference/5.0/auth/)
- [Best Practices](https://developers.saviynt.com/apis/rest/best-practices/)
- [API Reference](https://developers.saviynt.com/apis/rest/reference/5.0/saviynt-enterprise-identity-cloud-api-reference/)
- [Endpoints](https://developers.saviynt.com/apis/rest/reference/5.0/endpoints/)
- [OpenAPI](openapi/saviynt-eic-api-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/FetchControlListRequest.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchControlListResponse.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchControlListControl.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchControlDetailsRequest.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/RunAnalyticsControlsRequest.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchRuntimeControlsDataRequest.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchRuntimeControlsDataV2Request.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchControlAttributesRequest.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchControlListESRequest.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/FetchControlDetailsESRequest.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/saviynt-vocabulary.json)
- [J S O N L D Context](json-ld/saviynt-context.jsonld)

## Common Properties

- [Website](https://saviynt.com)
- [Documentation](https://docs.saviyntcloud.com/bundle/API-Reference-Guide/page/Content/API-References.htm)
- [Git Hub Org](https://github.com/saviynt)
- [LinkedIn](https://www.linkedin.com/company/saviynt)
- [Blog](https://saviynt.com/blog)
- [Pricing](https://saviynt.com/contact-us/)
- [Status Page](https://status.saviynt.com/)
- [X (Twitter)](https://x.com/saviynt)
- [Plans](plans/saviynt-plans-pricing.yml)
- [Rate Limits](rate-limits/saviynt-rate-limits.yml)
- [Fin Ops](finops/saviynt-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
