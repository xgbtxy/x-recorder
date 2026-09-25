# next-devtools-mcp：把 Next.js 运行时接到 Coding Agent

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/gao_jude/status/1982942366727372843
- 作者 / 频道：@gao_jude
- 发布时间：2025-10-27 22:47 UTC（约 2025-10-28 06:47 CST）

## 要点

- 作者在 Next.js Conf 相关帖中介绍 **Next.js DevTools MCP**：让 AI agent 在编码任务中与框架「对话」（运行时错误/路由/日志等，以 README 为准）。
- 可装：`npx add-mcp next-devtools-mcp@latest` 或 MCP 配置里 `npx -y next-devtools-mcp@latest`；仓库 `vercel/next-devtools-mcp`，npm 包同名。
- 需要 Next.js 16+ 且本地 dev server 在跑（代理 `/_next/mcp`）；与已入库 Playwright MCP / Chrome DevTools MCP 互补，偏框架运行时而非通用浏览器。

## 落地链接（可选）

- 仓库：https://github.com/vercel/next-devtools-mcp
- npm：https://www.npmjs.com/package/next-devtools-mcp
- 演讲页：https://nextjs.org/conf/session/nextjs-for-ai-agents

## 价值判断

- 为什么值得记：官方仓 + npm 可装，专门打通 Next 开发态上下文，落地命令清楚。
- 风险 / 待核实：来源为演讲介绍帖非产品官号发版帖；星数/兼容客户端「待核实」；依赖本机 Next 16+ dev server。

## 原文摘要（可选）

摘要：gao_jude 分享 Next.js for AI agents 演讲回放，并点出 Next.js DevTools MCP 可让 agent 在编码时对接框架。
