# Gemma 4 × Antigravity SDK：本地 LiteRT 离线/混合 Agent 运行入口

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/googledevs/status/2103157200139043291
- 作者 / 频道：@googledevs
- 发布时间：2026-09-24 16:18:45 UTC（约 2026-09-25 00:18 CST）

## 要点

- Google for Developers 宣布：在 **Antigravity SDK** 内可 **本地 on-device** 跑 **Gemma 4**（LiteRT），支持全本地或「云端模型 + 本地 Gemma 劳动力」混合多 Agent 工作流。
- 卖点轴是隐私与零 API 费用（算力门槛/具体型号 **待核实**）；配套文档说明 `pip install google-antigravity litert-lm` 与 `LiteRTAgentConfig` 配置。
- 可动手入口：Antigravity 本地模型文档 + Developers Blog；Edge/LiteRT-LM 的 Gemma 4 模型页。效果与 VRAM 需求 **待核实**。

## 落地链接（可选）

- Antigravity 本地模型文档：https://antigravity.google/docs/sdk/local-models/
- 博客：https://developers.googleblog.com/en/introducing-support-for-local-ai-models-in-the-antigravity-sdk/
- LiteRT-LM Gemma 4：https://ai.google.dev/edge/litert-lm/models/gemma-4

## 价值判断

- 为什么值得记：把已有开源权重接到官方 Agent SDK 的 **本地运行时**，补「可离线 Agent 开发」轴，不是重复发一遍权重。
- 风险 / 待核实：硬件门槛（公开材料提到较大显存/统一内存，以文档为准）；与云端配额/许可证条款；性能相对云端 Flash 的落差 **待核实**。

## 原文摘要（可选）

摘要：@googledevs 称 Gemma 4 已可在 Antigravity SDK 本地运行，支持全本地或混合多 Agent，底层为 LiteRT。

## 与其他条目的关系（可选）

同厂模型族：已入库 **Gemma-4** 是模型本身；本条是 **Antigravity SDK 本地 LiteRT 交付/Agent 运行入口**。勿与 Gemini 3.8 Live/Flash TTS、AlphaGenome Atlas Skills 或 Google Cloud Developer Plugin 混交。
