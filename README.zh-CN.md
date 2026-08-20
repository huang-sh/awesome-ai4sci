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

可按下方项目类型浏览。若需在一张表中查看所有开源项目，请查看
[对比矩阵](COMPARISON.zh-CN.md)。

## 端到端科研工作台

| 项目 | 主要界面 | 运行时或模型策略 | 主要特点 | 许可证 |
| --- | --- | --- | --- | --- |
| [BrainPilot](https://github.com/NeuroAIHub/BrainPilot) | 浏览器工作台、CLI | Pi SDK；Anthropic、OpenAI 兼容和 Azure Provider | 脑科学、专项 Agent 与 Graph of Trace | AGPL-3.0 |
| [Dr. Claw](https://github.com/OpenLAIR/dr-claw) | 浏览器工作台 | 多 Agent 运行时、可复用 Skill 与流水线执行 | 从调研到出版的科研工作流 | AGPL-3.0 / 部分 GPL-3.0 |
| [DeepScience](https://github.com/huang-sh/DeepScience) | Web、CLI | 多 Provider Pi Agent 运行时 | 领域 Agent、项目/会话隔离、科学产物 | MIT |
| [InternAgentS](https://github.com/qzzqzzb/OpenClaudeScience) | Web | DeepAgents + LangGraph；云模型、私有网关或本地模型 | 远程计算审批与科学文件工作流 | MIT |
| [K-Dense BYOK](https://github.com/K-Dense-AI/k-dense-byok) | 本地浏览器工作台 | 托管 Provider、订阅 OAuth 与本地 OpenAI 兼容模型 | 科学 Skill、实验记录本、文件预览与可选云计算 | MIT |
| [Open Science](https://github.com/aipoch/open-science) | Electron 桌面端 | Claude Code 登录或自定义模型网关 | 早期 Alpha：Notebook、Artifact、Skill 和生命科学连接器 | Apache-2.0 |
| [Open Science Desktop](https://github.com/ai4s-research/open-science) | Tauri 桌面端 | 基于 OpenCode 的模型无关运行时 | 端到端 Skill、溯源、Notebook 与可复现运行 | MIT |
| [OpenAI4S](https://github.com/PKU-YuanGroup/OpenAI4S) | Web、CLI | JSON 工具 + 持久 Python/R Kernel | 低成本模型、沙箱执行、BYOC 计算 | MIT |
| [OpenScience](https://github.com/synthetic-sciences/openscience) | 浏览器工作台、CLI | 多 Provider 与开源权重模型 | 完整科研闭环、大型 Skill 库、科学数据库 | Apache-2.0 |
| [Runcell Science](https://github.com/runcell-ai/runcell-science) | Web、Electron 桌面端 | Codex、Claude Code、Grok 运行时 | 交互式 Artifact、Notebook 与 Worktree Diff | Apache-2.0 |
| [Wisp Science](https://github.com/xuzhougeng/wisp-science) | Tauri 桌面端、CLI | OpenAI 兼容、Anthropic 与 ACP Agent | Rust 技术栈、持久 Python/R、生物数据库 MCP | Apache-2.0 |

## 领域、平台与工程专项项目

| 项目 | 主要界面 | 运行时或模型策略 | 主要特点 | 许可证 |
| --- | --- | --- | --- | --- |
| [Claude Science for Windows](https://github.com/JWM0203/Claude-Science-for-win) | Windows CLI | Claude Code 编排 | Coordinator/Reviewer Agent、连接器与溯源 | 未提供许可证文件 |
| [Motif](https://github.com/jvogan/motif) | Claude Science MCP App、自包含 HTML | 本地 Connector；无托管后端 | 分子序列编辑与分析 | MIT |
| [Open Engineer](https://github.com/svd-ai-lab/open-engineer) | Windows 桌面端 | OpenCode Providers | 工程、CAE/CAD、仿真与科学 Skill | MIT |
| [ScholarCopilot](https://github.com/TIGER-AI-Lab/ScholarCopilot) | Gradio Web 应用 | ScholarCopilot Checkpoint + HNSW 索引的 arXiv 语料库 | 学术文本续写与引用检索 | MIT |

## 商业化科研 Agent 平台

以下托管产品与开源项目分开列出，不纳入对比矩阵。

| 平台 | 主要特点 |
| --- | --- |
| [SciSpace](https://scispace.com/) | 论文检索、文献综述、PDF 对话与科研成果起草 |
| [ScienceOne](https://www.scienceone.ai/portal/) | 多智能体研究、科学计算、工具编排与实验辅助 |
| [Biomni Lab](https://biomni.phylo.bio/) | 使用专业工具、数据库和计算资源的生物医学与生命科学工作流 |
| [omicOS](https://omicos.cn/omicos) | 面向单细胞与空间组学分析的自然语言工作流 |
| [PromptBio](https://www.promptbio.ai/) | 生物信息学数据管理、分析、AutoML 与生物标志物发现 |

## Claude Science 兼容与模型路由

以下工具用于扩展或路由已有 Claude Science 安装，本身不是独立科研工作台。

| 项目 | 主要界面 | 运行时或模型策略 | 主要特点 | 许可证 |
| --- | --- | --- | --- | --- |
| [CSSwitch](https://github.com/SuperJJ007/CSSwitch) | macOS 菜单栏应用 | 本地 Anthropic/OpenAI 协议网关 | 将 Claude Science 路由到第三方模型 API | MIT |
| [CSSwitch Linux](https://github.com/YuntaoOvO/CSSwitch-Linux) | Linux/WSL CLI、Tauri GUI | 本地协议网关与隔离环境 | CSSwitch 工作流的原生 Linux/WSL 移植 | MIT |

## 参与贡献

欢迎贡献。提交 Pull Request 前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。描述应保持客观，如实披露与项目的关系，并且每个 Pull Request 只提交一个项目。

本列表采用 [CC0-1.0](LICENSE)；每个被收录项目仍适用其各自的许可证和条款。
