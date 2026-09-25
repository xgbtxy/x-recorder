# Fastly MCP：CDN/边缘 CLI 封装的官方 MCP（非 Cloudflare）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/fastly/status/1952460057641095332
- 作者 / 频道：@fastly
- 发布时间：2025-08-04 20:02:07 UTC（约 2025-08-05 04:02 CST）

## 要点

- Fastly 官方发布 **Fastly MCP server**：将 Fastly CLI 能力封装为 MCP，可在 AI 助手中管理服务、purge 缓存、查看性能相关操作。
- 可动手入口：开源仓 `github.com/fastly/mcp`；博文与社区公告可开。认证优先用 `fastly profile`，文档不推荐依赖环境变量传 token。
- 属未入库的 CDN/边缘垂直 MCP（明确非 Cloudflare）。

## 落地链接（可选）

- 仓库：https://github.com/fastly/mcp
- 博文：https://www.fastly.com/blog/fastly-easier-than-ever-model-context-protocol-mcp-server
- 社区：https://community.fastly.com/t/fastly-mcp-server-is-here-control-fastly-with-ai/4162

## 价值判断

- 为什么值得记：官方 CDN MCP，仓与博文可开，补 Cloudflare 以外的边缘面入口。
- 风险 / 待核实：CLI 写操作影响线上服务与缓存；需有效 Fastly API 凭证；fastly/mcp ★39（2026-09-26 gh api）；效果待核实。

## 原文摘要（可选）

摘要：官方介绍 Fastly MCP 将 CLI 包成 MCP 接口，便于在 AI 工具里管服务与 purge。

## 与其他条目的关系（可选）

非 Cloudflare API MCP（已入库）；非「在 Fastly Compute 上自建安全 MCP」工程博文（若另收应标脚手架/教程，勿与本产品条合并）。
