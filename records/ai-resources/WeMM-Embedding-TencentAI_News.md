# WeMM-Embedding：腾讯微信视觉开源多模态嵌入族

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/TencentAI_News/status/2095873481917505558
- 作者 / 频道：@TencentAI_News
- 发布时间：2026-09-04 13:55:52 UTC（约 2026-09-04 21:55 CST）

## 要点

- 腾讯微信视觉团队开源 **WeMM-Embedding** 通用多模态嵌入族：支持文本 / 图像 / 视频 / 视觉文档及交错输入，面向检索、搜索、推荐与分类。
- 官方称已在微信侧大规模流量验证；公开权重含 **2B / 4B / 9B**，宣称 9B 在 MMEB-v2 居前、2B 在低维截断下仍可检索（榜面数字 **待核实**）。
- 可动手：GitHub `Tencent/WeMM-Embedding`、HF 权重（如 `tencent/WeMM-Embedding-2B` 等），可用 SentenceTransformer 加载。

## 落地链接（可选）

- 仓库：https://github.com/Tencent/WeMM-Embedding
- HF 例：https://huggingface.co/tencent/WeMM-Embedding-2B
- 论文：https://arxiv.org/abs/2608.24053

## 价值判断

- 为什么值得记：新开源**多模态编码器/嵌入族**（非聊天 LLM），官方 X + 可下权重，补已入库 NeoMME 之外的另一条嵌入轴。
- 风险 / 待核实：仓库 ★约 1667（2026-09-26 `gh api`）；MMEB/吞吐与许可以模型卡为准；同引擎量化/Day-0 serving 帖勿跟。

## 原文摘要（可选）

摘要：@TencentAI_News 宣布 WeMM-Embedding 开源，强调真实流量验证、多模态按序编码与可截断维度检索。

## 与其他条目的关系（可选）

非已入库 NeoMME / LensVLM / Qwen-Image 等生成或表征条；本条是 **embedding 族**。非 vLLM/SGLang/LMDeploy 等 serving。
