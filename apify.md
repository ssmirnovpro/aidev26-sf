# Apify

## Company Overview

**Apify** is a cloud platform for web scraping, browser automation, AI agents, and AI data preparation. The platform offers 26,000+ ready-to-use tools, code templates, and custom solutions.

## Role at AI Dev 26

**Role:** Exhibitor (booth), Speaker, Sponsor

**Speaker:** Ondra Urban
**Talk:** "Agents with Wallets? Putting 25,000 Tools on x402"
**Time:** Day 2 (April 29, 2026), 11:00 AM — 11:20 AM

At the conference booth, Apify demonstrated their ecosystem with an interactive experience focused on developer onboarding.

## Product

**Apify Platform** — a full-stack platform for web data extraction and automation.

### Key Components (from materials and analysis)

- **Apify Actors** — automations for data extraction and processing that run in the cloud or locally. Scrape websites, process data, integrate APIs — all without managing infrastructure
- **Apify Store** — a marketplace with 26,000+ ready-made scrapers, AI agents, and automation tools
- **AI Web Scraper** — an LLM-powered tool that extracts structured data using natural language prompts, no coding required

### AI Framework Integrations

- Model Context Protocol (MCP) — native support that lets AI agents autonomously discover and use the right Actors
- LangChain, Zapier, Make, n8n
- Python/JavaScript SDKs, Crawlee, Scrapy, Playwright, Puppeteer, Selenium

### Platform Specs

- 99.95% uptime
- SOC2, GDPR, CCPA compliance
- Python and JavaScript support
- Integration with Scrapy and Crawlee

## Funding

| Round | Amount | Date | Lead Investors |
|-------|--------|------|----------------|
| Early rounds | — | — | Y Combinator |
| Venture round | €2.8M (~$2.97M) | April 2024 | Led by J&T Ventures; participant: Reflex Capital |

- **Total raised**: Approximately $3.0M-$3.5M reported (varies by source: CB Insights $3.21M, other estimates up to $3.49M)
- **Investors**: J&T Ventures, Reflex Capital, Y Combinator

## Business Model

**Model: Freemium + Pay-as-you-go + Marketplace**

| Plan | Price/mo | What's Included |
|-------|----------|----------|
| **Free** | $0 | $5 in credits |
| **Starter** | $29 | Basic features |
| **Scale** | $199 | Advanced features |
| **Business** | $999 | Full functionality |
| **Enterprise** | Custom | Custom solutions |

**Pricing Unit:** Compute Unit (CU) = 1 GB RAM × 1 hour
- Free/Starter: $0.20/CU
- Scale: $0.16/CU
- Business: $0.13/CU
- Monthly credits don't roll over to the next period

**Marketplace Model:** Developers publish their scrapers to the Apify Store, set their own pricing, and earn money when other users run their tools. Many Actors add per-result or per-event fees on top of CU charges.

**Revenue Streams:**
- Platform subscriptions
- Compute resource consumption (CU)
- Marketplace commission
- Enterprise contracts

### What Customers Should Expect to Pay

| Use Case | Typical Monthly Cost |
|----------------------|---------------------|
| Hobby / testing | $0–$29 |
| Small project (scraping) | $50–$200 |
| Medium volume (regular data collection) | $200–$1,000 |
| Heavy usage (AI agents + data) | $1,000–$3,000 |
| Enterprise | $3,000+ (with 15–30% negotiated discount) |

**Important:** Costs beyond the base subscription include concurrent runs ($5/run), Actor RAM ($1/GB), dataset storage, and data transfer. These can significantly increase your total bill. The billing is complex, making it hard to predict exact costs upfront.

## Analysis

Apify positions itself as a data infrastructure provider for AI agents. As agentic AI grows and agents need to connect to real-world internet data, platforms like Apify are becoming a critical layer in the AI stack. Their MCP Server is dropping SSE transport in favor of Streamable HTTP (April 1, 2026), showing they're keeping pace with evolving standards.

## Links

- Website: https://apify.com
- Actors: https://apify.com/actors
- AI Agents: https://apify.com/ai-agents
- GitHub MCP Server: https://github.com/apify/apify-mcp-server
