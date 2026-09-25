# Pipette：端侧模型评测套件（质量×速度×延迟×显存，联合 Artificial Analysis）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/liquidai/status/2091906366428598284
- 作者 / 频道：@liquidai
- 发布时间：2026-08-24 15:11:58 UTC（约 2026-08-24 23:11 CST）

## 要点

- Liquid AI 与 @ArtificialAnlys 发布 **Pipette**：面向手机/笔记本/PC/嵌入式等设备的开源评测套件，强调按「模型 + 量化 + 运行时 + 设备」组合度量质量、吞吐、延迟与内存，而非只看云端满精度分数。
- 开源组件：`pipette-mgmt`（目录与提交）、`pipette-clients`（含 iOS/Android 客户端）、`pipette-scores`（盲评打分）；另有 dashboard 与公开结果仓。
- 官称已有约 10k+ 已核结果、35 类模型、多种量化与 llama.cpp 路径；覆盖与方法论见文档。**星数 / 端侧数字待核实**。

## 落地链接（可选）

- 博客：https://www.liquid.ai/blog/pipette-on-device-ai-benchmarking-by-liquid-ai
- 管理端：https://github.com/Liquid4All/pipette-mgmt
- 客户端：https://github.com/Liquid4All/pipette-clients
- 打分服务：https://github.com/Liquid4All/pipette-scores

## 价值判断

- 为什么值得记：可核官帖 + 多仓开源入口，补「端侧部署组合」评测轴；非纯 PPT。
- 风险 / 待核实：`pipette-mgmt` ★约 6、`pipette-clients` ★约 46（2026-09-26）；跨设备对比有方法学边界；站点偶发限流。

## 原文摘要（可选）

摘要：@liquidai 宣布 Pipette 开源端侧评测套件，并与 Artificial Analysis 合作提供可复现的设备侧质量与性能测量。

## 与其他条目的关系（可选）

已入库 **LongevityBench / LFM2.5-VL-DSpark** 等 Liquid 条目侧重模型或领域评测；本条是 **通用端侧基准平台**。勿与 Artificial Analysis 云端 Intelligence Index 混为同一产品。
