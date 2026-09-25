# Pruna-Qwen-Image-2.1：少步 LoRA 加速 Qwen-Image 生成/编辑

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/PrunaAI/status/2103152549809311816
- 作者 / 频道：@PrunaAI
- 发布时间：2026-09-24 16:00:17 UTC（约 2026-09-25 00:00 CST）

## 要点

- 开源 **Pruna-Qwen-Image-2.1**：挂在 Qwen-Image-2.1 上的少步 LoRA 适配器，宣称把生成/编辑从约 40 步压到 5/8 步（加速倍数「待核实」）。
- 动手入口：HF `PrunaAI/Pruna-Qwen-Image-2.1`（Diffusers）；帖内 buff 链指向该模型卡；8 步适配器为推荐默认，支持文生图与最多三参考图编辑。
- 管线不变、按适配器使用优化 sigma、默认可关 CFG（以 README 为准）。

## 落地链接（可选）

- 模型：https://huggingface.co/PrunaAI/Pruna-Qwen-Image-2.1
- 官网：https://www.pruna.ai/

## 价值判断

- 为什么值得记：可下载的开源加速适配器，直接降低本地/自建图像 Agent 的采样成本。
- 风险 / 待核实：效果与「6.3×」宣传「待核实」；依赖基座 Qwen-Image-2.1 权重与许可；另有付费 API 入口，与开源卡区分清楚。

## 原文摘要（可选）

摘要：Pruna 宣布开源少步 LoRA，加速 Qwen-Image-2.1 的生成与多图编辑，并给出 Diffusers / API 两条试用路径。
