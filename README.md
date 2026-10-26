# IPinfo (ipinfo)

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

IPinfo is an IP address data and intelligence platform that provides geolocation (country, region, city, coordinates, postal, timezone), ASN data, company association, mobile carrier identification, hosted domains lookup, privacy detection (VPN, proxy, Tor, relay, hosting), residential proxy detection, WHOIS, IP ranges, abuse contacts, and an IP-to-Places product. Data is available via a unified REST API (Lite, Core, Plus, Max, Enterprise tiers), a Batch Enrichment endpoint, and downloadable databases (CSV, MMDB, JSON, Parquet). Authentication uses access tokens via Basic Auth, Bearer Token, or query parameter; dual-stack IPv4/IPv6 endpoints are available.

**APIs.json:** [https://ipinfo.io/developers](https://ipinfo.io/developers)

## Tags

- IP Intelligence
- IP Geolocation
- ASN
- Privacy Detection
- VPN Detection
- Threat Intelligence
- Network Data
- Mobile Carrier
- WHOIS
- Public APIs
- Development

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### IPinfo Core API

Unified IP intelligence REST API exposing the Lite, Core, Plus, Max, Enterprise, Places, ASN, Company, Carrier, Hosted Domains, Privacy Detection (Standard and Extended), Residential Proxy Detection, WHOIS, IP Ranges, Abuse Contact, Batch Enrichment, and Tools (Summarize IPs, Map IPs) endpoints. All endpoints share the same `api.ipinfo.io` base URL and the same token-based authentication.

- **Human URL:** [https://ipinfo.io/developers](https://ipinfo.io/developers)
- **Base URL:** `https://api.ipinfo.io`

#### Tags

- IP Intelligence
- REST API
- Geolocation
- ASN
- Privacy Detection

#### Properties

- [Documentation](https://ipinfo.io/developers)
- [API Reference](https://ipinfo.io/developers)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/openapi/ipinfo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://ipinfo.io/developers/getting-started)
- [Authentication](https://ipinfo.io/developers#authentication)
- [Quickstart](https://ipinfo.io/developers/lite-api)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/json-structure/)
- [Example](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/examples/)
- [SDK](https://github.com/ipinfo/python)
- [SDK](https://github.com/ipinfo/node)
- [SDK](https://github.com/ipinfo/java)
- [SDK](https://github.com/ipinfo/go)
- [SDK](https://github.com/ipinfo/ruby)
- [SDK](https://github.com/ipinfo/php)
- [SDK](https://github.com/ipinfo/csharp)
- [SDK](https://github.com/ipinfo/rust)
- [SDK](https://github.com/ipinfo/perl)
- [SDK](https://github.com/ipinfo/swift)
- [SDK](https://github.com/ipinfo/erlang)
- [SDK](https://github.com/ipinfo/django)
- [SDK](https://github.com/ipinfo/laravel)
- [SDK](https://github.com/ipinfo/spring)
- [SDK](https://github.com/ipinfo/rails)
- [SDK](https://github.com/ipinfo/node-express)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/rate-limits/ipinfo-rate-limits.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/plans/ipinfo-plans-pricing.yml)
- [Postman Collection](collections/ipinfo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipinfo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://ipinfo.io)
- [Developer Portal](https://ipinfo.io/developers)
- [Sign Up](https://ipinfo.io/signup)
- [Login](https://ipinfo.io/login)
- [Pricing](https://ipinfo.io/pricing)
- [Console](https://ipinfo.io/account)
- [Blog](https://ipinfo.io/blog)
- [Support](https://support.ipinfo.io)
- [Status Page](https://status.ipinfo.io)
- [Changelog](https://ipinfo.io/changelog)
- [Terms of Service](https://ipinfo.io/terms-of-service)
- [Privacy Policy](https://ipinfo.io/privacy-policy)
- [Compliance](https://ipinfo.io/security)
- [GitHub Organization](https://github.com/ipinfo)
- [C L I](https://github.com/ipinfo/cli)
- [C L I](https://github.com/ipinfo/mmdbctl)
- [Tools](https://ipinfo.io/tools/summarize-ips)
- [Tools](https://ipinfo.io/tools/map)
- [Code Examples](https://github.com/ipinfo/sample-database)
- [Code Examples](https://github.com/ipinfo/rails-example)
- [Code Examples](https://github.com/ipinfo/docker)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/rules/ipinfo-spectral-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/vocabulary/ipinfo-vocabulary.yml)
- [J S O N- L D](https://raw.githubusercontent.com/api-evangelist/ipinfo/main/json-ld/ipinfo-context.jsonld)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
