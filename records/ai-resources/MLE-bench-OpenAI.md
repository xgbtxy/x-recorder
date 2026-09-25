# MLE-bench：OpenAI 机器学习工程 Agent 评测（Kaggle 竞赛轴）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/OpenAI/status/1844429536353714427
- 作者 / 频道：@OpenAI
- 发布时间：2024-10-10 17:27:23 UTC（约 2024-10-11 01:27 CST）

## 要点

- OpenAI 发布 **MLE-bench**：衡量 AI Agent 在 **机器学习工程** 上的表现，收录约 **75** 道源自 Kaggle 的竞赛任务（训练模型、数据准备、实验迭代等）。
- 与纯 coding / 终端 / 函数调用轴不同：强调端到端 ML 工程交付（奖牌率等指标见官文与论文，**具体 SOTA 待核实**）。
- 可动手：官网说明、GitHub `openai/mle-bench`、论文；可复现评测 harness。

## 落地链接（可选）

- 公告帖：https://x.com/OpenAI/status/1844429536353714427
- 官网：https://openai.com/index/mle-bench/
- 仓库：https://github.com/openai/mle-bench
- 论文：https://arxiv.org/pdf/2410.07095

## 价值判断

- 为什么值得记：可复现的 **ML 工程** 评测轴，官方 X + 开源码；补已入库 SWE-Bench Pro / Terminal-Bench / τ2 / BFCL / MCPMark / MLPerf / MentalHealth / VQ 等之外的 Kaggle/MLE 向能力。
- 风险 / 待核实：openai/mle-bench ★1753（2026-09-26 gh api）；竞赛数据与奖牌阈值可能随 Kaggle/harness 版本变化；当前榜数字待对照仓库 README。

## 原文摘要（可选）

摘要：@OpenAI 宣布 MLE-bench，用 75 项 Kaggle 向竞赛衡量 Agent 的机器学习工程能力，并给官网链。

## 与其他条目的关系（可选）

非 SWE-Bench Pro V2 / Terminal-Bench / τ2-bench / BFCL V4 / MCPMark / MLPerf Training / MentalHealthBench / VQ-bench / SWE-Serve；非 ADE-bench（dbt 数据分析工程，若后续单开）。
