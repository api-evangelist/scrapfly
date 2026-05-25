# Scrapfly

Scrapfly is a web scraping API platform that enables effortless collection of web data with battle-tested APIs that scale. It provides capabilities for scraping web pages, capturing screenshots, and extracting structured data with AI assistance to handle anti-bot measures and JavaScript rendering. One API key unlocks five APIs: Web Scraping (anti-bot unblocker), Cloud Browser (CDP), Screenshot, Extraction, and Crawler. Global proxy mesh across 190+ countries.

**Human URL:** https://scrapfly.io/
**Developer Documentation:** https://scrapfly.io/docs
**APIs.yml:** https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/apis.yml

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

## APIs

| API | Description |
|-----|-------------|
| [Scrape API](https://scrapfly.io/docs/scrape-api) | Core web scraping with anti-bot bypass, proxy rotation, and JS rendering |
| [Screenshot API](https://scrapfly.io/docs/screenshot-api/getting-started) | Full-page and element screenshot capture |
| [Extraction API](https://scrapfly.io/docs/scrape-api/extraction) | AI-powered structured data extraction |
| [Crawler API](https://scrapfly.io/docs) | Website crawling with WARC output (Early Access) |
| [Cloud Browser API](https://scrapfly.io/docs) | Playwright/Puppeteer/Selenium cloud browser (Beta) |

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [openapi/scrapfly-scrape-openapi.yml](openapi/scrapfly-scrape-openapi.yml) | Scrapfly Scrape and Screenshot API |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/scrapfly-rules.yml](rules/scrapfly-rules.yml) | Scrapfly API conventions and linting ruleset |

### Capabilities

| File | Description |
|------|-------------|
| [capabilities/scrape-scraping.yaml](capabilities/scrape-scraping.yaml) | Naftiko capability for Scrapfly scrape operations (REST + MCP exposers) |
| [capabilities/scrape-screenshots.yaml](capabilities/scrape-screenshots.yaml) | Naftiko capability for Scrapfly screenshot operations (REST + MCP exposers) |

### Plans, Rate Limits & FinOps

| File | Description |
|------|-------------|
| [plans/scrapfly-plans-pricing.yml](plans/scrapfly-plans-pricing.yml) | API Commons Plans 0.1 — Scrapfly tiers and pricing |
| [rate-limits/scrapfly-rate-limits.yml](rate-limits/scrapfly-rate-limits.yml) | API Commons Rate Limits 0.1 — request-rate, concurrency, quotas |
| [finops/scrapfly-finops.yml](finops/scrapfly-finops.yml) | FinOps Framework / FOCUS billing surface |

### JSON Schema

| File | Description |
|------|-------------|
| [json-schema/scrapfly-scraperequest-schema.json](json-schema/scrapfly-scraperequest-schema.json) | Schema for scrape API request |
| [json-schema/scrapfly-scraperesponse-schema.json](json-schema/scrapfly-scraperesponse-schema.json) | Schema for scrape API response |
| [json-schema/scrapfly-scrape-response-schema.json](json-schema/scrapfly-scrape-response-schema.json) | Legacy schema for scrape API response |

### JSON Structure

| File | Description |
|------|-------------|
| [json-structure/scrapfly-scrape-request-structure.json](json-structure/scrapfly-scrape-request-structure.json) | Scrape request parameter structure documentation |
| [json-structure/scrapfly-structure.json](json-structure/scrapfly-structure.json) | Overall Scrapfly API structure |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/scrapfly-context.jsonld](json-ld/scrapfly-context.jsonld) | JSON-LD context for Scrapfly data vocabulary |

### Examples

| File | Description |
|------|-------------|
| [examples/scrapfly-scrape-url-example.json](examples/scrapfly-scrape-url-example.json) | Scrape URL with AI extraction example |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/scrapfly-vocabulary.yml](vocabulary/scrapfly-vocabulary.yml) | Web scraping domain vocabulary and taxonomy |

## Links

- **GitHub Org:** https://github.com/scrapfly
- **OpenAPI Docs:** https://scrapfly.io/docs/openapi
- **Python SDK:** https://scrapfly.io/docs/sdk/python

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
