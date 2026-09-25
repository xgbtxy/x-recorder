# Atlassian Rovo MCP：把 AI 客户端接到 Jira / Confluence（官方远程）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Atlassian/status/2031067692182941991
- 作者 / 频道：@Atlassian
- 发布时间：2026-03-09 18:00:47 UTC（约 2026-03-10 02:00 CST）

## 要点

- Atlassian 官方帖展示 **Rovo MCP server**，可在外部 AI 客户端里用自然语言访问、创建、更新 Jira 与 Confluence 内容（帖中联合 @awscloud Amazon Quick 演示）。
- 可动手入口：开发者文档与远程端点（OAuth；权限跟 Atlassian 云账号/站点策略走）。
- 属未入库的垂直协作/工单面 MCP，不是已入库的 Notion / Linear / GitHub / X Hosted MCP。

## 落地链接（可选）

- 产品页：https://www.atlassian.com/platform/remote-mcp-server
- 入门文档：https://developer.atlassian.com/cloud/rovo-mcp/guides/getting-started/
- 托管端点（文档所述）：`https://mcp.atlassian.com/v2/mcp`（对匿名 GET 常返回 401，属预期）

## 价值判断

- 为什么值得记：官方可连接的 Jira/Confluence MCP，文档与产品页可开，适合补协作套件垂直面。
- 风险 / 待核实：企业租户可能要管理员放行 AI 客户端；写操作会改真实工单/页面。星数不适用（托管服务）；效果待核实。

## 原文摘要（可选）

摘要：官方称可用 Rovo MCP + Amazon Quick，用自然语言读写 Jira/Confluence，并链到 Rovo MCP 能力页。

## 与其他条目的关系（可选）

非 Notion MCP / Linear MCP Inbox / GitHub Remote MCP / X Hosted MCP 等同仓重复；同属「官方托管垂直 MCP」线，产品面为 Atlassian 云协作。
