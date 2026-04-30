# Vocal Bridge

## About the Company

**Vocal Bridge** is a platform for building voice interfaces (Voice UI) into AI applications. The company is a portfolio member of **AI Fund** — the venture studio founded by Andrew Ng that recently closed a $190M second fund (Fund II, May 2025) with backing from Sequoia Capital, NEA, Nikkei, AES, HP Inc., Mitsui & Co., Mitsubishi, QBE, and TELUS Global Ventures. AI Fund doesn't just write checks — they co-found companies with entrepreneurs, helping with team formation, market validation, and product development from day one.

Founder and CEO is **Ashwyn Sharma** (Founder-in-Residence at AI Fund).

The company's mission is to give developers the fastest path from idea to production-ready voice apps, embedding voice directly into products rather than limiting it to standard customer service scenarios.

## AI Dev 26 Participation

**Conference:** AI Dev 26 x SF — a technical conference for AI developers organized by DeepLearning.AI (Andrew Ng). April 28-29, 2026, Pier 48, San Francisco. 3000+ developers.

**Talk:** "Every App Needs a Voice UI. Here's How to Build It."
**Speaker:** Ashwyn Sharma, CEO & Founder, Vocal Bridge
**Time:** Day 2 (April 29, 2026), 1:50–2:10 PM (20 min)

Vocal Bridge was listed in the AI Startup Track — a section featuring startups solving real problems with AI.

In The Batch newsletter (DeepLearning.AI), Andrew Ng personally wrote about Vocal Bridge in the article "Building Voice-Enabled Apps is Easier Than You May Think," highlighting that adding voice UI to an existing app can take less than an hour.

## Product

### Vocal Bridge — Platform for Building Voice-First Apps

Vocal Bridge abstracts away the complex infrastructure of voice apps (WebRTC connections, speech-to-text pipelines, audio streaming), giving developers a simple API for creating and deploying voice agents.

### Architecture: Dual-Agent

A distinctive feature is a dual-agent architecture:

| Component | Purpose | Priority |
|-----------|---------|----------|
| **Foreground Agent** | Handles real-time conversation with users | Low latency |
| **Background Agent** | Manages complex agentic workflows, reasoning, guardrails, and tool calls | High intelligence |

This separation addresses the tradeoff between response speed and answer quality in voice AI systems.

### Tech Stack

- Built on **LiveKit** — an open-source WebRTC infrastructure for real-time communications
- WebRTC-based architecture for real-time audio streaming
- Sub-second latency, reliable tool calling, bidirectional communication between app and agent

### Key Features

- **Fast Start:** From zero to working voice agent in 5 minutes, no infrastructure management
- **Multi-Surface Deployment:** One agent deploys to web apps, mobile apps, and phone numbers from a single configuration
- **Bidirectional Communication:** Agent can update app UI, app sends events to agent for context maintenance
- **Multimodal:** Visual updates + voice input for richer UX than voice-only
- **Analytics:** Full transcripts, call recordings, usage analytics for debugging and improving agents

### SDKs and Developer Tools

| Tool | Description |
|------|-------------|
| **JavaScript/React SDK** | `npm install @vocalbridgeai/sdk` and `@vocalbridgeai/react` — hooks `useVocalBridge()`, `useTranscript()`, `useAgentActions()` |
| **CLI (Python)** | `pip install vocal-bridge` — manage agents, view logs, update prompts, debug |
| **REST API** | Programmatic agent management |
| **Flutter/Dart, Swift, Kotlin** | Mobile SDKs via WebRTC |
| **Claude Code Plugin** | GitHub: vocalbridgeai/vocal-bridge-claude-plugin — manage agents directly from Claude Code |

### Integrations

- **MCP servers** — connect to external tools via Model Context Protocol
- **Zapier** — access to 7000+ apps (calendars, CRM, databases)
- **HTTP API** — arbitrary integrations
- **"Bring Your Own Agent"** — connect existing chatbots and RAG systems

### Use Cases

- Language tutors
- Voice commerce / shopping assistants
- Voice-first gaming
- Accessibility
- Clinical trial matchers (healthcare)
- Portfolio advisors (finance)
- Voice layers on top of existing text agents

## Funding

