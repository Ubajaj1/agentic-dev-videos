# Agentic Development Videos

A curated list of the most useful videos for understanding agentic AI development, from fundamentals to production patterns.

**Last updated:** May 2026

> Know a great video that's missing? Open a PR or [suggest one via Issues](../../issues/new?template=suggest-video.md).

---

## Contents

- [Foundations](#foundations)
- [Tool Use & Function Calling](#tool-use--function-calling)
- [Multi-Agent Systems](#multi-agent-systems)
- [RAG & Retrieval](#rag--retrieval)
- [Production & Deployment](#production--deployment)
- [Frameworks & SDKs](#frameworks--sdks)

---

## Foundations

| Video | Why Watch |
|-------|-----------|
| [What's next for AI agentic workflows ft. Andrew Ng](https://www.youtube.com/watch?v=sal78ACtGTc) | The talk that kicked off the "agentic AI" wave. Andrew Ng lays out why agentic workflows will drive massive AI progress. |
| [Andrew Ng on AI Agentic Workflows and Their Potential](https://www.youtube.com/watch?v=q1XFm21I-VQ) | Deep-dive into the four agentic design patterns (reflection, tool use, planning, multi-agent) that became the canonical framework. |
| [Andrew Ng: The Rise of AI Agents - BUILD 2024 Keynote](https://www.youtube.com/watch?v=KrRD7r7y7NY) | Connects agentic reasoning to real enterprise use cases, with concrete examples of how agents outperform zero-shot prompting. |
| [Andrew Ng: State of AI Agents - LangChain Interrupt](https://www.youtube.com/watch?v=4pYzYmSdSH4) | Most recent state-of-the-field address on agents, covering where the ecosystem is headed. |
| [Build an AI Agent From Scratch in Python - freeCodeCamp](https://www.youtube.com/watch?v=bTMPwUgLZf0) | Hands-on beginner tutorial that builds an agent from raw Python, so you understand the loop (perceive, reason, act) before reaching for frameworks. |

## Tool Use & Function Calling

| Video | Why Watch |
|-------|-----------|
| [Function Calling is All You Need - Ilan Bigio, OpenAI](https://www.youtube.com/watch?v=KUEmEb71vzQ) | An OpenAI engineer walks through function calling end-to-end, covering the Agents SDK, Realtime API, and o1/o3 models. The definitive first-party workshop. |
| [Build Hour: Agentic Tool Calling - OpenAI](https://www.youtube.com/watch?v=7E-qdsVEoB8) | Official OpenAI session focused on agentic tool calling patterns with live coding. |
| [Tips for Building AI Agents - Anthropic](https://www.youtube.com/watch?v=LP5OCa20Zpg) | Anthropic engineers share hard-won lessons on tool design, error handling, and agent reliability. Practical wisdom from the team that built Claude's tool use. |
| [Building Agents with MCP - Mahesh Murag, Anthropic](https://www.youtube.com/watch?v=kQmXtrmQ5Zg) | The definitive MCP workshop from its creator at Anthropic, showing how to build standardized tool servers that any agent can connect to. |
| [Model Context Protocol (MCP), Clearly Explained + Live Demo](https://www.youtube.com/watch?v=YMUKo0akXtU) | Concise explainer with working code that demystifies MCP for developers who want to understand the protocol without reading the spec. |

## Multi-Agent Systems

| Video | Why Watch |
|-------|-----------|
| [Harrison Chase - Agents Masterclass (LLM Bootcamp)](https://www.youtube.com/watch?v=DWUdGhRrv2c) | The LangChain founder's comprehensive masterclass covering single-agent to multi-agent patterns, with LangGraph as the orchestration layer. |
| [Building Agentic and Multi-Agent Systems with LangGraph](https://www.youtube.com/watch?v=95XrWA6-UFM) | Official LangGraph tutorial on building multi-agent systems with state graphs, handoffs, and shared memory. |
| [Multi-Agent Systems in OpenAI's Agents SDK](https://www.youtube.com/watch?v=2MYzc79Lj04) | Walks through OpenAI's agents-as-tools pattern for orchestrator-subagent architectures, with full working code. |
| [What's next for AI agents ft. Harrison Chase - Sequoia](https://www.youtube.com/watch?v=pBBe1pk8hf4) | Harrison Chase explains why multi-agent orchestration matters and where LangGraph fits in the stack. |
| [Claude Agent SDK Full Workshop - Thariq Shihipar, Anthropic](https://www.youtube.com/watch?v=TqC1qOfiVcQ) | Full hands-on workshop on Anthropic's Agent SDK covering multi-agent coordination, tool use, and building production workflows. |

## RAG & Retrieval

| Video | Why Watch |
|-------|-----------|
| [Agentic RAG Explained - IBM Technology](https://www.youtube.com/watch?v=MYPDsV_825U) | Clear, concept-first explanation of how agentic RAG differs from vanilla RAG. The agent decides when to retrieve, what to retrieve, and whether to re-retrieve. |
| [The Future of RAG is Agentic - Sam Witteveen](https://www.youtube.com/watch?v=_R-ff4ZMLC8) | Practical walkthrough of agentic RAG strategies (query decomposition, routing, self-reflection on retrieval quality) with code. |
| [Agentic RAG Tutorial - DataTalks.Club](https://www.youtube.com/watch?v=GH3lrOsU3AU) | Hands-on tutorial combining function calling with RAG, from the creator of the popular LLM Zoomcamp course. |
| [Agentic RAG for SMARTER AI Agents - Rabbitmetrics](https://www.youtube.com/watch?v=DSvU92YhQ0w) | Breaks down how agentic RAG combines vector databases, tool use, and agent loops into a single system, with a working demo. |

## Production & Deployment

| Video | Why Watch |
|-------|-----------|
| [3 Ingredients for Reliable Enterprise Agents - Harrison Chase](https://www.youtube.com/watch?v=kTnfJszFxCg) | Distills enterprise agent reliability into three concrete principles. Essential for moving agents beyond demos. |
| [Anthropic: How to Build Production AI Agents in 30 Minutes](https://www.youtube.com/watch?v=X0ASQC5AfpI) | Covers Anthropic's production agent patterns: error recovery, human-in-the-loop, guardrails, and deployment strategies. |
| [How to Solve the #1 Blocker for Agents in Production - LangChain](https://www.youtube.com/watch?v=DsjkO2vB618) | Addresses the gap between demo and production: evaluation, observability, and failure modes that kill agent deployments. |
| [Evaluating Agents and Assistants - Arize AI](https://www.youtube.com/watch?v=6uXWhmDRcMc) | Deep dive into evaluation frameworks for agents: metrics, tracing, and how to measure whether your agent is actually working. |
| [Software Architecture Patterns for AI Agents - ByteByteGo](https://www.youtube.com/watch?v=kMH71AVZEc0) | System design perspective on agent architectures, covering key patterns for reliable, scalable agent systems. |

## Frameworks & SDKs

| Video | Why Watch |
|-------|-----------|
| [Agents SDK from OpenAI - Full Tutorial - Sam Witteveen](https://www.youtube.com/watch?v=35nxORG1mtg) | Comprehensive walkthrough of OpenAI's Agents SDK covering agents, handoffs, guardrails, and tracing. |
| [Interrupt 2025 Keynote - Harrison Chase, LangChain](https://www.youtube.com/watch?v=DrygcOI-kG8) | Harrison Chase lays out the LangGraph vision: state machines, persistence, human-in-the-loop, and the full LangChain agent stack. |
| [Building the Future of Agents with Claude - Anthropic](https://www.youtube.com/watch?v=XuvKFsktX0Q) | Anthropic leadership discusses their agent philosophy, Claude's tool use architecture, and how they see the agent ecosystem evolving. |
| [LangGraph vs CrewAI vs AutoGen - Maya Akim](https://www.youtube.com/watch?v=8lsJ7zLa2Pk) | Balanced comparison of the three major frameworks with code examples for each. Helps you pick the right tool for your use case. |
| [Context Engineering for Long-Horizon Agents - Harrison Chase](https://www.youtube.com/watch?v=vtugjs2chdA) | Explores context engineering as the key unlock for long-running agents: memory management, context windows, and state over extended tasks. |

---

## How to Use This List

Each video includes a short "Why Watch" note explaining what makes it worth your time. Videos are grouped by topic so you can jump to what's relevant.

## Contributing

Found a video that changed how you think about agentic development? PRs are welcome.

1. Add the video under the right section
2. Include a one-liner on why it's worth watching
3. Keep it concise: the curation is the value

## License

[MIT](LICENSE)
