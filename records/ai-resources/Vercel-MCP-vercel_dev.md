# Vercel MCP：项目/部署/日志/文档的远程 MCP

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/vercel_dev/status/1954190678596157824
- 作者 / 频道：@vercel_dev
- 发布时间：2025-08-09 14:38 UTC（约 2025-08-09 22:38 CST）

## 要点

- Vercel 官方远程 MCP，帖文称已支持在 **Cursor** 内访问项目与部署、分析日志、搜索文档。
- 远程入口常见为 `https://mcp.vercel.com`（OAuth；GET 探测可能 405，属 MCP 端点常态）；文档见 Agent Resources。
- 可动手：按文档把 MCP URL 配进 Cursor/Claude 等客户端（changelog 链出配置说明）。

## 落地链接（可选）

- MCP 端点：https://mcp.vercel.com
- 文档：https://vercel.com/docs/agent-resources/vercel-mcp
- Changelog：https://vercel.com/changelog/cursor-now-supported-on-vercel-mcp

## 价值判断

- 为什么值得记：官方托管 MCP，直接服务「部署/日志/项目」Agent 工作流，少装本地进程。
- 风险 / 待核实：星数/效果「待核实」；写操作依赖 OAuth 权限，误操作面大，应用最小权限。

## 原文摘要（可选）

摘要：vercel_dev 宣布 Vercel MCP 已可在 Cursor 中使用，覆盖项目、部署、日志与文档搜索。
