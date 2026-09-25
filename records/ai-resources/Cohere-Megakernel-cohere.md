# Cohere Megakernel：面向 North Mini Code 的开源 decode megakernel serving

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/cohere/status/2097410772355666393
- 作者 / 频道：@cohere
- 发布时间：2026-09-08 19:44:30 UTC（约 2026-09-09 03:44 CST）

## 要点

- Cohere 开源 **decode megakernel serving 引擎**：把整步 decode 收成单持久 CUDA kernel，宣称支持 continuous batching / paged attention / OpenAI 兼容端点与 tool calling。
- 面向已入库 **North Mini Code**（非新基座模型）：官称单卡 H100、BS=1 可达约 292 tok/s、相对 vLLM 最高约 **1.58×** decode；端到端约 **1.25×–1.41×**——吞吐与对照版本 **待核实**。
- 可动手：GitHub `cohere-ai/cohere-megakernel` + 技术博客；当前实现侧重 decode（prefill 仍常规 kernel；最大 batch 等限制以仓库/博客为准）。

## 落地链接（可选）

- 仓库：https://github.com/cohere-ai/cohere-megakernel
- 博客：https://cohere.com/blog/megakernels

## 价值判断

- 为什么值得记：官号可核的**新 serving 实现轴**（非 vLLM/SGLang/LMDeploy/Ollama/EXO/llama.cpp 发版帖），有仓库可 clone；补 North Mini Code「怎么更快伺候」入口。
- 风险 / 待核实：仓库 ★约 93（2026-09-26 `api.github.com`）；速度倍数相对 vLLM 版本与负载 **待核实**；主要为 North Mini Code / H100 BF16 路径，泛化到其他模型/GPU **待核实**；勿与已入库 North Small Translate 模型卡混淆。

## 原文摘要（可选）

摘要：@cohere 称发布首个以 decode megakernel 为核心的完整 serving 系统，相对 vLLM 最高约 1.58×，为 North Mini Code 构建且完全开源。

## 与其他条目的关系（可选）

同厂已入库 **North Mini Code**（模型权重/HF）；本条是 **serving / megakernel 引擎轴**，勿与模型卡重复。非已覆盖的 vLLM / SGLang / LMDeploy / Ollama / EXO / llama.cpp 发版帖。对照 Cursor **Mixture-of-Kittens**（训练侧 MoE megakernel）产品轴不同。
