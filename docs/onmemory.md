# OnMemory

## Company Overview

**OnMemory** is building deterministic, verifiable memory infrastructure for AI agents. The company's pitch: delivering accurate and traceable AI responses through a memory architecture that guarantees reproducibility and verification of stored data.

| Parameter | Value |
|----------|----------|
| **Name** | OnMemory |
| **Website** | https://onmemory.ai |
| **Stage** | Early launch (as of April 2026) |
| **Focus** | Deterministic, verifiable memory for AI agents |
| **Public Presence** | Minimal |

**Key positioning (from website):**

> "Deterministic, verifiable memory for AI agents, ensuring accurate and traceable responses."

As of April 2026, the company's in early launch mode. The onmemory.ai site contains minimal information: a product description, a waitlist signup form, and About and Contact pages. There's no public information about the team, founders, legal entity, or company size.

OnMemory has virtually no presence in professional directories (Crunchbase, Product Hunt, LinkedIn) and doesn't appear in any AI memory market analysis articles. No GitHub repository found.

## AI Dev 26 Participation

**Conference:** AI Dev 26 x SF, April 28-29, 2026, Pier 48, San Francisco. Organized by DeepLearning.AI (Andrew Ng).

OnMemory had presence at AI Dev 26, though no speaking session is listed in the conference schedule.

| Parameter | Value |
|----------|----------|
| **Conference presence** | Confirmed (no speaking session in schedule) |
| **Description** | Memory infrastructure for agents |
| **Talk** | None in schedule |

**Thematic context:** The conference included two separate "Agent Context and Memory" blocks (Stage 3, Day 2), confirming high interest in agent memory topics. Related talks:

| Time | Talk | Speaker | Company |
|-------|--------|--------|----------|
| Day 1, 2:10 PM | Hands-On Agent Context and Memory Engineering with Oracle AI Database | Eli Schilling | Oracle |
| Day 2, 2:30 PM | Deterministic Memory: How to Build an AI That Cannot Lie | Andrew K. Davies | Harmony8 |
| Day 2, 1:00 PM | Building the Context Engine AI Agents Need | Brandon Waselnuk | Unblocked |

Harmony8's talk on "deterministic memory" aligns most closely with OnMemory's stated positioning.

**Other companies with speaking sessions at AI Dev 26:** CopilotKit, Anchor Browser, Spice AI, Apify, Vocal Bridge, and others (verified from schedule).

## Product

### Positioning

OnMemory positions itself as memory infrastructure for AI agents with two key properties:

1. **Deterministic memory** — memory whose results are reproducible and predictable. Unlike probabilistic approaches (LLM-based memory extraction), a deterministic architecture guarantees identical results for identical inputs.

2. **Verifiable memory** — the ability to verify and confirm the origin and correctness of each memory element. Enables auditing and tracing agent responses back to specific sources.

### Inferred Architecture

**Note:** The detailed technical product description hasn't been disclosed. The following is speculative based on the company's positioning:

| Property | Description |
|----------|----------|
| **Deterministic IDs** | Content-addressable identifiers (hash-based) ensuring reproducibility |
| **Append-only log** | Memory journal that doesn't allow history modification (auditability) |
| **Provenance tracking** | Tracking the origin of each fact in memory |
| **Verification layer** | Mechanism for verifying stored facts' correctness |

### Competitive Differentiation

Many existing solutions on the market (Mem0, Supermemory, Zep) use LLM-based methods for extracting and storing memory: models analyze interactions, extract information, and save them in vector/graph stores.

Based on its positioning, OnMemory appears to offer an alternative approach: deterministic processing where each memory element is verifiable and traceable. This matters for:

- Regulated industries (finance, healthcare, legal)
- Decision-making systems requiring audit trails
- Enterprise scenarios with compliance requirements (SOC 2, HIPAA, GDPR)

### Integrations

