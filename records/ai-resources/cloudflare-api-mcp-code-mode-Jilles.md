# Cloudflare API MCP（Code Mode）：~2500 端点 ≈1k tokens

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/Jilles/status/2094833926879560031
- 作者 / 频道：@Jilles
- 发布时间：2026-09-01 17:05:02 UTC（约 2026-09-02 01:05 CST）

## 要点

- 作者演示 Cloudflare 官方 API MCP：用 **Code Mode**（仅 `search` / `execute` 两工具）把整站 API（约 2500 endpoints）塞进约 1k tokens 上下文。
- 视频链路：买域名 → 部署 React → agent 查错再部署；对应官方入口 `https://mcp.cloudflare.com/mcp`，仓库 `cloudflare/mcp`，OAuth 或 API token。
- 官方博客另开源 Code Mode SDK（Cloudflare Agents），可自建同类 MCP。

## 落地链接（可选）

- MCP 端点：https://mcp.cloudflare.com/mcp
- 仓库：https://github.com/cloudflare/mcp
- 博客：https://blog.cloudflare.com/code-mode-mcp/

## 价值判断

- 为什么值得记：可核验的实用 MCP（带 X status + GitHub），解决「大 API 工具表撑爆上下文」；本线 MCP 缺口优先。
- 风险 / 待核实：来源为社区演示帖而非 Cloudflare 官号首发；效果/星数「待核实」；写操作需授权，误操作面大，应用最小权限 token。

## 原文摘要（可选）

摘要：称 Cloudflare API MCP 的 Code Mode「sick」，并拍了从域名到部署修复的完整 agent 流程。
