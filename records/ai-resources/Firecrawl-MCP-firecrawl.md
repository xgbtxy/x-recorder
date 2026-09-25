# Firecrawl MCP：给 Agent 的网页搜索/抓取（官方）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/firecrawl/status/2066918976689754148
- 作者 / 频道：@firecrawl
- 发布时间：2026-06-16 16:21:00 UTC（约 2026-06-17 00:21 CST）

## 要点

- 官方帖称可无 API key 试用：搜索、抓取、页面交互，以及 PDF→markdown；入口覆盖 **MCP / CLI / API**。
- 托管 MCP 文档给出 keyless 与 OAuth/API key 路径；示例端点：`https://mcp.firecrawl.dev/v2/mcp`（keyless 限流）与 OAuth URL（以文档为准）。
- 本地/开源 MCP 仓库：`firecrawl/firecrawl-mcp-server`（可接 Cursor、Claude 等 MCP 客户端）。

## 落地链接（可选）

- MCP 文档：https://docs.firecrawl.dev/mcp-server
- 仓库：https://github.com/firecrawl/firecrawl-mcp-server
- 产品页：https://www.firecrawl.dev/mcp

## 价值判断

- 为什么值得记：新 MCP（非已入库 Playwright/CF/datasette），面向 Agent 的网页数据入口，可 keyless 试。
- 风险 / 待核实：星数/额度待核实；keyless 工具面与限流以文档为准；抓取目标站可能触发风控；商业 API 另计费。

## 原文摘要（可选）

摘要：Firecrawl 宣布免 key 试用搜索/抓取/PDF 解析，并称 MCP、CLI、API 已上线。
