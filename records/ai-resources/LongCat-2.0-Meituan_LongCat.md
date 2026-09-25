# LongCat-2.0：美团开源 1.6T MoE Agent 向模型（约 48B 激活 / 1M 上下文）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Meituan_LongCat/status/2071783587205308721
- 作者 / 频道：@Meituan_LongCat
- 发布时间：2026-06-30 02:31:13 UTC（约 2026-06-30 10:31 CST）

## 要点

- 美团 LongCat 官号发布 **LongCat-2.0**：约 1.6T 参数 MoE、宣称约 48B 激活、原生约 1M 上下文；面向 agentic coding。
- 帖文宣称 LongCat Sparse Attention（LSA）、Zero-Compute Experts（动态约 33B–56B）、MOPD（Agent / Reasoning / Interaction 三组专家）——架构与效果数字 **待核实**。
- 榜面宣称 Terminal-Bench 2.1 约 70.8、SWE-bench Pro 约 59.5 等——**待核实**；可动手：HF、GitHub、技术博客 / 官网。

## 落地链接（可选）

- 仓库：https://github.com/meituan-longcat/LongCat-2.0
- HF：https://huggingface.co/meituan-longcat/LongCat-2.0
- 技术博客：https://longcat.chat/blog/longcat-2.0/
- 官网：https://longcat.ai/

## 价值判断

- 为什么值得记：官号可核的**新开源超大规模 MoE / Agent 向模型族**（非已入库 Qwen3.x / DeepSeek-V4 / MiniMax-M3 / Nex-N2.5 等），HF/GitHub 可下；补长上下文 coding Agent 权重入口。
- 风险 / 待核实：GitHub ★约 564（2026-09-26）；榜面对比与权重/许可以 HF 卡与仓库为准；部署门槛高；勿收同引擎 serving Day-0 / 第三方量化扩散帖。

## 原文摘要（可选）

摘要：@Meituan_LongCat 宣布 LongCat-2.0（1.6T MoE / ~48B 激活 / 1M 上下文），强调 agentic coding 与若干 coding / browse 榜面数字，并给出博客入口。

## 与其他条目的关系（可选）

非 Qwen3.5 / DeepSeek-V4 / MiniMax-M3 / Nex-N2.5 / Kimi-K3 / GLM-5.3 等已入库基座条；本条是 **美团 LongCat 自有开源 MoE 族**。非 vLLM/SGLang Day-0 帖。未开 Qwen3.8。
