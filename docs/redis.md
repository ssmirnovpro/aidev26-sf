# Redis

## About the Company

**Redis** develops the world's most popular in-memory database, which shares the company's name. Now they're expanding into AI, offering specialized tools to optimize LLM applications.

## Participation in AI Dev 26

**Role:** Speaker.

**Talk:** "Building SRE Agents with the Redis Context Engine"
**Speaker:** Aditi Gupta from Redis
**Time:** Day 1 (April 28, 2026), 2:30–3:10 PM (40 min)

Redis offers **LangCache**, a managed service for semantic caching of LLM responses, with the pitch: "Save up to 90% on LLM calls with Redis LangCache."

## Product

**Redis LangCache** — a managed service for semantic caching of LLM responses.

### Key Messages (from materials)

> "Save up to 90% on LLM calls with Redis LangCache"

> "Chatbots get asked the same questions over and over again, and agents use 4x more tokens than chat. Cache your most common responses and skip the extra calls and costs with LangCache."

> "The smarter way to scale LLMs without scaling costs."

### How Semantic Caching Works

Unlike exact caching, semantic caching captures the **meaning** of queries and responses through vector embeddings, matching on similarity rather than exact strings. For example:
- User A: "How do I reset my password?"
- User B: "I can't log in — how do I change my password?"
- The system recognizes these share the same intent and returns the cached response

### Results

- **Up to 73%** cost reduction in workloads with high query repetition
- **70%** cache hit rate in a production voice assistant for healthcare = 70% savings on LLM costs
- Cached responses return in **milliseconds** vs seconds for LLM inference
- On cache hits — **zero cost** for output tokens

### Key Features

- REST API for simple integration
- Fully-managed service (public preview as of September 4, 2025)
- Advanced optimizations for high-precision caching

### Recommended Use Cases

- Chatbots and support systems
- Knowledge base lookups
- RAG pipelines
- Any application with repetitive queries

### Prompt Caching vs Semantic Caching

Redis distinguishes between two approaches:
- **Prompt caching** (provider-level caching) — reduces input token costs
- **Semantic caching** (LangCache) — eliminates the LLM call on cache hits, avoiding output token regeneration costs (though embeddings/storage have their own costs)

## Funding and Financials

| Metric | Value |
|--------|-------|
| **Total Raised** | $355M across 8 rounds |
| **Investors** | TCV, Tiger Global, SoftBank, Bain Capital Ventures |
| **ARR (January 2026)** | $300M+ |
| **Status** | Private company |
| **Acquisitions** | Featureform (acquired October 9, 2025), Decodable (announced September 4, 2025), and others |

## Business Model

**Model: Open Source + Managed Cloud + Enterprise Licenses**

| Product | Type | Price |
|---------|------|-------|
| **Redis Open Source** | Open-source (RSALv2, SSPLv1, or AGPLv3) | Free |
| **Redis Cloud (Free)** | Managed cloud | $0 (limited) |
| **Redis Cloud (Essentials)** | Managed cloud | from $5/month |
| **Redis Cloud (Pro)** | Managed cloud | Usage-based |
| **Redis Enterprise** | On-prem/cloud | Enterprise pricing |
| **Redis LangCache** | Managed service | Public preview (Sept 2025) |

**Redis Cloud** — their main managed service:
- Pay-as-you-go based on consumption (memory, throughput)
- Multi-cloud support (AWS, GCP, Azure)
- Pricing calculator at redis.io/pricing/calculator

**Redis LangCache** — new managed service for AI:
- Public preview (announced September 4, 2025)
- REST API

**Revenue streams:**
- Redis Cloud subscriptions
- Redis Enterprise licenses
- LangCache (new AI product)
- Support and consulting

### What Customers Can Expect to Pay

**Redis Cloud pricing:**
- Free tier: limited capacity
- Essentials: from $5/month
- Pro: minimum $200/month (dedicated VPC, up to 99.999% SLA)
- Pay-as-you-go based on consumption (memory, throughput)

Use the pricing calculator at redis.io/pricing/calculator for specific estimates.

## Analysis

Redis LangCache tackles one of AI development's biggest pain points: the cost of LLM calls. With agents consuming 4x more tokens than traditional chat and the rise of agentic AI, optimizing LLM costs has become critical. Semantic caching offers one of the most effective ways to cut expenses without sacrificing quality.

## Links

- Redis LangCache: https://redis.io/langcache/
- Documentation: https://redis.io/docs/latest/develop/ai/langcache/
- Blog: https://redis.io/blog/llm-token-optimization-speed-up-apps/
- Prompt vs Semantic Caching: https://redis.io/blog/prompt-caching-vs-semantic-caching/
