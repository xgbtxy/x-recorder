# Stripe MCP：官方 MCP，让 Agent 查文档并调 Stripe API

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/StripeDev/status/1892685153987592526
- 作者 / 频道：@StripeDev
- 发布时间：2025-02-20 21:17 UTC（约 2025-02-21 05:17 CST）

## 要点

- Stripe 开发者账号宣布官方 **Stripe MCP server**，可在 Cursor 等 MCP 客户端里检索 Stripe 知识并调用 Stripe API。
- 帖内给出可执行入口示例：`npx -y @stripe/mcp --tools=all --api-key=STRIPE_SECRET_KEY`（具体参数以当前文档为准）；并指向 GitHub MCP 目录（历史路径 `stripe/agent-toolkit/...` 现重定向至 `stripe/ai/tools/modelcontextprotocol`）。
- 现亦提供托管端点（文档常见 `https://mcp.stripe.com`）与 OAuth / Agent API Key；写操作需人工确认等安全项以文档为准。

## 落地链接（可选）

- 文档：https://docs.stripe.com/mcp
- 仓库（MCP 路径）：https://github.com/stripe/ai/tree/main/tools/modelcontextprotocol
- npm：`@stripe/mcp`（版本/星数「待核实」）

## 价值判断

- 为什么值得记：一线支付平台官方 MCP，安装命令明确，属于可装入口而非纯营销。
- 风险 / 待核实：需 Stripe 密钥 / OAuth；写工具可改生产数据，务必最小权限与人工确认；星数/调用量「待核实」。

## 原文摘要（可选）

摘要：StripeDev 介绍可在 Cursor 使用的 Stripe MCP，并给出 `npx @stripe/mcp` 启动示例与 GitHub 路径。
