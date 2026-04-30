# Databricks

## About the Company

**Databricks** is the leading data and AI platform for enterprises. Founded in 2013 by seven researchers from UC Berkeley: Ali Ghodsi (CEO), Ion Stoica, Matei Zaharia, Patrick Wendell, Reynold Xin, Andy Konwinski, and Arsalan Tavakoli-Shiraji. The founders are the original creators of Apache Spark (developed at UC Berkeley), and Databricks later created Delta Lake, MLflow, and Unity Catalog—the core open-source projects that power the platform.

The company is headquartered in San Francisco with over 8,000 employees worldwide. More than 15,000 organizations use Databricks, including Block, Comcast, Conde Nast, Rivian, Shell, and 70% of the Fortune 500.

Databricks remains private with a $134 billion valuation (February 2026). Its anticipated IPO is one of the most closely watched events in enterprise tech.

## AI Dev 26 Participation

**Conference:** AI Dev 26 x SF — The AI Developer Conference
**Dates:** April 28–29, 2026, Pier 48, San Francisco
**Organizer:** DeepLearning.AI (Andrew Ng)

**Role:** Sponsor, Speaker.

**Talk:** "The Coding Agent Multiverse of Madness"
**Speaker:** Ankit Mathur from Databricks
**Time:** Day 2 (April 29), Stage 1 — Software Development in the Age of GenAI, 9:45–10:25 AM (40 min).

The talk covered the explosive growth in AI coding agents and tooling. On the same stage, Mathur was joined by speakers from Cursor (Amrita Venkatraman, "3rd Era of Software Development") and Docker (Tushar Jain, "Shipping Agents Safely").

## Product

Databricks offers the **Data Intelligence Platform**—a cloud platform that unifies data processing, analytics, data governance, and AI in a single environment. The platform runs on all three major clouds: AWS, Azure, and GCP.

### Lakehouse Architecture

Databricks pioneered the **Data Lakehouse** architecture—a hybrid that combines the flexibility of data lakes with the performance and governance of data warehouses. It's built on open formats (Delta Lake, Apache Iceberg) and Apache Spark.

- **Delta Lake** — open-source storage layer providing ACID transactions on top of data lakes
- **Lakebase** (generally available on AWS February 3, 2026) — Postgres-compatible transactional database inside the Lakehouse, designed for AI-native apps where operational and analytical data need to coexist. Came through Databricks' approximately $1B Neon acquisition.

### Unity Catalog — Data Governance

A unified governance system for the entire platform:

- Centralized access control for tables, models, and pipelines
- Lineage tracking at the table, model, and prompt level
- Unity Catalog Metrics — define metrics once, reuse everywhere
- Zero-copy data sharing with external systems (Snowflake, Trino, Flink, Spark) via Iceberg format

### Mosaic AI — The AI Layer

After acquiring MosaicML for $1.3 billion (2023), Databricks integrated LLM training and serving capabilities:

- **Mosaic AI Model Serving** — managed model serving with routing, monitoring, guardrails, and cost optimization
- **Agent frameworks and evaluation** — tools for building AI agents with evaluation capabilities
- **Vector Search** — serverless vector database integrated with Delta tables for RAG architectures
- **Feature Store** and **Model Registry** — integrated into Unity Catalog
- **AutoML** — low-code tool for automated ML model creation

### MLflow and LLMOps

- **MLflow 3.0** — updated platform for the full ML/LLM lifecycle: evaluation with "LLM judges," trace capture, feedback loops for generative AI quality control
- Open standard widely adopted across the industry beyond Databricks

### Lakeflow — Data Pipelines

- **Lakeflow Designer** — no/low-code tool that lets business users design data products visually with an AI assistant, while using Spark SQL under the hood

### Databricks SQL

Full-featured SQL engine for analytical queries with serverless compute, optimized for BI tools and ad-hoc analysis.

### Key Acquisitions

