# AliceAI-Foundation-80B-A3B-Base：Yandex 开源 80B-A3B MoE 基座

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/yandexcom/status/2102050970939383810
- 作者 / 频道：@yandexcom
- 发布时间：2026-09-21 15:03:00 UTC（约 2026-09-21 23:03 CST）

## 要点

- Yandex 官方英语号发布 **AliceAI-Foundation-80B-A3B-Base**：从零预训练的混合架构 + MoE 基座；总参约 80B、每 token 激活约 3B；上下文宣称至 262144；Apache 2.0（以模型卡为准）。
- HF 模型卡提供 Transformers / vLLM 运行说明，并附俄语事实向内部基准（WikiWebFacts、HardMultiQA 等）与对比表——分数 **待核实**。
- 可动手：Hugging Face 权重与 README；官方称可配合 flash-linear-attention / 专用 vLLM 镜像；同引擎第三方量化扩散帖勿跟。

## 落地链接（可选）

- HF：https://huggingface.co/yandex/AliceAI-Foundation-80B-A3B-Base

## 价值判断

- 为什么值得记：官方可核的**新开源大底座**（非已入库 DeepSeek-V4 / Kimi-K2 / Mistral 3 / Olmo 3 等），HF 可下、许可证清晰。
- 风险 / 待核实：HF likes 约 333、downloads 约 2911（2026-09-26）；基座未做 alignment，生产前需自测；部分基准为内部俄语事实集，跨语泛化待核。

## 原文摘要（可选）

摘要：@yandexcom 宣布开源 Alice AI Foundation 80B-A3B Base 权重，强调 80B/3B MoE、256K 上下文与 Apache 2.0，并指向 Hugging Face。

## 与其他条目的关系（可选）

非 DeepSeek-V4 / Kimi K2 Thinking / Qwen3.5；本条是 **Yandex AliceAI 开源基座**。非 serving Day-0 帖。
