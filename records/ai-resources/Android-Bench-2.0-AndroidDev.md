# Android Bench 2.0：面向多日工程任务的 Agent/模型评测框架升级

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/AndroidDev/status/2100622197253398669
- 作者 / 频道：@AndroidDev
- 发布时间：2026-09-17 16:25:34 UTC（约 2026-09-18 00:25 CST）

## 要点

- Android 官方宣布 **Android Bench 2.0**：把评测从短任务拉到「多日」真实工程挑战——从零做应用/功能、跨平台代码库迁到 Android、复杂架构迁移等。
- 强调 agentic evaluation、多模态 UI 校验与 **continuous completion scoring**（看模型在哪些子任务上站住，而非只报总分）。分数与榜单名次 **待核实**。
- 可动手入口：官方 Bench 站点与方法论页；社区数据集仓 `android-bench/community-dataset`（星数 **待核实**）。

## 落地链接（可选）

- 博客：https://developer.android.com/blog/posts/android-bench-2-0-pushing-the-frontier-with-challenging-long-horizon-tasks
- Bench 站点：https://developer.android.com/bench
- 方法论 2.0：https://developer.android.com/bench/methodology/2
- 社区数据集：https://github.com/android-bench/community-dataset

## 价值判断

- 为什么值得记：官方 Android 工程向 long-horizon Agent 评测，补移动端/IDE 工程轴，不是通用 SWE 榜换皮。
- 风险 / 待核实：完整任务包与 runner 开放程度以官方页为准；社区数据集星数偏低，主落地仍是官方 leaderboard/方法论；效果数字 **待核实**。

## 原文摘要（可选）

摘要：@AndroidDev 介绍 Android Bench 2.0，面向从零构建与跨平台迁移等多日工程挑战。

## 与其他条目的关系（可选）

评测轴；勿与已入库 Terminal-Bench / SWE-Bench / AgencyBench / AutomationBench 混名。相对 Google 其他条目：本条是 **Android 工程评测框架**，不是 Cloud Plugin、也不是 Gemma/Antigravity 模型入口。
