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
| [capabilities/web-data-collection.yaml](capabilities/web-data-collection.yaml) | Web data collection workflow (scraping + screenshots + extraction) |
| [capabilities/shared/scrapfly-scrape.yaml](capabilities/shared/scrapfly-scrape.yaml) | Shared Scrapfly scrape and screenshot API definition |

### JSON Schema

| File | Description |
|------|-------------|
| [json-schema/scrapfly-scrape-response-schema.json](json-schema/scrapfly-scrape-response-schema.json) | Schema for scrape API response |

### JSON Structure

| File | Description |
|------|-------------|
| [json-structure/scrapfly-scrape-request-structure.json](json-structure/scrapfly-scrape-request-structure.json) | Scrape request parameter structure documentation |

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
