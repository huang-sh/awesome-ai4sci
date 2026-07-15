# AI for Science 项目对比

[English](COMPARISON.md)

本表用于快速索引，不代表项目排名。界面、平台和许可证信息于 2026-07-15
对照上游仓库检查。功能变化很快，采用前请以各项目最新文档为准。

| 项目 | 主要界面 | 运行时或模型策略 | 主要特点 | 许可证 |
| --- | --- | --- | --- | --- |
| [DeepScience](https://github.com/huang-sh/DeepScience) | Web、CLI | 多 Provider Pi Agent 运行时 | 领域 Agent、项目/会话隔离、科学产物 | MIT |
| [InternAgentS](https://github.com/qzzqzzb/OpenClaudeScience) | Web | DeepAgents + LangGraph；云模型、私有网关或本地模型 | 远程计算审批与科学文件工作流 | MIT |
| [Open Science](https://github.com/aipoch/open-science) | Electron 桌面端 | Claude Code 登录或自定义模型网关 | 早期 Alpha：Notebook、Artifact、Skill 和生命科学连接器 | Apache-2.0 |
| [Open Science Desktop](https://github.com/ai4s-research/open-science) | Tauri 桌面端 | 基于 OpenCode 的模型无关运行时 | 端到端 Skill、溯源、Notebook 与可复现运行 | MIT |
| [OpenAI4S](https://github.com/PKU-YuanGroup/OpenAI4S) | Web、CLI | JSON 工具 + 持久 Python/R Kernel | 低成本模型、沙箱执行、BYOC 计算 | MIT |
| [OpenScience](https://github.com/synthetic-sciences/openscience) | 浏览器工作台、CLI | 多 Provider 与开源权重模型 | 完整科研闭环、大型 Skill 库、科学数据库 | Apache-2.0 |
| [Runcell Science](https://github.com/runcell-ai/runcell-science) | Web、Electron 桌面端 | Codex、Claude Code、Grok 运行时 | 交互式 Artifact、Notebook 与 Worktree Diff | Apache-2.0 |
| [Wisp Science](https://github.com/xuzhougeng/wisp-science) | Tauri 桌面端、CLI | OpenAI 兼容、Anthropic 与 ACP Agent | Rust 技术栈、持久 Python/R、生物数据库 MCP | Apache-2.0 |
| [Open Engineer](https://github.com/svd-ai-lab/open-engineer) | Windows 桌面端 | OpenCode Providers | 工程、CAE/CAD、仿真与科学 Skill | MIT |
| [Claude Science for Windows](https://github.com/JWM0203/Claude-Science-for-win) | Windows CLI | Claude Code 编排 | Coordinator/Reviewer Agent、连接器与溯源 | 未提供许可证文件 |
| [CSSwitch](https://github.com/SuperJJ007/CSSwitch) | macOS 菜单栏应用 | 本地 Anthropic/OpenAI 协议网关 | 将 Claude Science 路由到第三方模型 API | MIT |
| [CSSwitch Linux](https://github.com/YuntaoOvO/CSSwitch-Linux) | Linux/WSL CLI、Tauri GUI | 本地协议网关与隔离环境 | CSSwitch 工作流的原生 Linux/WSL 移植 | MIT |

“未提供许可证文件”表示检查时仓库未公开许可证；公开源代码不等同于自动授予
开源许可。
