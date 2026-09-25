# Strands Harness：AWS 开源、可装即用的多模型 Agent Harness（Python/TS）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/MarcJBrooker/status/2102095972688138283
- 作者 / 频道：@MarcJBrooker（AWS Distinguished Engineer）
- 发布时间：2026-09-21 18:01:49 UTC（约 2026-09-22 02:01 CST）

## 要点

- AWS Strands 团队开源 **Strands Harness**：开箱即用的 agent harness，宣称在同等表现下约 **28% 更少 token**（数字 **待核实**）；模型无关，可接 Bedrock / Anthropic / OpenAI / Gemini / Ollama 等。
- 默认带 shell/文件/网页工具、prompt caching、上下文管理、长期记忆、generalist 子代理与 todos 等；提供 CLI、`pip install strands-harness` / `npm i @strands-agents/harness`、以及给 Codex/Claude Code/Kiro 的安装引导提示。
- 可动手入口：文档 quickstart；源码 `strands-agents/harness-sdk`。星数 **待核实**（公开页约八千级，以 GitHub 实时为准）。

## 落地链接（可选）

- 文档：https://strandsagents.com/docs/user-guide/harness/quickstart/
- 仓库：https://github.com/strands-agents/harness-sdk
- PyPI：https://pypi.org/project/strands-harness/

## 价值判断

- 为什么值得记：官方工程负责人宣发 + 可装 CLI/库入口清楚，补「组装好的开源 harness」产品轴。
- 风险 / 待核实：token 节省与性能对比数字待核实；默认依赖云模型权限与计费；个人账号转发，以文档/仓库为准。

## 原文摘要（可选）

摘要：@MarcJBrooker 宣布开源 Strands Harness，称便于用任意模型构建可靠、成本可控的 agents，并给出相对专有 harness 的 token 节省主张。

## 与其他条目的关系（可选）

同厂 AWS Agent 生态，但本条是 **Strands Harness（完整可运行 harness SDK/CLI）**；勿与已入库 Agent Toolkit for AWS（AWS 域 Skills/MCP）、HCLS 域技能包（若后续单独入库）或 Reef（持续自改进闭环）混为同一项。
