# VQ-bench：Pinecone 开源的向量量化评测框架

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/pinecone/status/2102416782971769178
- 作者 / 频道：@pinecone
- 发布时间：2026-09-22 15:16:36 UTC（约 2026-09-22 23:16 CST）

## 要点

- Pinecone 宣布开源 **VQ-bench**：用来实现、组合并比较向量量化方法的评测框架。
- 仓库可克隆；README 写明用 `vqb data get` 拉取内置数据集，按召回、重构误差等指标跑量化器。站点 https://vq-bench.com 放当前榜。
- 与已入库的 FineWeb / Stack / SmolDataEnvs 不是同一数据集；也不是 SWE / Terminal 类软件工程榜。

## 落地链接（可选）

- 仓库：https://github.com/pinecone-io/vq-bench
- 博客：https://www.pinecone.io/blog/vq-bench/
- 榜站：https://vq-bench.com/

## 价值判断

- 为什么值得记：向量检索向的可下载评测框架，有仓、有数据拉取入口，能动手跑。
- 风险 / 待核实：pinecone-io/vq-bench ★2（2026-09-26 gh api）。榜上分数与论文效果待核实。依赖 Rust/`cargo` 工具链；数据集体积未在本条核过。

## 原文摘要（可选）

摘要：Pinecone 称 VQ-bench 用来测试和比较向量量化方法，并链到官方博客。

## 与其他条目的关系（可选）

非 FineWeb / The Stack / SmolDataEnvs。Pinecone 产品本身此前未入库。
