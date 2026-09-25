# Nemotron 3 Embed：NVIDIA 开源检索嵌入族（8B/1B/NVFP4）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NVIDIAAI/status/2077786069840318800
- 作者 / 频道：@NVIDIAAI
- 发布时间：2026-07-16 16:02:57 UTC（约 2026-07-17 00:02 CST）

## 要点

- NVIDIA AI 官号发布 **Nemotron 3 Embed**：开源嵌入族，旗舰 **8B** 自称 RTEB 总榜 #1，另有 **1B BF16** 与 **1B NVFP4**——榜单名次与分数 **待核实**。
- 叙事面向 RAG / agentic retrieval / 长文与代码检索；宣称约 32k 上下文、多语与代码检索、开放权重与微调/蒸馏配方——能力边界 **待核实**。
- 可动手：HF（`nvidia/Nemotron-3-Embed-8B-BF16` 等）、HF 博客；NIM/合作云入口以卡页为准。

## 落地链接（可选）

- HF 8B：https://huggingface.co/nvidia/Nemotron-3-Embed-8B-BF16
- HF 1B：https://huggingface.co/nvidia/Nemotron-3-Embed-1B-BF16
- HF NVFP4：https://huggingface.co/nvidia/Nemotron-3-Embed-1B-NVFP4
- 博客：https://huggingface.co/blog/nvidia/nemotron-3-embed-wins-rteb

## 价值判断

- 为什么值得记：官号可核的**新开源嵌入族**（非已入库 WeMM / Qwen3-VL-Embedding / jina-embeddings-v5-omni），HF 可下；补 NVIDIA 检索侧入口。
- 风险 / 待核实：HF likes 约 101（8B）/ 154（1B）/ 80（NVFP4）（2026-09-26）；RTEB/LMEB 等自报 **待核实**；许可以卡页为准；勿收 serving Day-0 / 第三方量化扩散帖。

## 原文摘要（可选）

摘要：@NVIDIAAI 宣布 Nemotron 3 Embed 8B 发布并宣称 RTEB 总榜第一，强调更好检索对 Agent 上下文的帮助。

## 与其他条目的关系（可选）

同厂已入库 **Nemotron-3.5-Lightning**（生成/Agent 执行 MoE）与 **Cosmos-3**（Physical AI）/ nvidia-verified-agent-skills；本条是 **嵌入/检索产品轴**，勿与 Lightning 权重混淆。非 jina-embeddings-v5-omni / WeMM / Qwen3-VL-Embedding。未开 Qwen3.8 / jina-v5-text。
