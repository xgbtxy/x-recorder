# NeoMME：H Company 开源多模态原生编码器族（+ Visual RAG Retriever）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/hcompany_ai/status/2098040121547182154
- 作者 / 频道：@hcompany_ai
- 发布时间：2026-09-10 13:25:19 UTC（约 2026-09-10 21:25 CST）

## 要点

- H Company 开源 **NeoMME** 族：260M / 800M **多模态原生、多语言** foundation encoder，单塔双向 Transformer 直接处理文本 token 与原始 image patch（无独立预训练 vision tower / 因果 LM）。
- 同步发布 **NeoMME-Retriever**：基于 NeoMME 骨干的 Visual RAG 文档检索器，把 PDF 页当图像编码（免 OCR），一次前向同时给出 dense 与 late-interaction 向量。
- 宣称两侧 retriever 规模落在 ViDoRe v3 模型规模帕累托前沿；同设置下 260M 约 51 pages/s（对照数字 **待核实**）。权重 Apache 2.0，day-0 Transformers。

## 落地链接（可选）

- 公告帖：https://x.com/hcompany_ai/status/2098040121547182154
- 作者技术线程：https://x.com/tonywu_71/status/2095501116033126584
- 论文：https://arxiv.org/abs/2609.01657
- HF 博客：https://huggingface.co/blog/Hcompany/neomme
- HF 例：https://huggingface.co/Hcompany/NeoMME-260M 、https://huggingface.co/Hcompany/NeoMME-800M 、https://huggingface.co/Hcompany/NeoMME-260M-Retriever 、https://huggingface.co/Hcompany/NeoMME-800M-Retriever

## 价值判断

- 为什么值得记：新开源**编码器/检索**模型族（非生成式 LLM 扩散），官方 X + 可下权重 + Transformers day-0，补已入库 Gemma/Mistral/Olmo/MiMo 等生成族之外的多模态表征轴。
- 风险 / 待核实：HF likes（约，2026-09-26 抽查）NeoMME-260M 16 / 800M 8 / Retriever 系列约 4–10；ViDoRe / 页吞吐数字待核对；许可以模型卡为准；同引擎量化/Day-0 serving 帖勿跟。

## 原文摘要（可选）

摘要：@hcompany_ai 宣布 NeoMME（260M/800M）与 NeoMME-Retriever，面向 Visual RAG，Apache 2.0 开源并宣称 ViDoRe v3 帕累托表现。

## 与其他条目的关系（可选）

非已入库 LensVLM / FLUX / Qwen-Image / Muse Glimmer 等；本条是 **encoder+retriever 族**，非聊天 LLM。
