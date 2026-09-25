# Box MCP：企业内容远程 MCP（含管理端工具治理）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Box/status/2092286094427787588
- 作者 / 频道：@Box
- 发布时间：2026-08-25 16:20:52 UTC（约 2026-08-26 00:20 CST）

## 要点

- Box 官方介绍 **Box MCP Server** 管理端控制：可在企业范围或按 AI 集成治理工具可见性，配置只读/读写，细到单个 tool；禁用后 Agent 运行时不可发现或调用。
- 产品本体为托管远程 MCP（文档所述 `https://mcp.box.com` 等，OAuth）；开发者文档与 Admin Console 启用流程可开。本帖强调治理增量，仍锚定未入库的 Box 内容 MCP 产品入口。
- 属未入库的企业内容平台垂直 MCP。

## 落地链接（可选）

- 文档：https://developer.box.com/guides/box-mcp
- 远程设置：https://developer.box.com/guides/box-mcp/remote
- 远程线索：`https://mcp.box.com`（以文档为准）
- 相关仓：https://github.com/box/mcp-server-box-remote

## 价值判断

- 为什么值得记：官方内容面 MCP + 可核对的管理治理能力，文档与端点可开。
- 风险 / 待核实：需管理员启用与 OAuth 应用配置；写工具改真实文件；box/mcp-server-box-remote ★6（2026-09-26 gh api）；mcp.box.com 匿名常 401（预期）；效果待核实。

## 原文摘要（可选）

摘要：官方强调 Agent 治理不止于「能访问什么」，介绍 Box MCP 管理端对工具级读写与发现的运行时强制控制。

## 与其他条目的关系（可选）

非 Dropbox Dash MCP（同内容检索面、产品不同）；同账号 AgentKit/合作方联宣帖、行业 demo/skill 帖属渠道或技巧扩散，勿另开产品条。本帖为产品治理增量，仍作 Box MCP 产品入口候选。
