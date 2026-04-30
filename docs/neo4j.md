# Neo4j

## Company Overview

**Neo4j** is the world's leading graph database company. Founded in 2007 by Emil Eifrem, Johan Svensson, and Peter Neubauer in Sweden, the company is now headquartered in San Mateo, California (400 Concar Dr, San Mateo, CA 94402). Neo4j commands a dominant 44% share of the graph database market. The company's technology powers 84% of Fortune 100 companies. In 2024, Neo4j crossed $200 million in annual recurring revenue (ARR), doubling its top line in just three years.

| Parameter | Value |
|----------|----------|
| **Founded** | 2007 |
| **Founders** | Emil Eifrem, Johan Svensson, Peter Neubauer |
| **Headquarters** | San Mateo, California, USA |
| **CEO** | Emil Eifrem |
| **Employees** | 500–1,000 (LinkedIn range) |
| **ARR** | $200+ million (November 2024) |
| **Graph DB Market Share** | 44% |
| **Status** | Private company, preparing for IPO |

## Participation in AI Dev 26

**Role:** Speaker.

Neo4j participated in the AI Dev 26 x SF conference (April 28-29, 2026, Pier 48, San Francisco), organized by DeepLearning.AI (Andrew Ng). The event brought together over 3,000 AI developers.

**Talk:** "'The AI Said So?' How to Build Auditable AI Agents Using Context Graphs"
**Speaker:** Nyah Macklin from Neo4j
**Time:** Day 1 (April 28, 2026), Stage 3 — Agent Search and Context, 1:00–1:40 PM (40 min)

The talk focused on context graphs—knowledge graphs designed to capture not just data and events, but the causal reasoning behind decisions. A context graph unifies three types of AI agent memory:

- **Episodic memory** — stores conversation history and interactions
- **Semantic memory** — structured knowledge as a graph (entities, relationships, properties)
- **Reasoning memory** — reasoning traces, tool usage audit trails, decision provenance

Key argument: without reasoning memory, you can't explain an agent's decisions, learn from experience, or debug unexpected behavior. All three memory types combined in a graph create a complete audit trail: which data sources influenced a decision, what reasoning steps the agent took, and whether similar approaches succeeded before.

Neo4j offers the open-source **neo4j-agent-memory** library (Neo4j Labs), which integrates with LangChain, Pydantic AI, LlamaIndex, OpenAI Agents, CrewAI, and other agent frameworks.

## Product

### Neo4j Graph Database

Neo4j is an ACID-compliant transactional graph database with native graph storage and processing. Core data model elements:

- **Nodes** — entities with unique identifiers, labels, and properties (key-value pairs)
- **Relationships** — typed connections between nodes with direction and properties
- **Properties** — key-value attributes on nodes and relationships

Key characteristics:

- **ACID transactions** — atomicity, consistency, isolation, durability
- **Native graph processing** — index-free adjacency, O(1) relationship traversal
- **Flexible schema** — add/remove properties on the fly
- **Elastic scalability** — replication protocol for horizontal scaling
- **CRUD operations** via Cypher declarative query language

### Cypher Query Language

Cypher is a declarative query language for graphs—essentially SQL for graph models. It uses ASCII-art syntax:

- Parentheses `()` — nodes
- Square brackets `[]` — relationships
- Arrows `-->`, `<--` — relationship direction

Example query:
```cypher
MATCH (p:Person)-[:WORKS_AT]->(c:Company {name: 'Neo4j'})
RETURN p.name, p.role
```

Cypher is a major influence on GQL (Graph Query Language)—the first international standard for graph query languages (ISO/IEC 39075), which draws from existing graph query languages.

### GraphRAG

GraphRAG is an approach to Retrieval-Augmented Generation that uses graph-based data representation to enrich LLM context. Unlike traditional vector RAG, GraphRAG:

- Provides **structured relationships** between entities, not isolated text chunks
- Executes **dynamic queries** across the graph for precise context retrieval
- Ensures **traceability** of answers to specific nodes and relationships
- Reduces **LLM hallucinations** through explicit knowledge graphs

### Knowledge Graphs for AI

Neo4j positions knowledge graphs as a foundational layer for AI systems:

- **Context graphs** — graphs for storing agent context (memory, reasoning, decisions)
- **Neo4j Aura Agent** — ontology-driven platform for building, connecting to knowledge graphs, and deploying AI agents (generally available in 2026)

### AuraDB — Managed Cloud Service

**Neo4j AuraDB** is a fully managed cloud graph database service, available on AWS, Google Cloud, and Microsoft Azure. It's the company's primary revenue driver. Demand for the cloud offering grew 5x over three years.

| Edition | Description |
|----------|----------|
| **AuraDB Free** | Free: 1 DB, 200K nodes, 400K relationships |
| **AuraDB Professional** | Up to 128 GB, 7-day backups, best-effort support |
| **AuraDB Business Critical** | Up to 512 GB, 99.95% SLA, 30-day PITR backups, RBAC/SSO |
| **Virtual Dedicated Cloud** | For regulated industries, on request |
| **Neo4j Community** | Open-source, on-premises, free |
| **Neo4j Enterprise** | On-premises, extended capabilities, licensed |

## Funding

Neo4j has raised significant funding across multiple rounds. The company reached unicorn status ($1B+ valuation) in 2021, 14 years after founding.

