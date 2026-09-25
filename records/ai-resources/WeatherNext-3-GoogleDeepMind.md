# WeatherNext 3：DeepMind 新一代全球天气 AI 模型（小时级/更高分辨率）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/GoogleDeepMind/status/2095528012791902536
- 作者 / 频道：@GoogleDeepMind
- 发布时间：2026-09-03 15:03:05 UTC（约 2026-09-03 23:03 CST）

## 要点

- Google DeepMind × Google Research 发布 **WeatherNext 3**：相对 WeatherNext 2，强调直接吃实时观测/地球静止卫星镶嵌、**约每小时**刷新，并把部分地表变量分辨率推到约 **5 km**（相对先前约 25 km / 6 小时档，数字 **待核实**）。
- 能力轴含降水、清洁能源相关变量（如约 100 m 风速、辐射/云量等）及更高时空一致性；官博称 Brightband 等独立实况评测领先（效果 **待核实**）。
- 可动手入口：Google for Developers 的 WeatherNext 模型文档；预报场可通过 BigQuery / Earth Engine / Cloud Storage 等查询或批量下载（以文档为准），并逐步接入 Search / Gemini / Maps 等产品。

## 落地链接（可选）

- 官博：https://blog.google/innovation-and-ai/models-and-research/google-deepmind/introducing-weathernext-3/
- 文档：https://developers.google.com/weathernext/guides/models

## 价值判断

- 为什么值得记：官帖 + 开发者文档/数据接入路径清晰；是气象 AI 基础设施更新，而非纯营销演示。
- 风险 / 待核实：分辨率/刷新/降水 CRPS 等宣传数字待核实；正式预警仍以各地气象台为准；Cloud/Earth Engine 计费与区域可用性待核实。

## 原文摘要（可选）

摘要：@GoogleDeepMind 介绍 WeatherNext 3，强调实时观测驱动、更高分辨率与更快刷新的全球天气预报。

## 与其他条目的关系（可选）

DeepMind 科学线与 AlphaGenome Atlas 同厂不同轴：本条是 **全球天气预报模型与数据产品**，不是基因组库。非已入库各类 LLM/Agent 评测或视频世界模型。
