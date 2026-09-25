# PP-OCRv6：PaddleOCR 轻量多语 OCR 族（1.5M–34.5M）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/PaddlePaddle/status/2065299834756902995
- 作者 / 频道：@PaddlePaddle
- 发布时间：2026-06-12 05:07:06 UTC（约 2026-06-12 13:07 CST）

## 要点

- PaddlePaddle 官号发布 **PP-OCRv6**：通用 OCR 系列，规格 **Tiny 1.5M / Small 7.7M / Medium 34.5M**；宣称相对 PP-OCRv5 检测/识别提升与更快 CPU 推理——效果与速度 **待核实**。
- Small/Medium 宣称支持约 **50 语**；部署路径含 Paddle Inference、Transformers、ONNX Runtime（`pip install paddleocr`）——集成细节以文档为准。
- 可动手：HF Collection、PaddleOCR 文档/官网、官号帖文。

## 落地链接（可选）

- HF Collection：https://huggingface.co/collections/PaddlePaddle/pp-ocrv6-6a2950fe1a4f3063c35dae75
- HF 博客：https://huggingface.co/blog/PaddlePaddle/pp-ocrv6
- 官网：https://www.paddleocr.com

## 价值判断

- 为什么值得记：官号可核的**新开源轻量 OCR 族**（非已入库 jina-ocr-v1），HF/文档可动手；补端侧/多后端 OCR 入口。
- 风险 / 待核实：各子模型 HF likes 约十余至百余（medium_det 约 135，2026-09-26）；自报分数与复杂版面还原 **待核实**；勿与低价 OCR API/合租混淆。

## 原文摘要（可选）

摘要：@PaddlePaddle 宣布 PP-OCRv6 正式发布，给出 Tiny/Small/Medium 参数档与相对 v5 的精度/速度宣传。

## 与其他条目的关系（可选）

非 **jina-ocr-v1**（Jina 文档解析/OCR 权重）；本条是 **PaddleOCR PP-OCRv6 检测+识别族**。非 jina-embeddings-v5-omni / jina-reranker-v3.5。未开 Qwen3.8 / jina-v5-text。
