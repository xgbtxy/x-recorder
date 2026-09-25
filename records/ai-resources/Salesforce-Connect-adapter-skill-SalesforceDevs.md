# Salesforce Connect adapter skill：用自然语言生成自定义 Connect Apex 适配器

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/SalesforceDevs/status/2102080476957614405
- 作者 / 频道：@SalesforceDevs
- 发布时间：2026-09-21 17:00:15 UTC（约 2026-09-22 01:00 CST）

## 要点

- Salesforce Developers 介绍 **`platform-salesforce-connect-adapter-generate`** Skill：让编码 Agent 根据自然语言 API 描述生成自定义 **Salesforce Connect** Apex 适配器（`DataSource.Provider` / `Connection`），减少手写与幻觉。
- 可与 Headless 360 MCP 等配合做外部数据源注册；需 Connect 许可、Salesforce CLI 等——效果与覆盖 API 形态 **待核实**。
- 可动手：`npx skills add forcedotcom/sf-skills`（库内含该 skill；Agentforce Vibes 预装）；博客说明端到端流程。

## 落地链接（可选）

- 仓库：https://github.com/forcedotcom/sf-skills
- Skill 路径：https://github.com/forcedotcom/sf-skills/tree/main/skills/platform-salesforce-connect-adapter-generate
- 博客：https://developer.salesforce.com/blogs/2026/09/build-custom-salesforce-connect-adapters-smarter-with-salesforce-skills
- 帖内短链：https://sforce.co/4rg8xQL

## 价值判断

- 为什么值得记：**可装垂直 Skill**（Connect 集成轴），官号 + `npx skills add` 入口清晰；补已入库 Salesforce DX MCP 之外的 Skills 产品轴。
- 风险 / 待核实：sf-skills 仓 ★约 1033（2026-09-26）；需 Connect 许可与 org 权限；生成代码仍需测试覆盖后再上生产；博客对部分爬虫 403，以浏览器打开为准。

## 原文摘要（可选）

摘要：@SalesforceDevs 称新 Connect adapter generation skill 可把自然语言 API 描述变成可部署的自定义 Apex 适配器，并指向入门链接。

## 与其他条目的关系（可选）

同厂已入库 **Salesforce DX MCP**（工具调用 / CLI 开发面）；本条是 **sf-skills 库内 Connect 适配器生成 Skill**，产品轴为 Skills 而非 MCP。非 Stitch MCP 第二棒。同库另有 Metadata API Context 等 skill，本条只收 Connect 适配器这一可核新帖。
