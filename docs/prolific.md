# Prolific

## About the Company

**Prolific** bills itself as "The Human Intelligence Layer for AI." The platform connects AI developers with verified human participants who provide high-quality data for training, testing, and improving AI models. Verified clients include Google, Stanford University, AI2 (Allen Institute for AI), Hugging Face, NIH, CMU, Oxford, King's College London, and the European Commission.

## Participation in AI Dev 26

**Note:** Prolific does not appear in the AI Dev 26 conference schedule. Conference presence not verified in available sources.

## Funding

| Round | Amount | Date | Lead/Co-Lead Investors | Other Investors |
|-------|-------|------|----------------------|-----------------|
| Seed | — | Dec 4, 2019 | Pioneer Fund, Y Combinator | 10x Value Partners, AltaIR Capital |
| Series A | £25M (~$32M) | July 2023 | Partech, Oxford Science Enterprises (co-lead) | — |

- **Total raised**: ~$33.4M–$33.5M
- **Founded**: 2014, London
- **Co-founders**: Phelim Bradley (CEO), Ekaterina Damer
- **Employees**: 51–200 (as of July 2025)

## Business Model

**Model: Self-serve marketplace + Enterprise contracts**

Prolific operates a two-sided marketplace connecting researchers and AI developers with verified human participants.

**How it works for clients:**
1. Create a study through the web interface or API
2. Set three parameters: participant criteria (300+ demographic and skill filters), sample size, and payment per participant
3. Receive data from verified humans

**Revenue streams:**
- Platform commission on each study (academic researchers)
- Contracts with AI labs (enterprise)
- Self-serve B2B for AI companies
- Enterprise market research projects

**Network effects:** A more diverse participant pool attracts more researchers → more studies keep participants engaged

**Scale:** 200,000+ verified participants, over a million people on the waitlist

### What Clients Should Expect

| Component | Cost |
|-----------|----------|
| Minimum participant payment | $8/hour |
| Recommended payment | $12/hour |
| Platform fee (corporate) | 42.8% on top of payment |
| Platform fee (academic) | 33.3% on top of payment |

**Example calculation (corporate):** $70 to participants → $100 total (with fees).

No subscription required — it's pay-as-you-go. Prolific provides a cost calculator on their pricing page for specific study estimates.

## Product

**Prolific** provides Human-in-the-Loop (HITL) data for AI model post-training, including training/fine-tuning, alignment/preference data, evaluation, RLHF, and safety testing.

### HITL Post-Training Pipeline: SFT + DPO

The pipeline consists of three stages:

1. **Pre-training** — the model learns from large text corpora (foundational stage)
2. **Supervised Fine-Tuning (SFT)** — adapting the pre-trained model through instructions and demonstrations. Prolific participates in **Instruction Data Collection**: participants write high-quality "instruction-response" pairs (prompt + ideal response demonstrations)
3. **Direct Preference Optimization (DPO)** — optimizing the model through preference pairs. Prolific participates in **Preference Data Collection**: participants compare or rank model outputs (chosen vs rejected response pairs)

### Result

A post-trained model that's:
- More helpful
- Safer
- Aligned with human preferences

### Key Platform Capabilities

- Access to 200,000+ verified participants
- API-first approach
- RLHF (Reinforcement Learning from Human Feedback)
- Model Evaluation
- Safety Testing
- UX Research

## Analysis

Prolific occupies a unique niche at the intersection of human data and AI alignment. The global data collection and labeling market was $3.77B in 2024, expected to reach $4.89B in 2025, and projected to reach $17.10B by 2030 (Grand View Research). As attention on RLHF, DPO, and alignment grows, demand for high-quality human data continues to climb.

## Links

- Website: https://www.prolific.com
- RLHF: https://www.prolific.com/reinforcement-learning-from-human-feedback
- AI Alignment: https://www.prolific.com/alignment
