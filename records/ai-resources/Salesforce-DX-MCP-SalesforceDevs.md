# Salesforce DX MCP：给 Agent IDE 用的官方 Salesforce 开发 MCP

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/SalesforceDevs/status/1937587282619331071
- 作者 / 频道：@SalesforceDevs
- 发布时间：2025-06-24 19:03:01 UTC（约 2025-06-25 03:03 CST）

## 要点

- Salesforce Developers 宣布 **Salesforce DX MCP**，面向 Agentforce for Developers、Cursor、Claude Desktop 等 agentic IDE，做受信任的 Salesforce 开发侧工具调用。
- 可动手入口：npm 包 `@salesforce/mcp`（`npx -y @salesforce/mcp@latest` 一类接入）；帖内短链指向开发者博客说明。
- 属未入库的垂直 CRM/平台开发 MCP，不是 Stripe / HubSpot（未收）/ Prisma / Neon 数据面重复。

## 落地链接（可选）

- npm：https://www.npmjs.com/package/@salesforce/mcp
- 博客（帖内短链解析）：https://developer.salesforce.com/blogs/2025/06/level-up-your-developer-tools-with-salesforce-dx-mcp
- 短链原文：https://sforce.co/4k8gdiL
- 源码仓：https://github.com/salesforcecli/mcp

## 价值判断

- 为什么值得记：一线 CRM 平台官方 DX MCP，npm 可装，适合 Agent 连 Salesforce org 做元数据/数据/测试等开发动作。
- 风险 / 待核实：需已认证 Salesforce CLI org；写操作影响真实 org。博客页对部分爬虫返回 403，以浏览器打开为准。salesforcecli/mcp ★481（2026-09-26 gh api；npm `@salesforce/mcp`）；效果待核实。

## 原文摘要（可选）

摘要：官方称用 Salesforce DX MCP 提升开发工具，并指向博客介绍面向 Cursor/Claude Desktop 等的 MCP server。

## 与其他条目的关系（可选）

非 Stripe MCP / Prisma MCP / Neon MCP / MongoDB Atlas MCP；若后续另收 Hosted Salesforce MCP（面向业务数据的托管服务），应分条并写清 DX（本地/CLI 开发）与 Hosted（运行时数据）差异。
