# Auth0 MCP：Management API 本地 MCP + Skills，附模型对照评测

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/auth0/status/2103127841114038462
- 作者 / 频道：@auth0
- 发布时间：2026-09-24 14:22:06 UTC（约 2026-09-24 22:22 CST）

## 要点

- Auth0 官方帖：用同一套 Auth0 集成任务，对照「有无 Auth0 MCP + Skills」时各模型输出的正确性、安全与常见错误（偏可动手评测，不是空口榜）。
- 产品面：开源 **auth0-mcp-server** 把 LLM/Agent 接到 Auth0 Management API（自然语言建应用、部署 Actions、查日志等；本地跑、支持交互式租户登录，以 README 为准）。
- 属未入库的身份/鉴权垂直 MCP；帖同时带「MCP 专用对照评测」线索。

## 落地链接（可选）

- 帖内落地：https://auth0.com/agent-experience （由 bit.ly/4AmLDLB 解析）
- 仓库：https://github.com/auth0/auth0-mcp-server

## 价值判断

- 为什么值得记：可装的 Auth0 MCP + 官方给出的有无 MCP 对照评测入口，补身份面垂直能力。
- 风险 / 待核实：Management API 写操作影响真实租户，务必非生产先行；评测分数/样本以页面为准；auth0/auth0-mcp-server ★122（2026-09-26 gh api）。

## 原文摘要（可选）

摘要：官方称对多模型跑同一 Auth0 集成任务，对比启用 Auth0 MCP 与 Skills 前后的代码质量与安全问题，并链到 Agent Experience 页。

## 与其他条目的关系（可选）

非 MCPMark / τ2 / Harbor（通用或他域评测）；本条主体是 Auth0 产品 MCP，评测是同帖附带对照。非 Cloudflare / Stripe 等已入库垂直 MCP。
