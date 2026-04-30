# Anchor Browser

## About the Company

**Anchor Browser** is a cloud infrastructure platform for running and managing AI agent browsers. It provides secure, isolated Chromium instances in the cloud, letting AI agents interact with websites just like humans do: logging in, navigating, filling forms, and extracting data.

The company was founded in 2024 by three veterans of Unit 8200 (Israel's elite military intelligence unit), with prior experience at SentinelOne, Noname Security, and BlinkOps. They're headquartered in New York City with Israeli roots.

| Parameter | Value |
|----------|----------|
| **Founded** | 2024 |
| **Headquarters** | New York, USA |
| **Origins** | Israel (Unit 8200) |
| **CEO** | Idan Raman |
| **CTO** | Dor Dankner |
| **Co-Founder & CPO** | Guy Ben Simhon |
| **Stage** | Seed |
| **Website** | https://anchorbrowser.io |

## AI Dev 26 Participation

**Role:** Sponsor in the Startup Track / Demo Tables category.

**Speaker:** Idan Raman, Co-Founder & CEO

**Talk:** "The Identity Crisis of Browser Agents — Securing Human Identities for Agent Use"

**Time:** Day 2 (April 29, 2026), 1:00 PM — 1:20 PM, 20-minute presentation.

The talk addresses a critical market problem: AI agents operating in browsers exist in an "identity gray zone" — organizations don't manage them as human users or as full-fledged machine identities. This creates serious security risks, especially when dealing with authenticated sessions, MFA, and enterprise SSO systems.

## Product

### Anchor Browser — Cloud Browser for AI Agents

Anchor provides fully managed, "humanized" Chromium instances in the cloud. Each AI agent gets its own isolated browser environment, completely separate from human users.

### Key Capabilities

- **Browser Isolation.** Each agent runs in its own cloud Chromium instance with complete isolation
- **Identity Management (Browser Profiles).** Saves and reuses authenticated sessions: cookies, local storage, auth tokens
- **Anti-Bot Protection.** Automatic CAPTCHA solving, stealth mode (browser fingerprinting), and verified-bot authentication
- **Authentication Support.** Integrates with IdPs (Okta, Azure AD), supports MFA, SSO, multi-step verification
- **Geolocation and Proxies.** Deploy anywhere geographically, residential and mobile IPs
- **Scalability.** Enterprise plans support 500+ concurrent browsers (marketing materials mention higher scale); unlimited session duration
- **VPN Integration.** Built-in Anchor VPN eliminates IP anomalies, prevents "impossible traveler" blocks

### b0.dev — Deterministic Workflows

The b0.dev product changes how browser agents work: instead of running an AI model at every step, the system lets agents **plan a workflow once**, then execute it repeatedly with high reliability. According to Anchor's benchmarks, this makes automation up to 80x more token-efficient, 12-15x faster, and capable of 10x more actions compared to traditional approaches.

### OmniConnect — Enterprise Authentication

Integrates with 1Password, providing self-healing authentication for agents:

- Native MFA and complex verification flow support
- Zero-configuration credential onboarding through embedded UI, CLI, or live browser view
- Advanced features (RBAC, configurable data storage, unique fingerprinting) available on Enterprise plans

### Cloudflare Partnership — Verified Browser Agents

Anchor became one of the first providers to receive Cloudflare Verified Bot status. Anchor agents cryptographically sign their traffic, letting site owners verify exactly who's accessing their resources. This eliminates the traditional "cat and mouse game" between bots and anti-bot systems.

### Coinbase Partnership (x402)

Integration with Coinbase's x402 protocol for HTTP-native USDC micropayments, enabling payment-triggered sessions and allowing site owners to monetize automated access.

### Supported Integrations

- Groq (Compound research agent)
- Browser-use (open-source framework)
- Composio (MCP integration)
- LangChain, CrewAI, and other agentic frameworks

### Compliance

SOC2 Type 2, ISO27001, HIPAA, GDPR (available on Growth and Enterprise plans).

## Funding

| Round | Amount | Date | Lead Investors | Co-Investors |
|-------|-------|------|---------------|--------------|
| **Seed** | **$6M** | **October 2025** | **Led by Blumberg Capital; participant: Gradient Ventures (Google AI fund)** | **Colin Evans (Head of VC & Startup Partnerships, OpenAI), angels from ServiceNow, SentinelOne** |

- **Total Raised:** $6M
- **Valuation:** Not disclosed
- **Strategic Investor Partners:** Gradient Ventures (Google), angel from OpenAI
- **Customers at Round:** Groq, Unify, Browser-use and dozens of others

## Business Model

**Model: Freemium + Pay-as-you-go (usage-based)**

Anchor uses a two-component model: fixed monthly subscription + pay for actual consumption (browser creation, runtime, proxy traffic, AI steps).

| Tier | Price/month | Concurrent Browsers | Key Features |
|-------|----------|----------------------|---------------|
| **Free** | $0 ($5 credits) | 5 | Built-in browser agent, US region, 45-day storage |
| **Starter** | $50 | 25 | + authenticated browsers, CAPTCHA bypass, geolocation/proxies |
| **Team** | $500 | 50 | + Cloudflare Verified Browser Agents, custom proxy, 30-day retention |
| **Growth** | $2,000 | 200 | + full stealth, multi-region (US/EU/Asia/Australia), SOC2/ISO/HIPAA/GDPR, Slack support |
| **Enterprise** | Custom | 500+ | + unique fingerprinting, RBAC, on-premise deployment, custom terms |

**Infrastructure Costs (pay-per-use):**

| Resource | Cost |
|--------|-----------|
| Browser creation | $0.01 per instance |
| Browser runtime | $0.05 per hour (docs pricing; homepage calculator shows $0.09) |
| Proxy traffic (residential/mobile IP) | $8 per GB |
| AI steps | $0.01 per step |

**Target Customers:**

- SaaS companies building products with browser AI agents
- Service providers and system integrators
- Enterprise teams (finance, HR, procurement, compliance, operations)
- Industries: finance, healthcare, insurance, public sector, e-commerce

### What Customers Can Expect to Spend

| Usage Profile | Typical Monthly Cost |
|----------------------|---------------------|
| Testing / prototyping | $0 (Free, $5 credits) |
| Small project (few agents) | $50–$150 |
| Medium volume (dozens of agents, regular tasks) | $200–$1,000 |
| Production workload (hundreds of concurrent agents) | $2,000–$5,000 |
| Enterprise (thousands of agents, on-premise) | $5,000+ (custom) |

**Important:** The main hidden costs are proxy traffic ($8/GB) and AI steps ($0.01/step). With heavy residential IP proxy usage, traffic costs can significantly exceed the base subscription. It's recommended to start with the Free plan to estimate actual consumption.

## Analysis

### Market Position

Anchor Browser operates in the **cloud browsers / remote browsers for AI agents** segment — a fast-growing market at the intersection of browser automation, agentic AI, and cybersecurity.

**Market in Numbers:**
- The agentic browser market grew from $4.5B (2024) to a projected $76.8B by 2034
- CAGR for AI browsers — 32.8%
- 62% of enterprises are already experimenting with AI agents

### Competitors

| Company | Description |
|----------|---------------|
| **Browserless** | Premium solution, starter plan from $140/month, 1,000 free units |
| **Browserbase** | Cloud browsers for AI, also a Cloudflare Verified Bots partner |
| **Bright Data** | 95% feature coverage, strong proxy networks |
| **BrowserAI** | Highest scalability rating (86.4%) |
| **Steel.dev** | Competitor in browser automation segment |

Anchor ranks **16th among 653 active competitors** (per Tracxn data as of April 2026), of which 76 have received funding. Despite being early-stage, the company stands out with:

- **Cloudflare Verified Bot partnership** (cryptographic browser-agent traffic verification) — key strategic advantage
- **Focus on identity and security** — founders' background from Unit 8200 and cybersecurity companies
- **b0.dev approach** — plan once, execute many times (deterministic workflows)
- **Enterprise features** (OmniConnect + 1Password, SOC2, HIPAA) — targeting regulated industries

### Risks

- Early stage (seed, $6M), limited resources for scaling
- High competition (480 companies in the space)
- Dependent on agentic AI market dynamics: 79% of organizations have adopted agents, but only 11% in production (deployment gap)
- Regulatory risks around AI agent security and compliance in regulated industries

## Links

- Website: https://anchorbrowser.io
- Documentation: https://docs.anchorbrowser.io
- About: https://anchorbrowser.io/about
- Pricing: https://docs.anchorbrowser.io/pricing
- Blog: https://anchorbrowser.io/blog
- b0.dev: https://anchorbrowser.io/blog/anchor-launches-b0-dev---new-agentic-browser-paradigm
- Cloudflare partnership: https://anchorbrowser.io/blog/anchor-cloudflare-verified-browser-agents
- OmniConnect: https://www.bignewsnetwork.com/news/278969607/anchor-browser-launches-omniconnect-eliminating-the-1-cause-of-enterprise-computer-use-failure
- Seed round (Yahoo Finance): https://finance.yahoo.com/news/anchor-browser-raises-6m-seed-110000117.html
- Blumberg Capital: https://blumbergcapital.com/news-insights/anchor-browser-ai-web-infrastructure/
- Gradient Ventures: https://www.gradient.com/blog/posts/anchor-browser/
- Calcalist (Unit 8200): https://www.calcalistech.com/ctechnews/article/b1k00f48all
- Groq partnership: https://www.prnewswire.com/news-releases/anchor-browser-powers-groqs-agent-platform-enabling-reliable-ai-access-to-the-web-302658445.html
- Tracxn profile: https://tracxn.com/d/companies/anchor-browser/__SkpC2BzFoxP0dg0HxX_jrIm9SHJc4nMv8wkfm3jYI_4
- LinkedIn: https://www.linkedin.com/company/anchorbrowser
