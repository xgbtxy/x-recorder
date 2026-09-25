# GitHub Remote MCP Server：官方远程 MCP（GA）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/GHchangelog/status/1963634192010379338
- 作者 / 频道：@GHchangelog
- 发布时间：2025-09-05 00:04 CST（UTC+8）

## 关键点

- GitHub 官方 Remote MCP Server 宣布正式可用（GA）；开源实现仓库：github/github-mcp-server。
- 远程入口常见为 `https://api.githubcopilot.com/mcp/`（HTTP MCP，OAuth 或 PAT）；亦提供本地版。
- 能力：读仓/搜代码、Issue/PR、Actions、安全告警等，供 VS Code / Cursor / Claude Desktop 等 MCP 宿主使用。
- VS Code 需较新版本（文档示例提到 1.101+）以支持 remote MCP + OAuth。

## 落地链接（可选）

- 仓库 / 官网 / 文档：https://github.com/github/github-mcp-server ；https://github.blog/changelog/2025-09-04-remote-github-mcp-server-is-now-generally-available/

## 价值判断

- 为什么值得记：官方可点装的远程 MCP，是 coding agent 接 GitHub 上下文的标准入口之一。
- 风险 / 待核实：企业策略/权限范围以 GitHub 文档与租户策略为准；宿主兼容性需本地确认。

## 原文摘要（可选）

摘要：Changelog 账号宣布 Remote GitHub MCP Server 正式可用，并链到 GitHub Blog changelog。
