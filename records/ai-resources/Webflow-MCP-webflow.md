# Webflow MCP：站点/CMS/画布 Agent 远程 MCP（互动与 Cloud 调试增量）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/webflow/status/2102109983433470157
- 作者 / 频道：@webflow
- 发布时间：2026-09-21 18:57:30 UTC（约 2026-09-22 02:57 CST）

## 要点

- Webflow 官方称 MCP 可更深介入**线上站点**：IX3/@greensock 互动、单次请求内排序/过滤 CMS、部署与 Webflow Cloud 应用调试，而无需离开当前 AI 客户端。
- 可动手入口：远程 MCP（文档所述 `https://mcp.webflow.com/sse` 等 / Claude·Cursor 连接器）；开源仓 webflow/mcp-server；开发者文档 developers.webflow.com/data/docs/ai-tools。
- 属未入库的垂直建站/CMS MCP；本仓尚无 Webflow 条，本帖作为产品入口（含能力增量说明）。

## 落地链接（可选）

- 帖内博文：https://webflow.com/blog/mcp-interactions
- 文档：https://developers.webflow.com/data/docs/ai-tools
- 仓库：https://github.com/webflow/mcp-server
- 远程线索：`https://mcp.webflow.com/sse`（以文档为准）

## 价值判断

- 为什么值得记：官方建站 MCP，文档与连接器可开，适合 Agent 改 CMS/画布/部署。
- 风险 / 待核实：需站点 Owner/Admin 授权；Designer 工具依赖 Companion App 保持连接；写操作改真实站点；效果待核实；webflow/mcp-server ★141（2026-09-26 gh api）。

## 原文摘要（可选）

摘要：官方介绍 Webflow MCP 在互动、CMS 过滤与 Cloud 调试上的更深能力，并链到博文。

## 与其他条目的关系（可选）

非 Figma MCP / Remotion Skills（设计/动画面不同）；非 Cloudflare API MCP。同账号 MCP eval harness 帖（status/2099944843958984731）属「Webflow 场景下的 MCP 评测脚手架」，若另收应标交叉、勿与本产品条合并为一条增量。