| Round | Date | Amount | Lead Investors | Valuation |
|-------|------|-------|---------------|--------|
| **Seed** | 2009 | — | — | — |
| **Series A** | 2011 | $10.6M | Fidelity Growth Partners Europe | — |
| **Series B** | November 2012 | $11M | Sunstone Capital | — |
| **Series C** | January 2015 | $20M | Creandum, Dawn Capital | — |
| **Series D** | November 2016 | $36M | Greenbridge Partners | — |
| **Series E** | November 2018 | $80M | One Peak Partners, Morgan Stanley Expansion Capital | — |
| **Series F** | June 2021 | $325M | Eurazeo | $2B |
| **Series F (extension)** | October 2021 | $66M | Inovia Capital | $2B |
| **Series G** | November 2024 | $50M | Noteus Partners | ~$2B |

Key investors: Eurazeo, GV (Google Ventures), One Peak Partners, Creandum, Greenbridge Partners, Morgan Stanley Expansion Capital, Inovia Capital, DTCP, Lightrock, Eight Roads, Noteus Partners.

The Series F ($325M) was the largest investment in a private database company at the time.

## Business Model

**Model: Open Source + Managed Cloud (DBaaS) + Enterprise Licenses**

Neo4j uses a classic open-core model with emphasis on cloud DBaaS:

| Revenue Source | Description |
|----------------|----------|
| **AuraDB (cloud DBaaS)** | Primary revenue driver. Subscription to managed cloud service |
| **Enterprise licenses** | On-premises licenses for large organizations |
| **Professional services** | Consulting, training, technical support |
| **AI products** | Aura Agent, GraphRAG solutions — growing segment |

### AuraDB Pricing

| Plan | Price | Key Parameters |
|-------|------|--------------------|
| **AuraDB Free** | $0 | 1 DB, 200K nodes, 400K relationships, no credit card required |
| **AuraDB Professional** | $65/GB/month | Up to 128 GB, 7-day backups, best-effort support |
| **AuraDB Business Critical** | $146/GB/month | Up to 512 GB, 99.95% SLA, 30-day PITR backups, RBAC/SSO/IP filtering, 24/7 premium support |
| **Virtual Dedicated Cloud** | On request | For regulated industries, dedicated infrastructure |
| **Neo4j Community** | $0 | Open-source, on-premises, limited capabilities |
| **Neo4j Enterprise** | On request | On-premises, full feature set |

Important note: AuraDB pricing is based on **reserved capacity (RAM)**, not consumption (query volume). This is advantageous for high-throughput workloads where query volume is unpredictable. Pausing a database saves ~80% of costs.

### What Customers Should Expect

| Customer Profile | Plan | Typical Size | Estimated Cost/Month |
|-----------------|-------|---------------|------------------------------|
| Learning, prototyping | AuraDB Free | 200K nodes | $0 |
| Startup, MVP | AuraDB Professional | 1–4 GB | $65–$260 |
| Growing product | AuraDB Professional | 8–32 GB | $520–$2,080 |
| Production SaaS (medium) | AuraDB Professional | 32–64 GB | $2,080–$4,160 |
| Enterprise production | AuraDB Business Critical | 32–128 GB | $4,672–$18,688 |
| Large enterprise (HA, compliance) | AuraDB Business Critical | 128–512 GB | $18,688–$74,752 |
| Regulated industry | Virtual Dedicated Cloud | On request | Custom |
| On-premises (self-hosted) | Neo4j Enterprise | Unlimited | License on request |

**Notes:**

- AuraDB Professional works for most production workloads up to 128 GB
- Business Critical adds 99.95% SLA, enhanced security (RBAC, SSO, IP filtering), and 24/7 support
- On-premises (Community Edition) is free but lacks clustering, hot backup, RBAC, and commercial support
- Discounts available for annual and multi-year contracts
- Pausing databases saves ~80%—useful for dev/staging environments

## Market Analysis

### Graph Database Market

The graph database market is valued at **$3.31 billion** (2025) and projected to reach **$14.02 billion** by 2031, growing at a **27.19% CAGR (2026-2031)** (Mordor Intelligence). Cloud deployments account for 72% of market revenue (2024) and are growing at a 29.5% CAGR.

### Trend: Graphs for AI and RAG

Integration of graph databases with GenAI/LLMs is a key market growth driver:

- **GraphRAG** provides structured context for enterprise RAG applications, offering an alternative to flat vector search
- **AWS** launched GraphRAG in Amazon Bedrock Knowledge Bases (March 2025, generally available)—validation of the approach by the largest cloud provider
- Gartner predicts that by 2028, **33% of enterprise applications** will include agentic AI (less than 1% in 2024)
- AI Dev 26 featured a **Stage 3 — Agent Search and Context** track, reflecting growing industry focus on context engineering for AI agents

### Neo4j's Market Position

Neo4j leads the graph database market with a 44% share (company-reported). The company is actively pivoting toward AI: GraphRAG, agent memory, context graphs, Aura Agent. With $200+ million ARR (November 2024) and reported late-2024 IPO preparations (TechCrunch), the company holds a strong strategic position. The main challenge is competition from cloud-native graph services from hyperscalers (AWS Neptune, Azure Cosmos DB Gremlin, Google Cloud Spanner Graph).

## Links

- Company website: https://neo4j.com/
- AuraDB (cloud service): https://neo4j.com/cloud/aura-db/
- Pricing: https://neo4j.com/pricing/
- Documentation: https://neo4j.com/docs/
- GraphRAG: https://neo4j.com/use-cases/ai-systems/
- Context Graphs (create-context-graph): https://create-context-graph.dev/
- neo4j-agent-memory (GitHub): https://github.com/neo4j-labs/agent-memory
- NODES AI 2026 (Neo4j conference): https://neo4j.com/nodes-ai/
- Cypher Manual: https://neo4j.com/docs/cypher-manual/current/introduction/
- Neo4j Developer Blog: https://medium.com/neo4j
