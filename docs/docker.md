# Docker

## About the Company

**Docker** created the container platform that's become the industry standard for packaging, deploying, and running applications. Now they're rethinking their role in the AI agent era by offering secure runtime environments for autonomous AI systems.

## Participation in AI Dev 26

**Role:** Speaker.

**Talk:** "Shipping Agents Safely: Boundaries That Actually Work"
**Speaker:** Tushar Jain from Docker
**Time:** Day 2 (April 29, 2026), Stage 1 — Software Development in the Age of GenAI, 10:30–11:10 AM (40 min).

Docker's key AI products include **Docker Sandboxes** (microVMs) and **MCP Gateway** — tools for safely running AI agents with complete kernel-level isolation.

## Product

**Docker for AI** — a suite of tools and services for secure AI agent execution.

### Key Message (from materials)

> "Run your first agent safely with Docker."

### Core Components

- **Docker Sandboxes** (microVM isolation available January 30, 2026; additional features announced March 31, 2026) — lightweight microVMs with dedicated Linux kernels for each agent. Unlike traditional containers, they provide complete isolation: no shared memory or processes with the host, and kernel exploits inside the sandbox can't affect the host
- **Docker MCP Gateway & Catalog** — secure access to 200+ real-world tools through the Model Context Protocol
- **Docker Desktop** — isolated local environment for testing agents
- **Docker Hardened Images** — production-ready secured images
- **Docker Scout** — vulnerability scanning for container images

### Why Regular Containers Aren't Enough

Docker containers isolate processes using Linux namespaces and cgroups — fine for trusted code, but not sufficient for running untrusted AI agent code. In November 2025, three high-severity runc container-breakout vulnerabilities were disclosed affecting Docker, Kubernetes, containerd, and CRI-O.

### Partnerships

- **E2B** — cloud sandboxes for safe execution of agent-generated code
- **NanoClaw** — partnership for enhanced AI agent security

## Funding and Financials

| Metric | Value |
|--------|-------|
| **Total Raised** | $163M (as of March 2022) |
| **Latest Round** | Series C, $105M (March 2022) |
| **Valuation** | $2.1B (Series C, March 2022) |
| **Revenue (2023)** | ~$165M (third-party estimate) |
| **Revenue (2021)** | ~$20M (third-party estimate) |
| **Status** | Private company |

## Business Model

**Model: Subscription (SaaS)**

Docker has shifted to a unified subscription model that includes their entire product portfolio:

| Tier | Price/mo (annual) | Price/mo (monthly) | Target Audience |
|------|-------------------|-------------------|----------------|
| **Personal** | $0 | $0 | Individual developers |
| **Pro** | $9 | $11 | Professional developers |
| **Team** | $15/user | $16/user | Teams |
| **Business** | $24/user | $24/user | Large companies |

**What's included:** Docker Desktop, Docker Hub, Docker Build Cloud, Docker Scout, Testcontainers Cloud

**Revenue Sources:**
- Subscription tiers: Pro ($9-$11/user/month), Team ($15-$16/user/month), Business ($24/user/month)
- Enterprise contracts for large organizations

**Pricing Changes:** In December 2024, the Pro tier increased from $5 to $9/month (+80%).

### What Customers Should Expect to Pay

| Scale | Typical Annual Spend |
|-------|---------------------|
| Small team (5–10 people, Pro) | $540–$1,320 |
| Medium team (20–50 people, Team) | $3,600–$9,600 |
| Enterprise (50–100 people, Business) | $14,400–$28,800 |
| Large Enterprise (100+ people) | $28,800+ |

## Analysis

Docker is transforming from a DevOps tool into a platform for safely running AI agents. With Gartner predicting 40% of enterprise apps will include task-specific AI agents by the end of 2026 (up from less than 5% in 2025), Docker Sandboxes with microVM architecture addresses the growing need for secure agent execution environments.

## Links

- Docker for AI: https://www.docker.com/solutions/docker-ai/
- Docker Sandboxes: https://www.docker.com/blog/docker-sandboxes-a-new-approach-for-coding-agent-safety/
- Secure AI Agents: https://www.docker.com/blog/secure-ai-agents-runtime-security/
