# HoundDog.ai

## About the Company

**HoundDog.ai** is a static code analyzer that specializes in detecting personal data leaks (PII, PHI, CHD) and automating privacy compliance. Founded in 2023 and headquartered in San Francisco (2181 Greenwich Street), the company came out of stealth mode in May 2024.

**Founders:**

| Name | Role | Background |
|------|------|------------|
| **Amjad Afanah** | CEO, Co-founder | Serial cybersecurity entrepreneur. Founded DCHQ (cloud management, acquired), APISec.ai (API security scanner). Former VP of Product at Cyral (data security) |
| **Joohwan Oh** | Co-founder | Founding engineer at Aktos (FinTech). Previously at Facebook, Amazon, Instacart |
| **Sudipta Mukherjee** | Co-founder | — |

**Mission:** Operationalize Zero Trust through proactive data minimization — detecting and eliminating sensitive data leak risks early in the development cycle.

Since launch, HoundDog.ai has been adopted by a growing number of Fortune 1000 organizations across healthcare and technology sectors. The company has scanned over 20,000 repositories to date.

## AI Dev 26 Participation

**Conference:** AI Dev 26 x SF, April 28–29, 2026, Pier 48, San Francisco. Organized by DeepLearning.AI (Andrew Ng).

**Role:** Sponsor (Booth 512).

HoundDog.ai was a sponsor at AI Dev 26 with booth presence. No speaking session was listed in the conference schedule.

**Thematic fit:** The conference includes a "Reliability, Observability & Security" track, which directly aligns with HoundDog.ai's focus on data security and privacy compliance in AI application development.

## Product

### HoundDog.ai — Privacy Code Scanner

A domain-specific static code analyzer that detects sensitive data leaks and tracks data flows directly from source code.

### What It Detects

- **PII** (Personally Identifiable Information)
- **PHI** (Protected Health Information)
- **CHD** (Cardholder Data)
- **Authentication tokens**
- **Shadow AI** — unauthorized use of AI services (OpenAI, Anthropic, Gemini, etc.)
- Leaks through logs, files, local storage, third-party SDKs, LLM prompts

The scanner tracks **150+ types of sensitive data** and **600+ third-party SDKs**.

### How It Works

1. **Deterministic engine:** AI is used to generate and update data detection rules, but the actual scans run on a deterministic static analyzer. This ensures speed, low cost, and no hallucinations.
2. **Data flow tracing:** The scanner tracks data movement across functions, APIs, SDKs, AI connectors, and file boundaries.
3. **Speed:** Can process 1 million lines of code in under a minute on a regular laptop.
4. **Local execution:** Code doesn't leave the developer's environment (by default).

### Supported Languages

| Tier | Languages |
|------|-----------|
| **Free** | Python, JavaScript, TypeScript |
| **Enterprise** | + Java, C#, Go, SQL, GraphQL, OpenAPI/Swagger |

### Integrations

**IDE Plugins:**

| IDE | Status |
|-----|--------|
| VS Code | Available |
| JetBrains (IntelliJ) | Available |
| Cursor | Available |
| Eclipse | Available |

**CI/CD Pipelines:**

| Platform | Support |
|----------|---------|
| GitHub Actions | Yes |
| GitLab CI/CD | Yes |
| Azure Pipelines | Yes |
| CircleCI | Yes |
| Bitbucket Pipelines | Yes |
| Jenkins | Yes |

**Source Control:** GitHub, GitLab, Bitbucket (cloud + enterprise), including self-hosted runners, PR blocking, and automatic pull request comments.

**Partner Integrations:**

| Partner | Integration Description |
|---------|------------------------|
| **Replit** | Built-in privacy scanner for 45M+ Replit users, 10,000+ scans/day |
| **Checkmarx** | Import PII findings into Checkmarx One via Bring Your Own Results (BYOR) |
| **Brinqa** | Connector for importing PII leaks and PII inventory into risk management platform |

### Compliance Automation

Automatic report generation:
- **RoPA** (Record of Processing Activities)
- **PIA** (Privacy Impact Assessment)
- **DPIA** (Data Protection Impact Assessment)

Supported frameworks: **GDPR, CCPA, ISO 29100, NIST 800-53, HIPAA, PCI, FedRAMP**.

### Open Source

