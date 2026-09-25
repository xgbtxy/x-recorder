# Slack MCP：托管工作区 MCP（RTS + 权限模型）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/SlackHQ/status/2024948072212505008
- 作者 / 频道：@SlackHQ
- 发布时间：2026-02-20 20:43:36 UTC（约 2026-02-21 04:43 CST）

## 要点

- Slack 官方称 **Real-Time Search（RTS）API** 与 **MCP server** 已一般可用（GA）：开发者可把 AI 模型安全接到 Slack 对话、文件与 Canvas，并沿用既有权限模型。
- 可动手入口：托管端点线索 `https://mcp.slack.com/mcp`；开发者文档见 docs.slack.dev；博文说明 GA 与生态接入。
- 属未入库的企业协作垂直 MCP（非 Notion / Linear；非纯硬广渠道帖）。

## 落地链接（可选）

- 文档：https://docs.slack.dev/ai/slack-mcp-server
- GA 博文：https://slack.com/blog/news/mcp-real-time-search-api-now-available
- 远程端点线索：`https://mcp.slack.com/mcp`（以文档为准）

## 价值判断

- 为什么值得记：官方托管协作面 MCP + GA 口径，文档与端点可开。
- 风险 / 待核实：需工作区管理批准与 OAuth 应用；写消息/改 Canvas 影响真实工作区；托管服务未见本条对应独立开源仓星数；mcp.slack.com 匿名常 401（预期）；效果待核实。

## 原文摘要（可选）

摘要：官方宣布 RTS API 与 MCP server GA，开发者可在既有权限下把 Agent 接到 Slack 对话、文件与 Canvas。

## 与其他条目的关系（可选）

非 Slackbot「连接第三方 MCP」客户端扩散帖（同账号大量伙伴集成属渠道面，勿与本产品条合并为另一条）。本帖锚定 Slack 自有 MCP server 产品入口。