| Round | Amount | Source | Note |
|-------|--------|--------|------|
| AI Fund incubation | Undisclosed | AI Fund (Andrew Ng) | Co-founded through venture studio |

- **Status:** AI Fund portfolio company (verified by The Batch). AI Fund's website has a stealth "Voice Apps" category; The Batch separately confirms Vocal Bridge as an AI Fund portfolio company
- **AI Fund** raised $190M in their second fund (Fund II, May 2025) from Sequoia Capital, NEA, Nikkei, AES, HP Inc., Mitsui & Co., Mitsubishi, QBE, and TELUS Global Ventures
- Specific investment amounts in Vocal Bridge aren't publicly disclosed. The AI Fund model involves deep participation — not just a check, but co-founding the company, forming the team, validating the market

## Business Model

**Model: Developer platform with free sign-up**

Vocal Bridge targets developers and companies looking to embed voice interfaces into their apps:

| Segment | Description |
|---------|-------------|
| **Solo Developers** | Fast prototyping, free account available |
| **Startups** | Embed Voice UI into product without hiring an infrastructure team |
| **Enterprise** | Scalable voice agents with analytics and compliance |

**Revenue Sources:**
- Usage-based pricing (likely by API volume/conversation minutes)
- Paid subscriptions
- Enterprise contracts

### What to Expect as a Customer

| Tier | Cost | What's Included |
|------|------|-----------------|
| **Free account** | $0 | Free sign-up available |
| **Paid plans** | Not publicly disclosed | Details available upon account creation |
| **Enterprise** | Custom | Custom terms |

Detailed pricing isn't publicly available on the website. To get pricing information, create a free account at vocalbridgeai.com.

**For context:** competitor Vapi charges $0.05/min for orchestration plus provider costs. Voice AI platforms often use per-minute pricing models.

## Analysis

### Market Position

Vocal Bridge occupies the **developer-first Voice UI platform** niche — a tool for developers, not a ready-made SaaS solution for contact centers. This sets the company apart from most Voice AI players.

### Market Context

| Metric | Value |
|--------|-------|
| Voice AI Agents Market CAGR | 34.8% (Market.us) |
| Voice AI Agents Forecast (2034) | $47.5 billion (Market.us) |

### Competitive Landscape

| Competitor | Focus | Key Details |
|-----------|-------|-------------|
| **Vapi** | Voice agent orchestration, provider-agnostic | $0.05/min pricing (verified) |
| **ElevenLabs** | Speech generation, voice cloning | 70+ languages, 10,000+ voices |
| **Retell AI** | Enterprise voice AI | Enterprise-focused platform |
| **LiveKit (direct)** | Open-source WebRTC infrastructure | Vocal Bridge is built on top of LiveKit, simplifying integration |
| **Voiceflow** | No-code/low-code voice bots | More visual approach, less developer-oriented |

### Vocal Bridge Advantages

- **Dual-agent architecture** — distinctive approach to addressing the latency vs intelligence tradeoff
- **AI Fund / Andrew Ng backing** — venture studio co-founding model with resources and expertise
- **Developer-first** — SDKs for JavaScript/React, Flutter/Dart, Swift, Kotlin (via WebRTC), plus CLI and Claude Code plugin
- **Fast time-to-market** — from idea to working prototype in minutes

### Risks

- Early stage, public funding not disclosed
- Highly competitive market (Vapi, ElevenLabs, Retell and others are well-funded)
- Dependency on LiveKit as underlying infrastructure
- Lack of public pricing may deter developers

## Links

- Website: https://vocalbridgeai.com
- Documentation: https://vocalbridgeai.com/docs/overview
- Developer Guide: https://vocalbridgeai.com/docs/developer-guide
- GitHub (Claude Plugin): https://github.com/vocalbridgeai/vocal-bridge-claude-plugin
- PyPI (CLI): https://pypi.org/project/vocal-bridge/
- AI Fund Portfolio: https://aifund.ai/portfolio/
- DeepLearning.AI The Batch: https://www.deeplearning.ai/the-batch/building-voice-enabled-apps-is-easier-than-you-may-think/
- YouTube (CEO interview): https://www.youtube.com/watch?v=kd1bUJu71Cs
- LinkedIn (Ashwyn Sharma): https://www.linkedin.com/in/ashwyn-sharma/
