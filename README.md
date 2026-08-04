# Scrapfly (scrapfly)

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

Scrapfly is a web scraping API platform that enables effortless collection of web data with battle-tested APIs that scale. It provides capabilities for scraping web pages, capturing screenshots, and extracting structured data with AI assistance to handle anti-bot measures and JavaScript rendering. One API key unlocks five APIs: Web Scraping (anti-bot unblocker), Cloud Browser (CDP), Screenshot, Extraction, and Crawler. Scrapfly operates globally with proxies across 190+ countries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Data Extraction
- Screenshots
- Web Scraping
- Proxies
- Browser Automation

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### Scrapfly Scrape API

The core web scraping API that fetches any URL with anti-bot bypass, proxy rotation, and JavaScript rendering. Supports GET, POST, PUT, PATCH, HEAD, and OPTIONS methods. Returns clean HTML, markdown, JSON, or raw content. Features include session management, caching, custom headers, DNS customization, SSL info retrieval, webhooks, and structured data extraction with LLM assistance.

- **Human URL:** [https://scrapfly.io/docs/scrape-api/getting-started](https://scrapfly.io/docs/scrape-api/getting-started)

#### Tags

- Web Scraping
- Anti-Bot
- Proxies
- JavaScript Rendering

#### Properties

- [Documentation](https://scrapfly.io/docs/scrape-api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/openapi/scrapfly-scrape-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/rules/scrapfly-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/json-schema/scrapfly-scrape-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/json-ld/scrapfly-context.jsonld)
- [Postman Collection](collections/scrapfly-scrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapfly-scrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrapfly Screenshot API

Capture screenshots of web pages with full-page or element-specific capture using CSS selectors. Supports JavaScript rendering, viewport configuration, and screenshot of dynamic content. The base URL for screenshots is https://api.scrapfly.io/screenshot.

- **Human URL:** [https://scrapfly.io/docs/screenshot-api/getting-started](https://scrapfly.io/docs/screenshot-api/getting-started)

#### Tags

- Screenshots
- Web Scraping
- Browser Automation

#### Properties

- [Documentation](https://scrapfly.io/docs/screenshot-api/getting-started)
- [Postman Collection](collections/scrapfly-scrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapfly-scrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrapfly Extraction API

AI-powered structured data extraction from HTML content. Supports template-based extraction, LLM prompt-driven extraction, and auto-extraction using predefined models for common content types.

- **Human URL:** [https://scrapfly.io/docs/scrape-api/extraction](https://scrapfly.io/docs/scrape-api/extraction)

#### Tags

- Data Extraction
- AI
- Structured Data

#### Properties

- [Documentation](https://scrapfly.io/docs/scrape-api/extraction)
- [Postman Collection](collections/scrapfly-scrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapfly-scrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrapfly Crawler API

Web crawling API (currently in early access) that enables crawling entire websites with advanced configuration for depth control and content filtering. Outputs in WARC format for comprehensive web archive support.

- **Human URL:** [https://scrapfly.io/docs](https://scrapfly.io/docs)

#### Tags

- Web Crawling
- Data Collection
- WARC

#### Properties

- [Documentation](https://scrapfly.io/docs)
- [Postman Collection](collections/scrapfly-scrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapfly-scrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrapfly Cloud Browser API

Headless browser automation API (currently in beta) compatible with Playwright, Puppeteer, and Selenium frameworks. Enables complex browser interactions, JavaScript execution, and file download capture.

- **Human URL:** [https://scrapfly.io/docs](https://scrapfly.io/docs)

#### Tags

- Browser Automation
- Playwright
- Puppeteer
- Selenium

#### Properties

- [Documentation](https://scrapfly.io/docs)
- [Postman Collection](collections/scrapfly-scrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapfly-scrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scrapfly SDKs

Official SDKs for Python, TypeScript, Go, Rust, and Scrapy with full feature coverage across every language including scrape, screenshot, extract, and crawl capabilities.

- **Human URL:** [https://scrapfly.io/docs/sdk](https://scrapfly.io/docs/sdk)

#### Tags

- SDK
- Python
- TypeScript
- Go
- Rust

#### Properties

- [Documentation](https://scrapfly.io/docs/sdk)
- [Python S D K](https://scrapfly.io/docs/sdk/python)
- [Git Hub Org](https://github.com/scrapfly)
- [Postman Collection](collections/scrapfly-scrape.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scrapfly-scrape.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/scrapfly)
- [Integrations](https://scrapfly.io/integration)
- [L L Ms Txt](https://scrapfly.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
