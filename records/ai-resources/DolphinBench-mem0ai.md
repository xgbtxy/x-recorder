# DolphinBench：Agent 记忆 Pareto（准确率 × 成本 × 延迟）评测

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/mem0ai/status/2102438126941876590
- 作者 / 频道：@mem0ai
- 发布时间：2026-09-22 16:41:25 UTC（约 2026-09-23 00:41 CST）

## 要点

- mem0 官号发布 **DolphinBench**：用长历史后的**任务动作**评测 Agent 记忆，而非问答式 quiz；把准确率、成本、延迟放到同一板面。
- 设计宣称含多知识工作 persona、约 500k token 历史/人、约 200 任务/人，并以「有历史成功 / 无历史失败」校验任务依赖记忆——规模与协议 **待核实**。
- 可动手：站点 `dolphinbench.ai`、GitHub `mem0ai/dolphinbench`、arXiv `2609.24971`、排行榜 / run 入口。

## 落地链接（可选）

- 站点：https://dolphinbench.ai/
- 仓库：https://github.com/mem0ai/dolphinbench
- arXiv：https://arxiv.org/abs/2609.24971
- 排行榜：https://dolphinbench.ai/leaderboard/

## 价值判断

- 为什么值得记：**新评测轴（Agent 记忆 × 成本/延迟 Pareto）**，与 Terminal-Bench / Toolathlon / AgencyBench / AutomationBench 等轴互补；官号 + 仓库/站点/论文可核。
- 风险 / 待核实：GitHub ★约 29（2026-09-26）；官方结果与 harness（Hermes / Claude Code 等）版本以站点/仓库为准；勿与 mem0 产品营销混为一谈。

## 原文摘要（可选）

摘要：@mem0ai 宣布 DolphinBench，批评记忆评测多为 quiz，主张按长历史后动作打分，并同时报告准确率、成本与延迟。

## 与其他条目的关系（可选）

非 Terminal-Bench 4.0 / Toolathlon / SWE-Bench-Pro / AutomationBench-AA / AgencyBench / Long-Horizon-Terminal-Bench；本条是 **记忆系统 Pareto 评测**。未开 Qwen3.8。
