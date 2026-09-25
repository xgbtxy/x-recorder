# Long-Horizon-Terminal-Bench（LHTB）：长程终端 Agent 稠密奖励评测轴

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/rosinality/status/2076572455854825894
- 作者 / 频道：@rosinality（社区转 arXiv；非仓库作者官宣）
- 发布时间：2026-07-13 07:40:28 UTC（约 2026-07-13 15:40 CST）

## 要点

- **Long-Horizon-Terminal-Bench（LHTB）**：约 **46** 个容器化长程终端任务；强调数百步、最长约 90 分钟量级执行，用隐藏/可重建 verifier 给**稠密部分奖励**，而非只看终局 pass/fail。
- 官方叙事相对已入库 Terminal-Bench：更强调长程规划、状态维持与中间进度；榜面与「最强模型仍低通关率」等数字 **待核实**。
- 可动手：GitHub `zli12321/LHTB`、HF 数据集 `IntelligenceLab/Long-Horizon-Terminal-Bench`、站点与 arXiv；评测需按仓库说明使用其 Harbor 补丁（continue-until-timeout 等）。

## 落地链接（可选）

- 仓库：https://github.com/zli12321/LHTB
- 数据集：https://huggingface.co/datasets/IntelligenceLab/Long-Horizon-Terminal-Bench
- 站点：https://zli12321.github.io/LHTB/
- 论文：https://arxiv.org/abs/2607.08964

## 价值判断

- 为什么值得记：新评测轴——**长程终端 + 稠密奖励/部分分**，避开已入库 Terminal-Bench 4.0 / SWE / Toolathlon / τ2 / BFCL / MCPMark / SkillsBench / Harbor 等。
- 风险 / 待核实：出处为社区转 arXiv（@rosinality，非作者官宣；未找到作者官方 X status，落地以 GitHub/HF/站点为准）；仓库 ★约 712（2026-09-26 `gh api`）；HF dataset likes 约 136（同日）；榜面版本与 harness 补丁差异大，复现须对照 README。

## 原文摘要（可选）

摘要：@rosinality 转发 arXiv:2607.08964，标注为 Long Horizon Terminal Bench。

## 与其他条目的关系（可选）

非 Terminal-Bench 4.0（短/中程终端）/ SWE-Bench Pro / Toolathlon；本条是 **长程稠密奖励终端** 评测。Harbor harness 条目勿与本评测轴重复开。
