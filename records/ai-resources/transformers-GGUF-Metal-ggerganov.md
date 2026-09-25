# Transformers 直跑 GGUF：接入 ggml Metal 内核

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/ggerganov/status/2102382619845410978
- 作者 / 频道：@ggerganov
- 发布时间：2026-09-22 13:00:51 UTC（约 2026-09-22 21:00 CST）

## 要点

- llama.cpp / ggml 作者 @ggerganov 宣布：可在 **Hugging Face Transformers** 中直接运行 GGUF，并把 ggml 的 **Metal** 内核带到 Transformers 生态，提升兼容与本地性能。
- 可动手文档：HF Blog「Transformers now runs llama.cpp quants」与 Transformers GGUF 文档；配合 `kernels` 等依赖按文档安装。
- 当前优化重心与架构覆盖（如部分 Qwen 等）以博客为准；速度相对原生 llama.cpp **待核实**。

## 落地链接（可选）

- 博客：https://huggingface.co/blog/transformers-llama-cpp-quants
- 文档：https://huggingface.co/docs/transformers/en/gguf
- GGUF 说明：https://github.com/ggml-org/ggml/blob/master/docs/gguf.md

## 价值判断

- 为什么值得记：可核作者帖 + 官方博客/文档，打通「GGUF 量化权重 ↔ Transformers 工作流」，属高频 AI 开发工具。
- 风险 / 待核实：平台/内核覆盖仍在演进；与已入库 llama.cpp 发版帖互补而非重复 serving 公告。

## 原文摘要（可选）

摘要：@ggerganov 称 Transformers 现可直跑 GGUF，并引入 ggml Metal 内核以提升兼容与性能。

## 与其他条目的关系（可选）

已入库 **llama-cpp v0.5.0** 等为运行时发版；本条是 **Transformers ↔ GGUF/Metal** 互操作层，不是又一次 llama.cpp 版本帖。
