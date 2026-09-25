# LFM2.5-VL-3B-DSpark：Liquid 为 VL 模型开源的投机解码草稿模型

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/liquidai/status/2103131179100819783
- 作者 / 频道：@liquidai
- 发布时间：2026-09-24 14:35:22 UTC（约 2026-09-24 22:35 CST）

## 要点

- Liquid AI 发布实验性 **DSpark** 草稿模型，给 **LFM2.5-VL-3B** 做投机解码：轻量 drafter 多步猜测，目标模型一次校验，加速生成且宣称不改输出分布。
- 线程后续给出可动手权重：`LiquidAI/LFM2.5-VL-3B-DSpark` 与 GGUF；对接 llama.cpp / MLX-VLM / SGLang（相关 PR）；博客说明 VL 场景加速边界（编码/prefill 不受益）。
- 加速倍数（MLX / llama.cpp / SGLang）与 Pipette 评测细节 **待核实**。

## 落地链接（可选）

- 博客：https://www.liquid.ai/blog/lfm2-5-vl-dspark
- 权重：https://huggingface.co/LiquidAI/LFM2.5-VL-3B-DSpark
- GGUF：https://huggingface.co/LiquidAI/LFM2.5-VL-3B-DSpark-GGUF
- 线程续帖（权重与集成）：https://x.com/liquidai/status/2103131187216539690

## 价值判断

- 为什么值得记：可核官号 + HF 权重，补「VL 投机解码草稿模型」工具缺口；非又一个基座发版。
- 风险 / 待核实：实验性；端到端收益依赖解码占比；HF likes 约 14（DSpark）/ 8（GGUF）（2026-09-26）；需与目标 LFM2.5-VL-3B 联用。

## 原文摘要（可选）

摘要：@liquidai 称发布 LFM2.5-VL-3B 的 DSpark 草稿模型以启用投机解码，并在线程中给出 HF 与运行时集成链接。

## 与其他条目的关系（可选）

已入库 **LFM2.5-VL-3B** 为基座 VL；本条是其 **DSpark 草稿/加速组件**。非 vLLM/SGLang/Ollama 等 serving 发版帖（虽有 SGLang/llama.cpp 集成 PR）。
