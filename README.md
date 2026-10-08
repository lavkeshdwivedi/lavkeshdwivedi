# Lavkesh Dwivedi

**Forward Deployed Engineer · Forward Deployed AI Lead · Agentic AI security**

I'm a forward deployed engineer building agentic AI that holds up in production for regulated industries like financial services, insurance, and healthcare. Fifteen years of Python and .NET across Charles Schwab (Azure and Google Cloud with Vertex AI), Microsoft (Azure OpenAI, Semantic Kernel, LangChain), and Philips (AWS).

On the side, I run empirical safety research on autonomous agents and ship the tooling that operationalizes it. Current work covers attack categories C1-C4 tested across 29 models and 8 providers, with C5-C7 as an early pilot; the findings feed into production-ready detectors, evals, and red-team plugins contributed to garak, deepeval, promptfoo, and inspect_evals.

### What I'm building

- [**PolisIQ**](https://polisiq.ai): agentic AI underwriting associate for insurance carriers and MGAs. Intake, Intelligence, Decision, and Orchestrator agents, document AI for PDF/Excel/ACORD, auditable guardrails
- [**Ansera AI**](https://ansera.ai): AI answer engine that turns websites into searchable knowledge bases, re-indexing within minutes of content changes
- [**Kogni·OS**](https://github.com/lavkeshdwivedi/kogniOS) [![PyPI](https://img.shields.io/pypi/v/kognios.svg)](https://pypi.org/project/kognios/): Python agent framework built from scratch. SQLite-native RAG, readable ReAct loop, streaming, async, eval harness, HTTP serve, 9 providers (Anthropic, OpenAI, Groq, Gemini, Mistral, Cohere, Ollama, Bedrock, xAI)
- [**Bolo**](https://bolo.lavkesh.com): bilingual speech and vocabulary app for toddlers (English + Hindi, Web Speech API, PWA)
- [**geo-pulse**](https://pulse.lavkesh.com): signal-first geopolitics briefs with automated hourly updates (Python, GitHub Actions)
- [**BVSA**](https://bvsaorai.org): site for a grassroots nonprofit in Bundelkhand, built as a PWA for slow rural connections
- [**Planning Poker**](https://poker.lavkesh.com): real-time agile estimation tool; cards flip simultaneously so nobody anchors first (Firebase Realtime DB)

### Tech

```
Languages   Python · C# · .NET · TypeScript · Go · SQL
Cloud       GCP · Azure · AWS · Kubernetes · Helm · Docker · GitHub Actions
AI / Agents multi-agent orchestration · RAG · document AI · Vertex AI · Gemini · Azure OpenAI · LangChain · Semantic Kernel · MCP · Claude Code
```

### OSS contributions

<!-- OSS_CONTRIBUTIONS_START -->
**AI safety / agentic security** ([Dwivedi 2026, preprint](https://github.com/lavkeshdwivedi/agent-escape-lab): empirical research across 29 models and 8 providers, C1-C4 tested at scale, C5-C7 early pilot)

| Repo | PR | What |
|------|----|------|
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [#1918](https://github.com/NVIDIA/garak/pull/1918) | Multi-turn persona injection probe + detector (C2) |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [#1920](https://github.com/NVIDIA/garak/pull/1920) | Fix: retag AgentBreaker owasp:llm07/08 to owasp:llm06 |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [#1921](https://github.com/NVIDIA/garak/pull/1921) | Fix: coerce non-string REST response fields to str in RestGenerator |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [#1925](https://github.com/NVIDIA/garak/pull/1925) | C5 multi-agent orchestrator trust exploitation probe |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | [#10008](https://github.com/promptfoo/promptfoo/pull/10008) | `persona-injection` redteam plugin (C2) |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | [#10020](https://github.com/promptfoo/promptfoo/pull/10020) | `orchestrator-trust-injection` redteam plugin (C5) |
| [protectai/llm-guard](https://github.com/protectai/llm-guard) | [#350](https://github.com/protectai/llm-guard/pull/350) | `AgentEscalation` output scanner (C4) |
| [protectai/llm-guard](https://github.com/protectai/llm-guard) | [#351](https://github.com/protectai/llm-guard/pull/351) | `AgentMemoryPoisoning` output scanner (C6) |
| [protectai/llm-guard](https://github.com/protectai/llm-guard) | [#352](https://github.com/protectai/llm-guard/pull/352) | `CredentialExfiltration` output scanner (C7) |
| [confident-ai/deepeval](https://github.com/confident-ai/deepeval) | [#2855](https://github.com/confident-ai/deepeval/pull/2855) | `AgentEscalationMetric` LLM-judge metric (C4) |
| [confident-ai/deepeval](https://github.com/confident-ai/deepeval) | [#2863](https://github.com/confident-ai/deepeval/pull/2863) | `AgentMemoryPoisonMetric` LLM-judge metric (C6) |
| [UKGovernmentBEIS/inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals) | [#1906](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1906) | Register: AgentEscalationEval task (C4) |
| [UKGovernmentBEIS/inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals) | [#1907](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1907) | Register: OrchestratorTrustExploitationEval task (C5) |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | [#97107](https://github.com/openclaw/openclaw/pull/97107) | Fix: bypass fail-closed interpreter heuristic when security=full |

**Other**

| Repo | Contribution |
|------|-------------|
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | 2 merged PRs: technical job-search skill, technical interview prep coaching agent |
| [santifer/career-ops](https://github.com/santifer/career-ops) | 8 merged PRs: git-safety fixes, Windows symlink handling, dashboard scripts, rollback guard, interview-prep contract coverage |
| [AppMetrics/AppMetrics](https://github.com/AppMetrics/AppMetrics/pull/563) | Add IWebHostBuilder extensions for .NET metrics |
| [minio/minio-dotnet](https://github.com/minio/minio-dotnet/pull/521) | Fix stream disposal bug in ToXML method |
<!-- OSS_CONTRIBUTIONS_END -->

[![lavkesh.com](https://img.shields.io/badge/lavkesh.com-000?style=flat&logo=About.me&logoColor=white)](https://lavkesh.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/lavkesh)
