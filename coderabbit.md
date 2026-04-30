# CodeRabbit

## About the Company

**CodeRabbit** is an AI-powered code review platform that automatically analyzes pull requests and merge requests the moment they're opened. The product delivers line-by-line feedback directly inside GitHub, GitLab, Azure DevOps, and Bitbucket—supporting all four major Git platforms.

The company was founded in 2023 by co-founders **Harjot Gill** (CEO, previously co-founder of Netsil, acquired by Nutanix, and FluxNinja) and **Gur Singh** (co-founder, formerly led engineering and product teams at Alegeus Technologies). Headquarters are in Walnut Creek, California.

As of April 2026, CodeRabbit is connected to over 3 million repositories, processes over 1 million pull requests per week, serves 15,000+ customers (including Groupon, Chegg, Life360, Mercury, Brex, PostHog, and NVIDIA), and is the most-installed AI app on both GitHub and GitLab.

## Involvement in AI Dev 26

**Role:** Sponsor, Speaker.

CodeRabbit was a sponsor at the AI Dev 26 x SF conference (April 28–29, 2026, Pier 48, San Francisco), organized by DeepLearning.AI (Andrew Ng). The company presented a talk titled **"Deploying AI Code Review at Scale: Turning AI Velocity into a Reliable Quality Gate."** Speaker: **Erik Thorelli** from CodeRabbit. Time: Day 2 (April 29, 2026), 1:45 PM — 2:25 PM.

The talk tied directly into the company's strategic positioning in 2026: CodeRabbit isn't a tool for speeding up code generation—it's a quality gate, an automated check for AI-generated code before it gets merged. In the broader context of the conference's theme around transitioning from AI-assisted coding to agent-driven development, CodeRabbit's presentation emphasized the need for reliable quality gates in agentic SDLC.

Context: Other speakers in the "code quality and reliability" category at the same conference included Sonar (Agentic Analysis) and Datadog (LLM Observability).

## Product

**CodeRabbit** is an AI agent for code review that works at the pull request, IDE, and CLI levels.

### Core Features

- **Automatic PR review** — when a pull request opens, CodeRabbit generates a natural-language walkthrough describing what each change does
- **Sequence diagrams** — automatic control-flow diagrams to visualize code changes
- **Line-by-line comments** — inline comments flagging bugs, vulnerabilities, performance issues, and best practice violations
- **One-click fix** — suggested fixes you can apply with a single click
- **Autofix** — automatic resolution of detected issues
- **Pre-merge checks** — code checks before merging (custom checks in Pro Plus)
- **Agentic Chat** — AI chat inside the PR to discuss changes
- **Docstring generation** — automatic code documentation
- **Unit test generation** (UTG) — automatic test creation (Pro Plus)
- **Finishing Touches** — automatic merge conflict resolution, code simplification (Pro Plus)
- **Analytics Dashboard** — dashboards and customizable reports

### Static Analysis

CodeRabbit combines LLM reasoning with 40+ integrated static analyzers and security tools (linters, SAST scanners, secret detectors) running in isolated sandbox environments.

Built-in tools include: ESLint, Ruff, Gitleaks, Semgrep, Checkov, Brakeman, Trivy (security for IaC), TFLint (Terraform), Fortitude (Fortran), Blinter (Windows batch files), and others.

### Issue Planner (public beta, February 10, 2026)

CodeRabbit's expansion from code review into work planning. Integrates with Linear, Jira, GitHub Issues, and GitLab Issues, automatically generating a Coding Plan from each issue with links to relevant codebase files.

### Platforms and Integrations

- **Git platforms:** GitHub, GitLab, Azure DevOps, Bitbucket
- **IDE:** VS Code (free extension)
- **CLI:** terminal reviews, integration with Claude Code, Cursor, Codex, Gemini, and other AI coding tools
- **MCP (Model Context Protocol):** support for connections (5 in Pro, 15 in Pro Plus)
- **Issue trackers:** Jira, Linear, GitHub Issues, GitLab Issues
- **Messaging:** Slack
- **Configuration:** via UI settings or `.coderabbit.yaml` file

### How It Works

1. Developer opens a pull request
2. CodeRabbit automatically analyzes the diff using codebase context (RAG)
3. Generates walkthrough, sequence diagram, and inline comments
4. Comments are published directly in the PR on the Git platform
5. Developer can apply fixes with one click or discuss changes in agentic chat

Billing only counts developers who create pull requests. Reviewers, managers, and other team members aren't counted.

## Funding

| Round | Date | Amount | Lead Investor | Other Investors | Valuation |
|-------|------|--------|---------------|-----------------|-----------|
| Seed | March 2024 | ~$12M* | — | — | — |
| Series A | August 2024 | $16M | CRV | Flex Capital, Engineering Capital, Olivier Pomel (CEO Datadog) | — |
| Series B | September 2025 | $60M | Scale Venture Partners | NVentures (NVIDIA), CRV, Harmony Partners, Flex Capital, Engineering Capital, Pelion Venture Partners | $550M |

