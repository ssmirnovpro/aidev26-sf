# AI Dev 26 — Conference Overview

**AI Dev 26 x SF** — the third conference for AI developers from DeepLearning.AI (Andrew Ng). San Francisco, April 28–29, 2026. 3,000+ attendees. The event has grown 7.5x in just 13 months (400 → 1,200 → 3,000+) and sold out.

Positioned as a technical conference for practitioners, unlike academic events (NeurIPS) or product launches (Google I/O). In reality, the logistics fell apart at scale: one warehouse for all sessions, a silent disco where half the headphones didn't work, spotty Wi-Fi (Andrew Ng couldn't fully demo Codream during his keynote, constantly hedging on whether the internet would cooperate), and 40–60 minute coffee lines.

---

## Key Takeaways

**Andrew Ng (keynote):** Small teams of generalists managing AI agents. Frontier teams are moving toward 100% AI-generated code. Unveiled **Codream** — a collaborative AI learning platform.

> "If I have to review the code, I become the bottleneck"

**Marc Brooker (AWS):** Reducing errors matters more than pushing the frontier. Specifications give AI models better results. Spec-driven development.

> "The opportunity for agents is limited by the defect rate"

**Harrison Chase (LangChain):** "Observability flywheel" — how observability creates a continuous improvement loop for AI agents.

**Anush Elangovan (AMD):** "Speed is the moat" — velocity as competitive advantage.

**"Future of Software Development" panel:** Replit's Michele Catasta rated the future 10/10 for excitement, Oracle's Richmond Alake gave it 7/10. Moderated by Marina Mogilko.

---

## Six Conference Tracks

1. **Software Development in the GenAI Age** — transformation of software development
2. **Agentic AI** — autonomous agents, multi-step task execution
3. **Memory and Context Engineering** — context, memory, and tools for LLMs
4. **Reliability, Observability & Security** — production systems, tracing, fault tolerance
5. **Building and Scaling AI Startups** — startup track
6. **Enterprise Deployment & Real-World AI Systems** — AI at scale

---

## Companies with Detailed Profiles

We have detailed profiles (product, funding, business model, customer pricing) for the following conference participants:

### AI Platforms and Models

