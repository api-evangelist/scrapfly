# Scrapfly (scrapfly)

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
