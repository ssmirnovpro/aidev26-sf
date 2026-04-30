# Spice AI

## About the Company

**Spice AI** (spice.ai / spiceai.org) builds an open-source Data & AI Runtime. The Seattle-based startup has raised $14.5 million across two rounds.

## AI Dev 26 Participation

**Role:** Speaker.

**Talk:** "The Agent Data Stack: Why Every AI Agent Needs Its Own Data Stack"
**Speaker:** Luke Kim from Spice AI
**Time:** Day 2 (April 29, 2026), Stage 3, 3:30–4:00 PM (30 min)

Spice AI's core pitch: "Spice makes it easy to serve enterprise data to AI apps & agents."

## Product

**Spice** is an open-source SQL query, search, and LLM-inference engine written in Rust for data-intensive applications and AI agents.

### Key Messages (from materials)

> "The Open-Source Data & AI Runtime"

> "Spice makes it easy to serve enterprise data to AI apps & agents."

### Components (from materials)

#### What You Can Build
- Data-driven AI Apps
- Agents

#### Data Frameworks & Acceleration
- Data & acceleration layer
- Fast data access for AI applications
- SQL federation & acceleration

#### Hybrid Search
- Combined search capabilities
- Query acceleration for low-latency responses

#### AI Inference & Tools
- Built-in LLM inference
- Local model serving support (CUDA/Metal accelerated)

### Technical APIs (4 standard APIs)

1. **SQL Query & Search**: HTTP, Arrow Flight, Arrow Flight SQL, ODBC, JDBC, ADBC; vector_search and text_search
2. **OpenAI-Compatible APIs**: HTTP APIs for OpenAI SDK compatibility, local model serving, hosted model gateway
3. **Iceberg Catalog REST APIs**: Unified Iceberg REST Catalog API
4. **MCP HTTP+SSE APIs**: Integration via Model Context Protocol

### Control and Flexibility (from materials)

> "Spice OSS offers control and optionality at every layer. Deploy anywhere: on-premises, at the edge, or in the cloud."

### Integrations (from materials)

- DuckDB, DataFusion
- Vortex (columnar format)
- GitHub (open-source)

### Spice Cloud Platform

> "The Data Platform for AI Context"

- Serve petabytes of data to AI agents & apps without pipelines
- Ground Apps & AI Agents in Data
- Hybrid Search & AI
- SQL Federation & Acceleration
- Customers include: Twilio, Barracuda, NRC Health

## Funding

| Round | Amount | Lead/Participants |
|-------|--------|-------------------|
| Pre-seed | $1M (October 2021) | — |
| Seed | $13.5M (September 2022) | Led by Madrona; Blackbird Ventures, Basis Set Ventures, Asymmetric, Alumni Ventures Blockchain Fund, Protocol Labs |

- **Total raised**: $14.5 million
- **Founded**: 2021, Seattle, WA

## Business Model

**Model: Open Source + Managed Cloud (SaaS)**

| Product | Type | Pricing |
|---------|------|---------|
| **Spice OSS** | Open-source runtime | Free |
| **Spice Cloud** | Managed platform | Contact for pricing |

**Spice OSS** is a completely free open-source runtime (single binary/container) that you can deploy anywhere.

**Spice Cloud** is their managed platform branded as "The Data Platform for AI Context":
- Petabyte-scale capabilities
- No pipeline requirements
- Enterprise customers include: Twilio, Barracuda, NRC Health

**Pricing:**
- **Open Source**: Free (Apache 2.0 license)
- **Cloud**: Subscription and usage-based tiered plans
- **Enterprise**: Tailored pricing

**Revenue sources:**
- Spice Cloud subscriptions/consumption
- Enterprise contracts
- Support services

## Roadmap

Spice is developing distributed query execution (currently in preview), enhanced search, acceleration, and AI primitives.

## Analysis

Spice AI positions itself as the "data layer for AI agents"—a middle layer between data stores and AI applications. The Rust-based engine is designed for performance and portability (single binary/container). The platform combines an open-source approach with OpenAI API compatibility.

## Links

- Website: https://spice.ai
- OSS: https://spiceai.org
- Pricing: https://spice.ai/pricing
- GitHub: https://github.com/spiceai/spiceai
