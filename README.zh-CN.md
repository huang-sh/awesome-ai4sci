<div align="center">

# Awesome AI for Science

精选的科学智能体、科研工作台与 AI for Science 工具集合。

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)

[English](README.md) · 简体中文

</div>

> [!NOTE]
> 本列表聚焦可运行、可检查，且以科学研究为核心使用场景的软件。收录不代表背书。功能和平台支持变化很快，采用前请以各项目的最新文档为准。

## 目录

- [项目索引](#项目索引)
- [端到端科研工作台](#端到端科研工作台)
- [领域、平台与工程专项项目](#领域平台与工程专项项目)
- [商业化科研 Agent 平台](#商业化科研-agent-平台)
- [Claude Science 兼容与模型路由](#claude-science-兼容与模型路由)

## 项目索引

可按下方项目类型浏览。若需横向比较界面、运行时、主要特点与许可证，
请查看[对比矩阵](COMPARISON.zh-CN.md)。

## 端到端科研工作台

- **[BrainPilot](https://github.com/NeuroAIHub/BrainPilot)** — 面向脑科学的人在回路多智能体科研工作台。PI Agent 协调 librarian、experimentalist、engineer、writer 和 auditor，覆盖文献调研、研究设计、数据分析、写作与科学主张审计，并通过 Graph of Trace 保留可检查的研究过程。`TypeScript` `AGPL-3.0`

- **[Dr. Claw](https://github.com/OpenLAIR/dr-claw)** — 本地科研工作台，覆盖调研、构思、实验、出版与推广阶段，支持多种 Agent 运行时、可复用科研 Skill，以及通过浏览器界面顺序执行研究流水线。`JavaScript` `AGPL-3.0 / 部分 GPL-3.0`

- **[DeepScience](https://github.com/huang-sh/DeepScience)** — 基于 Pi Agent 运行时的本地科学智能体，提供 Biology、Research、Physics、Machine Learning 四类 Agent、按需科学资源与 MCP Connector、隔离的项目/会话 Workspace、Artifact 预览以及 Web/终端界面。`Python` `TypeScript` `MIT`

- **[InternAgentS](https://github.com/qzzqzzb/OpenClaudeScience)** — 基于 DeepAgents 与 LangGraph 的本地优先科研工作台，整合科学文件预览、可复用 Skill、MCP/SCP Connector、可配置模型后端和需要人工审批的 Linux SSH 计算。`Python` `TypeScript` `MIT`

- **[Open Science](https://github.com/aipoch/open-science)** — 面向 macOS、Windows 和 Linux 的早期 Alpha Electron 桌面工作台。当前已实现“计划 → 执行 → 产出 → 预览”闭环、持久 Notebook、Artifact、文件式 Skill 和生命科学 Connector；更广泛的多模型路由与溯源仍在路线图中。`TypeScript` `Apache-2.0`

- **[Open Science Desktop](https://github.com/ai4s-research/open-science)** — 面向 macOS、Windows 和 Linux 的本地优先 Tauri 工作台，使用基于 OpenCode 的模型无关运行时，内置端到端科研 Skill、Notebook、科学文件查看器、MCP Connector、溯源以及本地/远程可复现运行。`TypeScript` `MIT`

- **[OpenAI4S](https://github.com/PKU-YuanGroup/OpenAI4S)** — 混合式科学智能体：结构化 JSON 工具负责编排，持久 Python/R Kernel 负责计算。提供轻量 Web 应用与 CLI、科学 Skill、本地沙箱适配、低成本模型 Provider 和自带计算资源工作流。`Python` `MIT`

- **[OpenScience](https://github.com/synthetic-sciences/openscience)** — 覆盖文献调研、假设生成、编码、实验、分析和写作的浏览器科研工作台与 CLI，支持多种模型 Provider、大型 Skill 目录、科学数据库工具、插件、MCP 与 SDK。`TypeScript` `Apache-2.0`

- **[Runcell Science](https://github.com/runcell-ai/runcell-science)** — 围绕 Codex、Claude Code 和 Grok Agent 运行时构建的 Web/Electron 工作台，将 Prompt、工具活动、Notebook、交互式 Artifact、科学 Connector、项目文件和 Worktree Diff 保留在同一个可检查的科研会话中。`TypeScript` `Apache-2.0`

- **[Wisp Science](https://github.com/xuzhougeng/wisp-science)** — Rust 优先的本地桌面科研助手与 Headless CLI，支持 OpenAI 兼容和 Anthropic 模型、ACP Agent、持久 Python/R REPL、可复用 `SKILL.md` 工作流、加密项目同步和生物数据库 MCP。`Rust` `Apache-2.0`

## 领域、平台与工程专项项目

- **[Claude Science for Windows](https://github.com/JWM0203/Claude-Science-for-win)** — 面向 Windows 的 Claude Code 科研编排套件，包含 Coordinator、Specialist、Reviewer Agent、公开科学数据库 Connector、Python 环境和基于哈希的溯源记录。检查时仓库未提供许可证文件。`Python` `未提供许可证文件`

- **[Motif](https://github.com/jvogan/motif)** — 面向 Claude Science 的 AI 原生分子生物学工作台，提供本地 MCP App、插件、Skill 与自包含 HTML Workspace，用于编辑 DNA、RNA 和蛋白质记录，并审阅序列图谱、酶切、引物/PCR、组装流程、比对、Sanger 峰图、ORF 和 CRISPR guide 候选。`TypeScript` `MIT`

- **[Open Engineer](https://github.com/svd-ai-lab/open-engineer)** — 基于 OpenCode 的 Windows x64 工程工作台，在科学文献和文档工作流之外，还提供 COMSOL、Abaqus、Ansys、MATLAB 等 CAE/CAD 与仿真软件的 Skill。`TypeScript` `MIT`

- **[ScholarCopilot](https://github.com/TIGER-AI-Lab/ScholarCopilot)** — 基于 Gradio 的学术写作助手，通过统一的生成与检索模型提供上下文相关的文本续写，并从 arXiv 语料库检索引用建议。仓库提供本地 Demo 配置和语料索引工具。`Python` `MIT`

## 商业化科研 Agent 平台

以下托管产品与开源项目分开列出，不纳入对比矩阵。

- **[SciSpace](https://scispace.com/)** — 支持论文检索、文献综述、PDF 对话，以及研究文本、示意图和演示文稿生成的科研 Agent。

- **[ScienceOne](https://www.scienceone.ai/portal/)** — 覆盖多智能体深度研究、科学计算与工具编排、文献和数据库访问、实验辅助及科研成果产出的一站式 AI for Science 平台。

- **[Biomni Lab](https://biomni.phylo.bio/)** — 面向生物医学与生命科学的云端科研助手，可调用专业工具、数据库和计算资源规划并执行生物信息学分析。

- **[omicOS](https://omicos.cn/omicos)** — 面向单细胞与空间组学分析的多智能体工作台，可将自然语言需求转化为基于 OmicVerse、Scanpy 等工具的可执行流程。

- **[PromptBio](https://www.promptbio.ai/)** — 面向生命科学的对话式平台，用于编排生物信息学数据管理、处理、分析、自动化机器学习与生物标志物发现流程。

## Claude Science 兼容与模型路由

以下工具用于扩展或路由已有 Claude Science 安装，本身不是独立科研工作台。

- **[CSSwitch](https://github.com/SuperJJ007/CSSwitch)** — macOS Apple Silicon 菜单栏应用，在本地隔离环境运行 Claude Science，并将请求路由至 DeepSeek、Qwen、GLM、Kimi、MiniMax、OpenRouter 或兼容的自定义端点。`Rust` `MIT`

- **[CSSwitch Linux](https://github.com/YuntaoOvO/CSSwitch-Linux)** — 面向 Linux、WSL 和 Headless 环境的 CSSwitch 移植，提供 CLI 与 Tauri 桌面 GUI、多 Provider Profile、本地网关和隔离的 Claude Science 状态。`Rust` `MIT`

## 参与贡献

欢迎贡献。提交 Pull Request 前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。描述应保持客观，如实披露与项目的关系，并且每个 Pull Request 只提交一个项目。

本列表采用 [CC0-1.0](LICENSE)；每个被收录项目仍适用其各自的许可证和条款。
