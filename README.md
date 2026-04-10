# AI Synthesised Perspectives

A curated list of projects involving multi-agent simulations for exploring diverse perspectives on policy topics, including simulated fora, conferences, debates, and deliberative processes.

*Last updated: 2026-04-05*

---

## Table of Contents

- [Simulated Events & Fora](#simulated-events--fora)
- [Multi-Agent Deliberation](#multi-agent-deliberation)
- [LLM Councils](#llm-councils)
- [Negotiation & Benchmarks](#negotiation--benchmarks)

---

# Simulated Events & Fora

Projects simulating conferences, panels, symposia, and other deliberative events using AI agents.

## [Claude AI Conference](https://github.com/danielrosehill/Claude-AI-Conference)

![GitHub stars](https://img.shields.io/github/stars/danielrosehill/Claude-AI-Conference?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/danielrosehill/Claude-AI-Conference)

AI experiment: panel + TTS, mini conference/symposium

**Author:** [danielrosehill](https://github.com/danielrosehill)

---

# Multi-Agent Deliberation

Think tanks, debate simulations, and multi-agent systems for exploring diverse policy perspectives.

## [Claude Think Tank](https://github.com/danielrosehill/Claude-Think-Tank)

![GitHub stars](https://img.shields.io/github/stars/danielrosehill/Claude-Think-Tank?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/danielrosehill/Claude-Think-Tank)

Model repository for a think tank composed of AI agents (with Claude Code providing the framework) focused on assisting a user with research and ideating policy proposals

**Language:** Shell

**Author:** [danielrosehill](https://github.com/danielrosehill)

---

## [LLM-Deliberation](https://github.com/S-Abdelnabi/LLM-Deliberation)

![GitHub stars](https://img.shields.io/github/stars/S-Abdelnabi/LLM-Deliberation?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/S-Abdelnabi/LLM-Deliberation)

[NeurIPS 2024] Cooperation, Competition, and Maliciousness: LLM-Stakeholders Interactive Negotiation. Multi-agent negotiation framework with cooperative and adversarial dynamics.

*Models multi-stakeholder negotiation dynamics with LLM agents — directly applicable to diplomatic and policy negotiation simulation.*

**Language:** Jupyter Notebook

**Author:** [S-Abdelnabi](https://github.com/S-Abdelnabi)

---

## [Plurals](https://github.com/josh-ashkinaze/plurals)

![GitHub stars](https://img.shields.io/github/stars/josh-ashkinaze/plurals?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/josh-ashkinaze/plurals)

[CHI 2025 Honorable Mention] A System for Guiding LLMs Via Simulated Social Ensembles. Creates nationally representative virtual populations using government datasets (ANES) with deliberative democracy templates.

*Directly creates simulated deliberative bodies with demographically representative AI personas. Applicable to virtual town halls, policy deliberation, and simulated public opinion.*

**Language:** Python

**Author:** [josh-ashkinaze](https://github.com/josh-ashkinaze)

---

# LLM Councils

Multi-model systems that query multiple LLMs and synthesize their responses through peer review and deliberation.

> **See also:** [LLM-Council-Projects](https://github.com/danielrosehill/LLM-Council-Projects) — a dedicated index covering the broader LLM Council ecosystem (derivatives, IDE integrations, local-first, SDK, plugins, and domain-specific applications).

## [LLM Council](https://github.com/karpathy/llm-council)

![GitHub stars](https://img.shields.io/github/stars/karpathy/llm-council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/karpathy/llm-council)

Local web app that sends queries to multiple LLMs simultaneously, has them anonymously peer-review each other's responses, then a "chairman" model synthesizes a final answer. Uses OpenRouter for multi-provider access.

**Language:** Python

**Author:** [karpathy](https://github.com/karpathy) (Andrej Karpathy)

---

## [LLM Council Template](https://github.com/danielrosehill/LLM-Council-Template)

![GitHub stars](https://img.shields.io/github/stars/danielrosehill/LLM-Council-Template?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/danielrosehill/LLM-Council-Template)

Template based on Karpathy's llm-council, modified to use a single LLM with six personality-based system prompts (Logical Thinker, Creative Solver, Pessimist, Optimist, Connector, Unconventional) instead of multiple providers. Includes digest outputs: Typst PDF reports and personal podcast generation via Edge TTS.

**Language:** Python

*Author note: Daniel's derivative of the original llm-council concept, focused on personality-based deliberation rather than multi-provider comparison.*

---

## [LLM Council Plus](https://github.com/DmitryBMsk/llm-council-plus)

![GitHub stars](https://img.shields.io/github/stars/DmitryBMsk/llm-council-plus?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/DmitryBMsk/llm-council-plus)

Production-grade extension of Karpathy's llm-council. Adds multi-user JWT auth, web search integration, file upload (PDF/images/markdown), flexible storage (JSON/PostgreSQL/MySQL), Ollama support, and containerized deployment.

**Language:** Python

**Author:** [DmitryBMsk](https://github.com/DmitryBMsk)

---

## [Council of High Intelligence](https://github.com/0xNyk/council-of-high-intelligence)

![GitHub stars](https://img.shields.io/github/stars/0xNyk/council-of-high-intelligence?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/0xNyk/council-of-high-intelligence)

Claude Code `/council` skill that routes queries to 18 AI personas (Aristotle, Feynman, Kahneman, Sun Tzu, etc.) across multiple LLM providers. Three deliberation modes: full (3-round with cross-examination), quick (2-round), and duo (dialectic). Enforces dissent quotas and novelty gates.

**Language:** Shell

**Author:** [0xNyk](https://github.com/0xNyk)

---

## [The LLM Council](https://github.com/sherifkozman/the-llm-council)

![GitHub stars](https://img.shields.io/github/stars/sherifkozman/the-llm-council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/sherifkozman/the-llm-council)

Multi-model orchestration framework that runs adversarial council workflows. Multiple LLMs debate and critique each other's outputs, then synthesize a final answer. Supports adversarial debate rounds, cross-validation, and JSON schema enforcement.

**Language:** Python

**Author:** [sherifkozman](https://github.com/sherifkozman)

---

## [LLM Council (amiable-dev)](https://github.com/amiable-dev/llm-council)

![GitHub stars](https://img.shields.io/github/stars/amiable-dev/llm-council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/amiable-dev/llm-council)

Multi-LLM deliberation system with three-stage pipeline: parallel query to multiple LLMs, anonymized peer review and ranking, then chairman synthesis. Available as Python library, MCP server, or HTTP API.

**Language:** Python

**Author:** [amiable-dev](https://github.com/amiable-dev)

---

## [MultiMind-AI](https://github.com/JitseLambrichts/MultiMind-AI)

![GitHub stars](https://img.shields.io/github/stars/JitseLambrichts/MultiMind-AI?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/JitseLambrichts/MultiMind-AI)

Local-first web UI for multi-agent reasoning on small local models. Three architectures: sequential Thinking Pipeline (Plan/Execute/Critique), parallel Agent Council (expert advisors + lead judge), and hierarchical Organisation Mode (CEO → departments → employees → synthesis). Zero-config auto-discovery of Ollama/LM Studio.

**Language:** Python

**Author:** [JitseLambrichts](https://github.com/JitseLambrichts)

---

## [LLM Council Skill](https://github.com/gcpdev/llm-council-skill)

![GitHub stars](https://img.shields.io/github/stars/gcpdev/llm-council-skill?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/gcpdev/llm-council-skill)

Claude Code skill that queries ChatGPT and Gemini for their perspectives on a question, then synthesizes a combined implementation plan with attribution.

**Language:** Python

**Author:** [gcpdev](https://github.com/gcpdev)

---

## [Coven](https://github.com/pierluigi-failla/coven)

![GitHub stars](https://img.shields.io/github/stars/pierluigi-failla/coven?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/pierluigi-failla/coven)

On-premise/offline multi-LLM council interface. Multiple LLMs deliberate on a query in parallel, with optional peer critique, then a "Chairman" model synthesizes a final response. Includes RAG, tool calling, multimodal vision, and X-Ray deliberation view.

**Language:** Python

**Author:** [pierluigi-failla](https://github.com/pierluigi-failla)

---

## [LLM Council Skill (shuntacurosu)](https://github.com/shuntacurosu/llm_council_skill)

![GitHub stars](https://img.shields.io/github/stars/shuntacurosu/llm_council_skill?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/shuntacurosu/llm_council_skill)

Claude Skill that orchestrates multiple LLMs as a council through a 3-stage process: independent responses, anonymous peer review/ranking, then chairman synthesis. Uses git worktrees for member work and includes a real-time TUI dashboard.

**Language:** Python

**Author:** [shuntacurosu](https://github.com/shuntacurosu)

---

## [Yoetz](https://github.com/avivsinai/yoetz)

![GitHub stars](https://img.shields.io/github/stars/avivsinai/yoetz?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/avivsinai/yoetz)

Fast CLI-first LLM council + code bundler + multimodal gateway written in Rust. Multi-model consensus with configurable voting, code review, and image/video generation.

**Language:** Rust

**Author:** [avivsinai](https://github.com/avivsinai)

---

## [Star Chamber](https://github.com/peteski22/star-chamber)

![GitHub stars](https://img.shields.io/github/stars/peteski22/star-chamber?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/peteski22/star-chamber)

Multi-LLM council protocol SDK. Fan out code reviews and design questions to multiple providers, then classify findings by consensus. Pip-installable library with CLI.

**Language:** Python

**Author:** [peteski22](https://github.com/peteski22)

---

## [Roundtable](https://github.com/brandongalang/roundtable)

![GitHub stars](https://img.shields.io/github/stars/brandongalang/roundtable?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/brandongalang/roundtable)

Multi-model chat app where multiple AI models respond in parallel, then a synthesizer/judge model does comparative analysis and composes a final response. Supports custom personas (skeptic, advocate, expert) and token/cost analytics.

**Language:** TypeScript

**Author:** [brandongalang](https://github.com/brandongalang)

---

## [LLM Council (rachittshah)](https://github.com/rachittshah/llmcouncil)

![GitHub stars](https://img.shields.io/github/stars/rachittshah/llmcouncil?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/rachittshah/llmcouncil)

Multi-LLM deliberation council with 6 structured protocols: vote, debate, synthesize, critique, red team, and model-as-verifier. Ships as MCP server and Claude Code skill. Features adaptive stopping for debates.

**Language:** TypeScript

**Author:** [rachittshah](https://github.com/rachittshah)

---

## [Architect-Council](https://github.com/JustinNarracott/Architect-Council)

![GitHub stars](https://img.shields.io/github/stars/JustinNarracott/Architect-Council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/JustinNarracott/Architect-Council)

AI-powered Design Authority — 5 specialist agents evaluate architecture decisions and deliver structured rulings in under 60 seconds.

**Language:** Python

**Author:** [JustinNarracott](https://github.com/JustinNarracott)

---

## [autocouncil](https://github.com/shadmau/autocouncil)

![GitHub stars](https://img.shields.io/github/stars/shadmau/autocouncil?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/shadmau/autocouncil)

Self-improvement loops for OpenClaw agents via multi-model LLM council.

**Language:** Python

**Author:** [shadmau](https://github.com/shadmau)

---

## [claude-council](https://github.com/hex/claude-council)

![GitHub stars](https://img.shields.io/github/stars/hex/claude-council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/hex/claude-council)

Claude Code plugin to consult multiple AI coding agents (Gemini, OpenAI, Grok) for diverse perspectives.

**Language:** Shell

**Author:** [hex](https://github.com/hex)

---

## [Crew-Council](https://github.com/Josephcc2/Crew-Council)

![GitHub stars](https://img.shields.io/github/stars/Josephcc2/Crew-Council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/Josephcc2/Crew-Council)

4 LLMs work together to generate a report based off of scientific papers without hallucinations.

**Language:** Python

**Author:** [Josephcc2](https://github.com/Josephcc2)

---

## [gemini-llm-council](https://github.com/theerud/gemini-llm-council)

![GitHub stars](https://img.shields.io/github/stars/theerud/gemini-llm-council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/theerud/gemini-llm-council)

Multi-LLM consensus extension for Gemini CLI. Inspired by Andrej Karpathy's llm-council.

**Language:** TypeScript

**Author:** [theerud](https://github.com/theerud)

---

## [LLM-Council-IDE](https://github.com/ibrahimansr/LLM-Council-IDE)

![GitHub stars](https://img.shields.io/github/stars/ibrahimansr/LLM-Council-IDE?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/ibrahimansr/LLM-Council-IDE)

Drawing inspiration from Andrej Karpathy's LLM Council, this is an implementation for coding. LLMs evaluate each other and generate the best result rather than modern day IDEs where only one model is chosen.

**Language:** Python

**Author:** [ibrahimansr](https://github.com/ibrahimansr)

---

## [LLM-Council-v2](https://github.com/laceyp99/LLM-Council-v2)

![GitHub stars](https://img.shields.io/github/stars/laceyp99/LLM-Council-v2?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/laceyp99/LLM-Council-v2)

A take on Andrej Karpathy's LLM Council, where you are the ultimate head chairman making decisions in the real world. A great tool to prompt multiple models at the same time to compare output quality.

**Language:** Python

**Author:** [laceyp99](https://github.com/laceyp99)

---

## [Philosophers-council](https://github.com/dimitreOliveira/Philosophers-council)

![GitHub stars](https://img.shields.io/github/stars/dimitreOliveira/Philosophers-council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/dimitreOliveira/Philosophers-council)

A Gemma-based chatbot app that has multiple bots impersonating famous philosophers from different schools.

**Language:** Python

**Author:** [dimitreOliveira](https://github.com/dimitreOliveira)

---

## [PolyCouncil](https://github.com/TrentPierce/PolyCouncil)

![GitHub stars](https://img.shields.io/github/stars/TrentPierce/PolyCouncil?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/TrentPierce/PolyCouncil)

PolyCouncil is an open-source multi-model deliberation engine for LM Studio. It runs multiple LLMs in parallel, gathers their answers, scores each response using a shared rubric, and produces a final, consensus-driven result.

**Language:** Python

**Author:** [TrentPierce](https://github.com/TrentPierce)

---

## [Research_council](https://github.com/al1-nasir/Research_council)

![GitHub stars](https://img.shields.io/github/stars/al1-nasir/Research_council?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/al1-nasir/Research_council)

GraphRAG + 4-agent LLM council for biomedical research. Find contradictions, validate hypotheses, and get confidence-scored answers, cited to real papers. Built on Neo4j, LangGraph, Groq & OpenRouter.

**Language:** Python

**Author:** [al1-nasir](https://github.com/al1-nasir)

---

## [Sage](https://github.com/usetig/sage)

![GitHub stars](https://img.shields.io/github/stars/usetig/sage?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/usetig/sage)

An LLM council that reviews your coding agent's every move.

**Language:** TypeScript

**Author:** [usetig](https://github.com/usetig)

---

## [AgentTorch](https://github.com/AgentTorch/AgentTorch)

![GitHub stars](https://img.shields.io/github/stars/AgentTorch/AgentTorch?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/AgentTorch/AgentTorch)

Differentiable agent-based modeling framework supporting millions of LLM-powered agents. Used for population-level simulations of economic, epidemiological, and social dynamics where diverse agent perspectives emerge at scale.

*Enables large-scale deliberation and perspective synthesis across heterogeneous agent populations.*

**Language:** Jupyter Notebook

**Author:** [AgentTorch](https://github.com/AgentTorch)

---

# Negotiation & Benchmarks

Tools and benchmarks for multi-agent negotiation and strategic deliberation.

## [NegotiationArena](https://github.com/vinid/NegotiationArena)

![GitHub stars](https://img.shields.io/github/stars/vinid/NegotiationArena?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/vinid/NegotiationArena)

[ICML 2024] Platform for evaluating LLM negotiation abilities across ultimatum games, trading games, and price negotiations. Studies behavioral tactics and their effects on outcomes.

*Framework for understanding LLM negotiation dynamics, applicable to diplomatic bargaining and multi-party policy deliberation.*

**Language:** Python

**Author:** [vinid](https://github.com/vinid)

---

## [DiploBench](https://github.com/sam-paech/diplobench)

![GitHub stars](https://img.shields.io/github/stars/sam-paech/diplobench?style=social) ![GitHub last commit](https://img.shields.io/github/last-commit/sam-paech/diplobench)

Benchmark for LLMs playing full press Diplomacy with open negotiations and alliances. Assesses how LLMs reason, negotiate, ally, and betray in strategic competition.

*Benchmarking framework for LLM strategic negotiation capabilities — useful for evaluating which models are suitable for deliberation and negotiation simulation.*

**Language:** HTML

**Author:** [sam-paech](https://github.com/sam-paech)

---

# Contributing

Anyone is welcome to open a pull request to add a project to this list. Drop me a line at public@danielrosehill.com if you'd like me to add it manually.

# Disclaimer

This resource is intended for those discovering multi-agent AI projects for perspective synthesis and deliberation. It is not exhaustive and is maintained on a best-effort basis. The inclusion of a project does not constitute an endorsement.

---

Maintained by [Daniel Rosehill](https://github.com/danielrosehill)
