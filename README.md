<div align="center">

# Awesome AI for Science

A curated collection of open-source AI agents, research workbenches, and tooling for scientific discovery.

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)

English · [简体中文](README.zh-CN.md)

</div>

> [!NOTE]
> This list focuses on runnable, inspectable software in which scientific work is a primary use case. Inclusion is not an endorsement. Features and platform support change quickly, so check each project's documentation before adopting it.

## Contents

- [Project index](#project-index)
- [End-to-end research workbenches](#end-to-end-research-workbenches)
- [Platform and engineering-focused projects](#platform-and-engineering-focused-projects)
- [Claude Science compatibility and model routing](#claude-science-compatibility-and-model-routing)

## Project index

Use the sections below to browse by project type. For a side-by-side view of
interfaces, runtimes, focus areas, and licenses, see the
[comparison matrix](COMPARISON.md).

## End-to-end research workbenches

- [BrainPilot](https://github.com/NeuroAIHub/BrainPilot) - A human-in-the-loop, multi-agent research workspace for brain science. Its PI Agent coordinates librarian, experimentalist, engineer, writer, and auditor agents across literature review, study design, analysis, writing, and claim auditing, while Graph of Trace keeps the research process inspectable. `TypeScript` `AGPL-3.0`.

- [DeepScience](https://github.com/huang-sh/DeepScience) - A local scientific agent built on the Pi Agent runtime. It provides Biology, Research, Physics, and Machine Learning agents; on-demand scientific resources and MCP connectors; isolated project/session workspaces; artifact previews; and web or terminal interfaces. `Python` `TypeScript` `MIT`.

- [InternAgentS](https://github.com/qzzqzzb/OpenClaudeScience) - A local-first research workspace built with DeepAgents and LangGraph. It combines scientific file previews, reusable skills, MCP/SCP connectors, configurable model backends, and approval-gated Linux SSH compute. `Python` `TypeScript` `MIT`.

- [Open Science](https://github.com/aipoch/open-science) - An early-alpha Electron desktop workbench for macOS, Windows, and Linux. The current implementation includes the plan → execute → produce → preview loop, persistent notebooks, artifacts, file-based skills, and life-science connectors; broader multi-model routing and provenance remain roadmap items. `TypeScript` `Apache-2.0`.

- [Open Science Desktop](https://github.com/ai4s-research/open-science) - A local-first Tauri workbench for macOS, Windows, and Linux. It uses a model-agnostic OpenCode runtime and bundles end-to-end research skills, notebooks, scientific viewers, MCP connectors, provenance, and local or remote reproducible runs. `TypeScript` `MIT`.

- [OpenAI4S](https://github.com/PKU-YuanGroup/OpenAI4S) - A hybrid scientific agent whose structured JSON tools handle orchestration while persistent Python/R kernels handle computation. It includes a lightweight web app and CLI, bundled science skills, local sandbox adapters, low-cost provider support, and bring-your-own-compute workflows. `Python` `MIT`.

- [OpenScience](https://github.com/synthetic-sciences/openscience) - A browser-based research workspace and CLI that covers literature review, hypothesis generation, coding, experiments, analysis, and writing. It supports many model providers, an extensive skills catalog, scientific database tools, plugins, MCP, and an SDK. `TypeScript` `Apache-2.0`.

- [Runcell Science](https://github.com/runcell-ai/runcell-science) - A web/Electron workspace around Codex, Claude Code, and Grok agent runtimes. Its focus is keeping prompts, tool activity, notebooks, interactive artifacts, scientific connectors, project files, and worktree diffs in one inspectable research session. `TypeScript` `Apache-2.0`.

- [Wisp Science](https://github.com/xuzhougeng/wisp-science) - A Rust-first, local desktop copilot and headless CLI. It supports OpenAI-compatible and Anthropic models, ACP agents, persistent Python/R REPLs, reusable `SKILL.md` workflows, encrypted project sync, and bundled MCP access to biological databases. `Rust` `Apache-2.0`.

## Platform and engineering-focused projects

- [Claude Science for Windows](https://github.com/JWM0203/Claude-Science-for-win) - A Windows-oriented Claude Code orchestration kit with coordinator, specialist, and reviewer agents; public scientific database connectors; Python environments; and hash-based provenance records. The repository did not contain a license file when checked. `Python` `No license file`.

- [Open Engineer](https://github.com/svd-ai-lab/open-engineer) - A Windows x64 engineering workbench based on OpenCode. It packages scientific literature and document workflows alongside skills for CAE/CAD and simulation tools such as COMSOL, Abaqus, Ansys, MATLAB, and others. `TypeScript` `MIT`.

## Claude Science compatibility and model routing

These tools extend or reroute an existing Claude Science installation; they are not standalone research workbenches.

- [CSSwitch](https://github.com/SuperJJ007/CSSwitch) - A macOS Apple Silicon menu-bar application that runs Claude Science in an isolated local environment and routes requests to DeepSeek, Qwen, GLM, Kimi, MiniMax, OpenRouter, or compatible custom endpoints. `Rust` `MIT`.

- [CSSwitch Linux](https://github.com/YuntaoOvO/CSSwitch-Linux) - A Linux, WSL, and headless port of the CSSwitch workflow with both a CLI and Tauri desktop GUI, multiple provider profiles, a local gateway, and isolated Claude Science state. `Rust` `MIT`.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. Keep descriptions factual, disclose affiliations, and submit one project per pull request.

This list is released under [CC0-1.0](LICENSE). Every linked project retains its own license and terms.
