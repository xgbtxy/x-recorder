# Nemotron 3 Diarization：NVIDIA 开源实时说话人日志（≤8 人）

- 状态：已核
- 分类：ai-resources
- 记录日期：2026-09-26
- **平台**：X
- **来源（必填）**：https://x.com/NVIDIAAI/status/2102775666366435450
- 作者 / 频道：@NVIDIAAI
- 发布时间：2026-09-23 15:02:41 UTC（约 2026-09-23 23:02 CST）

## 要点

- NVIDIA AI 官号发布 **Nemotron 3 Diarization**：开源权重说话人日志模型，约 **100M** 参数，自称可跟踪「谁在何时说话」，支持最多 **8** 路说话人与重叠语音——DER / VoiceArena 榜单分数 **待核实**。
- 同一 checkpoint 覆盖离线与流式；推荐输入缓冲延迟约 0.32s–30.4s；输出为到达序说话人通道时间戳，再与 ASR 拼成带说话人标注的转写——协议以卡页/博客为准。
- 可动手：HF `nvidia/Nemotron-3-Diarization`、HF 博客、NeMo Speech / NeMo-Speech.cpp、Spaces 演示；OpenMDW 1.1。

## 落地链接（可选）

- HF：https://huggingface.co/nvidia/Nemotron-3-Diarization
- 博客：https://huggingface.co/blog/nvidia/nemotron-diarization
- Spaces：https://huggingface.co/spaces/nvidia/nemotron-diarization

## 价值判断

- 为什么值得记：官号可核的**新开源说话人日志族**（非通用 ASR/TTS 营销），HF 可下；补 NVIDIA Nemotron 语音侧可动手入口。
- 风险 / 待核实：HF likes 约 333（2026-09-26）；VoiceArena DER 自报、八人上限外场景与长录音退化 **待核实**；勿与第三方量化/合部署扩散帖混淆。

## 原文摘要（可选）

摘要：@NVIDIAAI 称多人同时说话时转写易乱，发布 Nemotron 3 Diarization，宣称最多八人、100M 参数，并指向 Hugging Face。

## 与其他条目的关系（可选）

同厂已入库 **Nemotron-3-Embed**（检索嵌入）与 **Nemotron-3.5-Lightning**（生成/Agent MoE）及 **Cosmos-3**；本条是 **说话人日志 / 多说话人时间戳轴**，勿与 Embed / Lightning 权重混淆。非 Granite Speech / VibeVoice-ASR / Qwen-Audio 云 API。未开 Qwen3.8 / jina-v5-text / Granite Speech。
