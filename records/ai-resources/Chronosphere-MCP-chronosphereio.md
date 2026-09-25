# Chronosphere MCP Server（GA · 只读可观测）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/chronosphereio/status/1988645524417790169
- 作者 / 频道：@chronosphereio
- 发布时间：2025-11-12 16:30:14 UTC（约 2025-11-13 00:30 Asia/Shanghai）

## 要点

- Chronosphere 官方宣布 **MCP Server GA**：只读，把指标 / 日志 / Trace / Dashboard / Monitor 等接到 Claude、Cursor 等 MCP 客户端。
- 可 **托管**（租户端点形如 `https://TENANT.chronosphere.io/api/mcp/mcp`）或 **开源自托管**（Go，GitHub `chronosphereio/chronosphere-mcp`）；鉴权用 API Token 或 OAuth。
- 帖文强调 Temporal Knowledge Graph 提供上下文；与已入库 Datadog/Sentry 不同厂商。

## 落地链接（可选）

- 公告：https://chronosphere.io/learn/announcing-the-chronosphere-mcp-server/
- 文档：https://docs.chronosphere.io/integrate/mcp-server
- 仓库：https://github.com/chronosphereio/chronosphere-mcp

## 价值判断

- 为什么值得记：另一家可观测厂商官方 MCP，托管 + OSS 双路径，可动手。
- 风险 / 待核实：星数约 8（chronosphereio/chronosphere-mcp，2026-09-26 核）；只读限制；需 Chronosphere 租户与 Token。

## 原文摘要（可选）

摘要：官方称 Chronosphere MCP Server 已 GA，强调安全只读、MCP 开放标准、托管或开源自托管，以及 Temporal Knowledge Graph 上下文。

## 与其他条目的关系（可选）

可观测 MCP 批次候选；产品与 Datadog/Sentry/Grafana/New Relic/PagerDuty 不重复。