| Company | Year | Amount | What They Got |
|----------|-----|-------|--------------|
| MosaicML | 2023 | ~$1.3B | LLM training platform, MPT models |
| Tabular | 2024 | Over $1B (not disclosed) | Creators of Apache Iceberg format |

## Funding

Databricks is one of the world's most highly valued private tech companies with funding across multiple rounds from major investors.

| Round | Date | Amount | Valuation | Key Investors |
|-------|------|-------|--------|-------------------|
| Series A | Sep 2013 | $14M | — | Andreessen Horowitz |
| Series B | 2014 | $33M | — | New Enterprise Associates (NEA) |
| Series C | 2016 | $60M | — | NEA |
| Series D | Aug 2017 | $140M | — | Andreessen Horowitz, Battery Ventures |
| Series E | Feb 2019 | $250M | — | Andreessen Horowitz |
| Series F | Oct 2019 | $400M | — | Andreessen Horowitz |
| Series G | Feb 2021 | $1B | $28B | Franklin Templeton, AWS, CapitalG, Salesforce Ventures |
| Series H | Aug 2021 | $1.6B | $38B | Morgan Stanley (Counterpoint Global), Baillie Gifford |
| Series I | Sep 2023 | $500M | $43B | T. Rowe Price, Nvidia, Capital One Ventures |
| Series J | Nov 2024 | $10B | $62B | Thrive Capital, Andreessen Horowitz, DST Global, Insight Partners |
| Series K | Aug 2025 | $1B | $100B+ | Oversubscribed 20x |
| Latest Funding | Feb 2026 | ~$5B equity + ~$2B debt capacity | $134B | Insight Partners, Fidelity, J.P. Morgan AM, BlackRock, Blackstone, Coatue, GIC, MGX, Temasek, Thrive Capital |

### Financial Metrics

| Metric | Value | Period |
|---------|----------|--------|
| Annual revenue (run-rate) | $5.4B | Q4 ended January 31, 2026 |
| Revenue growth (YoY) | 65%+ | Q4 ended January 31, 2026 |
| Previous run-rate | $4.8B | Q3 2025, 55% YoY growth |
| Free cash flow | Positive | 12 months prior to Jan 31, 2026 |
| Customer count | 15,000+ | 2026 |

## Business Model

**Model: Usage-based (consumption), SaaS subscription**

Databricks uses the **DBU (Databricks Unit)** as its pricing unit—an abstract measure of compute capacity. Customers pay for DBUs consumed multiplied by the per-DBU rate, which varies by workload type and subscription tier.

### The Double Bill

Customers receive **two bills**:
1. **Databricks** — for DBUs (platform compute)
2. **Cloud provider** (AWS/Azure/GCP) — for virtual machines, storage, network traffic

Cloud costs often **equal or exceed** DBU costs. Industry guidance suggests budgeting 2–3x your DBU spend for total cost, though actual ratios vary by workload.

### Pricing Tiers

| Tier | Availability | Features |
|---------|-------------|-------------|
| **Standard** | Being retired (Azure: creation ends April 1, 2026, retirement October 1, 2026) | Basic Apache Spark |
| **Premium** | Base tier for new customers | Unity Catalog, RBAC, audit logs, IP access lists |
| **Enterprise** | For large organizations | All Premium features + compliance, enhanced security. Rates 15–25% higher |

### DBU Rates (examples, AWS Premium tier)

**Note:** These are example rates based on industry sources and may vary. Check official Databricks pricing for current rates.

| Workload Type | Rate per DBU |
|--------------|--------------|
| Jobs Compute (batch jobs) | ~$0.15 |
| Jobs Photon | ~$0.20 |
| All-Purpose Compute (interactive) | ~$0.40 |
| All-Purpose Photon | ~$0.55 |
| SQL Classic | ~$0.22 |
| SQL Serverless | ~$0.70 |

*Azure rates differ slightly. Verify current pricing with Databricks.*

### Commitment Discounts

Databricks offers pre-purchase commitment discounts (DBCU) with varying percentages based on commitment term. Contact Databricks for current discount tiers.

