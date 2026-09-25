# GitLab MCP：19.4 扩展流水线 / MR / 漏洞工具（治理同轨）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/gitlab/status/2101008794184528304
- 作者 / 频道：@gitlab
- 发布时间：2026-09-18 18:01:46 UTC（约 2026-09-19 02:01 CST）

## 要点

- GitLab 官方宣布 **19.4** 为 MCP server 增加一批可动手工具：跑/重试流水线、开/更 MR、审评、仓库树与提交、工作项，以及 Ultimate 上的漏洞列表/处置（beta）。
- 强调「更宽工具面」与「同一套治理」：只读默认可自动；写入/合并/删除仍走团队选定的审批人。
- 可动手入口：博文与 MCP tools / tool governance 文档（帖内链 about.gitlab.com/blog/new-mcp-tools-for-automation/）。

## 落地链接（可选）

- 博文：https://about.gitlab.com/blog/new-mcp-tools-for-automation/
- MCP server 文档：https://docs.gitlab.com/user/model_context_protocol/mcp_server/
- MCP tools 文档：https://docs.gitlab.com/user/model_context_protocol/mcp_server_tools
- 工具治理：https://docs.gitlab.com/user/ai-governance/tool-governance
- 产品线：GitLab MCP server（随 GitLab 实例/套餐；漏洞工具需 Ultimate）

## 价值判断

- 为什么值得记：未入库的 DevOps/平台工程垂直 MCP，补流水线与 MR 闭环，且突出 Agent 权限治理。
- 风险 / 待核实：新工具集为 beta；写操作会改真实仓库/流水线；效果与工具完整列表以文档为准；星数不适用（产品 MCP，非独立开源仓主条）。

## 原文摘要（可选）

摘要：官方称 19.4 新增 MCP 工具，使任意 Agent（内部或第三方）在同一治理规则下跑流水线、开 MR、分诊漏洞。

## 与其他条目的关系（可选）

非 GitHub Remote MCP / Linear MCP Inbox / Atlassian Rovo（竞品协作/工单面，可并列）；非 SWE-Bench / Harbor 评测条。
