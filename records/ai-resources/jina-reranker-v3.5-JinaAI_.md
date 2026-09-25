# jina-reranker-v3.5：开源 0.6B listwise 重排器

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/JinaAI_/status/2084288559435903485
- 作者 / 频道：@JinaAI_
- 发布时间：2026-08-03 14:41:31 UTC（约 2026-08-03 22:41 CST）

## 要点

- Jina 官号发布 **jina-reranker-v3.5**：约 0.6B listwise 重排器，延续 v3 的 query–候选同窗交互；宣称更快、更贴企业检索数据。
- 帖文自报 BEIR nDCG@10 约 63.20，并对比更大参数 reranker——榜面数字 **待核实**。
- 可动手：HF `jinaai/jina-reranker-v3.5`（及 GGUF/MLX 变体以卡页为准）。

## 落地链接（可选）

- HF：https://huggingface.co/jinaai/jina-reranker-v3.5

## 价值判断

- 为什么值得记：官号可核的**新开源重排模型**，与嵌入族互补；HF 可下，适合 RAG/Agent 检索栈落地。
- 风险 / 待核实：HF likes 约 43、downloads 约 3.0 万（2026-09-26）；BEIR 对比与延迟以自测/卡页为准；勿收量化扩散帖。

## 原文摘要（可选）

摘要：@JinaAI_ 宣布 reranker-v3.5，强调 0.6B listwise、速度与 BEIR 数字。

## 与其他条目的关系（可选）

非 jina-embeddings-v5-omni；本条是 **重排器权重**。未开 Qwen3.8。
