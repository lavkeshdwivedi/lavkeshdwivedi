# Lavkesh Dwivedi

**Cloud-native systems · Agentic AI security · Full-stack**

I build systems that run reliably at scale and agents that work autonomously. Currently focused on agentic AI safety research and the tooling around it — identifying how autonomous agents break out of their guardrails, and building the detectors, evals, and probes that catch it.

### What I'm building

- [**Kogni·OS**](https://github.com/lavkeshdwivedi/kogniOS): Python agent framework built from scratch. SQLite-native RAG with FTS5, a readable ReAct loop, multi-provider support across Anthropic, OpenAI, Groq, and Gemini
- [**Bolo**](https://bolo.lavkesh.com): bilingual speech and vocabulary app for toddlers (English + Hindi, Web Speech API, PWA)
- [**geo-pulse**](https://pulse.lavkesh.com): signal-first geopolitics briefs with automated hourly updates (Python, GitHub Actions)
- [**BVSA**](https://bvsaorai.org): site for a grassroots nonprofit in Bundelkhand, built as a PWA for slow rural connections
- [**Planning Poker**](https://poker.lavkesh.com): real-time agile estimation tool — cards flip simultaneously so nobody anchors first (Firebase Realtime DB)

### Tech

```
Languages   Node.js • Go • C# • Python • SQL
Infra       Kubernetes • Docker • cloud-native • GitHub Actions
AI / Agents Claude Code • MCP • agentic workflows
```

### OSS contributions

<!-- OSS_CONTRIBUTIONS_START -->
**AI safety / agentic security** (from [Dwivedi 2025](https://github.com/lavkeshdwivedi/agent-escape-lab) empirical research across 29 models)

| Repo | PR | What |
|------|----|------|
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [#1918](https://github.com/NVIDIA/garak/pull/1918) | Multi-turn persona injection probe + detector (C2 — gradual identity substitution) |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [#1920](https://github.com/NVIDIA/garak/pull/1920) | Fix: retag AgentBreaker from owasp:llm07/08 → owasp:llm06 |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | [#1921](https://github.com/NVIDIA/garak/pull/1921) | Fix: guard against non-string output.text in promptinject detector |
| [UKGovernmentBEIS/inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai) | [#4428](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4428) | Agent escalation eval task (C4 — autonomous constraint modification) |
| [protectai/llm-guard](https://github.com/protectai/llm-guard) | [#350](https://github.com/protectai/llm-guard/pull/350) | `AgentEscalation` rule-based output scanner (C4) |
| [confident-ai/deepeval](https://github.com/confident-ai/deepeval) | [#2855](https://github.com/confident-ai/deepeval/pull/2855) | `AgentEscalationMetric` LLM-judge metric (C4) |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | [#10008](https://github.com/promptfoo/promptfoo/pull/10008) | `persona-injection` redteam plugin (C2) |

**Other**

| Repo | Contribution |
|------|-------------|
| [github/awesome-copilot](https://github.com/github/awesome-copilot) | 2 merged PRs — technical job-search skill, technical interview prep coaching agent |
| [santifer/career-ops](https://github.com/santifer/career-ops) | 8 merged PRs — git-safety fixes, Windows symlink handling, dashboard scripts, rollback guard, interview-prep contract coverage |
| [AppMetrics/AppMetrics](https://github.com/AppMetrics/AppMetrics/pull/563) | Add IWebHostBuilder extensions for .NET metrics |
| [minio/minio-dotnet](https://github.com/minio/minio-dotnet/pull/521) | Fix stream disposal bug in ToXML method |
<!-- OSS_CONTRIBUTIONS_END -->

[![lavkesh.com](https://img.shields.io/badge/lavkesh.com-000?style=flat&logo=About.me&logoColor=white)](https://lavkesh.com)
[![Twitter](https://img.shields.io/badge/@lavkeshdwivedi-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/lavkeshdwivedi)
