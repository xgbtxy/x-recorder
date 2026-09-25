# datasette-mcp：给任意 Datasette 实例加 `/-/mcp`

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/simonw/status/2102916558712705427
- 作者 / 频道：@simonw
- 发布时间：2026-09-24 00:22:32 UTC（约 2026-09-24 08:22 CST）

## 要点

- Simon Willison 自述用 **datasette-mcp** 经 MCP 连上自己博客的 Datasette 备份，并已能在 ChatGPT iPhone App 里语音对话查库。
- 插件仓库 `datasette/datasette-mcp`：给 Datasette 挂只读 MCP（如 `execute_sql`）；博客称 0.2 为首个非 alpha 正式版。
- 可对接 Claude / ChatGPT 等 MCP 客户端；公共演示实例见作者站点文档。

## 落地链接（可选）

- 仓库：https://github.com/datasette/datasette-mcp
- PyPI：https://pypi.org/project/datasette-mcp/
- 发版笔记：https://simonwillison.net/2026/Sep/1/datasette-mcp/

## 价值判断

- 为什么值得记：一手作者 + 可装插件，把现有 SQLite/Datasette 数据变成 agent 工具，MCP 线可动手。
- 风险 / 待核实：来源帖侧重「语音对话演示」而非单独发版公告；星数/兼容客户端「待核实」；暴露 SQL 面需只读与鉴权。

## 原文摘要（可选）

摘要：作者说刚通过 datasette-mcp 用 ChatGPT iPhone 语音聊自己的博客 Datasette 备份。