| Company | Website | Profile | What They Do |
|---------|---------|---------|--------------|
| **Codream** | [codream.ai](https://codream.ai) | [codream](docs/codream.md) | Collaborative AI learning platform (Andrew Ng) |
| **LangChain** | [langchain.com](https://langchain.com) | [langchain](docs/langchain.md) | Infrastructure for AI agents, LangSmith, LangGraph |
| **AI21 Labs** | [ai21.com](https://www.ai21.com) | [ai21-labs](docs/ai21-labs.md) | Enterprise LLM (Jamba), 256K context |
| **LandingAI** | [landing.ai](https://landing.ai) | [landingai](docs/landingai.md) | Agentic Document Extraction (Andrew Ng) |
| **Replit** | [replit.com](https://replit.com) | [replit](docs/replit.md) | AI app creation, $9B valuation, 54x ARR growth |

### Infrastructure and DevTools

| Company | Website | Profile | What They Do |
|---------|---------|---------|--------------|
| **Temporal** | [temporal.io](https://temporal.io) | [temporal](docs/temporal.md) | Durable Execution, $5B valuation, OpenAI integration |
| **Docker** | [docker.com](https://www.docker.com) | [docker](docs/docker.md) | Sandboxes (microVM) for safe agent execution |
| **Datadog** | [datadoghq.com](https://www.datadoghq.com) | [datadog](docs/datadog.md) | LLM Observability, AI agent monitoring |
| **Sonar** | [sonarsource.com](https://www.sonarsource.com) | [sonar](docs/sonar.md) | Agentic Analysis — AI code verification in seconds |
| **CodeRabbit** | [coderabbit.ai](https://coderabbit.ai) | [coderabbit](docs/coderabbit.md) | AI code review, $88M raised, 2M+ repos |
| **Redis** | [redis.io](https://redis.io) | [redis](docs/redis.md) | LangCache — semantic LLM caching |
| **Databricks** | [databricks.com](https://www.databricks.com) | [databricks](docs/databricks.md) | Data Intelligence Platform, $134B valuation |
| **Elastic** | [elastic.co](https://www.elastic.co) | [elastic](docs/elastic.md) | Elasticsearch Labs — GenAI, embedding, reranking |
| **Box** | [box.com](https://www.box.com) | [box](docs/box.md) | Cloud content management, file systems for agents |
| **Reducto** | [reducto.ai](https://reducto.ai) | [reducto](docs/reducto.md) | AI document intelligence, $108M raised, 2B+ pages processed |

### Data and Databases

| Company | Website | Profile | What They Do |
|---------|---------|---------|--------------|
| **Neo4j** | [neo4j.com](https://neo4j.com) | [neo4j](docs/neo4j.md) | Graph database, context graphs for agents |
| **Actian** | [actian.com](https://www.actian.com) | [actian](docs/actian.md) | VectorAI DB, on-premises vector search |

### AI Startups

| Company | Website | Profile | What They Do |
|---------|---------|---------|--------------|
| **BAND** | [band.ai](https://www.band.ai) | [band](docs/band.md) | Agentic Mesh — "Slack for agents" with governance |
| **Unblocked** | [getunblocked.com](https://getunblocked.com) | [unblocked](docs/unblocked.md) | Context Engine: -42% tokens, +27% speed |
| **Spice AI** | [spice.ai](https://spice.ai) | [spice-ai](docs/spice-ai.md) | Open-source Data & AI Runtime (Rust) |
| **Apify** | [apify.com](https://apify.com) | [apify](docs/apify.md) | Web scraping, 26K+ tools, MCP |
| **Prolific** | [prolific.com](https://www.prolific.com) | [prolific](docs/prolific.md) | Human-in-the-loop data for SFT/DPO |
| **Anchor Browser** | [anchorbrowser.io](https://www.anchorbrowser.io) | [anchor-browser](docs/anchor-browser.md) | Secure browser identity for AI agents |
| **HoundDog.ai** | [hounddog.ai](https://hounddog.ai) | [hounddog](docs/hounddog.md) | AI code security, PII code scanning |
| **Vocal Bridge** | [vocalbridge.ai](https://vocalbridge.ai) | [vocal-bridge](docs/vocal-bridge.md) | Voice UI for AI applications (AI Fund) |
| **OnMemory** | [onmemory.ai](https://onmemory.ai) | [onmemory](docs/onmemory.md) | Deterministic memory for AI agents |

---

## Key Themes and Insights

**Agentic AI is the central narrative.** The shift from "AI-assisted coding" to "AI-agent-driven development" is real. 79% of organizations have adopted AI agents, but only 11% have deployed them to production — a 68-point deployment gap that creates a massive market opportunity.

**Context engineering is emerging as its own discipline.** It got its own track at the conference. Companies are building entire businesses around delivering the right context to LLMs (Unblocked, Spice AI, OnMemory).

**MCP is becoming the standard.** Model Context Protocol came up in presentations from Docker, Apify, Spice AI, Unblocked, SonarQube, and Anchor Browser — it's becoming the de facto standard for how agents integrate with tools.

**Reliability is now a first-class citizen.** SonarQube Agentic Analysis, Datadog LLM Observability, Temporal Durable Execution, Redis LangCache — reliability and observability for AI agents aren't afterthoughts anymore.

**Security for agents is forming its own market.** Docker Sandboxes, BAND Control Plane, Anchor Browser, HoundDog.ai — AI agent security is emerging as a standalone category.

---

## All Conference Participants

50+ companies were sponsors or exhibitors.

Companies without detailed profiles: AMD, Oracle, Google DeepMind, AWS, Arm, Andela, Bain & Company, D. E. Shaw & Co, Snowflake, Flower Labs, Turing, Chroma, Reducto, JetBrains, Cursor, Qdrant, TRAE, CircleCI, SambaNova, CrewAI, Tavily, CopilotKit, MarcoPolo, Agentic Fabriq, Veris AI, Zencoder, Giskard, Oumi, Okahu AI, Refold AI, Vectara, Cline, OpenAI, LlamaIndex.

---

## What It Was Actually Like

Public feedback was overwhelmingly positive. The reality on the ground:

- **One warehouse for everything** — 4 parallel panels in a single space, silent disco with half the headphones broken
- **No internet** — exhibitors couldn't demo their products, Andrew Ng couldn't show Codream during his keynote
- **40–60 minute coffee lines**
- **No materials** — slides weren't distributed, speakers had to ask the audience to photograph screens, but someone was always standing in front
- **Zero discussion** on Hacker News and Reddit — unusual for a conference this size
