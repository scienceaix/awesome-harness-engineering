# Awesome Harness Engineering 🛠️

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Stars](https://img.shields.io/github/stars/scienceaix/awesome-harness-engineering)](https://github.com/scienceaix/awesome-harness-engineering/stargazers)

> A curated, comprehensive list of tools, frameworks, research papers, and enterprise playbooks for **Harness Engineering**—the discipline of designing deterministic environments, strict constraints, and automated feedback loops that make AI agents reliable and autonomous.

*The model is the commodity; the harness is the moat.*

## Contents

- [Awesome Harness Engineering 🛠️](#awesome-harness-engineering-️)
  - [Contents](#contents)
  - [Core Runtimes \& Agentic OS](#core-runtimes--agentic-os)
  - [Evaluation \& Benchmarking](#evaluation--benchmarking)
  - [Enterprise Playbooks \& Specifications](#enterprise-playbooks--specifications)
  - [Security \& Deterministic Guardrails](#security--deterministic-guardrails)
  - [Cutting-Edge Research Papers](#cutting-edge-research-papers)
  - [Contributing](#contributing)

---

## Core Runtimes & Agentic OS
*Tools that provide the physical scaffolding, memory management, and execution orchestration for autonomous agents.*

- [IHR (In-Loop Harness Runtime)](https://github.com/example/ihr) - An in-loop LLM runtime designed to directly interpret Natural-Language Agent Harnesses (NLAHs), cleanly separating execution from logic.
- [OpenDev](https://github.com/langchain-ai/opendev) - Advanced harness patterns optimized strictly for Levels 1-2 verifiable coding tasks.
- [OpenClaw](https://github.com/example/openclaw) - *(Use with extreme caution)* The viral, local-first AI agent runtime that highlighted the critical need for strict harness security and multi-user isolation.
- [NemoClaw](https://github.com/NVIDIA/nemoclaw) - Nvidia's enterprise-hardened fork of OpenClaw featuring kernel-level sandboxing, deterministic routers, and zero-trust execution.
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - The Model Context Protocol implementation used by Anthropic for deterministic, adversarial QA and UI evaluation within a multi-agent harness loop.

## Evaluation & Benchmarking
*Systems to empirically measure agent capability, alignment, architectural compliance, and cognitive progression.*

- [EleutherAI LM Evaluation Harness (v0.4.9.1)](https://github.com/EleutherAI/lm-evaluation-harness) - The industry standard. Features support for multi-modal tasks, vLLM acceleration, and advanced regex post-processing for Llama/Qwen/Gemma evaluations.
- [PostTrainBench](https://github.com/google-deepmind/posttrainbench) - Evaluates whether agents can autonomously post-train base LLMs against 7 strict benchmarks within fixed H100 compute constraints.
- [Stripe Agent Benchmark](https://github.com/stripe/agent-benchmark) - End-to-end benchmark for agents executing real-world cross-domain glue work, API integration, and database state management.
- [DeepEval](https://github.com/confident-ai/deepeval) - Platform for AI quality observability, automated human feedback collection, and A/B testing of harness performance and token efficiency.

## Enterprise Playbooks & Specifications
*How organizations like Stripe, Shopify, and Block actually deploy agents to production without breaking their architecture.*

- [agents.md](https://github.com/agentsmd/agents.md) - The universal standard for creating machine-readable repository documentation to govern agent behavior, style preferences, and CI/CD rules.
- [FairMind 72 Criteria Checklist](https://github.com/example/fairmind-checklist) - An open-source breakdown of the 7 dimensions and 72 practices required to achieve Level 5 harness maturity in a corporate environment.
- [Factory Model Playbook](https://github.com/example/factory-model) - Playbook for transitioning engineering teams from writing syntax to managing multi-agent orchestration (Feature Authors, Test Generators, Architecture Guardians).
- [Anthropic Harness Design Patterns](https://github.com/anthropic/harness-design-patterns) - Implementation guides for building adversarial Planner/Generator/Evaluator architectures equipped with context-reset mechanisms.

## Security & Deterministic Guardrails
*Probabilistic guardrails will inevitably fail. These tools enforce hard mathematical and cryptographic boundaries.*

- [Deterministic Interceptors](https://github.com/example/deterministic-interceptors) - Middle-layer pre-tool and post-tool execution hooks to sanitize data (regex scanning, base64 decoding) *before* it enters the agent's context window.
- [Session Isolation Toolkit](https://github.com/example/session-isolation) - A lab topology toolkit to aggressively test and expose ingress vs. execution identity bleed (CVE-2026-27183) in multi-agent routers.
- [Prompt Guard (Meta)](https://github.com/meta-llama/prompt-guard) - Robust, lightweight input/output classification models to prevent unauthorized tool execution and system prompt overriding.

## Cutting-Edge Research Papers

- **[Meta-Harness: End-to-End Optimization of Model Harnesses](https://arxiv.org/abs/2603.28052)** - Stanford research demonstrating how agents equipped with unrestricted filesystem access can autonomously discover optimal context retrieval and state update strategies, outperforming hand-engineered baselines.
- **[Natural-Language Agent Harnesses (NLAHs)](https://arxiv.org/abs/2603.25723)** - The foundational paper defining and standardizing the externalization of high-level control logic into portable, editable text artifacts.
- **[Google DeepMind: 10 Cognitive Faculties for Verifiable AGI](https://arxiv.org/abs/example)** - Google DeepMind's empirical, psychologically grounded framework establishing the 10 distinct cognitive faculties required for verifiable AGI.
- **[Exploring Automated R&D and Reward-Hacking Vectors](https://arxiv.org/abs/2603.08640)** - Exploring the automated R&D capabilities and the concerning reward-hacking vectors (test-set training, checkpoint theft) of autonomous agents.

---

## Contributing

Contributions are welcome! Please submit a Pull Request to add new tools, specifications, or cutting-edge academic papers that advance the discipline of Harness Engineering. 
