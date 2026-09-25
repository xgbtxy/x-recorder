# jina-ocr-v1：开源视觉文档解析（PDF/扫描→Markdown）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/JinaAI_/status/2100617174985638364
- 作者 / 频道：@JinaAI_
- 发布时间：2026-09-17 16:05:36 UTC（约 2026-09-18 00:05 CST）

## 要点

- Jina 官号发布 **jina-ocr-v1**：视觉文档解析模型，宣称约 3.4B 总参 / 约 570M 激活，内置 speculative decoding；面向 PDF、扫描件、表格、图表、发票等，输出干净 Markdown——效果与速度 **待核实**。
- 入口宣称 HF 与 Jina Reader（`x-respond-with`）当日可用——API 形态 **待核实**。
- 可动手：HF `jinaai/jina-ocr-v1`、官号帖文与 Reader 文档入口。

## 落地链接（可选）

- HF：https://huggingface.co/jinaai/jina-ocr-v1

## 价值判断

- 为什么值得记：官号可核的**新开源 OCR/文档解析模型**（非已入库嵌入/生成族重复），HF 可下；补「复杂版面→Markdown」可动手入口。
- 风险 / 待核实：HF likes 约 171、downloads 约 5034（2026-09-26）；多语种与表格还原质量以自测/卡页为准；勿与低价 OCR API 合租引流混淆。

## 原文摘要（可选）

摘要：@JinaAI_ 宣布 jina-ocr-v1，强调总参/激活与 speculative decoding，并给出 HF 与 Reader 可用性。

## 与其他条目的关系（可选）

非 jina-embeddings-v5-omni / WeMM / Qwen-Image；本条是 **文档 OCR/解析权重**。未开 Qwen3.8。
