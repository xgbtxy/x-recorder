# Neon MCP：托管 Postgres/平台 API 工具面（82 tools 更新）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/neondatabase/status/2097411958152855717
- 作者 / 频道：@neondatabase
- 发布时间：2026-09-08 19:49:13 UTC（约 2026-09-09 03:49 CST）

## 要点

- Neon 宣布托管 **Neon MCP** 接入同一平台工具目录：现暴露 **82** 个来自 `@neon/tools` 的 API tools（帖称 68 个为新增），并保留手写 SQL / migration / docs 工具。
- 文档入口：https://neon.com/docs/ai/neon-mcp-server ；开源实现 `neondatabase/mcp-server-neon`。
- 属数据库/平台 MCP 新面，不在已入库可观测/厂商 MCP 排除名单内（非 Datadog/Sentry/Grafana/NR/PD/Chronosphere 等）。

## 落地链接（可选）

- 文档：https://neon.com/docs/ai/neon-mcp-server
- 仓库：https://github.com/neondatabase/mcp-server-neon

## 价值判断

- 为什么值得记：可配置到 Claude/Cursor 等客户端的 Postgres 云平台 MCP，可动手。
- 风险 / 待核实：星数约 650（neondatabase/mcp-server-neon，2026-09-26 核）；工具数量与权限模型以文档为准；需 Neon 账号/API key，注意生产库写权限。

## 原文摘要（可选）

摘要：Neon 称同一 catalog 现挂在 Neon MCP 后，托管服务暴露 82 个 API tools。

## 与其他条目的关系（可选）

非 Prisma/Supabase Skills 等同仓；MCP 面未入库。
