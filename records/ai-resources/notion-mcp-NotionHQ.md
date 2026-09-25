# Notion MCP：官方远程 MCP（含 Custom Agents）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NotionHQ/status/2095923091134206448
- 作者 / 频道：@NotionHQ
- 发布时间：2026-09-05 01:12 CST（UTC+8）

## 关键点

- Notion 官方 MCP：把工作区上下文接到 ChatGPT / Claude / Cursor 等 MCP 客户端。
- 远程入口：`https://mcp.notion.com/mcp`（OAuth）；官方入门文档：developers.notion.com/guides/mcp。
- 本帖更新：Custom Agents 可通过 MCP 加入对话，在同一会话里调用有权限的自定义 Agent。
- 偏协作/知识库落地，适合给 coding agent 挂「公司 wiki」上下文。

## 落地链接（可选）

- 仓库 / 官网 / 文档：https://developers.notion.com/guides/mcp/get-started-with-mcp ；https://mcp.notion.com/mcp

## 价值判断

- 为什么值得记：官方可装远程 MCP，有明确文档与 OAuth 入口，非纯营销帖。
- 风险 / 待核实：MCP 根路径未登录返回 401 属预期；权限/破坏性写操作风险需在客户端侧收紧；功能范围以文档为准。

## 原文摘要（可选）

摘要：@NotionHQ 称 Custom Agents 现可通过 MCP 接入 ChatGPT、Claude、Grok Bot 等对话。

## 与其他条目的关系（可选）

与已入库 Cloudflare / datasette / Playwright / Firecrawl 等 MCP 并列，属 Notion 官方线。
