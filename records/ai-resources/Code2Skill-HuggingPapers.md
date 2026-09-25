# Code2Skill：从开源仓库规模化合成可核验 Agent 程序技能库

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/HuggingPapers/status/2102008836865352067
- 作者 / 频道：@HuggingPapers（社区转、非官宣）
- 发布时间：2026-09-21 12:15:34 UTC（约 2026-09-21 20:15 CST）

## 要点

- 社区日报转介 **Code2Skill**：自动化流水线把大量开源仓库单元抽成带出处的程序化 skill 记录（帖文称约 1.9 万仓 → 逾百万条，数字 **待核实**）。
- 方法要点：抽 skill → 源码体不可见的再生成 → 与源行为对照裁决 → 打检索标签；强调可核验与 provenance，而非纯营销 prompt 包。
- 可动手入口：HF 数据集 `ant-intl/DeveloperSkills-Code2Skill`；代码仓 `ant-intl/Code2Skill`（README 仍写 pre-release，公开程度 **待核实**）；项目页 developer-skill-hubs。星数/下载 **待核实**。

## 落地链接（可选）

- 数据集：https://huggingface.co/datasets/ant-intl/DeveloperSkills-Code2Skill
- 仓库：https://github.com/ant-intl/Code2Skill
- 项目页：https://ant-international-research.github.io/developer-skill-hubs/
- 论文：https://arxiv.org/abs/2609.05571

## 价值判断

- 为什么值得记：对准 Agent Skill 主线；有可下载数据集与可核对流水线说明，优于无落地的技能营销帖。
- 风险 / 待核实：出处为社区转；仓 README 称尚未正式开源发布，以 GitHub/HF 实际可见性为准；「百万 skill」与下游 Agent 增益数字待核实；LLM judge ≠ 程序等价证明。

## 原文摘要（可选）

摘要：@HuggingPapers 介绍 Code2Skill，称其能把海量开源仓转成逾百万条可复用、可核验的 Agent 程序技能。

## 与其他条目的关系（可选）

相对已入库 anthropics/skills、vercel/nvidia verified skills、State of agent skills 报告：本条是 **从代码合成 skill 数据/流水线**，不是某厂商官方 skills 包安装入口。禁开的「Scientific Agent Skills 仅社区 arxiv 转」不适用于本条（本条是通用程序 skill 合成，且有 HF 数据集落地）。
