# Qwen3.5-397B-A17B：通义开源 Qwen3.5 首发多模态 MoE 族

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/Alibaba_Qwen/status/2023331062433153103
- 作者 / 频道：@Alibaba_Qwen
- 发布时间：2026-02-16 09:38:11 UTC（约 2026-02-16 17:38 CST）

## 要点

- 通义官方发布 **Qwen3.5** 系列首个开源权重：**Qwen3.5-397B-A17B**（总参约 397B / 激活约 17B），原生多模态（视觉-语言），宣称面向真实 Agent 场景；Apache 2.0（以模型卡为准）。
- 架构要点：混合线性注意力（Gated DeltaNet）+ 稀疏 MoE；原生上下文约 262K、可扩展约 1M（以文档为准）；宣称相对 Qwen3-Max 解码吞吐 8.6×–19.0×、覆盖 201 语言/方言——效果与吞吐数字 **待核实**。
- 可动手：GitHub `QwenLM/Qwen3.5`、HF collection `Qwen/qwen35`（含 397B-A17B 等）、官方博客、Chat / ModelScope；同引擎 Day-0 / 第三方量化扩散帖勿跟。

## 落地链接（可选）

- 仓库：https://github.com/QwenLM/Qwen3.5（2026-09-26 访问会跳转到 `QwenLM/Qwen3.8`，★约 4177；以 HF 旗舰权重为主落地）
- HF 集合：https://huggingface.co/collections/Qwen/qwen35
- HF 旗舰：https://huggingface.co/Qwen/Qwen3.5-397B-A17B
- 博客：https://qwen.ai/blog?id=qwen3.5

## 价值判断

- 为什么值得记：官方可核的**新一代开源多模态 MoE 族**（非已入库 Qwen3-Coder / Qwen3-Omni / Qwen3-VL-Embedding / Qwen-Image），HF/GitHub 可下可装。
- 风险 / 待核实：HF 旗舰 likes 约 1560、downloads 约 20 万（Qwen3.5-397B-A17B，2026-09-26）；GitHub 入口现指向 Qwen3.8 仓 ★约 4177；榜面对比与云端 Plus 对应关系以官方文档为准；勿收同引擎 serving Day-0 扩散帖。

## 原文摘要（可选）

摘要：@Alibaba_Qwen 宣布开源 Qwen3.5-397B-A17B，强调原生多模态、混合线性注意力+稀疏 MoE、Agent 向 RL 与多语言，并给出 GitHub / HF / 博客入口。

## 与其他条目的关系（可选）

非 Qwen3-Coder / Qwen3-Omni / Qwen3-VL-Embedding / Qwen-Image-2.1；本条是 **Qwen3.5 基座多模态 MoE 族**。非 vLLM/SGLang 等 serving 帖。
