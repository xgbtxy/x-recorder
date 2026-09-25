# Sentry MCP Server Monitoring（监控你的 MCP 服务）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/sentry/status/1970911516716306813
- 作者 / 频道：@sentry
- 发布时间：2025-09-24 18:01:38 UTC（约 2025-09-25 02:01 Asia/Shanghai）

## 要点

- Sentry 宣布 **MCP Server Monitoring** GA：给自建 / 第三方 MCP server 包一层，监控工具调用与链路（帖中称 one-line wrap）。
- 与「把 Sentry 问题喂给 coding agent」的 **Sentry MCP**（`mcp.sentry.dev`）是不同产品面：本条是「观测 MCP 服务本身」。
- 可动手：官方 Insights/AI MCP 文档；若要让 agent 读 Sentry issue，另见托管端点 `https://mcp.sentry.dev/mcp` 与仓库 `getsentry/sentry-mcp`（可另条收录）。

## 落地链接（可选）

- MCP Monitoring 文档：https://docs.sentry.io/product/insights/ai/mcp/
- （相关）Sentry MCP 托管页：https://mcp.sentry.dev/
- （相关）Sentry MCP 仓库：https://github.com/getsentry/sentry-mcp
- Sentry MCP 产品文档：https://docs.sentry.io/product/sentry-mcp/

## 价值判断

- 为什么值得记：补「MCP 可观测」缺口；官方 X 可核、文档可开；库内尚无 Sentry MCP 相关条目。
- 风险 / 待核实：星数 相关仓 getsentry/sentry-mcp 约 861（2026-09-26 核；本条主体为 Monitoring 产品，非该仓本体）；Monitoring 与 Hosted MCP 易混淆，入库标题已区分；SDK/语言支持面以文档为准。

## 原文摘要（可选）

摘要：@sentry 称 MCP Server Monitoring 已 GA，一行包装即可监控 MCP server 全链路，并指向演示账号线程。
