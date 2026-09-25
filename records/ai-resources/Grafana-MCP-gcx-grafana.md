# Grafana MCP Server + gcx CLI（可观测 Agent 入口）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/grafana/status/2082162797366935823
- 作者 / 频道：@grafana
- 发布时间：2026-07-28 17:54:30 UTC（约 2026-07-29 01:54 Asia/Shanghai）

## 要点

- Grafana 官方宣布 **Grafana MCP server** 与 **gcx**（面向 Agent 的 Grafana CLI）一般可用（GA），方便编码 Agent 直接查遥测、管仪表盘/告警等资源。
- OSS：`grafana/mcp-grafana` 可本地跑（需 `GRAFANA_URL` + Service Account Token）；Cloud 另有托管端点 `https://mcp.grafana.com/mcp`（OAuth / Streamable HTTP）。
- gcx 面向 Claude Code / Copilot / Cursor 等 Agent，把仪表盘、告警规则、数据源等当代码操作；与已入库 Datadog/Sentry MCP 同赛道但不重复。

## 落地链接（可选）

- OSS 仓库：https://github.com/grafana/mcp-grafana
- OSS 文档：https://grafana.com/docs/grafana/latest/developer-resources/mcp/
- Cloud MCP：https://grafana.com/docs/grafana-cloud/ai-tools/mcp-servers/cloud-mcp/
- gcx 文档：https://grafana.com/docs/grafana/latest/as-code/observability-as-code/grafana-cli/gcx/
- 博文：https://grafana.com/blog/telemetry-driven-development-how-to-gain-confidence-in-your-coding-agents-behavior-with-gcx-and-grafana-mcp/

## 价值判断

- 为什么值得记：可观测垂直 MCP + Agent CLI 双入口，官方文档齐全，可动手落地。
- 风险 / 待核实：星数约 3497（grafana/mcp-grafana，2026-09-26 核）；需 Grafana 实例权限；Cloud 托管与 OSS 能力/鉴权路径不同。

## 原文摘要（可选）

摘要：官方称可用 gcx CLI 与 Grafana MCP server（均已 GA）给代码与 Agent 增加对 Grafana 遥测的信心，并附博文与 demo 链接。

## 与其他条目的关系（可选）

与已入库 Datadog MCP、Sentry MCP Monitoring 同属可观测 MCP，产品不同未重复。
