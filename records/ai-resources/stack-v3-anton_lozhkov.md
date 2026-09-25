# The Stack v3：开源代码预训练数据集（~5T tokens）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-25
- **平台**：X
- **来源（必填）**：https://x.com/anton_lozhkov/status/2080254608639701222
- 作者 / 频道：@anton_lozhkov（Hugging Face）
- 发布时间：2026-07-23 11:32:02 UTC（约 2026-07-23 19:32 CST）

## 要点

- 作者宣布 **The Stack v3**：声称约 114 TB 原始、224M 仓库、~5T 近去重过滤 token；相对 v2（~550B tokens）显著扩大。
- 相对 v2 的可动手变化：源码 **inline**（不再只给 Software Heritage ID），可直接 `load_dataset`；提供 `stack-v3-train`（过滤/PII 脱敏）与 `stack-v3-full`（114 TB 全量桶，含 cluster ID 便于自研过滤）。
- 许可口径：数据集 ODC-By，下游仍须遵守各文件原许可；作者称不含限制性许可代码。规模/质量「待核实」。

## 落地链接（可选）

- 训练集：https://huggingface.co/datasets/HuggingFaceCode/stack-v3-train
- 全量桶：https://huggingface.co/buckets/HuggingFaceCode/stack-v3-full

## 价值判断

- 为什么值得记：非 FineWeb/SmolDataEnvs 的新代码预训练数据入口，可直接下载动手。
- 风险 / 待核实：星数/「最大」宣传待核实；`no_license` 与隐私残留需自审；全量桶可能含密钥/PII。

## 原文摘要（可选）

摘要：Anton 对比 Stack v2→v3 规模，强调自包含源码与 train/full 双入口。
