# Airtable MCP：把 AI 助手接到 Airtable 基地（官方托管）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/airtable/status/2103483184931369312
- 作者 / 频道：@airtable
- 发布时间：2026-09-25 13:54:06 UTC（约 2026-09-25 21:54 CST）

## 要点

- Airtable 官方帖介绍把 AI 助手接到 **Airtable MCP**，用自然语言查数、改记录。
- 可动手入口不在帖内短链，而在帮助中心与托管端点 `https://mcp.airtable.com/mcp`（OAuth 或个人访问令牌；权限跟用户在 Airtable 里的角色一致）。
- 属未入库的垂直数据面 MCP，不是已入库的 Supabase Skills，也不是 Neon / MongoDB / Prisma。

## 落地链接（可选）

- 文档：https://support.airtable.com/articles/9897799762-using-the-airtable-mcp-server
- 托管端点：https://mcp.airtable.com/mcp
- 帖内短链指向的是直播课页（非文档）：https://www.airtable.com/lp/resources/webinars/lets-build-live-airtable-mcp

## 价值判断

- 为什么值得记：官方可连接的表格/基地 MCP，文档和端点都能打开，适合补数据库以外的垂直 MCP。
- 风险 / 待核实：托管服务，未见本条对应独立开源仓星数；mcp.airtable.com/mcp 对 GET/HEAD 返回 405（预期，MCP 多为 POST）。帖子本身偏 webinar 引流，产品能力以文档为准。写操作会改真实基地数据；企业租户可能要管理员放行第三方集成。效果待核实。

## 原文摘要（可选）

摘要：官方称可以把 AI 助手接到 Airtable MCP，并链到一场现场搭建演示。

## 与其他条目的关系（可选）

非 Prisma / Supabase Skills / Neon / MongoDB Atlas 等同仓重复。