No public information available about integrations with specific frameworks (LangChain, CrewAI, LlamaIndex) or platforms.

## Funding

| Round | Amount | Date | Investors |
|-------|-------|------|-----------|
| — | No data | — | No data |

There's no information about OnMemory funding rounds in Crunchbase, TechCrunch, or other specialized sources. Indirect signs point to a very early stage (pre-seed or bootstrapped):

- Minimal public presence
- No LinkedIn company page
- No press mentions
- Waitlist model (product not yet publicly launched)

## Business Model

OnMemory's business model hasn't been disclosed publicly. Based on market analogs, we can assume a typical model for the segment:

| Model | Description |
|--------|----------|
| **API-as-a-Service** | Providing memory as a cloud API (similar to Mem0, Supermemory) |
| **Usage-based pricing** | Pay for memory operations / stored data volume |
| **Freemium** | Free tier for developers + paid enterprise plans |

**Target customers (assumed):**

- AI developers building agentic systems requiring audit trails
- Enterprise teams in regulated industries
- Companies running mission-critical AI deployments

### What Customers Can Expect

As of this research, there's no public pricing information for OnMemory. For context—key competitor pricing:

| Company | Free plan | Paid plan | Enterprise |
|----------|----------------|-------------|------------|
| **Mem0** | Hobby: 10,000 memories | Starter $19/mo, Pro $249/mo | Custom |
| **Supermemory** | Free plan | Pro $19/mo, Scale $399/mo | Custom |
| **Zep** | Free: 1,000 credits/mo | Flex $25/mo, Flex Plus $475/mo | Custom |
| **Cognee** | Open-source (self-hosted) | — | Custom |
| **OnMemory** | No data | No data | No data |

## Analysis

### Market Context

OnMemory operates in the **AI Agent Memory Infrastructure** segment—a growing AI infrastructure segment in 2025-2026. The broader agentic AI market is experiencing rapid growth, though exact market size figures vary by source and definition.

### Competitive Landscape

The AI Agent Memory market is crowded and rapidly evolving. Key players:

| Company | Round/Funding | GitHub Stars | Differentiation |
|----------|---------------------|-------------|----------------|
| **Mem0** | $24M raise across Seed and Series A (YC-backed) | 41,000+ | Drop-in memory API, SOC 2 / HIPAA, 80K+ developers |
| **Supermemory** | Seed, $2.6M | Open-source | Context infrastructure, user profiles, memory graph |
| **Zep / Graphiti** | Undisclosed | Open-source | Temporal knowledge graph, episodic memory |
| **Cognee** | Undisclosed | Open-source | Local-first, privacy, graph reasoning |
| **Letta** | Felicis-backed | Open-source | Stateful agents, tool-augmented memory |
| **Cloudflare Agent Memory** | N/A (Cloudflare product) | — | Deterministic IDs, edge-first, Cloudflare ecosystem |
| **OnMemory** | No data | None | Deterministic + verifiable memory |

### OnMemory's Position

OnMemory's at the earliest development stage among listed competitors. However, the company's positioning ("deterministic, verifiable memory") differs from most players building probabilistic memory systems.

**Potential advantages:**
- Unique positioning in the verifiable/auditable memory niche
- Growing demand for compliance-ready AI solutions
- Gartner predicts 25% of enterprise GenAI applications will experience at least five minor security incidents per year by 2028—highlighting need for reliable systems

**Risks and constraints:**
- Very early stage: no public product, no funding, no team in public sources
- Intense competition: Mem0 ($24M funding), Supermemory ($2.6M), Cloudflare—serious players with resources
- Minimal public presence and no open-source component
- Deterministic approach may limit flexibility compared to LLM-based memory extraction

## Links

- Website: https://onmemory.ai
- AI Dev 26 (conference): https://ai-dev.deeplearning.ai/
- AI Dev 26 (sponsors): https://ai-dev.deeplearning.ai/sponsor