CLI scanner available on GitHub: [hounddogai/hounddog](https://github.com/hounddogai/hounddog). License is proprietary (commercial) with a free tier.

## Funding

| Round | Amount | Date | Lead Investors |
|-------|--------|------|----------------|
| **Seed** | **$3.1M** | **May 2024** | E14 Fund, Mozilla Ventures, ex/ante |

**Angel and Additional Investors:**
- **Amjad Masad** (CEO of Replit)
- **Graph Ventures**
- **Union Square Ventures**

**About the Investors:**
- **E14 Fund** — Cambridge, MA-based VC fund focused on startups from the MIT ecosystem
- **Mozilla Ventures** — Mozilla's investment arm, focused on privacy and the open internet
- **ex/ante** — Early-stage venture fund

## Business Model

**Model: Freemium + Enterprise**

The open-source CLI scanner attracts developers (freemium), then companies upgrade to paid plans for advanced features, compliance automation, and enterprise support.

**Target Customers:**
- Fortune 1000 companies in finance, healthcare, and tech
- Development teams working with PII/PHI data
- Privacy and compliance teams responsible for GDPR/HIPAA/PCI
- Companies actively using AI/LLM in their products

| Plan | Price | What's Included |
|------|-------|-----------------|
| **Free** | $0 | GitHub open source scanner. PII leak detection (limited languages/sinks). Basic data flow visualization. Shadow AI discovery (OpenAI, Anthropic, Gemini). IDE plugins. CI/CD integration. Support via GitHub Issues |
| **Starter** | $100/year per developer | All Free features (expanded). Third-party data flows (600+ SDKs). Automatic privacy reporting (RoPA, PIA, DPIA). Multiple compliance frameworks (GDPR, CCPA, ISO 29100, NIST 800-53, HIPAA). Slack/email alerts, issue tracking. Security dashboard integration. 8x5 email support |
| **Enterprise** | Custom pricing | All Starter features. Automatic CI configuration. Managed scans with broker support. Priority support with SLA. Dedicated Slack channel |

### What to Expect Cost-Wise

| Usage Profile | Approximate Cost |
|--------------|------------------|
| Individual developer / OSS | $0 (Free) |
| 10-developer team (Starter) | ~$1,000/year (~$83/month) |
| 50-developer team (Starter) | ~$5,000/year (~$417/month) |
| 100-developer team (Starter) | ~$10,000/year (~$833/month) |
| Enterprise (large organization) | Custom pricing, negotiated terms |

## Analysis

### Market Position

HoundDog.ai operates at the intersection of AI in Cybersecurity and Privacy-Preserving AI — two rapidly growing market segments.

### Competitive Landscape

| Competitor | Focus | HoundDog.ai Difference |
|------------|-------|------------------------|
| **Privado** | Privacy code scanning | HoundDog.ai claims improved accuracy, fewer false positives, and faster scans |
| **BigID** | Enterprise data discovery | BigID works at the data storage level, HoundDog.ai works at the code level |
| **Strac** | DLP + data discovery | Strac operates at the SaaS level (scans applications), HoundDog.ai uses shift-left (scans code) |
| **OpenAI Privacy Filter** | PII redaction in text | Runtime filter for text, not code analysis |

### Key Advantages

- **Shift-left approach:** Catch issues before deployment, not at runtime
- **Deterministic engine:** No hallucinations, fast and cheap to operate
- **AI Governance:** Detects shadow AI and data leaks in LLM prompts
- **Replit partnership:** Access to 45M+ developer audience
- **Low barrier to entry:** Free CLI + $100/year per developer

### Risks and Limitations

- Early stage (seed round, $3.1M) — limited resources
- Still building open source community
- Competition from major AppSec platforms (Checkmarx, Snyk), though Checkmarx is already a partner
- Dependence on B2B enterprise sales for scale

## Links

- Website: https://hounddog.ai
- GitHub: https://github.com/hounddogai/hounddog
- Pricing: https://hounddog.ai/pricing/
- TechCrunch: https://techcrunch.com/2024/05/22/hounddog-ai-helps-developers-prevent-personal-information-from-leaking/
- SiliconANGLE: https://siliconangle.com/2024/05/22/hounddog-ai-raises-3-1m-help-companies-proactively-prevent-sensitive-data-leaks/
- Checkmarx Partnership: https://checkmarx.com/blog/expanding-appsec-coverage-with-pii-leak-detection-with-checkmarx-hounddog-ai/
- Replit Integration: https://hounddog.ai/hounddog-ai-enables-privacy-by-design-in-replit-ai-apps/
- LinkedIn: https://www.linkedin.com/company/hounddog-ai
- Crunchbase: https://www.crunchbase.com/organization/hounddog-ai
