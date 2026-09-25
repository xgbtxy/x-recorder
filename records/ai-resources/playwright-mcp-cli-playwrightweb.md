# Playwright MCP / CLI：给 Agent 的浏览器自动化（官方）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/playwrightweb/status/2101099626401067367
- 作者 / 频道：@playwrightweb
- 发布时间：2026-09-19 00:02:42 UTC（约 2026-09-19 08:02 CST）

## 要点

- 官方帖对比 **Playwright MCP** 与 **Playwright CLI**：任选其一即可给 agent 浏览器能力（WebMCP、页面内 find/grep、更瘦 snapshot、codegen、复用本机 Chrome 登录态等）。
- MCP 安装常见写法：`npx @playwright/mcp@latest`（或文档中的客户端一键配置）；文档入口见 Playwright Getting Started MCP。
- 非网安逆向线；面向通用 coding agent 浏览器操作。

## 落地链接（可选）

- MCP 文档：https://playwright.dev/docs/getting-started-mcp
- 仓库：https://github.com/microsoft/playwright-mcp
- CLI（相关）：https://github.com/microsoft/playwright-cli

## 价值判断

- 为什么值得记：新 MCP（非 CF/datasette/网安），官方可装、可对接 Cursor/Claude 等客户端。
- 风险 / 待核实：星数/版本待核实；headed 浏览器与扩展模式需本机权限；自动化站点可能触发风控。

## 原文摘要（可选）

摘要：Playwright 官方说明 MCP 与 CLI 共享新能力清单，任选入口给 agent。
