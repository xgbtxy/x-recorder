# New Relic AI MCP Server（托管可观测）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/newrelic/status/1990876449075515478
- 作者 / 频道：@newrelic
- 发布时间：2025-11-18 20:15:08 UTC（约 2025-11-19 04:15 Asia/Shanghai）

## 要点

- New Relic 官方 **AI MCP Server**（托管）：把遥测 / 告警 / Incident 等可观测上下文接到 Cursor、Claude、VS Code、Gemini CLI 等 MCP 客户端。
- 区域端点示例：US `https://mcp.newrelic.com/mcp/`；另有 EU / JP 域名；鉴权支持 User API Key（`NRAK-…`）或 OAuth。
- 帖文场景是 Azure SRE Agent / Microsoft Foundry 的 agentic 集成，底层能力即该 MCP Server；文档含 Claude Desktop / VS Code 等配置样例。

## 落地链接（可选）

- 设置文档：https://docs.newrelic.com/docs/agentic-ai/mcp/setup/
- 产品博文：https://newrelic.com/blog/news/new-relic-ai-mcp-server-launch
- What’s New（Public Preview）：https://docs.newrelic.com/whats-new/2025/11/whats-new-11-05-mcp-server/

## 价值判断

- 为什么值得记：主流 APM/可观测厂商官方托管 MCP，可动手配置，补齐 Datadog/Sentry 之外的选择。
- 风险 / 待核实：星数不适用（托管为主；未另见主仓库，2026-09-26 核）；需 New Relic 账号与预览/功能开关；区域端点必须匹配账户区域。

## 原文摘要（可选）

摘要：官方宣布与 Microsoft Azure 的 agentic 集成，称由 New Relic AI MCP Server 为 Azure SRE Agent 与 Foundry 提供可观测洞察。

## 与其他条目的关系（可选）

与 Datadog MCP、Sentry MCP Monitoring 同赛道；本条为 New Relic 官方入口，未入库。