Optimization tip: Switching from All-Purpose Compute to Jobs Compute for production workloads can significantly reduce per-DBU costs.

### Revenue Sources

1. **DBU consumption** — primary source (compute for ETL, ML, SQL, streaming)
2. **Serverless services** — Vector Search, SQL Serverless, Model Serving (higher rates but include infrastructure)
3. **Enterprise contracts** — multi-year commits with guaranteed volume
4. **Professional Services** — consulting, training, implementation
5. **Marketplace** — ecosystem of data and solutions from partners

### What to Expect as a Customer

Realistic monthly cost estimates (DBU + cloud infrastructure):

| Customer Profile | DBU/month | DBU Costs | Cloud Infra | Total Monthly | Total Yearly |
|-----------------|---------|----------------|----------------|---------------|-------------|
| **Startup / small team** (5 analysts, ad-hoc analysis, light ETL) | ~200 | $110 | $150–300 | **$260–410** | **$3,000–5,000** |
| **Mid-market** (15 people, daily ETL, ML experiments, BI) | ~1,000 | $350–500 | $800–1,500 | **$1,150–2,000** | **$14,000–24,000** |
| **Enterprise** (24/7 production, streaming, ML serving, SQL warehouse) | 5,000+ | $3,000–5,000+ | $5,000–15,000+ | **$8,000–20,000+** | **$100,000–250,000+** |
| **Large Enterprise** (massive deployments, multiple teams) | 20,000+ | custom | custom | custom | **$500,000–$1,000,000+** |

**Optimization tips:**
- Use Jobs Compute instead of All-Purpose for production pipelines
- Consider pre-purchase commits (DBCU) for predictable workloads
- Configure auto-termination for inactive cluster sessions
- Use Photon engine for SQL workloads (higher per-DBU cost but faster, which can reduce overall spend)

## Analysis

### Market Position

Databricks and Snowflake are the two leading competitors in cloud data platforms. As of early 2026 (approximate figures):

| Metric | Databricks | Snowflake |
|---------|-----------|-----------|
| Annual revenue | $5.4B (run-rate, Q4 FY26) | ~$4.7B (estimates vary) |
| YoY growth | 65%+ | ~29% |
| Valuation | $134B (private) | ~$50–60B (market cap) |
| Free cash flow | Positive | Negative |
| Strength | AI/ML, Spark, open-source, Lakehouse | SQL analytics, data sharing, simplicity |

### Key Competitive Advantages

- **Open-source DNA** — Delta Lake, MLflow, Unity Catalog, Apache Spark as open projects reduce vendor lock-in
- **AI/ML first** — platform built for ML/AI workloads from the ground up, giving it an edge in the GenAI era
- **Lakehouse architecture** — unified platform instead of separate data lake and data warehouse
- **Faster growth** — 65% YoY vs. Snowflake's 29%

### Competitive Landscape

Beyond Snowflake, Databricks competes with:
- **Microsoft Fabric** — integrated data platform from Microsoft (Azure)
- **Google BigQuery** — serverless data warehouse from Google
- **Amazon Redshift** — data warehouse from AWS
- **Starburst/Trino** — open-source distributed SQL

### Outlook

Databricks has surpassed Snowflake in run-rate revenue and is growing significantly faster. Its move to positive free cash flow and $134 billion valuation position the company as a strong IPO candidate. At current growth rates, the company is on track for continued revenue expansion.

## Links

- Official website: https://www.databricks.com/
- About: https://www.databricks.com/company/about-us
- Founders: https://www.databricks.com/company/founders
- Pricing: https://www.databricks.com/product/pricing
- Documentation: https://docs.databricks.com/
- Mosaic AI: https://www.databricks.com/product/machine-learning/mosaic-ai
- Unity Catalog: https://www.databricks.com/product/unity-catalog
- Data + AI Summit 2026: https://www.databricks.com/dataaisummit
- Newsroom: https://www.databricks.com/company/newsroom
- GitHub (AI Dev Kit): https://github.com/databricks-solutions/ai-dev-kit
