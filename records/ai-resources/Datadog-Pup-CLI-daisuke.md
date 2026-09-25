# Datadog Pup CLI：给 Agent 用的 Datadog 命令行伴侣

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/daisuke/status/2024506290421260366
- 作者 / 频道：@daisuke
- 发布时间：2026-02-19 15:28:07 UTC（约 2026-02-19 23:28 Asia/Shanghai）

## 要点

- **Pup**：面向 AI agent 的 Datadog CLI（官方仓库 `DataDog/pup`），覆盖 monitors / logs / metrics / RUM / APM 等大量产品面命令。
- Agent 友好：自描述命令、`pup agent schema` 动态拉 schema、默认结构化 JSON/YAML；OAuth + PKCE，减少长期 API Key。
- 可与 Datadog MCP 互补：MCP 偏对话式 IDE，Pup 偏 shell / CI / 自动化 harness；另有 `pup skills install` 等 skills 安装路径（以仓库 README / 文档为准）。

## 落地链接（可选）

- 仓库：https://github.com/DataDog/pup
- 文档：https://docs.datadoghq.com/cli/
- 产品博文：https://www.datadoghq.com/blog/give-your-ai-agents-live-datadog-access-from-the-command-line/

## 价值判断

- 为什么值得记：可安装的 agent 向 observability CLI，落地明确；与本批 Datadog MCP 同厂不同形态，不重复条目主题。
- 风险 / 待核实：出处为个人账号转发式介绍而非 @datadoghq 官宣帖；星数约 1021（DataDog/pup，2026-09-26 核）；需 Datadog 权限；命令覆盖面以当前 `--help` / schema 为准。

## 原文摘要（可选）

摘要：@daisuke 分享 datadog-labs/pup（现官网仓为 DataDog/pup），称其为覆盖 33 个 Datadog 产品、200+ 命令的 AI agent CLI 伴侣。

## 与其他条目的关系（可选）

- 同厂：可与草稿 `Datadog-MCP-datadoghq.md` 交叉；一为托管 MCP，一为 CLI/skills。
