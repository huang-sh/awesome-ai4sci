# AI for Science project comparison

[简体中文](COMPARISON.zh-CN.md)

This matrix is a compact index, not a ranking. Existing entries were checked
against their upstream repositories on 2026-07-15; BrainPilot was added and
checked on 2026-07-19, and Motif on 2026-07-22. Features can change quickly, so
verify details upstream before adopting a project.

| Project | Primary surface | Runtime or model strategy | Notable focus | License |
| --- | --- | --- | --- | --- |
| [BrainPilot](https://github.com/NeuroAIHub/BrainPilot) | Browser workspace, CLI | Pi SDK; Anthropic, OpenAI-compatible, and Azure providers | Brain science, specialist agents, and Graph of Trace | AGPL-3.0 |
| [DeepScience](https://github.com/huang-sh/DeepScience) | Web, CLI | Multi-provider Pi Agent runtime | Domain agents, project/session isolation, scientific artifacts | MIT |
| [InternAgentS](https://github.com/qzzqzzb/OpenClaudeScience) | Web | DeepAgents and LangGraph; cloud, gateway, or local models | Remote compute approvals and scientific file workflows | MIT |
| [Open Science](https://github.com/aipoch/open-science) | Electron desktop | Claude Code login or custom model gateway | Early-alpha notebooks, artifacts, skills, and life-science connectors | Apache-2.0 |
| [Open Science Desktop](https://github.com/ai4s-research/open-science) | Tauri desktop | Model-agnostic OpenCode runtime | End-to-end skills, provenance, notebooks, and reproducible runs | MIT |
| [OpenAI4S](https://github.com/PKU-YuanGroup/OpenAI4S) | Web, CLI | Hybrid JSON tools plus persistent Python/R kernels | Low-cost providers, sandboxed execution, BYOC compute | MIT |
| [OpenScience](https://github.com/synthetic-sciences/openscience) | Browser workspace, CLI | Multi-provider and open-weight models | Full research loop, large skill library, scientific databases | Apache-2.0 |
| [Runcell Science](https://github.com/runcell-ai/runcell-science) | Web, Electron desktop | Codex, Claude Code, and Grok runtimes | Interactive artifacts, notebooks, and worktree diffs | Apache-2.0 |
| [Wisp Science](https://github.com/xuzhougeng/wisp-science) | Tauri desktop, CLI | OpenAI-compatible, Anthropic, and ACP agents | Rust stack, persistent Python/R, biological database MCPs | Apache-2.0 |
| [Claude Science for Windows](https://github.com/JWM0203/Claude-Science-for-win) | Windows CLI | Claude Code orchestration | Coordinator/reviewer agents, connectors, and provenance | No license file |
| [Motif](https://github.com/jvogan/motif) | Claude Science MCP App, standalone HTML | Local connector; no hosted backend | Molecular sequence editing and analysis | MIT |
| [Open Engineer](https://github.com/svd-ai-lab/open-engineer) | Windows desktop | OpenCode providers | Engineering, CAE/CAD, simulation, and science skills | MIT |
| [ScholarCopilot](https://github.com/TIGER-AI-Lab/ScholarCopilot) | Gradio web app | ScholarCopilot checkpoint with an HNSW-indexed arXiv corpus | Academic text completion and citation retrieval | MIT |
| [CSSwitch](https://github.com/SuperJJ007/CSSwitch) | macOS menu-bar app | Local Anthropic/OpenAI protocol gateway | Routes Claude Science to third-party model APIs | MIT |
| [CSSwitch Linux](https://github.com/YuntaoOvO/CSSwitch-Linux) | Linux/WSL CLI and Tauri GUI | Local protocol gateway and sandbox | Native Linux/WSL port of the CSSwitch workflow | MIT |

“No license file” means the repository did not expose a license at the time of
review. Public source code without a license is not automatically open source.
