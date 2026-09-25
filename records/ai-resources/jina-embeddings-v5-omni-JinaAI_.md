# jina-embeddings-v5-omni：开源全模态嵌入族（文本/图/音/视频）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/JinaAI_/status/2054226262047301933
- 作者 / 频道：@JinaAI_
- 发布时间：2026-05-12 15:44:41 UTC（约 2026-05-12 23:44 CST）

## 要点

- Jina 官号发布 **jina-embeddings-v5-omni**：面向文本、图像、音频、视频的统一嵌入空间；两档 small（约 1.57B / 1024-dim / 32K）与 nano（约 0.95B / 768-dim / 8K），宣称支持 Matryoshka 截断至 32 维——规格与效果 **待核实**。
- 宣称与既有 `jina-embeddings-v5-text-*` 文本向量字节级兼容（无需重建文本索引即可叠加多模态检索）——兼容性 **待核实**。
- 可动手：HF（`jinaai/jina-embeddings-v5-omni-small` 等）、官方新闻页、Jina Embedding API / Elasticsearch 入口。

## 落地链接（可选）

- HF small：https://huggingface.co/jinaai/jina-embeddings-v5-omni-small
- HF collection：https://huggingface.co/collections/jinaai/jina-embeddings-v5-omni
- 新闻：https://jina.ai/news/jina-embeddings-v5-omni-multimodal-embeddings-for-text-image-audio-and-video/

## 价值判断

- 为什么值得记：官号可核的**新开源全模态嵌入族**（非已入库 WeMM-Embedding / Qwen3-VL-Embedding / NeoMME），HF 可下；补图/音/视频检索底座入口。
- 风险 / 待核实：HF likes 约 152、downloads 约 37 万（jina-embeddings-v5-omni-small，2026-09-26）；许可宣称偏 CC BY-NC——商用条款需自核；榜面对比与 VRAM 以 HF/新闻为准；勿收第三方量化扩散帖。

## 原文摘要（可选）

摘要：@JinaAI_ 宣布 v5-omni，给出 small/nano 规格与 Matryoshka，并强调相对 v5-text 的文本索引向后兼容。

## 与其他条目的关系（可选）

非 WeMM-Embedding / Qwen3-VL-Embedding / NeoMME；本条是 **Jina v5 全模态嵌入族**。非 serving 引擎 Day-0。未开 Qwen3.8。
