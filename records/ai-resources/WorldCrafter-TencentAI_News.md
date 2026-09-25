# WorldCrafter：TencentARC 开源相机可控视频世界模型（隐式 3D 记忆）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/TencentAI_News/status/2102678781605691676
- 作者 / 频道：@TencentAI_News
- 发布时间：2026-09-23 08:37:42 UTC（约 2026-09-23 16:37 CST）

## 要点

- 腾讯 AI 新闻号介绍 **WorldCrafter**（TencentARC）：用相机位姿查询隐式 3D-aware memory，跳过显式 3D 重建，从单图或文本做场景漫游式视频生成。
- 开源权重分 **Base** 与蒸馏 **Fast**；当前示意分辨率约 384×640（以仓库/卡面为准）。
- 可动手：GitHub `TencentARC/WorldCrafter`、HF `TencentARC/WorldCrafter-Fast` / `WorldCrafter-Base`、项目页与 arXiv。

## 落地链接（可选）

- 仓库：https://github.com/TencentARC/WorldCrafter
- Fast 权重：https://huggingface.co/TencentARC/WorldCrafter-Fast
- Base 权重：https://huggingface.co/TencentARC/WorldCrafter-Base
- 项目页：https://drexubery.github.io/WorldCrafter/
- 论文：https://arxiv.org/abs/2609.24984

## 价值判断

- 为什么值得记：可核 X + GitHub/HF/论文齐全，属可复现的 **开源世界模型/长镜头视频** 工具，非纯产品 PPT。
- 风险 / 待核实：GitHub ★约 350、HF Fast likes 约 11 / Base likes 约 7（2026-09-26）；长时一致性与分辨率上限 **待核实**；新闻号转发研究作，非消费级 App 官宣。

## 原文摘要（可选）

摘要：@TencentAI_News 介绍 WorldCrafter 思路（隐式记忆替代 3D 重建），并指出 Base/Fast 权重已在 HF。

## 与其他条目的关系（可选）

相对已入库 **Hy4 preview**（大 MoE 文本）、**HunyuanImage 3.0**（图像生成开源）：本条是 **TencentARC 视频世界模型**，产品轴不同。勿当作 Hy Image3.5 同系列扩散微调再开一条。
