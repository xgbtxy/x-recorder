# Prisma MCP：给 Agent 管 Prisma Postgres 的官方 MCP

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/prisma/status/1905590716480585815
- 作者 / 频道：@prisma
- 发布时间：2025-03-28 12:00 UTC（约 2025-03-28 20:00 CST）

## 要点

- 官方帖宣布 **Prisma MCP server**：让 Cursor / Windsurf 等 agent 能开通与管理 Prisma Postgres。
- 现已有公开文档与仓库：远程入口 `https://mcp.prisma.io/mcp`（首次需 Prisma Console 鉴权）；亦支持 local MCP；示例可用 `npx -y mcp-remote https://mcp.prisma.io/mcp`。
- 工具面含列库、建连、备份/恢复、跑 SQL、introspect schema 等（以当前 README/文档为准）。

## 落地链接（可选）

- 文档：https://www.prisma.io/docs/ai/tools/mcp-server
- 仓库：https://github.com/prisma/mcp
- 远程 MCP：https://mcp.prisma.io/mcp

## 价值判断

- 为什么值得记：数据库侧官方可装 MCP，落地命令清晰，与 coding agent 工作流直接相关。
- 风险 / 待核实：出处帖为早期邀测口径，现已公开文档——能力/星数「待核实」；远程端未登录会 401 属预期；写库工具需严控权限。

## 原文摘要（可选）

摘要：@prisma 称在做 Prisma MCP，供 agent 开通/管理 Prisma Postgres，并邀请回复试用。

## 与其他条目的关系（可选）

与 datasette-mcp / Supabase Agent Skills 同属数据侧入口，但产品与鉴权路径不同，非换名重交。