- **Total raised:** $88M
- **Valuation (post-money, Series B):** $550M

*Seed round amount inferred from TechCrunch reporting: Series A brought total raised to just under $20M, Series B brought total to $88M.

### Revenue

| Period | ARR | Notes |
|--------|-----|-------|
| April 2025 | ~$5M | — |
| September 2025 | $15+M | 10x year-over-year growth |
| 2025 (Latka) | $15M | 24-person team |
| April 2026 | ~$40M | 700% year-over-year growth (Sacra estimate) |

Groupon reduced time from review to production from 86 hours to 39 minutes using CodeRabbit.

## Business Model

**Model: Freemium + Per-Seat Subscription + Enterprise**

CodeRabbit uses a seat-based subscription model, where a seat = a developer creating pull requests.

| Plan | Price/mo (monthly) | Price/mo (annual) | Key Features |
|------|---------------------|-------------------|--------------|
| **Free** | $0 | $0 | PR summarization, IDE/CLI reviews, unlimited public/private repositories, 14-day Pro/Pro+ trial; open-source projects get Pro+ features free |
| **Pro** | $30/user | $24/user | PR reviews, inline comments, linters/SAST, Jira/Linear, agentic chat, analytics, docstrings, autofix, 5 MCP, 1 linked repo |
| **Pro Plus** | $60/user | $48/user | Everything in Pro + custom pre-merge checks, UTG, merge conflict resolution, Issue Planner, 15 MCP, 10 linked repos, 10 reviews/hour |
| **Enterprise** | Contact sales | Contact sales | Everything in Pro Plus + SSO, RBAC, audit logging, API, self-hosting, multi-org, SLA, dedicated CSM, AWS/GCP Marketplace |

- **Free trial:** 14 days of Pro/Pro+ features, no credit card required
- **Open-source:** full Pro+ functionality free forever for public repositories
- **Enterprise:** contact sales; available via AWS/GCP Marketplace
- **Seats:** reassignable anytime; no limits on number of repos or PRs

**Revenue streams:**
- Pro and Pro Plus subscriptions (primary)
- Enterprise contracts with SLAs
- AWS/GCP Marketplace (simplified procurement for large companies)

### What Customers Can Expect to Pay

| Profile | Typical Monthly Cost |
|---------|---------------------|
| Individual developer (open-source) | $0 (free) |
| Individual developer (private repos) | $24–$30 |
| Small team (5–10 developers, Pro) | $120–$300 |
| Medium team (20–50, Pro Plus) | $960–$3,000 |
| Enterprise (500+ developers) | Contact sales |

**Important:** CodeRabbit only charges for developers creating PRs. If you have 50 people on your team but only 20 actively push code—you pay for 20. This lowers real costs compared to competitors' per-seat models that count all users.

## Analysis

CodeRabbit holds a leading position in the AI code review market—it's the most-installed AI app on GitHub and GitLab. The company's growing aggressively: from $5M to $40M ARR in one year (8x), and hit $15M in revenue with a team of just 24 people.

### Market Context

The AI coding tools market was valued at $4.86B (2023) with projections of $26B by 2030 (27.1% CAGR).

### Competitive Landscape

| Competitor | Positioning |
|-----------|-------------|
| **GitHub Copilot Code Review** | Built into GitHub ecosystem; convenient but less deep |
| **Qodo (ex-CodiumAI)** | AI code quality + test generation; $40M Series A |
| **Greptile** | Full-codebase indexing before review; strong in monorepos |
| **Sourcery** | Automatic code refactoring |
| **CodeAnt AI** | Code health, quality, and security |
| **Sonar (SonarQube)** | Classic code quality + Agentic Analysis |

**CodeRabbit's Advantages:**
- Supports all four major Git platforms: GitHub, GitLab, Azure DevOps, Bitbucket
- Positioned as a "quality gate" (not just another coding assistant)
- Free full-featured access for open-source
- High capital efficiency ($15M revenue with 24 employees)

**Risks:**
- GitHub Copilot Code Review is built into the dominant platform and could absorb standalone solutions
- Dependency on LLM providers (models, inference costs)
- Growing competition: Qodo, Greptile, CodeAnt are expanding features

## Links

- Website: https://www.coderabbit.ai
- Pricing: https://www.coderabbit.ai/pricing
- Documentation: https://docs.coderabbit.ai
- CLI: https://www.coderabbit.ai/cli
- About: https://www.coderabbit.ai/about-us
- GitHub Marketplace: https://github.com/marketplace/coderabbitai
- Blog: https://www.coderabbit.ai/blog
- Series B announcement: https://www.coderabbit.ai/blog/coderabbit-series-b-60-million-quality-gates-for-code-reviews
