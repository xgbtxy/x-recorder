# SkillsBench：评测 Agent 能否用好 Skills 的新轴

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/xdotli/status/2067006779255619912
- 作者 / 频道：@xdotli（BenchFlow / SkillsBench）
- 发布时间：2026-06-16 22:09:53 UTC（约 2026-06-17 06:09 CST）

## 要点

- 发布 **SkillsBench 1.1**：专测「Agent 装上 Skills 之后到底有没有用」——约 **87** 题、**8** 域，成对比较 no-Skills vs curated-Skills（Skill Lift）；并追踪 skill invocation。
- 自称全链路审计去错、剔除外依赖题到 `tasks-extra`；公开榜与论文报告平均 Skill Lift 约 +16.6pt、顶配置 with-skills 约 67%（**榜面数字待核实**）。
- 可动手：GitHub `benchflow-ai/skillsbench`、站点 `skillsbench.ai`、HF 数据集与 trajectory。

## 落地链接（可选）

- 公告帖：https://x.com/xdotli/status/2067006779255619912
- 仓库：https://github.com/benchflow-ai/skillsbench
- 站点 / 榜：https://www.skillsbench.ai/ 、https://www.skillsbench.ai/leaderboard
- 博客：https://www.skillsbench.ai/blogs/skillsbench-1-1
- 论文：https://arxiv.org/abs/2602.12670

## 价值判断

- 为什么值得记：新评测轴——**Skills 有效性 / Skill Lift**，避开已入库 SWE / Terminal / τ2 / BFCL / VQ / MLPerf / MentalHealth / MCPMark / MLE-bench / GameDevBench。
- 风险 / 待核实：仓库 ★约 1813（2026-09-26 `gh api`）；公开分数与 harness 版本需对照 README/v1.1；竞赛向 Skill Lift（Kaggle）帖勿重复开条。

## 原文摘要（可选）

摘要：@xdotli 宣布 SkillsBench 1.1——经端到端审计的 Agent Skills 评测，强调 Skill Lift 与 invocation 指标。

## 与其他条目的关系（可选）

非 skills CLI / vercel-labs/agent-skills 等**可装包**条目；本条是**评测 Skills 是否涨分**的基准。
