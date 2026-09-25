# Square MCP：Block/Square 官方商务 API MCP（远程 + 本地）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/jack/status/1915942871792029770
- 作者 / 频道：@jack（帖内指向 @Square / github.com/square/square-mcp-server）
- 发布时间：2025-04-26 01:35:51 UTC（约 2025-04-26 09:35 CST）

## 要点

- Jack Dorsey 发帖公布 **Square MCP server** 开源仓，把 AI 客户端接到 Square REST API（顾客、订单、商品等，以文档工具列表为准）。
- 可动手入口：远程托管 `https://mcp.squareup.com/sse`（OAuth，推荐；亦见 `/mcp`）；本地 `npx square-mcp-server start`（可用沙箱 `SANDBOX=true`）。
- 属未入库的垂直支付/零售 MCP，不是已入库的 Stripe / PayPal Remote MCP。

## 落地链接（可选）

- 仓库（README 即主文档）：https://github.com/square/square-mcp-server
- npm：https://www.npmjs.com/package/square-mcp-server
- 远程端点（README）：`https://mcp.squareup.com/sse`（亦见 `/mcp`；匿名探测常 401）
- 注：`developer.squareup.com/docs/mcp` 于 2026-09-26 返回 404，不以该路径为准

## 价值判断

- 为什么值得记：官方可连的 Square 全 API 面 MCP，文档与远程端点可开，适合 Agent 做结账/库存/顾客面动作。
- 风险 / 待核实：官方标注 Beta；写操作会影响真实商户数据，务必沙箱先行；效果待核实；square/square-mcp-server ★108（2026-09-26 gh api）。

## 原文摘要（可选）

摘要：@jack 贴出 Square MCP server 的 GitHub 链接。

## 与其他条目的关系（可选）

非 Stripe MCP / PayPal Remote MCP 重复（竞品支付/商务面，可并列）；非 Cloudflare API MCP。同生态后续工程博文/分层技巧帖（如 @sudo_moot）视为同产品说明，不必再开条。
