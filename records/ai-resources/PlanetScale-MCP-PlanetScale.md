# PlanetScale MCP：托管 DB MCP（Claude Connector / Insights）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/PlanetScale/status/2027074286394167793
- 作者 / 频道：@PlanetScale
- 发布时间：2026-02-26 17:32:25 UTC（约 2026-02-27 01:32 CST）

## 要点

- PlanetScale 官方称托管 **PlanetScale MCP server** 已可作为 Claude Connector：在 Claude Desktop / Claude Web 中连接后，可查询数据库、拉取性能洞察并生成组织级报告。
- 可动手入口：文档 `planetscale.com/docs/connect/mcp`；托管端点线索 `https://mcp.pscale.dev/mcp/planetscale`（以文档为准，OAuth）。
- 属未入库的企业数据库垂直 MCP（非 Neon / MongoDB Atlas / Prisma）。

## 落地链接（可选）

- 文档：https://planetscale.com/docs/connect/mcp
- 博文：https://planetscale.com/blog/introducing-planetscale-mcp-server
- 托管端点线索：`https://mcp.pscale.dev/mcp/planetscale`（以文档为准）

## 价值判断

- 为什么值得记：官方托管 DB MCP + Claude Connector，文档可开，补 PlanetScale 垂直入口。
- 风险 / 待核实：写查询需授权与人工确认策略；Insights / 权限范围以控制台为准；托管服务未见本条对应独立开源仓星数；mcp.pscale.dev 对 GET/HEAD 常 405（预期）；效果待核实。

## 原文摘要（可选）

摘要：官方宣布 PlanetScale MCP 可作为 Claude Connector 使用，用于查库、性能洞察与组织报告。

## 与其他条目的关系（可选）

非 Neon MCP / MongoDB Atlas MCP / Prisma MCP（已入库他库）；同账号 Insights 自动化修慢查询帖属能力扩散，勿与本产品条合并为另一条产品。
