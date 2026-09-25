# Mixture-of-Kittens（MoK）：Cursor 开源 NVL72 MoE 训练 megakernel

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/cursor_ai/status/2084670806613737919
- 作者 / 频道：@cursor_ai
- 发布时间：2026-08-04 16:00:26 UTC（约 2026-08-05 00:00 CST）

## 要点

- Cursor 开源 **Mixture-of-Kittens（MoK）**：面向 NVIDIA NVL72 的 **MoE 训练 megakernel**，把专家通信与计算融进单一、宣称全确定性的 kernel。
- 官称相对最强公开基线最高约 **2.37×**；生产千卡规模相对既有 DeepEP 栈约 **1.41×** 吞吐——数字 **待核实**。
- 可动手：GitHub `cursor/mixture-of-kittens` + Cursor 博客；仓库含与 DeepEP / NCCL / Transformer Engine 等对照的基准脚本（以 README 为准）。

## 落地链接（可选）

- 仓库：https://github.com/cursor/mixture-of-kittens
- 博客：https://cursor.com/blog/mixture-of-kittens

## 价值判断

- 为什么值得记：可核官号 + 开源训练侧 megakernel，补「MoE 通信融合」工具缺口；与 decode serving megakernel 不同轴。
- 风险 / 待核实：仓库 ★约 593（2026-09-26 `api.github.com`）；加速倍数依赖 NVL72 / 对照栈，消费级单卡不可直接复现；硬件门槛高。

## 原文摘要（可选）

摘要：@cursor_ai 宣布开源 MoK，称融合 MoE 通信与计算为单 kernel，相对公开基线最高约 2.37×。

## 与其他条目的关系（可选）

与本批候选 **Cohere Megakernel**（decode serving）同属 megakernel 话题，但本条是 **训练 / MoE dispatch 轴**。非 vLLM 等推理栈发版帖。
