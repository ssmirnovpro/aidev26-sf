# Reducto

## About the Company

**Reducto** (reducto.ai) builds AI-native document intelligence infrastructure that transforms unstructured documents into structured, reliable data for production AI pipelines. The San Francisco-based company has raised $108 million and processes over 2 billion pages to date.

**Founders:**
- **Adit Abraham** — Co-Founder & CEO (ex-Google Ads/Search PM, Co-Founder at Sidewalk Labs, MIT CS)
- **Raunak Chowdhuri** — Co-Founder & CTO (MIT CS, published CV papers with 100+ citations)

**Founded:** 2023 (Y Combinator Winter 2024)
**Headquarters:** 695 Minna Street, San Francisco, CA 94103

**The Founding Story:**
Reducto began as a classic pivot. Abraham and Chowdhuri initially built "long-term memory for language models" (winning Anthropic's hackathon), but it lacked commercial viability. The breakthrough came from a weekend "marketing stunt" — a simple Streamlit tool for document segmentation posted to YC's forum. The overwhelming response (immediate API requests and payment offers) revealed a genuine market need. Customers reported the same frustrations: traditional PDF processing tools failed on complex documents with tables, multi-column layouts, and figures. Reducto's competitive advantage emerged from treating PDFs as visual documents rather than purely text-based files.

## AI Dev 26 Participation

**Role:** Speaker and sponsor.

**Talk:** "Better Agents with Better Data: How Leading AI Teams Ingest Unstructured Data at Scale"
**Speaker:** Adit Abraham, Co-Founder & CEO
**Time:** Day 1 (April 28, 2026), Stage 2, 3:30–4:10 PM (40 min)
**Sponsorship:** 5th-6th tier sponsor

**Special Event:**
Reducto hosted a **Wine Night** on April 28, 2026 at JAX Vineyards, San Francisco — open to everyone (no conference ticket required) to meet the Reducto team and technical leaders.

## Product

**Reducto** provides an AI-powered document intelligence platform that converts unstructured documents (PDFs, images, spreadsheets, presentations) into structured, LLM-ready data. The platform processes documents through a multi-pass architecture combining computer vision, Vision-Language Models (VLMs), and proprietary Agentic OCR that detects and corrects errors in real-time.

### Core APIs

Reducto offers four main API endpoints:

| API | Purpose |
|-----|---------|
| **Parse** | Extracts all document content (text, tables, figures) with layout-aware chunking for RAG applications |
| **Split** | Automatically separates multi-document files into individual units using intelligent heuristics |
| **Extract** | Pulls specific fields into structured JSON with schema-level precision (invoices, forms, financial disclosures) |
| **Edit** | Fills PDF forms, tables, and checkboxes dynamically without templates; edits DOCX files programmatically |

### Key Features

**Technical Capabilities:**
- **Agentic OCR** — Proprietary framework that reviews and corrects parsing outputs in real-time for near-perfect results
- **Vision-first processing** — Treats documents as visual rather than text-based, capturing layout and formatting
- **Multi-pass architecture** — Combines OCR, multiple VLMs, and computer vision models
- **100+ language support** — Including mixed-language documents
- **Layout extraction** — Preserves bounding boxes and spatial relationships
- **Intelligent chunking** — Optimized for RAG and embedding models

**Supported File Types (30+ formats):**
- PDFs, images (scanned/faxed documents)
- Spreadsheets (Excel), presentations (PowerPoint)
- DOCX files
- Handwritten and low-quality scans

**Output Formats:**
- **JSON** — Structured data with text, tables, bounding boxes, confidence scores
- **Markdown** — Clean, LLM-ready text
- **HTML** — For table outputs
- **CSV** — Data export
- **Embeddings** — Optimized fields for vector database integration

Each chunk includes:
- "content" field with full text
- "embed" field with cleaned version optimized for embedding models
- Block information (type, bounding box coordinates)
- Metadata about document structure

**Chunking Options:**
- Configurable modes: variable, section, page, block, or page sections
- Adjustable chunk size and overlap for RAG tuning
- Variable mode recommended as default (most flexible for semantic relevance)

### Reducto Studio

**Reducto Studio** is a no-code browser interface for building, evaluating, and deploying document pipelines:
- Upload PDFs or images directly
- Review extracted data in real-time
- Export results as JSON or CSV
- Visual pipeline building with automatic schema generation
- Performance analytics with confidence scores
- Deploy button creates pipeline ID for production use
- Up to 5 Studio seats on Standard plan; unlimited on Growth plan

### Deployment Options

- **SaaS** — Cloud-hosted
- **Private VPC** — Customer-managed VPC deployment
- **On-premises/Air-gapped** — Fully isolated installations (critical for government/defense)

### Security & Compliance

- **SOC 2 Type II** certified
- **HIPAA compliant** (Business Associate Agreement available)
- Encryption in transit and at rest
- **Zero Data Retention** options (API data expires within 24 hours)
- Role-based access control
- SSO and SAML authentication

### Performance Metrics

- **99.24%** extraction accuracy on healthcare clinical workflows (real patient cases)
- **>99%** accuracy across 250+ million pages
- **Up to 20%** higher parsing accuracy vs. competitors on real-world documents
- **2+ billion pages** processed to date
- **Sub-minute SLAs** available
- **20+ point gains** vs. text-only parsers on table extraction

### Use Cases

**By Industry:**
- **Finance:** KYC onboarding, statement normalization, investor decks, SEC filings. Customer: LEA (serving $10B+ RIAs) cut manual data entry in half
- **Healthcare:** Prior authorization (95% completed within 1-minute SLA), health insurance claims (CMS-1500, UB-04, NCPDP), ICD/CPT extraction
- **Insurance:** Claims processing, underwriting. Customer: Elysian — 16x faster audit process
- **Legal:** Contract analysis, handwritten notes, redlines. Customer: Harvey — improved accuracy across complex legal documents
- **Government/Defense:** Scale AI Donovan platform, official orders, intelligence briefs (air-gapped deployment for classified data)

**By Technical Use Case:**
- RAG (Retrieval-Augmented Generation) pipelines
- Document search and knowledge bases
- Automated form filling
- Data extraction and structured output
- Compliance automation (Vanta)
- Agentic workflows

**Notable Customers:**
- **AI-Native Companies:** Scale AI, Harvey, Vanta, Medallion, Toast, Stack AI, Rogo, Mercor
- **Enterprise:** Fortune 10 company, Global Top 5 Hedge Fund
- **Specific Verticals:** Anterior (healthcare), Elysian (insurance), LEA (wealth management), Benchmark (VC/finance)

## Funding

| Round | Amount | Date | Lead Investor | Other Investors |
|-------|--------|------|---------------|-----------------|
| Seed | $8.4M | October 2024 | First Round Capital | Y Combinator |
| Series A | $24.5M | April 2025 | Benchmark | First Round Capital, BoxGroup, Y Combinator |
| **Series B** | **$75M** | **October 2025** | **Andreessen Horowitz (a16z)** | **Benchmark, First Round Capital, BoxGroup, Y Combinator** |

- **Total raised:** $108 million (3 rounds, 13 investors)
- **Investors:** a16z, Benchmark, First Round Capital, Y Combinator, BoxGroup, and others
- **Valuation:** Not publicly disclosed
- **Stage:** Series B company

### Growth Metrics

- Reached **$1M ARR** with just 4 employees
- **6x increase** in monthly processing volume in six months following Series A
- **2+ billion pages** processed to date
- Customer base ranges from leading AI teams to Fortune 10 companies and Global Top 5 Hedge Funds

## Business Model

**Model: SaaS with credit-based pricing**

Reducto operates on a credit-based consumption model where every document processing operation (parse, extract, split, edit) consumes credits based on operation type, configurations, and number of pages processed.

| Plan | Price | Best For | Key Features |
|------|-------|----------|--------------|
| **Standard** | Free tier: 15,000 credits; Pay-as-you-go: $0.015/credit (~$0.015/page) | Early-stage teams, startups | All APIs (Parse, Extract, Edit, Split), 30+ file types, up to 5 Studio seats |
| **Growth** | Custom pricing, volume discounts | Scaling teams | Includes Standard + Zero Data Retention, HIPAA BAA, premium rate limits, priority support, EU/AU endpoints, unlimited Studio seats |
| **Enterprise** | Custom pricing | Organizations with full control needs | Includes Growth + custom pipelines, on-premises/VPC deployment, dedicated on-call support, RBAC, SSO/SAML, custom SLAs |

**Additional Options:**
- AWS Marketplace purchasing available
- Enterprise can deploy on-premises or in customer VPC
- 99.9%+ uptime SLA for Enterprise

**Revenue Streams:**
- Usage-based credits (primary)
- Growth and Enterprise subscriptions
- Professional services and custom pipeline development

### What Customers Should Expect

| Scale | Estimated Cost |
|-------|---------------|
| Early prototyping | Free (15,000 credits) |
| Small-scale production (50K-100K pages/year) | $750-$1,500/year (on Standard pay-as-you-go) |
| Medium-scale (1M pages/year) | $15,000/year base + volume discounts (Growth tier) |
| Enterprise (3M+ pages/year) | Custom pricing (Enterprise tier) |

Example: Benchmark VC processes ~3.5M pages/year on Reducto.

Pricing scales down with volume. Growth and Enterprise tiers offer significant discounts for high-volume customers. Contact sales for specific quotes.

## Analysis

### Market Position

Reducto positions itself as an **"AI-native ingestion platform for high-volume enterprise pipelines"** targeting regulated industries where parsing accuracy directly impacts millions in liability and decisions. The company focuses on high-stakes verticals: finance, legal, healthcare, insurance, and government/defense.

**Key Differentiators:**
1. **Accuracy** — Up to 20% higher parsing accuracy vs. competitors; 99.24% extraction accuracy on healthcare workflows
2. **Technology** — Vision-first methodology + Agentic OCR (error detection and correction in real-time)
3. **Product breadth** — Only platform offering all four capabilities: Parse, Split, Extract, AND Edit
4. **Enterprise readiness** — Strongest deployment flexibility (SaaS, VPC, air-gapped), SOC 2 Type II, HIPAA, zero data retention
5. **Caring as competitive edge** — Founder philosophy emphasizing genuine obsession with accuracy and responsiveness

### Market Context

The global Document AI market is projected to grow from **$14.66B in 2025 to $27.62B by 2030** (13.5% CAGR). Alternative projections estimate **$14.16B in 2026 to $91.02B by 2034** (26.2% CAGR). The Intelligent Document Processing market stood at **$10.57B in 2025**.

### Competitive Landscape

**Main competitors:**
- **LlamaIndex/LlamaParse** — AI-driven, context-aware parsing
- **Unstructured** — Strong pipelines and wide connector support
- **Cloud providers:** Google Cloud Document AI (93% accuracy), AWS Textract, Azure Document Intelligence
- **Traditional vendors:** ABBYY (150+ pre-trained skills, 90% out-of-box accuracy)
- **Emerging:** Docling, Extend AI, Nanonets, Unstract

**Competitive advantages:**
- Highest documented accuracy (>99% across 250M+ pages)
- Unique Edit API for programmatic document filling
- Strongest deployment options (including air-gapped on-premises)
- Proven scale (2B+ pages processed)
- Speed to value (evaluation to production in ~6 weeks)

### Strengths

- Strong funding ($108M) and investor backing (a16z, Benchmark)
- Proven product-market fit ($1M ARR with 4 employees)
- Impressive customer roster (Fortune 10, Global Top 5 Hedge Fund, Scale AI, Harvey, Vanta)
- Technical moat: Agentic OCR, vision-first architecture
- Focus on regulated industries with high switching costs

### Risks

- Intense competition from well-funded startups and cloud giants
- Dependency on continued AI model improvements
- Enterprise sales cycles can be lengthy
- Market education required for vision-first vs. text-based approaches

## Links

- Website: https://reducto.ai
- Documentation: https://docs.reducto.ai/overview
- API Documentation: https://llms.reducto.ai/
- Pricing: https://reducto.ai/pricing
- Blog: https://reducto.ai/blog
- GitHub Benchmark: https://github.com/reductoai/benchmark
- Series B announcement: https://reducto.ai/blog/reducto-series-b-funding
- a16z investment announcement: https://a16z.com/announcement/investing-in-reducto/
- Customer case studies: https://reducto.ai/customers
- AI Dev 26 conference: https://ai-dev.deeplearning.ai/
