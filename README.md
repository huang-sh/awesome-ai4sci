<div align="center">

# Awesome AI for Science

A curated collection of AI agents, research workbenches, and tooling for scientific discovery.

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)

English · [简体中文](README.zh-CN.md)

</div>

> [!NOTE]
> This list focuses on runnable, inspectable software in which scientific work is a primary use case. Inclusion is not an endorsement. Features and platform support change quickly, so check each project's documentation before adopting it.

## Contents

- [Project index](#project-index)
- [End-to-end research workbenches](#end-to-end-research-workbenches)
- [Domain, platform, and engineering-focused projects](#domain-platform-and-engineering-focused-projects)
- [Commercial research agent platforms](#commercial-research-agent-platforms)
- [Claude Science compatibility and model routing](#claude-science-compatibility-and-model-routing)

## Project index

Use the sections below to browse by project type. For one consolidated table
across the open-source categories, see the [comparison matrix](COMPARISON.md).

## End-to-end research workbenches

| Project | Primary surface | Runtime or model strategy | Notable focus | License |
| --- | --- | --- | --- | --- |
| [BrainPilot](https://github.com/NeuroAIHub/BrainPilot) | Browser workspace, CLI | Pi SDK; Anthropic, OpenAI-compatible, and Azure providers | Brain science, specialist agents, and Graph of Trace | AGPL-3.0 |
| [Dr. Claw](https://github.com/OpenLAIR/dr-claw) | Browser workspace | Multiple agent runtimes with reusable skills and pipeline execution | Survey-to-publication research workflow | AGPL-3.0 / GPL-3.0 portions |
| [DeepScience](https://github.com/huang-sh/DeepScience) | Web, CLI | Multi-provider Pi Agent runtime | Domain agents, project/session isolation, scientific artifacts | MIT |
| [InternAgentS](https://github.com/qzzqzzb/OpenClaudeScience) | Web | DeepAgents and LangGraph; cloud, gateway, or local models | Remote compute approvals and scientific file workflows | MIT |
| [K-Dense BYOK](https://github.com/K-Dense-AI/k-dense-byok) | Local browser workspace | Hosted providers, subscription OAuth, and local OpenAI-compatible models | Scientific skills, lab notebook, file previews, and optional cloud compute | MIT |
| [Open Science](https://github.com/aipoch/open-science) | Electron desktop | Claude Code login or custom model gateway | Early-alpha notebooks, artifacts, skills, and life-science connectors | Apache-2.0 |
| [Open Science Desktop](https://github.com/ai4s-research/open-science) | Tauri desktop | Model-agnostic OpenCode runtime | End-to-end skills, provenance, notebooks, and reproducible runs | MIT |
| [OpenAI4S](https://github.com/PKU-YuanGroup/OpenAI4S) | Web, CLI | Hybrid JSON tools plus persistent Python/R kernels | Low-cost providers, sandboxed execution, BYOC compute | MIT |
| [OpenScience](https://github.com/synthetic-sciences/openscience) | Browser workspace, CLI | Multi-provider and open-weight models | Full research loop, large skill library, scientific databases | Apache-2.0 |
| [Runcell Science](https://github.com/runcell-ai/runcell-science) | Web, Electron desktop | Codex, Claude Code, and Grok runtimes | Interactive artifacts, notebooks, and worktree diffs | Apache-2.0 |
| [Wisp Science](https://github.com/xuzhougeng/wisp-science) | Tauri desktop, CLI | OpenAI-compatible, Anthropic, and ACP agents | Rust stack, persistent Python/R, biological database MCPs | Apache-2.0 |

## Domain, platform, and engineering-focused projects

| Project | Primary surface | Runtime or model strategy | Notable focus | License |
| --- | --- | --- | --- | --- |
| [Claude Science for Windows](https://github.com/JWM0203/Claude-Science-for-win) | Windows CLI | Claude Code orchestration | Coordinator/reviewer agents, connectors, and provenance | No license file |
| [Motif](https://github.com/jvogan/motif) | Claude Science MCP App, standalone HTML | Local connector; no hosted backend | Molecular sequence editing and analysis | MIT |
| [Open Engineer](https://github.com/svd-ai-lab/open-engineer) | Windows desktop | OpenCode providers | Engineering, CAE/CAD, simulation, and science skills | MIT |
| [ScholarCopilot](https://github.com/TIGER-AI-Lab/ScholarCopilot) | Gradio web app | ScholarCopilot checkpoint with an HNSW-indexed arXiv corpus | Academic text completion and citation retrieval | MIT |

## Commercial research agent platforms

These hosted products are listed separately from the open-source projects and are not included in the comparison matrix.

| Platform | Notable focus |
| --- | --- |
| [SciSpace](https://scispace.com/) | Paper search, literature review, PDF chat, and research-output drafting |
| [ScienceOne](https://www.scienceone.ai/portal/) | Multi-agent research, scientific computing, tool orchestration, and experiment support |
| [Biomni Lab](https://biomni.phylo.bio/) | Biomedical and life-science workflows using specialized tools, databases, and compute |
| [omicOS](https://omicos.cn/omicos) | Natural-language workflows for single-cell and spatial omics analysis |
| [PromptBio](https://www.promptbio.ai/) | Bioinformatics data management, analysis, AutoML, and biomarker discovery |

## Claude Science compatibility and model routing

These tools extend or reroute an existing Claude Science installation; they are not standalone research workbenches.

| Project | Primary surface | Runtime or model strategy | Notable focus | License |
| --- | --- | --- | --- | --- |
| [CSSwitch](https://github.com/SuperJJ007/CSSwitch) | macOS menu-bar app | Local Anthropic/OpenAI protocol gateway | Routes Claude Science to third-party model APIs | MIT |
| [CSSwitch Linux](https://github.com/YuntaoOvO/CSSwitch-Linux) | Linux/WSL CLI and Tauri GUI | Local protocol gateway and sandbox | Native Linux/WSL port of the CSSwitch workflow | MIT |

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. Keep descriptions factual, disclose affiliations, and submit one project per pull request.

This list is released under [CC0-1.0](LICENSE). Every linked project retains its own license and terms.
