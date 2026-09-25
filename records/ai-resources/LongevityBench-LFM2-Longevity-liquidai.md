# LongevityBench + LFM2 Longevity：衰老生物学评测与紧凑领域模型

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/liquidai/status/2100608105444684181
- 作者 / 频道：@liquidai
- 发布时间：2026-09-17 15:29:34 UTC（约 2026-09-17 23:29 CST）

## 要点

- @liquidai 与 @InSilicoMeds 在 *Cell* 封面研究中发布 **LongevityBench**（17 项衰老生物学任务）以及两枚紧凑领域模型 **LFM2-1.2B-Longevity** / **LFM2-2.6B-Longevity**。
- 任务覆盖临床记录、DNA 甲基化、转录组、血浆蛋白组与遗传证据等结构化衰老数据解读；官帖称在相关任务上相对部分 frontier 模型有优势（效果 **待核实**）。
- 可动手入口：Hugging Face 模型卡与数据集 `insilicomedicine/longebench`；基座为已入库族 LFM2 / LFM2.5 的领域微调，非新通用底座。

## 落地链接（可选）

- 模型（1.2B）：https://huggingface.co/LiquidAI/LFM2-1.2B-Longevity
- 模型（2.6B）：https://huggingface.co/LiquidAI/LFM2-2.6B-Longevity
- 数据集 LongevityBench：https://huggingface.co/datasets/insilicomedicine/longebench
- Cell 论文入口：https://www.cell.com/cell/fulltext/S0092-8674(26)00999-2

## 价值判断

- 为什么值得记：官号可核帖 + 可下载权重/基准，补「生物衰老 × 小模型」评测与领域微调轴；相对纯营销更可动手。
- 风险 / 待核实：HF likes 约 48/49，数据集 likes 约 8（2026-09-26）；相对 Gemini/GPT/Claude 的 SOTA 表述为论文/官宣口径，独立复现 **待核实**；许可证为 Liquid LFM 条款（非宽松开源需留意）。

## 原文摘要（可选）

摘要：@liquidai 称与 Insilico 发布 LongevityBench（17 任务）及 LFM2-1.2B/2.6B-Longevity 两枚紧凑模型，并指向 *Cell* 封面文章。

## 与其他条目的关系（可选）

相对已入库 **LFM2.5-2.6B / LFM2.5-VL-3B / DSpark**：本条是 **衰老生物学领域微调 + 专用评测**，不是通用 VL/端侧 DSpark 产物，也非 Liquid Context 设备合作营销帖。
