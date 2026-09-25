# AgencyBench：百万 token 长程真实场景 Agent 评测（ACL2026）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/rohanpaul_ai/status/2014934941226692747
- 作者 / 频道：@rohanpaul_ai
- 发布时间：2026-01-24 05:35:00 UTC（约 2026-01-24 13:35 CST）

## 要点

- 社区转帖介绍 **AgencyBench**（ACL2026 Main）：面向长程真实场景的自主 Agent 评测，宣称约 138 任务 / 32 场景，单次运行平均约 1M token、约 90 tool calls。
- 评测流水线宣称含用户模拟器 + Docker 沙箱的视觉/功能 rubric；闭源相对开源分数更高（帖文约 48.4% vs 32.1%）——效果数字 **待核实**。
- 可动手：GitHub `GAIR-NLP/AgencyBench`、站点 `agencybench.opensii.ai`、arXiv `2601.11044`。

## 落地链接（可选）

- 仓库：https://github.com/GAIR-NLP/AgencyBench
- 站点：https://agencybench.opensii.ai/
- arXiv：https://arxiv.org/abs/2601.11044

## 价值判断

- 为什么值得记：**新评测轴（超长上下文 + 多步真实交付物）**，与 Terminal-Bench / AutomationBench 等轴互补；落地仓库/站点可核。
- 风险 / 待核实：**社区转、非官宣**（出处为 @rohanpaul_ai 转述，非 GAIR 官号；落地以 GitHub/站点/arXiv 为准）；仓库 ★约 101（2026-09-26）；分数与 harness 版本以官方仓库/站点为准。

## 原文摘要（可选）

摘要：@rohanpaul_ai 介绍 AgencyBench 论文要点：长任务、1M token 级、自动用户模拟与 Docker 打分，并对比开闭源差距。

## 与其他条目的关系（可选）

非 Terminal-Bench 4.0 / Toolathlon / SWE-Bench-Pro / AutomationBench-AA / Long-Horizon-Terminal-Bench；本条是 **1M-token 长程真实场景评测**。
