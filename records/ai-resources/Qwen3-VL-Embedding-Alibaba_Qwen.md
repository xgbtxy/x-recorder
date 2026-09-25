# Qwen3-VL-Embedding：通义开源多模态嵌入 + Reranker 族

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Alibaba_Qwen/status/2009264754917863924
- 作者 / 频道：@Alibaba_Qwen
- 发布时间：2026-01-08 14:03:42 UTC（约 2026-01-08 22:03 CST）

## 要点

- 通义官方发布 **Qwen3-VL-Embedding** 与配套 **Qwen3-VL-Reranker**（各 2B / 8B）：基于 Qwen3-VL，面向多模态检索与跨模态理解；支持文本 / 图像 / 截图 / 视频及混合输入，宣称 30+ 语言。
- 两阶段管道：Embedding 做统一向量召回（宣称可自定义维度，如 64–4096，以模型卡为准），Reranker 对 (query, document) 打相关性分精排；效果数字 **待核实**。
- 可动手：GitHub `QwenLM/Qwen3-VL-Embedding`、HF 权重（Embedding / Reranker 2B·8B）、官方博客与技术报告；Apache 2.0（以模型卡为准）。

## 落地链接（可选）

- 仓库：https://github.com/QwenLM/Qwen3-VL-Embedding
- HF Embedding-8B：https://huggingface.co/Qwen/Qwen3-VL-Embedding-8B
- HF Embedding-2B：https://huggingface.co/Qwen/Qwen3-VL-Embedding-2B
- 博客：https://qwen.ai/blog?id=qwen3-vl-embedding
- 论文：https://arxiv.org/abs/2601.04720

## 价值判断

- 为什么值得记：官方可核的**新多模态嵌入/重排族**（非聊天 LLM），补已入库 WeMM-Embedding / NeoMME 之外的通义检索轴；HF 可下、仓库可装。
- 风险 / 待核实：仓库 ★约 1387（2026-09-26 `gh api`）；HF likes Embedding-8B/2B 约 483/457（同日 HF api）；榜面 SOTA 与云 API 进度待核实；同引擎 Day-0 / 第三方量化帖勿跟。

## 原文摘要（可选）

摘要：@Alibaba_Qwen 宣布开源 Qwen3-VL-Embedding 与 Reranker，强调多模态输入、多语言与两阶段检索，并指向 HF / GitHub / ModelScope。

## 与其他条目的关系（可选）

非 WeMM-Embedding / NeoMME / Qwen3-Omni / Qwen-Image；本条是 **VL 嵌入+重排** 族。非 vLLM/SGLang 等 serving Day-0 扩散帖。
