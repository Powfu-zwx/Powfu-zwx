## Hi, I'm Powfu

AI undergrad in China, working on reinforcement learning and AI agents.
Most of what I build circles one question: how do you know an agent actually did what it says it did?

**Now:** building [proofline](https://github.com/Powfu-zwx/proofline), tamper-evident run bundles for LLM and agent executions. Record a run, verify it offline, diff two runs in CI.

### Agent evidence

| Project | What it does |
|:--|:--|
| **[proofline](https://github.com/Powfu-zwx/proofline)** | One JSON bundle per run: inputs, steps, outputs, costs, redactions and hashes. Verify, replay, sign with Ed25519, and diff runs semantically. `pip install proofline` |
| **[pi-proofline](https://github.com/Powfu-zwx/pi-proofline)** | Extension for the pi coding agent. Every prompt you give pi becomes a sealed, verifiable proofline bundle. `pi install npm:pi-proofline` |

### Research

| Project | What it does |
|:--|:--|
| **[CoopFlow](https://github.com/Powfu-zwx/CoopFlow)** | A small RL policy decides when a team of frozen local LLMs should execute, review, repair or stop, under a hard token budget. Scored by real execution on BIRD text-to-SQL, no LLM judges. |
| **[BreakRL](https://github.com/Powfu-zwx/BreakRL)** | Bilingual RL textbook, from bandits to GRPO. Each chapter removes one mechanism so you can watch the algorithm fail. [Read online](https://powfu-zwx.github.io/BreakRL/) |

### Skills for coding agents

| Project | What it does |
|:--|:--|
| **[ai-auto-research-skill](https://github.com/Powfu-zwx/ai-auto-research-skill)** | Autonomous research where every claim needs a bounded experiment and an independent evaluator behind it. |
| **[clean-first-engineering](https://github.com/Powfu-zwx/clean-first-engineering)** | Engineering discipline for agents, in English and Chinese: fix the root cause, keep one source of truth, leave no residue. |

### Apps

| Project | What it does |
|:--|:--|
| **[NegotiationForge](https://github.com/Powfu-zwx/NegotiationForge)** | Local-first negotiation simulator. The opponent has tracked hidden state, every turn is analysed, and you can fork any turn to replay a different strategy. |
| **[PolyAgent](https://github.com/Powfu-zwx/PolyAgent)** | Multi-agent workspace for grounded QA, document summaries, formal writing and step-by-step guidance (LangGraph + RAG). |

**Usually working in:** Python · PyTorch · TypeScript · FastAPI · Next.js

<sub>Ablation note: remove the unit tests and I become confident and wrong.</sub>
