# PagerDuty MCP Server（事件/值班 Agent 入口）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/pagerduty/status/2099963502710440067
- 作者 / 频道：@pagerduty
- 发布时间：2026-09-15 20:48:09 UTC（约 2026-09-16 04:48 Asia/Shanghai）

## 要点

- PagerDuty 官方 **MCP**：本地 `uvx pagerduty-mcp` / Docker，以及托管 `https://mcp.pagerduty.com/mcp`（OAuth 或 API Key）。
- 工具覆盖 Incident、On-call、Service、Schedule、Status Page 等；默认可读，写工具需显式开启。
- 帖文新增能力：直播 Incident 的 **blast radius** 依赖/影响分析，以及频道内 **AI 起草事后复盘**（与 Slackbot MCP Client 等场景演示）。

## 落地链接（可选）

- 支持文档：https://support.pagerduty.com/main/docs/pagerduty-mcp-server
- 开发者文档：https://developer.pagerduty.com/docs/mcp
- 仓库：https://github.com/PagerDuty/pagerduty-mcp-server

## 价值判断

- 为什么值得记：事件管理垂直 MCP，本地 + 托管双路径，和日志/指标类 MCP 互补。
- 风险 / 待核实：星数约 79；GitHub 仓已 archived（PagerDuty/pagerduty-mcp-server，2026-09-26 核），以官方文档与托管端点为准；写操作与 blast-radius/复盘效果需自测；需 PagerDuty 账号权限。

## 原文摘要（可选）

摘要：官方宣布 MCP 能力扩展，强调 Incident 爆炸半径分析与 AI 起草事后复盘，并提到与 Slackbot MCP Client 的 Dreamforce 演示。

## 与其他条目的关系（可选）

偏 Incident/On-call，与 Datadog/Sentry/Grafana 等遥测 MCP 互补，未重复。
