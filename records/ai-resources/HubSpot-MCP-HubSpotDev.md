# HubSpot MCP：CRM 远程 MCP（Cursor / Claude 等）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/HubSpotDev/status/1919845598779396160
- 作者 / 频道：@HubSpotDev
- 发布时间：2025-05-06 20:03:54 UTC（约 2025-05-07 04:03 CST）

## 要点

- HubSpot 官方宣布 **HubSpot MCP server** 进入 public beta：MCP 兼容客户端（Cursor、Anthropic Claude 等）可与 HubSpot CRM 数据交互。
- 可动手入口：开发者文档与远程端点线索 `https://mcp.hubspot.com`（OAuth 2.1 + PKCE；需在账户内创建 MCP auth app）。另有本地 Developer MCP（`hs mcp setup`）面向 App/CMS 开发，与 CRM 远程面不同。
- 属未入库的企业 CRM 垂直 MCP（非 Salesforce DX / Notion 协作面）。

## 落地链接（可选）

- 总览：https://developers.hubspot.com/ai-tools/mcp
- 远程 CRM MCP 文档：https://developers.hubspot.com/docs/apps/developer-platform/build-apps/integrate-with-the-remote-hubspot-mcp-server
- 远程端点线索：`https://mcp.hubspot.com`（以文档为准）

## 价值判断

- 为什么值得记：官方 CRM 垂直 MCP 产品入口，文档与端点可开，补 HubSpot 企业面。
- 风险 / 待核实：OAuth / MCP auth app 与权限范围以控制台为准；写操作改真实 CRM；托管 CRM 面未见本条对应独立开源仓星数；mcp.hubspot.com 匿名常 401（预期）；效果待核实。

## 原文摘要（可选）

摘要：官方称 HubSpot MCP server 已 public beta，可供 Cursor、Claude 等 AI 客户端对接 HubSpot 数据。

## 与其他条目的关系（可选）

非 Salesforce DX MCP（已入库他 CRM/平台开发面）；同账号 skills 旁路帖、工作坊扩散帖勿另开产品条。本帖为 CRM MCP 产品入口候选。
