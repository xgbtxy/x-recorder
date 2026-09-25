# Scenario GameDev OS：开源游戏制作 Agent Skills（+ Scenario MCP）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Scenario_gg/status/2103460573895659982
- 作者 / 频道：@Scenario_gg
- 发布时间：2026-09-25 12:24 UTC（约 2026-09-25 20:24 CST）

## 要点

- 宣布开源 **GameDev OS**：称把整套游戏制作流水线做成 Agent Skills（帖称 64 skills / 9 角色：概念艺术、3D、关卡、音频、预告片等）。
- 可装入口：`npx skills add scenario-labs/skills`（可 `--skill "*"` 或按名挑选）；skills.sh 目录可见。
- Skills 需配合 **Scenario MCP**：`claude mcp add --transport http scenario https://mcp.scenario.com/mcp`（或把该 URL 配进任意 MCP 客户端，OAuth/API key）。

## 落地链接（可选）

- 仓库：https://github.com/scenario-labs/skills
- skills.sh：https://www.skills.sh/scenario-labs/skills
- MCP 文档：https://mcp.scenario.com/docs

## 价值判断

- 为什么值得记：可 `npx skills` 安装的垂直 skills 包 + 官方 MCP，落地点明确，偏创意/游戏资产而非泛营销号。
- 风险 / 待核实：技能数量/效果「待核实」；生成能力依赖 Scenario 账号与付费额度；宣传口径偏强，以 README 为准。

## 原文摘要（可选）

摘要：@Scenario_gg 称开源 GameDev OS，GitHub skills 仓提供多角色游戏制作 skills，供 coding agent 使用。

## 与其他条目的关系（可选）

与已入库 skills CLI / Cursor Skills 不同：本条是具体垂直 skills 包 + Scenario MCP，非 CLI 本身。
