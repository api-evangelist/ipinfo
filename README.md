# IPinfo (ipinfo)

IPinfo is an IP address data and intelligence platform that provides geolocation (country, region, city, coordinates, postal, timezone), ASN data, company association, mobile carrier identification, hosted domains lookup, privacy detection (VPN, proxy, Tor, relay, hosting), residential proxy detection, WHOIS, IP ranges, abuse contacts, and an IP-to-Places product. Data is available via a unified REST API (Lite, Core, Plus, Max, Enterprise tiers), a Batch Enrichment endpoint, and downloadable databases (CSV, MMDB, JSON, Parquet).

**URL:** [Visit APIs.json URL](https://ipinfo.io/developers)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- IP Intelligence, IP Geolocation, ASN, Privacy Detection, VPN Detection, Threat Intelligence, Network Data, Mobile Carrier, WHOIS, Public APIs, Development

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## Type
- **x-type:** company
- **x-tier:** 3 (bulk-registered from public-apis)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Development

## APIs

### IPinfo Core API

Unified IP intelligence REST API exposing the Lite, Core, Plus, Max, Enterprise, Places, ASN, Company, Carrier, Hosted Domains, Privacy Detection (Standard and Extended), Residential Proxy Detection, WHOIS, IP Ranges, Abuse Contact, Batch Enrichment, and Tools (Summarize IPs, Map IPs) endpoints. All endpoints share the same `api.ipinfo.io` base URL and the same token-based authentication.

**Human URL:** [https://ipinfo.io/developers](https://ipinfo.io/developers)
**Base URL:** `https://api.ipinfo.io`

#### Tags

- IP Intelligence, REST API, Geolocation, ASN, Privacy Detection

#### Properties

- **Documentation:** [https://ipinfo.io/developers](https://ipinfo.io/developers)
- **APIReference:** [https://ipinfo.io/developers](https://ipinfo.io/developers)
- **OpenAPI:** [openapi/ipinfo-openapi.yml](openapi/ipinfo-openapi.yml)
- **GettingStarted:** [https://ipinfo.io/developers/getting-started](https://ipinfo.io/developers/getting-started)
- **Authentication:** [https://ipinfo.io/developers#authentication](https://ipinfo.io/developers#authentication)
- **Quickstart:** [https://ipinfo.io/developers/lite-api](https://ipinfo.io/developers/lite-api)
- **JSONSchema:** [json-schema/](json-schema/)
- **JSONStructure:** [json-structure/](json-structure/)
- **Example:** [examples/](examples/)
- **RateLimits:** [rate-limits/ipinfo-rate-limits.yml](rate-limits/ipinfo-rate-limits.yml)
- **Plans:** [plans/ipinfo-plans-pricing.yml](plans/ipinfo-plans-pricing.yml)

#### SDKs

- [Python SDK](https://github.com/ipinfo/python)
- [Node.js SDK](https://github.com/ipinfo/node)
- [Java SDK](https://github.com/ipinfo/java)
- [Go SDK](https://github.com/ipinfo/go)
- [Ruby SDK](https://github.com/ipinfo/ruby)
- [PHP SDK](https://github.com/ipinfo/php)
- [C# SDK](https://github.com/ipinfo/csharp)
- [Rust SDK](https://github.com/ipinfo/rust)
- [Perl SDK](https://github.com/ipinfo/perl)
- [Swift SDK](https://github.com/ipinfo/swift)
- [Erlang SDK](https://github.com/ipinfo/erlang)
- [Django SDK](https://github.com/ipinfo/django)
- [Laravel SDK](https://github.com/ipinfo/laravel)
- [Spring SDK](https://github.com/ipinfo/spring)
- [Rails SDK](https://github.com/ipinfo/rails)
- [Node Express SDK](https://github.com/ipinfo/node-express)

## Common Properties

- **Website:** [https://ipinfo.io](https://ipinfo.io)
- **DeveloperPortal:** [https://ipinfo.io/developers](https://ipinfo.io/developers)
- **SignUp:** [https://ipinfo.io/signup](https://ipinfo.io/signup)
- **Login:** [https://ipinfo.io/login](https://ipinfo.io/login)
- **Pricing:** [https://ipinfo.io/pricing](https://ipinfo.io/pricing)
- **Console (Dashboard):** [https://ipinfo.io/account](https://ipinfo.io/account)
- **Blog:** [https://ipinfo.io/blog](https://ipinfo.io/blog)
- **Support:** [https://support.ipinfo.io](https://support.ipinfo.io)
- **StatusPage:** [https://status.ipinfo.io](https://status.ipinfo.io)
- **ChangeLog:** [https://ipinfo.io/changelog](https://ipinfo.io/changelog)
- **TermsOfService:** [https://ipinfo.io/terms-of-service](https://ipinfo.io/terms-of-service)
- **PrivacyPolicy:** [https://ipinfo.io/privacy-policy](https://ipinfo.io/privacy-policy)
- **Compliance:** [https://ipinfo.io/security](https://ipinfo.io/security)
- **GitHubOrganization:** [https://github.com/ipinfo](https://github.com/ipinfo)
- **CLI:** [IPinfo CLI](https://github.com/ipinfo/cli), [mmdbctl](https://github.com/ipinfo/mmdbctl)
- **Tools:** [Summarize IPs Tool](https://ipinfo.io/tools/summarize-ips), [Map IPs Tool](https://ipinfo.io/tools/map)
- **CodeExamples:** [Sample Database](https://github.com/ipinfo/sample-database), [Rails Example](https://github.com/ipinfo/rails-example), [Docker Image](https://github.com/ipinfo/docker)
- **SpectralRules:** [rules/ipinfo-spectral-rules.yml](rules/ipinfo-spectral-rules.yml)
- **Vocabulary:** [vocabulary/ipinfo-vocabulary.yml](vocabulary/ipinfo-vocabulary.yml)
- **JSON-LD:** [json-ld/ipinfo-context.jsonld](json-ld/ipinfo-context.jsonld)
- **PublicAPIsListing:** [public-apis/public-apis](https://github.com/public-apis/public-apis)

## Features

- **IP Geolocation** — City, region, country, postal code, coordinates, and timezone for any IP.
- **ASN Data** — Autonomous System Number, organization, domain, type, peers, upstreams, downstreams, and prefixes.
- **Company Identification** — Organization name, type, and domain associated with an IP block.
- **Mobile Carrier Detection** — Carrier name, Mobile Country Code (MCC), and Mobile Network Code (MNC).
- **Hosted Domains** — List of domains hosted on an IP address (up to 1,000 per request).
- **Privacy Detection** — Identifies VPN, proxy, Tor, relay, and hosting provider anonymization services.
- **Residential Proxy Detection** — Detects residential, mobile, and datacenter proxies with last-seen recency.
- **Abuse Contact** — Network administrator address, email, and phone for reporting abuse.
- **WHOIS** — WHOIS lookup by Net ID, IP, domain, ASN, organization, or point-of-contact.
- **Batch Enrichment** — Bulk lookup of up to thousands of IPs in a single request.
- **Database Downloads** — Daily-refreshed CSV, MMDB, JSON, and Parquet database files.
- **IPv4 and IPv6 Support** — Dual-stack service with explicit v4.api.ipinfo.io and v6.api.ipinfo.io endpoints.
- **Field Filtering** — Request a single field (plaintext) or filtered object (JSON) per lookup.
- **99.999% Uptime** — High-availability service with 50-200 ms typical response time.

## Use Cases

- **Fraud Prevention** — Block or flag traffic from VPNs, proxies, Tor, and known abuse sources.
- **Geo-Targeted Content** — Personalize content, pricing, and language based on visitor country and city.
- **Compliance and Geofencing** — Enforce geographic licensing or regulatory restrictions on content access.
- **Cybersecurity and Threat Intelligence** — Enrich SIEM, SOAR, and EDR events with IP context for faster triage.
- **Ad Tech and Marketing Analytics** — Attribute conversions, dedupe sessions, and segment by carrier or ASN.
- **Log Enrichment** — Add geolocation, ASN, and privacy flags to web, application, and network logs.
- **Bot Detection** — Identify datacenter and hosting-provider IPs that are likely bots.
- **Account Takeover Prevention** — Detect anomalous logins from unusual countries or proxy networks.
- **Customer Support Triage** — Surface visitor location and ISP to support agents in real time.
- **Network Engineering** — Look up ASN peering, prefixes, and abuse contacts during incident response.

## Integrations

Splunk, Elastic / Logstash, Cloudflare Workers, AWS Lambda, Snowflake, Datadog, Heroku, Docker, Homebrew.

## Solutions

- **IPinfo Lite** — Free tier (unlimited, 7 attributes)
- **IPinfo Core** — $49/mo base (16 attributes)
- **IPinfo Plus** — $74/mo base (32 attributes)
- **IPinfo Max** — $94/mo base (35 attributes)
- **IPinfo Enterprise** — Custom (40+ attributes, full WHOIS, IP ranges, SLA)
- **IPinfo Database** — Downloadable IP database (CSV, MMDB, JSON, Parquet)

## Artifacts Generated

| Artifact Type | Folder | Count |
|---|---|---|
| OpenAPI Specs | `openapi/` | 1 |
| JSON Schemas | `json-schema/` | 24 |
| JSON Structures | `json-structure/` | 24 |
| Examples | `examples/` | 24 |
| JSON-LD Contexts | `json-ld/` | 1 |
| Naftiko Capabilities | `capabilities/` | 17 |
| Spectral Rules | `rules/` | 1 |
| Vocabulary | `vocabulary/` | 1 |
| Plans | `plans/` | 1 |
| Rate Limits | `rate-limits/` | 1 |
| FinOps | `finops/` | 1 |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
