# Datadog MCP Server（含 Code Execution GA）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/datadoghq/status/2102849508073685485
- 作者 / 频道：@datadoghq
- 发布时间：2026-09-23 19:56:06 UTC（约 2026-09-24 03:56 Asia/Shanghai）

## 要点

- Datadog 官方托管 **MCP Server**，把日志 / 指标 / Trace / Incident 等可观测数据接到 Cursor、Claude Code、Codex、VS Code 等 MCP 客户端。
- 帖文宣布 **Code Execution for Datadog MCP Server** 正式 GA，宣称更准答案且「73% fewer input tokens / 40% fewer tool calls」（效果数字**待核实**）。
- 可动手入口：`claude mcp add --transport http datadog https://mcp.datadoghq.com/v1/mcp`（非 US1 站点需换区域域名）；亦有 `.mcp.json` 配置与官方示例 agent。

## 落地链接（可选）

- 文档：https://docs.datadoghq.com/bits_ai/mcp_server/
- 仓库 / 示例：https://github.com/datadog-ai-labs/mcp-server
- 用例博文：https://www.datadoghq.com/blog/datadog-mcp-server-use-cases/

## 价值判断

- 为什么值得记：可观测垂直 MCP，官方托管 + 文档齐全，和已入库的 Stripe/Notion/Linear 等公司 MCP 同赛道但未重复。
- 风险 / 待核实：星数 约 45（datadog-labs/mcp-server，2026-09-26 核）；token/tool-call 降幅为营销数字；需 Datadog 账号与站点权限；托管端点按区域不同。

## 原文摘要（可选）

摘要：官方称在 Datadog Summit 宣布 MCP Server 的 Code Execution GA，强调代理排查更准且更省 token/tool call。
