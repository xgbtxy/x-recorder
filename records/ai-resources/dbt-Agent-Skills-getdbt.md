# dbt Agent Skills：分析工程垂直 Skills（官方可装）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/getdbt/status/2019501979395817790
- 作者 / 频道：@getdbt
- 发布时间：2026-02-05 20:02:47 UTC（约 2026-02-06 04:02 CST）

## 要点

- dbt Labs 官方开源 **dbt Agent Skills**：把分析工程 / Semantic Layer / 平台运维 / Core→Fusion 迁移等实践封装为可装 Skill，宣称让通用编码 Agent 更像资深 dbt 协作者。
- 与 dbt MCP 互补：MCP 提供工具与治理上下文，Skills 提供如何像从业者那样用这些工具；效果数字 **待核实**。
- 可动手：`npx skills add dbt-labs/dbt-agent-skills --global`；Claude Code 可用 `/plugin marketplace add dbt-labs/dbt-agent-skills` 后安装插件；仓库与官方博客可核。

## 落地链接（可选）

- 仓库：https://github.com/dbt-labs/dbt-agent-skills
- 博客：https://docs.getdbt.com/blog/dbt-agent-skills

## 价值判断

- 为什么值得记：**新垂直域（分析工程 / 数据建模）可装 Skills**，官号发帖 + GitHub/`npx skills add` 落地清晰；补已入库营销/游戏/观测等 Skills 之外的数据工程轴。
- 风险 / 待核实：仓库 ★约 726（2026-09-26 `gh api`）；ADE-bench 等对比提升幅度待核；生产仓与敏感数据场景需自控权限。

## 原文摘要（可选）

摘要：@getdbt 宣布开源 dbt Agent Skills，强调 MCP 给工具、Skills 教用法，并指向博客与 GitHub 仓库。

## 与其他条目的关系（可选）

非 Prisma/Azure/Obsidian/Marketing 等已入库 Skills；本条是 **dbt 分析工程垂直包**。非 MCP 单条（虽可与 dbt MCP 同用）。
